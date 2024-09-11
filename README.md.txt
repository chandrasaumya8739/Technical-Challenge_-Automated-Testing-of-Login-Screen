1. Test Execution Steps:-
--------------------
1). To running the test scripts, following tools and dependencies are set up on your system:

1.1. Install Java JDk
1.2. Download Selenium 
1.3. Selenium WebDriver
1.4. Test Framework(TestNG).
1.5. Maven

2). Use Eclipse:

2.1. Create project as a Maven Project.

3). Set Up Dependencies:

3.1. In Maven, following dependencies are added to the pom.xml:


  <dependencies>
   
    <!-- https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-java -->
<dependency>
    <groupId>org.seleniumhq.selenium</groupId>
    <artifactId>selenium-java</artifactId>
    <version>4.16.1</version>
</dependency>

<!-- https://mvnrepository.com/artifact/org.testng/testng -->
<dependency>
    <groupId>org.testng</groupId>
    <artifactId>testng</artifactId>
    <version>7.10.0</version>
    <scope>test</scope>
</dependency>

  </dependencies>
</project>

4). Set the WebDriver Location

5).Test Cases:

5.1. Test 1: Successful Login

Objective: Verify that a user is able to log in with valid credentials.

Steps:
1.Open the login page.
2.Enter valid email and password.
3.Click on login button.
4.Verify that the user is redirected to the appropriate landing page.

Expected Result: The user should be login successfully. and redirected to the landing page

Test 2: Unsuccessful Login

Objective: Verify that error message is displayed. when incorrect credentials are used.

Steps:

1.Open the login page.
2.Enter an invalid email or password.
3.Click on login button.
4.Verify that the error message is displayed.

Expected Result: An error message should be displayed. and the user should remain on the login page.

6). Write scripts:
7). Run the Test Scripts:
8). Check the Test result
9). Generate Report

2. Assumptions:- 
--------------
1. Web application is properly accessible with correct URL during test execution.
2. during test execution of test application properly respond as expected.
3. Valid credentials are provided for the successful login test.
4. The error message for an unsuccessful login attempt is displayed .
5. The report generated will show a clear between passed and failed tests.

3.Additional Information:-
------------------------
I have significantly enhanced my skills and knowledge through this experience. It has been a rewarding journey where I not only enjoyed the process but also gained valuable insights and learning along the way.











