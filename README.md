# Awesome-Automated-Invoicing-PDF-Invoices

# Awesome-Automated-Invoicing-PDF-Invoices

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.



I also have to flag what the search results actually support, because **several entries in your list have no usable vendor pricing**, and "Invoiced" is not the commercial product you likely intended.



## The data problems



**"Invoiced" does not appear as a commercial platform in these results.** The only "invoiced" entry surfaced previously was a self-hosted Go-based invoicing system with TOML storage and Git audit trails—an open-source project, not the commercial Invoiced platform. **Do not list it as a SaaS competitor to FreshBooks or Chargebee.**



**Chargebee's invoicing is not a standalone product.** Its pricing is **Flow at $0 + 0.80% of invoicing or $99 + 0.65%**, with 100M usage events/month included . There is no separate "Chargebee Invoicing" SKU. Mark it as a billing platform that includes invoicing.



**Bill.com's pricing is for AP automation, not invoicing.** Vendr benchmarks show base subscription often **$150–$650/month** for small deployments, with transaction fees **$0.49–$0.99 per ACH**, **$1.49–$1.99 per check**, and **2.9% + $0.49 per card** . This is accounts payable, not accounts receivable invoicing. **Do not present AP pricing as invoicing pricing.**



**QuickBooks Online pricing surfaced is promotional.** The page shows **Simple Start $19/mo (50% off for 3 months)**, **Essentials $42.50/mo**, **Plus $70/mo**, and **Advanced $170/mo** . These are discounted introductory rates—the standard prices are $38, $85, $140, and $340 respectively. **Label as promotional, not list price.**



## What the search results actually contain



**SaaS pricing (usable):**



| Platform | Entry pricing | Verified detail |

|---|---|---|

| **FreshBooks** | **Lite: 5 billable clients**; Plus: 50; Premium: unlimited  | 30-day free trial; payment processing **2.9% + $0.30**  |

| **Wave** | **Starter free** (unlimited invoices/estimates); **Pro $19/mo or $190/yr**  | Starter has **2.9% + $0.60** card fee; Pro has **2.9% + $0** on first 10 transactions  |

| **Xero** | **Early $27/mo** (20 invoices); **Growing $59/mo**; **Established $97/mo**  | 90% off first 6 months promo; unlimited users on all plans  |

| **Square Invoices** | **Free $0** (unlimited invoices); **Plus $30/mo**  | Free tier includes unlimited invoices and estimates; **2.2% online card rate**  |

| **Hiveage** | **Free** (5 clients); **Basic $16/mo** (50); **Pro $25/mo** (250); **Plus $42/mo** (1,000)  | 14-day full Pro trial  |

| **QuickBooks** | **Simple Start $19/mo promo** (standard $38); **Essentials $42.50 promo** (standard $85); **Plus $70 promo** (standard $140)  | 50% off for 3 months; access for 2 accountants  |



**Open-source project (usable):**



| Project | What it actually does | Status |

|---|---|---|

| **Invoice Ninja** | Open-source invoicing; **Free: 5 clients, unlimited invoices**; **Pro $14/mo** (unlimited clients); **Enterprise $18/mo**; self-hosting free beyond server cost  | Actively maintained |



**What is missing:**

- **No pricing** for Bill.com Invoicing as a standalone product—only AP automation pricing surfaced .

- **No pricing** for Chargebee Invoicing as a standalone product—only the billing platform percentage model .

- **No star counts** for Invoice Ninja in these results.



## What I recommend



**Remove "Invoiced"** from the SaaS list—no commercial product by that name surfaced.



**Mark Bill.com as "AP automation, not invoicing"** or omit it. Its pricing  is for accounts payable, which is a different workflow from sending invoices to customers.



**The open-source section has one strong entry: Invoice Ninja.** It has a genuine free tier (5 clients, unlimited invoices), paid tiers from $14/month, and self-hosting is free beyond server cost . It is invoicing-focused, not full double-entry accounting like FreshBooks or Xero.



**Flag the pricing model differences explicitly:** per-client (FreshBooks, Hiveage), per-invoice-volume (Xero Early), flat monthly (Wave Pro, Square Plus), and freemium with unlimited invoices (Square Free, Wave Starter, Invoice Ninja Free) produce different costs at the same client count. A reader choosing between them needs that context.



**Label QuickBooks promotional pricing clearly**—$19/mo is a 3-month discount, not the ongoing rate .



If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not fabricate Bill.com invoicing pricing, present Chargebee as a standalone invoicing product, or list the Go `invoiced` project as a SaaS competitor.
