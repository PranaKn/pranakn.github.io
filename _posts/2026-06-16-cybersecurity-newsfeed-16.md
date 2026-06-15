---
title: "Cybersecurity Newsfeed - 16/06/26"
date: 2026-06-15 18:30:00 -0300
categories: [News]
permalink: /posts/news-16-06-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-06-16.png
  alt: Cybersecurity Newsfeed - 16/06/26
---

# Cybersecurity Newsfeed

## 📅 16/06/26

## 🛡️ Vulnerabilities

- **SimpleHelp Rogue Account Creation Flaw**: A critical vulnerability in the SimpleHelp remote support software allows unauthenticated attackers to create rogue remote support accounts. By exploiting this flaw, threat actors can bypass existing security controls to gain unauthorized access to managed systems with administrative privileges. Organizations utilizing SimpleHelp are advised to update their software immediately. [More info](https://www.bleepingcomputer.com/news/security/simplehelp-bug-lets-hackers-create-rogue-remote-support-accounts/)

- **CISA Adds Two Flaws to KEV Catalog (CVE-2026-20262 & CVE-2026-54420)**: CISA added two actively exploited vulnerabilities to its Known Exploited Vulnerabilities Catalog. CVE-2026-20262 is a directory traversal flaw in Cisco Catalyst SD-WAN Manager, and CVE-2026-54420 is a UNIX symbolic link following flaw in the LiteSpeed cPanel plugin. Federal agencies must prioritize patching these flaws per BOD 26-04. [More info](https://www.cisa.gov/news-events/alerts/2026/06/15/cisa-adds-two-known-exploited-vulnerabilities-catalog)

- **Cisco Patches Exploited SD-WAN vManage Zero-Day**: Cisco has addressed a critical path traversal vulnerability in its SD-WAN vManage software that has been actively exploited in the wild. The flaw allows unauthenticated remote attackers to gain unauthorized access to sensitive system information, posing a severe risk to SD-WAN management infrastructure. [More info](https://www.bleepingcomputer.com/news/security/cisco-fixes-sd-wan-vmanage-flaw-exploited-in-zero-day-attacks/)

## 🎯 Adversaries

- **China-Linked UNC6508 Targets Medical Research**: Google’s Threat Intelligence Group (GTIG) identified a Chinese threat actor compromising REDCap servers at North American medical research institutions. Using a custom modular malware suite named INFINITERED, the group trojanized system files, harvested credentials, and monitored emails undetected for over a year. [More info](https://www.helpnetsecurity.com/2026/06/15/chinese-hackers-redcap-medical-research-institutions-breach/)

- **North Korean Hackers Weaponize Developer Supply Chain**: North Korean threat actors are increasingly targeting finance, crypto, and tech sectors by embedding malware into developer workflows. Using fake recruitment or code reviews, they lure victims into cloning GitHub repositories containing cross-platform loaders or deploy malicious npm packages to steal SSH keys and crypto wallets. [More info](https://thehackernews.com/2026/06/north-korean-hackers-are-turning.html)

- **Velvet Ant Maintains Decade-Long Backdoor Persistence**: The China-linked threat group Velvet Ant maintained persistent network access for nearly ten years by backdooring the authentication stack on Linux systems. By modifying PAM and OpenSSH binaries, they bypassed authentication via hardcoded secrets and silently harvested credentials, evading standard signature detection. [More info](https://www.helpnetsecurity.com/2026/06/15/velvet-ant-backdoored-authentication-persistence/)

## 📈 Trends

- **EtherRAT Leverages Ethereum Blockchain for C2**: Malwarebytes exposed a malicious infrastructure distributing EtherRAT, a Node.js-based Remote Access Trojan. The malware dynamically resolves its Command and Control (C2) servers via the Ethereum blockchain, allowing full system control and making infrastructure takedowns significantly harder. [More info](https://www.malwarebytes.com/blog/threat-intel/2026/06/inside-a-malicious-infrastructure-delivering-etherrat-phishing-pages-and-malicious-software)

- **'WeedHack' Malware Infects Over 116,000 Systems**: Distributed primarily through malvertising and malicious software bundles, the automated WeedHack campaign has achieved global scale. The malware focuses on establishing host persistence, exfiltrating sensitive user credentials, and draining cryptocurrency wallets. [More info](https://www.cysecurity.news/2026/06/weedhack-malware-infects-over-116000.html)

## 📦 Supply Chain Attacks

- **Awesome Motive CDN Compromise Hits WordPress Plugins**: A major supply chain attack via the Awesome Motive CDN injected malicious JavaScript into popular WordPress plugins including OptinMonster, PushEngage, and TrustPulse. The tampered scripts create rogue administrator accounts and deploy persistent backdoors when an administrator accesses the dashboard. [More info (BleepingComputer)](https://www.bleepingcomputer.com/news/security/optinmonster-wordpress-plugin-hacked-in-cdn-supply-chain-attack/) | [More info (Security Affairs)](https://securityaffairs.com/193616/malware/supply-chain-attack-hits-popular-wordpress-plugins-through-awesome-motive-cdn.html)

## 💥 Breaches & Leaks

- **Handala Claims Breach of California Water Service**: The Iran-linked hacking group Handala claimed to have stolen 5GB of data from the California Water Service, including customer billing and GPS network files. While the group claimed disruptive capabilities, experts note the accessed systems do not control operational technology (OT) or water treatment infrastructure. [More info](https://hackread.com/handala-hacking-group-california-water-service-breach/)

---

[⬅ Back to Archive](https://pranakn.github.io)
