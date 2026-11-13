# Soorykant Suman

Agentic AI engineer and data architect. I build multi-agent systems for clinics at [KeeMakr.ai](https://keemakr.ai), built a 10 TB HIPAA-grade clinical data platform from zero at NeuroDiscovery AI, and co-founded dotagent, the team behind [Nextpy](https://github.com/dot-agent/nextpy) (2.3k+ stars). B.Tech, IIT Kanpur.

## What I work on

- **Multi-agent systems in production.** Scheduling, intake, follow-up and copilot agents for medspa clinics on Vercel's eve framework, with human-in-the-loop approval before any patient-facing action and tracing in Langfuse.
- **AI-native data migration with compliance built in.** An AI agent proposes field mappings from PHI-safe profiles, a person approves, and deterministic code executes in checkpointed, idempotent chunks (Ibis on Polars/DuckDB, dlt, Dagster) into Medplum FHIR and a CRM, with identity resolution, reconciliation, delta runs and an audit log.
- **Agents that never see patient data.** A retention agent that turns a clinic's raw export into one row per patient, places every patient into outreach groups with deterministic rules and priority scoring, and records consent at commit; the model sees service names and counts only.
- **Tool layers for agents.** An AI-native CRM exposed as an MCP server with 169 operations behind a single operator agent, with tiered permissions for read, write and destructive actions.
- **Document intelligence.** PRD Loop: Docling-based ingestion of stakeholder documents, claim extraction, conflict detection with LLM adjudication, and an ordered decision queue that writes accepted decisions back to versioned PRDs in git.
- **Retrieval over messy clinical data.** Hybrid keyword + vector search on OpenSearch over physician notes, evaluated with RAGAS, used by 100+ clinicians across 14 practices.
- **Data platforms that hold at 3am.** ETL and CDC from four EHR systems into a unified warehouse, 5M+ patient records, migrated across Azure, GCP and AWS.

## Currently building

A public clinical referral and prior-authorization copilot: LangGraph state graph with checkpointing and human-approval interrupts, a tiered MCP server, hybrid retrieval, and an eval suite that gates CI. Repo goes public in late November 2026.

## Stack

Python · TypeScript · LangGraph · LangChain · CrewAI · MCP · Vercel eve · PydanticAI · Docling · FastAPI · PostgreSQL · Polars · DuckDB · Dagster · dlt · OpenSearch · PySpark · Airflow · Databricks · FHIR/Medplum · AWS · GCP · Azure · Langfuse

## Elsewhere

[LinkedIn](https://linkedin.com/in/soorykant-suman) · [X](https://x.com/SumanSoorykant) · soorykant04@gmail.com
