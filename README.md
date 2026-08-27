# Bareed Reshi

**Search, marketing technology, and performance marketing.** Phoenix, Arizona.

I run search, martech, and performance marketing for an ownership group spanning three brands and 27 locations across Arizona and Texas, a furniture retailer, a family entertainment brand and a nonprofit education organization, on a $150K per month marketing budget. Separately I take on local service businesses through my own consultancy.

Most of what I get pulled into is the same problem wearing different clothes. It is nearly always a marketing stack producing numbers nobody trusts. The fix is almost always upstream in the data rather than in the campaigns.

I have a Computer Science degree, which in marketing mostly means I don't wait in a developer queue. I write the schema, configure the tags, build the automation, and ship the pages myself.

---

## What I run day to day

**Three brands, 27 locations, two states.** Mega Furniture (20 retail locations, 10 Arizona and 10 Texas), Rush Fun Park (7 family entertainment locations across San Antonio, Universal City, Phoenix, Peoria and Chandler), and Good Tree Institute, the group's nonprofit. One marketing function covering all of it.

**The budget.** Paid search, paid social, TikTok, YouTube, streaming, email, print, and out-of-home. Allocation between brands, pacing, forecasting, and marginal return by channel.

**Agency governance.** I also sit on the client side of an agency relationship, auditing contracted deliverables against what actually shipped and holding outside vendors to measurable outcomes rather than activity reports. It is a useful vantage point: you learn quickly where agency search delivery breaks down.

**The bench.** 10+ contract and agency specialists across content, copywriting, graphic design, video, and web development. Priorities, briefs, and quality review against brand standards that differ by brand.

---

## Things I've built

### Multi-brand schema and entity program
Organization, LocalBusiness, FAQ, and Course markup deployed across three genuinely different entity types, retail locations, entertainment venues, and an education nonprofit. Entity consistency held across Google Business Profile, on-site markup, and content, so each brand resolves as itself in local results and AI-generated answers rather than as a blur of the parent group.

### Google Business Profile visibility recovery
Maps visibility across the retail footprint collapsed year over year. The assumption in the room was content or links. It was neither. Location profile completeness sitting well below threshold, compounded by local algorithm changes that had quietly raised the bar for what counts as complete. Led remediation across every Arizona location plus a structured review and reputation program to hold the gains.

*In multi-location local search, the boring data-hygiene problem beats the interesting strategy problem most of the time.*

### Conversion tracking rebuild
Inherited a conversion foundation full of duplicate and junk actions that automated bidding was optimizing against. Audited and cleared it, then assigned defensible business values to offline outcomes such as store visits, direction requests and phone calls, so Smart Bidding optimized toward real results instead of surface conversions. Also traced and blocked overseas click-farm traffic that was contaminating the bidding signal.

Side effect worth naming: it made organic performance measurable in the same frame as paid, which is what finally let search work get argued for on equal footing at budget time.

### AI-augmented marketing operations
Roughly ten automated workflows on the Claude API and n8n covering recurring performance reporting, data aggregation, and campaign QA across the portfolio. Replaced a full day of manual weekly reporting and redirected that capacity into strategy and testing. Built without engineering support.

### [24locksmithpro.com](https://www.24locksmithpro.com/), consultancy client
A mobile automotive locksmith with a strong Google Business Profile and no website at all. Built a mobile-first single page from scratch: full LocalBusiness schema, geo meta and coordinates, service-area coverage across the Phoenix metro, and copy written for emergency intent.

Someone locked out of their car at 9pm doesn't read an About page. Every decision came from that one behavioural fact: single page, phone number fixed in view, services above the fold, no forms.

### Agency contract review and renegotiation
An SEO agency engagement arrived already in motion, a large one-time "local presence rollout" plus a monthly hours block, access granted, invoice issued. The rollout was a citation build priced several times above what the standard tooling costs for the same output. The monthly block was sold as capacity rather than deliverables, with contract language stating outright that no requested item was guaranteed. Scope overlapped the paid media accounts I had just rebuilt in house. Terms ran one direction: full payment upfront and non-refundable, low liability caps, out-of-state venue, unilateral rate increases.

Recommended killing the rollout, carving paid media out of scope, restructuring the monthly block around defined deliverables, and fixing the legal terms before renewal. Framed upward as financial stewardship rather than territorial defence.

The tell: their flagship deliverable targeted directory listings. Our actual problem was Google Business Profile completeness. Right invoice, wrong lever, which you only catch if you already know where the visibility is leaking.

### Vendor access governance
Two vendors on the same domain at once: an SEO agency running off-site local work, and a development partner mid-build on a platform migration. Least privilege by default, analytics, Search Console, Ads, Meta, TikTok and Shopify at editor rather than admin, admin downgraded after onboarding, developer seats held until scope settled. Registrar and DNS control never handed over; when bot mitigation was needed the answer was a scoped CDN member seat or an in-house implementation, not the keys to the domain.

A vendor holding DNS during an active migration is a single point of failure for the whole business. Coordination costs a few emails. A rollback costs the quarter.

### Technical SEO, Good Tree Institute
Organization, FAQ, and Course JSON-LD deployed through Squarespace code injection, site-wide meta rewrites, and de-indexing of low-value pages with sitemap resubmission to consolidate crawl budget onto enrollment pages. Also diagnosed a broken jQuery mega-menu caused by a case-sensitivity mismatch, which was silently blocking navigation and internal link equity.

Delivered alongside the board-level marketing briefing presented to organizational leadership, inside a formal brand approval workflow requiring executive sign-off on every published change.

### Promotional landing pages and Shopify theme work
Single-file HTML campaign pages with horizontal snap carousels, swipe support, live product data, and full markup, then deployed into a Shopify Online Store 2.0 theme. Which meant the real work: Custom Liquid hitting character limits and choking on CSS braces, a page template shadowed by an auto-generated JSON file, and the resolution being the two-file section-plus-JSON-template approach rather than a page builder.

### Ecommerce platform migration
End-to-end platform build with an external development partner: URL architecture, catalog and pricing data structure, tracking continuity, vendor access control, and domain and DNS cutover, with organic equity protected through the migration rather than rebuilt after it.

### Video commercial production
Concept, script, and creative direction through campaign build, audience targeting, and optimization on YouTube. The creative and the media buying in the same pair of hands.

### [triptology.in](https://triptology.in), personal project
A Kashmir travel content site I built and run end to end: site build, keyword targeting, on-page and entity structure, schema deployment, Search Console monitoring.

It doubles as a sandbox. Technical and structured-data changes get tested here, on a site I own, before they go near anything at work.

---

## Things I've taken apart to learn from

**Apple's homepage architecture.** Pulled the source and worked through it properly: inline SVG nav text rendering, the analytics instrumentation attribute pattern, scroll-driven video with keyframe syntax, responsive picture elements across four breakpoints with 2x retina variants, the JSON-driven client-side nav config, and their JSON-LD implementation. Then rebuilt the patterns from scratch to make sure I actually understood them.

**Multi-agent marketing systems.** A staged agent workflow where Claude and Gemini review each other's output. Adversarial quality control rather than a single model agreeing with itself. Covers strategy, creative production, and channel planning across different business models.

---

## Graduate research

**REI, when membership growth stops paying for itself.** Built a three-dataset view of the co-op: four years of high-level financials, store-level inventory and sales, and a customer service and returns log. Membership grew from roughly 21 million to 25 million between 2021 and 2024, close to 20% growth. Over the same window the co-op went from a $97.7M profit to three consecutive loss years, with net sales falling from $3.85B to $3.53B. Correlation between member growth and net income came out around −0.59.

Acquisition was working and unit economics were not. It is the counterweight to a career spent optimizing for more customers, and the reason I value conversions rather than counting them.

**Client Campaign Analytics System, database design.** A full relational design for a marketing department running campaigns on behalf of clients: conceptual model, logical schema, physical design with SQL. Clients, campaigns, channels (Google Ads, Meta, LinkedIn, email), audience segments defined by demographic and behavioral criteria, performance records carrying impressions, clicks, conversions and spend by reporting period, and team members. Two many-to-many relationships resolved with junction tables so targeting definitions stay consistent instead of being duplicated per campaign.

This is the data model underneath every reporting layer I have built since. Knowing why the schema looks the way it does is the difference between reading a dashboard and being able to fix one.

**Balanced Scorecard for a retail operation.** Financial, customer, internal process and learning perspectives, each measure defined with its purpose and the direction it should trend. The vocabulary for arguing marketing in front of a finance audience.

**Additional case analysis.** Comparative retail case work across large-format and specialty retail including Target and Walmart, positioning, omnichannel economics, operating model. Plus technology strategy and market-entry analysis, cost and operations cases, augmented reality in manufacturing, and business ethics.

---

## Stack

`GA4` `Google Tag Manager` `Looker Studio` `Search Console` `Google Business Profile` `Google Merchant Center` `SEMrush`

`Google Ads` `Performance Max` `Meta Ads` `TikTok Ads` `YouTube`

`JSON-LD` `Schema.org` `HTML` `CSS` `JavaScript` `Liquid`

`n8n` `Zapier` `Claude API` `Google Ads API`

`Shopify` `WordPress` `Squarespace`

---

## Background

Nine years across the US, Qatar, and India.

Before Phoenix I ran paid acquisition and live campaign operations for a delivery platform during the FIFA World Cup in Qatar, geo-fenced programs across eight stadium zones in eight languages, under conditions where a campaign decision had a window of minutes rather than days. Before that, built the analytics, tracking, and reporting foundation across a multi-brand portfolio in Doha, and ran B2B business development in India.

B.S. Computer Science · Executive MBA in Information Technology (STEM-designated)

English, Arabic, Urdu, Hindi, Kashmiri

---

Phoenix, AZ · [Portfolio](https://bareedreshi.github.io) · [LinkedIn](https://www.linkedin.com/in/bareedmushtaq) · reshi.bareed@gmail.com
