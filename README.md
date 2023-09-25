# Para-Bank-excel
The general test cases for manually testing the web/mobile application are available in this repository. 
Manual testing is a sort of software testing in which test cases are manually run by a tester without the use of any automated technologies. Manual testing is used to find bugs, issues, and defects in software applications.

Why manual testing?
When an application enters the market and is unstable, comes with a bug, or causes a problem while end-users are using it. If we do not want to face these sorts of issues, we must complete one round of testing to ensure that the application is bug free and stable, and that we give a quality product to the client, because if the program is bug free, the end-user will find it easier to use.

Perquisite: Basic computer skills and experience with software applications are advantageous. Understanding software development fundamentals is also useful.

Testing:
To manually test the application, follow these general steps:

1.Analyze the software requirement specification document's needs.


2.Make a detailed test plan.

3.Create test cases that cover all of the document's requirements.

4.Request that the QA lead review the test cases.

5.Execute test cases and look for bugs.

Features : I have written testcase for a website


Registration

Login

Online services

ATM services


1)Registration:

Preconditions: User does not have an existing account with the bank and has downloaded the bank application.

Steps: Fill the registration fields with correct details

Expected Result:
1.The application should validate the provided registration information.

2.If all information is valid and meets the bank's requirements:

3.The application should create a new account for the user.

4.A confirmation message should be displayed, indicating that the registration was successful.

5.The user should be automatically logged into their new account or redirected to the login page.

2)LOGIN

Preconditions: User has a valid account with the bank and has downloaded the bank application.

Steps:

1.Launch the bank application.

2.On the homepage, locate and tap the "Login" button.

3.Enter a valid username and password.

4.Tap the "Login" or "Sign In" button to submit the login credentials.

Expected Result:

The application should validate the provided username and password.

If the credentials are correct, the user should be successfully logged into their account.

If the credentials are incorrect, the application should display an error message, indicating that the login attempt failed.

3)BILL PAY:

Preconditions: User is logged in with sufficient funds.

Steps:

1.Navigate to the "Bill Payment" section.

2.Select a payee, enter the bill amount, and choose the payment date.

3.Confirm the payment.

Expected Result: The bill payment should be successful, and the user's account balance should reflect the payment.


4)View Account Balance:

Preconditions: User is logged in.

Steps:
1.Navigate to the "Account Balance" section.

Expected Result: The user should see their account balance displayed accurately.

5)MAKE A DEPOSIT:

Preconditions: User is logged in and has an active account.

Steps:
1.Navigate to the "Make Deposit" section.

2.Enter a valid deposit amount.

3.Select the account to deposit into.

4.Confirm the transaction.

Expected Result: The deposit should be successful, and the user's account balance should be updated accordingly.

After all testcases are written and testing is done , incase if there is any bug logged the bug in JIRA .Now after lodging it , locate the defect id from JIRA and enter it in document.

JIRA:

Log in to the bug tracking system

Create a New Issue

Select the Issue Type

Fill in the Bug Details

Set Priority and Severity

Assign the Bug

Submit the Bug

Confirmation and Notifications
Monitor and Update
