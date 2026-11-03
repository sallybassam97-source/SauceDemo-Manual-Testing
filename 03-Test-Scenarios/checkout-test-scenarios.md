# SauceDemo – Checkout Test Scenarios

## Module Information

- **Module:** Checkout
- **Module ID:** MOD-06
- **Testing Type:** Functional Testing
- **Testing Approach:** Manual Testing

## Test Scenarios

| Scenario ID | Test Scenario | Expected Result |
|---|---|---|
| TS-CHECKOUT-01 | Verify navigation to the Checkout Information page | Clicking the Checkout button should navigate the user to the Checkout: Your Information page. |
| TS-CHECKOUT-02 | Verify validation when all checkout information fields are empty | An error message "Error: First Name is required" should be displayed. |
| TS-CHECKOUT-03 | Verify validation when Last Name and Postal Code fields are empty | An error message "Error: Last Name is required" should be displayed. |
| TS-CHECKOUT-04 | Verify validation when Postal Code field is empty | An error message "Error: Postal Code is required" should be displayed. |
| TS-CHECKOUT-05 | Verify checkout information submission with valid data | The user should be able to proceed to the Checkout: Overview page after entering all required information. |
| TS-CHECKOUT-06 | Verify order information on the Checkout Overview page | Product information, Payment Information, Shipping Information, Item Total, Tax, and Total should be displayed. |
| TS-CHECKOUT-07 | Verify successful order completion | Clicking the Finish button should complete the order and display the order confirmation message. |
| TS-CHECKOUT-08 | Verify order confirmation message | The message "Thank you for your order!" should be displayed after successful checkout. |
| TS-CHECKOUT-09 | Verify navigation back to the Products page after order completion | Clicking the Back Home button should redirect the user to the Products page. |

## Notes

These scenarios were identified during the exploration phase. Detailed test execution and actual results will be
