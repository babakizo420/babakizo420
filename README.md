### Security Researcher | Application Security | MCP / AI-Agent Security

Published-CVE security researcher operating under **BlessedOps**. I break widely-used software (with permission), understand the code, and ship the fixes. Specialty: incomplete-fix and variant analysis, cross-fork discovery, and the emerging MCP / AI-agent security class.

---

**Published CVEs and advisories:**

| CVE | Software | Severity | Class |
|---|---|---|---|
| [CVE-2026-55667](https://github.com/filebrowser/filebrowser/security/advisories/GHSA-fmm7-x4gx-8jhr) | File Browser | HIGH (CVSS 8.2) | Symlink-following out-of-scope file deletion (incomplete-fix) |
| [CVE-2026-63131](https://github.com/openbao/openbao/security/advisories/GHSA-xp3c-3jw3-4vcr) | OpenBao (Vault fork) | MODERATE (CVSS 6.0) | Access-control bypass, cross-fork discovery |
| [CVE-2026-27761](https://github.com/babakizo420/security-research/blob/main/writeups/CVE-2026-27761-gitea.md) | Gitea | Credited | API token-scope bypass via RSS/Atom feeds (incomplete-fix) |

Full technical write-ups plus my research tooling live in **[security-research](https://github.com/babakizo420/security-research)**.

---

**What I do:**

- Web application security testing (OWASP Top 10, auth bypass, CSRF, IDOR)
- Incomplete-fix and variant analysis, cross-fork bug discovery
- MCP / AI-agent security: server auth boundaries, SSRF, credential forwarding
- Web3 security research (EIP-2612 permit phishing, smart contract analysis), Immunefi-cleared
- Reconnaissance automation for bug bounty programs
- NDPA and data protection compliance auditing for Nigerian businesses

**Tools I have built:**

| Project | What it does |
|---|---|
| [security-research](https://github.com/babakizo420/security-research) | CVE write-ups plus incfix (incomplete-fix analyzer) and mcp-audit (defensive MCP server self-audit scanner) |
| [PermitWatch](https://github.com/babakizo420/permit-watch) | Real-time EIP-2612 permit monitor. Detects wallet drainer attacks as they happen |
| [HeaderGuard](https://github.com/babakizo420/headerguard) | Security header auditor and NDPA compliance checker. Grades any website A to F |
| [Burp Auth Tagger](https://github.com/babakizo420/burp-auth-tagger) | Burp Suite extension. Auto-tags auth endpoints and flags missing CSRF tokens |
| [Auth Recon Tagger](https://github.com/babakizo420/blessedops-auth-recon) | Classifies auth endpoints from URL lists. JSON output, scope filtering |

**Also building:**

| Project | What it does |
|---|---|
| [Pejji](https://pejji.com) | Security-first web agency. Every site ships with CSP, HSTS, NDPA compliance, and CI/CD security gates |

---

**Stack:**

`Python` `Bash` `JavaScript` `Solidity` `Burp Suite` `Nuclei` `FFUF` `Nmap` `Caido`

---

**Full portfolio:** [babakizo420.github.io/security-dashboard](https://babakizo420.github.io/security-dashboard/)

---

[GitHub](https://github.com/babakizo420) . [YesWeHack](https://yeswehack.com) . [Upwork](https://www.upwork.com/freelancers/~01d1ef47c8b2a7a6aa)
