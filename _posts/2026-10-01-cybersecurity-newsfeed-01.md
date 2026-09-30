---
title: "Cybersecurity Newsfeed - 01/10/26"
date: 2026-09-30 09:00:00 -0300
categories: [News]
permalink: /posts/news-01-10-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-10-01.png
  alt: Cybersecurity Newsfeed - 01/10/26
---

# Cybersecurity Newsfeed

## 📅 01/10/26

## 🛡️ Vulnerabilities

- **Cisco Catalyst SD-WAN Manager Auth Bypass (CVE-2026-76504)**: CISA added this high-risk URI hex encoding vulnerability to its Known Exploited Vulnerabilities catalog following active exploitation. Improper handling of URI encoding allows unauthenticated remote attackers to bypass API authentication rules using strings like `%6a` to obtain administrative access. Administrators should inspect logs for unauthorized `j_security_check` entries and apply fixed software releases immediately. [More info](https://www.cisa.gov/news-events/alerts/2026/09/30/cisa-adds-one-known-exploited-vulnerability-catalog) | [More info](https://www.bleepingcomputer.com/news/security/cisco-warns-of-new-sd-wan-authentication-bypass-zero-day-exploited-in-attacks/)

- **Zimbra Collaboration Suite Command Injection (CVE-2026-73570)**: Threat actors are actively exploiting a critical unauthenticated command injection bug in Zimbra's SNMP notification handling. When `zimbra-snmp` is enabled, attackers can execute arbitrary code via crafted SMTP requests, deploying JSP web shells, establishing systemd/cron persistence, and executing LDAP queries to harvest secrets. [More info](https://thehackernews.com/2026/09/attackers-exploit-zimbra-flaw-to-deploy.html)

- **MikroTik RouterOS Pre-Auth RCE (CVE-2026-84411)**: CISA warned of a critical pre-authentication integer underflow vulnerability in RouterOS's web management service request body handling. An unauthenticated attacker can send a single crafted HTTP request to achieve root-level arbitrary code execution or cause a denial-of-service state. [More info](https://www.bleepingcomputer.com/news/security/cisa-warns-of-critical-pre-auth-rce-flaw-in-mikrotik-routeros/)

- **TeamViewer Patches Multiple High-Severity Flaws**: TeamViewer issued an urgent advisory requesting users to update client software across Windows, Linux, and macOS. The primary bug, an improper access control issue (CVE-2026-92370), allows remote session bypass leading to arbitrary code execution. Other patched vulnerabilities cover path traversal, heap buffer overflow, and race conditions. [More info](https://www.bleepingcomputer.com/news/security/teamviewer-urges-users-to-patch-severe-flaws-as-soon-as-possible/)

- **Chrome and Firefox Release Major Security Updates**: Google patched 32 defects in Chrome, including a critical buffer overflow bug in ANGLE (CVE-2026-102331) and high-severity V8 engine type confusion flaws. Mozilla released Firefox 157, patching 76 security issues including use-after-free conditions and sandbox escapes. [More info](https://www.securityweek.com/chrome-firefox-updates-patch-over-100-vulnerabilities/)

- **Citrix NetScaler Pre-Auth Memory Overflow (CVE-2026-88772)**: Threat actors are actively exploiting a critical pre-authentication memory overflow flaw in the DTLS parsing component of Citrix NetScaler ADC and Gateway appliances. The vulnerability allows root-level shellcode execution, dropping new PHP web shells like WHIPSHOT and Python-based tunneling tools like SLAPSHOT. [More info](https://thehackernews.com/2026/09/attackers-exploit-netscaler-flaw-for.html) | [More info](https://thehackernews.com/2026/09/citrix-netscaler-cve-2026-88772-exploit.html)

- **OpenSSL DTLS Memory Leak (CVE-2026-84782)**: OpenSSL patched a high-severity DTLS memory leak occurring during handshake message retransmissions. Resent datagrams incorrectly use paused buffer offsets, transmitting unencrypted heap memory to remote peers or triggering application crashes due to out-of-bounds reads. [More info](https://thehackernews.com/2026/09/openssl-fixes-high-severity-dtls-flaw.html)

## 🎯 Adversaries

- **OpenAI Disrupts Model Distillation Campaign Linked to Moonshot AI**: OpenAI disrupted a coordinated operation that submitted thousands of prompts to extract reasoning capabilities from its models. Attackers exploited a decryption flaw by copying encrypted reasoning data from one session and prompting the model to transcribe it in plain text in another. Core activity was attributed to individuals linked to Moonshot AI. [More info](https://cyberscoop.com/openai-moonshot-ai-model-distillation-attack/)

- **Malicious Custom GPTs Deliver RATs via ClickFix Lures**: Threat actors are deploying malicious Custom GPTs (such as "Plus 5.6") hosted on ChatGPT's official domain to distribute remote access Trojans. The GPTs instruct users to visit a backup Google Sites domain where a fake Cloudflare CAPTCHA tricks them into executing a malicious PowerShell command via ClickFix social engineering. [More info](https://www.darkreading.com/cyberattacks-data-breaches/malicious-custom-gpts-chatgpt-rat-delivery-lure) | [More info](https://thehackernews.com/2026/09/attackers-abuse-chatgpt-custom-gpts-to.html)

- **Star Blizzard Deploys CosmicPulse via RedFlick Technique**: Russian state-sponsored group Star Blizzard adopted a delivery chain called RedFlick to distribute the CosmicPulse backdoor. Phishing emails containing password-protected VHDX archives trigger an embedded LNK file that fetches an MSI installer, configuring scheduled tasks for reconnaissance, WebDAV setup, and payload execution. [More info](https://www.bleepingcomputer.com/news/security/russian-state-hackers-use-new-redflick-technique-to-push-malware/) | [More info](https://www.securityweek.com/russian-apt-star-blizzard-uses-redflick-infection-chain-in-recent-attacks/)

- **Phishing Campaign Abuses MSP360 for Dual-RMM Access**: Digitally signed MSP360 Remote Monitoring and Management (RMM) installers are being distributed via phishing emails posing as software updates or meeting invites. After establishing initial access and modifying firewall rules, attackers deploy ConnectWise ScreenConnect as a redundant remote management channel. [More info](https://thehackernews.com/2026/09/attackers-abuse-msp360-to-deploy.html)

## 📈 Trends

- **Over 543,000 Credentials Exposed on Public GitHub Repositories**: A study by Truffle Security scanning 224 million repositories revealed more than 543,000 valid credentials exposed with a median exposure time of 784 days. Despite default Push Protection introduced in 2023, over half of the active secrets fall into unblocked categories such as Google API keys and database strings. [More info](https://www.bleepingcomputer.com/news/security/over-543-000-valid-credentials-exposed-in-public-github-repositories/)

- **Microsoft Entra ID to Enforce CSP to Block Script Injection**: Starting mid-October 2026, Microsoft Entra ID will enforce updated Content Security Policy (CSP) rules on `login.microsoftonline.com` to limit executable scripts strictly to trusted Microsoft CDN domains, mitigating cross-site scripting and credential theft risks. [More info](https://www.bleepingcomputer.com/news/security/microsoft-to-block-entra-id-script-injection-attacks-starting-october/)

- **360 Netlab AI Security Intelligence Report**: 360 Netlab highlighted emerging risks across autonomous AI agents, including self-replicating prompt injection worms, GitHub token leaks, and OAuth credential hijacking targeting the Model Context Protocol Python SDK, alongside mobile malware like RatHat integrating AI capabilities. [More info](https://blog.netlab.360.com/aian-quan-zhuan-ti-zhou-bao-8/)

- **360 Netlab Financial Cybersecurity Report**: The September 2026 financial report covers MasterCard DPAN enumeration attacks causing card-not-present fraud, GoldFactory abusing Android work profiles via Vwork, and RatHat AI-assisted malware utilizing accessibility services and reverse proxies to capture credentials and bypass MFA. [More info](https://blog.netlab.360.com/jin-rong-xing-ye-wang-luo-an-quan-jian-ce-yue-bao-202609/)

## 💥 Breaches & Leaks

- **Bitget Crypto Exchange Suffers $387.5M Hack via Zero-Day Flaws**: Cryptocurrency exchange Bitget suffered a $387.5 million breach following zero-day exploits targeting two third-party security appliances. North Korean state-sponsored threat actors extracted database credentials, deployed web shells, and moved laterally to the production wallet job server to execute unauthorized transfers. [More info](https://www.bleepingcomputer.com/news/security/bitget-hacked-via-zero-day-in-third-party-security-products/)

---

[⬅ Back to Archive](https://pranakn.github.io)
