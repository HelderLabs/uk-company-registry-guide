# UK Company Registry Guide
A practical guide to extracting intelligence from Companies House for corporate research, beneficial ownership tracing and due diligence.

---
## What is Companies House?

Companies House is the UK's official register of companies. Every company incorporated in England, Wales, Scotland or Northern Ireland must register here. All filings are **free and publicly accessible** at [find-and-update.company-information.service.gov.uk](https://find-and-update.company-information.service.gov.uk).

---
## Company Types

| Code | Type | Notes |
|------|------|-------|
| Ltd | Private Limited Company | Most common. Shares not publicly traded. |
| PLC | Public Limited Company | Can offer shares to the public. |
| LLP | Limited Liability Partnership | Common for law/accountancy firms. Members not directors. |
| LP | Limited Partnership | Less common. Has general and limited partners. |

**Tip:** LLPs have **designated members** instead of directors. The members can be other companies (including foreign LLCs), which is common in acquisition structures.

## Key Sections of Every Company Record

### 1. Overview
- Registered office address
- Company status (Active / Dissolved / Liquidation)
- Incorporation date
- SIC code (nature of business)
- Next accounts and confirmation statement due dates

### 2. Officers (People)
- Lists all current and resigned **directors**, **secretaries**, and **LLP members**.
- Key things to look for:
- **Appointment date** — when did they join?
- **Resignation date** — when did they leave?
- **Nationality and country of residence** — signals foreign control
- **Date of birth** — helps distinguish between people with the same name
- Officers with very short tenures (days or weeks) are often **nominee directors** — professionals who temporarily hold the role during incorporation before real controllers take over
### 3. Persons with Significant Control (PSC)
- The PSC register was introduced in 2016. It lists individuals or entities that:
- Own more than 25% of shares or voting rights
- Have the right to appoint or remove the majority of the board
- Exercise significant influence or control
- **Important:** PSC data can be incomplete or inaccurate. Companies House does not verify it. Always cross-reference with other sources.

### 4. Filing History
A chronological log of every document filed. Key filings to look for:

| Filing | What it means |
|--------|--------------|
| Incorporation | Company was created |
| Confirmation statement (CS01) | Annual snapshot of ownership and structure |
| Accounts | Financial statements (may be abbreviated for small companies) |
| AP01 / AP02 | Appointment of director (individual / corporate) |
| TM01 / TM02 | Termination of director |
| SH01 | Return of allotment of shares — new shares issued |
| MR01 | Mortgage or charge registered — debt secured on assets |
| AD01 | Registered office address change |

### 5. Charges
Lists any mortgages, debentures or other charges (security interests) registered against the company. Useful for understanding debt structure and which lenders have security over assets.

---
## Reading the PSC Register

The PSC register shows the **ultimate beneficial owner** — the real person or entity in control. However there are important limitations:

- Entities with less than 25% ownership are not required to register
- Corporate PSCs (another company owns the shares) just push the question up one level — you must then trace that company
- Trusts and nominee arrangements can obscure the true owner
- Foreign companies are listed but their own beneficial ownership may not be visible in UK records

**Technique:** When a corporate entity is listed as PSC, search for that entity in Companies House or its home jurisdiction registry. Keep tracing up the chain until you reach an individual or a jurisdiction that doesn't disclose.

---
## Dissolved Companies

Dissolved companies still appear in Companies House searches. Their records remain accessible indefinitely. This is valuable because:

- Historical officer appointments are preserved
- Filing history shows what the company did before dissolution
- Dissolved holding companies often reveal past acquisition structures
- The registered address at time of dissolution often links to the law firm or formation agent that managed the dissolution

---
## Nominee Directors

A nominee director is someone temporarily appointed at incorporation — typically a paralegal or company formation agent — before real directors take over. Signs of a nominee:

- Appointed on the same day as incorporation
- Resigned within days or weeks
- Same person appears across hundreds of other companies (check their personal appointments profile)
- Address matches a law firm or company services provider

**Example:** A person with 1,000+ appointments across Companies House is almost certainly a professional nominee, not a genuine director of all those companies.

> >             >         >         >
> >             >         >         > ---
> >             >         >         >
> >             >         >         > ## Cross-Jurisdictional Structures
> >             >         >         >
> >             >         >         > UK companies are frequently used as part of larger international structures. Common patterns:
> >             >         >         >
> >             >         >         > - **Delaware LLC → UK LLP → UK Ltd → Operating company** — typical US-owned acquisition structure
> >             >         >         > - - **UK Ltd owned by BVI or Cayman company** — offshore holding, common in real estate
> >             >         >         >   - - **UK Ltd with Scottish or Welsh registered address** — may have different legal nuances
> >             >         >         >    
> >             >         >         >     - When a UK company is owned by a foreign entity, check:
> >             >         >         >     - - **SEC EDGAR** (US) for listed companies and their subsidiaries
> >             >         >         >       - - **OpenCorporates** for cross-jurisdictional entity search
> >             >         >         >         - - The home country registry (Delaware Division of Corporations, BVI Registry, etc.)
> >             >         >         >          
> >             >         >         >           - ---
> >             >         >         >
> >             >         >         > ## Useful Direct URLs
> >             >         >         >
> >             >         >         > | Resource | URL |
> >             >         >         > |----------|-----|
> >             >         >         > | Company search | https://find-and-update.company-information.service.gov.uk |
> >             >         >         > | Officer appointments | https://find-and-update.company-information.service.gov.uk/search/officers |
> >             >         >         > | OpenCorporates (global) | https://opencorporates.com |
> >             >         >         > | SEC EDGAR (US) | https://www.sec.gov/cgi-bin/browse-edgar |
> >             >         >         > | Land Registry (UK property) | https://www.gov.uk/search-property-information-land-registry |
> >             >         >         > | Charity Commission | https://register-of-charities.charitycommission.gov.uk |
> >             >         >         >
> >             >         >         > ---
> >             >         >         >

## Research Workflow

A standard corporate research workflow using Companies House:

1. **Search by company name** — find the exact legal entity
2. **Note the company number** — use this for all subsequent lookups, not the name
3. **Check Officers** — identify current and former directors, note nomination patterns
4. **Check PSC** — identify declared beneficial owners, trace corporate PSCs upward
5. **Review Filing History** — look for ownership changes, charges, address changes
6. **Cross-reference officer names** — search each officer's personal appointments to map their wider network
7. **Trace the holding structure** — follow ownership up through parent companies
8. **Document everything** — log every source URL, filing date, and company number

## Disclaimer
All information available through Companies House is public and freely accessible under UK law. This guide is for educational and research purposes. All research should be conducted using publicly available sources only.

