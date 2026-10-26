# DataHub Cookbook

<!-- ZQM-START -->
<!-- markdownlint-disable MD033 -->
<p align="center">
  <strong>ZQM Computing — Geospatial Engineering & Scientific Computing</strong><br>
  <a href="https://github.com/ZQM-Computing">ZQM Computing</a>
</p>
<!-- markdownlint-enable MD033 -->
<!-- ZQM-END -->

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A **DataHub cookbook** — metadata catalog and lineage over data platforms. Queued in wave-11 (Node-3 hub set). Patterns are planned from the design, not yet from fleet runs. It is intended for Data platform engineers who catalog datasets and trace lineage. Validate each pattern against your own data, software versions, and operating environment before adopting it.

## Repository role and status

**Status:** Active, public — seeding. Pattern passes land in follow-up work from fleet-verified setups; the tables below list what is planned, not what is already written.

**What this repository is:** DataHub patterns — see the table below.

**What it contributes:** Part of the ZQM Computing geospatial portfolio. The umbrella index for the series is [geospatial-cookbooks](https://github.com/ZQM-Computing/geospatial-cookbooks).

**Standing:** This repository is maintained independently. Automated checks cover only the paths and environments configured in its workflows; they do not establish production readiness or operational certification.

## Who this is for

Data platform engineers who catalog datasets and trace lineage.

## Prerequisites

- DataHub via Docker
- Postgres or DuckDB as a source platform
- A browser for the UI passes

## Patterns (planned)

| # | Example | What it will demonstrate |
|---|---------|--------------------------|
| 01 | `01-first-ingestion` | Ingesting a database source into the catalog |
| 02 | `02-lineage` | Lineage from ingestion and transformation jobs |
| 03 | `03-search` | Searching datasets, owners, and tags |
| 04 | `04-api-notes` | Driving ingestion and search through the API |

## Repository layout

```text
datahub-cookbook/
├── examples/          # pattern passes, landing in follow-up work
├── README.md
└── LICENSE
```

## Roadmap

- First pattern pass: the first two table rows
- Second pass: the remaining rows, from fleet-verified setups

## Contributing

A contributing guide lands with the first pattern pass. Report security issues to <zqmcomputing@gmail.com> — please do not open a public issue for those.

## More from this series

- [dbt-cookbook](https://github.com/ZQM-Computing/dbt-cookbook) — SQL transformations, models, and tests on Postgres
- [dlt-cookbook](https://github.com/ZQM-Computing/dlt-cookbook) — ELT pipelines from Python into Postgres and DuckDB
- [geonetwork-cookbook](https://github.com/ZQM-Computing/geonetwork-cookbook) — Spatial metadata catalogs, harvesting, and CSW search
