1. Project Title / Headline
🛡️ Insurance Policy & Claims Analytics Dashboard

An interactive Power BI dashboard built on an insurance dataset to track policy activity, premium & coverage performance, and claims behavior with slicers, KPIs, drill-through, and Power BI Service publishing.

2. Short Description / Purpose

The Insurance Policy & Claims Analytics Dashboard is a Power BI report created to analyze 10,000 insurance records stored in SQL Server. It helps users explore key metrics like premium amount, coverage amount, claim amount, claim status trends, customer segmentation, and active vs inactive policies, while allowing detailed drill-through analysis.

3. Tech Stack

The dashboard was built using the following tools and technologies:

📊 Power BI Desktop – Building the report, visuals, slicers, KPIs, and interactions

🔄 Power Query Editor – Data profiling, transformations, and conditional column creation

🧠 DAX / Built-in Aggregations – Used for totals, counts, filtering behavior, KPI summaries

🗄️ Microsoft SQL Server (Developer Edition) – Data storage and main data source

🧾 SSMS (SQL Server Management Studio) – Importing the CSV and validating data using SQL queries

☁️ Power BI Service – Publishing report, workspace creation, and report sharing

📁 File Format – .pbix for development

4. Data Source

Source: Insurance dataset imported into Microsoft SQL Server (flat file / CSV)

Records: ~10,000 rows

Key columns in the dataset:

Policy Number, Customer ID, Gender, Age, Policy Type

Policy Start Date, Policy End Date

Premium Amount, Coverage Amount

Claim Number, Claim Date, Claim Amount, Claim Status

Extra fields created in Power Query:

✅ Age Group (Young Adults / Adults / Senior)

✅ Active / Inactive (based on Policy End Date condition)

5. Features / Highlights
✅ Business Problem

Insurance data usually contains multiple fields (premium, coverage, claim status, customer details), but without a dashboard it’s difficult to quickly answer questions like:

Which policy types generate the highest premiums?

How many policies are currently active vs inactive?

What’s the claim outcome split (settled / rejected / pending)?

Which age segment contributes higher claim amounts?

How does coverage vary across different policy types and claim statuses?

✅ Goal of the Dashboard

To create a single Power BI report that:

Gives a clear summary of premium, coverage, and claims

Supports interactive filtering using slicers and visual selections

Provides drill-through access to full records for deeper analysis

Can be published and shared through Power BI Service

✅ Walkthrough of Key Visuals (Brief)
🔹 KPI Cards (Top Section)

Premium Amount

Coverage Amount

Claim Amount
These cards update instantly based on slicers and selections.

🔹 Slicers (Filters)

Policy Number

Customer ID

Claim Number
Used to filter the full report page.

🔹 Multi-Row Card (Gender Split)

Shows count of:

Male customers

Female customers
Also works as a filter when clicked.

🔹 Ribbon Chart (Claims by Status)

Displays the number of claims by:

Settled

Rejected

Pending

🔹 Bar Chart (Premium Amount by Policy Type)

Compares policy types (Auto, Health, Home, Life, Travel etc.) based on premium contribution.

🔹 Line Chart (Claim Amount by Age Group)

Shows total claim amount for:

Young Adults

Adults

Senior

🔹 Donut Chart (Active vs Inactive Policies)

Policy activity status distribution:

Active policies

Inactive policies

🔹 Matrix Visual (Coverage Amount Breakdown)

Coverage amount analyzed by:

Rows → Policy Type

Columns → Claim Status

Values → Coverage Amount

🔹 Drill Through Page (Detailed Records)

A separate page contains a full table view of records.
From the bar chart, users can right-click → drill through by Policy Type to see filtered row-level details.

✅ Business Impact & Insights

Fast reporting: Key KPIs are available in one view instead of manual Excel/SQL checks

Policy performance tracking: Premium by policy type shows which products generate value

Claims monitoring: Status breakdown helps track rejected vs settled patterns

Customer segmentation: Gender and age group visuals help understand customer claim behavior

Deep dive capability: Drill-through page provides record-level verification when needed

Share-ready: Report can be published and shared through Power BI Service workspaces

6. Screenshots / Demos
