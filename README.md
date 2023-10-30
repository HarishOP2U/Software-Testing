# Software-Testing
Learning....


## Manual Testing

Software: A set of instructions, data, or programs used to operate computers and execute specific tasks.

Types:
1. System Software (Operating System, Device drivers, Servers, Utilities, etc.)
2. Programming Software (Compiler, Debuggers, Interpreters, etc.)
3. Application Software (Web application, Mobile Apps, Desktop Applications, etc.)

### Software Testing:
It is The process of evaluating and verifying that a software product or application does what it is supposed to do.

-> is a part of the software development process.

-> is an activity to detect and identify the defects in the software.

-> to release a quality product to the client.

### Software Quality
Based on some parameters we can say whether our software is quality software or not, that is:

-> Bug-free

-> Delivered on time

-> Within Budget

-> Meets requirements and/or expectations

-> Maintainable (user friendly)

A quality product does precisely what the users want it to do.

### Project & Product

Project: If the software application is developed for a specific customer based on the requirement then it is called a Project.
Service-based companies mainly deal with different projects, or clients, for ex: TCS, Infosis, and Accenture, and they will work for n number of customers throughout the world.

Product: If the software is developed for multiple customers based on market requirements then it is called a Product.
The product-based company, develops products based on market requirements, for ex. google(Docs, Maps,gmail), Microsoft(MS Word, Ms office), Orcale.

### Error, Bug/Defect & Failure

-> Error: Any incorrect human action that produces a problem in the system is called an error.
(normally committed by the developers)

-> Defect/Bug: Deviation from the expected behavior to the actual behavior of the system is called a defect.
(are identified by the testers, at the time of the testing phase)

-> Failure: The deviation identified by the end-user while using the system is called a failure.
(failure will be there in the customer environment)

### Why does the Software have bugs?

-> Miscommunication

-> Software Complexity

-> Programming errors

-> Changing requirements

-> Lack of skilled testers
___

## SDLC - Software Development Life Cycle

SDLC is a process used by the software industry to design, develop, and test high-quality software.

<img width="337" alt="Screenshot 2023-10-26 155638" src="https://github.com/HarishOP2U/Software-Testing/assets/149035972/cc81115a-a48a-45a1-8eb0-2adf2a7bbaef">

1. Requirements Analysis (from customers).
2. Design (designers will design the software(UI, Navigation)).
3. Development (developers will write the program).
4. Testing (different type of testing is done).
5. Maintenance (we deploy the software in the customer environment and they start using it).

## Waterfall Model

<img width="313" alt="Screenshot 2023-10-26 163320" src="https://github.com/HarishOP2U/Software-Testing/assets/149035972/71060573-fb2f-403e-bccd-89ef85a0d040">

In this model, we have to prepare documentation after every phase.
Documentation plays a very important role in this model i.e., we will document each and every activity.

1. Requirement Analysis
2. System Design
3. Implementation
4. Testing
5. Deployment
6. Maintenance

-> Each and every phase has a certain input or it will give some output.

-> Each phase depends on the previous phase.

### Advantages

1. The quality of the product will be good.
2. Since Requirement changes are not allowed, chances of finding bugs will be less.
3. Initial investment is less since the testers are hired at the later stages.
4. Preferred for small projects where requirements are feezed

### Disadvantages

1. Requirement changes are not allowed.
2. If there is a defect in the Requirement that will be continued in later phases.
3. Total investment is more because the time taken for rework on defect is time-consuming which leads to
high investment.
4. Testing will start only after coding.

## Spiral Model

<img width="382" alt="Screenshot 2023-10-26 163511" src="https://github.com/HarishOP2U/Software-Testing/assets/149035972/ab6a203a-1ae7-4358-80ff-1e271bcd1800">

This model is especially suitable for product-based companies as the product is made on demand of market requirements. So based on customer requirements updates can be made.

After completion of each cycle, we'll release the peace of software to the customer(including all the requirements we have) and after that, we take new requirements from the customer.

-> The Spiral Model is an iterative model.

-> Spiral Model overcomes drawbacks of Waterfall
model.

-> We follow the spiral model whenever there is
dependency on the modules.

-> In every cycle new software will be released to
customer.

-> Software will be released in multiple versions.
So it is also called the version control model.

### Advantages

1. Testing is done in every cycle, before going to the next cycle.
2. Customers will get to use the software for every module.
3. Requirement changes are allowed after every cycle before going to the next cycle.

### Disadvantages

1. Requirement changes are NOT allowed in between the cycle.
2. Every cycle of the spiral model looks like a waterfall model.
3. There is no testing in requirement & design phase.(testing is there in every cycle but not every phase)

 ### Prototype Model

( It comes between the Waterfall Model and the Spiral Model)

 Prototype --- blueprint of the software.
 
 initial requirements from the customer --> make the Prototype --> Customer(if satisfied)--> design, coding,testing..

## V-Model / VV-Model

<img width="427" alt="Screenshot 2023-10-26 170415" src="https://github.com/HarishOP2U/Software-Testing/assets/149035972/d951716e-9367-4a16-8a4c-88e8a0ffbf01">

BRS: Business Requirement Specification; CRS: Customer Requirement Specification; URS: User Requirement Specification.

These documents can not be understood by the developers and testers, so based on this document another document called the SRS-Software Requirement Specification Document (which contains the technical details) will be prepared.

-> Testing is performed on each stage of documentation.

->Correctness and completeness of document The document is tested in the for of a Review.

#### Static Testing

Testing the project-related documents in the form of Review, Walkthrough, and inspection.

(static coz, we are not testing the software, we are testing the documents in the form of review, walkthrough, and inspection.)

-> After Coding, the sub-module and the main module will be tested by the developer himself in the form of Unit Testing and Integration Testing, because to conduct testing on this part you should have programming knowledge that testers do not have. 
   
-> (Code level testing --- White Box testing)

-> (System Testing -- Black Box testing)

#### Dynamic Testing

testing the actual software using techniques; Unit testing, Integration, System testing, UAT(user acceptance testing)

### Verification & Validation

#### Verification 

checks whether we are building the right product (Focus on Documentation)

-> Verification typically involves (static testing);
Reviews; Walkthroughs; Inspections

#### Validation 

checks whether we are building the product right.

-> Takes place after verifications are completed.

-> Focus on Software

-> Validation typically involves actual testing.;
Unit testing; integration; system testing; UATtesting.

### Advantages
-> Testing is involved in each and every phase.

### Disadvantages
-> Documentation is more.

-> Initial investment is more.
___
## Static testing techniques

1. Review:
   Conducts on documents to ensure correctness and completeness. (ex; Requirement Reviews, Design Reviews, Code Reviews, Test plan reviews, Test cases reviews, etc)

2. Walkthrough
   It is an informal review.
   
   -> The author reads the documents or code and discusses it with peers.
   
   -> It’s not pre-planned and can be done whenever required.
   
   -> Also walkthrough does not have minutes of the meeting.
    
4. Inspection
   It's a most formal review type. In which at least 3- 8 people will sit in the meeting.
   1. reader
   2. writer
   3. moderator plus concerned.
  
-> Inspection will have a proper schedule which will be intimated via email to the concerned developer/tester.

## Dynamic testing techniques
### Levels of Software Testing

1. Unit testing

   (A unit is a single component or the module of a software.)

   -> It is conducted on a single program or single module.
   
   -> It is a white box testing technique.
   
   -> It is conducted by the developers.

   -> Unit testing techniques:
   1. Basis path testing
   2. Control structure testing(Conditional coverage; Loops Coverage)
   3. Mutation Testing
   
2. Integration testing

   -> It is performed between 2 or more modules.

   -> It focuses on checking data communication between multiple modules.

   -> It is a white box testing technique.

   Types:
   1. Incremental IT
      
      Incrementally adding the modules and testing the data flow between the modules.
      
      Approaches:
      
      Top Down: Ensure the module added is the child of the previous module.
      
      Bottom-up: Ensure the module added is the Parent of the previous module.

      Sandwich/Hybrid: Combination of Top-Down & Bottom-Up approach.
      
   2. Non-Incremental IT

      Adding all the modules in a single shot and testing the data flow between modules.
      
      we usually don't prefer it coz of the following drawbacks.
      
      -> We might miss the data flow between some of the modules.
      
      -> If you find any defect, we can't understand the root cause of it.
            
3. System testing

   (The actual area where testers are involved)

   Testing overall functionality of the application with respective client requirements.

   -> It is a black box testing technique.

   -> It is conducted by the testing team.

   -> After completion of component and integration level testing we start System testing.

   -> Before conducting system testing we should know the customer requirements.

   -> System Testing focuses on below aspects:
   • User Interface Testing (GUI)
   • Functional Testing
   • Non-Functional Testing
   • Usability Testing
   
4. UAT
   
   After completion of system testing UAT team conducts acceptance testing in two levels.
   
   -> Alpha testing: users will do testing in the development/Testing environment
   
   -> Beta testing: users will install that software in their devices i.e., customer environment, and will perform the testing.
   
___

## QA & QC & QE

(Quality Assurance; Quality Control; Quality Engineering)

- P - People -- QC(Testers)
- P - Process -- QA
- P - Product -- QE 

(In QE people are writing the code to test the software, which also comes under QC)

#### QA Vs QC

- QA is process-related; QC is the actual testing of the software.
- QA focuses on building quality; QC focuses on testing for quality.

- QA is preventing defects; QC is detecting defects.
- QA is process-oriented; QC is Product-oriented.
- QA for the entire life cycle; QC for testing part in SDLC
___
___

## System Testing Types

### 1. GUI Testing

- GUI mainly focuses on the front-end part, the UI part.
- wherever the user is interacting with the application part is called the front-end part.
-  Graphical User-interface Testing or GUI testing is a process of testing the user interface of an application.
- A graphical user interface includes all the elements such as menus, checkboxes, buttons, colors, fonts, sizes, icons, content, and images.
- refer to the documentation for testing, don't assume the functionalities.

### 2. Usability Testing

-> During this testing validate application provided context-sensitive help or not to the user.

-> Checking how easily the end users are able to understand and operate the application is called usability testing.

(Help menu, User manual)

### 3. Functional Testing

Functionality is nothing but the behavior of the application.

(Functional testing talks about how your feature should work according to the customer's requirements)

=> Object Properties Testing:

  - checks the properties of the objects present in the application. Ex; Enable, disable, visible, Focused, etc.
   
=> Database Testing/Backend testing:

DML(data manipulation language) Operations

   - checking database operations w.r.t user operations
    
   - Includes white box testing at the UI Part and Black box testing at the backend on the database (insert, delete, update, select,..) so it is called Grey Box Testing.
   
   - Table & column level validation( Column type, column length, number of columns..), Relation between the table (Normalization), Functions, Precedures, Triggers, Indexes, view, etc.
 
=> Error Handling
  
- The tester verifies the error messages while performing incorrect actions on the application.
  
- Error messages should be readable( in user understandable/simple language)

=> Calculations/Manipulations Testing

checking if the calculations are done properly or not

=> Links Existence & Links Execution

Where exactly the links are placed ---- links' existence

Links are navigating to the proper page or not --- Link execution

- Internal Links: Navigate to different sections on but same page
- External Links: Navigate to some other page
- Broken Links: Navigates Nowhere/ Doesn't have any target page (Placed for future implementation)

=> Cookies & Sessions 

Cookies are the temporary files created by the browser while browsing the pages through the internet.

Sessions are time slots created by the server and sessions will expire after some time (if you are idle for some time).

### Non-Functional Testing

Mainly focusing on customer expectations

=> Performance testing

Speed of the application
   
   1. Load testing 

   Increasing the load on the application slowly then check the speed of the application (creating virtual users and hit requests to the server).
   
   2. Stress testing

   Suddenly increase/decrease the load on the application and check the speed of the application
   
   3. Volume testing

   Check how much data is able to be handled by the application.
 
=> Security testing

How secure our application is.

  - Authentication: Users are valid or not.
  - Authorization/Access Control: Permissions of the valid users.

=> Recovery testing

checks the system change from abnormal to normal

=> Compatibility testing

  - Forward compatibility
  - Backward compatibility
  - Hardware compatibility

=> Installation testing
 
  - Screens are clear to understand
  - simple or not
  - Un-installation

=> Sanitation/Garbage testing

If any application provides any extra features/functionality then we consider them as bugs.

![Screenshot 2023-10-28 123615](https://github.com/HarishOP2U/Software-Testing/assets/149035972/73d7c9f8-7f94-4f37-ad2a-58a76bfb7cfd)

___
## Software Testing Terminology

### 1. Regression Testing

Testing is conducted on modified builds to make sure there will not be an impact on existing functionality because of changes like adding/deleting/modifying features.

-> Unit regression testing

   - Testing only the changes/modifications done by the developer.
     
-> Regional Regression Testing

   - Testing the modified module along with the impacted modules 
   – Impact Analysis meeting conducted to identify impacted modules with QA & Dev.

-> Full Regression
   
   – Testing the main feature & remaining part of the application.
   – Ex: Dev has made changes in many modules, instead of identifying impacted modules, we perform one round of full regression.

### 2. Re-Testing

Whenever the developer fixes a bug, the tester will test the bug fix is called Re-testing.

- Tester closes the bug if it works otherwise re-open and send to developer.
- To ensure that the defects that were found and posted in the earlier build were fixed or not in the current build.

- Example
  - Build 1.0 was released. The test team found some defects (Defect Id 1.0.1, 1.0.2) and posted them.
  - Build 1.1 was released, and now testing the defects 1.0.1 and 1.0.2 in this build is re-testing.

### 3. Smoke Vs Sanity Testing

- Smoke testing -- very very basic testing (build verification)
- Sanity testing -- testing main functionalities

![Screenshot 2023-10-28 131940](https://github.com/HarishOP2U/Software-Testing/assets/149035972/047e7ed9-cb87-4aeb-a048-63960363b983)

![Screenshot 2023-10-28 132135](https://github.com/HarishOP2U/Software-Testing/assets/149035972/2a721cf1-3315-4158-9ec7-a5ba7eb1723a)

### 4. Exploratory Testing

(Any Application which is new to the tester)

- We have to explore the application, understand it completely, and test it.
- Understand the application, identify all possible scenarios, document it then use it for testing.
- We do exploratory testing when the Application is ready but there is no requirement. 
- Test Engineer will do exploratory testing when there is no requirement.

-> Drawbacks:

- You might misunderstand any feature as a bug (or) any bug as a feature since you do not have a requirement.
- Time consuming
- If there is any bug in an application, you will never know about it.

### 5. Adhoc Testing

(Any Applications)

- Testing applications randomly without any test cases or any business requirement document.
- Adhoc testing is an informal testing type with an aim to break the system. 
- The tester should have knowledge of the application even thou he doesn't have requirements/test cases.
- This testing is usually an unplanned activity.

### 6. Monkey/Gorilla Testing

(Gaming Applications)

- Testing applications randomly without any test cases or any business requirement document.
- Adhoc testing is an informal testing type with an aim to break the system. 
- Tester does not have knowledge of the application.
- Suitable for gaming applications.

![Screenshot 2023-10-28 134327](https://github.com/HarishOP2U/Software-Testing/assets/149035972/cff4c386-9e34-42c3-b5c7-17e8bb0b93f2)

### 7. Positive Testing

- Testing the application with valid inputs is called Positive Testing.
- It checks whether an application behaves as expected with positive inputs.

### 8. Negative Testing

- Testing the application with invalid inputs is called Negative Testing.
- It checks whether an application behaves as expected with the negative inputs.

### 9. End-To-End Testing

Testing the overall functionalities of the system including the data integration among all the modules is called end-to-end testing.

![Screenshot 2023-10-28 135859](https://github.com/HarishOP2U/Software-Testing/assets/149035972/385d25be-3420-48e0-a888-6b2a429a9c2c)

### 10. Globalization and Localization Testing

#### Globalization Testing:

- Performed to ensure the system or software application can run in any cultural or local environment. 
- Different aspects of the software application are tested to ensure that it supports every language and different attributes.
- It tests the different currency formats, mobile number formats, and address formats that are supported by the application.
- For example; Facebook.com supports many languages and it can be accessed by people of different countries. Hence it is a globalized product.
  
#### Localization Testing:

- Performed to check system or software application for a specific geographical and cultural environment. 
- Localized product only supports a specific kind of language and is usable only in specific regions.
- It tests whether the specific currency format, mobile number format, and address format are working properly or not.
- For example; Baidu.com supports only the Chinese language and can be accessed only by people from a few countries. Hence it is a localized product
___

## Test Data Design Techniques/Test Case Design Techniques

Used to prepare data for testing

1. Reduce the Data

2. More Coverage

>> These are the 5 Techniques we use to prepare the data 
>> To reduce the data and increase the coverage at the same time

### Equivalence Class Partitioning(ECP)

Partition data into various classes and we can select data according to class and then test. It reduces the number of test cases and saves time in testing.

- value check(1 value form a class)
- classify/divide/partition the data into multiple classes

### Boundary Value Analysis(BVA)

The BVA technique is used to check the Boundaries of the input.

- checks only boundary value (Min, Min+1, Min-1; Max, Max+1, Max-1)

>> #### Input Domain Testing
>> The value will be verified in the text box/input fields.
>> We use ECP & BVA techniques.

### Decision Table

- If we have more number of conditions /actions then we use the decision table technique.
- Here, we deal with combinations of inputs. 
- Here, we consider conditions and actions.

### State Transition

- In the State Transition technique changes in input conditions change the state of the Application.
- This testing technique allows the tester to test the behavior of an AUT. 
- The tester can perform this action by entering various input conditions in a sequence. 
- In the State transition technique, the testing team provides positive as well as negative input test values for evaluating the system behavior.

### Error Guessing

Error guessing is one of the testing techniques used to find bugs in a software application based on a tester’s prior experience. 
- In Error guessing we don’t follow any specific rules.
- It depends on Tester's Analytical skills and experience.
- Some of the examples are:
    - Submitting a form without entering values.
    - Entering invalid values such as entering alphabets in the numeric field
___
___
## Software Testing Life Cycle (STLC)

1. Requirement Analysis
2. Test Planning
3. Test Designing/ TestCase Development
4. Test Execution/ Environment Setup
5. Defect/Bug Reporting & Tracking
6. Test Closure

![Screenshot 2023-10-28 185534](https://github.com/HarishOP2U/Software-Testing/assets/149035972/05bb3395-b818-41f4-930d-6e1e3da4c0a2)
___

## Test Plan

A Test Plan is a document that describes the test scope, test strategy, objectives, schedule, deliverables, and resources required to perform testing for a software product.

- Overview
  - Scope
  - Inclusions
- Test Environments
- Exclusions
- Test Strategy
- Defect Reporting Procedure
- Roles/Responsibilities
- Test Schedule
- Test Deliverables
- Pricing
- Entry and Exit Criteria
- Suspension and Resumption Criteria
- Tools
- Risks and Mitigations
- Approvals

## Use Case, Test Scenario & Test Case

-> Use Case: 

- Use case describes the requirement. 
- Use case contains THREE Items.
   - Actor, which is the user, which can be a single person or a group of people, interacting with a process.
   - Action, which is to reach the final outcome.
   - Goal/Outcome, which is the successful user outcome.
   - 
-> Test Scenario:

- A possible area to be tested (What to test)
- tells what to test
  
-> Test Case: 

- Step-by-step actions to be performed to validate the functionality of AUT (How to test).
- Test case contains test steps, expected result & actual result.

>> Use Case – Describes functional requirement, prepared by Business 
Analyst(BA).
>> Test Case – Describes Test Steps/ Procedure, prepared by Test Engineer.
>> Test Scenario is ‘What to be tested’ and Test Case is ‘How to be tested.
>> Test Suite is a group of test cases that belongs to the same category

## Test Case

A Test Case is a set of actions executed to validate a particular feature or functionality of your software application.

- Test Case ID 
- Test Case Title
- Description
- Pre-condition
- Priority ( P0, P1,P2,P3) – order
- Requirement ID
- Steps/Actions 
- Expected Result
- Actual Result
- Test data

## Requirement Traceability Matrix(RTM)

-> What is RTM (Requirement Traceability Matrix)?

- RTM describes the mapping of Requirements with the Test cases.
- The main purpose of RTM is to see that all test cases are covered so that no functionality should be missed while doing Software testing.

 -> Requirement Traceability Matrix – Parameters include

- Requirement ID
- Req Description
- Test case IDs

## Test Environment

-> exact replica of customer platform

- Test Environment is a platform specially built for test case execution on the software product. 
- It is created by integrating the required software and hardware along with proper network configurations.
- Test environment simulates production/real-time environment.
- Another name for a test environment is Test Bed

## Test Execution

-> During this phase test team will carry out the testing based on the test plans and the test cases prepared.

-> Entry Criteria: Test cases, Test Data & Test Plan 

-> Activities:

   - Test cases are executed based on the test planning.
   - Status of test cases are marked, like Passed, Failed, Blocked, Run, and others.
   - Documentation of test results and log defects for failed cases is done.
   - All the blocked and failed test cases are assigned bug IDs.
   - Retesting once the defects are fixed.
   - Defects are tracked till closure.

-> Deliverables: Provides defect and test case execution report with completed results

## Guidelines for Test Execution

- The Build being deployed to the QA environment is the most important part of the test execution cycle.
- Test execution is done in a Quality Assurance (QA) environment.
- Test execution happens in multiple cycles.
- The test execution phase consists of Executing the test cases + test scripts( if automation)

## Defect/Bugs

-> Any mismatched functionality found in an application is called as 
Defect/Bug/Issue.

-> During Test Execution Test engineers are reporting mismatches as defects to developers through templates or using tools.

-> Defect Reporting Tools:
   - Clear Quest
   - DevTrack
   - Jira
   - Quality Center
   - Bug Jilla etc.

## Defect Classification

### Severity 

-> Severity describes the seriousness of the defect and how much impact on Business workflow. 

-> Defect severity can be categorized into four class
   
   - Blocker(Show stopper): This defect indicates nothing can proceed further.
      - Ex: Application crashed, Login Not Worked
        
   - Critical: The main/basic functionality is not working. Customer business workflow is broken. They cannot proceed further.
      - Ex1: Fund transfer is not working in net banking
      - Ex2: Ordering products in e-commerce application is not working.
     
   - Major: It causes some undesirable behavior, but the feature/application is still functional.
      - Ex1: After sending the email there is no confirmation message
      - Ex2: After booking a cab there is no confirmation.
        
   - Minor: It won't cause any major break-down of the system
      - Ex: Look and feel issues, spellings, alignments.

### Priority

- Priority describes the importance of the defect.
- Defect Priority states the order in which a defect should be fixed.
- Defect priority can be categorized into three class
   - P0 (High): The defect must be resolved immediately as it affects the system severely and cannot be used until it is fixed.
   - P1 (Medium): It can wait until a new version/build is created
   - P2 (Low): The developer can fix it in later releases

>> - Defect Resolution (Developers view if it is a defect or not)
>> - After receiving the defect report from the testing team, the development team conducts a review meeting to fix defects. Then they send a Resolution Type to the testing team for further 
communication.
>> - Accept; Reject; Duplicate; Enhancement, Need more info; As Designed.
___

## Defect/Bug Life Cycle

![Screenshot 2023-10-29 171914](https://github.com/HarishOP2U/Software-Testing/assets/149035972/8adef347-5cb1-4822-8fcc-43f7bb3384a1)

## Test Cycle Closure

-> Activities

   - Evaluate cycle completion criteria based on Time, Test coverage, Cost, Software, Critical Business Objectives, and Quality.
   - Prepare test metrics based on the above parameters.
   - Document the learning of the project
   - Prepare Test summary report
   - Qualitative and quantitative reporting of the quality of the work product to the customer.
   - Test result analysis to find out the defect distribution by type and severity.
     
-> Deliverables

   - Test Closure report
   - Test metrics

## QA/Testing Activities

- Understanding the requirements and functional specifications of the application. 
- Identifying required Test Scenario’s. 
- Designing Test Cases to validate applications. 
- Setting up Test Environment(Test Bed)
- Execute Test Cases to a valid application 
- Log Test results ( How many test cases pass/fail ).
- Defect reporting and tracking. 
- Retest fixed defects of the previous build 
- Perform various types of testing in the application. 
- Reports to Test Lead about the status of assigned tasks 
- Participated in regular team meetings.
- Creating automation scripts. 
- Provides recommendations on whether or not the application/system is ready for production.

## 7 Principles of Software Testing

1. Start software testing at early stages. This means from the beginning when you get the requirements.
2. Test the software in order to find the defects.
3. Highly impossible to give bug-free software to the customer.
4. Should not do Exhaustive testing. This means we should not use the same type of data for testing every time.
5. Testing is context-based. This means deciding what types of testing should be conducted based on the type of application.
6. We should follow the concept of the Pesticide Paradox. This means, that if you are executing the same cases for a longer run, they won't find any defects. We have to keep updating test cases in every 
cycle/release in order to find more defects.
7. We should follow defect clustering. This means some of the modules contain most of the defects. By experience, we can identify such risky modules. 80% of the problems are found in 20% of the modules

___
___

## Manual Testing Project

Project  introduction
Understanding & Explore the Functionality (FRS)
Test Plan
Writing Test Scenarios
Writing Test Case & Reviews
Envirornment Setuo & Buid deployment
Test Execution
Bug Reporting & Tracking
Sanity Testing, Re-Testing & Regression Testing
Test Sign off










