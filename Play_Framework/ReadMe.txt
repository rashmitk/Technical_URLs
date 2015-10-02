Books:

Learning Play Framework 2 by Packt publishing is one of the good book for learning Play Framework.

Video Tutorials

https://vimeo.com/58969923
https://vimeo.com/78892176

Blogs and Tutorials URLs

Slick with Play Framework
http://queirozf.com/entries/scala-slick-simple-example-on-connecting-to-a-postgresql-database

Play application deployment
http://alvinalexander.com/scala/play-framework-deploying-application-production-server

https://www.playframework.com/documentation/1.2/deployment

(How to deploy Play web application on CD or other server)
https://www.playframework.com/documentation/2.4.x/Production

Presentation slides
https://speakerdeck.com/spinscale/play-framework-introduction



Known Issues :

1. I encountered one issue that play-2.2.6 doesn't work with sbteclipse 4.0.0 and gives error while using 'play new' command. Thus I've to update the sbteclipse plugin to 3.0.0 and now the play framework works fine now. 

addSbtPlugin("com.typesafe.sbteclipse" % "sbteclipse-plugin" % "3.0.0")