# SauceDemo – Product Listing Test Cases

## Module Information

- **Module:** Product Listing
- **Module ID:** MOD-02
- **Testing Type:** Functional Testing
- **Testing Approach:** Manual Testing
- **Test Environment:** Windows 11, Google Chrome

## Test Cases

### TC-PRODUCT-01: Verify all products are displayed

- **Scenario ID:** TS-PRODUCT-01
- **Preconditions:** User is logged in successfully.
- **Test Steps:**
  1. Navigate to the Products page.
  2. Count the displayed products.
- **Test Data:** Standard user credentials.
- **Expected Result:** All 6 products should be displayed.
- **Actual Result:** All 6 products were displayed.
- **Status:** Pass

### TC-PRODUCT-02: Verify product images are displayed

- **Scenario ID:** TS-PRODUCT-02
- **Preconditions:** User is on the Products page.
- **Test Steps:**
  1. Inspect the images of all displayed products.
- **Expected Result:** Each product should have a visible image.
- **Actual Result:** Product images were displayed correctly.
- **Status:** Pass

### TC-PRODUCT-03: Verify product names are displayed

- **Scenario ID:** TS-PRODUCT-03
- **Preconditions:** User is on the Products page.
- **Test Steps:**
  1. Inspect the names of all displayed products.
- **Expected Result:** Each product should have a visible name.
- **Actual Result:** Product names were displayed.
- **Status:** Pass

### TC-PRODUCT-04: Verify product descriptions are displayed

- **Scenario ID:** TS-PRODUCT-04
- **Preconditions:** User is on the Products page.
- **Test Steps:**
  1. Inspect the descriptions of all displayed products.
- **Expected Result:** Each product should have a visible description.
- **Actual Result:** Product descriptions were displayed.
- **Status:** Pass

### TC-PRODUCT-05: Verify product prices are displayed

- **Scenario ID:** TS-PRODUCT-05
- **Preconditions:** User is on the Products page.
- **Test Steps:**
  1. Inspect the prices of all displayed products.
- **Expected Result:** Each product should have a visible price.
- **Actual Result:** Product prices were displayed.
- **Status:** Pass

### TC-PRODUCT-06: Verify Add to Cart buttons are displayed

- **Scenario ID:** TS-PRODUCT-06
- **Preconditions:** User is on the Products page.
- **Test Steps:**
  1. Inspect the buttons displayed under each product.
- **Expected Result:** Each product should have an Add to Cart button.
- **Actual Result:** Add to Cart buttons were displayed.
- **Status:** Pass

### TC-PRODUCT-07: Verify sorting by Name (A to Z)

- **Scenario ID:** TS-PRODUCT-07
- **Preconditions:** User is on the Products page.
- **Test Steps:**
  1. Open the sorting dropdown.
  2. Select Name (A to Z).
  3. Check the order of the products.
- **Expected Result:** Products should be sorted alphabetically in ascending order.
- **Actual Result:** Sorting worked as expected.
- **Status:** Pass

### TC-PRODUCT-08: Verify sorting by Name (Z to A)

- **Scenario ID:** TS-PRODUCT-08
- **Preconditions:** User is on the Products page.
- **Test Steps:**
  1. Open the sorting dropdown.
  2. Select Name (Z to A).
  3. Check the order of the products.
- **Expected Result:** Products should be sorted alphabetically in descending order.
- **Actual Result:** Sorting worked as expected.
- **Status:** Pass

### TC-PRODUCT-09: Verify sorting by Price (low to high)

- **Scenario ID:** TS-PRODUCT-09
- **Preconditions:** User is on the Products page.
- **Test Steps:**
  1. Open the sorting dropdown.
  2. Select Price (low to high).
  3. Check the order of the products.
- **Expected Result:** Products should be sorted by price in ascending order.
- **Actual Result:** Sorting worked as expected.
- **Status:** Pass

### TC-PRODUCT-10: Verify sorting by Price (high to low)

- **Scenario ID:** TS-PRODUCT-10
- **Preconditions:** User is on the Products page.
- **Test Steps:**
  1. Open the sorting dropdown.
  2. Select Price (high to low).
  3. Check the order of the products.
- **Expected Result:** Products should be sorted by price in descending order.
- **Actual Result:** Sorting worked as expected.
- **Status:** Pass

### TC-PRODUCT-11: Verify navigation to the Product Details page

- **Scenario ID:** TS-PRODUCT-11
- **Preconditions:** User is on the Products page.
- **Test Steps:**
  1. Click on a product name.
- **Expected Result:** The selected product's Product Details page should open.
- **Actual Result:** The Product Details page opened successfully.
- **Status:** Pass

### TC-PRODUCT-12: Verify product information on the Product Details page

- **Scenario ID:** TS-PRODUCT-12
- **Preconditions:** User is on a Product Details page.
- **Test Steps:**
  1. Inspect the product name.
  2. Inspect the product image.
  3. Inspect the product description.
  4. Inspect the product price.
- **Expected Result:** Product name, image, description, and price should be displayed.
- **Actual Result:** Product information was displayed.
- **Status:** Pass

### TC-PRODUCT-13: Verify that a product can be added to the cart

- **Scenario ID:** TS-PRODUCT-13
- **Preconditions:** User is on the Products page and the cart is empty.
- **Test Steps:**
  1. Click Add to Cart for the first product.
  2. Observe the button and cart badge.
- **Expected Result:** The button should change to Remove, and the cart badge should display 1.
- **Actual Result:** The button changed to Remove, and the cart badge displayed 1.
- **Status:** Pass

### TC-PRODUCT-14: Verify that a product can be removed from the cart

- **Scenario ID:** TS-PRODUCT-14
- **Preconditions:** A product has been added to the cart.
- **Test Steps:**
  1. Click Remove for the selected product.
  2. Observe the button and cart badge.
- **Expected Result:** The button should change to Add to Cart, and the cart badge should disappear.
- **Actual Result:** The button changed to Add to Cart, and the cart badge disappeared.
- **Status:** Pass

### TC-PRODUCT-15: Verify that the cart badge is updated

- **Scenario ID:** TS-PRODUCT-15
- **Preconditions:** User is on the Products page.
- **Test Steps:**
  1. Add a product to the cart.
  2. Observe the cart badge.
  3. Remove the product.
  4. Observe the cart badge again.
- **Expected Result:** The cart badge should display the correct number of added products and disappear when the cart is empty.
- **Actual Result:** The badge displayed 1 after adding the product and disappeared after removing it.
- **Status:** Pass

### TC-PRODUCT-16: Verify navigation back to the Products page

- **Scenario ID:** TS-PRODUCT-16
- **Preconditions:** User is on a Product Details page.
- **Test Steps:**
  1. Click Back to Products.
- **Expected Result:** The user should return to the Products page.
- **Actual Result:** The Products page opened successfully.
- **Status:** Pass

### TC-PRODUCT-17: Verify product cart status is maintained during navigation

- **Scenario ID:** TS-PRODUCT-17
- **Preconditions:** A product has been added to the cart.
- **Test Steps:**
  1. Open the Product Details page for the added product.
  2. Observe the product button.
- **Expected Result:** The button should remain Remove.
- **Actual Result:** The button displayed Remove.
- **Status:** Pass

### TC-PRODUCT-18: Verify product removal from the Product Details page

- **Scenario ID:** TS-PRODUCT-18
- **Preconditions:** A product has been added to the cart and its Product Details page is open.
- **Test Steps:**
  1. Click Remove.
  2. Observe the button and cart badge.
- **Expected Result:** The button should change to Add to Cart, and the cart badge should disappear.
- **Actual Result:** The button changed to Add to Cart, and the cart badge disappeared.
- **Status:** Pass

### TC-PRODUCT-19: Verify cart badge update after removal from Product Details

- **Scenario ID:** TS-PRODUCT-19
- **Preconditions:** A product has been added to the cart.
- **Test Steps:**
  1. Open the Product Details page.
  2. Click Remove.
  3. Check the cart badge.
- **Expected Result:** The cart badge should disappear when the only product is removed.
- **Actual Result:** The cart badge disappeared.
- **Status:** Pass

## Notes

Test cases were documented based on the observed behavior during the manual exploration phase.
