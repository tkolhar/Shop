# Shop
Shop Product Assignment Ethoca
Steps to set up and run the tests. 
Please feel free to check ListOfTestCases.docx to find more test cases documentated.

Test Automation Framework Shopping Application:
Development Tools Used:
Language Used: Java Jdk1.7+
Build Tool: Maven 4.0.0
Browser/UI Automation: Selenium HQ version 3.0.1
Browser Used for Testing: Chrome Version 56.0.2924.87 (64-bit)
Test Framework: Junit 4 
IDE: Eclipse Neon.2 4.6.2

1.	Maven is used to handle all the dependencies. 
2.	The pom.xml contains all the dependency details and plugin to be included. 
3.	For selenium, I had downloaded the it from official website and then included the jar files in the project. If you are using Eclipse, then Right Click the Project -> Properties -> Java Build Path Tab -> Libraries Tab -> Click Add External Jars. 
4.	Here you can Browse for selenium-java-3.0.1 folder and include all the jar files found in lib directory as well as outside lib directory. 
5.	Later update the pom.xml to handle the dependency for selenium. 
6.	Please download ChromeDriver and extract chromedriver.exe in C:\\chromedriver_win32\\chromedriver_win32\\chromedriver.exe.
7.	This location is important because for UI tests I have set the system property to locate the Chrome Driver in the above-mentioned path

To Run:
In eclipse, click Run As and select Junit Test



