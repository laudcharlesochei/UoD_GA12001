# Practical Manual  
## Lab 05: Building a Simple Business Contact Database & Comparing Data Repositories

## 1. Lab Overview

Businesses rely on well-organised data to operate efficiently. Customer records, supplier details, and internal contacts are often stored in **databases**, while documents such as reports and forms are stored in **digital repositories** (cloud folders).

In this lab, you will:

- Learn how business data is **structured and stored**
- Build a **simple contact database** using Microsoft Access
- Enter, sort, filter, and search data like a real business system
- Compare **databases** with **digital repositories** (e.g. cloud storage)
- Reflect on how data is currently stored in your workplace (or a workplace you know)

The focus is on **business understanding of data**, not advanced technical skills or programming.

---

## 2. Learning Outcomes

By the end of this lab, you will be able to:

- Identify different types of business data
- Design a simple database table with appropriate fields and data types
- Explain the difference between:
  - **Databases** (structured tables)
  - **Digital repositories** (cloud folders and files)
- Make informed decisions about how data should be stored and accessed in a business

---

## 3. Prerequisites

### Before beginning, ensure you have:

#### Hardware & Access
- A **desktop or laptop computer**
- A **reliable internet connection**
- A modern web browser (Chrome, Edge, or Firefox)

#### Software / Tools
- **Microsoft Access** (installed on lab computers)

> You will also reflect on cloud repositories such as **OneDrive**, **Google Drive**, or **Dropbox**, but no advanced setup is required.

---

### Pre-Class Work (as per module plan)

Before this lab, you should have identified **three data sources** used in your workplace (or a workplace you know), for example:
- Customer records
- HR or staff data
- Sales records
- Inventory lists

---

## 4. Lab Deliverables (What You Will Produce)

By the end of the lab, you will submit:

- A **simple Contact Database** (Microsoft Access file)
- A **repository comparison table**
- A **short reflection** on workplace data storage practices

---

## 5. Lab Practical Activity (Step-by-Step)

---

### Part A: Understanding Business Data (10 minutes)

#### Step 1: Identify business data types
Individually, list **three types of data** used in your workplace or a workplace you know.

Examples:
- Customer contact details
- Supplier information
- Staff records
- Sales transactions

#### Step 2: Data concepts (guided)
Quick reminders:
- **Structured data:** tables, rows, columns (databases)
- **Unstructured data:** documents, PDFs, images, emails

Think about:
- Which data needs **searching and filtering**?
- Which data is mainly **stored and shared**?

---

### Part B: Build a Simple Contact Database (30–40 minutes)

#### Step 3: Create a new database in Microsoft Access
1. Open **Microsoft Access**
2. Choose **Blank database**
3. Name the file:

Week5_Contact_Database_<YourName>.accdb

vbnet
Copy code

4. Click **Create**

---

#### Step 4: Design the Contact table
You will create a table to store business contacts.

1. Go to **Create → Table Design**
2. Add the following fields:

| Field Name | Data Type | Description |
|----------|----------|------------|
| ContactID | AutoNumber | Unique identifier |
| FirstName | Short Text | Contact first name |
| LastName | Short Text | Contact last name |
| Email | Short Text | Email address |
| Phone | Short Text | Phone number |
| Company | Short Text | Organisation name |
| JobRole | Short Text | Role or position |
| City | Short Text | Location |
| ContactType | Short Text | Customer / Supplier / Partner |
| DateAdded | Date/Time | Date record created |

3. Set **ContactID** as the **Primary Key**
4. Save the table as:

Contacts

yaml
Copy code

---

#### Step 5: Understand data types (business-level)
Make a note (in a notebook or new Access object):

- **Text:** names, email, company, job role
- **Number / AutoNumber:** ContactID
- **Date:** DateAdded
- **Category:** ContactType (Customer, Supplier, Partner, Internal)

This is how databases ensure **consistency and accuracy**.

---

#### Step 6: Enter sample data
1. Switch to **Datasheet View**
2. Enter **8–10 fictional contacts**
3. Use **realistic but fake data only** (no real personal data)

Example ContactType values:
- Customer
- Supplier
- Internal
- Partner

---

#### Step 7: Use basic database features
Practice:
- Sorting contacts by **Company** or **City**
- Filtering by **ContactType**
- Searching for a specific **name or email**

Notice how quickly you can find information—this is a key benefit of databases.

---

### Part C: Basic “Database Thinking” (10–15 minutes)

#### Step 8: Database logic (conceptual)
Without writing code, think about what these mean:

- **SELECT** → choose data  
- **WHERE** → filter data  
- **ORDER BY** → sort data  

Write **plain-English queries**, for example:
- “Show all customers in London”
- “List suppliers added this month”
- “Sort contacts by company name”

This helps you understand how databases work behind the scenes.

---

### Part D: Digital Repositories Comparison (15 minutes)

#### Step 9: Review digital repositories
Open or think about a cloud storage tool you’ve used:
- OneDrive
- Google Drive
- Dropbox

Consider:
- Folder structures
- File sharing
- Access permissions
- Version control

---

#### Step 10: Complete the comparison table
Create a new table (in Access, Word, or Excel) titled **Repository Comparison**.

| Feature | Database (Access Table) | Digital Repository (Cloud Folder) |
|------|-------------------------|----------------------------------|
| Data structure | | |
| Search capability | | |
| Multi-user access | | |
| Data integrity | | |
| Best for | | |
| Example use at work | | |

Fill this in based on your experience in the lab.

---

### Part E: Reflection & Application (10 minutes)

#### Step 11: Written reflection (150–200 words)
Answer:

- What type of data does your workplace store in **tables or systems**?
- What data is stored in **folders or repositories**?
- One improvement you would suggest for data storage at work.

---

## 6. Submission (End of Class)

Submit:

- `Week5_Contact_Database_<YourName>.accdb`
- Reflection answers (either inside the database as a note or via the VLE, as instructed)

---

## 7. Pre / Post-Class Alignment

### Pre-Class
- Identify three workplace data sources (already completed)

### Post-Class
- Sketch **one additional table** relevant to your workplace, such as:
  - HR records
  - Inventory list
  - Training records

You may draw it on paper or create it in Access or a spreadsheet.
