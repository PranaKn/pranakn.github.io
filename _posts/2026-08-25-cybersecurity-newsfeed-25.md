---
title: "Cybersecurity Newsfeed - 25/08/26"
date: 2026-08-24 09:00:00 -0300
categories: [News]
permalink: /posts/news-25-08-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-08-25.png
  alt: Cybersecurity Newsfeed - 25/08/26
---

# Cybersecurity Newsfeed

## 📅 25/08/26

## 🛡️ Vulnerabilities

- **Active Exploitation of WordPress miniOrange Plugin (CVE-2026-61979 & CVE-2026-15981)**: Attackers are actively chaining two authentication bypass flaws in the miniOrange SAML 2.0 Single Sign-On plugin. By forcing HMAC-SHA1 signature acceptance using identity provider public keys and treating OpenSSL errors as success, actors forge SAML responses for admin access. Unpatched paid instances remain heavily targeted. [More info](https://www.bleepingcomputer.com/news/security/hackers-target-wordpress-sites-in-miniorange-auth-bypass-attacks/)

- **Oracle HTTP Server and WebLogic Flaw Added to KEV (CVE-2026-21962)**: CISA added an improper access control vulnerability affecting Oracle HTTP Server and WebLogic Server Proxy Plug-in to its Known Exploited Vulnerabilities Catalog. FCEB agencies must patch under BOD 26-04 as the bug allows unauthorized post-exploitation access. [More info](https://www.cisa.gov/news-events/alerts/2026/08/24/cisa-adds-one-known-exploited-vulnerability-catalog)

- **Critical Keycloak Password Reset Flaw (CVE-2026-18963)**: Red Hat patched a 9.1 CVSS-rated flaw in Keycloak stemming from improper state validation in the reset-credentials flow. Unauthenticated remote attackers can bypass email action token verification to take over any user or admin account. Disabling the "Forgot password" option serves as an immediate workaround. [More info](https://thehackernews.com/2026/08/critical-keycloak-password-reset-flaw.html)

## 🎯 Adversaries

- **ShinyHunters Vishing Campaign Targets ReliaQuest**: Extortion group ShinyHunters executed voice phishing impersonating security staff to lead employees to a fake Okta portal (`reliaquest.claims`). Although one worker provided credentials and approved an MFA prompt, robust device-trust policies blocked internal pivoting and prevented data compromise. [More info](https://www.securityweek.com/reliaquest-confirms-shinyhunters-hack-but-says-impact-was-limited/) | [More info](https://www.bleepingcomputer.com/news/security/reliaquest-confirms-failed-data-theft-attack-after-shinyhunters-breach/)

- **Iran-Linked Cyberattack Takes Down UK Power Plant**: Threat actors linked to Iran disabled a small British power generation site for four days, creating operational disruption. Though the national grid was unaffected, experts warn that scalable attacks against distributed energy resources present systemic operational technology security risks. [More info](https://www.securityweek.com/iran-linked-hackers-shut-down-uk-power-plant-for-four-days/)

- **ToxicPanda 2.0 Android Banking Trojan Evolves**: An updated version of ToxicPanda targets 349 banking and crypto apps via AWS-hosted droppers. It abuses Android Accessibility Services to enable Wireless Debugging, capturing lock-screen PINs to bypass MFA/passkeys and granting attackers full root shell-level access for on-device fraud. [More info](https://www.darkreading.com/mobile-security/toxicpanda-banking-trojan-matures-enterprise-threat) | [More info](https://www.malwarebytes.com/blog/mobile/2026/08/toxicpanda-2-0-can-take-over-your-android-phone-and-banking-apps)

- **Fake "SysScan" Scams Trick Users into Removing Antivirus**: Scammers are operating AI-generated Microsoft-branded "SysScan" sites that perform false browser checks to claim third-party antivirus software is unsupported. The campaign harvesting personal and banking details via Telegram APIs while setting up remote-access scams. [More info](https://www.malwarebytes.com/blog/threat-intel/2026/08/fake-microsoft-security-scans-trick-victims-into-uninstalling-their-antivirus)

- **GTA VI Hype Weaponized to Distribute Malware**: Attackers are riding enthusiasm around Grand Theft Auto VI by distributing 113GB torrents filled with zero-byte padding and a 50KB malicious payload. Once run, bytecode disables Windows Defender via PowerShell. Fake installer sites and credential-stealing phishing portals are also active. [More info](https://securityaffairs.com/197772/malware/cybercriminals-turn-gta-vi-leaks-into-malware-bait.html)

- **WordlistLoader and SynkLoader Emergence**: Researchers identified WordlistLoader (delivered via ClearFake ClickFix and EtherHiding to drop Amatera Stealer) and SynkLoader (delivered via Teams phishing impersonating IT support). SynkLoader deploys C# profilers, reverse proxies, VNC modules, and PhishLocker components. [More info](https://thehackernews.com/2026/08/wordlistloader-delivers-amatera-via.html)

## 📈 Trends

- **Microsoft Teams Policy to Block External Meeting Bots**: Microsoft rolled out an admin policy allowing organizations to automatically block external third-party bots and transcription tools from Teams meetings. The feature aims to disrupt social engineering campaigns where attackers utilize external chats and bots for initial access. [More info](https://www.bleepingcomputer.com/news/security/microsoft-teams-now-lets-admins-block-external-bots-from-meetings/)

## 💥 Breaches & Leaks

- **Hardcoded Encryption Key Exposes South Korean Startup Platform Data**: South Korean startup platform Modu-ui Changup suffered a breach exposing evaluation comments and emails of 5,000 applicants. Attackers crawled an accessible API where administrators had hardcoded the encryption key, allowing straightforward decryption of harvesting records. [More info](https://www.bleepingcomputer.com/news/security/south-korean-startup-platform-breach-exposes-key-management-failures/)

---

[⬅ Back to Archive](https://pranakn.github.io)
