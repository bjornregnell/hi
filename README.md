# Hello World using Scala

This is a minimal Scala app that runs everywhere if you have a JVM with Java 17 or higher installed. 

It prints "Hello world!" in terminal using this Scala program:
```scala
@main def run = println("Hello world!")
```

# How to run?

Use one of these methods:

1. [Download hi.jar](https://github.com/bjornregnell/hi/releases/download/v1/hi.jar) or build `hi.jar` as described below, and then run in terminal: 
    ```
    java -jar hi.jar
    ```
2. If you are on linux you can run it as `./hi.jar` after you have made it executable with 
`chmod +x hi.jar`

3. If you have [scala-cli](https://scala-cli.virtuslab.org/install) installed then you can run this in terminal:
    ```
    scala-cli run hi.scala
    ```

# How to build?
* Clone this repo or download zip of repo and unpack.

* Install [scala-cli](https://scala-cli.virtuslab.org/install) and then run this in terminal:
```
scala-cli --power package hi.scala -o hi.jar --assembly
```

# How to run it on your android phone?

* Install F-droid on your phone from here: https://f-droid.org/

* Search for "Termux Terminal emulator with packages"  from within F-droid and install it.

* Open the Termux app and do these commands:
```
pkg install openjdk-17
pkg install wget
wget https://github.com/bjornregnell/hi/releases/download/v1/hi.jar
chmod +x hi.jar
./hi.jar
```
:tada: 

Now you know how to make and run terminal apps on your android phone yourself using Scala!!