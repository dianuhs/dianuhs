# Diana Molski — Cloud & Capital

Finance-trained FinOps analyst building production tooling for engineering and finance teams.

---

## Visibility → Variance → Tradeoffs

Six tools. One pipeline. Full Cloud+AI+SaaS coverage for every scope the FinOps Foundation 2026 Framework defines.

```
┌─────────────────────┐     ┌──────────────────────┐
│   FinOps Lite       │────▶│  FinOps Watchdog     │
│                     │     │                      │
│  Cost visibility    │     │  Anomaly detection   │
│  AWS/Azure/GCP      │     │  Spend spike alerts  │
│  FOCUS 1.0 export   │     │  Markdown reports    │
└─────────────────────┘     └──────────────────────┘
                                        │
                                        ▼
┌─────────────────────┐     ┌──────────────────────┐
│  Cloud Cost Guard   │◀────│  Recovery Economics  │
│                     │     │                      │
│  Dashboard          │     │  Resilience modeling │
│  Spend trends       │     │  Scenario comparison │
│  Savings coverage   │     │  Backup/restore cost │
│  Rightsizing        │     │  --compare flag      │
└─────────────────────┘     └──────────────────────┘
         │
         ▼
┌─────────────────────┐     ┌──────────────────────┐
│   AI Cost Lens      │     │  SaaS Cost Analyzer  │
│                     │     │                      │
│  AI spend           │     │  SaaS spend          │
│  OpenAI · Anthropic │     │  Unused licenses     │
│  AWS Bedrock        │     │  Per-seat costs      │
│  FOCUS 1.0          │     │  Forecasting         │
└─────────────────────┘     └──────────────────────┘
              │                        │
              └────────────┬───────────┘
                           ▼
              ┌─────────────────────────┐
              │  Tech Spend             │
              │  Command Center         │
              │                         │
              │  Cloud + AI + SaaS      │
              │  Unified exec report    │
              │  Markdown · JSON · HTML │
              └─────────────────────────┘
```

| Stage | Tool | What it does |
|-------|------|-------------|
| **Visibility** | [FinOps Lite](https://github.com/dianuhs/finops-lite) [![CI](https://github.com/dianuhs/finops-lite/actions/workflows/test.yml/badge.svg)](https://github.com/dianuhs/finops-lite/actions/workflows/test.yml) | AWS/Azure/GCP cost visibility, FOCUS 1.0 export |
| **Variance** | [FinOps Watchdog](https://github.com/dianuhs/finops-watchdog) [![CI](https://github.com/dianuhs/finops-watchdog/actions/workflows/test.yml/badge.svg)](https://github.com/dianuhs/finops-watchdog/actions/workflows/test.yml) | Anomaly detection from any cost CSV |
| **Tradeoffs** | [Recovery Economics](https://github.com/dianuhs/recovery-economics) [![CI](https://github.com/dianuhs/recovery-economics/actions/workflows/test.yml/badge.svg)](https://github.com/dianuhs/recovery-economics/actions/workflows/test.yml) | Resilience cost modeling, scenario comparison |
| **AI Spend** | [AI Cost Lens](https://github.com/dianuhs/ai-cost-lens) [![CI](https://github.com/dianuhs/ai-cost-lens/actions/workflows/test.yml/badge.svg)](https://github.com/dianuhs/ai-cost-lens/actions/workflows/test.yml) | OpenAI/Anthropic/Bedrock billing → FOCUS 1.0 |
| **SaaS Spend** | [SaaS Cost Analyzer](https://github.com/dianuhs/saas-cost-analyzer) [![CI](https://github.com/dianuhs/saas-cost-analyzer/actions/workflows/test.yml/badge.svg)](https://github.com/dianuhs/saas-cost-analyzer/actions/workflows/test.yml) | SaaS billing → FOCUS 1.0, unused licenses, per-seat costs, forecasting |
| **Dashboard** | [Cloud Cost Guard](https://github.com/dianuhs/cloud-cost-guard) [![CI](https://github.com/dianuhs/cloud-cost-guard/actions/workflows/test.yml/badge.svg)](https://github.com/dianuhs/cloud-cost-guard/actions/workflows/test.yml) | Unified spend dashboard, rightsizing recommendations |
| **Command Center** | [Tech Spend Command Center](https://github.com/dianuhs/tech-spend-command-center) [![CI](https://github.com/dianuhs/tech-spend-command-center/actions/workflows/test.yml/badge.svg)](https://github.com/dianuhs/tech-spend-command-center/actions/workflows/test.yml) | Reads all five tools → single CFO-ready report (markdown/json/html) |

---

## About Me

I come from a finance background and retrained into cloud infrastructure and FinOps. I build tools that translate between the language engineers speak (usage, resources, architecture) and the language finance teams need (cost, variance, tradeoffs, decisions).

**What I focus on:**

- Production-quality CLI tooling that works in real pipelines, not just demos
- FOCUS 1.0 compliance so cost data is portable across tools
- Deterministic, testable outputs with explicit exit codes and stable schemas
- Decision-ready artifacts: tables, markdown summaries, scenario comparisons, executive reports
- Full Cloud+AI+SaaS coverage — every spend category the FinOps Foundation 2026 Framework defines

**Tech stack:** Python, AWS (Cost Explorer, IAM, boto3), SQL, TypeScript/React for dashboards

---

## Projects

- **[dianuhs/finops-lite](https://github.com/dianuhs/finops-lite)** — AWS/Azure/GCP cost visibility CLI with FOCUS 1.0 export
- **[dianuhs/finops-watchdog](https://github.com/dianuhs/finops-watchdog)** — anomaly detection from any cost CSV
- **[dianuhs/recovery-economics](https://github.com/dianuhs/recovery-economics)** — resilience cost modeling with scenario compare
- **[dianuhs/ai-cost-lens](https://github.com/dianuhs/ai-cost-lens)** — AI spend observability: OpenAI, Anthropic, Bedrock → FOCUS 1.0
- **[dianuhs/saas-cost-analyzer](https://github.com/dianuhs/saas-cost-analyzer)** — SaaS spend governance: unused licenses, per-seat costs, forecasting
- **[dianuhs/cloud-cost-guard](https://github.com/dianuhs/cloud-cost-guard)** — open-source cloud cost dashboard
- **[dianuhs/tech-spend-command-center](https://github.com/dianuhs/tech-spend-command-center)** — executive summary: unified Cloud+AI+SaaS report

---

*Finance background. FinOps focus. Production tooling.*
