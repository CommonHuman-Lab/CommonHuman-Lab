# CommonHuman-Lab

Security tools built for penetration testers and bug bounty hunters — no Burp license required.

---

## Scanners

| Tool | Description |
|------|-------------|
| [StingXSS](https://github.com/CommonHuman-Lab/stingxss) | Context-aware XSS scanner — reflected, DOM, stored, and confirmed browser XSS with WAF detection and evasion |
| [BreachSQL](https://github.com/CommonHuman-Lab/breachsql) | Context-aware SQL injection scanner — error-based, boolean-blind, time-blind, UNION, and stacked queries across six DBMS with WAF evasion |

```bash
pip install stingxss breachsql
```

---

## Infrastructure

| Tool | Description |
|------|-------------|
| [NyxStrike](https://github.com/CommonHuman-Lab/nyxstrike) | AI-powered offensive security orchestration — connects LLM agents to real tools and runs full attack chains from recon to exploitation |
| [OctoRig](https://github.com/CommonHuman-Lab/OctoRig) | Docker lab launcher — spins up intentionally vulnerable environments for tool testing and practice with a single command |

---

## Libraries

| Package | Description |
|---------|-------------|
| [commonhuman-core](https://pypi.org/project/commonhuman-core/) | Shared HTTP engine and web crawler — session management, injection helpers, BFS crawling, and passive recon primitives |
| [commonhuman-payloads](https://pypi.org/project/commonhuman-payloads/) | Shared payload collections, encoders, and WAF signatures |
| [commonhuman-cli](https://pypi.org/project/commonhuman-cli/) | Shared CLI argument handling and output formatting |

---

All tools are licensed under [AGPLv3](https://www.gnu.org/licenses/agpl-3.0.html).
