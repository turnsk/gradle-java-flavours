# gradle-java-flavours [![Build Status](https://travis-ci.org/uklance/gradle-java-flavours.svg?branch=master)](https://travis-ci.org/uklance/gradle-java-flavours) [![Coverage Status](https://coveralls.io/repos/github/uklance/gradle-java-flavours/badge.svg?branch=master)](https://coveralls.io/github/uklance/gradle-java-flavours?branch=master) [![Download](https://api.bintray.com/packages/uklance/maven/gradle-java-flavours/images/download.svg) ](https://bintray.com/uklance/maven/gradle-java-flavours/_latestVersion)

A Gradle plugin to add Android style flavours to a Java project

Usage:

```groovy
apply plugin: 'com.lazan.javaflavours'
javaFlavours {
	flavours = ['red', 'blue']
}
```