---
title: "Cybersecurity Newsfeed - 08/09/26"
date: 2026-09-07 09:00:00 -0300
categories: [News]
permalink: /posts/news-08-09-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-09-08.png
  alt: Cybersecurity Newsfeed - 08/09/26
---

# Cybersecurity Newsfeed

## 📅 08/09/26

## 🛡️ Vulnerabilities

- **Magento "StyleSmuggler" Zero-Day Exploited**: A zero-day flaw across all versions of Magento and Adobe Commerce allows attackers to deploy a Rust-based Linux backdoor. The exploit abuses the template system via PHP code injection in fake payment failure emails to achieve remote code execution, establish persistence via cron jobs, and disguise C2 communications. [More info](https://www.bleepingcomputer.com/news/security/magento-stylesmuggler-zero-day-exploited-to-deploy-linux-backdoor/)

- **Telerik UI RCE Vulnerability Chain**: Researchers released a PoC chaining an AES-CBC padding oracle bug (CVE-2026-13182) and an uncurated type-resolution flaw (CVE-2026-13181) in Telerik UI for ASP.NET AJAX. The exploit allows unauthenticated attackers to forge configurations and load malicious DLL assemblies directly into memory. [More info](https://thehackernews.com/2026/09/telerik-ui-padding-oracle-bug-chained.html)

- **Zero-Day Privilege Escalations Dropped**: Security researcher Nightmare Eclipse published zero-day privilege escalation exploits targeting Avast ("PrettyPrague"), CrowdStrike ("FalconFlank"), and Nvidia ("GreenSection"), allowing local attackers to bypass sandboxes, abuse remediation features, or manipulate display drivers. [More info](https://www.securityweek.com/nightmare-eclipse-drops-crowdstrike-nvidia-avast-zero-day-exploits/)

- **"MikroTrick" RouterOS Zero-Day Exploitation**: Attackers are exploiting a zero-day chain combining an SSH authentication bypass (CVE-2026-67276) and privilege escalation (CVE-2026-86060) on MikroTik RouterOS devices to gain full administrative control and configure rogue accounts. [More info](https://www.bleepingcomputer.com/news/security/hackers-exploit-new-mikrotik-routeros-flaws-to-hijack-routers/)

- **ConnectWise ScreenConnect Unpatched Flaw**: ConnectWise issued an advisory for an unpatched file transfer vulnerability affecting ScreenConnect Remote Access sessions across cloud and on-premises deployments. Administrators are urged to temporarily revoke `TransferFiles` permissions while a patch is developed. [More info](https://www.bleepingcomputer.com/news/security/connectwise-warns-of-new-screenconnect-flaw-without-patch/)

- **Maximum-Severity Flaw in N-able N-central**: N-able released an emergency hotfix for a critical RCE vulnerability (CVE-2026-86218) in its N-central platform. The bug allows unauthenticated attackers to execute arbitrary code on exposed instances, with active exploitation and secondary auth-bypass flaws already observed in the wild. [More info](https://www.bleepingcomputer.com/news/security/n-able-patches-max-severity-n-central-flaw-amid-ongoing-attacks/)

## 🎯 Adversaries

- **Rogue ScreenConnect Clients Deploy VBScript Chain**: Threat actors are using rogue ScreenConnect clients to spread a four-stage VBScript attack chain that profiles systems, disables security controls, and deploys XMRig cryptocurrency miners. Compromised hosts act as distribution points to automatically propagate the malware to newly connected endpoints. [More info](https://thehackernews.com/2026/09/rogue-screenconnect-clients-spread-four.html) | [More info](https://www.helpnetsecurity.com/2026/09/07/connectwise-screenconnect-file-transfer-flaw/)

- **JSCeal Malware Targets Crypto Platforms**: The compiled V8 JavaScript malware JSCeal uses heavy obfuscation to steal saved browser credentials, cookies, and OAuth tokens to bypass Google authentication. It also injects content into active browser sessions to manipulate real-time transactions on major crypto exchanges. [More info](https://thehackernews.com/2026/09/jsceal-malware-can-bypass-google.html)

## 📈 Trends

- **Cybercriminals Target Consumer Loyalty Points**: Fraudsters are increasingly compromising consumer reward accounts to steal loyalty points and fund personal travel expenses. Because consumers monitor reward balances far less frequently than bank accounts, researchers advise enforcing strong passwords and MFA across all reward platforms. [More info](https://www.malwarebytes.com/blog/podcast/2026/09/loyalty-points-fraud-is-funding-hacker-holidays-lock-and-code-s07e18)

- **BigBear 2.0 Bypasses MFA Across 258 Organizations**: An Evilginx2-based adversary-in-the-middle phishing platform named BigBear 2.0 compromised over 5,000 Microsoft 365 credentials. The platform suppresses FIDO2/WebAuthn prompts via custom JavaScript and routes traffic through geo-matched residential proxies to evade detection. [More info](https://www.bleepingcomputer.com/news/security/bigbear-microsoft-365-phishing-service-bypassed-mfa-at-258-organizations/)

- **Cloud Risk Profile Comparison (AWS vs. Azure vs. GCP)**: Analysis of 3,000 organizations reveals distinct multi-cloud vulnerabilities: AWS accounts suffer from overly permissive firewalls, Azure from misconfigured storage keys and missing Entra ID MFA, while Google Cloud maintains lower exposure rates despite lingering OS Login misconfigurations. [More info](https://thehackernews.com/2026/09/your-cloud-security-checklist-doesnt.html)

- **AI Bots Automation Surge on X**: Inauthentic accounts on X are combining static scripts with conversational LLMs to execute adult-content marketing scams. The automated accounts decode complex text prompts and generate personalized voice notes to build rapport before directing targets to paid platforms. [More info](https://www.malwarebytes.com/blog/ai/2026/09/flirty-onlyfans-promoters-on-x-may-be-using-ai-to-appear-human)

- **ChatGPT Introduces Third-Party Personalization**: OpenAI is testing a "Writing Style" feature allowing ChatGPT to connect to Slack, Google Drive, Notion, and Gmail. The integration analyzes communication habits directly to adapt response tone without manual prompt engineering. [More info](https://www.bleepingcomputer.com/news/artificial-intelligence/chatgpt-can-now-connect-to-your-personal-apps-to-mimic-writing-style/)

## 💥 Breaches & Leaks

- **Mathspace Discloses Breach Affecting 1M Users**: Australian learning platform Mathspace suffered a breach exposing the personal information and emails of over one million users across Australia and New Zealand. The breach resulted from an exploited SQL injection zero-day in a self-hosted Metabase instance linked to the ShinyHunters group. [More info](https://www.bleepingcomputer.com/news/security/mathspace-discloses-data-breach-affecting-over-1-million-people/)

- **Trezor Shipping Provider Breach Reaches 81K Victims**: Hardware wallet maker Trezor reported that a supply-chain breach at shipping provider ShipMonk impacted an additional 67,000 U.S. customers. The incident exposed customer contact and shipping details following a SQL injection attack against ShipMonk's Metabase analytics infrastructure. [More info](https://www.bleepingcomputer.com/news/security/trezor-data-breach-impact-now-reaches-81-000-customers/)

---

[⬅ Back to Archive](https://pranakn.github.io)
