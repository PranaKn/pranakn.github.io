---
title: "Cybersecurity Newsfeed - 11/09/26"
date: 2026-09-10 09:00:00 -0300
categories: [News]
permalink: /posts/news-11-09-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-09-11.png
  alt: Cybersecurity Newsfeed - 11/09/26
---

# Cybersecurity Newsfeed

## 📅 11/09/26

## 🛡️ Vulnerabilities

- **Check Point VPN Critical RCE Flaws (CVE-2026-85102 & CVE-2026-85103)**: Check Point disclosed two critical 9.8 CVSS-rated vulnerabilities affecting Security Gateways and Security Management Servers. The flaws involve improper certificate trust validation during VPN negotiations and a heap-based buffer overflow during ASN.1 certificate decoding, allowing unauthenticated remote code execution. [More info](https://thehackernews.com/2026/09/check-point-discloses-two-98-rated-vpn.html)

- **CISA Adds MikroTik RouterOS Flaws to KEV**: CISA added two actively exploited MikroTik RouterOS vulnerabilities to its Known Exploited Vulnerabilities catalog. CVE-2026-67277 involves missing authentication for critical functions, while CVE-2026-86060 is caused by improper neutralization of command argument delimiters. Both pose significant risks of full system compromise. [More info](https://www.cisa.gov/news-events/alerts/2026/09/10/cisa-adds-two-known-exploited-vulnerabilities-catalog)

- **September 2026 Windows Server Updates Break Remote Desktop Services**: Microsoft's September 2026 cumulative updates (KB5122876, KB5122882, KB5122871) cause severe Remote Desktop Services (RDS) failures across Windows Server 2019, 2022, and 2025. System debugging points to a deadlock between the Remote Desktop service and Local Session Manager during logout procedures, forcing administrators to roll back updates to maintain server availability. [More info](https://www.bleepingcomputer.com/news/microsoft/september-windows-server-updates-break-remote-desktop-services/)

## 🎯 Adversaries

- **BlueMoon Exploit Kit Chains Chrome and Windows Zero-Days**: State-sponsored cyber-espionage groups, including Chinese-aligned actors JungleBamboo and UTA0560, are deploying a modular exploit kit named BlueMoon. The campaign chains two Chrome V8 engine flaws (CVE-2026-85046 and CVE-2026-87491) for sandbox escape with a Windows ALPC buffer overflow (CVE-2026-85880) for local privilege escalation. [More info](https://www.malwarebytes.com/blog/bugs/2026/09/bluemoon-exploit-kit-turns-chrome-and-windows-flaws-into-attacks) | [More info](https://www.bleepingcomputer.com/news/security/new-bluemoon-kit-exploited-windows-and-chrome-zero-day-flaws/)

- **Autonomous AI Agents Weaponize PaperCut Flaws Globally**: Threat actors deployed hundreds of autonomous AI agents utilizing OpenAI Codex and DeepSeek models to compromise at least 440 PaperCut instances across 395 organizations in 48 countries. Exploiting CVE-2026-81578 and CVE-2026-82078, the rapid operation escalated to domain administrator privileges in minutes using pass-the-hash attacks, noPac exploits, and DCSync credential harvesting. [More info](https://www.bleepingcomputer.com/news/security/ai-powered-attack-exploited-papercut-flaws-to-hack-395-organizations)

- **Voice Phishing Brokers Target Personal Devices to Hijack M365 Data**: Initial access brokers Storm-3032 and Storm-3121 are contacting employees on personal mobile phones while impersonating corporate IT helpdesks. By tricking users into adversary-in-the-middle or device code authentication flows, attackers register malicious MFA devices and leverage Microsoft's Graph API to silently map networks and exfiltrate enterprise data. [More info](https://www.darkreading.com/threat-intelligence/voice-callers-exploit-byod-microsoft-365-corporate-data)

- **Mantax Otax Android Ransomware-Spyware Hybrid Targets Indonesia**: Discovered by Zimperium, Mantax Otax (or MantaxOtax) spreads via malicious APKs outside Google Play. Upon abusing Accessibility services and fetching C2 domains from GitHub, it exfiltrates contacts, SMS, and messaging app chats. On Android 9 or older, it encrypts files with victim-specific AES keys, while using WebSockets, transparent screen overlays, and text-to-speech audio for intimidation. [More info](https://www.bleepingcomputer.com/news/security/new-android-malware-encrypts-files-steals-data-and-harasses-victims/) | [More info](https://www.infosecurity-magazine.com/news/mantaxotax-android-malware/)

- **Trezor Warns Users of Email Provider Phishing Campaign**: Cryptocurrency wallet maker Trezor issued an alert regarding spoofed emails targeting its users following a breach at its third-party email provider. Threat actors falsely claimed critical vulnerabilities in STM32 microcontrollers to trick victims into providing recovery seeds online. [More info](https://www.bleepingcomputer.com/news/security/trezor-warns-users-of-email-provider-breach-phishing-attacks/)

## 📈 Trends

- **Google Play Early Access Program Abused by Misleading Apps**: Bitdefender research highlights deceptive Android developers leveraging Google Play's Early Access feature to bypass public ratings and reviews. Promoted via TikTok and Facebook ads with AI deepfakes, these apps display endless advertisements, engage in trademark abuse, and deliver financial fraud trojans like Hagaseca and GoldFactory variants. [More info](https://thehackernews.com/2026/09/google-play-early-access-abused-to-push.html) | [More info](https://www.securityweek.com/deceptive-android-apps-exploit-google-play-early-access-to-evade-reviews/)

- **WordPress Implements Automated Plugin Security Reviews**: The Official WordPress.org Plugin Repository Team introduced an automated security review system enforcing a six-hour cooldown period for all plugin updates. Releasing code is automatically scanned by Jetpack Scan and AI models, blocking high-risk backdoors or security vulnerabilities prior to public distribution. [More info](https://www.helpnetsecurity.com/2026/09/10/wordpress-automated-plugin-security-review/)

- **Huntress Expands Managed Threat Hunting Services to Africa**: Managed detection and response (MDR) provider Huntress announced a strategic partnership with QBS Software Africa to deliver managed threat hunting and security services to small and medium-sized businesses across the African continent. [More info](https://www.itsecurityguru.org/2026/09/10/huntress-expands-into-africa-with-new-qbs-software-africa-partnership/)

## 💥 Breaches & Leaks

- **IDScan Breached Exposing 153 Million Driver's License Records**: Identity verification provider IDScan confirmed unauthorized cloud access following dark web listings advertising 153 million stolen driver's license scans, state IDs, and medical cards. Third-party specialists and the FBI are assisting with the investigation while affected users are offered credit monitoring services. [More info](https://www.bleepingcomputer.com/news/security/idscan-confirms-breach-tied-to-153-million-stolen-drivers-licenses/)

- **Surfshark Discloses Test Server Breach Exposing Internal Tokens**: VPN provider Surfshark reported a breach of an internal test environment caused by an internet-exposed configuration error. Attackers accessed build-related credentials, service configurations, and a content-accessibility proxy server. Core production infrastructure and customer identity data remained completely untouched. [More info](https://www.bleepingcomputer.com/news/security/surfshark-vpn-says-hackers-breached-internal-testing-proxy-servers/)

## 📚 Others

- **Kevin Mandia Appointed to Amazon Board of Directors**: Amazon officially appointed cybersecurity veteran and Mandiant founder Kevin Mandia to its board of directors, effective September 8, 2026. Mandia will help guide board-level strategy regarding threat intelligence, incident response, and cybersecurity challenges in the AI era. [More info](https://www.securityweek.com/mandiant-founder-kevin-mandia-joins-amazon-board/)

---

[⬅ Back to Archive](https://pranakn.github.io)
