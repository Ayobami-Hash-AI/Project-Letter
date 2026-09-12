# Cybersecurity Project Letter

## Monthly Progress Report — August–September 2026

**Ayobami Odulaja**  
Cybersecurity Analyst | Blue-Team and Healthcare Security Focus

[LinkedIn](https://www.linkedin.com/in/ayobami-o-077004152) · [TryHackMe](https://tryhackme.com/p/odulajaayobami) · [Cybersecurity Portfolio](https://github.com/Ayobami-Hash-AI/Cybersecurity-Portfolio-Ayobami-Odulaja)

---

## Executive Summary

Over the past month, I have deliberately strengthened my practical cybersecurity capabilities across security operations, network traffic analysis, threat detection, cloud administration, and home-lab engineering. My work has combined guided training with hands-on investigation, technical documentation, and repeated problem-solving in controlled environments.

My primary objective has been to move beyond theoretical familiarity and develop the investigation habits expected of a blue-team professional: establish context, identify evidence, filter noise, interpret activity, assess risk, document findings, and recommend appropriate defensive actions.

## Areas of Development

| Focus Area | Practical Work | Skills Demonstrated |
|---|---|---|
| SOC operations | Continued the TryHackMe SOC Level 1 pathway | Alert triage, investigation workflow, evidence interpretation |
| Network forensics | Examined PCAP files with Wireshark and NetworkMiner | Packet filtering, protocol analysis, session reconstruction |
| Threat analysis | Studied attacker behaviors and the Pyramid of Pain | Indicator analysis, defensive prioritization, adversary adaptation |
| Detection engineering | Practised Sigma concepts and network-control logic | Detection logic, firewall rules, DNS blocking |
| AI security | Progressed through the TryHackMe AI Security pathway | Emerging-threat awareness, security implications of AI systems |
| Home-lab engineering | Continued developing the MedSecure SOC environment | Network segmentation, logging architecture, endpoint visibility |
| Certification readiness | Prepared for CompTIA Security+ and CySA+ | Risk, operations, incident response, vulnerability management |
| Cloud administration | Reinforced Microsoft Azure administration concepts | Entra ID, RBAC, Azure Policy, monitoring, storage, networking |

## 1. SOC and Network-Traffic Analysis

I worked through practical security-operations exercises requiring the examination of network evidence rather than reliance on assumptions. I developed greater confidence in:

- Opening, navigating, and parsing PCAP files
- Applying Wireshark display filters to isolate relevant traffic
- Using NetworkMiner to identify hosts, sessions, files, and credentials
- Interpreting source and destination addresses, ports, and protocols
- Examining HTTP traffic, requests, responses, and URI structures
- Identifying the security risk of cleartext credentials
- Recognizing patterns associated with ICMP tunnelling
- Decoding encoded data and validating investigative findings
- Following evidence chains to identify lab flags and indicators

This work improved my ability to move from raw packet data to a concise explanation of what occurred, why it matters, and what should be investigated next.

## 2. Threat Intelligence and Detection

I strengthened my understanding of intelligence-led defense through the Pyramid of Pain and related blue-team concepts. I examined how defenders can impose greater operational cost on attackers by progressing from easily changed indicators—such as hashes and IP addresses—to behaviors, tools, tactics, techniques, and procedures.

Practical areas included:

- Differentiating indicators of compromise from attacker behavior
- Understanding why attackers change infrastructure after controls are introduced
- Selecting suitable firewall and DNS controls
- Interpreting the purpose and structure of Sigma detection rules
- Relating technical evidence to defensive decisions
- Documenting how an attacker may evolve in response to detection

## 3. MedSecure SOC Home Lab

I continued developing **MedSecure SOC**, a healthcare-inspired security operations home lab designed to simulate a small enterprise environment. The planned and developing stack includes:

- pfSense firewall
- Windows Server with Active Directory Domain Services
- Windows endpoint
- Kali Linux
- Splunk Enterprise and Universal Forwarder
- Sysmon
- LimaCharlie EDR
- Nessus Essentials

During this period, I progressed the pfSense deployment and virtual network-adapter configuration. The environment is intended to support controlled attack simulation, centralized logging, endpoint telemetry, vulnerability assessment, traffic analysis, and incident investigation.

My healthcare background informs the project’s emphasis on confidentiality, system availability, accurate documentation, and risk-based prioritization.

## 4. Cloud and Identity Development

I reinforced Microsoft Azure administration and security concepts relevant to cloud operations, including:

- Microsoft Entra ID users and groups
- Azure RBAC and the distinction between Azure and Entra roles
- Managed identities
- Azure Policy and resource locks
- Virtual networks, subnets, NSGs, peering, and route tables
- Azure Monitor, activity logs, alerts, and Defender for Cloud
- Storage access, replication, lifecycle management, and encryption
- Availability sets, availability zones, and scale sets
- Load Balancer, Application Gateway, WAF, and Azure Bastion

These topics support my broader goal of working effectively across security operations, identity, infrastructure, and cloud environments.

## 5. Technology Certifications and Credentials

My completed credentials reflect continued development across cybersecurity foundations, governance and risk, cloud computing, enterprise platforms, and applied technical learning.

### Cybersecurity and Governance

| Credential | Issuer | Issued | Validity |
|---|---|---:|---:|
| **Cybersecurity Foundations: Governance, Risk, and Compliance (GRC)** | LinkedIn Learning | August 2026 | No expiry stated |
| **Certified in Cybersecurity (CC)** | ISC2 | March 2026 | Through March 2029 |
| **Fortinet NSE 2 Certified in Cybersecurity** | Fortinet | January 2026 | Through January 2028 |
| **Fortinet NSE 1 Certified in Cybersecurity** | Fortinet | January 2026 | Through January 2028 |
| **Cyber Security 101 Certificate** | TryHackMe | July 2026 | Through July 2029 |
| **Pre Security (Legacy) Certificate** | TryHackMe | February 2026 | Through May 2029 |

### Cloud, Platforms, and AI

| Credential | Issuer | Issued |
|---|---|---:|
| **Microsoft Certified: Azure Fundamentals** | Microsoft | August 2026 |
| **Micro-Certification — Welcome to ServiceNow** | ServiceNow | August 2026 |
| **AI Skills Fest 2026** | Microsoft | June 2026 |
| **AWS Cloud Quest: Cloud Practitioner** | Amazon Web Services | May 2026 |
| **AWS Academy Graduate — Cloud Foundations** | Amazon Web Services | April 2026 |

These credentials complement my practical labs by establishing verified foundations in security principles, governance and compliance, Microsoft Azure, AWS cloud concepts, ServiceNow, AI, networking, and defensive-security practice.

## 6. Current Learning and Certification Goals

My active development plan combines hands-on labs with industry certification preparation:

- **CompTIA Security+** — active preparation
- **CompTIA CySA+** — examination planned for late October 2026
- **TryHackMe SOC Level 1** — in progress
- **TryHackMe AI Security** — in progress
- **ISO/IEC 27001 and IT service management** — developing governance and operational knowledge

## Tools and Technologies Used

`Wireshark` · `NetworkMiner` · `TryHackMe` · `pfSense` · `Splunk` · `Sysmon` · `LimaCharlie` · `Nessus` · `Windows Server` · `Active Directory` · `Kali Linux` · `Microsoft Azure` · `PowerShell` · `Python` · `VMware`

## Outcomes This Month

By the end of this period, I had:

1. Improved my ability to analyze network captures systematically.
2. Developed stronger recognition of suspicious protocol and credential activity.
3. Connected threat-intelligence concepts to practical defensive controls.
4. Expanded a realistic, healthcare-oriented SOC lab architecture.
5. Reinforced cloud identity, governance, networking, and monitoring knowledge.
6. Produced clearer technical explanations suitable for project documentation.
7. Maintained consistent hands-on learning while preparing for industry certifications.

## Next Objectives

My next phase will focus on:

- Completing additional SOC Level 1 and AI Security rooms
- Finishing the MedSecure virtual machines and network segmentation
- Forwarding Windows and Sysmon telemetry into Splunk
- Generating controlled attack activity from Kali Linux
- Creating detection searches and documenting incident investigations
- Running Nessus vulnerability assessments and prioritizing remediation
- Continuing Security+ and CySA+ practice, including performance-based questions
- Publishing concise, evidence-based project write-ups

## Professional Commitment

I am building toward a career in blue-team, network-security, and healthcare-cybersecurity operations. I approach every lab as an opportunity to demonstrate analytical discipline, ethical judgment, clear communication, and continuous improvement—not merely tool familiarity.

---

> **Ethical-use statement:** All security exercises and testing described in this repository were conducted in authorized educational or personally controlled lab environments. No production systems or third-party assets were targeted.
