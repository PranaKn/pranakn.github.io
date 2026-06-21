---
title: "Cybersecurity Newsfeed - 22/06/26"
date: 2026-06-21 18:50:00 -0300
categories: [News]
permalink: /posts/news-22-06-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-06-22.png
  alt: Cybersecurity Newsfeed - 22/06/26
---

# Cybersecurity Newsfeed

## 📅 22/06/26

## 🛡️ Vulnerabilities

- **CISA Adds Critical Splunk Enterprise Flaw to KEV (CVE-2026-20253)**: CISA added a critical vulnerability affecting Splunk Enterprise (versions 10.2.0–10.2.3 and 10.0.0–10.0.6) to its Known Exploited Vulnerabilities catalog. Boasting a CVSS score of 9.8, the flaw allows unauthenticated remote attackers to execute arbitrary file operations via an unprotected PostgreSQL sidecar service endpoint, which can be chained to achieve full remote code execution. [More info](https://www.bleepingcomputer.com/news/security/cisa-splunk-enterprise-flaw-actively-exploited-patch-by-sunday/)

- **Unpatchable "usbliter8" SecureROM Boot Chain Exploit**: Security researchers disclosed a foundational hardware-level flaw affecting Apple A12 and A13 Bionic chipsets. The exploit targets a vulnerability within the SecureROM boot chain to achieve arbitrary code execution. Because this code is permanently burned into the silicon during manufacturing, it cannot be patched via software updates. Exploitation requires physical or tethered USB access. [More info](https://www.cysecurity.news/2026/06/unpatchable-bootrom-flaw-exposes-apple.html) | [More info](https://thehackernews.com/2026/06/unpatchable-usbliter8-exploit-breaks.html)

- **Gravity SMTP WordPress Plugin Information Disclosure (CVE-2026-4020)**: Attackers are actively exploiting a critical flaw in the Gravity SMTP plugin stemming from an unauthenticated REST API endpoint. By appending specific query parameters, external visitors can force the plugin to dump its full System Report, exposing plain-text API keys, secrets, and OAuth tokens. Researchers have already blocked over 17 million exploitation attempts. [More info](https://www.bleepingcomputer.com/news/security/hackers-exploit-info-disclosure-bug-in-gravity-smtp-wordpress-plugin/)

## 🎯 Adversaries

- **AryStinger Botnet Targets Legacy D-Link Routers**: A sophisticated attack campaign is exploiting long-known vulnerabilities (CVE-2013-3307 and CVE-2016-5681) in outdated routers using RTL819X series chips. Dubbed AryStinger, the cluster is designed for intrusion reconnaissance, port scanning, and traffic proxying. It has infected at least 4,300 devices worldwide, primarily focusing on D-Link models DIR-850L and DIR-818LW while using Protobuf and XOR encryption to evade detection. [More info](https://www.bleepingcomputer.com/news/security/arystinger-botnet-infected-thousands-of-d-link-routers-worldwide/)

- **North Korean Hackers Hit Mastra AI via Supply Chain**: Microsoft Threat Intelligence linked a supply chain compromise affecting Mastra AI to North Korean state-sponsored threat actors. Hackers compromised a framework contributor account, republishing over 140 legitimate packages containing a malicious dependency called `easy-day-js`. When installed, npm lifecycle hooks automatically execute code to disable TLS certificate validation and drop secondary payloads. [More info](https://www.bleepingcomputer.com/news/security/microsoft-links-mastra-ai-supply-chain-attack-to-north-korean-hackers/)

- **FortiBleed Campaign Compromises 86k+ Fortinet Credentials**: A global operation harvested and systematically cracked legacy SHA-256 password hashes of over 86,644 internet-facing Fortinet FortiGate firewalls and SSL VPN gateways across 194 countries. Even on upgraded devices, older hashes persist until an administrator logs in post-update. CISA issued a directive warning that state-aligned actors are leveraging this dataset to deploy tunneling tools. [More info](https://securityaffairs.com/193931/hacking/fortibleed-exposes-global-credential-spraying-operation.html)

- **Prinz Eugen Ransomware Prioritizes Recent Files**: A new ransomware strain named Prinz Eugen has introduced a chronological encryption strategy that targets a victim's most newly created or modified data first. By prioritizing high-value, active operational files, the ransomware maximizes short-term disruption to accelerate extortion negotiations before behavioral defense systems trigger. [More info](https://www.bleepingcomputer.com/news/security/new-prinz-eugen-ransomware-prioritizes-recent-files-for-encryption/)

- **Operation Endgame Disrupts SocGholish Botnet**: An international law enforcement coalition dismantled critical infrastructure linked to the SocGholish malware operations. Authorities seized 106 servers and successfully cleaned backdoors from 14,971 compromised WordPress sites. The botnet served as a primary initial access broker for the Russian-affiliated Evil Corp syndicate to deploy ransomware. [More info](https://thehackernews.com/2026/06/operation-endgame-disrupts-socgholish.)

## 📈 Trends

- **Unit 42 Report: 90% of Intrusions Exploit Identity**: Palo Alto Networks Unit 42 released its 2026 Global Incident Response Report, highlighting that threat actors are shifting away from traditional malware to simply "logging in" using stolen credentials, session tokens, and illicit OAuth grants. The report notes that software supply chain risks have shifted heavily toward misusing trusted connectivity and SaaS integrations. [More info](https://unit42.paloaltonetworks.com/large-scale-credential-attacks/)

- **The Corporate Blind Spot of Unmanaged AI Agent Identities**: Security research warnings emphasize that organizations are deploying independent AI agents without assigning them distinct machine identities. AI agents frequently operate using broad, shared corporate credentials or over-scoped API keys, generating massive auditing gaps that allow attackers to move laterally across enterprise cloud environments undetected. [More info](https://www.bleepingcomputer.com/news/security/every-ai-agent-is-an-identity-most-organizations-dont-treat-them-that-way/)

- **EFAQ Investigates Structured Reputational Disinformation**: The Electronic Financial Action Queue published an investigative report mapping the infrastructure behind coordinated reputation attacks targeting digital asset networks. The findings highlight a growing trend where cybercriminals merge automated bot farms and coordinated social media amplification with psychological operations to manipulate market perceptions and extort entities. [More info](https://hackread.com/efaq-publishes-investigation-into-alleged-scam-activity-and-coordinated-reputation-attacks/)

## 💥 Breaches & Leaks

- **Klue OAuth Breach Impacts Corporate Giants**: Market intelligence platform Klue confirmed a critical infrastructure breach where threat actors used a compromised legacy credential within an integration service to steal OAuth tokens. Major cybersecurity vendors, including Huntress and Tanium, confirmed their Salesforce CRM and Gong data were exfiltrated. The "Icarus" extortion group claimed responsibility. [More info](https://www.bleepingcomputer.com/news/security/klue-oauth-breach-victim-list-grows-as-icarus-hackers-claim-attack/)

- **Texas Govt Data Breach Exposes 3 Million License Holders**: The Texas Parks and Wildlife Department announced a massive data breach originating from a third-party vendor handling the state's hunting and fishing licensing system. Exfiltrated profile data includes driver's license numbers, residential addresses, and passport numbers. Highly sensitive financial data or Social Security numbers were not compromised. [More info](https://www.bleepingcomputer.com/news/security/texas-govt-data-breach-exposes-over-3-million-drivers-licenses/)

- **Nintendo of America Hit by TinyPulse SaaS Breach**: Nintendo of America confirmed an employee data breach stemming from a supply chain cyberattack against third-party employee engagement platform TinyPulse (owned by WebMD Health Services). The threat group Shadowbyt3$ claimed responsibility, demanding a $2 million ransom for 1GB of stolen data containing employee names, survey analytics, and W-9 tax forms from 2016 to 2026. [More info](https://hackread.com/nintendo-america-employee-data-shadowbyt3-tinypulse/)

## 🛠️ Tools

- **SafeCloud Framework Launches Decoupled Browser Storage**: Developers launched SafeCloud, a browser-based encrypted storage framework executing client-side zero-knowledge AES-GCM encryption directly within browser sandboxes. By eliminating centralized desktop clients and ensuring cloud hosting providers never see cleartext data, the framework presents a scalable approach to modern cloud security. [More info](https://www.helpnetsecurity.com/2026/06/19/safecloud-browser-based-encrypted-storage/)

---

[⬅ Back to Archive](https://pranakn.github.io)
