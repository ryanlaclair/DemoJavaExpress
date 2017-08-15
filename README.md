# DemoJavaExpress

A demo application built with the [JavaExpress](https://github.com/ryanlaclair/JavaExpress) web-application framework.

### Building

JavaExpress and DemoJavaExpress use [Maven](https://maven.apache.org/) to manage dependencies and build. First build JavaExpress and install to your local Maven repository. Then, to build a JAR file for DemoJavaExpress, run:

```
mvn package
```

### Running

To start the DemoJavaExpress server listening on port 8999, run:

```
mvn compile exec:java
```
