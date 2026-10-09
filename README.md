# Awesome-Visual-Data-Analytics

## Top Visual Data Analytics Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Business Intelligence, Dashboarding & Self-Hosted Analytics Platforms*

**Last updated: October 2026**



This repository tracks notable **commercial visual data analytics platforms** and **open-source projects** that enable organizations to explore, visualize, and derive insights from data — from enterprise BI suites to self-hosted SQL-native analytics platforms and embedded dashboarding engines.



**Examples** include Salesforce Tableau, Microsoft Power BI, Looker, Qlik Sense, Domo, Sisense, ThoughtSpot, TIBCO Spotfire, Sigma Computing, and GoodData (the category leaders).



**Open-source emphasis**: Visual data analytics is one of the strongest open-source domains. **Apache Superset** leads with 60,000+ GitHub_Stars and Superset 5.0 delivering AI-powered intelligence layer with MCP server for LLM access . **Metabase** provides no-code self-service analytics for non-technical users . **Grafana** delivers unified dashboards across 100+ data sources with ML-powered alerting . **Redash** enables SQL-driven dashboards with collaboration . **Lightdash** brings a Looker-like semantic layer for dbt users . **Apache Doris** and **ClickHouse** power real-time analytical backends, while **Streamlit** and **Evidence.dev** enable code-first analytics apps . This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



The visual data analytics market is estimated at **$15.7 billion in 2026** and projected to reach **$32.5 billion by 2031**, exhibiting a **highly concentrated market structure** dominated by mega-cap cloud platform leaders (Microsoft, Google, Salesforce) while specialized independent vendors occupy high-value niches.

| Platform | Description & Key Strengths | Starting Pricing | Free Tier / Trial Limit | Company Size (Revenue / Valuation) |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft Power BI](https://powerbi.microsoft.com/)** | Deeply integrated with Excel, Azure, and Microsoft 365 with Copilot AI. Best for Microsoft-centric enterprise ecosystems. | $10/user/month (Pro plan) | 60-day free trial (Pro features) | Market Cap: **$3.93 Trillion** (Parent: Microsoft; Rev: $331.8B/yr) |
| **[Looker (Google Cloud)](https://looker.com/)** | Governed LookML semantic modeling layer and enterprise BI. (Includes free Looker Studio for basic visual reporting). | $9/user/month (Looker Studio Pro); Enterprise Looker from $60,000/yr | 30-day free trial (Looker Core) / Looker Studio free forever | Market Cap: **$4.28 Trillion** (Parent: Alphabet; Rev: $350B+/yr) |
| **[Salesforce Tableau](https://www.tableau.com/)** | Enterprise visual analytics standard with drag-and-drop interface, Tableau Pulse AI insights, and Tableau Next agentic workflows. | $15/user/month (Viewer); $75/user/month (Creator) | 14-day free trial (Tableau Cloud) / Tableau Public free for public datasets | Market Cap: **$280 Billion** (Salesforce acquisition: $15.7B) |
| **[Qlik Sense](https://www.qlik.com/)** | Associative analytics engine for exploring hidden data relationships across complex enterprise sources. | $300/month (Standard plan) | 30-day free trial | Valuation: **$10 Billion** (Rev: ~$1 Billion/yr) |
| **[ThoughtSpot](https://www.thoughtspot.com/)** | Natural language search-driven analytics powered by SpotIQ AI engine. | $25/user/month (Essentials plan) | 14-day free trial (max 5M rows / 1M export limit) | Valuation: **$4.2 Billion** (ARR: $150 Million+) |
| **[Sigma Computing](https://www.sigmacomputing.com/)** | Spreadsheet-native interface operating directly on Snowflake, Databricks, and BigQuery cloud data warehouses. | $61,000/year (Estimated entry-level enterprise contract) | 7-day free trial (no credit card required) | Valuation: **$3.0 Billion** (ARR: $200 Million+) |
| **[Sisense](https://www.sisense.com/)** | Embedded analytics platform featuring fusion data engine and in-chip technology for product embedding. | $25,000/year (Estimated entry-level contract) | 14-day free trial (Self-Serve tier) | Valuation: **$1.1 Billion** (ARR: $185 Million) |
| **[TIBCO Spotfire](https://www.tibco.com/products/tibco-spotfire)** | Advanced predictive analytics and location intelligence for scientific, industrial, and engineering data. | $65/user/month (Estimated Spotfire Analytics tier) | 30-day free trial (Spotfire Industry Pro) | Acquisition Value: **$8.0 Billion** (Parent: Cloud Software Group / Thoma Bravo) |
| **[Domo](https://www.domo.com/)** | Business-user-driven cloud BI platform with 1,000+ connectors, Magic ETL, and low-code app framework. | $30,000/year (Estimated entry-level contract) | 30-day free trial (unlimited credits for core features) | Acquisition Value: **$400 Million** (Progress acquisition in 2026; Rev: $318.9M) |
| **[GoodData](https://www.gooddata.com/)** | Headless composable analytics platform built for developer-first embedded BI at scale. | $1,000/month (Platform base fee + workspace fee) | 30-day free trial (100MB per workspace limit) | Valuation: **$311 Million** (Total Funding: $167.7M; Rev: ~$63M) |



## Open-Source GitHub Projects



### Full-Featured BI Platforms



- **[Apache Superset](https://github.com/apache/superset)**

  **The leading open-source modern data exploration and visualization platform**, Apache-2.0 licensed with **60,000+ GitHub_Stars** . **Superset 5.0 provides a rich set of data visualizations** with an easy-to-use interface for creating and sharing dashboards . **SQL IDE with Jinja templating, semantic layer, and advanced analytics** . **Superset MCP server** enables LLM access to datasets, charts, and dashboards for intelligent analytics . **Intelligence layer** enables AI agents to explore all company data with definition-level access control . **Best for open-source business intelligence**.



- **[Metabase](https://github.com/metabase/metabase)**

  **Open-source BI and analytics**, AGPL-3.0 licensed with **40,000+ GitHub_Stars** . **No-code question builder** for business users — ask questions without SQL . **Dashboards, alerts, and subscriptions** . **Self-hosted or cloud** . **Best for self-service analytics by non-technical users** .



- **[Grafana](https://github.com/grafana/grafana)**

  **The de facto standard for open-source dashboards**, AGPL-3.0 licensed with **65,000+ GitHub_Stars** . **Connects to 100+ data sources including Prometheus, Loki, Tempo, Elasticsearch, PostgreSQL, MySQL, and more** . **Rich visualization library with alerting, annotations, and templating** . **ML-powered alerting** with outlier detection and forecasting (AI features tier-locked on Grafana Cloud) . **Best for operational and observability dashboards** .



- **[Redash](https://github.com/getredash/redash)**

  **Open-source data visualization and dashboarding**, BSD-2-Clause licensed with **25,000+ GitHub_Stars** . **SQL-based query editor** with visualization and dashboards . **Collaboration features** with query sharing . **Best for SQL-driven dashboards** .



- **[Lightdash](https://github.com/lightdash/lightdash)**

  **Open-source Looker alternative for dbt users**, MIT licensed with **4,000+ GitHub_Stars** . **Semantic layer built on dbt** — defines metrics and dimensions in YAML . **Self-service analytics for the whole team** . **Best for dbt-centric analytics workflows** .



### Embedded & Developer-Focused Analytics



- **[Cube](https://github.com/cube-js/cube)**

  **Open-source semantic layer for data applications**, MIT licensed with **17,000+ GitHub_Stars** . **Headless BI** — define metrics once, use them everywhere . **Supports SQL, REST, GraphQL, and MDX APIs** . **Best for embedded analytics and consistent metrics** .



- **[Streamlit](https://github.com/streamlit/streamlit)**

  **Python framework for building data apps**, Apache-2.0 licensed with **35,000+ GitHub_Stars** . **Turn Python scripts into interactive web apps** — no frontend experience required . **Best for custom data apps and dashboards** .



- **[Evidence.dev](https://github.com/evidence-dev/evidence)**

  **Code-based BI platform**, MIT licensed with **4,000+ GitHub_Stars** . **Markdown + SQL** — build dashboards as code . **Version-controlled analytics** . **Best for developer-centric analytics** .



- **[Perses](https://github.com/perses/perses)**

  **CNCF dashboard and visualization tool**, Apache-2.0 licensed . **GitOps-friendly dashboard-as-code** . **The open standard for dashboards** . **Best for dashboard-as-code** .



### Analytical Databases



- **[Apache Doris](https://github.com/apache/doris)**

  **Real-time analytical database**, Apache-2.0 licensed with **12,000+ GitHub_Stars** . **High-performance SQL analytics** . **Best for real-time analytics** .



- **[ClickHouse](https://github.com/ClickHouse/ClickHouse)**

  **The leading columnar analytical database**, Apache-2.0 licensed with **35,000+ GitHub_Stars** . **Real-time ingestion and sub-second queries** . **Best for large-scale analytics** .



- **[StarRocks](https://github.com/StarRocks/starrocks)**

  **High-performance analytical database**, Apache-2.0 licensed with **8,000+ GitHub_Stars** . **Real-time analytics with lakehouse integration** . **Best for modern analytics** .



- **[DuckDB](https://github.com/duckdb/duckdb)**

  **In-process analytical database**, MIT licensed with **20,000+ GitHub_Stars** . **"SQLite for analytics"** — columnar storage with vectorized execution . **Best for embedded analytics** .



### Additional Strong Open-Source Options



- **Apache ECharts** — Powerful charting and visualization library .

- **D3.js** — Data-driven documents for custom visualizations .

- **Plotly** — Interactive charting library for Python, R, and JavaScript .

- **Bokeh** — Interactive visualization for Python .

- **Altair** — Declarative statistical visualization in Python .

- **Vega-Lite** — Grammar of interactive graphics .

- **Observable** — Reactive notebooks for data exploration .

- **Jupyter** — Interactive computing with visualization output .

- **Apache Zeppelin** — Web-based notebook for data analytics .

- **Rill Data** — Open-source BI for event data .



**Frameworks for building custom visual data analytics solutions**: Combine **Apache Superset** for comprehensive open-source BI with 60+ visualization types and AI-powered intelligence layer . Use **Metabase** for self-service analytics by non-technical users . Deploy **Grafana** for operational dashboards and ML-powered alerting . Choose **Lightdash** for dbt-centric analytics with semantic layer . Integrate **Cube** for headless BI and embedded analytics . Use **Streamlit** or **Evidence.dev** for code-first analytics apps . Power with **ClickHouse** or **Apache Doris** for real-time analytics . Note that true enterprise BI with governed semantic layers, predictive AI, and embedded analytics at scale (Tableau, Power BI, Looker) remains primarily commercial territory; open-source stacks provide strong dashboarding, self-service analytics, and semantic modeling foundations that require integration for complete visual data analytics.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Visual data analytics platforms handle sensitive business data and may expose PII. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations.

- **Total cost of ownership varies significantly** — Tableau at €75-115/user/month and Power BI at $10-20/user/month represent very different cost profiles. Apache Superset is free but requires engineering investment for deployment and maintenance .

- **License considerations**: Superset uses Apache-2.0, Metabase uses AGPL-3.0, Grafana uses AGPL-3.0, Lightdash uses MIT, and Cube uses MIT. Verify licensing against your use case before committing.

- The open-source ecosystem provides strong dashboarding, self-service analytics, and semantic modeling foundations, but **governed semantic layers, predictive AI, and embedded analytics at scale** remain primarily commercial offerings.



---



**Made for data analysts, BI engineers, and organizations seeking visual data analytics sovereignty.**

Let's make visual data analytics more open, transparent, and accessible.
