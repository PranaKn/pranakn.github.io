---
title: "Cybersecurity Newsfeed - 06/08/26"
date: 2026-08-05 09:00:00 -0300
categories: [News]
permalink: /posts/news-06-08-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-08-06.png
  alt: Cybersecurity Newsfeed - 06/08/26
---

# Cybersecurity Newsfeed

## 📅 06/08/26

## 🛡️ Vulnerabilities

- **Pre-Auth RCE Flaws in Enterprise Java Platforms**: Security researchers disclosed 12 vulnerabilities across four enterprise Java platforms, highlighting critical pre-authentication remote code execution paths in Bonita BPM and Apache OFBiz (CVE-2026-31986). Attackers exploit URL routing bypasses and default hardcoded SSO keys to execute system commands or evaluate unsafe Groovy scripts. [More info](https://www.helpnetsecurity.com/2026/08/05/pre-auth-rce-java-bonita-ofbiz-cve-2026-31986/)

- **Unvalidated Oracle Search Endpoint Deploys "khunt" Toolkit**: Threat actors exploited an unvalidated input vulnerability in an Oracle database search endpoint to install a custom post-exploitation toolkit named "khunt". Leveraging Oracle's embedded JVM, the attackers compiled and executed Java source objects to gain SYSTEM-level access and exfiltrate registry hives (SAM, SECURITY, SYSTEM). [More info](https://www.bleepingcomputer.com/news/security/hackers-run-khunt-post-exploitation-toolkit-from-oracle-database/)

- **CISA KEV Adds JetBrains TeamCity Deserialization (CVE-2026-63077)**: CISA added a critical untrusted data deserialization flaw in JetBrains TeamCity to its Known Exploited Vulnerabilities Catalog. The flaw allows remote unauthenticated code execution, requiring Federal Civilian Executive Branch agencies to prioritize immediate patch deployment. [More info](https://www.cisa.gov/news-events/alerts/2026/08/05/cisa-adds-one-known-exploited-vulnerability-catalog)

- **Agent-to-Agent Prompt Injection in Google ADK**: Security researchers identified vulnerabilities in Google's open-source Agent Development Kit for Python that enable prompt injection attacks across privilege boundaries. Malicious prompts in pull requests can trick low-privileged review agents into issuing formatted commands parsed by maintainer agents, potentially compromising CI/CD pipelines. [More info](https://www.darkreading.com/vulnerabilities-threats/flaws-google-apk-python-agent-to-agent-attack)

- **Paperclip AI Control Plane Vulnerabilities**: Flaws in the Paperclip open-source AI agent control plane, including CVE-2026-41679 (CVSS 10.0), allow unauthenticated remote attackers to register accounts, approve board credentials, and execute host server commands via malicious configurations or DNS rebinding. [More info](https://thehackernews.com/2026/08/paperclip-ai-flaws-let-attackers-run.html)

- **CISA Warns of Exploits in Langflow, N-central, and Tomcat**: CISA issued an alert regarding active exploitation of critical flaws across IBM Langflow (CVE-2026-9198), N-able N-central (CVE-2026-18576), and Apache Tomcat (CVE-2026-34486), which allow remote code execution or authentication bypass. [More info](https://www.bleepingcomputer.com/news/security/cisa-warns-of-hackers-exploiting-langflow-n-central-apache-tomcat-flaws/)

- **OVSwrap Linux Kernel Privilege Escalation (CVE-2026-64531)**: A memory corruption flaw caused by an integer overflow in the Linux kernel's Open vSwitch datapath Netlink attribute length field allows unprivileged local users to trigger a buffer wrap and escalate privileges to root. [More info](https://thehackernews.com/2026/08/new-ovswrap-linux-kernel-flaw-lets.html)

- **Critical Unauthenticated File Read in Gitea (CVE-2026-59774)**: A CVSS 9.8 vulnerability in self-hosted Gitea versions 1.22.1 through 1.27.0 allows unauthenticated attackers to read arbitrary local server files via crafted Org-mode markup, exposing configuration tokens that can lead to remote code execution. [More info](https://thehackernews.com/2026/08/critical-gitea-flaw-let-unauthenticated.html)

- **Forescout Discovers 15 Flaws in TP-Link Omada Platform**: Vedere Labs uncovered vulnerabilities across TP-Link Omada networking hardware and cloud controllers, including predictable serial numbers, hardcoded keys, and zero-touch provisioning flaws that allow device hijacking and credential extraction. [More info](https://www.helpnetsecurity.com/2026/08/05/forescout-tp-link-omada-vulnerabilities/) | [More info](https://www.bleepingcomputer.com/news/security/tp-link-patches-omada-ztp-flaws-allowing-hackers-to-breach-networks/)

## 🎯 Adversaries

- **OctLurk and SilkLurk Backdoors Target Six Nations**: Chinese-speaking actors have been deploying two previously undocumented Windows backdoors—OctLurk and SilkLurk—against government, research, and healthcare targets. The implants generate decryption keys using host-specific hardware details to evade analysis. [More info](https://hackread.com/hackread.com/octlurk-silklurk-backdoors-target-6-countries/)

- **COLDCARD Wallet Support Phishing Campaign**: A phishing lure exploiting recent wallet RNG vulnerability concerns uses fake live chat support to trick users into running diagnostic batch scripts. The script installs ScreenConnect disguised as a printer driver to gain remote access. [More info](https://www.bleepingcomputer.com/news/security/coldcard-security-audit-phishing-attack-installs-remote-access-tool/)

- **NullReceiver C2 Dead-Drop via Ethereum**: North Korean actors updated the EtherHiding technique with NullReceiver, a dead-drop method observed in trojanized npm packages (`bianira-ui` and `fluid-type-ui`). It encodes C2 IP addresses into the destination bytes of zero-value Ethereum transactions to non-existent wallets. [More info](https://thehackernews.com/2026/08/trojanized-npm-packages-decode-c2-ip.html)

- **Fake Bank of America Lures Deploy Stealthy ScreenConnect**: Windows targets clicking fake security update links download VBScript installers using UAC bypasses to install ScreenConnect as a hidden service, modifying SDDL access rules to block removal. Mac targets are sent to credential harvesting pages. [More info](https://www.helpnetsecurity.com/2026/08/05/fake-bank-of-america-email-account-guard/)

- **Kali365 PaaS Uses Microsoft Device Code Phishing**: The Kali365 Phishing-as-a-Service kit is targeting US corporate networks by directing victims to Microsoft's legitimate device login portal. Capturing the generated OAuth access and refresh tokens grants persistent cloud access while bypassing MFA. [More info](https://hackread.com/kali365-exploit-microsoft-device-login-access-us-data/)

- **Greatness PaaS Spoofs RingCentral to Steal M365 Accounts**: The Greatness phishing platform expands its adversary-in-the-middle and device-code phishing operations by spoofing RingCentral emails. Bypassing safe-sender lists, the lures capture MFA tokens to enumerate mailbox and cloud data via Microsoft Graph APIs. [More info](https://www.bleepingcomputer.com/news/security/phishing-service-spoofs-ringcentral-to-steal-microsoft-365-accounts/)

## 📈 Trends

- **ClickFix Campaign Weaponizes Server-Side Fingerprinting**: Over 250 ClickFix domains are using server-side JavaScript fingerprinting (checking WebGL, platform strings, and video codecs) to detect sandboxes and deliver Atomic Stealer or MacSync infostealers exclusively to genuine macOS hardware. [More info](https://thehackernews.com/2026/08/over-250-clickfix-domains-use-browser.html)

- **"Poison Claude" Cybercrime Service Resells Discounted LLM Access**: Underground services are abusing free cloud trial credits to proxy requests to Anthropic and OpenAI models at steep discounts. Because customer traffic passes through intermediary proxies, all submitted prompts and proprietary code are exposed to potential theft. [More info](https://thehackernews.com/2026/08/poison-claude-sells-discounted-claude.html)

- **Leaked n8n API Keys Expose Automation Instances**: Over 300 publicly accessible n8n instances were found accepting API keys exposed in public GitHub commits. These leaked JWT tokens grant full access to workflow definitions, node parameters, database credentials, and integrated AI models. [More info](https://thehackernews.com/2026/08/leaked-n8n-api-tokens-exposed-live.html)

## 💥 Breaches & Leaks

- **Brazil's SISVISA System Exposes 79GB of Health Surveillance Data**: An unsecured cloud repository belonging to Brazil's public health surveillance system exposed 102,215 files online without authentication, leaking CPFs, driver's licenses, professional medical IDs, facial photos, fingerprints, and inspection reports. [More info](https://hackread.com/brazil-health-surveillance-database-exposed-records/)

## 📚 Others

- **Google Blogger Automated Scans Trigger False Positive Lockouts**: Misclassifications in automated content moderation tools locked hundreds of legitimate blog owners out of their management dashboards with malware violation warnings and permanent deletion notices until manual appeals were processed. [More info](https://www.bleepingcomputer.com/news/google/google-blogger-locks-hundreds-of-blogs-in-malware-false-positive/)

---

[⬅ Back to Archive](https://pranakn.github.io)
