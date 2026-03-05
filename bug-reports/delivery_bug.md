# Bug Report: Incorrect Delivery Price Display

## Summary
Delivery cost is displayed incorrectly in the order checkout page when the order total exceeds the free delivery threshold.

## Environment
- Test Environment
- Web version: 1.2.0
- Browser: Chrome 121
- OS: Windows 11

## Preconditions
- User opened product catalog
- Cart is empty

## Steps to Reproduce
1. Add products to cart with total price = 5001
2. Go to checkout page
3. Check delivery price
4. Complete the order

## Expected Result
If order total is greater than 5000, delivery should be free and displayed as **0**.

## Actual Result
Checkout page shows delivery cost **300**, but final order receipt shows delivery cost **0**.

## Severity
Trivial

## Priority
High
