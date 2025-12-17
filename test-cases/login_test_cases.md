# Login Test Cases - SauceDemo

## TC-LOGIN-001: Login with valid credentials
**Description:** Verify that user can log in with valid credentials
**Preconditions:** User is on the login page
**Steps:**
1. Navigate to https://www.saucedemo.com
2. Enter a valid username
3. Enter the correct password
4. Click Login button
**Expected Result:** User gets redirected to Products page

---

## TC-LOGIN-002: Login with invalid password
**Description:** Verify error handling for invalid password
**Preconditions:** User is on the login page
**Steps:**
1. Enter valid username
2. Enter invalid password
3. Click Login button
**Expected Result:** Invlaid credentials error message displayed
**Related Bug:** [BUG-001-login-error-message](../bugs/BUG-001-login-error-message.md)

---

## TC-LOGIN-003: Login with invalid username
**Description:** Verify error handling for invalid username
**Preconditions:** User is on the login page
**Steps:**
1. Enter invalid username
2. Enter valid password
3. Click Login button
**Expected Result:** Invlaid credentials error message displayed
**Related Bug:** [BUG-001-login-error-message](../bugs/BUG-001-login-error-message.md)

---

## TC-LOGIN-004: Login with empty username
**Description:** Verify validation with missing username
**Preconditions:** User is on the login page
**Steps:**
1. Leave username empty
2. Enter valid password
3. Click Login button
**Expected Result:** Username required error message displayed
**Related Bug:** [BUG-003-login-empty-credentials](../bugs/BUG-003-login-empty-credentials.md)

---

## TC-LOGIN-005: Login with empty password
**Description:** Verify validation with missing password
**Preconditions:** User is on the login page
**Steps:**
1. Enter valid username
2. Leave password empty
3. Click Login button
**Expected Result:** Password required error message displayed
**Related Bug:** [BUG-003-login-empty-credentials](../bugs/BUG-003-login-empty-credentials.md)

---

## TC-LOGIN-006: Login with locked-out user
**Description:** Verify behavior for locked-out users
**Preconditions:** User is on the login page
**Steps:**
1. Enter locked_out_user for username
2. Enter valid password
3. Click Login button
**Expected Result:** User is locked out error message displayed
**Related Bug:** [BUG-004-login-locked-out-user](../bugs/BUG-004-login-locked-out-user.md)