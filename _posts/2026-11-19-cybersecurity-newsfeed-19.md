---
title: "Cybersecurity Newsfeed - 19/11/26"
date: 2026-11-18 09:00:00 -0300
categories: [News]
permalink: /posts/news-19-11-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-11-19.png
  alt: Cybersecurity Newsfeed - 19/11/26
---

# Cybersecurity Newsfeed

## 📅 19/11/26

## 🛡️ Vulnerabilities

- **Apache Roller Critical RCE Flaw (CVE-2026-129448)**: Rated CVSS 9.8, this unauthenticated remote code execution vulnerability stems from untrusted data deserialization in the XML-RPC interface (affecting versions 4.0.0 through 6.1.5) and is under active exploitation. Administrators must immediately upgrade to version 6.1.6 or disable XML-RPC functionality. [More info](https://securityaffairs.com/203419/security/apache-roller-rce-flaw-cve-2026-129448-under-active-attack.html) | [More info](https://thehackernews.com/2026/11/critical-apache-roller-rce-flaw-under.html)

- **"Java4Shell" Critical Memory Corruption (CVE-2026-114938)**: CISA issued an urgent advisory for a critical flaw in the Base64 decoder of the x86-64 HotSpot JVM (OpenJDK 17.0.6, 21, and 25 on AVX-512 systems), exposing enterprise tools like Jira, Confluence, Jenkins, and Elasticsearch to unauthenticated RCE. Organizations should apply Oracle’s November 2026 patches immediately or disable AVX-512 intrinsics (`-XX:UseAVX=2`). [More info](https://www.cisa.gov/news-events/alerts/2026/11/17/critical-java-vulnerability-requires-immediate-patching)

- **CISA Adds Four Flaws to KEV Catalog**: CISA added four actively exploited bugs to its Known Exploited Vulnerabilities catalog—Synology DSM/BeeStation OS improper output encoding (**CVE-2024-10441**, CVSS 9.8, targeted by C3RB3R ransomware affiliates), BerriAI LiteLLM sandbox escape (**CVE-2026-40217**), Vanderbilt REDCap code injection (**CVE-2026-90817**, CVSS 9.8), and Apache Axis 1.x unsafe reflection (**CVE-2026-90436**). Federal agencies and enterprises must remediate promptly. [More info](https://www.cisa.gov/news-events/alerts/2026/11/18/cisa-adds-four-known-exploited-vulnerabilities-catalog) | [CVE-2024-10441](https://www.cisa.gov/known-exploited-vulnerabilities-catalog?search_api_fulltext=CVE-2024-10441) | [CVE-2026-40217](https://www.cisa.gov/known-exploited-vulnerabilities-catalog?search_api_fulltext=CVE-2026-40217) | [CVE-2026-90817](https://www.cisa.gov/known-exploited-vulnerabilities-catalog?search_api_fulltext=CVE-2026-90817) | [CVE-2026-90436](https://www.cisa.gov/known-exploited-vulnerabilities-catalog?search_api_fulltext=CVE-2026-90436)

- **Decade-Old NGINX HTTP/2 Integer Underflow (CVE-2026-123007)**: NGINX patched five high-severity flaws, led by a 10-year-old HTTP/2 flow-control integer underflow (CVSS 9.2) enabling unauthenticated memory corruption and RCE. Administrators should upgrade to NGINX 1.31.9 or 1.30.7, or temporarily disable HTTP/2. [More info](https://thehackernews.com/2026/11/10-year-old-nginx-http2-flaw-lets.html)

- **AMD Hardware Interposer Bypasses TPM Lockout (CVE-2026-43613)**: Researchers demonstrated a physical interposer and voltage-glitching attack against SPI/Winbond RPMC flash chips that prevents counter increments, letting attackers brute-force BitLocker and Windows Hello PINs. Organizations should deploy November 2026 firmware updates and enforce complex alphanumeric PINs. [More info](https://thehackernews.com/2026/11/flash-chip-attack-bypasses-tpm-lockout.html)

- **Google Chrome 158 Patches 204 Flaws**: Google rolled out Chrome 158 across Windows, macOS, and Linux to resolve 204 vulnerabilities—including six critical and 62 high-severity memory safety and logic bugs—mitigating potential RCE and sandbox escape risks. [More info](https://www.securityweek.com/chrome-158-patches-204-vulnerabilities/)

## 🎯 Adversaries

- **Operation ShadowCloud Abuses GitHub and SharePoint**: Kaspersky uncovered a China-linked cyberespionage campaign active since early 2026 deploying two new backdoors, **GitDoor** and **GraphDoor**. By abusing legitimate GitHub repositories and Microsoft SharePoint APIs as covert C2 channels, the actors blend malicious traffic into normal enterprise cloud activity. [More info](https://www.cysecurity.news/2026/11/gitdoor-and-graphdoor-exploit-github.html)

- **EggStreme Malware Rebuilt to Evade EDR**: A suspected Chinese state-sponsored group refactored its EggStreme malware framework following public exposure, stripping artifacts and shifting to in-memory execution to bypass static signatures and behavioral heuristics in government targets. [More info](https://thehackernews.com/2026/11/eggstreme-hackers-rebuild-malware-with.html)

- **Optimizely Flaw Exploited to A/B Test Malware on 178 Top Sites**: Threat actors exploited an account signup bug (**CVE-2026-132224**) in Optimizely Web Experimentation to inject malicious JavaScript into snippets serving 178 major brands (including BBC, CNN, Zoom, and HSBC). Attackers iterated payloads to skim payment cards, swap crypto wallets, steal cookies, and deliver Coruna and DarkSword iOS exploit kits. [More info](https://krebsonsecurity.com/2026/11/attackers-used-optimizely-to-a-b-test-malware-on-top-websites/)

- **BubbleLoader Trojanizes WinRAR and Windows Utilities**: ReversingLabs discovered BubbleLoader, a stealthy loader that modifies legitimate Windows binaries (such as WinRAR and Windows Media Player) and hides encrypted payloads inside fake PNG image resources to execute malware in memory without disrupting normal app behavior. [More info](https://www.helpnetsecurity.com/2026/11/18/winrar-bubbleloader-malware/)

## 📈 Trends

- **Coinbase AI Defenses Block $4.7M in Deepfake Scam Transfers**: Coinbase disclosed that its autonomous machine learning fraud agent blocked roughly $4.7 million (91%) of user-authorized transfers tied to a fraudulent YouTube livestream featuring an AI deepfake of Elon Musk promoting a crypto giveaway. Real-time behavioral anomaly detection intervened directly with users where traditional access controls could not. [More info](https://www.bleepingcomputer.com/news/security/coinbase-blocks-47-million-in-transfers-to-elon-musk-deepfake-scam/)

## 💥 Breaches & Leaks

- **Wellington IT Breach Impacts 40 Irish Credit Unions**: Between October 2 and October 4, 2026, attackers used valid credentials and an automated script (five million requests) to exploit an authorization flaw in banking software provider Wellington IT’s CU Online infrastructure. Exposed data potentially includes payee names, addresses, and account numbers, while missing logs complicate impact assessment. [More info](https://www.bleepingcomputer.com/news/security/data-breach-impacts-40-irish-credit-unions-in-reported-it-provider-hack/)

---

[⬅ Back to Archive](https://pranakn.github.io)
