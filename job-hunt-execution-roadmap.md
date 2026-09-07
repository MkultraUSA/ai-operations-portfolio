# Job Hunt Execution Roadmap

## Goal

Build a coherent hiring funnel:

**Native LinkedIn proof -> LinkedIn profile -> Featured proof -> Portfolio case study -> GitHub repository -> Resume -> Interview stories**

Every surface should reinforce the same message:

> I build practical AI operations and automation systems that preserve context, connect tools, and make technical work easier to resume and operate.

## Phase 1: Proof Foundation

### Deliverables

- Context Forge GitHub repository cleaned and public-ready
- Context Forge case study page
- Sanitized Context Forge handoff
- Context Forge architecture diagram
- Before/after workflow example
- Resume with clickable proof links
- LinkedIn profile rewrite

### Completion Standard

The Context Forge story must be inspectable. A hiring manager should be able to click from LinkedIn to the case study, from the case study to GitHub, and from GitHub back to proof artifacts.

## Phase 2: GitHub Cleanup

### Actions

1. Locate the actual Context Forge repo.
2. Check repo status and uncommitted work.
3. Run a secret/privacy scan.
4. Review README and docs.
5. Add or repair `.gitignore`, `.env.example`, `SECURITY.md`, `CHANGELOG.md`, and sanitized examples.
6. Add minimal tests or smoke verification if code exists.
7. Confirm setup instructions work from a clean clone.
8. Prepare a public-release commit or PR.

### Output

- Public-ready repository
- Clean README
- Sanitized examples
- Proof assets
- Known limitations
- Release notes

## Phase 3: Portfolio Site

### Actions

1. Replace placeholder case-study proof with real redacted screenshots.
2. Add final public URLs.
3. Add Context Forge GitHub link.
4. Add Battle Buddy and infrastructure proof pages.
5. Publish the site.
6. Confirm links work from mobile and desktop.

### Output

- Public portfolio URL
- Context Forge anchor/page URL
- Proof library URL

## Phase 4: Resume

### Actions

1. Add final LinkedIn, portfolio, GitHub, and proof URLs.
2. Add real Tesla/work-history details.
3. Tailor one version for AI operations and automation roles.
4. Tailor a second version for technical operations and systems integration roles if needed.
5. Export PDF.
6. Upload to LinkedIn Featured and job boards.

### Output

- Clickable PDF resume
- Markdown source resume
- Optional DOCX version

## Phase 5: LinkedIn Launch

### Actions

1. Update headline.
2. Replace About section.
3. Add Context Forge, Battle Buddy, and infrastructure project entries.
4. Build the Context Forge native proof deck.
5. Add Featured proof assets in order.
6. Publish pinned launch post without relying on an external link.
7. Post twice per week for four weeks.
8. Comment daily on targeted hiring and operations posts.

### Output

- Updated LinkedIn profile
- Pinned launch post
- Eight proof-led content posts
- Native Context Forge proof deck

## Phase 6: Application System

### Actions

1. Identify role titles to target.
2. Build a list of companies and hiring managers.
3. Use LinkedIn search and saved jobs.
4. Track applications, referrals, messages, and follow-ups.
5. Reuse proof links in outreach.

### Role Targets

- AI Automation Specialist
- AI Operations Analyst
- Technical Operations Specialist
- Systems Integration Specialist
- Internal Tools Specialist
- Workflow Automation Specialist
- Applied AI Operations Associate
- Technical Program Support
- Lab Operations Specialist

## Proof Hierarchy

Use this order everywhere:

1. Context Forge
2. Sanitized handoff
3. Architecture diagram
4. GitHub repository
5. Battle Buddy
6. Infrastructure lab
7. Legal RAG source-grounded retrieval demo
8. Resume

## Phase 7: Legal RAG Proof Project

### Purpose

Show that Kevin can build a careful RAG workflow against serious source material, with citations, source boundaries, evaluation, and abstention.

### Actions

1. Pick a narrow public legal corpus.
2. Build a small ingestion and chunking pipeline.
3. Add source metadata and stable chunk IDs.
4. Build hybrid retrieval.
5. Generate answers only from retrieved passages.
6. Show source cards and retrieved passages.
7. Add abstention for unsupported questions.
8. Create a 20-question evaluation set.
9. Publish a clean GitHub repo.
10. Add the finished case study to the portfolio and LinkedIn Featured.

### Recommended First Corpus

Fair Credit Reporting Act regulations and selected public opinions.

### Output

- `legal-rag-source-demo` repository
- public demo or screenshots
- architecture diagram
- cited-answer screenshot
- audit-view screenshot
- evaluation table
- LinkedIn carousel

## Interview Stories To Prepare

### Story 1: Context Loss

Problem: AI-assisted work kept losing continuity.

Action: Built Context Forge to retrieve scoped memory and write structured handoffs.

Result: Future tasks can resume from evidence instead of asking for a full recap.

### Story 2: Safety Boundary

Problem: Project memory can accidentally become a place where secrets or unsafe assumptions spread.

Action: Made credentials and production authorization explicitly out of scope.

Result: The workflow supports continuity without weakening operational safety.

### Story 3: Battle Buddy

Problem: Radio and incident information is messy, time-sensitive, and hard to review.

Action: Built a capture, transcription, enrichment, storage, review, and notification workflow.

Result: Created searchable operational memory for later review.

### Story 4: Infrastructure Lab

Problem: Local and remote infrastructure becomes fragile when observability and recovery notes are scattered.

Action: Connected dashboards, synced notes, remote access, and restart verification.

Result: Improved visibility and repeatability across the lab environment.

## Immediate Next Step

Find the real Context Forge repository and run the GitHub immaculate release checklist against it.
