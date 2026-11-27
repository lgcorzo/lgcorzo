# Architecture: `lgcorzo` in Dark Gravity

## Ecosystem Role & Tier

- **Tier**: `public_portal`
- **Role**: Top-level GitHub Profile repository introducing Dark Gravity, the three-tier isolation topology, maintained fork governance, flagship managed repositories, and canonical entry links to `https://lgcorzo.github.io/start-here` and `/docs/auditor/`.
- **Visibility**: `public`

## Internal Component Design

- `README.md`: GitHub profile front page rendered on `https://github.com/lgcorzo` introducing the three-tier Autonomous Software Factory pattern (Protected Core Factory, Owned Applications, Maintained Sovereign Forks).
- `AGENTS.md`, `DARK_GRAVITY_MANIFEST.md`, `REPOSITORIES.md`, `ARCHITECTURE.md`: Agent-first onboarding layer routing external auditors directly into the full ecosystem.

## Upstream & Downstream Ecosystem Interfaces

```text
GitHub Profile Visitor / AI Agent ──► lgcorzo/README.md + DARK_GRAVITY_MANIFEST.md
                                          │
                                          ├──► https://lgcorzo.github.io/start-here (/ai-agents)
                                          ├──► https://lgcorzo.github.io/docs/auditor/
                                          └──► Core & Owned Repos (rust_CACD_autonomous_factory, mlops-python-package, ...)
```

## Security Boundary & Governance

- **`DOC-011` Public Boundary**: Uses generic labels (`Internal GitOps Control Plane`, `Internal Incident Remediation Service`) and never exposes private repo names, internal IPs, or secrets.
- **Vertex 4 HITL**: Profile updates arrive only via reviewed PRs onto `main`.

## Canonical Cross-Links

- [DARK_GRAVITY_MANIFEST.md](./DARK_GRAVITY_MANIFEST.md)
- [REPOSITORIES.md](./REPOSITORIES.md)
- [Global Architecture Portal](https://lgcorzo.github.io/architecture.html)
- [Unified Start-Here Portal](https://lgcorzo.github.io/start-here)
- [AI Auditor Pack](https://lgcorzo.github.io/docs/auditor/)
