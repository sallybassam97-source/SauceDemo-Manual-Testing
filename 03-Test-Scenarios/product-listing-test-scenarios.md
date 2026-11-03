# SauceDemo – Product Listing Test Scenarios

## Module Information

- **Module:** Product Listing
- **Module ID:** MOD-02
- **Testing Type:** Functional Testing
- **Testing Approach:** Manual Testing

## Test Scenarios

| Scenario ID | Test Scenario | Expected Result |
|---|---|---|
| TS-PRODUCT-01 | Verify all products are displayed | All 6 products should be displayed. |
| TS-PRODUCT-02 | Verify product images are displayed | Each product should have a visible image. |
| TS-PRODUCT-03 | Verify product names are displayed | Each product should have a visible name. |
| TS-PRODUCT-04 | Verify product descriptions are displayed | Each product should have a visible description. |
| TS-PRODUCT-05 | Verify product prices are displayed | Each product should have a visible price. |
| TS-PRODUCT-06 | Verify Add to Cart buttons are displayed | Each product should have an Add to Cart button. |
| TS-PRODUCT-07 | Verify sorting by Name (A to Z) | Products should be sorted alphabetically in ascending order. |
| TS-PRODUCT-08 | Verify sorting by Name (Z to A) | Products should be sorted alphabetically in descending order. |
| TS-PRODUCT-09 | Verify sorting by Price (low to high) | Products should be sorted by price in ascending order. |
| TS-PRODUCT-10 | Verify sorting by Price (high to low) | Products should be sorted by price in descending order. |
| TS-PRODUCT-11 | Verify navigation to the Product Details page | Clicking a product name or image should open its Product Details page. |
| TS-PRODUCT-12 | Verify product information on the Product Details page | Product name, image, description, and price should be displayed correctly. |
| TS-PRODUCT-13 | Verify that a product can be added to the cart | The Add to Cart button should change to Remove, and the cart badge should display 1. |
| TS-PRODUCT-14 | Verify that a product can be removed from the cart | The Remove button should change back to Add to Cart, and the cart badge should disappear. |
| TS-PRODUCT-15 | Verify that the cart badge is updated when a product is added or removed | The cart badge should display the correct number of added products and disappear when the cart is empty. |
| TS-PRODUCT-16 | Verify that clicking the Back to Products button returns the user to the Products page | The user should be redirected to the Products page. |
| TS-PRODUCT-17 | Verify that the product cart status is maintained when navigating between the Products and Product Details pages | The product should remain marked as Remove if it has already been added to the cart. |
| TS-PRODUCT-18 | Verify that a product can be removed from the cart on the Product Details page | The product should be removed from the cart, the button should change to Add to Cart, and the cart badge should disappear. |
| TS-PRODUCT-19 | Verify that the cart status is updated when a product is removed from the Product Details page | The cart badge should be updated to reflect the removal of the product. |

## Notes

These scenarios were identified during the exploration phase. Detailed test execution and actual results will be documented later in the Test Cases section.
