# Retailer_CN_Automation_Project
Short summary of the project (e.g., "Automated CN calculation for Finolex dealers using Python, Power BI, and SQL")
Retailer Credit Note Automation Project

About This Project

The previous process was entirely manual, involving repetitive tracking, reconciliation delays, and lack of system support. This resulted in a prolonged timeline of 4 to 5 months for crediting CNs to retailers. Post-implementation, the process was streamlined and completed within just 20 days after the fiscal year closing.

Goals

Streamline the credit note calculation process

Reduce the timeline for crediting CNs to retailers

Enhance accuracy and efficiency through automation

Minimize manual intervention and errors

Improve overall satisfaction and feedback from stakeholders

Challenges Faced

Dealer sales data was spread across multiple software systems (mostly Tally, some via CRM portal).

Material group mismatches caused incorrect credit calculations.

Manual data collection from dealers took up to 2-3 months.

Significant time was spent on data cleaning and CN calculations.

Customer (retailer) dissatisfaction due to errors and delays.

Annual processing costs were very high (Rs.25-30 lakhs per year).

My Role & Contributions

Designed a material group validation system to ensure all dealers used consistent classifications for products, eliminating mismatch errors.

Helped dealers migrate to Tally ERP and trained them to generate standardized reports for CN processing.

Integrated Tally data with Finolexs CRM portal, enabling real-time data sync and visibility.

Developed logic in Python to automate:

Data ingestion from Tally and CRM

Cleaning and validation of dealer-wise sales

CN calculation based on pre-defined rules (e.g., purchase > Rs.25L = 2%)

Created Power BI dashboards to visualize retailer performance and CN eligibility.

Tools & Technologies Used

🐍 Python

📊 Power BI

🗃️ SQL

🖥️ SAP

📁 Tally ERP

Impact & Outcomes

Retailer Data Collection: 60-90 days → 10-15 days (~85% faster)

Data Cleaning: 10-15 days → 1 day (~90% faster)

CN Calculation: 7-10 days → 1 day (~85% faster)

Customer Satisfaction: Very Low → Very Satisfied

Annual Processing Cost: Rs.25-30 lakhs → Rs.5-7 lakhs (~75-80% cost reduction)

Key Learnings

Business logic is just as important as technology aligning CN rules with real-world scenarios saved huge effort.

Data standardization across systems is critical for reliable automation.

Combining domain expertise (sales/supply chain) with analytics tools creates real business value.

Project Flowchart

Markdown Flowchart

[Start]
   ↓
[Dealer Sales Data Collection]
   ↓
[Tally ERP Export / CRM Sync]
   ↓
[Python: Data Cleaning & Validation]
   ↓
[Python: CN Calculation Logic]
   ↓
[Power BI Dashboard Generation]
   ↓
[Review & Approval]
   ↓
[CN Credit to Retailers]
   ↓
[End]

Visual Flowchart
![Project Flowchart](https://github.com/sharad-karande/Retailer_CN_Automation_Project/blob/main/flowchart_image.png)




