# Week of 2026-05-05 - Niche Data Sources

Source: `/pvp-research altbanq.com` + `/pvp-research skolnik.com`

Theme: Going deeper than LinkedIn and Apollo. Public databases, scraping tools, and regulatory signals that reveal exactly when companies need to buy.

---

## Tuesday: The .gov Goldmine

**Graphic:** `01_gov_goldmine.png`
**Pillar:** Data Quality & Enrichment

Your SDR is searching LinkedIn.

Mine is searching EPA violation databases.

The best prospecting lists come from .gov domains. Free. Public. Updated daily. Here are 6 I use:

**SBA Open Data** (data.sba.gov)
Every 7(a) and 504 loan recipient. Searchable by state, industry, loan amount.

**EPA RCRAInfo** (rcrapublic.epa.gov)
Hazardous waste generators by state and NAICS code. Perfect for industrial suppliers.

**NRC ADAMS** (nrc.gov/reading-rm/adams)
Nuclear license applications and decommissioning notices. 3-5 years advance warning.

**FDA Warning Letters** (fda.gov/inspections)
Companies with 30-90 days to fix compliance issues. Urgent buyers with approved budgets.

**PHMSA Incidents** (phmsa.dot.gov)
Container failures and hazmat incidents. Immediate replacement purchases.

**SAM.gov Contract Awards**
Daily federal contract wins. See who needs subcontractors, 30-60 day mobilization windows.

None of this requires a subscription. None of it shows up in Apollo or ZoomInfo.

What public databases are you scraping?

---

## Wednesday: The Scraper Stack

**Graphic:** `02_scraper_stack.png`
**Pillar:** GTM Infrastructure

Found a public database full of your ideal prospects.

Now you need to get the data out.

Here's the stack I use to turn any public website into a lead list:

**1. Apify**
Pre-built scrapers for 2,000+ sites. LinkedIn, G2, job boards, directories. No code, just configure and run.

**2. Firecrawl**
API that turns any URL into clean JSON. Handles JavaScript rendering, pagination, auth walls. Feed it FDA warning letters, get structured data back.

**3. Open Web Ninja**
Custom scraping for sites that fight back. Captchas, rate limits, fingerprinting. They handle state licensing databases, conference attendee lists, anything difficult.

**4. Python + BeautifulSoup**
For simple gov sites. 50 lines of code. Runs in Claude Code. Extracted 10,000 SBA loan recipients in 20 minutes.

The data is public. The tools exist. The question is whether you're using them.

What's your extraction stack?

---

## Thursday: Signals With Expiration Dates

**Graphic:** `03_expiration_signals.png`
**Pillar:** Data Quality & Enrichment

Bombora tells you someone is "researching."

Regulatory filings tell you someone must buy by a specific date.

FDA 483 citation = 30-90 days to remediate or face shutdown.

Nuclear decommissioning notice = 3-5 years advance warning on multi-year projects.

DOD contract award = 30-60 days to mobilize, subcontractors needed immediately.

Superfund ROD signature = 6-12 months before remediation contractors needed.

Each of these is public record. Each has a deadline attached. Each tells you exactly when budget is approved and decisions are being made.

Traditional intent data: "They visited a competitor's pricing page."

Regulatory signal: "They have 60 days to fix a compliance violation or the FDA shuts them down."

Which one would you rather prospect?

---

## Notes

**Theme differentiation**: This series focuses on data extraction and niche sources, not CRM cleanup or HubSpot configuration. Positions RevAlign as doing deeper research than typical prospecting.

**Hooks tested**: Avoided "everyone's buying the same lists" cliche. Used direct statements instead: "Your SDR is searching LinkedIn. Mine is searching EPA databases."

**Source material**: Combined niche data sources from:
- altbanq.com PVP research (SBA, CFPB, BuiltWith, health dept databases)
- skolnik.com PVP research (EPA RCRAInfo, NRC ADAMS, FDA Warning Letters, PHMSA, DOD contracts)
