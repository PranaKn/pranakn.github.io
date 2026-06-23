---
title: "Cybersecurity Newsfeed - 24/06/26"
date: 2026-06-23 09:00:00 -0300
categories: [News]
permalink: /posts/news-24-06-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-06-24.png
  alt: Cybersecurity Newsfeed - 24/06/26
---

# Cybersecurity Newsfeed

## 📅 24/06/26

## 🛡️ Vulnerabilities

- **Eight-Year-Old Samsung KNOX Kernel Flaw (CVE-2026-20971)**: Researchers discovered a high-severity use-after-free vulnerability impacting millions of Galaxy devices (S9 to S25). Caused by a race condition between the PROCA and FIVE subsystems, local apps could exploit it to gain elevated kernel control. A patch was issued in January 2026. [More info](https://securityaffairs.com/194090/security-samsung-knox-kernel-uaf-exposes-millions-of-galaxy-devices.html)

- **Cisco Unified CM SSRF Actively Exploited (CVE-2026-20230)**: Cisco warned of active exploitation targeting improper input validation in Unified Communications Manager. Remote, unauthenticated attackers can use crafted HTTP requests to write malicious files and escalate privileges to root when the WebDialer service is active. [More info](https://www.bleepingcomputer.com/news/security/cisco-unified-cm-sme-flaw-cve-2026-20230-now-exploited-in-attacks/)

- **"Cordyceps" CI/CD Structural Vulnerability**: Security firm Novee disclosed a widespread flaw class affecting GitHub Actions across thousands of major repositories, including Microsoft, Google, Apache, and Cloudflare. The issue allows command injection and repository hijacking via simple pull requests or comments. [More info](https://hackread.com/cordyceps-ci-cd-flaw-microsoft-google-apache-repos-hijack/)

- **"SquidBleed" Memory Leak Plagues Squid Proxies**: A critical uninitialized memory leak vulnerability tracing back to the late 1990s was discovered in Squid caching proxy servers. Attackers can trigger a buffer over-read using malformed chunked transfer-encoding requests to expose active web session data. [More info](https://www.theregister.com/security/2026/06/23/mythos-discovers-squidbleed-a-memory-leak-thats-gone-undetected-since-clinton-era/5260367)

## 🎯 Adversaries

- **macOS "ClickFix" Tactics Evolve**: A new campaign relies on fake browser updates or Google Meet error overlays to trick macOS users into executing terminal commands. The attack silently mounts a DMG file, bypassing Gatekeeper to install information stealers targeting crypto wallets and credentials. [More info](https://www.bleepingcomputer.com/news/security/new-macos-clickfix-attack-silently-mounts-dmgs-to-push-infostealer/)

- **PowerShell Scripts Hijack Telegram Accounts**: Kaspersky highlighted a multi-stage campaign targeting local Telegram state files via obfuscated PowerShell scripts embedded in cracked software downloads. The malware exfiltrates session tokens to bypass 2FA and mirror victim accounts. [More info](https://news.backbox.org/2026/06/23/how-hackers-use-powershell-scripts-to-steal-telegram-accounts-kaspersky-official-blog/)

- **Typosquatting Attack Mimics "postcss" on npm**: Threat actors deployed a lookalike package targeting developers with a malicious pre-install script. Once pulled, the payload scans environment variables and hardcoded cloud infrastructure keys to execute supply chain compromises. [More info](https://www.infosecurity-magazine.com/news/lookalike-npm-package-postcss/)

- **"CryptoBandits" Target Hardware and Tor Proxies**: Delivering its payload via infected USB drives, this malware targets crypto investors by monitoring system clipboards to swap out destination wallet addresses. It also installs localized Tor proxies to discreetly exfiltrate private recovery seeds. [More info](https://hackread.com/cryptobandits-malware-usb-drives-tor-steal-crypto/)

## 📈 Trends

- **Rise of Enterprise "Shadow AI" Exposure**: An N-able report detailed a sharp increase in corporate data exfiltration risks stemming from employees using unauthorized third-party AI tools and extensions. Security teams are urged to implement deep packet inspection to monitor unregulated AI traffic. [More info](https://www.helpnetsecurity.com/2026/06/23/n-able-shadow-ai-visibility/)

- **GitHub Hardens "actions/checkout" Defaults**: In response to persistent supply chain risks, GitHub updated its official checkout tool to automatically block unauthorized token access in pull requests originating from forked repositories. [More info](https://thehackernews.com/2026/06/github-updates-actionscheckout-to-block.html)

- **Proactive Behavioral Fuzzing Combats Zero-Days**: Security researchers demonstrated how advanced behavioral fuzzing models can map out expected exploitation pathways and validate EDR telemetry before public exploit payloads even exist. [More info](https://www.bleepingcomputer.com/news/security/the-exploit-doesnt-exist-you-can-still-prove-it-works-against-you/)

- **Phishing Exploits Native M365 Collaboration Features**: Attackers are increasingly abusing document comments and mention notifications inside Microsoft 365. Because the notification alerts come directly from legitimate Microsoft servers, they bypass traditional secure email gateways. [More info](https://www.helpnetsecurity.com/2026/06/23/microsoft-365-collaboration-features-phishing/)

## 💥 Breaches & Leaks

- **Tata Electronics Affected by Cyberattack**: Following a data leak by extortion group World Leaks (suspected rebrand of Hunters International), Tata Electronics confirmed an infrastructure compromise. Over 200,000 files allegedly tied to Apple and Tesla manufacturing specs were leaked on the dark web. [More info](https://www.bleepingcomputer.com/news/security/tata-electronics-confirms-cyberattack-as-hackers-leak-data/)

- **London Hydro Discloses Data Breach**: Canadian electricity provider London Hydro reported a perimeter breach that exposed customer names, billing accounts, and historical electricity consumption data. Operational technology systems governing the grid remained isolated. [More info](https://www.securityweek.com/canadian-electricity-provider-london-hydro-discloses-data-breach/)

- **"jaredfromsubway" MEV Bot Drained of $15M**: The notorious Ethereum network trading bot was compromised via a complex smart contract exploit. Attackers manipulated decentralized exchange liquidity pools to force bad trades, emptying the bot's multi-million dollar reserves. [More info](https://www.bleepingcomputer.com/news/security/jaredfromsubway-mev-bot-hacked-in-15-million-crypto-theft/)

## ⚖️ Legal & Law Enforcement

- **Scattered Spider Members Plead Guilty to TfL Attack**: Multiple operators associated with the syndicate pleaded guilty in federal court for their role in the ransomware campaign against Transport for London, which severely disrupted payment and portal services. [More info](https://www.bleepingcomputer.com/news/security/scattered-spider-members-plead-guilty-to-hacking-transport-for-london/)

- **Algerian National Indicted for Cybercrime Marketplaces**: US federal authorities indicted an individual accused of managing the administrative setup and financial escrow systems for top-tier illicit marketplaces trading in malware and stolen PII. [More info](https://cyberscoop.com/algerian-man-charged-cybercrime-marketplaces/)

## 📚 Others

- **Hack The Box Expands Incident Response Labs**: The enterprise readiness platform introduced collaborative live-fire team labs focused on cloud infrastructure compromises, active directory exploitation, and real-time skill analytics for security leaders. [More info](https://www.helpnetsecurity.com/2026/06/23/hack-the-box-expands-cyber-readiness-platform/)

---

[⬅ Back to Archive](https://pranakn.github.io)
