# JANOOMA — Customer Personas

*Based on janooma_reverse_engineering.md and deep-research-report.md (July 2026)*

> **Update note:** Persona 1 has been restructured. Rather than a single manufacturer, Ravi Sharma is now modeled as a **family of personas across the supply chain** — the same underlying business DNA (owner-operator, WhatsApp-native, relationship-driven, low-to-medium digital maturity) expressed at each tier: Manufacturer → Distributor → Wholesaler/Sub-dealer → Retailer. Company size shrinks as you move down the chain. Every stage shares two new dimensions: **strong offline presence with medium-to-zero online presence (and appetite to go online)**, and **medium-to-zero overseas presence (and appetite to go overseas)**.


# Persona 1: The Ravi Sharma Supply Chain Continuum

## 1.0 Concept Overview

Janooma's core wedge — AI SDR that finds distributors, buyers, and suppliers — serves not one business but an entire chain of businesses that look structurally alike and sit on the same WhatsApp-and-relationships operating system. Rather than treat "the manufacturer" and "the retailer" as unrelated personas, we model them as **one archetype recurring at four scales**:

| Stage | Who | Typical size | Role in the chain |
|-------|-----|--------------|--------------------|
| **1A** | **Ravi Sharma** — Manufacturer / Owner-Operator | ₹5–25 Cr, 50–150 employees | Makes the product, sells to distributors |
| **1B** | **Deepak Nair** — Regional Distributor | ₹2–10 Cr, 10–40 employees | Buys in bulk from manufacturers, sells to wholesalers/sub-dealers across a state or region |
| **1C** | **Farooq Ansari** — Wholesaler / Sub-Dealer | ₹50 L–3 Cr, 3–12 employees | Buys from distributors, breaks bulk, sells to retailers in a district or cluster of towns |
| **1D** | **Meena Joshi** — Retailer / Kirana-style Shop | ₹20 L–1 Cr, 1–5 employees | Buys from wholesalers/sub-dealers, sells to end customers |

As you move from 1A → 1D: **revenue shrinks, headcount shrinks, digital maturity drops, and the "job to be done" shifts from finding downstream partners to finding both upstream supply and local customers.** But every stage shares the same four cross-cutting traits described below, which now apply uniformly across the whole persona family.

### Shared cross-cutting traits (apply to all four stages)

| Trait | Description |
|-------|-------------|
| **Offline presence** | Strong to very strong at every stage — decades of local reputation, personal relationships, physical shopfronts/warehouses/factories. This is the core asset. |
| **Online presence** | Medium (1A/1B) to near-zero (1C/1D). No or minimal website, patchy/no social media, listing presence (if any) is outdated or third-party-managed. |
| **Interest in going online** | Present at every stage but expressed differently — 1A/1B want a lead-generation engine and better distributor discovery; 1C/1D want to be *findable* by nearby buyers and want an easier way to *reach new suppliers* without traveling. All want it with near-zero technical effort. |
| **Overseas presence** | Medium (1A, via export-oriented distributors or trade fairs) to zero (1B/1C/1D, who have never sold or bought outside India). |
| **Interest in going overseas** | Present but aspirational rather than urgent — most vivid at 1A (export as a growth lever) and faintest at 1D (not on the radar until prompted, but not rejected either). Framed as "if it were easy, I'd try it," not as a current priority. |

### Confidence: High — directly supported by the website's target-persona description of Indian manufacturing SMBs and their three-tier distribution model; the multi-stage framing and the offline/online/overseas dimensions are validated extensions based on field research into the same distribution chain.


## 1A. Ravi Sharma — The Manufacturer

### Executive Summary

| Attribute | Detail |
|-----------|--------|
| **Name** | Ravi Sharma |
| **Company type** | Family-owned manufacturing business |
| **Industry** | Electrical / Lighting (switchgear, LED components, MCBs) |
| **Company size** | 50–150 employees |
| **Annual revenue** | ₹5–25 Cr |
| **Geography** | Tier-1 city HQ; distribution targets across South India / Tier-2-3 markets |
| **Decision-making authority** | Owner / Managing Director — final decision-maker |
| **Digital maturity** | Low-medium — WhatsApp, Tally, Excel. No CRM |
| **Offline presence** | Very strong — 10–15 years of distributor relationships, factory, trade fair presence |
| **Online presence** | Medium-low — no real website beyond a placeholder, occasional IndiaMART listing, no active social media |
| **Interest in going online** | High — wants a repeatable digital lead-generation engine, not a brand-building website |
| **Overseas presence** | Low-medium — has fulfilled a handful of one-off export orders via a trading intermediary; no direct export relationships |
| **Interest in going overseas** | Medium — sees Middle East / Africa electrical demand as a plausible growth lever if someone else does the market discovery |

### Company Profile

**Business model:** Manufactures electrical components and sells through ~15–20 distributors, with gaps in South India and Tier-2 cities. Some direct institutional sales to panel builders and contractors.

**Team structure:** Ravi (owner) handles strategy and key relationships; a production manager runs the factory; 3–4 sales staff handle inquiries and orders; an accountant manages Tally and GST; warehouse staff manage dispatch.

**Sales process:** Primarily inbound. Distributors order via phone/WhatsApp. Occasional outbound calling. Trade fairs (Elecrama, etc.) generate 2–3 new leads a year. No structured lead generation.

**Current software stack:** Tally Prime, WhatsApp Business, Excel, email (formal documents only).

**Distribution model:** Three-tier — Ravi's company → regional distributors (see 1B) → wholesalers/sub-dealers (see 1C) → retailers (see 1D). Built over a decade of relationships; no systematic new-partner discovery process.

### Goals

- Expand distribution footprint in South India; grow revenue 20–30% YoY
- Reduce dependency on 2–3 distributors who account for 60% of revenue
- Onboard 30–50 new distributors in Tier-2/3 cities within 12 months
- Enter new product categories (e.g., solar) with dedicated channel partners
- **New:** Test 1–2 export markets without hiring a dedicated export team

**Personal success metrics:** "I want to wake up to qualified leads on my WhatsApp instead of spending hours on research." "I want to know exactly which cities — and now, maybe which countries — need my products."

### Pain Points

| Severity | Pain Point |
|----------|------------|
| **Critical** | Weeks of manual work to find distributors |
| **Critical** | Scattered across disconnected tools: Google, WhatsApp, Excel, directories |
| **High** | ₹4K–9K/month on IndiaMART with poor lead-to-order conversion |
| **High** | No systematic way to verify distributor credibility |
| **Medium** | No visibility into overseas demand — doesn't know where to start |
| **Medium** | Ravi is the bottleneck for every key relationship |

### Buying Behaviour

Skeptical of "tech solutions," needs a 5-minute explanation and clear ROI. Controls budget personally. Trust signals: no credit card, pay for outcomes, direct founder access, peer usage in the electrical industry. Objections mirror the base case: "How do I know it works?", "My data is sensitive," "I already pay for IndiaMART."

### Relationship with AI

Novice. Would delegate prospect research, lead identification, initial outreach, data enrichment. Would **not** delegate final relationship negotiation or partner approval. Would consider AI for a first pass at "who buys electrical components in country X" if framed as low-effort exploration, not a commitment to export.

### Relationship with Janooma

**Primary jobs-to-be-done:** "Find 50 distributors for my LED switchgear in South India"; "Find 30 panel builders sourcing MCBs"; and now, exploratively, "Show me who imports electrical components in the UAE."

**Aha moment:** A ranked WhatsApp list of 50 distributor candidates within 24–48 hours, with confidence scores and contacts.

**Feature priorities:** AI SDR — Find Distributors (critical), WhatsApp-native delivery (critical), ranked/confidence-scored results (high), pay-per-outcome pricing (high); AI Researcher for export market intelligence moves from "nice to have" to a real second-tier priority given the new overseas interest.

### Design Implications (specific to this stage)
- Keep the domestic distributor flow as the primary path; introduce export/overseas discovery as an optional, low-commitment "explore" mode rather than a separate product
- Messaging should not oversell export readiness — frame as "see who's out there," not "start exporting"


## 1B. Deepak Nair — The Regional Distributor

### Executive Summary

| Attribute | Detail |
|-----------|--------|
| **Name** | Deepak Nair |
| **Company type** | Regional distribution / stockist business |
| **Industry** | Electrical / lighting distribution across a state or multi-city region |
| **Company size** | 10–40 employees |
| **Annual revenue** | ₹2–10 Cr |
| **Geography** | Operates from a Tier-2 hub city, covers a state or cluster of districts |
| **Decision-making authority** | Owner/proprietor — sole decision-maker |
| **Digital maturity** | Low-medium — WhatsApp-first, basic billing software, no CRM |
| **Offline presence** | Very strong within his region — personally knows most wholesalers/sub-dealers and retailers he sells to |
| **Online presence** | Low — no website, may have an outdated IndiaMART or Justdial listing |
| **Interest in going online** | Medium-high — wants to be found by manufacturers looking for regional partners, and to find new sub-dealers faster than by traveling |
| **Overseas presence** | None |
| **Interest in going overseas** | Low but not zero — curious about becoming an import agent for a foreign brand if the opportunity were surfaced to him, not something he's actively pursuing |

### Company Profile

**Business model:** Buys in bulk from 5–8 manufacturers (like Ravi Sharma), holds inventory in a regional warehouse, sells to 30–60 wholesalers/sub-dealers and larger retailers across his territory. Margin comes from volume and reliable stocking, not brand-building.

**Team structure:** Deepak (owner), 2–3 sales/relationship staff who tour the territory, warehouse/logistics staff, a part-time accountant.

**Sales process:** Relationship-led. Sub-dealers call or WhatsApp orders in. Deepak's team does periodic "route visits" to existing and prospective sub-dealers. New manufacturer tie-ups come through trade fairs or manufacturer outreach — rarely the other way around.

**Procurement process (from manufacturers):** Long-standing relationships with a handful of manufacturers; adding a new manufacturer line is opportunistic, not systematic.

### Goals

- Add 2–3 new manufacturer product lines to distribute without losing focus on core lines
- Expand sub-dealer network into 2 uncovered districts
- Reduce time spent traveling to find and vet new sub-dealers
- Get discovered by manufacturers (like Ravi) looking for regional coverage, instead of only chasing them

### Pain Points

| Severity | Pain Point |
|----------|------------|
| **Critical** | Manufacturers don't know he exists — new mandates come from who he happens to meet at a trade fair |
| **High** | Finding new sub-dealers means physically traveling town to town |
| **High** | No way to verify a new sub-dealer's creditworthiness before extending stock on credit |
| **Medium** | Juggles 5–8 manufacturer relationships with no system, just memory and WhatsApp threads |

### Buying Behaviour

Needs it framed as "get found, get leads" on both sides of his business — upstream (manufacturers who want regional coverage) and downstream (new sub-dealers). Price-sensitive; will only pay for results. Trusts WhatsApp-native delivery and peer recommendation from other distributors far more than a sales pitch.

### Relationship with AI

Novice-to-low-intermediate. Comfortable with the idea if it's explained as "finds you sub-dealers and gets you noticed by manufacturers," not as "AI platform." Would delegate prospecting and discovery; would not delegate credit decisions or long-standing manufacturer relationships.

### Relationship with Janooma

**Primary jobs-to-be-done:** "Find 40 sub-dealers for electrical goods in [district]"; "Get my distribution business in front of manufacturers looking for regional partners in [state]."

**Feature priorities:** WhatsApp-native lead delivery (critical), pre-indexed/discoverable profile so manufacturers can find him (critical), AI SDR — Find Sub-Dealers/Buyers (critical), pay-per-outcome pricing (high). Dashboards and CRM integration are low priority — he doesn't use either today.

### Design Implications (specific to this stage)
- A "get discovered" profile matters as much as outbound lead-finding — this stage is the first in the chain where inbound discoverability is a distinct, valued job
- No CRM integration needed; keep everything inside WhatsApp


## 1C. Farooq Ansari — The Wholesaler / Sub-Dealer

### Executive Summary

| Attribute | Detail |
|-----------|--------|
| **Name** | Farooq Ansari |
| **Company type** | Wholesale / sub-dealer business |
| **Industry** | Electrical goods, hardware, or building materials, sold to retailers across a district or town cluster |
| **Company size** | 3–12 employees |
| **Annual revenue** | ₹50 L–3 Cr |
| **Geography** | Based in a Tier-3 town, serves surrounding smaller towns and villages |
| **Decision-making authority** | Owner — sole decision-maker |
| **Digital maturity** | Low — WhatsApp for orders, paper or very basic billing software |
| **Offline presence** | Strong locally — every retailer within a 30–40 km radius knows his shop |
| **Online presence** | Very low to none — no website, no listings, findable only by word of mouth |
| **Interest in going online** | Medium — mainly wants to be reachable by new retailers and to find better/cheaper distributors upstream, not to "build a brand" |
| **Overseas presence** | None |
| **Interest in going overseas** | Effectively none, but not actively opposed — would engage only if it appeared as a downstream effect of a distributor/manufacturer relationship, never self-initiated |

### Company Profile

**Business model:** Buys in smaller bulk from 2–3 regional distributors (like Deepak), breaks it into smaller lots, sells to 40–80 retailers spread across nearby towns. Runs on thin margins and fast turnover.

**Team structure:** Farooq (owner), 1–2 helpers for loading/delivery, occasionally a family member handling accounts.

**Sales process:** Entirely relationship and route-based — retailers call or WhatsApp in orders; Farooq or a helper delivers by bike/tempo. No marketing of any kind.

**Procurement process:** 2–3 known distributors; switching or adding one happens only if an existing one runs out of stock or raises prices sharply.

### Goals

- Find a second distributor for his top-selling product line to avoid stockouts
- Add 10–15 new retailer accounts in a neighboring town he doesn't currently serve
- Reduce the 1–2 days a month he loses traveling to the district distribution hub just to check on stock and pricing

### Pain Points

| Severity | Pain Point |
|----------|------------|
| **Critical** | Entirely dependent on 2–3 distributors — a stockout or price hike has no fast alternative |
| **High** | No way to find new retailer customers beyond his existing delivery route |
| **High** | Loses a day or more each month traveling just to gather pricing/stock information |
| **Medium** | Doesn't know what's happening in the neighboring town's retail market |

### Buying Behaviour

Extremely price- and effort-sensitive. Needs a WhatsApp message, not a dashboard. Won't set anything up himself — needs either a family member or a Janooma-side person to do it for him. Trust comes from a peer wholesaler using it successfully, not from marketing copy.

### Relationship with AI

Doesn't know what AI is, similar to Sunil/Meena. Wants only the outcome — "more retailer customers" and "another distributor to call when I'm short on stock" — described in plain language.

### Relationship with Janooma

**Primary jobs-to-be-done:** "Find me a second distributor for MCBs near [district]"; "Help retailers in [neighboring town] find me."

**Feature priorities:** WhatsApp-native delivery (critical), zero-setup/pre-filled profile (critical), AI SDR — Find Suppliers/Buyers (critical). Everything else — dashboards, confidence scores, file attachments — is low priority; he has no digital documents to attach and no time to review analytics.

### Design Implications (specific to this stage)
- Setup must be done *for* him, likely via a family member or local Janooma outreach, exactly as with Sunil/Meena at the retail end
- The single most valuable feature is simply reducing his upstream single-source risk


## 1D. Meena Joshi — The Retailer

### Executive Summary

| Attribute | Detail |
|-----------|--------|
| **Name** | Meena Joshi |
| **Company type** | Small retail / kirana-style shop |
| **Industry** | Electrical, hardware, or general consumer goods retail |
| **Company size** | 1–5 employees (often family-run) |
| **Annual revenue** | ₹20 L–1 Cr |
| **Geography** | Tier-3 town or large village |
| **Decision-making authority** | Owner — sole decision-maker |
| **Digital maturity** | Very low — WhatsApp only, sometimes not even that for business |
| **Offline presence** | Very strong locally — known by name to most regular customers, often for a generation |
| **Online presence** | Zero to negligible — no website, no listings, occasionally a Google Maps pin someone else set up |
| **Interest in going online** | Medium — wants more walk-ins and phone/WhatsApp orders, not a website or social media presence she'd have to maintain |
| **Overseas presence** | None |
| **Interest in going overseas** | None — not a meaningful concept at this scale; not part of her mental model of the business at all |

### Company Profile

**Business model:** Buys from 1–3 wholesalers/sub-dealers (like Farooq), sells to local retail and small-business customers. Relationship-based credit with regulars is common.

**Team structure:** Meena and one or two family members or shop assistants.

**Sales process:** Entirely walk-in and word-of-mouth. No marketing, no digital order-taking beyond occasional WhatsApp requests from known customers.

**Procurement process:** 1–3 known wholesalers, contacted by phone/WhatsApp; switching is rare and only happens on a serious price or stock problem.

### Goals

- Get a few more customers walking in or calling, especially younger ones who don't know her shop exists
- Find a wholesaler with slightly better margins without having to travel to check
- Not be left behind as bigger, more visible competitors open nearby

### Pain Points

| Severity | Pain Point |
|----------|------------|
| **Critical** | No digital presence at all — invisible to anyone who doesn't already know the shop |
| **High** | No easy way to compare wholesaler prices without visiting in person |
| **High** | Feels the pressure of larger, more visible competitors without knowing how to respond |
| **Medium** | Has no idea what nearby customers are actually looking for that she isn't stocking |

### Buying Behaviour

Same pattern as the base retail persona: needs someone else — a child, a shop assistant, or a Janooma team member — to set everything up. Only trusts what she can see working, delivered entirely inside WhatsApp, for free or nearly free.

### Relationship with AI

Doesn't know what AI is and doesn't need to. Wants "more customers" and "another supplier to call," nothing more abstract than that.

### Relationship with Janooma

**Primary jobs-to-be-done:** "Send me customer inquiries near my shop"; "Show me a supplier with better prices for [product]."

**Aha moment:** An unprompted WhatsApp message — "A customer nearby is looking for [product] — here's their contact" — that turns into a sale with zero effort on her part.

**Feature priorities:** WhatsApp-native delivery (critical), pre-indexed/zero-setup profile (critical), AI SDR — Find Suppliers/Buyers (critical). Dashboards, confidence scores, multi-channel outreach, and file attachments are all low priority or irrelevant.

### Design Implications (specific to this stage)
- Identical UX posture to the original Sunil Rao design implications: WhatsApp-only, zero learning curve, family-assisted setup
- "Overseas" has no place anywhere in this stage's product experience — omit entirely rather than gesture at it


## 1.9 Cross-Stage Summary Table

| Dimension | 1A Manufacturer (Ravi) | 1B Distributor (Deepak) | 1C Wholesaler (Farooq) | 1D Retailer (Meena) |
|-----------|--------------------------|----------------------------|----------------------------|--------------------------|
| **Revenue** | ₹5–25 Cr | ₹2–10 Cr | ₹50 L–3 Cr | ₹20 L–1 Cr |
| **Employees** | 50–150 | 10–40 | 3–12 | 1–5 |
| **Core job-to-be-done** | Find distributors | Find sub-dealers + get found by manufacturers | Find a backup distributor + find retailers | Find customers + find a backup supplier |
| **Offline presence** | Very strong | Very strong (regional) | Strong (local) | Very strong (hyperlocal) |
| **Online presence** | Medium-low | Low | Very low | Zero |
| **Interest in going online** | High | Medium-high | Medium | Medium |
| **Overseas presence** | Low-medium | None | None | None |
| **Interest in going overseas** | Medium | Low | Near-zero | None |
| **Setup capability** | Can self-serve with guidance | Can self-serve with guidance | Needs help | Needs family/team help |
| **Primary channel** | WhatsApp | WhatsApp | WhatsApp | WhatsApp |
| **Pricing sensitivity** | Medium | Medium-high | High | Very high |

**Product implication:** A single WhatsApp-native, zero-setup, pay-per-outcome experience can serve all four stages with the same core AI SDR worker, provided the *direction of search* adapts to the stage — manufacturers and distributors mostly search downstream and want to be found upstream; wholesalers and retailers mostly search upstream for supply while wanting to be found by customers downstream. An "explore overseas" mode is a relevant, low-commitment add-on only at the manufacturer and (weakly) distributor stages, and should not appear at all for wholesalers and retailers.


# Persona 2: Priya Patel — The Sales/Business Development Manager

## 1. Executive Summary

| Attribute | Detail |
|-----------|--------|
| **Name** | Priya Patel |
| **Company type** | Mid-size manufacturing or B2B services company |
| **Industry** | Packaging / Industrial Machinery / Building Materials |
| **Company size** | 100–300 employees |
| **Annual revenue** | ₹25–100 Cr |
| **Geography** | Based in Tier-1 city, responsible for national or regional expansion |
| **Decision-making authority** | Recommender / Implementer — reports to VP Sales or Owner; has budget influence but not final sign-off |
| **Digital maturity** | Medium. Uses CRM (Zoho/Salesforce), LinkedIn Sales Navigator, Excel. Comfortable with digital tools. |

**Confidence: High** — Directly supported by "Sales/Business Development Manager" persona description.

## 2. Company Profile

**Business model:** Priya works for a mid-size manufacturer in packaging, industrial machinery, or building materials. The company has an established presence in their home region but is expanding into new geographies and customer segments. They sell through a mix of direct sales, distributors, and channel partners.

**Team structure:**
- VP Sales (Priya's manager) — sets targets, reviews performance
- **Priya** — Sales/Business Development Manager, responsible for lead generation and channel expansion
- 5–10 sales representatives — handle inbound inquiries, follow-ups, account management
- Marketing team (2–3 people) — handles collateral, digital presence, trade shows
- Operations/Logistics team — handles order fulfilment

**Sales process:** Structured but manual. Priya's team uses a CRM (Zoho or Salesforce) to track leads and opportunities. Leads come from multiple sources: website inquiries, trade shows, LinkedIn outreach, referrals, directories (IndiaMART/TradeIndia). Priya spends 40–60% of her time on prospecting and research — manually identifying potential distributors, buyers, and partners.

**Procurement process:** Not applicable — Priya is on the sales side.

**Current software stack:**
- CRM (Zoho or Salesforce) — lead and opportunity tracking
- LinkedIn Sales Navigator — prospecting
- Excel — data analysis, lead list management, reporting
- WhatsApp — communication with prospects and partners
- Email — formal outreach and documentation
- IndiaMART/TradeIndia — lead generation (company has paid subscriptions)

**Communication channels:** Email (formal), WhatsApp (fast follow-ups), LinkedIn (prospecting), phone calls.

**Existing distribution model:** Company has 30–50 distributors across India, with gaps in specific regions and market segments. Priya is responsible for identifying and onboarding new distributors to fill those gaps.

## 3. Goals

**Primary business objectives:**
- Expand distribution network into underpenetrated regions (e.g., East India, Northeast)
- Increase qualified lead volume by 50% year-over-year
- Reduce cost per lead acquisition

**Growth goals:**
- Onboard 20–30 new channel partners in the next 12 months
- Enter 2–3 new product categories with dedicated channel support
- Build a predictable, repeatable lead generation engine (not dependent on trade shows)

**Operational goals:**
- Reduce time spent on manual prospecting from 15–20 hours/week to <5 hours/week
- Improve lead quality (reduce time wasted on unqualified prospects)
- Get better visibility into which channels and geographies have the highest ROI

**Personal success metrics:**
- "I want to hit my quarterly targets without working 60-hour weeks"
- "I want my team to spend more time selling and less time researching"
- "I want to be known as the person who built our best-performing distribution channel"

## 4. Current Workflow

**Current process for generating distributor leads:**

| Step | Activity | Tools | Time | Owner | Pain Point |
|------|----------|-------|------|-------|------------|
| 1 | Define target geographies and segments | CRM data, market analysis | 2–3 hours/month | Priya | Data is stale |
| 2 | Search for potential distributors | IndiaMART, TradeIndia, Google, LinkedIn Sales Navigator | 5–8 hours/week | Priya + 2 SDRs | Repetitive, time-consuming |
| 3 | Research and vet candidates | Company websites, LinkedIn profiles, call to verify | 3–5 hours/week | Priya | No standardised vetting process |
| 4 | Build contact list | Excel, CRM | 2–3 hours/week | SDRs | Manual data entry |
| 5 | Draft outreach | Email templates, personalised notes | 2–3 hours/week | Priya | Personalisation at scale is hard |
| 6 | Send outreach | Email, LinkedIn InMail, WhatsApp | 1–2 hours/week | SDRs | Low response rates |
| 7 | Track responses and follow up | CRM, Excel | Ongoing | SDRs + Priya | Follow-ups get lost |
| 8 | Qualify and pass to sales | CRM | Ongoing | Priya | Manual handoff |

**Total time per week on prospecting:** 15–20 hours

**Current lead sources:**
- IndiaMART/TradeIndia (paid subscriptions)
- LinkedIn Sales Navigator (company subscription)
- Trade shows and exhibitions (2–3 per year)
- Industry associations and networks
- Referrals from existing distributors
- Website inquiries

## 5. Pain Points

| Severity | Category | Pain Point | Evidence |
|----------|----------|------------|----------|
| **Critical** | **Operational** | 15–20 hours/week spent on manual prospecting — "Scattered across dozens of disconnected tools" | Direct from website |
| **Critical** | **Commercial** | Lead quality from directories is poor — "Poor lead-to-order conversion" | Direct from report |
| **High** | **Technical** | No single source of truth for prospect data — "Scattered tools" | Direct from website |
| **High** | **Organizational** | Handoffs between SDRs and sales are manual and inefficient | Inferred from workflow |
| **High** | **Financial** | Multiple subscriptions (CRM, LinkedIn Sales Nav, IndiaMART) — "3-4 subscriptions" | Direct from website |
| **Medium** | **Emotional** | "I'm spending more time on research than actually selling" | Inferred from sales role |
| **Medium** | **Operational** | Follow-up cadences are manual — leads fall through the cracks | Inferred from workflow |
| **Medium** | **Financial** | ROI of existing tools is unclear — "Pay for tool not result" | Direct from website |

**Emotional frustrations (ranked):**
1. "I spend 20 hours a week on research that should take 5 hours with the right tools"
2. "I'm paying for 4 different subscriptions and still doing most of the work manually"
3. "My team is burned out from repetitive prospecting work"
4. "I can't prove the ROI of my lead generation spend to my VP"
5. "I know there are good distributors out there — I just can't find them efficiently"

## 6. Buying Behaviour

**How they evaluate new software:**
- Priya is more tech-savvy than Ravi — she uses CRM, LinkedIn Sales Nav, and is comfortable with digital tools
- She evaluates software based on: ease of integration, time savings, lead quality, and cost
- She reads reviews, asks peers, and does demo comparisons
- She needs to build a business case for her VP — ROI is critical

**Budget ownership:** Priya recommends purchases; VP Sales or CEO approves. Budget for sales tools is typically ₹50K–2L/year.

**Purchase triggers:**
- A specific target (e.g., "we need 30 new distributors in East India by Q3")
- Burnout from manual processes
- A competitor adopting a new tool and gaining an edge

**Objections (likely):**
- "How does this integrate with our CRM?"
- "Can I export the data and use it in my existing workflows?"
- "What's the data quality — how do I know these leads are real?"
- "How long does it take to set up?"
- "Is this just another tool I have to learn?"

**Trust signals that work for Priya:**
- CRM integration — "synced to your CRM"
- Citations for every fact — "Never a black box"
- Concrete metrics — "247 leads, 31 qualified meetings, 8 distributors signed"
- Pay-per-outcome pricing — aligns with her need to prove ROI
- Case studies or testimonials from similar companies

**Sales cycle:** 1–3 weeks. Priya will do her own research, request a demo, and build a business case.

**Decision criteria (ranked):**
1. **Lead quality and relevance** — does it actually find the right distributors?
2. **Time savings** — how many hours per week does it save?
3. **Integration** — does it work with our existing CRM?
4. **Cost and ROI** — is the cost justified by the results?
5. **Ease of use** — can my team use it without extensive training?

## 7. Relationship With AI

**Current AI usage:** Limited. Priya has used ChatGPT for drafting emails and basic research. She understands AI's capabilities and limitations. She may have tried AI-powered sales tools (e.g., Apollo.io, ZoomInfo) but found them expensive or low-quality for Indian market data.

**AI maturity:** Intermediate. Priya understands what AI can and cannot do. She's open to AI tools but demands transparency and accuracy.

**Trust level:** Medium. Priya trusts AI for research and initial outreach but wants to review results before they go out. She needs to see citations and confidence scores.

**Biggest concerns:**
- "How accurate is the data? I can't afford to waste time on bad leads."
- "Can I see the sources? I need to verify before I reach out."
- "Will this actually save my team time or just add another tool to learn?"

**Tasks they would delegate to AI:**
- **Yes:** Prospect research, lead discovery, data enrichment, initial outreach drafting, follow-up scheduling
- **Maybe:** Lead qualification (needs to review before sending to sales)
- **No:** Final relationship building, negotiation, strategic decisions

## 8. Relationship With Janooma

**Which AI worker(s) create immediate value:**
- **AI SDR — Find Distributors / Find Buyers** — Primary value
- AI SDR — Find Suppliers (if procurement is also in scope)
- AI Researcher — Market intelligence for new regions

**Primary jobs-to-be-done:**
1. "Find 60 architects designing premium residential"
2. "Find 40 builders constructing 200+ unit projects"
3. "Find 100 retail showrooms in West India"
4. "Generate 200 qualified leads for our industrial machinery"

**Expected first success ("aha") moment:**
- Within 24–48 hours, Priya receives a ranked list of 200+ qualified prospects with confidence scores, contact details, and source citations
- She cross-checks a few against her existing knowledge — they're accurate
- "This would have taken my team 2 weeks to compile manually"

**Reasons to continue using the platform:**
- Consistent, high-quality lead flow
- Time savings for her team (can redeploy SDRs to higher-value work)
- CRM integration means no manual data entry
- Worker memory improves over time
- Dashboard shows clear ROI per project

**Reasons they might churn:**
- Lead quality deteriorates over time
- Integration with existing CRM is buggy or incomplete
- Cost per lead is higher than alternatives
- Team doesn't adopt the tool (training gap)

**Expansion opportunities:**
- Scale to multiple projects simultaneously (different regions, different product lines)
- Upgrade to AI Researcher for competitive intelligence
- Add AI Marketing for campaign support
- Enterprise/B2B API access for integration into broader workflow

## 9. Representative User Journey

**Before Janooma:**
Priya manages a team of 5 sales representatives who spend 60% of their time on prospecting and research. They use IndiaMART (₹4K/month), LinkedIn Sales Navigator (₹8K/month), and a CRM (₹10K/month) — total ~₹22K/month in subscriptions. Despite this, lead quality is inconsistent, and Priya still spends 10–15 hours/week manually vetting leads. Her team is burned out from repetitive work.

**Discovery:**
Priya sees an ad or LinkedIn post about Janooma. The tagline "Pay for outcomes, not seats" catches her attention — she's tired of paying for tools that don't deliver results. She clicks through and reads the "How it works" page. The 6-step workflow makes sense to her.

**Evaluation:**
Priya does her research. She reads the use cases page and sees packaging industry examples that match her company. She checks the pricing page — pay-per-outcome means no upfront commitment. She applies for the Alpha program.

**Onboarding:**
The Janooma team contacts Priya within 24 hours. They discuss her specific needs: finding distributors in East India and packaging buyers in the pharmaceutical sector. She uploads her ICP template and existing lead lists. The team sets up her account.

**First successful project:**
Priya creates her first project: "Find 30 pharma buyers for blister packs." She attaches her product catalogue and ICP. Within 24 hours, she receives 30 verified leads with confidence scores. She approves 25, rejects 5 (wrong segment). Outreach goes out. Within a week, 8 buyers have responded, 3 RFQs are in progress.

**Long-term usage:**
Three months later, Priya has run 5 projects through Janooma. Her team's prospecting time has dropped from 20 hours/week to 5 hours/week. Lead quality is consistently higher than IndiaMART. The CRM integration means no manual data entry. Priya has hit her quarterly targets and is considering upgrading to AI Researcher for competitive intelligence.

## 10. Representative Quotes

1. "I spend 20 hours a week on research that should take 5 hours with the right tools."
2. "My team is burned out from prospecting. They want to sell, not search Google all day."
3. "IndiaMART gives us inquiries, but the quality is terrible. We waste so much time qualifying bad leads."
4. "I need to show my VP that our lead generation spend is actually working. Right now, I can't."
5. "If I could get 200 qualified leads delivered to my CRM every month, I'd be a hero to my team."
6. "I've tried AI tools before. Most of them are just wrappers around ChatGPT that don't understand Indian B2B."
7. "The fact that I can see citations for every lead is huge. I need to verify before I reach out."
8. "I don't want another dashboard. I want leads in my CRM and on WhatsApp."
9. "My team doesn't need more training. They need better leads."
10. "If Janooma can actually deliver what it promises, I'll be the first to recommend it to my peers."

## 11. Feature Importance

| Rank | Feature | Importance | Reasoning |
|------|---------|------------|-----------|
| 1 | AI SDR — Find Buyers / Distributors | **Critical** | Primary job-to-be-done |
| 2 | CRM integration | **Critical** | "synced to your CRM" — Priya needs seamless workflow |
| 3 | Ranked results with confidence scores | **High** | Priya needs to prioritise and justify lead selection |
| 4 | Citations for every fact | **High** | "Never a black box" — Priya needs to verify |
| 5 | Multi-channel outreach (email, WhatsApp, LinkedIn) | **High** | Priya uses all three channels |
| 6 | Outcome dashboard | **High** | Priya needs to prove ROI to her VP |
| 7 | Pay-per-outcome pricing | **High** | Aligns with her need to show cost-effectiveness |
| 8 | Worker memory | **Medium** | Improves efficiency over time |
| 9 | File attachment (ICP, catalogue) | **Medium** | Priya has these documents |
| 10 | AI Researcher | **Medium** | Valuable for market intelligence |
| 11 | AI Marketing | **Low** | Not Priya's primary responsibility |
| 12 | Bespoke worker co-build | **Low** | Priya needs a working solution now |

## 12. Product Design Implications

**UX implications:**
- **CRM integration is non-negotiable:** Priya will not use a tool that requires manual data entry into her CRM
- **Dashboard should show ROI metrics:** Priya needs to justify the spend to her VP
- **Export functionality:** Priya needs to share lead lists with her team
- **Mobile access:** Priya is often on the road — needs mobile access

**Onboarding implications:**
- **ICP template guidance:** Priya has an ICP but may need help structuring it for the platform
- **CRM integration setup:** Walk Priya through connecting her CRM
- **Team onboarding:** Priya needs to train her team on the tool — provide resources

**Messaging implications:**
- **ROI-focused:** "247 leads, 31 qualified meetings, 8 distributors signed"
- **Time savings:** "From weeks of manual work to hours of autonomous execution"
- **Transparency:** "Citations for every fact — never a black box"
- **Integration:** "Synced to your CRM"

**Pricing implications:**
- **Pay-per-outcome:** Priya needs to show cost-per-lead vs. alternatives
- **Transparent pricing:** Priya needs to build a business case — clear per-lead cost is essential
- **Volume discounts:** As usage scales, pricing should reflect volume

**Support implications:**
- **CRM integration support:** Priya will need help setting up and troubleshooting integrations
- **Team training:** Provide onboarding resources for team adoption
- **Quick response:** Priya is busy — support needs to be fast

**Potential enterprise requirements:**
- CRM integration (Salesforce, Zoho, HubSpot)
- Team management (multiple users, permissions)
- API access for custom workflows
- Data export and reporting

## 13. Evidence

| Characteristic | Evidence Type | Source | Confidence |
|----------------|---------------|--------|------------|
| Sales/Business Development Manager persona | **Direct** | "Persona 2: Priya — Sales/Business Development Manager" | High |
| Uses CRM (Zoho/Salesforce) | **Direct** | "CRM usage (among digitized MSMEs): 71.8%" | High |
| Uses LinkedIn Sales Navigator | **Direct** | "LinkedIn Sales Navigator — prospecting" | High |
| Spends 40-60% of time on prospecting | **Direct** | "spends 40–60% of her time on prospecting and research" | High |
| Pain: "scattered across disconnected tools" | **Direct** | "Business growth is scattered across dozens of disconnected tools" | High |
| Pain: poor lead quality from directories | **Direct** | "Poor lead-to-order conversion" | High |
| Has budget influence | **Inference** | From "recommender/implementer" role | Medium |
| Tech-savvy, open to AI tools | **Inference** | From CRM usage and LinkedIn Sales Navigator adoption | Medium |
| Needs to prove ROI to management | **Inference** | From mid-level manager role | Medium |
| Wants CRM integration | **Direct** | "synced to your CRM" | High |


# Persona 3: Vikram Mehta — The Startup Founder

## 1. Executive Summary

| Attribute | Detail |
|-----------|--------|
| **Name** | Vikram Mehta |
| **Company type** | Early-stage startup in manufacturing, B2B services, or consumer goods |
| **Industry** | D2C / FMCG / Sustainable Packaging / Industrial Products |
| **Company size** | 2–10 employees |
| **Annual revenue** | ₹0–2 Cr (pre-revenue or early revenue) |
| **Geography** | Based in Tier-1 or Tier-2 city, targeting national market |
| **Decision-making authority** | Founder / CEO — sole decision-maker |
| **Digital maturity** | High. Comfortable with digital tools, SaaS, social media. May have tried AI tools. |

**Confidence: High** — Directly supported by "Startups & New Ventures" persona.

## 2. Company Profile

**Business model:** Vikram is building a startup in manufacturing, B2B services, or consumer goods. His company is pre-revenue or early-revenue (₹0–2 Cr). He has limited marketing budget (₹0–₹50K/month) and no dedicated sales team. He is the founder, product manager, and primary salesperson.

**Team structure:**
- Vikram (Founder/CEO) — does everything: product development, sales, fundraising, strategy
- 1–3 co-founders or early employees — product/tech/operations
- No dedicated sales or marketing team

**Sales process:** Vikram is the entire sales team. He finds leads through personal network, LinkedIn, cold outreach, and founder communities. He does all prospecting, outreach, follow-up, and closing himself. This takes 30–50% of his time.

**Procurement process:** Vikram sources raw materials, packaging, and manufacturing services from suppliers. He finds suppliers through Google, IndiaMART, personal network, and founder communities.

**Current software stack:**
- Email (Gmail/Outlook)
- WhatsApp — primary communication
- LinkedIn — networking and prospecting
- Google Sheets/Excel — tracking leads and suppliers
- Notion or similar — documentation and planning
- Accounting software (Zoho Books or similar)

**Communication channels:** WhatsApp (primary), email (formal), LinkedIn (networking), phone calls.

**Existing distribution model:** None — Vikram is building his distribution network from scratch. He needs to find his first customers, distributors, and suppliers.

## 3. Goals

**Primary business objectives:**
- Acquire first 50–100 customers
- Secure first distribution partners
- Generate revenue to achieve product-market fit
- Attract investor interest

**Growth goals:**
- Build a repeatable customer acquisition channel
- Onboard 10–20 distributors or channel partners
- Scale from ₹0 to ₹2–5 Cr annual revenue within 18 months

**Operational goals:**
- Spend less time on manual lead generation (currently 15–20 hours/week)
- Focus more time on product development and fundraising
- Build a systematic sales process (not dependent on personal network)

**Personal success metrics:**
- "I want to prove there's real demand for my product"
- "I want to close my first 10 customers without spending my entire marketing budget"
- "I want to show investors a repeatable sales engine"

## 4. Current Workflow

**Current process for finding customers and distributors:**

| Step | Activity | Tools | Time | Owner | Pain Point |
|------|----------|-------|------|-------|------------|
| 1 | Define target customer profile | Intuition, market research | 2–3 hours | Vikram | No data to validate |
| 2 | Search for potential customers | Google, LinkedIn, IndiaMART, personal network | 5–10 hours/week | Vikram | Time-consuming |
| 3 | Research and qualify | Company websites, LinkedIn profiles | 3–5 hours/week | Vikram | No system |
| 4 | Reach out | LinkedIn InMail, email, WhatsApp | 2–4 hours/week | Vikram | Low response rates |
| 5 | Follow up | Manual tracking | Ongoing | Vikram | Hard to track |
| 6 | Close | Calls, meetings, negotiations | Ongoing | Vikram | Takes focus from product |

**Total time per week on sales:** 15–20 hours

**Current lead sources:**
- Personal network (founders, investors, mentors)
- LinkedIn (cold outreach)
- Founder communities (e.g., Startup India, incubators)
- Google searches
- IndiaMART/TradeIndia (free listings only — no budget for paid)

## 5. Pain Points

| Severity | Category | Pain Point | Evidence |
|----------|----------|------------|----------|
| **Critical** | **Commercial** | "Zero marketing budget" — cannot afford paid lead generation | Direct from website |
| **Critical** | **Operational** | Founder spends 40% of time on sales instead of product | Inferred from startup reality |
| **High** | **Emotional** | "No warm network, no budget for sales tools" | Direct from website |
| **High** | **Financial** | Cannot afford per-seat SaaS subscriptions | Inferred from budget constraints |
| **High** | **Technical** | No CRM, no sales infrastructure | Inferred from team size |
| **Medium** | **Commercial** | Need customer validation data for investors | Direct from website |
| **Medium** | **Operational** | No systematic way to track leads and follow-ups | Inferred from workflow |
| **Medium** | **Emotional** | High stress from doing everything alone | Inferred from founder role |

**Emotional frustrations (ranked):**
1. "I'm spending 20 hours a week on sales when I should be building my product"
2. "I have no network in this industry — every lead is cold"
3. "I can't afford IndiaMART subscriptions or fancy sales tools"
4. "Investors keep asking me for customer validation data and I don't have enough"
5. "I know there are customers out there — I just can't find them efficiently"

## 6. Buying Behaviour

**How they evaluate new software:**
- Vikram is digitally native — comfortable with SaaS, AI tools, and new technology
- He evaluates software based on: cost, ease of use, free trial availability, and potential ROI
- He reads reviews, tries free versions, and asks other founders
- He is price-sensitive but will pay if ROI is clear

**Budget ownership:** Vikram controls the budget personally. Very limited — ₹0–₹20K/month for tools.

**Purchase triggers:**
- A specific, urgent need (e.g., "I need to find 100 customers in the next 30 days")
- A free trial or alpha program that allows testing before committing
- Recommendation from a trusted founder peer

**Objections (likely):**
- "I can't afford another subscription right now"
- "How do I know this will actually work for my specific industry?"
- "I don't have time to learn a new tool"
- "Can I just try it for free first?"

**Trust signals that work for Vikram:**
- **"Free during Alpha"** — critical for Vikram
- **"No credit card"** — removes friction
- **"Pay for outcomes, not seats"** — aligns with his budget constraints
- **"Zero-cost listing"** — directly addresses his needs
- **Founder credibility** — "30+ years building products"
- **Community aspect** — "Founder community"

**Sales cycle:** 1–7 days. Vikram makes decisions quickly when he sees value.

**Decision criteria (ranked):**
1. **Cost** — can I afford this right now?
2. **Free trial** — can I test it before committing?
3. **Ease of use** — can I set this up in 10 minutes?
4. **Potential ROI** — will this actually help me find customers?
5. **Founder credibility** — do I trust the people behind it?

## 7. Relationship With AI

**Current AI usage:** High. Vikram uses ChatGPT regularly for research, content drafting, and brainstorming. He's familiar with AI tools and their capabilities. He may have tried AI sales tools (e.g., Apollo.io) but found them expensive or unsuitable for Indian market.

**AI maturity:** Advanced. Vikram understands AI's capabilities and limitations. He's comfortable experimenting with new AI tools.

**Trust level:** Medium-high. Vikram trusts AI for research and initial outreach but wants to review results. He understands that AI is a tool, not a replacement for judgment.

**Biggest concerns:**
- "Can this handle my specific industry or is it generic?"
- "How accurate is the data? I can't afford to waste time on bad leads."
- "Is this just ChatGPT with a wrapper?"

**Tasks they would delegate to AI:**
- **Yes:** Prospect research, lead discovery, initial outreach, data enrichment, follow-up scheduling
- **Maybe:** Lead qualification (needs to review)
- **No:** Final relationship building, strategic decisions

## 8. Relationship With Janooma

**Which AI worker(s) create immediate value:**
- **AI SDR — Find Buyers** — Primary value
- AI SDR — Find Suppliers (if sourcing)
- AI SDR — Find Distributors (if building channel)

**Primary jobs-to-be-done:**
1. "Generate 200 qualified leads for our [product/service]"
2. "Find 100 interior designers for modular kitchen"
3. "Find 40 FMCG brands sourcing flexible packaging"
4. "Find 80 e-commerce sellers for corrugated boxes"

**Expected first success ("aha") moment:**
- Vikram creates a project and receives a ranked list of 50–200 qualified leads within 24–48 hours
- He reaches out to 10 of them and gets 3 positive responses
- "This would have taken me 2 weeks — I got it in 2 days, and it didn't cost me anything"

**Reasons to continue using the platform:**
- Consistent lead flow without spending marketing budget
- Time savings — Vikram can focus on product and fundraising
- Free during alpha means no financial risk
- Customer validation data for investors

**Reasons they might churn:**
- Leads aren't relevant to his specific industry
- Too complicated to set up
- Starts generating revenue and upgrades to a more sophisticated tool
- Competitor offers something better/free

**Expansion opportunities:**
- As the startup grows, upgrade to paid plans
- Add AI Researcher for market intelligence
- Bespoke worker for specific startup needs
- Refer other founders (viral growth)

## 9. Representative User Journey

**Before Janooma:**
Vikram is a first-time founder building a sustainable packaging startup. He has no existing network in the packaging industry. He spends 20 hours/week on LinkedIn, Google, and cold outreach trying to find potential customers. He's made 200+ cold contacts with a 2% response rate. He's stressed and considering hiring a salesperson he can't afford.

**Discovery:**
Vikram sees Janooma mentioned in a founder WhatsApp group. Someone says: "Free AI tool that finds customers for you — worth checking out." Vikram clicks through. The "Free during Alpha" and "No credit card" messaging immediately catches his attention.

**Evaluation:**
Vikram reads the homepage, scrolls through use cases, and sees packaging industry examples. He applies for the Alpha program immediately — zero risk, potentially high reward.

**Onboarding:**
The Janooma team contacts Vikram within 24 hours. They discuss his specific needs: finding FMCG brands that need sustainable packaging. Vikram uploads his product catalogue and ICP. The team sets up his account.

**First successful project:**
Vikram creates his first project: "Find 40 FMCG brands sourcing flexible packaging." Within 24 hours, he receives a ranked list of 40 leads with confidence scores and contact details. He reaches out to 10 and gets 3 positive responses. One of them becomes his first paying customer.

**Long-term usage:**
Three months later, Vikram has acquired 12 customers through Janooma. He's using it regularly for lead generation. The time savings have allowed him to focus on product development. He's referenced Janooma in his investor pitch as a key customer acquisition channel. He's now considering the paid version as his startup generates revenue.

## 10. Representative Quotes

1. "I spend 20 hours a week on sales when I should be building my product."
2. "I have no network in this industry — every single lead is a cold lead."
3. "I can't afford IndiaMART subscriptions. My marketing budget is zero."
4. "Investors keep asking me for customer validation data. I need real leads, not promises."
5. "Free during Alpha? No credit card? I'm in."
6. "I've tried AI tools before. Most of them are expensive and don't work for India."
7. "If I can get 50 qualified leads without spending my entire budget, that's a game-changer."
8. "My first customer came from Janooma. That's all the validation I needed."
9. "I don't have time to learn a complicated tool. It needs to work out of the box."
10. "When I'm raising my seed round, I'm going to show investors my Janooma dashboard as proof of traction."

## 11. Feature Importance

| Rank | Feature | Importance | Reasoning |
|------|---------|------------|-----------|
| 1 | AI SDR — Find Buyers | **Critical** | Primary job-to-be-done |
| 2 | Free during Alpha / No credit card | **Critical** | Vikram has zero budget |
| 3 | Pay-per-outcome pricing | **High** | Only pays for results |
| 4 | WhatsApp-native lead delivery | **High** | Vikram uses WhatsApp for everything |
| 5 | Ranked results with confidence scores | **High** | Needs to prioritise limited time |
| 6 | Outcome dashboard | **High** | Customer validation for investors |
| 7 | File attachment (catalogue, ICP) | **Medium** | Vikram has these documents |
| 8 | Worker memory | **Medium** | Improves over time |
| 9 | Multi-channel outreach | **Medium** | Nice-to-have but not critical |
| 10 | AI Researcher | **Medium** | Valuable for market understanding |
| 11 | AI Marketing | **Low** | Not a priority |
| 12 | Bespoke worker co-build | **Low** | Vikram needs a working solution now |

## 12. Product Design Implications

**UX implications:**
- **Dead simple onboarding:** Vikram needs to set up in <10 minutes
- **Mobile-first:** Vikram works from anywhere — phone is primary device
- **No jargon:** "AI worker" is fine; "NSAI" is not
- **Immediate value:** First results should appear within 24 hours

**Onboarding implications:**
- **Zero-setup:** "Claiming takes two minutes"
- **No credit card required:** Critical for Vikram
- **Guided first project:** Template examples that match his industry
- **Human touch:** Founder access builds trust

**Messaging implications:**
- **Cost-focused:** "Free during Alpha" — primary hook
- **Outcome-focused:** "Pay for outcomes, not seats"
- **Founder credibility:** "30+ years building products"
- **Community:** "Founder community" — Vikram wants to connect with peers

**Pricing implications:**
- **Free during Alpha:** Non-negotiable for Vikram
- **Pay-per-outcome:** Vikram will only pay for results
- **Low entry price:** When paid, needs to be affordable for early-stage startups
- **No minimum commitment:** Vikram can't commit to annual contracts

**Support implications:**
- **Founder access:** Direct WhatsApp line is a major trust signal
- **Quick response:** Vikram expects fast, personal support
- **Community:** Peer support through founder community

**Potential enterprise requirements:**
- None — Vikram is not an enterprise customer

## 13. Evidence

| Characteristic | Evidence Type | Source | Confidence |
|----------------|---------------|--------|------------|
| Startup founder persona | **Direct** | "Startups & New Ventures" persona | High |
| Zero marketing budget | **Direct** | "Zero-cost listing; AI agent as first sales rep" | High |
| Needs customer validation for investors | **Direct** | "customer validation data; investor signal" | High |
| No network in industry | **Direct** | "No warm network, no budget for sales tools" | High |
| Digitally native | **Inference** | From startup founder profile and "comfortable with digital tools" | Medium |
| Uses AI tools (ChatGPT) | **Inference** | From "advanced AI maturity" and high digital comfort | Medium |
| Price-sensitive | **Direct** | "Zero-cost listing" and "pay-per-outcome" appeal | High |
| Needs free trial | **Direct** | "Free during Alpha" messaging | High |


# Persona 4: Sunil Rao — The Offline Retailer

*(Note: Sunil's stand-alone retail archetype is preserved here for cross-category retail, e.g. general hardware/consumer goods, distinct from Meena Joshi in 1D who is specifically the terminal node of Ravi Sharma's electrical supply chain. Where a retailer sits inside a modeled supply chain, use 1D; where retail is being considered independent of a specific chain, use Sunil.)*

## 1. Executive Summary

| Attribute | Detail |
|-----------|--------|
| **Name** | Sunil Rao |
| **Company type** | Offline retail store / Kirana / Showroom |
| **Industry** | Retail (electrical, hardware, building materials, consumer goods) |
| **Company size** | 2–10 employees (owner + 1–9 staff) |
| **Annual revenue** | ₹50 L–5 Cr |
| **Geography** | Tier-2 or Tier-3 city in India |
| **Decision-making authority** | Owner — sole decision-maker |
| **Digital maturity** | Very low. Uses WhatsApp for communication, maybe a billing software (Tally/Busy). No website. No social media presence. |

**Confidence: High** — Directly supported by "Offline Stores & Retail" persona.

## 2. Company Profile

**Business model:** Sunil owns a retail store in a Tier-2/3 city selling electrical products, hardware, building materials, or consumer goods. He sources products from distributors and manufacturers and sells to local customers (retail consumers, contractors, small businesses). He has been in business for 10–20+ years.

**Team structure:**
- Sunil (owner) — manages everything: purchasing, sales, customer relationships, finances
- 2–5 shop assistants — handle customers, stock management, deliveries
- 1 accountant (may be part-time) — manages billing and accounts

**Sales process:** Walk-in customers, phone orders from regular customers, WhatsApp orders. Sunil knows most of his customers personally. No structured marketing or lead generation.

**Procurement process:** Sunil sources products from distributors and manufacturers. He has 10–20 established suppliers. He places orders by phone/WhatsApp. He attends trade fairs occasionally to find new suppliers. No systematic supplier discovery process.

**Current software stack:**
- WhatsApp Business — primary communication
- Tally or Busy — billing and accounting
- Maybe a billing software (if digital)
- Paper registers for stock and credit tracking (if not digital)

**Communication channels:** WhatsApp (primary), phone calls, in-person.

**Existing distribution model:** Sunil is at the retail end of the distribution chain. He buys from distributors and sells to end customers. He has no digital presence — no website, no social media, no online listings (or outdated ones).

## 3. Goals

**Primary business objectives:**
- Increase sales and footfall
- Find new suppliers with better prices or products
- Compete with larger chains and online retailers
- Reduce dependency on a few suppliers

**Growth goals:**
- Expand product range
- Attract new customers (especially younger, digitally-savvy customers)
- Build a digital presence without technical complexity

**Operational goals:**
- Find better suppliers more efficiently
- Reduce time spent on procurement research
- Get more visibility for his store without needing a website

**Personal success metrics:**
- "I want more customers walking through my door"
- "I want to find suppliers who can give me better margins"
- "I don't want to be left behind as the market goes digital"

## 4. Current Workflow

**Current process for finding new suppliers:**

| Step | Activity | Tools | Time | Owner | Pain Point |
|------|----------|-------|------|-------|------------|
| 1 | Identify need for new supplier | Customer demand, product gaps | Ongoing | Sunil | Reactive, not proactive |
| 2 | Ask existing contacts | Phone calls to fellow retailers, distributors | 1–2 hours | Sunil | Limited network |
| 3 | Search online | Google, IndiaMART (if he knows how) | 2–3 hours | Sunil or son/daughter | Not comfortable with online search |
| 4 | Visit local market | Travel to nearest wholesale market | Half-day to full day | Sunil | Time-consuming |
| 5 | Evaluate supplier | Visit shop/factory, check quality, negotiate | Ongoing | Sunil | No systematic evaluation |
| 6 | Place trial order | Phone/WhatsApp | 30 mins | Sunil | No formal process |

**Current process for getting discovered by new customers:**
- Word of mouth (primary)
- Walk-in customers (location-dependent)
- Occasionally listed on Google Maps or Justdial (if someone set it up)
- No active marketing

## 5. Pain Points

| Severity | Category | Pain Point | Evidence |
|----------|----------|------------|----------|
| **Critical** | **Commercial** | No digital presence — "No website, no digital presence" | Direct from website |
| **Critical** | **Commercial** | Competing with larger chains — "Compete with larger chains" | Direct from website |
| **High** | **Technical** | "No technical skills" — can't set up a website or digital tools | Direct from website |
| **High** | **Operational** | Finding new suppliers is time-consuming and reactive | Inferred from workflow |
| **High** | **Emotional** | Fear of being left behind as the market digitises | Inferred from retail pressures |
| **Medium** | **Financial** | Limited budget for digital tools | Inferred from small business reality |
| **Medium** | **Operational** | No way to know what buyers are searching for in his area | Direct from website |

**Emotional frustrations (ranked):**
1. "I've been in business for 20 years and now I'm competing with websites I don't understand"
2. "My son keeps telling me to get online but I don't know where to start"
3. "I spend days traveling to find new suppliers when I should be running my shop"
4. "I'm losing customers to bigger stores and online retailers"
5. "I know there are better suppliers out there — I just can't find them"

## 6. Buying Behaviour

**How they evaluate new software:**
- Sunil is not tech-savvy. He is intimidated by software and digital tools.
- He relies on his children or younger staff for technology.
- He needs solutions that work through WhatsApp — the only app he uses regularly.
- He will not read documentation or watch tutorials.
- He needs someone to set it up for him.

**Budget ownership:** Sunil controls the budget personally. Very limited — ₹0–₹5K/month for tools.

**Purchase triggers:**
- A simple, WhatsApp-based solution that requires no setup
- Recommendation from a fellow retailer
- Seeing a competitor get ahead using digital tools
- His children setting it up for him

**Objections (likely):**
- "I don't understand this technology"
- "Who will set it up for me?"
- "I don't have time to learn a new system"
- "Is this going to cost me money I don't have?"

**Trust signals that work for Sunil:**
- **WhatsApp-native** — "Leads delivered to WhatsApp — the channel you already use"
- **"No technical skills required"** — implied by zero-setup positioning
- **"Claiming takes two minutes"**
- **Pre-indexed profile** — "Your business profile exists — AI-enriched from public records"
- **"Zero-cost listing"**

**Sales cycle:** 1–2 weeks. Needs someone to explain it simply and set it up.

**Decision criteria (ranked):**
1. **Simplicity** — can I use it through WhatsApp without learning anything new?
2. **Cost** — is it free or very cheap?
3. **Setup** — will someone set it up for me?
4. **Results** — will this actually bring me more customers?
5. **Trust** — do I trust the people behind it?

## 7. Relationship With AI

**Current AI usage:** None. Sunil doesn't know what AI is. He may have heard the term but doesn't understand it.

**AI maturity:** Novice. Needs everything explained in simple, concrete terms. The "AI worker" metaphor may or may not resonate — he just wants more customers.

**Trust level:** Very low. Sunil doesn't trust technology he doesn't understand. He needs to see results before believing.

**Biggest concerns:**
- "I don't understand this. Who's going to help me if something goes wrong?"
- "Is this going to replace me or my shop?"
- "Where does my data go? I don't want my competitors knowing my business."

**Tasks they would delegate to AI:**
- **Yes:** Finding new suppliers, getting discovered by new customers, receiving leads
- **Maybe:** Basic customer communication (if it's simple)
- **No:** Anything that requires judgment or personal relationships

## 8. Relationship With Janooma

**Which AI worker(s) create immediate value:**
- **AI SDR — Find Suppliers** — Primary value
- **AI SDR — Find Buyers** — Getting discovered by new customers

**Primary jobs-to-be-done:**
1. "Find suppliers for my store with better prices"
2. "Help customers in my area find my store"
3. "Show me what buyers in my area are searching for"

**Expected first success ("aha") moment:**
- Sunil receives a WhatsApp message saying "A customer in your area is looking for [product you sell] — here's their contact"
- He responds and gets a sale
- "This actually works — I didn't have to do anything"

**Reasons to continue using the platform:**
- Consistent flow of customer inquiries on WhatsApp
- Finding better suppliers without traveling
- Staying competitive without technical effort

**Reasons they might churn:**
- Too complicated to use
- No visible results within first 1–2 weeks
- Prefers his existing ways of doing business
- Gets a better offer from a competitor

**Expansion opportunities:**
- As Sunil becomes more comfortable, upgrade to additional features
- Refer other retailers in his network

## 9. Representative User Journey

**Before Janooma:**
Sunil has run his electrical shop in a Tier-2 city for 15 years. He knows his customers personally. His son has been telling him to "get online" for years, but Sunil doesn't understand websites and doesn't have time to learn. He's worried about losing customers to the new big-box store that opened in town. He spends 2–3 days every quarter traveling to the nearest wholesale market to find new suppliers.

**Discovery:**
Sunil's son hears about Janooma from a friend. He visits the website and sees "Leads delivered to WhatsApp — the channel you already use." He shows it to his father: "Dad, this finds customers for you on WhatsApp. You don't need a website."

**Evaluation:**
Sunil is skeptical but his son sets everything up. The "claiming takes two minutes" and "free" messaging convince Sunil to try it.

**Onboarding:**
Sunil's son claims the store profile (it's already pre-indexed from public data). He adds basic product categories. No setup required beyond that.

**First successful project:**
A week later, Sunil receives a WhatsApp message: "New buyer inquiry: local contractor looking for MCBs — ₹50,000 order." Sunil responds, gets the order, and makes a sale. He's shocked — "I didn't do anything and I got a customer?"

**Long-term usage:**
Six months later, Sunil has gotten 15+ customer inquiries through Janooma. He's also found 3 new suppliers with better prices. He still doesn't understand "AI" but he doesn't care — the WhatsApp messages keep coming and his business is growing.

## 10. Representative Quotes

1. "I don't understand websites. I use WhatsApp for everything."
2. "My son keeps telling me to get online. I don't have time to learn."
3. "I spend days traveling to find new suppliers. There has to be a better way."
4. "I've been in business for 20 years and now I'm competing with websites I don't understand."
5. "If I can get customer inquiries on WhatsApp without doing anything, that's all I need."
6. "I don't know what AI is. I just know I got a ₹50,000 order from a WhatsApp message."
7. "I don't want to learn a new system. Just send me leads on WhatsApp."
8. "The big store down the road is taking my customers. I need to fight back somehow."
9. "My son set it up for me. I didn't have to do anything."
10. "If it works and it's free, why wouldn't I use it?"

## 11. Feature Importance

| Rank | Feature | Importance | Reasoning |
|------|---------|------------|-----------|
| 1 | WhatsApp-native lead delivery | **Critical** | Sunil only uses WhatsApp |
| 2 | Pre-indexed profile — no setup | **Critical** | Sunil can't set up a profile himself |
| 3 | AI SDR — Find Suppliers / Buyers | **Critical** | Primary value |
| 4 | Free / Zero-cost | **High** | Sunil has limited budget |
| 5 | Buyer intent data | **High** | "See what buyers in your area are searching for" |
| 6 | Outcome dashboard | **Low** | Sunil doesn't need dashboards |
| 7 | Ranked results with confidence scores | **Low** | Sunil just wants leads, not analytics |
| 8 | File attachment | **Low** | Sunil doesn't have digital catalogues |
| 9 | Multi-channel outreach | **Low** | WhatsApp is all that matters |
| 10 | Worker memory | **Low** | Nice-to-have but not critical |
| 11 | AI Researcher | **Low** | Too complex |
| 12 | AI Marketing | **Low** | Not relevant |

## 12. Product Design Implications

**UX implications:**
- **WhatsApp-first:** The entire experience should be through WhatsApp. Sunil should never need to log into a dashboard.
- **Zero setup:** Sunil's profile should exist before he claims it
- **No learning curve:** Sunil should not need to learn anything new
- **Simple language:** No technical terms. "Customer inquiry" not "lead".

**Onboarding implications:**
- **Someone else sets it up:** Sunil's son or a Janooma team member should set everything up
- **Claiming takes 2 minutes:** Sunil just confirms his business details
- **Immediate value:** First lead should arrive within days, not weeks

**Messaging implications:**
- **Channel-first:** "Leads delivered to WhatsApp — the channel you already use"
- **No tech jargon:** "AI worker" is acceptable if explained simply
- **Zero risk:** "Free" and "no commitment" are critical
- **Concrete benefit:** "More customers without doing anything"

**Pricing implications:**
- **Free or very cheap:** Sunil won't pay more than ₹1K/month
- **Pay-per-outcome:** Sunil will only pay for results he can see
- **No subscriptions:** Sunil won't commit to recurring payments

**Support implications:**
- **Family-assisted support:** Sunil's children will be the primary support channel
- **WhatsApp support:** Sunil expects help via WhatsApp, not email
- **Simple troubleshooting:** Sunil won't read documentation

**Potential enterprise requirements:**
- None — Sunil is not an enterprise customer

## 13. Evidence

| Characteristic | Evidence Type | Source | Confidence |
|----------------|---------------|--------|------------|
| Offline retailer persona | **Direct** | "Offline Stores & Retail" persona | High |
| No website, no digital presence | **Direct** | "No website, no digital presence" | High |
| Uses WhatsApp for business | **Direct** | "WhatsApp as primary business tool" | High |
| No technical skills | **Direct** | "No technical skills" | High |
| Tier-2/3 city | **Direct** | "Tier-2/3 markets" | High |
| Competing with larger chains | **Direct** | "Compete with larger chains" | High |
| Needs to find suppliers | **Direct** | "Find suppliers for my store" | High |
| Limited budget | **Inference** | From small business reality and "zero-cost listing" appeal | High |
| Uses Tally/Busy for billing | **Direct** | "Tally / Busy (Accounting)" | High |
| Needs family assistance for tech | **Inference** | From "no technical skills" and generational gap | Medium |


# Persona 5: Ananya Reddy — The Influencer/Creator

## 1. Executive Summary

| Attribute | Detail |
|-----------|--------|
| **Name** | Ananya Reddy |
| **Company type** | Individual creator / Influencer |
| **Industry** | Lifestyle / Home & Living / Local Commerce |
| **Company size** | 1 (solo creator) |
| **Annual revenue** | ₹5–50 L (from content + brand deals) |
| **Geography** | Based in Tier-1 city, audience across India |
| **Decision-making authority** | Self — sole decision-maker |
| **Digital maturity** | High. Native to social media, digital tools, influencer platforms. |

**Confidence: Medium** — Supported by "Influencers & Creators" persona but this is a secondary segment with less evidence.

## 2. Company Profile

**Business model:** Ananya is a content creator (Instagram, YouTube, or both) with a engaged audience interested in lifestyle, home decor, local businesses, or sustainability. She currently monetizes through brand deals and sponsorships. She's looking for additional, more predictable revenue streams.

**Team structure:**
- Ananya (creator) — content creation, audience engagement, brand relationships
- Maybe a manager or assistant (if revenue is high enough)

**Sales process:** Brand deals come through inbound inquiries from brands or through influencer marketing agencies. Ananya negotiates deals on a project-by-project basis. No structured sales process.

**Procurement process:** Not applicable.

**Current software stack:**
- Instagram, YouTube — primary platforms
- WhatsApp — communication with brands and agencies
- Email — formal communication
- Analytics tools (Instagram Insights, YouTube Analytics)

**Communication channels:** Instagram DMs, WhatsApp, email.

**Existing distribution model:** Ananya distributes content through social media platforms. She doesn't have a product to distribute — she's a marketing channel.

## 3. Goals

**Primary business objectives:**
- Diversify income beyond brand deals
- Build a sustainable, recurring revenue stream
- Monetize her audience more effectively

**Growth goals:**
- Become the go-to influencer for local businesses in her niche
- Scale her income to ₹1 Cr+/year
- Build a community of engaged followers who trust her recommendations

**Operational goals:**
- Find brands and local businesses to partner with
- Streamline affiliate and commission tracking
- Build a structured monetization engine (not dependent on inbound deals)

**Personal success metrics:**
- "I want to earn passive income from my content"
- "I want to be known as the person who connects my audience with amazing local businesses"
- "I want to build something lasting, not just one-off brand deals"

## 4. Current Workflow

**Current process for monetizing audience:**

| Step | Activity | Tools | Time | Owner | Pain Point |
|------|----------|-------|------|-------|------------|
| 1 | Create content | Instagram, YouTube | 10–20 hours/week | Ananya | Time-consuming |
| 2 | Build audience | Organic growth, engagement | Ongoing | Ananya | Slow, uncertain |
| 3 | Get brand deals | Inbound inquiries, agencies | Passive | Ananya | Unpredictable |
| 4 | Negotiate and execute | WhatsApp, email | 2–5 hours/week | Ananya | Time-consuming |
| 5 | Get paid | Bank transfer | Passive | Ananya | Payment delays |

**Current monetization sources:**
- Brand deals (primary)
- Affiliate links (secondary, if applicable)
- Merchandise (if applicable)

## 5. Pain Points

| Severity | Category | Pain Point | Evidence |
|----------|----------|------------|----------|
| **High** | **Commercial** | Income is unpredictable — "one-off brand deals" | Inferred from creator economy |
| **High** | **Commercial** | No structured affiliate commerce platform | Direct from website |
| **High** | **Operational** | Finding brands to partner with is time-consuming | Inferred from workflow |
| **Medium** | **Financial** | Payment delays from brands | Inferred from creator economy |
| **Medium** | **Emotional** | "I want to monetize my audience without selling my soul" | Inferred from creator values |
| **Medium** | **Technical** | No easy way to track affiliate commissions | Inferred from workflow |

**Emotional frustrations (ranked):**
1. "My income is entirely dependent on brands reaching out to me"
2. "I want to earn passive income from my content, not just one-off deals"
3. "I'm constantly looking for brands to partner with instead of creating content"
4. "I want to recommend businesses I actually believe in, not just whoever pays me"

## 6. Buying Behaviour

**How they evaluate new software:**
- Ananya is digitally native — comfortable with new platforms and tools
- She evaluates based on: ease of use, reputation, earning potential, and community
- She discovers tools through creator communities and social media

**Budget ownership:** Self. Limited but willing to invest in tools that generate income.

**Purchase triggers:**
- A clear path to earning money
- Recommendation from a trusted creator peer
- Easy setup and onboarding

**Objections (likely):**
- "Will this actually make me money?"
- "Is this platform legitimate?"
- "How much work do I have to put in?"
- "What's the commission structure?"

**Trust signals that work for Ananya:**
- "Affiliate revenue on every category"
- "AI-powered recommendation engine"
- "Direct brand partner access"
- "City ambassador programme"
- "Audience monetisation dashboard"

**Sales cycle:** 1–7 days. Quick decisions when value is clear.

**Decision criteria (ranked):**
1. **Earning potential** — how much can I make?
2. **Ease of use** — can I set this up quickly?
3. **Reputation** — is this platform trusted?
4. **Community** — are other creators using it?
5. **Commission structure** — what's my cut?

## 7. Relationship With AI

**Current AI usage:** Medium. Ananya uses AI tools for content ideation, caption writing, and editing. She's familiar with ChatGPT, Canva AI, and similar tools.

**AI maturity:** Intermediate. Ananya understands AI's capabilities and limitations. She's open to AI tools that save her time or help her earn money.

**Trust level:** Medium. Ananya trusts AI for recommendations and automation but wants to review before publishing.

**Biggest concerns:**
- "Will this actually recommend businesses my audience will like?"
- "Is this just another platform taking a cut of my earnings?"
- "Will I lose my personal touch if I use AI?"

**Tasks they would delegate to AI:**
- **Yes:** Finding brands to partner with, matching recommendations to audience, commission tracking
- **Maybe:** Content creation (needs to review)
- **No:** Final editorial judgment, personal brand decisions

## 8. Relationship With Janooma

**Which AI worker(s) create immediate value:**
- **AI-powered recommendation engine** — matching businesses to audience
- **Affiliate revenue tracking** — commission dashboard
- **Direct brand partner access** — finding brands to work with

**Primary jobs-to-be-done:**
1. "Help me find local businesses to recommend to my audience"
2. "Track affiliate commissions automatically"
3. "Show me which products my audience is most likely to buy"

**Expected first success ("aha") moment:**
- Ananya recommends a business through Janooma, her audience buys, and she sees the commission appear in her dashboard
- "I just made money without negotiating a brand deal"

**Reasons to continue using the platform:**
- Consistent affiliate income
- Easy discovery of businesses to recommend
- Audience engagement data helps her create better content

**Reasons they might churn:**
- Low commissions
- Poor product recommendations (audience doesn't buy)
- Better alternative emerges
- Too much work to maintain

**Expansion opportunities:**
- City ambassador programme — exclusive status in her city
- Premium features for top creators
- Direct brand partnerships through the platform

## 9. Representative User Journey

**Before Janooma:**
Ananya has 50K Instagram followers. She gets 2–3 brand deal inquiries per month but only accepts 1–2. Her income is unpredictable. She spends hours researching brands to partner with. She wants to monetize her audience more consistently but doesn't know how.

**Discovery:**
Ananya sees Janooma mentioned in a creator WhatsApp group. Someone says: "Platform that helps you earn affiliate commissions from local businesses — and they handle all the tracking." Ananya clicks through.

**Evaluation:**
She reads the website, sees the influencer-specific value prop, and applies for the Alpha program. The "city ambassador" programme sounds interesting — exclusive status in her city.

**Onboarding:**
Ananya creates her profile, connects her social media accounts, and starts receiving business recommendations to share with her audience.

**First successful project:**
Ananya shares a recommendation for a local furniture store through Janooma. 5 of her followers make purchases. She earns ₹5,000 in commissions. "That was easier than any brand deal I've ever done."

**Long-term usage:**
Six months later, Ananya is earning ₹20K–₹50K/month in affiliate commissions through Janooma. She's a city ambassador. She recommends Janooma to other creators. Her income is more predictable and she spends less time chasing brand deals.

## 10. Representative Quotes

1. "I'm tired of relying on brand deals for my income. I want something more predictable."
2. "I want to recommend businesses I actually believe in, not just whoever pays me."
3. "If I can earn commissions without negotiating deals, that's a game-changer."
4. "My audience trusts my recommendations. I need a platform that helps me monetize that trust."
5. "I don't want to be a salesperson. I want to be a curator."
6. "City ambassador? Exclusive status in my city? That's exactly the kind of recognition I want."
7. "I spend too much time finding brands to work with. I'd rather spend that time creating content."
8. "If Janooma can help me earn passive income from my content, I'm in."
9. "My audience is always asking me where to buy things. Now I can answer and earn at the same time."
10. "I want to build something sustainable, not just chase the next brand deal."

## 11. Feature Importance

| Rank | Feature | Importance | Reasoning |
|------|---------|------------|-----------|
| 1 | Affiliate revenue / commission tracking | **Critical** | Primary value driver |
| 2 | AI-powered recommendation engine | **High** | Matches businesses to audience |
| 3 | Direct brand partner access | **High** | Finds brands to work with |
| 4 | Audience monetisation dashboard | **High** | Tracks earnings |
| 5 | City ambassador programme | **Medium** | Exclusive status and perks |
| 6 | WhatsApp integration | **Medium** | Ananya uses WhatsApp for communication |
| 7 | Analytics and insights | **Medium** | Helps understand audience |
| 8 | Content creation tools | **Low** | Ananya already creates content |
| 9 | Worker memory | **Low** | Nice-to-have |
| 10 | AI SDR — Find Buyers | **Low** | Not relevant to influencer persona |

## 12. Product Design Implications

**UX implications:**
- **Clean, visual interface:** Ananya expects beautiful design
- **Mobile-first:** Ananya creates content on her phone
- **Dashboard-first:** Ananya wants to see earnings at a glance
- **Social media integration:** Connect Instagram/YouTube easily

**Onboarding implications:**
- **Quick setup:** Ananya should be able to start earning within hours
- **Social media connect:** One-click connection to Instagram/YouTube
- **Clear earning potential:** Show examples of what creators earn

**Messaging implications:**
- **Earnings-focused:** "Earn commissions from every recommendation"
- **Creator-first:** "Built for creators, by people who understand creators"
- **Community:** "Join the city ambassador programme"
- **Authenticity:** "Recommend businesses you actually believe in"

**Pricing implications:**
- **Commission-based:** Ananya pays a percentage of earnings, not upfront fees
- **Free to join:** No barrier to entry
- **Tiered commissions:** Higher commissions for top creators

**Support implications:**
- **Community support:** Creator community for peer support
- **Quick response:** Creators expect fast support
- **WhatsApp support:** Ananya prefers WhatsApp for communication

**Potential enterprise requirements:**
- None — Ananya is an individual creator

## 13. Evidence

| Characteristic | Evidence Type | Source | Confidence |
|----------------|---------------|--------|------------|
| Influencer/creator persona | **Direct** | "Influencers & Creators" persona | High |
| Affiliate revenue | **Direct** | "Affiliate revenue on every category" | High |
| AI-powered recommendation engine | **Direct** | "AI-powered recommendation engine" | High |
| Direct brand partner access | **Direct** | "Direct brand partner access" | High |
| City ambassador programme | **Direct** | "City ambassador programme" | High |
| Audience monetisation dashboard | **Direct** | "Audience monetisation dashboard" | High |
| Digitally native | **Inference** | From creator profile | High |
| Seeks passive income | **Inference** | From "diversify beyond brand deals" | Medium |
| Values authenticity | **Inference** | From creator values and "recommend businesses I believe in" | Medium |
| Community-driven | **Inference** | From "city ambassador" and creator community focus | Medium |


# Summary: Persona Prioritisation

| Rank | Persona | Priority | Reasoning |
|------|---------|----------|-----------|
| 1 | **Ravi Sharma Continuum (1A–1D)** — Manufacturer → Distributor → Wholesaler → Retailer | **Highest** | Directly matches primary target across the whole chain; highest aggregate willingness to pay at 1A/1B, largest addressable footprint at 1C/1D; each stage reinforces demand for the others (network effects up and down the chain) |
| 2 | **Priya Patel** — Sales/Business Development Manager | **High** | Decision-influencer, higher volume potential, CRM integration = stickiness |
| 3 | **Vikram Mehta** — Startup Founder | **High** | Low acquisition cost, viral potential, future enterprise value |
| 4 | **Sunil Rao** — Offline Retailer (cross-category, non-chain-specific) | **Medium** | Large addressable market, but lowest willingness/ability to pay |
| 5 | **Ananya Reddy** — Influencer/Creator | **Medium** | Secondary segment, important for marketplace liquidity but not core |

**Note on Persona 1's re-ranking rationale:** Because 1A–1D share one WhatsApp-native, zero-setup, pay-per-outcome product experience, acquiring one stage of the chain (e.g., a manufacturer) creates a natural on-ramp to acquire the stages immediately above and below it (their existing distributors/sub-dealers/retailers), which no other persona in this set offers. This compounding acquisition dynamic is the reason the continuum is ranked above Priya and Vikram despite individual stages (1C, 1D) having low ability to pay on their own.


# Product Design Implications by Persona

| Dimension | 1A Ravi (Mfr) | 1B Deepak (Dist.) | 1C Farooq (Whlsr) | 1D Meena (Retail) | Priya (Manager) | Vikram (Startup) | Sunil (Cross-cat. Retail) | Ananya (Creator) |
|-----------|----------------|---------------------|----------------------|-----------------------|-----------------|------------------|-------------------------------|------------------|
| **Primary channel** | WhatsApp | WhatsApp | WhatsApp | WhatsApp | CRM + WhatsApp | WhatsApp | WhatsApp | Dashboard + Social |
| **Key outcome** | 50 distributors | 40 sub-dealers | 1 backup distributor + 15 retailers | Customer inquiries + 1 backup supplier | 200 qualified leads | First customers | Customer inquiries | Commission earnings |
| **Offline presence** | Very strong | Very strong (regional) | Strong (local) | Very strong (hyperlocal) | N/A (works inside a company) | Building from scratch | Very strong | N/A (digital-first) |
| **Online presence** | Medium-low | Low | Very low | Zero | Medium (company-level) | High | Very low | High |
| **Overseas presence** | Low-medium | None | None | None | Low (company may export) | None | None | None |
| **Interest in overseas** | Medium | Low | Near-zero | None | Low-medium | Low | None | None |
| **Pricing sensitivity** | Medium | Medium-high | High | Very high | Low-medium | High | Very high | Medium |
| **Tech comfort** | Low | Low | Low | Very low | Medium | High | Very low | High |
| **Setup complexity** | Low | Low | Needs help | None (family-assisted) | Medium | Low | None (family-assisted) | Low |
| **Support need** | High (WhatsApp) | High (WhatsApp) | High (family/peer) | High (family) | Medium | Low | High (family) | Low |
| **Integration need** | None | None | None | None | CRM | None | None | Social media |
| **Churn risk** | Medium (if no results) | Medium (if no results) | High (if complex) | High (if complex) | Low (if integrated) | High (if no results) | High (if complex) | Medium |
