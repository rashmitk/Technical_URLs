Video

https://www.youtube.com/watch?v=LKkw140QmyU
https://www.youtube.com/watch?v=V2rl62CZPVc
https://www.youtube.com/watch?v=DxrLPZD1Hxw&index=5&list=PLCVV85RZ-3pieWmC04bOBULPyNeg5xqEC


Presentation Slides

SBT
http://www.slideshare.net/dgalichet/simple-build-tool-10290583

Gradle vs Maven vs SBT
http://www.slideshare.net/fabiofumarola1/3-maven-gradle-and-sbt


Tutorials & Blogs


http://www.bks2.com/blog/2013/02/23/zero-to-a-scala-sbt-project/
http://www.scala-sbt.org/0.13/tutorial/index.html

Community plugins
http://www.scala-sbt.org/0.13/docs/Community-Plugins.html

Configuring sonarqube with SBT
http://blog.knoldus.com/2015/06/27/configuring-sonarqube-with-scoverage-plug-in-the-complete-guide/


Multi Module SBT project
http://xerial.org/blog/2014/03/26/buidling-multi-module-projects-in-sbt/



SBT vs Gradle
http://rgoulter.com/blog/posts/programming/2015-01-19-gradle-or-sbt.html

Ant vs Maven vs Gradle
http://technologyconversations.com/2014/06/18/build-tools/
(below url talks abt XML vs DSL)
http://zeroturnaround.com/rebellabs/java-build-tools-maven-gradle-and-ant-plus-the-dsl-vs-xml-debate/

Make vs Ant vs Maven
http://grokcode.com/538/java-build-systems-a-sad-state-of-affairs/

Build tool history along with Scala
http://brizzled.clapper.org/blog/2009/02/12/a-scala-build-tool/

Apache Maven History
http://informatics-sapm.blogspot.in/2013/03/maven-love-it-or-hate-it-tool.html

Ant, Maven and then Gradle - Evolution etc explained very well
http://www.drdobbs.com/jvm/why-build-your-java-projects-with-gradle/240168608

Polygot Maven (convert your existing pom.xml to ruby, groovy, scala and yaml)
http://takari.io/2015/03/21/polyglot-maven.html



-------
POC
-------

1. Creating eclipse project using 'eclipse' command on SBT command prompt

Created plugins folder inside C:\Users\rashmitr\.sbt\0.13 and placed following code inside it

addSbtPlugin("com.typesafe.sbteclipse" % "sbteclipse-plugin" % "4.0.0")

Now go to your HelloWorld project root and execute with command 'eclipse', It'll create complete eclipse project for you.

2. SBT Project folder structure
HelloWorld
 
 src/main/java
 src/main/scala
 src/main/resources
 
 src/test/java
 src/test/scala
 src/test/resources


3. How to publish your artifacts to maven
http://www.scala-sbt.org/0.13/docs/Publishing.html

4. jacoco plugin and related config
(https://github.com/sbt/jacoco4sbt)

Copy following to project/plugins.sbt
 addSbtPlugin("de.johoop" % "jacoco4sbt" % "2.1.6")
Copy following to build.sbt
jacoco.settings

5. Scalastyle static code analysis
http://www.scalastyle.org/sbt.html

6. Sonarqube configuration in SBT
http://blog.knoldus.com/2015/06/27/configuring-sonarqube-with-scoverage-plug-in-the-complete-guide/

7.SBT SCoverage Integration

https://github.com/scoverage/sbt-scoverage

8. Tasks to compile in SBT
clean compile test coverage it:test coverageReport
clean compile test coverage it:test coverageReport scalastyle



9. Gatling integration
http://gatling.io/docs/2.1.5/extensions/sbt_plugin.html


10. ScalaTestintegration
http://scalatest.org/quick_start (details of dependency available there)
http://www.scalatest.org/user_guide/writing_your_first_test

11. Flyway integration
http://flywaydb.org/getstarted/firststeps/sbt.html

12. Scapgoat Integration
https://github.com/sksamuel/sbt-scapegoat

13. Selenium Integration
http://www.hascode.com/2013/01/a-short-introduction-to-scalatest/

14 CI Tool for Scala code quality
http://blog.knoldus.com/2013/07/09/building-quality-into-scala-development/
