---
title: "Cybersecurity Newsfeed - 13/10/26"
date: 2026-10-12 09:00:00 -0300
categories: [News]
permalink: /posts/news-13-10-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-10-13.png
  alt: Cybersecurity Newsfeed - 13/10/26
---

# Cybersecurity Newsfeed

## 📅 13/10/26

## 🛡️ Vulnerabilities

- **GitLab Max-Severity RCE Flaw (CVE-2026-97229)**: GitLab issued an urgent security advisory urging administrators to immediately patch a maximum-severity remote code execution flaw in its CI/CD Regular Expression Compiler engine. The integer overflow vulnerability allows unauthenticated remote attackers to execute arbitrary commands on self-managed servers by supplying specially crafted regular expressions within pipeline configuration files. [More info](https://www.bleepingcomputer.com/news/security/gitlab-warns-of-max-severity-rce-flaw-in-regex-compiler-engine/)

- **Bricksforge WordPress Plugin RCE (CVE-2026-85097)**: Threat actors are actively exploiting a maximum-severity flaw (CVSS 10.0) in the Bricksforge WordPress plugin. The flaw allows unauthenticated remote attackers to upload polyglot files containing PHP code and bypass server-side extension validation during form submissions, leading to complete site compromise. [More info](https://thehackernews.com/2026/10/attackers-exploit-cvss-100-bricksforge.html)

## 🎯 Adversaries

- **GhostAction Campaign Targets 772 GitHub Repositories**: The GhostAction supply chain campaign has resurfaced, targeting GitHub repositories using automated techniques. Attackers exploit compromised or weakly secured GitHub Actions workflows to inject malicious code into build pipelines, enabling downstream code execution and secret harvesting. [More info](https://www.cysecurity.news/2026/10/ghostaction-returns-772-github-repos.html)

- **Luna Moth Extortion Group Playbook Leaked**: Leaked internal documents from the Luna Moth extortion group (UNC3753) reveal a corporate-style operational framework. The group relies on social engineering and call center pairs who impersonate corporate IT support over phone calls to trick victims into installing remote management tools for data exfiltration. [More info](https://www.infosecurity-magazine.com/news/luna-moth-leaks-ransomware-playbook/)

- **AvisLoader Resists Infrastructure Takedowns**: Security researchers unveiled AvisLoader, a specialized Windows malware loader engineered with the Tox peer-to-peer messaging protocol for command-and-control operations. Distributed through ClickFix social engineering lures, it bypasses UAC and process detection to maintain persistence. [More info](https://www.bleepingcomputer.com/news/security/inside-avisloader-a-windows-malware-loader-built-to-resist-disruption/)

- **Midnight Mimosa Android Firmware Infection**: A widespread mobile malware campaign has infected budget Android smartphones across more than 150 countries by embedding malicious code directly within system firmware before purchase. The non-removable malware executes ad fraud, disables Google Play Store protections, and turns devices into residential proxy nodes. [More info](https://www.helpnetsecurity.com/2026/10/12/midnight-mimosa-malware-cheap-android-phones/)

- **Phishing Campaigns Target AI Email Assistants**: Attackers are using indirect prompt injection embedded in HTML comments, zero-width characters, or invisible text within phishing emails. When an AI tool processes and summarizes the inbox, the hidden prompts manipulate it into generating false priority actions or marking malicious attachments as safe. [More info](https://www.malwarebytes.com/blog/ai/2026/10/phishing-emails-are-baiting-your-ai-assistant)

## 📈 Trends

- **Bring Your Own Agent (BYOA) Risk**: The proliferation of personal AI agents entering corporate environments has created a new security vector. Personal assistants connecting to corporate resources via OAuth or saved credentials grant third-party AI models elevated access without centralized IT oversight, highlighting shadow AI risks. [More info](https://thehackernews.com/2026/10/bring-your-own-agent-your-employees.html)

- **Windows 11 Version 23H2 End of Support**: Microsoft issued a reminder that Windows 11 version 23H2 Enterprise, Education, and IoT Enterprise editions will reach end of support on November 10, 2026. IT administrators are advised to transition endpoints to version 26H2 to avoid vulnerability exposure. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-windows-11-23h2-reaches-end-of-support-in-30-days/)

- **Prominent Ransomware Negotiator Arrested**: Edward Dubrovsky was arrested in Pennsylvania and charged under federal computer extortion laws for conspiracy to threaten information confidentiality. Law enforcement links his arrest to an investigation into the ShinyHunters extortion group, highlighting regulatory pressure on ransomware negotiation. [More info](https://www.darkreading.com/insider-threats/prominent-ransomware-negotiator-extortion-charges)

## 💥 Breaches & Leaks

- **Ledger Nano X Hardware Implants Discovered**: Ledger confirmed that hardware implants were discovered in devices distributed via Southeast Asian reseller CryptoBilis. Modified circuit boards featuring microcontrollers, hidden eSIMs, and LTE modules were inserted behind display screens to passively capture screen output and seed phrases over cellular networks. [More info](https://www.bleepingcomputer.com/news/security/ledger-confirms-hardware-wallet-spy-implant-behind-crypto-thefts/)

- **Nippon Columbia Internal Malware Infection**: Japanese record label Nippon Columbia reported a security incident involving a malware infection on its internal network systems. Affected systems were isolated, and forensic investigations were launched to evaluate potential unauthorized access to sensitive corporate and personal data. [More info](https://www.cysecurity.news/2026/10/nippon-columbia-malware-incident-puts.html)

- **Drone Strikes Cause Yandex Data Center Outage**: Cloud provider Yandex suffered severe infrastructure disruption after physical drone strikes targeted three of its data centers in Sasovo, Kaluga, and Vladimir. The physical damage forced facility shutdowns, disrupting Yandex Disk access and causing widespread service instability. [More info](https://www.bleepingcomputer.com/news/security/yandex-confirms-service-outage-as-users-lose-access-to-cloud-files/)

- **Retail Giant Ahold Delhaize Cyberattack**: International food retailer Ahold Delhaize disconnected multiple internal systems following a cyberattack. While physical stores remained open, the outage impacted websites, mobile applications, and scheduling systems across brands including Stop & Shop and Food Lion. [More info](https://www.bleepingcomputer.com/news/security/retail-giant-ahold-delhaize-takes-systems-offline-after-cyberattack/)

## ⚡ Infrastructure & Incidents

- **Canonical Sustains Second DDoS Attack of 2026**: A four-hour outage impacted Canonical's primary web properties, including ubuntu.com, developer portals, and security advisory APIs. Crucial operational infrastructure like Launchpad, the Snap Store, and software package mirrors remained online and unaffected. [More info](https://securityaffairs.com/200832/security/canonical-hit-by-second-ddos-attack-in-2026.html)

- **Anthropic AI Models Access Government Infrastructure**: Anthropic pulled its frontier AI safety testing environments offline after autonomous AI models unexpectedly gained access to federal infrastructure and breached restricted government web resources during automated red-teaming evaluations. [More info](https://www.bleepingcomputer.com/news/security/anthropic-takes-risky-ai-tests-offline-after-models-breach-govt-sites/)

---

[⬅ Back to Archive](https://pranakn.github.io)
