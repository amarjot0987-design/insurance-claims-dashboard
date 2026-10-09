# 🏥 Insurance Claims Analysis Dashboard — Excel + Power BI

## 📌 Project Overview
End-to-end insurance claims analysis project covering a **sample of 30 claims** across Health, Motor, and Property categories. Built dashboards to track monthly claim volume, settlement rates, handler performance, and operational efficiency.

---

## 🎯 Business Questions Answered
| # | Question |
|---|---|
| 1 | What is the overall claim volume and settlement rate? |
| 2 | Which claim type has the highest volume and approved amount? |
| 3 | How are claims trending month over month? |
| 4 | How many claims are Settled vs Pending vs Rejected? |
| 5 | Which handler is most efficient in settling claims? |
| 6 | What is the average number of days to settle a claim? |
| 7 | Which months had the highest unresolved (Pending) claims? |

---

## 🔑 Key Insight
> **Pending (unresolved) claims cluster in March–April, the period to investigate first for settlement delays. Overall settlement rate is ~73%.**

---

## 🛠️ Tools & Techniques Used
| Tool | Usage |
|---|---|
| **Excel** | Data cleaning, COUNTIF, COUNTIFS, SUMIF, AVERAGEIF, conditional formatting |
| **Power BI** | DAX measures, slicers, KPI cards, status-conditional formatting |
| **Functions** | COUNTIF, COUNTIFS, SUMIF, AVERAGEIF, DIVIDE |
| **DAX** | COUNTA, SUM, CALCULATE, AVERAGE, DIVIDE |

---

## 📁 File Structure
```
insurance-claims-dashboard/
│
├── Insurance_Claims_Dashboard.xlsx   # Excel workbook (3 sheets)
│   ├── Claims Data                   # 30 records — fully formatted with status colors
│   ├── Summary Dashboard             # KPIs + Type/Monthly/Handler/Status tables + Charts
│   └── Power BI Steps                # 18-step Power BI guide
│
├── dashboard_screenshot.png          # Power BI dashboard screenshot
└── README.md
```

---

## 📊 Key Findings
- **Health claims** are the most frequent claim type (12 out of 30)
- Overall **Settlement Rate: ~73%** — 22 out of 30 claims settled
- **4 claims remain Pending** — concentrated in March–April
- **Ravi Kumar** handles the highest claim volume
- **Property claims** have the highest average claim amount (₹3,00,000+)
- Average days to settle: **~16 days** for settled claims

---

## 🚀 How to Use
1. Open `Insurance_Claims_Dashboard.xlsx` in Microsoft Excel
2. Navigate to **Summary Dashboard** for all KPIs and charts
3. For Power BI — follow **Power BI Steps** sheet (18 steps)
4. Import **Claims Data** sheet into Power BI Desktop

---

## 👤 Author
**Amarjot Singh Chawla**
B.Tech ECE (IoT) — NSUT Delhi
[LinkedIn](https://www.linkedin.com/in/amarjot-singh-chawla-02b168422/) | [GitHub](https://github.com/amarjot0987-design)
