# Skills and evidence matrix

This is a **portfolio audit**, not a proficiency score. A tool is "evidenced" only in the scope shown; it does not imply expert competence in that entire domain.

| Skill or technology | Demonstrated context | Evidence anchor | Status |
| --- | --- | --- | --- |
| Vercel application deployment | Flownix, LeadAtlas, RouteTill, ReturnTail and other web applications | Individual [README sections](../README.md#case-studies) | Deployed in selected projects |
| Neon / PostgreSQL | Migrations, transactional persistence, access controls and API data | [Flownix](https://github.com/sopskistar/Flownix) / [LeadAtlas](https://github.com/sopskistar/LeadAtlas) / [ReturnTail](https://github.com/sopskistar/returntail) | Implemented |
| Supabase | Auth/persistent data integration in selected applications; practice not equivalent to Neon operations | [EverRelay](https://github.com/sopskistar/everrelay) | Project-specific |
| Railway / hosted workers | Discord gateway worker in AgenticOps; not universal across all projects | [AgenticOps AI](https://github.com/sopskistar/agentic-community-ops) | Project-specific, deployment state to recheck |
| Render | Worker deployment preparation and platform exploration | [Flownix worker deployment](https://github.com/sopskistar/Flownix/blob/main/docs/WORKER_DEPLOYMENT.md) | **Not proven as an active paid production host** |
| GitHub Actions | CI/build/test workflows in Flownix, LeadAtlas and Cuelira | [Flownix CI](https://github.com/sopskistar/Flownix/actions) · [Cuelira CI](https://github.com/sopskistar/Cuelira/actions) | Implemented in selected repos |
| Docker / Compose | Flownix local PostgreSQL development and portable worker setup | [Flownix README](https://github.com/sopskistar/Flownix#cloud-engineering--devops) | Local/dev, not a production Kubernetes fleet |
| Linux / WSL | Node tooling, builds, debugging and terminal workflows | [Cuelira](https://github.com/sopskistar/Cuelira) · [Flownix](https://github.com/sopskistar/Flownix) | Hands-on development |
| DNS / HTTPS / custom domains | deployed application connectivity and troubleshooting | [Flownix](https://flownix.xyz) · [LeadAtlas](https://leadatlas.xyz) | Application deployment scope |
| REST APIs, RPC, auth and retries | Flownix, LeadAtlas, RouteTill, ReturnTail | project code and technical documentation | Implemented |
| Tests / browser automation | Playwright QA and project regressions | [Playwright QA](https://github.com/sopskistar/playwright-qa) | Implemented |
| AWS | Cloud Quest/labs learning | [AWS hands-on practice](https://github.com/sopskistar/AWS-hands-on-projects) | Learning labs; no AWS production operations claim |
| Terraform | No applied infrastructure plan demonstrated | [Future roadmap](INFRASTRUCTURE_ROADMAP.md) | **Not yet evidenced** |
| Kubernetes | No cluster rollout independently verified | [Future roadmap](INFRASTRUCTURE_ROADMAP.md) | **Not yet evidenced** |
| Prometheus/Grafana | No sustained metrics/alerting deployment independently verified | [Future roadmap](INFRASTRUCTURE_ROADMAP.md) | **Not yet evidenced** |
| Backup + restore | Operational guidance may exist; no validated restoration drill across these projects | project deployment docs | **Needs verification** |

**How to change status:** add a commit, deployed environment, reproducible test/plan or meaningful incident report; then edit this matrix. Do not upgrade a status because a tool is listed in a design document.
