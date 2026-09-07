# GitHub Pages Publishing Plan

## Recommendation

Publish the portfolio as a GitHub Pages site.

That gives LinkedIn viewers a more trusted destination than a random link because the URL visibly belongs to GitHub:

```text
https://mkultrausa.github.io/ai-operations-portfolio/
```

## Repository

Recommended repo:

```text
ai-operations-portfolio
```

Visibility:

```text
Public
```

Why not make this the same repo as Context Forge:

- The portfolio should explain multiple projects.
- The Context Forge repo should stay technically focused and immaculate.
- The portfolio can link to Context Forge once that repo is public-safe.

## Publishing Options

### Option 1: GitHub Pages From Main Branch

Best for this static site.

Settings:

- Source: Deploy from branch
- Branch: `main`
- Folder: `/root`

Files needed:

- `index.html`
- `styles.css`
- `.nojekyll`
- `README.md`

### Option 2: GitHub Pages From `/docs`

Useful if the repo later contains source files, scripts, or build tooling.

Settings:

- Source: Deploy from branch
- Branch: `main`
- Folder: `/docs`

For now, root is simpler.

## LinkedIn Use

Do not lead feed posts with the URL.

Use the GitHub Pages URL in:

- LinkedIn Contact Info
- Featured section
- Resume
- Project entries
- Replies to people who ask for the link

Feed posts should show native proof first:

- PDF carousel
- screenshot
- architecture diagram
- sanitized handoff

Then say:

```text
I put the proof links in my Featured section.
```

## Suggested Link Map

After publishing, update these placeholders:

```text
[PORTFOLIO_URL] = https://mkultrausa.github.io/ai-operations-portfolio/
[CONTEXT_FORGE_CASE_STUDY_URL] = https://mkultrausa.github.io/ai-operations-portfolio/#context-forge
[PROOF_LIBRARY_URL] = https://mkultrausa.github.io/ai-operations-portfolio/#proof
[BATTLE_BUDDY_CASE_STUDY_URL] = https://mkultrausa.github.io/ai-operations-portfolio/#battle-buddy
[INFRASTRUCTURE_CASE_STUDY_URL] = https://mkultrausa.github.io/ai-operations-portfolio/#infrastructure
```

## Local Publish Commands

Once GitHub login is complete:

```text
cd C:\Users\mrrob\Documents\Codex\2026-09-07\referenced-chatgpt-conversation-this-is-an-2\outputs
git init
git add .
git commit -m "Create AI operations portfolio"
gh repo create ai-operations-portfolio --public --source . --remote origin --push
gh repo edit --homepage "https://[github-username].github.io/ai-operations-portfolio/"
```

Then enable Pages in GitHub:

```text
Repo -> Settings -> Pages -> Deploy from branch -> main -> /root
```

If the GitHub account supports enabling Pages from the command line, this can also be handled after authentication.

## Current Blocker

The local GitHub CLI is installed, but it is not logged in.

Run:

```text
gh auth login
```

Then this site can be pushed to GitHub.
