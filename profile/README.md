<!--
Public facts verified on 2026-09-20 against the canonical OpenLegalCore
component register, named public repositories and published release records.
Recheck those sources before changing a version, status, licence, repository,
evidence record or public/private boundary.
-->

# OpenLegalCore

**Open-source components. A private, reviewable system core.**

OpenLegalCore develops legal-AI infrastructure that keeps sources, processing
steps and human responsibility visible. The project is designed as one coherent
system and as a set of independently useful components.

The public project currently records **nine components**: four public, four
private and one planned. A private component record describes a capability and
its boundary; it does not offer source access. Each public component has its own
version, licence, evidence and release decision.

## Start here

1. [Review the complete component register](https://openlegalcore.org/components/)
   for the current system map and access state.
2. Choose a public repository below for source, technical documentation and the
   exact licence that governs that component.
3. Inspect the component's evidence and limitations before relying on a public
   capability claim.
4. Use [OpenLegalCore Discussions](https://github.com/orgs/OpenLegalCore/discussions)
   or the [published contribution paths](https://openlegalcore.org/#contribute)
   for public participation.

## Public components

### Legal OCR Pipeline · public v0.1.2

An auditable, resumable OCR building block for image-based legal documents,
with deterministic controls and an offline page-level review tool.

[Repository](https://github.com/OpenLegalCore/legal-ocr-pipeline) ·
[Component record](https://openlegalcore.org/components/legal-ocr-pipeline/) ·
[Recorded acceptance](https://github.com/OpenLegalCore/legal-ocr-pipeline/blob/v0.1.2/docs/RECORDED_ACCEPTANCE.md) ·
[v0.1.2 source](https://github.com/OpenLegalCore/legal-ocr-pipeline/tree/v0.1.2) ·
[Apache-2.0 licence](https://github.com/OpenLegalCore/legal-ocr-pipeline/blob/v0.1.2/LICENSE)

**Boundary:** Code, documentation, tests, offline review tooling and the bounded
acceptance record are public. The source filing, OCR output and detailed review
artefacts are not public.

### Slovenian Legislation Pipeline · public v0.1.0

A source-available ingestion and integrity-maintenance pipeline for PISRS
legislation, with PostgreSQL as authoritative structured state and Qdrant as a
derived semantic index.

[Repository](https://github.com/OpenLegalCore/slovenia-pisrs-ingest) ·
[Component record](https://openlegalcore.org/components/slovenian-legislation/) ·
[v0.1.0 source](https://github.com/OpenLegalCore/slovenia-pisrs-ingest/tree/v0.1.0) ·
[BUSL-1.1 licence](https://github.com/OpenLegalCore/slovenia-pisrs-ingest/blob/v0.1.0/LICENSE)

**Boundary:** The repository does not include PISRS credentials, PISRS data,
legislative text, database or vector snapshots, managed infrastructure, a
retrieval interface or a user interface.

### Slovenian Case Law Pipeline · public v0.1.7

A source-available ingestion and integrity-maintenance pipeline for Slovenian
case law, with PostgreSQL as authoritative state and a derived Qdrant semantic
index.

[Repository](https://github.com/OpenLegalCore/slovenia-sodnapraksa-ingest) ·
[Component record](https://openlegalcore.org/components/slovenian-case-law/) ·
[v0.1.7 release](https://github.com/OpenLegalCore/slovenia-sodnapraksa-ingest/releases/tag/v0.1.7) ·
[BUSL-1.1 licence](https://github.com/OpenLegalCore/slovenia-sodnapraksa-ingest/blob/v0.1.7/LICENSE)

**Boundary:** The repository does not include source credentials, court
decisions, source records, data snapshots, embedding access, managed
infrastructure, a retrieval interface or legal advice.

### OpenLegalCore Word Connector · public v0.1.0-beta.1

An Apache-2.0 Microsoft Word task-pane add-in for researching Slovenian
legislation and case law through an operator-configured compatible backend.

[Repository](https://github.com/OpenLegalCore/olc-word-connector) ·
[Component record](https://openlegalcore.org/components/word-connector/) ·
[v0.1.0-beta.1 release](https://github.com/OpenLegalCore/olc-word-connector/releases/tag/v0.1.0-beta.1) ·
[Apache-2.0 licence](https://github.com/OpenLegalCore/olc-word-connector/blob/v0.1.0-beta.1/LICENSE)

**Boundary:** This is a source-only beta verified in Word for the web. It does
not include a hosted legal-research service, public backend, legal database,
AppSource listing or access to OpenLegalCore's private infrastructure.

## How to read the public record

- The [project website](https://openlegalcore.org/) is the current public record
  for the system narrative, component status, access state, governance and
  roadmap.
- A component repository controls its source, technical documentation, exact
  licence, operational limits and component-specific security policy.
- Git tags and GitHub Releases identify published versions. A branch, plan,
  private preview or component name alone is not a release.

## Work in public

- Use [OpenLegalCore Discussions](https://github.com/orgs/OpenLegalCore/discussions)
  for public questions, ideas, proposals and project-wide method or governance
  topics.
- Use the affected public repository for reproducible bugs, focused issues and
  code contributions.
- Read the [Community home](https://github.com/OpenLegalCore/community) for
  contribution guidance, governance and the Code of Conduct.
- Legal, methodological and source review are welcome through the
  [public contribution paths](https://openlegalcore.org/#contribute).

## Security

Do not disclose vulnerabilities, active incidents, credentials, private legal
documents or other sensitive information in public issues or Discussions. Use
the [project-wide private reporting policy](https://openlegalcore.org/security/)
or a component's private vulnerability-reporting channel when available.

## Public boundary

The public repositories are not the complete OpenLegalCore system. They do not
publish the private system core, legal-data snapshots, credentials, private
documents, managed infrastructure or a generally available product. Code,
data, documentation, website content and brand rights remain separate; the
exact licence in each repository controls its licensed work.

[English website](https://openlegalcore.org/) ·
[Slovensko spletišče](https://openlegalcore.si/) ·
[Roadmap](https://openlegalcore.org/roadmap/) ·
[Governance](https://openlegalcore.org/governance/) ·
[Security](https://openlegalcore.org/security/)
