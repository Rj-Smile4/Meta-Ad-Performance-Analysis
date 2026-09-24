# 📊 Meta Ad Performance Analysis (Power BI Dashboard)

An end-to-end Marketing Analytics project built with Power BI to analyze advertising campaigns running across Meta platforms (Facebook and Instagram). This report provides actionable visibility into campaign reach, audience engagement, conversion funnel efficiency, and budget utilization.

---

## 📌 Business Problem & Objectives
The primary objective of this project is to evaluate the performance of paid ad campaigns on Facebook and Instagram:
- **Platform & Format Effectiveness:** Identify which ad creative formats (Video, Stories, Carousel, Image) and platforms deliver the best return.
- **Audience Profiling:** Understand user engagement across gender, age groups, and geographies.
- **Funnel Drop-off Identification:** Analyze conversion pacing from Impressions to Clicks and final Purchases.
- **Budget & ROI Optimization:** Track total budget spending and cost efficiency across multiple campaigns.

---

## 📈 Key KPIs & Summary Metrics
- **Total Impressions:** 216K (Strong campaign visibility and reach)
- **Total Clicks:** 25.4K
- **Engagements:** 29K (Includes Clicks, Shares, Comments)
- **Click-Through Rate (CTR):** 11.76% (Substantially higher than industry benchmarks, reflecting high creative appeal)
- **Engagement Rate:** 13.56%
- **Conversions (Purchases):** 1.3K
- **Conversion Rate:** 5.21% (Purchases / Clicks)
- **Purchase Rate:** 0.61% (Indicates high top-of-funnel interest but sharp drop-off before checkout)
- **Total Budget:** $2.5M (Average budget per campaign: ~$50.7K)

---

## 🔍 Key Insights from the Dashboard
1. **Ad Creative Formats:**
   - **Video Ads** outperformed other formats with the highest CTR (11.9%), Conversion Rate (5.2%), and Engagement Rate (13.7%).
   - **Story Ads** drove the highest volume of impressions (72K).
2. **Demographics:**
   - **Gender:** Female users accounted for the highest share of engagement (43%, ~13K interactions) compared to males (22%).
   - **Age Groups:** Peak responsiveness observed in the **18–30 age segment**; engagement declines sharply after 35+.
3. **Geographic Distribution:**
   - High volume and reach concentrated in the **US, India, and Brazil**.
4. **Time & Timing Patterns:**
   - Peak user activity occurs during **afternoon and evening hours (15:00–20:00)**.
   - Campaigns show notable spikes during scheduled mid-week promotional events.

---

## 💡 Business Recommendations
- **Reallocate Budget to High-ROI Formats:** Shift marketing spend toward **Video and Story ads** rather than static carousels/images.
- **Targeted Audiences:** Prioritize female audiences aged **18–30** in high-engagement geographies.
- **Conversion Funnel Optimization:** Improve landing page load speed, simplify checkout flows, and introduce retargeting campaigns to fix the lower-funnel drop-off.
- **Dayparting:** Schedule high-spend delivery in the afternoon and evening time slots to capture maximum active engagement.

---
👤 Author
Portfolio / LinkedIn: Raju Raidas
GitHub: @Rj-Smile4

## 🛠️ Data Model & Tech Stack
- **Fact Table:** `ad_events` (event-level interactions: impressions, clicks, purchases)
- **Dimension Tables:** `ads`, `campaigns`, `users`
- **Model Schema:** Star Schema linking dimensions to the fact table
- **Tools Used:** Power BI Desktop, DAX, Power Query, Data Modeling

---

## 📂 Repository Structure
```text
├── Data/
│   ├── ad_events.csv
│   ├── ads.csv
│   ├── campaigns.csv
│   └── users.csv
├── Dashboard/
│   └── Meta Ad Performance Plane A.pbix
├── Documentation/
│   ├── Business Requirements Document.pdf
│   ├── Domain Knowledge Document.pdf
│   └── Dashboard Insights.pdf
└── README.md
