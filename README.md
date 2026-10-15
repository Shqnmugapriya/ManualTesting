# 🧪 Manual Testing – SauceDemo Web Application

A manual software testing project focused on validating the functionality, usability, and reliability of the SauceDemo e-commerce web application.

## 📌 Project Overview

Manual testing is a software testing technique in which testers execute test cases manually to verify whether an application behaves as expected.

In this project, the SauceDemo web application is tested to identify functional issues, validate user workflows, and ensure that important features work according to the expected results.

The testing process includes test scenario identification, test case preparation, test execution, actual-versus-expected result comparison, and defect reporting.

## 🎯 Objectives

- Validate the login functionality.
- Verify product listing and product details.
- Test shopping cart operations.
- Validate sorting and filtering options.
- Verify the checkout process.
- Identify and document application defects.
- Ensure a smooth and user-friendly shopping experience.

## 🌐 Application Under Test

**Application:** SauceDemo

**Website:** https://www.saucedemo.com/

**Testing Type:** Manual Testing

**Testing Approach:** Black-box testing

## 🛠️ Testing Scope

| Module | Testing Activities |
|---|---|
| Login | Valid login, invalid login, empty fields |
| Products | Product display, product information |
| Sorting | Price sorting and name sorting |
| Shopping Cart | Add items, remove items, verify cart |
| Checkout | Enter customer information and continue |
| Order Completion | Verify order summary and confirmation |
| Logout | Verify logout functionality |

## 🧪 Test Scenarios

### 1. Login Module
- Verify login using valid credentials.
- Verify login using an invalid username.
- Verify login using an incorrect password.
- Verify behavior when username or password is empty.
- Verify navigation after successful login.

### 2. Product Module
- Verify that products are displayed correctly.
- Verify product names, prices, and descriptions.
- Verify sorting products by name.
- Verify sorting products by price.

### 3. Shopping Cart Module
- Verify adding a product to the cart.
- Verify adding multiple products.
- Verify removing a product from the cart.
- Verify the cart item count.
- Verify that selected products appear in the cart.

### 4. Checkout Module
- Verify navigation to checkout.
- Verify required customer information fields.
- Verify validation for missing information.
- Verify order summary and total price.
- Verify successful order completion.

### 5. Logout Module
- Verify logout from the application.
- Verify redirection to the login page.
- Verify access behavior after logout.

## 📋 Sample Test Cases

| Test Case ID | Test Scenario | Expected Result |
|---|---|---|
| TC_LOGIN_001 | Login with valid credentials | User should navigate to the products page |
| TC_LOGIN_002 | Login with invalid credentials | An appropriate error message should appear |
| TC_LOGIN_003 | Submit empty login fields | Required-field validation should be displayed |
| TC_CART_001 | Add a product to the cart | Product should be added successfully |
| TC_CART_002 | Remove a product from the cart | Product should be removed |
| TC_SORT_001 | Sort products by price | Products should appear in the selected price order |
| TC_CHECKOUT_001 | Continue checkout with valid details | User should proceed to the order overview |
| TC_CHECKOUT_002 | Complete a valid order | Order confirmation should be displayed |
| TC_LOGOUT_001 | Log out of the application | User should return to the login page |

*Note: Record the actual results and pass/fail status only after executing each test case.*

## 🔄 Testing Process

1. **Requirement Analysis:** Understand the application's features and expected behavior.
2. **Test Planning:** Identify modules, testing scope, and test scenarios.
3. **Test Case Design:** Prepare test cases with preconditions, steps, and expected results.
4. **Test Execution:** Execute each test case manually.
5. **Result Comparison:** Compare actual results with expected results.
6. **Defect Reporting:** Document unexpected behavior with reproduction steps and evidence.
7. **Retesting:** Verify fixes when defects are resolved.
8. **Regression Testing:** Check that changes have not affected existing functionality.

## 🐞 Defect Reporting Template

When an issue is identified, document it using the following format:

| Field | Description |
|---|---|
| Bug ID | Unique defect identifier |
| Title | Short description of the issue |
| Module | Affected application module |
| Steps to Reproduce | Steps required to reproduce the issue |
| Expected Result | Correct expected behavior |
| Actual Result | Observed behavior |
| Severity | Impact of the defect |
| Priority | Urgency of fixing the defect |
| Status | New, Open, Fixed, Retested, or Closed |

## 📊 Test Execution Summary

Update this section after completing your testing.

| Metric | Result |
|---|---|
| Total Test Cases | To be updated |
| Passed | To be updated |
| Failed | To be updated |
| Blocked | To be updated |
| Not Executed | To be updated |

## 🧰 Tools Used

- **Browser:** Google Chrome or another supported browser
- **Test Documentation:** Markdown / Microsoft Excel
- **Defect Tracking:** GitHub Issues or a test management tool, if used
- **Application:** SauceDemo

## 📚 Key Learnings

- Understanding the software testing life cycle (STLC).
- Preparing effective manual test cases.
- Applying positive and negative testing.
- Validating end-to-end user workflows.
- Identifying and documenting defects.
- Understanding severity, priority, retesting, and regression testing.
- Comparing actual results with expected results.

## 👩‍💻 Author
Shanmugapriya S
B.Tech – Artificial Intelligence and Data Science
