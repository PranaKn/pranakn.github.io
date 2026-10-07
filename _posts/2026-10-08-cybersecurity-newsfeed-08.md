---
title: "Cybersecurity Newsfeed - 08/10/26"
date: 2026-10-07 09:00:00 -0300
categories: [News]
permalink: /posts/news-08-10-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-10-08.png
  alt: Cybersecurity Newsfeed - 08/10/26
---

# Cybersecurity Newsfeed

## 📅 08/10/26

## 🛡️ Vulnerabilities

- **Active Exploitation of Atlassian Data Center Flaw (CVE-2026-21589)**: Threat actors are actively exploiting a critical arbitrary file access bug (CVSS 9.3) in self-managed Atlassian products including Jira, Confluence, Bitbucket, Bamboo, and Crowd. A path-normalization flaw converts `::` to `/`, allowing attackers to read webroot files like `crowd.properties` to harvest plaintext credentials and forge admin accounts. [More info](https://www.helpnetsecurity.com/2026/10/07/exploitation-critical-atlassian-flaw-cve-2026-21589/) | [More info](https://www.bleepingcomputer.com/news/security/hackers-exploit-critical-atlassian-flaw-after-public-poc-release/) | [More info](https://thehackernews.com/2026/10/atlassian-data-center-flaw-draws.html)

- **Unpatched Critical LMCache ZeroMQ Flaw (CVE-2026-105192)**: An unpatched flaw (CVSS 9.8) in LMCache versions 0.3.9–0.5.5 in multiprocess mode allows unauthenticated remote attackers to execute arbitrary code with process privileges. The vulnerability stems from unauthenticated message deserialization via Python's `pickle` module. [More info](https://thehackernews.com/2026/10/unpatched-critical-lmcache-flaw-lets.html)

- **SonicWall Patches Pre-Auth SSRF (CVE-2026-102255)**: SonicWall released hotfixes for four SMA1000 series vulnerabilities, headlined by a CVSS 10.0 pre-authentication SSRF in the WorkPlace portal. Additional fixes address authenticated OS command injection (CVE-2026-102256), Zip Slip, and Stored XSS. [More info](https://thehackernews.com/2026/10/sonicwall-patches-cvss-100-pre.html)

- **Chrome 155 Fixes 247 Security Flaws**: Google released Chrome version 155, resolving 247 security issues, including four critical-severity use-after-free bugs in the Chromecast, Browser, Navigation, and Track components (CVE-2026-106382, CVE-2026-106197, CVE-2026-106358, and CVE-2026-106347). [More info](https://www.securityweek.com/chrome-155-update-patches-247-vulnerabilities/)

## 🎯 Adversaries

- **ccTLD Registry Hijacking Targets Google Domains**: Threat actors compromised third-party ccTLD registries for Ghana (.gh), Sierra Leone (.sl), and American Samoa (.as), modifying authoritative DNS records to obtain unauthorized domain-validated HTTPS certificates via Let's Encrypt and ZeroSSL for Google and YouTube domains. Google revoked the certificates and deployed Chrome CRLSets blocks. [More info](https://www.bleepingcomputer.com/news/security/hackers-hijack-google-domains-after-breaching-cctld-registries/) | [More info](https://www.theregister.com/security/2026/10/07/attackers-hijacked-top-level-domains-minted-fake-security-certs-for-google-and-other-orgs/5301718) | [More info](https://thehackernews.com/2026/10/attackers-hijack-gh-sl-and-as.html)

- **MALFEX Campaign Distributes Overlord RAT via npm**: Researchers uncovered eight malicious npm packages with over 40,000 downloads delivering information stealers and the Go-based Overlord RAT. The packages use lifecycle hooks and Solana blockchain transactions to fetch C2 addresses, alongside postinstall scripts deploying the "movinlike" stealer. [More info](https://thehackernews.com/2026/10/eight-malicious-npm-packages-downloaded.html)

- **Ongoing "FortiBleed" Attacks Lock Out FortiGate Admins**: An FBI and CISA joint advisory warns of ongoing attacks targeting internet-facing Fortinet FortiGate firewalls and SSL VPN gateways. Threat actors use leaked credentials and password spraying to extract and crack legacy password hashes, create unauthorized admin accounts, and lock out legitimate administrators before deploying ransomware like INC/Lynx and Payload. [More info](https://www.bleepingcomputer.com/news/security/fbi-ongoing-fortibleed-attacks-lock-out-fortigate-vpn-admins/) | [More info](https://www.helpnetsecurity.com/2026/10/07/fortinet-fortibleed-campaign-fbi-advisory/)

- **PoeLLM Malware Infects 3,400 AI and LLM Servers**: The Canto Incognito campaign infected over 3,400 exposed AI/LLM servers (including LiteLLM, Gotenberg, Gitea, and Ivanti Sentry) with PoeLLM malware to mine XMRig and Iron cryptocurrencies. C2 IP addresses are dynamically derived from poem text hosted in a GitHub repository. [More info](https://thehackernews.com/2026/10/poellm-malware-infects-3400-servers-to.html)

## 📈 Trends

- **Web3 Smart Contracts Used for Dynamic C2 Infrastructure**: Palo Alto Unit 42 research highlights threat actors adopting Web3 smart contracts to execute single-transaction, botnet-wide C2 infrastructure updates. Combined with open-source dependency poisoning, actors harvest elevated cloud identity tokens and CI/CD secrets. [More info](https://unit42.paloaltonetworks.com/web3-cloud-supply-chain-attacks/)

- **Autonomous AI Discovery Trends from Microsoft FORGE Lab**: Insights from Microsoft's FORGE Lab highlight 140 Windows CVEs and 155 open-source bugs discovered via its autonomous harness, MDASH. The report outlines key shifts in operational scale, token-economics balancing, and integrating automated PoC generation to avoid triage bottlenecks. [More info](https://www.microsoft.com/en-us/security/blog/2026/10/07/3-lessons-from-frontier-ai-vulnerability-research/)

- **Ransomware Groups Systematically Target Backup Repositories**: CISA, FBI, and NSA released joint guidance detailing how groups like BlackMatter, ALPHV/BlackCat, and Gunra leverage compromised admin credentials to wipe, reformat, or encrypt backup and disaster recovery systems prior to primary network encryption. [More info](https://www.bleepingcomputer.com/news/security/ransomware-has-a-new-target-is-your-backup-ready/)

- **Microsoft Outlook to Block .msix Attachments**: Exchange Online will automatically add `.msix` and `.msixbundle` file extensions to the default `BlockedFileTypes` list in `OwaMailboxPolicy`, preventing users from sending, receiving, or downloading these installer packages to curb package-based malware distribution. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-outlook-to-block-msix-attachments-used-in-attacks/)

- **Autonomous Agentic Pen-Testing via Edgescan Atomic**: Edgescan launched an autonomous penetration testing platform driven by agentic AI to continuously validate complex enterprise attack paths, focus on business-logic bugs and access controls, and enforce scope through an execution policy layer. [More info](https://www.helpnetsecurity.com/2026/10/07/edgescan-atomic/)

## 💥 Breaches & Leaks

- **Advantest Confirms Data Theft in Ransomware Attack**: Japanese semiconductor test equipment maker Advantest Corporation began issuing breach notifications following a February 2026 ransomware attack. Exfiltrated server files contained PII, including full names, DoBs, Social Security numbers, driver's licenses, passports, and medical records. [More info](https://www.bleepingcomputer.com/news/security/advantest-confirms-personal-information-stolen-in-ransomware-attack/)

## ⚖️ Legal & Policy

- **Musician Sentenced for $10M AI Bot Streaming Fraud Scheme**: A federal judge sentenced Michael Smith to 18 months in prison and ordered $8 million in forfeiture for operating a $10 million streaming royalty fraud scheme that used over 1,000 automated bot accounts and VPNs to stream AI-generated music billions of times across major platforms. [More info](https://www.bleepingcomputer.com/news/security/musician-gets-18-months-in-prison-for-10-million-streaming-fraud-using-ai-bots/)

---

[⬅ Back to Archive](https://pranakn.github.io)
