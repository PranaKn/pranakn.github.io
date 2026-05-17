---
title: "Cybersecurity Newsfeed - 18/05/26"
date: 2026-05-17 09:00:00 -0300
categories: [News]
permalink: /posts/news-18-05-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-05-18.png
  alt: Cybersecurity Newsfeed - 18/05/26
---

# Cybersecurity Newsfeed

## 📅 18/05/26

## 🛡️ Vulnerabilities

- **Nginx HTTP/3 Critical Memory Corruption (CVE-2026-42945)**: A critical heap-based buffer overflow vulnerability in Nginx’s HTTP/3 module is under active exploitation. Attackers utilize specially crafted QUIC packets to trigger the flaw, enabling remote code execution on vulnerable web servers. With public proof-of-concept (PoC) code now published, automated scanners are actively identifying unpatched instances. Organizations are urged to update to Nginx version 1.27.4 or 1.28.1 immediately, or disable HTTP/3 support as a temporary mitigation. [More info](https://thehackernews.com/2026/05/nginx-cve-2026-42945-exploited-in-wild.html) | [More info](https://www.securityweek.com/poc-code-published-for-critical-nginx-vulnerability/)

- **Active Exploitation of Funnel Builder WordPress Plugin**: Cybercriminals are actively exploiting a critical vulnerability in the Funnel Builder WordPress plugin. The flaw allows unauthenticated attackers to perform unauthorized file uploads and execute arbitrary code, leading to the injection of "Magecart-style" JavaScript e-skimmers on checkout pages to harvest customer credit card data in real-time. Over 5,000 WooCommerce stores are estimated to be at risk. Administrators are urged to update to version 3.5.2 or higher immediately. [More info](https://securityaffairs.com/192260/cyber-crime/attackers-exploit-funnel-builder-bug-to-inject-e-skimmers-into-e-stores.html) | [More info](https://thehackernews.com/2026/05/funnel-builder-flaw-under-active.html) | [More info](https://www.bleepingcomputer.com/news/security/funnel-builder-wordpress-plugin-bug-exploited-to-steal-credit-cards/)

- **Microsoft Declines CVE for Azure Automation Service Flaw**: Microsoft has declined to issue a CVE for a critical privilege escalation vulnerability reported in Azure’s automation service, asserting it does not breach a security boundary. While researchers argue the risk of unauthorized internal tenant access is substantial, Microsoft maintains that existing configuration controls adequately mitigate the threat. [More info](https://www.bleepingcomputer.com/news/security/microsoft-rejects-critical-azure-vulnerability-report-no-cve-issued/)

- **CISA Adds New Enterprise Software Flaw to KEV Catalog**: The Cybersecurity and Infrastructure Security Agency (CISA) has added a new vulnerability to its Known Exploited Vulnerabilities (KEV) Catalog based on evidence of active exploitation. Federal agencies must apply patches by the specified deadline, and private organizations are strongly encouraged to prioritize it. [More info](https://www.cisa.gov/news-events/alerts/2026/05/15/cisa-adds-one-known-exploited-vulnerability-catalog)

- **Pwn2Own Day Two Showcases Zero-Days**: Security researchers demonstrated multiple zero-day vulnerabilities in Microsoft Exchange, Windows 11, and Red Hat Enterprise Linux. Highlights included a sophisticated Microsoft Exchange chain enabling remote code execution and complete system takeover, alongside Windows 11 kernel-level local privilege escalation bugs. [More info](https://www.bleepingcomputer.com/news/security/pwn2own-day-two-hackers-demo-microsoft-exchange-windows-11-red-had-enterprise-linux-zero-days/)

- **Microsoft Warns of Exchange Server Zero-Day**: Microsoft has issued an immediate warning regarding an Exchange Server zero-day vulnerability being exploited in targeted attacks via specially crafted emails to achieve remote code execution. While working on a patch, Microsoft has provided temporary URL rewrite mitigation rules. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-warns-of-exchange-zero-day-flaw-exploited-in-attacks/)

- **Google Patches Critical RCE Bugs in Chrome 148**: Google released Chrome version 148, patching several critical flaws, including a high-severity "use-after-free" bug in the browser's rendering engine that could lead to remote code execution if a user visits a malicious website. [More info](https://www.securityweek.com/chrome-148-update-patches-critical-vulnerabilities/)

- **"Claw Chain" Infrastructure Flaws Risk OpenClaw AI Servers**: Vulnerabilities discovered in OpenClaw AI server infrastructure could allow unauthorized actors to bypass authentication protocols. This grants administrative access to AI training environments, risking the theft of proprietary models, training data poisoning, and exposure of confidential queries. [More info](https://hackread.com/claw-chain-vulnerabilities-openclaw-ai-servers-risk/)

## 🎯 Adversaries

- **Tycoon2FA Kit Uses Device Code Flow to Bypass MFA**: The Tycoon2FA adversary-in-the-middle phishing kit has evolved to bypass multifactor authentication by leveraging Microsoft 365’s device code flow. It tricks users into entering a unique code on a legitimate login page, allowing attackers to authorize their own devices, hijack active sessions, and extract emails and session cookies. [More info](https://www.bleepingcomputer.com/news/security/tycoon2fa-hijacks-microsoft-365-accounts-via-device-code-phishing/)

- **Russian APT Turla Upgrades Kazuar Backdoor to P2P Botnet**: The Russian state-sponsored threat group Turla has significantly transformed its Kazuar backdoor into a highly sophisticated, modular P2P botnet for long-term espionage. By shifting to decentralized peer-to-peer communication, enhanced obfuscation, and a complex plugin system (supporting keylogging and file manipulation), the group reduces reliance on static infrastructure and resists sinkholing efforts within government and military networks. [More info](https://securityaffairs.com/192231/apt/russian-apt-turla-builds-long-term-access-tool-with-kazuar-botnet-evolution.html) | [More info](https://www.bleepingcomputer.com/news/security/russian-hackers-turn-kazuar-backdoor-into-modular-p2p-botnet/)

- **China-Linked Threat Actors Deploy New "TencShell" Backdoor**: State-sponsored Chinese threat actors are utilizing a sophisticated new malware strain named "TencShell" in espionage campaigns targeting government and telecommunications sectors in Southeast Asia. The backdoor uses custom encryption and multi-layer obfuscation to execute commands, upload files, and maintain long-term network presence. [More info](https://www.infosecurity-magazine.com/news/china-hackers-tencshell-malware/)

- **Ghostwriter Targets Ukrainian Officials with Phishing**: The Ghostwriter threat group, linked to Belarusian or Russian interests, is launching a new wave of credential-theft and malware-delivery phishing campaigns. The attacks impersonate official state departments to target Ukrainian government officials for cyber-espionage and communication disruption. [More info](https://thehackernews.com/2026/05/ghostwriter-targets-ukrainian.)

- **FamousSparrow Spies on Azerbaijani Energy Sector**: The FamousSparrow APT group has initiated a multi-wave espionage campaign targeting the Azerbaijani energy sector. Exploiting unpatched server vulnerabilities to deploy custom backdoors, the group aims to exfiltrate strategic data to influence regional energy politics. [More info](https://securityaffairs.com/192113/apt/famoussparrow-targets-azerbaijani-energy-sector-in-multi-wave-espionage-campaign.html)

## 📈 Trends

- **Physical Phishing Letters Target Ledger Wallet Users**: A high-effort social engineering campaign is targeting Ledger hardware wallet users via fraudulent letters mailed directly to their homes. Disguised as official Ledger security alerts, the correspondence includes a counterfeit, tampered replacement device with instructions to enter the 24-word recovery seed phrase into a malicious application, draining the victims' cryptocurrency. [More info](https://hackread.com/scammers-physical-phishing-letters-ledger-wallet-seed/)

- **Hackers Combine PyInstaller and AMSI Patching for XWorm RAT**: Attackers are distributing version 7.4 of the XWorm Remote Access Trojan (RAT) by packaging it with PyInstaller to complicate static analysis. The malware incorporates advanced in-memory Antimalware Scan Interface (AMSI) patching to bypass native Windows security features, enabling keylogging, file exfiltration, and secondary payload deployment. [More info](https://hackread.com/hackers-pyinstaller-amsi-patching-xworm-rat-v7-4/)

- **Microsoft Edge to Restrict Cleartext Passwords in Memory**: Microsoft Edge is introducing a security feature that halts the practice of loading decrypted user credentials into RAM upon browser startup. By keeping passwords encrypted until an explicit autofill action occurs, the update significantly mitigates risks associated with memory-scraping malware. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-edge-to-stop-loading-cleartext-passwords-in-memory-on-startup/)

- **Gremlin Stealer Evolves Sandbox and Virtual Machine Evasion**: Palo Alto Networks Unit 42 has detailed the evolution of Gremlin Stealer from a basic information collector into a sophisticated threat. The latest variants feature enhanced sandbox and virtual machine detection to evade analysis while ramping up exfiltration of Discord tokens, browser cookies, crypto wallets, and saved credentials via malicious advertisements. [More info](https://www.infosecurity-magazine.com/news/gremlin-stealer-evolves-into/) | [More info](https://unit42.paloaltonetworks.com/gremlin-stealer-evolution/)

- **Remus Infostealer Emerges in the MaaS Market**: Remus Infostealer has quickly gained traction as a prominent Malware-as-a-Service (MaaS) offering specializing in session hijacking and credential theft. Featuring a user-friendly dashboard for low-skilled operators, the malware employs rapid development updates specifically designed to bypass the latest browser security protections. [More info](https://www.bleepingcomputer.com/news/security/inside-the-remus-infostealer-session-theft-maas-and-rapid-evolution/)

- **"EvilTokens" Kit Spreads via Outlook Calendar Invites**: A novel "CalPhishing" technique utilizes a phishing kit called "EvilTokens" to send fake Outlook calendar notifications to Microsoft 365 users. The embedded links lead to highly convincing login interfaces designed to steal active session tokens rather than standard credentials, allowing attackers to completely bypass multifactor authentication. [More info](https://hackread.com/calphishing-eviltokens-kit-outlook-invites-m365/)

- **"ConsentFix v3" Automates OAuth Abuse at Scale**: Cybercriminals are turning to an automated tool named "ConsentFix v3" to abuse OAuth consent flows. The application automates the creation of malicious apps that trick users into granting permanent cloud environment permissions (e.g., Google or M365), allowing threat actors to retain access even if account passwords are reset. [More info](https://www.cysecurity.news/2026/05/automated-oauth-abuse-by-consentfix-v3.html)

## 💥 Breaches & Leaks

- **Grafana Labs Source Code Stolen Following Refused Ransom**: Grafana Labs confirmed a security incident involving the theft of several gigabytes of internal development repositories and secrets by the "RansomHub" ransomware group. Grafana refused to comply with extortion demands and confirmed that customer data and cloud environments remain isolated and unaffected. [More info](https://hackread.com/grafana-source-code-theft-rejected-ransom-demand/)

- **OpenAI Impacted by TanStack Package Supply Chain Attack**: OpenAI and at least one other major enterprise were impacted by a supply chain compromise involving malicious versions of popular TanStack packages uploaded to the npm registry. The contaminated packages contained obfuscated code designed to harvest developer environment variables and sensitive API keys. OpenAI responded by auditing internal dependency trees and rotating compromised credentials. [More info](https://securityaffairs.com/192222/hacking/openai-hit-by-supply-chain-attack-linked-to-malicious-tanstack-packages.html) | [More info](https://thehackernews.com/2026/05/tanstack-supply-chain-attack-hits-two.html)

- **Popular node-ipc npm Package Compromised**: In another software supply chain blow, recent versions of the popular `node-ipc` npm package were compromised to inject credential-stealing code. The malicious modifications targeted developers in specific geographic regions to overwrite local files and exfiltrate environment configurations. Malicious versions have since been purged by maintainers. [More info](https://www.bleepingcomputer.com/news/security/popular-node-ipc-npm-package-compromised-to-steal-credentials/)

---

[⬅ Back to Archive](https://pranakn.github.io)
