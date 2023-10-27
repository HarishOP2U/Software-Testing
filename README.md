# Software-Testing
Learning....


## Manual Testing

Software: A set of instrcutions, data or programs used to operate computers and execute specific tasks.

Types:
1. System Software (Operating System, Device drivers, Servers, Utilities, etc.)
2. Programming Software (Compiler, Debuggers, Interpreters, etc.)
3. Application Software (Web Applicaion, Mobile Apps, Desktop Applications etc.)

### Software Testing:
It is The process of evaluating and verifying that a software product or application does what it is supposed to do.

-> is a part of software development process.

-> is an activity to detect and idetify the defects in the software.

-> to release a quality product to the client.

### Software Qualtiy
Based on some parameters we can say our software is a quality softwware or not, that are:

-> Bug-free

-> Delivered on time

-> Within budget

-> Meets requirements and/or expectations

-> Maintainable (user friendly)

A quality product does precisely what the users want it to do.

### Project & Product

Project: If the software application is developed for specific customer based on the requirement then it is called a Project.
Service based company mainly deals with different projects, or clients, for ex: TCS, Infosis, Accenture, and they will work for n number of customers thought the world.

Product: If the software is developed for multiple customers based on market requirements then it is called a Product.
Product based company, devlops products based on market req, for ex. google(Docs, Maps,gmail), Microsoft(MS Word, Ms office), Orcale.

### Error, Bug/Defect & Failure

-> Error: Any incorrect human action that produces a problem in the system is called an error.
(normally committed by the develpoers)

-> Defect/Bug: Deviation from the expected behavior to the actual behavior of the system is called defect.
(are identified by the testers, at the time of testing phase)

-> Failure: The deviation identified by end-user while using the system is called a failure.
(failure will be there in customer environment)

### Why the Software has bugs?

-> Miscommunication

-> Software Complexity

-> Programming errors

-> Changing requirements

-> Lack of skilled testers
___

### SDLC - Software Development Life Cycle

SDLC is a process used by the software industry to design, develop and test high quality softwares.

<img width="337" alt="Screenshot 2023-10-26 155638" src="https://github.com/HarishOP2U/Software-Testing/assets/149035972/cc81115a-a48a-45a1-8eb0-2adf2a7bbaef">

1. Requirements Analysis (from customers).
2. Desgin (designers will design the software(UI, Navigation)).
3. Development (developers will write the program).
4. Testing (different type of testing is done).
5. Maintenance (we deploy the software in customer environment and they start using it).

### Waterfall Model

<img width="313" alt="Screenshot 2023-10-26 163320" src="https://github.com/HarishOP2U/Software-Testing/assets/149035972/71060573-fb2f-403e-bccd-89ef85a0d040">

In this model we have to prepare documentaion after every phase.
Documentation plays very important role in this model i.e, we will document each and every activity.

1. Requirement Analysis
2. System Design
3. Implementation
4. Testing
5. Deployment
6. Maintenance

-> Each and every phase have certian input or it will give some output.

-> Each phase depends on previous phase.

### Advantages

1. Quality of the product will be good.
2. Since Requirement changes are not allowed , chances of finding bugs will be less.
3. Initial investment is less since the testers are hired at the later stages.
4. Preferred for small projects where requirements are feezed

### Disadvantages

1. Requirement changes are not allowed.
2. If there is defect in Requirement that will be continued in later phases.
3. Total investment is more because time taking for rework on defect is time consuming which leads to
high investment.
4. Testing will start only after coding.

### Spiral Model

<img width="382" alt="Screenshot 2023-10-26 163511" src="https://github.com/HarishOP2U/Software-Testing/assets/149035972/ab6a203a-1ae7-4358-80ff-1e271bcd1800">

This model is especially suitable for product based companies as the product is made on demand of market requirement. So based on customer requirement updates can be made.

After completion on each cycle, we'll release the peace of software to the customer( includes all the requirements we have) and after that we take new requirements from the customer.

-> Spiral Model is iterative model.

-> Spiral Model overcome drawbacks of Waterfall
model.

-> We follow spiral model whenever there is
dependency on the modules.

-> In every cycle new software will be released to
customer.

-> Software will be released in multiple versions.
So it is also called version control model.

### Advantages

1. Testing is done in every cycle, before going to the next cycle.
2. Customer will get to use the software for every module.
3. Requirement changes are allowed after every cycle before going to the next cycle.

### Disadvantages

1. Requirement changes are NOT allowed in between the cycle.
2. Every cycle of spiral model looks like waterfall model.
3. There is no testing in requirement & design phase.(testing is there in every cycle but not every phase)

 ### Prototype Model

( It comes between Waterfall Model and Spiral Model)

 Prototype --- blue print of the software.
 
 initial requirements from the customer --> make the Prototype --> Customer(if satisfied)--> design, coding,testing..

### V-Model / VV-Model

<img width="427" alt="Screenshot 2023-10-26 170415" src="https://github.com/HarishOP2U/Software-Testing/assets/149035972/d951716e-9367-4a16-8a4c-88e8a0ffbf01">

BRS: Business Requirement Specification; CRS: Customer Requirement Specification; URS: User Requirement Specification.

These documents can not be understood by the developers and testers, so based on this document another document called SRS-Software Requirement Specification Document (contains the technical details) will be prepaired.

-> Testing is performed on each stage documentation.

->Correctness and completeness of document the document is tested in the for of Review.

#### Static Testing

Testing the project related documents in the form of Review, Walkthrough and inspection.

(static coz, we are not testing the software, we are testing the documents in the form of review, walkthrough and inspection.)

-> After Coding, the sub-module and the main-module will be tested by the developer himself in the form of Unit Testing and Integration Testing, because to conduct testing on this part you should have programming knowledge which testers do not have. 
   
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
### Static testing techniques

1. Review:
   Conducts on documents to ensure correctness and completeness.(ex;Requirement Reviews, Design Reviews, Code Reviews, Test plan reviews, Test cases reviews etc)

2. Walkthrough
   It is a informal review.
   
   -> Author reads the documents or code and discuss with peers.
   
   -> It’s not pre-planned and can be done whenever required.
   
   -> Also walkthrough does not have minutes of the meet.
    
4. Inspection
   Its a most formal review type. In which at least 3- 8 people will sit in the meeting.
   1. reader
   2. writer
   3. moderator plus concerned.
  
-> Inspection will have a proper schedule which will be intimated via email to the concerned developer/tester.

### Dynamic testing techniques
#### Levels of Software Testing
1. Unit testing

   (A unit is a single component or the modlue of a software.)

   -> It conducts on a single program or single module.
   
   -> It is white box testing technique.
   
   -> It is conducted by the developers.

   -> Unit testing techniques:
   1. Basis path testing
   2. Control structure testing(Conditional coverage; Loops Coverage)
   3. Mutation Testing
   
3. Integration testing

   -> It performed between 2 or more modules.

   -> It focuses on checking data communication between multiple modules.

   -> It is white box testing technique.

   Types:
   1. Incremental IT
      Incrementaly adding the modules and testing the data flow between the modules.
      
      Approaches:
      
      Top Down: Ensure the module added is the child of previous module.
      
      Bottom-UP: Ensure the module added is the Parent of previous module.

      Sandwich/Hybrid: Combination of Top-Down & Bottom Up approach.
      
   2. Non-Incremental IT

      Adding all the modules in a single shot and test the data flow between modules.
      
      we usually don't prefer it coz of the following draw backs.
      
      -> We might misss the data floe between some of the modules.
      
      -> If you find any defect, we can't understand the root cause of it.
            
4. System testing

   (The actual area where testers are involved)

   Testing over all functionality of the application with respective client requirements.

   -> It is a black box testing technique.

   -> It is conducted by testing team.

   -> After completion of component and integration level testing’s we start System testing.

   -> Before conducting system testing we should know the customer requirements.

   -> System Testing focusses on below aspects:
   • User Interface Testing (GUI)
   • Functional Testing
   • Non-Functional Testing
   • Usability Testing
   
6. UAT
   
   After completion of system testing UAT team conducts acceptance testing in two levels.
   
   -> Alpha testing: users will do testing in development/Testing environment
   
   -> Beta testing: users will install that software in there devices i.e, customer environmet and will perform the testing.
   
___

### QA & QC & QE

(Quality Assurance; Quality Control; Quality Engineering)

P - People -- QC(Testers)

P - Process -- QA

P - Product -- QE 

(In QE people are writing the code to test the software, that also comes under QC)

#### QA Vs QC

-> QA is Process related; QC is the actual testing of the software.

-> QA focuses on building in quality; QC focuses on testing for quality.

-> QA is preventing defects; QC is detecting defects.

-> QA is process oriented; QC is Product oriented.

-> QA for entire life cycle; QC for testing part in SDLC
___













