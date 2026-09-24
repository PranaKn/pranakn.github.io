---
title: "Cybersecurity Newsfeed - 25/09/26"
date: 2026-09-24 09:00:00 -0300
categories: [News]
permalink: /posts/news-25-09-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-09-25.png
  alt: Cybersecurity Newsfeed - 25/09/26
---

# Cybersecurity Newsfeed

## 📅 25/09/26

## 🛡️ Vulnerabilities

- **CISA Adds Two Known Exploited Vulnerabilities to Catalog**: CISA added CVE-2026-5430 (path traversal in WSO2 products) and CVE-2026-71362 (incorrect authorization in Adobe Commerce/Magento) to its KEV catalog. Federal agencies must remediate these actively exploited flaws per BOD 26-04. [More info](https://www.cisa.gov/news-events/alerts/2026/09/24/cisa-adds-two-known-exploited-vulnerabilities-catalog)

- **Unpatched OnePlus Flaws Let Installed Apps Escalate Privileges**: Security researchers discovered unpatched vulnerabilities in pre-installed OnePlus system applications, allowing low-privilege Android apps to execute unauthorized system calls and escalate privileges. [More info](https://thehackernews.com/2026/09/unpatched-oneplus-flaws-let-installed.html)

- **Exposed GitLab Project Email Addresses Let Attackers Push Code**: A flaw in GitLab repository settings exposes internal commit email addresses, allowing threat actors to spoof trusted committers, bypass branch protection, and push unauthorized code. [More info](https://www.bleepingcomputer.com/news/security/exposed-gitlab-project-email-addresses-let-attackers-push-code/)

- **Decades-Old File Security Flaws Found in Android, Linux, macOS, and Windows**: A fundamental path validation design flaw affecting major operating systems allows path traversal, sandbox bypasses, and arbitrary code execution when handling specific reserved filenames. [More info](https://www.theregister.com/security/2026/09/24/decades-old-file-security-flaws-found-in-android-linux-macos-and-windows/5298672)

- **Critical Roundcube Flaw Now Actively Exploited in Code Injection Attacks**: A critical code injection flaw in Roundcube webmail is being actively exploited via crafted emails containing JavaScript, allowing full control over target email sessions. [More info](https://www.bleepingcomputer.com/news/security/critical-roundcube-flaw-now-actively-exploited-in-code-injection-attacks/)

- **Prompt-Injection Bug Hits Agentic AI App Manus**: An indirect prompt-injection vulnerability in autonomous AI app Manus enables attackers to bypass security filters via JSFuck obfuscation and execute code to exfiltrate connected service tokens. [More info](https://www.darkreading.com/application-security/prompt-injection-bug-agentic-ai-app-manus)

- **CISA Warns Ransomware Gangs Are Exploiting Critical TeamCity Flaw**: Ransomware actors are actively exploiting a critical authentication bypass in JetBrains TeamCity servers to create admin accounts and deploy ransomware payloads. [More info](https://www.bleepingcomputer.com/news/security/cisa-ransomware-gangs-now-exploiting-critical-teamcity-flaw/)

- **Ubuntu Releases Patch Schedule for Ubuntu Kernel CVE Vulnerabilities**: Canonical published a maintenance release schedule addressing privilege escalation, DoS, and memory corruption kernel vulnerabilities across supported Ubuntu versions. [More info](https://www.helpnetsecurity.com/2026/09/24/ubuntu-kernel-cve-fixes-release-schedule/)

## 🎯 Adversaries

- **MacSync Malware Uses Public iCloud Calendars to Deliver New Payloads**: MacSync leverages public iCloud calendar event subscriptions as a resilient C2 mechanism to deliver secondary payloads and bypass standard web filtering. [More info](https://www.bleepingcomputer.com/news/security/macsync-malware-uses-public-icloud-calendars-to-deliver-new-payloads/)

- **SectopRAT Returns, Hiding Inside Legitimate Application**: A revised variant of SectopRAT is being packed inside trusted software installers to execute in memory, establish remote access, and steal host credentials. [More info](https://www.darkreading.com/cyberattacks-data-breaches/sectoprat-returns-hiding-inside-legitimate-application)

- **New Carbonato Malware Uses AI Agents to Hijack Exposed Docker Hosts**: The Carbonato campaign targets publicly accessible Docker Engine APIs, using embedded AI agents to survey environments, construct evasion scripts, and deploy cryptominers. [More info](https://www.bleepingcomputer.com/news/security/new-carbonato-malware-uses-ai-agents-to-hijack-exposed-docker-hosts/)

- **Hacked Ukrainian Sites Serve Fake Software Updates Carrying Malware**: Compromised Ukrainian websites are delivering drive-by downloads via fake update notifications to distribute RATs and infostealers in watering-hole attacks. [More info](https://thehackernews.com/2026/09/hacked-ukreadable-sites-serve-fake.html)

- **Corporate MDM Spyware Targets Logistics Sector Operations**: A targeted campaign tricks logistics workers into installing rogue Mobile Device Management (MDM) profiles, enabling attackers to intercept communications and track endpoints. [More info](https://thehackernews.com/2026/09/corp-mdm-spyware-targets-logistics.html)

- **RemControl Android Banking Trojan Disguised as Fake TV App**: The RemControl trojan spreads through fake streaming apps, abusing Android Accessibility Services to log keystrokes, intercept MFA tokens, and steal banking credentials. [More info](https://www.helpnetsecurity.com/2026/09/24/remcontrol-android-banking-trojan-fake-tv-app/)

- **Malicious npm Packages Evade Defensive Analysis Controls**: Threat actors are publishing obfuscated npm packages with dynamic payload execution that detect sandbox environments before stealing developer credentials and API keys. [More info](https://www.schneier.com/blog/archives/2026/09/malicious-npm-packages-that-evade-defenses.html)

- **Updated MacSync Variant Enhances Evasion Capabilities**: An updated variant of MacSync features anti-analysis capabilities, inspecting sandbox parameters and terminating security processes prior to exfiltrating browser and wallet data. [More info](https://securelist.com/macsync-new-version/121383/)

- **TeamFiltration Framework Compromises Corporate Environments**: Attackers are using the TeamFiltration framework to automate password spraying and data exfiltration against M365 environments, leading to tenant compromises. [More info](https://thehackernews.com/2026/09/teamfiltration-compromises-seven.html)

- **Placeholder Domain in Developer Docs Repurposed for ClickFix Attacks**: Attackers registered an expired domain referenced in developer documentation to host ClickFix social engineering attacks that trick users into pasting malicious scripts into terminals. [More info](https://www.bleepingcomputer.com/news/security/placeholder-domain-used-in-dev-docs-now-serves-clickfix-attacks/)

## 📈 Trends

- **OAuth Phishing Attacks Bypass Passwords and Multi-Factor Authentication**: Attackers are deploying OAuth consent phishing campaigns to trick users into authorizing rogue third-party apps, securing persistent API access without triggering MFA. [More info](https://www.cysecurity.news/2026/09/oauth-phishing-attacks-bypass-passwords.html)

- **Google Assures Critical Infrastructure Organizations Over AI Security Scanners**: Google outlined encryption boundaries and safeguards for its automated AI safety scanners to reassure critical infrastructure operators regarding proprietary data privacy. [More info](https://www.theregister.com/security/2026/09/24/google-to-critical-infra-orgs-our-ai-scanners-wont-be-evil-promise/5298685)

- **New Browser Guard Features Add Protection Before and After You Click**: Malwarebytes updated Browser Guard with pre- and post-click detection mechanisms, behavioral monitoring, and script-blocking to stop web threats. [More info](https://www.malwarebytes.com/blog/product/2026/09/new-browser-guard-features-add-protection-before-and-after-you-click)

- **Secrets Sprawl Highlights Growing Enterprise Identity Challenges**: Unmanaged API keys and hardcoded credentials in repositories continue to expose organizations to lateral movement, highlighting the need for automated detection and short-lived tokens. [More info](https://thehackernews.com/2026/09/secrets-sprawl-is-identity-problem-that.html)

## 📚 Others

- **Microsoft Resolves Windows Backup Issues Caused by September Updates**: Microsoft issued an out-of-band update resolving a Windows Backup feature bug introduced during the September update cycle. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-fixes-windows-backup-feature-broken-by-september-updates/)

---

[⬅ Back to Archive](https://pranakn.github.io)
