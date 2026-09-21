# Al Raghda — Quote-to-Cash Job Management (MVP demo)

Bilingual (English / العربية) job management system for a signage, printing, laser & CNC workshop.
Single-file web app — open `index.html` or host on GitHub Pages. No server, no install.

## What's in this MVP (Phase 1 of the proposal)
- **Dashboard** — open enquiries, quotes awaiting approval, jobs in production, due this week, revenue and margin this month, jobs due soon, recent activity
- **Enquiries (CRM)** — every lead with source (Google, Instagram, WhatsApp, walk-in, referral, LinkedIn), need, deadline, status; one click to quote; WhatsApp link
- **Quotes** — rule-based quotation builder: material rate × (width × height) × qty, or per piece; installation; discount; VAT-ready; print/PDF; send on WhatsApp; approve → job created automatically
- **Jobs** — Kanban board Design → Approval → Production → Installation → Delivered → Closed; due dates, machine, assignee, late flag; actual materials, machine hours and labour hours give **margin per job**
- **Invoices** — created from a job; deposit and balance; cash / card / transfer payments; print/PDF tax invoice
- **Customers** — jobs and total value per customer
- **Settings** — company details, VAT %, labour rate, machine hourly rates, material price list; reset demo data

## Demo notes
- Data is stored in the browser (`localStorage`). "Reset demo data" in Settings restores the sample set.
- Company phone, prices and rates are sample/placeholder values from the proposal.
- Phase 2 (production board, inventory, owner dashboard, installer mobile view) and Phase 3 (customer portal, gift web shop, retainers, accounting integration) are scoped in the proposal deck; a production version adds a cloud database, user logins and WhatsApp Business API sending.

## Run on GitHub Pages
Settings → Pages → Source: *Deploy from a branch* → `main` / root. The app is then live at `https://<user>.github.io/<repo>/`.
