Actual use of Interface
http://java67.blogspot.in/2014/02/what-is-actual-use-of-interface-in-java.html

object SimplePatternMatch {

  def matchTest(num : Int) = {
    num match{
      case 1 => "Yes"
      case 0 => "No"
      case _ => "Invalid"
    }
  }


  def main(args: Array[String]): Unit = {

    println(matchTest(1))
    println(matchTest(0))
    println(matchTest(23))
  }
}



object PMGuard {
  def matchTest(num: Int) = {
    num match {
      case 1 | 0      => "Yes"
      case n if n < 0 => "No"
      case _          => "Invalid"
    }
  }

  def main(args: Array[String]): Unit = {

    println(matchTest(1))
    println(matchTest(0))
    println(matchTest(2))
    println(matchTest(-1))
 
  }
}


object PMAny {

  def matchTest(myList: List[Any]) {

    for (e <- myList){
      e match {
        case s: String => println("String")
        case i: Int    => println("Integer")
        case c: Char   => println("Character")
        case d: Double => println("Double")
      }
    }
  }

  def main(args: Array[String]): Unit = {
    matchTest(List("Hello", 12, 'A', 22.34, "Bye", 'b'))
  }
}



object PMOption {
  def toInt(s: String): Option[Int] = {
    try {
      Some(Integer.parseInt(s))
    } catch {
      case e: NumberFormatException => None
    }
  }

  def matchTest(s: String) {
    toInt(s) match {
      case Some(s) => println(s)
      case None    => println("Not an integer")
    }
  }

  def main(args: Array[String]): Unit = {
    for (str <- List("2", "two", "three", "4")) {
      matchTest(str)
    }

    println(List("2", "two", "three", "4").flatMap { toInt }.sum)
  }

}