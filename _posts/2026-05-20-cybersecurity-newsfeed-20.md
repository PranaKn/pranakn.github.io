---
title: "Cybersecurity Newsfeed - 20/05/26"
date: 2026-05-19 17:35:00 -0300
categories: [News]
permalink: /posts/news-20-05-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-05-20.png
  alt: Cybersecurity Newsfeed - 20/05/26
---

# Cybersecurity Newsfeed

## 📅 20/05/26

## 🛡️ Vulnerabilities

- **Cisco Talos Discloses 11 Flaws Across Multiple Vendors**: Researchers disclosed eleven vulnerabilities impacting TP-Link, Adobe, OpenVPN, and Gen Digital. Highlights include a critical stack-based buffer overflow (CVE-2026-30814) and OS command injection flaws in the TP-Link Archer AX53 router, local privilege escalation in Adobe Photoshop (CVE-2026-34632) and Norton Secure VPN (CVE-2025-58074), and a DoS vulnerability in OpenVPN 2.6.x (CVE-2026-35058). [More info](https://blog.talosintelligence.com/tp-link-photoshop-openvpn-norton-vpn-vulnerabilities/)

- **"DirtyDecrypt" PoC Exploits Linux Kernel (CVE-2026-31635)**: A proof-of-concept exploit has been released for a local privilege escalation flaw in the Linux kernel's `rxgk_decrypt_skb` function. Lacking a copy-on-write (COW) guard, it allows unprivileged users to write data into privileged memory or the page cache of sensitive files like `/etc/shadow`, leading to full root compromise on affected distributions like Fedora and Arch Linux. [More info](https://thehackernews.com/2026/05/dirtydecrypt-poc-released-for-linux.html)

- **Unpatched ChromaDB RCE Vulnerability**: An unpatched flaw stemming from improper input validation in the API endpoint of ChromaDB—a popular vector database for AI applications—allows for complete server takeover. Unauthenticated attackers can perform Remote Code Execution (RCE), creating a systemic risk for the AI supply chain by potentially manipulating training data or exfiltrating proprietary model weights. [More info](https://www.securityweek.com/unpatched-chromadb-vulnerability-can-lead-to-server-takeover/)

- **"NGINX Rift" Vulnerability Chain Enables RCE (CVE-2026-42945)**: Researchers disclosed a critical four-vulnerability chain allowing unauthenticated Remote Code Execution (RCE) on NGINX servers. The most severe flaw involves a long-standing heap buffer overflow in the script engine (present since 2008), which can be triggered by common configuration patterns involving rewrite and set directives. [More info](https://hackread.com/hackers-exploit-nginx-rift-vulnerability-nginx-f5-products/)

- **SEPPmail Secure E-Mail Gateway Vulnerabilities**: Multiple vulnerabilities have been identified in the SEPPmail Secure E-Mail Gateway that could allow attackers to bypass encryption or gain administrative access. The flaws include improper session management and insecure default configurations that expose sensitive cryptographic keys. [More info](https://thehackernews.com/2026/05/seppmail-secure-e-mail-gateway.html)

- **Critical Flaw Threatens Universal Robots' Fleets (CVE-2026-8153)**: A critical OS command injection vulnerability rated 9.8 on the CVSS scale has been identified in Universal Robots' PolyScope 5 operating system. The flaw allows unauthenticated network attackers to execute arbitrary commands via the Dashboard Server interface, exposing industrial cobot fleets to hacking and physical operational shutdowns. [More info](https://www.securityweek.com/critical-vulnerability-exposes-industrial-robot-fleets-to-hacking/)

- **"Claw Chain" Vulnerabilities Flaw in OpenClaw (CVE-2026-44112 to CVE-2026-44118)**: Security researchers have identified a series of four critical vulnerabilities involving race conditions and improper access controls in the OpenClaw agent platform. When chained, they allow attackers to bypass sandboxes, exfiltrate credentials, and achieve persistent root access. [More info](https://www.darkreading.com/application-security/claw-chain-vulnerabilities-threaten-openclaw)

## 🎯 Adversaries

- **Storm-2949 Abuses SSPR in Azure Data Theft Attacks**: Microsoft identified a cloud data theft campaign where the threat cluster Storm-2949 targeted Entra ID and Azure infrastructure. Attackers systematically abused the Self-Service Password Reset (SSPR) mechanism alongside IT-support social engineering to manipulate victims into approving fraudulent MFA prompts, ultimately escalating privileges to exfiltrate database keys and secrets. [More info](https://www.bleepingcomputer.com/news/security/microsoft-self-service-password-reset-abused-in-azure-data-theft-attacks/)

- **SHub Reaper macOS Malware Evades Defenses**: Threat actors are actively distributing a sophisticated macOS infostealer and backdoor named SHub Reaper via trojanized WeChat and Miro installers. The malware abuses the `applescript://` URL scheme to execute payloads via the native Script Editor, successfully bypassing Apple's Terminal protections and XProtect detection to exfiltrate credentials and crypto wallets. [More info](https://www.darkreading.com/threat-intelligence/stealer-spoofs-google-microsoft-apple-backdoors-macos) | [More info](https://www.helpnetsecurity.com/2026/05/19/shub-reaper-macos-infostealer-apple-google-microsoft/)

- **Microsoft Dismantles MSaaS Network "Fox Tempest"**: Microsoft's Digital Crimes Unit successfully disrupted Fox Tempest, a massive malware-signing-as-a-service (MSaaS) operation. The actor abused Microsoft's Artifact Signing and Azure infrastructure to issue over 1,000 fraudulent code-signing certificates, making malicious software like Rhysida ransomware and Lumma Stealer appear legitimate. [More info](https://securityaffairs.com/192391/cyber-crime/microsoft-dismantled-malware-signing-network-fox-tempest.html)

- **Trapdoor Android Ad Fraud Scheme Disrupted**: A sophisticated Android ad fraud and malvertising campaign named Trapdoor has been taken down after compromising 455 utility applications and generating up to 659 million daily ad bid requests. The operation infected over 24 million devices and evaded detection by using install attribution software to hide its malicious payload from organic users and researchers. [More info](https://thehackernews.com/2026/05/trapdoor-android-ad-fraud-scheme-hit.html)

- **"Shai-Hulud" Wave Compromises 600 npm Packages**: A new software supply chain attack has targeted the npm registry using dependency confusion and typosquatting to infiltrate developer environments. Once active within CI/CD pipelines, Shai-Hulud executes obfuscated scripts to exfiltrate environment variables, SSH keys, and cloud credentials. [More info](https://www.bleepingcomputer.com/news/security/new-shai-hulud-malware-wave-compromises-600-npm-packages/)

- **PureLogs Infostealer Deployed via Steganography**: Cybercriminals are distributing the PureLogs info-stealer by hiding malicious code within seemingly benign image files to bypass email filters and endpoint detection systems. Once opened, a secondary loader extracts and executes the stealer to target browser data, crypto wallets, and session cookies. [More info](https://www.helpnetsecurity.com/2026/05/19/purelogs-infostealer-delivery-steganography/)

- **"The New Phishing Click" Exploits OAuth 2.0**: A new phishing technique leverages the OAuth 2.0 protocol to hijack cloud user sessions without requiring traditional password theft. By tricking users into approving extensive permissions for malicious apps, attackers acquire access tokens that grant persistent access to email and cloud storage while completely bypassing MFA. [More info](https://thehackernews.com/2026/05/the-new-phishing-click-how-oauth.html)

## 📈 Trends

- **Critical Microsoft Vulnerabilities Doubled Year-Over-Year**: The 2026 Microsoft Vulnerabilities Report reveals that while total CVEs remained stable, critical vulnerabilities doubled to 157. Attackers are shifting strategic focus toward Elevation of Privilege and Information Disclosure within Azure, Dynamics 365, and Microsoft Office to quietly collapse identity boundaries. [More info](https://www.bleepingcomputer.com/news/security/critical-microsoft-vulnerabilities-doubled-from-exposure-to-escalation/)

- **Two-Thirds of Non-Human Accounts Left Unmanaged**: Orchid Security's Identity Gap Report highlights a massive enterprise blind spot: two-thirds of non-human accounts—such as service accounts, API keys, and bots—remain completely unseen and unmanaged, creating an expansive attack surface lacking MFA that is ripe for lateral movement. [More info](https://hackread.com/two-thirds-of-nonhuman-accounts-are-unseen-and-unmanaged-according-to-orchid-securitys-identity-gap-report/)

- **Microsoft Blames Incessant Teams Location Prompts on macOS Update**: Microsoft acknowledged a disruptive issue where macOS users face persistent, undismissible location prompts within Teams. The problem stems from a recent macOS security update failing to properly store user permission selections, causing the operating system to repeatedly request access for GPS and Wi-Fi data. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-blames-undismissible-teams-location-prompts-on-macos-update/)

## 💥 Breaches & Leaks

- **Public CISA GitHub Repository Exposed Internal Credentials**: Security researchers discovered an unsecured public GitHub repository belonging to the Cybersecurity and Infrastructure Security Agency (CISA) that exposed 844MB of internal data. Named "Private-CISA," the repository had been accessible since November 2025 and contained plain-text passwords, authentication tokens, SAML certificates, and Kubernetes manifests. [More info](https://www.darkreading.com/cybersecurity-operations/cisa-exposes-secrets-credentials-private-repo)

- **7-Eleven Breached; ShinyHunters Demands Ransom for Salesforce Records**: 7-Eleven has confirmed a data breach after the ShinyHunters hacker group claimed to have exfiltrated over 600,000 Salesforce records containing franchisee documents and personal information. The attackers are threatening to leak the corporate instances unless a $250,000 ransom is paid. [More info](https://www.bleepingcomputer.com/news/security/7-eleven-confirms-data-breach-claimed-by-the-shinyhunters-gang/)

## 📚 Others

- **Interpol "Operation Ramz" Seizes 53 Malware and Phishing Servers**: Interpol's four-month operation across the MENA region concluded with the arrest of 201 individuals and the seizure of 53 infrastructure servers. The operation successfully neutralized malicious infrastructure and dismantled a prominent "phishing-as-a-service" platform in Algeria. [More info](https://www.bleepingcomputer.com/news/security/interpol-operation-ramz-seizes-53-malware-phishing-servers/)

---

[⬅ Back to Archive](https://pranakn.github.io)
