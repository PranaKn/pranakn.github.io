---
title: "Cybersecurity Newsfeed - 01/07/26"
date: 2026-06-30 18:14:00 -0300
categories: [News]
permalink: /posts/news-01-07-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware, ai-security]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-07-01.png
  alt: Cybersecurity Newsfeed - 01/07/26
---

# Cybersecurity Newsfeed

## 📅 01/07/26

## 🛡️ Vulnerabilities

- **Progress Kemp LoadMaster Critical Pre-Auth Flaw**: A maximum-severity pre-authentication vulnerability has been disclosed in the Progress Kemp LoadMaster management API. Unauthenticated, remote attackers can bypass controls via a crafted request to execute arbitrary system commands with elevated root privileges. Organizations must apply emergency patches immediately to prevent complete device takeover. [More info](https://thehackernews.com/2026/06/progress-kemp-loadmaster-flaw-could-let.html)

- **SimpleHelp OIDC Flow Authentication Bypass (CVE-2026-48558)**: Attackers are actively weaponizing this critical vulnerability in public-facing SimpleHelp servers. Exploitation grants an authenticated technician session used to deploy the TaskWeaver JavaScript loader and subsequent Djinn Stealer malware. [More info](https://www.darkreading.com/cyberattacks-data-breaches/djinn-stealer-targets-cloud-ai-credentials)

- **Apple Rushes Emergency Fixes in iOS & macOS (v26.5.2)**: Apple released out-of-band updates addressing 29 vulnerabilities, including critical kernel-level bugs and memory-safety flaws in WebKit. The release was accelerated to counter threat actors weaponizing AI to rapidly generate functional exploits for public flaws. [More info](https://www.zdnet.com/article/apple-rushed-software-fixes-over-ai-threats-update-iphone-asap/)

## 🎯 Adversaries

- **RustDuck Botnet Rebuilds Core in Rust**: Active since February 2026, the RustDuck DDoS malware family targeting Android boxes, IP cameras, and routers is systematically rewriting its modules from C to Rust to hinder analysis. It uses rotating ChaCha20-Poly1305 and AES-GCM keys and propagates via credential brute-forcing and router vulnerabilities. [More info](https://thehackernews.com/2026/06/rustduck-botnet-rebuilds-in-rust-to.html)

- **Djinn Stealer Targets Local AI Development Configurations**: Delivered via compromised SimpleHelp servers, Djinn Stealer is designed to harvest infrastructure secrets, cloud configurations, SSH keys, package registry tokens, and local configuration files for AI development tools like Claude and Gemini. [More info](https://www.darkreading.com/cyberattacks-data-breaches/djinn-stealer-targets-cloud-ai-credentials)

- **"Operation Navy Ghost" Seeds Backdoored PyPI Packages**: Attackers published at least eight malicious forks of the unmaintained Pyrogram framework (such as VLifeGram). The packages contain a hidden `secret.py` module that grants attackers silent shell access and arbitrary code execution on compromised Telegram bot servers. [More info](https://www.bleepingcomputer.com/news/security/malicious-pypi-packages-give-hackers-control-of-telegram-bot-servers/)

- **Silent Swap Crypto Clipper Employs Fake "Google Notes"**: McAfee Labs exposed a campaign deploying unsigned installers (e.g., BaseZipInstaller) written in .NET and Golang to sideload a malicious Chromium extension. It monitors browser activity to stealthily swap out cryptocurrency wallet addresses during live transactions. [More info](https://thehackernews.com/2026/06/silent-swap-crypto-clipper-uses-fake.html)

- **TONResolver RAT Abuses Blockchain Smart Contracts**: A phishing campaign targeting Booking.com partner hotels in Japan delivers a JavaScript RAT wrapped in VM-based obfuscation. The malware uniquely abuses The Open Network (TON) blockchain smart contracts as a dead drop resolver to dynamically update C2 addresses. [More info](https://www.infosecurity-magazine.com/news/hackers-blockchain-japan-hotels/)

## 📈 Trends

- **Poisoned MCP Tool Descriptions Hijack Workplace AI**: Microsoft research reveals that attackers can manipulate the Model Context Protocol (MCP) by secretly changing tool metadata. This alters an AI agent's working memory, letting threat actors bypass boundaries to force unauthorized file exfiltration or invoice fraud. [More info](https://thehackernews.com/2026/06/microsoft-warns-poisoned-mcp-tool.html)

- **ClickFix Emerges as Top Global Malware Delivery Method**: ReliaQuest analysis shows the ClickFix social engineering technique—which tricks users into copying and pasting malicious PowerShell or script commands from fake CAPTCHAs—is now highly favored. It has also expanded to target macOS users with Atomic Stealer (AMOS). [More info](https://www.infosecurity-magazine.com/news/clickfix-cybercriminals-favorite/)

- **GuardFall Flaw Bypasses Controls in Open-Source AI Coding Agents**: Research from Adversa AI outlines a major security bypass affecting 10 out of 11 popular open-source AI computer-use agents. Using shell injection and bash-rewriting, attackers can trick agents scanning a booby-trapped repository into running arbitrary system code. [More info](https://thehackernews.com/2026/06/guardfall-exposes-open-source-ai-coding.)

- **EvilTokens Exploits SOC Visibility Gaps via Device Code Flow**: Data from ANY.RUN highlights an attack vector where phishing payloads are delivered as AES-GCM encrypted strings to evade static URL scanners. Once executed in the browser, EvilTokens abuses Microsoft's Device Code flow for credential-less account takeovers. [More info](https://hackread.com/eviltokens-attack-browser-visibility-gap-enterprise-socs/)

- **Rogue Perplexity AI Extension Hits Chrome Web Store**: A malicious extension capitalizing on Perplexity AI branding was discovered harvesting sensitive browsing data and search traffic from compromised users under the cover of pervasive browser permissions. [More info](https://www.bleepingcomputer.com/news/security/fake-perplexity-extension-on-chrome-web-store-tracked-searches/)

- **Aikido Security Acquires Root for Backported Open-Source Patches**: In a move to combat supply chain risks without introducing breaking upgrades, Aikido Security acquired Root (formerly Slim.AI) to automate daily, verified backported security fixes directly into vulnerable software dependencies. [More info](https://www.helpnetsecurity.com/2026/06/30/aikido-security-root-acquisition/)

- **Jamf Announces Native AI Governance for Apple Silicon Mac**: To combat endpoint "Shadow AI," Jamf rolled out controls that natively discover running instances like Claude Desktop or OpenAI Codex. The system integrates with Okta to enforce scoped, short-lived credentials for AI agents. [More info](https://www.helpnetsecurity.com/2026/06/30/jamf-enables-ai-governance-and-shadow-ai-detection-on-mac/)

- **Microsoft Teams Adds Smart Rogue Bot Protection**: Microsoft rolled out a new Teams admin policy to detect and route unauthorized third-party bots to the meeting lobby. The feature blocks automated note-taking apps and impersonation setups used by attackers to eavesdrop. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-adds-smarter-bot-protection-to-teams-meetings/)

---

[⬅ Back to Archive](https://pranakn.github.io)
