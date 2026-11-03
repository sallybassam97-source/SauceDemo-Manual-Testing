# SauceDemo – Checkout Test Cases

## TC-CHECKOUT-01 – Navigate to Checkout Information Page

**Scenario ID:** TS-CHECKOUT-01

**Preconditions:**
- User is logged in.
- At least one product is added to the cart.

**Test Steps:**
1. Open the Cart page.
2. Click the Checkout button.

**Expected Result:**
The Checkout: Your Information page should be displayed.

**Actual Result:**
The Checkout: Your Information page was displayed successfully.

**Status:** Pass

---

## TC-CHECKOUT-02 – Verify Required First Name Validation

**Scenario ID:** TS-CHECKOUT-02

**Preconditions:**
- User is on the Checkout Information page.

**Test Steps:**
1. Leave all fields empty.
2. Click Continue.

**Expected Result:**
An error message indicating that First Name is required should be displayed.

**Actual Result:**
The error message "Error: First Name is required" was displayed.

**Status:** Pass

---

## TC-CHECKOUT-03 – Verify Required Last Name Validation

**Scenario ID:** TS-CHECKOUT-03

**Preconditions:**
- User is on the Checkout Information page.

**Test Steps:**
1. Enter a valid First Name.
2. Leave Last Name and Postal Code empty.
3. Click Continue.

**Test Data:**
- First Name: Sally
- Last Name: Empty
- Postal Code: Empty

**Expected Result:**
An error message indicating that Last Name is required should be displayed.

**Actual Result:**
The error message "Error: Last Name is required" was displayed.

**Status:** Pass

---

## TC-CHECKOUT-04 – Verify Required Postal Code Validation

**Scenario ID:** TS-CHECKOUT-04

**Preconditions:**
- User is on the Checkout Information page.

**Test Steps:**
1. Enter a valid First Name and Last Name.
2. Leave Postal Code empty.
3. Click Continue.

**Test Data:**
- First Name: Sally
- Last Name: Test
- Postal Code: Empty

**Expected Result:**
An error message indicating that Postal Code is required should be displayed.

**Actual Result:**
The error message "Error: Postal Code is required" was displayed.

**Status:** Pass

---

## TC-CHECKOUT-05 – Continue Checkout With Valid Information

**Scenario ID:** TS-CHECKOUT-05

**Preconditions:**
- User is on the Checkout Information page.

**Test Steps:**
1. Enter a valid First Name.
2. Enter a valid Last Name.
3. Enter a valid Postal Code.
4. Click Continue.

**Test Data:**
- First Name: Sally
- Last Name: Test
- Postal Code: 11111

**Expected Result:**
The Checkout: Overview page should be displayed.

**Actual Result:**
The Checkout: Overview page was displayed successfully.

**Status:** Pass

---

## TC-CHECKOUT-06 – Verify Order Information on Checkout Overview

**Scenario ID:** TS-CHECKOUT-06

**Preconditions:**
- User has reached the Checkout Overview page.

**Test Steps:**
1. Review the order summary.
2. Verify the product information.
3. Review Payment Information and Shipping Information.
4. Verify Item Total, Tax, and Total.

**Expected Result:**
All order details and summary information should be displayed.

**Actual Result:**
Product information, Payment Information, Shipping Information, Item Total, Tax, and Total were displayed.

**Status:** Pass

---

## TC-CHECKOUT-07 – Complete an Order Successfully

**Scenario ID:** TS-CHECKOUT-07

**Preconditions:**
- User is on the Checkout Overview page.

**Test Steps:**
1. Click the Finish button.

**Expected Result:**
The order should be completed and the order confirmation page should be displayed.

**Actual Result:**
The order confirmation page was displayed successfully.

**Status:** Pass

---

## TC-CHECKOUT-08 – Verify Order Confirmation Message

**Scenario ID:** TS-CHECKOUT-08

**Preconditions:**
- User has completed the order.

**Test Steps:**
1. Review the order confirmation page.
2. Verify the confirmation message.

**Expected Result:**
The order confirmation message should be displayed.

**Actual Result:**
"Thank you for your order!" and the order dispatch message were displayed.

**Status:** Pass

---

## TC-CHECKOUT-09 – Verify Back Home Navigation

**Scenario ID:** TS-CHECKOUT-09

**Preconditions:**
- User is on the order confirmation page.

**Test Steps:**
1. Click the Back Home button.

**Expected Result:**
The user should be redirected to the Products page.

**Actual Result:**
The Products page was displayed successfully.

**Status:** Pass
