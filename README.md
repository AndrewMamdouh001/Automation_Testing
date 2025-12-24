
# Automation Exercise – UI & API Testing

## 📌 Project Overview

This project demonstrates end-to-end **software testing for an e-commerce application** using both **UI automation** and **API testing**.
The goal is to validate critical user workflows, ensure system reliability, and detect defects early through automated regression suites.

The project covers:

* Core **UI user journeys** using automation
* **API testing** for backend services
* Positive & negative test scenarios
* Defect documentation with logs and screenshots

---

## 🧪 Test Scope

### UI Testing

Automated validation of core e-commerce workflows:

* User Registration & Login
* Product browsing
* Add to Cart
* Cart management
* Checkout flow

Test design follows:

* Page Object Model (POM)
* Regression-focused test suites
* Reusable and maintainable test structure

---

### API Testing

API tests were created to validate backend functionality independently from the UI.

Covered APIs:

* Authentication
* Products
* Cart
* Orders

Test coverage includes:

* Positive scenarios
* Negative scenarios
* Status code validation
* Request/response validation

---

## 🛠 Tools & Technologies

### UI Automation

* Programming Language: *[Add language if applicable – e.g. Java / JavaScript / TypeScript]*
* Automation Framework: *[Selenium / Playwright – adjust if needed]*
* Design Pattern: **Page Object Model (POM)**
* Test Type: End-to-End & Regression Testing

### API Testing

* **Postman**
* RESTful APIs
* JSON request & response handling

### Reporting & Debugging

* Execution logs
* Screenshots on failure
* Documented defects

---

## 📂 Project Structure

```
├── tests/
│   ├── ui/
│   └── api/
├── pages/
│   └── pageObjects/
├── testData/
├── reports/
├── screenshots/
└── README.md
```

---

## ▶️ How to Run the Tests

### UI Tests

1. Clone the repository
2. Install project dependencies
3. Configure environment variables if needed
4. Run the test suite using the test runner

### API Tests

1. Import the Postman collection
2. Set environment variables
3. Execute requests individually or as a collection

---

## 🐞 Defect Management

* Defects are identified during test execution
* Each defect includes:

  * Clear steps to reproduce
  * Expected vs actual result
  * Screenshots or logs when applicable
* Focus on **early detection of critical user-path issues**

---
