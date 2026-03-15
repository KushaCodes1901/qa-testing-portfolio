# Test Cases: Login Page

## TC-01 Valid login
- Precondition: User account exists
- Steps:
  1. Open login page
  2. Enter valid email
  3. Enter valid password
  4. Click Login
- Expected Result: User is logged in and redirected to dashboard

## TC-02 Invalid password
- Precondition: User account exists
- Steps:
  1. Open login page
  2. Enter valid email
  3. Enter invalid password
  4. Click Login
- Expected Result: Error message is shown and user remains on login page
