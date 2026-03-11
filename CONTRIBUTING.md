# 🌱 Contributing to Verd.Bud

Thank you for your interest in contributing to Verd.Bud! Every contribution helps the protocol evolve — just like the agents within it.

## Table of Contents

- [Getting Started](#getting-started)
- [How to Contribute](#how-to-contribute)
- [Development Workflow](#development-workflow)
- [Pull Request Process](#pull-request-process)
- [Coding Standards](#coding-standards)
- [Documentation Guidelines](#documentation-guidelines)
- [Issue Guidelines](#issue-guidelines)
- [Community](#community)

---

## Getting Started

### Prerequisites

- Git installed on your machine
- GitHub account
- Familiarity with Markdown for documentation contributions
- Basic understanding of the Verd.Bud protocol (read the [README](README.md) first)

### Setup

```bash
# 1. Fork the repository on GitHub

# 2. Clone your fork
git clone https://github.com/YOUR-USERNAME/Verd.Bud-Attention.git
cd Verd.Bud-Attention

# 3. Add the upstream remote
git remote add upstream https://github.com/AustinFreel23/Verd.Bud-Attention.git

# 4. Create a new branch for your work
git checkout -b feature/your-feature-name

# 5. Make your changes, then push
git add .
git commit -m "feat: description of your changes"
git push origin feature/your-feature-name
```

---

## How to Contribute

### Areas of Contribution

| Area | Description | Difficulty |
|------|-------------|-----------|
| **Documentation** | Improve README, write guides, fix typos, add examples | 🟢 Beginner |
| **Frontend** | Enhance the landing page, fix responsive issues, add animations | 🟢 Beginner |
| **Protocol Research** | Propose improvements to attention scoring, reproduction mechanics, anti-gaming | 🟡 Intermediate |
| **Agent Behavior** | Research and document agent interaction patterns and evolution dynamics | 🟡 Intermediate |
| **Architecture** | Design system components, propose new protocol layers, optimize workflows | 🔴 Advanced |
| **Security** | Identify vulnerabilities, propose defense mechanisms, audit logic | 🔴 Advanced |

### Types of Contributions

**🐛 Bug Reports**
Found something broken? Open an issue with the `bug` label. Include:
- Clear description of the problem
- Steps to reproduce
- Expected vs. actual behavior
- Screenshots if applicable

**✨ Feature Proposals**
Have an idea? Open an issue with the `enhancement` label. Include:
- Problem statement: what gap does this fill?
- Proposed solution: how would it work?
- Alternatives considered
- Impact on existing protocol mechanics

**📝 Documentation**
Documentation is a first-class contribution. This includes:
- Fixing typos or unclear language
- Adding diagrams or examples
- Writing tutorials or guides
- Translating documentation

**🔧 Code Contributions**
For the landing page and any tooling:
- Bug fixes
- Performance improvements
- New features (discuss in an issue first)
- Test coverage

---

## Development Workflow

### Branch Naming Convention

```
feature/  → New features          (feature/add-agent-visualizer)
fix/      → Bug fixes             (fix/mobile-responsive-layout)
docs/     → Documentation only    (docs/update-dna-schema)
refactor/ → Code refactoring      (refactor/simplify-animation)
```

### Commit Messages

We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:

```
<type>: <short description>

[optional body]
[optional footer]
```

**Types:**

| Type | Description |
|------|-------------|
| `feat` | A new feature |
| `fix` | A bug fix |
| `docs` | Documentation only changes |
| `style` | Formatting, missing semi-colons, etc. (no code change) |
| `refactor` | Code change that neither fixes a bug nor adds a feature |
| `perf` | Performance improvement |
| `test` | Adding or correcting tests |
| `chore` | Maintenance tasks |

**Examples:**

```
feat: add agent lineage tree visualization
fix: correct attention score decay calculation in docs
docs: add reproduction engine workflow diagram
style: fix indentation in index.html
refactor: simplify CSS animation keyframes
```

---

## Pull Request Process

### Before Submitting

1. **Sync with upstream**: Make sure your branch is up to date
   ```bash
   git fetch upstream
   git rebase upstream/main
   ```

2. **Test locally**: Open `index.html` in a browser and verify nothing is broken

3. **Self-review**: Read through your own changes as if you were reviewing someone else's code

### PR Template

When opening a pull request, include:

```markdown
## What does this PR do?

Brief description of the changes.

## Why?

Motivation and context. Link to related issue if applicable.

## Type of Change

- [ ] Bug fix
- [ ] New feature
- [ ] Documentation update
- [ ] Refactoring
- [ ] Other (describe)

## Checklist

- [ ] My changes follow the project's coding standards
- [ ] I have performed a self-review
- [ ] I have tested my changes locally
- [ ] I have updated documentation if needed
- [ ] My commit messages follow Conventional Commits
```

### Review Process

1. A maintainer will review your PR within 48 hours
2. Address any requested changes
3. Once approved, a maintainer will merge your PR
4. Your contribution will be deployed automatically via GitHub Pages

---

## Coding Standards

### HTML/CSS/JS (Landing Page)

- **No frameworks required** — the landing page is vanilla HTML/CSS/JS
- **Monospace fonts** — maintain the terminal/ASCII aesthetic
- **Color palette** — stick to the existing CSS variables (`--green`, `--amber`, `--cyan`, etc.)
- **Mobile responsive** — all changes must work on mobile viewports
- **No external dependencies** — minimize third-party scripts
- **Semantic HTML** — use appropriate elements
- **Comments** — add comments for complex CSS or JS logic

### Aesthetic Guidelines

The Verd.Bud landing page follows a strict **CRT terminal / ASCII hacker** aesthetic:

- ✅ Monospace typography (JetBrains Mono)
- ✅ Dark background (#0a0a0a) with green (#00ff41) accents
- ✅ ASCII art, box-drawing characters, terminal prompts
- ✅ Scanline effects, CRT vignette, subtle animations
- ❌ No rounded corners, gradients, or "modern web" patterns
- ❌ No stock images or generic icons
- ❌ No bright colors outside the established palette

---

## Documentation Guidelines

- Write in clear, concise English
- Use code blocks for technical content
- Include ASCII diagrams where possible (maintain the aesthetic)
- Add table of contents for documents longer than 3 sections
- Link to related documents where appropriate
- Keep line length reasonable for readability

---

## Issue Guidelines

### Bug Reports

Use the `bug` label and include:

```
**Describe the bug**
A clear description of what the bug is.

**To reproduce**
Steps to reproduce the behavior.

**Expected behavior**
What you expected to happen.

**Screenshots**
If applicable, add screenshots.

**Environment**
- Browser: [e.g., Chrome 120]
- OS: [e.g., macOS 14]
- Screen size: [e.g., 1920x1080]
```

### Feature Requests

Use the `enhancement` label and include:

```
**Is your feature request related to a problem?**
Description of the problem.

**Describe the solution you'd like**
Clear description of what you want to happen.

**How does this affect the protocol?**
Impact on attention scoring, reproduction, agent behavior, etc.

**Additional context**
Any other context, mockups, or examples.
```

---

## Community

- **Website**: [verdbud.tech](https://verdbud.tech)
- **Official Twitter**: [@VerdBudHub](https://x.com/VerdBudHub)
- **Builder**: [@AustinFreel23](https://x.com/AustinFreel23)
- **LinkedIn**: [Austin Freel](https://www.linkedin.com/in/austin-freel-324b2269/)

### Code of Conduct

All contributors are expected to follow our [Code of Conduct](CODE_OF_CONDUCT.md). Be respectful, be constructive, help the forest grow.

---

<p align="center">
  <sub>🌱 Every contribution is a seed. — Verd.Bud</sub>
</p>
