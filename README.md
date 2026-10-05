# Awesome Security

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A curated collection of fantastic software, libraries, documents, books, and resources dedicated to security. From network and endpoint protection to threat intelligence and web security — a comprehensive list to enhance your security knowledge and practices.

---

## 🌐 Network

### 🔍 Scanning / Pentesting

* [Metasploit Framework](https://github.com/rapid7/metasploit-framework) – tool for developing and executing exploit code against a remote target machine.
* [Nmap](https://nmap.org) – free and open source utility for network discovery and security auditing.
* [Nuclei](https://github.com/projectdiscovery/nuclei) – fast, customizable vulnerability scanner based on simple YAML-based templates.
* [OpenVAS](https://www.openvas.org/) – framework of services and tools offering comprehensive vulnerability scanning and management.
* [pig](https://github.com/rafael-santiago/pig) – Linux packet crafting tool.
* [Pompem](https://github.com/rfunix/Pompem) – open source tool to automate the search for exploits in major databases.
* [scapy](https://github.com/secdev/scapy) – Python-based interactive packet manipulation program and library.

### 📊 Monitoring / Logging

* [Fibratus](https://github.com/rabbitstack/fibratus) – tool for exploration and tracing of the Windows kernel activity.
* [httpry](https://github.com/jbittel/httpry) – specialized packet sniffer for displaying and logging HTTP traffic.
* [justniffer](https://github.com/onotelli/justniffer) – network protocol analyzer that captures traffic and produces customized logs.
* [ngrep](https://github.com/jpr5/ngrep) – pcap-aware tool applying grep-like features to the network layer.
* [ntopng](https://www.ntop.org/products/traffic-analysis/ntop/) – network traffic probe showing usage similar to the Unix `top` command.
* [passivedns](https://github.com/gamelinux/passivedns) – tool to collect DNS records passively for incident handling and NSM.
* [sagan](https://sagan.readthedocs.io/) – multi-threaded, real-time log analysis engine with a Snort-like rule set.

### 🛡️ IDS / IPS / Host IDS / Host IPS

* [AIEngine](https://bitbucket.org/camp0/aiengine) – next generation interactive Python/Ruby/Java/Lua packet inspection engine with NIDS functionality.
* [Denyhosts](https://github.com/denyhosts/denyhosts) – thwart SSH dictionary-based and brute force attacks.
* [Fail2Ban](https://www.fail2ban.org/) – scans log files and takes action on IPs that show malicious behavior.
* [Falco](https://falco.org/) – cloud-native runtime security tool for detecting unexpected behavior in Linux systems.
* [Lynis](https://cisofy.com/lynis/) – open source security auditing tool for Linux/Unix.
* [OSSEC](https://ossec.github.io/) – comprehensive open source HIDS performing log analysis, file integrity, rootkit detection and alerting.
* [Security Onion](https://securityonionsolutions.com/) – Linux distro for intrusion detection, network security monitoring, and log management.
* [Snort](https://www.snort.org/) – free and open source network intrusion prevention and detection system.
* [SSHGuard](https://www.sshguard.net/) – software protecting services in addition to SSH, written in C.
* [sshwatch](https://github.com/marshyski/sshwatch) – IPS for SSH written in Python, gathers attacker information during attacks.
* [Stealth](https://fbb-git.github.io/stealth/) – file integrity checker that leaves virtually no sediment on the monitored host.
* [Suricata](https://suricata.io/) – high performance Network IDS, IPS and Network Security Monitoring engine.
* [Wazuh](https://wazuh.com/) – open source security platform unifying SIEM, XDR, and cloud security capabilities.
* [Zeek](https://zeek.org/) – powerful network analysis framework (formerly Bro).

### 🍯 Honey Pot / Honey Net

* [Amun](https://github.com/zeroq/amun) – Python-based low-interaction honeypot.
* [awesome-honeypots](https://github.com/paralax/awesome-honeypots) – the canonical awesome honeypot list.
* [Bifrozt](https://github.com/Bifrozt/bifrozt-ansible) – NAT device that works as a transparent SSHv2 proxy between an attacker and your honeypot.
* [Conpot](http://conpot.org/) – ICS/SCADA low-interactive server-side honeypot.
* [Cuckoo Sandbox](https://cuckoosandbox.org/) – open source software for automating analysis of suspicious files.
* [Dionaea](https://github.com/DinoTools/dionaea) – nepenthes successor honeypot embedding Python as scripting language.
* [Glastopf](https://github.com/mushorg/glastopf) – honeypot emulating thousands of vulnerabilities to gather web attack data.
* [HoneyDrive](https://bruteforce.gr/honeydrive/) – premier honeypot Linux distro with over 10 pre-installed honeypot packages.
* [HoneyPy](https://github.com/foospidy/HoneyPy) – low to medium interaction honeypot, easy to deploy and extend.
* [HonSSH](https://github.com/tnich/honssh) – high-interaction honeypot sitting between an attacker and a honeypot over SSH.
* [Kippo](https://github.com/desaster/kippo) – medium interaction SSH honeypot for logging brute force attacks.
* [Kojoney](https://github.com/sec-tools/kojoney) – low level interaction honeypot emulating an SSH server.

### 🗂️ Full Packet Capture / Forensic

* [Dshell](https://github.com/USArmyResearchLab/Dshell) – network forensic analysis framework enabling rapid development of dissection plugins.
* [Moloch](https://github.com/aol/moloch) – open source large scale IPv4 packet capturing, indexing and database system.
* [OpenFPC](https://github.com/leonward/OpenFPC) – lightweight full-packet network traffic recorder and buffering system.
* [stenographer](https://github.com/google/stenographer) – packet capture solution that spools all packets to disk for fast subset access.
* [tcpflow](https://github.com/simsong/tcpflow) – captures TCP connection data and stores it for protocol analysis and debugging.
* [Xplico](https://www.xplico.org/) – open source Network Forensic Analysis Tool extracting applications data from captures.

### 🔬 Sniffer

* [netsniff-ng](http://netsniff-ng.org/) – free Linux networking toolkit using zero-copy mechanisms for high performance.
* [Wireshark](https://www.wireshark.org) – free and open-source packet analyzer with graphical front-end and filtering options.

### 📋 Security Information & Event Management

* [FIR](https://github.com/certsocietegenerale/FIR) – Fast Incident Response, a cybersecurity incident management platform.
* [OSSIM](https://cybersecurity.att.com/products/ossim) – AT&T Cybersecurity SIEM with event collection, normalization, and correlation.
* [Prelude](https://www.prelude-siem.org/) – universal SIEM collecting, normalizing, aggregating and correlating security events.

### 🔐 VPN

* [OpenVPN](https://openvpn.net/) – open source VPN using a custom security protocol utilizing SSL/TLS for key exchange.
* [WireGuard](https://www.wireguard.com/) – extremely simple yet fast and modern VPN utilizing state-of-the-art cryptography.

### ⚡ Fast Packet Processing

* [DPDK](https://www.dpdk.org/) – set of libraries and drivers for fast packet processing.
* [netmap](https://github.com/luigirizzo/netmap) – framework for high speed packet I/O available for FreeBSD, Linux and Windows.
* [PACKET_MMAP/TPACKET/AF_PACKET](https://www.kernel.org/doc/html/latest/networking/packet_mmap.html) – Linux kernel mechanism for high-performance packet capture and transmission.
* [PF_RING](https://www.ntop.org/products/packet-capture/pf_ring/) – network socket dramatically improving packet capture speed.
* [PF_RING ZC (Zero Copy)](https://www.ntop.org/products/packet-capture/pf_ring/pf_ring-zc-zero-copy/) – flexible packet processing framework achieving line rate at any packet size.
* [PFQ](https://github.com/pfq/PFQ) – functional networking framework for efficient packet capture and in-kernel processing.

### 🔥 Firewall

* [fwknop](https://www.cipherdyne.org/fwknop/) – protects ports via Single Packet Authorization.
* [OPNsense](https://opnsense.org/) – open source, easy-to-use FreeBSD-based firewall and routing platform.
* [pfSense](https://www.pfsense.org/) – firewall and Router FreeBSD distribution.

### 📧 Anti-Spam

* [SpamAssassin](https://spamassassin.apache.org/) – powerful and popular email spam filter employing a variety of detection techniques.

### 🐳 Docker Images for Penetration Testing & Security

* `docker pull kalilinux/kali-rolling` – [official Kali Linux](https://hub.docker.com/r/kalilinux/kali-rolling)
* `docker pull ghcr.io/zaproxy/zaproxy:stable` – [official OWASP ZAP](https://github.com/zaproxy/zaproxy)
* `docker pull wpscanteam/wpscan` – [official WPScan](https://hub.docker.com/r/wpscanteam/wpscan/)
* `docker pull metasploitframework/metasploit-framework` – [Metasploit](https://hub.docker.com/r/metasploitframework/metasploit-framework/)
* `docker pull citizenstig/dvwa` – [Damn Vulnerable Web Application](https://hub.docker.com/r/citizenstig/dvwa/)
* `docker pull hmlio/vaas-cve-2014-6271` – [Vulnerability as a service: Shellshock](https://hub.docker.com/r/hmlio/vaas-cve-2014-6271/)
* `docker pull hmlio/vaas-cve-2014-0160` – [Vulnerability as a service: Heartbleed](https://hub.docker.com/r/hmlio/vaas-cve-2014-0160/)
* `docker pull opendns/security-ninjas` – [Security Ninjas](https://hub.docker.com/r/opendns/security-ninjas/)
* `docker pull ismisepaul/securityshepherd` – [OWASP Security Shepherd](https://hub.docker.com/r/ismisepaul/securityshepherd/)

---

## 💻 Endpoint

### 🦠 Anti-Virus / Anti-Malware

* [ClamAV](https://www.clamav.net/) – open source antivirus engine for detecting trojans, viruses, malware and other threats.
* [Linux Malware Detect](https://www.rfxn.com/projects/linux-malware-detect/) – malware scanner for Linux designed around threats in shared hosted environments.

### 🧹 Content Disarm & Reconstruct

* [DocBleach](https://github.com/docbleach/DocBleach) – open-source CDR software sanitizing Office, PDF and RTF documents.

### ⚙️ Configuration Management

* [Rudder](https://www.rudder.io/) – web-driven, role-based solution for IT Infrastructure Automation and Compliance.

### 🔑 Authentication

* [google-authenticator](https://github.com/google/google-authenticator) – implementations of one-time passcode generators and a PAM module.

### 📱 Mobile / Android / iOS

* [android-security-awesome](https://github.com/ashishb/android-security-awesome) – collection of Android security related resources.
* [OWASP Mobile Security Testing Guide](https://github.com/OWASP/owasp-mstg) – comprehensive manual for mobile app security testing and reverse engineering.
* [OSX Security Awesome](https://github.com/kai5263499/osx-security-awesome) – collection of OSX and iOS security resources.

### 🔍 Forensics

* [grr](https://github.com/google/grr) – GRR Rapid Response is an incident response framework focused on remote live forensics.
* [ir-rescue](https://github.com/diogo-fernan/ir-rescue) – Windows Batch and Unix Bash scripts to collect host forensic data during incident response.
* [mig](https://github.com/mozilla/mig) – platform to perform investigative surgery on remote endpoints in parallel.
* [Velociraptor](https://github.com/Velocidex/velociraptor) – tool for collecting host-based state information using Velociraptor Query Language.
* [Volatility](https://github.com/volatilityfoundation/volatility3) – Python-based memory extraction and analysis framework.

---

## 🕵️ Threat Intelligence

* [abuse.ch](https://abuse.ch/) – tracks Command&Control servers and provides domain and IP blocklists.
* [AlienVault Open Threat Exchange](https://otx.alienvault.com/) – collaborative threat intelligence network.
* [AutoShun](https://www.autoshun.org/) – Snort plugin correlating attacks across sensors, honeypots and mail filters worldwide.
* [CIFv2](https://github.com/csirtgadgets/massive-octo-spice) – cyber threat intelligence management system combining malicious threat information from many sources.
* [CriticalStack](https://intel.criticalstack.com/) – free aggregated threat intel for the Zeek network security monitoring platform.
* [DNS-BH](https://www.malwaredomains.com/) – listing of domains known to propagate malware and spyware.
* [Emerging Threats - Open Source](https://doc.emergingthreats.net/) – open source community providing Suricata and Snort rules, firewall rules and IDS rulesets.
* [FireEye OpenIOCs](https://github.com/fireeye/iocs) – FireEye publicly shared Indicators of Compromise.
* [IntelMQ](https://github.com/certtools/intelmq/) – solution for CERTs for collecting and processing security feeds using a message queue protocol.
* [Internet Storm Center](https://www.dshield.org/reports.html) – free analysis and warning service for Internet threats.
* [MISP](https://www.misp-project.org/) – open source threat intelligence and sharing platform.
* [OpenVAS NVT Feed](https://www.openvas.org/openvas-nvt-feed.html) – public feed of Network Vulnerability Tests containing 35,000+ NVTs.
* [PhishTank](https://www.phishtank.com/) – collaborative clearing house for phishing data with open API.
* [Project Honey Pot](https://www.projecthoneypot.org/) – distributed system for identifying spammers and harvesting bots.
* [SBL / XBL / PBL / DBL / DROP / ROKSO](https://www.spamhaus.org/) – Spamhaus real-time anti-spam protection and blocklists.
* [TheHive](https://thehive-project.org/) – scalable, open source security incident response platform.
* [Tor Bulk Exit List](https://metrics.torproject.org/collector.html) – CollecTor data-collecting service providing Tor network data.
* [virustotal](https://www.virustotal.com/) – free online service analyzing files and URLs for malicious content detected by 70+ AV engines.

---

## 🌍 Web

### 🏢 Organization

* [OWASP](https://owasp.org) – the Open Web Application Security Project, focused on improving the security of software.

### 🛡️ Web Application Firewall

* [ironbee](https://github.com/ironbee/ironbee) – open source universal web application security sensor and WAF framework.
* [ModSecurity](https://github.com/SpiderLabs/ModSecurity) – toolkit for real-time web application monitoring, logging, and access control.
* [NAXSI](https://github.com/nbs-system/naxsi) – open-source, high performance, low rules maintenance WAF for NGINX.
* [sql_firewall](https://github.com/uptimejp/sql_firewall) – SQL Firewall extension for PostgreSQL.

### 🔍 Scanning / Pentesting

* [ACSTIS](https://github.com/tijme/angularjs-csti-scanner) – scans web applications for AngularJS Client-Side Template Injection vulnerabilities.
* [Infection Monkey](https://github.com/guardicore/monkey) – semi-automatic pen testing tool for mapping and pen-testing networks.
* [Nikto](https://github.com/sullo/nikto) – open source web server scanner performing comprehensive tests against web servers.
* [OWASP Testing Checklist v4](https://owasp.org/www-project-web-security-testing-guide/) – list of controls to test during a web vulnerability assessment.
* [PTF](https://github.com/trustedsec/ptf) – Penetration Testers Framework providing modular support for up-to-date tools.
* [Recon-ng](https://github.com/lanmaster53/recon-ng) – full-featured Web Reconnaissance framework written in Python.
* [sqlmap](https://sqlmap.org/) – open source penetration testing tool automating detection and exploitation of SQL injection.
* [w3af](https://w3af.org/) – Web Application Attack and Audit Framework.
* [ZAP](https://www.zaproxy.org/) – OWASP Zed Attack Proxy, easy-to-use integrated penetration testing tool.

### ⚡ Runtime Application Self-Protection

* [Sqreen](https://www.sqreen.io/) – Runtime Application Self-Protection solution instrumenting and monitoring the app at runtime.

### 👨‍💻 Development

* [OAuth 2 in Action](https://www.manning.com/books/oauth-2-in-action) – book teaching practical use and deployment of OAuth 2.
* [Secure by Design](https://www.manning.com/books/secure-by-design) – book identifying design patterns and coding styles that reduce security vulnerabilities.
* [Securing DevOps](https://www.manning.com/books/securing-devops) – book exploring how DevOps and Security techniques apply together for safer cloud services.
* [Semgrep](https://semgrep.dev/) – fast, open source static analysis tool for finding bugs and enforcing code standards.
* [Understanding API Security](https://www.manning.com/books/understanding-api-security) – free eBook on how APIs are put together and how OAuth protects them.

---

## 🎯 Usability

* [Usable Security Course](https://www.coursera.org/learn/usable-security) – Coursera course on the intersection of security and usability.

---

## 📊 Big Data

* [Apache Metron](https://github.com/apache/metron) – integrates open source big data technologies for centralized security monitoring and analysis.
* [Apache Spot](https://github.com/apache/spot) – open source software for leveraging insights from flow and packet analysis.
* [binarypig](https://github.com/endgameinc/binarypig) – scalable binary data extraction in Hadoop for malware processing and analytics.
* [data_hacking](https://github.com/ClickSecurity/data_hacking) – examples using IPython, Pandas, and Scikit Learn to get the most out of security data.
* [hadoop-pcap](https://github.com/RIPE-NCC/hadoop-pcap) – Hadoop library to read packet capture (PCAP) files.
* [OpenSOC](https://github.com/OpenSOC/opensoc) – integrates open source big data technologies for centralized security monitoring.
* [Workbench](https://github.com/SuperCowPowers/workbench) – scalable Python framework for security research and development teams.

---

## 🗄️ Datastores

* [aws-vault](https://github.com/99designs/aws-vault) – store AWS credentials in the OSX Keychain or an encrypted file.
* [blackbox](https://github.com/StackExchange/blackbox) – safely store secrets in a VCS repo using GPG.
* [chamber](https://github.com/segmentio/chamber) – store secrets using AWS KMS and SSM Parameter Store.
* [confidant](https://github.com/lyft/confidant) – stores secrets in AWS DynamoDB, encrypted at rest and integrated with IAM.
* [credstash](https://github.com/fugue/credstash) – store secrets using AWS KMS and DynamoDB.
* [dotgpg](https://github.com/ConradIrwin/dotgpg) – tool for backing up and versioning production secrets or shared passwords securely.
* [passbolt](https://www.passbolt.com/) – open source, extensible password manager based on OpenPGP.
* [redoctober](https://github.com/cloudflare/redoctober) – server for two-man rule style file encryption and decryption.
* [Safe](https://github.com/starkandwayne/safe) – a Vault CLI making reading and writing to Vault easier.
* [Sops](https://github.com/mozilla/sops) – editor of encrypted files supporting YAML, JSON and BINARY formats with AWS KMS and PGP.
* [Vault](https://www.vaultproject.io/) – encrypted datastore secure enough to hold environment and application secrets.

---

## 🚀 DevOps

* [Checkov](https://www.checkov.io/) – static code analysis tool for infrastructure-as-code detecting security misconfigurations.
* [Securing DevOps](https://www.manning.com/books/securing-devops) – book on security techniques for DevOps reviewing state-of-the-art practices.
* [tfsec](https://github.com/aquasecurity/tfsec) – static analysis security scanner for Terraform code.

---

## 🖥️ Operating Systems

### 🌐 Online Resources

* [Best Linux Penetration Testing Distributions @ CyberPunk](https://n0where.net/best-linux-penetration-testing-distributions/) – description of main penetration testing distributions.
* [Security @ Distrowatch](https://distrowatch.com/search.php?category=Security) – website reviewing and tracking open source security operating systems.
* [Security related Operating Systems @ Rawsec](https://inventory.raw.pm/) – complete list of security related operating systems.

---

## ☸️ Kubernetes Security

* [Falco](https://falco.org/) – cloud-native runtime security detecting unexpected behavior and configuration changes.
* [Kube-bench](https://github.com/aquasecurity/kube-bench) – checks whether Kubernetes is deployed according to CIS security benchmarks.
* [Kube-hunter](https://github.com/aquasecurity/kube-hunter) – security scanner discovering vulnerabilities and security issues in Kubernetes clusters.
* [Kubernetes CIS Benchmark](https://www.cisecurity.org/benchmark/kubernetes/) – official CIS benchmark with security configuration guidelines for Kubernetes.
* [Kubesec](https://kubesec.io/) – scans Kubernetes resource manifests for security issues, providing risk scores.
* [Open Policy Agent (OPA)](https://www.openpolicyagent.org/) – general-purpose policy engine for fine-grained, context-aware policies in Kubernetes.
* [Trivy](https://github.com/aquasecurity/trivy) – comprehensive vulnerability scanner for container images, file systems and Kubernetes clusters.

---

## ☁️ Cloud Security

* [Azure Defender for Cloud](https://azure.microsoft.com/en-us/products/defender-for-cloud/) – Microsoft Azure's unified security management with advanced threat protection.
* [Cloud Custodian](https://cloudcustodian.io/) – cloud security policy automation tool managing governance across cloud environments.
* [Cloud Security Alliance](https://cloudsecurityalliance.org/) – provides best practices and security guidance for cloud computing environments.
* [GCP Security Command Center](https://cloud.google.com/security-command-center) – Google Cloud's security and risk management platform for threat detection and compliance.
* [Prowler](https://github.com/prowler-cloud/prowler) – open source cloud security tool for AWS, Azure and GCP security assessments and audits.
* [ScoutSuite](https://github.com/nccgroup/ScoutSuite) – multi-cloud security auditing tool providing comprehensive security posture assessments.

---

## 🐛 Vulnerability Management

* [Grype](https://github.com/anchore/grype) – vulnerability scanner for container images and filesystems.
* [Nessus](https://www.tenable.com/products/nessus) – widely used commercial vulnerability scanner.
* [OpenVAS](https://www.openvas.org/) – open source vulnerability scanner.
* [Qualys Community Edition](https://www.qualys.com/community-edition/) – free version of Qualys vulnerability scanner.
* [Rapid7 Nexpose](https://www.rapid7.com/products/nexpose/) – vulnerability and risk management scanner.
* [Vuls](https://github.com/future-architect/vuls) – vulnerability scanner for Linux, FreeBSD and containers.

---

## 👤 Identity / Access Management

* [HashiCorp Boundary](https://www.boundaryproject.io/) – infrastructure access management.
* [Keycloak](https://www.keycloak.org/) – open source Identity and Access Management.
* [OAuth 2.0](https://oauth.net/2/) – authorization standard.
* [OpenID Connect](https://openid.net/connect/) – identity layer on top of OAuth 2.0.

---

## ⚡ Serverless Security

* [OWASP Serverless Top 10](https://owasp.org/www-project-serverless-top-10/) – list of top threats in serverless applications.
* [PureSec](https://www.puresec.io/) – security for serverless functions.
* [Snyk Serverless](https://snyk.io/solutions/serverless-security/) – Snyk security scanning for serverless applications.

---

## 📚 Other Awesome Lists

* [Android Security Awesome](https://github.com/ashishb/android-security-awesome) – collection of Android security related resources.
* [Awesome CTF](https://github.com/apsdehal/awesome-ctf) – curated list of CTF frameworks, libraries, resources and software.
* [Awesome Cyber Skills](https://github.com/joe-shenouda/awesome-cyber-skills) – curated list of legal hacking environments to train cyber skills.
* [Awesome Hacking](https://github.com/carpedm20/awesome-hacking) – curated list of hacking tutorials, tools and resources.
* [Awesome Honeypots](https://github.com/paralax/awesome-honeypots) – awesome list of honeypot resources.
* [Awesome Incident Response](https://github.com/meirwah/awesome-incident-response) – curated list of resources for incident response.
* [Awesome Industrial Control System Security](https://github.com/mpesen/awesome-industrial-control-system-security) – resources related to ICS security.
* [Awesome Linux Containers](https://github.com/Friz-zy/awesome-linux-containers) – curated list of Linux Containers frameworks, libraries and software.
* [Awesome Malware Analysis](https://github.com/rshipp/awesome-malware-analysis) – curated list of malware analysis tools and resources.
* [Awesome PCAP Tools](https://github.com/caesar0301/awesome-pcaptools) – tools for processing network traces.
* [Awesome Pentest](https://github.com/enaqx/awesome-pentest) – collection of penetration testing resources, tools and shiny things.
* [Awesome Pentest Cheat Sheets](https://github.com/coreb1t/awesome-pentest-cheat-sheets) – cheat sheets useful for pentesting.
* [Awesome Threat Detection and Hunting](https://github.com/0x4D31/awesome-threat-detection) – curated list of threat detection and hunting resources.
* [Awesome Threat Intelligence](https://github.com/hslatman/awesome-threat-intelligence) – curated list of threat intelligence resources.
* [Awesome Web Hacking](https://github.com/infoslack/awesome-web-hacking) – list for learning about web application security.
* [Awesome YARA](https://github.com/InQuest/awesome-yara) – curated list of awesome YARA rules, tools, and people.

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

[MIT](LICENSE) © [Think Cube](https://github.com/Think-Cube)
