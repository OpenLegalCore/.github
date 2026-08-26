<!--
Public facts verified on 2026-08-26 against the canonical OpenLegalCore Component records
and the named public repositories. Recheck both sources before changing a version, status,
licence, repository, evidence path or public/private boundary.
-->

# OpenLegalCore

**Open-source, traceable and human-verifiable infrastructure for legal AI.**

The law is too important for black-box systems.

OpenLegalCore develops reusable legal-tech components around a private, jurisdiction-aware system
core. Public repositories are released component by component, with their status, evidence, rights
and limits stated separately.

## Start here

1. [See every Component and its current status](https://openlegalcore.org/components/).
2. Choose a public repository below and read its versioned documentation and exact licence.
3. [Inspect the evidence and its limits](https://openlegalcore.org/evidence/) where a separate public record exists.
4. [Join project-wide Discussions](https://github.com/orgs/OpenLegalCore/discussions) or [choose a contribution path](https://openlegalcore.org/#contribute).

## Public components

### Legal OCR Pipeline · public v0.1.2

An auditable, resumable OCR building block for image-based legal documents, with deterministic
controls and an offline page-level review tool.

[Repository](https://github.com/OpenLegalCore/legal-ocr-pipeline) ·
[Component record](https://openlegalcore.org/components/legal-ocr-pipeline/) ·
[Acceptance evidence](https://openlegalcore.org/evidence/ocr-acceptance/) ·
[v0.1.2 source](https://github.com/OpenLegalCore/legal-ocr-pipeline/tree/v0.1.2) ·
[Apache-2.0 licence](https://github.com/OpenLegalCore/legal-ocr-pipeline/blob/v0.1.2/LICENSE)

**Boundary:** Code, documentation, tests, offline review tooling and the acceptance method are
public. The source filing, OCR output and detailed review artefacts are not public.

### Slovenian Legislation Pipeline · public v0.1.0

A source-available ingestion and integrity-maintenance pipeline for PISRS legislation, with
PostgreSQL as authoritative structured state and Qdrant as a derived semantic index.

[Repository](https://github.com/OpenLegalCore/slovenia-pisrs-ingest) ·
[Component record](https://openlegalcore.org/components/slovenian-legislation/) ·
[v0.1.0 source](https://github.com/OpenLegalCore/slovenia-pisrs-ingest/tree/v0.1.0) ·
[BUSL-1.1 licence](https://github.com/OpenLegalCore/slovenia-pisrs-ingest/blob/v0.1.0/LICENSE)

**Boundary:** The repository does not include PISRS credentials, PISRS data, legislative text,
PostgreSQL or Qdrant snapshots, managed infrastructure, a retrieval interface or a user interface.

### Slovenian Case Law Pipeline · public v0.1.7

A source-available ingestion and integrity-maintenance pipeline for Slovenian case law, with
PostgreSQL as authoritative state and a derived Qdrant semantic index.

[Repository](https://github.com/OpenLegalCore/slovenia-sodnapraksa-ingest) ·
[Component record](https://openlegalcore.org/components/slovenian-case-law/) ·
[v0.1.7 release](https://github.com/OpenLegalCore/slovenia-sodnapraksa-ingest/releases/tag/v0.1.7) ·
[BUSL-1.1 licence](https://github.com/OpenLegalCore/slovenia-sodnapraksa-ingest/blob/v0.1.7/LICENSE)

**Boundary:** The repository does not include source credentials, court decisions, source records,
data snapshots, embedding access, managed infrastructure, a retrieval interface or legal advice.

## Work in public

- Use [OpenLegalCore Discussions](https://github.com/orgs/OpenLegalCore/discussions) for public questions, ideas, proposals and project-wide method or governance topics.
- Use the affected public repository for reproducible bugs, focused issues and code contributions.
- Read the [Community home](https://github.com/OpenLegalCore/community) for contribution guidance, governance and the Code of Conduct.
- Legal, methodological and source review are welcome through the [public contribution paths](https://openlegalcore.org/#contribute).

## Security

Do not disclose vulnerabilities, active incidents, credentials, private legal documents or other
sensitive information in public issues or Discussions. Use the
[private security-reporting policy](https://openlegalcore.org/security/).

## Public boundary

The public repositories are not the complete OpenLegalCore system. They do not publish the private
system core, legal-data snapshots, credentials, private documents, managed infrastructure or a
generally available product. Code, data, documentation, website content and brand rights remain
separate; the exact licence in each repository controls its licensed work.

[Project website](https://openlegalcore.org/) ·
[Roadmap](https://openlegalcore.org/roadmap/) ·
[Governance](https://openlegalcore.org/governance/) ·
[Security](https://openlegalcore.org/security/)
