---
title: "Cybersecurity Newsfeed - 28/08/26"
date: 2026-08-27 09:00:00 -0300
categories: [News]
permalink: /posts/news-28-08-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-08-28.png
  alt: Cybersecurity Newsfeed - 28/08/26
---

# Cybersecurity Newsfeed

## 📅 28/08/26

## 🛡️ Vulnerabilities

- **PaperCut Zero-Day Exploitation (PaperCut NG & MF)**: Active zero-day exploitation is targeting the web interface of PaperCut NG and PaperCut MF Application Servers. Emergency patches have been issued, and administrators are advised to restrict public web access immediately. [More info](https://www.bleepingcomputer.com/news/security/papercut-warns-of-ng-mf-flaw-exploited-in-zero-day-attacks/) | [More info](https://www.helpnetsecurity.com/2026/08/27/papercut-ng-mf-vulnerability-attack/)

- **Critical Next.js RCE Flaws (CVE-2026-75604 & GHSA-2xp9-vwfh-vxw4)**: Vercel released emergency updates for Next.js fixing a Windows path traversal flaw and a heap buffer overflow in the libheif library triggered via AVIF image optimization. Both permit unauthenticated remote code execution. [More info](https://thehackernews.com/2026/08/nextjs-patches-critical-avif-and.html)

- **CISA Adds 3 Flaws to KEV Catalog**: CISA added CVE-2023-49105 (ownCloud), CVE-2026-53362 (Linux Kernel), and CVE-2026-66384 (JFrog Artifactory) to its KEV Catalog due to active exploitation. Federal agencies must remediate them per BOD 26-04 timelines. [More info](https://www.cisa.gov/news-events/alerts/2026/08/27/cisa-adds-three-known-exploited-vulnerabilities-catalog)

- **CISA Adds 6 Flaws to KEV Catalog**: CISA expanded its catalog with six additional active exploits, including Red Hat (CVE-2015-3246, CVE-2015-5287), MS SQL Server (CVE-2019-1068), Ajax.NET Professional (CVE-2021-23758), Linux Kernel (CVE-2022-0995), and Citrix NetScaler (CVE-2026-8452). [More info](https://www.cisa.gov/news-events/alerts/2026/08/26/cisa-adds-six-known-exploited-vulnerabilities-catalog)

- **Critical Avada & Fusion Builder WordPress Flaw (CVE-2026-18431)**: An exploit chain rated CVSS 9.8 allows unauthenticated attackers to execute arbitrary PHP code on vulnerable WordPress sites. Emergency fixes were released in Avada 7.16.1. [More info](https://www.bleepingcomputer.com/news/security/critical-avada-wordpress-theme-flaw-enables-zero-click-rce/)

- **Ubiquiti Maximum-Severity Patches**: Ubiquiti patched three critical flaws allowing unauthenticated RCE or authentication bypass across UniFi Protect (CVE-2026-77537), UniFi OS (CVE-2026-77550), and UniFi Talk (CVE-2026-77554). [More info](https://www.bleepingcomputer.com/news/security/ubiquiti-patches-three-max-severity-security-vulnerabilities/)

- **Active Exploitation Chain Targeting Microsoft SharePoint**: Attackers are chaining CVE-2026-55040 (JWT authentication bypass) and CVE-2026-63520 (Business Connectivity Services RCE) to perform administrative enumeration and gain execution on SharePoint servers. [More info](https://www.bleepingcomputer.com/news/security/hackers-target-microsoft-sharepoint-rce-chain-with-poc-exploit/)

- **Amazon Kiro IDE Prompt Injection**: A flaw in version 0.7.45 allows malicious repository files (`POWER.md`) to hijack the AI agent and exfiltrate sensitive local files to external endpoints. The issue was fixed in version 0.8.140. [More info](https://thehackernews.com/2026/08/amazon-kiro-prompt-injection-can.html)

- **GPUThor Rowhammer Attack on NVIDIA GPUs**: University of Toronto researchers demonstrated GDDR6 memory hammering on workstation GPUs (RTX A6000/A5000), bypassing ECC protection to cause memory corruption and host privilege escalation to root. [More info](https://thehackernews.com/2026/08/gputhor-rowhammer-defeats-ecc-on-nvidia.html)

## 🎯 Adversaries

- **Dark Caracal Deploys GoCaracal Malware**: Arctic Wolf Labs tied a Venezuelan communications breach to the Lebanon-nexus group Dark Caracal, who deployed a new Go-based implant with an Ethereum smart-contract C2 fallback mechanism. [More info](https://securityaffairs.com/197948/apt/dark-caracal-deploys-new-go-malware-with-ethereum-based-c2-fallback.html)

- **TeamPCP Cybercrime Syndicate Arrests**: Law enforcement in Australia and the US arrested two men for planting a self-spreading worm (Mini Shai-Hulud) in open-source repositories, compromising over 1,000 organizations. [More info](https://www.helpnetsecurity.com/2026/08/27/alleged-teampcp-hackers-arrested-australia/)

- **FBI Disrupts China-Linked "QTFY" Proxy Infrastructure**: The FBI seized domain infrastructure used by QTFY, a quartermaster group operating reconnaissance platforms (QScan) and proxy networks (QTRouter) targeting US government entities. [More info](https://www.bleepingcomputer.com/news/security/fbi-disrupts-proxy-network-enabling-chinese-espionage-operations/)

- **NovaCookies Phishing-as-a-Service**: A new AiTM phishing kit advertised on Telegram abuses DocuSign notification emails and OAuth redirects to bypass MFA and hijack Microsoft 365 sessions. [More info](https://thehackernews.com/2026/08/novacookies-campaigns-abuse-genuine.html)

- **SLEEPWALKER Stealth Memory Backdoor**: Researchers detailed a passive Windows backdoor that side-loads into `ERAAgent.exe` as `dpapi.dll`. It remains silent until triggered by a specific encrypted network packet. [More info](https://thehackernews.com/2026/08/newly-sleepwalker-backdoor-waits-for.html)

- **Mobile Tech Support Scam Fake Apple Pay Interface**: Malicious websites are mimicking Apple Pay and Face ID components while leveraging the Web Speech API to read out fake charge alerts and pressure victims into calling fraudulent support lines. [More info](https://www.malwarebytes.com/blog/scams/2026/08/fake-apple-pay-charge-brings-the-classic-tech-support-scam-to-your-phone)

- **AnonyMousKIT Phishing Targets Lost Apple Devices**: An automated phishing kit uses AI voice agents, SMS, and email lures impersonating Apple Support to trick victims into revealing passcodes and MFA tokens to bypass Activation Lock. [More info](https://thehackernews.com/2026/08/fake-apple-support-ai-calls-target.html)

## 📈 Trends

- **Unit 42 Warns of Agentic AI Acceleration**: Palo Alto Networks highlighted that threat actors are leveraging autonomous AI frameworks across attack chains, allowing single attackers to compromise tens of enterprise applications in hours. [More info](https://cyberscoop.com/unit-42-palo-alto-networks-warning-agentic-ai-frontier-models/)

- **Apple AI Rollout Meets EU Regulatory Friction**: EU Digital Markets Act requirements are forcing changes to Apple's ecosystem, causing delays for features like Siri AI while pushing reliance on Google Gemini models on Private Cloud Compute. [More info](https://www.zdnet.com/article/apple-escaped-android-toxic-hellstew-siri-ai-creates-a-new-one/)

- **Android 17 Integrates Encrypted Client Hello (ECH)**: Google announced platform-level support for ECH in Android 17 to encrypt SNI domain metadata, alongside ECH GREASE implementation and mandatory Certificate Transparency. [More info](https://www.bleepingcomputer.com/news/security/android-17-adds-ech-support-to-make-web-browsing-harder-to-track/)

- **HTTP Terminator AI Framework Discovers Smuggling Vectors**: PortSwigger unveiled an open-source AI tool that autonomously identifies novel HTTP request desync vectors against modern web infrastructure. [More info](https://www.darkreading.com/application-security/http-terminator-hunts-novel-desync-attacks)

- **Evolution of Modern SOCs to AI Hypothesis Engines**: Security operations are transitioning away from manual queue triage toward asynchronous agentic AI engines that test threat hypotheses across raw network telemetry automatically. [More info](https://thehackernews.com/2026/08/imagine-soc-without-queue-from-alert.html)

- **Snowflake Enforces Phase 3 Service Account Security**: Snowflake has deprecated legacy password authentication for non-human accounts, requiring migration to SERVICE user types, OAuth, or Workload Identity Federation. [More info](https://www.bleepingcomputer.com/news/security/snowflake-ends-service-account-passwords-now-comes-the-hard-part/)

## 💥 Breaches & Leaks

- **ShinyHunters Leaks 13M Carhartt Records**: Following a failed $3.3M extortion attempt linked to a Databricks environment compromise, ShinyHunters published 50GB of stolen customer and employee data. [More info](https://www.bleepingcomputer.com/news/security/carhartt-data-breach-exposes-information-of-129-million-accounts/)

- **ATF Confirms Standalone System Incident After QILIN Claims**: The Bureau of Alcohol, Tobacco, Firearms and Explosives disconnected a segregated standalone system following extortion claims by the Qilin ransomware gang. [More info](https://www.bleepingcomputer.com/news/security/atf-confirms-major-incident-after-recent-qilin-breach-claims/)

- **Boston Scientific Operations Disrupted by Cyberattack**: A cyber incident detected on August 25 impacted global order processing and shipping services, forcing the medical device maker to deploy external response teams. [More info](https://www.bleepingcomputer.com/news/security/boston-scientific-says-cyberattack-disrupted-operations-globally/)

## 📚 Others

- **Meta Agrees to $17B Child Safety Lawsuit Settlement**: Resolving a multi-state attorney general lawsuit over teen mental health and privacy, Meta agreed to mandate daily screen time limits and default safety controls on Instagram and Facebook. [More info](https://www.malwarebytes.com/blog/news/2026/08/new-instagram-and-facebook-rules-will-set-a-default-two-hour-daily-limit-for-teens)

---

[⬅ Back to Archive](https://pranakn.github.io)
