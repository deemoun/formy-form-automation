# formy-form-automation
An example of automating a Web Form using WebDriver and ChromeDriver using PageObject model

This is an example of automating a WebForm on https://formy-project.herokuapp.com/form

Description of files used in the project:
PageObject: An parent PageObject that all classes should inherit to be able to perform WebDriver tests
TestPlan: A class that wires all test methods together
Utils: A configuration class that shows the location of chromedriver and constants related to general project configuration. Might also include helper methods in the futures
WebForm: A form class that includes all the locators, variables and methods for automating a Form Page. If automation of other webpages on the website is necessary, those pages should be created separately and should inherit the PageObject class

A step-by-step tutorial is located here: 

https://medium.com/software-testing-break-and-improve/intellij-idea-selenium-webdriver-automated-web-tests-with-page-objects-in-15-minutes-50aff32b7492
