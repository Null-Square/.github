<div align="center">

<img src="https://raw.githubusercontent.com/Null-Square/.github/main/profile/assets/nullsquare-org-cover.png" alt="NullSquare — Secure the unknown" width="100%">

### AI-driven offensive security &amp; continuous intelligence

Scoped AI agents for **authorized** security testing — reconnaissance, scanner orchestration,
evidence-backed findings, Markdown/SARIF reports, and compliance-readiness mapping.

[**Website**](https://nullsquare.net) · [**Null AI CLI**](https://github.com/Null-Square/Null-CLi) · [**Agent Authority**](https://github.com/Null-Square/agent-authority) · [**Agent Behavior Lab**](https://github.com/Null-Square/Agent-Behavior-Lab)

</div>

---

## What we build

Modern teams need security feedback that's faster than a traditional pentest and more useful than
raw scanner output. **NullSquare** is the AI layer in between: autonomous, scoped agents that run
reproducible assessments, normalize scanner results, capture evidence, generate reports, and map
findings to the frameworks your auditors care about.

Everything runs under an authorized scope, in isolated environments, with an immutable record of
every action.

## Platform

The managed platform at **[nullsquare.net](https://nullsquare.net)** adds hosted sandboxes, team
workflows, dashboards, continuous testing, and enterprise reporting on top of the open-source core:

- **Scoped offensive agents** — autonomous reconnaissance and code-aware assessments within a defined scope.
- **Private runners** — execute assessments behind your firewall with full **data residency**.
- **Ephemeral sandboxes** — every session runs in a transient, isolated container with no persistent state or cross-contamination.
- **Evidence &amp; audit** — immutable logs capture every action, tool output, and console event for full traceability.
- **Compliance-readiness mapping** — findings mapped to OWASP Top 10, PCI DSS, ISO 27001, NIST CSF, and SOC 2.

## Open source

| Project | What it is | License |
| --- | --- | --- |
| [**Null AI CLI**](https://github.com/Null-Square/Null-CLi) | A scoped terminal agent for authorized testing: safe recon, scanner orchestration, evidence capture, Markdown/SARIF reports, and compliance-readiness mapping. | Apache-2.0 |
| [**Agent Authority**](https://github.com/Null-Square/agent-authority) | Task-bounded execution authority for AI agents: turn one human-approved task into temporary, provenance-aware authority for exact effects without handing the agent broad standing account access. | Apache-2.0 |
| [**Agent Behavior Lab**](https://github.com/Null-Square/Agent-Behavior-Lab) | A controlled-experiment lab for studying how tool-using LLM agents behave — vary tools, personas, and histories, run trials across models, and measure the effect on safety and tool-call behavior. | MIT |

```bash
# Try the CLI in one line — no install
npx @nullsquare/null-cli --help
```

## Security &amp; responsible use

- **Encryption everywhere** — AES-256 at rest, TLS 1.3 in transit, strictly scoped RBAC.
- **Isolation by default** — ephemeral, single-tenant execution with no shared state.
- **Authorized testing only** — our tooling is built for security teams operating on systems they
  own or are explicitly permitted to test. Please use it accordingly.

<div align="center">

**[nullsquare.net](https://nullsquare.net)**

<sub>Secure the unknown.</sub>

</div>
