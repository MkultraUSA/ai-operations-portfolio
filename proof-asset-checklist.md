# Proof Asset Checklist

Use this as the collection list before publishing the portfolio publicly.

## Context Forge Required Assets

### Screenshots

- Codex task showing `get_context` retrieving scoped project memory
- Context Forge vault folder in Nextcloud
- Sanitized `CONTEXT-FORGE-V1.md` snapshot
- Handoff record showing outcome, decisions, changed artifacts, verification, and next actions
- Fresh task resuming from prior context without manual recap
- GitHub repository landing page once public
- Commit history showing implementation progress
- Optional: Hermes reading `/opt/data/ContextForge/CONTEXT-FORGE-V1.md`

### Sanitized Text Artifacts

- One real handoff with secrets and private paths removed
- One project context excerpt showing scoped memory
- One before/after example:
  - Before: "new AI session starts with no project state"
  - After: "new AI session retrieves project state and continues with next action"
- One short runbook excerpt for how another agent should use Context Forge

### Diagrams

- System architecture: Codex, Context Forge MCP, filesystem vault, Nextcloud, Hermes
- Workflow loop: work, verify, handoff, retrieve, resume
- Safety boundary: project memory vs credentials/authorization

### Outcome Evidence

- Count of handoffs/checkpoints if available
- Time saved example if measurable
- Number of projects using the pattern if available
- A concrete resume story: "A new task recovered the project state from Context Forge and continued from the recorded next action."

## Battle Buddy Required Assets

### Screenshots

- Sanitized incident/transcript database view
- Example event timeline with sensitive details removed
- Telegram or notification example with private identifiers removed
- VPS service status or pipeline dashboard if safe to show
- GitHub commits, issues, or project board if available

### Sanitized Text Artifacts

- One transcript excerpt with private details removed
- One incident enrichment example
- One pipeline run note
- One troubleshooting journal entry

### Diagrams

- Ingestion pipeline: radio/audio source, decoder, transcription, enrichment, database, alerts
- Operations loop: capture, process, review, correct, notify, archive

### Outcome Evidence

- Number of captured transcripts or incidents if safe to publish
- Search or review workflow before/after
- Example of faster review or better continuity

## Infrastructure / Home Automation Required Assets

### Screenshots

- Home Assistant dashboard
- Grafana dashboard backed by InfluxDB
- Tailscale machine list with identifying details blurred
- Nextcloud folder structure for operational notes
- Sanitized scheduled-job status

### Sanitized Text Artifacts

- One runbook
- One restart/recovery note
- One monitoring or data-retention note
- One before/after workflow example

### Diagrams

- Local and remote topology
- Home Assistant to InfluxDB to Grafana data flow
- Remote access boundary with Tailscale and SSH

### Outcome Evidence

- Fresh post-restart writes across multiple Home Assistant domains
- Dashboard continuity after restart
- Evidence of repeatable recovery or monitoring

## Sanitization Rules

- Remove credentials, tokens, cookies, API keys, and private URLs.
- Blur or redact home addresses, precise location data, IP addresses, device serial numbers, account names, and personal identifiers.
- Replace sensitive paths with labels like `[local vault]`, `[remote host]`, and `[private repo]`.
- Keep enough structure visible that the artifact still proves the workflow.
- Add a short caption to every asset explaining what it proves.

## Minimum Publishable Asset Set

The first public version can launch with:
- 3 Context Forge screenshots
- 1 Context Forge architecture diagram
- 1 sanitized handoff excerpt
- 1 before/after workflow example
- 1 GitHub link or "repository pending public cleanup" note
- 1 Battle Buddy diagram
- 1 infrastructure dashboard screenshot
- 1 LinkedIn launch post
