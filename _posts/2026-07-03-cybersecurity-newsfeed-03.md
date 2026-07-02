---
title: "Cybersecurity Newsfeed - 03/07/26"
date: 2026-07-02 18:30:00 -0300
categories: [News]
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-07-03.png
  alt: Cybersecurity Newsfeed - 03/07/26
---

# Cybersecurity Newsfeed

## 📅 03/07/26

## 🛡️ Vulnerabilities

- **WinRAR Critical RCE Flaw (CVE-2026-14191)**: WinRAR released version 7.23 to patch a memory buffer overflow flaw in RAR5 recovery-volume (`.rev`) files. Attackers can exploit this to write data outside allocated memory and execute malicious code. Because WinRAR lacks auto-updates, users must patch manually. [More info](https://www.malwarebytes.com/blog/news/2026/07/winrar-flaw-could-allow-attackers-to-take-control-of-your-computer)

- **Microsoft SharePoint Active KEV Exploitation (CVE-2026-45659)**: CISA added a high-severity SharePoint RCE flaw to its Known Exploited Vulnerabilities (KEV) catalog. Arising from unsafe deserialization of untrusted data, it allows low-privilege authenticated attackers to execute remote code. Federal agencies must patch immediately. [More info](https://www.bleepingcomputer.com/news/security/cisa-microsoft-sharepoint-rce-flaw-now-actively-exploited/)

- **Cisco Unified CM SSRF Exploitation (CVE-2026-20230)**: Cisco confirmed active exploitation of an SSRF flaw in its Unified Communications Manager. Unauthenticated remote attackers can execute commands or create files via crafted HTTP requests. Organizations are urged to upgrade or disable the WebDialer service. [More info](https://www.bleepingcomputer.com/news/security/cisco-finally-confirms-attackers-exploiting-unified-cm-flaw/)

- **Yarbo Autonomous Mower Hardcoded Root Password**: Researchers discovered a permanent, unpatchable backdoor sharing a hardcoded "root" password across all Yarbo robotic lawn mowers. The flaw allows attackers to hijack cameras, GPS, and mechanical controls remotely. [More info](https://www.kaspersky.com/blog/yarbo-robot-lawn-mower-hacked-2/56067/)

- **Uncoordinated Zero-Day Drop in "Exploitarium"**: A pseudonymous researcher published a GitHub repository containing over 30 AI-fuzzed proof-of-concept exploits for open-source projects like the Linux kernel, 7-Zip, and a critical RCE in libssh2 (CVE-2026-55200), skipping coordinated disclosure. [More info](https://www.infosecurity-magazine.com/news/researcher-exploitarium-exploits/)

## 🎯 Adversaries

- **JADEPUFFER Executes First "Agentic" Ransomware Attack**: Sysdig documented the first known autonomous attack executed entirely by an AI agent. Targeting exposed Langflow instances (CVE-2025-3248), the agent harvested credentials and destroyed production configuration data, self-correcting its payload errors within 31 seconds. [More info](https://hackread.com/sysdig-jadepuffer-first-agentic-ransomware-operation/)

- **Anubis & Gentlemen RaaS Group Tactics**: The Anubis ransomware operation is actively exploiting the "Citrix Bleed 2" flaw (CVE-2025-5777) for initial access before dropping RMM tools. Concurrently, the Gentlemen RaaS group is deploying a Go-based backdoor using BYOVD techniques to kill EDR agents. [More info](https://thehackernews.com/2026/07/ransomware-groups-turn-to-citrix-bleed.html)

- **ConsentFix and ClickFix Hijack M365 Accounts**: Attackers are utilizing "ClickFix" to trick users into running malicious CLI commands and "ConsentFix" to manipulate OAuth flows. Both techniques steal active session tokens, effectively bypassing MFA and standard passwords within seconds. [More info](https://www.bleepingcomputer.com/news/security/consentfix-and-clickfix-how-microsoft-365-accounts-are-hijacked-in-3-seconds/)

- **ToddyCat APT Umbrij Malware Targets Gmail**: The ToddyCat threat group is deploying a new .NET malware named Umbrij. It abuses the "Shadow Token via Remote Debug" technique to spawn headless Chromium browsers, seizing active user sessions to exfiltrate corporate Google Workspace tokens. [More info](https://thehackernews.com/2026/07/toddycat-linked-umbrij-malware-abuses.html)

- **ChocoPoC RAT Targets Cyber Researchers via GitHub**: A supply chain campaign hides the "ChocoPoC" remote access trojan inside fake proof-of-concept exploit repos on GitHub. Masked via malicious Python dependencies, the trojan steals browser cookies, passwords, and SSH keys upon installation. [More info](https://thehackernews.com/2026/07/new-chocopoc-rat-targets-vulnerability.html)

## 📈 Trends

- **iboss Launches Free AI Security Platform to Fight Shadow AI**: To combat unauthorized employee usage of unvetted corporate AI tools and potential data leaks, iboss released a free platform that automatically inventories internal AI tools, risk-scores them, and maps user activity. [More info](https://www.helpnetsecurity.com/2026/07/02/iboss-ai-security-platform/)

- **Opera Integrates "Paste Protect" Feature**: To reduce the success rate of ClickFix and clipboard injection social engineering lures, Opera introduced an automated security feature that scans copied content for malicious script patterns before allowing CLI execution. [More info](https://www.bleepingcomputer.com/news/security/opera-rolls-out-paste-protect-feature-to-fight-clickfix-attacks/)

## 💥 Breaches & Leaks

- **FBI Seizes NetNut Residential Proxy Platform & Popa Botnet**: International law enforcement operations dismantled the criminal NetNut residential proxy infrastructure and the linked Popa botnet. Authorities seized hundreds of domains used by actors to hide password spraying and account takeovers via compromised IoT streaming boxes. [More info](https://krebsonsecurity.com/2026/07/fbi-seizes-netnut-proxy-platform-popa-botnet/)

---

[⬅ Back to Archive](https://pranakn.github.io)
