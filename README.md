# Emmanuel Beristain Guzman

## Logistics Engineer | Junior Supply Chain & Data Analyst

**Transport operations background • SQL • Python • dbt • Dashboards • Data quality**

I am a logistics engineer and former **Transport Fleet Coordinator** building toward
junior roles in supply chain analytics, operations analysis, data analysis, and BI.
My formal logistics experience provides the domain context; the repositories below
are independent, executable work samples rather than corporate or production work.

## Evidence in 60 seconds

| A manager may ask | Direct evidence | Transferable capability |
|---|---|---|
| KPI's | [Control Tower issue #6](https://github.com/net421/supply-chain-operations-control-tower/issues/6) → [tested PR #7](https://github.com/net421/supply-chain-operations-control-tower/pull/7) → [manager case study](https://github.com/net421/supply-chain-operations-control-tower/blob/main/docs/manager_case_study.md) | Metric governance, SQL/Python debugging, and root-cause validation |
|urn operational records into a usable report? | [Logistics issue #3](https://github.com/net421/logistics-dashboard/issues/3) → [export PR #4](https://github.com/net421/logistics-dashboard/pull/4) → [verified screenshot](https://github.com/net421/logistics-dashboard/blob/main/docs/logistics-dashboard.png) | KPI design, filtering, visualization, and operational communication |
| build trustworthy reporting models? | [dbt issue #3](https://github.com/net421/dbt-analytics-engineering-lab/issues/3) → [evidence PR #4](https://github.com/net421/dbt-analytics-engineering-lab/pull/4) → [validation summary](https://github.com/net421/dbt-analytics-engineering-lab/blob/main/validation/dbt_validation_summary.md) | Dimensional modeling, reusable SQL, tests, documentation, and lineage |
| receive a change request and prove the result? | The linked issues and PRs document the problem, acceptance criteria, implementation, tests, and limitations | Ticket-based delivery, regression testing, and clear handoff |

## Featured work samples

### [Supply Chain Operations Control Tower](https://github.com/net421/supply-chain-operations-control-tower)

**Business problem:** service, fulfillment, inventory, transportation, and planning
metrics can disagree when their grain or definitions are unclear.

**Delivered:** a one-command local pipeline over 2,400 synthetic orders and 5,928
order lines, with independent pandas and DuckDB implementations.

**Evidence:** eight reconciled SQL/Python metrics, 38 automated data-quality checks,
eleven regression tests, exception outputs, and a bounded executive summary.

**Transferable to:** KPI reconciliation, recurring operational reporting, carrier or
supplier investigation, and data-quality troubleshooting.

### [Logistics KPI Dashboard](https://github.com/net421/logistics-dashboard)

**Business problem:** operations teams need service and cost measures that respond
consistently to the same period, supplier, and route selections.

**Delivered:** a Streamlit/Plotly application calculated from 996 deterministic
synthetic orders, with five governed KPIs and operational observations.

**Evidence:** verified dashboard image, known-result KPI fixtures, input contracts,
sixteen tests, application smoke coverage, and GitHub Actions.

**Transferable to:** operational dashboards, recurring KPI reporting, exception
prioritization, and communication with non-technical stakeholders.

### [dbt Analytics Engineering Lab](https://github.com/net421/dbt-analytics-engineering-lab)

**Business problem:** dashboards need consistent, documented models between raw
operational sources and business-facing metrics.

**Delivered:** deterministic source generation plus staging, intermediate, fact,
dimension, operations, and customer models on dbt and DuckDB.

**Evidence:** 20 models, a Type 2 snapshot, two exposures, 71 passing data tests,
98.35% unit-weighted fill reconciliation, generated documentation, and CI evidence.

**Transferable to:** analytics model maintenance, SQL transformation, lineage,
regression testing, and reliable BI datasets.

## How the skills transfer

| Work activity | Demonstrated approach |
|---|---|
| Define a KPI | Document formula, grain, denominator, unit, and limitations |
| Investigate an exception | Trace source rows through transformations to the reported result |
| Change a business rule | Update both implementations, tests, documentation, and reconciliation |
| Prepare an operational review | Separate observations, possible actions, assumptions, and missing context |
| Maintain recurring reporting | Use deterministic runs, validation contracts, regression tests, and CI |

## Tools demonstrated

- **Supply chain:** OTIF, on-time delivery, fill rate, inventory, transportation,
  forecast, service, and cost metrics.
- **SQL and modeling:** joins, CTEs, aggregations, window functions, dimensional
  models, marts, and reconciliation queries.
- **Python:** pandas analysis, validation, KPI calculation, reporting, pytest,
  Streamlit, and Plotly.
- **Analytics engineering:** dbt models, snapshots, tests, documentation, lineage,
  exposures, DuckDB, Git, and GitHub Actions CI.

## Scope

The featured datasets are synthetic and the projects run locally. They demonstrate
junior-level implementation and explainable work samples, not enterprise production
experience, real customer impact, Power BI/Tableau delivery, SAP integration, cloud
operations, or years of professional data-platform ownership.

AI tools assisted implementation and review. I remain responsible for the problem
definition, metric choices, validation, testing, corrections, and explanation of the
final work, and I can reproduce and modify the featured projects.
