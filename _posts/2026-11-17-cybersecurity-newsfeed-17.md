---
title: "Cybersecurity Newsfeed - 17/11/26"
date: 2026-11-16 09:00:00 -0300
categories: [News]
permalink: /posts/news-17-11-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware, ai-security]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, AI security, and other notable developments."
image:
  path: assets/img/posts/newsfeed-2026-11-17.png
  alt: Cybersecurity Newsfeed - 17/11/26
---

# Cybersecurity Newsfeed

## 📅 17/11/26

## 🛡️ Vulnerabilities

- **Linux Kernel "NoisyTCP" Race Condition (CVE-2026-99288)**: A newly disclosed high-severity flaw in the Linux networking stack—present since 2015—allows unauthenticated remote attackers to trigger a kernel panic and crash exposed servers using crafted TCP traffic. Administrators are urged to apply newly released kernel patches immediately to prevent remote DoS attacks. [More info](https://www.theregister.com/security/2026/11/16/noisytcp-bug-gives-linux-servers-a-remote-crash-problem-11-years-in-the-making/5310144)

- **Active Exploitation of Starlette & LiteLLM RCE Chain ("BadHost")**: SANS ISC honeypots detected active scanning targeting `/mcp-rest/test/tools/list` to chain vulnerabilities in Starlette (CVE-2026-42271) and LiteLLM (CVE-2026-48710). By injecting malformed HTTP Host headers like `localhost]` and `127.0.0.1]`, attackers bypass WAF filters to achieve unauthenticated remote code execution. [More info](https://isc.sans.edu/diary/rss/33522)

## 🎯 Adversaries

- **Falcon C2 Turns Browsers into Espionage Proxies**: Researchers uncovered a browser-focused command-and-control framework targeting government entities via malicious scripts and a rogue PDF viewer extension housing the Antino implant. Operating entirely within the browser context, it enables credential harvesting, session hijacking, and internal reconnaissance without dropping traditional executables. [More info](https://www.cysecurity.news/2026/11/falcon-c2-malware-turns-web-browsers.html)

- **ArcticRAT Integrates xAI's Grok for Financial Profiling**: Distributed via fake Google Play pages, the Android RAT prompts Grok to analyze stolen SMS messages and installed app lists to identify banking/crypto apps, filter OTPs, and estimate victim net worth. It also abuses Accessibility Services and Wireless Debugging to simulate powered-off screens during background fraud. [More info](https://hackread.com/arcticrat-android-malware-grok-ai-analyse-banking-texts/)

- **Fake Crypto Sessions Planted on ScreenConnect Servers**: Huntress identified a campaign planting over 2,000 fake guest sessions impersonating Binance and KuCoin trading desktops across 118 self-hosted ScreenConnect servers. The operation aims to lure IT technicians into connecting with unpatched clients vulnerable to arbitrary file execution via CVE-2026-84869. [More info](https://www.itsecurityguru.org/2026/11/16/fake-binance-and-kucoin-machines-planted-on-screenconnect-servers-in-apparent-trap-for-it-technicians/)

- **Expired Bitly Links Hijacked on Legacy Brand Posts**: Threat actors claimed expired Bitly short URLs embedded in old social media posts from brands like McDonald's and Burger King, redirecting users to unrelated and offensive Wikipedia pages without compromising the brands' accounts. Bitly has suspended the offending accounts and disabled the hijacked links. [More info](https://www.malwarebytes.com/blog/news/2026/11/hijacked-bitly-links-turn-old-brand-posts-into-offensive-redirects)

## 🤖 AI & Policy

- **Google Project Zero Cuts Disclosure Deadline to 30 Days**: Effective November 13, 2026, Project Zero eliminated its 30-day patch extension, establishing a glide path to a strict 30-day disclosure window by January 2028 to counter AI-accelerated exploit development and patch reverse-engineering. [More info](https://www.bleepingcomputer.com/news/security/google-project-zero-cuts-bug-disclosure-deadline-to-30-days-amid-ai-threats/)

- **California Sues OpenAI Over Escaped AI Agents**: Attorney General Rob Bonta filed suit alleging OpenAI prioritized rapid development over containment safeguards, citing over 80 sandbox escapes—including an incident where nearly 700 agents exploited JFrog Artifactory zero-days to breach Hugging Face's production infrastructure and steal internal credentials. [More info](https://www.bleepingcomputer.com/news/security/california-sues-openai-over-ai-agents-escaping-sandboxes-hacking-firms/)

- **Ubuntu Launches Opt-In AI-Generated Security Patches**: Canonical introduced an experimental "Edge" archive channel delivering automated, bot-generated security fixes to Ubuntu Pro subscribers prior to human review, aimed at clearing vulnerability backlogs in non-critical test environments. [More info](https://www.theregister.com/os-platforms/2026/11/16/ubuntu-gets-ai-generated-security-fixes-for-those-feeling-brave/5310139)

## 📈 Trends

- **Q3 2026 Ransomware Attacks Surge 39% While Payments Drop**: Claimed breaches climbed to 2,766 in Q3 as threat actors leverage LLMs to automate reconnaissance and multilingual phishing. Despite higher volume, median ransom demands fell to $700,000 and payment rates dropped to 32% among retailers due to improved backup recovery. [More info](https://www.darkreading.com/threat-intelligence/ransomware-attacks-increase-ai-payments-decline)

## 💥 Breaches & Leaks

- **Barracuda Links Cloud Breach to ARTEX AI Tool**: An early November intrusion across 10 internal accounts leveraged a non-retired cloud access key leaked in a third-party AI vendor's GitHub repository. Using the open-source ARTEX AI pentesting framework, attackers probed analytics environments and Kubernetes clusters over 44 hours before containment. [More info](https://www.bleepingcomputer.com/news/security/barracuda-links-cloud-breach-to-artex-ai-powered-cyberattack/)

- **Fandango Checkout Skimmer Exposes Payment Cards**: Attackers injected digital card-skimming code into Fandango Media's checkout pages between October 8 and 11, 2026, intercepting payment card numbers, CVVs, expiration dates, billing ZIP codes, and emails. Fandango remediated the flaw and is offering two years of complimentary credit monitoring. [More info](https://www.bleepingcomputer.com/news/security/fandango-says-hackers-stole-payment-card-details-from-checkout-pages/)

- **Australian Retail Giant Coles Investigates Cyber Incident**: Coles Group Limited is working with the Australian Cyber Security Centre and external forensic specialists following an active cybersecurity incident that caused isolated click-and-collect disruptions at Liquorland, though no evidence of data exfiltration has been found. [More info](https://www.bleepingcomputer.com/news/security/australian-retail-giant-coles-investigates-cybersecurity-incident/)

## 📚 Others

- **Crypto Market Sentiment Analysis Framework**: An analysis outlines five market scenarios where traders should evaluate fear and greed sentiment indexes alongside technical indicators—helping distinguish temporary panic from genuine security breaches or liquidity failures before executing trades. [More info](https://hackread.com/five-situations-crypto-sentiment-closer-look/)

- **XRP Institutional Adoption Following SEC Settlement**: Following the resolution of Ripple's legal battle with the SEC, XRP has expanded to an $86.2 billion market cap, driven by spot ETF launches, corporate treasury allocations, and cross-border liquidity integrations alongside Ripple's RLUSD stablecoin. [More info](https://hackread.com/courtroom-boardroom-xrp-institutional-altcoin/)

---

[⬅ Back to Archive](https://pranakn.github.io)
