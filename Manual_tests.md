# Manual Test Cases

## Test Case 1 – Valid Login

- **Test Case ID:** TC_001
- **Module:** Authentication
- **Objective:** Verify user can log in with valid credentials
- **Precondition:** User account exists

### Steps:
1. Navigate to Login page
2. Enter valid username
3. Enter valid password
4. Click Login button

### Expected Result:
User is successfully logged in and redirected to dashboard.


---

## Test Case 2 – Invalid Login

- **Test Case ID:** TC_002
- **Module:** Authentication
- **Objective:** Verify system handles invalid credentials correctly

### Steps:
1. Enter invalid username/password
2. Click Login button

### Expected Result:
Error message is displayed.
User remains on login page.


---

## Test Case 3 – Empty Field Validation

- **Test Case ID:** TC_003
- **Module:** Authentication
- **Objective:** Verify system validates empty fields

### Steps:
1. Leave username empty
2. Leave password empty
3. Click Login

### Expected Result:
Validation message appears indicating required fields.


---

## Test Case 4 – Navigation Links

- **Test Case ID:** TC_004
- **Module:** Navigation
- **Objective:** Verify all main menu links work correctly

### Steps:
1. Click each main menu link (Home, About, Contact, etc.)

### Expected Result:
Correct corresponding page loads without error.
