# Learn-SecByte-CTF-Labs-Collection-Cloud-Security-IaC-Hardening-Serverless-Incident-Response
A curated collection of hands-on cloud security CTF labs covering Terraform/CloudFormation IaC Hardening, Secrets Management &amp; KMS, Serverless Security, Cloud Privilege Escalation, Incident Response, and Multi-Cloud Architecture from Learn SecByte.
# Learn SecByte CTF & Cybersecurity Labs Collection

Welcome to the **Learn SecByte CTF & Cybersecurity Labs Collection**. This repository is a dedicated, searchable index of hands-on cloud security architecture, Infrastructure as Code (IaC) static analysis, Key Management Services (KMS) & secrets management, serverless security, cloud privilege escalation, digital forensics, and native threat detection labs designed for cybersecurity students, CTF players, cloud security engineers, DevSecOps practitioners, and DFIR specialists.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Securing cloud-native environments requires controlling every layer of the lifecycle—from static Infrastructure as Code templates and secret store configurations to runtime serverless functions, identity policies, and cloud incident response pipelines. Hosted on [Learn SecByte](https://learn.secbyte.org/), this comprehensive cloud security collection provides rigorous, practical training across multi-cloud security domains (AWS, Azure, GCP).

From auditing Terraform and CloudFormation templates for deployment security flaws, managing envelope encryption in Key Management Services (KMS), and investigating AWS Lambda/GCP Cloud Function compromises, to weaponizing misconfigured IAM roles, detecting cloud persistence, conducting CloudTrail/Flow Log digital forensics, and hardening cloud control planes, these labs build full-stack cloud defense expertise.

---

## Lab Collection & Index

Below is the complete, searchable index of all cloud security, IaC hardening, secrets management, serverless defense, and cloud incident response challenges in this collection:

| # | Lab / Challenge Name | Category | Focus / Key Topics | Lab Link |
|---|----------------------|----------|---------------------|----------|
| 1 | **Terraform & CloudFormation Security** | Infrastructure as Code & Hardening | Static code analysis (`tfsec`, `Checkov`), overly permissive security groups, unencrypted storage buckets, public access blocks | [Access Lab](https://learn.secbyte.org/ctf/terraform-cloudformation-security) |
| 2 | **Secrets Management and Key Management Services** | Infrastructure as Code & Hardening | KMS key policies, envelope encryption, AWS Secrets Manager / Azure Key Vault abuse, secret rotation, hardcoded credential hunting | [Access Lab](https://learn.secbyte.org/ctf/secrets-management-and-key-management-services) |
| 3 | **Cloud Security Hardening Best Practices** | Infrastructure as Code & Hardening | Center for Internet Security (CIS) Benchmarks, cloud posture management (CSPM), multi-account organization governance, SCPs | [Access Lab](https://learn.secbyte.org/ctf/cloud-security-hardening-best-practices) |
| 4 | **Serverless Security: Fundamentals to Advanced Incident Response** | Serverless & Runtime Security | AWS Lambda / Azure Functions security, event source injection, layer tampering, transient runtime forensics, execution context reuse | [Access Lab](https://learn.secbyte.org/ctf/serverless-security-fundamentals-to-advanced-incident-respon) |
| 5 | **Cloud Enumeration and Attack Techniques** | Cloud Attacks & Privilege Escalation | S3/Blob storage scanning, unauthenticated API discovery, metadata endpoint (IMDSv1/v2) auditing, ScoutSuite | [Access Lab](https://learn.secbyte.org/ctf/cloud-enumeration-and-attack-techniques) |
| 6 | **Cloud Privilege Escalation: Misconfigured IAM to Full Control** | Cloud Attacks & Privilege Escalation | AWS IAM policy evaluation, wildcard permissions (`*`), `iam:PassRole` abuse, assume role chaining | [Access Lab](https://learn.secbyte.org/ctf/cloud-privilege-escalation-misconfigured-iam-full-control) |
| 7 | **Cloud Persistence & Lateral Movement: Defending Identity in the Cloud** | Cloud Attacks & Privilege Escalation | Backdoor role creation, service principal abuse, federated trust exploitation, cross-account lateral movement | [Access Lab](https://learn.secbyte.org/ctf/cloud-persistence-and-lateral-movement-defending-identity-in) |
| 8 | **Cloud Incident Response & Digital Forensics** | Cloud Forensics & Native Defense | CloudTrail log parsing, memory/disk snapshot analysis, S3/blob timeline reconstruction, incident containment | [Access Lab](https://learn.secbyte.org/ctf/cloud-incident-response-digital-forensics) |
| 9 | **Cloud Watchtower: AWS Security Services Deep Dive** | Cloud Forensics & Native Defense | AWS GuardDuty threat detection, AWS Security Hub integration, Macie data discovery, IAM Access Analyzer | [Access Lab](https://learn.secbyte.org/ctf/cloud-watchtower-aws-security-services-deep-dive) |
| 10 | **Microsoft Defender for Cloud: Azure Security Center Defense** | Cloud Forensics & Native Defense | Azure Defender, Secure Score optimization, Just-In-Time (JIT) VM access, Workload Protection alert triage | [Access Lab](https://learn.secbyte.org/ctf/microsoft-defender-for-cloud-azure-security-center-cloud-def) |
| 11 | **Google Cloud Security Command Center: Detection, Triage & Response** | Cloud Forensics & Native Defense | GCP SCC alert triage, anomaly detection, Security Health Analytics, event response automation | [Access Lab](https://learn.secbyte.org/ctf/google-cloud-security-command-center-detection-triage-respon) |
| 12 | **Multi-Cloud Security Architecture: Identity & Network Control Planes** | Architecture & Enterprise Governance | Zero Trust architecture, cross-cloud identity federation, transit gateways, unified policy management | [Access Lab](https://learn.secbyte.org/ctf/multi-cloud-security-architecture-identity-network-control-p) |

---

## Categories

### 1. Infrastructure as Code, Secrets Management & Hardening
Audit Terraform and CloudFormation templates, manage key management services (KMS), and enforce CIS Benchmark hardening controls.
- [Terraform & CloudFormation Security](https://learn.secbyte.org/ctf/terraform-cloudformation-security)
- [Secrets Management and Key Management Services](https://learn.secbyte.org/ctf/secrets-management-and-key-management-services)
- [Cloud Security Hardening Best Practices](https://learn.secbyte.org/ctf/cloud-security-hardening-best-practices)

### 2. Cloud Attacks, IAM Escalation & Serverless Exploitation
Discover cloud attack surfaces, exploit IAM policy misconfigurations, compromise serverless function runtimes, and establish identity persistence.
- [Cloud Enumeration and Attack Techniques](https://learn.secbyte.org/ctf/cloud-enumeration-and-attack-techniques)
- [Cloud Privilege Escalation: Misconfigured IAM to Full Control](https://learn.secbyte.org/ctf/cloud-privilege-escalation-misconfigured-iam-full-control)
- [Cloud Persistence & Lateral Movement: Defending Identity in the Cloud](https://learn.secbyte.org/ctf/cloud-persistence-and-lateral-movement-defending-identity-in)
- [Serverless Security: Fundamentals to Advanced Incident Response](https://learn.secbyte.org/ctf/serverless-security-fundamentals-to-advanced-incident-respon)

### 3. Cloud Digital Forensics, Native Threat Detection & Triage
Parse audit log streams, perform snapshot forensics, and triage security alerts in native AWS, Azure, and Google Cloud security suites.
- [Cloud Incident Response & Digital Forensics](https://learn.secbyte.org/ctf/cloud-incident-response-digital-forensics)
- [Cloud Watchtower: AWS Security Services Deep Dive](https://learn.secbyte.org/ctf/cloud-watchtower-aws-security-services-deep-dive)
- [Microsoft Defender for Cloud: Azure Security Center Defense](https://learn.secbyte.org/ctf/microsoft-defender-for-cloud-azure-security-center-cloud-def)
- [Google Cloud Security Command Center: Detection, Triage & Response](https://learn.secbyte.org/ctf/google-cloud-security-command-center-detection-triage-respon)

### 4. Multi-Cloud Architecture & Enterprise Governance
Design federated Zero Trust architecture models, secure network control planes, and enforce cross-cloud security policies.
- [Multi-Cloud Security Architecture: Identity & Network Control Planes](https://learn.secbyte.org/ctf/multi-cloud-security-architecture-identity-network-control-p)

---

## Learning Path

Follow this structured progression path to build complete, end-to-end expertise in cloud security engineering, DevSecOps, and cloud incident response:

1. **Phase 1: Shift-Left IaC Security, KMS & Hardening** — Audit deployment code and manage encryption secrets before cloud provisioning:
   - [Terraform & CloudFormation Security](https://learn.secbyte.org/ctf/terraform-cloudformation-security)
   - [Secrets Management and Key Management Services](https://learn.secbyte.org/ctf/secrets-management-and-key-management-services)
   - [Cloud Security Hardening Best Practices](https://learn.secbyte.org/ctf/cloud-security-hardening-best-practices)

2. **Phase 2: Cloud IAM Escalation & Serverless Exploitation** — Analyze attack vectors across identity roles and serverless runtimes:
   - [Cloud Enumeration and Attack Techniques](https://learn.secbyte.org/ctf/cloud-enumeration-and-attack-techniques)
   - [Cloud Privilege Escalation: Misconfigured IAM to Full Control](https://learn.secbyte.org/ctf/cloud-privilege-escalation-misconfigured-iam-full-control)
   - [Serverless Security: Fundamentals to Advanced Incident Response](https://learn.secbyte.org/ctf/serverless-security-fundamentals-to-advanced-incident-respon)
   - [Cloud Persistence & Lateral Movement: Defending Identity in the Cloud](https://learn.secbyte.org/ctf/cloud-persistence-and-lateral-movement-defending-identity-in)

3. **Phase 3: Cloud Forensics & Native Detection Triage** — Investigate CloudTrail audit logs and triage alerts in native security suites:
   - [Cloud Incident Response & Digital Forensics](https://learn.secbyte.org/ctf/cloud-incident-response-digital-forensics)
   - [Cloud Watchtower: AWS Security Services Deep Dive](https://learn.secbyte.org/ctf/cloud-watchtower-aws-security-services-deep-dive)
   - [Microsoft Defender for Cloud: Azure Security Center Defense](https://learn.secbyte.org/ctf/microsoft-defender-for-cloud-azure-security-center-cloud-def)
   - [Google Cloud Security Command Center: Detection, Triage & Response](https://learn.secbyte.org/ctf/google-cloud-security-command-center-detection-triage-respon)

4. **Phase 4: Multi-Cloud Enterprise Security Architecture** — Architect unified Zero Trust control planes and federated identity models:
   - [Multi-Cloud Security Architecture: Identity & Network Control Planes](https://learn.secbyte.org/ctf/multi-cloud-security-architecture-identity-network-control-p)

---

## How to Use the Labs

1. Select a challenge link from the index or category sections above.
2. Read the scenario directives and cloud environment specifications on [Learn SecByte](https://learn.secbyte.org/).
3. Deploy cloud auditing and DevSecOps tools (`tfsec`, `Checkov`, AWS CLI, Azure CLI, gcloud SDK, Pacu, ScoutSuite, CloudFox, Athena) inside an isolated workstation.
4. Scan IaC templates, exploit IAM policies, analyze CloudTrail log streams, investigate serverless compromises, and retrieve target flags.

---

## Disclaimer

This repository and its linked challenge resources are strictly intended for educational, threat research, and authorized technical training purposes. Never execute cloud security scans, privilege escalation tools, or static analysis scripts against unauthorized cloud tenancies, production codebases, or third-party infrastructure.
