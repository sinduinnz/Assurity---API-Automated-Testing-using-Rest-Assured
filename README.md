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
          1) Setting up 
                   -> Java
                   -> Eclispse
                   -> TestNg (Framework implemented on top of Java,used for organizing testcases and test suites
          2) Downalod Rest -Assured JAR files
          3) Creating a Project in Eclipse
          4) Setting up Rest-Assured Jars in class Path of Eclipse
              
B) As the Rest-Assured Setup is done,RESTful Webservice test can be written as mentioned in the attached file.


