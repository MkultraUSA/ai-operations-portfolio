# Resume Proof URL Map

Use this file to manage the clickable evidence links in the resume and LinkedIn Featured section.

## Required Public URLs

| Proof Item | URL | Status | Notes |
|---|---|---|---|
| LinkedIn profile | [LINKEDIN_URL] | Needed | Use the public profile URL. |
| Portfolio home | [PORTFOLIO_URL] | Needed | Can be GitHub Pages, personal domain, or hosted static site. |
| Context Forge case study | [CONTEXT_FORGE_CASE_STUDY_URL] | Needed | Flagship link for resume and LinkedIn Featured. |
| Context Forge GitHub repository | [CONTEXT_FORGE_GITHUB_URL] | Pending public cleanup | Publish only after secret/path review. |
| Sanitized Context Forge handoff | [HANDOFF_PROOF_URL] | Needed | Can be a PDF, image, or portfolio section anchor. |
| Battle Buddy case study | [BATTLE_BUDDY_CASE_STUDY_URL] | Needed | Use sanitized proof only. |
| Infrastructure lab case study | [INFRASTRUCTURE_CASE_STUDY_URL] | Needed | Use dashboard screenshots with private details redacted. |
| Proof library | [PROOF_LIBRARY_URL] | Optional but useful | A gallery page or folder of proof artifacts. |

## Resume Link Priority

If the resume has limited space, keep these links:

1. LinkedIn
2. Portfolio
3. Context Forge case study
4. Context Forge GitHub
5. Proof library

Battle Buddy and infrastructure links can live inside the portfolio if the resume gets crowded.

## LinkedIn Featured Priority

Use this order:

1. Context Forge case study
2. Context Forge GitHub repository
3. Sanitized Context Forge handoff
4. Architecture diagram or proof library
5. Battle Buddy case study
6. Infrastructure lab case study
7. Resume PDF

The GitHub repository must be immaculate before it is placed this high. If cleanup is still pending, feature the Context Forge case study first and label the repository as "public release pending cleanup" only inside the case study, not as a LinkedIn Featured item.

## URL Rules

- Use stable public URLs, not local file paths.
- Do not link directly to private files that require a login unless the employer has explicit access.
- Avoid URLs that reveal private hostnames, usernames, tokens, home network details, or internal paths.
- Use portfolio anchor links for specific sections when possible:
  - `[PORTFOLIO_URL]#context-forge`
  - `[PORTFOLIO_URL]#battle-buddy`
  - `[PORTFOLIO_URL]#infrastructure`
  - `[PORTFOLIO_URL]#proof`

## Suggested Public Link Structure

If using a portfolio site:

- `/`
- `/#context-forge`
- `/#proof`
- `/#battle-buddy`
- `/#infrastructure`
- `/assets/context-forge-handoff.pdf`
- `/assets/context-forge-architecture.png`

If using GitHub Pages:

- `https://[github-username].github.io/[portfolio-repo]/`
- `https://github.com/[github-username]/context-forge`

If using a custom domain:

- `https://[domain]/`
- `https://[domain]/context-forge`
- `https://[domain]/proof/context-forge-handoff`
