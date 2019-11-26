# 86400BankTest

1.Run from terminal
   >Cd 86400BankTest 
   
   >mvn clean install

Or

From IDE
Go to folder structure —>86400BankTest/src/test/resources/runner/testng.xml —>Run as TestNg

Reports : target—>cucumber-reports (general report)

Project structure

app.base - testable class to initialise driver

app.feature - feature files

App.pages.android- page object for each page

App.runner - runner class to run the cucumber features and step definitions

App.stepdefinitions - step definiton for each feature file from app.feature

App.util :  initialising capabilities from properties file

testng.xml: to run testrunner.java










