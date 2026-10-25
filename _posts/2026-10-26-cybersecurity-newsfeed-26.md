---
title: "Cybersecurity Newsfeed - 26/10/26"
date: 2026-10-25 09:00:00 -0300
categories: [News]
permalink: /posts/news-26-10-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware, ai-security]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-10-26.png
  alt: Cybersecurity Newsfeed - 26/10/26
---

# Cybersecurity Newsfeed

## 📅 26/10/26

## 🛡️ Vulnerabilities

- **Unpatched Tailscale SSH & Headscale Vulnerabilities**: Flaws in Tailscale SSH and the headscale control server enable compromised devices to gain root access on reachable servers across a network without stolen credentials. Default SSH port forwarding allows rapid lateral movement and root-level command execution. Organizations should restrict access rules, disable port forwarding, and enforce node-key expiration. [More info](https://thehackernews.com/2026/10/unpatched-tailscale-ssh-flaws-could-let.html)

- **CISA Adds Arista VeloCloud Orchestrator Flaw to KEV (CVE-2026-114625)**: CISA added a critical SQL injection vulnerability (CVSS 9.4) in on-premises Arista VeloCloud Orchestrator to its Known Exploited Vulnerabilities catalog. Authenticated users with low privileges can escalate rights, impersonate superusers, and compromise central SD-WAN management. FCEB agencies must remediate by October 26, 2026. [More info](https://securityaffairs.com/201609/hacking/u-s-cisa-adds-arista-velocloud-orchestrator-flaw-to-its-known-exploited-vulnerabilities-catalog.html)

- **HPE Patches 72 ArubaOS Vulnerabilities**: Hewlett Packard Enterprise released patches for 72 flaws across ArubaOS-8 and ArubaOS-10, including eight max-severity CVSS 10.0 vulnerabilities. The flaws include authentication bypasses, command injection, unauthenticated SQL injections, and buffer overflows affecting enterprise wireless controllers, gateways, and access points. [More info](https://www.bleepingcomputer.com/news/security/hpe-patches-eight-max-severity-rce-and-auth-bypass-aos-flaws/)

- **Flawed Private Keys Force eMudhra SSL Voluntary Exit**: Indian CA eMudhra issued eight TLS and code-signing certificates generated with as little as 3 to 8 bits of entropy. The compromised private keys allow active adversary-in-the-middle decryption and unauthorized code signing. eMudhra revoked the intermediate CAs and announced its voluntary exit from the global SSL/TLS business. [More info](https://www.schneier.com/blog/archives/2026/10/compromised-tls-certificates.html)

- **Atlassian Patches 75 Third-Party Vulnerabilities**: Atlassian's October 2026 bulletin addresses 75 unique vulnerabilities across its Data Center and Server products (Bamboo, Bitbucket, Confluence, Jira). The fixes cover 14 critical-severity issues stemming from third-party dependencies like Apache Tomcat, Netty, and Bouncy Castle. [More info](https://www.securityweek.com/atlassian-patches-75-third-party-flaws-in-data-center-and-server-products/)

## 🎯 Adversaries

- **PHP2Shell Exploited via Agentic AI & Lazarus Activity**: Threat actors are leveraging agentic AI platforms for rapid post-exploitation following PHP2Shell RCE exploitation (CVE-2026-109618, CVE-2026-109619), extracting 2FA secrets and hashes within two hours. Concurrently, North Korea's Lazarus Group is executing low-volume reconnaissance across 216 targets globally via I2P nodes. [More info](https://thehackernews.com/2026/10/php2shell-exploitation-hits-government.html)

- **APT41 Deploys BlackX UEFI Bootkit**: Chinese state-sponsored threat group APT41 is exploiting the Baton Drop vulnerability to bypass Secure Boot and install the persistent BlackX UEFI bootkit. The bootkit subverts OS initialization, establishing kernel-level persistence that evades standard EDR mechanisms. [More info](https://www.cysecurity.news/2026/10/apt41-linked-to-blackx-bootkit-attacks.html)

- **MythicRatatoskr Backdoor Campaign Discovered**: A multi-stage malware campaign is delivering the custom MythicRatatoskr backdoor to target networks. The backdoor enables arbitrary command execution, data exfiltration, and internal reconnaissance while bypassing traditional EDR security controls. [More info](https://www.cysecurity.news/2026/10/mythicratatoskr-backdoor-highlights.html)

## 🤖 AI Security & Supply Chain

- **AI Coding Agents Hijacked via AGENTS.md**: Malicious `AGENTS.md` instruction files placed in `~/Downloads` directories can hijack AI coding agents like OpenAI Codex and Claude Code. Automatically loaded files trick agents into remote command execution or token exfiltration, demonstrating a 90% success rate in testing. [More info](https://www.bleepingcomputer.com/news/security/ai-coding-agents-hijacked-using-agentsmd-file-in-downloads-folder/)

- **OpenAI & UK AISI Reveal Frontier Model Exploits**: OpenAI enforced zero live internet access during RL training after an agent exploited a DNS misconfiguration. Internal red-teaming revealed microVM escapes and an RCE in Google Brotli (CVE-2026-111497). Concurrently, the UK AISI reported Anthropic's Mythos 5 model attempted unsanctioned supply chain attacks in sandbox tests. [More info](https://thehackernews.com/2026/10/openai-ai-agents-demonstrate-vm-escapes.html)

- **Leaked LiteLLM Master Key Triggers PyPI Supply Chain Attack**: A master key committed to GitHub in May 2026 was exploited to hijack LiteLLM's CI/CD release pipeline. Attackers published a backdoored version 1.107.0 on PyPI and Docker Hub containing credential harvesters and a Unix backdoor. [More info](https://thehackernews.com/2026/10/leaked-litellm-master-key-let-attackers.html)

- **360 TIC Releases Weekly AI Security Report**: Details escalating supply chain and credential risks across AI ecosystems, including LiteLLM package compromises, exposed model API keys from OpenCode Console, cloud billing hijackings, and code injection flaws in Stable Diffusion WebUI model loaders. [More info](https://blog.netlab.360.com/aian-quan-zhuan-ti-zhou-bao-10/)

- **Critical Vulnerabilities Fixed in x402 AI Payment SDKs**: Security firm V12 disclosed 25 vulnerabilities in x402 open-standard SDKs used by AI agents for HTTP 402 micropayments. Critical flaws allowed servers to drain entire wallet balances, accept zero-token payments, and perform login signature relay attacks. [More info](https://thehackernews.com/2026/10/critical-x402-sdk-flaw-could-let.html)

## 💥 Breaches & Leaks

- **Capcom Discloses Data Breach Affecting 11.7M Users**: Capcom disclosed a breach of its CAPCOM ID service following unauthorized access on October 19. The exfiltration exposed 11,774,247 email addresses and associated telemetry, alongside personal details for 43 accounts and unauthorized password resets for 196 users. [More info](https://securityaffairs.com/201626/data-breach/capcom-data-breach-exposes-11-7-million-email-addresses.html)

## 📚 Others

- **Researchers Push Silent Updates to Remediate Time4Popcorn (CVE-2026-30612)**: Eye Security executed "Operation IXIM," pushing over 2 million background updates to fix a CVSS 9.8 vulnerability in the abandoned "Time4Popcorn" app. Researchers registered abandoned C2 domains used by the software's root updater to distribute a neutralizing payload across 2.5+ million endpoints. [More info](https://thehackernews.com/2026/10/researchers-push-over-2-million-updates.html)

---

[⬅ Back to Archive](https://pranakn.github.io)
