
# Proiect-Practic-Testare-Manuala OpenCart
  
  

## Revision History
| Date  | Description  | Author | Comments | 
|---|---|---|---|
| 17.07.2023 | Test Plan | Lucian Bogdan Scutariu|   |

  ### 1.Introduction
      1.1  Project Objective
      1.2  Functionalities in scope
      1.3  Functionalities and tests out of scope
 ### 2. Test Process
      2.1 Test Planning
      2.2 Test Analysis
      2.3 Test design
      2.4 Test implementation
      2.5 Test execution
      2.6 Test closure
      2.7 Test monitoring and control
  ### 3.Test deliverables
      3.1 Test plan
      3.2 Test conditions
      3.3 Test cases
      3.4 Daily test summary reports
      3.5 Traceability matrix
      3.6 Test case results
      3.7 Bugs report
      3.8 Test completion report

      
   ## 1.Introduction
OpenCart is free open source e-commerce platform for online merchants. OpenCart provides a professional and reliable foundation from which to build a successful online store.Ranging from seasoned web developers looking for a user-friendly interface to use, to shop owners just launching their business online for the first time. OpenCart has an extensive amount of features that gives you a strong hold over the customization of your store.This release will have limited features and stocks.
   ### 1.1 Project objective
  OpenCart's administration side of the store is where you can modify features, upload images, add products, keep track of customers, manage payments, and much more. Customization in the admin affects how the customer will interact with a store: by modifying the look, structure, and content of the store front.
 
   Application under test link: [OpenCart](https://demo.opencart.com/)
   
   Application documentation link: [Documentation](http://docs.opencart.com/en-gb/introduction)
   
   ### 1.2  Functionalities in scope
      - Create an account successfully 
      - Check the menu if are corect products categories 
      - Ability to chose one or more products and insert in cart
      - Make an order successfully 
      - Chech if the website can be accesed of diffent internet browser
      
   The following are the functionalities that need to be
prioritised for the testing of the web application : 
   
   <li> Acces the site, create a new user and insert personal details
   <li> Check payments methods 
   <li> Check de Menu with products
   <li> Managing and adding products in the cart
   <li> Check if Vouchers are applied 
   <li> Check out and Shipping adress
  

Testing types used:<strong>Functional testing,Positive Testing,Experience-based testing,Negative Testing, GUI testing</strong>

  ### 1.3 Functionalities and tests out of scope

  <li> No QA support for mobile applications provided. Only web applications will be tested
  <li> Performance testing with all the subcategories and security testing are put of scope since they will be handled in a different project
  <li> Localization testing will not be in scope for this project since for the moment it will be used on a small range of coustumers who do not present a risk from this point of view

    
  ## 2.Test process
  
  ### 2.1 Test Planning
  Roles and responsibilities
  
  | Date | Name| Role |
  |---|---|---|
  | 17.07.2023 | Lucian Bogdan Scutariu | Junior Tester| 

  <em><strong>Entry criteria:</strong></em>
  
 <li>Functional business specifications are defined
 <li>Types of browsers we need to use : Internet explorer,Google Chrome, Firefox
 <li>Roles needed for the project are allocated
 

 <em><strong>Exit criteria:</strong></em>

 <li>all test cases have been executed 
 <li>90% of tests are passed
 <li>no Critical issues/bugs have Open status (All unresolved bugs have low priority and low severity)
 <li>exploratory testing performed on the features: Add funds, buy a product, Cancel order
 

 <em><strong>Risks:</strong></em>

 <li>user data (banking related data, funds, transactions, etc) might be impacted with update tests
 <li>stability risks (crashes, disconnects, etc)
 <li>IE browser might have performance issues
 <li>versions of IE older than 1.5923e have security vulnerabilities 
 <li>the web page pagination could be impacted when opened on mobile devices
 <li>stress conditions might impact the web application
 <li>browsers that are new released might not be supported
 <li>Security problems due new updates that might impact the vulnerability of the application
 <li>Log in problems: creditentials may be wrong ,or not accepted with next caracters:"£$%^!"
   
  #### 2.2 Test analysis 

 The testing process will be done based on the requirements for features:
   <li> Acces the site   
   <li> Create a new user
   <li> Insert personal details
   <li> Check payments methods 
   <li> Managing and adding products in the cart
   <li> Check if Voucher are applied 
   <li> Check out and Shipping adress 
   
 we plan on running a full regression test on the current version
   Test Conditions:
  <li> We will use test environment ;
  <li> Testing using new accounts and older account is necessary ;
  <li> The following test conditions could be found here: <a href="https://github.com/BogdanScutariu/Plan-testare-manuala-Open-Cart/blob/795585ddfcd36a295c95273075b0291befdde931/ZFJ-issue-export-08-16-2023-242ac113-0001.xlsx" target="_blank">Test Conditions</a>
  
    #### 2.3 Test design

- All the test cases are written and reviewed 
- Functional test cases will be created in Zephyr Squad using Jira as Test Management tool 
- Test condition will be created in Jira
- GUI test cases will be created in Zephyr Squad using Jira as Test Management tool .

#### 2.4 Test implementation

- all the test data is available and reviewed 
- Cycle summary was created and test cases were added to the cycle summary ;
- Test environment is up and running
- Positive Testing and Negative Testing will be written and executed 
  
  #### 2.5 Test execution

- The tests will be executed on the top 4 used browsers: Chrome, Mozilla Firefox, Microsoft Edge, Apple Safari. If time will be available we will extend tests on Opera and Brave browsers ;
- Test cases will be executed on the created Test Cycle Summary 
- Positive Testing and Negative Testing will be written and executed  
- Bugs will be reported based on the failed tests .

#### 2.6 Test closure

- At least 90% of tests are passed ;
- No Critical issues have Open status ;
- Exploratory testing have been performed .

#### 2.7 Test monitoring and control
- Reports will be generated to reflect the current status of the testing process.

## 3. Test deliverables	


#### 3.1 Test plan 
- The Test Plan is designed to describe all the details of testing for the following features:
  
   <li> Acces the site, Create a new user and insert personal details
   <li> Check payments methods 
   <li> Managing and adding products in the cart
   <li> Check is Voucher is applied 
   <li> Check out and Shipping adress

- The plan identifies the items and the features to be tested, the type of testing to be performed, the roles and responsibilities for testing process, the risks associated with the plan, the resources and schedule required to complete testing.

#### 3.2 Test conditions 


#### 3.3 Test cases
Here you can acces the link for the test cases executed:
 - <a href="https://github.com/BogdanScutariu/Plan-testare-manuala-Open-Cart/blob/795585ddfcd36a295c95273075b0291befdde931/ZFJ-issue-export-08-16-2023-242ac113-0001.xlsx" target="_blank">Test case</a>

#### 3.4 Daily/Weekly/Bi-weekly test summary report
 - link to the [summary reports](https://github.com/BogdanScutariu/Plan-testare-manuala-Open-Cart/blob/dfc98ed2890661c63c61806206bf8ef7bc7ebce2/ZFJ-Cycles-09-14-2023.html)
    

#### 3.5 Traceability matrix
 - Link to traceability matrix :  <a href="https://github.com/BogdanScutariu/Plan-testare-manuala-Open-Cart/blob/1df41d86dd52dde85857e9ef60131526458ec927/Tracebility%20Matrix.xlsx">Traceability Matrix report</a>
   
#### 3.6 Test case results
 -  The test cases results could be found here: <a href="https://github.com/BogdanScutariu/Plan-testare-manuala-Open-Cart/blob/24bef84f66aa40056c6934f7b85684345d6c215d/test%20case%20results.html">Test Case Results</a> 

#### 3.7 Bugs report
 - The bugs reported could be found here:  <a href="https://github.com/BogdanScutariu/Plan-testare-manuala-Open-Cart/blob/3a2e2ef01919873549ffb17bd45cab5630051406/bug%20report.png">Bug Report</a>

   
#### 3.8 Test completion report
 Here is the report for the test are passed and failed : <a href="https://github.com/BogdanScutariu/Plan-testare-manuala-Open-Cart/blob/5c99d7d5a36ea0f36343f78bd8cc9f2feafdda78/test%20execution.png">Test Execution</a>
 - we have 10 days of testing
 - we have 30 functional and GUI tests
 - in order to finish the regression run we would need to run an ~ of 3 tests/day



       


 



 

  

   

   

     
  
