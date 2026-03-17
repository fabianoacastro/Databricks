### PR #16 – teste commit

- **Autor:** fabianoacastro
- **Data:** 2026-03-17
- **Labels:** _sem labels_
- **Branch:** `testepr` → `main`

**Arquivos alterados:**
```
NotebookFabiano.ipynb
```

---

### PR #13 – 📋 Atualização automática do CHANGELOG – PR #12

- **Autor:** github-actions[bot]
- **Data:** 2026-03-17
- **Labels:** _sem labels_
- **Branch:** `update-changelog-pr-12` → `main`

**Descrição:**
Este PR foi gerado automaticamente pelo Changelog Agent para registrar as alterações do PR #12.

**PR de origem:** #12 – feat: Add automated Code Review Agent and enhance Changelog Agent
**Autor:** Copilot

**Arquivos alterados:**
```
CHANGELOG.md
```

---

### PR #12 – feat: Add automated Code Review Agent and enhance Changelog Agent

- **Autor:** Copilot
- **Data:** 2026-03-17
- **Labels:** _sem labels_
- **Branch:** `copilot/create-code-review-agent` → `main`

**Descrição:**
Adds two GitHub Actions workflows to automate code review and changelog tracking for every PR.

## Code Review Agent ()
- Triggers on PR open/sync/reopen
- Lints changed  files via  and  notebooks via  + 
- Validates notebook format with 
- Posts a structured markdown review comment directly on the PR

## Changelog Agent ()
- Richer CHANGELOG entries: PR labels, source→target branch, description body, and list of changed files
- Upgraded actions: , 
- Added explicit  +  permissions
- Commit message follows conventional commits ()

**Example review comment posted to a PR:**

NotebookFabiano.ipynb


<!-- START COPILOT CODING AGENT TIPS -->
---

💡 You can make Copilot smarter by setting up custom instructions, customizing its development environment and configuring Model Context Protocol (MCP) servers. Learn more [Copilot coding agent tips](https://gh.io/copilot-coding-agent-tips) in the docs.

**Arquivos alterados:**
```
.github/workflows/code-review.yml
.github/workflows/generate-changelog.yml
```

---

### PR #7 - Atualização automática do CHANGELOG – PR #6
- Autor: github-actions[bot]
- Data: 2026-02-14

### PR #6 - Atualização automática do CHANGELOG – PR #5
- Autor: github-actions[bot]
- Data: 2026-02-14

### PR #5 - Atualização automática do CHANGELOG – PR #3
- Autor: github-actions[bot]
- Data: 2026-02-14

### PR #3 - Atualização automática do CHANGELOG – PR #2
- Autor: github-actions[bot]
- Data: 2026-02-14

### PR #2 - Fix changelog workflow: remove redundant git operations
- Autor: Copilot
- Data: 2026-02-14

