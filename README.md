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
- 📄 **PDF Invoices** — Input files (10 invoices processed in this project)

---

## 🚀 How It Works — Step by Step

**Step 1 — Connect Google Sheets**
Go to Nanonets → Connectors → Click Connect on Google Sheets → Authorize your Google account

**Step 2 — Create the Agent**
Go to Agents → New Agent → Configure tab → Enter this instruction:

```
When a new invoice is uploaded, extract invoice number, date, 
vendor name, and total amount and save it to Google Sheets
```

**Step 3 — Add Google Sheets Tool**
Click + Add tool → Search "google sheets" → Select Google Sheets Update → Link your Google account → Create Tool

**Step 4 — Set Email Trigger**
Click Run when... → Copy your agent's unique inbound email address

**Step 5 — Send Invoices**
Email your invoice PDFs to the agent's inbound address → Agent runs automatically

**Step 6 — Check Output**
Open Google Sheets → All invoice data extracted, structured, and saved ✅

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

## 📈 Why This Beats Manual Entry

| | Manual Process | Nanonets Agent |
|--|--|--|
| Time per invoice | 3–5 mins | Seconds |
| Human effort | High | Zero |
| Error risk | High | Minimal |
| Scalability | Limited | Unlimited |
| Audit trail | None | Full logs |

---

## 🔮 Scope for Scaling

- Process thousands of invoices in a single batch
- Chain agents: Extract → Validate → Route for Approval → Log to ERP
- Connect to SAP, Microsoft Dynamics, Sage Intacct, PostgreSQL
- Works across teams — anyone can trigger it by forwarding an email

---

## 👩‍💻 Author

**Khushi Lathwal**
MBA Applied Finance | Chitkara University
Specialization: GRC · ESG · Financial Automation

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin)](https://linkedin.com)

---

## 📁 Project Structure

```
nanonets-invoice-automation/
│
├── README.md                  # This file
├── sample-invoices/           # Sample PDF invoices used for testing
├── extracted-output/          # Google Sheets export (CSV)
└── guide/                     # Step-by-step setup guide (Word doc)
```

---

> 💡 *Built as part of AI Agents & Automation coursework — demonstrating real-world applications of no-code AI in financial operations.*
