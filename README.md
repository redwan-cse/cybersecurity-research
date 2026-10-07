<div align="center">

# 🛡️ Cybersecurity Research & Detection Engineering Artifacts

### Production-Grade Threat Models, Sigma Rules, Falco Policies & Blue Team Hardening Artifacts
Companion to the research publications on [blogs.redwan.work](https://blogs.redwan.work/)

[![Publication](https://img.shields.io/badge/Research_Blog-blogs.redwan.work-00DC82?style=for-the-badge&logo=blogger)](https://blogs.redwan.work)
[![Portfolio](https://img.shields.io/badge/Author-redwan.work-0A66C2?style=for-the-badge&logo=google-chrome)](https://redwan.work)
[![LinkedIn](https://img.shields.io/badge/Connect-redwancse-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/redwancse)

---

</div>

## 📌 About This Repository

This repository hosts official detection artifacts, Sigma YAML rules, Falco policies, and blue team mitigation configurations accompanying the in-depth offensive and defensive research published on **[blogs.redwan.work](https://blogs.redwan.work/)**.

Every research entry follows **The Rule of Pairs**:
- **⚔️ Attack Mechanics / Threat Model**: Root-cause analysis, memory corruption, protocol abuse primitives, and exploit chains.
- **🛡️ Blue Team Defense / Hardening**: Production detection telemetry, Sysmon / Event ID mappings, Sigma rules, and kernel policies.

---

## 🔥 Featured & High-Priority Research

| Date | Topic / Focus | Threat Model & Exploitation Mechanics | Blue Team Hardening & Detection Guide |
|---|---|---|---|
| 2026-10 | **LiteLLM AI Gateway** | [LiteLLM: Deconstructing AI Gateway MCP RCE Chain](https://blogs.redwan.work/2026/10/litellm-deconstructing-ai-gateway-mcp.html) | [Hardening LiteLLM AI Gateway: Blue Team Guide](https://blogs.redwan.work/2026/10/hardening-litellm-ai-gateway-blue-team.html) |
| 2026-10 | **Active Directory PKI** | [AD CS ESC8: Deconstructing NTLM Relay to Web Enrollment](https://blogs.redwan.work/2026/10/ad-cs-esc8-deconstructing-ntlm-relay-to.html) | [Hardening AD CS Web Enrollment: Defense Guide](https://blogs.redwan.work/2026/10/hardening-ad-cs-web-enrollment-blue.html) |
| 2026-10 | **Federated Identity** | [Golden SAML: Deconstructing ADFS Token Forgery](https://blogs.redwan.work/2026/10/golden-saml-deconstructing-adfs-token.html) | [Hardening AD FS: Blue Team Golden SAML Defense](https://blogs.redwan.work/2026/10/hardening-ad-fs-blue-team-golden-saml.html) |
| 2026-10 | **Linux Kernel Privilege Escalation** | [Linux Kernel Dirty Pipe: Page Cache Overwrite](https://blogs.redwan.work/2026/10/linux-kernel-dirty-pipe-deconstructing.html) | [Hardening Linux Against Dirty Pipe: Blue Team Guide](https://blogs.redwan.work/2026/10/hardening-linux-against-dirty-pipe-blue.html) |
| 2026-09 | **Linux Kernel eBPF** | [Linux Kernel eBPF: Verifier Logic Flaws](https://blogs.redwan.work/2026/09/linux-kernel-ebpf-deconstructing.html) | [Hardening Linux Kernel eBPF: Blue Team Guide](https://blogs.redwan.work/2026/09/hardening-linux-kernel-ebpf-blue-team.html) |
| 2026-09 | **Cloud IAM (GCP)** | [GCP IAM: Service Account Impersonation Deep-Dive](https://blogs.redwan.work/2026/09/gcp-iam-service-account-impersonation.html) | [Hardening GCP Service Accounts: Blue Team Guide](https://blogs.redwan.work/2026/09/hardening-gcp-service-accounts-blue.html) |
| 2026-09 | **Active Directory Replication** | [Active Directory DCSync: MS-DRSR Architecture](https://blogs.redwan.work/2026/09/active-directory-dcsync-deconstructing.html) | [Hardening Active Directory: DCSync Defense Guide](https://blogs.redwan.work/2026/09/hardening-active-directory-blue-team_0958470769.html) |

---

## 📚 Complete Permanent Research Catalog

<!-- RESEARCH-CATALOG-START -->
| Date | Research Publication | Category | Full Technical Writeup |
|---|---|---|---|
| 2026-10-07 | **Hardening GitLab CI/CD: Blue Team Pipeline Defense Guide** | `DevSecOps` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/10/hardening-gitlab-cicd-blue-team.html) |
| 2026-10-07 | **GitLab: Deconstructing CI/CD Pipeline Impersonation** | `DevSecOps` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/10/gitlab-deconstructing-cicd-pipeline.html) |
| 2026-10-06 | **Hardening AWS EKS Pod Identity: Blue Team Defense Guide** | `Cloud & Infrastructure Security` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/10/hardening-aws-eks-pod-identity-blue.html) |
| 2026-10-06 | **AWS EKS Pod Identity: Deconstructing Workload Token Interception** | `Cloud Security` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/10/aws-eks-pod-identity-deconstructing.html) |
| 2026-10-06 | **Hardening LiteLLM AI Gateway: Blue Team Defense Guide** | `AI Security` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/10/hardening-litellm-ai-gateway-blue-team.html) |
| 2026-10-05 | **LiteLLM: Deconstructing AI Gateway MCP RCE Chain** | `AI Security` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/10/litellm-deconstructing-ai-gateway-mcp.html) |
| 2026-10-05 | **Hardening AD FS: Blue Team Golden SAML Defense Guide** | `Active Directory` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/10/hardening-ad-fs-blue-team-golden-saml.html) |
| 2026-10-04 | **Golden SAML: Deconstructing ADFS Token Forgery Architecture** | `Active Directory` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/10/golden-saml-deconstructing-adfs-token.html) |
| 2026-10-04 | **Hardening Citrix NetScaler: Blue Team Defense Guide** | `Infra & CI/CD` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/10/hardening-citrix-netscaler-blue-team.html) |
| 2026-10-03 | **Hardening Linux Against Dirty Pipe: Blue Team Defense Guide** | `Kernel & Linux` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/10/hardening-linux-against-dirty-pipe-blue.html) |
| 2026-10-02 | **Linux Kernel Dirty Pipe: Deconstructing Page Cache Overwrite Mechanics** | `Kernel & Linux` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/10/linux-kernel-dirty-pipe-deconstructing.html) |
| 2026-10-02 | **Hardening AD CS Web Enrollment: Blue Team Defense Guide** | `Active Directory` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/10/hardening-ad-cs-web-enrollment-blue.html) |
| 2026-10-01 | **AD CS ESC8: Deconstructing NTLM Relay to Web Enrollment** | `Active Directory` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/10/ad-cs-esc8-deconstructing-ntlm-relay-to.html) |
| 2026-10-01 | **Hardening Jenkins Controllers: Blue Team Defense Guide** | `Infra & CI/CD` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/10/hardening-jenkins-controllers-blue-team.html) |
| 2026-09-30 | **Jenkins Core: Deconstructing the CLI File Read RCE Chain** | `Infra & CI/CD` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/09/jenkins-core-deconstructing-cli-file.html) |
| 2026-09-30 | **Hardening GCP Service Accounts: Blue Team Defense Guide** | `Cloud Security` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/09/hardening-gcp-service-accounts-blue.html) |
| 2026-09-29 | **GCP IAM: Service Account Impersonation Deep-Dive** | `Cloud Security` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/09/gcp-iam-service-account-impersonation.html) |
| 2026-09-29 | **Hardening Ray AI Clusters: Blue Team Defense Guide** | `AI Security` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/09/hardening-ray-ai-clusters-blue-team.html) |
| 2026-09-28 | **Ray AI Framework: Deconstructing ShadowRay Cluster RCE** | `AI Security` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/09/ray-ai-framework-deconstructing.html) |
| 2026-09-28 | **Hardening Active Directory: Blue Team DCSync Defense Guide** | `Active Directory` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/09/hardening-active-directory-blue-team_0958470769.html) |
| 2026-09-27 | **Active Directory DCSync: Deconstructing MS-DRSR Architecture** | `Active Directory` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/09/active-directory-dcsync-deconstructing.html) |
| 2026-09-27 | **Hardening Ivanti Connect Secure: Blue Team Defense Guide** | `Infra & CI/CD` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/09/hardening-ivanti-connect-secure-blue.html) |
| 2026-09-26 | **Ivanti Connect Secure: Deconstructing the Edge Zero-Day Chain** | `Infra & CI/CD` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/09/ivanti-connect-secure-deconstructing.html) |
| 2026-09-26 | **Hardening Linux Kernel eBPF: Blue Team Defense Guide** | `Kernel & Linux` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/09/hardening-linux-kernel-ebpf-blue-team.html) |
| 2026-09-25 | **Linux Kernel eBPF: Deconstructing Verifier Logic Flaws** | `Kernel & Linux` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/09/linux-kernel-ebpf-deconstructing.html) |
| 2026-09-25 | **Hardening Active Directory: Blue Team RBCD Defense Guide** | `Active Directory` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/09/hardening-active-directory-blue-team.html) |
| 2026-09-24 | **Active Directory RBCD: Deconstructing Kerberos Delegation** | `Active Directory` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/09/active-directory-rbcd-deconstructing.html) |
| 2026-09-24 | **Hardening TeamCity: Blue Team Defense Guide** | `Infra & CI/CD` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/09/hardening-teamcity-blue-team-defense.html) |
| 2026-09-23 | **TeamCity: Deconstructing CI/CD Pipeline RCE** | `Infra & CI/CD` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/09/teamcity-deconstructing-cicd-pipeline.html) |
| 2026-09-23 | **Hardening Azure Managed Identity: Blue Team Defense Guide** | `Cloud Security` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/09/hardening-azure-managed-identity-blue.html) |
| 2026-09-22 | **Azure Managed Identity: Exploiting IMDS for Cloud Escalation** | `Cloud Security` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/09/azure-managed-identity-exploiting-imds.html) |
| 2026-09-22 | **Hardening Ollama: Blue Team Defense Guide** | `AI Security` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/09/hardening-ollama-blue-team-defense-guide.html) |
| 2026-09-21 | **Ollama: Deconstructing the Probllama RCE** | `AI Security` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/09/ollama-deconstructing-probllama-rce.html) |
| 2026-09-21 | **Hardening Linux Binaries: Blue Team Defense Guide** | `Kernel & Linux` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/09/hardening-linux-binaries-blue-team.html) |
| 2026-09-20 | **XZ Utils: Deconstructing the IFUNC Backdoor** | `Kernel & Linux` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/09/xz-utils-deconstructing-ifunc-backdoor.html) |
| 2026-09-20 | **Hardening FortiManager: Blue Team Defense Guide** | `Infra & CI/CD` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/09/hardening-fortimanager-blue-team.html) |
| 2026-09-19 | **FortiManager FortiJump: Threat Modeling the FGFM Zero-Day** | `Infra & CI/CD` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/09/fortimanager-fortijump-threat-modeling.html) |
| 2026-09-19 | **Hardening Linux Kernel nf_tables: Blue Team Defense Guide** | `Kernel & Linux` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/09/hardening-linux-kernel-nftables-blue.html) |
| 2026-09-18 | **Linux Kernel CVE-2024-1086: Deconstructing the nf_tables UAF** | `Kernel & Linux` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/09/linux-kernel-cve-2024-1086.html) |
| 2026-09-18 | **Hardening Active Directory: Shadow Credentials Defense Guide** | `Active Directory` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/09/hardening-active-directory-shadow.html) |
| 2026-09-17 | **Active Directory Shadow Credentials: msDS-KeyCredentialLink Abuse** | `Active Directory` | [Read Full Analysis & Threat Model](https://blogs.redwan.work/2026/09/active-directory-shadow-credentials.html) |
<!-- RESEARCH-CATALOG-END -->

---

## 📁 Repository Structure

```text
cybersecurity-research/
├── detections/
│   ├── sigma/          # Sigma detection rules (YAML)
│   ├── falco/          # Falco eBPF runtime detection policies
│   └── audit-scripts/  # PowerShell, Bash & Python audit scripts
├── README.md           # Research catalog and direct publication links
```

---

## 👨‍💻 Author & Research Inquiries

- **Author**: **Md. Redwan Ahmed** (Founder & CEO, [Fast Cyber Defense](https://fastcyberdefense.com))
- **Research Publication**: [blogs.redwan.work](https://blogs.redwan.work)
- **Portfolio**: [redwan.work](https://redwan.work)
- **LinkedIn**: [linkedin.com/in/redwancse](https://www.linkedin.com/in/redwancse)
- **ORCID**: [0009-0001-9419-4760](https://orcid.org/0009-0001-9419-4760)
