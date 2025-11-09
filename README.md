# 🧭 Lead Flow Analysis

### 📊 End-to-End Data Cleaning, Analysis & Visualization Project

This project focuses on understanding **lead behavior across different marketing channels and webinar engagement stages**. It aims to optimize marketing spend, improve conversion rates, and strengthen the alignment between pre-sales and sales teams.

---

## 📁 Project Overview

**Goal:**  
To analyze the flow of leads from creation to conversion, identify bottlenecks in the funnel, and recommend actions to improve lead quality and conversion performance.

**Key Outcomes:**
- Built a **data cleaning and transformation pipeline** in Python  
- Designed an **interactive Excel dashboard** for sales and marketing decision-makers  
- Identified actionable insights on engagement, conversion, and campaign effectiveness  

---

## 🔁 Flow Diagram
![Lead Flow Diagram](https://github.com/Namratasheetal/lead-flow-analysis/blob/main/Lead%20Analysis%20Flow.png)

---

## 🧰 Tools & Technologies

| Tool | Purpose |
|------|----------|
| **Python (Pandas, NumPy, Seaborn, Matplotlib)** | Data cleaning, transformation, and visualization |
| **Microsoft Excel** | Dashboard creation and interactive visualizations |
| **Jupyter Notebook / VS Code** | Code execution and documentation |

---

## ⚙️ Data Cleaning & Transformation Steps

1. **Removed non-ASCII characters** and standardized datetime formats  
2. **Handled missing data** — filled or dropped depending on data criticality  
3. **Created custom segments:**
   - Engagement Segment → based on webinar duration  
   - Funnel Stage → Lead Created → Webinar Attended → Qualified for Sales  
4. **Added flag columns** to indicate contacted, qualified, or converted leads  
5. **Converted mixed-type fields** (e.g., call attempts) into integers for aggregation  
6. **Exported cleaned dataset** for Excel visualization  

---

## 📈 Visualization & Dashboard Highlights

Created **seven key charts** and **interactive slicers** in Excel:

1. **Leads by Channel** — Identify top-performing marketing channels  
2. **Webinar Engagement Funnel** — Track lead progression from registration to qualification  
3. **Language-wise Conversion Rate** — Analyze performance across language demographics  
4. **Sales Team Effectiveness** — Assess conversion rate after sales handoff  
5. **Trend of Leads Over Time** — Monitor peak engagement and campaign success  
6. **Call Attempt Analysis** — Measure outreach efforts and contact drop-offs  
7. **Sales Trend vs Campaign Correlation** — Link campaign timelines with lead spikes  

**Dynamic Filters:**  
- Language  
- Channel  

---

## 🧩 Challenges & Solutions

| Challenge | Resolution |
|------------|-------------|
| Non-standard datetime formats | Cleaned using ASCII removal and `pd.to_datetime()` |
| Missing webinar duration | Dropped selectively for funnel charts |
| Mixed-type call attempt fields | Used `pd.to_numeric(errors='coerce')` |
| Funnel logic inconsistencies | Reframed funnel stage logic (attendance → duration → qualification) |

---

## 💡 Insights & Recommendations

1. Many leads **register but skip webinars** — improve reminders & timing  
2. **Hindi and regional language** leads convert more — focus on these demographics  
3. Leads watching **>35 mins webinars** convert 3× better — improve content engagement  
4. Faster lead assignment (<2 days) → higher conversion rate  
5. Channels like **digital marketing, IM, offline workshops, outbound** perform better  

---

## 🧭 Conclusion

This analysis provides a **data-driven foundation** for marketing and sales teams, helping them:  
- Track funnel health and drop-offs  
- Improve webinar engagement and follow-up strategy  
- Prioritize high-performing channels and campaigns  

It can serve as a **live dashboard model** for real-time business decision-making.

---



