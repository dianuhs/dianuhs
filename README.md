# Diana Molski — Cloud & Capital

Finance-trained FinOps analyst building production tooling for engineering and finance teams.

---

## Visibility → Variance → Tradeoffs

Four tools. One pipeline. Built end-to-end for real cost decisions.

```
┌─────────────────────┐     ┌──────────────────────┐
│   FinOps Lite       │────▶│  FinOps Watchdog      │
│                     │     │                      │
│  Cost visibility    │     │  Anomaly detection   │
│  AWS Cost Explorer  │     │  Spend spike alerts  │
│  FOCUS 1.0 export   │     │  Markdown reports    │
└─────────────────────┘     └──────────────────────┘
                                        │
                                        ▼
┌─────────────────────┐     ┌──────────────────────┐
│  Cloud Cost Guard   │◀────│  Recovery Economics   │
│                     │     │                      │
│  Dashboard          │     │  Resilience modeling │
│  Spend trends       │     │  Scenario comparison │
│  Savings coverage   │     │  Backup/restore cost │
│  Rightsizing        │     │  --compare flag      │
└─────────────────────┘     └──────────────────────┘
```

| Stage | Tool | What it does |
|-------|------|-------------|
| **Visibility** | [FinOps Lite](https://github.com/dianuhs/finops-lite) | Pulls AWS spend from Cost Explorer, compares periods, exports FOCUS 1.0 CSV |
| **Variance** | [FinOps Watchdog](https://github.com/dianuhs/finops-watchdog) | Detects spend anomalies from any cost CSV; outputs JSON/YAML/CSV + markdown summary |
| **Tradeoffs** | [Recovery Economics](https://github.com/dianuhs/recovery-economics) | Models monthly resilience cost and compares scenarios side by side |
| **Dashboard** | [Cloud Cost Guard](https://github.com/dianuhs/cloud-cost-guard) | Open-source dashboard: spend trends, savings coverage, rightsizing recommendations |

---

## About Me

I come from a finance background and retrained into cloud infrastructure and FinOps. I build tools that translate between the language engineers speak (usage, resources, architecture) and the language finance teams need (cost, variance, tradeoffs, decisions).

**What I focus on:**

- Production-quality CLI tooling that works in real pipelines, not just demos
- FOCUS 1.0 compliance so cost data is portable across tools
- Deterministic, testable outputs with explicit exit codes and stable schemas
- Decision-ready artifacts: tables, markdown summaries, scenario comparisons

**Tech stack:** Python, AWS (Cost Explorer, IAM, boto3), SQL, TypeScript/React for dashboards

---

## Projects

- **[dianuhs/finops-lite](https://github.com/dianuhs/finops-lite)** — AWS cost visibility CLI with FOCUS 1.0 export
- **[dianuhs/finops-watchdog](https://github.com/dianuhs/finops-watchdog)** — anomaly detection from cost CSV
- **[dianuhs/recovery-economics](https://github.com/dianuhs/recovery-economics)** — resilience cost modeling with scenario compare
- **[dianuhs/cloud-cost-guard](https://github.com/dianuhs/cloud-cost-guard)** — open-source cloud cost dashboard

---

*Finance background. FinOps focus. Production tooling.*
