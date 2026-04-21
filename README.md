📊 Loan Performance Dashboard (Google Sheets)
📌 Project Overview

This project is an interactive Loan Performance Dashboard built using Google Sheets to analyze loan data, monitor repayment behavior, and identify risk patterns.

The dashboard transforms raw loan data into actionable insights through automated calculations, segmentation, and visual reporting.

🎯 Objectives
Track overall loan performance
Monitor default rates and active loans
Segment customers based on loan value
Identify high-risk borrowers
Provide insights for better lending decisions
🛠️ Tools Used
Google Sheets
Pivot Tables
Data Cleaning Techniques
Advanced Excel/Sheets Formulas
📂 Dataset Description

The dataset includes:

Loan ID
Loan Date
Customer Type (Individual/Business)
Loan Amount
Loan Status (Active, Paid, Default)
⚙️ Key Features
✅ 1. Data Cleaning & Transformation
Structured raw data into a clean format
Extracted Month and Year for time-based analysis
🧠 2. Risk Scoring Model

A simple rule-based scoring system:

=IF(Status="Default",3,IF(Status="Active",2,1))
3 → High Risk
2 → Medium Risk
1 → Low Risk
🎯 3. Customer Segmentation

Segmented customers based on loan size:

=IF(Loan_Amount>100000,"High Value",IF(Loan_Amount>50000,"Medium Value","Low Value"))
📊 4. Key Performance Indicators (KPIs)
Total Loans Issued
Total Loan Amount
Average Loan Size
Default Rate
Active Loans
📈 5. Dashboard Visuals
Loan trends over time (Line Chart)
Loan distribution by status (Pie Chart)
Loan amount by segment (Bar Chart)
📊 Insights Generated
Identified proportion of defaulted vs active loans
Detected high-value customers contributing most revenue
Highlighted risk concentration in specific segments
Tracked loan issuance trends over time
🚀 How to Use
Download or clone the repository
Upload the Excel file to Google Sheets
Replace the sample data in the Raw_Data sheet
Dashboard updates automatically
💼 Business Value

This dashboard can help:

Financial institutions reduce loan default risk
Improve customer targeting strategies
Support data-driven lending decisions
🔥 Future Improvements
Add credit score integration
Build predictive model for default risk
Automate data updates using APIs
Migrate dashboard to Power BI or Tableau
📎 Project Files
Loan_Dashboard_Template.xlsx → Main dashboard file
📢 Author

Thomas Oselu
📍 Nairobi, Kenya
📧 Thomasoselu1@gmail.com

⭐ If you found this useful

Give the project a star ⭐ and feel free to fork it!
