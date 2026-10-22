---
title: "Cybersecurity Newsfeed - 23/10/26"
date: 2026-10-22 09:00:00 -0300
categories: [News]
permalink: /posts/news-23-10-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-10-23.png
  alt: Cybersecurity Newsfeed - 23/10/26
---

# Cybersecurity Newsfeed

## 📅 23/10/26

## 🛡️ Vulnerabilities

- **Arista VeloCloud Orchestrator Zero-Day (CVE-2026-114625)**: Arista Networks warned of active zero-day exploitation targeting its VeloCloud Orchestrator central management platform. The critical SQL injection flaw (CVSS 9.9) allows low-privileged authenticated users to escalate privileges to full superuser operator status. Arista patched hosted instances and released software updates for on-premises deployments. [More info](https://thehackernews.com/2026/10/arista-warns-of-critical-velocloud-sql.html) | [More info](https://www.bleepingcomputer.com/news/security/arista-patches-new-velocloud-orchestrator-zero-day-exploited-in-attacks/)

- **Critical Unpatched Flaws in Linux Kernel KSMBD**: Two unpatched CVSS 9.0 remote code execution vulnerabilities in the Linux kernel SMB server module were publicly disclosed on developer mailing lists. The bugs stem from a protocol dispatch race condition (ZDI-CAN-33774) and an integer underflow in the SMB Direct transport mechanism (ZDI-CAN-33549). Official CVE identifiers and fixes remain pending. [More info](https://thehackernews.com/2026/10/two-cvss-90-linux-ksmbd-rce-flaws.html)

- **OpenCode MCP Remote Code Execution Flaw**: A critical vulnerability in the OpenCode AI coding assistant allows malicious Model Context Protocol (MCP) servers to execute arbitrary shell commands on Windows and WSL developer host systems via unescaped OAuth authorization URLs. The issue was remediated quietly in version 1.18.33. [More info](https://thehackernews.com/2026/10/opencode-flaw-lets-malicious-mcp.html)

- **Node.js Brotli Decoder & TLS Vulnerabilities (CVE-2026-111497)**: Node.js released security updates across versions 22.x, 24.x, and 26.x addressing ten vulnerabilities, led by a high-severity out-of-bounds write defect in its bundled Brotli decompression library that poses remote code execution risks during HTTP fetch operations. [More info](https://thehackernews.com/2026/10/nodejs-brotli-decoder-bug-could-allow.html)

- **QPACK HTTP/3 Denial-of-Service Flaws**: Researchers detailed implementation flaws within the QPACK HTTP/3 header compression mechanism across seven protocol stacks. Malicious actors can transmit small, highly compressed header packets that trigger massive memory expansion and infinite execution loops on unpatched implementations. [More info](https://thehackernews.com/2026/10/new-qpack-flaws-can-crash-http3-servers.html)

## 🎯 Adversaries

- **APT41 Deploys BlackX UEFI Bootkit**: Kaspersky GReAT discovered a UEFI bootkit named BlackX deployed by APT41 against Central Asian diplomatic entities. Exploiting the Baton Drop vulnerability (CVE-2022-21894), BlackX bypasses Secure Boot, tampers with security software callbacks/ETW, and drops RAT payloads using commercial cloud C2 infrastructure. [More info](https://securelist.com/uefi-bootkit-blackx/121539/)

- **Brazilian Financial Ecosystem & Eternidade Stealer**: A technical deep dive exposes Eternidade Stealer, a threat spreading via WhatsApp phishing campaigns in Brazil. It uses an automated WhatsApp Web worm and a Delphi-based core banking Trojan with multi-stage execution containers to perform process hollowing, credential theft, and banking fraud. [More info](https://0x0d4y.blog/inside-brazils-financial-malware-ecosystem-deep-dive-into-eternidade-stealer/)

- **LiteLLM PyPI & Docker Supply Chain Compromise**: Attackers compromised the open-source LiteLLM project on PyPI and Docker Hub to distribute information-stealer malware in version 1.107.0. The malicious package harvested cloud credentials, AI API keys, developer SSH keys, and browser data before maintainers removed the compromised release. [More info](https://www.bleepingcomputer.com/news/security/litellm-release-pipeline-hacked-to-distribute-info-stealer-malware/)

## 📈 Trends & Industry

- **Anthropic AI Attack Surface Reduction Research**: Anthropic evaluated 25 major open-source projects using Claude, identifying 493 structural security weaknesses. Anthropic collaborated with OpenSSH maintainers to apply these principles to OpenSSH 10.6, restricting unauthenticated experimental code access and reducing default attack surface area by nearly 20%. [More info](https://www.helpnetsecurity.com/2026/10/22/anthropic-attack-surface-reduction-open-source/)

- **Palo Alto Networks and NVIDIA Partner for Agentic AI Security**: Palo Alto Networks announced a strategic collaboration with NVIDIA to protect autonomous agentic AI infrastructure, integrating AI Runtime Security directly onto NVIDIA BlueField DPUs using the NVIDIA OpenShell Reference Architecture. [More info](https://www.paloaltonetworks.com/blog/2026/10/advancing-agentic-ai-security-with-palo-alto-networks-and-nvidia/)

- **Compromised eMudhra Intermediate CA Keys**: Cisco Talos warned that flawed key generation procedures generated sub-keys with severely degraded entropy for eight intermediate certificate authority keys belonging to eMudhra. The vulnerability allows adversaries to forge valid TLS and code-signing certificates. [More info](https://blog.talosintelligence.com/compromised-intermediate-certificates/)

## 💥 Breaches & Leaks

- **Capcom Confirms Data Breach (11.7M Accounts)**: Video game publisher Capcom confirmed a security breach involving its CAPCOM ID membership system, exposing customer email addresses, account timestamps, and IP addresses. Capcom assured users that payment details remain uncompromised and online gaming services operate securely. [More info](https://www.bleepingcomputer.com/news/security/capcom-confirms-data-breach-affecting-117-million-accounts/)

- **Japan's Onamae Desktop Cloud Hacked (27,000 Servers)**: Japanese VPS provider Onamae Desktop Cloud suffered a security breach resulting in malicious software installations across 26,739 customer virtual servers, prompting an emergency infrastructure shutdown of the MetaTrader-focused hosting environment. [More info](https://www.bleepingcomputer.com/news/security/japans-onamae-desktop-cloud-hacked-up-to-27-000-servers-affected/)

---

[⬅ Back to Archive](https://pranakn.github.io)
