---
title: "Cybersecurity Newsfeed - 16/10/26"
date: 2026-10-15 09:00:00 -0300
categories: [News]
permalink: /posts/news-16-10-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-10-16.png
  alt: Cybersecurity Newsfeed - 16/10/26
---

# Cybersecurity Newsfeed

## 📅 16/10/26

## 🛡️ Vulnerabilities

- **PwnEscape Critical Linux Kernel RCE (CVE-2026-99999)**: Discovered by pwn.ai during a Vercel security challenge, a flaw in kernel networking checksum handling allows guest VMs to leak 32 bytes of host memory per packet, crash hosts, or execute arbitrary code. Affects major stable kernel branches including 5.10, 5.15, 6.1, 6.6, 6.12, 6.18, and 7.2. [More info](https://thehackernews.com/2026/10/critical-pwnescape-linux-kernel.html)

- **Collabora Online RCE Exploited to Backdoor Nextcloud**: Threat actors are actively exploiting an unauthenticated HTTP RCE flaw in Collabora Online integrated with Nextcloud servers to bypass authorization, install web shells, and maintain long-term access. [More info](https://www.bleepingcomputer.com/news/security/hackers-exploit-collabora-rce-flaw-to-backdoor-nextcloud-servers/)

- **Atlassian File Exposure Added to CISA KEV (CVE-2026-21589)**: CISA added an Atlassian multiple products vulnerability involving accessible files/directories to external parties to its Known Exploited Vulnerabilities catalog following active exploitation. Federal agencies must patch under BOD 26-04. [More info](https://www.cisa.gov/news-events/alerts/2026/10/15/cisa-adds-one-known-exploited-vulnerability-catalog)

- **Chrome Patches 37 Security Flaws (Including 7 Critical)**: Google released updates for Chrome (build 155.0.8059.79/.80) addressing critical buffer overflow and use-after-free RCE flaws in the ANGLE graphics engine (CVE-2026-110152) and PDF components (CVE-2026-110136, CVE-2026-110147) that allow sandbox escapes. [More info](https://www.malwarebytes.com/blog/bugs/2026/10/update-chrome-google-fixes-37-security-flaws-including-seven-critical-bugs)

- **Drupal Field UI Core Remote Code Execution (CVE-2026-108097)**: Drupal issued security patches for a critical pre-render callback table processing flaw in its core Field UI module, allowing unauthenticated remote code execution when paired with contributed modules across versions 11.4.10, 11.3.19, and 10.6.19. [More info](https://thehackernews.com/2026/10/drupal-patches-critical-core-rce-flaw.html)

- **Langflow Authenticated RCE Flaw (CVE-2026-105740)**: Carrying a CVSS score of 9.9, attackers are exploiting Langflow instances prior to version 1.9.0 via stdio transport parameters in MCP server additions to execute unvalidated bash commands and extract system environment variables. [More info](https://thehackernews.com/2026/10/langflows-critical-authenticated-rce.html)

- **Palo Alto PAN-OS Authenticated Root RCE (CVE-2026-0322)**: Rated CVSS 8.6, active limited exploitation was detected targeting management interfaces on PA-Series, VM-Series, and Panorama devices running affected PAN-OS 10.2 through 12.2 branches. [More info](https://thehackernews.com/2026/10/palo-alto-networks-patches-pan-os.html)

## 🎯 Adversaries

- **Mass Proxyjacking Hijacks D-Link, Ubiquiti, and SAP Systems**: GreyNoise uncovered a campaign spanning 34 countries that exploits known edge vulnerabilities (including CVE-2024-3272, CVE-2024-3273, CVE-2021-44228, and CVE-2025-31324) to install Pawns.app bandwidth-sharing tools and persistent SSH keys. [More info](https://www.bleepingcomputer.com/news/security/hackers-hijack-d-link-ubiquiti-devices-to-resell-your-stolen-bandwidth/)

- **Fake AUR Packages Distribute Backdoors with Root Privileges**: Malicious packages impersonating `yay` and `paru` uploaded by account `marchos1as` to the Arch User Repository contained malicious installation scripts fetching root-level payloads via Wayback Machine links pointing to GitFlic. [More info](https://www.bleepingcomputer.com/news/security/fake-arch-linux-packages-push-malware-with-root-privileges/)

- **Citizen Lab Uncovers Ad-Based Zero-Click Candiru Spyware**: Al Jazeera devices were targeted via online ad networks connected to Israeli ad firm Discover-Tech, using injected tracking code to deliver zero-click exploits and deploy Candiru spyware without user interaction. [More info](https://thehackernews.com/2026/10/citizen-lab-traces-zero-click-candiru.html)

- **KGB RAT Marketed for Windows Surveillance**: An upgraded NjRAT variant priced at $150/month features keylogging, webcam/mic spying, Windows Credential Manager extraction, crypto clipboard hijacking, persistence via `ChromeUpdate` scheduled tasks, and psychological harassment tools. [More info](https://www.helpnetsecurity.com/2026/10/15/kgb-rat-windows-trojan-webcam-spying-password-theft/)

- **Aoki Infostealer Targets Developer AI Tools**: Symantec identified an updated Aoki variant specifically harvesting API keys, tokens, and configuration files (`.claude.json`, `config.toml`) from Anthropic Claude, OpenAI, GitHub Copilot, Cursor, Gemini, and JetBrains AI Assistant. [More info](https://www.infosecurity-magazine.com/news/aoki-infostealer-ai-coding/)

- **Fake AI Apps Spread Infostealers via ClickFix**: ANY.RUN identified over 1,200 sandbox analyses tied to fraudulent AI download portals and sponsored ads impersonating Claude, ChatGPT, and Gemini desktop apps that trick users into running PowerShell scripts via `mshta.exe`. [More info](https://thehackernews.com/2026/10/fake-ai-attacks-spread-across-us.html)

- **CikaBika Bot Operates C2 via Discord**: Darktrace discovered a new Rust-based RAT delivered via phishing PDFs with LNK shortcuts and Nim loaders, exploiting UAC bypasses and utilizing Discord channels and Ngrok for interactive command-and-control operations. [More info](https://www.securityweek.com/cikabika-bot-rat-uses-discord-for-cc/)

- **SilverFox Evolves Infrastructure with Time-Window Sandbox Evasion**: 360 Netlab detailed SilverFox's fifth infrastructure iteration, which uses scheduling logic in `api.php` to evaluate Referer headers and redirect requests to 360.com between 00:00 and 08:00 to evade automated sandbox analysis. [More info](https://blog.netlab.360.com/yin-hu-yun-duan-sheng-si-bo-xu-pian-cong-chi-xu-sheng-chan-dao-referer-shi-jian-chuang-bian-chong/)

- **PEERSTITCH Malware Targets Telecommunications via FortiManager**: Palo Alto Unit 42 revealed that activity cluster CL-STA-0954 exploited CVE-2024-47575 in FortiManager to deploy the custom PEERSTITCH Linux implant onto managed FortiGate firewalls for traffic manipulation and persistent reverse shell access. [More info](https://unit42.paloaltonetworks.com/fortimanager-cve-2024-47575-peerstitch-malware/)

## 📈 Trends

- **Android Introduces AI-Powered Anti-Scam Defenses**: Google added Gemini-backed analysis in Google Messages using Private AI Compute, on-device Gemini Nano link checking, background call-forwarding blocks, and international expansion of verified bank call protections. [More info](https://www.bleepingcomputer.com/news/security/android-gets-ai-defenses-against-messaging-scams-fake-calls/)

- **Fake CAPTCHAs Comprise 43% of Analyzed Phishing Kits**: Barracuda research shows phishing campaigns increasingly deploy human verification prompts to bypass security filters, with many leveraging ClickFix social engineering tactics to coax users into running PowerShell commands via the Run dialog. [More info](https://www.helpnetsecurity.com/2026/10/15/barracuda-fake-captcha-phishing-attacks/)

## 🔗 Supply Chain & Ecosystems

- **GhostAction Campaign Compromises 1,900 GitHub Accounts**: GitGuardian reported that threat actors used stolen Personal Access Tokens and infostealer credentials to inject malicious GitHub Actions workflows into over 30,000 repositories to harvest CI/CD secrets, AWS keys, and AI platform tokens. [More info](https://thehackernews.com/2026/10/ghostaction-compromises-about-1900.html)

---

[⬅ Back to Archive](https://pranakn.github.io)
