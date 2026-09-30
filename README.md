# Awesome-Data-Contracts-Platform

# Top Data Contracts Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Schema Agreements, Quality SLAs, Producer–Consumer Contracts, Stream/API Contracts & Enforceable Data Promises*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Data Contracts**. These systems formalize agreements between data producers and consumers—covering schema, semantics, quality expectations, SLAs, and sometimes security—so breaking changes and quality regressions are detected and governed.

**Examples** include OpenMetadata, DataHub, Atlan, Secoda, Datafold, Monte Carlo, Soda, Confluent Stream Governance, AsyncAPI Studio, Redpanda Console, Sifflet, Metaplane, and Elementary (the category leaders and closely related tooling).

**Open-source emphasis**: Data contracts have strong open foundations. **OpenMetadata**, **DataHub**, **Soda Core**, **Elementary**, **Great Expectations**, **AsyncAPI**, and **OpenLineage** provide practical contract definition and enforcement. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[OpenMetadata (Managed / Collate)](https://open-metadata.org/)**  
  Open-source-rooted platform with first-class data contracts (schema, quality, SLA, semantics) and collaborative UI.

- **[DataHub (Managed / Acryl)](https://datahubproject.io/)**  
  Metadata platform with contract-style assertions, schema governance, and real-time metadata for large estates.

- **[Atlan](https://atlan.com/)**  
  Active metadata and data-product platform used to define ownership, contracts, and collaboration around assets.

- **[Secoda](https://www.secoda.co/)**  
  AI-assisted catalog and knowledge layer that supports documentation and contract-like agreements for data assets.

- **[Datafold](https://www.datafold.com/)**  
  Data quality and diff platform often used to validate changes against expected contracts before promotion.

- **[Monte Carlo](https://www.montecarlodata.com/)**  
  Data observability platform that monitors freshness, volume, schema, and quality—frequently paired with contract programs.

- **[Soda (Cloud)](https://www.soda.io/)**  
  Data quality and contract testing platform with commercial cloud offerings on top of open Soda Core.

- **[Confluent Stream Governance](https://www.confluent.io/)**  
  Schema Registry and stream governance capabilities for Kafka-centric data contracts and compatibility rules.

- **[AsyncAPI Studio / tooling](https://www.asyncapi.com/)**  
  Tooling around the AsyncAPI specification for event-driven API and stream contracts.

- **[Redpanda Console](https://www.redpanda.com/)**  
  Console and governance features for streaming platforms, supporting schema and topic-level contracts.

- **[Sifflet](https://www.siffletdata.com/)**  
  Data observability platform used to monitor and enforce quality expectations aligned with data contracts.

- **[Metaplane](https://www.metaplane.dev/)**  
  Data observability focused on warehouse monitoring and anomaly detection supporting contract-style guarantees.

- **[Elementary](https://www.elementary-data.com/)**  
  dbt-native data observability with open core; widely used for tests and contract-like checks in transformation layers.

## Open-Source GitHub Projects
- **[OpenMetadata](https://github.com/open-metadata/OpenMetadata)**  
  Open-source data catalog and governance platform with native **data contracts** (schema, quality, SLA, semantics) and UI-driven collaboration.

- **[DataHub](https://github.com/datahub-project/datahub)**  
  Open-source metadata platform supporting assertions, schema evolution policies, and contract-style governance.

- **[Soda Core](https://github.com/sodadata/soda-core)**  
  Open-source data quality and contract testing framework—define expectations as code and run them in pipelines.

- **[Elementary](https://github.com/elementary-data/elementary)**  
  Open-source dbt-native observability and testing framework for data quality and contract-aligned checks.

- **[Great Expectations](https://github.com/great-expectations/great_expectations)**  
  Open-source data validation framework used to encode expectations that act as enforceable data contracts.

- **[AsyncAPI](https://github.com/asyncapi)**  
  Open specification and tooling for event-driven APIs—schemas and contracts for message-based systems.

- **[OpenLineage](https://github.com/OpenLineage/OpenLineage)**  
  Open standard for lineage that complements contracts by showing producer–consumer dependencies.

- **[Data Contract CLI / community specs](https://github.com/)**  
  Open CLI and YAML/JSON-based data contract formats used by developer-led teams.

- **[Confluent / community Schema Registry](https://github.com/confluentinc/schema-registry)**  
  Open Schema Registry components for Avro/Protobuf/JSON schema contracts on Kafka topics.

- **[Documentation and OpenMetadata / Soda playbooks](https://docs.open-metadata.org/)**  
  Guides for defining, approving, and validating data contracts in open platforms.

### Additional Strong Open-Source Options
- Defining and enforcing contracts natively in **OpenMetadata**.
- Encoding quality and schema expectations with **Soda Core**, **Elementary**, or **Great Expectations**.
- Managing stream and event contracts with **AsyncAPI** and Schema Registry.
- Accepting that enterprise collaboration UIs, multi-tool observability packaging, and fully managed enforcement still lead many teams to commercial layers (Atlan, Monte Carlo, Soda Cloud, Datafold, etc.).
- Focusing open-source efforts on portable contract definitions and pipeline-native validation.

**Frameworks for building custom systems**: Define contracts in OpenMetadata or as YAML → validate with Soda/Elementary/GE in CI and production → track lineage with OpenLineage → govern schemas for streams via Schema Registry/AsyncAPI. Suitable for modern data teams. Larger organizations often combine open contracts with commercial observability and catalog products.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Data contracts improve reliability but do not replace governance, security, or legal agreements. Open-source enforcement depends on correct pipeline integration. This list is not operational or legal advice.

---
**Made for data engineers, analytics engineers, and open data platform advocates.**
Let's keep producer–consumer agreements explicit, testable, and as open as practical.
