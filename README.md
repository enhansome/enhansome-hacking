# Awesome Hacking -An Amazing Project with stars

A curated list of awesome Hacking. Inspired by [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning/) ⭐ 74,018 | 🐛 25 | 🌐 Python | 📅 2026-08-11

If you want to contribute to this list (please do), send me a pull request!

For a list of free hacking books available for download, go [here](https://github.com/Hack-with-Github/Free-Security-eBooks) ⚠️ Archived

## Table of Contents

<!-- MarkdownTOC depth=4 -->

* [System](#system)
  * [Tutorials](#tutorials)
  * [Tools](#tools)
  * [Docker](#docker-images-for-penetration-testing--security)
  * [General](#general)
* [Reverse Engineering](#reverse-engineering)
  * [Tutorials](#tutorials-1)
  * [Tools](#tools-1)
  * [General](#general-1)
* [Web](#web)
  * [Tools](#tools-2)
  * [General](#general-2)
* [Network](#network)
  * [Tools](#tools-3)
* [Forensic](#forensic)
  * [Tools](#tools-4)
* [Cryptography](#cryptography)
  * [Tools](#tools-5)
* [Wargame](#wargame)
  * [System](#system-1)
  * [Reverse Engineering](#reverse-engineering-1)
  * [Web](#web-1)
  * [Cryptography](#cryptography-1)
  * [Bug bounty](#bug-bounty)
* [CTF](#ctf)
  * [Competition](#competition)
  * [General](#general-2)
* [OS](#os)
  * [Online resources](#online-resources)
* [Post exploitation](#post-exploitation)
  * [tools](#tools-6)
* [ETC](#etc)

<!-- /MarkdownTOC -->

# System

## Tutorials

* [Roppers Computing Fundamentals](https://www.roppers.org/courses/fundamentals)
  * Free, self-paced curriculum that builds a base of knowledge in computers and networking. Intended to build up a student with no prior technical knowledge to be confident in their ability to learn anything and continue their security education. Full text available as a [gitbook](https://www.hoppersroppers.org/fundamentals/).
* [Corelan Team's Exploit writing tutorial](https://www.corelan.be/index.php/2009/07/19/exploit-writing-tutorial-part-1-stack-based-overflows/)
* [Exploit Writing Tutorials for Pentesters](http://web.archive.org/web/20140916085343/http://www.punter-infosec.com/exploit-writing-tutorials-for-pentesters/)
* [Understanding the basics of Linux Binary Exploitation](https://github.com/r0hi7/BinExp) ⭐ 1,356 | 🐛 4 | 🌐 C | 📅 2021-06-15
* [Shells](https://www.youtube.com/playlist?list=PLyzOVJj3bHQuloKGG59rS43e29ro7I57J)
* [Missing Semester](https://missing.csail.mit.edu/2020/course-shell/)

## Tools

* [Metasploit](https://github.com/rapid7/metasploit-framework) ⭐ 38,799 | 🐛 610 | 🌐 Ruby | 📅 2026-08-13 A computer security project that provides information about security vulnerabilities and aids in penetration testing and IDS signature development.
* [mimikatz](https://github.com/gentilkiwi/mimikatz) ⭐ 21,769 | 🐛 196 | 🌐 C | 📅 2026-04-17 - A little tool to play with Windows security
* [Hackers tools](https://www.youtube.com/playlist?list=PLyzOVJj3bHQuiujH1lpn8cA9dsyulbYRv) - Tutorial on tools.

### Docker Images for Penetration Testing & Security

* `docker pull owasp/zap2docker-stable` - [official OWASP ZAP](https://github.com/zaproxy/zaproxy) ⭐ 15,591 | 🐛 854 | 🌐 Java | 📅 2026-08-13
* `docker pull vulnerables/web-owasp-nodegoat` - [OWASP NodeGoat](https://github.com/owasp/nodegoat#option-3---run-nodegoat-on-docker) ⭐ 2,060 | 🐛 105 | 🌐 HTML | 📅 2024-06-15
* `docker pull kalilinux/kali-linux-docker` [official Kali Linux](https://hub.docker.com/r/kalilinux/kali-last-release/)
* `docker pull wpscanteam/wpscan` - [official WPScan](https://hub.docker.com/r/wpscanteam/wpscan/)
* `docker pull metasploitframework/metasploit-framework
  ` - [Official Metasploit](https://hub.docker.com/r/metasploitframework/metasploit-framework/)
* `docker pull citizenstig/dvwa` - [Damn Vulnerable Web Application (DVWA)](https://hub.docker.com/r/citizenstig/dvwa/)
* `docker pull wpscanteam/vulnerablewordpress` - [Vulnerable WordPress Installation](https://hub.docker.com/r/wpscanteam/vulnerablewordpress/)
* `docker pull hmlio/vaas-cve-2014-6271` - [Vulnerability as a service: Shellshock](https://hub.docker.com/r/hmlio/vaas-cve-2014-6271/)
* `docker pull hmlio/vaas-cve-2014-0160` - [Vulnerability as a service: Heartbleed](https://hub.docker.com/r/hmlio/vaas-cve-2014-0160/)
* `docker pull opendns/security-ninjas` - [Security Ninjas](https://hub.docker.com/r/opendns/security-ninjas/)
* `docker pull noncetonic/archlinux-pentest-lxde` - [Arch Linux Penetration Tester](https://hub.docker.com/r/noncetonic/archlinux-pentest-lxde)
* `docker pull diogomonica/docker-bench-security` - [Docker Bench for Security](https://hub.docker.com/r/diogomonica/docker-bench-security/)
* `docker pull ismisepaul/securityshepherd` - [OWASP Security Shepherd](https://hub.docker.com/r/ismisepaul/securityshepherd/)
* `docker pull danmx/docker-owasp-webgoat` - [OWASP WebGoat Project docker image](https://hub.docker.com/r/danmx/docker-owasp-webgoat/)
* `docker pull citizenstig/nowasp` - [OWASP Mutillidae II Web Pen-Test Practice Application](https://hub.docker.com/r/citizenstig/nowasp/)
* `docker pull bkimminich/juice-shop` - [OWASP Juice Shop](https://github.com/bkimminich/juice-shop#docker-container--)
* `docker pull phocean/msf` - [Docker Metasploit](https://hub.docker.com/r/phocean/msf/)

## General

* [Exploit database](https://www.exploit-db.com/) - An ultimate archive of exploits and vulnerable software

# Reverse Engineering

## Tutorials

* [Begin RE: A Reverse Engineering Tutorial Workshop](https://www.begin.re/the-workshop)
* [Malware Analysis Tutorials: a Reverse Engineering Approach](http://fumalwareanalysis.blogspot.kr/p/malware-analysis-tutorials-reverse.html)
* [Malware Unicorn Reverse Engineering Tutorial](https://malwareunicorn.org/workshops/re101.html#0)
* [Lena151: Reversing With Lena](https://archive.org/details/lena151)

## Tools

### Disassemblers and debuggers

* [x64dbg](https://github.com/x64dbg/x64dbg) ⭐ 49,153 | 🐛 576 | 🌐 C++ | 📅 2026-08-09 - An open-source x64/x32 debugger for Windows
* [radare2](https://github.com/radare/radare2) ⭐ 24,564 | 🐛 822 | 🌐 C | 📅 2026-08-13 - A portable reversing framework
* [Capstone](https://github.com/aquynh/capstone) ⭐ 8,945 | 🐛 360 | 🌐 C | 📅 2026-08-13
* [plasma](https://github.com/joelpx/plasma) ⭐ 3,072 | 🐛 15 | 🌐 Python | 📅 2021-08-31 - Interactive disassembler for x86/ARM/MIPS. Generates indented pseudo-code with colored syntax code.
* [ScratchABit](https://github.com/pfalcon/ScratchABit) ⭐ 413 | 🐛 29 | 🌐 Python | 📅 2020-11-25 - Easily retargetable and hackable interactive disassembler with IDAPython-compatible plugin API
* [IDA](https://www.hex-rays.com/products/ida/) - IDA is a Windows, Linux or Mac OS X hosted multi-processor disassembler and debugger
* [OllyDbg](http://www.ollydbg.de/) - A 32-bit assembler level analysing debugger for Windows
* [Ghidra](https://ghidra-sre.org/) - A software reverse engineering (SRE) suite of tools developed by NSA's Research Directorate in support of the Cybersecurity mission

### Decompilers

* [JADX](https://github.com/skylot/jadx) ⭐ 50,051 | 🐛 443 | 🌐 Java | 📅 2026-08-05 - a decompiler for Android apps. Not related to JAD.

* [JD-GUI](https://github.com/java-decompiler/jd-gui) ⭐ 15,172 | 🐛 248 | 🌐 Java | 📅 2024-07-08

* [Krakatau](https://github.com/Storyyeller/Krakatau) ⭐ 2,241 | 🐛 25 | 🌐 Rust | 📅 2026-04-07 - the best decompiler I have used. Is able to decompile apps written in Scala and Kotlin into Java code. JD-GUI and Luyten have failed to do it fully.

* JVM-based languages

* [procyon](https://bitbucket.org/mstrobel/procyon/wiki/Java%20Decompiler)
  * [Luyten](https://github.com/deathmarine/Luyten) ⭐ 5,110 | 🐛 193 | 🌐 Java | 📅 2024-07-11 - one of the best, though a bit slow, hangs on some binaries and not very well maintained.

* [JAD](http://varaneckas.com/jad/) - JAD Java Decompiler (closed-source, unmaintained)

* .net-based languages
  * [dnSpy](https://github.com/0xd4d/dnSpy) ⚠️ Archived - .NET assembly editor, decompiler, and debugger
  * [ILSpy](https://github.com/icsharpcode/ILSpy/) ⭐ 25,854 | 🐛 189 | 🌐 C# | 📅 2026-08-13 - an open-source .NET assembly browser and decompiler
  * [dotPeek](https://www.jetbrains.com/decompiler/) - a free-of-charge .NET decompiler from JetBrains

* native code
  * [retdec](https://github.com/avast-tl/retdec) ⭐ 8,604 | 🐛 458 | 🌐 C++ | 📅 2026-05-26
  * [snowman](https://github.com/yegord/snowman) ⚠️ Archived
  * [Hopper](https://www.hopperapp.com) - A OS X and Linux Disassembler/Decompiler for 32/64-bit Windows/Mac/Linux/iOS executables.
  * [cutter](https://github.com/radareorg/cutter) - a decompiler based on radare2.
  * [Hex-Rays](https://www.hex-rays.com/products/decompiler/)

* Python
  * [uncompyle6](https://github.com/rocky/python-uncompyle6) ⭐ 4,317 | 🐛 42 | 🌐 Python | 📅 2026-04-24 - decompiler for the over 20 releases and 20 years of CPython.

### Deobfuscators

* [JS Beautifier](https://github.com/beautify-web/js-beautify) ⭐ 8,984 | 🐛 433 | 🌐 JavaScript | 📅 2026-08-11
* [de4dot](https://github.com/0xd4d/de4dot) ⚠️ Archived - .NET deobfuscator and unpacker.
* [JS Nice](http://jsnice.org/) - a web service guessing JS variables names and types based on the model derived from open source.

### Other

* [dex2jar](https://github.com/pxb1988/dex2jar) ⭐ 13,133 | 🐛 379 | 🌐 Java | 📅 2024-07-21 - Tools to work with Android .dex and Java .class files
* [antinet](https://github.com/0xd4d/antinet) ⚠️ Archived - .NET anti-managed debugger and anti-profiler code
* [nudge4j](https://github.com/lorenzoongithub/nudge4j) ⭐ 164 | 🐛 2 | 🌐 Java | 📅 2020-04-12 - Java tool to let the browser talk to the JVM
* [androguard](https://code.google.com/p/androguard/) - Reverse engineering, malware and goodware analysis of Android applications
* [UPX](http://upx.sourceforge.net/) - the Ultimate Packer (and unpacker) for eXecutables

### Execution logging and tracing

* [mitmproxy](https://github.com/mitmproxy/mitmproxy) ⭐ 44,682 | 🐛 464 | 🌐 Python | 📅 2026-08-13 - An interactive, SSL-capable man-in-the-middle proxy for HTTP with a console interface
* [USBPcap](https://github.com/desowin/usbpcap) ⭐ 1,123 | 🐛 65 | 🌐 C | 📅 2025-02-09 - USB capture for Windows.
* [drltrace](https://github.com/mxmssh/drltrace) ⭐ 419 | 🐛 14 | 🌐 HTML | 📅 2020-08-16 - shared library calls tracing.
* [dynStruct](https://github.com/ampotos/dynStruct) ⭐ 329 | 🐛 18 | 🌐 C | 📅 2019-08-12 - structures recovery via dynamic instrumentation.
* [Wireshark](https://www.wireshark.org/) - A free and open-source packet analyzer
* [tcpdump](http://www.tcpdump.org/) - A powerful command-line packet analyzer; and libpcap, a portable C/C++ library for network traffic capture
* [Charles Proxy](https://charlesproxy.com) - A cross-platform GUI web debugging proxy to view intercepted HTTP and HTTPS/SSL live traffic
* [usbmon](https://www.kernel.org/doc/Documentation/usb/usbmon.txt) - USB capture for Linux.

### Binary files examination and editing

#### Hex editors

* [HxD](http://mh-nexus.de/en/hxd/) - A hex editor which, additionally to raw disk editing and modifying of main memory (RAM), handles files of any size
* [WinHex](http://www.winhex.com/winhex/) - A hexadecimal editor, helpful in the realm of computer forensics, data recovery, low-level data processing, and IT security
* [wxHexEditor](https://github.com/EUA/wxHexEditor) ⭐ 618 | 🐛 83 | 🌐 C | 📅 2024-06-27
* [Synalize It](https://www.synalysis.net/)/[Hexinator](https://hexinator.com/) -

#### Other

* [DBeaver](https://github.com/dbeaver/dbeaver) ⭐ 51,447 | 🐛 3,315 | 🌐 Java | 📅 2026-08-13 - a DB editor.
* [Binwalk](https://github.com/ReFirmLabs/binwalk) ⭐ 14,225 | 🐛 91 | 🌐 Rust | 📅 2026-08-11 -  Detects signatures, unpacks archives, visualizes entropy.
* [Dependencies](https://github.com/lucasg/Dependencies) ⭐ 11,755 | 🐛 142 | 🌐 C# | 📅 2024-05-15 - a FOSS replacement to Dependency Walker.
* [Kaitai Struct](https://github.com/kaitai-io/kaitai_struct) ⭐ 4,653 | 🐛 524 | 🌐 Shell | 📅 2026-08-10 - a DSL for creating parsers in a variety of programming languages. The Web IDE is particularly useful for reverse-engineering.
* [Veles](https://github.com/codilime/veles) ⚠️ Archived - a visualizer for statistical properties of blobs.
* [Protobuf inspector](https://github.com/jmendeth/protobuf-inspector) ⭐ 1,124 | 🐛 5 | 🌐 Python | 📅 2020-12-13
* [DarunGrim](https://github.com/ohjeongwook/DarunGrim) ⭐ 365 | 🐛 4 | 📅 2020-08-22 - executable differ.
* [PEview](http://wjradburn.com/software/) - A quick and easy way to view the structure and content of 32-bit Portable Executable (PE) and Component Object File Format (COFF) files
* [BinText](https://web.archive.org/web/http://www.mcafee.com/kr/downloads/free-tools/bintext.aspx) - A small, very fast and powerful text extractor that will be of particular interest to programmers.

## General

* [Open Malware](http://www.offensivecomputing.net/)

# Web

## Tools

* [sqlmap](https://github.com/sqlmapproject/sqlmap) ⭐ 38,176 | 🐛 32 | 🌐 Python | 📅 2026-08-13 - Automatic SQL injection and database takeover tool
* [masscan](https://github.com/robertdavidgraham/masscan) ⭐ 25,930 | 🐛 414 | 🌐 C | 📅 2026-04-23 - Internet scale portscanner.
* [SubFinder](https://github.com/subfinder/subfinder) ⭐ 14,192 | 🐛 7 | 🌐 Go | 📅 2026-08-12 - SubFinder is a subdomain discovery tool that discovers valid subdomains for any target using passive online sources.
* [NoSQLMap](https://github.com/codingo/NoSQLMap) ⭐ 3,338 | 🐛 1 | 🌐 Python | 📅 2026-07-28 - Automated NoSQL database enumeration and web application exploitation tool.
* [PhpSploit](https://github.com/nil0x42/phpsploit) ⭐ 2,489 | 🐛 27 | 🌐 Python | 📅 2024-05-06 - Full-featured C2 framework which silently persists on webserver via evil PHP oneliner
* [VHostScan](https://github.com/codingo/VHostScan) ⭐ 1,310 | 🐛 1 | 🌐 Python | 📅 2025-08-18 - A virtual host scanner that performs reverse lookups, can be used with pivot tools, detect catch-all scenarios, aliases and dynamic default pages.
* [badtouch](https://github.com/kpcyrd/badtouch) ⭐ 418 | 🐛 24 | 🌐 Rust | 📅 2023-12-19 - Scriptable network authentication cracker
* [Keyscope](https://github.com/SpectralOps/keyscope) ⭐ 412 | 🐛 1 | 🌐 Rust | 📅 2025-07-24 - an extensible key and secret validation tool for auditing active secrets against multiple SaaS vendors
* [Git-Scanner](https://github.com/HightechSec/git-scanner) ⭐ 384 | 🐛 3 | 🌐 Shell | 📅 2020-06-23 - A tool for bug hunting or pentesting for targeting websites that have open `.git` repositories available in public
* [Spyse](https://spyse.com/) -  Data gathering service that collects web info using OSINT. Provided info: IPv4 hosts, domains/whois, ports/banners/protocols, technologies, OS, AS, maintains huge SSL/TLS DB, and more... All the data is stored in its own database allowing get the data without scanning.
* [tools.web-max.ca](http://tools.web-max.ca/encode_decode.php) - base64 base85 md4,5 hash, sha1 hash encoding/decoding
* [Findsubdomains](https://findsubdomains.com/) - A subdomains discovery tool that collects all possible subdomains from open source internet and validates them through various tools to provide accurate results.
* [CSP Scanner](https://cspscanner.com/) - Analyze a site's Content-Security-Policy (CSP) to find bypasses and missing directives.
* [Shodan](https://www.shodan.io/) - A web-crawling search engine that lets users search for various types of servers connected to the internet.
* [Decompiler.com](https://www.decompiler.com/) - Java, Android, Python, C# online decompiler.

## General

* [Strong node.js](https://github.com/jesusprubio/strong-node) ⚠️ Archived - An exhaustive checklist to assist in the source code security analysis of a node.js web service.

# Network

## Tools

* [RustScan](https://github.com/rustscan/rustscan) ⭐ 20,268 | 🐛 60 | 🌐 Rust | 📅 2026-07-29 - Extremely fast port scanner built with Rust, designed to scan all ports in a couple of seconds and utilizes nmap to perform port enumeration in a fraction of the time.
* [Amass](https://github.com/OWASP/Amass) ⭐ 14,978 | 🐛 235 | 🌐 Go | 📅 2026-07-19 - In-depth subdomain enumeration tool that performs scraping, recursive brute forcing, crawling of web archives, name altering and reverse DNS sweeping
* [Nipe](https://github.com/GouveaHeitor/nipe) ⭐ 2,366 | 🐛 15 | 🌐 Perl | 📅 2026-06-27 - A script to make Tor Network your default gateway.
* [ssh-mitm](https://github.com/jtesta/ssh-mitm) ⚠️ Archived - An SSH/SFTP man-in-the-middle tool that logs interactive sessions and passwords.
* [sniffglue](https://github.com/kpcyrd/sniffglue) ⭐ 1,266 | 🐛 18 | 🌐 Rust | 📅 2026-04-19 - Secure multithreaded packet sniffer
* [Habu](https://github.com/portantier/habu) ⭐ 983 | 🐛 3 | 🌐 Python | 📅 2025-12-30 - Python Network Hacking Toolkit
* [pig](https://github.com/rafael-santiago/pig) ⭐ 479 | 🐛 0 | 🌐 C | 📅 2020-11-02 - A Linux packet crafting tool
* [Netz](https://github.com/spectralops/netz) ⭐ 399 | 🐛 1 | 🌐 Go | 📅 2021-05-11 - Discover internet-wide misconfigurations, using zgrab2 and others.
* [Scapy](https://github.com/secdev/awesome-scapy) ⭐ 363 | 🐛 2 | 📅 2025-06-09 - A Python tool and library for low level packet creation and manipulation
* [PETEP](https://github.com/Warxim/petep) ⭐ 231 | 🐛 0 | 🌐 Java | 📅 2023-12-01 - Extensible TCP/UDP proxy with GUI for traffic analysis & modification with SSL/TLS support.
* [mitmsocks4j](https://github.com/Akdeniz/mitmsocks4j) ⭐ 40 | 🐛 0 | 🌐 Java | 📅 2013-02-14 - Man-in-the-middle SOCKS Proxy for Java
* [NetworkMiner](http://www.netresec.com/?page=NetworkMiner) - A Network Forensic Analysis Tool (NFAT)
* [Paros](http://sourceforge.net/projects/paros/) - A Java-based HTTP/HTTPS proxy for assessing web application vulnerability
* [findsubdomains](https://findsubdomains.com) - really fast subdomains scanning service that has much greater opportunities than simple subs finder(works using OSINT).
* [cirt-fuzzer](http://www.cirt.dk/) - A simple TCP/UDP protocol fuzzer.
* [ASlookup](https://aslookup.com/) - a useful tool for exploring autonomous systems and all related info (CIDR, ASN, Org...)
* [ZAP](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project) - The Zed Attack Proxy (ZAP) is an easy to use integrated penetration testing tool for finding vulnerabilities in web applications
* [nmap](https://nmap.org/) - Nmap (Network Mapper) is a security scanner
* [Aircrack-ng](http://www.aircrack-ng.org/) - An 802.11 WEP and WPA-PSK keys cracking program
* [Wifi Jammer](https://n0where.net/wifijammer/) - Free program to jam all wifi clients in range
* [Firesheep](https://codebutler.github.io/firesheep/) - Free program for HTTP session hijacking attacks.

# Forensic

## Tools

* [sleuthkit](https://github.com/sleuthkit/sleuthkit) ⭐ 3,126 | 🐛 478 | 🌐 C | 📅 2026-08-11 - A library and collection of command-line digital forensics tools
* [CyLR](https://github.com/orlikoski/CyLR) ⭐ 733 | 🐛 21 | 🌐 C# | 📅 2022-06-01 - NTFS forensic image collector
* [Autopsy](http://www.sleuthkit.org/autopsy/) - A digital forensics platform and graphical interface to [The Sleuth Kit](http://www.sleuthkit.org/sleuthkit/index.php) and other digital forensics tools
* [EnCase](https://www.guidancesoftware.com/products/Pages/encase-forensic/overview.aspx) - The shared technology within a suite of digital investigations products by Guidance Software
* [malzilla](http://malzilla.sourceforge.net/) - Malware hunting tool
* [IPED - Indexador e Processador de Evidências Digitais](https://servicos.dpf.gov.br/ferramentas/IPED/) - Brazilian Federal Police Tool for Forensic Investigation
* [CAINE](https://www.caine-live.net/)- CAINE is a Ubuntu-based app that offers a complete forensic environment that provides a graphical interface. This tool can be integrated into existing software tools as a module. It automatically extracts a timeline from RAM.

# Cryptography

### Tools

* [Ciphey](https://github.com/ciphey/ciphey) ⭐ 21,580 | 🐛 2 | 🌐 Rust | 📅 2026-08-10 - Automated decryption tool using artificial intelligence & natural language processing.
* [xortool](https://github.com/hellman/xortool) ⭐ 1,485 | 🐛 3 | 🌐 Python | 📅 2025-05-21 - A tool to analyze multi-byte XOR cipher
* [John the Ripper](http://www.openwall.com/john/) - A fast password cracker
* [Aircrack](http://www.aircrack-ng.org/) - Aircrack is 802.11 WEP and WPA-PSK keys cracking program.

# Wargame

## System

* [OverTheWire - Semtex](http://overthewire.org/wargames/semtex/)
* [OverTheWire - Vortex](http://overthewire.org/wargames/vortex/)
* [OverTheWire - Drifter](http://overthewire.org/wargames/drifter/)
* [pwnable.kr](http://pwnable.kr/) - Provide various pwn challenges regarding system security
* [Exploit Exercises - Nebula](https://exploit-exercises.com/nebula/)
* [SmashTheStack](http://smashthestack.org/)
* [HackingLab](https://www.hacking-lab.com/)

## Reverse Engineering

* [Reversing.kr](http://www.reversing.kr/) - This site tests your ability to Cracking & Reverse Code Engineering
* [CodeEngn](http://codeengn.com/challenges/) - (Korean)
* [simples.kr](http://simples.kr/) - (Korean)
* [Crackmes.de](http://crackmes.de/) - The world first and largest community website for crackmes and reversemes.

## Web

* [Hack This Site!](https://www.hackthissite.org/) - a free, safe and legal training ground for hackers to test and expand their hacking skills
* [Hack The Box](https://www.hackthebox.eu) - a free site to perform pentesting in a variety of different systems.
* [Webhacking.kr](http://webhacking.kr/)
* [0xf.at](https://0xf.at/) - a website without logins or ads where you can solve password-riddles (so called hackits).
* [fuzzy.land](https://fuzzy.land/) - Website by an Austrian group. Lots of challenges taken from CTFs they participated in.
* [Gruyere](https://google-gruyere.appspot.com/)
* [Others](https://www.owasp.org/index.php/OWASP_Vulnerable_Web_Applications_Directory_Project#tab=On-Line_apps)
* [TryHackMe](https://tryhackme.com/) - Hands-on cyber security training through real-world scenarios.

## Cryptography

* [OverTheWire - Krypton](http://overthewire.org/wargames/krypton/)

## Bug bounty

* [Awesome bug bounty resources by EdOverflow](https://github.com/EdOverflow/bugbounty-cheatsheet) ⭐ 6,531 | 🐛 11 | 📅 2023-09-14

## Bug bounty -  Earn Some Money

* [Bugcrowd](https://www.bugcrowd.com/)
* [Hackerone](https://www.hackerone.com/start-hacking)
* [Intigriti](https://www.intigriti.com/) Europe's #1 ethical hacking and bug bounty program.

# CTF

## Competition

* [DEF CON](https://legitbs.net/)
* [CSAW CTF](https://ctf.isis.poly.edu/)
* [hack.lu CTF](http://hack.lu/)
* [Pliad CTF](http://www.plaidctf.com/)
* [RuCTFe](http://ructf.org/e/)
* [Ghost in the Shellcode](http://ghostintheshellcode.com/)
* [PHD CTF](http://www.phdays.com/)
* [SECUINSIDE CTF](http://secuinside.com/)
* [Codegate CTF](http://ctf.codegate.org/html/Main.html?lang=eng)
* [Boston Key Party CTF](http://bostonkeyparty.net/)
* [ZeroDays CTF](https://zerodays.ie/)
* [Insomni’hack](https://insomnihack.ch/)
* [Pico CTF](https://picoctf.com/)
* [prompt(1) to win](http://prompt.ml/) - XSS Challenges
* [HackTheBox](https://www.hackthebox.eu/)

## General

* [Movies For Hackers](https://github.com/k4m4/movies-for-hackers) ⭐ 11,856 | 🐛 129 | 🌐 Shell | 📅 2024-08-01 - A curated list of movies every hacker & cyberpunk must watch.
* [Pentest Cheat Sheets](https://github.com/coreb1t/awesome-pentest-cheat-sheets) ⚠️ Archived - Collection of cheat sheets useful for pentesting
* [Hack+](http://hack.plus) - An Intelligent network of bots that fetch the latest InfoSec content.
* [CTFtime.org](https://ctftime.org/) - All about CTF (Capture The Flag)
* [WeChall](http://www.wechall.net/)
* [CTF archives (shell-storm)](http://shell-storm.org/repo/CTF/)
* [Rookit Arsenal](https://amzn.com/144962636X) - OS RE and rootkit development
* [Roppers CTF Fundamentals Course](https://www.roppers.org/courses/ctf) - Free course designed to get a student crushing CTFs as quickly as possible. Teaches the mentality and skills required for crypto, forensics, and more. Full text available as a [gitbook](https://www.hoppersroppers.org/ctf/).

# OS

## Online resources

* [Security related Operating Systems @ Rawsec](https://inventory.raw.pm/operating_systems.html) - Complete list of security related operating systems
* [Best Linux Penetration Testing Distributions @ CyberPunk](https://n0where.net/best-linux-penetration-testing-distributions/) - Description of main penetration testing distributions
* [Security @ Distrowatch](http://distrowatch.com/search.php?category=Security) - Website dedicated to talking about, reviewing and keeping up to date with open source operating systems

# Post exploitation

## tools

* [PowerSploit](https://github.com/PowerShellMafia/PowerSploit) ⚠️ Archived - A PowerShell post exploitation framework
* [empire](https://github.com/EmpireProject/Empire) ⚠️ Archived - A post exploitation framework for powershell and python.
* [silenttrinity](https://github.com/byt3bl33d3r/SILENTTRINITY) ⭐ 2,343 | 🐛 48 | 🌐 Boo | 📅 2023-12-06 - A post exploitation tool that uses iron python to get past powershell restrictions.
* [ebowla](https://github.com/Genetic-Malware/Ebowla) ⭐ 762 | 🐛 10 | 🌐 Python | 📅 2019-01-28 - Framework for Making Environmental Keyed Payloads

# ETC

* [SecTools](http://sectools.org/) - Top 125 Network Security Tools
* [Roppers Security Fundamentals](https://www.roppers.org/courses/security) - Free course that teaches a beginner how security works in the real world. Learn security theory and execute defensive measures so that you are better prepared against threats online and in the physical world. Full text available as a [gitbook](https://www.hoppersroppers.org/security/).
* [Roppers Practical Networking](https://www.roppers.org/courses/networking) - A hands-on, wildly practical introduction to networking and making packets dance. No wasted time, no memorizing, just learning the fundamentals.
* [Rawsec's CyberSecurity Inventory](https://inventory.raw.pm/) - An open-source inventory of tools, resources, CTF platforms and Operating Systems about CyberSecurity. ([Source](https://gitlab.com/rawsec/rawsec-cybersecurity-list))
* [The Cyberclopaedia](https://cr0mll.github.io/cyberclopaedia/) - The open-source encyclopedia of cybersecurity. [GitHub Repository](https://github.com/cr0mll/cyberclopaedia) ⭐ 207 | 🐛 0 | 🌐 Handlebars | 📅 2024-08-06

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-13._
