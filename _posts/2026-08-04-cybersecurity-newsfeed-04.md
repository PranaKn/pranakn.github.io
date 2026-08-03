---
title: "Cybersecurity Newsfeed - 04/08/26"
date: 2026-08-03 09:00:00 -0300
categories: [News]
permalink: /posts/news-04-08-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-08-04.png
  alt: Cybersecurity Newsfeed - 04/08/26
---

# Cybersecurity Newsfeed

## 📅 04/08/26

## 🛡️ Vulnerabilities

- **N-able N-central Authentication Bypass (CVE-2026-18577)**: Threat actors are actively exploiting a patch bypass flaw in N-able N-central RMM servers to gain unauthenticated administrative access. Attackers leverage the Take Control feature to pivot to high-value endpoints like domain controllers and establish persistence via Cloudflare tunnels. N-able has released hotfix 2026.3.1.7 and urges immediate patching. [More info](https://www.darkreading.com/vulnerabilities-threats/attackers-exploit-n-able-patch-bypass-flaw) | [More info](https://www.bleepingcomputer.com/news/security/n-able-warns-of-n-central-auth-bypass-flaw-exploited-in-attacks/)

- **CISA KEV Adds N-able N-central Flaw (CVE-2026-18577)**: CISA added the N-able N-central authentication bypass vulnerability to its Known Exploited Vulnerabilities Catalog following evidence of active exploitation. Federal agencies are mandated under BOD 26-04 to prioritize remediation, conduct compromise assessments, and apply risk-based management. [More info](https://www.cisa.gov/news-events/alerts/2026/08/03/cisa-adds-one-known-exploited-vulnerability-catalog)

- **INC Ransomware Targets SonicWall SMA 1000 Zero-Days**: INC Ransomware is exploiting chained zero-day vulnerabilities (CVE-2026-15409 & CVE-2026-15410) in SonicWall SMA 1000 appliances to establish WebSocket tunnels and gain root access. Attackers harvest credentials and MFA seeds to pivot internally, prompting urgent patching recommendations. [More info](https://thehackernews.com/2026/08/inc-ransomware-emerges-as-dominant.html) | [More info](https://www.securityweek.com/recent-sonicwall-vulnerabilities-exploited-in-ransomware-attacks/)

- **FaceHugger Flaws in Hugging Face Diffusers**: Three high-severity vulnerabilities (CVE-2026-44827, CVE-2026-45804, CVE-2026-44513) in Hugging Face's Diffusers library enable remote code execution via TOCTOU race conditions when downloading pretrained models. Maintainers resolved the flaws in version 0.38.0. [More info](https://thehackernews.com/2026/08/hugging-face-diffusers-flaws-could-let.html)

## 🎯 Adversaries

- **DOUBLECUP ClickFix Service Delivers CountLoader and DeviceManager**: A Russian loader-as-a-service uses ClickFix social engineering to impersonate platforms like Salesforce and deploy malware via steganographic PNGs in browser caches. Command-line execution drops CountLoader for profiling and DeviceManager, a Python-based Windows RAT using EtherHiding smart contracts. [More info](https://www.bleepingcomputer.com/news/security/new-doublecup-clickfix-service-hides-malware-in-browser-cache-images/)

- **Fake Roblox Xeno Executor Pushes Infostealer RAT**: Fake installers for the Xeno Executor scripting tool distributed across gaming forums deliver a multi-stage Java payload. The malware steals browser credentials, Discord/Roblox session tokens, crypto wallets, and provides interactive shell access. [More info](https://www.bleepingcomputer.com/news/security/fake-roblox-xeno-script-launcher-pushes-infostealer-rat-malware/)

- **18 Malicious npm Packages Target Alibaba Developers**: A supply chain attack utilizing typosquatting and dependency confusion targeted developers affiliated with Alibaba Group (@ali scope). The malicious packages deploy a cross-platform RAT that terminates security software on Windows, executes detached binaries on Linux, and adds Launch Agents on macOS. [More info](https://thehackernews.com/2026/08/18-malicious-npm-packages-deliver-cross.html)

- **Chrome Passkey Security Domain Secret Attacks**: Unit 42 detailed post-compromise attack vectors (Pass-ta-key, Silver Pass-ta-key, Golden Pass-ta-key) targeting Google Password Manager on Windows TPM devices. Local malware can exploit re-enrollment flows or extract the Security Domain Secret from client memory to decrypt synchronized passkeys. [More info](https://thehackernews.com/2026/08/google-password-manager-attacks-could.html)

- **Autonomous DeepSeek AI Agent Conducts Proxyjacking**: Cybersecurity firm Jesta Security intercepted an autonomous campaign operated by a weaponized DeepSeek Version 4 AI agent linked to a Chinese actor. The agent executed automated SSH sessions across over 1,200 hosts to deploy MicroSocks proxies, highlighting a shift toward real-time tactical AI threats. [More info](https://www.darkreading.com/cyberattacks-data-breaches/chinese-actor-deepseek-ai-agent-attack-security-firm)

- **Midnight Blizzard CaptiveCrunch Campaign Targets Hotel Wi-Fi**: Russian APT group Midnight Blizzard (Storm-2945) is compromising captive portals on public Wi-Fi networks to deliver CornFlake RAT and ChocoShell infostealer via fake update prompts. The campaign also incorporates device code phishing to hijack M365 sessions. [More info](https://www.infosecurity-magazine.com/news/captivecrunch-midnight-blizzard/) | [More info](https://www.securityweek.com/russian-state-apt-linked-to-recent-public-wi-fi-gateway-hacking/)

- **Spear-Phishing Campaign Delivers HollowFrame and Matryoshka**: A targeted attack on a law firm used counterfeit python311.dll files for DLL sideloading to deliver HollowFrame and Rust-based Matryoshka backdoors. The malware configured Microsoft Defender exclusions and used private GitHub repositories for covert C2 infrastructure. [More info](https://www.infosecurity-magazine.com/news/hollowframe-fake-python-dll/)

## 📈 Trends

- **AI Source Attribution Framework (SAGA) Advances Deepfake Forensics**: Researchers at UC Riverside developed the SAGA framework to identify the specific model, version, and developer behind AI-generated videos. By analyzing temporal frame signatures, SAGA enables security teams to trace deepfakes back to their origin platforms. [More info](https://www.darkreading.com/cyber-risk/new-tool-advances-ai-generated-video-detection)

- **BTMOB Android RAT Ecosystem Decentralizes**: Flare research reveals that source code leaks and infrastructure disputes led to the fragmentation of the BTMOB Android RAT platform. The code leak spawned a secondary market of unauthorized resellers, custom variants, and impersonator channels on Telegram. [More info](https://www.bleepingcomputer.com/news/security/inside-the-underground-business-of-btmob-rat/)

## 💥 Breaches & Leaks

- **UK Police Database Breach Exposes 100,000+ Records**: Extortion group ExfilSquad claimed a breach of the UK Police National Legal Database, leaking 1.9 GB of data (~135,000 records) containing officer names, organizations, and work emails. Misconfigured Microsoft Power Pages web portals are suspected to have allowed unauthenticated data extraction. [More info](https://www.bleepingcomputer.com/news/security/exfilsquad-hackers-leak-info-of-over-100-000-uk-police-officers-staff/) | [More info](https://securityaffairs.com/196525/data-breach/pnld-confirms-data-breach-affecting-uk-police-and-justice-staff.html)

- **South Korea's KT Fined $39M Over Security Failures**: Telecom giant KT was fined following rogue base station attacks using stolen femtocell certificates that intercepted traffic from 16,000+ subscribers. Investigators also found 38 internal servers compromised by BPFDoor backdoor malware following unpatched web vulnerabilities and SQL injections. [More info](https://www.infosecurity-magazine.com/news/koreas-largest-telco-kt-fine-39m/)

---

[⬅ Back to Archive](https://pranakn.github.io)
