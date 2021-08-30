# Run-Maven-Project-GUI-TOOL
In this repo, you can clean and build any MAVEN project with the help of a button in a JAVA GUI.

Maven is a build automation tool used primarily for Java projects. Maven can also be used to build and manage projects written in C#, Ruby, Scala, and other languages. The Maven project is hosted by the Apache Software Foundation, where it was formerly part of the Jakarta Project. Apache Maven is a software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information.

## In this repo, there are two projects.
## One of them belongs to the maven project (my-app) and the other is the gui that belongs to the desktop application (my-app-desktop).

![image](https://user-images.githubusercontent.com/5441882/131273700-ecd6c9b8-7a94-47e4-bb33-582f90bcbed2.png)

## The command line is opened with the help of a button in the desktop application designed in the gui. 

![image](https://user-images.githubusercontent.com/5441882/131273673-25f5f9e2-4393-47d9-8ddf-af434dd54b9c.png)

## The following line of code is run on the command line, which can clean and build maven.

![image](https://user-images.githubusercontent.com/5441882/131273359-6269edd8-fb24-4cbb-a335-19c4b643ddec.png)

## Thus, you can easily build an existing maven project without using any ide. 

* mvn claen compile test package

## You can also easily call not only one maven project, but also multiple maven projects or any java class.

## Of course, a maven project is called normally as follows.

![image](https://user-images.githubusercontent.com/5441882/131273747-ade31cc4-cc0a-4f44-a6b3-64e4df9a1b22.png)

![image](https://user-images.githubusercontent.com/5441882/131273794-683fcc60-f87c-4174-9420-22847d3db827.png)

## Of course, in order to run all these operations on the command line, you need to create the following settings in the system variables.
NOTE : While making all these adjustments, it varies according to the versions of the java and maven libraries available on your system.

### Under System Variables add below

* JAVA_HOME = C:\Program Files\Java\jdk1.8.0_201

* JDK_HOME = %JAVA_HOME%\bin

* M2_HOME = C:\apache-maven-3.6.0

* MAVEN_BIN = %M2_HOME%\bin

* MAVEN_HOME = %M2_HOME%

### Under path Add these

* %M2_HOME%
* %JDK_HOME%



