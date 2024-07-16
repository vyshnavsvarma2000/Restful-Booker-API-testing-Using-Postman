# RESTful Booker API Automation Testing

## Overview

This project focuses on automating the testing of the RESTful Booker API, which is available at [https://restful-booker.herokuapp.com](https://restful-booker.herokuapp.com).

## Table of Contents

1. [Prerequisites](#prerequisites)
2. [Technologies](#technologies)
3. [Installation and Usage](#installation-and-usage)
4. [Benefits](#benefits)
5. [Reporting](#reporting)

---

## Prerequisites

Before running the tests, make sure the following tools are installed:

- Node.js
- Postman
- Newman
- htmlextraReporter

---

## Technologies

### Technologies Used:

- **Postman**: Used for designing and executing API requests.
- **Collection Runner**: Postman's built-in tool for running collections sequentially.
- **Newman**: Command-line tool for running Postman collections from the terminal.
- **npm**: Package manager for managing Node.js dependencies.
- **htmlextra**: HTML reporting library for generating detailed test reports.

---

## Installation and Usage

### Installation Steps:

1. Clone the project repository:
git clone <repository-url>

2. Install necessary dependencies:
npm install

3. Update environment variables (e.g., base URL) in the `.env` file (optional).

### Usage:

- Run tests using Postman Collection Runner or npm:

- View the test report in `report.html` located in the `newman` directory after running the tests.

---

## Benefits

- Improves testing efficiency and saves time.
- Ensures consistent and reliable testing of Update Booking functionality.
- Provides clear and readable reports for easy analysis.

---

## Reporting

HTML reports for test execution can be generated using Newman and htmlextra. After running the tests, check the `newman` directory for the generated HTML reports.
![Testingfor RESTful Booker](https://github.com/user-attachments/assets/39e9e616-6725-45e3-af83-c8a2e7a2e99e)
