# Infrastructure growth roadmap

Learn deeper cloud engineering by **adding evidence to existing apps**, not artificially deploying complicated stacks.

## 1. Container reliability — Flownix
- [ ] Build and run a documented Docker image for the worker with reproducible logs.
- [ ] Test startup and DB connectivity in a clean Docker Compose environment.
- [ ] Document ports, service names, health probes, secrets and failure recovery.
- [ ] Save `docker compose config` output and a CI build log without secret values.

## 2. CI and secure releases — LeadAtlas
- [ ] Verify the repository's exact GitHub Actions workflow gates.
- [ ] Require test/typecheck/build checks before protected branch deployment where permissions permit.
- [ ] Test staged migration/runbook steps in a disposable database.
- [ ] Separate staging and production secrets and record how rollbacks are tested.

## 3. DNS and TLS — DomScout or a disposable domain
- [ ] Document actual A/AAAA/MX/NS/TXT/CNAME lookups and resolver results.
- [ ] Diagnose one real HTTP/TLS or nameserver issue with `dig`, `curl` and `openssl s_client`.
- [ ] Add input validation and bounded timeouts to a DNS health-check API only if it fits DomScout's product scope.

## 4. Terraform, from a safe sandbox
- [ ] Choose one low-cost provider and write a tiny test environment.
- [ ] Run `terraform fmt`, `validate` and inspect `plan` without committing credentials/state.
- [ ] Apply and destroy the **sandbox** once, documenting actual resources and cost.
- [ ] Only then add Terraform to the `Implemented` section of the relevant README.

## 5. Kubernetes, locally
- [ ] Run a small local Kind/Minikube cluster.
- [ ] Deploy one container and verify readiness, logs, service access and failure recovery.
- [ ] Document why the real project does or does not need Kubernetes.

## 6. Observability and disaster recovery
- [ ] Instrument a meaningful endpoint and worker diagnostic.
- [ ] Record real log/metric observations under defined failure conditions.
- [ ] Test a database backup-and-restore into an isolated database.
- [ ] Document an incident simulation with detection, diagnosis, repair and retest.

**Rule:** never add a future tool to a resume as production experience until the corresponding exercise is implemented, observed and documented.
