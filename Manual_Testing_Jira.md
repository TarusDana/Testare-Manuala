<h1>Testing Project for Carturesti</h1>
The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: Carturesti

Tools used: Jira, Zephyr Squad.<br>
<br>
The below stories were created in Jira and describe the functional specifications of the "Login" module, for which the final project is performed upon.

![image](https://github.com/TarusDana/Testare-Manuala/assets/166814004/7ee58839-9b02-429c-9f15-096d54cf6350)
![image](https://github.com/TarusDana/Testare-Manuala/assets/166814004/91fb84ce-1c08-4f9e-bfef-b4696b4d2838)



Here you can find the release that was created for this project:

![image](https://github.com/TarusDana/Testare-Manuala/assets/166814004/4d66ba4e-f990-4e73-b64c-736711238058)


<h2><br>
Testing process<br></h2>
The test process was performed based on the standard test process as described below.

1.1 Test planning<br>
The Test Plan is designed to describe all details of testing for the Login module for the Carturesti application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here [Test Plan Carturesti](https://github.com/TarusDana/Testare-Manuala/files/14969886/Copy.of.Untitled.document.docx)

1.1.1. Roles asigned to the project and persons allocated


<h5>Project manager<br>
Andrei Constantin<br>
<h5>Product owner<br>
Constantin Dobrin<br>
<h5>Software developer<br>
Andreea Panait<br>
<h5>QA Engineer<br>
Tarus Dana<br><br>
<h4>1.1.2 Entry criteria defined</h4>
smoke test passed (being the most basic type of test, this is a very important entry criteria in the process of testing)<br>
testing environment is up and running<br><br>
<h4>1.1.3 Exit criteria defined</h4>
90% of tests are passed
no Critical issues have Open status<br>
update tests are 100% passed (update tests will not generate other new issues that impact the application)<br>

## 1.1.4 Test scope
### Tests in scope:
Browse Books: Users can search and explore a wide variety of books available on the website.<br>
Add to Cart: Users can add books to their cart for purchase.<br>
Checkout: Users can proceed to checkout to finalize their purchases.<br>
User Account: Users can create accounts, log in, and manage their personal information.<br>
Wishlist: Users can add books to their wishlist for future reference or purchase.<br>


<h4>Tests not in scope:</h4><br>
Non-functional Testing: Stress testing, performance testing, and other non-functional testing are not included in this project scope.<br>
QA Support for Mobile Applications: Testing and quality assurance support for mobile applications are not provided. Only web applications will be tested.<br>
Automation Testing: Automated testing is not within the scope of this project. Testing will be conducted manually<br>
<br>
<h4>1.1.5 Risks detected</h4>
<h4>Project risks:</h4>
Team members may lack sufficient knowledge or skills to perform testing efficiently and accurately.<br>
Testers may fail to communicate testing needs or results clearly or accurately to other teams or stakeholders.<br>
Team members may have a negative or unproductive attitude towards the testing process, viewing it as an unimportant or uninteresting task.<br>
The team may encounter difficulties in using or configuring testing tools, which can affect the efficiency and effectiveness of the testing process.<br>

<h4>Product risks:</h4>
Data security<br>
User experience<br>
Update and maintenance<br>
<h4>1.1.6 Evaluating entry criteria</h4>
The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.<br>

<h2>1.2 Test Monitoring and Control</h2>

The monitoring and control phase was implemented to ensure that the project progresses according to plan and to address any deviations or issues promptly. This phase allows project managers to track project performance, identify potential risks or delays, and take corrective actions to keep the project on track.<br>
![status report](https://github.com/TarusDana/Testare-Manuala/assets/166814004/aab40c37-f6cd-451c-82c7-f1ae499c2b23)<br>
![text execution progress](https://github.com/TarusDana/Testare-Manuala/assets/166814004/e282b7ea-9d0b-4545-9bf9-e5ebe78010e1)<br>

<h4>1.3 Test Analysis</h4>
The testing process will be executed based on the application requirements.

The following test conditions were found:
![testele](https://github.com/TarusDana/Testare-Manuala/assets/166814004/8aa6d450-e03b-4a66-8c15-aa33381381cd)<br>
<h4>1.4 Test Design</h4>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here [Test Cases](https://github.com/TarusDana/Testare-Manuala/files/14970560/Copy.of.Teste.-.Jira.csv.pdf)

### 1.5 Test Implementation<br>
The following elements are needed to be ready before the test execution phase begins:<br>

<ul>
<li>Test Environment Setup</li><br>
<li>Test Data Preparation</li><br>
<li>Test Case Execution</li><br>
<li>Defect Reporting</li><br>
<li>Test Coverage Analysis</li><br>
<li>Regression Testing</li><br>
<li>Test Progress Tracking</li><br>
<li>Test Documentation</li><br>
<li>Test Execution Validation</li><br>
</ul>
<h4>1.6. Test Execution</h4>
Test cases are executed on the created test Cycle summary: Test Login

Bugs have been created based on the failed tests. The complete bug reports can be found here: [Bugs](https://github.com/TarusDana/Testare-Manuala/files/14970667/Bugs.-.Jira.1.csv.pdf)

The following is a summary of the bugs that have been found [Summary](https://github.com/TarusDana/Testare-Manuala/files/14970667/Bugs.-.Jira.1.csv.pdf)

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.
1.7 Test Completion As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: ![story matrice](https://github.com/TarusDana/Testare-Manuala/assets/166814004/a9251957-5de2-48d9-b058-fc4d89b0f34b)

Test execution chart was generated and can be found below.

![Screenshot_5](https://github.com/TarusDana/Testare-Manuala/assets/166814004/f0736e4c-f241-4dfa-898f-f7f6951c6e7c)

The final report shows that a number 2 tests have failed of a total of 10

A number of 2 total bugs were found, from which the priority is: 1 is high and 1 is medium

Based on the test results, it's positive to see that all functionalities have been tested and that the bugs found can be easily fixed. However, it's concerning that the product risks include medium data security and user experience.

Given the potential impact of security-related bugs on user data, it's crucial to prioritize security measures and conduct thorough testing to identify and address any vulnerabilities. Additionally, focusing on improving the user experience and ensuring smooth update and maintenance processes can help enhance the overall quality of the product.

Therefore, it's recommended to allocate more attention and resources to addressing security-related issues and improving the overall user experience. This proactive approach can help mitigate potential risks and ensure a more secure and user-friendly product in the future.











