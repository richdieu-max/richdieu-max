## Rich Dieu

**Systems Engineer · Microsoft 365, Entra ID, Intune & Azure · NIST 800-53**

I build and secure Microsoft cloud environments for organisations that get audited: pharmaceutical and biotech R&D, legal, and compliance software. About seven years in, from help desk to system administration to cloud and security engineering, with the same habit throughout: if it isn't documented and evidenced, it isn't done.

**What I work on**

- **Identity:** Entra ID, Conditional Access, MFA, RBAC and just-in-time access, hybrid identity, federated SSO (SAML, OIDC)
- **Endpoints:** Intune for Windows and macOS, Defender for Endpoint, patching at scale, lab and instrument PCs in validated environments
- **Azure:** tenant and landing-zone builds, Azure Policy guardrails, Key Vault, private networking, backup and DR, logging and alerting
- **Automation:** PowerShell and Microsoft Graph, read-only evidence collection, Python for reporting
- **Compliance:** NIST SP 800-53 and CSF 2.0, ISO/IEC 27001, 21 CFR Part 11 and ALCOA+ data integrity, audit-ready documentation

![How the projects fit together: build with the runbooks, prove with azure-posture-check, assess and report with security-assessment-toolkit](assets/portfolio-overview.svg)

### Projects by discipline

**Cloud security & automation**

| Project | What it is |
|---|---|
| [azure-posture-check](https://github.com/richdieu-max/azure-posture-check) | Read-only PowerShell posture check for an Azure subscription: PASS/WARN/FAIL per control, NIST mapping, SHA-256 evidence manifest, Pester tests in CI |

**Governance, risk & compliance**

| Project | What it is |
|---|---|
| [security-assessment-toolkit](https://github.com/richdieu-max/security-assessment-toolkit) | The workbook behind my assessments: threat model, risk register with formula-driven severity, control register, compliance mapping, logging validation |

**Endpoint management**

| Runbook | What it covers |
|---|---|
| [Defender for Endpoint on macOS via Intune](https://github.com/richdieu-max/endpoint-identity-runbooks/blob/main/runbooks/macos-defender-for-endpoint-via-intune.md) | Zero-prompt onboarding of managed Macs |
| [Two-person control for device wipe](https://github.com/richdieu-max/endpoint-identity-runbooks/blob/main/runbooks/intune-multi-admin-approval-device-wipe.md) | Intune Multi Admin Approval for wipe, retire and delete |

**Identity & access**

| Runbook | What it covers |
|---|---|
| [Azure tenant foundation](https://github.com/richdieu-max/endpoint-identity-runbooks/blob/main/runbooks/azure-tenant-foundation.md) | Break-glass accounts, MFA, domain, management groups and policy |
| [Point-to-site VPN with Entra ID sign-in](https://github.com/richdieu-max/endpoint-identity-runbooks/blob/main/runbooks/azure-p2s-vpn-entra-id.md) | Admin access to private VMs through an MFA-protected tunnel |

**Infrastructure & resilience**

| Runbook | What it covers |
|---|---|
| [Two-region backup and DR design](https://github.com/richdieu-max/endpoint-identity-runbooks/blob/main/runbooks/azure-backup-dr-two-region.md) | 4-hour recovery points, immutable off-site copies, tiered RPO/RTO |

**Certifications:** Microsoft SC-300 Identity and Access Administrator · CompTIA Security+ (in progress)

**Elsewhere:** [richdieu.com](https://richdieu.com) · [LinkedIn](https://www.linkedin.com/in/richdieu)

<sub>Everything here is generalised from real work. No client or employer names, tenant identifiers, addresses or data appear in these repositories.</sub>
