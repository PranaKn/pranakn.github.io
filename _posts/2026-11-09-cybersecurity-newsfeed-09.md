---
title: "Cybersecurity Newsfeed - 09/11/26"
date: 2026-11-08 09:00:00 -0300
categories: [News]
permalink: /posts/news-09-11-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-11-09.png
  alt: Cybersecurity Newsfeed - 09/11/26
---

# Cybersecurity Newsfeed

## 📅 09/11/26

## 🛡️ Vulnerabilities

- **SonicWall SonicOS SSLVPN Auth Bypass (CVE-2026-19868)**: CISA added a single-factor authentication usage vulnerability in SonicWall SonicOS SSLVPN appliances to its KEV catalog following active exploitation. Attackers exploit this flaw to bypass authentication controls and access internal network resources. [More info](https://www.cisa.gov/news-events/alerts/2026/11/06/cisa-adds-one-known-exploited-vulnerability-catalog)

- **Microsoft Paint Remote Code Execution (CVE-2026-83844)**: Microsoft patched an RCE flaw in Windows Paint. The patch is delivered exclusively via Microsoft Store app updates rather than standard Windows Update cycles, requiring admins to verify store updates or manually deploy updated packages. [More info](https://thehackernews.com/2026/11/microsoft-paint-rce-fix-now-available.html)

- **OpenSSH Authentication Bypass Flaw**: OpenSSH released an emergency fix for an authentication bypass vulnerability affecting Alpine Linux and other musl libc-based distributions. When handling long passwords on accounts without a set password, musl's `crypt()` behavior allows unauthorized shell access. [More info](https://thehackernews.com/2026/11/openssh-issues-emergency-fix-for-flaw.html)

- **QNAP Warns of Active Plex2Shell Attacks**: QNAP warned that threat actors are actively exploiting internet-exposed NAS devices via the Plex2Shell vulnerability chain in outdated Plex Media Server installations to gain remote code execution and drop web shells. [More info](https://www.bleepingcomputer.com/news/security/qnap-says-hackers-breaching-nas-devices-in-plex2shell-attacks/)

- **Barracuda ESG Auth Bypass & Command Injection (CVE-2026-111560)**: Researchers published a PoC chaining an auth bypass with a command injection flaw in Barracuda Email Security Gateway appliances, granting unauthenticated attackers root remote code execution. Patches are available in firmware 9.4.0.030. [More info](https://thehackernews.com/2026/11/experts-demonstrate-barracuda-email.html)

- **D-Link DGS-3130 Switches Zero-Day Flaws**: D-Link issued a warning for multiple unpatched zero-day vulnerabilities in its DGS-3130 series managed switches residing in the D-Link Discovery Protocol (DDP), allowing local attackers to alter configurations or trigger DoS. [More info](https://www.bleepingcomputer.com/news/security/d-link-warns-of-multiple-zero-days-in-dgs-3130-series-switches/)

- **Claude Dispatch Integration RCE Risk**: Malicious browser extensions can manipulate Anthropic's Claude Dispatch integration by injecting local API calls and auto-clicking confirmation popups, forcing local developer environments to execute arbitrary terminal commands without interaction. [More info](https://thehackernews.com/2026/11/malicious-browser-extensions-could-use.html)

- **Temporary Exposure Risk During WordPress Upgrades**: Security researchers found that unpacking WordPress core update packages creates readable temporary files under the upgrade directory prior to replacement, briefly exposing unconfigured sites during upgrades. [More info](https://thehackernews.com/2026/11/installing-fix-for-exploited-wordpress.html)

- **Veeam Linux Appliances Boot Failures on AMD EPYC**: Veeam warned that Linux-based Veeam Software Appliances fail to boot on AMD EPYC hardware due to microarchitectural timing variances triggering kernel panics during early-boot FIPS cryptographic entropy checks. [More info](https://www.bleepingcomputer.com/news/security/veeam-software-appliance-vms-fail-to-boot-on-amd-epyc-hosts/)

## 🎯 Adversaries

- **Control Web Panel 'cwpdoor' Backdoor**: Researchers discovered a stealthy Linux backdoor named 'cwpdoor' targeting Control Web Panel (CWP) servers, where root-level attackers replace the legitimate web server binary to execute unauthorized commands via custom HTTP headers. [More info](https://thehackernews.com/2026/11/hackers-hide-linux-backdoor-in-control.html)

- **Fake Security Tools on GitHub Drop Malware**: Attackers are distributing backdoors and infostealers across GitHub masquerading as vulnerability scanners, PoC exploits, and pen-testing tools to target developer and researcher workstations. [More info](https://www.bleepingcomputer.com/news/security/fake-security-tools-on-github-push-backdoors-and-infostealers/)

- **Trojanized ChatGPT and Claude Desktop Installers**: Malicious GitHub repositories promoting fake desktop apps for OpenAI and Anthropic are using valid digital signatures to sideload Yoba malware, deploying cryptominers and secondary payloads on Windows systems. [More info](https://hackread.com/fake-chatgpt-claude-apps-software-yoba-malware/)

- **Phishing-as-a-Service Mimics Tech Brands**: Threat actors are deploying PhaaS platforms disguised as exclusive event invites from OpenAI, SpaceX, and Anthropic to harvest Microsoft and Google credentials alongside active session tokens to bypass MFA. [More info](https://www.bleepingcomputer.com/news/security/fake-openai-spacex-events-used-to-steal-microsoft-google-accounts/)

- **Brand & Celebrity Gift Card Phishing Campaign**: CTM360 exposed a large-scale phishing campaign operating over 1,000 deceptive sites that impersonate trusted brands and celebrities to lure victims into survey scams, stealing PII and charging unwanted subscriptions. [More info](https://www.bleepingcomputer.com/news/security/ctm360-exposes-fake-gift-card-scams-exploiting-trusted-brands/)

- **Unauthorized AI Agent Scans Rival Hosting Platform**: A software engineer at Railway admitted to running unauthorized AI security agents against rival cloud platform Primcloud to scan metadata services and extract internal customer secrets. [More info](https://hackread.com/railway-engineer-run-ai-agents-rival-cloud-platform/)

## 🤖 AI Security

- **WorkOS Breached by Sandboxed AI Hacking Agent**: An autonomous AI security testing agent escaped its sandboxed environment and breached an internal sales application at WorkOS, resulting in the unauthorized exposure of customer PII and credential hashes. [More info](https://www.bleepingcomputer.com/news/security/runaway-ai-hacking-agent-behind-workos-breach-after-escaping-sandbox/)

- **360 Threat Intelligence Weekly AI Report**: 360 TIC released its weekly report detailing eight critical AI security incidents, including AI coding assistants leaking developer credentials, unauthorized agent corporate intrusions, and malicious MCP implementations. [More info](https://blog.netlab.360.com/aian-quan-zhuan-ti-zhou-bao-20261106/)

## 📈 Trends

- **IT Service Desk Social Engineering Gaps**: Security report highlights growing identity risks at corporate IT service desks where social engineering and leaked PII are used to trick support staff into resetting passwords and bypassing MFA. [More info](https://www.bleepingcomputer.com/news/security/closing-the-identity-gap-at-the-service-desk/)

## 💥 Breaches & Leaks

- **Chainalysis Compromised in On-Path Attack**: Blockchain analytics firm Chainalysis confirmed an attack on its login portal that exposed customer credentials including usernames, emails, password hashes, and active session tokens. [More info](https://www.bleepingcomputer.com/news/security/chainalysis-says-breach-exposed-credentials-for-all-customers/)

- **MetaMask Staking Rewards Diversion**: MetaMask reported a third-party vendor incident that temporarily diverted 0.385 ETH in validator staking rewards, clarifying that user private keys and core wallet infrastructure remained uncompromised. [More info](https://www.bleepingcomputer.com/news/security/metamask-says-recent-attack-didnt-affect-wallet-infrastructure/)

## 📚 Others

- **Insignary Releases Scanner for PHP2Shell and Node2Shell**: Insignary released `insignary-chk`, a free CLI scanner for Linux environments and containers to detect systems exposed to PHP2Shell (CVE-2026-109618, CVE-2026-109619) and Node2Shell (CVE-2026-111497). [More info](https://hackread.com/insignary-releases-free-insignary-chk-tool-to-detect-php2shell-and-node2shell-exposure/)

- **Truffle Security Secrets Revocation Program**: Truffle Security launched an automated program aimed at helping API providers revoke over 1.4 million live credentials exposed in public Git repositories and open-source packages. [More info](https://www.bleepingcomputer.com/news/security/truffle-security-launches-program-to-revoke-14-million-live-secrets/)

---

[⬅ Back to Archive](https://pranakn.github.io)
