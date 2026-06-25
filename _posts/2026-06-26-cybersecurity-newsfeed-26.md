---
title: "Cybersecurity Newsfeed - 26/06/26"
date: 2026-06-25 09:00:00 -0300
categories: [News]
permalink: /posts/news-26-06-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-06-26.png
  alt: Cybersecurity Newsfeed - 26/06/26
---

# Cybersecurity Newsfeed

## 📅 26/06/26

## 🛡️ Vulnerabilities

- **curl Remediates 18 Flaws in Largest Release (CVE-2026-8932)**: The open-source data transfer utility curl has addressed 18 vulnerabilities, including a 25-year-old historic flaw in libcurl discovered via AI-assisted code analysis. The bug allows for authentication bypass during mutual TLS (mTLS) connection reuse. The release also fixes multiple logic, credential confusion, and memory safety issues. [More info](https://securityaffairs.com/194220/security-curl-fixes-a-25-year-old-bug-in-its-largest-cve-release-yet.html)

- **Ubiquiti UniFi OS Improper Access Control (CVE-2026-34908)**: CISA added a critical flaw in Ubiquiti UniFi OS to its Known Exploited Vulnerabilities (KEV) catalog. The flaw allows unauthenticated threat actors with network access to execute unauthorized configuration modifications, and ransomware campaigns have actively targeted exposed systems. [More info](https://www.cysecurity.news/2026/06/ubiquiti-unifi-os-flaw-under-active.html)

- **Cisco Catalyst SD-WAN Zero-Day Exploited (CVE-2026-20245)**: Mandiant released a technical analysis detailing how threat actors exploited a critical zero-day command injection flaw in Cisco Catalyst SD-WAN components. Attackers used the tenant-upload feature to execute arbitrary commands, establish a rogue root account named "troot," and applied anti-forensic measures to erase trace artifacts. [More info](https://www.bleepingcomputer.com/news/security/mandiant-reveals-how-cisco-sd-wan-zero-day-attacks-gained-root-access/)

## 🎯 Adversaries

- **Gamaredon APT Overhauls Arsenal Against Ukraine**: The Russian advanced persistent threat group Gamaredon has significantly adapted its offensive tooling, deploying six novel PowerShell downloaders—including the multi-functional "PteroPaste" utility. The group is routing C2 infrastructure via legitimate services like Telegram and Dropbox, while also exploiting a WinRAR flaw (CVE-2025-8088) to achieve automatic execution. [More info](https://www.darkreading.com/threat-intelligence/russia-apt-gamaredon-arsenal-defense)

- **New macOS Malware Deceives AI Security Analyzers**: A new macOS malware strain implements anti-analysis defenses specifically engineered to deceive artificial intelligence tools and automated sandboxes. By inserting structurally deceptive but valid fake error handling routines and dead-end logic paths, the malware induces false negatives or parsing failures in machine learning triaging workflows. [More info](https://www.bleepingcomputer.com/news/security/new-macos-malware-embeds-fake-errors-to-confuse-ai-analysis-tools/)

## 📈 Trends

- **Shop Tracking App Exploited for Callback Phishing**: Threat actors are abusing Shopify's order-tracking application, Shop, to conduct sophisticated callback phishing campaigns. Because the fraudulent invoice notifications route through the official Shop app infrastructure, they bypass traditional email filters to trick victims into calling a fraudulent customer support number. [More info](https://www.bleepingcomputer.com/news/security/order-tracking-app-shop-abused-to-push-callback-phishing-attacks/)

- **Bluekit Phishing Kit Adopts Browser-in-the-Middle Capabilities**: The phishing-as-a-service platform Bluekit has integrated advanced Adversary-in-the-Middle (AitM) reverse proxy servers to intercept credentials and session tokens in real time, effectively bypassing multi-factor authentication. The kit also features local AI assistance for dynamic lure modifications and voice-cloning capabilities. [More info](https://www.bleepingcomputer.com/news/security/bluekit-phishing-kit-adopts-browser-in-the-middle-for-login-theft/)

- **Ransomware Incidents Surge by 55% in Europe**: Ransomware attacks across Europe spiked significantly during the first four months of 2026 compared to the same period in 2025. The shift is attributed to threat groups exploiting unpatched regional systems following tactical fragmentation from legacy syndicates like LockBit, with a heavy focus on downstream supply chain extortion in the UK, Germany, France, Italy, and Spain. [More info](https://www.infosecurity-magazine.com/news/increase-ransomware-europe/)

- **"Renovarix" Scam Targets Website Owners**: A deceptive cybercrime campaign is utilizing fake domain renewal notices under the "Renovarix" brand to defraud website administrators. Using public registry data, the scheme initiates urgent emails with countdown timers that redirect targets to a fake checkout interface, collecting personal and financial credentials. [More info](https://www.malwarebytes.com/blog/threat-intel/2026/06/fake-domain-renewal-emails-trick-website-owners-into-paying-scammers)

## ⚖️ Legal & Disruptions

- **PirloTV Sports Piracy Network Dismantled**: The Alliance for Creativity and Entertainment (ACE), collaborating with Mexican law enforcement and UEFA, successfully seized 44 domains linked to the illegal live-streaming platform PirloTV. Prior to its disruption, the network accumulated more than 950 million annual visits globally across Latin America, Spain, and the US. [More info](https://www.bleepingcomputer.com/news/security/pirlotv-sports-piracy-network-disrupted-as-44-domains-seized/)

- **DraftKings Hacker Sentenced to 18 Months**: Nathan Austad, operating under the cyber alias "Snoopy," was sentenced to 18 months in federal prison for orchestrating a massive 2022 credential-stuffing attack against DraftKings. Austad compromised nearly 68,000 customer accounts using leaked historical data, resulting in the siphoning of approximately $600,000. [More info](https://www.bleepingcomputer.com/news/security/draftkings-hacker-snoopy-sentenced-to-18-months-in-prison/)

---

[⬅ Back to Archive](https://pranakn.github.io)
