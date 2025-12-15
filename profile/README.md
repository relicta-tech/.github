<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/relicta-tech/relicta-action/main/brand/relicta-logo-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/relicta-tech/relicta-action/main/brand/relicta-logo-light.svg">
    <img alt="Relicta" src="https://raw.githubusercontent.com/relicta-tech/relicta-action/main/brand/relicta-logo-light.svg" width="320">
  </picture>

  <p><strong>Release intelligence for modern DevOps</strong></p>

  <p>
    <a href="https://github.com/relicta-tech/relicta/releases"><img src="https://img.shields.io/github/v/release/relicta-tech/relicta?label=CLI" alt="CLI Release"></a>
    <a href="https://github.com/relicta-tech/relicta-action/releases"><img src="https://img.shields.io/github/v/release/relicta-tech/relicta-action?label=Action" alt="Action Release"></a>
    <a href="https://github.com/relicta-tech/relicta/blob/main/LICENSE"><img src="https://img.shields.io/github/license/relicta-tech/relicta" alt="License"></a>
  </p>
</div>

---

**Relicta** is an AI-native release intelligence engine that analyzes the impact of code changes, predicts blast radius, and enables safe, policy-driven releases.

Traditional release tooling relies on brittle commit conventions and blind automation.
Relicta understands **what a change means**, **what it affects**, and **when it is safe to ship**.

### What Relicta does

- **Semantic change analysis** — Understands intent and impact from code diffs, not just commit messages
- **Blast radius detection** — Identifies downstream services, packages, and teams affected by a release
- **Policy-based automation** — Safely auto-approve low-risk releases while blocking high-risk ones
- **AI-generated release notes** — Professional documentation with OpenAI, Anthropic, Gemini, or local models
- **MCP-first architecture** — Grounded AI reasoning using real system context (Git, Jira, CI, monorepos)

### Get Started

```bash
# Install via Homebrew
brew install relicta-tech/tap/relicta

# Initialize in your project
relicta init
```

Or use the GitHub Action for zero-config CI/CD:

```yaml
- uses: relicta-tech/relicta-action@v1
  with:
    github-token: ${{ secrets.GITHUB_TOKEN }}
```

### Projects

| Repository | Description |
|------------|-------------|
| [`relicta`](https://github.com/relicta-tech/relicta) | Core CLI and release engine |
| [`relicta-action`](https://github.com/relicta-tech/relicta-action) | GitHub Action for CI/CD integration |
| [`homebrew-tap`](https://github.com/relicta-tech/homebrew-tap) | Homebrew formula for easy installation |

### Philosophy

> *Automate releases — not trust.*

Relicta is built for teams that want speed **and** confidence, automation **and** control.

---

<div align="center">
  <a href="https://relicta.tech">Website</a> · <a href="https://docs.relicta.tech">Documentation</a> · <a href="https://github.com/relicta-tech/relicta/issues">Issues</a>
</div>
