# Human Resource Tool

A small application to a human resource area.

## Description 

The objective of the application is that managers can write objectives to their employees and then qualify them.

Also that employees can give a qualitative qualification (a short description) of how their boss is towards them.

This is useful for human resources areas to obtain feedback from both the employee and their bosses and thus be able to make correction or improvement decisions.

## 1. UML

#### Boss

This is the flow for the boss process:

![boss_flow](Documents/img/uml1.png)

#### Employee

This is the flow for the employee process:

![employee_flow1](Documents/img/uml2.png)

Second part of the flow:

![employee_flow2](Documents/img/uml3.png)

## 2. Metrics

At the beginning, SONARQUBE was used to perform the metrics, but since it was a direct installation on my computer, it was difficult to share the results in this document, so I decided to switch to SONARCLOUD which is a solution in the cloud and allowed me to easily share the results of my metrics.

Here you can see the metrics of my project : [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=edpape007_App_Hr_Tool&metric=alert_status)](https://sonarcloud.io/dashboard?id=edpape007_App_Hr_Tool)

This is a summary:





## 3. Clean Code

This is the link for the [CheatSheet](Documents/CleanCode_CheatSheet.rst) use for this section.

## 4. Build Management

MAVEN was used for this project due to its excellent integration with the java. MAVEN use POM(Project Object Model) and is the fundamental unit of work in Maven. POM is an XML file that contains information about the project and configuration details used by Maven to build the project.

Here you can find the [Pom](pom.xml) file, to see the configuration used in this project.

Another reason why MAVE was selected is because Intellij IDEA has excellent integration, facilitating user use with a graphical interface.

![Maven](Documents/img/Maven.png)

## 5. Testing

Unit tests are contained in the [Test](src/test/java/com/hrtool) directory.

Test Folder:

![TestFolder](Documents/img/Test_Folder.png)

Test Results:

![TestResults](Documents/img/Test_Result.png)

And to test the code and that its functionality was successful, "Spring Boot" was used, which is a framework that according to its webpage "Spring Boot makes it easy to create stand-alone, production-grade Spring based Applications that you can" just run " . " https://spring.io/projects/spring-boot

It consists of GET - POST - PUT methods that serve to test the methods and functions that were created for the application.

To test them, the POSTMAN application was used, which has a user-friendly graphic interface to perform these tests.

## 6. Continuous Delivery

JENKINS was used for this project

## 7. IDE

The IDE "IntelliJ IDEA" was used for this project because of its versatility and the possibility of integrating plugins in a simple way.

The commands below are for Mac OS:

  - Ctrl + space bar --> to autocomplete or show the available options.
  - Cmd + R --> to run the project
  - Cmd + Fn + F2 --> to stop the running project
  - Alt + Cmd + K --> commit and push to github 
  - Ctrl + Tab --> File Switcher

## 8. DSL
## 9. Functional Programming 

1. Only Final Data Structures
   
   You can find the definition of an employee (or boss because both are employees the difference is the relation between them)    in the class [Employee.java](src/main/java/com/hrtool/model/Employee.java)
   
   ![FinalStructures](Documents/img/FinalStructures.png)
