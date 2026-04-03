<h1>Tally Automation System</h1>
This project automates the tedious, manual process of entering financial data from Excel spreadsheets directly into Tally ERP/Prime. By replacing manual data entry with Python-driven automation, it eliminates human error and drastically reduces processing time.

**Impact & Value**<br>
**Situation:**
Accounting teams often spend hours manually keying in hundreds of vouchers from Excel into Tally. This process is not only slow but highly prone to typos and data mismatches, leading to reconciliation nightmares at month-end.
**Task:**
I set out to create a bridge between Excel and Tally that could handle bulk data imports with a single click, ensuring 100% data integrity.

**Action:**
Using Python, I developed a script that parses structured financial data from an .xlsx file and communicates with Tally’s XML interface. I implemented logic to map Excel columns to Tally’s ledger fields, ensuring that debits, credits, and dates are synced perfectly.

**Result:**

Time Savings: Reduced data entry time by 90% (processing hundreds of entries in seconds instead of hours).

Accuracy: Achieved 0% manual entry error rate, eliminating the need for hours of troubleshooting and corrections.

Cost Efficiency: Freed up accounting staff to focus on high-value financial analysis rather than clerical data entry.

<h1>How it Works (For Non-Technical Users)</h1>
You don't need to be a coder to use this tool. Here is the "3-Step" workflow:

Prepare your Data: Put your financial transactions into the svsltd.xlsx template.

Run the Tool: Double-click the automation script.

Check Tally: Open your Tally company; all your vouchers will be automatically populated, organized, and ready for review.

Why this matters: For a business owner or accountant, this tool acts as a "Digital Assistant" that never gets tired and never makes a typo.

**Impact Highlights**
Scalability: Whether you have 10 entries or 10,000, the time taken remains nearly the same.

Audit-Ready: Since the data is pulled directly from the source file, the audit trail between your Excel records and Tally remains pristine.

**Tech Stack Used**
Language: Python

Data Handling: Pandas / Openpyxl

Interface: Tally XML / Request API
