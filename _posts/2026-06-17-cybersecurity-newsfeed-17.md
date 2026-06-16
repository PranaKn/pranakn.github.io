---
title: "Cybersecurity Newsfeed - 17/06/26"
date: 2026-06-16 19:50:00 -0300
categories: [News]
permalink: /posts/news-17-06-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-06-17.png
  alt: Cybersecurity Newsfeed - 17/06/26
---

# Cybersecurity Newsfeed

## 📅 17/06/26

## 🛡️ Vulnerabilities

- **CISA Adds Widget Factory Joomla Flaw to KEV (CVE-2026-48907)**: CISA expanded its Known Exploited Vulnerabilities Catalog to include an improper access control flaw in the Widget Factory Joomla Content Editor. Remote actors can exploit it to bypass security mechanisms and gain unauthorized system access. Federal Civilian Executive Branch agencies must patch this under Binding Operational Directive 26-04. [More info](https://www.cisa.gov/news-events/alerts/2026/06/16/cisa-adds-one-known-exploited-vulnerability-catalog)

- **SimpleHelp RMM Critical Authentication Bypass (CVE-2026-48558)**: Discovered by Horizon3.ai using an autonomous AI vulnerability-hunting system, this flaw impacts SimpleHelp deployments configured with OpenID Connect authentication. Unauthenticated remote attackers can forge a "Technician" account and completely bypass mandatory MFA via self-registration on first login, allowing arbitrary script execution on managed endpoints. Patches were released in late May. [More info](https://www.helpnetsecurity.com/2026/06/16/simplehelp-rmm-cve-2026-48558/)

- **Google Vertex AI SDK "Pickle in the Middle" Hijacking**: Palo Alto Networks Unit 42 discovered a critical flaw in the Google Cloud Vertex AI SDK for Python that allowed attackers to hijack machine learning model uploads. The vulnerability stemmed from predictable, unverified staging bucket names generated from public project IDs. Attackers could preemptively create these buckets to swap legitimate files with malicious pickle payloads, achieving code execution inside Google's serving infrastructure. Google patched the flaw in version 1.148.0. [More info](https://thehackernews.com/2026/06/google-vertex-ai-sdk-flaw-let-attackers.html)

- **GhostTree Attack Evades EDR via Recursive Junction Loops**: A newly uncovered file system evasion technique exploits recursive NTFS junctions and symbolic links to render malware directories completely unscannable by security software without needing administrative privileges. By establishing a binary tree structure of looping junctions, a single executable can generate an exponential number of valid, distinct file paths, trapping EDR tools in infinite processing loops. [More info](https://www.bleepingcomputer.com/news/security/ghosttree-attack-abused-recursive-windows-junctions-to-hide-malware/)

## 🎯 Adversaries

- **FishMonger Deploys Kernel-Level SprySOCKS Windows Variant**: The China-nexus cyber-espionage group FishMonger (Earth Lusca) has expanded its cross-platform toolkit to deploy a highly evasive Windows variant of the SprySOCKS Linux backdoor. Actively deployed against government organizations in Taiwan, Thailand, Pakistan, and Honduras, the variant uses an encrypted driver loader signed with a leaked certificate to inject a secondary rootkit driver directly into system memory, hooking critical system calls to hide its activity from enterprise security software. [More info](https://www.darkreading.com/threat-intelligence/sprysocks-windows-variant-kernel-drivers) | [More info](https://www.bleepingcomputer.com/news/security/windows-version-of-sprysocks-linux-malware-used-to-attack-govt-orgs/)

- **DragonForce Hides C2 Traffic Inside Microsoft Teams relays**: The DragonForce ransomware group compromised a major US services firm by concealing its command-and-control traffic inside legitimate Microsoft Teams infrastructure. Utilizing a custom Go-based RAT called "Backdoor.Turn", the group hijacked temporary TURN protocol credentials to establish communication tunnels through trusted conferencing relays, blending in with outbound network traffic. The attackers combined this with Bring Your Own Vulnerable Driver (BYOVD) tactics to terminate endpoint security tools. [More info](https://www.infosecurity-magazine.com/news/dragonforce-ransomware-hidden/) | [More info](https://www.bleepingcomputer.com/news/security/ransomware-gang-abuses-microsoft-teams-relays-to-hide-malicious-traffic/)

- **Rokarolla Android Trojan Targets 217 Banking & Crypto Apps**: Discovered by Zimperium zLabs, Rokarolla is a highly invasive Android banking trojan that shifts the mobile threat paradigm toward full device isolation and remote surveillance. Distributed via fake TikTok or Chrome updates, its dropper abuses Accessibility Services to monitor screens. It leverages 137 commands to display deceptive screen overlays over legitimate financial apps, log keys, hijack clipboards, intercept SMS/MFA codes, and operate in total silence by blocking banking calls and suppressing system audio. [More info](https://www.bleepingcomputer.com/news/security/new-rokarolla-android-malware-targets-217-banking-crypto-apps/) | [More info](https://www.darkreading.com/endpoint-security/rokarolla-android-trojan) | [More info](https://hackread.com/rokarolla-android-trojan-crypto-and-banking-apps/) | [More info](https://www.infosecurity-magazine.com/news/rokarolla-android-banking-trojan/)

- **Fileless "Phantom Stealer" Targets Financial Institutions**: Discovered by Fortra, Phantom Stealer is a sophisticated malware-as-a-service campaign that runs entirely in memory to evade signature-based defenses. Distributed via phishing emails disguised as business documents, the infection chain utilizes obfuscated batch files, PowerShell commands, and Base64-XOR encoding to inject payloads directly into the legitimate Windows Explorer process, exfiltrating credentials through four parallel channels (Telegram, Discord, FTP, and SMTP). [More info](https://www.darkreading.com/cyberattacks-data-breaches/fileless-phantom-stealer-targets-browser-credentials)

- **Amos Stealer Targets macOS via Native Utility Abuse**: Deployed in financially motivated campaigns detailed by CyberProof, Amos Stealer is targeting macOS systems through deceptive software downloads. The malware utilizes the native macOS utility `curl` with hidden flags to silently download malicious scripts without triggering error alerts. Once inside, it extracts browser credentials, copies the macOS Keychain database, compresses them using the native `ditto` tool, and exfiltrates the archive before erasing its footprint. [More info](https://hackread.com/amos-stealer-macos-keychain-files-browser-passwords/)

- **ClickFix Campaigns Expand Modular Malware Loaders**: ClickFix social engineering campaigns have been detected distributing three highly evasive malware loaders: BabaDeda, Lorem Ipsum, and Potemkin. Relying on fake browser and security update lures on compromised WordPress sites, they convince users to run malicious PowerShell commands. These frameworks utilize in-memory shellcode, DLL side-loading, and encrypted containers to profile victim environments and deploy secondary payloads like Rhysida ransomware. This shift follows Microsoft's disruption of Fox Tempest, which revoked over 1,000 fraudulent code-signing certificates previously used in trojanized Microsoft Teams installers. [More info](https://thehackernews.com/2026/06/clickfix-campaigns-expand-malware.html) | [More info](https://www.darkreading.com/cyberattacks-data-breaches/lorem-ipsum-malware-clickfix-delivery)

- **EvilTokens Phishing-as-a-Service Kit Subverts OAuth Flow**: Documented by ESET and Sekoia, the EvilTokens toolkit targets Microsoft 365 environments by subverting the legitimate OAuth 2.0 device authorization grant flow. Bypassing traditional defenses, it eliminates the need for fake login pages by displaying a decoy page that requests a device code, tricking victims into completing a legitimate authentication challenge on Microsoft's official portal to issue valid access tokens directly to the attacker. [More info](https://www.welivesecurity.com/en/cybercrime/eviltokens-phishing-doesnt-steal-password/)

- **Steam Workshop Abused via Wallpaper Engine App**: Valve's Steam Workshop is being actively abused by threat actors to distribute malware disguised as custom application wallpapers for the popular Wallpaper Engine software. Discovered by Kaspersky, the campaign exploits a built-in feature permitting wallpapers to run as active Windows executables. Attackers bundle various payloads—including DarkKomet backdoors, Lumma and Vidar infostealers, cryptominers, and ransomware—directly into the packages. [More info](https://www.bleepingcomputer.com/news/security/steam-workshop-abused-to-spread-malware-via-wallpaper-engine-app/)

## 📈 Trends

- **Athena Coalition Launched to Combat AI-Driven Exploitation**: Over two dozen prominent technology and fintech organizations have launched a shared defense coalition named Athena. Formed in response to frontier AI models capable of identifying and chaining complex software flaws at machine speed, the coalition pools pre-disclosure vulnerability findings and correlates defensive telemetry. Managed through Chainguard Libraries, it coordinates immediate virtual patching and signatures to protect open-source libraries. [More info](https://www.securityweek.com/tech-coalition-athena-targets-oss-vulnerabilities-ahead-of-disclosure/)

- **Security Community Slams US Export Ban on Frontier AI Models**: The cybersecurity community has issued a joint open letter criticizing the United States government's sudden export restriction on Anthropic's newly launched Claude Fable 5 and Mythos 5 models. Experts warn that restricting foreign nationals from accessing the technology due to national security concerns regarding exploit chain discovery harms defensive capabilities significantly, arguing that geopolitical adversaries already possess equivalent capabilities. [More info](https://www.darkreading.com/vulnerabilities-threats/security-community-slams-us-ban-on-exporting-mythos-fable)

## 💥 Breaches & Leaks

- **Malicious JetBrains Marketplace Plugins Harvest AI API Keys**: Uncovered by Aikido Security, at least 15 malicious plugins discovered on the JetBrains Marketplace (including DeepSeek AI Assist and CodeGPT AI Assistant) have been found stealing AI API keys from developers, affecting nearly 70,000 installations. The malicious code transmits stored API keys via HTTP to an attacker-controlled server whenever a developer saves their settings, harvesting keys from OpenAI, DeepSeek, and SiliconFlow services. [More info](https://www.bleepingcomputer.com/news/security/malicious-jetbrains-marketplace-plugins-steal-ai-api-keys-from-developers/)

- **Atomic Arch Supply Chain Attack Hits 1,500+ AUR Packages**: Arch Linux has suspended new account registrations on the community-driven Arch User Repository following an extensive supply chain campaign tracked as Atomic Arch. Discovered by Sonatype, attackers compromised more than 1,500 packages by targeting abandoned, orphaned build scripts. The rootkit-like malware references extended Berkeley Packet Filter (eBPF) technology to achieve advanced kernel-level persistence for credential harvesting and secret exfiltration. [More info](https://www.securityweek.com/atomic-arch-supply-chain-attack-hits-1500-aur-packages/)

---

[⬅ Back to Archive](https://pranakn.github.io)
