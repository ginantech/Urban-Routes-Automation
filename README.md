# 🚕 Urban Routes Automation Testing

> Automated end-to-end (E2E) tests for the Urban Routes application, ensuring a smooth and reliable taxi booking experience from start to finish.

![Tests](https://img.shields.io/badge/tests-e2e-blue?style=flat-square)
![Framework](https://img.shields.io/badge/framework-WebdriverIO-orange?style=flat-square)
![Status](https://img.shields.io/badge/status-active-success?style=flat-square)

---

## 📋 Overview

This repository contains automated end-to-end tests for the **Urban Routes** application. The test suite verifies the full process of ordering a taxi, covering everything from setting the address to confirming the car search modal appears.

---

## ✅ Test Scenarios

|
 
#
 
|
 Scenario 
|
 Description 
|

|
---
|
----------
|
-------------
|

|
 1 
|
 📍 
**
Setting the Address
**
 
|
 Verify that the user can correctly set the pickup and drop-off locations. 
|

|
 2 
|
 🧑‍🦯 
**
Selecting Supportive Plan
**
 
|
 Check that the user can choose a supportive plan from the available options. 
|

|
 3 
|
 📞 
**
Filling in the Phone Number
**
 
|
 Ensure the phone number field is functional and accepts valid input. 
|

|
 4 
|
 💳 
**
Adding a Credit Card
**
 
|
 Ensure credit card details can be added correctly using the modal with 
`id="code"`
 and 
`class="card-input"`
. 
|

|
 5 
|
 💬 
**
Writing a Message for the Driver
**
 
|
 Verify that the user can add a custom message for the driver. 
|

|
 6 
|
 🛏️ 
**
Ordering a Blanket and Handkerchiefs
**
 
|
 Verify the user can order a blanket and handkerchiefs, using two selectors: one for the click and one for the state verification. 
|

|
 7 
|
 🍦 
**
Ordering 2 Ice Creams
**
 
|
 Check the user can successfully order two ice creams along with the ride. 
|

|
 8 
|
 🚗 
**
Car Search Modal Appears
**
 
|
 Verify that the car search modal pops up after the order has been placed. 
|

|
 9 
|
 ⏳ 
**
Waiting for Driver Info
**
 
*
(Optional)
*
 
|
 Ensures that the driver's information is displayed correctly in the modal after the car search. 
|


> 💡 **Tip:** The "Link" button for adding a credit card does not become active until the CVV field loses focus. This can be simulated by pressing `TAB` or clicking somewhere else on the screen.

> 💡 **Tip:** For the blanket and handkerchiefs step, use one selector to perform the click and a separate selector with an `expect` statement to verify the state change.

---

## 🗂️ Project Structure

```text
urban-routes-automation/
├── test/
│   └── specs/
│       └── createAnOrder.e2e.js   # All E2E tests for the Urban Routes order process
├── package.json
└── README.md

🚀 Installation & Setup
1. Clone the repository

git clone https://github.com/username/urban-routes-automation.git

2. Navigate to the project directory

cd urban-routes-automation

3. Install dependencies

npm install

▶️ Running the Tests

To execute the test suite, run:

npm test

📝 Notes

    Ensure the Urban Routes application server is running before executing the tests.
    Make sure all dependencies are up to date for the smoothest test execution.
    Tests are located in test/specs/createAnOrder.e2e.js.

🤝 Contributing

Contributions are welcome! If you find a bug or want to add a new test scenario, feel free to open an issue or submit a pull request.
<p align="center">Made with ❤️ for reliable Urban Routes testing.</p> ```
