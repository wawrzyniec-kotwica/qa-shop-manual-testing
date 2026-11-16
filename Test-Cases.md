# Test Cases – QA SHOP

**Application:** SauceDemo  
**Testing Type:** Manual Testing  
**Browser:** Safari  
**Status:** Test cases created based on practical testing.

## TC-001 – Login with valid credentials

**Preconditions:**
- User has valid login credentials.

**Test Steps:**
1. Open the application.
2. Enter a valid username.
3. Enter a valid password.
4. Click Login.

**Expected Result:**
- User is successfully logged in.
- Product list is displayed.

**Actual Result:** User logged in successfully and the product list was displayed.  
**Status:** PASS

---

## TC-002 – Add product to cart

**Preconditions:**
- User is logged in.
- Product list is displayed.

**Test Steps:**
1. Click Add to cart on a product.
2. Open the shopping cart.

**Expected Result:**
- Selected product is displayed in the cart.
- Cart counter increases by one.

**Actual Result:** Product was successfully added to the cart.  
**Status:** PASS

---

## TC-003 – Remove product from cart

**Preconditions:**
- User is logged in.
- At least one product has been added to the cart.

**Test Steps:**
1. Open the shopping cart.
2. Click Remove next to the product.
3. Check the cart contents.

**Expected Result:**
- Product is removed from the cart.
- Cart is empty if no other products were added.

**Actual Result:** Product was successfully removed.  
**Status:** PASS

---

## TC-004 – Complete checkout process

**Preconditions:**
- User is logged in.
- At least one product is in the cart.

**Test Steps:**
1. Open the shopping cart.
2. Click Checkout.
3. Enter checkout information.
4. Click Continue.
5. Review the order summary.
6. Click Finish.

**Expected Result:**
- Checkout process is completed.
- Order confirmation is displayed.

**Actual Result:** Checkout process was completed successfully.  
**Status:** PASS

---

## TC-005 – Checkout with an empty cart

**Preconditions:**
- User is logged in.
- Shopping cart is empty.

**Test Steps:**
1. Open the shopping cart.
2. Attempt to proceed to checkout.
3. Complete the checkout steps if the application allows it.

**Expected Result:**
- Application should prevent placing an order without products.

**Actual Result:** Application allowed an order to be completed without products during the observed test.  
**Status:** FAIL

**Related Bug:** BUG-001

---

## TC-006 – Login with valid username and invalid password

**Test Steps:**
1. Open the login page.
2. Enter a valid username.
3. Enter an incorrect password.
4. Click Login.

**Expected Result:**
- Login is rejected.
- An error message is displayed.

**Actual Result:** Login was rejected.  
**Status:** PASS

---

## TC-007 – Login with invalid username and valid password

**Test Steps:**
1. Open the login page.
2. Enter an incorrect username.
3. Enter a valid password.
4. Click Login.

**Expected Result:**
- Login is rejected.
- An error message is displayed.

**Actual Result:** Login was rejected.  
**Status:** PASS

---

## TC-008 – Login with empty username and password

**Test Steps:**
1. Open the login page.
2. Leave both fields empty.
3. Click Login.

**Expected Result:**
- Login is rejected.
- Validation message is displayed.

**Actual Result:** Login was rejected and a validation message was displayed.  
**Status:** PASS

---

## TC-009 – Login with empty password

**Test Steps:**
1. Open the login page.
2. Enter a valid username.
3. Leave the password field empty.
4. Click Login.

**Expected Result:**
- Login is rejected.
- Password validation message is displayed.

**Actual Result:** Login was rejected and a password validation message was displayed.  
**Status:** PASS

---

## TC-010 – Login with locked user account

**Test Steps:**
1. Open the login page.
2. Enter the locked user credentials.
3. Click Login.

**Expected Result:**
- Login is rejected.
- A locked account message is displayed.

**Actual Result:** Login was rejected and a locked account message was displayed.  
**Status:** PASS

---

## TC-011 – Sort products by price (low to high)

**Expected Result:**
- Products are displayed from the lowest to the highest price.

**Actual Result:** Sorting worked correctly.  
**Status:** PASS

---

## TC-012 – Sort products by price (high to low)

**Expected Result:**
- Products are displayed from the highest to the lowest price.

**Actual Result:** Sorting worked correctly.  
**Status:** PASS

---

## TC-013 – Sort products by name (A to Z)

**Expected Result:**
- Products are displayed alphabetically from A to Z.

**Actual Result:** Sorting worked correctly.  
**Status:** PASS

---

## TC-014 – Sort products by name (Z to A)

**Expected Result:**
- Products are displayed alphabetically from Z to A.

**Actual Result:** Sorting worked correctly.  
**Status:** PASS

---

## TC-015 – Verify cart contents after returning to products

**Expected Result:**
- Previously added products remain in the cart.

**Actual Result:** Products remained in the cart after returning to the product list.  
**Status:** PASS

---

## TC-016 – Verify product details

**Expected Result:**
- Product name, description, price and Add to cart functionality are displayed correctly.

**Actual Result:** Product details were displayed correctly.  
**Status:** PASS

---

## TC-017 – Return to products from product details

**Expected Result:**
- User is returned to the product list.

**Actual Result:** User returned to the product list successfully.  
**Status:** PASS

---

## TC-018 – Change product quantity

**Expected Result:**
- User can change the quantity of a product.

**Actual Result:** Quantity modification is not available in the tested application.  
**Status:** N/A
