# Google Ads Campaign Operations | Campaign Management & Optimization

### Digital Marketing & Paid Search Portfolio — Praveen Kumar Annepu

---

## 📌 About This Project

I put this repository together to walk through how I actually run a Google Ads account, end to end — from defining the business objective to launch, daily monitoring, optimization, and reporting back to stakeholders.

Over 7+ years working across CM360, DV360, Google Ads, and SA360, I've built a fairly consistent process for how I plan, set up, QA, and optimize search campaigns — this documents that process in detail: how I structure accounts, research and manage keywords, set up conversion tracking, run QA before launch, troubleshoot performance issues, and report results to stakeholders.

> **Note:** Since I can't share real client or employer campaign data, everything here uses synthetic figures and fictional business scenarios. The process, frameworks, and checklists are the same ones I use in real campaigns — the numbers and examples just aren't tied to any actual client, employer, or proprietary work.

---

## 🎯 Campaign Management Lifecycle

```text
Business Objective
       ↓
Campaign Planning
       ↓
Account & Campaign Structure
       ↓
Keyword Research
       ↓
Audience Strategy
       ↓
Budget & Bidding Strategy
       ↓
Ad Creation
       ↓
Conversion Tracking
       ↓
Campaign QA
       ↓
Launch
       ↓
Daily Monitoring
       ↓
Performance Optimization
       ↓
Search Term Analysis
       ↓
Bid & Budget Optimization
       ↓
Conversion Analysis
       ↓
Reporting
       ↓
Business Recommendations
       ↓
Continuous Optimization
```

---

## 1. Business & Campaign Planning

Before I build a campaign, I get clear on the business objective first — everything downstream (structure, keywords, bidding, KPIs) flows from that.

### Business objectives I've planned around

- Lead generation
- Online sales / e-commerce revenue
- Website traffic
- Brand awareness
- App promotion
- Local store visits
- Phone calls
- Product consideration
- Customer acquisition
- Remarketing

### How I map objective to primary KPI

| Business Objective    | Primary KPI              |
|------------------------|---------------------------|
| Lead Generation        | CPA                       |
| E-commerce             | ROAS                      |
| Revenue Growth         | Conversion Value          |
| Traffic                | Qualified Clicks          |
| Awareness               | Impressions / Reach       |
| Brand Search            | Impression Share          |
| Customer Acquisition   | New Customer CPA / ROAS   |

### Supporting KPIs I track alongside the primary one

Impressions · Clicks · CTR · CPC · Cost · Conversion Rate · Conversions · CPA · Conversion Value · ROAS · Search Impression Share · Search Lost IS (Budget) · Search Lost IS (Rank) · Top / Absolute Top metrics · Average CPC · Engagement metrics

---

## 2. Campaign Structure

I build campaign structure around:

- Business objectives
- Products or services
- User intent
- Geography
- Budget requirements
- Audience strategy
- Performance and reporting requirements

```text
Google Ads Account
│
├── Search
│   ├── Brand
│   ├── Generic Services
│   ├── High Intent Services
│   └── Competitor / Alternative
│
├── Performance Max
│   ├── Product / Service Group A
│   └── Product / Service Group B
│
├── Display
│   ├── Remarketing
│   └── Prospecting
│
└── YouTube / Video
    ├── Awareness
    ├── Consideration
    └── Remarketing
```

---

## 3. Campaign Setup

### What I configure at the campaign level

Campaign name · type · marketing objective · networks · locations · languages · budget · bidding strategy · start/end dates · ad schedule · location options · conversion goals · URL options · campaign-level settings

### The naming convention I use

```text
US_Search_NonBrand_LeadGen_HighIntent
```

My format: **Geo + Channel + Campaign Type + Business Category + Objective**

I stick to this consistently because it makes reporting, troubleshooting, bulk edits, stakeholder updates, and account governance much easier down the line — especially once an account grows past a handful of campaigns.

---

## 4. Keyword Research

### What I look at before adding a keyword

Search intent · search volume · competition · commercial intent · relevance · cost · expected conversion potential · geographic relevance · user journey stage

### How I categorize keyword intent

| Intent Type | Example |
|---|---|
| Informational | `what is digital marketing` |
| Commercial investigation | `best digital marketing agency` |
| High intent | `digital marketing agency near me` |
| Transactional | `hire digital marketing agency` |

---

## 5. Keyword Match Types

I choose between broad, phrase, and exact match based on conversion data, search term quality, how mature the account is, the Smart Bidding strategy running, volume needs, and the underlying business objective — not a one-size-fits-all rule.

---

## 6. Negative Keyword Management

I use negative keywords to cut irrelevant traffic before it drains budget. Things I typically filter out:

- Irrelevant or low-intent searches
- Free/job/career/tutorial searches
- Unrelated products
- Incorrect locations
- Competitor terms, where appropriate

```text
free · jobs · career · course · training · salary · definition
```

Depending on the situation, I manage these at the campaign, ad group, or account (shared list) level.

---

## 7. Responsive Search Ads (RSA)

When I build out RSAs, I work through headlines, descriptions, landing page relevance, keyword relevance, CTAs, value propositions, and brand messaging together — not in isolation.

```text
Headline 1 → Primary Service
Headline 2 → Key Benefit
Headline 3 → Call to Action

Description 1 → Business value
Description 2 → Supporting benefit + CTA
```

**What I check when optimizing ads:** asset performance, CTR, conversion rate, conversion volume, search terms, ad relevance, landing page experience, messaging consistency. I try not to swap out an asset just because one metric looks low — I look at the overall campaign context first.

---

## 8. Landing Page QA

I've seen well-built campaigns underperform purely because of a weak landing page, so this is a step I don't skip. What I check:

URL functionality · page load speed · mobile experience · message consistency · CTA visibility · form functionality · contact information · tracking implementation · thank-you page · redirects · broken links · page relevance

---

## 9. Location Targeting

I manage country, state, city, and radius targeting, along with exclusions and location-specific campaigns where needed. I track performance by location (cost, conversions, CPA, conversion rate, conversion value) and, when a location underperforms, decide between reducing budget, adjusting bids, excluding it outright, or breaking it into its own campaign.

---

## 10. Ad Scheduling

I look at performance by day of week and hour of day against conversion patterns, CPA, ROAS, and conversion rate — a typical pattern I've seen:

```text
Monday–Friday → Strong conversion volume
Saturday      → Moderate performance
Sunday        → High CPA
```

I make sure I'm working with enough data before acting on a pattern like this — a couple of bad days isn't a trend.

---

## 11. Audience Management

**Audience sources I've worked with:** website visitors, customer lists, app users, similar/behavioral segments, remarketing audiences, in-market audiences, custom segments, demographic signals.

**What I analyze:** audience performance, conversion rate, CPA, ROAS, engagement, new vs. returning users.

---

## 12. Budget Management

**What I keep an eye on daily:** daily budget, monthly spend, actual spend, pacing, campaign priority, conversion volume, CPA, ROAS, lost impression share due to budget.

**The pacing calculation I use:**

```text
Expected Spend = Planned Budget × Elapsed Campaign Percentage

Example:
Monthly Budget = $30,000
Elapsed Month  = 50%
Expected Spend = $15,000
```

I compare expected vs. actual spend regularly and dig into anything that's off by a meaningful margin.

---

## 13. Bid Strategy Management

Bidding approaches I've worked with: Manual CPC · Maximize Clicks · Maximize Conversions · Target CPA · Maximize Conversion Value · Target ROAS, plus other automated strategies depending on the campaign type.

I choose based on the campaign objective, conversion volume, historical performance, budget, business goals, and how much data is actually available to work with.

---

## 14. Smart Bidding Optimization

When I'm running automated bidding, I track conversion volume, CPA, ROAS, conversion value, budget utilization, bid strategy status, learning/adjustment periods, and performance trends — and I hold off on frequent major changes until I've got enough data to act on.

```text
Observe → Analyze → Identify Issue → Make Controlled Change → Monitor → Evaluate
```

---

## 15. Search Terms Analysis

This is one of the recurring tasks I spend the most time on in Search Ads. I review search term relevance, conversion performance, cost, CTR, CPC, conversion rate, CPA, and conversion value.

```text
Relevant + Converting        → Consider keyword expansion
Relevant + High Cost         → Evaluate bids / landing page / intent
Irrelevant                   → Consider negative keyword
High Conversion Value        → Investigate scaling opportunity
```

---

## 16. Quality Score Analysis

I treat Expected CTR, Ad Relevance, and Landing Page Experience as diagnostic signals — not the actual business KPI I'm optimizing for.

- **To improve expected CTR**, I work on stronger messaging, tighter relevance, and testing value propositions
- **To improve ad relevance**, I align keywords and ad copy and clean up account/ad-group structure
- **To improve landing page experience**, I look at relevance, usability, page speed, mobile experience, and how clear the conversion path is

---

## 17. Search Impression Share Analysis

**What I track:** Search Impression Share, Search Lost IS (Budget), Search Lost IS (Rank), Top and Absolute Top Impression Share.

```text
High Lost IS (Budget) → Evaluate budget opportunity
High Lost IS (Rank)   → Evaluate ad rank factors
Low Impression Share  → Investigate eligibility, budget, bids, quality, targeting, competition
```

---

## 18. Ad Rank Analysis

When I'm diagnosing a visibility issue, I look at bid, ad quality, landing page experience, ad relevance, expected CTR, search context, competition, auction dynamics, and relevant assets together. I don't rely on Quality Score alone to explain an Ad Rank problem — it's rarely the full picture.

---

## 19. Conversion Tracking

**Conversion actions I've set up and tracked:** lead form submission, purchase, phone call, sign-up, demo request, consultation request, download, add to cart, qualified lead.

```text
User Action → Website Event → Tag/Tracking Implementation → Conversion Recorded → Google Ads → Reporting & Optimization
```

---

## 20. Conversion Tracking QA

Before I trust a conversion number, I validate the conversion action configuration, category, counting method, value, attribution setting, primary/secondary status, tag firing, event triggering, duplicate conversions, timestamps, landing/thank-you pages, and any imported conversions — using browser dev tools and tag-debugging tools as needed.

---

## 21. Google Tag Manager Integration

On accounts running GTM, my QA covers tags, triggers, variables, the data layer, Google Ads conversion tags, Conversion Linker, and custom/click/form events. My usual debug flow:

```text
Open Website → Open GTM Preview/Debug → Perform Conversion Action
     → Check Event → Check Trigger → Check Tag → Validate Parameters → Validate Conversion
```

---

## 22. UTM & URL Tracking

I check landing page URLs, UTM parameters, tracking templates, final URL suffixes, redirects, and broken parameters before I consider a campaign launch-ready.

```text
utm_source=google
utm_medium=cpc
utm_campaign=campaign_name
utm_term=keyword
utm_content=ad_variant
```

---

## 23. Campaign QA Checklist

Here's the checklist I actually run through before any campaign goes live:

**Campaign:** name · type · objective · budget · bidding strategy · location · language · schedule · networks · conversion goals

**Keywords:** keywords added · match types reviewed · negative keywords reviewed · relevance validated

**Ads:** headlines · descriptions · URLs · CTAs · spelling · policy · messaging consistency

**Tracking:** final URLs · UTM parameters · conversion tags/actions · tracking templates · GTM implementation · analytics tracking

**Landing Page:** loads correctly · form works · CTA works · mobile experience · tracking works

```text
Campaign Settings ✓  Keywords ✓  Ads ✓  Budget ✓  Targeting ✓  Tracking ✓  Landing Page ✓  QA ✓  Launch ✓
```

---

## 24. Daily Campaign Monitoring

Every day, I'm looking at: Spend · budget utilization · impressions · clicks · CTR · CPC · conversions · conversion rate · CPA · conversion value · ROAS · search impression share · campaign status · disapproved ads · tracking issues · significant performance changes

---

## 25. Weekly Optimization

Here's what my weekly optimization pass usually covers:

- **Search terms:** find new opportunities, add negatives, flag irrelevant traffic
- **Keywords:** review performance by match type, flag high/low performers
- **Ads:** review asset performance, test messaging
- **Budget:** flag campaigns needing more budget or underutilizing it, review pacing
- **Bidding:** review CPA/ROAS/conversion volume, assess bid strategy performance
- **Targeting:** geography, device, audience, schedule, demographics

---

## 26. Monthly Performance Review

Every monthly review I put together answers the same four questions: **What happened? Why did it happen? What worked? What didn't? What should happen next?**

---

## 27. Performance Reporting

**How I open an executive summary:**

> Campaign generated X conversions at a CPA of $X, with total spend of $X and conversion value of $X.

**A performance table I'd typically build (synthetic figures):**

| Campaign    |   Spend | Impressions | Clicks |   CTR |   CPC | Conversions |    CPA | Conv. Rate | ROAS |
| ----------- | ------: | -----------: | -----: | ----: | ----: | -----------: | -----: | ---------: | ---: |
| Brand       |  $5,000 |      100,000 | 12,000 | 12.0% | $0.42 |          600 |  $8.33 |       5.0% |  4.2 |
| Generic     | $15,000 |      250,000 | 15,000 |  6.0% | $1.00 |          500 | $30.00 |       3.3% |  2.8 |
| High Intent | $10,000 |      120,000 |  9,000 |  7.5% | $1.11 |          450 | $22.22 |       5.0% |  3.5 |

---

## 28. Performance Trend Analysis

I compare current vs. previous period, month-over-month, year-over-year, campaign-vs-campaign, and device/location/keyword-vs-keyword to spot what's actually changing.

| Metric | Previous | Current | Change |
|---|---:|---:|---:|
| Spend | $25,000 | $30,000 | +20% |
| Clicks | 20,000 | 25,000 | +25% |
| Conversions | 700 | 900 | +29% |
| CPA | $35.71 | $33.33 | −7% |
| Conversion Rate | 3.50% | 3.60% | +0.10 pp |

---

## 29. Root Cause Analysis

This is the sequence I walk through whenever performance moves unexpectedly:

```text
Performance Change
   → Is tracking working?
   → Is spend pacing correctly?
   → Did traffic change?
   → Did CPC change?
   → Did CTR change?
   → Did conversion rate change?
   → Did search terms change?
   → Did targeting change?
   → Did landing page change?
   → Did competition change?
   → Determine Root Cause
```

---

## 30. Common Troubleshooting Scenarios

Scenarios I've run into and how I usually approach them:

| Symptom | What I check |
|---|---|
| Low impressions | Budget, bids, targeting, keyword volume/status, ad status, search volume, impression share, eligibility |
| High clicks, low conversions | Search terms, keyword intent, landing page, conversion tracking, device, geography, ad messaging, form experience |
| High CPA | CPC, conversion rate, search terms, keyword efficiency, landing page, audience, geography, device, budget allocation |
| High spend, low conversion value | Conversion tracking, search intent, product/service mix, keyword quality, landing page, bidding strategy, conversion value config |
| Sudden conversion drop | Tracking → website → conversion tag → conversion action → landing page → campaign changes → traffic → search terms |

---

## 31. Optimization Framework

This is the loop I follow for any optimization decision, big or small:

```text
Measure → Identify Performance Gap → Diagnose Root Cause → Prioritize Opportunity
   → Implement Controlled Change → Monitor Impact → Compare Results
   → Document Learning → Scale Successful Changes
```

---

## 32. Experimentation & Testing

**Areas I've tested:** ad messaging, landing pages, keyword strategy, match types, bidding strategies, budget allocation, audience strategy, geographic targeting, campaign structure.

For every test I run, I write down a **hypothesis**, the **test itself**, the **KPI(s)** it affects, and a **documented result** (what changed, what happened, why, and what I'd do next).

---

## 33. Budget Reallocation Framework

This is how I think through moving budget between campaigns:

```text
Business Priority + Conversion Volume + CPA + ROAS + Impression Share + Scaling Opportunity

Campaign A: Strong ROAS + Limited Budget      → Potential scaling opportunity
Campaign B: High Spend + Poor CPA             → Optimization required
Campaign C: Low Spend + Strong Conv. Rate     → Evaluate additional budget
```

---

## 34. Campaign Governance

I keep naming conventions, change logs, QA checklists, tracking documentation, campaign documentation, budget records, optimization logs, reporting templates, approval processes, and stakeholder communication records up to date — governance is what keeps an account manageable once it scales past a couple of people.

---

## 35. Change Log (Example)

A sample of how I document changes as I make them:

| Date       | Campaign        | Change                    | Reason                     | Expected Impact          |
| ---------- | ---------------- | -------------------------- | --------------------------- | -------------------------- |
| 2026-01-05 | Generic Search   | Added negative keywords    | Reduce irrelevant traffic   | Improve CTR                |
| 2026-01-08 | High Intent      | Budget increased           | Strong CPA                  | Increase conversions       |
| 2026-01-12 | Brand            | Ad messaging updated       | Improve engagement          | Improve CTR                |
| 2026-01-15 | Generic Search   | Landing page reviewed      | Low CVR                     | Improve conversion rate    |

---

## 36. Stakeholder Communication

I've learned that campaign management isn't only about platform changes — a big part of the job is communicating performance, issues, risks, opportunities, recommendations, budget needs, tracking issues, launch status, and optimization results clearly to people who aren't in the platform every day.

**An update I'd typically send:**

> Performance is currently below the target CPA.
>
> **Primary driver:** Conversion rate decreased by 18%.
>
> **Initial investigation:** Traffic volume remains stable, CPC increased slightly, search term quality is consistent, but landing page conversion rate declined.
>
> **Recommendation:** Validate the landing page and conversion flow before making major bidding or budget changes.

---

## 37. Campaign Launch Checklist

This is the checklist I go through before hitting launch on any campaign:

```text
[ ] Business objective confirmed        [ ] Ads created
[ ] KPI defined                         [ ] Landing pages validated
[ ] Campaign structure approved         [ ] Conversion tracking configured
[ ] Naming convention applied           [ ] UTM / URL tracking validated
[ ] Budget configured                   [ ] QA completed
[ ] Bidding strategy selected           [ ] Stakeholder approval received
[ ] Locations configured                [ ] Campaign launched
[ ] Schedule configured                 [ ] Post-launch monitoring completed
[ ] Keywords added
[ ] Negative keywords reviewed
```

---

## 38. Post-Launch Checklist

And what I check right after a campaign goes live:

```text
[ ] Campaign is eligible               [ ] Spend is pacing correctly
[ ] Ads are serving                    [ ] Search terms are relevant
[ ] Impressions are generating         [ ] No major policy issues
[ ] Clicks are generating              [ ] Performance monitoring enabled
[ ] URLs work correctly
[ ] Tracking is firing
[ ] Conversions are recording
```

---

## 39. Tools & Platforms I've Worked With

| Category | Tools |
|---|---|
| **Advertising** | Google Ads, Search Ads 360, Campaign Manager 360, Display & Video 360, Google Ad Manager, Meta Ads, X Ads |
| **Analytics** | Google Analytics 4, Google Analytics 360, Adobe Analytics, Looker Studio |
| **Tag Management** | Google Tag Manager, Tealium iQ, Adobe Launch |
| **Campaign Operations** | Jira, Salesforce, Celtra, Genesys, Verve |
| **Measurement & Verification** | Floodlight, IAS, DoubleVerify |

---

## 40. Key Google Ads Metrics I Report On

| Metric | Purpose |
|---|---|
| Impressions | Measures ad visibility |
| Clicks | Measures traffic generated |
| CTR | Measures click engagement |
| CPC | Measures average click cost |
| Cost | Measures spend |
| Conversions | Measures desired actions |
| Conversion Rate | Measures conversion efficiency |
| CPA | Measures cost per conversion |
| Conversion Value | Measures business value |
| ROAS | Measures return on advertising spend |
| Search Impression Share | Measures eligible search visibility |
| Search Lost IS (Budget) | Visibility lost due to budget |
| Search Lost IS (Rank) | Visibility lost due to Ad Rank |

---

## 41. Example Optimization Scenario

Here's a walkthrough of how I'd approach a real underperformance scenario (using synthetic numbers):

**Situation:** A campaign is generating Spend $20,000 / Clicks 18,000 / Conversions 400 / CPA $50 against a target CPA of $35.

**What I'd investigate:** Search terms, keyword performance, CPC, conversion rate, landing page, device performance, geography, ad performance, conversion tracking, bidding strategy.

**What I'd typically find:** 20% of spend going to low-intent search terms; mobile conversion rate significantly lower; high-intent keywords converting well; higher landing page abandonment on mobile.

**Actions I'd take:** Add relevant negative keywords, review the mobile landing page, re-evaluate budget allocation, prioritize high-intent traffic, and double-check conversion tracking before making bigger changes.

**What I'm optimizing for:** Reduce wasted spend, improve conversion rate and CPA, protect conversion volume.

---

## 42. Reporting Dashboard Framework

When I build a dashboard, it usually has four parts:

- **Executive KPI cards:** Spend, Conversions, CPA, Conversion Value, ROAS, CTR, CPC
- **Performance trends:** Spend, Conversions, CPA, ROAS, CTR over time
- **Campaign performance table:** Campaign, Spend, Clicks, CTR, CPC, Conversions, CPA, Conversion Value, ROAS
- **Optimization insights:** Top/underperforming campaigns, search term opportunities, budget opportunities, tracking issues, testing recommendations

---

## 43. What I Handle as a Campaign Manager

| Area | What I Do |
|---|---|
| **Planning** | Understand business objectives, define KPIs, build strategy, allocate budgets |
| **Setup** | Campaign creation, keyword implementation, ad creation, targeting, conversion setup, URL tracking |
| **QA** | Campaign settings, ads, keywords, URLs, tracking, conversion actions, landing pages |
| **Monitoring** | Spend, pacing, traffic, conversions, CPA, ROAS, search terms, campaign health |
| **Optimization** | Keywords, negatives, ads, bids, budgets, targeting, landing pages, conversion strategy |
| **Reporting** | Daily/weekly/monthly reporting, KPI and trend analysis, root cause analysis, recommendations |
| **Stakeholder Management** | Campaign updates, performance discussions, issue escalation, recommendations, launch coordination, documentation |

---

## 44. Skills I've Built Through This Work

Google Ads · Search Advertising · Campaign Management · Ad Operations · Campaign Setup · Campaign QA · Keyword Management · Negative Keywords · RSA Management · Search Term Analysis · Bid Management · Budget Management · Pacing · Conversion Tracking · GTM · UTM Tracking · Performance Optimization · Quality Score Analysis · Ad Rank Analysis · Search Impression Share · CPA Optimization · ROAS Optimization · Performance Reporting · Root Cause Analysis · A/B Testing · Stakeholder Management · Campaign Governance

---

## 45. Why I Put This Together

I wanted this to show more than just "I know how to create an ad." Running a Google Ads account well means owning the whole process:

```text
Business Requirement → Campaign Strategy → Platform Setup → Tracking → QA
   → Launch → Monitoring → Optimization → Reporting → Business Recommendation
```

That's the loop I actually work in day to day, and this repo walks through each stage of it.

---

## 👨‍💼 About Me

**Praveen Kumar Annepu**

I'm a Digital Marketing & Ad Operations Specialist with 7+ years across Digital Advertising, Search Advertising, Programmatic Advertising, Campaign Operations, Analytics, Tag Management, Performance Optimization, Client & Stakeholder Management, Customer Success, and Team Leadership.

**Platforms I work in day to day:** Google Ads · SA360 · DV360 · CM360 · GA4 · GTM · Adobe Analytics · Tealium

- **Portfolio:** [praveenkumarannepu.github.io/Consultant](https://praveenkumarannepu.github.io/Consultant/)
- **LinkedIn:** [linkedin.com/in/praveen-kumar-annepu](https://www.linkedin.com/in/praveen-kumar-annepu)
- **Email:** [kumarpraveen719@gmail.com](mailto:kumarpraveen719@gmail.com)

---

## ⚠️ A Note on the Data in This Repo

I can't share real client or employer campaign data here, so everything you see — campaign names, business scenarios, performance numbers, budgets, and metrics — is **synthetic**, created to walk through the process realistically. No confidential client, employer, proprietary campaign, or personal information is included anywhere in this repo.

---

## ⭐ What This Repo Walks Through

**Campaign Setup → Campaign QA → Search Operations → Keyword Management → Ad Management → Conversion Tracking → Budget & Bid Management → Optimization → Reporting → Troubleshooting → Stakeholder Management**
