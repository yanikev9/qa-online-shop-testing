# Bug Report: Account is not locked after multiple failed login attempts

## Summary
User account is not blocked after multiple incorrect login attempts.

## Environment
- Test Environment
- Web version: 1.2.0
- Browser: Chrome 121
- OS: Windows 11

## Preconditions
- User account exists
- User is on login page

## Steps to Reproduce
1. Enter valid email
2. Enter incorrect password
3. Click Login
4. Repeat steps 1–3 five times

## Expected Result
After several failed login attempts, the account should be temporarily locked.

## Actual Result
User can continue attempting to log in without any restrictions.

## Severity
Major

## Priority
High
