# Wide World Importers Business Process Analysis  

End‑to‑end analytics project on Microsoft’s **Wide World Importers** sample database.  
It reverse‑engineers WWI’s purchasing, sales, and warehouse workflows, surfaces key
revenue & cost drivers, and wraps the insights in a formal business report.

---

## 🎯 Objective

* Map WWI’s core business processes and related tables  
* Deliver business‑critical KPIs: sales trends, gross‑profit dynamics, stock turnover, and supplier risk
* Detect notable data trends and suggest bussiness actions  
---

## 🛠 Tools & Technique

| Layer        | Tech / Tool | Notes |
|--------------|-------------|-------|
| Query  | **SQL Server Management Studio (SSMS)** | All scripts tested on `WideWorldImportersDW` |
| Visualization  | **Python 3** (`pandas`, `matplotlib`) | Optional ad‑hoc notebooks |
| Docs         |  PDF | 80‑page final report in `Analysis report.pdf` |

---

## 🔑 Key Insights Uncovered & Why They Matter

| Insight | Business Impact |
|---------|-----------------|
| **Packaging Materials keep the lights on.** The category is the company’s single biggest revenue engine. | Prioritise supply‑chain resilience and dynamic safety‑stock policies for this line before any other. |
| **Novelty Items are boom‑and‑bust.** They fueled the 9.7 % YoY sales surge in 2016 (+92 % for the group) but cooled sharply after 2022. | Treat as a tactical product line—seasonal promos instead of blanket re‑orders; watch lead times. |
| **Growth is slowing.** Revenue and gross profit hit highs in 2019 & 2022, yet the five‑year CAGR is flattening. | Time to pursue margin expansion (pricing, cost cuts) rather than sheer volume. |
| **Clear seasonality exists.** March, July, and October are peak months; February, June, and September slump—especially for Packaging Materials. | Shift workforce rosters & warehousing space in line with the cycle; load balance promotions. |
| **Discounts ≠ loyalty.** USB Novelties stayed low‑margin despite multiple price cuts; Halloween masks run a chronic loss. | End ineffective blanket discounts; run data‑backed, product‑specific campaigns—or delist. |
| **Stock age alarm: > 4 000 days** on multiple SKUs. | Liquidate or bundle immediately; introduce rolling stock‑age KPIs. |
| **Procurement ≠ demand.** “The Gu Red Shirt” leads imports yet lags in profitability; contracts, not market pull, drive buying decisions. | Move to demand‑driven MRP, renegotiate supplier MOQs, diversify vendors to cut tied‑up capital. |
| **Data gaps hide waste.** No historical stock snapshots or true supplier delivery timestamps hamper turnover & lead‑time analytics. | Add audit tables + ETL to capture daily holdings & actual delivery dates; close the visibility loop. |

---

## 👤 Contact

**Trương Bảo Khang**  
Email: truongbaokhang.work@gmail.com  
University: Foreign Trade University  
Major: International Economics  
