## Manual Testing Project

### 1. Project Introduction

-> Product

-> eCommerce Product/Appplication
     - Login
     - search for products/items
     - add them to cart
     - do payment
     - product will be delivered
     - return the product
     - etc...

-> Frontend -- Public

-> Backend -- Admin

-> URL : https://demo.opencart.com/

-> Customer : Opencart

### 2. Understanding & Explore the Functionality (FRS)

[OpenCart+-FRS.pdf](https://github.com/HarishOP2U/Software-Testing/files/13201544/OpenCart%2B-FRS.pdf)

-> FRS gives an overview what exactly the project is

-> Based on FRS we understand the Functionalities, and based on that we prepare test case, test scenarios

-> Mockup Screens are also provided in the FRS.

Mockup screens are dummy screens which are designed before actual screen so based on that we can write some test cases

> ### Estimation
> How much time we need for:
> - to understand the requirements
> - to write test cases
> - for execution
> - to verify the bugs

### 3. Test Plan

[OpenCart+-Test+Plan.pdf](https://github.com/HarishOP2U/Software-Testing/files/13201545/OpenCart%2B-Test%2BPlan.pdf)

-Scope
 - Inclusions
 - Test Environments
 - Exclusuions
- Test Strategy
- Defect Reporting Procedure
- Roles/ Responsibilities
- Test Schedule/ Deliverables
- Tools
- Risks and Mitigations
- Approval

### 4. Test Scenarios

[OpenCart-Test+Scenarios+.xlsx](https://github.com/HarishOP2U/Software-Testing/files/13202898/OpenCart-Test%2BScenarios%2B.xlsx)

-> area to be tested/ What to test

### 5. Writing Test Cases, Reviews & RTM

[OpenCart-TestCases.xlsx](https://github.com/HarishOP2U/Software-Testing/files/13204989/OpenCart-TestCases.xlsx)

### 6. Environment Setup & Build deployment

- MySQL Database
- Apache server

- XAMPP: controlling database and server

  1. Opencart download location
  2. XAMPP for apache, mysql, and php installaton.
  3. copy opencart folder(Step 1) in to below location.(C:\xampp\htdocs)
  4. After copying rename the folder "opencart ".
  5. Rename files
   
 Go to C:\xampp\htdocs\opencart\upload

 Rename file 'config-dist.php' to 'config.php'

 Go to C:\xampp\htdocs\opencart\upload\admin

 Rename file 'config-dist.php' to 'config.php'

   6. Connect to the database and create DB.
   
 DB Access URL: http://localhost/phpmyadmin/\

   7. Open the site http://localhost/opencart/
 
 Click on upload

   8. Provide Database connection details

 if there is error in installation do step 9
   
   9. Go to location C:\xampp\htdocs\opencart\upload
Delete install folder

   10. Go to Application URL

  Frontend application URL: http://localhost/opencart/upload/

  Backend Application url: http://localhost/opencart/upload/admin/

### 7. Test Execution
### 8. Bug Reporting & Tracking
### 9. Sanity Testing, Re-Testing &Regression Testing
### 10. Test Sign off



