---
title: "Cybersecurity Newsfeed - 18/06/26"
date: 2026-06-17 09:00:00 -0300
categories: [News]
permalink: /posts/news-18-06-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-06-18.png
  alt: Cybersecurity Newsfeed - 18/06/26
---

# Cybersecurity Newsfeed

## 📅 18/06/26

## 🛡️ Vulnerabilities

- **Max-Severity Joomla JCE Plugin Flaw (CVE-2026-48907)**: CISA ordered federal agencies to urgently patch an improper access control vulnerability in the Widget Factory Joomla Content Editor (JCE) plugin. The flaw allows unauthenticated remote attackers to create editor profiles and execute malicious PHP code for full RCE. Due to active scanning and exploitation in the wild, it has been added to the KEV Catalog under BOD 26-04. [More info](https://www.bleepingcomputer.com/news/security/cisa-orders-feds-to-patch-max-severity-joomla-plugin-flaw-by-friday/)

- **Microsoft Releases Open-Source Anti-SSRF Library**: To mitigate Server-Side Request Forgery (SSRF) risks, Microsoft has published an open-source defensive wrapper library. The utility strictly validates outbound network requests against safety policies, internal address blocks, and loopback rules, providing developers a standard framework to prevent infrastructure exposure. [More info](https://www.helpnetsecurity.com/2026/06/17/microsoft-antissrf-open-source-library/)

## 🎯 Adversaries

- **Inc Ransomware Thrives on Security Basics**: An ongoing campaign demonstrates that Inc Ransomware achieves widespread compromise by mastering fundamental execution rather than using complex zero-days. The group exploits routine entry vectors like poorly secured RDP, weak credentials, and unpatched bugs to move laterally and exfiltrate data. [More info](https://www.darkreading.com/cyberattacks-data-breaches/inc-ransomware-thrives-by-mastering-the-basics)

- **Roblox Developers Targeted by Cookie-Stealing Malware**: A sophisticated campaign is distributing malicious packages disguised as legitimate development utilities and plugins within Roblox community spaces. Once executed, the info-stealer harvests session cookies and credentials, allowing attackers to bypass MFA and hijack high-value games. [More info](https://www.malwarebytes.com/blog/scams/2026/06/roblox-developers-are-losing-entire-games-to-malware-attacks)

- **Massive "FortiBleed" Campaign Hits 75,000 Fortinet Firewalls**: A large-scale credential stuffing and brute-force operation has compromised administrative and VPN credentials across thousands of internet-facing Fortinet devices worldwide. The attackers systematically converted the perimeter firewalls into listening posts to intercept downstream enterprise network data. [More info](https://www.theregister.com/cyber-crime/2026/06/17/massive-password-stealing-attack-hits-75k-fortinet-firewalls/5257877)

- **Junior Hacker Penetrates Corporate Network via Tailscale**: An individual successfully bypassed traditional perimeter security by convincing an internal user to authorize a new node connection or by exploiting exposed endpoint access keys on a Tailscale mesh VPN. The incident highlights the risks of misconfigured zero-trust overlay software. [More info](https://thehackernews.com/2026/06/junior-hacker-used-tailscale-and.html)

- **Rokarolla Android Banking Trojan Surfaces**: A robust new malware variant targets 217 distinct banking and cryptocurrency applications using a repertoire of 137 specific commands. Rokarolla abuses Android's Accessibility Services to capture keystrokes, intercept SMS, and generate deceptive overlay windows to execute fraudulent transactions. [More info](https://www.malwarebytes.com/blog/mobile/2026/06/rokarolla-android-malware-can-take-over-your-phone-and-steal-banking-logins)

- **Fishmongers Group Upgrades SprySocks Malware**: ESET Research uncovered an overhauled arsenal from the Fishmongers threat group targeting Windows systems. The updated SprySocks variant features advanced obfuscation to evade EDR solutions alongside modular capabilities to dynamically download plugin extensions and maintain long-term persistence. [More info](https://www.welivesecurity.com/en/eset-research/fishmongers-arsenal-upgraded-sprysocks-windows/)

## 📈 Trends

- **Active Crypto Clipper Campaign Uses Deceptive Apps**: Threat operators are using fraudulent sites mimicking legitimate crypto software to distribute malware that monitors the system clipboard. When a user copies a destination wallet string, the malware silently swaps it with an attacker-controlled address to steal digital assets. [More info](https://thehackernews.com/2026/06/crypto-clipper-campaign-abuses-fake.html)

- **"GitBait" Phishing Campaign Leverages GitHub Pages & SheetBest**: Attackers are hosting convincing phishing landing pages on GitHub's trusted infrastructure. When victims enter credentials, the backend script utilizes the SheetBest service to seamlessly transfer the stolen data straight into Google Sheets, bypassing traditional database server detections. [More info](https://www.infosecurity-magazine.com/news/gitbait-github-pages-sheetbest/)

- **India's Telegram Ban Causes BGP Routing Issues in UAE**: A temporary ban on Telegram in India inadvertently disrupted service access across parts of the United Arab Emirates. The outage stemmed from BGP route hijacking and sweeping IP blocks executed by Reliance. Users are currently leveraging MTProto proxy servers and VPNs to restore access. [More info](https://www.bleepingcomputer.com/news/security/indias-telegram-ban-hit-the-uae-too-heres-how-to-get-around-it/)

- **Malicious JetBrains Marketplace Plugins Steal AI API Keys**: Security researchers identified fifteen malicious development plugins across seven vendor accounts designed to steal DeepSeek and OpenAI API keys. When configured, the plugins transmit the keys via unencrypted HTTP to attacker-controlled infrastructure, amassing roughly 70,000 installations. [More info](https://hackread.com/malicious-jetbrains-plugins-steal-deepseek-openai-api-keys/)

## 💥 Breaches & Leaks

- **Kodak Confirms Data Breach After ShinyHunters Extortion Claims**: Photography and technology giant Kodak confirmed a security incident following claims made on the ShinyHunters dark web portal. External digital forensics experts are investigating the parameters of the breach, while the threat actors claim to have exfiltrated proprietary corporate repositories. [More info](https://www.bleepingcomputer.com/news/security/kodak-confirms-data-breach-claimed-by-shinyhunters-extortion-gang/)

## 🛠️ Tools

- **Tigera Introduces "Calico Lynx" for Kubernetes Security**: Tigera launched a new capability within its Calico Cloud platform to streamline containerized infrastructure defenses. The feature provides automated visibility, continuous threat detection, and real-time mitigation to enforce strict zero-trust rules dynamically across multi-cloud architectures. [More info](https://www.helpnetsecurity.com/2026/06/17/tigera-lynx/)

---

[⬅ Back to Archive](https://pranakn.github.io)
