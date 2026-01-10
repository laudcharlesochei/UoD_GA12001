# Practical Manual  
## Lab 03: Data, Information & KPIs → Excel/Sheets Data Dashboard  

---

## 1. Lab Overview

Businesses collect lots of **raw data** (transactions, customer interactions, delivery times, etc.). On its own, raw data is not very useful. The real value comes when we transform it into **information** and **Key Performance Indicators (KPIs)** that help managers make decisions.

In this lab, you will use a simple fictional sales dataset to:

- Identify business-relevant **KPIs**
- Sort, filter, and summarise data
- Create charts and a mini **dashboard**
- Explain what your results mean and recommend actions

This lab focuses on **understanding and communicating insights** (not advanced statistics or coding).

---

## 2. Learning Outcomes

By the end of this lab, you will be able to:

- Distinguish between **data**, **information**, and **KPIs**
- Identify relevant KPIs for a business scenario
- Use basic spreadsheet functions to analyse data
- Create clear charts that support decision-making
- Interpret results and link them to realistic business actions

---

## 3. Prerequisites

### Before beginning, ensure you have:

#### Hardware & Access
- A **desktop or laptop**
- **Internet connection**
- A modern browser (Chrome, Edge, Firefox)

#### Spreadsheet Software (choose one)
- **LibreOffice Calc** (open-source, recommended), OR
- **Google Sheets** (free, web-based), OR
- **Microsoft Excel** (if available)

---

### Pre-Class Work (as per module plan)

Identify **2–3 KPIs** used in your workplace (or a workplace you know), for example:
- Sales revenue
- Customer satisfaction
- Number of transactions
- Response time
- Attendance / productivity

> You do **not** need to bring sensitive or confidential data.

---

## 4. Lab Deliverables (What You Will Produce)

By the end of the session, you will submit:

- A cleaned and analysed sales dataset
- At least **one KPI chart**
- A **mini dashboard** sheet
- A short business interpretation (100–150 words)

---

## 5. Dataset Used in Class

### Option A (Recommended): Provided Sample Dataset
Use the fictional dataset provided below.

**Download files:**
- CSV: [week3_kpi_sales_dataset.csv](sandbox:/mnt/data/week3_kpi_sales_dataset.csv)  
- Excel: [week3_kpi_sales_dataset.xlsx](sandbox:/mnt/data/week3_kpi_sales_dataset.xlsx)

### Option B (Optional): Your Own Workplace Dataset
You may use a small dataset (10–50 rows) **only if**:
- It contains **no personal/confidential data**
- It is approved by your lecturer (if required by your module rules)

---

### Sample Dataset Preview (first 15 rows)

| Date | Product | Region | Salesperson | Units Sold | Revenue |
|---|---|---|---|---:|---:|
| 2025-01-06 | Wireless Mouse | East | D. Chen | 4 | 92.96 |
| 2025-01-06 | Laptop Sleeve | East | A. Okafor | 8 | 155.89 |
| 2025-01-07 | Noise-Cancel Headphones | West | D. Chen | 5 | 390.56 |
| 2025-01-08 | Webcam | North | D. Chen | 6 | 235.05 |
| 2025-01-09 | Webcam | South | A. Okafor | 4 | 155.23 |
| 2025-01-10 | USB-C Hub | North | C. Ahmed | 2 | 67.75 |
| 2025-01-10 | USB-C Hub | West | A. Okafor | 4 | 140.86 |
| 2025-01-11 | USB-C Hub | North | A. Okafor | 5 | 185.15 |
| 2025-01-12 | Wireless Mouse | South | D. Chen | 1 | 17.19 |
| 2025-01-12 | USB-C Hub | South | A. Okafor | 4 | 138.36 |
| 2025-01-13 | Wireless Mouse | West | B. Smith | 4 | 89.14 |
| 2025-01-13 | USB-C Hub | South | B. Smith | 2 | 70.45 |
| 2025-01-14 | Wireless Mouse | West | C. Ahmed | 4 | 99.30 |
| 2025-01-14 | USB-C Hub | East | D. Chen | 1 | 31.53 |
| 2025-01-15 | Laptop Sleeve | South | B. Smith | 5 | 91.13 |

> The downloadable file contains the full dataset.

---

## 6. Step-by-Step Lab Procedure (Student Instructions)

### Part A: Understanding Data & KPIs (10 minutes)

#### Step 1: Open the exercise file
1. Download the dataset (CSV or Excel).
2. Open it in your chosen spreadsheet tool.
3. Save your working file as:

Week3_KPI_Analysis_<YourName>.xlsx

yaml
Copy code

*(If you’re using Google Sheets, name the file the same way.)*

#### Step 2: Review the dataset
Look at the columns and think:
- What does each column represent?
- Which parts are **raw data**?
- What information would help a manager?

#### Step 3: Identify KPIs
Create a new sheet called **KPI List** and write **3 KPIs** relevant to this dataset, for example:
- Total revenue
- Average revenue per sale (transaction)
- Revenue by region
- Best-selling product (by revenue or units)
- Top-performing salesperson (by revenue)

---

### Part B: Basic Data Analysis (20–25 minutes)

#### Step 4: Sort the data
Sort by **Revenue** (highest to lowest) and identify:
- Top product(s)
- Top region(s)
- Highest-performing salesperson(s)

#### Step 5: Filter the data
Apply filters to:
- Show one **region** only
- Show one **product** only
- Show **revenue above** a chosen threshold

Answer (in notes or on a new sheet called **Answers**):
- Which region performs best?
- Are there any underperforming regions/products?

#### Step 6: Use basic functions
Create a sheet called **KPI Summary** and calculate:

- **Total Revenue:** `=SUM(RevenueRange)`
- **Average Revenue per Sale:** `=AVERAGE(RevenueRange)`
- **Maximum Sale Value:** `=MAX(RevenueRange)`

Record results in a small table like:

| KPI | Value |
|---|---:|
| Total Revenue | |
| Average Revenue per Sale | |
| Maximum Sale Value | |

---

### Part C: Pivot Table for KPI Summary (15–20 minutes)

#### Step 7: Create a pivot table
Create pivot tables that show:
- **Revenue by Region**
- **Revenue by Product**

*(If you’re in Google Sheets: Data → Pivot table. In Excel/Calc: Insert → Pivot table.)*

#### Step 8: Interpret pivot results
Write short answers:
- Which region contributes the most revenue?
- Which product performs best?
- What decision might management take based on this?

---

### Part D: Create a KPI Chart / Mini Dashboard (15–20 minutes)

#### Step 9: Choose and create at least one chart
Create **at least one chart**, for example:
- Column chart → Revenue by Region
- Bar chart → Revenue by Product
- Line chart → Revenue over Time

#### Step 10: Improve chart quality
Make your chart management-friendly:
- Add a clear **title**
- Label axes
- Remove unnecessary clutter
- Ensure values are readable

#### Step 11: Build a simple dashboard
Create a new sheet called **Dashboard**:
- Copy your KPI Summary table
- Insert your chart(s)
- Arrange neatly so a manager can read it quickly

---

### Part E: Business Interpretation (10 minutes)

#### Step 12: Write a short interpretation (100–150 words)
Answer:
- What does the data tell you?
- Which KPI matters most and why?
- What business action would you recommend?

---

## 7. Submission (End of Class)

Submit:
- `Week3_KPI_Analysis_<YourName>.xlsx` (or Google Sheets export)
- Your 100–150 word interpretation (in the same file or in the VLE text box, depending on instructions)

---

## 8. Pre / Post-Class Alignment

### Pre-Class
- Identify KPIs used in your workplace (or a workplace you know)

### Post-Class
- Create one additional chart from the dataset  
- Optional: Repeat the exercise using a small non-sensitive workplace dataset
