# Practical Manual  
## Lab 06: Password & MFA Workshop — Cybersecurity Basics

## 1. Lab Overview

Passwords remain one of the **weakest points in cybersecurity**. Reused, predictable, or compromised passwords are a leading cause of data breaches in organisations.

In this lab, you will build **practical cybersecurity habits** by:

- Auditing your own (or example) accounts for password risks  
- Checking whether an email address has appeared in known data breaches  
- Safely testing password strength using **test-only passwords**  
- Setting up **Multi-Factor Authentication (MFA)** on a test account  
- Creating a short **security improvement plan** you can apply at work  

This is a **hands-on, practical lab** focused on real-world behaviour—not theory or technical hacking.

---

## 2. Learning Outcomes

By the end of this lab, you will be able to:

- Identify common password risks (reuse, weak patterns, personal information)
- Check breach exposure safely using reputable tools
- Explain how MFA works and enable it using an authenticator app
- Create a simple personal or workplace **security checklist**
- Propose one realistic cybersecurity improvement for your workplace

---

## 3. Prerequisites

### Before beginning, ensure you have:

#### Hardware & Access
- A **desktop or laptop** with internet access
- A modern web browser  
  (Chrome, Edge, or Firefox)

#### Spreadsheet Software (choose one)
- **LibreOffice Calc** (open-source, works offline – recommended)
- **Microsoft Excel**
- **Google Sheets**

#### Accounts & Apps
- Access to an **email inbox** (for test account signup)
- A **smartphone** (optional but recommended for MFA)

#### Authenticator App (choose one)
- **Aegis Authenticator** (Android, open-source)
- **2FAS** (iOS / Android, free)
- **Google Authenticator** or **Microsoft Authenticator**

> If you do **not** have a phone, you can still complete the audit and breach check. MFA will be demonstrated in class.

---

### ⚠️ Important Safety Rules (Read Carefully)

- **Do NOT share passwords with anyone**
- **Do NOT type real passwords into any website during class**
- Use **test-only passwords** for strength testing
- When checking breach exposure, use:
  - Your own email *only if comfortable*, OR  
  - A **demo email** provided in class  

---

## 4. Tools & Websites (Free and Reputable)

### 1. Breach Exposure Check
**Have I Been Pwned (HIBP)**  
https://haveibeenpwned.com/

- Created by security expert **Troy Hunt**
- Industry-standard breach checking tool
- Checks **email or phone number only**
- **Never asks for passwords**

---

### 2. Password Strength Testing (Safe Methods)

**Safest option (recommended):**
- Use your browser’s built-in password strength indicator  
  (Chrome, Edge, Firefox all include this)

**Alternative reputable checker (test passwords only):**
- Bitwarden Password Strength Tool  
  https://bitwarden.com/password-strength/

⚠️ **CRITICAL RULE:**  
Only test **fake/dummy passwords** you do not use anywhere.

---

### 3. Authenticator Apps (All Free)
- **Aegis Authenticator** – Android, open-source, local storage only  
- **2FAS** – iOS/Android, open-source, optional encrypted backup  
- **Authy** – iOS/Android/Desktop, cloud backup (less private)

**Recommendation:**  
- Aegis or 2FAS → best privacy  
- Authy → convenience across devices

---

### 4. Spreadsheet Software
- LibreOffice Calc – fully offline and private
- Excel / Google Sheets – acceptable for this lab

---

## 5. Lab Deliverables (What You Will Produce)

By the end of the lab, you will have:

- A **Password Audit Spreadsheet**
- A completed **Security Checklist**
- One **Security Improvement Plan** you will implement after class

---

## 6. Step-by-Step Procedure (Student Instructions)

---

### Part A — Create Your Password Audit Sheet (10–15 minutes)

#### Step 1: Open the spreadsheet
Open LibreOffice Calc (or Excel/Sheets) and save as:

Week6_Password_MFA_Workshop_<YourName>.xlsx

yaml
Copy code

---

#### Step 2: Create the “Password Audit” table
In Row 1, create these column headers:

| Account Type | Example Service (optional) | Risk Category | Password Reused? (Y/N) | Weak Pattern? (Y/N) | MFA Enabled? (Y/N) | Priority (High/Med/Low) | Action Needed |
|------------|----------------------------|--------------|------------------------|--------------------|--------------------|------------------------|---------------|

---

#### Step 3: Fill at least 8 rows (NO passwords)
Choose relevant account types such as:
- Email
- Banking
- Workplace login (Microsoft 365 / Google Workspace)
- Social media
- Online shopping
- Government services
- University / VLE
- Cloud storage

**Risk Category options:**
- High value (money / identity)
- Work / academic access
- Personal / social
- Low importance

---

#### Step 4: Identify your “Top 3 High-Risk Accounts”
Below the table, add:

High-risk account 1: __________ Action: __________
High-risk account 2: __________ Action: __________
High-risk account 3: __________ Action: __________

yaml
Copy code

---

### Part B — Breach Exposure Check (10–15 minutes)

#### Step 5: Use Have I Been Pwned
Go to:  
https://haveibeenpwned.com/

Enter:
- Your email address **OR**
- A demo email provided in class

---

#### Step 6: Record results safely
In a new section of your spreadsheet, record:

- **Email checked:** (mask it, e.g. `a***@domain.com`)
- **Result:**
  - No breach found  
  - Found in breaches (number shown)
- **Immediate actions (if breached):**
  - Change passwords
  - Enable MFA
  - Stop password reuse

**Quick discussion prompt:**  
What does a breach result *mean*—and what does it **not** guarantee?

---

### Part C — Password Strength Testing (15–20 minutes)

#### Step 7: Create 3 test-only passwords
Do **not** use real passwords.

Examples:
- **Weak:** `Company2026`
- **Medium:** `CoffeeMug!28Jan`
- **Strong passphrase:**  
  `Correct-Horse-Battery-Staple-Window-2026!`

---

#### Step 8: Test strength (safely)
Using a browser indicator or reputable checker, note:
- Strength rating (weak / medium / strong)
- What improves strength:
  - Length
  - Randomness
  - Uniqueness

---

#### Step 9: Write your password rules
Write **5 rules**, for example:
1. Minimum length of 14+ characters
2. Use passphrases
3. Never reuse passwords
4. Use a password manager (if allowed)
5. Enable MFA on high-risk accounts

---

### Part D — MFA Setup on a Test Account (20–30 minutes)

#### Step 10: Create or choose a test account
Choose **one**:
- A new or existing Google account
- A Microsoft account
- A dummy email account

---

#### Step 11: Install an authenticator app
Install one on your phone:
- Aegis (Android) OR
- 2FAS (iOS/Android)

---

#### Step 12: Enable MFA (TOTP)
In the account’s security settings:
1. Find **Two-Step Verification / MFA**
2. Choose **Authenticator App**
3. Scan the QR code
4. Enter the 6-digit code to confirm

---

#### Step 13: Save recovery options (private)
Do **not** submit these:
- Backup codes location
- Recovery email or phone number

---

#### Step 14: Verify MFA works
- Log out and log back in
- Confirm a code is required

Record in your spreadsheet:
- MFA enabled (Y/N)
- Method used (Authenticator / SMS)
- Any issues encountered

---

### Part E — Security Checklist & Action Plan (10 minutes)

#### Step 15: Complete the checklist (Yes / No)

- I do not reuse passwords for important accounts  
- My email account has MFA enabled  
- I can recognise phishing signs  
- I keep my devices updated  
- I know how to recover an account  

---

#### Step 16: Write ONE security improvement plan
Choose **one realistic action**:

- Enable MFA on workplace email (if allowed)
- Switch to passphrases
- Stop password reuse
- Use a password manager
- Enable automatic updates

Write:
- What I will do  
- When  
- Expected benefit  
- Potential barrier  
- How I will overcome it  

---

## 7. Submission (End of Class)

Submit:
- `Week6_Password_MFA_Workshop_<YourName>.xlsx`

**Optional:**  
A 100–150 word reflection:  
> “One thing I will change immediately and why.”

---

## 8. Pre / Post-Class Work

### Pre-Class
- Reflect on your password habits (reuse? weak patterns? MFA enabled?)

### Post-Class
- Implement one improvement and provide **evidence**:
  - Screenshot of MFA enabled (redact personal info), OR
  - Short reflection confirming the change

---

### Optional Add-On (If Time Allows): Phishing Mini-Exercise
- Review example emails (real vs phishing)
- Identify red flags
- Write **two rules** to avoid scams
