**API/WebServices Testing( End- to -End Process)**

**Objective**:- Testing of API is automated using Rest Assured which is a java based library

**Description:**- Code has been written to automate the testing of the API given below with 3 acceptance criteria listed :

1)     API = https://api.tmsandbox.co.nz/v1/Categories/6327/Details.json?catalogue=false   

2)     Acceptance Criteria  
          a) Name = "Carbon credits" 
          b) CanRelist = true 
          c) The Promotions element with Name = "Gallery" has a Description that contains the text "2x larger image"

**Steps to be followed to execute the TestCase:**

A) **Pre-Requisites - Setting up the Environment********
          1)  Java Set up 
          2)  IDE Setup
          3)  Maven setup
          4)  Create a Maven Project as mentioned in below steps
                a. Navigate to File -> New -> Maven Project.
                b. Select Project Name and Location .Click on Next.
                c. Select an Archetype as QuickStart.Click on Next.
                c. Give Name into group id and Artifact ID .Enter values into required fields.Click on Finish,
                d. A Java Project with name equal to Artifact Id value is created in Package Explorer.
          5) Now open pom.xml file and start adding dependecies as shown in below steps.
             a)  Add Rest Assured Dependecy in pom.xml file( Link for Rest Assured JAR- https://mvnrepository.com/artifact/io.rest-assured/rest-assured)
             b)  Add Testng Dependecny in pom.xml file(Required to manage and run tests effectively)(Link for Testng JAR-                                      https://mvnrepository.com/artifact/org.testng/testng) 
             c)  Add JSON Schema Validator Dependency in pom.xml file(https://mvnrepository.com/artifact/com.fasterxml.jackson.module/jackson-module-jsonSchema)
             d)  Add JSON Path Depedency in pom.xml file (https://mvnrepository.com/artifact/io.rest-assured/json-path)
                                
              
B) As the Maven Project is created,create a new Java Package "apitest" under src/test/java.

c) Create a new Java Class "APITEST" under Package "apitest". 

d) In the Java class created above ,REST API End to End Test can be written as mentioned in the attached file.

d) Run the Rest API Test by right clicking on the test body and Run as Java Application.

e) The Test will run and you can see the results in Console.


