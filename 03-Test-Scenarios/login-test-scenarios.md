# SauceDemo – Login Test Scenarios

## Module Information

- **Module:** Login
- **Module ID:** MOD-01
- **Testing Type:** Functional Testing
- **Testing Approach:** Manual Testing

## Test Scenarios

| Scenario ID | Test Scenario | Expected Result |
|---|---|---|
| TS-LOGIN-01 | Login using valid username and valid password | User should be redirected to the Products page. |
| TS-LOGIN-02 | Login using valid username and invalid password | An appropriate error message should be displayed. |
| TS-LOGIN-03 | Login using invalid username and valid password | An appropriate error message should be displayed. |
| TS-LOGIN-04 | Login using invalid username and invalid password | An appropriate error message should be displayed. |
| TS-LOGIN-05 | Login with both fields empty | Required field validation should be displayed. |
| TS-LOGIN-06 | Login with empty username and valid password | Username validation message should be displayed. |
| TS-LOGIN-07 | Login with valid username and empty password | Password validation message should be displayed. |
| TS-LOGIN-08 | Login using a username containing spaces | The application should handle the input correctly and display an appropriate response. |
| TS-LOGIN-09 | Verify password masking | Password characters should be masked. |
| TS-LOGIN-10 | Verify login error message | The appropriate error message should be displayed after an unsuccessful login attempt. |
| TS-LOGIN-11 | Login using locked_out_user with valid password | Login should be prevented and a locked-out error message should be displayed. |

## Executed Test Scenario

### TS-LOGIN-11

- **Test Data:** locked_out_user / secret_sauce
- **Expected Result:** Login should be prevented and an appropriate locked-out error message should be displayed.
- **Actual Result:** The application displayed the message: "Epic sadface: Sorry, this user has been locked out."
- **Observed Behavior:** The user remained on the Login page and was not redirected to the Products page.
- **Status:** Passed

## Notes

Only TS-LOGIN-11 has been executed and verified at this stage. The remaining scenarios are planned and have not yet been executed.
