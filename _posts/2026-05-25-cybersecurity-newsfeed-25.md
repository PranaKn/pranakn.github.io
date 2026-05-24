---
title: "Cybersecurity Newsfeed - 25/05/26"
date: 2026-05-24 18:39:31 -0300
categories: [News]
permalink: /posts/news-25-05-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-05-25.png
  alt: Cybersecurity Newsfeed - 25/05/26
---

# Cybersecurity Newsfeed

## 📅 25/05/26

## 🛡️ Vulnerabilities

- **Highly Critical Drupal Core SQL Injection Added to CISA KEV (CVE-2026-9082)**: CISA expanded its Known Exploited Vulnerabilities catalog by adding a maximum-severity SQL injection flaw affecting Drupal Core. The vulnerability allows unauthenticated attackers to execute arbitrary SQL commands via crafted requests, leading to database compromise and full administrative takeover. Federal agencies must patch the flaw by June 12, 2026. [More info (SecurityAffairs)](https://securityaffairs.com/192557/security-cve-2026-9082-drupals-highly-critical-sql-injection-flaw-is-already-under-active-attack.html) | [More info (CISA)](https://www.cisa.gov/news-events/alerts/2026/05/22/cisa-adds-one-known-exploited-vulnerability-catalog)

- **Qualcomm Snapdragon BootROM Hardware Vulnerability (CVE-2026-25262)**: Kaspersky researchers discovered a critical physical flaw in the Sahara protocol used during Emergency Download Mode (EDL) on Snapdragon chipsets (including MDM9x07 and MSM8909 series). Attackers with brief physical access can bypass secure boot to deploy persistent, undetectable malware. Traditional reboots can be simulated by the malware, making full battery/power disconnection the only recovery method. [More info](https://www.kaspersky.com/blog/qualcomm-cve-2026-25262/55811/)

- **Ubiquiti UniFi OS Maximum-Severity Flaws Patched**: Ubiquiti released urgent security patches covering three maximum-severity vulnerabilities in UniFi OS. The flaws include authentication bypass and remote code execution paths in the management interface, enabling unauthenticated attackers to hijack managed network consoles, intercept traffic, and modify configurations. [More info](https://www.bleepingcomputer.com/news/security/ubiquiti-patches-three-max-severity-unifi-os-vulnerabilities/)

- **Trend Micro Apex One Zero-Day Under Active Attack**: Trend Micro issued an urgent alert for an actively exploited zero-day vulnerability in its Apex One endpoint security platform. The flaw enables unauthorized remote code execution and privilege escalation, allowing attackers to bypass critical endpoint defenses. [More info](https://www.bleepingcomputer.com/news/security/trend-micro-warns-of-apex-one-zero-day-exploited-in-attacks/)

## 🎯 Adversaries

- **Megalodon Supply Chain Attack Targets 5,500+ GitHub Repositories**: A massive campaign compromised thousands of GitHub repositories in a short six-hour window by injecting backdoored GitHub Actions workflows (`SysDiag` or `Optimize-Build`). Targeting repositories with weak branch protections via forged commits, the malicious workflows leverage CI runner outbound access to exfiltrate cloud credentials, SSH keys, and OIDC tokens. [More info](https://hackread.com/github-repositories-megalodon-supply-chain-attack/)

- **"Mini Shai-Hulud" Supply Chain Campaign Hits 8,000+ Packages**: A sweeping two-phase supply chain campaign active since late April has poisoned over 8,000 npm and PyPI packages, including major libraries like TanStack and Mistral AI. The obfuscated payloads harvest GitHub tokens and cloud keys upon installation, executing lateral movement to infect further upstream repositories. [More info](https://thehackernews.com/2026/05/packagist-supply-chain-attack-infects-8.html)

- **Laravel-Lang Namespace Hijacked on Packagist**: Attackers exploited a GitHub-to-Packagist synchronization quirk allowing external fork commits to resolve as legitimate Git tags. Roughly 700 release tags across four localization libraries were republished with a malicious `helpers.php` backdoor, deploying a secondary credential stealer targeting SSH keys and cloud environment variables. [More info](https://www.bleepingcomputer.com/news/security/laravel-lang-packages-hijacked-to-deploy-credential-stealing-malware/)

- **Ghost CMS Vulnerability Exploited in Massive "ClickFix" Campaign (CVE-2026-26980)**: An unauthenticated SQL injection flaw within the slug filtering logic of Ghost CMS Content API (versions 3.24.0 to 6.19.0) is under active exploitation. Attackers inject code into `ORDER BY` clauses to exfiltrate session secrets and deploy deceptive overlay scripts that trick visitors into downloading malware. [More info](https://www.bleepingcomputer.com/news/security/ghost-cms-sql-injection-flaw-exploited-in-large-scale-clickfix-campaign/)

- **Rondodox Botnet Hijacks Legacy ASUS Routers**: The Rondodox botnet has resurfaced to build an expansive peer-to-peer DDoS and remote execution network. The malware scans for a long-standing firmware flaw from 2018 to drop encrypted modular binaries on unpatched, end-of-life edge devices. [More info](https://hackread.com/rondodox-botnet-2018-vulnerability-hijack-asus-routers/)

## 📈 Trends

- **Dutch Authorities Seize 800 "Bulletproof" Host Servers**: In a massive international infrastructure takedown, law enforcement in the Netherlands seized 800 servers linked to a bulletproof hosting provider. The firm deliberately ignored abuse complaints, acting as a primary C2 and operational launchpad for global ransomware and phishing syndicates. [More info](https://www.bleepingcomputer.com/news/security/netherlands-seizes-800-servers-of-hosting-firm-enabling-cyberattacks/)

- **Former US Telecom Executives Plead Guilty to Scammer Aid**: Two American executives, Adam Young and Harrison Gevirtz, pleaded guilty to providing specialized call routing and analytics infrastructure to international tech support scams. The duo advised India-based call centers on bypassing provider detection and evasion techniques. Sentencing is slated for June 2026. [More info](https://www.bleepingcomputer.com/news/security/former-us-execs-plead-guilty-to-aiding-tech-support-scammers/)

- **CinemaGoal Piracy App Weaponized for Credential Theft**: Italian police dismantled the CinemaGoal piracy streaming ring. Beyond unauthorized content distribution, the platform's custom streaming application secretly harvested user account authentication codes and personal data for secondary fraud operations. [More info](https://www.bleepingcomputer.com/news/legal/italy-disrupts-cinemagoal-piracy-app-that-stole-streaming-auth-codes/)

## 💥 Breaches & Leaks

- **JDownloader Website Compromised to Serve Malicious Installers**: Attackers breached the official JDownloader site CMS, manipulating access control lists to replace official Windows and Linux alternative installer links with a heavily obfuscated Python-based remote access trojan (RAT). The malware achieves persistence via a SUID-root binary to run arbitrary code from a C2 server. [More info](https://www.cysecurity.news/2026/05/jdownloader-website-breach-spreads.html)

---

[⬅ Back to Archive](https://pranakn.github.io)
