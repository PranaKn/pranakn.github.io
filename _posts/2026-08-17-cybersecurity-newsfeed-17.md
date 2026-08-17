---
title: "Cybersecurity Newsfeed - 17/08/26"
date: 2026-08-16 09:00:00 -0300
categories: [News]
permalink: /posts/news-17-08-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-08-17.png
  alt: Cybersecurity Newsfeed - 17/08/26
---

# Cybersecurity Newsfeed

## 📅 17/08/26

## 🛡️ Vulnerabilities

- **macOS Screen Sharing Exploited for Crypto Mining (CVE-2026-65400)**: Threat actors are actively exploiting a critical authentication flaw (CVSS 9.8) in native macOS Screen Sharing listening on TCP port 5900. Insufficient state management allows unauthenticated attackers to bypass login checks and gain root access, which is currently being leveraged to deploy Monero miners. [More info](https://securityaffairs.com/197234/uncategorized/macos-screen-sharing-flaw-exploited-to-deploy-monero-miners.html)

- **Max-Severity SAP Commerce Cloud RCE Targeted (CVE-2026-58231)**: Active exploitation attempts have been detected targeting a maximum-severity flaw (CVSS 10.0) in the Data Hub Adapter extension. Unauthenticated remote attackers can execute arbitrary code with low complexity. Immediate patching is recommended. [More info](https://www.bleepingcomputer.com/news/security/max-severity-sap-commerce-cloud-flaw-now-targeted-in-attacks/)

- **Unpatched GeoServer Zero-Day Exploited in the Wild**: Attackers began probing and exploiting an unpatched SQL injection weakness in GeoServer's `jsonArrayContains` filter function within hours of public disclosure. Under specific conditions, it can lead to remote code execution. [More info](https://www.securityweek.com/hackers-exploiting-unpatched-geoserver-zero-day/)

- **Spectre Side-Channel Attacks Hit Commercial RISC-V Chips**: Researchers demonstrated that out-of-order RISC-V processors (such as the SiFive P550 and Alibaba T-Head C910/C920) are vulnerable to Spectre variants, leaking kernel memory at rates up to 338 bytes/sec. Simple in-order cores remain unaffected. [More info](https://www.theregister.com/security/2026/08/12/spectre-rears-its-ugly-head-again-as-researchers-show-some-risc-v-chips-are-susceptible/5286978)

## 🎯 Adversaries

- **AmnesiaStealer macOS Malware Hijacks Browser Sessions**: Distributed via ClickFix lures on fake GitHub pages, AmnesiaStealer bypasses TCC protections and uses Chrome DevTools Protocol over WebSockets to clone browser profiles into headless instances, giving attackers live interactive remote control over authenticated sessions. [More info](https://www.bleepingcomputer.com/news/security/new-amnesiastealer-macos-malware-hijacks-browser-sessions-via-remote-control/) | [More info](https://www.infosecurity-magazine.com/news/macos-infostealer-spread-clickfix/)

- **APT36 Uses Google Sheets API for C2 in Espionage Campaign**: APT36 (Transparent Tribe) targeted South Asian infrastructure and Afghan telecom providers with the PATCHCORD backdoor and a Go-based backdoor named SHEETCORD, which abuses Google Sheets tabs for command-and-control operations. [More info](https://securityaffairs.com/197266/intelligence/apt36-suspected-in-patchcord-espionage-campaign-using-google-sheets-c2.html)

- **HoneyMyte (Mustang Panda) Deploys Kernel-Mode Driver Rootkit**: CoolClient backdoor updates reveal a signed driver (`msagent.sys`) that communicates via IOCTL requests, hiding processes, registry keys, and filtering network traffic via Nsiproxy hooks to evade detection. [More info](https://securelist.com/honeymyte-coolclient-driver-rootkit/121028/)

- **New Evooo1Bot Linux Botnet Relays Traffic**: Built on Mirai source code, Evooo1Bot targets routers and edge devices (NETGEAR, D-Link, Zyxel, Hikvision, TP-Link). It clears logs, establishes persistence via cron/systemd, and monetizes infections via a SOCKS5 proxy module. [More info](https://www.bleepingcomputer.com/news/security/new-evooo1bot-linux-botnet-turns-routers-into-traffic-relay-nodes/)

## 📈 Trends

- **Anthropic to Implement Generative Text Watermarking**: Anthropic plans to integrate invisible text watermarking across Claude models based on Google DeepMind's SynthID-Text framework to satisfy EU AI Act requirements, using a secret cryptographic key without sacrificing output quality. [More info](https://www.bleepingcomputer.com/news/meta/how-anthropic-plans-to-watermark-claudes-ai-generated-text/)

- **Rethinking Google Workspace Security: The OAuth Vector**: Security analysis demonstrates how modern attack chains are pivoting from traditional phishing to OAuth token abuse and improperly scoped AI integrations, bypassing MFA and password resets for persistent access. [More info](https://www.bleepingcomputer.com/news/security/the-modern-attack-chain-rethinking-google-workspace-security-in-the-age-of-ai/)

- **Apple Expands Mercenary Spyware Lock Screen Alerts**: Apple now delivers native on-device Lock Screen and Settings notifications to alert users targeted by state-sponsored commercial spyware campaigns, guiding them toward Lockdown Mode and software updates. [More info](https://www.malwarebytes.com/blog/news/2026/08/apple-now-uses-iphone-alerts-for-targets-of-mercenary-spyware)

## 💥 Breaches & Leaks

- **SafePal Data Breach Exposes 39,798 Customers**: A vulnerability in an order-tracking plug-in exposed customer shipping details, names, and purchase data for orders placed between March 2025 and April 2026. Seed phrases and private keys were not exposed. [More info](https://www.bleepingcomputer.com/news/security/safepal-data-breach-impacts-39-798-customers-stolen-info-for-sale/)

- **Scottish Prosecutors Office Exposes Data via Vendor**: A security incident at a third-party vendor conducting an online assessment exposed PII of approximately 300 Crown Office and Procurator Fiscal Service (COPFS) staff members. Case files were not affected. [More info](https://www.darkreading.com/cyberattacks-data-breaches/scottish-govt-data-breach-prosecutors-office)

- **Shell Investigates Potential Breach After Clop Claims**: Ransomware group Clop listed Shell on its dark web leak site, claiming data exfiltration via critical flaws in enterprise PTC Windchill and FlexPLM platforms (CVE-2026-12569). Shell is actively investigating. [More info](https://www.bleepingcomputer.com/news/security/shell-investigates-potential-incident-after-clop-data-theft-claims/)

- **ShinyHunters Exposes 1.6 Million RingCentral Records**: Following a refusal to pay ransom demands, ShinyHunters published 280GB of exfiltrated data containing customer names, emails, addresses, and phone numbers obtained via a July social engineering breach. [More info](https://www.bleepingcomputer.com/news/security/ringcentral-data-breach-exposed-info-of-16-million-accounts/)

- **AWS Key Exposure Leads to Beacon Charity Database Theft**: CRM vendor Beacon confirmed that an Amazon Web Services access key accidentally embedded in public JavaScript build artifacts allowed attackers to exfiltrate database records affecting over 1,500 UK nonprofits. [More info](https://www.theregister.com/security/2026/08/13/aws-key-exposed-in-javascript-may-have-lit-way-to-beacons-charity-data/5287303)

- **Uber Freight Targeted in Extortion Attempt**: Extortion group Helix listed Uber Freight on its portal, claiming data theft from OneDrive and email accounts. Uber Freight confirmed unauthorized system access but reported no operational disruptions to freight logistics. [More info](https://www.theregister.com/security/2026/08/12/uber-freight-keeps-on-trucking-after-extortion-crew-breaks-in/5286782)

## 📚 Others

- **Large-Scale DDoS Attacks Cause Disruption to Threema**: Volumetric DDoS attacks targeting Threema and its colocation provider caused connection outages for cloud-based secure messaging users. On-premise enterprise deployments remained unaffected. [More info](https://securityaffairs.com/197353/hacking/ddos-attacks-cause-major-threema-outages.html) | [More info](https://www.bleepingcomputer.com/news/security/large-scale-ddos-attacks-disrupted-threema-secure-messaging-service/)

- **Anthropic Services Suffer Major Outage**: Claude.ai, Claude Code, and Claude Cowork experienced widespread service outages and authentication failures, though developer Console and API endpoints remained functional. [More info](https://www.bleepingcomputer.com/news/artificial-intelligence/anthropic-confirms-claude-is-down-in-major-outage-affecting-multiple-services/)

- **Operation Klonen Tenders Arrests Over €30M German Banking Fraud**: Authorities in Brazil and Germany dismantled a cybercrime ring that exploited a third-party payment provider vulnerability serving Commerzbank to execute unauthorized direct debits. [More info](https://www.bleepingcomputer.com/news/security/hackers-arrested-over-30m-bank-fraud-exploiting-service-provider-flaw/)

- **Ukraine Shuts Down 94 Fraudulent Call Centers**: Ukrainian police seized thousands of devices and crypto assets across 400 searches, dismantling structured call center operations conducting bank impersonation and investment fraud. [More info](https://www.helpnetsecurity.com/2026/08/14/ukraine-fraudulent-call-centers-shut-down/)

---

[⬅ Back to Archive](https://pranakn.github.io)
