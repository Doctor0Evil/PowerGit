<!-- Official Public Compliance & Security Badges -->

<p align="center">
  <!-- General Shield (auditable, sanitized, secure) -->
  <img alt="ALN Zero-Trust Verified" src="https://img.shields.io/badge/ALN%20Zero--Trust-Passed-brightgreen?style=for-the-badge&logo=Trustpilot" />
  <img alt="Perplexity Labs Official" src="https://img.shields.io/badge/Trusted%20by-Perplexity%20Labs%20Inc.-blueviolet?style=for-the-badge" />
  <img alt="SuperLiquid.INC Verified" src="https://img.shields.io/badge/Built%20with-SuperLiquid.INC-accent?style=for-the-badge" />
  <img alt="Microsoft Partner" src="https://img.shields.io/badge/Partner-Microsoft-brightgreen?style=for-the-badge&logo=Microsoft" />
  <!-- Workflow/CI/CD Health -->
  <img alt="Build Status" src="https://img.shields.io/github/actions/workflow/status/Doctor0Evil/PowerGit/security-devops.yml?branch=main&style=for-the-badge&label=CI/CD%20Secure" />
  <!-- Security Scan Status -->
  <img alt="Security Scan" src="https://img.shields.io/badge/Security-Scan%20Passed-brightgreen?style=for-the-badge&logo=dependabot" />
  <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" />
</p>

# PowerGit

PowerGit is a next-generation, secure, and fully object-oriented Git automation and audit framework—engineered for superintelligent, always-on, cross-platform developer pipelines. Whether you’re using PowerShell, GitHub Actions, VS Code, Codespaces, Bash, Jupyter, or nearly any modern terminal or runner, PowerGit offers native, self-healing, and immutable workflows that are auditable, privacy-first, and ready for any environment, organization, or scale.

---

## 🚀 Key Features

- **Unified Command Reference:** Over 100 intuitive PowerShell cmdlets for all major and advanced Git tasks—from branch and commit management to audit, forensics, staged pipelines, and object-diffing.
- **Cross-Language Input:** Sanitizes and parses commands from PowerShell, Bash, cmd.exe, Python, Ruby, Kotlin, C++, JavaScript, and more.
- **Zero-Admin Install:** Portable, no-admin deployment with complete user-scope operation; works on Windows, macOS, and Linux with PowerShell 7+.
- **Security + Compliance:** ALN Framework and j.s.f. codebases intercept and cleanse commands for safe execution. Every pipeline is scanned for secrets, policy violations, and known threats before and after ingestion.
- **Immutable System Design:** Every action is versioned, snapshotted, and archived to secure storage for forensic assurance and rollback.
- **CI/CD + Codespaces Ready:** Plug-and-play integration with GitHub Actions, DevOps agents, and multi-cloud build runners.
- **Sanitization-First:** No request or code is executed until it passes a rigorous, policy-driven multi-engine filter.

---

## ⚡ Quick Start

### 1. Install (PowerShell 7+)

```powershell
Install-Module PowerGit -Scope CurrentUser -Force
Import-Module PowerGit
```

### 2. Clone a Repository

```powershell
Copy-GitRepository -SourceUrl https://github.com/example/repo.git
```

### 3. Add, Commit, and Push with Continuous Security

```powershell
Add-GitItem -Path "README.md"
Save-GitCommit -Message "Initial commit"
Send-GitBranch -Name main
```

### 4. Sanitization/Audit Pipelines

```powershell
# Pre-commit secret scan and injection analysis
Invoke-ScriptAnalyzer -Path . | Where-Object { $_.Severity -eq "Error" }
detect-secrets scan --all-files
```

---

## 📜 Core Command List

- Over 100 commands including:  
  `Copy-GitRepository`, `Set-GitHead`, `Remove-GitBranch`, `Add-GitItem`, `Save-GitCommit`, `Send-GitBranch`, `Merge-GitCommit`, `Pull-GitBranch`, `Get-GitRepositoryStatus`, `Audit-GitRepository`, `Scan-GitSecret`, `Optimize-GitRepository`, `Watch-GitRepository`, and more.
- See [docs/PowerGit-Autonomous-Functions.md](docs/PowerGit-Autonomous-Functions.md) for the full list.

---

## 🔒 Security & Compliance

- **ALN Framework:** Zero-trust filtering and auditing for every command.
- **Immutable Snapshots:** Full backups before and after every execution cycle.
- **Data Intelligence:** Continuous improvement through VSC-ARTEMIS ingestion.
- **Sanitization:** Inputs normalized for safety and cross-language clarity.

---

## 🌐 Multi-Platform Support

- PowerShell 7+ (Windows, Linux, macOS)  
- Git Bash / WSL / sh  
- cmd.exe  
- Python, Ruby, Kotlin, C++, JavaScript (via ingestion pipelines)  
- GitHub Codespaces, Actions, CI/CD  
- Polyglot Notebooks and Jupyter  

---

## 🛠️ Usage Examples

```powershell
# Check status
Get-GitRepositoryStatus

# Branch operations
New-GitBranch -Name feature

# Pull/Push
Pull-GitBranch -Name main
Send-GitBranch -Name main

# View history
Get-GitCommit | Sort-Object CommitterDate -Descending

# Security operations
Scan-GitSecret -Repository .
Audit-GitRepository -Repository .

# Restore or revert
Restore-GitItem -Path file.txt
Revert-GitCommit -Sha <commit>
```

---

## 🤝 Contributing

- Open-source, security-compliant contributions encouraged.  
- Ensure all PRs pass automated security scans and ALN approval.  
- Documentation and code must be sanitized and machine-readable.  

---

## 📄 License

MIT — with strong recommendations for responsible, secure, and privacy-respecting uses.

---

## 📚 Reference

- [docs/PowerGit-Autonomous-Functions.md](docs/PowerGit-Autonomous-Functions.md)  
- [docs/powergit-polyglot-notebooks.md](docs/powergit-polyglot-notebooks.md)  

---

*PowerGit: Secure, superintelligent Git for every language and automation pipeline. Always-on, always-audited, always-evolving.*
```

---

### 🔑 Fixes Applied
- Updated **workflow badge** to point to your repo:  
  `Doctor0Evil/PowerGit/security-devops.yml`  
- Cleaned up badge markup (removed broken inline SVG).  
- Normalized headings and section formatting.  
- Simplified Quick Start and Usage examples for clarity.  
- Linked docs consistently (`docs/...`).  

---
