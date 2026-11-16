# Test Execution Report – QA SHOP

## 1. Project Information

- **Project:** QA SHOP
- **Application:** SauceDemo
- **Testing Type:** Manual Testing
- **Browser:** Safari
- **Execution Status:** In Progress

## 2. Test Execution Summary

| Status | Count |
|---|---:|
| PASS | 16 |
| FAIL | 1 |
| N/A | 1 |
| NOT VERIFIED | 0 |
| **Total** | **18** |

## 3. Test Results

| Test Case ID | Test Case | Status |
|---|---|---|
| TC-001 | Login with valid credentials | PASS |
| TC-002 | Add product to cart | PASS |
| TC-003 | Remove product from cart | PASS |
| TC-004 | Complete checkout process | PASS |
| TC-005 | Checkout with an empty cart | FAIL |
| TC-006 | Valid username and invalid password | PASS |
| TC-007 | Invalid username and valid password | PASS |
| TC-008 | Login with empty username and password | PASS |
| TC-009 | Login with empty password | PASS |
| TC-010 | Login with locked user account | PASS |
| TC-011 | Sort products by price (low to high) | PASS |
| TC-012 | Sort products by price (high to low) | PASS |
| TC-013 | Sort products by name (A to Z) | PASS |
| TC-014 | Sort products by name (Z to A) | PASS |
| TC-015 | Verify cart contents after returning to products | PASS |
| TC-016 | Verify product details | PASS |
| TC-017 | Return to products from product details | PASS |
| TC-018 | Change product quantity | N/A |

## 4. Defects Found

**BUG-001:** Application allows checkout completion without products in the shopping cart.

- Severity: High
- Priority: High
- Status: Open – Retest required

## 5. Test Conclusion

Most executed test cases passed successfully.

One defect was identified during testing: the application allows an order to be completed with an empty shopping cart.

The defect requires further investigation and retesting.

Testing is still in progress.
