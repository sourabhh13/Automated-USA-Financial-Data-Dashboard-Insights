📊 Automated Financial Data Processing & Analytics Dashboard
🚀 Project Overview

This project automates the end-to-end financial data pipeline for the US Government’s survey program.
Every day, ~25 financial survey files are received via email at 3 PM, which must be consolidated, cleaned, analyzed, and turned into a Power BI dashboard by 8 PM.

Challenges before automation:

Manual download, merging, and cleaning of ~25 files.

~5 hours daily processing time.

Frequent errors in data handling.

$12,000/month additional hiring cost.

My Solution:

Automated file ingestion from Outlook using Power Automate.

Data consolidation, cleaning, and validation with Python (pandas, Google Colab).

Additional data via API integration.

Power BI dashboard for real-time KPIs and insights.

🛠 Tech Stack

Python (pandas, numpy, matplotlib, seaborn) – Data cleaning, transformation, analysis

Google Colab – Cloud-based notebooks for development & collaboration

Outlook + Power Automate – Email automation & daily file ingestion

API Integration – Fetching supplemental financial data

Power BI – Dashboard design & visualization

📈 Key Features

✅ End-to-End Automation – From email ingestion to dashboard update
✅ Error Reduction – 90% fewer data issues after automation
✅ Time Savings – Processing time cut from 5 hours → 45 minutes
✅ Cost Savings – Eliminated $12,000/month manual workload
✅ Business Insights – Actionable recommendations for credit strategy

📊 Dashboard Insights

The dashboard provides:

Average Annual Income

Average Monthly Balance

Average Credit Utilization

Average Payment Delays

Age Demographics Distribution Plot

Credit Score Segmentation by Age Groups

Teen (14–18)

Young Adult (19–25)

Old Adult (26–35)

Old1 (36–45)

Old2 (46+)

Age vs Credit Limit Changes (Regression Analysis)

Payment Behavior by Credit Mix

Loan Type Popularity (Loan Count Visualization)

Customer LTV Scoring by Age Cohort

LTV > 80,000 → 🎁 30% off + Home Loan @ 4%

60,000–80,000 → 🎁 15% off + $10,000 Gift Hampers

50,000–60,000 → 🎁 Any Loan @ 5% Interest

📐 LTV Formula
LTV
=
(
0.3
×
Avg Annual Income
)
−
(
0.15
×
Avg Payment Delay
)
+
(
0.4
×
Avg Credit Score (mapped)
)
+
(
0.075
×
Avg Amount Invested
)
+
(
0.075
×
Avg Monthly Balance
)
LTV=(0.3×Avg Annual Income)−(0.15×Avg Payment Delay)+(0.4×Avg Credit Score (mapped))+(0.075×Avg Amount Invested)+(0.075×Avg Monthly Balance)

Credit Score Mapping:

Good = 3

Average = 2

Poor = 1

Bad = 0

🏆 Impact & Results

⏳ 80% faster reporting (5 hrs → 45 mins)

💰 $12,000/month savings in labor costs

📉 90% fewer manual errors in reporting

📊 Real-time financial insights driving smarter credit strategies

🎯 Targeted customer promotions using LTV-based segmentation
