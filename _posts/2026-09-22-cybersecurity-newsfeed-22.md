---
title: "Cybersecurity Newsfeed - 22/09/26"
date: 2026-09-21 09:00:00 -0300
categories: [News]
permalink: /posts/news-22-09-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-09-22.png
  alt: Cybersecurity Newsfeed - 22/09/26
---

# Cybersecurity Newsfeed

## 📅 22/09/26

## 🛡️ Vulnerabilities

- **Zyxel GS1900 Series Buffer Overflow (CVE-2026-7273)**: CISA added a critical stack-based buffer overflow flaw in Zyxel GS1900 Series Switches to its KEV Catalog. The vulnerability allows remote attackers to gain full post-exploitation control over exposed devices, prompting CISA to mandate rapid remediation for federal agencies under BOD 26-04. [More info](https://www.cisa.gov/news-events/alerts/2026/09/21/cisa-adds-one-known-exploited-vulnerability-catalog)

- **Active Exploitation of Three Linux Kernel Flaws**: CISA warned of active exploitation targeting three Linux kernel vulnerabilities: CVE-2025-39964 (a 14-year-old race condition in AF_ALG), CVE-2026-53266 (an out-of-bounds write in ebtables SNAT), and CVE-2025-39682 (a kTLS receive-path logic bug). These flaws allow local attackers to crash systems, modify memory, or escalate privileges. [More info](https://www.bleepingcomputer.com/news/security/cisa-alerts-of-active-exploitation-of-three-linux-kernel-flaws/)

- **Meta Muse AI Audio Traffic Interception**: A security flaw in Meta's Muse AI desktop application allows local malware to intercept and alter voice dictation traffic. Due to insecure local IPC channels and missing endpoint encryption, unauthorized processes can tap live audio streams without needing administrative privileges. [More info](https://www.theregister.com/ai-and-ml/2026/09/21/meta-muse-ai-app-flaw-lets-local-malware-redirect-dictation-traffic/5297980)

## 🎯 Adversaries

- **Fake LastPass Installers Distribute Rapuncel Stealer**: A wide campaign spoofing over 40 major brands delivers the Rapuncel infostealer paired with a Microsoft-attested kernel driver acting as an EDR killer. The driver disables 145 security tools while the stealer harvests credentials, crypto wallets, and session tokens via GitHub redirect chains and DLL side-loading. [More info](https://www.securityweek.com/fake-lastpass-installers-push-kernel-level-edr-killer-rapuncel-stealer/)

- **Exvicy MaaS Framework Drives ClickFix Attacks**: Security researchers uncovered Exvicy, a malware-as-a-service framework built on stolen code from ErrTraffic. Exvicy injects fake Cloudflare verification prompts into compromised WordPress sites, tricking users into executing malicious PowerShell scripts via Win+R. [More info](https://www.infosecurity-magazine.com/news/exvicy-clickfix-framework/)

- **Attackers Abuse npm Trusted Publishing for GHAPPIER Loader**: Threat actors leveraged stolen developer credentials to abuse npm's OIDC-based Trusted Publishing in the `@dforge-core/dforge-mcp` package. The compromised releases drop GHAPPIER, an in-memory interactive shellloader linked to the PolinRider campaign, proving build provenance does not guarantee source code safety. [More info](https://www.infosecurity-magazine.com/news/attackers-abuse-npm-trusted/)

- **RatHat Android Trojan Employs Generative AI**: A novel Android trojan named RatHat uses generative AI to automate real-time device navigation, interact with UI elements, and bypass security controls. Distributed through smishing and malvertising, the malware facilitates automated fraud on infected devices. [More info](https://www.securityweek.com/rathat-android-trojan-uses-ai-for-automation/)

## 📈 Trends

- **FBI Updates CJIS Security Policy to Version 6.1**: The FBI CJIS Security Policy v6.1 raises mandatory encryption standards from 128-bit to 256-bit for data outside secure facilities, mandates monthly vulnerability scans, and enforces strict MFA and continuous auditing models across law enforcement systems. [More info](https://www.bleepingcomputer.com/news/security/fbis-cjis-v61-what-security-teams-need-to-know/)

## 💥 Breaches & Leaks

- **BigCommerce Merchant Data Breach via Ribon Apps**: BigCommerce alerted merchants to a supply chain breach caused by compromised API keys and integration vulnerabilities in third-party Ribon apps. Attackers exfiltrated transactional logs and personal identifiable information (PII), prompting forced API key rotations. [More info](https://www.bleepingcomputer.com/news/security/bigcommerce-alerts-merchants-of-data-breach-linked-to-ribon-apps/)

- **ShinyHunters Hacks Rival Clop Ransomware Leak Site**: Threat group ShinyHunters defaced the leak site of Clop ransomware using an unauthenticated file upload flaw in Grav CMS. Demanding an eight-figure extortion payment, ShinyHunters claims to have stolen Clop's internal databases, private keys, source code, and historical victim payment records. [More info](https://www.darkreading.com/cyberattacks-data-breaches/shinyhunters-hacked-clop-what-about-clops-victims)

---

[⬅ Back to Archive](https://pranakn.github.io)
