# Engineering Lab — Cloud, DevOps, APIs & Reliability

**Udeorji Sopuruchi Juliana** · [GitHub profile](https://github.com/sopskistar) · [Portfolio](https://github.com/sopskistar/juliana-sopuruchi-portfolio)

A living, evidence-first record of **independent software and infrastructure engineering practice**: what I built, which services actually ran, what I tested, which failures I investigated, and what I am learning next.

> Some projects are live applications; others are local prototypes, contest builds or learning exercises. Each project's README identifies its real deployment state. I use AI-assisted development tools, but I validate integrations and document limitations instead of treating generated code as proof.

## Engineering experience by area

| Area | Implemented and evidenced | Still learning or requires separate proof |
| --- | --- | --- |
| Cloud applications | Vercel deployment, custom domains and environment configuration in selected projects | Operating a full cloud infrastructure fleet |
| Databases | PostgreSQL on Neon; database migrations, constraints and transactions; Supabase in selected projects | Demonstrated backup-restore drills for every app |
| CI and delivery | GitHub Actions workflows, regression suites, typecheck, lint and release checks in selected projects | Reproducible cross-platform delivery of every repository |
| Containers | Docker Compose/local PostgreSQL setup and portable worker configuration in Flownix | Production orchestration and proven K8s rollout |
| Networking & APIs | DNS/TLS troubleshooting, HTTP REST APIs, auth, provider integrations, webhooks, RPC calls | Deep cloud networking, infrastructure segmentation |
| Operations | Logs, diagnostics, worker heartbeats, retries, health and provider-failure investigation where documented | Tested on-call/SLO program and disaster-recovery operations |
| Infrastructure as code | No independently verified production Terraform implementation | Terraform plans and safe sandbox provisioning |

## Case studies

### Cloud platforms, backend and data processing
- [Flownix — data ingestion, jobs, OAuth, CI and Neon/Vercel](https://github.com/sopskistar/Flownix#cloud-engineering--devops) · [live](https://flownix.xyz) · 24/7 worker not yet active
- [LeadAtlas — Next.js SaaS, Neon, auth, Inngest, API integration](https://github.com/sopskistar/LeadAtlas#cloud-engineering--devops) · [live](https://leadatlas.xyz) · restricted providers not activated
- [AgenticOps AI — communication integrations, persistent worker and durable event storage](https://github.com/sopskistar/agentic-community-ops)
- [ProofFeed — Python FastAPI, provider quorum logic and diagnostics](https://github.com/sopskistar/prooffeed) · development-stage, not a production miner

### Financial systems and verification
- [RouteTill — verified cross-chain checkout and digital delivery](https://github.com/sopskistar/RouteTill#cloud-engineering--devops) · [public evidence](https://routetill.vercel.app)
- [ReturnTail — non-custodial BCH purchase/refund reconciliation](https://github.com/sopskistar/returntail#cloud-engineering--devops) · [mainnet self-test](https://returntail.vercel.app)
- [ShadowBid — sealed-bid marketplace and Zcash testnet receiving](https://github.com/sopskistar/shadowbid#cloud-engineering--devops)
- [PayGuard Verify — supplier-payment review, Sui and Walrus integration](https://github.com/sopskistar/payguard-ai#cloud-engineering--devops)
- [SplitBrief — Solana Devnet batch payment and wallet integration](https://github.com/sopskistar/SplitBrief#cloud-engineering--devops)

### API integration, desktop software and product engineering
- [CrewCover — agent-native scheduling with Neon persistence](https://github.com/sopskistar/crewcover#cloud-engineering--devops)
- [ModelSwitch Lab — server-side model gateway integration](https://github.com/sopskistar/modelswitch-lab#cloud-engineering--devops)
- [BlindCouncil — Hermes gateway plugin, SQLite and Telegram delivery recovery](https://github.com/sopskistar/blindcouncil#cloud-engineering--devops)
- [Cuelira — Electron, native SDK, Windows packaging and CI](https://github.com/sopskistar/Cuelira#cloud-engineering--devops) · physical-camera SDK acceptance remains unverified
- [DomScout — domain research and local QA](https://github.com/sopskistar/DomScout#cloud-engineering--devops) · local only
- [Playwright QA — independent end-to-end automation practice](https://github.com/sopskistar/playwright-qa)
- [AWS hands-on practice](https://github.com/sopskistar/AWS-hands-on-projects) · learning labs, not production AWS operations

## How I document new experience

1. Add a dated, reproducible record in [Engineering experience log](docs/EXPERIENCE_LOG.md).
2. Use the [project evidence template](docs/EVIDENCE_TEMPLATE.md) for architecture, deployment and test results.
3. Link the relevant project commit, GitHub Actions run, diagram and public proof. Never include secrets or private customer data.
4. Mark each capability **implemented**, **validated locally**, **deployed**, **partially verified**, **planned** or **blocked**.
5. Keep this index current, and update the corresponding project's `Cloud Engineering & DevOps` README section.

[Skill and evidence matrix](docs/SKILL_MATRIX.md) · [Learning and infrastructure roadmap](docs/INFRASTRUCTURE_ROADMAP.md)

**Professional focus:** junior cloud/backend, platform/developer support, API integration, automation, cloud operations and software QA.
