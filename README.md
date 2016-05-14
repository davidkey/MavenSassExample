# Maven Sass Example #
[![Build Status](https://travis-ci.org/davidkey/MavenSassExample.svg?branch=master)](https://travis-ci.org/davidkey/MavenSassExample)

### What is this repository for? ###

A working (albeit very simple) example of maven-generated sass->css during build process. I used Spring Boot for this example.

### How do I get set up? ###
```
git clone 
mvn package
java -jar ./target/sassPOC-0.0.1-SNAPSHOT.jar
```
Browse to http://localhost:8080

### More information ###
See [src/main/resources/static/sass](https://github.com/davidkey/MavenSassExample/tree/master/src/main/resources/static/sass) and [pom.xml](https://github.com/davidkey/MavenSassExample/blob/master/pom.xml).
