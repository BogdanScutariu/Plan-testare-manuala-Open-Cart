
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
OpenCart is free open source e-commerce platform for online merchants. OpenCart provides a professional and reliable foundation from which to build a successful online store. This foundation appeals to a wide variety of users; ranging from seasoned web developers looking for a user-friendly interface to use, to shop owners just launching their business online for the first time. OpenCart has an extensive amount of features that gives you a strong hold over the customization of your store. With OpenCart's tools, you can help your online shop live up to its fullest potential..This release will have limited features and stocks.Over a period it will be upgraded and new functionality will be added to the website.
   ### 1.1 Project objective
  OpenCart's administration side of the store is where you can modify features, upload images, add products, keep track of customers, manage payments, and much more. Customization in the admin affects how the customer will interact with a store: by modifying the look, structure, and content of the store front.
 
   Application under test link: [OpenCart](https://demo.opencart.com/)
   
   Application documentation link: [Documentation](http://docs.opencart.com/en-gb/introduction)
   
   ### 1.2  Functionalities in scope
      - Create an account successfully 
      - Check the menu if are corect products in the category 
      - Ability to chose one or more products and insert in cart
      - Make a order successfully 
   The following are the functionalities that need to be
prioritised for the testing of the web application : 
   
   <li> Acces the site, create a new user and insert personal details
   <li> Check payments methods 
   <li> Check de Menu with products
   <li> Managing and adding products in the cart
   <li> Check if Voucher are applied 
     
The features in scope for testing:<strong> 
   <li> Acces the site Create a new user and insert personal details
   <li> Check payments methods 
   <li> Check de Menu with products
   <li> Managing and adding products in the cart
   <li> Check is Voucher are applied
   <li> Check out and Shipping adress
  </strong>

Testing types used:<strong>Funtional testing,Pozitiv Testing,Experienced test,Negativ Test,Condtition Test, GUI testing</strong>

  ### 1.3 Functionalities and tests out of scope
  <li>  <li> Type of Menu
  <li> Browser suported
  <li> No QA support for mobile applications developed. Only web applications will be tested
  <li> Non-functional testing like stress, performance is beyond scope of this project.

  ## 2.Test process
  ### 2.1 Test Planning
  Roles and responsibilities
  
  | Date | Name| Role |
  |---|---|---|
  | 17.07.2023 | Lucian Bogdan Scutariu | Junior Tester| 

  <em><strong>Entry criteria:</strong></em>
  
 <li>Functional business specifications are defined
 <li>Hardware specifications 
 <li>Roles needed for the project are allocated
 <li>Testing environment is up and running
 <li>Smoke test passed (being the most basic type of test, this is a very important entry criteria in the process of testing)

 <em><strong>Exit criteria:</strong></em>

 <li>all test cases have been executed 
 <li>90% of tests are passed
 <li>no Critical issues/bugs have Open status (All unresolved bugs have low priority and low severity)
 <li>exploratory testing performed on the features: Add funds, buy a product, Cancel order
 <li>update tests are 100% passed (update tests will not generate other new issues that impact the application)

 <em><strong>Risks:</strong></em>

 <li>user data (banking related data, funds, transactions, etc) might be impacted with update tests
 <li>stability risks (crashes, disconnects, etc)
 <li>IE browser might have performance issues
 <li>versions of IE older than 1.5923e have security vulnerabilities (we could mention what vulnerabilities are)
 <li>the web page pagination could be impacted when opened on mobile devices
 <li>stress conditions might impact the web application
 <li>new browser might not be supported 
 <li>Security problem due new updates
 <li> Log in problems


  #### 2.2 Test analysis 

- The testing process will be done based on the requirements for features:
- 
   <li> Acces the site Create a new user and insert personal details
   <li> Check payments methods 
   <li> Check de Menu with products
   <li> Managing and adding products in the cart
   <li> Check is Voucher are applied 
   <li> Check out and Shipping adress 
   
- we plan on running a full regression test on the current version
  
    #### 2.3 Test design

- All the test cases are written and reviewed ;
- Functional test cases will be created in Zephyr Squad using Jira as Test Management tool ;
- Test condition will be created in Jira
- Pozitive Test and Negative Test will be written and executed 
- GUI test cases will be created in Zephyr Squad using Jira as Test Management tool .

#### 2.4 Test implementation

- all the test data is available and reviewed 
- this test run includes only regression testing in which we will run tests that have the highest priority, this will be main priority ;
- Cycle summary was created and test cases were added to the cycle summary ;
- Test environment is up and running:
  #### 2.5 Test execution

- The tests will be executed on the top 4 used browsers: Chrome, Mozilla Firefox, Microsoft Edge, Apple Safari. If time will be available we will extend tests on Opera and Brave browsers ;
- Test cases will be executed on the created Test Cycle Summary ;
- Bugs will be reported based on the failed tests .

#### 2.6 Test closure

- At least 90% of tests are passed ;
- No Critical issues have Open status ;
- Exploratory testing have been performed .

#### 2.7 Test monitoring and control
- Various periodic reports (daily/weekly/bi-weekly) will be generated to reflect the current status of the testing process.

## 3. Test deliverables	


#### 3.1 Test plan - link to test plan
- The Test Plan is designed to describe all the details of testing for the following features:
  
   <li> Acces the site, Create a new user and insert personal details
   <li> Check payments methods 
   <li> Check de Menu with products
   <li> Managing and adding products in the cart
   <li> Check is Voucher are applied 
   <li> Check out and Shipping adress

- The plan identifies the items and the features to be tested, the type of testing to be performed, the roles and responsibilities for testing process, the risks associated with the plan, the resources and schedule required to complete testing.

#### 3.2 Test conditions 
-  we will use test environment ;
- testing using new accounts and older account is necessary ;
- The following test conditions could be found here: *vom adauga link catre document cu test conditions create si incarcate pe github. Test conditions vor fi exportate din Jira.

#### 3.3 Test cases
 - The test cases with steps could be found here: *vom adauga link catre document cu test cases create si incarcate pe github. Test cases vor fi exportate din Jira.

#### 3.4 Daily/Weekly/Bi-weekly test summary report
 - link to daily test summary report (number of tests ran today, % of them failed, passed, re-test, etc) *vom adauga link catre screenshot cu cu test summary report incarcat pe github SAU incarcam imaginea cu raportul direct pe github. Raportul va fi generat din Jira pe masura ce executam test caseurile.

#### 3.5 Traceability matrix
 - Link to traceability matrix *vom incarca pe github un screenshot din Jira
   
#### 3.6 Test case results
 -  The test cases results could be found here: *vom adauga link catre document cu test cases executate si incarcate pe github. Test cases results vor fi exportate din Jira.

#### 3.7 Bugs report
 - The bugs reported could be found here: *vom adauga link catre document cu defectele raportate in Jira pt test case-urile failed
   
#### 3.8 Test completion report
 - link to test completion report (Test cases ran, how many TC are passed and how many are failed)
   *vom adauga screenshot cu test completion report din Jira la sfarsitul testarii (toate test case-urile au fost executate)

#### 3.9 Schedule
 - we have 10 days of testing
 - we have 30 functional and GUI tests
 - in order to finish the regression run we would need to run an ~ of 3 tests/day



       


 



 

  

   

   

     
  
