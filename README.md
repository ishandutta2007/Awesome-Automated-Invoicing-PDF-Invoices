# Awesome-Automated-Invoicing-PDF-Invoices

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.

I also have to flag what the search results actually support, because **several entries in your list have no usable pricing**, and "Invoiced" is not the product you think it is.

## The data problems

**"Invoiced" is not a standalone invoicing platform in these results.** The only "invoiced" entry surfaced is a **self-hosted Go-based invoicing system** (`github.com/mpdroog/invoiced`) that stores data as TOML files with Git audit trails . This is an open-source project, not the commercial Invoiced platform you likely intended. **Do not list it as a SaaS competitor to Chargebee or FreshBooks.**

**Bill.com Invoicing has no pricing surfaced.** The only Bill.com data in the results is for **AP automation** (Team tier $650/month for 10 seats, per-transaction fees), not for invoicing specifically . Do not present AP pricing as invoicing pricing.

**Chargebee's invoicing is bundled into its billing platform.** The pricing page shows **Flow at $0 + 0.80% of invoicing** or **$160/month** for up to $500K billing/month, with 100M usage events included . There is no standalone "Chargebee Invoicing" SKU. Mark it as a billing platform that includes invoicing.

**QuickBooks Online pricing was not surfaced in usable form.** The page returned only FAQ text about annual billing and add-ons—no tier prices . **Do not fabricate.**

## What the search results actually contain

**SaaS pricing (usable):**

| Platform | Entry pricing | Verified detail |
|---|---|---|
| **FreshBooks** | **Lite £8/mo per team member** (5 billable clients); Plus £11/mo (50 clients); Premium and Select higher  | 30-day free trial; unlimited invoices on all paid tiers  |
| **Wave** | **Starter free**; **Pro $19/month** ($190/year)  | Free tier has unlimited invoices; Pro adds auto-import and receipt capture  |
| **Xero** | **Early $27/mo** (20 invoices); Growing $59/mo; Established $97/mo  | 90% off first 6 months promotion; invoice limits on Early  |
| **Square Invoices** | **Free $0** (unlimited invoices); **Plus $30/month**  | Free tier includes unlimited invoices and estimates  |
| **Hiveage** | **Free $0** (5 clients); **Basic $16/mo** (50 clients); **Pro $25/mo** (250 clients); **Plus $42/mo** (1,000 clients)  | 14-day full Pro trial  |

**Open-source project (usable):**

| Project | What it actually does | Status |
|---|---|---|
| **Invoice Ninja** | Open-source invoicing; **Free plan: 5 clients, unlimited invoicing, 11 templates, recurring billing, client portal**; **Pro $14/mo** (unlimited clients); **Enterprise $18/mo**; **Premium Business from $280/year**  | Actively maintained; self-hosted or cloud  |

**What is missing:**
- **No pricing** for QuickBooks Online, Bill.com Invoicing, or Chargebee Invoicing as standalone products.
- **No star counts** for Invoice Ninja or invoiced in the results.
- **No revenue or valuation** for any vendor.

## What I recommend

**Remove "Invoiced"** from the SaaS list—the only result is an open-source Go project, not the commercial platform . If you want an open-source entry, use **Invoice Ninja** instead, which has verified free and paid tiers .

**Mark QuickBooks Online, Bill.com Invoicing, and Chargebee Invoicing as "pricing not surfaced"** or omit them. Bill.com's AP pricing is not invoicing pricing.

**The open-source section has exactly one strong entry: Invoice Ninja.** It has a genuine free tier (5 clients, unlimited invoicing), paid tiers from $14/month, and is actively maintained . Do not present it as a replacement for FreshBooks' accounting features—it is invoicing-focused, not full double-entry accounting.

**Flag the pricing model differences explicitly:** per-client (FreshBooks, Hiveage), per-invoice-volume (Xero), flat monthly (Wave, Square Plus), and freemium with unlimited invoices (Square Free, Invoice Ninja Free) produce different costs at the same client count. A reader choosing between them needs that context.

If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not fabricate QuickBooks or Bill.com invoicing pricing, present the Go `invoiced` project as a SaaS competitor, or claim Invoice Ninja replaces FreshBooks' full accounting.
