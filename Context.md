# JANOOMA — Company & Product Context

This document captures who JANOOMA is, what it does, and what it believes — independent of any specific design, UI, or landing page. It synthesizes the founder's own notes, the pitch deck, and a review of the live site, stripped down to company facts, philosophy, and positioning.

---

## 1. What JANOOMA Is, In One Line

**JANOOMA is an AI-powered "Business Growth Operating System" for Indian SMBs and manufacturers — you describe a business goal in plain English (e.g. "Find 50 distributors for my LED switchgear in South India"), and autonomous AI workers discover, verify, and reach out to the buyers/suppliers/distributors/wholesalers who match, delivering ranked results and running the outreach end-to-end.**

Company: Janooma Labs Private Limited (Bangalore, India) + Janooma Labs LLC (New Jersey, US subsidiary)
Founder: Madan Mohan K N — 3x serial entrepreneur, 25+ years building products, prior: Co-founder/Head of Eng at Xindus (cross-border trade rails, raised $13M+, $3M MRR), Global Head of Engineering at WaSoKo (Africa B2B marketplace, grew MRR to $25M+), Head of Engineering & India Head at AirAsia, Director of Engineering at Myntra, Senior Principal Architect at Sabre, Lead Engineer at AOL, Engineer at Honeywell.
Stage: Pre-revenue Alpha (Alpha 0.1), raising a seed round, running a 100-Design-Partner program.

---

## 2. The Problem It Solves

Businesses — especially Indian SMB manufacturers — struggle to grow because of three compounding failures:

1. **Discovery is hard.** Finding the right buyers, distributors, suppliers, wholesalers/retailers takes weeks of manual work across Google, LinkedIn, trade directories, trade portals, WhatsApp groups, trade fairs, and personal networks.
2. **Data and tools are scattered.** A typical growth workflow hops across a dozen disconnected tools: Google → LinkedIn → Directories → Trade Portals → WhatsApp → Excel → Email → CRM → Quotation → Negotiation → Follow-up → Deal. Nothing is unified.
3. **No visibility.** There's no clear measurement of what's working — conversions, spend, drop-offs, ROI per growth initiative are invisible.

The founder's own framing (from internal notes): *"Businesses don't just struggle to find customers. They also struggle to find reliable suppliers, qualified distributors, manufacturing partners, export opportunities, and market intelligence. Every growth initiative starts with discovering the right business opportunity. No single platform solves this end-to-end."*

Existing alternatives all fall short:
- **Directories** (IndiaMART, TradeIndia, Justdial) — passive listings, no agent, wait for buyers to browse.
- **Vertical/Horizontal SaaS** (Salesforce, HubSpot, Zoho, ServiceTitan) — built for forms and reports, AI bolted on, not outcome-owning.
- **Horizontal AI** (ChatGPT, Copilot, Gemini, Perplexity) — smart but generic, no industry grounding, no relationships, no outcomes.
- **Google** — shows ads/results, doesn't orchestrate a transaction.

---

## 3. The Solution / How It Works

**Core mechanic:** You describe an outcome in natural language. AI Workers plan, discover, enrich, verify, and execute — end to end. "Talk to your worker like you would a teammate."

### The 6-step workflow
1. **Define** — Create a project, pick an AI worker, state the goal in plain language, attach context (product catalogue, ICP, past leads, CRM exports).
2. **Execute** — An AI Planner composes a custom workflow for the goal. Atomic sub-agents run in parallel: Search → Crawl → Enrich → Verify → Rank. Live progress is shown with citations for every fact (never a black box).
3. **Review** — Results appear as ranked cards with confidence scores (e.g. 92/100) and source citations. One-click approve / edit / reject. Full audit trail.
4. **Enrich & Re-execute** — Add more constraints or files (e.g. "only distributors with turnover > ₹2 Cr"), attach exclusion lists, re-run. The worker only re-plans what changed — fast and cheap.
5. **Action** — Approved results trigger multi-channel outreach: personalized email, WhatsApp, LinkedIn. RFQs are generated, meetings get booked, follow-up cadences auto-run for non-responders, replies route back to inbox/CRM.
6. **Measure & Learn** — An outcome dashboard tracks leads generated, qualified meetings, RFQs, deals signed, per-project ROI/conversion/cycle-time. The worker's memory (ICP, preferences, blocklists) persists and compounds across projects.

### The "Magic Recipe" (unique advantage / architecture)
Every project is unique — the AI Planner composes a tailored workflow using two proprietary data assets:
- **Industry Twin** — a neuro-symbolic graph modeling an entire industry: companies + products + process, suppliers + distributors + buyers relationship graph, standards/pricing/regulations, and AI workers with worker memory. ~$25-50k to build per industry, targeting $1M+ ARR per twin at maturity, 10 → 100 twins planned.
- **Business Opportunity Graph** — buyer↔supplier matching, demand/supply signals, distributor/partner network reach, cross-industry intelligence from patterns across millions of deals. Compounds with every transaction (two-sided network effects).

Pipeline stages inside a project: Search → Crawl → Enrich → Verify → Rank → Draft → Verify → Report → Outcome.

### Underlying tech claim: NSAI (Neuro-Symbolic AI)
JANOOMA's claimed technical moat is combining a small neural model (~1B params) for language understanding with a symbolic knowledge graph for permanent, structured, encrypted memory. Claimed advantages over plain LLMs: unlimited context (graph grows without bound), full data privacy (on-prem, customer-held encryption keys), explainability (full graph trace, not a black box), near-zero marginal cost (CPU graph traversal, not per-token), instant updates (no retraining), near-zero hallucination risk. This is architecturally ambitious — treat as the company's technical story/differentiator, not necessarily a fully shipped capability.

### AI Workers ("AI Business Team")
Businesses don't buy software — they gain AI teammates:
- **AI SDR Worker** — live now. Objectives: Find Buyers, Find Suppliers, Find Distributors, Find Wholesalers/Retailers.
- **AI Researcher Worker** — on request. Market intelligence, competitor research.
- **AI Marketing Worker** — on request. Campaign planning, content generation.
- **Future/planned employees:** Operations, Finance, Marketing, Customer Success, Compliance, Procurement, Sales.

---

## 4. Who It's For (Target Customers)

**Beachhead market: India.** Global manufacturing/B2B expansion planned later (Middle East & SEA next, then global).

**Target customer types:**
- Manufacturers
- Exporters
- Industrial brands
- OEM suppliers
- Distributors
- Wholesalers

**Priority industries (India beachhead):**
Electrical & Lighting, Industrial Machinery, Furniture, Modular Kitchen, Packaging, Plastics, Chemicals, Building Materials, Medical Devices.

**Broader personas the company addresses (secondary, from the live site's "Why" page):**
1. **Registered businesses / manufacturers** (primary) — want passive listings turned into active revenue, structured qualified leads via WhatsApp, zero-effort lead capture.
2. **Service professionals** (doctors, consultants, contractors) — want intent-matched enquiries, pay-per-qualified-lead.
3. **Offline stores & retail** (Tier-2/3 India) — want to go from zero digital presence to an AI-built catalogue and hyperlocal buyer matching in minutes.
4. **Startups & new ventures** — want a zero-cost first "sales rep" and market validation signal.
5. **Influencers & creators** — affiliate/commission layer on the seller marketplace side (seller.janooma.com — a related but distinct product).

**Revenue band of target companies:** roughly ₹1 Cr to ₹100 Cr+ annual revenue — i.e., real operating SMBs/mid-market, not micro-businesses and not large enterprises with existing Salesforce/SAP setups.

**Illustrative persona:** *Ravi, 40-55, owns a mid-size manufacturing business (electrical/packaging/machinery), ₹5-100 Cr revenue, currently finds distributors via WhatsApp groups and trade fairs, not a SaaS/CRM person, lives on WhatsApp for business.*

**Who it's explicitly NOT for:** large enterprises with existing procurement/CRM stacks, pure D2C/e-commerce consumer brands, and (initially) non-Indian markets.

---

## 5. Real-World Traction / Proof (use carefully — early stage, be honest)

- Alpha platform live; design-partner experiments run with real companies: Travel & Tours (CSR), Office Interiors (Dhanishta) — currently interacting/paid pilots (WebStore + WebChat via friend referrals). Some dropped pilots too (WakeFit, a diamond jewellery dealer, John Deere/tractors) — for internal learning, not something to put on a public landing page.
- 100 Design Partner slots being opened; alpha is free, "you choose the price."
- Backed by / part of: ConquestBits 2026, ZeroPearl VC Mentorship, Cloudflare Startup Program, Aiven Startup Program, Azure Startup Program, AWS Activate, Zoho Startup Program, Algolia Startup Program, customer.io Startup Program, Utho Startup Program, Yandex Cloud Startup Program, DPIIT #startupindia recognition.
- Raising a seed round: 35% engineering, 30% infrastructure (LLM compute/cloud/data pipelines), 20% business & GTM, 15% operations.

---

## 6. Business Model

Philosophy: **"Pay for outcomes. Not seats."**

- **Subscriptions:** Starter/Growth/Enterprise — $99 / $499 / $2,500 per month.
- **AI Credits:** pay-as-you-go, ~$60-120 per customer/month average.
- **Enterprise Deals:** $90k-120k ACV, custom workers + private deployment.
- **Expansion streams:** Marketplace (4-5% of GMV), APIs & SDK, Industry Reports ($5k-50k each), Services (onboarding).
- Targets: Y1 ARR $3-7M, Y2 ARR $30-40M, LTV/CAC >5x, Y2 gross margin 80%+.
- During Alpha specifically: free, "you choose the price," dedicated build pod, direct founder access.

---

## 7. Positioning & Messaging

**Category claim:** JANOOMA says it isn't competing in existing categories — it's creating a new one: **"Business Opportunity Intelligence."** Sales platforms focus on customers, procurement platforms focus on suppliers, CRMs manage existing relationships — JANOOMA discovers, connects, and executes opportunities across the entire ecosystem.

**Core positioning line:** *"Foundation models are the engine. JANOOMA is the car — with steering, brakes, and a road map."*

**Messaging hierarchy:**
1. **Identity:** "The Business Growth Platform" / "The Business Growth Operating System"
2. **Value proposition:** Discover Opportunities, Execute Projects, Grow Faster — using AI Workers and Industry Twins
3. **Mechanism:** "Tell your AI worker what you want. It does the rest."
4. **Proof:** concrete example queries (see below)
5. **Differentiation:** "Pay for outcomes, not seats" / "No credit card · Free during Alpha"

**Example queries (the company's actual go-to examples of what the product can do):**
- "Find 50 distributors for my LED switchgear in South India."
- "Source 10 verified suppliers for biodegradable packaging."
- "Generate 200 qualified leads for our industrial machinery."
- "I manufacture electrical switchgear and want distributors in Karnataka."

**Company mission statement:** "Build The World's AI Business Team." — help every business Discover opportunities, Build trusted business relationships, Expand into new markets, Execute business growth faster. "AI teammates that amplify people — not replace them."

**Company vision statement:** "Empower 100+ Million Businesses Worldwide To Grow Beyond Borders." No business should be limited by geography, networks, knowledge, resources, or access to opportunities. "Opportunity should belong to everyone."

**Founder belief / narrative arc for "why now":** Software digitized businesses. AI will operate businesses. Three shifts have converged: (1) AI can now understand businesses, products, and markets, (2) business data is increasingly digital and accessible, (3) companies are embracing AI for mission-critical workflows.

**Emotional/aspirational closing line used in the deck:** *"Imagine a future where every business has an AI team working alongside its people. Where discovering the next customer, supplier, distributor, or market takes minutes — not months. Where opportunity is no longer limited by geography, networks, or resources."*

---

## 8. Honesty / Guardrails

- The company is **pre-revenue, Alpha stage**. Do not fabricate customer counts, revenue figures, or testimonials beyond what's in this document. The pitch-deck "5K+ Active Sellers / $50M+ Sales" figures belong to a **separate, related product** (the seller.janooma.com marketplace) — do not present those as JANOOMA's own numbers unless confirmed they should be merged.
- NSAI/Industry Twins are the company's forward-looking technical story — present them as differentiators/vision, not as fully proven, battle-tested infrastructure.
- Two related-but-distinct surfaces exist in the wild: the main AI Business Team platform (janooma.com) and a seller marketplace (seller.janooma.com, branded "JanooMa"). Unless told otherwise, treat these as the **main AI Business Team platform's** context — keep the marketplace/influencer-affiliate material out of scope unless asked.
- Some internal experiment notes (dropped pilots, reasons for churn) are for internal learning only — never surface them publicly.
