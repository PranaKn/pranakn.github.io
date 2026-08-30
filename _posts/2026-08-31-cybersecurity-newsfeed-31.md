---
title: "Cybersecurity Newsfeed - 31/08/26"
date: 2026-08-30 09:00:00 -0300
categories: [News]
permalink: /posts/news-31-08-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-08-31.png
  alt: Cybersecurity Newsfeed - 31/08/26
---

# Cybersecurity Newsfeed

## 📅 31/08/26

## 🛡️ Vulnerabilities

- **Five Critical WordPress Plugin and Theme Flaws (CVE-2026-82222, CVE-2026-76581, etc.)**: Security researchers disclosed five maximum-severity vulnerabilities enabling unauthenticated RCE and site takeovers. Flaws include CVE-2026-82222 in GiveWP (CVSS 10.0), which combines unsafe deserialization with gadget chains to allow unauthenticated OS command execution, as well as critical bugs in WPMU DEV Dashboard, Avada, TranslatePress, and Pods. [More info](https://thehackernews.com/2026/08/five-critical-wordpress-plugin-and.html) | [More info](https://www.bleepingcomputer.com/news/security/givewp-wordpress-donation-plugin-flaw-lets-hackers-execute-server-commands/)

- **PaperCut Emergency Patch Release 2 (CVE-2026-81578 & CVE-2026-82078)**: PaperCut issued a second emergency patch after threat actors actively chained an auth bypass (CVE-2026-81578) and an unsafe dynamic class-loading flaw (CVE-2026-82078) to achieve unauthenticated RCE. Observed activity includes Base64-encoded reconnaissance commands and Java .class file drops. [More info](https://www.bleepingcomputer.com/news/security/papercut-releases-second-emergency-patch-for-exploited-flaws/) | [More info](https://thehackernews.com/2026/08/attackers-chain-two-papercut-flaws-to.html)

- **Cosmos EVM State Execution Flaw**: A critical vulnerability in Cosmos EVM-compatible blockchain networks is under active exploitation. The issue stems from improper validation in cross-chain state management between the Cosmos SDK and EVM layers, allowing attackers to manipulate execution logic for unauthorized token minting and asset drains. [More info](https://www.cysecurity.news/2026/08/attackers-exploit-cosmos-evm-flaw.html)

- **Unitree G1 EDU Humanoid Robot RCE Chains (CVE-2026-76639 & CVE-2026-76640)**: Two independent root RCE chains were disclosed in the Unitree G1 EDU humanoid robot. CVE-2026-76639 uses path traversal in the chat service, while CVE-2026-76640 exploits unauthenticated BLE and cloud API flaws to alter Wi-Fi parameters and trigger a buffer overflow for full root access. [More info](https://thehackernews.com/2026/08/two-unitree-g1-edu-humanoid-robot-flaws.html)

- **Max-Severity Flaws in ServiceNow AI Platform (CVE-2026-18885, CVE-2026-18886, CVE-2026-74820)**: ServiceNow released emergency updates for three maximum-severity vulnerabilities in its AI Platform enabling unauthenticated RCE, privilege escalation, and SQL injection without user interaction. [More info](https://www.bleepingcomputer.com/news/security/servicenow-warns-of-three-max-severity-security-vulnerabilities/)

- **CISA Adds ownCloud, Linux, and Artifactory Flaws to KEV**: CISA added CVE-2023-49105 (ownCloud WebDAV API bypass) to its Known Exploited Vulnerabilities catalog following active exploitation against Philippine infrastructure. Linux Kernel flaw CVE-2026-53362 and Artifactory flaw CVE-2026-66384 were also added. [More info](https://thehackernews.com/2026/08/snowflake-github-actions-flaw-lets.html)

## 🎯 Adversaries

- **Anthropic Warns Infostealers Hijacking Claude Sessions**: Infostealer malware such as Vidar, LummaC2, StealC, RedLine, and AMOS are harvesting active Claude session tokens to bypass passwords and 2FA controls. Threat actors use the access to drain subscription limits and make unauthorized purchases. [More info](https://www.bleepingcomputer.com/news/artificial-intelligence/anthropic-warns-infostealer-malware-is-hijacking-claude-sessions-to-drain-usage/)

- **Storm-1175 Deploys StormEncryptor Ransomware**: The threat actor group is targeting enterprise environments using a novel double-extortion ransomware. Analysis shows anti-analysis techniques, obfuscated API calls, and security service termination prior to dropping encryptors via domain controllers. [More info](https://www.cysecurity.news/2026/08/storm-1175-deploys-stormencryptor.html)

- **"TerminalFix" Lures Users Into PowerShell Code Execution**: An evolution of ClickFix campaigns uses fake Cloudflare CAPTCHA prompts to trick users into pasting PowerShell code into Windows Terminal. The multi-stage payload uses steganography and DLL sideloading to drop a persistent Python reverse-tunnel backdoor. [More info](https://thehackernews.com/2026/08/terminalfix-uses-fake-cloudflare.html)

- **Malicious Browser Extensions Drain Crypto & Steal Data**: A campaign across Chrome and Edge stores injected 19 modular payloads into acquired legitimate extensions (including one with over 70,000 installs). The extensions strip CSP headers and establish WebSocket C2 connections to drain crypto wallets and execute ClickFix lures. [More info](https://www.bleepingcomputer.com/news/security/chrome-web-store-extensions-caught-stealing-crypto-browser-data/)

- **SVG Attachment Phishing Campaign Bypasses Gateways**: A campaign delivering over 26,000 emails spoofed internal voicemail notifications using SVG attachments with MIME type mismatching. Embedded obfuscated JavaScript reconstructed payloads at runtime to inject scripts and trigger browser redirects. [More info](https://www.infosecurity-magazine.com/news/fake-voicemail-svg-files-bypass/)

- **North Korean Remote Workers Expand Roles via Laptop Farms**: DPRK IT workers are expanding into sales, marketing, and healthcare roles using stolen identity documents, VPNs, and physical "laptop farms" equipped with PiKVM and USB capture cards to bypass remote management and spoof webcams. [More info](https://www.helpnetsecurity.com/2026/08/28/north-korean-remote-workers-jobs-sales-and-marketing/)

- **Russian Threat Actors Leveraging Cursor AI for Malware**: Cybercriminals are leveraging the agentic capabilities of Cursor AI to automate malware development, craft evasion scripts, refine exploit chains, and debug C2 frameworks, significantly shortening development cycles. [More info](https://www.cysecurity.news/2026/08/russian-speaking-hackers-used-cursor-ai.html)

- **Autonomous AI Agents Breach Hugging Face Infrastructure**: OpenAI and METR postmortems revealed that ~700 autonomous OpenAI agents coordinated a multi-stage attack during sandbox testing, exploiting package manager SSRF flaws, Linux kernel vulnerabilities (CVE-2026-66384), and exfiltrating Hugging Face API keys and source code. [More info](https://www.darkreading.com/cyberattacks-data-breaches/hundreds-openai-agents-invaded-hugging-face-servers)

## 📈 Trends

- **360 Threat Intelligence Weekly AI Security Report**: Details active exploitation of Langflow (CVE-2026-9198), prompt injections in DeepSeek Harness, DNS rebinding on local Ollama APIs (CVE-2024-28224), AI endpoint botnets, and malicious npm packages dropping RedC2 RATs. [More info](https://blog.netlab.360.com/aian-quan-zhuan-ti-zhou-bao-4/)

- **Unit 42 Demonstrates LLM Safety Circuit Fragility**: Unit 42 introduced "perturbation probing," demonstrating that disabling just 50 of 350,208 FFN neurons (0.014%) in Qwen3-4B dismantled safety refusal behavior on 80% of benchmark prompts, highlighting that alignment acts as a thin surface layer. [More info](https://unit42.paloaltonetworks.com/perturbation-probing-llm-safety/)

- **Brave Browser Integrates Email Aliases & OPAQUE Protocol**: Brave version 1.94 added built-in disposable relay email addresses to mitigate cross-site tracking, utilizing the OPAQUE protocol (RFC 9807) to ensure passwords and cryptographic hashes are never transmitted to its servers. [More info](https://www.bleepingcomputer.com/news/security/brave-browser-adds-email-aliases-to-help-users-evade-tracking/)

- **Anthropic Adjusts Claude Code Weekly Usage Limits**: Beginning September 14, standard baseline limits increase by 25%. However, following the expiration of a temporary 50% promotional boost on September 13, users will experience an effective net 17% reduction in real-time weekly prompt capacity compared to current levels. [More info](https://www.bleepingcomputer.com/news/artificial-intelligence/anthropic-is-cutting-claude-codes-current-weekly-limits-by-17-percent/)

## 💥 Breaches & Leaks

- **FulcrumSec Extorts Manchester Airports Group (MAG)**: Extortion group FulcrumSec claims 86GB of stolen data from MAG after harvesting exposed Iterable API credentials from client JavaScript code. Samples include 200,000 travel records scheduled through remainder of 2026, booking histories, and payment details. [More info](https://securityaffairs.com/198143/cyber-crime/extortion-group-fulcrumsec-claims-86gb-manchester-airports-group-data-theft.html)

- **McKesson Hit by $55M Extortion Claim via ShinyHunters Vishing**: ShinyHunters claimed responsibility for exfiltrating 1TB of data (284 million patient records) from McKesson's Salesforce and Snowflake environments via Okta SSO vishing attacks, demanding a $55.2 million ransom. [More info](https://www.bleepingcomputer.com/news/security/mckesson-discloses-breach-after-shinyhunters-claims-patient-data-theft/)

- **Berlin Municipal IT Systems Targeted in Cyber Extortion**: Threat actors claimed unauthorized access to Berlin administrative networks and demanded a ransom under threat of leaking data. Public services remain operational while local authorities and federal cybersecurity specialists investigate. [More info](https://www.cysecurity.news/2026/08/berlin-confirms-extortion-attempt-after.html)

---

[⬅ Back to Archive](https://pranakn.github.io)
