# Frontier AI hiring signals — 2026-11-04 snapshot

A small, reproducible summary of role-title signals from official applicant-tracking-system boards. This snapshot covers 29 configured boards and 6,864 open postings fetched on 2026-11-04.

The data answers a narrow question: how many engineering postings had titles matching four role families? It does **not** estimate the total number of people being hired, and title matching can miss relevant work under broader titles.

## Snapshot

| Role family | Matching engineering roles | Companies represented |
|---|---:|---:|
| Search | 22 | 4 |
| Agents | 21 | 3 |
| Hardware / silicon | 19 | 3 |
| Reinforcement learning | 4 | 1 |

See [`data/role_family_summary.csv`](data/role_family_summary.csv) for the machine-readable summary and [`data/company_role_counts.csv`](data/company_role_counts.csv) for company-level counts.

## Method

- Source: official ATS boards only; 29 boards configured in the source project.
- Snapshot time: 2026-11-04, between 02:16 and 02:19 UTC.
- Scope: engineering roles whose titles matched each report's declared terms.
- Deduplication: each posting is counted once per role-family scan.
- Description coverage: all 66 matched postings had descriptions available for the underlying technique analysis.
- Caveat: the four scans overlap. Do not sum their counts to infer a unique-role total.

## Explore the related guides

- [Frontier AI job-market tracker](https://frontierrehearsal.com/jobs/market)
- [Search engineering role guide](https://frontierrehearsal.com/jobs/roles/search)
- [Data infrastructure role guide](https://frontierrehearsal.com/jobs/roles/data-infrastructure)

## License and independence

The aggregated tables in this repository may be reused with attribution. Job postings remain the property of their respective publishers. Frontier Rehearsal is independent and is not affiliated with the companies referenced in the data.

