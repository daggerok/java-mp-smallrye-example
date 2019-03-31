# Smallrye MicrpProfile [![Build Status](https://travis-ci.org/daggerok/java-mp-smallrye-example.svg?branch=master)](https://travis-ci.org/daggerok/java-mp-smallrye-example)
Example of java micro-profile example using smallrye

## maven

```bash
mvn clean package exec:java -Dexec.mainClass=com.github.daggerok.App
```

## gradle

### fatJar gradle task

```bash
./gradlew fatJar
java -jar ./build/libs/*-all.jar
```

### application gradle plugin

```bash
./gradlew installDist
bash ./build/install/java-mp-smallrye-example/bin/java-mp-smallrye-example
```

links:

* [MicroProfile starter](https://start.microprofile.io/index.xhtml)
* [SmallRye Reactive Messaging](https://smallrye.io/smallrye-reactive-messaging/#_quickstart)
* [Logback reference](https://logback.qos.ch/manual/configuration.html)
* [Lightbend MicroProfile Reactive Messaging](https://github.com/lightbend/microprofile-reactive-messaging)
* [Gradle fatJar task](https://gist.github.com/Renkai/58ec2272f3d614baa8fdb4e3778481a1#gistcomment-2876927)
