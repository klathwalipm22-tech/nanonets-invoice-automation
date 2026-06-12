# 🤖 Nanonets Invoice Automation

> Eliminate manual data entry. Drop AI agents into your invoice workflow.

![Nanonets](https://img.shields.io/badge/Built%20with-Nanonets%20Agents-4472C4?style=for-the-badge)
![Google Sheets](https://img.shields.io/badge/Output-Google%20Sheets-34A853?style=for-the-badge)
![Automation](https://img.shields.io/badge/Type-No--Code%20Automation-FF6B6B?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

## 📌 Overview

This project automates the entire invoice data extraction process using **Nanonets Agents** — an AI-powered document automation platform. Instead of manually opening each invoice and copying data into a spreadsheet, the agent does it all automatically the moment invoices land in an email inbox.

**No code. No templates. No manual entry.**

---

## ⚡ What It Does

```
📧 Invoice PDF arrives via email
        ↓
🤖 Nanonets Agent reads and extracts data
        ↓
📊 Data saved automatically to Google Sheets
        ↓
✅ Done — in under 2 minutes
```

---

## 🚀 Step-by-Step Workflow

### Step 1 — Nanonets Homepage
![Nanonets Homepage](Nanonets%20homepage.png)

> Navigate to nanonets.com and click **Get Started** to create your free account.

---

### Step 2 — Nanonets Agents Dashboard
![Nanonets Agent Dashboard](Nanonets%20Agent%20dashboard.png)

> After logging in, you land on the Agents dashboard. This is the central hub for all your document automation tasks.

---

### Step 3 — Connect Google Sheets
![Google Sheets Connector](Google%20Sheets%20connector.png)

> Go to **Connectors** in the sidebar. Find Google Sheets and click **Connect**. Authorize your Google account via OAuth.

---

### Step 4 — API Connectors Page
![API Connectors Page](API%20Connectors%20Page.png)

> Nanonets supports connections to Microsoft Outlook, SharePoint, Gmail, Teams, SAP, Dynamics, PostgreSQL, and more — all available from this page.

---

### Step 5 — Configure the Agent
![Agent Configure Tab](Agent%20Configure%20tab%20-%20instruction.png)

> Create a new agent and enter this plain-English instruction:
> *"When a new invoice is uploaded, extract invoice number, date, vendor name, and total amount and save it to Google Sheets"*

---

### Step 6 — Add Google Sheets Tool
![Add Tool - Google Sheets Search](Add%20tool%20-%20Google%20Sheets%20Search.png)

> Click **+ Add tool**, search for "google sheets" and select **Google Sheets Update**.

---

### Step 7 — Google Sheets Tool Added
![Google Sheets Update Tool Added](Google%20Sheets%20Update%20tool%20Added.png)

> The tool appears as a tag below the instruction box — the agent now knows where to save extracted data.

---

### Step 8 — Create Configured Tool
![Create Configured Tool Dialog](Create%20Configured%20Tool%20dialog.png)

> Fill in the display name and description for the tool so the AI understands its purpose.

---

### Step 9 — Link Google Account
![Access Token - Google Account Selection](Access%20Token%20-%20Google%20account%20selection.png)

> Select your connected Google account from the Access Token dropdown to authorize write access to Sheets.

---

### Step 10 — Set Email Trigger
![Run When - Email Trigger Setup](Run%20when%20-%20email%20trigger%20setup.png)

> Click **Run when...** and copy your agent's unique inbound email address. Any invoice emailed here triggers the agent automatically.

---

### Step 11 — Send Invoices via Gmail
![Gmail - Invoices Sent to Agent](Gmail%20-%20invoices%20sent%20to%20agent.png)

> Attach invoice PDFs and send to the agent's inbound email. 10 invoices were processed in this project in a single email.

---

### Step 12 — Monitor Tasks
![Task Page - Running and Completed](Task%20Page%20-%20running%20and%20completed.png)

> Go to the **Tasks** page to monitor status in real time — Running or Completed with full audit trail.

---

### Step 13 — Milestone Completed
![Task Detail - Milestone Completed](Task%20detail%20-%20milestone%20compeleted.png)

> The agent confirms extraction is complete: *"Extracted invoice details from all 10 invoices and saved them to a new Google Sheet."*

---

### Step 14 — Results in Google Sheets
![Extracted Invoices - Google Sheet Output](Extracted%20Invoices%20-%20Google%20Sheet%20output.png)

> All 10 invoices extracted and structured automatically — Invoice Number, Date, Vendor Name, Total Amount — zero manual entry.

---

## 📊 Results

```
Total Invoices Processed  :  10
Fields Extracted Per File :  4
Total Data Points         :  40
Processing Time           :  Under 2 minutes
Manual Effort Required    :  Zero
```

---

## 🗂️ Data Extracted Per Invoice

| Field | Example |
|-------|---------|
| Invoice Number | INV-2024-001 |
| Date | January 10, 2024 |
| Vendor Name | TechSupply Co. |
| Total Amount | ₹16,194 |

---

## 🛠️ Tools & Integrations

- 🔷 **Nanonets Agents** — AI agent platform for document workflows
- 🟢 **Google Sheets** — Output destination via native API connector
- 📧 **Gmail** — Email trigger to auto-run the agent
- 📄 **PDF Invoices** — 10 invoices processed in this project

---

## 🔮 Scope for Scaling

- Process thousands of invoices in a single batch
- Chain agents: Extract → Validate → Route for Approval → Log to ERP
- Connect to SAP, Microsoft Dynamics, Sage Intacct, PostgreSQL
- Works across teams — anyone triggers it by forwarding an email

---

## 📁 Project Structure

```
nanonets-invoice-automation/
│
├── README.md                          # This file
├── Nanonets Invoice Automation Guide.docx  # Full step-by-step guide
├── screenshots (folder)               # Placeholder file
├── API Connectors Page.png
├── Access Token - Google account selection.png
├── Add tool - Google Sheets Search.png
├── Agent Configure tab - instruction.png
├── Create Configured Tool dialog.png
├── Extracted Invoices - Google Sheet output.png
├── Gmail - invoices sent to agent.png
├── Google Sheets Update tool Added.png
├── Google Sheets connector.png
├── Nanonets Agent dashboard.png
├── Nanonets homepage.png
├── Run when - email trigger setup.png
├── Task Page - running and completed.png
└── Task detail - milestone compeleted.png
```

---

## 👩‍💻 Author

**Khushi Lathwal**
MBA Applied Finance | Chitkara University
Specialization: GRC · ESG · Financial Automation

> 💡 *Built as part of AI Agents & Automation coursework — demonstrating real-world applications of no-code AI in financial operations.*
