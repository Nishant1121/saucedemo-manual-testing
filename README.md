# SauceDemo Manual Testing

A manual testing project for the SauceDemo web application, covering Login, Cart, and Checkout modules.

This repository contains structured test cases, test data, expected results, actual results, post-conditions, and execution status documented in Excel.

## Application Under Test

- **Application:** SauceDemo
- **Testing Type:** Manual Testing
- **Testing Approach:** Functional Testing
- **Test Documentation Tool:** Microsoft Excel
- **Tester:** Nishant Kumar

## Testing Scope

The following modules have been tested:

- Login
- Cart
- Checkout

---

## 1. Login Testing

The Login module was tested using positive and negative test scenarios.

### Test Scenarios Covered

- Login with valid username and password
- Login with valid username and invalid password
- Login with invalid username and valid password
- Login with invalid username and invalid password
- Login with empty username and password
- Login with valid username and empty password
- Login with locked user account
- Username field case-sensitivity validation

### Test Cases

**Total Test Cases:** 8

**Execution Status:** 8 Passed

The test cases include:

- Test Case ID
- Test Scenario
- Test Case
- Pre-Condition
- Test Steps
- Test Data
- Expected Result
- Post-Condition
- Actual Result
- Pass/Fail Status

### Documentation

`Sauce Demo Login Testing.xlsx`

---

## 2. Cart Testing

The Cart module was tested to verify the core shopping cart functionality.

### Testing Areas

- Adding products to the cart
- Adding multiple products
- Verifying cart item count
- Verifying products displayed in the cart
- Removing products from the cart
- Verifying cart after product removal
- Cart navigation
- Continue shopping functionality

### Documentation

`Cart and Checkout.xlsx`

---

## 3. Checkout Testing

The Checkout module was tested as part of the complete shopping workflow.

### Testing Areas

- Navigating from Cart to Checkout
- Checkout information
- Required field validation
- Entering customer information
- Continuing through the checkout process
- Verifying order summary
- Completing the order
- Verifying successful order completion

### Documentation

`Cart and Checkout.xlsx`

---

## Testing Progress

| Module | Test Cases | Status |
|---|---:|---|
| Login | 8 | Completed |
| Cart | Documented | Completed |
| Checkout | Documented | Completed |

---

## Test Documentation

| File | Module |
|---|---|
| `Sauce Demo Login Testing.xlsx` | Login |
| `Cart and Checkout.xlsx` | Cart & Checkout |

---

## Test Case Documentation Format

Each test case is documented using a structured format:

1. Test Case ID
2. Test Scenario
3. Test Case
4. Pre-Condition
5. Test Steps
6. Test Data
7. Expected Result
8. Post-Condition
9. Actual Result
10. Status (Pass/Fail)

This format helps maintain clear and traceable test execution records.

---

## Testing Techniques Practiced

- Functional Testing
- Positive Testing
- Negative Testing
- Boundary / Validation Testing
- UI Testing
- Input Validation
- Error Message Verification
- End-to-End Testing
- Test Case Design
- Test Execution
- Test Documentation

---

## Repository Structure

```text
saucedemo-manual-testing/
│
├── README.md
│
├── Sauce Demo Login Testing.xlsx
│
└── Cart and Checkout.xlsx
