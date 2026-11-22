<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="Valantis Chatzimagkas, full-stack engineer" src="assets/banner-light.svg" width="100%">
</picture>

**Dossenheim, Germany** · [LinkedIn](https://www.linkedin.com/in/valantischatzimagkas)

Full-stack engineer at **ARC Intelligence**, building product features and agentic AI functionality for a multi-tenant finance platform. Before that, six years of industrial IoT middleware, data pipelines and ETL. I work end to end, from ingestion and APIs to the UI people use.

### Experience

**ARC Intelligence** · Full-stack engineer · 2026–present<br><sub>Multi-tenant B2B finance platform · Django REST, Next.js, AWS</sub>

- Agent-generated dashboards and charts, agent artifacts, filtering and chat-interface features
- Building human-in-the-loop interactions so users can step in while the agent works
- Contributed to prompt evals that check agent behaviour before changes ship
- Authentication and user management on AWS Cognito; database migrations

**KISTERS** · Software engineer · 2025–2026<br><sub>In-house ETL framework</sub>

- Refactored existing pipelines
- Integrated forecasting models
- Wrote integration tests for the framework

**Future Intelligence** · Software engineer · 2020–2025<br><sub>Industrial IoT and data platform</sub>

- Data pipelines in Prefect that compute metrics and KPIs and feed decision-support systems
- Features for the company's data platform
- IoT middleware for industrial setups over MQTT and OPC UA
- Weather-data analysis, plus tooling for data wrangling, visualisation and Bash automation

### Toolbox

- **Backend:** Python (Django REST, FastAPI, SQLAlchemy), Go
- **Frontend:** TypeScript, React, Next.js
- **Data:** PostgreSQL, PostGIS, TimescaleDB, InfluxDB, Redis, MongoDB, Prefect
- **IoT:** MQTT, OPC UA
- **AI:** OpenAI SDK, agent tooling, evals
- **Infra:** AWS, Docker, GitHub Actions, Bash

### Selected projects

**[synaptic-hive](https://github.com/ValantisChatzimagkas/synaptic-hive)**<br><sub>Python · FastAPI · TimescaleDB · Redis Streams</sub><br>Industrial IoT telemetry with a switchable sync/async ingestion path: an at-least-once worker that is idempotent on redelivery.

**[brew-room-monitor](https://github.com/ValantisChatzimagkas/brew-room-monitor)**<br><sub>Python · FastAPI · PostgreSQL · Next.js · sensor devices</sub><br>End-to-end monitoring for brewing rooms: devices push readings with hashed, revocable tokens, and a server-rendered Next.js UI consumes types generated from the API's OpenAPI contract.

**[mcp-tool-calling-benchmark](https://github.com/ValantisChatzimagkas/mcp-tool-calling-benchmark)**<br><sub>Python · OpenAI-compatible APIs · LLM evaluation</sub><br>Measures how reliably models call MCP-style tools, with replicated runs, Wilson intervals and an explicit statement of what it does not test.

**[Road-Archiver](https://github.com/ValantisChatzimagkas/Road-Archiver)**<br><sub>Python · FastAPI · PostGIS</sub><br>Versioned road networks: updates never delete, and any network can be queried exactly as it was at a given instant.

My day-to-day work is in private repositories; these are smaller projects where I work through ideas in the open.
