# Hi, I'm Carl 👋

BI & Data Architecture leader with 20+ years modernizing enterprise analytics — 12 of them leading BI for Finance and Supply Chain organizations. I design governed dimensional and semantic models, lead platform migrations, and build the standards and Centers of Excellence that make BI sustainable at scale. Currently expanding hands-on into Microsoft Fabric (DP-600 in progress) and Python.

Open to Architect / Lead / Senior BI Manager roles — remote or Nashville, TN metro.

## What I work with

**Languages:** SQL (T-SQL) · DAX · M (Power Query) · Python (learning)
**Platforms:** Microsoft Fabric · Azure SQL · Databricks · Presto/Trino · SQL Server
**BI & Modeling:** Power BI (semantic models, Direct Lake) · SSAS Tabular · Dimensional/Star Schema modeling · Data Governance
**AI-assisted development:** Cursor, Claude Code, custom GPTs for standards enforcement and code review — see [the evaluation pipeline](https://github.com/CarlWooldridge/fabric-portfolio/tree/main/job-search-fabric/ai-workflow) behind the Job Search project

## Background

- Architected Finance's migration from on-prem SQL Server to a cloud analytics stack (AWS S3, Databricks, Presto/Trino, Power BI) — AWS & Databricks certified for the effort
- Built and led a Power BI Center of Excellence: ~10 governed semantic models, 100–200 reports, standards adopted across a 10-developer team
- 12 years architecting and delivering Finance & Supply Chain BI — dimensional models, automated reconciliations, executive reporting
- Now building hands-on Fabric projects (Lakehouse, Direct Lake semantic models, Delta Lake optimization) as part of DP-600 study — see pinned repos

## Featured projects

**[fabric-portfolio](https://github.com/CarlWooldridge/fabric-portfolio)** — Running series of hands-on Microsoft Fabric projects built alongside DP-600 study. First up: [P1 — NYC Taxi](https://github.com/CarlWooldridge/fabric-portfolio/tree/main/P1-nyc-taxi), a 76.5M-row benchmark comparing three ingestion methods, isolating the real effect of compaction vs. V-Order vs. Z-Order, and mapping five distinct T-SQL surface-area gaps between Lakehouse and Warehouse.

**[P2 — Olist: the DP-600 build](https://github.com/CarlWooldridge/fabric-portfolio/tree/main/P2-olist)** — My DP-600 preparation, built rather than read: 25 sessions mapped to the exam's skills outline, from ten security layers tested as real users to a medallion lakehouse, SCD2, and a Direct Lake semantic model with RLS/OLS, each step closed on a measured number. Two of the findings: a SQL view that silently cost ~600× by pushing a Direct Lake model into DirectQuery fallback (17 ms vs 10 s), and a deliberately bad model that came out 17% larger at the same query speed. Reference page: [Security in Fabric: ten layers](https://carlwooldridge.github.io/fabric-portfolio/P2-olist/reference/security-ten-layers.html).

**[Job Search — an AI evaluation pipeline on Fabric](https://github.com/CarlWooldridge/fabric-portfolio/tree/main/job-search-fabric)** — A workflow I actually run daily, productionized: AI-scored job postings flowing through Dataflow Gen2 into a Fabric SQL Database, a Direct Lake semantic model, and a Power BI report I write back to from inside the report via Translytical Task Flows and a Python User Data Function. 1,066 evaluated postings. Includes a [post-mortem](https://carlwooldridge.github.io/fabric-portfolio/job-search-fabric/reference/writeback-incident-postmortem.html) on the routine `DROP` that erased the evidence it had ever happened, a scoring rubric calibrated by measured override rate rather than preference, and a DAX bug where the measure, the relationship, and the data each verified correct while the answer stayed wrong.

## Currently

🎓 Studying for DP-600 (Microsoft Fabric Analytics Engineer)
🔍 Open to BI Architect / Analytics Engineering roles, Microsoft-stack, Finance BI a plus
📍 Nashville, TN metro or remote (US)
