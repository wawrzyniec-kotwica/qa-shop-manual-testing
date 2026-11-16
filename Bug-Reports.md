# Bug Reports – QA SHOP

**Application:** SauceDemo  
**Testing Type:** Manual Testing  
**Browser:** Safari

---

## BUG-001 – Order can be completed with an empty shopping cart

**Bug ID:** BUG-001

**Title:** Application allows checkout completion without any products in the shopping cart.

**Environment:**
- Application: SauceDemo
- Browser: Safari
- Testing Type: Manual Testing

**Preconditions:**
- User is logged in.
- Shopping cart is empty.

**Steps to Reproduce:**
1. Open the application.
2. Log in with valid credentials.
3. Add a product to the shopping cart.
4. Open the shopping cart.
5. Remove the product.
6. Proceed to Checkout.
7. Enter the required checkout information.
8. Continue and attempt to finish the order.

**Expected Result:**
- Application should prevent order completion when the shopping cart is empty.
- An appropriate validation message should be displayed.

**Actual Result:**
- Application allows the user to complete an order without any products.

**Severity:** High

**Priority:** High

**Status:** Open – Retest failed

**Related Test Case:** TC-005

---

## Bug Report Summary

| Bug ID | Title | Severity | Priority | Status |
|---|---|---|---|---|
| BUG-001 | Order can be completed with an empty cart | High | High | Open – Retest failed |

---

**Retest Result:**
- The bug still occurs.
- Checkout can still be completed with an empty cart.
- **Retest Status:** FAIL
- **Bug Status:** OPEN

*Only defects actually observed during testing are included in this document.*
