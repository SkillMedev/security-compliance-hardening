# Security & Compliance Hardening

**Threat models, secure reviews, and compliance evidence — ship with confidence.** — built in-house by [Skill&nbsp;Me](https://skillme.dev).

Six skills covering the full defensive security lifecycle for engineering teams: threat modeling, dependency risk, secrets management, SOC 2 compliance, vulnerability triage, and secure code review. Designed for staff engineers and AppSec practitioners who need structured, opinionated guidance without the noise.

⭐ **If this is useful, star the repo** — it's how we gauge what to build next.

## Install

- **From the catalog:** [skillme.dev/pack/security-compliance-hardening](https://skillme.dev/pack/security-compliance-hardening) — install the whole pack into Claude in one step.
- **With the skills CLI:** `npx skills add aouellets/security-compliance-hardening`
- **Manually:** copy any `skills/<slug>/SKILL.md` into your Claude skills directory.

## Skills in this pack

- **[Threat Model STRIDE](skills/threat-model-stride/SKILL.md)** — Runs a STRIDE threat model on a feature or system, surfaces high-priority threats, and recommends concrete mitigations.
- **[Dependency Risk Audit](skills/dependency-risk-audit/SKILL.md)** — Assesses third-party dependency risk across CVEs, maintenance health, license exposure, and supply-chain hygiene.
- **[Secrets Hygiene](skills/secrets-hygiene/SKILL.md)** — Prevents and remediates leaked secrets and credentials in source code, CI, logs, and config.
- **[SOC 2 Evidence Helper](skills/soc2-evidence-helper/SKILL.md)** — Organizes SOC 2 Type I and Type II evidence collection, maps controls to Trust Service Criteria, and reduces audit busywork.
- **[Vulnerability Triage](skills/vulnerability-triage/SKILL.md)** — Triages and prioritizes vulnerability findings by real-world exploitability and business impact, cutting through scanner noise.
- **[Secure Code Review](skills/secure-code-review/SKILL.md)** — Reviews code for high-impact security flaws including broken authorization, injection, SSRF, and unsafe deserialization.
- **[Security Audit](aouellets)** — Reviews code for OWASP Top 10 vulnerabilities with concrete fix recommendations. _(external — see source)_
- **[PII Scrubber](skills/pii-scrubber/SKILL.md)** — Detects and redacts 18 categories of PII from text, logs, and structured data.

## License

MIT — see [LICENSE](LICENSE). Skills are portable `SKILL.md` files; the canonical
copies live in the [Skill&nbsp;Me catalog](https://skillme.dev).
