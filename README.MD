# GIT Repository for CETM65 Week 10
## Unit/Integration/Functional Testing and TDD

 
## How to use this repository:
* After cloning the Repository set up a Virtual Environment (I called mine VirtualENV, for instance)
* Activate the Virtual Environment
* Use the command 'pip install -r requirements.txt' to install required packages
* Ensure the Django Application is running ('python manage.py runserver') - found in Task 2
* Execute the Selenium Script in the home Task 2 directory ('python selenium_test.py')
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Task One

1. Create a basic class in app.py that has several functions (e.g. calculator)

2. Create a file called tests.py

3. Write Unit Tests in tests.py that test the following:

    * The class in app.py is instantiated properly
    * All functions in app.py have at least 1 associated  unit test
    * Include a setUp() method with appropriate code
    
4. Upload app.py and tests.py to new GitHub repo

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Task Two

1. Create a Selenium script that performs Functional tests on the front-end of an application
  * Selenium script can be found in 'Task 2' as: selenium_test.py
  

2. Must include:

setUp and tearDown() methods
* At least 1 test per route/URL endpoint
* At least 2 different Unit Test assertions e.g. AssertIn and AssertEquals

4. Upload selenium_script.py alongside application code to GitHub (ensure you include an updated requirements.txt file)
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

