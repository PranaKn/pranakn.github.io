---
title: "Cybersecurity Newsfeed - 02/10/26"
date: 2026-10-01 09:00:00 -0300
categories: [News]
permalink: /posts/news-02-10-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-10-02.png
  alt: Cybersecurity Newsfeed - 02/10/26
---

# Cybersecurity Newsfeed

## 📅 02/10/26

## 🛡️ Vulnerabilities

- **Cisco Catalyst SD-WAN Manager Auth Bypass (CVE-2026-76504)**: CISA added this critical zero-day flaw to its Known Exploited Vulnerabilities catalog. Stemming from improper URI encoding handling in HTTP requests, unauthenticated remote attackers can bypass authentication rules and gain full administrative API access over affected management consoles. Organizations must patch immediately and restrict public API exposure. [More info](https://www.cisa.gov/news-events/alerts/2026/10/01/cisa-adds-one-known-exploited-vulnerability-catalog) | [More info](https://www.helpnetsecurity.com/2026/10/01/new-cisco-sd-wan-zero-day-exploited-in-the-wild-cve-2026-76504/)

- **Kiteworks Email Protection Gateway Code Injection (CVE-2026-54154)**: Kiteworks released security updates addressing 126 vulnerabilities, headlined by a maximum-severity flaw allowing unauthenticated remote code execution by chaining path traversal and input-handling defects. Patched in EPG version 9.4.1. [More info](https://www.bleepingcomputer.com/news/security/kiteworks-patches-max-severity-email-protection-gateway-code-injection-vulnerability/)

- **Apple CoreGraphics Out-of-Bounds Write (CVE-2026-86950)**: A proof-of-concept exploit was published for a zero-day integer truncation vulnerability in Apple's CoreGraphics during PDF font coordinate calculations. Apple has released updates across iOS and macOS to patch the heap memory safety issue. [More info](https://thehackernews.com/2026/10/apple-coregraphics-poc-emerges-as.html)

## 🎯 Adversaries

- **Self-Healing WordPress Backdoor**: Researchers uncovered a sophisticated WordPress backdoor functioning as a mesh across files, database entries, and System V shared memory. Using eight components, it continuously monitors and rebuilds deleted files from memory or database copies, utilizing Ethereum blockchain nodes for C2 communications. [More info](https://thehackernews.com/2026/10/wordpress-backdoor-rebuilds-itself.html)

- **Autonomous AI Agents Attack US and Canadian Government Web Platforms**: Security researchers observed autonomous AI systems conducting high-frequency vulnerability scanning and exploitation, navigating web forms and executing attack payloads without human intervention. [More info](https://www.bleepingcomputer.com/news/security/autonomous-ai-agents-tried-to-hack-us-canadian-government-websites/)

- **DIVD Suffers Breach via Agentic AI Exploitation**: The Dutch Institute for Vulnerability Disclosure (DIVD) suffered a security breach executed by autonomous AI agents chaining two zero-day vulnerabilities (CVE-2026-102489 and CVE-2026-102490) in the Zammad helpdesk framework to obtain root access. Network segmentation successfully limited the scope. [More info](https://www.helpnetsecurity.com/2026/10/01/divd-agentic-ai-attack-breach/)

- **Operation KillSwitch Dismantles KillSec Ransomware**: International law enforcement seized five C2 servers, took control of the group's leak site, and secured over 110 TB of exfiltrated data, resulting in three arrests across Europe and disrupting a syndicate responsible for compromising roughly 500 organizations globally. [More info](https://securityaffairs.com/200200/cyber-crime/operation-killswitch-police-dismantle-killsec-ransomware-group.html)

## 📈 Trends

- **Microsoft Warns Adversaries Hold Advantage in AI Race**: Microsoft released findings stating that threat actors currently hold an edge in leveraging generative AI for cyber operations, specifically accelerating vulnerability discovery, social engineering, and post-compromise automation. [More info](https://www.bleepingcomputer.com/news/security/microsoft-says-threat-actors-are-ahead-in-the-early-ai-race/)

- **Zero Trust "Day One" Architectural Exposure**: Enterprise Zero Trust frameworks face risk during initial user onboarding and credential enrollment before MFA or security keys are provisioned, requiring stricter initial identity proofing and biometric liveness checks. [More info](https://www.bleepingcomputer.com/news/security/the-day-one-hole-in-zero-trust-architecture/)

## 💥 Breaches & Leaks

- **Pentagon DMDC Data Breach Affects 3.05 Million**: Exploitation of a file-sharing vulnerability between October 2025 and July 2026 exposed Social Security numbers, dates of birth, names, and career records belonging to military personnel, civilian employees, and dependents. [More info](https://www.malwarebytes.com/blog/privacy/2026/10/pentagon-breach-exposes-social-security-numbers-and-military-records-of-millions) | [More info](https://www.bleepingcomputer.com/news/security/hackers-breach-pentagon-human-resources-management-system-steal-data-of-nearly-3-million-people/)

- **Bitget Exchange Discloses $387.5 Million Breach**: Bitget confirmed a major breach resulting from a third-party software zero-day vulnerability. North Korean threat actors compromised service nodes, deployed web shells, and issued unauthorized withdrawals. [More info](https://thehackernews.com/2026/10/bitget-confirms-third-party-zero-day.html)

- **MetaMask Infrastructure Incident**: MetaMask disclosed a security incident affecting non-custodial staking components, initiating validator node exits with Lido Finance to mitigate penalties. Seed phrases, private keys, and user funds remain fully uncompromised. [More info](https://www.bleepingcomputer.com/news/security/metamask-discloses-security-incident-affecting-its-infrastructure/)

---

[⬅ Back to Archive](https://pranakn.github.io)
