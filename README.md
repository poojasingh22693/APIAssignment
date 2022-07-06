# APIAssignment
# RestApiTesting.Framework.Leopard <img src ="RestApiTesting.Framework.Leopard/images/leopard.jpg" width=139>
This is a RESTful API testing Framework using Java, Maven, JUnit, REST Assured and Jackson to test JSONPlaceholder REST API.

## Project Natures

### Maven <img src ="RestApiTesting.Framework.Leopard/images/maven.png" width=99>
Apache Maven is a software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information.
https://maven.apache.org/

### JUnit <img src ="RestApiTesting.Framework.Leopard/images/junit.png" width=99>
JUnit is a simple framework to write repeatable tests. It is an instance of the xUnit architecture for unit testing frameworks.
https://junit.org/junit4/

## JSONPlaceholder  <img src ="RestApiTesting.Framework.Leopard/images/JSONPlaceholder.jpg" width=119>
JSONPlaceholder is a free online REST API that you can use whenever you need some fake data. It's great for tutorials, testing new libraries, sharing code examples.
https://jsonplaceholder.typicode.com/

## Routes Tested
The following HTTP methods are tested:
* GET
* POST
* PUT
* PATCH
* DELETE

## REST Assured  <img src ="RestApiTesting.Framework.Leopard/images/restassured.png" width=79>
Testing and validating REST services in Java is harder than in dynamic languages such as Ruby and Groovy. REST Assured brings the simplicity of using these languages into the Java domain.
http://rest-assured.io/

## Getting code in local
Step 1: Download the .zip file.
Step 2: Extract the files 
Step 3: Open files in local

## Integrated Development Environment
IntelliJ is used to develop this Framework.

Feature file: RestApiTesting.Framework.Leopard\src\test\java\features\apiValidation.feature
Runner folder-file: RestApiTesting.Framework.Leopard\src\test\java\runner\AllClassesTestRunner.java
Step definition folder-file: RestApiTesting.Framework.Leopard\src\test\java\StepDefinitions\ApiBasicGetBookingTest.java

### Run Tests
* Running all classes at once::  Open file in IntelliJ: ..RestApiTesting.Framework.Leopardmaster\RestApiTesting.Framework.Leopard\src\test\java\runner\AllClassesTestRunner.java
* * Running for Get method::  Open file in IntelliJ: ..RestApiTesting.Framework.Leopardmaster\RestApiTesting.Framework.Leopard\src\test\java\runner\TestGetRunner.java
* Right click => Run As
* JUnit Test

#### Shortcut:
* Alt + Shift + X, T

### Run Tests with Command Prompt/Windows PowerShell
* Open Folder in File Explorer: ..\RestApiTesting.Framework.Leopard (where you have the "pom.xml" file)
* Open Command Prompt/Windows PowerShell
* Run "mvn clean test"

#### Notes ('mvn' is not recognized as an internal or external command)
* Download "apache-maven-3.6.1-bin.tar.gz" from "https://maven.apache.org/download.cgi#"
* Set the Environment Variables

