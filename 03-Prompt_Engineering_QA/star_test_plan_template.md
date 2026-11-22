# STAR

Situation: I'm Senior QA Engineer , and I'm currebtly working on WSO2 Identity Platform Signin Feature Testing Effort.I have asked to create a test plan for the Signin Feature Testing effort. Ihave been provided with the requiements and the test plan teamplate.

This Signin Page - https://console.asgardeo.io/ and here the user can signin with Identity First authenticator to access the WSO2 Identity Platform.
Regisistered user can signin with their valid credentilas.
Invalid credentials should not allow to signin and should display an error message. "Login failed! Please check your username and password and try again."
Username should be email address and password should be minimum 8 characters long with at least one uppercase letter, one lowercase letter, one number and one special character.
User who forget the password there should be a "Forgot Password" link to reset the password.
If user need to change their username in different username there should be "Not You? Use a different account" link to change the username.
Successful signin should redirect the user to the WSO2 Identity Platform console Home page.

Task: Create a test plan for the Signin Feature Testing effort based on the provided requirements and template.

Refer for template: QA-AI-Blueprint-Knowledge-Lab/03-Prompt_Engineering_QA/templates/test_plan_template.md

Action: Define the objectives, scope, and testing approach.

Cover valid login, invalid credentials, empty fields, and access to the dashboard after login.

Include positive, negative, and boundary scenarios where the supplied requirements support them.

Define test environment needs, test data, entry criteria, exit criteria, deliverables, and risks.

Mark unspecified behavior as “Requires clarification.” Do not invent password rules, exact error messages, or session timeouts.

Consider More important points:as Security Cases based on user inputs only in this test plan.

Resuts: Return a comprehensive test plan in Markdown format that can be directly used for the Signin Feature Testing effort. based on the provided requirements and template.
Use clear language and tables where useful. Label any proposed criteria as recommendations.