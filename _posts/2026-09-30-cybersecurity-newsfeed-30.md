---
title: "Cybersecurity Newsfeed - 30/09/26"
date: 2026-09-29 09:00:00 -0300
categories: [News]
permalink: /posts/news-30-09-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-09-30.png
  alt: Cybersecurity Newsfeed - 30/09/26
---

# Cybersecurity Newsfeed

## 📅 30/09/26

## 🛡️ Vulnerabilities

- **Apple CoreGraphics Zero-Day Exploited in Targeted Attacks**: Apple released urgent security updates to address an actively exploited out-of-bounds write flaw in CoreGraphics. Processing maliciously crafted images allows arbitrary code execution on vulnerable iOS, iPadOS, and macOS devices. [More info](https://www.darkreading.com/cyberattacks-data-breaches/apple-zero-day-vulnerability-weaponized-targeted-attacks) | [More info](https://securityaffairs.com/200001/hacking/apple-patches-coregraphics-zero-day-linked-to-sophisticated-targeted-attacks.html) | [More info](https://www.theregister.com/security/2026/09/29/apple-patches-coregraphics-zero-day-already-exploited-in-targeted-attacks/5299721) | [More info](https://www.bleepingcomputer.com/news/security/apple-patches-coregraphics-zero-day-flaw-exploited-in-attacks/)

- **CISA Adds Apple Flaw (CVE-2026-86950) to KEV Catalog**: CISA added CVE-2026-86950, an out-of-bounds write flaw affecting iOS, iPadOS, macOS, watchOS, and tvOS, to its Known Exploited Vulnerabilities Catalog. Federal agencies must patch promptly to mitigate remote code execution risks. [More info](https://www.cisa.gov/news-events/alerts/2026/09/29/cisa-adds-one-known-exploited-vulnerability-catalog)

- **Citrix NetScaler Zero-Day Exploited for Web Shell Deployment**: Threat actors are exploiting an unauthenticated remote code execution zero-day vulnerability in Citrix NetScaler ADC and Gateway appliances to deploy persistent web shells, harvest credentials, and perform lateral movement. [More info](https://www.bleepingcomputer.com/news/security/hackers-exploit-citrix-netscaler-zero-day-to-deploy-web-shells/)

- **New Spectre v2 Variant Leaks Linux Root Password Hashes**: Researchers disclosed a new Spectre v2 speculative execution attack variant capable of extracting kernel memory contents—including root password hashes—within minutes via microarchitectural timing side channels. [More info](https://www.bleepingcomputer.com/news/security/new-spectre-v2-attack-variant-leaks-linux-root-password-hash-in-minutes/)

- **Kiteworks Patches Critical Remote Code Execution Flaw**: Kiteworks lifted its temporary shutdown advisory after issuing security patches for a critical vulnerability in its secure file transfer platform that allowed unauthenticated remote code execution. [More info](https://thehackernews.com/2026/09/kiteworks-fixes-critical-flaw-found.html) | [More info](https://www.infosecurity-magazine.com/news/kiteworks-customers-restart/) | [More info](https://www.bleepingcomputer.com/news/security/kiteworks-lifts-shutdown-warning-after-patching-critical-flaw/)

## 🎯 Adversaries

- **Phishing Abuses RMM Tools for Persistent Access**: Microsoft Security detailed how threat actors exploit legitimate remote monitoring and management tools like AnyDesk, ScreenConnect, and Atera to maintain persistent network access and bypass security controls. [More info](https://www.microsoft.com/en-us/security/blog/2026/09/29/phishing-abuses-rmm-tools-persistent-access/)

- **Custom ChatGPTs Push ClickFix Attacks to Deploy RAT Malware**: Cybercriminals are leveraging custom ChatGPT instances in ClickFix social engineering campaigns, prompting users to run obfuscated terminal commands that download remote access trojans and infostealers. [More info](https://www.bleepingcomputer.com/news/security/custom-chatgpts-push-clickfix-attacks-to-deploy-rat-malware/) | [More info](https://www.helpnetsecurity.com/2026/09/29/malicious-chatgpt-custom-gpt-malware-via-clickfix/)

- **Automated AI Agent Breaches Cybersecurity Nonprofit DIVD**: An autonomous AI agent exploited exposed configuration flaws to breach internal networks of the Dutch Institute for Vulnerability Disclosure (DIVD), gaining administrative privileges without human intervention. [More info](https://www.bleepingcomputer.com/news/security/automated-ai-agent-used-to-breach-cybersecurity-nonprofit-divd/)

- **101 Malicious npm Packages Target Developer Credentials**: Security researchers uncovered 101 typosquatted npm packages that execute malicious installation scripts to steal API keys, SSH credentials, and environment variables from developer workstations. [More info](https://thehackernews.com/2026/09/101-malicious-npm-packages-add.html)

- **NeedyMantis Malware Expands to Cloud & Hybrid Environments**: The NeedyMantis campaign updated its post-exploitation framework with new modules targeting Active Directory and enterprise cloud infrastructure for credential harvesting and lateral movement. [More info](https://www.cysecurity.news/2026/09/needymantis-malware-expands-post.html)

- **JadePuffer Hijacks Azure Identities for Resource Abuse**: Threat actors compromised Azure enterprise credentials to spin up high-performance virtual machines for unauthorized cryptocurrency mining, leading to severe cloud utility costs for victim organizations. [More info](https://www.theregister.com/security/2026/09/28/jadepuffer-crims-hijacked-azure-identities-and-used-them-to-blow-up-cloud-resources/5299591)

## 📈 Trends

- **Self-Replicating Prompt Injection Attacks Threaten AI Workflows**: Researchers warned of self-propagating prompt injection vulnerabilities in LLM agents, which allow hidden malicious instructions in text or web content to hijack AI workflows and spread autonomously across tools. [More info](https://www.theregister.com/security/2026/09/29/add-one-more-ai-worry-to-the-nightmare-scenario-self-replicating-prompt-injections/5299922)

- **Signal Adds Encrypted Local Backup Support to iOS and Desktop**: Signal introduced end-to-end encrypted local database backups for iOS and desktop apps, providing user-controlled message history and media recovery independent of cloud infrastructure. [More info](https://www.bleepingcomputer.com/news/security/signal-adds-encypted-local-backup-support-to-ios-desktop-apps/)

- **Windows 11 2026 Update Introduces Advanced AI Security**: Microsoft released the Windows 11 2026 Update, featuring smart application control, hardened credential isolation, and refined memory protection defaults to defend against zero-day exploits. [More info](https://www.bleepingcomputer.com/news/microsoft/windows-11-2026-update-released-heres-everything-you-need-to-know/)

- **RemoteThreat Launches Offensive Operations Platform**: Security startup RemoteThreat secured $7 million in funding to build an automated platform that continuously simulates adversary tactics and identifies network misconfigurations. [More info](https://www.securityweek.com/remotethreat-launches-with-7-million-for-offensive-operations-platform/)

## 💥 Breaches & Leaks

- **French Tax Authorities Suffer Data Breach via Stolen Credentials**: Cybercriminals used compromised administrative credentials to gain unauthorized access to French tax authority systems, exfiltrating personal identities, tax IDs, and income records. [More info](https://thehackernews.com/2026/09/french-tax-data-theft-using-stolen.html)

## 📚 Others

- **FBI Warns ShinyHunters Members Following Operative Arrest**: The FBI urged remaining members of the ShinyHunters cybercrime group to surrender following a major operative arrest, warning of intensified global law enforcement operations. [More info](https://www.bleepingcomputer.com/news/security/fbi-tells-shinyhunters-members-to-turn-themselves-in-after-recent-arrest/)

- **Former U.S. Air Force Members Sentenced for BEC Attacks**: Two former Air Force personnel were sentenced to prison for executing business email compromise (BEC) schemes targeting government contractors and laundering millions in illicit funds. [More info](https://www.bleepingcomputer.com/news/security/former-us-air-force-members-sent-to-prison-over-bec-attacks/)

- **Vietnamese National Charged in $16M Pig Butchering Crypto Scam**: Federal prosecutors charged a Vietnamese national for operating a global $16 million romance-based investment scam that laundered funds through cryptocurrency networks. [More info](https://www.bleepingcomputer.com/news/security/vietnamese-man-charged-in-16-million-pig-butchering-crypto-scam/)

---

[⬅ Back to Archive](https://pranakn.github.io)
