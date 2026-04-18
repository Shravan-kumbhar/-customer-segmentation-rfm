# -customer-segmentation-rfm
Customer segmentation using RFM analysis and K-Means clustering on e-commerce data

# Customer Segmentation Analysis — RFM + K-Means Clustering

## Project Overview
Analysed 1M+ real e-commerce transactions to segment 4,338 customers
into behavioural groups using RFM (Recency, Frequency, Monetary)
feature engineering and K-Means clustering.

## Business Problem
An online retail business needed to understand their customer base
to run targeted marketing campaigns instead of sending the same
message to all customers.

## Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Power BI (interactive dashboard)
- Dataset: Online Retail II — UCI Machine Learning Repository

## Project Steps
1. Data cleaning — handled 135K missing IDs, cancellations, duplicates
2. RFM feature engineering — calculated Recency, Frequency, Monetary per customer
3. K-Means clustering — optimal K=4 selected via elbow method
4. Visualisation — 4 charts built in Matplotlib/Seaborn
5. Power BI dashboard — interactive segment slicer with business KPIs

## Key Findings
| Segment | Customers | Revenue Share | Avg Spend |
|---|---|---|---|
| Champions | 612 (14%) | 36% | £5,241 |
| Loyal Customers | 1,687 (39%) | 25% | £1,283 |
| At Risk | 794 (18%) | 14% | £521 |
| Dormant | 1,245 (29%) | 10% | £394 |

**Key insight:** 14% of customers (Champions) generate 36% of
all revenue — making them the highest priority retention target.

## Business Recommendations
- **Champions** — VIP loyalty programme, early product access
- **Loyal Customers** — Upsell with bundle offers and personalised recommendations
- **At Risk** — Urgent win-back email campaign with 15% discount
- **Dormant** — Last-chance offer, then suppress from marketing lists


## How to Run
```bash
pip install pandas numpy scikit-learn matplotlib seaborn openpyxl
jupyter notebook customer_segmentation.ipynb
```
