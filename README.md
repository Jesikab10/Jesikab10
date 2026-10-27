## Hi, I'm Jesika

**Solutions Architect | Workflow Automation | AI Integration Engineering**

I design and automate complex workflows across systems, services, and data pipelines.

10+ years across broadcast, video, and media delivery workflows.

Experience across international and Latin American distribution environments, working with complex
delivery chains, technical validation, metadata requirements, and interoperability between systems.

My background in broadcast engineering taught me to orchestrate multi-stage processes with strict
technical requirements, multiple dependencies, and real-world failure modes. I apply that same
engineering discipline across domains, from media pipelines to data automation, cloud services,
and AI-powered systems.

I use AI coding assistants as primary implementation tools, combining fast iteration with engineering
best practices: tested, reviewed, and secure by design.

### How I work

- **Start from the actual problem.** Onboard into the real problem statement and business goals,
  then design and build the solution that meets them.
- **Understand the real system.** When there is an existing system, read the code, inspect the
  schema, validate actual payloads, and identify constraints before deciding how to build.
- **Ship fast, harden where it matters.** Validate assumptions early, iterate quickly, and add
  reliability, testing, and safeguards before it reaches production.
- **Design for failure.** Idempotent operations, selective retries, explicit states, and traceable
  execution.
- **Integrate AI with purpose.** Agents and LLMs where they add measurable value, with grounded
  retrieval, evaluations, and safeguards.
- **Keep control of production systems.** Least-privilege access, human approval for consequential
  actions, and controlled deployments.

### Selected work

#### Video Processing Orchestrator - production system, private code

[Architecture overview](https://github.com/Jesikab10/video-pipeline-architecture/blob/main/docs/airflow-orchestrator/ARCHITECTURE.md)

A cloud-based orchestration system for media processing and delivery, coordinating raw-footage
ingestion, technical validation, timeline-based trimming and assembly, and publication to an
external media asset library.

- **Orchestration:** Apache Airflow on Google Cloud Composer, coordinating multi-stage media workflows.
- **Media engineering:** FFmpeg, GPU-accelerated NVENC processing, CPU workloads, and technical
  quality-control steps.
- **Integration layer:** Cloud Run services, PostgreSQL, project-management APIs, REST-based
  asset-library integration, and Slack notifications.
- **Workflow reliability:** Explicit states, controlled retries, and centralized data ownership.

The goal is to make complex media operations repeatable and reliable across systems, while keeping
processing, orchestration, and integration responsibilities clearly separated.

#### media-jobs-mcp - public project

[MCP server and LangGraph agent](https://github.com/Jesikab10/media-jobs-mcp)

An AI-assisted media-job triage system that applies production-oriented integration patterns to
agent workflows.

- MCP tools and API integrations for media-job operations.
- OAuth scopes, rate-limit handling, and idempotent writes.
- Human approval before consequential actions.
- Retrieval-augmented generation (RAG) with grounded citations.
- Evaluation scenarios for prompt injection and data leakage.

The project explores how AI agents can interact with operational systems while respecting their
security boundaries and existing business rules.

### Broadcast & Media Engineering

https://www.linkedin.com/in/jesika-berroteran-b16a3a32/

- **Video and transport:** MPEG-2, H.264/AVC, H.265/HEVC, SDI, RTP, HLS, and DVB.
- **Media packaging and metadata:** CableLabs specifications, ADI, asset metadata, and delivery
  requirements.
- **Subtitles and accessibility:** DVB subtitles, TTML, and WebVTT.
- **Processing and quality control:** FFmpeg, hardware-accelerated encoding, automated validation,
  and media-analysis tools.
- **Workflow integration:** Media processing, asset-management systems, scheduling, and delivery
  automation.

This experience shapes how I approach engineering beyond media: understand the domain, map the
dependencies, orchestrate the steps, and choose the right level of automation and control for the
problem.

### Stack

| Area | Tools |
|---|---|
| AI & Agent Engineering | MCP, LangGraph, RAG, LLM evaluations, Claude Code |
| Backend & Data | Python, SQL, PostgreSQL, TypeScript, REST APIs |
| Orchestration & Cloud | Apache Airflow, Google Cloud Composer, Cloud Run, Cloud SQL, Google Cloud Storage |
| Media Engineering | FFmpeg, NVENC, video codecs, media QC, metadata and packaging workflows |
| Delivery & Infrastructure | Docker, GitHub Actions, CI/CD, automated testing |
