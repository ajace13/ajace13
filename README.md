![Aidan Long - Applied AI and Data Science, University of Chicago](https://capsule-render.vercel.app/api?type=waving&color=0:800000,100:1B3A5C&height=220&section=header&text=Aidan%20Long&fontColor=ffffff&fontSize=52&fontAlignY=30&desc=Forward-Deployed%20AI%20Engineer%20%C2%B7%20MS%20Applied%20Data%20Science%2C%20UChicago&descAlignY=50&descSize=18)

### Forward-deployed AI engineer who builds with ML | MS Applied Data Science, University of Chicago (Dec 2027)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aidan%20Long-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aidanlong9/)
![UChicago](https://img.shields.io/badge/MS%20Applied%20Data%20Science-University%20of%20Chicago-800000?style=for-the-badge)
![Relocation](https://img.shields.io/badge/Open%20to%20relocation-NYC%20%C2%B7%20Chicago%20%C2%B7%20SF%20Bay%20Area-424242?style=for-the-badge&logo=googlemaps&logoColor=white)
![Open to work](https://img.shields.io/badge/Open%20to%20work-2EA043?style=for-the-badge)

I like sitting with the people who have the problem, working out what they actually need, and shipping the AI tool that solves it. At Ten Ventra that meant agents and a pricing engine for a real estate client. At the UChicago Data Science Institute it meant graph neural network research for Fermilab. I want to keep doing customer-facing engineering where the hard part is ML. I'm finishing an MS in Applied Data Science at the University of Chicago (expected December 2027), after a BA there in economics and data science (2026).

My economics background is the part most ML engineers don't have. I've modeled $113M of solar loans, analyzed building energy use, and trained models on a GPU cluster, so I can talk about power, capital and compute in the same conversation.

---

## Pinned work

**[Snowflake MCP Server & Streamlit App](https://github.com/ajace13/snowflake-mcp-server-streamlit)** — plain-English questions over a Snowflake star schema, answered through four bounded, read-only tools instead of free-form SQL. Survives 23 adversarial questions (false premises, DROP TABLE injection, data it doesn't have); 76 tests in CI.

**[RAG over SEC filings](https://github.com/ajace13/RAG-Financial-Reports)** — ask questions about 10-K/10-Q filings and get answers with verified, passage-level citations. Hybrid BM25 + vector search with a cross-encoder re-ranker nearly doubles Hit@10 over keyword search alone (0.25 to 0.49) on 125 FinanceBench questions; runs free on a local LLM.

**[Cloud data engineering portfolio](https://github.com/ajace13/cloud-data-engineering-portfolio)** — one dataset across four platforms: Google Cloud SQL, a Snowflake star schema (57 of 57 reconciliation checks), the MCP server above, and a Databricks Delta lakehouse. Every project has a runnable demo and tests in CI.

---

## Contributed to

**[NuGraph](https://github.com/nugraph/nugraph)** — Fermilab's graph neural networks for 3D neutrino reconstruction from LArTPC detector data. On a seven-member UChicago Data Science Institute team, I owned the instance-decoder changes for NuGraph3: the encoder initializes instance embeddings, every pass of the core message-passing loop refines them, and the decoder clusters detector hits into individual particles from the refined embeddings. Validation Rand score rose ~15% over a 0.474 baseline, and scaling training from 1 to 4 GPUs cut a run from 1.08 days to 5.4 hours. The changes are implemented in the current version of NuGraph3 ([PR #139](https://github.com/nugraph/nugraph/pull/139)).

---

## Experience

**AI Engineer, Ten Ventra** (AI consulting and automation startup, remote) · May 2026 – Jul 2026 — engineered 8 data collectors and a pricing engine for off-market LA multifamily deals, pairing hedonic regression (property random effects + spatial random walk) with Mahalanobis similarity search to price deals with confidence intervals before due diligence; worked directly with a real estate client to turn their manual deal flow into Claude Code agent skills they run on demand; and shipped a FastAPI + Next.js geospatial tool that finds LA County lots with room for accessory dwelling units.

**Student Researcher, UChicago Data Science Institute** (research for Fermilab, Batavia, IL) · Sep 2025 – Mar 2026 — extended NuGraph3, Fermilab's open-source PyTorch Geometric graph neural network for 3D neutrino reconstruction, moving instance embeddings into its core message-passing loop; validation Rand score rose ~15% over a 0.474 baseline, and scaling training from 1 to 4 GPUs cut a run from 1.08 days to 5.4 hours. Owned the instance-decoder changes on a seven-member team, now implemented in the current version of NuGraph3.

**Investment Analyst Intern, Eyre Street Capital** · Jun 2025 – Sep 2025 — scenario, sensitivity and cash-flow models to structure and diligence $113M of senior secured solar loans.

**Data Analyst, Environmental Frontiers** (energy research lab) · May 2024 – Dec 2024 — Python data pipelines and an energy-savings optimization model across large, heterogeneous building-energy datasets.

**Investment Analyst Intern, PPF Group** (Prague) · Aug 2024 – Sep 2024 — Python web scrapers for cross-sector equity and fixed-income research; valuation-range analysis.

---

## Stack

**ML & AI**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![PyG](https://img.shields.io/badge/PyTorch%20Geometric-3C2179?style=for-the-badge)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![MCP](https://img.shields.io/badge/MCP%20%26%20Tool%20Use-412991?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG%20%26%20Reranking-412991?style=for-the-badge)

**Data & Systems**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## Earlier projects

**[DataFest 2026 Hackathon](https://github.com/ajace13/datafest2026-hackathon)** — customer-journey analysis with outlier detection and interactive geospatial plots, built in a weekend.

**[Data Ethics: Misinformation & LLMs](https://github.com/ajace13/Data-Ethics-Misinformation-Project)** — ML vs. LLM fake-news detection across five datasets, plus LLM bias testing against the BBQ benchmark.

**[UChicago Course Catalog Webscraper](https://github.com/ajace13/Course-Catalog-Webscraper)** — every course in the university catalog, scraped into analysis-ready CSVs.

---

## Education

**University of Chicago** — MS in Applied Data Science, expected December 2027

**University of Chicago** — BA in Data Science & Economics (double major), 2026

---

## Get in touch

Open to new-grad roles in forward-deployed and applied AI engineering first, then ML engineering and data science, and to relocating to New York, the SF Bay Area or staying in Chicago. The best way to reach me is [LinkedIn](https://www.linkedin.com/in/aidanlong9/).
