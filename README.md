<div align="center">

# Balasurya Chandana

### Supply Chain Analyst · Data & Business Analyst · Operations Analytics

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/balasurya-chandana)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:balasuryachandana@gmail.com)
[![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)](https://public.tableau.com/app/profile/balasurya.chandana)
[![Resume](https://img.shields.io/badge/Open%20to%20Work-US%20Based-2ea44f?style=flat-square)]()

**SQL · Python · Power BI · Tableau · Azure AutoML · SAP/Tally ERP · scikit-learn · Oracle SCM · DMAIC**

---

*60% stockout reduction · 35% anomaly detection improvement · $70M+ write-off savings · 89% model accuracy*

</div>

---

## Who I Am

I’m a Supply Chain and Data Analyst with ~3 years of experience across operations, inventory, and financial risk analytics. My work spans two very different environments: a small-to-mid-sized operations firm in Hyderabad, where I rebuilt Cash and inventory workflows from scratch, and a US-based tech company, where I work in the analytics function. In both cases, the job was the same: take messy operational data and turn it into decisions that save money or prevent problems before they land.

I hold an M.S. in Business Analytics & Global Supply Chain Management from the University of New Haven (GPA 3.94, Beta Gamma Sigma Honoree), and my capstone work produced a production-grade predictive model that flagged $70M+ in credit write-off exposure. That’s not a classroom exercise; that’s what happens when you apply causal inference correctly to a real financial dataset.

Right now I’m based in the US, actively looking for analyst roles in supply chain, data, or business analytics. I don’t just build dashboards; I find the number that moves the decision.

---

## Experience

### Analyst Supply Chain — Mere Inc (Introlligent Inc).
**Jul 2025 – Present | USA**

- Built executive KPI dashboards in Power BI and Excel tracking order flow, on-time delivery, supplier performance, and supply continuity; cut decision latency by 30% and surfaced exception visibility across 4 critical operational metrics
- Led cross-functional analytics initiatives across 6+ stakeholder groups (Supply Chain, Operations, Compliance, Engineering), delivering prescriptive action plans that improved issue resolution cycle time by ~25%
- Ran structured root-cause analyses (5-Why, Pareto, fishbone) on procurement bottlenecks; standardized fixes reduced repeat escalations by 20%
- Built demand forecasting insights from CRM pipelines to surface supply risks 2–3 weeks ahead of potential shortages
- Ran scenario and sensitivity analyses on supplier delivery trends and demand adoption curves to support proactive supply plan adjustments

### Business Associate — Operations & Inventory | P&B Pvt Limited / R. Tata & Co.
**Jan 2022 – Feb 2023 | Hyderabad, India**

- Redesigned inventory allocation across SKUs using SQL and Tally ERP, reduced stockout risk by 60% and directly improved order fulfillment rates
- Built anomaly detection models to flag supply discrepancies and logistics deviations, improved issue identification accuracy by 35%, cut mean time-to-corrective-action
- Engineered statistical demand forecasting models (time-series, seasonality decomposition, MRP-aligned), reduced excess inventory carrying costs by ~15%
- Automated supply reporting pipelines in SQL and Python, eliminating 100% of manual Excel reporting
- Built supplier performance scorecards and total-cost-of-supply analyses, identified sourcing inefficiencies, reduced procurement variances by ~10%
- Standardized procurement workflows (PR to delivery receipt) across 3 sites, cut cycle times by 18%

---

## Projects

### Credit Risk Intervention & Treatment Effect Analysis — Fleetcor [$70M+]
`Python` `Propensity Score Matching` `Ridge Regression` `Random Forest` `Tableau` `Azure AutoML` `pandas` `scikit-learn`

The credit team at Fleetcor was applying proactive treatments to high-risk accounts but had no evidence the interventions were actually working or just coinciding with accounts that would have recovered anyway. Selection bias made a straight comparison useless.

I applied Propensity Score Matching to build a valid control group, then used Ridge Regression to isolate the Average Treatment Effect (−$785/account). A Random Forest classifier (precision-recall optimized) scored which treated accounts would still churn. Azure AutoML validated the 89% model accuracy. A Tableau executive dashboard made the findings actionable without re-running code.

| Metric | Result |
|---|---|
| Write-off savings identified | ~$70M |
| Avg. Treatment Effect per account | −$785 |
| Churn prediction accuracy | 89% |
| Post-treatment spend decline | 5–7% vs. much higher for untreated group |

The key insight wasn’t just the $70M; it was that treated customers only dropped 5–7% in spend. Early intervention preserved the customer relationship. That’s what made the business case for scaling.

[→ Finance-and-Credit](https://github.com/Balasurya-Ch/Finance-and-Credit)

---

### Public Transit Operations Optimization 
`Excel` `Queuing Theory (Little’s Law)` `Demand Forecasting` `Centre of Gravity` `KPI Framework Design`

CT Transit’s corridor had no quantitative basis for fleet sizing or hub placement. Schedules were static. Maintenance crews were positioned by convention, not data.

I built 3-scenario demand forecasts (±10–15% confidence intervals) so management had a range to stress-test, not a single number to trust blindly. Applied Little’s Law to model exactly how much wait time each additional bus removes — identified diminishing returns at 8 buses, which is the number that went into the recommendation. Centre of Gravity analysis on breakdown incident data repositioned maintenance hubs, cutting deadhead mileage by 12%.

| Metric | Result |
|---|---|
| Passenger wait time reduction | 25–28% |
| Daily ridership | 320 → 500/day (+56%) |
| Annualized revenue impact | $100K+ |
| Operating cost reduction | 10–15% projected |
| Breakdown response time | 15–20% faster |

[→ Public_Transport_Supply_Chain_Operations](https://github.com/Balasurya-Ch/Public_Transport_Supply_Chain_Operations)

---### Retail Supply Chain Quality & Cost Analytics — IKEA Case Study
`Excel` `Pareto Analysis` `Nonconformance Rate Trending` `SPC / DMAIC` `Total Cost Modeling` `KPI Design`

A global multi-country supply chain was tracking quality failures as company-wide averages, which made the numbers look fine at the top while hiding that 20% of suppliers were driving 75–80% of all defects. Managing the average meant ignoring the outliers doing the damage.

I ran Pareto segmentation to surface that concentration, then nonconformance rate trending per supplier and route to separate chronic failures from one-off incidents. A total landed cost model translated quality targets into P&L impact, so the conversation shifted from “we need a supplier program” to “here are the 12 suppliers we fix first, and here’s the dollar value.” Applied SPC and DMAIC framework throughout.

| KPI | Improvement Target |
|---|---|
| Missing parts rate | 25–30% reduction |
| Transit damage (targeted routes) | 15–20% reduction |
| Order fulfillment accuracy | 10–15% improvement |
| Total supply chain cost per unit | 8–12% reduction |
| Simulated revenue leakage | 20% reduction |

[→ Retail_Supply_Chain_Work](https://github.com/Balasurya-Ch/Retail_Supply_Chain_Work)

---

### NLP Task Intelligence System — Deployed on Flask
`Python` `spaCy (en_core_web_sm)` `scikit-learn` `Flask` `Jupyter`

Operational teams waste time on the lowest-value part of their workflow: reading unstructured text, categorizing it, and assigning priority. I built a system that does this automatically.

The spaCy pipeline handles tokenization, lemmatization, NER, and stop-word filtering. A scikit-learn classifier (precision-recall optimized across all classes, not just accuracy) takes the normalized input and returns a task category and priority tier. The whole thing runs in a Flask web app, not a Jupyter notebook, an actual browser interface. The NLP layer and classifier are independently swappable, which is what makes it extensible rather than a one-off demo.

This architecture is identical to what drives enterprise service-desk triage, CRM ticket routing, and operations workflow classification, just at smaller scale.

[→ Task-Management-System-ML](https://github.com/Balasurya-Ch/Task-Management-System-ML)

---

### Hybrid Recommendation Engine — Collaborative Filtering + Cold-Start Fallback
`Python` `scikit-learn` `Collaborative Filtering` `Content-Based Filtering` `Cosine Similarity` `Flask`

Built a hybrid recommendation system: collaborative filtering (user-item preference similarity) as the primary engine, content-based filtering (item attribute cosine similarity) as the cold-start fallback. Deployed on Flask.

The design decision that mattered was doing sparsity analysis during EDA first, that’s what revealed the user-item matrix was too sparse for pure collaborative filtering and made the hybrid approach the right call, not just a safe one. The domain is games, but the user-item matrix architecture transfers directly to product recommendation, demand-driven assortment, and supplier matching.

[→ Game_Recommendation_System](https://github.com/Balasurya-Ch/Game_Recommendation_System)

---

## Technical Skills

| | |
|---|---|
| **Languages** | SQL (SSMS), Python (pandas, NumPy, scikit-learn), R, Advanced Excel (Power Query, Pivot Tables) |
| **BI & Visualization** | Power BI (DAX, Data Modeling), Tableau, Matplotlib, Seaborn |
| **Cloud & ML Platforms** | Azure AutoML & AI, Databricks, Google Cloud Vertex AI |
| **ERP & Planning** | Tally ERP9, SAP-equivalent workflows, MRP/S&OP planning |
| **Supply Chain Methods** | Demand Forecasting, Inventory Optimization, Total Landed Cost, Cost-to-Serve, Network Optimization, Supplier Scorecard, S&OP Analytics |
| **Analytics Methods** | Propensity Score Matching, Regression, Clustering, Anomaly Detection, SPC, DMAIC/Lean Six Sigma, Scenario Analysis, Root-Cause Analysis (5-Why, Pareto) |
| **Engineering** | Flask, dbt (in progress), Git, Jupyter, Anaconda, Power Query automation |

---

## Education

**M.S. Business Analytics — Global Supply Chain Management**
University of New Haven, West Haven, CT — GPA: 3.94 / 4.00
Beta Gamma Sigma International Business Honor Society
*Supply Chain Risk · Demand Forecasting · Operations Analytics · Predictive Modeling · ERP/MRP & Planning · Global Supply Chain Management*
Aug 2023 – May 2025

**B.S. Mathematics, Computer Science & Electronics**
Osmania University, Hyderabad, India — CGPA: 8.18 / 10
Jun 2018 – Nov 2021

---

## Certifications

DataCamp: SQL, Python, R · Azure AI Essentials · LinkedIn Learning: Excel & Business Analytics · Google Digital Marketing · Google Analytics

---

## GitHub Stats

<div align="center">

<img height="175em" src="https://github-readme-stats.vercel.app/api?username=Balasurya-Ch&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true&hide_border=true"/>
<img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Balasurya-Ch&layout=compact&langs_count=8&theme=github_dark&hide_border=true"/>

</div>

---

## Open To

*Currently in USA, Open to relocation*
*Actively seeking roles — full-time, contract, or hybrid*

| Role | Fit |
|---|---|
| **Supply Chain Analyst** | Demand forecasting, inventory optimization, S&OP, supplier scorecards, cost modeling |
| **Data Analyst** | Python/SQL pipelines, predictive modeling, KPI design, business translation |
| **Business Analyst** | Cross-functional analytics, root-cause analysis, process improvement, stakeholder reporting |
| **Operations Analyst** | Logistics analytics, supply continuity, ERP workflows, process standardization |
| **Analytics Engineer** | Pipeline development, dbt, BI tooling, Power BI/Tableau |

---

## Connect

| | |
|---|---|
| **LinkedIn** | [linkedin.com/in/balasurya-chandana](https://linkedin.com/in/balasurya-chandana) |
| **Email** | balasuryachandana@gmail.com |
| **Tableau Public** | [public.tableau.com/app/profile/balasurya.chandana](https://public.tableau.com/app/profile/balasurya.chandana) |

---

<div align="center">
<sub><i>2+ years. Two countries. Five+ projects. One standard: does the number move a decision?</i></sub>
</div>
