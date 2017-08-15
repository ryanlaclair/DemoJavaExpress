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

An application like [Postman](https://www.getpostman.com/) can be used to easily test the different DemoJavaExpress routes. Point your browser or Postman to `http://localhost:8999` to test the web-application routes. The following routes are defined in DemoJavaExpress:

`GET /` - the school main page

`GET /students` - the list of enrolled students

`POST /students` - add a student where the request body specifies the student name

`GET /students/:name/classes` - a student's class list

`POST /students/:name/classes` - add a class to a student's class list, where the request body specifies the class name
