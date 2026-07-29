## Hi, I'm David Santos Salvador 👋

🌱 **Sustainability Specialist applying Data Science & Data Engineer** | 🤖 **Exploring AI Agents** | 🌍 **Spain**

[![Blog](https://img.shields.io/badge/-Blog-2E7D32?style=flat-square&logo=hugo&logoColor=white)](https://www.davidsantossalvador.es/blog)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/david-santos-salvador/)
[![YouTube](https://img.shields.io/badge/-YouTube-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/@David_Santos_Salvador)
[![Newsletter](https://img.shields.io/badge/-Newsletter-1B5E20?style=flat-square&logo=substack&logoColor=white)](https://www.davidsantossalvador.es/newsletter)


The skill I'm most interested in developing — and the one I think the sustainability sector needs far more of — is the ability to **move between domain knowledge and technical possibility**.

Not to become an engineer. Not to abandon the environmental focus. But to be fluent enough in both languages to identify where the gap is, scope a solution that actually fits the problem, and build it without making it more complicated than it needs to be.

Everything I publish here is part of that journey.


> *"I publish my projects and learnings not because I have all the answers, but because building in public is how I learn best — and maybe it helps someone else along the way."*

---

## 🌿 What I'm exploring

I'm a Sustainability Specialist who started studying **Data Science and Data Engineering** about a year ago — not to change careers, but because I kept hitting a ceiling in sustainability work where I could see what needed to happen technically and lacked the language to make it happen myself.

My focus sits at the intersection of two ideas:

- **🤖 AI for Sustainability** — applying data pipelines, agentic systems, and automation to real ESG and environmental challenges
- **🌱 Sustainability for AI** — keeping an honest eye on the resource cost of the tools I build

My GitHub profile is my space to show finished products. I come here to learn, share what works, share what doesn't, and document the process.




## 🛠️ Tools I'm learning with

[![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/-Jupyter_Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white)](https://jupyter.org/)




## 📂 Projects

#### 🌿 [Agentic Analytics ESG](https://github.com/Daaviid99/agentic-analytics-sustainability)
Two-agent system that turns raw environmental data (DuckDB) into natural-language ESG analysis and automated PDF sustainability reports — with per-query carbon footprint tracking built in. A prototype born from a real frustration: ESG teams spending hours in Excel doing things that should be automated.
This project explores what happens when you move sustainability data into a proper database and let an AI agent query it in plain English.
- **Stack:** Python · Claude API (Agentic tool use) · DuckDB · Streamlit · Jinja2
- **Honest note:** This is a proof of concept, not a production system. The README documents its limitations in detail.

---

#### 🗄️ [ESG-Data-Hub](https://github.com/Daaviid99/ESG-Data-Hub)
A full ESG data infrastructure built from scratch to replace the endless cycle of manual reporting. An ETL pipeline ingests sustainability data into DuckDB monthly via cron, dbt handles transformations and tracks every data change with snapshots, and OpenMetadata (hosted locally with Docker) adds data governance and lineage. Final outputs: a Power BI dashboard and structured Excel files — the data language most organisations actually speak.

On top of the auditable data layer sits a 3-agent AI system: a Data Analyst that queries the database in SQL, an ESG Specialist that interprets results against GRI frameworks and generates executive summaries, and an ESG Designer that turns the analysis into a ready-to-present report.
- **Stack:** Python · DuckDB · dbt · OpenMetadata · Docker · Claude API (multi-agent) · Power BI · Cron
- **Honest note:** Built around a real problem I was living week after week. The AI layer is a complement, not the core — the core is the auditable data infrastructure underneath. Audits require traceability, and that's what this was designed around.

---

#### 🗑️ [waste-mvp-sustaintech](https://github.com/Daaviid99/waste-mvp-sustaintech)
A data product trying to answer one question well: *where are industrial waste flows located, in what volume, and what is the best valorisation route for each of them?* Industrial waste data in Europe is scattered across 27 national registries, aggregated at the sector level, and largely disconnected from valorisation capacity. This project builds a structured dataset for Iberia, starting with the agri-food sector (olive, wine, dairy, meat), pulling from 15+ public sources and using LLM pipelines to extract structured data from corporate sustainability disclosures.
- **Stack:** Python · PostgreSQL + PostGIS · dbt-core · Dagster · Great Expectations · Splink · Claude API (LLM extraction) · FastAPI · Next.js
- **Honest note:** This is Phase 1 of an MVP. The full vision is a SaaS platform for waste managers and valorisation plant developers. Right now, it's a data pipeline and a dataset. The roadmap is documented, and the ambition is real — the product is still being built.

---

## 🎓 Business Analytics Case Studies

Projects completed as part of my Data Science training. Each one follows the same methodology: understand the business levers → define KPIs → ask the right questions → let the data answer them. The analysis, code, and conclusions are mine; the datasets and problem framing are from the course.

#### 🏙️ Caso-BA-1b · Análisis de mercado inmobiliario (Madrid)
Identified the most commercially promising property profiles and neighbourhoods for short-term rental investment in Madrid using Inside Airbnb data. Analysed price, occupancy, and acquisition cost simultaneously to surface the profiles with the highest return potential.
- **Stack:** Python · Jupyter · Pandas · Seaborn · Folium

#### ☀️ Caso-BA-2b · Detección de anomalías en plantas solares fotovoltaicas
A solar energy company had two plants showing abnormal production behaviour — and the maintenance contractor couldn't identify why. Using 34 days of 15-minute sensor and inverter readings, I analysed DC/AC efficiency ratios, irradiation patterns, and data quality gaps to identify where the failures were coming from and which equipment was involved.
- **Stack:** Python · Jupyter · Pandas · time series analysis
- **Honest note:** This case introduced me to IoT and industrial sensor data — the same patterns apply to smart cities, agricultural IoT, and any production environment where time matters.

#### 🛍️ Caso-BA-3 · Análisis CRO para e-commerce de cosmética
A cosmetics e-commerce with flat growth needed to understand *why*. RFM segmentation, cohort analysis, LTV estimation, and a product recommendation system built in Python — translated into a prioritised CRO action plan with ROI projections by lever. Main finding: 8% of clients generated 45% of revenue, and 72% of carts were being abandoned.
- **Stack:** Python · Jupyter · Pandas · Scikit-learn




## ✍️ Latest Blog Posts

- 📄 [How I Built an ESG Data Hub from Scratch](https://www.davidsantossalvador.es/how-i-built-an-esg-data-hub-from-scratch)
- 📄 [ESG Data Automation in Practice: Building an Agentic ESG System](https://www.davidsantossalvador.es/esg-data-automation-in-practice-building-an-agentic-esg-system-to-replace-manual-reporting-and-centralise-environmental-data)
- 📄 [5 Ways to Digitalise Sustainability Reporting and ESG Automation](https://www.davidsantossalvador.es/5-ways-to-digitalise-sustainability-reporting-and-automate-esg-collect)
- 📄 [I Built an AI Agent That Thinks Like Me (It Saved Me 15 Hours a Week)](https://www.davidsantossalvador.es/my-digital-brain-agent-saved-15-hours)




## 📬 Connect

I write about sustainability, data, and the honest intersection of both.

[![Blog](https://img.shields.io/badge/Read_the_blog-davidsantossalvador.es-2E7D32?style=flat-square)](https://www.davidsantossalvador.es/blog)
[![LinkedIn](https://img.shields.io/badge/Connect_on-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/david-santos-salvador/)
[![YouTube](https://img.shields.io/badge/Watch_on-YouTube-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/@David_Santos_Salvador)
