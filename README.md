# Hello World using Scala

This is a minimal Scala app that runs everywhere if you have a JVM with Java 17 or higher installed. 

It prints "Hello world!" in terminal using this Scala program:
```scala
@main def run = println("Hello world!")
```
 
# How to run?

Run using the `java` command:

```
java -jar hi.jar
``````

Or if the jar is made executable with `chmod +x hi.jar` on linux:

```
./hi.jar
``````

Or if you have [scala-cli]() installed:

```
scala-cli run hi.scala
``````

# How to build?

If you have [scala-cli]() installed:

```
scala-cli --power package helloworld.scala -o helloworld.jar --assembly`
```

# How to run it on your Android phone?

1. Install F-Droid from here: https://f-droid.org/  
  (you need to allow your browser to install unknown apps)

2. Search for in F-droid for "Termux Terminal emulator with packages" and install it by pressing the down-arrow in F-Droid
  (you need to allow F-droid to install unknown apps)

3. Open Termux and type this by the `$` prompt:
    ```
    pkg install openjdk-17
    pkg install wget
    wget https://github.com/bjornregnell/hi/releases/download/v1/hi.jar
    chmod +x hi.jar
    ./hi.jar
    ```

Con gratulations!! You now know how to run your own Scala terminal apps on your Android phone! 

It is pretty cool:

![hi-on-android.jpg](https://github.com/bjornregnell/hi/blob/main/hi-on-android.jpg)