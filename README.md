# utility-core

[![Maven Central](https://img.shields.io/maven-central/v/io.github.rajparsaniya/utility-core.svg?style=plastic)](https://search.maven.org/artifact/io.github.rajparsaniya/utility-core)
##### Introduction

The Utility Core library provides a set of utility classes intended to streamline development by reducing boilerplate code and enhancing code readability. By offering reusable functions and tools, the library helps you perform common tasks more efficiently.

##### Installation

Add **Utility Core** to your project using your preferred build tool:

- **Apache Maven**
  Add the following dependency to your `pom.xml`  
```
<dependency>
    <groupId>io.github.rajparsaniya</groupId>
    <artifactId>utility-core</artifactId>
    <version>1.0.0</version>
</dependency>
```
- ** Gradle **
- Add the following to your `build.gradle` dependencies block
```
implementation group: 'io.github.rajparsaniya', name: 'utility-core', version: '1.0.0'
```
* Gradle-short (Add the short-form dependency in your ```build.gradle```)
```
implementation 'io.github.rajparsaniya:utility-core:1.0.0'
```
* Gradle-kotlin (Add this line in your ```build.gradle.kts```)
```
implementation("io.github.rajparsaniya:utility-core:1.0.0")
```
* sbt (Add the dependency in your ```build.sbt```)
```
libraryDependencies += "io.github.rajparsaniya" % "utility-core" % "1.0.0"
```
* ivy (Add the following to your Ivy XML file)
```
<dependency org="io.github.rajparsaniya" name="utility-core" rev="1.0.0"/>
```
* grape (Add this annotation in your Groovy/Grape script)
```
@Grapes(
      @Grab(group='io.github.rajparsaniya', module='utility-core', version='1.0.0')
  )
```
* leiningen (Add the following to your ```project.clj``` dependencies vector)
```
[io.github.rajparsaniya/utility-core "1.0.0"]
```
* buildr (Add this line in your ```buildfile```)
```
'io.github.rajparsaniya:utility-core:jar:1.0.0'
```
