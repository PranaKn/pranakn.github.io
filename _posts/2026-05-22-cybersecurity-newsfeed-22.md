---
title: "Cybersecurity Newsfeed - 22/05/26"
date: 2026-05-21 19:13:12 -0300
categories: [News]
permalink: /posts/news-22-05-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-05-22.png
  alt: Cybersecurity Newsfeed - 22/05/26
---

# Cybersecurity Newsfeed

## 📅 22/05/26

## 🛡️ Vulnerabilities

- **Microsoft Defender Zero-Days Active in the Wild (CVE-2026-41091 & CVE-2026-45498)**: Microsoft and CISA warned of two zero-day flaws in the Microsoft Malware Protection Engine and Antimalware Platform. The bugs allow privilege escalation and denial-of-service, enabling attackers to disable defenses or elevate rights. CISA added them to the KEV catalog, mandating federal patching by June 3, 2026. [More info (CISA)](https://www.cisa.gov/news-events/alerts/2026/05/21/cisa-adds-two-known-exploited-vulnerabilities-catalog) | [More info (BleepingComputer)](https://www.bleepingcomputer.com/news/security/microsoft-warns-of-new-defender-zero-days-exploited-in-attacks/)

- **Google API Keys Remain Active After Deletion**: Google faced scrutiny over an IAM infrastructure flaw where API keys remained cached and functional after administrative deletion. This allows leaked keys to continue accessing cloud resources. Organizations are urged to audit log activity for deleted credentials. [More info](https://www.darkreading.com/identity-access-management-security/google-api-keys-active-after-deletion)

- **Google Accidentally Exposes Unfixed Chromium Flaw**: Google leaked technical data on its public tracker regarding an unpatched "zombie" JavaScript execution bug in Chromium. The flaw allows malicious code to persist running in the background after browser closure, posing botnet and proxy risks. [More info](https://www.bleepingcomputer.com/news/security/google-accidentally-exposed-details-of-unfixed-chromium-flaw/)

- **Highly Critical Drupal Architecture Patch**: The Drupal Security Team rushed out a patch for core architecture flaws affecting Drupal 10 and 11 (plus emergency EOL fixes). The vulnerability allows unauthenticated site compromise, making it a major target for automated exploitation. [More info](https://www.securityweek.com/drupal-patches-highly-critical-vulnerability-exposing-websites-to-hacking/)

## 🎯 Adversaries

- **Operation Saffron Dismantles "First VPN"**: International police forces across Europe, France, and the Netherlands seized 33 servers and arrested an administrator in Ukraine to shut down First VPN. The "no-logs" service actively catered to ransomware syndicates for data theft and C2 masking. [More info (HelpNetSecurity)](https://www.helpnetsecurity.com/2026/05/21/operation-saffron-first-vpn-takedown/) | [More info (BleepingComputer)](https://www.bleepingcomputer.com/news/security/police-seize-first-vpn-service-used-in-ransomware-data-theft-attacks/)

- **Nx Console and TanStack NPM Supply Chain Attacks**: Attackers poisoned the TanStack ecosystem and a VS Code extension via compromised credentials and "Pwn-Request" CI/CD pipeline bugs. The campaigns dropped a malicious payload called "Mini Shai-Hulud" to steal OIDC tokens and cloud secrets from runner memory, hitting GitHub and Grafana environments. [More info (HelpNetSecurity)](https://www.helpnetsecurity.com/2026/05/21/github-grafana-breach-root-cause-nx-console/) | [More info (BleepingComputer)](https://www.bleepingcomputer.com/news/security/github-links-repo-breach-to-tanstack-npm-supply-chain-attack/)

- **"Showboat" Linux Malware Targeting Middle East**: A new campaign leverages platform-agnostic malware to hit telecom and government groups in the Middle East. Showboat maintains remote access via encrypted C2 channels, utilizing localized lures for credential harvesting. [More info](https://thehackernews.com/2026/05/showboat-linux-malware-hits-middle-east.html)

- **Cross-Platform Chinese Espionage Hits Telcos**: A Chinese state-sponsored threat group is deploying a modular, cross-platform malware suite targeting both Windows and Linux systems inside global telecommunications networks to conduct long-term traffic sniffing and data interception. [More info](https://www.bleepingcomputer.com/news/security/chinese-hackers-target-telcos-with-new-linux-windows-malware/)

- **KimWolf Botnet Master Arrested**: An alleged botmaster known as "Dort" has been charged following a joint US-Canadian operation. Dort operated the infrastructure behind the KimWolf botnet, which targeted financial entities via large-scale phishing and credential theft. [More info](https://krebsonsecurity.com/2026/05/alleged-kimwolf-botmaster-dort-arrested-charged-in-u-s-and-canada/)

## 📈 Trends

- **Anatomy of Crypto Drainers**: Threat researchers published a deep dive on modern Web3 wallet drainers exploiting "approval phishing." The scripts bypass MFA and abuse functions like `SetApprovalForAll` on obfuscated JavaScript to drain digital assets silently. [More info](https://www.bleepingcomputer.com/news/security/inside-a-crypto-drainer-how-to-spot-it-before-it-empties-your-wallet/)

- **Android WAP Billing Fraud on the Rise**: New Android campaigns distribute trojanized third-party apps designed to manipulate web subscription forms and intercept OTP validation codes, covertly signing up victims to expensive premium services. [More info](https://hackread.com/android-malware-subscribe-services-without-consent/)

- **Supply Chain Security Reaches Crisis Proportions**: A security analysis highlights that enterprises are overwhelmed by thousands of software dependencies, creating widespread visibility blind spots and leaving downstream architecture open to cascading failures. [More info](https://www.securityweek.com/supply-chain-security-crisis-too-many-vulnerabilities-too-little-visibility/)

## 💥 Breaches & Leaks

- **MySpace93 Plaintext Passwords Indexed**: Over 46,000 plaintext passwords from a 2021 breach of retro social platform MySpace93 were recently indexed and added to Have I Been Pwned. The lack of cryptographic hashing exposes affected users to immediate credential stuffing risks. [More info](https://www.theregister.com/security/2026/05/21/46k-plaintext-passwords-pwned-in-myspace93-breach/5244024)

---

[⬅ Back to Archive](https://pranakn.github.io)
