---
title: "Cybersecurity Newsfeed - 03/09/26"
date: 2026-09-02 09:00:00 -0300
categories: [News]
permalink: /posts/news-03-09-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-09-03.png
  alt: Cybersecurity Newsfeed - 03/09/26
---

# Cybersecurity Newsfeed

## 📅 03/09/26

## 🛡️ Vulnerabilities

- **SonicWall SMA 1000 Zero-Days (CVE-2026-83548 & CVE-2026-83549)**: Attackers are actively exploiting two zero-day vulnerabilities in SonicWall SMA 1000 series appliances. Chaining the unauthenticated SSRF (CVE-2026-83548, CVSS 10.0) and post-authentication OS command injection (CVE-2026-83549, CVSS 7.8) allows remote unauthenticated actors to execute arbitrary code on targeted gateways. Hotfixes are available. [More info](https://www.darkreading.com/vulnerabilities-threats/sonicwall-sma-1000-zero-days-unauthenticated-rce)

- **Sangoma Switchvox Flaw (CVE-2026-9586)**: Threat actors are actively exploiting a critical unauthenticated SQL injection vulnerability in the Sangoma Switchvox VoIP platform's `/pa` HTTP endpoint to deploy reverse shells and gather system data. Administrators are urged to update to version 8.4.0.2 or later. [More info](https://www.bleepingcomputer.com/news/security/hackers-exploit-sangoma-switchvox-flaw-to-deploy-reverse-shells/)

- **WordPress Backup Plugin Flaw (CVE-2026-19949)**: A high-severity second-order SQL injection in the All-in-One WP Migration and Backup plugin threatens over 3.25 million WordPress sites. Unauthenticated attackers can plant payloads via trackbacks to expose secret keys and achieve remote code execution. ServMask resolved the issue in version 7.110. [More info](https://www.bleepingcomputer.com/news/security/wordpress-backup-plugin-flaw-exposes-millions-of-sites-to-takeover-attacks/)

- **CISA Adds 7 Vulnerabilities to KEV Catalog**: CISA added seven flaws to its Known Exploited Vulnerabilities catalog following active exploitation, including vulnerabilities in Sangoma Switchvox, Kludex Starlette, Kestra OSS, BerriAI LiteLLM, JFrog Artifactory, and SonicWall SMA 1000. Federal agencies must patch under BOD 26-04. [More info](https://www.cisa.gov/news-events/alerts/2026/09/02/cisa-adds-seven-known-exploited-vulnerabilities-catalog)

- **GitSpawn Flaws in AI Coding Agents**: Researchers identified eight vulnerabilities across command-line AI coding agents (including Claude Code, Cursor, and Codex). Malicious `.git/config` files can execute repository-defined commands like `core.fsmonitor` outside the sandbox when opening a repository, bypassing workspace trust controls. [More info](https://thehackernews.com/2026/09/malicious-git-configs-can-make-claude.html)

- **Microsoft Exchange Authentication Bypass (CVE-2026-62911)**: Nearly 22,000 Microsoft Exchange servers remain exposed to a critical authentication bypass flaw (CVSS 8.0) that enables capture-replay attacks and privilege escalation. With public PoC code available, organizations are advised to apply August 2026 patches immediately. [More info](https://www.helpnetsecurity.com/2026/09/02/microsoft-exchange-cve-2026-62911-critical-authentication-bypass-flaw/)

## 🎯 Adversaries

- **Silver Fox Campaign Delivers Fake Software Installers**: Chinese threat actor Silver Fox is using clone websites to distribute fake software installers. The malware establishes persistence, modifies ACLs, disables Microsoft Defender via PowerShell, deletes shadow copies, and connects to C2 servers. [More info](https://thehackernews.com/2026/09/fake-software-installers-disable.html)

- **"Spring Ring" Vishing Targets Microsoft Teams**: A voice phishing campaign is targeting enterprise Microsoft Teams users. Attackers pose as IT help desk staff to trick employees into installing RMM tools or executing scripts, with advanced variants using PetitPotam NTLM relay operations against domain controllers. [More info](https://www.darkreading.com/cyberattacks-data-breaches/threat-gang-springs-vishing-attacks-microsoft-teams-users)

- **Pegasus and NoviSpy Used Against Serbian Activists**: Forensic analysis confirmed zero-click Pegasus and NoviSpy infections on devices belonging to Serbian student activists and civil society members. NoviSpy infections were linked to police detentions, while Pegasus targeted iOS devices ahead of local elections. [More info](https://cyberscoop.com/pegasus-novispy-variant-spyware-found-on-devices-of-serbian-activists/)

- **Gambling Goblin Hijacks Brazilian Web Servers**: Cybercrime cluster Gambling Goblin has compromised Brazilian government (`.gov.br`) and judicial (`.jus.br`) web servers using tools like DownPro and AlphaAgent. Rogue Apache modules strip security headers and redirect visitors to unauthorized betting platforms for SEO manipulation. [More info](https://thehackernews.com/2026/09/malicious-apache-modules-hijack.html)

- **Extradited Russian Hacker Faces US Charges**: Russian national Searzhudin Tamirlanovich Aktulaev was extradited from Cyprus to face US charges. He is accused of using 255 fake freelancing accounts to send malware-laden Excel macros to 80,000 users, deploying TVRAT and DarkVNC malware to harvest credentials. [More info](https://thehackernews.com/2026/09/extradited-russian-hacker-faces-charges.html) | [More info](https://www.bleepingcomputer.com/news/security/us-charges-russian-for-infecting-80-000-freelancers-with-malware/)

## 📈 Trends

- **Evolution of Tech Support Scams**: Tech support scams have moved beyond pop-ups to leverage search engine ads, hijacked search results, fake business listings, and fraudulent renewal notices. Scammers impersonate security vendors to gain remote device access, steal data, or install persistent backdoors. [More info](https://www.malwarebytes.com/blog/scams/2026/09/tech-support-scams-look-different-now-heres-what-to-watch-for)

- **Ransomware Protection Checklist for MSPs**: A comprehensive framework outlines six operational practices for MSPs to counter double-extortion ransomware: exposure reduction, continuous behavioral detection, 24/7 IR, immutable recovery storage, clean restoration procedures, and multi-tenant management. [More info](https://www.bleepingcomputer.com/news/security/ransomware-protection-for-msps-a-6-point-checklist-for-faster-recovery/)

## 💥 Breaches & Leaks

- **Lenovo Email Verification Flaw Impacts Dropbox Accounts**: A flaw in Lenovo's email verification process allowed attackers to create fake Lenovo IDs with victim email addresses. Because Dropbox trusted Lenovo's authentication, attackers accessed approximately 5,000 Dropbox accounts. Active Lenovo SSO sessions were terminated. [More info](https://www.bleepingcomputer.com/news/security/dropbox-accounts-breached-through-lenovo-email-verification-flaw/)

- **Dark Web Marketplace Nexus Sells 153M ID Scans**: Dark web marketplace Nexus is selling over 153 million driver's license scans alongside passport and medical records. The FBI opened an investigation into third-party verification provider IDScan.net regarding the potential exposure. [More info](https://www.malwarebytes.com/blog/news/2026/09/dark-web-site-puts-153-million-drivers-licenses-and-millions-more-ids-up-for-sale)

## 📚 Others

- **Revolut Phone Scam Wave in Jersey**: Law enforcement in Jersey warned of a surge in phone scams targeting local Revolut users, accounting for 75% of fraud cases and £180,000 in losses over four weeks. Scammers posed as bank fraud agents to trick victims into revealing credentials. [More info](https://www.bitdefender.com/en-us/blog/hotforsecurity/revolut-scam-jersey)

- **Microsoft Defender False Positives on Google Links**: Microsoft Defender for Office 365 (Safe Links) mistakenly flagged legitimate Google search URLs as malicious (incident MO1465962). Engineers are correcting the security classification to restore proper routing. [More info](https://www.bleepingcomputer.com/news/security/microsoft-defender-flags-legitimate-google-search-links-as-malicious/)

- **Sality Botnet Infrastructure Dismantled**: International law enforcement, alongside CrowdStrike and Shadowserver, dismantled the 23-year-old Sality peer-to-peer botnet. Operations seized C2 domains and sinkholed super peers to permanently disconnect over 15,000 infected hosts. [More info](https://www.helpnetsecurity.com/2026/09/02/sality-botnet-disruption-crowdstrike-law-enforcement/) | [More info](https://www.bleepingcomputer.com/news/security/sality-botnet-infrastructure-dismantled-in-joint-global-takedown/)

---

[⬅ Back to Archive](https://pranakn.github.io)
