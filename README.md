# Awesome Security Tools 2026 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![GitHub stars](https://img.shields.io/github/stars/spinov001-art/awesome-security-tools-2026?style=social)](https://github.com/spinov001-art/awesome-security-tools-2026)
[![Last Updated](https://img.shields.io/badge/last%20updated-March%202026-brightgreen)](https://github.com/spinov001-art/awesome-security-tools-2026)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/spinov001-art/awesome-security-tools-2026/pulls)

> A curated list of 100+ cybersecurity tools for penetration testers, bug bounty hunters, security engineers, and DevSecOps professionals in 2026.

## Contents

- [Vulnerability Scanners](#vulnerability-scanners)
- [Network Security](#network-security)
- [Web Application Security](#web-application-security)
- [SAST & DAST](#sast--dast)
- [Container Security](#container-security)
- [Cloud Security](#cloud-security)
- [Secret Detection](#secret-detection)
- [Reconnaissance](#reconnaissance)
- [Exploitation Frameworks](#exploitation-frameworks)
- [Password & Credential Tools](#password--credential-tools)
- [Forensics & Incident Response](#forensics--incident-response)
- [OSINT](#osint)
- [Malware Analysis](#malware-analysis)
- [Bug Bounty Platforms](#bug-bounty-platforms)
- [Learning Resources](#learning-resources)

---

## Vulnerability Scanners

- [Nuclei](https://github.com/projectdiscovery/nuclei) — Fast, template-based vulnerability scanner. 22K+ stars
- [Nmap](https://nmap.org) — The gold standard network scanner and security auditor
- [OpenVAS](https://www.openvas.org) — Full-featured open-source vulnerability assessment system
- [Nikto](https://github.com/sullo/nikto) — Web server scanner for dangerous files and misconfigurations
- [Trivy](https://github.com/aquasecurity/trivy) — All-in-one security scanner (containers, IaC, repos). 24K+ stars
- [Wapiti](https://wapiti-scanner.github.io) — Web application vulnerability scanner
- [Vuls](https://github.com/future-architect/vuls) — Agent-less vulnerability scanner for Linux/FreeBSD
- [Tsunami](https://github.com/google/tsunami-security-scanner) — General-purpose network security scanner by Google

## Network Security

- [Wireshark](https://www.wireshark.org) — World's foremost network protocol analyzer
- [Suricata](https://suricata.io) — High-performance network IDS, IPS, and security monitoring
- [Zeek](https://zeek.org) — Powerful network analysis framework (formerly Bro)
- [Snort](https://www.snort.org) — Open-source intrusion detection/prevention system
- [Scapy](https://scapy.net) — Python-based packet manipulation library
- [Masscan](https://github.com/robertdavidgraham/masscan) — Internet-scale port scanner (10M packets/sec)
- [Zmap](https://zmap.io) — Fast single-packet network scanner
- [Netcat](https://nmap.org/ncat/) — Versatile networking utility (the Swiss Army knife of networking)

## Web Application Security

- [Burp Suite](https://portswigger.net/burp) — Industry-standard web vulnerability scanner (Community edition free)
- [OWASP ZAP](https://www.zaproxy.org) — Free web application security scanner
- [SQLMap](https://sqlmap.org) — Automatic SQL injection and database takeover tool
- [ffuf](https://github.com/ffuf/ffuf) — Fast web fuzzer written in Go. 13K+ stars
- [Wfuzz](https://github.com/xmendez/wfuzz) — Web application fuzzer
- [Dirsearch](https://github.com/maurosoria/dirsearch) — Web path discovery tool
- [Gobuster](https://github.com/OJ/gobuster) — Directory/file & DNS busting tool in Go
- [httpx](https://github.com/projectdiscovery/httpx) — Fast multi-purpose HTTP toolkit. 8K+ stars
- [Katana](https://github.com/projectdiscovery/katana) — Next-gen crawling and spidering framework

## SAST & DAST

- [Semgrep](https://semgrep.dev) — Lightweight static analysis for many languages. 11K+ stars
- [SonarQube](https://www.sonarqube.org) — Continuous code quality and security inspection
- [Bandit](https://github.com/PyCQA/bandit) — Security linter for Python code
- [Brakeman](https://brakemanscanner.org) — Static analysis for Ruby on Rails security
- [CodeQL](https://codeql.github.com) — GitHub's semantic code analysis engine
- [Bearer](https://github.com/Bearer/bearer) — Code security scanning for data flows
- [Snyk Code](https://snyk.io/product/snyk-code/) — Real-time static analysis powered by AI
- [Checkov](https://github.com/bridgecrewio/checkov) — Static analysis for IaC security

## Container Security

- [Trivy](https://github.com/aquasecurity/trivy) — Comprehensive container/image scanner
- [Grype](https://github.com/anchore/grype) — Vulnerability scanner for container images
- [Falco](https://falco.org) — Cloud-native runtime security (CNCF project)
- [Clair](https://github.com/quay/clair) — Static analysis of vulnerabilities in containers
- [Docker Bench](https://github.com/docker/docker-bench-security) — Docker security best practices checker
- [Kubescape](https://github.com/kubescape/kubescape) — Kubernetes security platform. 10K+ stars
- [kube-hunter](https://github.com/aquasecurity/kube-hunter) — Hunt for security weaknesses in Kubernetes

## Cloud Security

- [Prowler](https://github.com/prowler-cloud/prowler) — AWS/Azure/GCP security assessment tool. 11K+ stars
- [ScoutSuite](https://github.com/nccgroup/ScoutSuite) — Multi-cloud security auditing tool
- [CloudSploit](https://github.com/aquasecurity/cloudsploit) — Cloud security configuration monitoring
- [Steampipe](https://steampipe.io) — Query cloud infrastructure with SQL
- [Cartography](https://github.com/lyft/cartography) — Infrastructure attack surface mapping
- [Pacu](https://github.com/RhinoSecurityLabs/pacu) — AWS exploitation framework

## Secret Detection

- [TruffleHog](https://github.com/trufflesecurity/trufflehog) — Find leaked credentials in git repos. 17K+ stars
- [GitLeaks](https://github.com/gitleaks/gitleaks) — SAST tool for detecting secrets in git. 18K+ stars
- [detect-secrets](https://github.com/Yelp/detect-secrets) — Enterprise-friendly secrets detection by Yelp
- [SpectralOps](https://spectralops.io) — Monitors for exposed secrets, tokens, and credentials
- [git-secrets](https://github.com/awslabs/git-secrets) — Prevents committing secrets to git (by AWS)

## Reconnaissance

- [Subfinder](https://github.com/projectdiscovery/subfinder) — Fast passive subdomain enumeration. 10K+ stars
- [Amass](https://github.com/owasp-amass/amass) — In-depth attack surface mapping and asset discovery
- [theHarvester](https://github.com/laramies/theHarvester) — E-mails, subdomains, and names harvester
- [Shodan](https://www.shodan.io) — Search engine for Internet-connected devices
- [Censys](https://censys.io) — Internet-wide scanning platform
- [Recon-ng](https://github.com/lanmaster53/recon-ng) — Full-featured web reconnaissance framework
- [dnsrecon](https://github.com/darkoperator/dnsrecon) — DNS enumeration and reconnaissance

## Exploitation Frameworks

- [Metasploit](https://www.metasploit.com) — The world's most used penetration testing framework
- [Cobalt Strike](https://www.cobaltstrike.com) — Adversary simulation and red team operations (commercial)
- [Empire](https://github.com/BC-SECURITY/Empire) — Post-exploitation PowerShell/Python/C# agent
- [Sliver](https://github.com/BishopFox/sliver) — Open-source adversary emulation framework. 9K+ stars
- [Covenant](https://github.com/cobbr/Covenant) — .NET-based C2 framework

## Password & Credential Tools

- [Hashcat](https://hashcat.net) — World's fastest password recovery utility
- [John the Ripper](https://www.openwall.com/john/) — Open-source password security auditing
- [Hydra](https://github.com/vanhauser-thc/thc-hydra) — Fast online password cracking tool
- [CrackMapExec](https://github.com/byt3bl33d3r/CrackMapExec) — Swiss army knife for pentesting networks
- [Mimikatz](https://github.com/gentilkiwi/mimikatz) — Windows credential extraction tool

## Forensics & Incident Response

- [Volatility](https://github.com/volatilityfoundation/volatility3) — Memory forensics framework
- [Velociraptor](https://github.com/Velocidex/velociraptor) — Endpoint visibility and collection tool
- [TheHive](https://thehive-project.org) — Security incident response platform
- [GRR](https://github.com/google/grr) — Remote live forensics for incident response (Google)
- [YARA](https://github.com/VirusTotal/yara) — Pattern matching for malware researchers
- [Autopsy](https://www.autopsy.com) — Digital forensics platform

## OSINT

- [Maltego](https://www.maltego.com) — Open-source intelligence and graphical link analysis
- [SpiderFoot](https://github.com/smicallef/spiderfoot) — Automates OSINT collection. 13K+ stars
- [Sherlock](https://github.com/sherlock-project/sherlock) — Hunt usernames across social networks. 60K+ stars
- [Photon](https://github.com/s0md3v/Photon) — Incredibly fast web crawler for OSINT
- [Holehe](https://github.com/megadose/holehe) — Check if an email is used on different sites
- [Maigret](https://github.com/soxoj/maigret) — Collect dossier on a person by username

## Malware Analysis

- [Ghidra](https://ghidra-sre.org) — NSA's software reverse engineering framework
- [Cuckoo Sandbox](https://cuckoosandbox.org) — Automated malware analysis system
- [FLARE VM](https://github.com/mandiant/flare-vm) — Windows-based malware analysis distribution
- [REMnux](https://remnux.org) — Linux toolkit for reverse-engineering malware
- [Any.Run](https://any.run) — Interactive malware analysis service
- [VirusTotal](https://www.virustotal.com) — Analyze suspicious files, URLs, and domains

## Bug Bounty Platforms

- [HackerOne](https://www.hackerone.com) — World's largest ethical hacker community
- [Bugcrowd](https://www.bugcrowd.com) — Bug bounty and vulnerability disclosure platform
- [Intigriti](https://www.intigriti.com) — European bug bounty platform
- [Synack](https://www.synack.com) — Premier security testing platform
- [YesWeHack](https://www.yeswehack.com) — Global bug bounty and VDP platform

## Learning Resources

- [PortSwigger Web Security Academy](https://portswigger.net/web-security) — Free web security training
- [HackTheBox](https://www.hackthebox.com) — Cybersecurity training platform
- [TryHackMe](https://tryhackme.com) — Learn cybersecurity with hands-on labs
- [PentesterLab](https://pentesterlab.com) — Learn web penetration testing
- [OWASP Top 10](https://owasp.org/www-project-top-ten/) — Top 10 web application security risks
- [CyberDefenders](https://cyberdefenders.org) — Blue team training platform

---

## Related Awesome Lists

- [Awesome MCP Tools 2026](https://github.com/spinov001-art/awesome-mcp-tools-2026) — 130+ Model Context Protocol tools
- [Awesome Web Scraping 2026](https://github.com/spinov001-art/awesome-web-scraping-2026) — 150+ web scraping tools
- [Awesome AI Tools 2026](https://github.com/spinov001-art/awesome-ai-tools-2026) — 150+ AI/ML tools
- [Awesome DevOps Tools 2026](https://github.com/spinov001-art/awesome-devops-tools-2026) — 120+ DevOps tools
- [Awesome Automation Tools 2026](https://github.com/spinov001-art/awesome-automation-tools-2026) — 130+ automation tools

## Contributing

Contributions welcome! Open a PR if you know a security tool not listed here.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
