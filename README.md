# Hello World using Scala

This is a minimal Scala app that runs everywhere if you have a JVM with Java 17 or higher installed. 

It prints "Hello world!" in terminal using this Scala program:
```scala
@main def run = println("Hello world!")
```
 
# How to run?

If you have built a jar:

`./helloworld.jar`

Or:

`scala-cli run helloworld.scala`

# How to build?

`scala-cli --power package helloworld.scala -o helloworld.jar --assembly`
