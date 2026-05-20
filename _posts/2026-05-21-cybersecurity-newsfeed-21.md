---
title: "Cybersecurity Newsfeed - 21/05/26"
date: 2026-05-21 18:00:00 -0300
categories: [News]
permalink: /posts/news-21-05-2026/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware, ai-security]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-05-21.png
  alt: Cybersecurity Newsfeed - 21/05/26
---

# Cybersecurity Newsfeed

## 📅 21/05/26

## 🛡️ Vulnerabilities

- **SonicWall MFA Bypass via Incomplete Patching**: SonicWall has cautioned customers that threat actors are bypassing multi-factor authentication (MFA) on its SSL VPN appliances. The issue stems from incomplete patching of a previously disclosed vulnerability, allowing attackers to exploit lingering weaknesses in the authentication logic to gain persistent corporate network access. [More info](https://www.bleepingcomputer.com/news/security/hackers-bypass-sonicwall-vpn-mfa-due-to-incomplete-patching/)

- **PinTheft Local Privilege Escalation in Arch Linux**: A newly discovered local privilege escalation vulnerability, dubbed PinTheft, has been identified in Arch Linux. This flaw allows a standard user to gain root privileges by exploiting a race condition within specific system utilities. A functional exploit has been released. [More info](https://securityaffairs.com/192456/security/pintheft-another-linux-privilege-escalation-another-working-exploit-this-time-targeting-arch.html)

- **CISA Adds Seven Flaws to KEV Catalog**: CISA has added seven vulnerabilities to its Known Exploited Vulnerabilities (KEV) catalog, based on evidence of active exploitation in the wild. These flaws span various software and hardware products, and the agency mandates that organizations prioritize patching them immediately. [More info](https://www.cisa.gov/news-events/alerts/2026/05/20/cisa-adds-seven-known-exploited-vulnerabilities-catalog)

- **Critical Drupal Update Fixes High-Exploitation Risk Bug**: Drupal has released a critical security update to address a high-risk vulnerability that could lead to full site compromise. The flaw involves an exploitation risk where attackers could execute arbitrary code under certain configurations. [More info](https://www.bleepingcomputer.com/news/security/drupal-critical-update-to-fix-bug-with-high-exploitation-risk/)

- **DirtyDecrypt PoC Released for Linux Kernel Flaw**: A proof-of-concept (PoC) exploit, named DirtyDecrypt, has been released for a significant Linux kernel vulnerability. This flaw allows local users to bypass memory protections and achieve unauthorized data decryption or privilege escalation. [More info](https://securityaffairs.com/192436/uncategorized/dirtydecrypt-poc-released-for-yet-another-linux-flaw.html)

- **Microsoft Shares Mitigations for YellowKey Zero-Day**: Microsoft has issued mitigation guidance for "YellowKey," a critical Windows zero-day vulnerability currently being exploited in the wild. The flaw resides in the Windows kernel and can be leveraged by attackers to bypass security features and gain elevated system privileges. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-shares-mitigation-for-yellowkey-windows-zero-day/)

- **Huawei Zero-Day Linked to 2025 Luxembourg Telecom Crash**: An alleged Huawei zero-day vulnerability has been linked to a major telecommunications crash in Luxembourg in 2025. Investigations suggest that threat actors exploited an unpatched flaw in Huawei networking gear to disrupt core services. [More info](https://securityaffairs.com/192431/hacking/alleged-huawei-zero-day-blamed-for-the-2025-luxembourg-telecom-crash.html)

- **Windows Zero-Day Barrage Escalates After Patch Tuesday**: Following Patch Tuesday, a barrage of new Windows zero-day vulnerabilities has been reported, keeping security teams on high alert. These flaws include remote code execution and privilege escalation bugs across multiple components and are being targeted by APT groups. [More info](https://www.darkreading.com/cyberattacks-data-breaches/windows-zero-day-barrage-continues-after-patch-tuesday)

## 🎯 Adversaries

- **Webworm APT Launches New European Campaign**: The Webworm APT group has launched a new campaign targeting European government and industrial sectors. Using updated malware variants, the group employs sophisticated obfuscation techniques to evade traditional detection mechanisms and conduct cyber espionage. [More info](https://www.helpnetsecurity.com/2026/05/20/webworm-apt-campaign-targets-europe/) | [More info](https://www.infosecurity-magazine.com/news/webworm-apt-evolves-tactics/)

- **Banana RAT Targets 16 Brazilian Banks via Fake Invoices**: The Banana RAT malware is currently targeting sixteen major Brazilian banks through a campaign involving fraudulent invoices. Distributed via email, this Remote Access Trojan allows hackers to monitor user activity, capture keystrokes, and intercept credentials. [More info](https://hackread.com/banana-rat-malware-fake-invoices-16-brazilian-banks/)

- **Unit 42 Tracks Maliciously Tampered Chef Clusters**: Unit 42 researchers are tracking a campaign involving tampered Chef clusters where attackers gain access to management consoles to inject malicious recipes and cookbooks into the infrastructure-as-code pipeline, deploying backdoors and cryptominers. [More info](https://origin-unit42.paloaltonetworks.com/tracking-tampered-chef-clusters/)

- **Fake Word Documents Deploy RATs in Enterprise Phishing**: A sophisticated phishing campaign is utilizing fake Microsoft Word documents containing malicious macros or exploits to deploy remote access tools (RATs). By leveraging trusted tools, the campaign often bypasses traditional antivirus signatures. [More info](https://hackread.com/fake-word-phishing-enterprise-blind-spot-trusted-remote-access-tools/)

## 🤖 AI Security

- **Claude AI Sandbox Escape Defeated**: Security researchers have identified a dangerous sandbox escape vulnerability in Anthropic’s Claude AI model. The flaw allowed the AI to execute unauthorized code outside its restricted environment. Anthropic acknowledged the risk and deployed a fix to reinforce the boundary. [More info](https://www.theregister.com/security/2026/05/20/even-claude-agrees-hole-in-its-sandbox-was-real-and-dangerous/)

- **Microsoft Releases Open-Source AI Safety Tools (Rampart & Clarity)**: Microsoft has introduced two new open-source tools designed to enhance AI agent security. Rampart focuses on providing a secure execution boundary for agents, while Clarity offers observability into agent decision-making processes. [More info](https://www.microsoft.com/en-us/security/blog/2026/05/20/introducing-rampart-and-clarity-open-source-tools-to-bring-safety-into-agent-development-workflow/)

- **Max-Severity Flaw in ChromaDB Vector Database**: A maximum-severity vulnerability has been discovered in ChromaDB, a popular vector database used in AI applications. The flaw enables remote code execution (RCE) by exploiting improper input validation during data ingestion, allowing for complete server hijacking. [More info](https://www.bleepingcomputer.com/news/security/max-severity-flaw-in-chromadb-for-ai-apps-allows-server-hijacking/)

## 📈 Trends & Supply Chain

- **Mini-Shai-Hulud Campaign Targets CI/CD Pipelines via npm**: Microsoft researchers have uncovered a malicious campaign involving compromised npm packages designed to facilitate CI/CD credential theft. The attack targets developers by injecting malicious scripts into legitimate package dependencies to exfiltrate API keys and cloud tokens. [More info](https://www.microsoft.com/en-us/security/blog/2026/05/20/mini-shai-hulud-compromised-antv-npm-packages-enable-ci-cd-credential-theft/)

- **Token Pilfering Surges to Bypass Multi-Factor Authentication**: A recent report highlights the surging threat of token theft as a primary method for bypassing MFA. Attackers are increasingly using adversary-in-the-middle (AiTM) techniques to steal session tokens directly from browsers and hijack active cloud sessions. [More info](https://www.cysecurity.news/2026/05/token-pilfering-how-token-theft-is.html)

- **PCPJack Worm Steals Cloud Service Provider Credentials**: A new wormable malware named PCPJack has been identified targeting cloud environments. The worm spreads by exploiting misconfigured Port Control Protocol (PCP) services, moving laterally across networks to exfiltrate cloud infrastructure management secrets. [More info](https://www.cysecurity.news/2026/05/pcpjack-worm-steals-cloud-credentials.html)

## 💥 Breaches & Leaks

- **GitHub Confirms Breach as 4,000 Internal Repos Stolen**: GitHub has confirmed a security breach resulting in the theft of approximately 4,000 internal repositories. The incident occurred after an attacker gained unauthorized access via a compromised employee credential. Customer data and core services were not impacted. [More info](https://www.darkreading.com/application-security/github-confirms-breach-4k-internal-repos-stolen)

## 🏛️ Takedowns & Disruptions

- **Microsoft Dismantles 'Fox Tempest' Malware-Signing Operation**: Microsoft has successfully dismantled "Fox Tempest," a cybercrime operation that provided fake malware-signing services to threat actors by abusing Microsoft's platform to obtain legitimate digital certificates and evade security filters. [More info](https://www.malwarebytes.com/blog/news/2026/05/fake-malware-signing-service-fox-tempest-dismantled-by-microsoft) | [More info](https://www.bleepingcomputer.com/news/security/cybercrime-service-disrupted-for-abusing-microsoft-platform-to-sign-malware/)

---

[⬅ Back to Archive](https://pranakn.github.io)
