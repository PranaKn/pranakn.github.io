---
title: "Cybersecurity Newsfeed - 22/10/26"
date: 2026-10-21 09:00:00 -0300
categories: [News]
permalink: /posts/news-22-10-26/
tags: [cybersecurity, vulnerabilities, threat-intelligence, breaches, malware]
pin: false
toc: true
comments: true
description: "Daily cybersecurity news covering vulnerabilities, adversaries, trends, breaches, and other notable security developments."
image:
  path: assets/img/posts/newsfeed-2026-10-22.png
  alt: Cybersecurity Newsfeed - 22/10/26
---

# Cybersecurity Newsfeed

## 📅 22/10/26

## 🛡️ Vulnerabilities

- **Critical GitLab Remote Code Execution (CVE-2026-97229)**: GitLab released urgent updates for a maximum-severity flaw (CVSS 10.0) allowing unauthenticated remote code execution on self-managed Community and Enterprise Edition servers under specific conditions. Rapid7 verified the exploit path, executing commands with `git` user privileges. Administrators are urged to update to fixed versions (19.2.x, 19.3.x, or 19.4.2) immediately. [More info](https://thehackernews.com/2026/10/critical-gitlab-flaw-cvss-100-could.html)

- **CISA Warns of Active "Plex2Shell" Exploitation**: Threat actors are chaining four medium-to-high severity flaws (CVE-2026-96652, CVE-2026-96654, CVE-2026-96655, and CVE-2026-96656) in Plex Media Server prior to version 1.43.3.10861 into a critical 9.8-rated exploit chain. The exploit grants unauthenticated arbitrary code execution to plant malicious shared libraries, deploy cryptominers, and install Linux proxy backdoors. [More info](https://www.bleepingcomputer.com/news/security/cisa-hackers-chain-plex-flaws-in-plex2shell-attacks-to-breach-servers/)

- **Ransomware Groups Exploit Palo Alto GlobalProtect (CVE-2026-0257)**: Qilin (Spikey Scorpius) and INC Ransomware (Tarnished Scorpius) are actively exploiting an authentication bypass flaw (CVSS 7.8) in Palo Alto Networks GlobalProtect. Attackers leverage the vulnerability to establish unauthorized VPN sessions, bypass MFA controls, perform internal reconnaissance, and deploy ransomware. [More info](https://www.helpnetsecurity.com/2026/10/21/ransomware-groups-exploit-palo-alto-globalprotect-cve-2026-0257/)

## 🎯 Adversaries

- **Lazarus Group Deploys Post-Quantum Cryptography**: Lazarus is using post-quantum cryptography to protect C2 communications and payload delivery. Targeting South Korean companies via GitHub phishing pages, the group abuses legitimate binaries like `fsquirt.exe` via INISAFE CrossWeb EX side-loading to deliver TechHub downloaders and the Cubridge backdoor in memory. [More info](https://www.bleepingcomputer.com/news/security/lazarus-hackers-use-post-quantum-cryptography-for-malware-delivery/)

- **Bronze Sandcastle Weaponizes Sandboxie DLL Sideloading**: The China-aligned threat actor is abusing Sandboxie alongside Java (`javaw.exe`), Krita (`Krita.exe`), and Sysinternals utilities (`vmmap.exe`) across Asia and Africa. By side-loading malicious libraries via trusted software, the group bypasses traditional antivirus tools to execute arbitrary code and maintain persistent access. [More info](https://thehackernews.com/2026/10/china-aligned-bronze-sandcastle-abuses.html)

- **Partisan Zmiy Conceals Vasilek Backdoor in VMware Tools**: In a two-year espionage campaign targeting a medical organization, attackers replaced authentic system files (`vmtoolsd.exe`, `vmtools.dll`) with malicious binaries while mimicking legitimate timestamps. Custom loaders disguised as Windows services executed the Vasilek backdoor and GOST proxies to facilitate lateral movement. [More info](https://thehackernews.com/2026/10/hackers-hid-vasilek-backdoor-in-vmware.html)

- **Fake "Amazon Artists" Portal Targets YouTube Creators**: A phishing campaign hosting a spoofed portal on `amazonyt[.]com` uses embedded Google API keys to extract real-time channel metrics and build trust with creators. Victims are redirected to `youtubechannelverification[.]com` to harvest credentials and MFA codes, allowing attackers to hijack high-value channels for crypto scams. [More info](https://www.malwarebytes.com/blog/threat-intel/2026/10/fake-amazon-music-x-youtube-deal-lures-creators-into-a-google-login-trap)

- **300+ Tor Exit Nodes Hijacked by Ebury Backdoor**: Threat actors infected Linux servers running over 7% of Tor's total exit capacity with OpenSSH backdoor Ebury 1.8.3. While standard web traffic passed normally, outgoing SSH connections on port 22 were redirected to 12 attacker-controlled interception servers to harvest SSH credentials. Tor has removed the malicious relays from the network consensus. [More info](https://thehackernews.com/2026/10/attackers-hijacked-over-300-tor-exit.html)

## 📈 Trends

- **Critical Entropy Flaw Exposes eMudhra Private Keys**: Indian CA eMudhra generated private keys for eight intermediate certificates with trivial integer values due to a script error. The flaw allows unauthenticated actors to derive keys, forge valid TLS certificates, and perform MITM attacks. eMudhra revoked the intermediate certificates, and major browsers (Chrome, Firefox, Apple, Microsoft) blocked them. [More info](https://www.helpnetsecurity.com/2026/10/21/emudhra-certificates-private-keys-compromised/) | [More info](https://www.bleepingcomputer.com/news/security/mozilla-google-apple-block-compromised-emudhra-ca-certificates/)

## 💥 Breaches & Leaks

- **LiteLLM Supply Chain Attack via Compromised Trivy Pipeline**: Threat group TeamPCP compromised Trivy's CI/CD pipeline to steal PyPI publishing tokens and release malicious LiteLLM packages (versions 1.82.7 and 1.82.8). The malicious scripts exfiltrated cloud credentials, SSH keys, and Kubernetes tokens encrypted via hybrid AES-256/RSA-4096, establishing persistence via a hidden `systemd` service. [More info](https://www.theregister.com/security/2026/10/21/litellm-supply-chain-attack-hoovers-up-passwords-and-secrets/5304548)

- **Stolen UpdraftCentral Keys Used to Backdoor WordPress Sites**: Attackers compromised TeamUpdraft's database and stole API keys for UpdraftCentral, UpdraftVault, and UpdraftClone. The stolen keys were used to issue remote commands to connected UpdraftPlus sites, deploying over 100 backdoor plugin variants to establish rogue administrator accounts. [More info](https://www.bleepingcomputer.com/news/security/stolen-updraftcentral-keys-used-to-backdoor-wordpress-sites/)

## 📚 Others

- **Microsoft PowerToys Adds CursorHide and Button Lock Tools**: The latest PowerToys release introduces CursorHide (hiding the mouse cursor via hotkeys or idle triggers) and Button Lock (locking mouse buttons for drag operations or accidental click prevention) to enhance productivity for Windows users. [More info](https://www.bleepingcomputer.com/news/microsoft/microsoft-powertoys-adds-cursorhide-button-lock-mouse-tools/)

---

[⬅ Back to Archive](https://pranakn.github.io)
