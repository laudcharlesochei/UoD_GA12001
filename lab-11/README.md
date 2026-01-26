# Practical Manual  
## Lab 11: Designing AI-Enabled Automation for Business Processes

---

## 1. Lab Overview

Many business roles include repetitive, rule-based tasks—replying to common emails, updating spreadsheets, routing requests, or logging enquiries. These are ideal opportunities for **automation**.

In this lab, you will think like a **digital business analyst** and learn how to:

- Spot automation opportunities in business processes
- Use AI (e.g., ChatGPT) to support idea generation and workflow design (no coding)
- Build a simple “if this, then that” workflow using a no-code automation tool (Zapier)
- Evaluate benefits, risks, and governance issues (privacy, errors, oversight)
- Produce a practical automation idea that can feed into your final assignment

This lab focuses on **design and decision-making**, not technical implementation.

---

## 2. Learning Outcomes

By the end of this lab, you will be able to:

- Explain how AI and automation improve business efficiency
- Identify suitable processes for automation
- Design a simple workflow using no-code tools
- Describe benefits, risks, and limitations of automation
- Communicate an automation proposal in clear business language

---

## 3. Prerequisites

### Before beginning, ensure you have:

#### Hardware & Access
- A **desktop or laptop**
- A **reliable internet connection**
- A modern web browser (Chrome, Edge, or Firefox)

#### Accounts (Free)
- An **email account** (for sign-up and testing)
- Free access to:
  - **Zapier** (free tier)
  - **Google Sheets**
  - **Gmail**
- Access to **ChatGPT** (free version is fine)

⚠️ **Data Safety Rule:**  
Do **not** use real customer data, workplace data, or private personal data. Use dummy/sample data only.

---

## 4. Pre-Class Work (as per module plan)

Before this lab, identify **one repetitive task** you do at work or university, such as:

- Logging enquiries into a spreadsheet
- Sending confirmation emails
- Updating a task list
- Collecting and organising form responses

Make brief notes:
- Who performs the task?
- How often does it happen?
- Why is it repetitive?

---

## 5. Lab Deliverables (What You Will Produce)

By the end of the lab, you will submit:

1. A designed **automation use case** (what you’re automating and why)
2. A simple **Zapier workflow** (or screenshots if you cannot publish)
3. A short **automation justification** (benefits + risks)

---

## 6. Step-by-Step Lab Procedure (Student Instructions)

---

### Part A: Understanding Automation & AI in Business (10 minutes)

#### Step 1: Quick concept check (guided)
Make sure you can explain:
- **Manual process** vs **automated workflow**
- Where **AI tools** add value (e.g., text generation, summarisation, classification)

**Write down:**  
One task you believe **should NOT** be automated, and why.  
(Example: approving refunds, hiring decisions, handling sensitive complaints.)

---

### Part B: Define an Automation Use Case (15 minutes)

#### Step 2: Form a small group
Work in groups of **3–4**.

#### Step 3: Select a business scenario
Choose one scenario (or propose your own):

- Customer enquiry handling
- Job application screening *(high-level only — avoid sensitive personal data)*
- Meeting request management
- Expense claim submission
- Training registration

#### Step 4: Describe the current (“As-Is”) manual process
In your group, write:

- **Trigger:** what starts the process?
- **Steps involved:** what happens from start to finish?
- **Who is responsible:** roles (not names)
- **Pain points:** time, errors, delays, missed follow-ups

---

### Part C: Use AI to Support Design (10 minutes)

#### Step 5: Use ChatGPT for idea generation (smart + critical)
Ask questions such as:
- “How could this process be automated?”
- “Which steps are suitable for automation?”
- “What risks should we consider?”
- “Where should humans stay in control?”

**Important:** Don’t accept suggestions blindly. Discuss:
- What is realistic for a business?
- What needs human oversight?
- What would require approvals or policy changes?

---

### Part D: Build a Simple Automation Workflow (20–30 minutes)

#### Simple Lab Activity: Automate Email → Spreadsheet using Zapier  
**Goal:** Automatically copy info from specific emails into a Google Sheet.

---

#### Step 6: Open three tabs (5 minutes)
Open these in your browser:

- Tab 1: Gmail (`gmail.com`)
- Tab 2: Google Sheets (`sheets.google.com`)
- Tab 3: Zapier (`zapier.com`)

---

#### Step 7: Create a test email (in Gmail)
Send an email to yourself:

- **To:** your own email address
- **Subject:** `Newsletter Signup - Test Student`
- **Body (copy exactly):**
Name: Alex Johnson
Email: alex@example.com

Send it, wait a few seconds, and confirm it appears in your inbox.

---

#### Step 8: Create a spreadsheet (in Google Sheets)
1. Create a **Blank** sheet
2. Add headers:

| A1 | B1 | C1 |
|---|---|---|
| Customer Name | Customer Email | Date Added |

---

#### Step 9: Sign up / log in to Zapier
1. Go to Zapier
2. Sign up (free tier) or log in
3. Go to the dashboard

---

#### Step 10: Create your first “Zap” (automation)
Zapier works like this:

- **Trigger:** *When this happens…*
- **Action:** *Then do this…*

##### 10.1 Trigger: Gmail (New email matching search)
1. Click **Create Zap**
2. Search for **Gmail**
3. Choose trigger: **New Email Matching Search**
4. Connect your Gmail account (Allow permissions)
5. In **Search String**, type: subject:"Newsletter Signup"
6. Click **Test trigger**  
You should see your test email.

---

#### Step 11: Action: Google Sheets (Create Spreadsheet Row)
1. Choose action app: **Google Sheets**
2. Choose action event: **Create Spreadsheet Row**
3. Connect your Google account
4. Select:
- Spreadsheet: your sheet
- Worksheet: `Sheet1`

##### Map fields (“take this → put it here”)
- **Customer Name:** choose **Body Plain** (email body text)
- **Customer Email:** choose **From Email** *(or “Body Plain” if preferred)*
- **Date Added:** choose **Current Time**

5. Click **Test action**
6. Go to Google Sheets, refresh, and confirm a new row appears.

---

#### Step 12: Publish and test your automation
1. Rename your Zap: My First Automation - <YourName>

2. Click **Publish**

Now send another test email to yourself with subject:
- `Newsletter Signup - New Customer`

Refresh Google Sheets after a short wait—your new row should appear automatically.

---

### Part E: Automation Evaluation (15 minutes)

#### Step 13: Analyse benefits and risks (group task)
Complete this table:

| Aspect | Notes |
|---|---|
| Efficiency gain | |
| Error reduction | |
| Cost implications | |
| Data/privacy risk | |
| Human oversight needed | |

---

#### Step 14: Create a “To-Be” process summary
Describe how the automated process works:

- Which steps are automated?
- Which steps remain manual?
- Who monitors the system?
- What happens when something goes wrong?

---

### Part F: Group Output & Reflection (10 minutes)

#### Step 15: Group mini-presentation (informal)
Each group gives a **2–3 minute** summary:

- Process chosen
- Automation idea
- Key benefit
- Key risk

#### Step 16: Individual reflection (post-class, 150–200 words)
Write:
- One automation you would realistically propose at work (or study)
- Why it adds value
- One concern or limitation

---

## 7. Submission (End of Class)

Submit:

- Your **automation use-case description**
- Your **workflow diagram or screenshots** (Zapier + Google Sheet)
- Your **short written justification** (benefits + risks)

---

## 8. Pre / Post-Class Alignment

### Pre-Class
- Identify one repetitive task (work or university)

### Post-Class
- Design one simple automation idea for workplace or study context
- Keep it as input to your **final assignment**
