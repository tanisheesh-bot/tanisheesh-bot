<p align="center">
  <svg xmlns="http://www.w3.org/2000/svg" width="56" height="56" viewBox="0 0 24 24" fill="none" stroke="#F59E0B" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
    <path d="M12 8V4H8"/>
    <rect width="16" height="12" x="4" y="8" rx="2"/>
    <path d="M2 14h2"/>
    <path d="M20 14h2"/>
    <path d="M15 13v2"/>
    <path d="M9 13v2"/>
  </svg>
</p>

<h1 align="center">Yantra [bot]</h1>

<p align="center">
  <strong>Automated Maintenance Bot</strong> &nbsp;·&nbsp; Dependency Updates &nbsp;·&nbsp; Security Patching &nbsp;·&nbsp; CI-Gated Auto-Merge
</p>

<p align="center">
  <a href="https://github.com/tanisheesh"><img src="https://img.shields.io/badge/Maintainer-@tanisheesh-111111?style=flat-square&logo=github&logoColor=white" alt="Maintainer"></a>
  <a href="https://tanisheesh.in"><img src="https://img.shields.io/badge/tanisheesh.in-F59E0B?style=flat-square&logo=googlechrome&logoColor=111111" alt="Website"></a>
  <a href="https://github.com/tanisheesh/setup-toolkit"><img src="https://img.shields.io/badge/Powered_by-setup--toolkit-06b6d4?style=flat-square" alt="setup-toolkit"></a>
  <a href="mailto:hi@tanisheesh.in"><img src="https://img.shields.io/badge/hi@tanisheesh.in-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

I am the automated maintenance account for **[@tanisheesh](https://github.com/tanisheesh)** repositories, powered by **[setup-toolkit](https://github.com/tanisheesh/setup-toolkit)**. I keep dependencies current, raise OSV security patch PRs, and squash-merge verified updates once every CI and security gate passes.

---

## What I automate

| Schedule (IST) | Task | Details |
|---|---|---|
| **Monday 06:00** | **Dependency Scan** | Runs Renovate across Node, Python, Docker, and GitHub Actions with a 3-day release cooldown |
| **On every PR** | **Quality & Security Gates** | Waits for `CI` (lint, typecheck, build, unit + Playwright E2E), `CodeQL`, `Gitleaks`, and `Dependency Review` |
| **After CI passes** | **Auto-Merge** | Squash-merges passing updates and deletes branches automatically (`needs-review` label on failures) |
| **Monday 10:00** | **Maintenance Digest** | Summarizes merged PRs, pending updates, Dependabot/CodeQL/Secret alerts, and `main` CI health |

---

## Stack

<p>
  <img src="https://img.shields.io/badge/Renovate-1A1F6C?style=flat-square&logo=renovate&logoColor=white" alt="Renovate">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/CodeQL-181717?style=flat-square&logo=github&logoColor=white" alt="CodeQL">
  <img src="https://img.shields.io/badge/Gitleaks-0284C7?style=flat-square&logo=github&logoColor=white" alt="Gitleaks">
  <img src="https://img.shields.io/badge/CodeRabbit-FF570A?style=flat-square" alt="CodeRabbit">
</p>

---

<p align="center">
  Operated by <a href="https://github.com/tanisheesh">Tanish Poddar</a> &nbsp;·&nbsp;
  <a href="mailto:hi@tanisheesh.in">hi@tanisheesh.in</a> &nbsp;·&nbsp;
  <a href="https://tanisheesh.in">tanisheesh.in</a>
</p>
