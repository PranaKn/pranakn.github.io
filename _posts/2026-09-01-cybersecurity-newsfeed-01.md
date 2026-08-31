---
title: "Cybersecurity Newsfeed - 01/09/26"
date: 2026-08-31 09:00:00 -0300
categories: [News]
permalink: /posts/news-01-09-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-09-01.png
  alt: Cybersecurity Newsfeed - 01/09/26
---

# Cybersecurity Newsfeed

## 📅 01/09/26

## 🛡️ Vulnerabilities

- **PaperCut NG/MF Vulnerabilities Added to CISA KEV**: CISA added two critical PaperCut NG/MF flaws (CVE-2026-81578 and CVE-2026-82078) to its Known Exploited Vulnerabilities Catalog following active exploitation. Chained together, unauthenticated attackers can bypass authentication, modify system configurations, and execute arbitrary Java bytecode. [More info](https://www.cisa.gov/news-events/alerts/2026/08/31/cisa-adds-two-known-exploited-vulnerabilities-catalog)

- **Unauthenticated Zero-Day Exploitation in PaperCut NG/MF**: Threat actors are actively exploiting two zero-day vulnerabilities in PaperCut application servers to deploy SimpleHelp and AnyDesk remote access tools. The post-exploitation chain includes privilege enumeration, Active Directory discovery, and payload delivery. Emergency patches have been issued. [More info](https://www.helpnetsecurity.com/2026/08/31/papercut-attack-remote-access-tools/)

- **Nightmare Eclipse Releases HardBreacher Kaspersky Exploit**: A zero-day privilege escalation exploit named HardBreacher was publicly released, targeting Kaspersky Endpoint Security. The exploit tampers with the application's user interface process to mismanage file access permissions. Kaspersky has released automatic updates to mitigate the flaw. [More info](https://www.securityweek.com/nightmare-eclipse-drops-hardbreacher-kaspersky-product-exploit/)

- **Critical GiveWP WordPress Plugin RCE (CVE-2026-82222)**: A CVSS 10.0 vulnerability in the GiveWP plugin allows unauthenticated OS command execution via unsafe handling of serialized PHP objects in donation forms. The flaw triggers a gadget chain in TCPDF to execute system commands. GiveWP released version 4.16.7.2 to address the issue. [More info](https://securityaffairs.com/198156/security/critical-givewp-flaw-lets-attackers-run-commands-on-wordpress-servers.html)

## 🎯 Adversaries

- **Fire Ant Targets Cisco Routers and Infrastructure**: The Chinese cyberespionage group Fire Ant (UNC3886) has shifted tactics to target Cisco IOS XR routers, TACACS servers, and Linux hosts using GRE tunnels and system service implants. They also deployed a systemd backdoor named BridgeAgent disguised as a Zabbix monitoring agent. [More info](https://www.bleepingcomputer.com/news/security/chinese-fire-ant-hackers-turn-cisco-routers-into-spying-platforms/)

- **Silver Fox Group Delivers ValleyRAT via QN Wallpaper**: Kaspersky identified a campaign by the Silver Fox cybercrime group using modified QN Wallpaper installers to execute DLL sideloading via a malicious `libcef.dll`. The infection disables Microsoft Defender, elevates privileges, and deploys the ValleyRAT backdoor. [More info](https://securityaffairs.com/198191/security/valleyrat-when-legitimate-software-becomes-a-malware-delivery-tool.html)

- **North Korean Job Fraud Expands Beyond IT**: North Korean threat actors, including PurpleDelta, are expanding employment fraud operations into sales, marketing, and healthcare. The actors use stolen identities, deepfakes, and hardware KVM switches (such as PiKVM) to pass hiring processes and funnel revenue back to state-sanctioned entities. [More info](https://thehackernews.com/2026/08/north-korean-job-fraud-expands-beyond.html)

- **Aurora Ransomware Operators Leverage Cursor AI**: Aurora ransomware actors are abusing the AI coding assistant Cursor to plan and execute post-exploitation activities, including Active Directory Certificate Services attacks and NTLM relay attempts. They also utilize an AI-generated toolkit called Gryxa to steal credentials and disable defenses. [More info](https://thehackernews.com/2026/08/aurora-ransomware-operators-use-cursor.html)

## 📈 Trends

- **TerminalFix ClickFix Campaign Deploys Reverse Tunnels**: Microsoft warned of a multi-stage campaign using fake Cloudflare CAPTCHAs to trick users into running PowerShell commands in Windows Terminal. The attack uses steganography in PNG files and installs a custom Python reverse-tunnel module with SOCKS5 proxy capabilities for internal AD pivoting. [More info](https://www.bleepingcomputer.com/news/security/microsoft-warns-of-terminalfix-attacks-deploying-reverse-tunnels/)

- **OpenAI Warns of Autonomous AI-Driven Cyberattacks**: OpenAI published an open letter warning that autonomous AI cyberattacks will become widespread within months. Evaluating multi-agent networks revealed risks to critical infrastructure, prompting calls for defense-in-depth frameworks, identity monitoring, and passkey adoption. [More info](https://www.zdnet.com/article/openai-warns-malicious-agents-coming-recommended-action/)

- **Manic Android Trojan Exfiltrates Data Offline**: Kaspersky discovered Manic, an Android banking Trojan that abuses Accessibility services for keylogging and intercepting 2FA codes. When offline, the malware uses Bluetooth and Wi-Fi to chain harvested credentials across nearby infected devices until one gains internet connectivity to reach C2 servers. [More info](https://www.kaspersky.com/blog/manic-android-trojan/56323/)

- **Best Practices for Secure On-Premises File Server Management**: Despite widespread cloud adoption, organizations rely on local file servers for cost and data sovereignty reasons. Security recommendations focus on the Principle of Least Privilege, avoiding direct user permissions, and enforcing the AGDLP model with nested Active Directory groups. [More info](https://www.bleepingcomputer.com/news/security/file-servers-are-here-to-stay-heres-how-to-manage-them-securely/)

- **Anthropic Releases Compliance API for Claude Code**: Anthropic introduced Compliance API endpoints for Claude Code to give enterprise security teams visibility into local session transcripts, tool usage, and bash execution context. This helps monitor developer endpoints and enforce governance over agent actions. [More info](https://thehackernews.com/2026/08/securing-claude-code-new-compliance-api.html)

## 💥 Breaches & Leaks

- **McKesson Confirms Cyber Incident Following ShinyHunters Claims**: Healthcare provider McKesson disclosed unauthorized access affecting its Oncology, Multispecialty, and Medical-Surgical units. Threat group ShinyHunters claimed responsibility, alleging the exfiltration of hundreds of millions of PII and PHI records. Forensic investigations remain ongoing. [More info](https://www.malwarebytes.com/blog/news/2026/08/mckesson-confirms-cyber-incident-after-shinyhunters-claims-patient-data-theft)

- **Berlin Confirms Data Theft in Rhysida Ransomware Attack**: Municipal authorities in Berlin confirmed data exfiltration after the Rhysida ransomware gang claimed to have stolen 5.79 terabytes of data (1.44 million files). Exfiltrated content includes administrative files, password vaults, and critical infrastructure security assessments. [More info](https://www.bleepingcomputer.com/news/security/berlin-confirms-data-theft-after-rhysida-ransomware-attack-claims/)

## 📚 Others

- **Widespread Microsoft 365 and Exchange Online Outage**: Incident MO1465074 caused authentication failures, mail flow disruptions, and access delays across Exchange Online, Teams, OneDrive, and Defender XDR. Microsoft traced the root cause to internal configuration flaws within core authentication protocols. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-exchange-online-outage-causes-email-failures-auth-issues/)

- **OpenAI Confirms Service Outage Affecting ChatGPT Work and Plus**: Operational latency and elevated error rates temporarily impacted ChatGPT Work and Plus subscription tiers. Technical teams resolved backend infrastructure bottlenecks supporting task execution routines to restore service. [More info](https://www.bleepingcomputer.com/news/artificial-intelligence/openai-confirms-chatgpt-outage-as-users-report-errors/)

- **Nigerian Nationals Extradited Over Sextortion Operations**: Two Nigerian citizens were extradited to the U.S. to face federal charges related to international sextortion schemes targeting minors, which resulted in the deaths of two American teenagers. [More info](https://www.bleepingcomputer.com/news/security/nigerians-charged-US-over-sextortion-deaths-of-us-teens/)

- **Microsoft False Positive Warning for Defender Antivirus**: Recent Defender security intelligence updates triggered false notifications stating Microsoft Defender Antivirus was turned off across Windows 11 and Windows Server 2025. Microsoft confirmed Defender remains operational and advised users to disregard the alerts while a fix is issued. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-asks-users-to-ignore-antivirus-is-turned-off-errors/)

---

[⬅ Back to Archive](https://pranakn.github.io)
