# Loan Application Gateway - HUOKAInG THARA BANK
## 🚀 Key Features

* **Bilingual Interface:** Fully localized forms and documentation supporting both **Khmer (ភាសាខ្មែរ)** and **English**.
* **Dynamic Loan Estimation:** Real-time calculation of estimated monthly payments based on requested loan amounts and terms at an 8.50% annual interest rate.
* **Document Export & Printing:** Built-in PDF generation and printing support (`printPdfBtn`) to allow applicants to archive or submit hard copies.
* **Security Headers & Practices:** Configured with robust security headers (`X-Content-Type-Options: nosniff`, `X-Frame-Options: DENY`) and autocomplete protections.
* **Responsive Design:** Optimized layout for desktop, tablet, and mobile devices using modern CSS.

## 📂 Project Structure

├── index.html            # Main loan application gateway interface
├── style.css             # Core layout, styling, and typography (Inter & Kantumruy Pro fonts)
├── app.js                # Form logic, dynamic interest/payment calculator, and validation
├── ultra_secure_mode.js  # Additional security layer & session route handlers
├── music.js              # Optional background/ambient script or interface effects
├── bank.jpg              # Favicon image asset
└── borrow.jpg            # Hero banner background image asset

## 🛠️ Getting Started & Installation

To run or deploy this project locally, follow these simple steps:

1. **Clone the Repository:**

git clone https://github.com/your-username/huokaing-thara-bank-loan-gateway.git
cd huokaing-thara-bank-loan-gateway

2. **Ensure Assets are in Place:**
Make sure `bank.jpg` and `borrow.jpg` (or your preferred banner/icon replacements) exist in the root directory, or update the references in `index.html`.
3. **Run Locally:**
Open `index.html` directly in your web browser, or use a local development server (such as Live Server in VS Code) for the best experience.

## ⚙️ How It Works

1. **Personal Information Entry:** Applicants provide their full name, National ID or Passport number, phone number, and email address.
2. **Loan Requirements:** Select or input the desired loan amount (minimum $1000), repayment term (12 to 60 months), and stated loan purpose.
3. **Real-time Calculation:** As inputs change, the interactive script calculates the estimated monthly repayment using standard amortization formulas.
4. **Submission:** Upon checking the terms and conditions agreement, users can either print/save the document as a PDF or submit the form to connect with the digital customer service desk.
