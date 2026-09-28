# Awesome-Data-Quality-Platform

## Top Data Quality Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Data Validation, Anomaly Detection, Observability, Profiling, Cleansing, Contracts & Pipeline Quality Gates*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Data Quality**. These systems validate data, detect anomalies, enforce contracts, profile datasets, and help teams prevent bad data from reaching downstream consumers.

**Examples** include Monte Carlo, Bigeye, Soda, Great Expectations, Ataccama, Talend Data Quality, Precisely Trillium, Anomalo, Acceldata, Informatica Data Quality, Ataccama ONE, Collibra Data Quality, IBM InfoSphere QualityStage, and Data Ladder (the category leaders).

**Open-source emphasis**: Data quality has strong open-source foundations. **Great Expectations**, **Soda Core**, **dbt tests**, **Elementary**, and **OpenMetadata** are widely used for validation, monitoring, and governance. This section heavily expands those projects.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Monte Carlo](https://www.montecarlodata.com/)**  
  Leading data observability platform for automated monitoring, anomaly detection, lineage-aware incident management, and warehouse-scale data reliability.

- **[Bigeye](https://www.bigeye.com/)**  
  Data quality and observability platform with monitors, SLAs, and AI-assisted trust features for modern data stacks.

- **[Soda](https://www.soda.io/)**  
  Data quality platform with open-core (Soda Core) and commercial offerings—readable checks, data contracts, and pipeline integration.

- **[Great Expectations (GX Cloud)](https://greatexpectations.io/)**  
  Data quality platform built on the popular open-source GX Core framework—expectations, validation, and documentation with managed options.

- **[Ataccama / Ataccama ONE](https://www.ataccama.com/)**  
  Enterprise data quality, MDM, and governance platform with extensive built-in DQ functions and unified data management.

- **[Talend Data Quality (Qlik)](https://www.talend.com/)**  
  Data quality and profiling capabilities integrated with Talend/Qlik data integration and governance suites.

- **[Precisely Trillium](https://www.precisely.com/)**  
  Enterprise data quality and data integrity solutions for cleansing, matching, and standardization.

- **[Anomalo](https://www.anomalo.com/)**  
  Automated data quality monitoring platform focused on ML-based anomaly detection with low configuration overhead.

- **[Acceldata](https://www.acceldata.io/)**  
  Data observability platform covering quality, pipeline reliability, and multi-engine environments.

- **[Informatica Data Quality](https://www.informatica.com/)**  
  Enterprise data quality capabilities within Informatica’s Intelligent Data Management Cloud and related products.

- **[Collibra Data Quality](https://www.collibra.com/)**  
  Data quality features integrated with Collibra’s data intelligence and governance platform.

- **[IBM InfoSphere QualityStage](https://www.ibm.com/)**  
  Long-standing enterprise data quality and standardization tooling within IBM’s data and integration portfolio.

- **[Data Ladder](https://dataladder.com/)**  
  Data quality and matching software focused on cleansing, deduplication, and data preparation.

## Open-Source GitHub Projects
- **[Great Expectations (GX Core)](https://github.com/great-expectations/great_expectations)**  
  Leading open-source data quality framework—expressive Expectations, validation suites, Data Docs, and broad integrations (Apache 2.0).

- **[Soda Core](https://github.com/sodadata/soda-core)**  
  Open-source data quality engine with human-readable SodaCL checks, scans, and support for many data sources.

- **[dbt tests / dbt Core](https://github.com/dbt-labs/dbt-core)**  
  Built-in and custom tests within dbt for schema, uniqueness, relationships, and accepted values—widely used as pipeline quality gates.

- **[Elementary](https://github.com/elementary-data/elementary)**  
  Open-source data observability package for dbt—anomaly detection, lineage, and monitoring on top of dbt projects.

- **[OpenMetadata](https://github.com/open-metadata/OpenMetadata)**  
  Open-source metadata platform with data quality tests, profiling, discovery, lineage, and governance features.

- **[Great Expectations plugins and expectations gallery](https://greatexpectations.io/expectations)**  
  Community and official libraries of reusable expectations for common data quality checks.

- **[Data contracts and open validation experiments](https://github.com/)**  
  Emerging open approaches to declarative data contracts enforced in CI/CD or at write time.

- **[Profiling open libraries (e.g., ydata-profiling)](https://github.com/ydataai/ydata-profiling)**  
  Open tools for exploratory data profiling and quality reports.

- **[SQL and pipeline assertion open helpers](https://github.com/)**  
  Lightweight open utilities for asserting row counts, null rates, and distribution checks inside orchestrators.

- **[Documentation and data-quality open playbooks](https://greatexpectations.io/docs)**  
  Guides for embedding Great Expectations, Soda Core, or dbt tests into modern data pipelines.

### Additional Strong Open-Source Options
- Starting with **Great Expectations** for the richest library of validation rules and documentation.
- Using **Soda Core** for readable YAML/SodaCL checks and fast adoption.
- Relying on **dbt tests + Elementary** when the stack is already dbt-centric.
- Adding **OpenMetadata** when quality needs to sit inside a broader open metadata and governance platform.
- Accepting that fully managed anomaly detection at warehouse scale, enterprise MDM integration, and polished incident workflows still favor commercial platforms (Monte Carlo, Anomalo, Bigeye, Ataccama, Informatica, Collibra, etc.).
- Focusing open-source efforts on shift-left validation, pipeline gates, and transparent ownership of quality rules.

**Frameworks for building custom systems**: Write Expectations/checks (GX or Soda) → run in CI/orchestrator → fail pipelines on critical breaches → monitor trends with Elementary or OpenMetadata → document in Data Docs or a catalog. Suitable for analytics engineering and data platform teams. Many enterprises still adopt commercial data quality/observability platforms for scale and automation.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Data quality tools influence production data products. Open-source deployments require careful rule design and operational ownership. This list is not data-governance
