# Automation Demo – Login Flow (Pseudocode)

This document demonstrates a basic automation testing approach for a mobile application's login functionality.

## Test Objective
Verify that a user can successfully log in with valid credentials.

## Test Scenario (Gherkin Style)

Given the user has installed the app  
And the user is on the login screen  
When the user enters a valid email and password  
And taps the Login button  
Then the user should be redirected to the Home screen  
And the user session should remain active  

## Notes
- This scenario can be automated using tools such as Appium or Selenium.
- Assertions would validate navigation, session state, and UI elements.
- This serves as a proof-of-concept for automation readiness.

