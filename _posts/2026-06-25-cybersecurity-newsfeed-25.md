---
title: "Cybersecurity Newsfeed - 25/06/26"
date: 2026-06-24 18:00:00 -0300
categories: [News]
permalink: /posts/news-25-06-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-06-25.png
  alt: Cybersecurity Newsfeed - 25/06/26
---

# Cybersecurity Newsfeed

## 📅 25/06/26

## 🛡️ Vulnerabilities

- **CISA Warns of Max-Severity Ubiquiti Flaws (CVE-2026-34908, CVE-2026-34909, CVE-2026-34910)**: CISA issued an urgent warning regarding the active exploitation of three perfect 10.0 CVSS flaws in Ubiquiti UniFi OS. Attackers are chaining an NGINX authentication gateway bypass with input validation bugs for remote command injection, allowing them to silently create rogue admin accounts during automated reconnaissance. [More info](https://www.bleepingcomputer.com/news/security/cisa-warns-of-max-severity-ubiquiti-flaws-exploited-in-attacks/)

- **Critical Lantronix EDS5000 Flaw Added to KEV (CVE-2025-67038)**: CISA added a critical improper input validation flaw affecting Lantronix EDS5000 serial-to-ethernet converters to its Known Exploited Vulnerabilities catalog. Boasting a CVSS score of 9.8, unauthenticated remote attackers can exploit the HTTP RPC username parameter to execute arbitrary OS commands with root privileges, posing severe cyber-physical risks to OT environments. [More info](https://thehackernews.com/2026/06/cisa-warns-critical-lantronix-eds5000.html)

- **PixelSmash Video Decoder Vulnerability (CVE-2026-8461)**: Security researchers disclosed a critical vulnerability inside FFmpeg’s MagicYUV video decoder. Carrying a CVSS score of 8.8, the flaw allows attackers to weaponize malformed video files (AVI, MKV, MOV) to trigger system crashes or arbitrary code execution when applications attempt to render thumbnails, play videos, or extract metadata. [More info](https://www.malwarebytes.com/blog/news/2026/06/pixelsmash-flaw-turns-video-files-into-attack-tools)

## 🎯 Adversaries

- **North Korean macOS.Gaslight Backdoor Mimics AI Tools**: Researchers discovered a sophisticated Rust-based macOS backdoor attributed to North Korean state-sponsored actors. The implant embeds 38 fabricated system messages formatted to mimic AI-assisted triage tools to derail automated malware analysis, while secretly exfiltrating browser cookies and keychains via an encrypted Telegram C2 channel. [More info](https://www.infosecurity-magazine.com/news/macos-gaslight-rust-backdoor/)

- **StrikeShark Campaign Targets Government and Tech Sectors**: Kaspersky’s GReAT team uncovered a sophisticated global malicious campaign utilizing a previously undocumented malware loader called SharkLoader to deliver Cobalt Strike Beacons. Initial access is achieved by exploiting known vulnerabilities in Microsoft Exchange and SharePoint or using droppers disguised as legitimate installers. [More info](https://securelist.com/strikeshark-campaign/120326/)

- **Woodgnat IAB Deploys New Mistic RAT**: An initial access broker tracked as Woodgnat is deploying a new remote access trojan named Backdoor.Mistic across education, insurance, and IT sectors. Executed via DLL side-loading, the malware establishes access via compromised WordPress sites and ClickFix social engineering to later sell access to prominent ransomware groups. [More info](https://www.securityweek.com/new-mistic-rat-opens-door-to-several-ransomware-families/)

- **Fake npm Packages Impersonate PostCSS to Steal Chrome Passwords**: JFrog discovered three malicious packages on the npm registry, including `postcss-minify-selector-parser`, designed to deceive software developers. Upon installation, the package executes a multi-stage infection chain to deploy a Python-based RAT that targets Google Chrome to steal saved credentials and bypass app-bound encryption. [More info](https://hackread.com/fake-npm-packages-postcss-tool-steal-chrome-password/)

## 📈 Trends

- **Device Code Phishing Attacks Surge 1,380%**: New research from Huntress exposes a dramatic spike in device code phishing during early 2026, driven by a sophisticated phishing-as-a-service platform. By leveraging automated AI workflows and legitimate developer cloud infrastructure like Railway, attackers abuse Microsoft 365 authentication flows to render MFA obsolete. [More info](https://www.itsecurityguru.org/2026/06/24/ai-powered-phishing-attacks-surge-1380-as-criminal-platforms-render-mfa-obsolete/)

- **BioShocking Technique Bypasses AI Browser Guardrails**: LayerX demonstrated a novel proof-of-concept attack technique that tricks AI-powered web browsers and plugins (such as ChatGPT Atlas and Claude extensions) into abandoning safety guardrails. Using prompt injection, attackers convince the AI it is engaging in a fictional game, leading it to silently exfiltrate user credentials. [More info](https://www.infosecurity-magazine.com/news/bioshocking-ai-browser-prompt/)

- **Malicious Edge Extension Abuses Native Messaging API**: A newly identified malicious browser extension targeting Microsoft Edge uses the browser's Native Messaging API to bypass traditional sandbox boundaries. This legitimate communication interface allows the extension to establish a direct bridge to launch secondary malware payloads on the host operating system. [More info](https://www.bleepingcomputer.com/news/security/malicious-edge-extension-abuses-native-messaging-as-bridge-to-malware/)

- **macOS Weaknesses Chained to Silently Disable EDR**: XM Cyber demonstrated a sophisticated privilege escalation technique enabling standard macOS users to silently disable enterprise endpoint security tools. The method chains weakly validated cross-process communication connections and payload injections into Interface Builder files to deactivate prominent EDR agents and MDM tools. [More info](https://www.securityweek.com/macos-weaknesses-chained-to-silently-disable-endpoint-security-agents/)

## 💥 Breaches & Leaks

- **LastPass Confirms Data Breach via Third-Party Supplier Klue**: LastPass confirmed a new data breach resulting from a security incident at its customer relationship management supplier, Klue. Threat actors compromised OAuth security tokens to access customer data stored within Salesforce, including names, phone numbers, email addresses, and support descriptions. Master passwords and vaults remain unaffected. [More info](https://www.zdnet.com/article/lastpass-new-data-breach-2026-steps-to-take-now/)

## 🤖 AI Supply Chain

- **OpenClaw Autonomous AI Framework Found Highly Vulnerable**: Security audits of the popular OpenClaw autonomous AI agent framework revealed over 512 distinct vulnerabilities. The most critical, ClawJacked, involves an unauthenticated local WebSocket server that lets malicious sites execute arbitrary commands. Additionally, 7.6% of skills on the ClawHub marketplace were found to be malicious. [More info](https://www.darkreading.com/cyber-risk/malicious-openclaw-skills-clawhub-threaten-ai-supply-chain)

## ⚖️ Law Enforcement

- **Operation Endgame Disrupted Amadey and StealC Infrastructure**: International law enforcement coordinated by Europol and supported by private sector partners executed a major disruption against the Amadey loader and StealC infostealer families. The operation resulted in the seizure of over 200 C2 servers and 142 domains, recovering 27 million stolen credentials and freezing 41 million euros in criminal crypto assets. [More info](https://securityaffairs.com/194173/cyber-crime/europol-disrupts-stealc-and-amadey-malware-infrastructure-in-operation-endgame.html)

---

[⬅ Back to Archive](https://pranakn.github.io)
