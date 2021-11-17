## Backbase Mobile QA Assignment Delivery update
```
As mention in assignment, Demonstrate my testing knowledge with below artefact delivery. 
- Build functional test scenario which is present under the Report > TestScenario folder (15 test scenarios are written with test steps)
- Functional Defect Report present under the Report > DefectReports folder (6 defect found)  
- Develop a automation regression test suites 
- Used github as source version control 
- Automation Test report -  which will be auto generated once the review execute the code with gradel command ./gradlew cAT
```
# Prerequisite
```
- Java 8 or higher
- User need Github & Android Studio 
- A Build Tool - Used Gradel
```
# Process to execute this test suites
```
- Open Terminal > go to project root folder > execute command ./gradlew cAT
- Open Android Studio > go to Terminal > execute command ./gradlew cAT
```
# How to develop new testcase ?
```
- Step1. Defiene the test scenarion and add into the testScenario folder
- Step2. Add new method with @test annotation under package com.test.tests
- Step3. Add Page object or granuler method under package com.test.pages 
- Step4. Add resulable component to package com.test.utils (if applicable)
```
# Detail description about the tests
```
- Current scope of testing is limited to the Launch, Main and Map screen
- Functional or manual testing cover the map screen in details (Not in scope of automation)
- All defects in details with reproducable steps are recored in defect report folder
- Automation test report will be generated under Reports > expressso_Refport folder
```
## Framework improvement
```
- With minimum experience with espresso, decided to use outdated library (ActivityTestRule) which need to be further improved with ActivityScenarioRule
```
# Reference Test Report
Detailed HTML report will auto generate once the end user execute using command prompt

![Sample Test Report](SampleTestReportScreenshot.png)


# Backbase Mobile QA Assignment

## Description
This assessment is to measure the candidate's knowledge with Git, test cases creation, test reporting and the ability to adapt with automation tools.

# Application under test
A simple native Android application that shows a list of cities which you can search and when you choose a city the app shows a pin on a map. Then you can go back and repeat the process.

# Prerequisites
- Github account
- Android Studio

## Deliverables:
1. Create a series of testcases based on the application functionality. Make sure that you give detailed instructions for each test case (step preconditions, steps to execute test case, expected results, etc). You can use any format you prefer.
2. Automate at least 5 (the more, the better!) of the previously created test cases. Use of Espresso as an automation tool is highly preferred. As an alternative you can use UI Automator. No other tool is accepted.
3. Provide a clear set of instructions how to run tests.
4. Provide a test report for executed test cases (manual and automated)
5. In the case of finding bugs, provide a separate bug report
6. Provide an overall evaluation test report for the application (issues, risks, recommendation, etc.). Make it personal! Explain why you decided to automate what you’ve automated, why you decided to test what you’ve tested, what test strategies you decided to use and why... Summarising, guide us through your mind!

All manual deliverables should be added to a "Reports" folder in root of project.

Once you are done,  push your test assignment to your fork. Please provide user **bb-qa** access to your fork and share a link to your fork when you are done with the assignment.

**Bonus Question:**
Part of the app functionality is currently not working. Fix it if you can.

**NOTE:**
If you need to take any assumptions please note them as part of your answers.


