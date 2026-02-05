# Login Test Cases

## TC-01: Login with valid credentials
Preconditions:
- User is registered
- Login page is opened

Steps:
1. Enter valid email
2. Enter valid password
3. Click "Login" button

Expected Result:
- User is successfully logged in
- User dashboard is displayed

---

## TC-02: Login with invalid password
Preconditions:
- User is registered
- Login page is opened

Steps:
1. Enter valid email
2. Enter invalid password
3. Click "Login" button

Expected Result:
- Error message is shown
- User is not logged in
