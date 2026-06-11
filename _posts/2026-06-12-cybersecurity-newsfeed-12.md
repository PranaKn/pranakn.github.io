---
title: "Cybersecurity Newsfeed - 12/06/26"
date: 2026-06-11 20:00:00 -0300
categories: [News]
permalink: /posts/news-12-06-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware, ransomware, ai-security]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering critical zero-days, international ransomware takedowns, supply chain attacks, and emerging AI agent vulnerabilities."
image:
  path: assets/img/posts/newsfeed-2026-06-12.png
  alt: Cybersecurity Newsfeed - 12/06/26
---

# Cybersecurity Newsfeed

## 📅 12/06/26

## 🛡️ Vulnerabilities

- **CISA Adds Ivanti Sentry Flaw to KEV Catalog (CVE-2026-10520)**: CISA added this high-risk OS command injection flaw within Ivanti Sentry to its Known Exploited Vulnerabilities catalog. Attackers are actively leveraging the bug to achieve unauthenticated remote code execution. Under Binding Operational Directive (BOD) 26-04, federal agencies must prioritize immediate remediation. [More info](https://www.cisa.gov/news-events/alerts/2026/06/11/cisa-adds-one-known-exploited-vulnerability-catalog)

- **Oracle Mitigates PeopleSoft Zero-Day (CVE-2026-35273)**: Oracle released emergency mitigations for a critical unauthenticated RCE vulnerability (CVSS 9.8) affecting PeopleSoft Enterprise PeopleTools (v8.61/8.62). Mandiant confirmed that the ShinyHunters extortion gang is actively exploiting this flaw to exfiltrate massive corporate databases from over 100 organizations. [More info](https://www.bleepingcomputer.com/news/security/oracle-mitigates-peoplesoft-zero-day-exploited-in-data-theft-attacks/)

- **GreatXML Exploit Bypasses Windows BitLocker**: Security researcher Chaotic Eclipse released "GreatXML," an exploit utilizing a vulnerability linked to the Windows Defender Offline Scan feature. By dropping modified XML configuration scripts into the recovery partition, an attacker can bypass BitLocker encryption and drop into an unrestricted command shell. [More info](https://thehackernews.com/2026/06/new-greatxml-exploit-bypasses-windows.html)

- **Fortinet Patches Critical Command Injection in FortiSandbox (CVE-2026-25089)**: Boasting a CVSS score of 9.8, this flaw impacts FortiSandbox web user interfaces due to improper input neutralization. An unauthenticated remote attacker could execute unauthorized system commands via crafted HTTP requests. Administrators are urged to upgrade immediately. [More info](https://securityaffairs.com/193509/security-to-patched-a-new-critical-fortisandbox-flaw.html)

- **Input Flattening Flaws Expose OpenClaw AI Agents**: Researchers from Imperva and Varonis demonstrated that the self-hosted AI agent OpenClaw flattens complex message objects into system prompts without untrusted boundaries. This permits hidden command injections and data exfiltration. OpenClaw addressed the flaw in version 2026.4.23. [More info](https://thehackernews.com/2026/06/new-attacks-trick-openclaw-ai-agent.html)

## 🎯 Adversaries

- **The Gentlemen Ransomware Claims Hundreds of Global Victims**: The Phantom Mantis group has rebranded into an independent partnership program called "The Gentlemen." Led by a Russian-speaking threat actor, the group has hit 478 victims using Go-based wormable malware and aggressive 90% profit-splits for affiliates targeting Cisco and Fortinet edge devices. [More info](https://thehackernews.com/2026/06/the-gentlemen-ransomware-claims-478.html)

- **OnyxC2 MaaS Exploits DLL Sideloading for Data Theft**: A new Malware-as-a-Service platform targeting over 210 applications has emerged. Discovered by BlackFog, OnyxC2 achieves zero antivirus detections by utilizing a valid Authenticode signature and sideloading its malicious payload disguised as an NVIDIA library. [More info](https://securityaffairs.com/193523/malware/onyxc2-malware-as-a-service-offers-enterprise-grade-data-theft.html)

- **Vidar Infostealer Distributed via Social Media Tutorials**: Cybercriminals are exploiting TikTok and Instagram Reels to spread Vidar infostealer via fake software premium guides (e.g., Spotify Premium). ReversingLabs observed malicious PowerShell scripts being executed by non-technical users, harvesting browser credentials and tokens. [More info](https://www.helpnetsecurity.com/2026/06/11/vidar-infostealer-tiktok-instagram-reels-malware-campaigns/)

- **Hackers Distribute AsyncRAT via Poisoned Claude Code Guides**: FortiGuard Labs discovered a campaign masquerading as a technical guide for Anthropic's Claude Code. Opening the shortcut file drops AsyncRAT via an obfuscated PDF container chain, blindsiding local defenses by adding the system drive to Microsoft Defender's exclusion paths. [More info](https://hackread.com/hackers-fake-claude-code-guide-ai-pdfs-asyncrat/)

- **OceanLotus Conducts Supply Chain Attacks Targeting Vietnam**: The Vietnam-aligned APT group OceanLotus compromised the update server of trading platform FireAnt Metakit. Distributing a payload without integrity validation allowed the actors to sideload the SPECTRALVIPER backdoor into OneDrive processes for domestic cyber espionage. [More info](https://thehackernews.com/2026/06/oceanlotus-hits-vietnam-investors-with.html)

## 📈 Trends

- **Phishing Volume Decreases While Attack Severity Escalates**: Zscaler intelligence shows global phishing volumes dropped 20%, but financial losses tripled to $215 million. Threat actors are transitioning to highly targeted campaigns crafted with AI lures and hosted on mainstream infrastructure like AWS to evade standard IP filters. [More info](https://www.darkreading.com/cybersecurity-analytics/phishing-volume-down-20-risk-rising)

- **OWASP Identifies Prompt Injection as Dominant Production Flaw**: The OWASP GenAI Security Project released version 2.01 of its State of Agentic AI Security report, confirming prompt injection remains the top production failure mode. Coding assistants represent the highest vulnerability concentration following recent supply chain threats. [More info](https://www.helpnetsecurity.com/2026/06/11/owasp-prompt-injection-ai-security-failures/)

## 💥 Breaches & Leaks

- **Maine Breach Portal Exploited via Fraudulent Disclosures**: Maine’s official breach portal allowed unverified direct public postings, enabling scammers to submit fake filings. Fraudulent claims stated VRChat leaked 2.4 million users' data and Discord suffered a 10-million user breach, causing massive corporate reputational risks. [More info](https://www.bleepingcomputer.com/news/security/maine-breach-portal-abused-to-publish-fake-data-breach-disclosures/)

- **ShinyHunters Leaks 40GB of University of Nottingham Data**: Hacking group ShinyHunters breached the University of Nottingham's Campus Solutions network. The incident exposed records of 455,000 unique email addresses across the UK, Malaysia, and China, leaking student IDs, National Insurance numbers, and financial details. [More info](https://hackread.com/shinyhunters-university-of-nottingham-student-data-leak/)

## 📚 Others

- **International Operation Dismantles SniperDZ Phishing Network**: A joint initiative involving Group-IB, Interpol, and Algerian police dismantled SniperDZ, a Phishing-as-a-Service operator hosting over 20,000 domains. The operation resulted in 201 global arrests and the seizure of 53 infrastructure servers. [More info](https://hackread.com/authorities-dismantle-sniperdz-phishing-network/)

- **AudiA6 Ransomware Crypto-Laundering Hub Dismantled**: An international law enforcement operation involving 11 countries seized 25 domains and arrested administrators behind "AudiA6," a crypto mixer that laundered over $380 million for ransomware operations using money mule networks. [More info](https://www.bleepingcomputer.com/news/legal/authorities-dismantle-audia6-ransomware-crypto-laundering-service/)

---

[⬅ Back to Archive](https://pranakn.github.io)
