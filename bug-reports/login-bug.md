# Bug Report: Login allows empty password

ID: BUG-01

Title:
Login allows user to submit form with empty password

Environment:
- OS: Windows 10
- Browser: Chrome
- Version: latest

Preconditions:
- User is registered
- Login page is opened

Steps to Reproduce:
1. Enter valid email
2. Leave password field empty
3. Click "Login" button

Actual Result:
- Login request is sent
- No validation message is shown

Expected Result:
- Validation message should be displayed
- User should not be logged in

Severity:
Major

Priority:
High
