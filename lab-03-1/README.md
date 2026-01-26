# Sample Submission for Lab 3: AI and Automation in Business

---

## Student Information

- **Name:** James Wilson  
- **Student ID:** JW2024003  
- **Date:** April 10, 2024  
- **Lab:** 11 — Designing AI-Enabled Automation for Business Processes  
- **Group Members:** Sarah, Michael, Priya *(Group 4)*

---

## DELIVERABLE 1: Automation Use Case Description

### Part A: Concept Check

**One task that should NOT be automated**

> *“Approving sensitive customer complaints for refunds over £500. This requires human judgment to assess customer history, complaint validity, and potential relationship impact. Automated systems lack emotional intelligence and contextual understanding for high-value, sensitive decisions.”*

---

### Selected Business Scenario  
**Customer Enquiry Handling**

---

### Current “As-Is” Manual Process

**Trigger**  
Customer sends an enquiry email to `info@company.com`

**Steps Involved**
1. Office administrator checks shared inbox 3 times daily  
2. Reads each email and categorises it (Sales, Support, Billing, General)  
3. Forwards enquiry to the appropriate department with brief notes  
4. Logs enquiry in an Excel spreadsheet (date, category, assigned person)  
5. Sends a standard “We received your enquiry” confirmation email  
6. Follows up after 48 hours if no department response  

**Roles Responsible**
- Office Administrator (primary)  
- Department Heads (secondary assignment)  
- Customer Service Team (follow-up)

**Pain Points Identified**
- 2–4 hour delay before initial response due to batch inbox checks  
- Manual logging causes data entry errors (≈15% error rate observed)  
- Inconsistent categorisation between administrators  
- Follow-ups missed during busy periods  
- Spreadsheet becomes outdated quickly  

---

## DELIVERABLE 2: Zapier Workflow Implementation

**Workflow Name:** *Customer Enquiry Auto-Log & Route*  
**Filename:** `Zapier_Screenshots_James_Wilson.zip`

---

### Screenshots Included

- **Zap Overview:** `zap_overview.png`  
  - Shows complete workflow (Gmail trigger → Google Sheets action)  
  - **Status:** Published and Active  

- **Trigger Configuration:** `trigger_setup.png`  
  - **App:** Gmail  
  - **Trigger Event:** New Email Matching Search  
  - **Search String:**  
    ```
    to:info@exampletest.com OR subject:"enquiry" OR subject:"question"
    ```

- **Action Setup:** `action_setup.png`  
  - **App:** Google Sheets  
  - **Action Event:** Create Spreadsheet Row  

**Field Mapping**
- Timestamp → `{{Current Time}}`  
- Customer Email → `{{From Email}}`  
- Subject → `{{Subject}}`  
- Body Excerpt → `{{Body Plain (first 200 chars)}}`  
- Category → AI-determined  
- Status → `New`

- **Test Results:** `test_results.png`  
  - 3 successful test runs  
  - Data correctly populated in Google Sheets  

---

### Google Sheets Output

Timestamp	Customer Email	Subject	Body Excerpt	Category	Status
2024-04-10 14:30:22	customer1@test.com	Product enquiry	"Hello, I'm interested in..."	Sales	New
2024-04-10 14:32:45	customer2@test.com	Billing question	"I have a query about..."	Billing	New
2024-04-10 14:35:10	customer3@test.com	Support needed	"The product isn't working..."	Support	New

---

### AI-Enhanced Component

The workflow was enhanced using **ChatGPT** to automatically classify enquiries.

**ChatGPT Prompt Used**
You are an email classifier. Analyze this customer enquiry and categorize it as:
Sales, Support, Billing, or General. Return ONLY the category name.

Email subject: {{Subject}}
Email body: {{Body Plain}}

Rules:

If mentions 'buy', 'price', 'purchase', 'demo' → Sales

If mentions 'broken', 'not working', 'help', 'issue' → Support

If mentions 'invoice', 'payment', 'charge', 'bill' → Billing

Otherwise → General


**Implementation**  
Added as a *Code by Zapier* step between the Gmail trigger and Google Sheets action.

---

## DELIVERABLE 3: Automation Justification & Analysis

### Benefits vs. Risks Analysis

| Aspect | Analysis |
|---|---|
| **Efficiency Gain** | Processing time reduced from 2–4 hours to <5 minutes. Estimated saving: ~10 hours/week. |
| **Error Reduction** | Removes manual data entry; categorisation accuracy improved from ~65% to ~95%. |
| **Cost Implications** | No immediate cost (free tier tools). Long-term reduction in admin workload. Training time ≈ 2 hours. |
| **Data / Privacy Risk** | Medium risk due to third-party storage. Mitigation: DPAs, encryption, strict access control. |
| **Human Oversight Needed** | High. Daily review of classifications and weekly audit required. Sensitive emails bypass automation. |

---

### “To-Be” Process Summary

**Automated Steps**
- Email receipt and instant acknowledgement  
- Data extraction (sender, subject, excerpt)  
- AI-based categorisation  
- Automatic logging to central spreadsheet  
- Notification to relevant department channel  

**Manual Steps Remain**
- Daily review of AI categorisation  
- Handling sensitive or flagged emails  
- Escalation of complex enquiries  
- Final resolution and follow-up  

**System Monitoring**
- Daily admin review  
- Weekly audit of 10% of automated decisions  
- Monthly performance review  

**Error Handling**
- Failed emails routed to *Needs Review*  
- Alert if no emails processed in 24 hours  
- Manual fallback if automation fails  
- Regular spreadsheet backups  

---

## DELIVERABLE 4: Group Mini-Presentation Summary

- **Process Chosen:** Customer Enquiry Handling  
- **Automation Idea:** AI-classified email routing with automatic logging  

**Key Benefit**  
> *“Reduces initial response time from hours to minutes while ensuring enquiries reach the right department faster. The AI classifier improves over time through corrections.”*

**Key Risk**  
> *“Over-reliance on AI may misroute sensitive complaints.”*  

**Mitigation**  
- Keyword flagging for human review  
- Emails containing *complaint*, *legal*, or *urgent* bypass automation  

---

## DELIVERABLE 5: Individual Reflection *(195 words)*

The automation I would realistically propose at my workplace is automating the new employee onboarding checklist. Currently, HR manually creates 12 different accounts, schedules five training sessions, and coordinates with three departments—a process taking over eight hours per hire.

This automation would add value by ensuring consistency, reducing HR workload by approximately 70%, and improving the new-hire experience through timely, automated communications. The time saved would allow HR to focus on strategic initiatives such as engagement and retention rather than administrative work.

My main concern is integration complexity with legacy systems. Our payroll software lacks modern API access, requiring manual checkpoints. While around 80% of the process could be automated, salary and contract components must remain human-verified for compliance. A phased rollout—starting with email communications and account creation—would balance efficiency with regulatory safety. Regular audits would be essential to ensure compliance in sensitive areas such as payroll and data privacy.

---

## SUBMISSION PACKAGE

### Files Submitted via VLE
- `Automation_Use_Case_Group4.docx`  
- `Zapier_Workflow_JamesWilson.pdf`  
- `Automation_Justification.xlsx`  
- `Individual_Reflection_JamesWilson.docx`  

### Additional Evidence
- Shared Google Sheet with automated entries (link provided)  
- ChatGPT prompt export: `chatgpt_classification_prompts.txt`  
- Workflow diagram: `workflow_diagram.png`  

---

## Notes on Implementation

### Data Safety Compliance
- ✓ Dummy/test email addresses only  
- ✓ No real customer or company data  
- ✓ Clearly labelled as an academic exercise  

### Tools Used
- Zapier (Free Tier)  
- Gmail test account  
- Google Sheets  
- ChatGPT 3.5 (free version)  
- Lucidchart (free tier)  

### Scalability Considerations
The solution could scale by:
- Training AI with historical enquiry data  
- Adding priority scoring for urgent requests  
- Creating a real-time monitoring dashboard  
- Implementing SLA tracking for response times  
