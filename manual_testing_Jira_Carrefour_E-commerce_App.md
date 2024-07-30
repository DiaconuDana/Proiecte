# Testing Project for **CARREFOUR E-commerce App** 

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

**Application under test:** carrefour.ro

**Tools used:** Jira, Zephyr Squad.


## 1. Functional specifications: 
The stories attached [here](https://github.com/DiaconuDana/Proiecte/blob/main/Jira_Stories.doc) were created in Jira and describe the functional specifications of the "register / login" module, for which the final project is performed upon.

You can find an example of one of the stories that were created below.

![image](https://github.com/DiaconuDana/Proiecte/assets/169816019/a695beb5-3d3a-40fd-b65a-6256b456b6f4)


## Release
Here you can find the release that was created for this project:

![Release](https://github.com/DiaconuDana/Proiecte/assets/169816019/932bcdd2-5ccb-4cc4-a881-d6d04943cbff)



## 2. Testing process 
The test process was performed based on the standard test process as described below.


### 1.1 Test planning 
The Test Plan is designed to describe all details of testing for Register/Signup modules from the Carrefour e-commerce application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing and the project risks associated with the plan. 


#### 1.1.1. Roles asigned to the project and persons allocated 

<table>
<tr><td>Project manager</td><td>Ion Popescu</td></tr>
<tr><td>Product owner</td><td>Maria Ionescu</td></tr> 
<tr><td>Software developer</td><td>Mihai Andreescu</td></tr> 
<tr><td>QA Engineer</td><td>Dana-Gabriela Diaconu</td></tr> 
</table>


#### 1.1.2 Entry criteria defined 

- Business requirements are completed by the analysis team and are delivered to the appropriate testing team for evaluation.
- Potential project risks are detected and mitigated.
- Roles and responsibilities are allocated.
- Test plan should be finalized before entering the next phase of testing.
- Define the objectives of testing and the accepted level of quality.


#### 1.1.3 Exit criteria defined 

- 90% or more of the tests are passed.
- No critical issues have status open.
- All detected errors have been reported and closed.
- Not finding bugs of major severity in a specific period of time.
- The deadline was reached.
- The objectives were fulfilled.
- The product usage documentation has been finalized with the scenarios evaluated during the testing phase.
- Test completion report has been created and sent to the stakeholders.
- Product risks have been identified and mitigated.


#### 1.1.4 Test scope 

##### Tests in scope
In order to fulfill the testing objectives, we will focus on the core functionalities of the REGISTER ACCOUNT / LOGIN feature within CARREFOUR e-commerce shop app over the next 2 months.
It will encompass testing user registration, data validation and error handling aspects.

Throughout the testing process, we will perform mostly blackbox testing with the following testing techniques:
- equivalence partitionong
- boundary value analysis
- decision table

From a non-functional perspective, we will perform only usability testing and compatibility testing.<br>
We will execute positive testing and negative testing scenarios and also (as needed) we will perform retesting and regression testing, when defects are going to be fixed or when modifications of any type are going to be brought to the code.<br> 
Other types and techniques of testing will be decided accordingly after requirement analysis.<br>
Testing will be performed at a system testing level.

##### Tests not in scope
All the other modules, except Register account module and Login (implicit), will not be tested throughout this project.
Non-functional testing like performance (stress testing, load testing, volume testing, scalability testing, spike testing) and security is beyond the scope of this project.
No QA support for mobile applications developed.<br>
Only web application will be tested. <br>
Automation testing is beyond scope.

Reason: 
These functionalities are not part of the current release of the e-commerce web app.


#### 1.1.5 Risks detected 

##### Project risks

- The team does not have the proper knowledge or experience in order to guarantee the desired level of quality for the application.<br>
- Not enough time has been allocated in order to properly test and cover all the functionalities in scope.<br>
- All that the data that is going to be used will have to be created explicitly in the scope of testing, which will cut off from the time allocated for testing, generating a risk of not reaching the deadline.

##### Product risks

- All the data that is going to be used will be test data, which will not give us an experience of the application close enough to the ones that the user will experience.<br>
- Taking into account that only two modules are in the scope of testing, the rest of the modules will still be at risk of not fulfilling the user needs.


#### 1.1.6 Evaluating entry criteria 
The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.


### 1.2 Test Monitoring and Control
Periodic reports (daily/weekly/monthly) will be generated to reflect the current status of the testing process.

![Jira_test_metrics](https://github.com/DiaconuDana/Proiecte/assets/169816019/1ee43669-33f1-48d4-8e7b-b80d81492498)


### 1.3 Test Analysis 

The testing process will be executed based on the application requirements. 

The following test conditions were found:

![teste jira](https://github.com/DiaconuDana/Proiecte/assets/169816019/2a5cf62d-b16c-4d30-8570-617e8414aff1)


### 1.4 Test Design 
Functional test cases were created in Zephyr Squad, using Jira as a manual testing tool based on the analysis of the specifications.<br>
The test cases can be accessed [here](https://github.com/DiaconuDana/Proiecte/blob/main/Jira_TestCases.pdf).


### 1.5 Test Implementation 
The following elements are needed to be ready before the test execution phase begins:

 - defined test objectives and scope - in order to have a clear understanding of what we're aiming to achieve with testing and what functionalities or features will be covered. This ensures everyone's on the same page and avoids wasted effort testing irrelevant areas.

- test strategy and approach - this outlines the overall testing methodology we'll be following. It details the types of testing planned (functional, usability, etc.) and the rationale behind them.

- test cases and scripts - test cases define specific scenarios to be tested, while scripts provide detailed instructions on how to execute those tests. Having them documented ensures consistent and thorough testing.

- test data prepared - we'll need a variety of test data to execute our test cases effectively. This data should encompass valid, invalid and edge cases to comprehensively test the system's behavior.

- defect reporting and tracking procedure - A clear process for identifying, reporting and tracking bugs encountered during testing is essential. This ensures efficient resolution of issues and maintains a record for future reference.

- test resources assigned - testing requires qualified personnel with the necessary skills and experience. Assigning testers and defining their roles ensures proper test coverage and efficient execution.

- schedule and risk management plan - having a defined testing timeline keeps everyone on track. A risk management plan helps identify potential roadblocks and establish mitigation strategies to ensure smooth test execution.


### 1.6. Test Execution 
Test cases are executed on the created test Cycle summary: Carrefour E-commerce App - User Authentication v1.0

Bugs have been created based on the failed tests. The complete bug reports can be found [here](https://github.com/DiaconuDana/Proiecte/blob/main/Jira_BugReport.pdf).

The following is a summary of the bugs that have been found:

![bugs jira](https://github.com/DiaconuDana/Proiecte/assets/169816019/57a56fb8-87c1-4f4f-9207-ef24399cdbc0)

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.


### 1.7 Test Completion 
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team.

The traceability matrix outlines the number of the business requirements created, the number of tests executed for each business requirement and the number of bugs reported.
I created 3 business requirements (3 stories) and the tests distribution was:
  - story ST3DD-2 - 14 test cases, with 5 errors found
  - story ST3DD-3 -  2 test cases, with 2 errors found
  - story ST3DD-4 - 10 test cases, with 3 errors found

The traceability matrix was generated and can be found here:

![Jira_traceability_matrix](https://github.com/DiaconuDana/Proiecte/assets/169816019/04b929ae-8cfb-433e-a0b7-31ad2bcf809b)


Test execution chart was generated and can be found below.

![Jira_Test_execution](https://github.com/DiaconuDana/Proiecte/assets/169816019/8c4529b0-6e0d-4769-8aa3-ba057efe7c76)


The final report shows that a number of 5 tests have failed out of a total of 17 tests executed.

A number of **8 bugs** were found, from which **2 bugs are of high risk and low severity**, which can be fixed later and **6 bugs are medium risk**. That means the product can be released into production.

