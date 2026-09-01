# Paul Christian Aguilar — AI/ML Cybersecurity Engineering Portfolio

Multi-page portfolio showcasing production LLM systems, threat-detection automation, ML tooling, and technical leadership.

**Live site:** `https://YOUR_GITHUB_USERNAME.github.io/portfolio/`

## Structure

```
portfolio/
├── index.html                              # Home: owned projects, contributions, leadership, skills, journey
├── styles.css                              # Shared theme
└── projects/
    ├── verdict-engine.html           # Flagship deep-dive (with architecture diagram)
    ├── alert-triage-ai.html
    ├── file-path-risk-analyzer.html
    ├── threat-data-pipeline.html
    └── telemetry-monitoring.html
```

## Deploy to GitHub Pages

1. Create a new **public** repo (e.g., `portfolio`).
2. Push everything:
   ```bash
   git init
   git add .
   git commit -m "Portfolio site"
   git branch -M main
   git remote add origin https://github.com/YOUR_GITHUB_USERNAME/portfolio.git
   git push -u origin main
   ```
3. Repo **Settings → Pages → Source: Deploy from a branch → main / (root) → Save**.
4. Live at `https://YOUR_GITHUB_USERNAME.github.io/portfolio/` in ~1 minute.

## Before you publish — fill in placeholders

In `index.html`:

- `YOUR_PERSONAL_EMAIL@example.com` — use a **personal** email, not a work one
- `YOUR_GITHUB_USERNAME` (contact link + this README)
- `YOUR_LINKEDIN`

## Privacy statement

This portfolio intentionally excludes:

- Employer name (described only as "a global cybersecurity company")
- Internal project codenames — all projects use descriptive, genericized names
- Source code, configs, credentials, API endpoints, or infrastructure identifiers
- Datasets, file hashes, detection rules, accuracy figures, or internal metrics
- Names of colleagues or internal teams

All projects are described at capability level only. Architecture diagrams are simplified and generalized.
