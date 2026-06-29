---
title: "Cybersecurity Newsfeed - 30/06/26"
date: 2026-06-29 18:00:00 -0300
categories: [News]
permalink: /posts/news-30-06-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-06-30.png
  alt: Cybersecurity Newsfeed - 30/06/26
---

# Cybersecurity Newsfeed

## 📅 30/06/26

## 🛡️ Vulnerabilities

- **CISA Adds SimpleHelp Flaw to KEV (CVE-2026-48558)**: CISA added a critical authentication bypass vulnerability in SimpleHelp remote support software to its Known Exploited Vulnerabilities Catalog. The flaw allows attackers to circumvent security mechanisms and gain full control over exposed assets. Federal agencies must remediate public-facing instances immediately. [More info](https://www.cisa.gov/news-events/alerts/2026/06/29/cisa-adds-one-known-exploited-vulnerability-catalog)

- **Critical Oracle E-Business Suite Flaw Exploited (CVE-2026-46817)**: Threat intelligence firm Defused reported active exploitation of a flaw impacting the Oracle Payments module. With a maximum CVSS score of 9.8, unauthenticated attackers can exploit the bug over HTTP to achieve complete system takeover. Hundreds of vulnerable instances remain exposed online. [More info](https://www.bleepingcomputer.com/news/security/new-oracle-e-business-suite-flaw-now-exploited-in-attacks/)

- **Public PoC Released for Critical libssh2 Bug (CVE-2026-55200)**: A public proof-of-concept exploit was released for a client-side integer overflow flaw in libssh2 (versions up to 1.11.1). Holding a CVSS score of 9.2, a malicious server can trigger an out-of-bounds heap buffer write to execute remote code. The library is statically embedded in widespread tools like curl, Git, and PHP. [More info](https://thehackernews.com/2026/06/public-poc-released-for-critical.html)

## 🎯 Adversaries

- **TONResolver RAT Targets Japanese Accommodations**: A phishing campaign utilizes conversational Gmail threads and bed bug complaints to deploy the novel TONResolver remote access trojan. The malware abuses The Open Network (TON) blockchain as a dead drop resolver to fetch C2 domains via a smart contract, bypassing standard domain take-down actions. [More info](https://www.trendmicro.com/en_us/research/26/f/tonresolver.html)

- **Mustang Panda Exploits Zoho WorkDrive in India**: The China-linked cyber espionage group is targeting the Indian government and hydropower sector. Spear-phishing emails deliver a loader named SHARDLOADER, dropping a modified Toneshell backdoor variant (MINIRECON) and a new tool called ZOHOMURK. The latter abuses legitimate Zoho WorkDrive folders as a stealthy C2 channel. [More info](https://www.thehackernews.com/2026/06/mustang-panda-uses-zoho-workdrive-as.html)

- **Millenium RAT 4.0 Rewritten to Evade Detection**: A major campaign distributing Millenium RAT has compromised over 60,000 Windows endpoints globally. Version four has been rewritten from .NET into native C++ to evade EDR tools. Sold as MaaS for $50/month, it leverages the Telegram Bot API to exfiltrate data and uses deceptive UAC prompts to gain admin rights. [More info](https://www.infosecurity-magazine.com/news/millenium-rat-telegram-60000/)

- **Gamaredon Expands Ukraine Operations with New Tactics**: The Russian APT group expanded its offensive campaigns against Ukrainian military and government targets. Gamaredon introduced six new custom PowerShell tools executing in-memory payloads and weaponized serverless worker platforms, third-party cloud services, and paste sites to hide its infrastructure footprint. [More info](https://thehackernews.com/2026/06/gamaredon-expands-ukraine-attacks-with.)

- **The Gentlemen RaaS Enters Top-Ten Threat Group Rankings**: The Gentlemen ransomware-as-a-service group has emerged as a major threat targeting enterprises and critical infrastructure. The group gains initial access via credential stuffing or exposed firewalls, deploys custom Go-based backdoors, and leverages Bring Your Own Vulnerable Driver (BYOVD) tactics to terminate EDR software. [More info](https://securelist.com/the-gentlemen-raas/120447/)

- **Russian Hackers Linked to Destructive Jaguar Land Rover Attack**: Investigative assessments have linked Russian nation-state actors to a destructive cyberattack against Jaguar Land Rover that cost the British economy £2.5 billion. The intrusion lacked financial ransom demands and deployed highly customized ransomware just before a commercial rollout, aiming for economic sabotage. [More info](https://www.infosecurity-magazine.com/news/russian-hackers-destructive-jaguar/)

- **StegoAd Malicious Extensions Disrupted by Microsoft**: Microsoft disrupted a sophisticated ad fraud and credential harvesting campaign operating undetected for two years. StegoAd accumulated 2.6 million installations via 119 malicious browser extensions on the Edge Add-ons store, using steganography to embed executable JavaScript inside font and image assets. [More info](https://securityaffairs.com/194409/malware/stegoad-how-119-fake-browser-extensions-stole-credentials-and-ran-ad-fraud-for-two-years.html)

## 📈 Trends

- **Agentic AI Introduces Critical Identity Security Risks**: The proliferation of autonomous AI agents is creating severe identity security challenges. Token Security reports that many agents operate via overprivileged, unmapped service accounts or static developer tokens, creating an unmonitored blast radius vulnerable to credential theft and prompt injection. [More info](https://www.bleepingcomputer.com/news/security/agentic-ai-has-an-identity-problem-and-attackers-know-it/)

- **Bluekit PaaS Deploys Browser-in-the-Middle Attacks**: A new phishing-as-a-service platform named Bluekit is scaling globally to bypass multi-factor authentication. Moving away from classic reverse-proxies, it renders corporate logins within a hacker-controlled browser and streams DOM interactions to victims via WebSockets, while running 20+ checks to filter out security scanners. [More info](https://hackread.com/bluekit-phishing-uses-browser-in-the-middle-attacks/)

- **WhatsApp Rolls Out Usernames to Enhance Privacy**: Meta announced a gradual rollout allowing WhatsApp users to reserve custom usernames, eliminating the need to expose phone numbers to non-contacts. Users can also set an optional username key as a secondary passcode required by new interlocutors, mirroring privacy controls launched by Signal in 2024. [More info](https://www.bleepingcomputer.com/news/security/whatsapp-rolls-out-usernames-to-help-users-hide-their-phone-number/)

## 💥 Breaches & Leaks

- **Nissan Americas Discloses Breach Caused by Oracle Zero-Day**: Nissan Americas has suffered a data breach exposing personal information of employees across the US, Canada, Mexico, and Brazil. The threat actors exploited a critical zero-day vulnerability in Oracle PeopleSoft servers (CVE-2026-35273). The ShinyHunters extortion group claimed responsibility. [More info](https://www.bleepingcomputer.com/news/security/nissan-discloses-employee-data-breach-linked-to-oracle-zero-day-attacks/)

- **NAIC PeopleSoft System Breached by ShinyHunters**: The National Association of Insurance Commissioners confirmed a breach of its Oracle PeopleSoft system following an intrusion on June 11, 2026, linked to the same CVE-2026-35273 zero-day. While ShinyHunters claimed to leak 3.1 TB of data, NAIC states that only public financial reports and legacy logs were compromised. [More info](https://www.bleepingcomputer.com/news/security/naic-says-public-data-stolen-in-shinyhunters-peoplesoft-breach/)

---

[⬅ Back to Archive](https://pranakn.github.io)
