# Authentication Test Cases

| ID | Title | Preconditions | Steps | Test Data | Expected Result |
|----|------|---------------|------|-----------|----------------|
| TC-01 | Successful user registration | User is on registration page | 1. Enter valid email 2. Enter valid password 3. Click Register | email: test@test.com password: Test12345 | User account is created successfully |
| TC-02 | Registration with existing email | User is on registration page | 1. Enter already registered email 2. Enter password 3. Click Register | email: existing@test.com | Error message "User already exists" |
| TC-03 | Registration with invalid email | User is on registration page | 1. Enter invalid email format 2. Enter password 3. Click Register | email: test@test password: Test12345 | Validation error is displayed |
| TC-04 | Login with valid credentials | User account exists | 1. Open login page 2. Enter email 3. Enter password 4. Click Login | email: test@test.com password: Test12345 | User successfully logged in |
| TC-05 | Login with incorrect password | User account exists | 1. Open login page 2. Enter email 3. Enter wrong password 4. Click Login | password: Wrong123 | Error message "Invalid credentials" |
| TC-06 | Login with empty fields | User is on login page | 1. Click Login without entering data | empty fields | Validation errors displayed |
