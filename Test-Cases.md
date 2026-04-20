# Test Cases – Login Page

Target Website: https://practicetestautomation.com/practice-test-login/

## TC-01: Login with valid credentials
**Precondition:** User is on the login page.

**Steps:**
1. Enter valid username
2. Enter valid password
3. Click the Submit button

**Expected Result:**
User is redirected to the secure page and login is successful.

---

## TC-02: Login with invalid password
**Precondition:** User is on the login page.

**Steps:**
1. Enter valid username
2. Enter an invalid password
3. Click the Submit button

**Expected Result:**
An error message is displayed and login is not successful.

---

## TC-03: Login with invalid username
**Precondition:** User is on the login page.

**Steps:**
1. Enter an invalid username
2. Enter valid password
3. Click the Submit button

**Expected Result:**
An error message is displayed and login is not successful.

---

## TC-04: Login with both fields empty
**Precondition:** User is on the login page.

**Steps:**
1. Leave username empty
2. Leave password empty
3. Click the Submit button

**Expected Result:**
User remains on the login page and validation or error handling is triggered.

---

## TC-05: Login with empty username only
**Precondition:** User is on the login page.

**Steps:**
1. Leave username empty
2. Enter a valid password
3. Click the Submit button

**Expected Result:**
User remains on the login page and validation or error handling is triggered.

---

## TC-06: Login with empty password only
**Precondition:** User is on the login page.

**Steps:**
1. Enter a valid username
2. Leave password empty
3. Click the Submit button

**Expected Result:**
User remains on the login page and validation or error handling is triggered.

---

## TC-07: Verify password field masks characters
**Precondition:** User is on the login page.

**Steps:**
1. Click on the password field
2. Type any password

**Expected Result:**
Typed characters are hidden or masked in the password field.

---

## TC-08: Verify successful logout
**Precondition:** User is logged in and on the secure page.

**Steps:**
1. Click the Log out button

**Expected Result:**
User is logged out and redirected away from the secure page.
