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
          4)  Create a Maven Project
          5)  Add Rest Assured Dependencies
          6)  Setup Maven Compiler Plugin
          
                   
              
B) As the Setup is done,Create a Test Package and a Class.

c) In the class,REST API End to End Test can be written as mentioned in the attached file.

d) Run the Rest API Test by right clicking on the test body and Run as Java Application.

e) The Test will run and you can see the results in Console.


