---
title: "Cybersecurity Newsfeed - 26/08/26"
date: 2026-08-25 09:00:00 -0300
categories: [News]
permalink: /posts/news-26-08-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-08-26.png
  alt: Cybersecurity Newsfeed - 26/08/26
---

# Cybersecurity Newsfeed

## 📅 26/08/26

## 🛡️ Vulnerabilities

- **Gitea Code Injection Flaw Added to CISA KEV (CVE-2026-60004)**: The Cybersecurity and Infrastructure Security Agency added CVE-2026-60004 to its Known Exploited Vulnerabilities Catalog following evidence of active exploitation. The code injection vulnerability affects Gitea, an open-source self-hosted Git service, allowing attackers to execute arbitrary code and gain control over exposed assets. Federal agencies are required to prioritize remediation under BOD 26-04. [More info](https://www.cisa.gov/news-events/alerts/2026/08/25/cisa-adds-one-known-exploited-vulnerability-catalog)

- **Zimbra SNMP Command Injection (CVE-2026-73570)**: Over 270 Zimbra Collaboration Suite servers have been compromised in ongoing attacks exploiting a high-severity command injection vulnerability in the SNMP monitoring component. The flaw allows unauthenticated remote attackers to execute arbitrary code on servers with SNMP notifications enabled. CERT Polska and CISA issued urgent remediation advisories. [More info](https://www.bleepingcomputer.com/news/security/hackers-breached-over-270-zimbra-servers-in-ongoing-attacks/)

- **Unpatched Calix GS7 Router UPnP Flaw (CVE-2026-75501)**: An unpatched missing authentication flaw affects Calix GS7 XGS (GS5239XG) residential routers running EXOS/6.6.47 firmware. The router exposes its UPnP WANIPConnection SOAP service on TCP port 5000, allowing unauthenticated attackers to create permanent port-forwarding rules and bypass NAT to expose internal devices directly to the public internet. [More info](https://www.bleepingcomputer.com/news/security/unpatched-calix-flaw-lets-hackers-bypass-nat-to-expose-internal-devices/)

## 🎯 Adversaries

- **AnonyMousKIT Uses AI Voice Agents to Bypass Activation Lock**: A phishing-as-a-service platform called AnonyMousKIT uses AI-powered voice agents and fake Apple support pages to bypass Activation Lock on stolen iPhones. Operatives contact victims to trick them into disclosing passcodes, Apple IDs, and 2FA codes using over 500 connected domains and automated call bots. [More info](https://www.bleepingcomputer.com/news/security/anonymouskit-phaas-uses-voice-ai-agents-to-phish-iphone-passcodes/)

- **Mirage2FA Campaign Hits Over 4,500 Domains**: The Mirage2FA phishing-as-a-service campaign has targeted over 4,500 organizational email domains in the U.S. and Europe. Utilizing adversary-in-the-middle (AiTM) techniques, the campaign steals passwords and session cookies to bypass two-factor authentication on Microsoft 365 logins. [More info](https://thehackernews.com/2026/08/mirage2fa-surge-hits-4500-us-and-eu.html)

- **E4del and PINHOLE RATs Weaponize FTP Server Banners**: Threat actors are deploying E4del and PINHOLE remote access trojans by utilizing FTP server banners as dead drop resolvers. Embedded command payloads in protocol response strings trigger execution via Windows Shortcut files, WebDAV, and Early Bird APC injection. [More info](https://thehackernews.com/2026/08/e4del-and-pinhole-rats-turn-ftp-banners.html)

- **Fake Minecraft WeedHack Malware Persists After C2 Takedown**: The WeedHack malware-as-a-service campaign continues targeting Minecraft players through SEO poisoning, AI-built landing pages, and lookalike websites despite primary C2 servers being offline. File-hosting platforms and EtherHiding smart contracts are used to distribute infostealers. [More info](https://www.infosecurity-magazine.com/news/fake-minecraft-weedhack-malware/) | [More info](https://securityaffairs.com/197784/malware/fake-minecraft-sites-are-still-spreading-weedhack-after-c2-takedown.html)

- **24 npm Packages Abuse UNPKG Mirrors for Phishing**: Security researchers uncovered 24 npm packages that abuse UNPKG mirrors to host fake Cloudflare CAPTCHA verification pages. The packages serve HTML files via UNPKG links to execute redirects to fake authentication portals or fetch encrypted URLs from public KV store APIs. [More info](https://www.bleepingcomputer.com/news/security/hackers-abuse-npm-mirrors-to-host-phishing-redirect-pages/) | [More info](https://thehackernews.com/2026/08/24-npm-packages-abuse-unpkg-mirrors-to.html)

## 📈 Trends

- **Identity Verification Checkpoints Become Primary Attack Surface**: Threat actors are shifting focus to identity verification checkpoints during employee onboarding and account recovery. Tactics include submitting fraudulent documentation via fake remote workers and using synthetic media or deepfake voice cloning to trick helpdesks into forcing password resets. [More info](https://www.bleepingcomputer.com/news/security/from-fake-workers-to-account-recovery-the-growing-identity-verification-risk/)

- **Cryptographic Context Injection Bypasses AI Safety Guardrails**: Researchers identified an attack method called Cryptographic Context Injection that bypasses safety guardrails in AI assistants such as Grok and Gemini. By hiding prompt injection instructions inside encrypted payloads, the AI decrypts and executes the hidden commands as trusted inputs. [More info](https://www.malwarebytes.com/blog/ai/2026/08/encrypted-instructions-can-fool-ai-assistants-like-grok-and-gemini)

- **Silent Patching Practices Blind Defenders**: Software vendors silently patching vulnerabilities without issuing CVEs or advisory documentation leave security administrators without necessary risk context. While silent fixes fail to stop skilled attackers from reverse-engineering binaries, they deprive defenders of details needed for detection signatures and patch prioritization. [More info](https://www.securityweek.com/silent-patches-dont-stop-attackers-they-blind-defenders/)

## 💥 Breaches & Leaks

- **LACMA Discloses Data Breach Exposing SSNs and Health Data**: The Los Angeles County Museum of Art disclosed a data breach following suspicious network activity detected in July 2025. Investigations finalized in February 2026 confirmed unauthorized access compromised full names, dates of birth, Social Security numbers, driver's licenses, and health insurance information. [More info](https://www.bleepingcomputer.com/news/security/lacma-data-breach-last-year-exposed-social-security-and-medical-data/)

- **Hospital Operator Nutex Health Reports Data Theft**: Healthcare provider Nutex Health disclosed a data breach in an SEC filing after detecting unauthorized data exfiltration from company servers across its 28 medical facilities in 12 states. Forensic teams are currently assessing the extent of compromised patient, employee, or financial data. [More info](https://www.bleepingcomputer.com/news/security/hospital-operator-nutex-health-says-data-stolen-in-cyberattack/)

## 📚 Others

- **Microsoft PowerToys Adds Window Hopper and Workspace Features**: Microsoft released Windows PowerToys version 0.101.2362.0, introducing a utility called Window Hopper that enables users to switch exclusively between open windows of the currently active application. The update also adds multi-monitor brightness synchronization and Command Palette enhancements. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-powertoys-adds-alt-plustab-style-switching-for-an-apps-windows/)

- **WhatsApp Enhances Two-Step Verification and Passkey Support**: WhatsApp updated its account security features by expanding passkey support across multiple Android and iOS devices on a single account. Two-step verification now supports long, complex alphanumeric passwords instead of standard six-digit PINs, alongside expanded caller context displays. [More info](https://www.bleepingcomputer.com/news/security/whatsapp-adds-stronger-two-step-verification-multiple-passkeys/)

---

[⬅ Back to Archive](https://pranakn.github.io)
