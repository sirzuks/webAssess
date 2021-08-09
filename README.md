# Task 2 - Web Automation

Author: Zukile Ngcizela 
Date: 09 August 2021<br />

Create test cases for web link : [Way2Automation](http://www.way2automation.com/angularjs-protractor/webtables/)

- Navigate to - http://www.way2automation.com/angularjs-protractor/webtables/
- Validate that you are on the User List Table
- Click Add user
- Add users with the following details:

| First Name | Last Name | User Name (*) | Password | Customer   | Role     | Email             | Cell   |
|------------|-----------|---------------|----------|------------|----------|-------------------|--------|
| FName1     | LName1    | User1         | Pass1    | CompanyAAA | Admin    | admin@mail.com    | 082555 |
| Fname2     | LName2    | User2         | Pass2    | CompanyBBB | Customer | cusomter@mail.com | 083444 |


## Technologies Used
a. This Project was created in Visual studio Community - Best experienced cloned in Visual Studio (Can use other editors as well)
  1. For this test case I created a UnitTest .NetFrameWork 4.7.2 Project 
  2. Installed Selenium webdriver package for solution 
  3. Installed NUnitFramework
  4. Installed nunitTestAdapter.WithFramework
  5. Installed chrome drive using Nuget Packages

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.


## Package Manager

PM> Get-Package

| Id                              | Versions          | ProjectName   |
|---------------------------------|-------------------|---------------|
| MSTest.TestAdapter              | {2.2.5}           | webAssessment |
| MSTest.TestFramework            | {2.2.5}           | webAssessment |
| Selenium.Support                | {3.141.0}         | webAssessment |
| Selenium.WebDriver              | {3.141.0}         | webAssessment |
| Selenium.WebDriver.ChromeDriver | {92.0.4515.10700} | webAssessment |
