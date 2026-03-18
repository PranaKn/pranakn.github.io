---
title: "Cybersecurity Newsfeed - 19/03/26"
date: 2026-03-18 09:00:00 -0300
categories: [News]
permalink: /posts/news-19-03/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-03-19.png
  alt: Cybersecurity Newsfeed - 19/03/26
---

# Cybersecurity Newsfeed

## 📅 19/03/26

## 🛡️ Vulnerabilities

- **CISA Updates KEV Catalog**: CISA added a critical vulnerability to its Known Exploited Vulnerabilities (KEV) catalog, signaling active exploitation in the wild. Federal agencies are mandated to remediate this flaw to mitigate risks of unauthorized access or RCE. [More info](https://www.cisa.gov/news-events/alerts/2026/03/18/cisa-adds-one-known-exploited-vulnerability-catalog-0)

- **ConnectWise ScreenConnect Hijacking Flaw**: Critical security patches address a vulnerability in ScreenConnect that could allow attackers to bypass authentication and hijack active sessions, granting administrative control over managed endpoints. [More info](https://www.bleepingcomputer.com/news/security/connectwise-patches-new-flaw-allowing-screenconnect-hijacking/)

- **CVE-2025-66376 Exploitation**: CISA documented the active exploitation of this critical flaw impacting enterprise systems. It allows for significant privilege escalation and deep persistence within target networks. [More info](https://www.cisa.gov/known-exploited-vulnerabilities-catalog?search_api_fulltext=CVE-2025-66376)

- **Ubuntu Local Privilege Escalation**: A flaw in the system's handling of specific kernel modules enables local users to gain root-level access by manipulating system memory. [More info](https://www.infosecurity-magazine.com/news/ubuntu-flaw-enables-root-access/)

- **Unpatched Telnetd Critical Flaw**: Researchers warn of an unpatched vulnerability affecting all versions of the telnetd daemon. It allows for remote code execution without authentication, posing risks to legacy industrial and IoT systems. [More info](https://securityaffairs.com/189620/hacking/researchers-warn-of-unpatched-critical-telnetd-flaw-affecting-all-versions.html)

- **Apple Patches WebKit Cross-Origin Bug (CVE-2026-20643)**: Apple released a "Background Security Improvement" for iOS and macOS to address a flaw in the Navigation API that could allow malicious sites to bypass the same-origin policy. [More info](https://www.malwarebytes.com/blog/news/2026/03/apple-patches-webkit-bug-that-could-let-sites-access-your-data)

## 🎯 Adversaries

- **Claudy Day Malvertising Campaign**: Attackers are using fraudulent Claude AI advertisements on Google and social media to lure users into downloading installers bundled with info-stealing malware. [More info](https://hackread.com/claudy-day-flaws-data-theft-fake-claude-ai-ads/)

- **Interlock Ransomware Targets Cisco FMC**: The group has been exploiting a zero-day vulnerability in Cisco Firepower Management Center since January to gain unauthorized access and disable security controls. [More info](https://www.bleepingcomputer.com/news/security/interlock-ransomware-exploited-secure-fmc-flaw-in-zero-day-attacks-since-january/)

- **DarkSword iOS Exploit Kit**: State-sponsored hackers are utilizing a sophisticated "zero-click" exploit chain to install spyware on iOS devices, enabling silent exfiltration of messages and location data. [More info](https://www.securityweek.com/darksword-ios-exploit-kit-used-by-state-sponsored-hackers-spyware-vendors/)

- **Russian iOS Exploit Kit Discovered**: A second iOS exploit kit, likely of Russian origin, has emerged. It appears to utilize tools originally developed by the U.S. government to achieve remote code execution. [More info](https://cyberscoop.com/second-ios-exploit-kit-emerges-from-suspected-russian-hackers-using-possible-u-s-government-developed-tools/)

- **SideWinder Espionage Expansion**: The India-linked actor is targeting government and military sectors in Indonesia and Thailand, using infrastructure that derives C2 addresses dynamically to avoid detection. [More info](https://www.darkreading.com/threat-intelligence/sidewinder-espionage-campaign-expands-across-southeast-asia)

- **Handala Group Breach of Stryker**: Iranian-linked threat actors claimed responsibility for a disruptive attack on Stryker, using Microsoft Intune to issue mass wipe commands to 80,000 devices. [More info](https://www.securityweek.com/iranian-hackers-likely-used-malware-stolen-credentials-in-stryker-breach/)

- **Vidar Stealer 2.0 Exploits GitHub**: A new campaign uses GitHub Pages and Reddit to distribute Vidar Stealer 2.0 disguised as game cheats, targeting credentials and 2FA data. [More info](https://www.infosecurity-magazine.com/news/vidar-stealer-exploits-github/)

## 📈 Trends

- **Font Rendering Malicious Command Hiding**: A novel technique uses ligatures and specialized glyph mapping to hide malicious scripts from security scanners while appearing benign to human analysts. [More info](https://www.malwarebytes.com/blog/news/2026/03/researchers-found-font-rendering-trick-to-hide-malicious-commands)

- **Refund Fraud Economy Exploitation**: A burgeoning "Refund-as-a-Service" (RaaS) economy is targeting major retailers by automating fake return requests using social engineering or stolen credentials. [More info](https://www.bleepingcomputer.com/news/security/the-refund-fraud-economy-exploiting-major-retailers-and-payment-platforms/)

- **Glassworm Malware Hits Repositories**: The Glassworm campaign has compromised over 400 repositories across GitHub, npm, and VS Code using typosquatting and dependency confusion. [More info](https://www.bleepingcomputer.com/news/security/glassworm-malware-hits-400-plus-code-repos-on-github-npm-vscode-openvsx/)

- **Nordstrom Email System Exploitation**: Threat actors abused Nordstrom’s legitimate email infrastructure to bypass filters and send high-credibility cryptocurrency scams to customers. [More info](https://www.bleepingcomputer.com/news/security/nordstroms-email-system-abused-to-send-crypto-scams-to-customers/)

- **.NET AOT Malware Evasion**: New malware is using .NET Ahead-of-Time (AOT) compilation to remove metadata, significantly complicating reverse-engineering and static analysis. [More info](https://hackread.com/net-aot-malware-code-black-box-evade-detection/)

- **ClickFix Social Engineering Tactics**: Attackers are using fake browser updates to trick users into pasting and executing malicious PowerShell scripts via the Windows Run dialog. [More info](https://hackread.com/clickfix-scam-users-mapping-hacker-controlled-drives/)

- **WhatsApp View Once Bypass Refusal**: Meta has stated it will not patch a newly discovered method to bypass "View Once" media protections, arguing that unofficial clients are outside its security model. [More info](https://www.securityweek.com/researcher-discovers-4th-whatsapp-view-once-bypass-meta-wont-patch/)

## 💥 Breaches & Leaks

- **Marquis Ransomware Data Theft**: The group linked to a major 2025 cyberattack has exfiltrated personal data belonging to 672,000 individuals, including social security numbers and financial details. [More info](https://www.bleepingcomputer.com/news/security/marquis-ransomware-gang-stole-data-of-672-000-people-in-2025-cyberattack/)

- **ShieldGuard Crypto Scam Dismantled**: Law enforcement successfully took down a massive cryptocurrency fraud operation that used phishing websites to defraud thousands of investors. [More info](https://www.infosecurity-magazine.com/news/crypto-scam-shieldguard-dismantled/)

## 🛠️ Tools & Defense

- **Veracode Fix for SCA**: Veracode introduced an AI-powered engine to automate the patching of open-source vulnerabilities by generating cohesive pull requests in developer environments. [More info](https://www.helpnetsecurity.com/2026/03/18/veracode-fix-for-sca/)

- **Claude Code Security vs Magecart**: A new report highlights why AI-driven static analysis often misses Magecart attacks that hide in third-party assets like favicon EXIF metadata. [More info](https://thehackernews.com/2026/03/claude-code-security-and-magecart.html)

- **DispatchLogger for COM Analysis**: Cisco Talos released an open-source tool to intercept and log malicious COM (Component Object Model) automation used by script-based malware. [More info](https://blog.talosintelligence.com/transparent-com-instrumentation-for-malware-analysis/)

---

[⬅ Back to Archive](https://pranakn.github.io)
