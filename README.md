# API Automated Testing Project

## Project Overview

This project contains automated API tests developed using Python, Requests, and Pytest.

The objective of the project was to validate the functionality of the Urban Grocers API by creating and executing automated test cases for user creation and product kit endpoints.

The tests verify that the API correctly processes requests, validates input data, and returns the expected responses.

---

## Technologies Used

* Python
* Pytest
* Requests
* REST API Testing
* Git
* GitHub

---

## Project Structure

### configuration.py

Contains the base URL and API endpoint paths used throughout the project.

### data.py

Stores request headers and test data used in API calls.

### sender_stand_request.py

Contains helper functions that send HTTP requests to the API.

### create_user_test.py

Contains automated test cases that validate user creation functionality.

---

## Test Scenarios Covered

### Positive Tests

* Create a user with valid data
* Verify successful user creation
* Verify correct status codes

### Negative Tests

* Validate incorrect user name formats
* Validate empty values
* Validate invalid request data
* Verify proper error responses

---

## Skills Demonstrated

* API Testing
* Test Automation
* Test Case Design
* Request and Response Validation
* Positive and Negative Testing
* Python Programming
* REST API Validation
* Bug Detection and Analysis

---

## How to Run the Tests

1. Clone the repository.
2. Install dependencies:

```bash
pip install pytest requests
```

3. Run the test suite:

```bash
pytest
```

---

## Author

Rosa Eréndira Medina Olvera

QA Engineer | Manual Testing | API Testing | Test Automation
