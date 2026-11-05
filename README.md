# E-Commerce Platform

## Project Overview

The E-Commerce Platform project focuses on organizing and managing the major modules required for an online shopping system. The project is divided into different functional modules to make development, management and tracking easier.

GitHub Projects is used to organize the modules, assign tasks and monitor the progress of each module through a Kanban board.

## Project Objectives

- Organize the major functionalities of an e-commerce platform.
- Divide the application into manageable modules.
- Track the development progress of each module.
- Identify pending and ongoing tasks.
- Maintain project activities using GitHub Issues.
- Improve project organization and task management.

## Project Modules

The project contains the following modules:

| No. | Module | GitHub Issue | Status |
|---|---|---|---|
| 1 | User Module | #3 | Done |
| 2 | Product Module | #4 | Done |
| 3 | Search Module | #5 | Done |
| 4 | Cart Module | #6 | In Progress |
| 5 | Order Module | #7 | In Progress |
| 6 | Payment Module | #8 | Todo |
| 7 | Admin Module | #9 | Todo |
| 8 | Delivery Module | #10 | Todo |
| 9 | Review Module | #11 | Todo |
| 10 | Testing Module | #12 | Todo |

## Module Descriptions

### 1. User Module
Handles user registration, login, authentication and account-related activities. It allows customers to create accounts and access the platform securely.

### 2. Product Module
Manages product information, including product names, descriptions, images, prices and availability.

### 3. Search Module
Allows customers to search for products and find relevant items based on their search keywords.

### 4. Cart Module
Allows customers to add products to their shopping cart, update quantities, remove items and view the total price.

### 5. Order Module
Handles customer orders, order confirmation, order history and order details.

### 6. Payment Module
Manages payment processing through available payment methods and handles successful, failed and cancelled transactions.

### 7. Admin Module
Provides administrative features for managing users, products, orders and other platform activities.

###
TEST CASE

# E-Commerce Platform – Manual Testing Project

## 1. Project Overview

This project focuses on manual testing of an E-Commerce Shopping Platform. The main purpose is to check whether the website works correctly and provides a smooth shopping experience for users.

The testing covers important features such as user registration, login, product browsing, shopping cart, checkout, payment and order management.

The test cases are documented using GitHub Issues and organized through GitHub Projects to make testing activities easier to manage and track.

## 2. Project Objectives

- Verify that all major features of the e-commerce platform work correctly.
- Identify functional errors and unexpected behaviour.
- Check how the application handles valid and invalid user inputs.
- Ensure that shopping cart and checkout calculations are correct.
- Verify payment and order processing functionality.
- Maintain organized test case documentation using GitHub.

## 3. Testing Information

| Category | Details |
|---|---|
| Project | E-Commerce Platform |
| Testing Type | Manual Testing |
| Testing Approach | Functional Testing |
| Testing Level | System Testing |
| Test Management Tool | GitHub Projects |
| Issue Tracking | GitHub Issues |
| Documentation | Markdown |
| Total Test Cases | 35 |
| Total Modules | 7 |

## 4. Modules and Test Cases

### Module 1: User Registration (TC001–TC005)

| Test ID | Test Case |
|---|---|
| TC001 | Verify User Registration with Valid Details |
| TC002 | Verify Registration with Existing Email |
| TC003 | Verify Registration with Invalid Email |
| TC004 | Verify Registration with Empty Fields |
| TC005 | Verify Registration with Weak Password |

### Module 2: User Login & Authentication (TC006–TC010)

| Test ID | Test Case |
|---|---|
| TC006 | Verify Login with Valid Credentials |
| TC007 | Verify Login with Incorrect Password |
| TC008 | Verify Login with Invalid Email |
| TC009 | Verify Login with Empty Fields |
| TC010 | Verify Logout Functionality |

### Module 3: Product Management (TC011–TC015)

| Test ID | Test Case |
|---|---|
| TC011 | Verify Display of All Products |
| TC012 | Verify Product Search Functionality |
| TC013 | Verify Search with Non-Existing Product |
| TC014 | Verify Product Filtering by Category |
| TC015 | Verify Product Details |

### Module 4: Shopping Cart (TC016–TC020)

| Test ID | Test Case |
|---|---|
| TC016 | Verify Adding Product to Shopping Cart |
| TC017 | Verify Adding Multiple Products to Shopping Cart |
| TC018 | Verify Updating Product Quantity in Shopping Cart |
| TC019 | Verify Removing Product from Shopping Cart |
| TC020 | Verify Empty Shopping Cart |

### Module 5: Checkout Management (TC021–TC025)

| Test ID | Test Case |
|---|---|
| TC021 | Verify Proceeding to Checkout |
| TC022 | Verify Adding a Valid Delivery Address |
| TC023 | Verify Checkout with Missing Delivery Address |
| TC024 | Verify Order Total Calculation |
| TC025 | Verify Applying Valid and Invalid Coupon Codes |

### Module 6: Payment Management (TC026–TC030)

| Test ID | Test Case |
|---|---|
| TC026 | Verify Successful Payment |
| TC027 | Verify Payment with Invalid Details |
| TC028 | Verify Payment Cancellation |
| TC029 | Verify Payment Confirmation |
| TC030 | Verify Prevention of Duplicate Payment and Orders |

### Module 7: Order Management (TC031–TC035)

| Test ID | Test Case |
|---|---|
| TC031 | Verify Placing an Order Successfully |
| TC032 | Verify Viewing Order History |
| TC033 | Verify Order Tracking Functionality |
| TC034 | Verify Order Cancellation Functionality |
| TC035 | Verify Viewing Order Details |

## 5. Testing Techniques

The following testing techniques are covered in this project:

- **Positive Testing:** Checking application behaviour with valid inputs.
- **Negative Testing:** Checking application behaviour with invalid inputs.
- **Functional Testing:** Verifying whether application features work according to requirements.
- **Validation Testing:** Checking required fields and user input validation.
- **End-to-End Testing:** Verifying the complete shopping process from registration to order placement.

## 6. Test Case Structure

Each test case includes the following information:

1. Test Case ID
2. Module Name
3. Test Scenario
4. Description
5. Preconditions
6. Test Steps
7. Test Data
8. Expected Result
9. Actual Result
10. Priority
11. Test Status
12. Testing Type

## 7. Test Execution Status

The GitHub Project uses the following statuses to manage testing activities:

| Status | Description |
|---|---|
| Todo | Test case is documented but not executed |
| In Progress | Test execution is currently ongoing |
| Done | Test case work has been completed |

Test results should be recorded after actual execution. A test should only be marked as passed or failed after comparing the actual result with the expected result.

## 8. Project Management Using GitHub

GitHub is used to organize and manage all testing activities.

- GitHub Issues are used to document individual test cases.
- GitHub Projects provides a centralized view of all test cases.
- Module fields help organize test cases by functionality.
- Status fields help track testing progress.
- Issues can be updated whenever test execution results or improvements are available.

## 9. Project Statistics

| Module | Test Cases |
|---|---:|
| User Registration | 5 |
| User Login & Authentication | 5 |
| Product Management | 5 |
| Shopping Cart | 5 |
| Checkout Management | 5 |
| Payment Management | 5 |
| Order Management | 5 |
| **Total** | **35** |

## 10. Conclusion

This project provides a structured approach to manual testing of an E-Commerce Shopping Platform. It covers the major functionalities that customers use while shopping online, from creating an account to placing and tracking an order.

By preparing and organizing these test cases in GitHub, the project makes it easier to identify potential issues, manage testing activities and maintain proper documentation.

The project can be extended in the future with additional test scenarios, bug reports and automation testing using Selenium, Playwright or Cypress.

---

**Project:** E-Commerce Platform – Manual Testing  
**Tool:** GitHub  
**Testing Approach:** Manual Software Testing
