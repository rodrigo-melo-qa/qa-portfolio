# Bug Reports – Login Page

Target Website: https://practicetestautomation.com/practice-test-login/

## BUG-01: Generic error handling for empty username and password
**ID:** BUG-01  
**Title:** Login attempt with both username and password empty shows only generic error handling  
**Severity:** Medium  
**Priority:** Medium  
**Environment:** Chrome on Desktop  

**Steps to Reproduce:**
1. Open the login page
2. Leave username empty
3. Leave password empty
4. Click the Submit button

**Expected Result:**
The page should clearly indicate that both required fields are missing, preferably with field-level validation.

**Actual Result:**
The user remains on the login page and only generic error handling is shown.

---

## BUG-02: No field-specific validation for empty username
**ID:** BUG-02  
**Title:** Empty username does not show field-specific validation message  
**Severity:** Low  
**Priority:** Medium  
**Environment:** Chrome on Desktop  

**Steps to Reproduce:**
1. Open the login page
2. Leave username empty
3. Enter any password
4. Click the Submit button

**Expected Result:**
The page should display a clear validation message for the username field.

**Actual Result:**
The login fails, but no field-specific validation is shown for username.

---

## BUG-03: No field-specific validation for empty password
**ID:** BUG-03  
**Title:** Empty password does not show field-specific validation message  
**Severity:** Low  
**Priority:** Medium  
**Environment:** Chrome on Desktop  

**Steps to Reproduce:**
1. Open the login page
2. Enter a valid username
3. Leave password empty
4. Click the Submit button

**Expected Result:**
The page should display a clear validation message for the password field.

**Actual Result:**
The login fails, but no field-specific validation is shown for password.

---

## BUG-04: Error messaging does not clearly identify which credential is incorrect
**ID:** BUG-04  
**Title:** Login failure message is too generic when invalid credentials are entered  
**Severity:** Low  
**Priority:** Low  
**Environment:** Chrome on Desktop  

**Steps to Reproduce:**
1. Open the login page
2. Enter an invalid username or password
3. Click the Submit button

**Expected Result:**
The message should be clear, user-friendly, and help the user understand that the credentials are invalid.

**Actual Result:**
The system displays a generic failure message without much guidance.
