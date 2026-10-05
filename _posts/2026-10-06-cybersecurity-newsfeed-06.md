---
title: "Cybersecurity Newsfeed - 06/10/26"
date: 2026-10-05 09:00:00 -0300
categories: [News]
permalink: /posts/news-06-10-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-10-06.png
  alt: Cybersecurity Newsfeed - 06/10/26
---

# Cybersecurity Newsfeed

## 📅 06/10/26

## 🛡️ Vulnerabilities

- **Rejetto HFS RCE Vulnerability (CVE-2026-61500)**: Threat actors are actively scanning for a critical flaw in Rejetto HTTP File Server (HFS). Discovered by Anthropic's Mythos AI model, the issue stems from weak pseudorandom number generation used for key signing, allowing unauthenticated attackers to forge administrative session tokens and achieve remote code execution. [More info](https://www.bleepingcomputer.com/news/security/rejetto-hfs-servers-now-actively-scanned-for-critical-rce-flaw/) | [More info](https://securityaffairs.com/200444/ai/anthropic-mythos-found-a-bug-in-rejetto-hfs-attackers-are-now-exploiting-it.html)

- **Microsoft Exchange Server Elevation of Privilege (CVE-2026-96940)**: Microsoft issued an out-of-band security update for a high-severity flaw (CVSS 8.8) in Exchange Server 2016, 2019, and Subscription Edition. Weak authorization mechanisms allow an authenticated internal network attacker to elevate privileges and gain unauthorized access to other users' mailboxes and attachments. [More info](https://thehackernews.com/2026/10/microsoft-exchange-flaw-lets.html) | [More info](https://www.helpnetsecurity.com/2026/10/05/exchange-server-vulnerability-cve-2026-96940/)

- **Dell System Update Local Privilege Escalation**: Dell warned of a critical vulnerability in its System Update (DSU) CLI tool. The flaw enables local unprivileged attackers to execute arbitrary commands with root privileges, affecting enterprise endpoints and servers. [More info](https://www.bleepingcomputer.com/news/security/new-dell-system-update-flaw-lets-hackers-gain-root-privileges/)

- **Active Exploitation of Realtek Jungle SDK (CVE-2021-35394)**: Threat actors continue to target internet-exposed routers and IoT devices running vulnerable Realtek Jungle SDK code, leveraging the unauthenticated RCE vulnerability to deploy Mirai botnet variants. [More info](https://thehackernews.com/2026/10/realtek-jungle-sdk-exploit-attempts.html)

## 🎯 Adversaries

- **ClingSTUN Linux Backdoor Converts IoT to Proxies**: FortiGuard Labs identified ClingSTUN, a novel Linux backdoor targeting IoT assets across 24 known vulnerabilities. It leverages STUN and ICE servers to bypass NAT/firewalls, turning infected devices into remotely controlled proxies to obfuscate malicious C2 traffic. [More info](https://www.darkreading.com/iot/clingstun-vulnerable-iot-devices-proxy-nodes)

- **CloudSyncD macOS Backdoor Poses as Zoom Installer**: A stealthy macOS backdoor called CloudSyncD uses fake Zoom installers to establish long-term persistence. It displays a fake password prompt, embeds credentials using zero-width Unicode characters, and covertly polls C2 servers. [More info](https://www.cysecurity.news/2026/10/cloudsyncd-backdoor-spread-through-fake.html)

- **SMTP-Based Linux Backdoors Target Security Gateways**: A campaign targeting Secure Email Gateways (SEGs) deploys custom implants (such as BPFdoor and Rekoobe variants) disguised as legitimate processes. C2 communications are disguised over TCP Port 25 (SMTP) to blend into regular mail traffic. [More info](https://www.infosecurity-magazine.com/news/smtp-linux-backdoors-network-edge/)

- **Milk Dragon Phishing Kit Abuse on Social Platforms**: Attackers are using the "Milk Dragon" kit across TikTok and Facebook, pushing fake discount ads that send victims to fraudulent storefronts. A custom plugin named BytePress steals payment details and intercepts MFA tokens in real time. [More info](https://www.helpnetsecurity.com/2026/10/05/milk-dragon-phishing-fake-discounts/)

## 📈 Trends

- **OpenAI Integrates Invisible Watermarks in EU**: OpenAI is rolling out invisible text watermarking for ChatGPT and Codex in the EU. Utilizing Google DeepMind’s SynthID and open C2PA standards, cryptographic signatures are embedded directly into outputs to improve content provenance. [More info](https://www.bleepingcomputer.com/news/artificial-intelligence/openai-is-adding-invisible-watermarks-to-chatgpt-and-codex-text-in-the-eu/)

- **Proposed Federal "Anti-Flock" LPR Legislation**: Proposed US federal laws aim to restrict automated license plate reader (ALPR) technology by limiting cross-jurisdiction data sharing, retention periods, and real-time tracking to address privacy concerns. [More info](https://www.malwarebytes.com/blog/news/2026/10/proposed-anti-flock-bills-could-spell-trouble-for-license-plate-readers)

- **Malwarebytes Launches Free Link Checker**: Malwarebytes introduced a real-time link verification tool that analyzes domain reputation and threat telemetry to catch phishing schemes, drive-by downloads, and malicious sites before navigation. [More info](https://www.helpnetsecurity.com/2026/10/05/malwarebytes-scam-link-check/)

## 💥 Breaches & Leaks

- **IQVIA Fined €7M ($7.8M) for GDPR Anonymization Failures**: Italy's GPDP penalized health data provider IQVIA after an investigation showed its 1-million-patient database included metadata that enabled re-identification, violating GDPR rules. [More info](https://www.bleepingcomputer.com/news/security/iqvia-fined-78-million-for-failing-to-properly-anonymize-health-data/)

- **Denmark Population Register Breach Exposes 8.8M Records**: Unauthorized access via a third-party contractor resulted in the exfiltration of 8.8 million personal records from Denmark's Central Population Register (CPR), including names, addresses, and social security numbers. [More info](https://www.bleepingcomputer.com/news/security/denmark-population-registry-data-breach-affects-88-million-people/)

- **South Korean Banks Targeted in AI-Assisted Attacks**: South Korea's Financial Services Commission launched emergency investigations following breaches at major commercial banks (including Shinhan Bank and KB Kookmin Bank) involving AI-driven penetration-testing tools. [More info](https://www.bleepingcomputer.com/news/security/south-korea-probes-bank-breaches-amid-suspected-ai-powered-attacks/)

## 📚 Others

- **Ploutus ATM Malware Developer Appears in US Court**: The alleged developer of the Ploutus ATM jackpotting malware was presented in U.S. federal court following an international law enforcement arrest. [More info](https://www.bleepingcomputer.com/news/security/suspected-dev-of-ploutus-atm-malware-appears-in-us-court-after-arrest/)

---

[⬅ Back to Archive](https://pranakn.github.io)
