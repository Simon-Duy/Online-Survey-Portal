# Online-Survey-Portal
An website Application empowered by Java Servlet enables users who has registered to create online survey forms with multiple question types, customizes forms into favorite look and feel with integrated tools, as well as have ability to conduct ongoing surveys from other users

## Features
• Manager Page
⁃ Survey Management Layout: Survey Creation and Modifications
⁃ Survey Insight Layout: helps view created survey quantity, number of conducted surveys
⁃ Account Management with account decentralization capability

## User Page
⁃ Registration form supports new user creation
⁃ Approval system would prevent unauthorized users from accessing the portal
⁃ Ability to conduct and view answered surveys
⁃ Account information management mode supporting various information modifications

## Deployement Steps
- Unzip the download package by choosing “ Extract to … “ option with your personal, favored file archiver utility (either Winrar or 7Zip works best in this instances)
- Download and install Java JDK-1.8 with the attached link
- Download STS (Spring Tool Suite) IDE from the following link and run its portable version
- Navigate to “File” tab from menu bar, import the existing project with “Existing Maven Project” Option
- Right-click on imported project, navigate to ”Properties”
- Navigate to “Java Build Path” -> “Tab Library” -> “JRE System Library” -> “Edit” -> Choose “JRE-1.8” -> Choose “Finish” -> Click on “Apply”
- Navigate to “Order and Export” Tab -> Click on “JRE System Library” -> Click on “Apply”
- Continue proceeding to “Project Facets” Tab -> “Java” -> Choose “1.8” option -> Click on “Apply and Close”
- Move into “pom.xml” file from package browser and modify MySQL version corresponding to your machine version
- Download Tomcat Server version 8.5 from the attached link and copy its components into C Drive (Windows Drive)
- Right-click on package browser in STS IDE and choose New -> Server option
- Choose “Apache” Tab -> Click on “8.5” -> Next -> Browse C Drive and look for Tomcat Server folder -> Click “Next” and “Finish”
- Download and Install MySQL along with its components from MySQL official website
- Make sure to name MySQL credentials with “root” for both username and password.
- After MySQL workbench has been successfully installed, sign-in and create database with the name “envsurvey”, then use the following code “USE envsurvey” to set its as a active database
- Navigate to “Server” from within MySQL Workbench, then move into “Data Import” -> “Import from Self-Contained File” -> Browse sql script in project “Database” folder -> Click on “Start Import”
- In case your security for MySQL is based on your preferences, you are asked to modify your info in “system.properties” file from “src/main/resources” directory so as for the project to run flawlessly
- Right-click on the project, navigate to “Run as” -> “Run on Server” -> “Tomcat Server 8.5” -> Click on “Next” and “Finish”
- To run on your specific, favorite browser, set your default browser engine in your OS Settings (either Microsoft Edge or Google Chrome is recommended)
- Should your STS execute the project on its specific browser, you may need to set STS behavior to utilize your favored browser by going to “Windows” Tab -> “Web Browser” -> Choose “Default Web Broswer”
- The project setup is now completed, enjoy the seamless experiences with robust features
