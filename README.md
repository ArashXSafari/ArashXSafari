<p align="center">
  <img src="./assets/hero.svg" width="100%" alt="Arash Safari — Search, Ranking & Decision Systems" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/arashsafari95/">LinkedIn</a>
  &nbsp;·&nbsp;
  <a href="mailto:ArashXSafari@gmail.com">Email</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/ArashXSafari">GitHub</a>
</p>

## What I work on

I build machine-learning and search systems for marketplace products, with experience spanning ranking, personalization, experimentation, decision systems, and large-scale data infrastructure.

Over 6+ years, my work has progressed from analytics and data engineering into search/ranking engineering, technical leadership, and senior individual-contributor ML work. I am strongest at the boundary between modeling and systems engineering: turning ambiguous product problems into measurable formulations, production architectures, and auditable experiments.

| Search & Ranking | Decision Systems | Experimentation | ML & Data Systems |
| --- | --- | --- | --- |
| Relevance, ranking, map ranking, personalization | Constrained optimization, marketplace objectives, feedback loops | A/B testing, experiment integrity, online/offline evaluation | Spark, Kafka, batch/stream processing, inference, observability |

## Selected work

<table>
<tr>
<td width="33%" valign="top">

### Neshaneh

Geospatial data reconstruction and validation for Iranian administrative geography using official maps, automated extraction, georeferencing, topology checks, coverage-gap detection, and human review.

`Python` `GIS` `FastAPI` `React` `GeoJSON`

**Status:** preparing a public version.

</td>
<td width="33%" valign="top">

### Snowplow Validator

Event-contract testing and validation system for analytics pipelines: test cases, automated execution, Snowplow Micro integration, findings, regression detection, auditability, and a review UI.

`Python` `FastAPI` `PostgreSQL` `React` `Playwright`

**Status:** preparing a public version.

</td>
<td width="33%" valign="top">

### [Satellite ADCS Simulation](https://github.com/ArashXSafari/Satellite-ADCS-Simulation)

Spacecraft attitude-determination and control simulation from my aerospace/control background.

`Python` `Control Systems` `Simulation`

</td>
</tr>
</table>

## Systems I’ve built

```text
Data collection
      ↓
Processing & validation
      ↓
Modeling / ranking / optimization
      ↓
Experimentation
      ↓
Production & monitoring
      ↓
Better product decisions
```

Selected examples from production and applied work:

- Built and operated ranking systems serving approximately **500K impressions/day** across roughly **20K accommodations**.
- Solely designed and implemented **MapRank**, from an interactive algorithm sandbox through the production Go search-service module for viewport-aware pin ranking, collision handling, and adaptive clustering.
- Built a live **guarantee-ranking controller** translating marketplace financial state into constrained ranking interventions using hourly PySpark optimization, auditable decision state, and Kafka publication.
- Designed booking/close hazard and survival-style formulations connecting exposure, booking probability, and expected marketplace P&L.
- Built personalization scoring infrastructure with Spark Structured Streaming and Kafka around inherited user/item representations.
- Revived and expanded Snowplow event-data infrastructure, including impression-level instrumentation used for ranking and experimentation; pipelines processed approximately **10 GB/day** into Hive.
- Led Data and Ranking teams for approximately **14 months**, covering technical direction, roadmap planning, hiring, mentoring, reviews, stakeholder management, and delivery.

## Core stack

**Languages** — Python, SQL, Go  
**ML** — ranking, recommender systems, personalization, survival/hazard modeling, gradient boosting, scikit-learn  
**Data & distributed systems** — Apache Spark, Kafka, Airflow, Hive/HDFS, Delta Lake, ClickHouse, Elasticsearch, Snowplow  
**Services** — FastAPI, GraphQL, REST APIs, batch inference, model serving  
**Engineering** — Docker, Linux, Git, CI/CD, production monitoring

## Background

B.Sc. in Aerospace Engineering from K. N. Toosi University of Technology. My control and systems background continues to influence how I approach online decision-making, ranking, and marketplace optimization problems.

> I’m most interested in the boundary between machine learning and systems engineering: formulating the right problem, building the infrastructure, and operating it in the real world.
