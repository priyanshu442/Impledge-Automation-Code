# With That credential I am unable to login at Kloudship Website Because of that i have Written that code according to my understanding .

Add Package
This project contains a Python script to automate the process of testing the "Add Package" feature on the KloudShip QA application. The script uses the Selenium WebDriver library to interact with the application and perform end-to-end testing, including login, adding a package, and verifying the addition.

Prerequisites
1. Python Installation
Ensure Python (version 3.7 or above) is installed on your system. You can download it from Python.org.

2. Selenium Installation
Install Selenium by running:

bash
Copy
Edit
pip install selenium
3. WebDriver
Download the appropriate WebDriver for your browser:
ChromeDriver for Google Chrome
Make sure the WebDriver version matches your browser version.
Add the WebDriver's location to your system's PATH or specify the full path in the script.
Project Files
automation_script.py: The main Python script that automates the test.
README.md: Documentation file (this file).
Script Details
Script Features:
Login Automation: Logs into the KloudShip QA application using provided credentials.

Navigate to Package Types: Automates navigation to the "Package Types" section of the application.

Add a Package:

Adds a new package with a pre-defined name and a random dimension between 1 and 20.
Saves the package and logs out.
Re-login and Verification:

Logs back into the application to confirm the package was successfully added.
Verifies by checking the presence of the package name in the page source.
Error Handling:

Includes exception handling to catch and log errors during execution.
Cleanup:

Ensures the browser is properly closed after execution

# Delete Package
Login: Automates login using the provided credentials.
Navigate to Package Types: Accesses the "Package Types" section.
Find and Delete Package: Locates the package with the name Test_User (created in Test Case 01) and deletes it. You may need to adjust the XPath or element selectors based on the HTML structure of your application.
Logout: Logs out of the application.
Verification: Logs back in to confirm the package is no longer visible
