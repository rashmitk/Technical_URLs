======================================================================
Language                                 Year                 Inventor
Lamda Calculus                           1929                 Alonzo Church
FORTRAN(Formula Translating System)      1957                 John Backus & IBM
LISP (List Processing)                   1958                 John McCarthy
COBOL(Common Business Oriented Lang)     1959                 US Dept of Defense
C Language                               1972                 Dennis Ritchie
C++                                      1983                 Bjourn StrouStrup
JAVA                                     1995                 James Gosling & Sun Microsystem
Scala (Scalable Language)                2003                 Martin Odersky
======================================================================

List of Scala book

Programming in Scala by Martin Odersky
Scala In Action
Scala Cookbook
Programming Scala by Venkat Subramaniam
Scala for Impatient
Beginning Scala - 1st edition
Beginning Scala - 2nd edition

Free eBook Downloads

1. Scala for Impatient by Cay Horstmann
logic.cse.unt.edu/tarau/teaching/scala_docs/scala-for-the-impatient.pdf

2. Programming in Scala by Martin Odersky 2nd edition
ccfit.nsu.ru/~den/Scala/programming_in_scala_2nd.pdf

3. Scala By Example by Martin Odersky
www.scala-lang.org/docu/files/ScalaByExample.pdf

4. Programming Scala by Venkat Subramaniam
https://www.ebooks-it.net/ebook/programming-scala (Best site to download free pdf ebook)

http://barbie.uta.edu/~jli/Resources/Resource%20Provisoning&Performance%20Evaluation/84.pdf

5. Scala cookbook pdf download
www.bigdataanalyst.in/wp-content/uploads/2015/07/Scala-Cookbook.pdf



Videos

-Search on Youtube with 'Scala or Functional Programming by Venkat Subramaniam'  - You will get various video by Venkat Subramaniam, Awesome way of teaching and superb presentation skill.

https://www.youtube.com/watch?v=LH75sJAR0hc
http://nofluffjuststuff.com/conference/speaker/venkat_subramaniam (various videos from Venkat)

Joy of Functional Programming
https://www.youtube.com/watch?v=__dDAD0Y_WU



Online Blogs and Tutorials

------------------------------------
Online Scala REPL:

http://www.simplyscala.com/
------------------------------------

Various Scala important concepts tutorial on JavaBeat easy way
http://www.javabeat.net/tag/scala/

https://www.cs.helsinki.fi/u/wikla/OTS/Sisalto/examples/index.html (Too good link, by Martin Odersky)

http://www.scala-lang.org/api/2.11.4/index.html#scala.collection.immutable.List (Good Examples for every scala function)

https://twitter.github.io/scala_school/collections.html

http://www.javacodegeeks.com/2011/11/scala-tutorial-code-blocks-coding-style.html (good list of tutorials)

docs.scala-lang.org/tutorials/
http://en.wikibooks.org/wiki/Scala
http://tutorials.jenkov.com/scala/overview.html
https://twitter.github.io/scala_school/

http://www.tutorialspoint.com/scala/scala_overview.htm
http://javarevisited.blogspot.in/2014/01/top-5-free-books-to-learn-scala-programming-PDF.html
http://docs.scala-lang.org/tutorials/tour/tour-of-scala.html

https://twitter.github.io/scala_school/basics.html
http://www.artima.com/pins1ed/indexP.html


Blogs and Tutorials:
http://www.scala-lang.org/what-is-scala.html


Sanaulla blogs on Scala

http://blog.sanaulla.info/category/scala-4/
val vs var in scala :
http://blog.sanaulla.info/2009/07/02/val-versus-var-in-scala/

Brief Overview of An "Object" and "class" in Scala
http://java.dzone.com/articles/brief-overview-object-scala

Scala Functions - Very good one
http://www.tutorialspoint.com/scala/scala_functions.htm

Scala Function vs Method
https://softwarecorner.wordpress.com/2013/09/06/scala-methods-and-functions/

http://www.codecommit.com/blog/scala/roundup-scala-for-java-refugees

cheatsheet :
http://mbonaci.github.io/scala/#scala-type-hierarchy


Scala CI - Code coverage and quality
http://blog.knoldus.com/2013/07/09/building-quality-into-scala-development/


10 Oneliners to impress about Scala
https://mkaz.github.io/2011/05/31/10-scala-one-liners-to-impress-your-friends/

Good examples of Scala features


http://www.javacodegeeks.com/2011/10/scala-tutorial-iteration-for.html
http://www.javacodegeeks.com/2011/10/scala-tutorial-maps-sets-groupby.html
http://www.javacodegeeks.com/2011/10/scala-tutorial-objects-classes.html
http://www.javacodegeeks.com/2011/10/scala-tutorial-scalaiosource-accessing.html

http://www.nurkiewicz.com/2012/04/secret-powers-of-foldleft-in-scala.html
http://alvinalexander.com/scala/scala-reduceleft-examples
http://www.codecommit.com/blog/scala/quick-explanation-of-scalas-syntax
https://lizdouglass.wordpress.com/2010/12/15/scala-singleton-objects/



What is function in mathematical way :
https://www.mathsisfun.com/sets/function.html
http://alvinalexander.com/scala/best-practice-think-expression-oriented-programming-eop

Val vs Lazy Val
https://stackoverflow.com/questions/7484928/what-does-a-lazy-val-do/7484933#7484933


Traits

Read traits from Scala cookbook

http://www.nurkiewicz.com/2013/04/scala-traits-implementation-and.html (Secret how traits transformed under the hood in java)

http://jim-mcbeath.blogspot.in/2009/08/scala-class-linearization.html

http://www.javabeat.net/traits-scala/
http://www.javabeat.net/traits-scala-advanced-concepts/
https://techvivek.wordpress.com/2009/10/16/multiple-inheritence-in-scala-with-trait-mixin/

http://www.codeproject.com/Articles/897624/Differences-Between-Scala-and-Java-Part -Very good comparison of Java n Scala especially at Default method and trait explanation

http://alvinalexander.com/scala/scala-trait-examples
http://www.artima.com/scalazine/articles/stackable_trait_pattern.html - Dont miss the understanding of Stackable Trait Pattern

apply() and update() - Syntactic Sugar
http://naildrivin5.com/scalatour/wiki_pages/AdvancedScalaObjects/

Some,None and Option
http://alvinalexander.com/scala/using-scala-option-some-none-idiom-function-java-null

Implicit in Scala
http://alvinalexander.com/scala/scala-2.10-implicit-class-example

Package Object
http://www.scala-lang.org/docu/files/packageobjects/packageobjects.html

Function Literals
http://docs.scala-lang.org/tutorials/tour/anonymous-function-syntax.html

-----------------------------------------------------------------------------------------------------------------------
Some examples

File Reading :

val lines = Source.fromFile("C:\\Temp.txt").getLines()
lines.foreach(println)


FunctionalProgramming is programming paradigm or style where functions and not objects or procedures are used as the fundamental building blocks of a program. In Functional programming, function evaluates the expression based on the input value and generate the same output value every time the same input value is passed to it which is called pure function or side effect free evaluation. Functional Programming promotes immutability e.g. eliminating changing state.
