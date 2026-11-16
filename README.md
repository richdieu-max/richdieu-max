## Rich Dieu

**Cloud, Identity & Endpoint Security Engineer · Azure · Entra ID · Intune · Microsoft 365 · AWS · RHEL · NIST 800-53 · GxP**

I build and secure cloud environments, Microsoft first, with AWS and Red Hat Enterprise Linux alongside, for organisations that get audited: pharmaceutical and biotech R&D, legal, and compliance software. About seven years in, from help desk to system administration to cloud and security engineering, with the same habit throughout: if it isn't documented and evidenced, it isn't done. The [SOP library](https://github.com/richdieu-max/sop-library) is the proof: 44 runbooks with 125 architecture, flow and concept diagrams, each one written from work I have done.

![Skill map: nine areas of hands-on work and the SOPs that document each one](assets/skill-map.svg)

**What I work on**

- **Identity & access:** Entra ID, Conditional Access, phishing-resistant MFA, PIM and just-in-time access, joiner-mover-leaver lifecycle, Temporary Access Pass, hybrid identity, federated SSO (SAML, OIDC)
- **Azure infrastructure:** tenant and landing-zone builds as code (Bicep, Azure CLI, PowerShell), management groups, Azure Policy guardrails, Trusted Launch VMs, point-to-site VPN, Key Vault, private endpoints
- **AWS:** account foundations with IAM Identity Center, CloudTrail, GuardDuty, Security Hub and AWS Config; hardened EC2 (IMDSv2, KMS, Session Manager), service control policies, Client VPN with SAML, AWS Backup with Vault Lock, Elastic Disaster Recovery
- **Linux (RHEL 8 and 9):** hardening with Ansible and OpenSCAP (CIS), SELinux, firewalld, auditd, patching with dnf-automatic and maintenance windows, Active Directory join with realmd and SSSD, troubleshooting
- **Backup & DR:** Azure Backup, Veeam Backup for Azure, Azure Site Recovery, AWS Backup, two-region designs with tested RPO/RTO
- **Security assessment:** STRIDE threat modeling, secrets and supply-chain scanning (gitleaks, Trivy, Dependabot), network segmentation reviews against CIS and Defender for Cloud, logging validation with KQL, control crosswalks
- **Security operations:** vulnerability remediation with Qualys and Microsoft Defender, business email compromise containment in Entra ID and Exchange Online, EDR migrations
- **Endpoint management:** Intune for Windows and macOS, Windows Autopilot, update rings (WUfB), Defender for Endpoint, Apple Business Manager and Jamf Pro, Tanium, ConfigMgr, Multi Admin Approval
- **Windows & Active Directory:** Group Policy, DHCP and domain repair, SMB and mapped drives, USB serial devices, remote fixes with Invoke-Command and Intune Remediations
- **Regulated lab IT (GxP):** 21 CFR Part 11 and EU GMP Annex 11 change control, validated workstations, lab application modernisation (Windows 7 to 11, Hyper-V), compliance data agents, BeyondTrust PRA, LIMS, Zebra and BarTender label printing
- **Microsoft 365 & migration:** file shares to Teams and SharePoint (Migration Manager, SPMT), server rehosting with Azure Migrate or AWS Application Migration Service
- **Automation:** PowerShell and Microsoft Graph, Python and boto3, Ansible, read-only evidence collection
- **Frameworks:** NIST SP 800-53 and CSF 2.0, ISO/IEC 27001, 21 CFR Part 11 and ALCOA+ data integrity, HIPAA Security Rule, PCI DSS, CIS Benchmarks and Controls

![How the projects fit together: build with the runbooks, prove with azure-posture-check, assess with security-assessment-toolkit, and write it all down in the SOP library](assets/portfolio-overview.svg)

### Projects

| Project | What it is |
|---|---|
| [sop-library](https://github.com/richdieu-max/sop-library) | 44 runbooks with 125 diagrams across Azure, Entra ID, Intune, AWS, RHEL, security operations, GxP lab IT and Windows support: console steps, PowerShell / CLI, at-scale methods, verification, rollback and control mapping |
| [azure-posture-check](https://github.com/richdieu-max/azure-posture-check) | Read-only PowerShell posture check for an Azure subscription: PASS/WARN/FAIL per control, NIST mapping, SHA-256 evidence manifest, Pester tests in CI. Also holds the Tenant Hardening Assessment SOP and script skeleton |
| [aws-posture-check](https://github.com/richdieu-max/aws-posture-check) | The same method for AWS in Python and boto3: nine areas across regions, NIST mapping, hashed evidence, pytest suite against a fictional account |
| [rhel-hardening](https://github.com/richdieu-max/rhel-hardening) | Ansible role for a RHEL 8 and 9 baseline, proven by an OpenSCAP scan turned into hashed evidence with NIST references |
| [security-assessment-toolkit](https://github.com/richdieu-max/security-assessment-toolkit) | The workbook behind my assessments: threat model, risk register with formula-driven severity, control register, compliance mapping, logging validation |
| [endpoint-identity-runbooks](https://github.com/richdieu-max/endpoint-identity-runbooks) | Short-form runbooks with architecture diagrams and control mappings |

**Runbooks**

| Runbook | What it covers |
|---|---|
| [Azure tenant foundation](https://github.com/richdieu-max/endpoint-identity-runbooks/blob/main/runbooks/azure-tenant-foundation.md) | Break-glass accounts, MFA, domain, management groups and policy |
| [Point-to-site VPN with Entra ID sign-in](https://github.com/richdieu-max/endpoint-identity-runbooks/blob/main/runbooks/azure-p2s-vpn-entra-id.md) | Admin access to private VMs through an MFA-protected tunnel |
| [Two-region backup and DR design](https://github.com/richdieu-max/endpoint-identity-runbooks/blob/main/runbooks/azure-backup-dr-two-region.md) | 4-hour recovery points, immutable off-site copies, tiered RPO/RTO |
| [Defender for Endpoint on macOS via Intune](https://github.com/richdieu-max/endpoint-identity-runbooks/blob/main/runbooks/macos-defender-for-endpoint-via-intune.md) | Zero-prompt onboarding of managed Macs |
| [Two-person control for device wipe](https://github.com/richdieu-max/endpoint-identity-runbooks/blob/main/runbooks/intune-multi-admin-approval-device-wipe.md) | Intune Multi Admin Approval for wipe, retire and delete |

**Certifications:** Microsoft SC-300 Identity and Access Administrator · CompTIA Security+ (in progress)

**Elsewhere:** [richdieu.com](https://richdieu.com) · [LinkedIn](https://www.linkedin.com/in/richdieu)

<sub>Everything here is generalised from real work. No client or employer names, tenant identifiers, addresses or data appear in these repositories.</sub>
