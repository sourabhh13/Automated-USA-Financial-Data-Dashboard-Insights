<h1 align="center"> Automated USA Financial Data Dashboard</h1>  

<p align="center">
  This project delivers a <b>comprehensive automation of the US Government’s financial survey pipeline</b> using 
  <b>Python, Power Automate, and Power BI</b>.  
  It eliminates manual data handling by streamlining <b>file ingestion, consolidation, cleaning, and visualization</b>, 
  enabling <b>faster, error-free, and insightful reporting</b>.
</p>  



---

## Project Context
- Around **25 survey files** are received daily at 3 PM via Outlook.  
- These files need to be consolidated, cleaned, and analyzed quickly.  
- A **Power BI dashboard** must be ready by 8 PM for stakeholders.  

---

## Challenges Before Automation
- Manual file handling was taking **4–5 hours per day**.  
- Frequent human errors in merging and cleaning affected accuracy.  
- Resource pressure was building up as the workflow grew in scale.  

---

## Automated Solution
- **File ingestion:** Automated through Outlook + Power Automate.  
- **Data processing:** Python scripts (pandas, numpy, seaborn) used for cleaning, merging, and validation.  
- **Data enrichment:** Integrated with APIs for additional datasets.  
- **Visualization:** Interactive Power BI dashboard with real-time updates.  

---

## Tech Stack
- Python (pandas, numpy, matplotlib, seaborn)  
- Google Colab (development & collaboration)  
- Outlook + Power Automate (file ingestion automation)  
- Power BI (dashboard & KPI reporting)  

---

## Key Features
- End-to-end automated pipeline (from email to dashboard).  
- **90% reduction in manual errors.**  
- Reporting time reduced from **~5 hours to under 1 hour.**  
- Real-time dashboards with KPIs for financial monitoring.  

---

## Dashboard Highlights
- Average Annual Income, Monthly Balance, Credit Utilization.  
- Payment Delays and Demographic Distributions.  
- Credit Score segmentation across defined age groups.  
- Relationship between age and credit limit.  
- Loan type distribution and popularity tracking.  
- Customer LTV segmentation for targeted offers.  

---

## LTV Formula
LTV = (0.3 * Avg Annual Income)
- (0.15 * Avg Payment Delay)
+ (0.4 * Avg Credit Score [mapped])
+ (0.075 * Avg Amount Invested)
+ (0.075 * Avg Monthly Balance)


**Credit Score Mapping**  
- Good = 3  
- Average = 2  
- Poor = 1  
- Bad = 0  

---

## Impact
- Reporting process is now **80% faster**.  
- **Accuracy improved significantly** with automated validation.  
- Freed up analyst time for deeper insights instead of manual tasks.  
- Clearer credit and customer behaviour insights available in real time.  

---
<h3 align="center">
✨ This project demonstrates how <b>automation + analytics</b> can 
<b>transform financial reporting & decision-making</b>.
</h3>  

---

