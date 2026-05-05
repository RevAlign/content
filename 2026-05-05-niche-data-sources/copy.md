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

## Friday: Speed is Table Stakes

**Graphic:** `04_table_stakes.png`
**Pillar:** RevOps for Early-Stage

Analyzed 7 alt-lenders last week.

Every single one claims:
- Same-day funding
- No hard credit pull
- Simple application
- Fast approval

When your "differentiator" is the same as everyone else's, it's not a differentiator. It's table stakes.

So I asked a different question: What can this company offer that competitors literally cannot match?

Found 4 things:

**1. Zero-interest switching**
$40K interest-free if you move your payment processing. Nobody else bundles this.

**2. Float protection**
Cash buffer when your processor freezes funds. A product that doesn't exist elsewhere.

**3. $10M loan cap**
Most competitors max at $500K. For real expansion, size matters.

**4. No platform lock-in**
Unlike Square/PayPal, use their lending without switching your whole stack.

Speed is the cost of entry. The real question is: what's your moat?

---

## Bonus 1: The Undetectable Signal

**Graphic:** `05_undetectable_signal.png`
**Pillar:** Data Quality & Enrichment

The best buying signal I found has 10/10 pain and 3/10 detectability.

Bank loan rejection.

80% of small businesses get denied by traditional banks. They desperately need alternatives. Budget is pre-approved. Decision timeline is urgent.

Perfect signal. One problem: rejections are private. You can't scrape them.

So I scored every signal on two axes:
- Pain intensity (how much does it hurt?)
- Detectability (can you find these companies?)

| Signal | Pain | Detect |
|--------|------|--------|
| Bank rejection | 10 | 3 |
| Hiring Controller | 7 | 9 |
| Opening new location | 8 | 8 |
| Series A funding | 7 | 10 |
| Healthcare vertical | 8 | 9 |

The insight: Use high-pain/low-detect signals for inbound and SEO. Use high-detect signals for outbound.

Same buyers. Different entry points.

What's your highest-pain signal?

---

## Bonus 2: Mining Trustpilot

**Graphic:** `06_trustpilot_mining.png`
**Pillar:** Data Quality & Enrichment

Spent 2 hours reading 200+ Trustpilot reviews for a client.

Got more insight than 15 sales calls.

Customers are literally telling you how to sell to them. You just have to listen.

What to extract:

**Pain statements**
"They heard my urgent need at 9 am and by 4 pm there was money in my account."
→ Pain category: Urgency

**Switching triggers**
"I switched my processing and received $40,000 interest free."
→ Pain category: Incentive to switch

**Before/after**
"Growing from $3M to $25M wouldn't have been possible without their backing."
→ Pain category: Growth enablement

**Friction points**
"The process was simple, quick and hassle free."
→ Pain category: Process friction (competitors have it, they don't)

15 reviews. 4 pain categories. One hour of work.

Your prospects are writing your copy for you.

What review site are you mining?

---

## Notes

**Theme differentiation**: This series focuses on data extraction and niche sources, not CRM cleanup or HubSpot configuration. Positions RevAlign as doing deeper research than typical prospecting.

**Hooks tested**: Avoided "everyone's buying the same lists" cliche. Used direct statements instead: "Your SDR is searching LinkedIn. Mine is searching EPA databases."

**Source material**: Combined niche data sources from:
- altbanq.com PVP research (SBA, CFPB, BuiltWith, health dept databases)
- skolnik.com PVP research (EPA RCRAInfo, NRC ADAMS, FDA Warning Letters, PHMSA, DOD contracts)
- altbanq.com analysis (EDP scoring, wedge ranking, customer quotes)
