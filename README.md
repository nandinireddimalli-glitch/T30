# 📣 Influencer Marketing Plan — MilletBite `#SnackSmartHyd`

> **Digital Marketing Track · Task: Create an Influencer Marketing Plan**
> Author: **Reddi Malli Nandini**

A complete influencer campaign plan for **MilletBite**, a sample Hyderabad-based healthy millet snack brand. The plan covers how influencers are selected, which creators are shortlisted, what the campaign wants to achieve, what content creators must make, and which KPIs prove whether it worked.

**Core principle:** _audience relevance and engagement come before follower count._

---

## 🎯 Objective
Understand influencer marketing planning by building a realistic, end-to-end campaign: from creator discovery and scoring to the brief, content rules, budget and measurement.

## 🧰 Tools used
| Tool | Used for |
|------|----------|
| **Instagram** | Main campaign platform — Reels, Stories, Collab posts; creator discovery & audience checks |
| **YouTube** | Long-form recipe integration + Shorts; channel analytics for creator vetting |
| **Google Sheets** | Influencer shortlist with automatic scoring, budget split, KPI tracker |

---

## 📦 Deliverables
| # | Deliverable | File |
|---|-------------|------|
| 1 | Influencer shortlist | [`docs/03-influencer-shortlist.md`](docs/03-influencer-shortlist.md) · [`sheets/influencer_shortlist.xlsx`](sheets/influencer_shortlist.xlsx) |
| 2 | Selection criteria | [`docs/02-selection-criteria.md`](docs/02-selection-criteria.md) |
| 3 | Campaign brief | [`docs/01-campaign-brief.md`](docs/01-campaign-brief.md) |
| 4 | Content requirements | [`docs/04-content-requirements.md`](docs/04-content-requirements.md) |
| 5 | KPI list | [`docs/05-kpi-list.md`](docs/05-kpi-list.md) |
| ➕ | Full project report (PDF) | [`report/Influencer_Marketing_Plan_Report.pdf`](report/Influencer_Marketing_Plan_Report.pdf) |

---

## 🗂️ Repository structure
```
influencer-marketing-plan/
├── README.md
├── docs/
│   ├── 01-campaign-brief.md
│   ├── 02-selection-criteria.md
│   ├── 03-influencer-shortlist.md
│   ├── 04-content-requirements.md
│   └── 05-kpi-list.md
├── sheets/
│   ├── influencer_shortlist.xlsx   # 4 tabs: Criteria, Shortlist, Budget, KPI Tracker
│   └── influencer_shortlist.csv    # plain data export
└── report/
    └── Influencer_Marketing_Plan_Report.pdf
```

---

## 🧭 Campaign at a glance
| | |
|---|---|
| **Brand** | MilletBite — baked millet chips & cookies (sample brand) |
| **Campaign** | `#SnackSmartHyd` — "swap one snack a day" |
| **Audience** | 18–34 in Hyderabad (students, IT workers, gym-goers) + young parents |
| **Duration** | 4 weeks (+1 week prep, +1 week reporting) |
| **Budget** | ₹2,50,000 |
| **Creators** | 7 shortlisted (2 nano · 3 micro · 2 mid) out of 9 evaluated |
| **Platforms** | Instagram (primary), YouTube |

### Objectives
1. **Awareness** — 8,00,000 unique reach
2. **Engagement** — 60,000 engagements, 4% avg engagement rate, 150 UGC posts
3. **Consideration** — 15,000 brand profile visits, 8,000 link clicks
4. **Conversion** — 1,200 promo-code orders, 1.5x ROAS

---

## ⚖️ How influencers are selected
**Step 1 – Must-pass filters:** Indian audience ≥40%, active in last 30 days, brand-safe, no fake-follower signs, no recent competitor deals.

**Step 2 – Weighted score (1–5 each):**

| Criterion | Weight |
|-----------|-------:|
| Audience relevance (% in Hyderabad) | 30% |
| Engagement rate | 25% |
| Content fit & quality | 20% |
| Brand safety | 15% |
| Cost efficiency (₹ per view) | 10% |

Creators scoring **≥ 3.5** are shortlisted. In the Google Sheet, scores, weighted totals and status are **calculated by formulas**, so changing any input or weight updates the shortlist instantly.

### Result
| Creator | Platform | Tier | ER | Hyd audience | Score | Status |
|---------|----------|------|---:|---:|---:|---|
| Ananya Reddy | Instagram | Micro | 5.8% | 68% | 4.65 | ✅ |
| Karthik Rao | Instagram | Micro | 9.1% | 63% | 4.65 | ✅ |
| Deepika S | Instagram | Micro | 11.6% | 71% | 4.65 | ✅ |
| Priya Nair | Instagram | Nano | 9.6% | 74% | 4.60 | ✅ |
| Arjun Mehta | Instagram | Nano | 8.7% | 66% | 4.60 | ✅ |
| Sneha Kothapalli | YouTube | Mid | 1.1% | 52% | 3.75 | ✅ |
| Rahul Varma | Instagram | Mid | 3.5% | 41% | 3.65 | ✅ |
| Vikram Shetty | YouTube | Macro | 0.8% | 18% | 2.20 | ❌ |
| Trendy Hyd Offers | Instagram | Mid | 0.4% | 22% | 1.65 | ❌ |

👉 The biggest account (7.5 lakh subscribers) was **rejected** — mostly non-local audience and under 1% engagement. That is the main lesson of this task.

> ⚠️ Creator names, handles and metrics are **illustrative sample data** created for this exercise, not real creators' statistics.

---

## 🎬 Content requirements (summary)
- 1 Reel (30–60s) + 2–3 Stories per Instagram creator; 1 integration + 1 Short for YouTube
- `#ad` / Paid-partnership label (ASCI guidelines), `@milletbite`, `#SnackSmartHyd`
- Product visible in the first 3 seconds, subtitles on, 9:16 vertical
- Unique promo code + UTM link per creator
- Draft shared 48 h before posting, one revision round
- No medical or weight-loss claims · 90-day usage rights for the brand

## 📊 KPI list (summary)
| Stage | KPIs |
|-------|------|
| Awareness | Reach, impressions/views |
| Engagement | Total engagements, engagement rate, cost per engagement, UGC posts |
| Consideration | Profile visits, link clicks, new followers |
| Conversion | Promo-code orders, ROAS |
| Sentiment | % positive comments |

---

## ▶️ How to use the Google Sheet
1. Download [`sheets/influencer_shortlist.xlsx`](sheets/influencer_shortlist.xlsx).
2. In Google Sheets: **File → Import → Upload → Replace spreadsheet**.
3. Yellow cells with blue text are inputs — edit them. Everything else recalculates.
4. After the campaign, fill the **Actual** column in the `KPI Tracker` tab.

## 💡 Key learnings
- **Engagement and relevance beat reach.** Micro and nano creators gave the best score per rupee.
- **Fake followers are easy to spot with numbers:** high followers + very low views/comments = red flag.
- **Mix tiers:** nano for trust, micro for local reach, mid for credibility.
- **Measure from day one:** unique codes and UTMs show which creator actually drove sales.

---

## 👤 Author
**Reddi Malli Nandini**
🔗 [LinkedIn](https://www.linkedin.com/in/your-profile) · 💻 [GitHub](https://github.com/your-username)
