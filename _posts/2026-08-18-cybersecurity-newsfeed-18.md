---
title: "Cybersecurity Newsfeed - 18/08/26"
date: 2026-08-17 09:00:00 -0300
categories: [News]
permalink: /posts/news-18-08-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-08-18.png
  alt: Cybersecurity Newsfeed - 18/08/26
---

# Cybersecurity Newsfeed

## 📅 18/08/26

## 🛡️ Vulnerabilities

- **Snowflake GitHub Actions Workflow Injection**: Researchers identified a severe workflow injection vulnerability in Snowflake's public GitHub repository (`jira_issue.yml`). Unsafe string interpolation allowed attackers to execute arbitrary commands and retrieve an internal Jira API token. Snowflake remediated the flaw using `jq` environment variables and credential rotation. [More info](https://thehackernews.com/2026/08/snowflake-github-actions-flaw-lets_0330881554.html)

- **Forminator Forms Arbitrary File Upload (CVE-2026-15748)**: A critical flaw in Forminator Forms (v1.56.1 and prior) allows unauthenticated attackers to bypass file-type validation via MIME key manipulation. Combined with custom storage paths, attackers can execute PHP scripts and achieve full RCE. [More info](https://thehackernews.com/2026/08/forminator-wordpress-flaw-can-enable.html)

- **UNISOC Modem Privilege Escalation**: A missing memory boundary flaw (CWE-1189) in UNISOC mobile modems allows remote privilege escalation to kernel space. Attackers can trigger the exploit chain via incoming VoLTE video calls, forcing modem memory overwrites and payload execution on Android kernels. [More info](https://www.infosecurity-magazine.com/news/unisoc-modem-flaw-rce-calls/)

- **CISA Adds Ray Framework Flaw (CVE-2025-62593) to KEV**: CISA added a code injection vulnerability in the Ray-Project Ray framework to its KEV catalog following active exploitation. Federal agencies must patch the flaw to prevent remote arbitrary code execution on exposed instances. [More info](https://www.cisa.gov/news-events/alerts/2026/08/17/cisa-adds-one-known-exploited-vulnerability-catalog)

- **Certighost AD CS Privilege Escalation (CVE-2026-54121)**: A critical flaw in Active Directory Certificate Services allows low-privileged domain users to route enrollment requests to rogue endpoints. The CA issues forged Domain Controller certificates, allowing attackers to exfiltrate credential hashes via Kerberos PKINIT and DCSync. [More info](https://www.bleepingcomputer.com/news/security/certighost-and-the-privilege-hiding-in-your-certificate-authority/)

- **WordPress User Profile Builder Auth Bypass (CVE-2026-15826)**: Over 40,000 sites are vulnerable to account takeover due to a type confusion bug during integer coercion in `wppb_log_in_user`. The bug coerces registration errors into user ID 1, issuing administrative autologin nonces. Patched in version 3.16.5. [More info](https://www.infosecurity-magazine.com/news/wordpress-plugin-flaw-40000-sites/)

- **SAP Commerce Cloud RCE (CVE-2026-58231)**: Improper input validation in core business logic components enables unauthenticated remote code execution on application servers, risking full database compromise and corporate network lateral movement. Emergency security patches are available. [More info](https://thehackernews.com/2026/08/sap-commerce-cloud-cve-2026-58231.html)

- **Microsoft Defender ShieldBreak Zero-Day**: Microsoft is working on an emergency patch for a zero-day vulnerability in Defender that allows attackers with unprivileged access to bypass real-time scanning routines, enabling undetected payload execution like ransomware and infostealers. [More info](https://www.bleepingcomputer.com/news/security/microsoft-working-on-defender-patch-for-shieldbreak-zero-day/)

- **Critical GraphQL Flaw in GitLab**: Missing authorization checks in GraphQL API resolvers allow unauthenticated remote attackers to execute administrative actions, exfiltrate repository data, and manipulate user accounts. Instance administrators are urged to apply emergency patches. [More info](https://thehackernews.com/2026/08/critical-gitlab-graphql-flaw-could-let.html)

## 🎯 Adversaries

- **Cavern Manticore Upgrades Cavern C2**: Iranian threat actors targeting Israel upgraded their C2 framework using `GoogleService.dll` to route traffic dynamically between direct HTTPS and Google Apps Script relays via DNS responses. They also leverage the Microsoft Graph API to convert Microsoft 365 calendar entries into encrypted dead-drop resolvers. [More info](https://thehackernews.com/2026/08/cavern-c2-uses-dns-and-google-apps.html)

- **Evooo1Bot Targets Edge Equipment**: A modified Mirai-derived Linux botnet targets equipment from NETGEAR, D-Link, Alcatel, and Tenda using legacy RCE flaws and SSH brute-forcing. It incorporates encrypted TCP C2, systemd persistence, and a reverse SOCKS relay to turn infected hosts into proxies. [More info](https://www.darkreading.com/cyber-risk/linux-botnet-evooo1bot-mirai-capabilities-beyond-ddos) | [More info](https://thehackernews.com/2026/08/evooo1bot-linux-botnet-exploits-known.html)

- **ClickFix Attacks Target Steam Forums**: Attackers impersonating troubleshooting support on Steam community forums trick users into running PowerShell commands (`Invoke-RestMethod` / `Invoke-Expression`). The malicious script sets Defender exclusions and deploys hidden XMRig miners. [More info](https://www.kaspersky.com/blog/steam-forum-clickfix-attack-irm-iex/56285/)

- **China-Nexus Threat Group Targets Edge Devices**: Chinese state-sponsored actors are exploiting vulnerabilities in edge devices to deploy custom web shells and living-off-the-land techniques, establishing encrypted reverse proxy tunnels to exfiltrate critical infrastructure data. [More info](https://thehackernews.com/2026/08/suspected-china-nexus-actor-exploits.html)

- **Mustang Panda Leverages Digitally Signed Binaries**: Espionage group Mustang Panda is executing DLL side-loading attacks by pairing valid, digitally signed Windows binaries with custom malicious DLLs to bypass trust verification controls and establish persistent backdoors. [More info](https://thehackernews.com/2026/08/mustang-panda-adds-signed-windows.html)

- **Global Recruitment Scam Network Discovered**: Security firm CTM360 uncovered over 3,000 malicious recruitment domains spoofing corporate brands. The sites harvest PII and banking details, while distributing infostealers under the guise of pre-employment testing software. [More info](https://thehackernews.com/2026/08/ctm360-uncovers-over-3000-recruitment.html)

- **Mercenary Spyware Attacks Prompt Apple Warnings**: Apple issued threat notifications to users across 110 countries after detecting targeted mercenary spyware exploits attempting to compromise microphones, cameras, messages, and location data on high-profile devices. [More info](https://thehackernews.com/2026/08/apple-warns-users-in-110-countries-they.html)

- **PatchCord Backdoor Targets Afghan Entities**: A novel backdoor delivered via spear-phishing weaponized archives establishes persistence using registry run keys and custom service registrations. It features encrypted C2 channels for keystroke logging, file exfiltration, and arbitrary process execution. [More info](https://thehackernews.com/2026/08/new-patchcord-backdoor-targets-afghan.html)

- **AmnesiaStealer Attacks Chromium Browsers**: Distributed via malicious search ads and trojanized utility installers, AmnesiaStealer extracts saved credentials, cookies, and crypto wallet keys from Chromium browsers, encrypting exfiltrated data to evade network controls. [More info](https://thehackernews.com/2026/08/amnesiastealer-hijacks-chromium.html)

## 📈 Trends

- **Zhipu AI Claims GLM-5.3 Superiority in Bug Finding**: Chinese AI firm Zhipu claims its GLM-5.3 model identified 2,436 security flaws in CyberGym benchmarks. However, independent analysts highlight that these vendor claims lack confirmed CVEs and note lower performance in standard software engineering tasks. [More info](https://www.theregister.com/security/2026/08/17/chinese-ai-company-zhipu-claims-its-new-model-is-a-better-bug-finder-than-anthropic-openai/5288203)

- **ChainDrop Worm Poisons 444 npm Packages**: A Shai-Hulud malware variant named ChainDrop infected 444 npm packages by poisoning archive tarballs and hooking developer tooling, bypassing traditional software composition analysis defenses. [More info](https://www.theregister.com/security/2026/08/15/chaindrop-worm-crawls-into-npm-supply-chain-evades-standard-defenses/5287958)

## 💥 Breaches & Leaks

- **3.64M Azure Records Allegedly Exfiltrated**: A threat actor known as "TheHatman" claims to be selling internal Azure tenant databases from companies like McDonald's, Gap, Vodafone, and TCS. Exfiltrated data includes employee contact details and service account configs obtained via credential stuffing and MFA fatigue, though affected firms indicate data may be legacy records. [More info](https://www.bleepingcomputer.com/news/security/hacker-claims-36-million-azure-account-records-stolen-from-major-companies/)

- **Pokémon Center Supply-Chain Breach**: A cyberattack on logistics provider CEVA Logistics exposed customer names, shipping addresses, phone numbers, and order details for European Pokémon Center shoppers. Card data was not impacted, but the incident caused severe fulfillment cancellations and delays. [More info](https://www.bleepingcomputer.com/news/security/pokemon-center-data-breach-exposes-customer-info-cancels-some-orders/)

- **Trezor Logistics Breach Exposes 13,000 Customers**: Crypto wallet maker Trezor confirmed a third-party shipping provider breach exposing PII for 13,000 customers who placed orders between May and August. Wallet keys and financial assets remain secure, but users face social engineering risks. [More info](https://www.theregister.com/security/2026/08/14/crypto-wallet-maker-trezor-confirms-13000-customers-details-exposed-in-logistics-breach/5287734)

- **Clop Extortion Syndicate Targets Philips and GE Healthcare**: Clop listed Philips and GE Healthcare on its dark web site, claiming file exfiltration via enterprise file-transfer zero-day flaws. Both corporations have launched investigations into potential data compromise. [More info](https://www.bleepingcomputer.com/news/security/philips-and-ge-investigating-clop-ransomware-data-theft-claims/)

## 📚 Others

- **Worldwide Outage Hits GitHub Services**: GitHub experienced a global outage causing ~20% error rates across APIs/web interfaces and over 50% failure rates on archive downloads. Automated workflows in GitHub Actions, webhooks, and Copilot were severely degraded before mitigation. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-confirms-github-is-down-worldwide/)

---

[⬅ Back to Archive](https://pranakn.github.io)
