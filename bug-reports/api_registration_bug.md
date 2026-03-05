# Bug Report: API returns success response but user is not created

## Summary
Registration API returns status 200 and message "registered", but the user is not actually created in the database.

## Environment
- Test Environment
- API endpoint: /register
- Tool: Postman

## Preconditions
- API endpoint is available

## Steps to Reproduce
1. Send POST request to /register
2. Provide valid user data in request body
3. Receive response
4. Check user in database

## Expected Result
If API returns success response, the user should be created in the database.

## Actual Result
API returns status 200 and message "registered", but the user is not present in the database.

## Severity
Critical

## Priority
High
