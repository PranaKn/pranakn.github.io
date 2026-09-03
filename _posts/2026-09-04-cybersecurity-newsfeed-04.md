---
title: "Cybersecurity Newsfeed - 04/09/26"
date: 2026-09-03 09:00:00 -0300
categories: [News]
permalink: /posts/news-04-09-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-09-04.png
  alt: Cybersecurity Newsfeed - 04/09/26
---

# Cybersecurity Newsfeed

## 📅 04/09/26

## 🛡️ Vulnerabilities

- **Cisco Nexus 9000 Series Critical RCE (CVE-2026-20212)**: Cisco patched a critical remote code execution flaw with a CVSS score of 9.8 affecting ten Silicon One-based Nexus 9000 series switches. Unauthenticated attackers can send specially crafted input to exposed TCP ports in the default Layer 3 VRF to execute code with root privileges or cause switch reloads. [More info](https://securityaffairs.com/198366/security/cisco-fixed-critical-rce-in-nexus-9000-series-switches.html)

- **Critical Buffer Overflow in HPE ArubaOS-CX (CVE-2026-73749)**: HPE issued patches for a critical buffer overflow vulnerability in its ArubaOS-CX network operating system. Unauthenticated remote attackers can send malicious packets to an affected daemon to execute code with elevated privileges. The advisory covers 23 additional high- and medium-severity flaws. [More info](https://www.bleepingcomputer.com/news/security/hpe-patches-critical-arubaos-cx-remote-code-execution-flaw/)

- **Critical Elementor Pro Flaw Exploited in Website Takeovers (CVE-2026-32475)**: Attackers are actively exploiting a critical file-upload validation flaw in Elementor Pro versions 4.2.1 and earlier. Unauthenticated attackers bypass extension checks to upload PHP payloads and gain remote code execution, with Wordfence blocking nearly 200,000 exploit attempts. [More info](https://www.bleepingcomputer.com/news/security/critical-elementor-pro-flaw-exploited-to-take-over-wordpress-sites/)

- **Urgent Security Updates Issued for Plex Media Server**: Plex released an urgent security advisory directing users to update Plex Media Server (1.43.3+) and Plex Desktop (1.115.0+) to fix unassigned vulnerabilities that could lead to remote exploitation and network compromise. [More info](https://www.bleepingcomputer.com/news/security/plex-warns-users-to-patch-security-vulnerabilities-immediately/)

- **CrowdStrike Falcon Zero-Day Privilege Escalation ("FalconFlank")**: Security researcher Chaotic Eclipse disclosed a local privilege escalation zero-day targeting the CrowdStrike Falcon agent. The proof-of-concept abuses Falcon's macro removal feature to escalate local accounts to administrative privileges on Windows 11 and Windows Server 2025. [More info](https://securityaffairs.com/198342/hacking/chaotic-eclipse-releases-crowdstrike-falcon-zeroday-falconflank.html)

- **CISA Adds Seven Actively Exploited Flaws to KEV Catalog**: CISA added seven security vulnerabilities to its Known Exploited Vulnerabilities catalog involving SonicWall SMA, Sangoma Switchvox, JFrog Artifactory, Starlette, Kestra OSS, and LiteLLM. Attackers are exploiting these flaws for command execution, credential theft, and cryptomining. [More info](https://thehackernews.com/2026/09/cisa-adds-seven-exploited-flaws-as.html)

## 🎯 Adversaries

- **Coder Infrastructure Hijacked to Distribute Trojanized Terraform Modules**: Attackers compromised Coder's Cloudflare setup to add malicious registry servers for registry.coder.com. Users requesting modules received trojanized versions designed to exfiltrate environment variables, API keys, SSH keys, and CI/CD secrets to a lookalike domain. [More info](https://www.bleepingcomputer.com/news/security/coders-registry-infrastructure-compromised-to-push-malicious-modules/)

- **ThreatsDay Briefing: Teams Vishing, Outsider PaaS, and Dropbox Compromise**: Recent threat monitoring details Microsoft Teams vishing delivering Node.js implants, the return of the Outsider phishing platform, the BlueKit phishing framework targeting financial executives, and the compromise of 5,000 Dropbox accounts via legacy Lenovo ID integrations. [More info](https://thehackernews.com/2026/09/threatsday-ceo-phishing-kits-5k-dropbox.html)

- **BraZetsu Modular Python Framework Targets Brazilian Enterprises**: Group-IB detailed BraZetsu, an AI-assisted Python malware framework fueling the underground "Infected Marketplace." Designed to target corporate financial systems in Brazil and broader LATAM, it steals banking credentials and Brazilian CNAB financial EDI files. [More info](https://thehackernews.com/2026/09/brazetsu-malware-turns-compromised.html)

- **StreamRat Android Banking Malware Spread via Meta and TikTok Ads**: A malicious ad campaign reaching over 570,000 Spanish-speaking users promoted fake free TV streaming apps to infect Android devices with StreamRat. The Trojan abuses Accessibility services to capture keystrokes, overlay fake banking login forms, and grant remote control. [More info](https://www.malwarebytes.com/blog/news/2026/09/streamrat-android-malware-spreads-through-meta-and-tiktok-ads)

- **iMessage Zero-Click Pegasus Spyware Infection Confirmed in Serbia**: Forensic investigations by Citizen Lab and SHARE Foundation confirmed a Serbian pro-democracy student activist was infected with NSO Group's Pegasus spyware via an iMessage zero-click exploit ahead of election cycles. [More info](https://www.infosecurity-magazine.com/news/pegasus-zero-click-exploit/)

- **Shai-Hulud Infostealer Worm Expands Scope to 469 Targets**: Research revealed variants of the Shai-Hulud infostealer worm have expanded their harvesting capabilities to target 469 locations across developer workstations, CI/CD tools, cloud configs, and AI developer credentials to automate software supply chain propagation. [More info](https://thehackernews.com/2026/09/shai-huluds-reach-just-grew-to-469.html)

## 📈 Trends

- **Microsoft Warns of ASCII Smuggling Techniques in Mass Phishing**: Microsoft observed a high-volume phishing campaign adapting "ASCII smuggling" prompt-injection techniques to email. By inserting invisible Unicode tag characters into financial terms, attackers break signature matching to bypass security filters without altering visual text. [More info](https://www.microsoft.com/en-us/security/blog/2026/09/03/ascii-smuggling-crosses-over-from-ai-prompt-injection-to-phishing-evasion/)

- **Windows 11 August Update Bug Resets Custom Mouse Settings**: Microsoft confirmed a bug in the Windows 11 KB5120998 preview update that resets custom mouse cursor and animation settings back to default values. The issue exclusively impacts non-English system installations across versions 24H2 and 25H2. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-kb5120998-mouse-reset-bug-affects-only-non-english-pcs/)

## 💥 Breaches & Leaks

- **Thomson Reuters C-Track Court System Data Breach**: Thomson Reuters reported that unauthorized actors accessed cloud storage and production environments for its C-Track court management platform, impacting 24 court systems across 11 U.S. states, the Virgin Islands, and Ontario, exposing SSNs, health records, and sealed court data. [More info](https://thehackernews.com/2026/09/thomson-reuters-court-software-breach.html)

## 📚 Others

- **Major Service Outage Hits Anthropic Claude AI Models**: Anthropic experienced a significant service outage causing elevated error rates and failed requests across multiple Claude models, including Mythos 5.1, Fable 5.1, and Opus 5 tiers, across both API and web interfaces. [More info](https://www.bleepingcomputer.com/news/artificial-intelligence/anthropic-confirms-claude-is-down-multiple-models-affected/)

- **OpenAI ChatGPT and Codex Experience Global Outage**: OpenAI reported a widespread infrastructure failure affecting over 15 components of ChatGPT and Codex, disabling conversation processing, Search, Voice mode, file uploads, and API features shortly before the planned rollout of its new model. [More info](https://www.bleepingcomputer.com/news/artificial-intelligence/openai-confirms-chatgpt-is-down-ahead-of-astra-model-launch/)

---

[⬅ Back to Archive](https://pranakn.github.io)
