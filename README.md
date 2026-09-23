# Hi, I'm Khoa (David) Tran 👋

**Data Analyst** · SQL · Python · Power BI · PostgreSQL · Toronto, ON

I'm a final-year Software Development & Network Engineering student at Sheridan College (graduating **December 2026**) who ended up spending most of my time on data: building pipelines, modeling warehouses, and turning messy source files into reports people can actually trust.

The part I enjoy most is the unglamorous middle: finding the data quality issue nobody documented, writing down the assumption behind an ambiguous requirement, and making sure the numbers reconcile before anyone sees a chart.

🎯 **Looking for:** new-grad / full-time **Data Analyst, BI Analyst, or Analytics Engineer** roles in Ontario or New Brunswick, starting early 2027.

---

## 🔧 Featured Projects

### VietDist Analytics Platform · *Analytics Engineering*
`Python` `PostgreSQL` `SQLAlchemy` `Google Drive API` `Azure AD / MSAL` `Power BI`

End-to-end pipeline for a simulated FMCG distributor, built solo against a realistic business requirements document: 10 source files in 4 formats (CSV / XLSX / XLSM / XLSB) → PostgreSQL Medallion warehouse (Bronze / Silver / Gold) → Power BI semantic model.

- **SCD Type 2** employee dimension with point-in-time joins, so a rep changing region doesn't rewrite last year's reports
- **Temporal fact table** for a sales plan revised multiple times a year, keeping every version queryable
- Row counts asserted end to end (raw = staging = fact); 0 orphan keys, 0 duplicates on the true grain
- Every ambiguous requirement logged in an assumptions file instead of silently guessed

🔗 [Repository](https://github.com/David277353/vietdist-analytics)

### Sales Forecasting & Inventory Planning · *Machine Learning*
`Python` `LightGBM` `SHAP` `pandas`

Global LightGBM model forecasting daily units sold across 676 SKUs and 6 sales channels, with SHAP explanations the commercial team can read in units of product.

- Found an undocumented **2-day reporting cycle** in the data that made one naive baseline look far worse than it was, and switched to a fair baseline instead of quoting the inflated comparison
- **WAPE 0.531**, about 17% better than the fair lag-14 baseline, with known limitations documented in the README

🔗 [Repository](https://github.com/David277353/Sales-Forecasting-Inventory-Planning)

### E-Commerce Data Analytics · *SQL / Cloud*
`SQL` `BigQuery` `Google Analytics sample dataset`

SQL analysis of multi-million-row Google Analytics transaction data in BigQuery.

- Unnested hit- and product-level records into an analysis-ready table
- Cumulative revenue tracking with window functions ($240K+ over 14 weeks)
- CTE / JOIN co-purchase analysis surfacing a concrete bundling recommendation

🔗 [Repository]((https://github.com/David277353/ECommerceProject-DataAnalyst-KhoaTran))

---

## 📁 More Projects

| Project | What it is | Tools |
|---|---|---|
| [Fashion Market & Sales Analysis](https://github.com/David277353/fashion-market-sales-powerbi) | 4-page marketing performance report: 175 campaigns, ROAS by funnel stage, zero-ROAS campaigns flagged | Power BI, DAX |
| Bank Customer Churn Analysis | 10,000-customer churn analysis with a star schema model, 3-page dashboard, and manager-facing slide summary | Power BI, DAX |
| [Smartphone Sales & Customer Behavior](https://github.com/David277353/SmartphoneSales-Hackathon-KhoaTran-DataAnalystProject) | Hackathon analysis of sales trends and purchasing behavior | SQL, Google BigQuery |
| [UN SDG #4: Quality Education](https://github.com/David277353/DFG-SD) | Sheridan Datathon 2025, 5-person team. I handled data analysis and validated AI-agent outputs against manual EDA | Python, Vertex AI |
| [BioLinker](https://github.com/David277353/BenchSciChallenge) | BenchSci hackathon: BigQuery schema for a self-serve biomedical knowledge explorer | BigQuery, Python |

---

## 🤝 Volunteer Work

**Data Analyst, U+ (U+ Toastmaster/U+ Education) · Volunteer Connect**
Analytics for a Canadian youth-development nonprofit, including:
- **Youth Volunteerism Benchmark** (solo): Statistics Canada data, multi-sheet Excel model with documented QA checks and a plain-language insight memo for program staff
- **DA-42 Career Impact** (team): labour-market and partner-prospect analysis in Tableau, shortlisting GTA organizations for outreach

---

## 🚧 Currently Building

**E-commerce Analytics Warehouse**: Olist Brazilian e-commerce dataset, PostgreSQL + dbt (staging / intermediate / marts) + Power BI.

---

## 🛠️ Tech Stack

**Data & SQL:** SQL · PostgreSQL · BigQuery
**Programming:** Python (pandas, NumPy, SQLAlchemy, LightGBM, SHAP, Matplotlib, Plotly)
**BI & Reporting:** Power BI · DAX · Excel · Tableau
**Cloud:** GCP (BigQuery, Vertex AI) · AWS (coursework labs) · Azure AD
**Workflow:** Git · GitHub · VS Code · DBeaver

**Languages:** English · Vietnamese (native) · French (intermediate)

---

## 📫 Connect

[LinkedIn](https://linkedin.com/in/khoatran-da) · [Email](mailto:ktran4618@gmail.com) · [GitHub](https://github.com/David277353)
