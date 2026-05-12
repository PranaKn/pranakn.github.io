---
title: "Cybersecurity Newsfeed - 13/05/26"
date: 2026-05-12 09:00:00 -0300
categories: [News]
permalink: /posts/news-13-05-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-05-13.png
  alt: Cybersecurity Newsfeed - 13/05/26
---

# Cybersecurity Newsfeed

## 📅 13/05/26

## 🛡️ Vulnerabilities

- **Microsoft May 2026 Patch Tuesday (120 Flaws)**: Microsoft addressed 120 vulnerabilities, including several critical flaws across the Windows ecosystem and Office suite. While no zero-days were actively exploited at release, security teams are urged to prioritize the 12 "Critical" rated vulnerabilities to mitigate ransomware risks. [More info](https://blog.qualys.com/vulnerabilities-threat-research/2026/05/12/microsoft-patch-tuesday-may-2026-security-update-review) | [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-may-2026-patch-tuesday-fixes-120-flaws-no-zero-days/)

- **Fortinet Critical RCE Advisories**: Fortinet issued an advisory regarding Remote Code Execution (RCE) vulnerabilities in FortiSandbox and FortiAuthenticator. These flaws allow unauthenticated attackers to execute arbitrary code with elevated privileges, potentially compromising network isolation and identity management. [More info](https://www.bleepingcomputer.com/news/security/fortinet-warns-of-critical-rce-flaws-in-fortisandbox-and-fortiauthenticator/)

- **Exim BDAT Command Vulnerability**: A newly discovered vulnerability in the Exim mail transfer agent involves the improper handling of BDAT commands. This flaw could allow attackers to bypass security filters or cause a denial-of-service (DoS) condition on one of the world's most widely used mail servers. [More info](https://thehackernews.com/2026/05/new-exim-bdat-vulnerability-exposes.html)

- **Windows 10 KB5087544 Extended Security Update**: Microsoft released the KB5087544 update, marking a critical phase in the Extended Security Update (ESU) program. These security-only patches are vital for maintaining compliance and protecting legacy systems from emerging exploits targeting older architectures. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-releases-windows-10-kb5087544-extended-security-update/)

## 🎯 Adversaries

- **Fake "Claude Code" Installer Targets Devs**: Attackers are leveraging the popularity of Anthropic’s AI tools by creating fraudulent websites and GitHub repositories that deliver browser credential stealers. The malware harvests saved passwords, cookies, and session tokens. [More info](https://hackread.com/fake-claude-code-installer-devs-browser-credential-stealer/)

- **Operation HumanitarianBait Spyware**: This campaign utilizes fake humanitarian aid documents to deliver Python-based spyware. Targeting NGOs and relief workers, the malware exfiltrates sensitive files, records keystrokes, and monitors communications. [More info](https://hackread.com/operation-humanitarianbait-fake-aid-docs-python-spyware/)

- **Trickmo Trojan Evolves with TON Blockchain**: The Android banking trojan Trickmo now utilizes the TON (The Open Network) blockchain for its C2 infrastructure. This decentralized approach allows the malware to bypass traditional network defenses and IP-based blocking. [More info](https://securityaffairs.com/192003/malware-android-banking-trojan-trickmo-evolves-using-ton-network-for-c2.html)

- **AI-Augmented "Vibe Hacking" in LATAM**: Trend Micro identified a campaign targeting government and financial sectors using AI to generate deepfake audio and personalized phishing content. This shift signifies a new era of difficult-to-verify social engineering. [More info](https://www.trendmicro.com/en_us/research/26/e/vibe-hacking-two-ai-augmented-campaigns-target-government-and-financial-sectors-in-latin-america)

- **"ClickFix" SEO Poisoning for Mac Users**: Attackers are using fake search results for Claude AI to lure Mac users to fraudulent sites. Users are prompted to "fix" a browser error by running a terminal command, which executes an infostealer script. [More info](https://www.malwarebytes.com/blog/news/2026/05/fake-claude-search-results-lure-mac-users-into-clickfix-attack)

- **AD CS Exploitation Techniques**: Palo Alto Unit 42 released an analysis of how attackers abuse misconfigured Active Directory Certificate Services (AD CS) templates to escalate privileges and achieve persistent domain dominance. [More info](https://origin-unit42.paloaltonetworks.com/active-directory-certificate-services-exploitation/)

- **GhostLock Tool Abuses Windows APIs**: A new tool named GhostLock leverages built-in Windows APIs to deny read/write permissions to directories. Unlike traditional ransomware, it "locks" users out of files without altering the data, bypassing some encryption-based detection. [More info](https://www.bleepingcomputer.com/news/security/new-ghostlock-tool-abuses-windows-api-to-block-file-access/)

## 📈 Trends

- **OpenAI "Daybreak" Secure by Design**: OpenAI announced the "Daybreak" initiative, focusing on embedding security at every stage of the model lifecycle to mitigate risks like prompt injection and data poisoning. [More info](https://www.infosecurity-magazine.com/news/openai-daybreak-secure-by-design/)

- **Android 17 Anti-Scam Protections**: The upcoming Android 17 OS will integrate advanced AI-driven detection to combat banking scams, preventing unauthorized screen sharing and interception of OTPs. [More info](https://www.bleepingcomputer.com/news/security/android-17-to-expand-banking-scam-call-and-privacy-protections/)

- **RubyGems Suspends New Signups**: Following a surge in malicious package uploads containing backdoors, RubyGems has temporarily suspended new user signups to purge malicious content and refine verification. [More info](https://thehackernews.com/2026/05/rubygems-suspends-new-signups-after.html)

- **Signal Adds Social Engineering Warnings**: Signal has introduced proactive security warnings for messages from unknown contacts containing suspicious patterns, aimed at mitigating "pig butchering" and credential harvesting. [More info](https://www.bleepingcomputer.com/news/security/signal-adds-security-warnings-for-social-engineering-phishing-attacks/)

- **Pwn2Own Berlin 2026 Hits Capacity**: The hacking competition is set to demonstrate a record number of zero-day exploits focusing on automotive systems, smart home devices, and enterprise hardware. [More info](https://hackread.com/pwn2own-berlin-2026-hits-capacity-hackers-0-days/)

## 💥 Breaches & Leaks

- **UK ICO Fines South East Water £1.3M**: Following a 2024 data breach exposing 664,000 customers, the utility provider was fined for failing to implement appropriate technical measures for an insecure database. [More info](https://www.bleepingcomputer.com/news/security/uk-fines-water-supplier-13m-for-exposing-data-of-664k-customers/)

- **Skoda Online Shop Data Breach**: Skoda warned customers that unauthorized actors accessed names and contact details via its official online shop. While payment info was encrypted, the data may be used for phishing. [More info](https://www.bleepingcomputer.com/news/security/skoda-warns-of-customer-data-breach-after-online-shop-hack/)

- **Checkmarx Jenkins Package Compromised**: An official Checkmarx Jenkins package was compromised with an information stealer, threatening CI/CD pipelines by exfiltrating environment variables and source code. [More info](https://www.bleepingcomputer.com/news/security/official-checkmarx-jenkins-package-compromised-with-infostealer/)

## 📚 Others

- **Webinar: Fixing Gaps in Network Incident Response**: BleepingComputer is hosting a session covering automated forensics, hybrid environment visibility, and methods for reducing mean time to remediation (MTTR). [More info](https://www.bleepingcomputer.com/news/security/webinar-fixing-the-gaps-in-network-incident-response/)

---

[⬅ Back to Archive](https://pranakn.github.io)
