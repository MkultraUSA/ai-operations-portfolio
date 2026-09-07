# Context Forge Sanitized Journal Examples

These examples are public-facing excerpts based on current project state. Before publishing, replace them with screenshots or excerpts from the real vault after redacting private details.

## Example 1: Project Context Retrieval

```text
Project: Context Forge
Task: Continue implementation from prior validated state.

Current state:
- Context Forge MVP is implemented.
- Codex reads the dedicated synced filesystem vault.
- A remote Hermes environment can read an additive v1 snapshot through an existing mounted path.
- Legacy README and journal files remain unchanged during validation.

Active decisions:
- Adopt Codex first through project-scoped MCP.
- Keep Hermes unchanged during validation.
- Use a separately named manual shadow adapter before wider remote automation.
- Keep credentials and production authorization out of project memory.

Next action:
- Open a fresh task and confirm that scoped context is retrieved automatically before work starts.
```

## Example 2: Evidence-Backed Handoff

```text
Summary:
Confirmed that the project-memory vault is visible through both the local sync folder and the remote readable path.

Decisions:
- Treat filesystem sync status separately from WebDAV sync status.
- Record clean-baseline state without implying a WebDAV operation occurred.
- Keep remote validation harmless until authentication and safety boundaries are explicitly approved.

Changes:
- Added a clean-baseline command for the filesystem-synced vault.
- Updated live vault state after verification.

Verification:
- Local Context Forge context retrieval succeeded.
- Remote snapshot path exposed the expected additive v1 file.
- No credentials were stored or relayed in the handoff.

Next actions:
- Ask the remote environment to read the snapshot.
- Have it perform one harmless scoped task.
- Record the result as another handoff.
```

## Example 3: Before / After Workflow

### Before

```text
New task prompt:
"Continue the Context Forge project."

Likely failure mode:
- Agent does not know current state.
- Agent asks for recap or searches too broadly.
- Agent may repeat old work.
- Agent may miss current safety decisions.
- User has to reconstruct the project from memory.
```

### After

```text
New task startup:
1. Retrieve scoped Context Forge context.
2. Read current state, decisions, verification, and next actions.
3. Continue from the recorded next action.
4. Write a new handoff after substantive work.

Result:
The project can resume from evidence instead of memory.
```

## Example 4: Safety Boundary

```text
Context Forge stores:
- project state
- decisions
- verification notes
- changed artifacts
- next actions
- sanitized runbook guidance

Context Forge does not store:
- credentials
- tokens
- cookies
- secret-bearing paths
- production authorization
- permission to perform destructive actions
```
