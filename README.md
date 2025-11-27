# 💰 Loan EMI Calculator

| Function | Tech Stack | Design Focus |
| :---: | :---: | :---: |
| [![Calculator](https://img.shields.io/badge/Type-Financial%20Tool-informational?style=for-the-badge)](https://en.wikipedia.org/wiki/Equated_monthly_instalment) | [![MERN Stack](https://img.shields.io/badge/Stack-MERN-success?style=for-the-badge)](https://www.mongodb.com/mern-stack) | [![Responsive](https://img.shields.io/badge/Design-Responsive%20UI-success?style=for-the-badge)](https://emi-calcs.netlify.app/) |

## 🌟 Project Overview

The **Loan EMI Calculator** is a simple, responsive web application designed to help users quickly estimate their loan repayment obligations. Built using fundamental web technologies (HTML, CSS, JavaScript), this intuitive tool calculates the **Monthly EMI (Equated Monthly Installment)**, total interest payable, and the total amount due, providing a clear financial snapshot based on user input.

***

<img width="1164" height="518" alt="repo3" src="https://github.com/user-attachments/assets/fb1a0e6b-626b-4145-a40d-5fe9ad2e939b" />

## ✨ Key Features

* **Comprehensive Calculation:** Calculates three essential metrics:
    * **EMI (Equated Monthly Installment)**
    * **Total Interest Payable**
    * **Total Payment** (Principal + Total Interest)
* **Flexible Tenure Input:** Allows users to input the loan tenure in either **months or years**.
* **Real-time Validation:** Implements strict input validation to ensure realistic and accurate calculations:
    * **Amount Limits:** Accepts values from ₹10,000 up to ₹1,00,00,000.
    * **Rate Limits:** Interest rate is constrained between 1% and 99%.
    * **Tenure Limits:** Maximum tenure is capped at 360 months (30 years).
* **Modern UI/UX:** Features a visually appealing, responsive interface with a modern aesthetic, including a background image and blur effects for focus.
* **Maintainable Code:** Utilizes a clean and modular code structure for easy understanding and future maintenance.

***

## 📚 Core Formula

The calculations are derived from the standard financial formula for EMI, ensuring accuracy:

**EMI Formula:**

$$
\text{EMI} = \left[ P \times r \times (1 + r)^n \right] \div \left[ (1 + r)^n – 1 \right]
$$

Where:
* **$P$** = Principal loan amount
* **$r$** = Monthly interest rate (calculated as $\text{Annual Rate} \div 12 \div 100$)
* **$n$** = Loan tenure in months

***

## 🎨 Tech Stack

| Technology | Purpose |
| :--- | :--- |
| **HTML5** | Provides the semantic structure and layout of the calculator form and result area. |
| **CSS3** | Handles all styling, responsiveness, and visual effects (e.g., background blur). |
| **JavaScript** | Implements the core calculation logic, real-time input validation, and DOM manipulation for displaying results. |

***

## 📌 Usage Guide

1.  **Try It Here:** [https://emi-calcs.netlify.app/)] 
2.  **Input Loan Amount:** Enter the desired principal loan amount (in ₹).
3.  **Input Interest Rate:** Provide the annual interest rate (in %).
4.  **Define Tenure:** Enter the loan duration and select the appropriate unit (**Yearly** or **Monthly**).
5.  **Calculate:** Click the **"Calculate"** button to instantly view the calculated EMI, Total Interest, and Total Payment.

***

## 🛠️ Getting Started

To run this calculator locally, follow these simple steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/loan-emi-calculator.git](https://github.com/your-username/loan-emi-calculator.git)
    cd loan-emi-calculator
    ```

2.  **Run Locally:**
    Open the `index.html` file in your preferred web browser.

***
