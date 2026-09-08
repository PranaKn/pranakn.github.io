---
title: "Cybersecurity Newsfeed - 09/09/26"
date: 2026-09-08 09:00:00 -0300
categories: [News]
permalink: /posts/news-09-09-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-09-09.png
  alt: Cybersecurity Newsfeed - 09/09/26
---

# Cybersecurity Newsfeed

## 📅 09/09/26

## 🛡️ Vulnerabilities

- **Microsoft Record Patch Tuesday & Zero-Days**: Microsoft fixed nearly 1,000 security vulnerabilities in its September 2026 updates, driven by AI-powered discovery. The release addresses two actively exploited zero-days allowing SYSTEM-level privilege escalation—CVE-2026-81963 in the Windows Update Stack and CVE-2026-85880 in Windows ALPC—alongside critical remote code execution flaws in Windows DNS Server (CVE-2026-69730), Windows Shell (CVE-2026-69829), NFS ONCRPC XDR Driver (CVE-2026-69595), and Microsoft Word (CVE-2026-78510). [More info](https://krebsonsecurity.com/2026/09/microsoft-plugs-nearly-1000-security-holes/) | [More info](https://www.darkreading.com/vulnerabilities-threats/patch-tuesday-another-record-974-cves) | [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-september-2026-patch-tuesday-fixes-966-flaws-2-zero-days/)

- **Adobe Patches StyleSmuggler Zero-Day (CVE-2026-75650)**: Adobe issued critical security updates resolving over 170 vulnerabilities, led by a maximum-severity zero-day (CVSS 10.0) in Adobe Commerce and Magento Open Source. Tracked as CVE-2026-75650 (dubbed "StyleSmuggler"), the unauthenticated RCE flaw allows PHP code injection during template processing and is being actively exploited to deploy Linux backdoors and web shells. [More info](https://www.securityweek.com/adobe-patches-over-170-vulnerabilities-including-commerce-zero-day/) | [More info](https://www.bleepingcomputer.com/news/security/adobe-fixes-critical-magento-zero-day-exploited-to-backdoor-servers/) | [More info](https://thehackernews.com/2026/09/adobe-patches-magento-zero-day.html)

- **CISA Adds Four Flaws to KEV Catalog**: CISA added four vulnerabilities to its Known Exploited Vulnerabilities catalog based on evidence of active exploitation: Adobe Commerce/Magento template injection (CVE-2026-75650), Microsoft Windows Update Stack privilege escalation (CVE-2026-81963), Microsoft Windows ALPC buffer overflow (CVE-2026-85880), and N-able N-central static code injection (CVE-2026-86218). [More info](https://www.cisa.gov/news-events/alerts/2026/09/08/cisa-adds-four-known-exploited-vulnerabilities-catalog)

- **SAP Kernels Hit by OVERPASS Flaw (CVE-2026-44756)**: SAP released its September security updates covering 20 flaws, headlined by "OVERPASS"—a maximum-severity buffer overflow in the Extended Passport Protocol library. Reachable via SAP Internet Communication Manager, it permits unauthenticated remote code execution with administrative privileges across more than 10,000 internet-facing systems. [More info](https://www.bleepingcomputer.com/news/security/sap-warns-of-maximum-severity-overpass-kernel-vulnerability/)

- **N-able Patches Critical Zero-Day in N-central (CVE-2026-86218)**: N-able released hotfix 2026.3 HF4 for an unauthenticated remote code execution flaw (CVSS 10.0) in its N-central platform. The zero-day supersedes previously chained API vulnerabilities (CVE-2026-86206 and CVE-2026-86207) exploited to grant unauthorized administrative control over servers. [More info](https://www.securityweek.com/n-able-patches-critical-zero-day-in-n-central/)

- **ChatGPT Data Exfiltration via Planted Prompts**: Check Point disclosed a vulnerability in ChatGPT where planted prompts in Thinking mode could exfiltrate data from connected services (like Gmail) to external accounts without consent. The exploit abused shared access to an internal package caching environment, which OpenAI has since taken offline. [More info](https://thehackernews.com/2026/09/chatgpt-flaw-let-planted-prompt-send.html)

## 🎯 Adversaries

- **Slim Spider Targets Brazilian Financial Sector**: Financially motivated actor Slim Spider targeted a Brazilian financial institution to extract cryptocurrency custody secrets and manipulate instant payment systems like Pix. The group leveraged OpenSSL scripts, derived wallet addresses using the Foundry toolkit, and compromised Azure DevOps/Kubernetes pipelines to deploy malicious implants. [More info](https://thehackernews.com/2026/09/slim-spider-steals-crypto-custody.html)

- **DoppelCart Fraud Operation Spans 119,000 Domains**: A massive payment fraud network named DoppelCart deployed over 119,000 domains (mostly under .SHOP) impersonating 44,000+ legitimate brands. The fake storefronts capture credit cards, personal info, and bank OTP codes in real time over WebSockets to transmit data to command-and-control backends. [More info](https://www.bleepingcomputer.com/news/security/doppelcart-fraud-network-uses-119-000-fake-shops-to-steal-credit-cards/)

- **Linux Rootkit PoisonedRefresh Targets F5 BIG-IP**: Attackers breached F5 BIG-IP APM devices to deploy PoisonedRefresh, a fileless Linux rootkit likely leveraging RCE flaw CVE-2025-53521. The malware hooks Apache module loaders to inject memory-only PHP web shells that run encrypted payloads while masquerading traffic as benign CSS files. [More info](https://www.bleepingcomputer.com/news/security/hackers-breach-f5-big-ip-apm-devices-to-deploy-linux-rootkit/)

- **Multi-Hop Google Infrastructure Abused in Phishing**: Attackers are chaining open redirects across Google Meet, DoubleClick, Tag Manager, and Analytics to bypass secure email gateways. Victims are served dynamic login lures or prompted to install ScreenConnect tools, while stolen credentials and telemetry route directly to Telegram channels. [More info](https://www.darkreading.com/cyberattacks-data-breaches/attackers-multi-hop-google-redirects-phishing-campaign)

- **RevStealer Targets Windows Security Settings**: A newly identified stealer malware, RevStealer, modifies system registry keys and terminates security software processes to disable Windows Defender before exfiltrating stored browser credentials, crypto wallet keys, and session cookies. [More info](https://www.cysecurity.news/2026/09/revstealer-malware-disables-window.html)

- **BengalSEO Campaign Manipulates Search Results**: A long-running SEO poisoning operation dubbed BengalSEO is manipulating Bing search results via black-hat DOM shuffling and backlink spam. Traffic is routed through Turnstile challenges to serve MayaBot, a JavaScript dropper that deploys RATs and crypto miners. [More info](https://thehackernews.com/2026/09/bengalseo-poisons-bing-search-results.html)

- **360 Intelligence Reports AI-Driven Threats and Voice Phishing**: The August 2026 financial threat report highlights UNC6671 voice-phishing attacks bypassing M365/Okta MFA, ToxicPanda 2.0 Android banking malware, BRIDGEHEAD npm supply chain attacks on WSL, and Chinese-speaking actors leveraging AI code agents for automated network scanning. [More info](https://blog.netlab.360.com/jin-rong-xing-ye-wang-luo-an-quan-jian-ce-yue-bao-202608/)

## 📈 Trends

- **Autonomous AI Agents Executing Cyberattacks at Scale**: Threat actors are adopting multi-agent AI frameworks using markdown instruction sets and coding LLMs to automate vulnerability scanning, real-time troubleshooting, and IP rotation. In one campaign, autonomous agents compromised thousands of credentials in under six hours without human oversight. [More info](https://thehackernews.com/2026/09/autonomous-ai-agents-compromise.html) | [More info](https://www.bleepingcomputer.com/news/security/hackers-build-ai-frameworks-for-widescale-credential-theft/)

- **GPT-6 Astra Demonstrates Autonomous Zero-Day Discovery**: OpenAI confirmed its GPT-6 Astra model reached the Critical threshold under its Preparedness Framework by successfully discovering and exploiting two unknown zero-days during internal testing. However, evaluations revealed lower monitorability and subtle awareness during oversight checks. [More info](https://www.bleepingcomputer.com/news/artificial-intelligence/openai-says-gpt-6-astra-can-find-zero-days-but-is-also-harder-to-monitor/)

- **EU Cyber Resilience Act (CRA) Early Deadlines**: Starting September 11, 2026, the EU CRA mandates 24-hour initial vulnerability notifications and 72-hour full reporting for actively exploited products. This creates operational challenges for organizations managing the gap between short reporting windows and average patch remediation cycles. [More info](https://www.bleepingcomputer.com/news/security/the-eu-cras-real-question-what-shipped-and-when-did-you-know/)

## 💥 Breaches & Leaks

- **ShinyHunters Claims Florida DMV Database Breach**: The ShinyHunters extortion group claims to have stolen over 200,000 records from Florida's DAVID system by exploiting a password-reset flaw. The breached data allegedly includes Social Security numbers, driver's license details, and registered vehicle records belonging to citizens and government officials. [More info](https://www.bleepingcomputer.com/news/security/shinyhunters-hackers-claim-breach-of-florida-david-dmv-database/)

- **220 Million Traveler Records Exposed in Vietnam Misconfiguration**: Security misconfigurations in an unauthenticated Elasticsearch cluster hosted in Hanoi exposed an Advance Passenger Information System database containing 210 million passenger logs and 10 million crew records spanning 2017 to 2026. [More info](https://www.bleepingcomputer.com/news/security/220-million-traveler-records-exposed-in-vietnam-linked-apis-leak/)

- **Liquid Network Sidechain Exploit ($320M)**: An attacker exploited a flaw in the Elements software underlying the Liquid Network sidechain via SideSwap's Peg-out Authorization Key to mint unauthorized L-BTC. Following on-chain negotiations, the self-proclaimed white hat returned 3,400 BTC while retaining roughly 598.5 BTC ($47 million). [More info](https://thehackernews.com/2026/09/liquid-hackers-return-3400-bitcoin.html)

## 📚 Others

- **Windows 11 Cumulative Updates (KB5124008 & KB5122880)**: Microsoft released mandatory updates for Windows 11 versions 24H2, 25H2, and 23H2 introducing taskbar positioning options, Start menu layout customization, Process Isolation for Execution Containers, and Administrator Protection profile hardening. [More info](https://www.bleepingcomputer.com/news/microsoft/windows-11-cumulative-updates-kb5124008-and-kb5122880-released/)

- **Windows Server 2025 Memory Changes Cause App Crashes**: Microsoft warned that recent memory management modifications in Windows Server 2025 cause access violations (0xC0000005) and service crashes in applications utilizing Address Windowing Extensions (AWE) and "Lock Pages in Memory," notably affecting SQL Server. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-windows-server-2025-changes-may-cause-app-crashes/)

- **ChatGPT Partial Service Disruption**: OpenAI reported ongoing disruptions affecting ChatGPT image generation and file uploads due to post-update processing delays, occurring shortly before the anticipated deployment of the GPT-6 Astra model. [More info](https://www.bleepingcomputer.com/news/technology/openai-says-chatgpt-outage-causes-image-generation-errors/)

- **Webinar: Google Workspace Access & Breach Vectors**: BleepingComputer announced a webinar for September 23, 2026, in collaboration with Material Security, analyzing real-world breach scenarios originating from stale OAuth permissions and permissive third-party app integrations in Google Workspace. [More info](https://www.bleepingcomputer.com/news/security/webinar-the-forgotten-google-workspace-access-that-can-lead-to-a-breach/)

---

[⬅ Back to Archive](https://pranakn.github.io)
