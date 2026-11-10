# Awesome-Automated-Invoicing-PDF-Invoices

## Top Automated Invoicing & PDF Invoices Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Invoice Automation, PDF Generation & Billing Workflow Orchestration*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Automated Invoicing & PDF Invoices**. These tools help businesses create, send, and manage invoices programmatically — covering recurring billing, PDF rendering, payment reconciliation, tax handling, and accounts receivable automation.

**Examples** include Chargebee Invoicing, FreshBooks Invoicing, QuickBooks Online Invoicing, Wave Invoicing, Xero Invoicing, Invoiced, Bill.com Invoicing, Square Invoices, Hiveage, and Invoice Ninja (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosted billing systems, PDF invoice generation libraries, UBL/e-invoicing standards, and CI-native billing automation — ideal for freelancers, small businesses, developers, and finance teams building transparent, vendor-neutral invoicing pipelines.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform | Description | Pricing (Starting Tier) | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Chargebee Invoicing](https://www.chargebee.com/)** | Subscription billing and invoicing platform with usage-based metering, multi-currency support, tax handling, and ASC 606/IFRS 15 revenue recognition [citation:1][citation:13]. | $599/mo (Performance plan, billed annually) | Free for first $250,000 cumulative lifetime billing (Starter plan; 0.75% overage fee thereafter). |
| **[FreshBooks Invoicing](https://www.freshbooks.com/)** | Small-business accounting suite with customizable invoice templates, recurring billing, automated payment reminders, and downloadable PDF/Word/Excel formats [citation:2]. | $23/mo (Lite plan, up to 5 billable clients) | 30-day free trial with full feature access (no credit card required; no permanent free plan). |
| **[QuickBooks Online Invoicing](https://quickbooks.intuit.com/)** | Intuit's invoicing module with customer management, recurring invoices, online payment options, and automatic reminder scheduling [citation:3][citation:14]. | $38/mo (Simple Start plan, 1 user) | 30-day free trial with full plan access; permanent free tier limited to 2 invoices/mo and 1 connected bank account. |
| **[Wave Invoicing](https://www.waveapps.com/)** | Free invoicing for small businesses with three template styles, recurring invoice scheduling, automated reminders, and online payment acceptance [citation:4][citation:15]. | $19/mo (Pro plan) | Free forever plan with unlimited invoices and estimates (manual bank imports; 2.9% + $0.60 per card transaction). |
| **[Xero Invoicing](https://www.xero.com/)** | Cloud accounting platform with unlimited users, automated reminders, repeating invoices, online payment options, and 1000+ app integrations [citation:5]. | $29/mo (Early plan) | 30-day free trial with full access (no credit card required; Early plan limited to 20 invoices/quotes & 5 bills/mo). |
| **[Invoiced](https://www.invoiced.com/)** | Accounts receivable automation platform with AI-assisted invoicing, collections workflows, multi-rail payments (ACH, SEPA, Bacs), and real-time cash forecasting [citation:6]. | $50/mo (Entry/Startup plan) | 30-day free trial with full platform access (no permanent free plan). |
| **[Bill.com Invoicing](https://www.bill.com/)** | AP/AR automation with invoice intake via AI extraction, approval workflows, BILL Network vendor payments, and 1099/W-9 e-filing support [citation:7]. | $49/user/mo (Essentials plan) | 30-day free trial for AP/AR software; forever-free plan limited strictly to spend & corporate expense tracking. |
| **[Square Invoices](https://squareup.com/)** | Free unlimited invoicing with custom layouts, recurring invoices, milestone-based payment schedules, and digital contracts with e-signatures [citation:8]. | $49/location/mo (Plus plan) | Free forever plan with unlimited invoices and estimates (3.3% + 30¢ processing fee; lacks custom layouts & milestone schedules). |
| **[Hiveage](https://www.hiveage.com/)** | Online invoicing and billing for freelancers with estimates, 12+ payment gateways, recurring subscriptions, time/expense tracking, and multi-currency support [citation:9]. | $19/mo (Basic plan, up to 50 clients) | Free forever plan limited to 5 clients in CRM with unlimited invoices and estimates. |
| **[Invoice Ninja](https://invoiceninja.com/)** | Open-core invoicing platform with 11 invoice templates, recurring billing, client portal, PEPPOL e-invoicing, and REST API access on paid plans [citation:10]. | $14/mo (Ninja Pro plan, unlimited clients) | Free forever plan limited to 5 clients and 1 user with unlimited invoices (retains Invoice Ninja branding). |

## Open-Source GitHub Projects

- **[Invoice Ninja (Self-Hosted)](https://github.com/invoiceninja/invoiceninja)**  
  Full-featured self-hosted invoicing, quoting, and billing system with recurring invoices, payment gateway integrations, and client portal .

- **[InvoiceD](https://github.com/mpdroog/invoiced)**  
  Self-hosted invoicing and hour registration system storing data as human-readable TOML files with built-in Git audit trail, PDF generation, and UBL XML export [citation:11].

- **[go-invoice-generator](https://github.com/angelodlfrtr/go-invoice-generator)**  
  Go library for generating professional PDF invoices with support for taxes, discounts, multi-line items, logos, and HTML-formatted headers/footers [citation:12].

- **[Crater](https://github.com/crater-invoice/crater)**  
  Open-source invoicing app for freelancers and small businesses with estimates, recurring invoices, expenses, and payment tracking.

- **[Akaunting](https://github.com/akaunting/akaunting)**  
  Online accounting software for small businesses with invoicing, recurring billing, multi-currency, and client portal features.

- **[Kill Bill](https://github.com/killbill/killbill)**  
  Open-source subscription billing and payments platform with invoicing, entitlements, and usage metering for SaaS businesses.

- **[SolidInvoice](https://github.com/SolidInvoice/SolidInvoice)**  
  Open-source invoicing and quoting application built on Symfony with recurring invoices, payment tracking, and PDF export.

- **[FOSSBilling](https://github.com/FOSSBilling/FOSSBilling)**  
  Free, open-source billing and client management system for hosting providers and digital businesses.

- **[Blesta](https://github.com/blesta/blesta)**  
  Client management, billing, and support software with invoicing, recurring charges, and payment gateway modules.

- **[WHMCS (Open-Source Alternatives)](https://github.com/search?q=whmcs+alternative)**  
  Community billing solutions for hosting and subscription businesses; see also **FOSSBilling** and **Blesta**.

### Additional Strong Open-Source Options

- **[UBL (Universal Business Language)](https://github.com/OpenPEPPOL/peppol-bis-invoice-3)** libraries and schemas for standardized e-invoicing across EU/global networks.
- **[Factur-X](https://github.com/akretion/factur-x)** and **[ZUGFeRD](https://github.com/ZUGFeRD)** libraries for hybrid PDF/A-3 + XML e-invoices.
- **[dompdf](https://github.com/dompdf/dompdf)**, **[TCPDF](https://github.com/tecnickcom/TCPDF)**, and **[wkhtmltopdf](https://github.com/wkhtmltopdf/wkhtmltopdf)** for server-side HTML-to-PDF invoice rendering.
- **[Puppeteer](https://github.com/puppeteer/puppeteer)** and **[Playwright](https://github.com/microsoft/playwright)** for headless Chrome PDF generation from HTML templates.
- Many community **PEPPOL access point** implementations and **e-invoicing validation** tools.

**Frameworks for building custom systems**: Combine **Invoice Ninja** or **InvoiceD** with **go-invoice-generator**, **UBL libraries**, and **GitHub Actions** for end-to-end automated billing pipelines.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Invoicing tools must comply with applicable tax regulations (VAT, GST, PEPPOL, etc.) and e-invoicing mandates.
- Self-hosted open-source solutions require proper data backup, security, and regulatory validation.

---

**Made for freelancers, small business owners, finance teams, and developers building billing automation.**  
Let's make automated invoicing more open, transparent, and efficient.
