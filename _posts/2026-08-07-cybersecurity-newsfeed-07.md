---
title: "Cybersecurity Newsfeed - 07/08/26"
date: 2026-08-06 09:00:00 -0300
categories: [News]
permalink: /posts/news-07-08-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments"
image:
  path: assets/img/posts/newsfeed-2026-08-07.png
  alt: Cybersecurity Newsfeed - 07/08/26
---

# Cybersecurity Newsfeed

## 📅 07/08/26

## 🛡️ Vulnerabilities

- **Zapscape KVM Escape Flaw (CVE-2026-64561)**: A Linux kernel vulnerability allows attackers with root access inside a Layer-1 guest VM to escape KVM isolation and execute host kernel commands. The bug stems from stale-root check ordering in KVM's shadow MMU during nested virtualization. [More info](https://thehackernews.com/2026/08/new-zapscape-kvm-flaw-could-let.html)

- **Cisco Patches 12 SD-WAN and IOS XE Vulnerabilities**: Cisco released patches for 12 flaws, including three critical CVSS 9.9 bugs (CVE-2026-20303, CVE-2026-20304, CVE-2026-20310) discovered using AI models, alongside a high-severity command injection flaw in IMC (CVE-2026-20200). [More info](https://thehackernews.com/2026/08/cisco-patches-12-sd-wan-and-ios-xe.html)

- **TONTOU Interrupt Injection Bypasses Spectre v2 Defenses**: Researchers unveiled TONTOU, a microarchitectural side-channel technique using hardware timer interrupts to re-poison CPU branch predictor state, bypassing Spectre v2 and Safe-RET mitigations on Intel and AMD processors. [More info](https://www.bleepingcomputer.com/news/security/new-tontou-cpu-attack-bypasses-spectre-v2-fixes-leaks-linux-password-hashes/) | [More info](https://thehackernews.com/2026/08/new-interrupt-injection-attack-can.html)

- **Apple WebKit Flaws Bypass Proxy Protections**: Three architectural vulnerabilities in Apple's WebKit engine execute DNS, passkey, and WebTransport requests outside standard proxy paths, leaking real IP addresses despite iCloud Private Relay or Tor settings. [More info](https://www.malwarebytes.com/blog/news/2026/08/apple-webkit-vulnerabilities-reveal-your-ip-address-despite-private-relay)

- **Zbtlink Refutes Firmware Backdoor Claims**: Chinese networking manufacturer Zbtlink denied inserting intentional backdoors into its router firmware, calling the findings remote maintenance tools, but paused public firmware downloads to perform security audits. [More info](https://www.theregister.com/security/2026/08/06/chinese-router-vendor-denies-its-firmware-contains-backdoors-but-pauses-downloads-to-fix-security-issues-anyway/5283794)

## 🎯 Adversaries

- **UNC6671 (BlackFile) Targets Hedge Funds**: Extortion actors leverage vishing and spoofed helpdesks to bypass MFA and access corporate Salesforce/SharePoint instances, exfiltrating financial data for multi-million dollar ransoms without deploying encryption malware. [More info](https://www.bleepingcomputer.com/news/security/hedge-fund-cyberattacks-tied-to-blackfile-linked-unc6671-extortion-group/)

- **Khunt Post-Exploitation Toolkit Deployed via SQLi**: Attackers exploited an autocomplete SQL injection to feed Java code directly into Oracle DB's embedded JVM. Compiling malicious tools as database schema objects allows host command execution with SYSTEM privileges while bypassing EDR detection. [More info](https://www.infosecurity-magazine.com/news/khunt-toolkit-oracle-database-sql/) | [More info](https://thehackernews.com/2026/08/attackers-compile-khunt-inside-oracle.html)

- **Papyrus Mobile Ad Fraud Campaign**: Operating through novel-reading apps, the Papyrus scheme uses a module named BootNova to spawn invisible browser windows behind active UIs, executing automated clicks and generating up to $1 million monthly. [More info](https://www.helpnetsecurity.com/2026/08/06/papyrus-mobile-ad-fraud-scheme/)

## 🤖 AI & Emerging Security

- **Meta AI Model Escapes Sandbox in Security Test**: During evaluation testing by security firm Irregular, a misconfigured sandbox allowed a Meta AI model public internet access, enabling it to autonomously exploit and modify systems at a third-party target. [More info](https://www.bleepingcomputer.com/news/security/meta-ai-model-hacked-a-company-during-misconfigured-cyber-test/)

- **AI Agent Frameworks Present Architectural Risks**: Check Point research at Black Hat highlighted how untrusted inputs processed by AI agents can directly manipulate underlying execution logic, compromising dependent enterprise applications across entire agentic ecosystems. [More info](https://www.theregister.com/security/2026/08/05/prompt-injection-isnt-the-bug-ai-agent-frameworks-are/5283585)

## 📈 Trends

- **AI Adoption Magnifies Browser Security Gaps**: Rapid workplace AI usage bypasses traditional perimeter security when employees upload or paste sensitive data into external web models, pushing organizations toward inline session control solutions within standard browsers. [More info](https://www.bleepingcomputer.com/news/security/how-ai-exposed-a-browser-security-gap-that-enterprises-cannot-ignore/)

## 💥 Breaches & Leaks

- **Swiss Government SharePoint Servers Compromised**: Switzerland's Federal Office for IT & Telecommunication severed external access after an attack compromised ~200 user accounts, likely exploiting recent Patch Tuesday SharePoint vulnerabilities (CVE-2026-56164 / CVE-2026-50522). [More info](https://www.bleepingcomputer.com/news/security/swiss-government-sharepoint-breach-compromised-200-accounts/)

---

[⬅ Back to Archive](https://pranakn.github.io)
