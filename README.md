#  Sales & Marketing ROI Dashboard

**An interactive Excel dashboard that shows where marketing dollars work hardest, and where they don't.**

![Excel](https://img.shields.io/badge/Built%20with-Microsoft%20Excel-217346?logo=microsoftexcel&logoColor=white)
![PivotTables](https://img.shields.io/badge/PivotTables-Slicers-blue)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

![Dashboard Preview](images/dashboard-preview.png)
<!-- Add a screenshot of your dashboard at images/dashboard-preview.png -->

</div>

---

## The Short Version

Across **9 campaigns, 3 channels, and 3 months (Jun–Aug 2025)**, **$13.0K in ad spend generated $55.1K in revenue**, a **~323% blended return**.

**Email is the standout channel.** It produced the highest ROI on the lowest spend, and its newsletter campaign improved every month.

|  Total Ad Spend |  Total Revenue |  Avg. ROI |  Avg. CPA |
|:---:|:---:|:---:|:---:|
| **$13,019** | **$55,060** | **421%** | **$18.34** |

---

##  Business Questions Answered

| Question | Where to look |
|---|---|
| How much are we spending vs. earning? | KPI cards + Spend vs. Sales trend |
| Which campaigns give the best return? | ROI and CPA by campaign |
| Which channel performs best? | ROI by Channel chart |
| What does it cost to win one customer? | CPA by Campaign |

---

##  Key Insights

**1. Email wins on ROI, by a wide margin.**
Email averaged **562% ROI**, versus 360% for Facebook and 341% for Google Ads, while using the smallest share of budget (~25% of total spend).

**2. The August Newsletter is the most efficient campaign.**
It returned **777% ROI at a $7.88 CPA**. Its ROI climbed each month: **231% → 677% → 777%**.

**3. Higher spend didn't mean higher revenue.**
In August, spend rose **41%** (from $3.9K to $5.5K), but revenue **fell 10%** (from $20.8K to $18.8K). Monthly ROI dropped from 433% in July to 240% in August.

**4. Two August paid campaigns are the weak spots.**
*08 Promo 2* (Google Ads) had the worst CPA at **$33.86** and the lowest ROI at **150%**. *08 Promo 1* (Facebook) was close behind at **$27.35 CPA**.

**5. Recommendation:** Shift budget from underperforming paid promos toward Email, and test whether the newsletter's results hold as spend scales.

---

##  Dashboard Features

**KPI Cards:** Total Ad Spend · Total Revenue · ROI (%) · Average CPA

**Visuals**
-  **Spend vs. Sales Trend** (line chart): monthly relationship between investment and revenue
-  **CPA by Campaign** (bar chart): cost-efficiency ranking
-  **ROI by Channel** (bar chart): Email vs. Facebook vs. Google Ads

**Interactivity:** Slicers for **Campaign** and **Month** update every chart and KPI at once.

---

##  Metric Definitions

| Metric | Formula |
|---|---|
| **CTR** | Clicks ÷ Impressions |
| **LCR** (Lead Conversion Rate) | Leads ÷ Clicks |
| **SCR** (Sales Conversion Rate) | Conversions ÷ Leads |
| **CPL** (Cost per Lead) | Ad Spend ÷ Leads |
| **CPA** (Cost per Acquisition) | Ad Spend ÷ Conversions |
| **ROI** | (Revenue − Ad Spend) ÷ Ad Spend |

---

##  Tools & Skills Demonstrated

- **Excel PivotTables & PivotCharts** for aggregating and summarizing campaign data
- **Slicers** for self-service filtering by campaign and month
- **Calculated metrics** (CTR, LCR, SCR, CPL, CPA, ROI) built from raw campaign data
- **Conditional formatting & KPI cards** for an executive-ready summary
- **Data cleaning & transformation** to prepare the dataset for analysis
- **Data storytelling:** turning numbers into a clear recommendation




##  How to Use

1. Download `sales_marketing_roi_dashboard.xlsx` and open it in Microsoft Excel (desktop version recommended for slicers).
2. Go to the **DASHBOARD** sheet.
3. Click the **Campaign** or **Month** slicers to filter. Hold `Ctrl` to select multiple.
4. Click **Clear Filter** on a slicer to reset the view.

---

##  Notes & Limitations

- The dataset covers **9 campaigns over 3 months**, so findings are directional, not statistically conclusive.
- The headline ROI (421%) is the **average of campaign-level ROIs**. The **blended ROI** (total revenue vs. total spend) is **323%**, which weights larger campaigns more heavily. Likewise, the average CPA of $18.34 compares to a blended **$17.27**.

##  Next Steps

- Extend the dataset to 12+ months to test seasonality
- Add a budget-reallocation scenario (what if 20% of paid spend moved to Email?)
- Track customer lifetime value (LTV) alongside CPA
- Rebuild in Power BI or Tableau for comparison

---
