<div align="center">

# Balasurya Chandana

**Data Analyst · Analytics Engineer · Supply Chain & Operations Analytics**

Python · SQL · Power BI · Tableau · scikit-learn · spaCy · dbt · Flask

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/balasurya-chandana)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:balasuryachandana@gmail.com)
[![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)](https://public.tableau.com/app/profile/balasurya.chandana)
[![Open to Work](https://img.shields.io/badge/Open%20to%20Work-US%20Based-2ea44f?style=flat-square)](https://linkedin.com/in/balasurya-chandana)

</div>

---

## The 10-Second Version

I quantified **$70M in credit write-off exposure** using causal inference, built an **NLP triage system deployed to production**, drove **56% ridership growth** on a transit corridor through queuing models, and cut a multi-country supply chain cost base by **8–12%** through Pareto-driven supplier targeting.

I own the full stack — raw data to boardroom recommendation. I don’t hand off to someone else to “make it business-friendly.”

> Currently an Analyst at **Introlligent Inc** (US), building production-grade Power BI pipelines and deepening dbt + SQL for data warehouse workloads.

---

## What I Actually Do

Most analysts describe what happened. I build systems that explain *why* it happened — and deliver the specific number that moves the decision.

| Capability | What That Looks Like in Practice |
|---|---|
| **Causal Inference** | PSM + Ridge Regression isolating a $785/account ATE — surviving CFO follow-up |
| **Operations Research** | Little's Law + Centre of Gravity cutting wait time 28% and lifting revenue $100K+ |
| **ML Engineering** | spaCy + scikit-learn NLP pipeline, deployed on Flask, handling live free-text inference |
| **Supply Chain Analytics** | Pareto + SPC + total cost model connecting defect rates directly to P&L |
| **Business Intelligence** | Power BI / Tableau dashboards built for C-suite decisions, not data dumps |

---

## Signature Projects

### 💳 Credit Risk & Causal Inference — Fleetcor [$70M+ Exposure]
`Python` `Propensity Score Matching` `Ridge Regression` `Random Forest` `Tableau` `pandas` `scikit-learn`

**The problem:** High-risk commercial accounts silently accumulating credit exposure — visible only at write-off. The intervention *looked* effective. But selection bias made the raw comparison worthless.

**What I built:**
- Applied **Propensity Score Matching** to construct a valid counterfactual — approximating a randomized experiment from observational data
- Used **Ridge Regression** (regularized for correlated features) to estimate the Average Treatment Effect: **−$785 per treated account**
- Trained a **Random Forest classifier** optimized on precision-recall (not accuracy) to score which treated customers would still churn post-intervention
- Built a **Tableau executive dashboard** tracking write-off savings by treatment type, attrition by segment, and spend trajectory over time

| Outcome | Result |
|---|---|
| Write-off savings quantified | ~$70M |
| Avg. Treatment Effect (ATE) | −$785 per account |
| Churn prediction accuracy | 89% |
| Post-treatment spend decline | 5–7% vs. significantly higher for untreated |

**Why it matters:** Treated customers showed only 5–7% spend decline vs. comparable untreated accounts. Early intervention *preserved* customer value. That finding justified scaling the program and embedding ML-based risk scoring into CRM workflows.

[→ View Repository](https://github.com/Balasurya-Ch/Finance-and-Credit)

---

### 🚌 Public Transit Operations — CT Transit New Haven Corridor
`Excel` `Little's Law` `Demand Forecasting` `Centre of Gravity` `Queuing Theory` `KPI Framework Design`

**The problem:** Static schedules. No quantitative basis for fleet sizing. Maintenance hubs placed by convention, not by where breakdowns actually happened.

**What I built:**
- **3-scenario demand forecasts** (±10–15% CI) for budget stress-testing — single-point projections that can’t survive a “what if demand is lower” question don’t belong in capital decisions
- Applied **Little’s Law (L = λW)** to model wait time vs. frequency precisely — identified the point of diminishing returns at 8 buses
- Used **Centre of Gravity analysis** on breakdown incident data to optimize hub placement, minimizing total deadhead mileage across all service events
- Designed a **6-KPI monitoring framework** built for continuous visibility, not one-time reporting

| Outcome | Result |
|---|---|
| Passenger wait time reduction | 25–28% |
| Daily ridership | 320 → 500 passengers (+56%) |
| Annualized revenue impact | $100K+ |
| Operating cost reduction | 10–15% projected |
| Breakdown response time | 15–20% faster |

[→ View Repository](https://github.com/Balasurya-Ch/Public_Transport_Supply_Chain_Operations)

---

### 📦 Retail Supply Chain — Supplier Quality & Cost Analytics [IKEA Case Study]
`Excel` `Pareto Analysis` `Nonconformance Rate Trending` `SPC` `Total Cost Modeling` `KPI Design`

**The problem:** A global retailer tracking aggregate defect rates — masking that 20% of suppliers drove 75–80% of all failures. Managing to the average meant tolerating the outliers doing most of the damage.

**What I built:**
- **Pareto segmentation** by supplier and SKU to create an actionable intervention list (not a broad program — a specific list of the 20% causing 80% of failures)
- **Nonconformance rate trending** to separate systematic failures from isolated incidents — critical for deciding between structural intervention vs. one-time correction
- **Total landed cost model** connecting manufacturing, transportation, warehousing, and quality failure costs in one framework — translating quality targets directly into P&L impact
- Designed **6 KPIs with baselines and targets** for ongoing operational monitoring

| KPI | Target Improvement |
|---|---|
| Missing parts rate | 25–30% reduction |
| Transit damage (targeted routes) | 15–20% reduction |
| Order fulfillment accuracy | 10–15% improvement |
| Total supply chain cost per unit | 8–12% reduction |

[→ View Repository](https://github.com/Balasurya-Ch/Retail_Supply_Chain_Work)

---

### 🤖 NLP Task Intelligence System — Live Flask Deployment
`Python` `spaCy` `scikit-learn` `Flask` `Jupyter`

spaCy NLP pipeline (tokenization → lemmatization → NER → feature extraction) feeding a scikit-learn classifier that takes free-text task descriptions and returns structured category + priority labels in real time. Deployed as a browser-accessible Flask app.

- **Modular architecture**: NLP layer and classifier are independently swappable — upgrade to transformer without rebuilding the pipeline
- Classifier optimized on **precision-recall across all classes** to handle class imbalance
- Architecture mirrors enterprise service-desk triage, customer email routing, and CRM classification systems

[→ View Repository](https://github.com/Balasurya-Ch/Task-Management-System-ML)

---

### 🎮 Hybrid Recommendation Engine — Collaborative Filtering + Cold-Start Fallback
`Python` `scikit-learn` `Collaborative Filtering` `Content-Based Filtering` `Flask` `Cosine Similarity`

Hybrid system: collaborative filtering (user-item preference similarity) as primary, content-based filtering (item attribute cosine similarity) as cold-start fallback. Deployed as a live Flask app. EDA-driven architecture: sparsity analysis of the user-item matrix directly shaped the similarity metric and minimum interaction threshold.

[→ View Repository](https://github.com/Balasurya-Ch/Game_Recommendation_System)

---

## Tech Stack

| Layer | Tools |
|---|---|
| **Languages** | Python · SQL · DAX |
| **Analytics & ML** | pandas · NumPy · scikit-learn · spaCy · statsmodels |
| **Methods** | Propensity Score Matching · Ridge Regression · Random Forest · Collaborative Filtering · Queuing Theory · Causal Inference · Demand Forecasting · Pareto/SPC · Total Cost Modeling · Centre of Gravity · KPI Design |
| **BI** | Power BI · Tableau · Excel (advanced modeling) |
| **Engineering** | Flask · dbt (in progress) · Git · Jupyter |

---

## Domain Map

| Domain | Core Methods | Proven P&L Impact |
|---|---|---|
| **Financial Risk** | PSM, Ridge Regression, ATE estimation, churn modeling | $70M exposure quantified, 89% model accuracy |
| **Supply Chain** | Pareto, SPC, nonconformance trending, total cost modeling | 8–12% cost reduction pathway |
| **Operations Research** | Queuing theory, demand forecasting, facility location | 25–28% wait reduction, $100K+ revenue lift |
| **ML Engineering** | NLP pipelines, classification, recommendation systems | Production Flask deployments, live inference |
| **Business Intelligence** | KPI frameworks, executive dashboards, reporting pipelines | Power BI + Tableau at Introlligent Inc |

---

## GitHub Analytics

<div align="center">

<img height="175em" src="https://github-readme-stats.vercel.app/api?username=Balasurya-Ch&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true&hide_border=true"/>
<img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Balasurya-Ch&layout=compact&langs_count=8&theme=github_dark&hide_border=true"/>

</div>

---

## Currently Building

At **Introlligent Inc** — operational analytics and strategy

- Building a production-grade **Power BI KPI monitoring dashboard** for operations reporting
- Deepening **SQL** for large-scale analytical workloads and data warehouse querying
- Learning **dbt** for analytics engineering and modular pipeline design
- Building toward **ARIMA / Prophet** time series forecasting for demand planning

---

## Open To

*Actively seeking US-based roles — full-time, contract, or hybrid*

| Role | Signal That Fits |
|---|---|
| **Data Analyst** | End-to-end Python/SQL, causal inference, KPI design, business translation |
| **Analytics Engineer** | Pipeline development, dbt, BI tooling, data modeling |
| **Business Analyst** | Requirements definition, process analytics, stakeholder reporting |
| **Supply Chain Analyst** | Forecasting, supplier analytics, cost modeling, operations optimization |
| **BI / Reporting Analyst** | Power BI / Tableau, KPI architecture, executive dashboards |

---

## Connect

| | |
|---|---|
| **LinkedIn** | [linkedin.com/in/balasurya-chandana](https://linkedin.com/in/balasurya-chandana) |
| **Email** | balasuryachandana@gmail.com |
| **Tableau Public** | [public.tableau.com/app/profile/balasurya.chandana](https://public.tableau.com/app/profile/balasurya.chandana) |

---

<div align="center">
<sub><i>Every project starts with a business question. Every deliverable ends with a number that moves a decision.</i></sub>
</div>## Tech Stack

| | |
|---|---|
| **Languages** | Python · SQL · DAX |
| **Analytics & ML** | pandas · NumPy · scikit-learn · spaCy · statsmodels |
| **Methods** | Propensity Score Matching · Ridge/Lasso Regression · Random Forest · Collaborative Filtering · Queuing Theory · Demand Forecasting · Pareto/SPC · Total Cost Modeling · Centre of Gravity · KPI Framework Design |
| **BI & Visualization** | Power BI · Tableau · Excel (advanced modeling) |
| **Engineering** | Flask · dbt (in progress) · Git · Jupyter |

---

## Domain Map

| Domain | Core Methods | Proven P&L Impact |
|---|---|---|
| **Financial Risk** | Causal inference, PSM, ATE estimation, churn modeling | $70M exposure quantified, 89% accuracy |
| **Supply Chain** | Pareto, SPC, nonconformance trending, total cost modeling | 8–12% cost reduction pathway |
| **Operations Research** | Queuing theory, demand forecasting, facility location | 25–28% wait time cut, $100K+ revenue lift |
| **ML Engineering** | NLP pipelines, classification, recommendation systems | Production Flask deployments, live inference |
| **Business Intelligence** | KPI frameworks, exec dashboards, reporting pipelines | Power BI + Tableau at Introlligent Inc |

---

## GitHub Analytics

<div align="center">

<img height="175em" src="https://github-readme-stats.vercel.app/api?username=Balasurya-Ch&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true&hide_border=true"/>
<img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Balasurya-Ch&layout=compact&langs_count=8&theme=github_dark&hide_border=true"/>

</div>

---

## Currently Building

**Analyst @ Introlligent Inc** — operational analytics and business strategy

- Building a production-grade **Power BI KPI monitoring dashboard** for operations reporting
- Deepening **SQL** for large-scale analytical workloads and data warehouse querying
- Learning **dbt** for analytics engineering and modular pipeline design
- Building toward **ARIMA / Prophet** time series forecasting for demand planning

---

## Open To

*Actively seeking US-based roles — full-time, contract, or hybrid*

| Role | Signal That Fits |
|---|---|
| **Data Analyst** | End-to-end Python/SQL, causal inference, KPI design, business translation |
| **Analytics Engineer** | Pipeline development, dbt, BI tooling, data modeling |
| **Business Analyst** | Requirements definition, process analytics, stakeholder reporting |
| **Supply Chain Analyst** | Forecasting, supplier analytics, cost modeling, operations optimization |
| **BI / Reporting Analyst** | Power BI / Tableau, KPI architecture, executive dashboards |

---

## Connect

| | |
|---|---|
| **LinkedIn** | [linkedin.com/in/balasurya-chandana](https://linkedin.com/in/balasurya-chandana) |
| **Email** | balasuryachandana@gmail.com |
| **Tableau Public** | [public.tableau.com/app/profile/balasurya.chandana](https://public.tableau.com/app/profile/balasurya.chandana) |

---

<div align="center">
<sub><i>Every project starts with a business question. Every deliverable ends with a number that moves a decision.</i></sub>
</div>
