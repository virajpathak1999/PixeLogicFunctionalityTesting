register-page-testing
This is an automation script using Selenium and TestNG to test a registration page.
testing scope :
- in scope: functions related to the register process,
  1- Verify if all input fields meet the requirements 
     (first name - last name - email - phone - password)
  2- Verify the verification email was sent.
  
- out of scope: all non-functional tests -load and performance test- also UI test.
To run this project on your machine:
1- install java and eclipse IDE. 2- Install TestNG extension to Eclipse (from Eclipse Marketplace). 3- add selenium JARs as external JARs to the project (JARs exist in folder "selenium"). 4- the class newtest: it contains all methods used to perform test cases. 5- after running the project successfully an auto-generated report would be created contaiining the testing results, it can be found at: folder->test-output/index.html and test-output/emailable-report.html 5- the test can be run only once successfully, to rerun it again a change would be done,emails used in all functions would be changed.

Attached to this project are two Excel files containing the test cases report for manual testing and the bugs report for manually detected defects.
Also attached the automation reports in two .html files: "index.html" & "emailable-report.html"
