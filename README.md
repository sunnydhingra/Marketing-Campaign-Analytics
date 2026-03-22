# Marketing-Campaign-Analytics
End-to-end marketing analytics project using MySQL, Excel and Power BI

## 📌 Project Overview
Analyzed Q1 2024 digital marketing data across Google, 
Facebook and Email channels to identify the most 
cost-efficient campaigns and highest-value audience 
segments. Built an end-to-end analytics solution using 
MySQL, Excel and Power BI.

---

## 🎯 Business Problem
The marketing team had no unified view of campaign 
performance across 3 channels. Budget decisions were 
being made without data. This project builds a single 
source of truth for campaign ROI.

---

## 🔧 Tools Used
| Tool | Purpose |
|---|---|
| MySQL | Data storage, querying, KPI calculation |
| Excel | Power Query, KPI summary, pivot analysis |
| Power BI | Interactive 3-page dashboard |

---

## 📁 Project Structure
```
marketing-campaign-analytics/
│
├── sql/
│   └── queries.sql          ← All 6 business queries
│
├── raw_data/
│   ├── query1_channel_overview.csv
│   ├── query2_campaign_roas.csv
│   ├── query3_channel_cpa.csv
│   ├── query4_audience_segments.csv
│   ├── query5_budget_tracker.csv
│   └── query6_weekly_trends.csv
│
├── marketing_analysis.xlsx
├── marketing_campaign_tracker.pbix
└── README.md
```

---

## 📊 Key Findings

### Finding 1 — Email is the Most Efficient Channel
- Email CPA: ₹[YOUR NUMBER]
- Google CPA: ₹[YOUR NUMBER]
- Email delivers [X]x lower cost per acquisition
- **Recommendation:** Increase Email budget by 20% in Q2

### Finding 2 — Retargeting Outperforms All Objectives
- Retargeting ROAS: [X]x
- Awareness ROAS: [X]x  
- Retargeting campaigns deliver [X]% higher ROAS
- **Recommendation:** Shift 15% of Awareness budget 
  to Retargeting

### Finding 3 — High Value Audience Identified
- 25-34 age group + Returning customers
- Avg Order Value: ₹[YOUR NUMBER]
- [X]% higher than overall average
- **Recommendation:** Create lookalike audience 
  based on this segment for Q2

---

## 📈 Dashboard
🔗 [View Live Power BI Dashboard]([YOUR PUBLISHED LINK])

### Dashboard Pages:
**Page 1 — Executive Summary**
![Executive Summary]
https://github.com/sunnydhingra/Marketing-Campaign-Analytics/blob/main/Page3.png

**Page 2 — Channel Deep Dive**
![Channel Deep Dive]
https://github.com/sunnydhingra/Marketing-Campaign-Analytics/blob/main/Page2.png

**Page 3 — Audience Intelligence**
![Audience Intelligence]
https://github.com/sunnydhingra/Marketing-Campaign-Analytics/blob/main/Page3.png



## 🗄️ Database Schema
```sql
campaigns     → campaign metadata (9 campaigns)
daily_metrics → daily spend, impressions, clicks
conversions   → individual conversion events + revenue
customers     → customer demographics
```

---

## 💡 SQL Concepts Used
- JOINs (LEFT JOIN, INNER JOIN)
- Window Functions (LAG, PARTITION BY)
- Aggregate Functions (SUM, AVG, COUNT)
- CASE WHEN for categorization
- NULLIF for divide-by-zero handling
- CTEs for multi-step analysis

---

