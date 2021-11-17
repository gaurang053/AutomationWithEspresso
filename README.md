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


