# Yildiz-Engine component-native-jpeg

This is the official repository of The Component native jpeg, part of the Yildiz-Engine project.
This component will hold the code for the jpeg library project.

## Original repository
https://github.com/LuaDist/libjpeg

## Features

* Hold the source code for the jpeg library to be used in the Yildiz-Engine project.

## Requirements

To build this module, you will need a java 9 JDK, Maven 3, cmake and a c++ compiler.

## Coding Style and other information

Project website:
http://www.yildiz-games.be

Issue tracker:
https://yildiz.atlassian.net

Wiki:
https://yildiz.atlassian.net/wiki

## License

All source code files are licensed under the permissive MIT license
(http://opensource.org/licenses/MIT).

Exception for all the files contained in src/main/c++, those are part of the jpeg project, using its own licence, and having its own authors, thoses files are simply a snapshot of the jpeg repository.

## Build instructions

Go to your root directory, where you POM file is located.

Then invoke maven

mvn clean install

This will compile the source code, then run the unit tests, and finally build a jar file.

## Usage

In your maven project, add the dependency


```xml
<dependency>
    <groupId>be.yildiz-games</groupId>
    <artifactId>component-native-jpeg</artifactId>
    <version>LATEST</version>
</dependency>
```
Replace LATEST by the version to use.

## Contact
Owner of this repository: Grégory Van den Borre
