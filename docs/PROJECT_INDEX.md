# Project index and evidence status

This inventory links to the **Cloud Engineering & DevOps** section of every relevant independently maintained project documented as of 2026-11-22. Project descriptions are deliberately modest. “Deployed” means project documentation reports a deployment; it does not imply an audited SLA or paying customers.

| Repository | Main engineering area | Evidence / scope |
| --- | --- | --- |
| [Flownix](https://github.com/sopskistar/Flownix#cloud-engineering--devops) | Cloud backend/data | Vercel + Neon web verified; worker 24/7 pending |
| [LeadAtlas](https://github.com/sopskistar/LeadAtlas#cloud-engineering--devops) | Full-stack / API | Vercel + Neon; restricted providers and worker acceptance pending |
| [RouteTill](https://github.com/sopskistar/RouteTill#cloud-engineering--devops) | Payments / platform | Vercel; independently checkable mainnet settlement |
| [returntail](https://github.com/sopskistar/returntail#cloud-engineering--devops) | Payments / platform | Vercel + Neon; documented BCH mainnet self-test |
| [Cuelira](https://github.com/sopskistar/Cuelira#cloud-engineering--devops) | Desktop / CI | Electron Windows packaging; physical-camera SDK unverified |
| [DomScout](https://github.com/sopskistar/DomScout#cloud-engineering--devops) | Local research / QA | Local TypeScript application; no public deployment |
| [shadowbid](https://github.com/sopskistar/shadowbid#cloud-engineering--devops) | Privacy / fintech | Vercel/Neon; separate public Zcash testnet payment evidence |
| [payguard-ai](https://github.com/sopskistar/payguard-ai#cloud-engineering--devops) | Automation / fintech | Vercel/Neon; supported Sui and Walrus evidence |
| [modelswitch-lab](https://github.com/sopskistar/modelswitch-lab#cloud-engineering--devops) | API/AI engineering | Vercel; no app database |
| [SplitBrief](https://github.com/sopskistar/SplitBrief#cloud-engineering--devops) | Payments / integration | Vercel; Solana Devnet batch proof, no mainnet |
| [crewcover](https://github.com/sopskistar/crewcover#cloud-engineering--devops) | Automation / SaaS | Vercel + Neon; fictional demo scenario |
| [blindcouncil](https://github.com/sopskistar/blindcouncil#cloud-engineering--devops) | Plugin / reliability | Hermes gateway plugin; two owned Telegram test accounts |
| [agentic-community-ops](https://github.com/sopskistar/agentic-community-ops#cloud-engineering--devops) | Integrations / workers | Railway-compatible Discord worker; provider activation varies |
| [chogcourt](https://github.com/sopskistar/chogcourt#cloud-engineering--devops) | Web backend | Local SQLite + Vercel/Neon adapter; public deployment not verified |
| [Proofcourt](https://github.com/sopskistar/Proofcourt#cloud-engineering--devops) | API / consensus | PostgreSQL and GenLayer backend; public deployment not verified |
| [prooffeed](https://github.com/sopskistar/prooffeed#cloud-engineering--devops) | Python API / data | FastAPI/Next.js/Expo; no deployed miner |
| [sealforms](https://github.com/sopskistar/sealforms#cloud-engineering--devops) | Web prototype | Scaffold; deployment incomplete |
| [everrelay](https://github.com/sopskistar/everrelay#cloud-engineering--devops) | AI / web | Optional Supabase; Vercel deployment described but not verified |
| [everrelay-court](https://github.com/sopskistar/everrelay-court#cloud-engineering--devops) | API / smart contracts | GenLayer config-gated; deployment not verified |
| [adchain](https://github.com/sopskistar/adchain#cloud-engineering--devops) | Vite / frontend | Starter/source integration; review tracked .env configuration |
| [Goptimum.xyz](https://github.com/sopskistar/Goptimum.xyz#cloud-engineering--devops) | Generated web UI | v0 auto-sync; public Vercel URL not verified |
| [v0-gensyn-educational-website](https://github.com/sopskistar/v0-gensyn-educational-website#cloud-engineering--devops) | Generated web UI | v0 auto-sync; public Vercel URL not verified |
| [AZTEC-MEMBERSHIP-CARD](https://github.com/sopskistar/AZTEC-MEMBERSHIP-CARD#cloud-engineering--devops) | Generated web UI | v0 starter; blockchain integration not verified |
| [AWS-hands-on-projects](https://github.com/sopskistar/AWS-hands-on-projects#cloud-engineering--devops) | Cloud learning | AWS Cloud Quest and infrastructure exercises only |
| [playwright-qa](https://github.com/sopskistar/playwright-qa#cloud-engineering--devops) | QA automation | Local/CI Playwright tests; no cloud app |
| [qa-practice](https://github.com/sopskistar/qa-practice#cloud-engineering--devops) | QA / HTTP API testing | Postman, bug reports and test cases |
| [python-for-cloud](https://github.com/sopskistar/python-for-cloud#cloud-engineering--devops) | Python learning | Introductory Python exercises; no deployed cloud automation |

### Repository selection boundaries

- Excluded **velipay** for now: it currently contains only a short concept README, with no implementation/deployment evidence to document.
- Excluded empty/incomplete training repositories without a relevant README or implemented application.
- Did **not** rewrite **hermes-agent**, an upstream project/fork rather than an independently authored application case study. Its separate [BlindCouncil](https://github.com/sopskistar/blindcouncil) plugin is documented.
- Did not change any application runtime behavior while writing portfolio documentation.

### Recheck when something changes

1. Open the specific repo's README section and technical documentation.
2. Inspect the actual source and workflow run, not just a badge.
3. Change the implementation status in [SKILL_MATRIX](SKILL_MATRIX.md).
4. Add a dated [experience log](EXPERIENCE_LOG.md) entry with a commit/CI/proof link.
5. Keep unverified sources, cloud hosting and lab exercises clearly labeled.
