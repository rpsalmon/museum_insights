# MUSEUM INSIGHTS 

Data pipeline and dashboard exploring how public fundings, exhibitions, transit ridership, museum visitation relate across NYC museums

> Status: under construction [Roadmap](#roadmap)

## Purpose

Does NYC cultural funding have any influence on the art being acquired for public collections and do those acquisitions and subsequent exhibits have an influence on visition and transit ridership.

## Technology

| Layer | Tool |
|---|---|
* Orchestration : Airflow
* Transformation : dbt
* Storage : DuckDB (local), Postgres (cloud)
* Language : Python 3.1x
* Dashboard : Streamlit

## Architechture


## Data Sources

See ['docs/data_sources.md'](docs/data_sources.md) for a full inventory (source, granularity, update cadence)

## Directory

museum_insights/
├── airflow/
├── dbt/
├── src/museum_insights/
├── sql/adhoc/
├── streamlit_app/
├── data/
├── docs/
├── notebooks/

## Getting Started

## Running against Postgres vs DuckDB


## Roadmap

- [x] Phase 0 - repo, tooling, data model, docs
- [ ] Phase 1 - source ingestion
- [ ] Phase 2 - dbt staging + mart models
- [ ] Phase 3 - Airflow DAGs
- [ ] Phase 4 - Streamlit
- [ ] Phase 5 - deploy