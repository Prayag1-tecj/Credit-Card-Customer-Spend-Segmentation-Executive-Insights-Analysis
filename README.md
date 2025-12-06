## 🧾 About This Project

This project applies unsupervised customer segmentation to credit card users to uncover distinct financial and behavioral clusters. Using PCA for dimensionality reduction and K-Means clustering, 17+ card usage and repayment features were reduced into 2 principal components, forming 8 clear customer segments validated through Silhouette Score and Elbow Method.

Key KPIs such as Balance, Purchases (One-off vs Installment), Credit Utilization, Credit Limit, and Full Payment Ratio enabled precise profiling and transformation of clustering output into business-relevant financial behaviors. The segmentation clearly distinguishes between high-value transactors, premium spenders, and high-risk debt revolvers, providing actionable insights for risk-control, retention, and targeted portfolio strategies.

---

### 📌 Methodology Summary

| Step | Technique | Purpose |
|---|---|---|
| 1 | Data Cleaning & Feature Engineering | Remove noise, build meaningful ratios (e.g., Utilization) |
| 2 | PCA | Reduce 17+ features → 2 interpretable components |
| 3 | K-Means Clustering | Form stable behavioral clusters |
| 4 | Silhouette & Elbow | Validate **k = 8** cluster size |
| 5 | KPI Profiling | Derive spend, repayment, debt & risk patterns |
| 6 | Executive Insights | Translate clusters into portfolio action |

---

### 📊 Core KPIs Used

| KPI | Purpose |
|---|---|
| **Balance** | Current debt level |
| **Purchases** | Spending intensity (one-off vs installment) |
| **Credit Limit** | Available spending capacity |
| **PRC_FULL_PAYMENT** | Repayment discipline indicator |
| **Credit Utilization** | Balance / Credit Limit (risk lever) |

---

### 🔍 Key Findings: 8 Customer Segments

| Segment | Core Behavior | Strategic Action |
|---|---|---|
| **Ultra-VIP / Top Tier** | Highest spend, strong payment rate | Premium rewards + retention |
| **Aggressive Debt Revolvers** | High debt & cash advances, low payment | Risk mitigation & restructuring |
| **Premium Spenders** | High purchases, moderate repayment | Push full-pay habits + upgrades |
| **Frequent Transactors** | High swipe frequency, low debt | Loyalty boosts, line increases |
| **Pure Cash Users** | Heavy cash advance reliance | Monitor default risk, manage returns |
| **Conservative / Low Use** | Minimal spend & card activity | Activation & engagement push |
| **Utilization Stretchers** | High utilization vs limit | Controlled exposure strategy |
| **Occasional Spenders** | Predictable seasonal activity | Timed promotional nudges |

---

### 🏁 Strategic Outcomes

- Shift from uniform credit treatment → **data-driven personalization**
- Early risk detection for revolvers, cash-advance clusters, and utilization heavy users
- Improved retention for VIP and loyal high-frequency segments
- Better allocation of APR benefits, credit line adjustments, and loyalty rewards
- Portfolio-level insight into **default risk, churn triggers, and profitability paths**

---

### 📂 Deliverables Included

- PCA component visualizations
- Cluster distribution plots
- KPI comparison graphs
- Executive insights summary
- Full segmentation notebook & KPIs dashboard

---

### 🚀 Why This Project Matters

This segmentation framework enables financial institutions to realign marketing, risk oversight, and credit management strategies with nuanced behavioral groups, improving revenue growth, repayment health, and customer lifetime value through precision-focused decisioning.


