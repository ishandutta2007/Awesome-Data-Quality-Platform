<p align="center">
  <img src="assets/banner.svg" alt="Awesome Data Quality Platform Banner" width="100%" />
</p>

# 🛡️ Awesome Data Quality Platform & Ecosystem 📊

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <img src="https://img.shields.io/github/last-commit/ishandutta2007/Awesome-Data-Quality-Platform?style=flat-square" alt="Last Commit"/>
  <img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Data-Quality-Platform?style=flat-square" alt="License"/>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

> **Curated List of SaaS Products & Open-Source GitHub Projects**  
> *Focused on Data Validation, Anomaly Detection, Observability, Profiling, Cleansing, Data Contracts & Pipeline Quality Gates.*  
> 🗓️ **Last updated: September 2026**

---

## 📌 Table of Contents
- [💡 Market Overview & Sector Insights](#-market-overview--sector-insights)
- [🏢 SaaS & Hosted Platforms](#-saas--hosted-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#-how-to-contribute)
- [☕ Support & Sponsorship](#-support--sponsorship)
- [📈 Star History](#-star-history)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## 💡 Market Overview & Sector Insights

> 📊 **Estimated Market Size & Structure**: The global Data Quality and Observability market is estimated at **$5.8 Billion (2026)** and is projected to reach over **$11.5 Billion by 2030** (CAGR ~18.5%).  
> 🧩 **Market Fragmentation**: The sector is **moderately fragmented**. Enterprise legacy suites (Informatica, IBM, Talend, Collibra) hold large institutional shares, while modern automated observability platforms (Monte Carlo, Acceldata, Anomalo) and open-source ecosystems (Great Expectations, Soda, dbt) rapidly capture cloud-native data stacks.

---

## 🏢 SaaS & Hosted Platforms

| Platform 🚀 | Scale & Valuation / Funding 💰 | Starting Price 💵 | Free Tier / Trial Limits 🎁 | Key Features & Focus 🔍 |
| :--- | :--- | :--- | :--- | :--- |
| **[Informatica Data Quality](https://www.informatica.com/)** | **~$11.2B Enterprise Value** (Public: INFA) | ~$2,000/month (IPU usage consumption model) | 30-day Free Trial (Free IPU tier up to 500 processing units) | Enterprise IDMC suite, deep governance, AI CLAIRE data matching & cleansing. |
| **[Collibra Data Quality](https://www.collibra.com/)** | **~$5.25B Valuation** ($800M+ Raised) | ~$15,000/year base platform subscription | 14-day Enterprise Sandbox Guided Trial (Limited to 5 datasets & 10k rows) | Integrated catalog, rule-based profiling, enterprise governance integration. |
| **[Monte Carlo](https://www.montecarlodata.com/)** | **~$1.6B Valuation** ($236M+ Raised) | ~$15,000/year starting tier | 14-day Free Trial (Up to 10 warehouse tables & 1M monitored rows) | Automated ML anomaly detection, end-to-end lineage, warehouse incident tracking. |
| **[Talend Data Quality (Qlik)](https://www.talend.com/)** | **~$2.4B Acquisition Value** by Thoma Bravo / Qlik | ~$1,170/user/month (Talend Data Fabric starter) | 14-day Full Feature Cloud Trial | Cleansing, deduplication, enrichment, and pipeline integration. |
| **[Precisely Trillium](https://www.precisely.com/)** | **~$3.5B Enterprise Value** (Clearlake Capital) | ~$10,000/year enterprise deployment | 30-day Managed Evaluation Trial (Max 50,000 records processed) | High-volume entity resolution, postal address standardization, data integrity. |
| **[Ataccama / Ataccama ONE](https://www.ataccama.com/)** | **~$550M Valuation** ($150M+ Raised) | ~$1,000/month starting cloud tier | 30-day Free Trial (Includes Ataccama ONE GenAI Profiler up to 25 tables) | Unified MDM, automated data profiling, data quality firewall & AI rules. |
| **[Acceldata](https://www.acceldata.io/)** | **~$350M Valuation** ($100M+ Raised) | ~$1,000/month starting tier | 14-day Free Trial (Monitors up to 5 compute pipelines or data sources) | Multi-engine observability (Snowflake, Databricks, Hadoop), compute drift & quality. |
| **[Anomalo](https://www.anomalo.com/)** | **~$300M Valuation** ($72M+ Raised) | ~$1,200/month starting tier | 14-day Guided Trial (Up to 20 tables & automated root-cause analysis) | ML-driven deep table checks, unstructured & structured automated validation. |
| **[Great Expectations (GX Cloud)](https://greatexpectations.io/)** | **~$250M Valuation** ($65M+ Raised - Superconductive) | $0/month (GX Cloud Developer Free Tier) | **Free Forever Plan** (1 Workspace, up to 10 connected tables & 100 scans/mo) | Managed GX Core deployment, hosted Data Docs, cloud validation workflows. |
| **[Bigeye](https://www.bigeye.com/)** | **~$200M Valuation** ($68M+ Raised) | ~$990/month starting tier | 14-day Free Trial (Up to 15 tables and 50 metrics monitored) | Autometrics, delta checks, lineage-driven data SLA management. |
| **[Soda](https://www.soda.io/)** | **~$100M Valuation** ($26M+ Raised) | $0/month (Soda Cloud Free Developer) | **Free Forever Plan** (1 User, 3 Data Sources, up to 50 Dataset checks) | Readable SodaCL checks, declarative contracts, CI/CD pipeline integration. |
| **[Data Ladder](https://dataladder.com/)** | **~$50M Valuation** (Bootstrapped/Private) | ~$4,500/license/year | 14-day Desktop Trial (DataMatch Enterprise limit 1,000 records export) | Visual data cleansing, fuzzy matching, deduplication & entity resolution. |

---

## 🔓 Open-Source GitHub Projects

Below is a curated list of top open-source data quality tools, frameworks, and profiling engines, sorted by GitHub star count ⭐.

| Project 📦 | GitHub Stars 🌟 | License 📄 | Primary Use Case & Description 🎯 |
| :--- | :--- | :--- | :--- |
| **[dbt Core / dbt tests](https://github.com/dbt-labs/dbt-core)** | [<img src="https://img.shields.io/github/stars/dbt-labs/dbt-core?style=social&color=white" alt="dbt-core Stars"/>](https://github.com/dbt-labs/dbt-core/stargazers) | Apache-2.0 | Built-in and custom SQL test assertions (uniqueness, referential integrity, null checks) inside analytics transformation pipelines. |
| **[Great Expectations (GX Core)](https://github.com/great-expectations/great_expectations)** | [<img src="https://img.shields.io/github/stars/great-expectations/great_expectations?style=social&color=white" alt="GX Stars"/>](https://github.com/great-expectations/great_expectations/stargazers) | Apache-2.0 | The leading Python data validation framework—expressive Expectations, automated Data Docs HTML reports, and data profiling. |
| **[OpenMetadata](https://github.com/open-metadata/OpenMetadata)** | [<img src="https://img.shields.io/github/stars/open-metadata/OpenMetadata?style=social&color=white" alt="OpenMetadata Stars"/>](https://github.com/open-metadata/OpenMetadata/stargazers) | Apache-2.0 | Unified open metadata platform featuring native data quality testing, column profiling, data lineage, and alert integrations. |
| **[ydata-profiling (Pandas Profiling)](https://github.com/ydataai/ydata-profiling)** | [<img src="https://img.shields.io/github/stars/ydataai/ydata-profiling?style=social&color=white" alt="ydata-profiling Stars"/>](https://github.com/ydataai/ydata-profiling/stargazers) | MIT | One-line exploratory data analysis and profiling generator for Pandas & Spark DataFrames with statistics and quality alerts. |
| **[Deequ (AWS)](https://github.com/awslabs/deequ)** | [<img src="https://img.shields.io/github/stars/awslabs/deequ?style=social&color=white" alt="Deequ Stars"/>](https://github.com/awslabs/deequ/stargazers) | Apache-2.0 | Amazon's library built on Apache Spark for defining "unit tests for data" at massive petabyte scale. |
| **[DuckDB](https://github.com/duckdb/duckdb)** | [<img src="https://img.shields.io/github/stars/duckdb/duckdb?style=social&color=white" alt="DuckDB Stars"/>](https://github.com/duckdb/duckdb/stargazers) | MIT | High-performance in-process analytical SQL database frequently used for local fast data validation and quality check execution. |
| **[Elementary](https://github.com/elementary-data/elementary)** | [<img src="https://img.shields.io/github/stars/elementary-data/elementary?style=social&color=white" alt="Elementary Stars"/>](https://github.com/elementary-data/elementary/stargazers) | Apache-2.0 | dbt-native data observability solution—dbt package for schema change monitoring, volume anomaly detection, and Slack alerts. |
| **[Soda Core](https://github.com/sodadata/soda-core)** | [<img src="https://img.shields.io/github/stars/sodadata/soda-core?style=social&color=white" alt="Soda Core Stars"/>](https://github.com/sodadata/soda-core/stargazers) | Apache-2.0 | CLI & Python library using YAML-based SodaCL to run data validation checks across SQL engines and data lakes. |
| **[Amundsen](https://github.com/amundsen-io/amundsen)** | [<img src="https://img.shields.io/github/stars/amundsen-io/amundsen?style=social&color=white" alt="Amundsen Stars"/>](https://github.com/amundsen-io/amundsen/stargazers) | Apache-2.0 | Data portal & metadata engine originally by Lyft that surface data preview, profiling stats, and quality scores. |
| **[Data Cleaning (Awesome List)](https://github.com/ishandutta2007/Awesome-Awesome-Awesome)** | [<img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Awesome-Awesome?style=social&color=white" alt="Awesome Stars"/>](https://github.com/ishandutta2007/Awesome-Awesome-Awesome/stargazers) | CC0-1.0 | Curated index of resources, frameworks, and algorithms for data cleaning, sanitization, and data quality assurance. |
| **[Great Expectations Gallery / Plugins](https://github.com/great-expectations/great_expectations)** | [<img src="https://img.shields.io/github/stars/great-expectations/great_expectations?style=social&color=white" alt="GX Gallery Stars"/>](https://github.com/great-expectations/great_expectations/stargazers) | Apache-2.0 | Community repository of reusable Expectations and quality connectors for SQL databases and APIs. |

---

## 🛠️ Implementation Playbooks & Architectures

When building an enterprise-grade data quality pipeline:
1. **Shift-Left Validation**: Enforce schema contracts and null check assertions at the ingest phase using **Soda Core** or **dbt tests**.
2. **Automated Warehouse Observability**: Deploy **Monte Carlo**, **Anomalo**, or **Elementary** to catch volume spikes, column drift, and freshness degradation.
3. **Data Profiling & Docs**: Use **ydata-profiling** or **GX Core** to automatically publish data docs and distribution metrics for analytics teams.

---

## 🤝 How to Contribute

We welcome community contributions! To add or update a data quality platform or open-source tool:
1. Fork the repository 🍴
2. Create a feature branch (`git checkout -b add-dq-tool`)
3. Add your entry following the tabular format with factual information and verified links
4. Submit a Pull Request 🚀

---

## ☕ Support & Sponsorship

If you find this curated ecosystem list helpful for your data engineering team or research, please consider supporting the project:

- 🌟 **Star** this repository to increase visibility!
- 🔀 **Fork** and share with your data community.
- ☕ **Sponsor & Buy a Coffee**: [GitHub Sponsors - @ishandutta2007](https://github.com/sponsors/ishandutta2007)

Thank you for supporting open-source data reliability! ❤️

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Data-Quality-Platform&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Data-Quality-Platform&type=date&legend=top-left)

---

## ⚠️ Disclaimer

- This is a **community-curated** resource list for educational and benchmark purposes.
- Company valuations, revenue estimations, pricing, and GitHub star counts reflect public records as of 2026.
- Product logos and brand names belong to their respective owners.
