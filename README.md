# Blixwerk Templates

Practical, ready-to-use templates and small automation kits for freelancers and small businesses.

> Built and maintained by an autonomous AI agent system (Kontor-7). Products are created with AI assistance and checked automatically.

## Products

### [Freelancer Project, Time & Invoice Tracker (Excel)](https://blixwerk.gumroad.com/l/freelancer-project-invoice-tracker-xlsx)

![Freelancer Project, Time & Invoice Tracker (Excel)](images/freelancer-project-invoice-tracker-xlsx.png)

Excel tracker for clients, projects, hours and invoices: auto invoice numbers, due dates, overdue flags, dashboard. Sample data + PDF guide.

Stop losing track of billable hours and unpaid invoices. This Excel workbook keeps your clients, projects, time log and invoices in one place, linked by dropdowns and formulas.

What's included

- Empty template and a sample-data version (5 clients, 9 projects, time entries and invoices)
- Sheets: Instructions, Dashboard, Clients, Projects, Time Log, Invoices, Settings
- Automatic invoice numbers (e.g. INV-2026-001), due dates from payment terms, and OVERDUE flags with days overdue
- Partial payments, draft/void invoices, unbilled vs. invoiced hours, project budget tracking
- Dashboard: hours, billed and received per year, month and client, with a chart
- Locked formula cells (no password) and data validation to prevent typos
- Short PDF quick-start guide

Who it is for

Solo freelancers and tiny agencies who track work in scattered notes and want a simple, reliable sheet instead of paying for spreadsheet fixes.

How to use

Open the sample file to see how it works, then fill in Settings, Clients, Projects, Time Log and Invoices in that order. The Dashboard updates itself. Step-by-step instructions are on the first sheet and in the PDF.

Requirements

Excel 2010 or newer (Windows/Mac/365); works in LibreOffice Calc. Capacity: 200 clients, 200 projects, 2000 time entries, 500 invoices.

Please note

This is a tracking tool and gives no tax, accounting or legal advice. Personal and commercial use allowed; no resale or redistribution.

This product was created with AI assistance

**Price:** 12 USD · **[Get it on Gumroad](https://blixwerk.gumroad.com/l/freelancer-project-invoice-tracker-xlsx)**

---

### [CSV & Excel Data Cleaning Toolkit (Python scripts)](https://blixwerk.gumroad.com/l/csv-cleaning-toolkit-python)

![CSV & Excel Data Cleaning Toolkit (Python scripts)](images/csv-cleaning-toolkit-python.png)

Clean messy CSV/Excel exports in minutes: dedupe, fix dates, phones, encoding, split, merge, validate. Dry-run + change report.

Stop spending hours fixing messy CSV and Excel exports by hand. This toolkit gives you eight ready-to-run Python command-line tools and one rules file that cleans a whole export in a single command &ndash; and shows you exactly what it changed.

What is included

- csv_clean &ndash; all-in-one cleaner driven by a YAML or JSON rules file (trim, null values, value mapping, case, dates, phones, numbers, dedupe, validation)
- csv_dedupe &ndash; remove duplicates by chosen columns, keep first, last or the most complete row
- csv_normalize &ndash; unify many date styles, phone formats (E.164, international, national) and numbers such as 1.234,50
- csv_trim &ndash; strip stray, double, non-breaking and zero-width whitespace
- csv_fix_encoding &ndash; convert to UTF-8, repair garbled text like CafÃ©, change delimiters, remove BOM
- csv_split / csv_merge &ndash; split by row count or column value; merge many files even with different column order, encodings and delimiters
- csv_validate &ndash; check a file against column rules (required, unique, type, regex, min/max, allowed) with an exit code for automation
- Fully commented example rules in YAML and JSON, sample messy datasets with the exact expected output (including an .xlsx), a cheat sheet, and 50+ unit and end-to-end tests

Safe by design

Dry-run mode and a CSV change report on every tool. Your original file is never modified or overwritten, values the toolkit cannot understand are left unchanged and flagged, and the scripts n

**Price:** 15 USD · **[Get it on Gumroad](https://blixwerk.gumroad.com/l/csv-cleaning-toolkit-python)**

---

## Free guides

- [Track Unpaid Invoices and Overdue Payments in Excel (Free Setup)](https://blixwerk-shop.kontor7-agent.deno.net/guides/free-excel-template-track-unpaid-invoices-overdue-client-payments-free?s=github) – Build a free Excel sheet to track unpaid invoices and overdue client payments as a freelancer: columns, formulas, aging buckets, and a reminder routine.

- [Track Freelance Projects, Hours & Invoices in Excel](https://blixwerk-shop.kontor7-agent.deno.net/guides/how-to-track-freelance-projects-hours-and-invoices-in-excel?s=github) – Step-by-step guide to build an Excel tracker for freelance clients, hours and invoices, with formulas for invoice numbers, due dates and overdue flags.

- [How to Calculate Your Effective Hourly Rate in Excel](https://blixwerk-shop.kontor7-agent.deno.net/guides/how-to-calculate-effective-hourly-rate-freelancer-excel?s=github) – Learn to calculate your real freelance hourly rate in Excel: set up columns, use SUMIFS and IFERROR formulas, include unbilled time, and compare projects.

## Support

Questions or a bug in a template? Open an issue in this repository.
