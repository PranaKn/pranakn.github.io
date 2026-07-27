---
title: "Cybersecurity Newsfeed - 28/07/26"
date: 2026-07-27 09:00:00 -0300
categories: [News]
permalink: /posts/news-28-07-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-07-28.png
  alt: Cybersecurity Newsfeed - 28/07/26
---

# Cybersecurity Newsfeed

## 📅 28/07/26

## 🛡️ Vulnerabilities

- **vBulletin Pre-Auth RCE Exploit Released (CVE-2026-61511)**: A public exploit has been published for a pre-authentication remote code execution flaw in vBulletin's template engine (v6.2.1 and earlier). The flaw allows unauthenticated users to pass restricted math expressions directly to PHP's `eval` function to execute arbitrary OS commands. [More info](https://thehackernews.com/2026/07/public-exploit-released-for-patched.html)

- **High-Severity n8n Sandbox Escape**: Automation platform n8n patched a sandbox escape vulnerability that permitted authenticated workflow editors to bypass JavaScript identifier rewriting via arrow functions and execute operating system commands as the n8n process. [More info](https://thehackernews.com/2026/07/n8n-sandbox-escape-lets-workflow.html)

- **Certighost Active Directory AD CS Exploit (CVE-2026-54121)**: A proof-of-concept exploit was released for Certighost, a critical flaw in Windows Active Directory Certificate Services allowing low-privileged authenticated users to hijack domain controller certificates and obtain full administrative rights. [More info](https://www.bleepingcomputer.com/news/security/new-certighost-poc-exploit-lets-attackers-hijack-windows-domains/)

- **CISA Adds Fortinet and Arista Flaws to KEV**: CISA added Fortinet FortiOS info disclosure (CVE-2025-68686) and Arista VeloCloud Orchestrator command injection (CVE-2026-16812) to its Known Exploited Vulnerabilities catalog following active in-the-wild exploitation. [More info](https://www.cisa.gov/news-events/alerts/2026/07/27/cisa-adds-two-known-exploited-vulnerabilities-catalog)

## 🎯 Adversaries

- **macOS ClickFix Campaign Delivers AMOS Stealer**: Threat actors are using deceptive fake CAPTCHA verifications ("ClickFix") to trick macOS users into executing terminal commands that fetch and deploy Atomic macOS Stealer (AMOS) to siphon Keychain entries, browser cookies, and crypto wallets. [More info](https://www.kaspersky.com/blog/macos-clickfix-attack/56187/)

- **MedusaHVNC Trojan Uses Hidden Desktops**: A new malware-as-a-service Remote Access Trojan named MedusaHVNC executes browser sessions on invisible desktop workspaces and injects into `charmap.exe` to covertly steal data while bypassing behavioral detection. [More info](https://securityaffairs.com/196111/malware/medusahvnc-trojan-creates-hidden-desktops-to-hijack-browsers-and-steal-data.html) | [More info](https://www.securityweek.com/medusahvnc-malware-uses-hidden-windows-desktops-to-evade-detection/)

- **Sextortion Scammers Leverage ShinyHunters Leaks**: Cybercriminals are abusing victim email addresses leaked in historical ShinyHunters breaches to demand $2,000 in Bitcoin through fake extortion campaigns alleging device infection and adult content viewing. [More info](https://www.malwarebytes.com/blog/scams/2026/07/sextortion-scammers-are-exploiting-shinyhunters-data-leaks)

- **Fake GitHub Repositories Distribute Malware**: Attackers are creating malicious GitHub software repositories backed by fake star/fork metrics to trick developers into running code containing embedded supply-chain malware and credential stealers. [More info](https://www.cysecurity.news/2026/07/github-fake-repos-spread-malware-in-new.html)

- **Cruciferra Crypter Uses BYOVD and Process Ghosting**: The Mono-based Cruciferra crypter employs API unhooking, Bring Your Own Vulnerable Driver (BYOVD) privilege escalation, and Process Ghosting to run stealthy payloads completely in memory without leaving forensic artifacts on disk. [More info](https://thehackernews.com/2026/07/cruciferra-crypter-uses-byovd-and.html)

- **SourTrade Malvertising Assembles Payloads In-Browser**: The SourTrade campaign bypasses network security and file signatures by delivering raw assembly instructions that construct infostealer binaries directly inside victim browser memory. [More info](https://www.infosecurity-magazine.com/news/malvertising-builds-malware-in/)

- **TELESHIM Backdoor Abuses Telegram C2**: An East Asian cyber espionage actor targeting Middle Eastern government infrastructure is deploying TELESHIM, a backdoor abusing the Telegram API for C2 communications, alongside the machine-locked BINDCLOAK implant. [More info](https://thehackernews.com/2026/07/teleshim-abuses-telegram-for-c2-in.html)

- **Dysphoria DDoS Botnet Spreads to 200k Devices**: A rapidly growing IoT botnet named Dysphoria has infected over 200,000 devices globally. It leverages Solana and Ethereum domain resolving mechanisms for C2 resilience and can launch DDoS attacks exceeding 4 Tbps. [More info](https://www.bleepingcomputer.com/news/security/new-dysphoria-ddos-botnet-spreads-to-200k-devices-worldwide/)

## 📈 Trends

- **Daylight Security Launches Detection Program Visibility**: Daylight Security introduced a program for Managed Agentic MDR customers that centralizes detection logs across SIEM platforms and maps them directly to the MITRE ATT&CK matrix to highlight operational coverage gaps. [More info](https://hackread.com/daylight-security-detection-program-visibility/)

- **Proliferation of Unmanaged "Shadow AI" Agents**: Employees are actively creating unmanaged AI automations via Microsoft Copilot Studio and Zapier. Possessing persistent permissions without API discovery mechanisms, these agents introduce severe risks of credential exposure and unauthorized access. [More info](https://www.bleepingcomputer.com/news/security/shadow-ai-agents-are-multiplying-heres-how-to-find-and-secure-them/)

## 💥 Breaches & Leaks

- **Apple Sued Over Fake App Store Crypto Wallet**: Victims who lost $1.8 million in Bitcoin to a fraudulent Sparrow Wallet application on the iOS App Store have filed a lawsuit against Apple for negligent marketplace screening despite prior warning reports. [More info](https://www.bleepingcomputer.com/news/apple/apple-sued-over-fake-app-store-crypto-wallet-app-stealing-18m-in-bitcoin/)

- **Coca-Cola Confirms Fairlife Ransomware Data Theft**: Coca-Cola confirmed that the Anubis ransomware gang exfiltrated 1 TB of data from its Fairlife subsidiary. After the company refused ransom demands, the extortion group published the files online. [More info](https://www.bleepingcomputer.com/news/security/coca-cola-confirms-data-theft-in-fairlife-ransomware-attack/)

- **ShinyHunters Claims Ernst & Young Data Breach**: The ShinyHunters extortion group claims to have breached EY's Jira, GitHub, and Azure environments by compromising its IT support ticketing system, threatening to publish client tax and operational data unless paid. [More info](https://www.bleepingcomputer.com/news/security/ernst-and-young-data-breach-claimed-by-shinyhunters-extortion-gang/)

---

[⬅ Back to Archive](https://pranakn.github.io)
