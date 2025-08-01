<h2>📊 Loan EMI Calculator</h2>

A simple, responsive web application that calculates the monthly EMI (Equated Monthly Installment), total interest, and total payment for a loan based on user input. Built using **HTML, CSS, and JavaScript**, this tool is designed to be intuitive and visually appealing.

<h2>Features</h2>

- Accepts **loan amount**, **interest rate**, and **loan tenure** from users
- Tenure can be calculated in **months or years**
- Calculates:
  - **EMI (Equated Monthly Installment)**
  - **Total Interest Payable**
  - **Total Payment including principal**
- Real-time input validation
- Modern, responsive UI with background image and blur effect
- Clean and modular code structure for ease of maintenance


<h2>Formula Used</h2> 

<p>EMI = [P × r × (1 + r)^n] / [(1 + r)^n – 1]</p>
Where:</p>
<p>P = Principal loan amount</p>
<p>r = Monthly interest rate (annual rate / 12 / 100)</p>
<p>n = Loan tenure in months</p>


<h2>🎨 Tech Stack </h2>

<ul>
<li>HTML5 – Structure and layout</li>
<li>CSS3 – Styling and responsive design</li>
<li>JavaScript – Logic and DOM manipulation</li>
</ul>

<h2>📌 Usage</h2>

<ol>
<li>Enter the loan amount in Indian Rupees (₹)</li> 
<li> Provide the annual interest rate (%) of the loan</li>
<li> Choose loan tenure and specify its value</li>
<li> Select tenure type – yearly or monthly</li>
<li> Click **Calculate** to see EMI, total interest, and total payment</li>
</ol>

<h2>📷 Screenshot</h2>

<img width="1164" height="518" alt="repo3" src="https://github.com/user-attachments/assets/fb1a0e6b-626b-4145-a40d-5fe9ad2e939b" />



<h2>Validation Notes</h2>

-Input limits ensure realistic values:
- Amount: ₹10,000 to ₹1,00,00,000
- Interest: 1% to 99%
- Tenure: Up to 360 months
- Inputs are trimmed automatically beyond max length

<h2>Try It Here</h2>
<a href="https://emi-calcs.netlify.app/">EMI-Calculator</a>
