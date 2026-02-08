# 📊 SaaS Onboarding Funnel & Retention Analysis

> **Executive Summary:** Analyzing user journey friction and long-term retention patterns to optimize product onboarding.

---

### 🚀 Key Insights
| Metric | Achievement |
| :--- | :--- |
| **Funnel Efficiency** | **58%+ completion rate** for core media-play action. |
| **Platform Variance** | **iOS** sessions averaged **46 mins longer** than Android. |
| **Retention** | Monitored cohorts of **1.2k–1.6k users** to identify drop-offs. |

---

### 🛠 Tech Stack
* **Analysis:** SQL (BigQuery), Amplitude, GA4
* **Visualization:** Amplitude
* **Metrics:** Conversion Rate, Retention Rate, Session Duration

---

### 📈 Visualizations & Data

#### 1. User Onboarding Funnel (Amplitude)
*Mapped onboarding for 34.6k Android and 29.3k iOS users.*
![Funnel Visualization](./Users_Onboarding_and_Retention_Analysis%20(2).png)

#### 2. Retention Cohort (Amplitude)
*Visualized retention patterns per group.*
![Retention Heatmap](./Cohort%20(1).png)

---

### 🧾 Technical Implementation
**SQL Funnel Query (GA4 + BigQuery)**
Tracked step-by-step funnel events from add-to-cart to purchase and calculated conversion rates.
👉 [**View SQL Query Source Code**](./ga4_funnel_full_query_from_user%20(1).sql)
