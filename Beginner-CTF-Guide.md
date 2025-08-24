# 🛡️ | Beginner CTF Starter Training Guide |
Welcome, rookies! This guide will help you build a strong foundation in CTFs with recommended platforms, guided learning paths, and video links.

### CTF > 101
- :ledger:  [**CTF Handbook**](https://ctf101.org/)

## :wrench: Beginner Platforms & Paths

### **TryHackMe**
- :rocket: [**Free Beginner Path**](https://tryhackme.com/resources/blog/free_path/) – Covers Linux, Networking, Web, Forensics & more

### **Hack The Box (HTB)**
- :rocket: [**Beginner's Bible**](https://www.hackthebox.com/blog/learn-to-hack-beginners-bible) - The truth behind learning the wonderful wizardry of hacking. Here's what it takes to learn hacking from scratch and the necessary steps to get started!

### :rocket: [**OverTheWire**](https://overthewire.org/wargames/)
- Familiarize yourself with basic Linux commands through Wargames like “Bandit”

### :rocket: [**picoCTF**](https://play.picoctf.org/login)
- Beginner-friendly contest with story-driven puzzles in cryptography, forensics, web, and more

## :mortar_board: Video & Tutorial Resources

- **“Learn How to Hack with CTFs as a COMPLETE Beginner”** - [Watch](https://m.youtube.com/watch?v=Xp_jAakX_J8)  
- **“Capture the Flag Beginner Guide 2024”** - [Watch](https://www.youtube.com/watch?v=YAqZmMYudZU)  
- **“Getting Started in CTF: PicoCTF 2017”** - [Watch](https://www.youtube.com/playlist?list=PL1H1sBF1VAKVTu-v1XcJV9VVdhEEALvkY)
- **TryHackMe Beginner-to-Expert Guide** - [GitHub Link](https://github.com/0xneobyte/TryHackMe-Learning-Path-From-Beginner-to-Expert)

## :dart: Essential Toolset for Beginners

- **Kali Linux**  
- **Nmap**, **Wireshark**, **Gobuster**, **CyberChef**, **Burp Suite**, **StegSolve**, **ExifTool**

## ❗Training Recommendations

1. **Start with TryHackMe** – Begin foundational rooms to build basic Linux & network skills.
2. **Watch beginner CTF tutorials** – Follow along with a video, then try on your own.
3. **Practice with “Simple CTF”** – Use Nmap scanning, Gobuster enumeration, exploit discovery, and SSH access.  
   *Recommended Walkthrough [InfoSec Writeup](https://infosecwriteups.com/tryhackme-simple-ctf-walkthrough-by-hexahunter-b9457e4d7d16)
4. **Join picoCTF** – Try entry-level challenges in competition format.
5. **Practice OSINT & tools** – Download Kali Linux, start exploring tools like Nmap, Wireshark, Burp Suite, and CyberChef.

## :brain: Tips for Beginners

- Reference tools below... 
- Ask questions or share tips in the respective workrooms
- Pair up with teammates in for collaborative learning

___

# 🧰 | Starter CTF Tool Library |
Tools organized by CTF categories. Each tool includes a short description and a link to download or explore more.


## :detective: Forensics
------------------
:mag: Tools for memory analysis, metadata extraction, disk imaging, and packet capture review.

- **Volatility** – Memory forensics analysis tool  
  :link: [GitHub](https://github.com/volatilityfoundation/volatility3)

- **Autopsy** – Digital forensic tool for disk image analysis  
  :link: [autopsy.com](https://www.sleuthkit.org/autopsy/)

- **ExifTool** – Extract and analyze metadata from images/files  
  :link: [exiftool.org](https://exiftool.org/)

- **Wireshark** – Network packet capture and analysis  
  :link: [wireshark.org](https://www.wireshark.org/)

- **Security Onion** – Threat hunting and network monitoring platform  
  :link: [securityonionsolutions.com](https://securityonionsolutions.com/)

## :closed_lock_with_key: Crypto
----------------
:closed_lock_with_key: Tools for cryptography puzzles, decoding, and data transformation.

- **CyberChef** – Swiss army knife for encoding, decoding, encryption  
  :link: [CyberChef](https://gchq.github.io/CyberChef/)

- **RsaCtfTool** – Decrypt RSA encryption challenges (e.g., low exponent, shared factors)  
  :link: [GitHub](https://github.com/Ganapati/RsaCtfTool)


## :globe_with_meridians: Web
-------------
:globe_with_meridians: Tools for discovering and exploiting web vulnerabilities and analyzing endpoints.

- **Burp Suite** – Web security scanner and proxy testing  
  :link: [portswigger.net](https://portswigger.net/burp)

- **FFUF** – Fast web fuzzer for endpoints and parameters  
  :link: [GitHub](https://github.com/ffuf/ffuf)

- **SQLmap** – Automated tool for SQL injection detection and exploitation  
  :link: [sqlmap.org](https://sqlmap.org/)

- **Gobuster** – Directory and DNS brute-forcing  
  :link: [GitHub](https://github.com/OJ/gobuster)

- **StegSolve** – Java tool for analyzing steganography in images  
  :link: [GitHub](https://github.com/zardus/ctf-tools/blob/master/stegsolve/stegsolve.jar)

## :brain: Reversing
-------------------
:mag_right: Tools for static/dynamic binary analysis and reverse engineering challenges.

- **Ghidra** – Open-source reverse engineering suite by NSA  
  :link: [ghidra-sre.org](https://ghidra-sre.org/)

- **Radare2** – Open-source command-line reverse engineering tool  
  :link: [GitHub](https://github.com/radareorg/radare2)

- **x64dbg** – Windows debugger for binary analysis  
  :link: [x64dbg.com](https://x64dbg.com/#start)

- **Binwalk** – Extract firmware images and analyze embedded files  
  :link: [GitHub](https://github.com/ReFirmLabs/binwalk)


## :bomb: Pwn / Binary Exploitation
-----------------------------------------
:boom: Tools for buffer overflow, ROP, shellcode, and exploit dev.

- **Pwntools** – CTF framework for binary exploitation (Python-based)  
  :link: [Docs](https://docs.pwntools.com/en/stable/)

- **ROPgadget** – Find ROP chains in binaries  
  :link: [GitHub](https://github.com/JonathanSalwan/ROPgadget)

- **checksec** – Inspect binaries for security mitigations (e.g., PIE, NX)  
  :link: [GitHub](https://github.com/slimm609/checksec.sh)

## :satellite: Networking / Recon / OSINT
---------------------------------------------
:bar_chart: Tools for scanning, sniffing, reconnaissance, and general network work.

- **Nmap** – Network discovery and port scanning  
  :link: [nmap.org](https://nmap.org/)

- **Aircrack-ng** – Wireless network cracking and monitoring  
  :link: [aircrack-ng.org](https://www.aircrack-ng.org/)

- **Snort** – Real-time traffic analysis and IDS  
  :link: [snort.org](https://www.snort.org/)

- **Suricata** – High-performance IDS/IPS engine  
  :link: [suricata.io](https://suricata.io/)

- **Zeek** – Network traffic analysis and monitoring  
  :link: [zeek.org](https://zeek.org/)

- **OpenVAS** – Vulnerability scanner maintained by Greenbone  
  :link: [Greenbone Docs](https://greenbone.github.io/docs/latest/22.4/kali/index.html)

- **Metasploit** – Framework for developing and executing exploits  
  :link: [metasploit.com](https://www.metasploit.com/)

- **Hashcat** – Password recovery and cracking with GPU support  
  :link: [hashcat.net](https://hashcat.net/hashcat/)

- **John the Ripper** – Password security testing tool  
  :link: [Openwall](https://www.openwall.com/john/)

## ⚙️ Platforms & Infrastructure
------------------------------------------
:jigsaw: Tools that support threat intelligence, red teaming, and SIEM/monitoring.

- **Kali Linux** – Linux distro for ethical hacking and pentesting  
  :link: [kali.org](https://www.kali.org/)

- **Elastic Stack** – Log collection, SIEM, and data analysis  
  :link: [elastic.co](https://www.elastic.co/siem)

- **Fabric** – AI-curated threat intel and tool aggregator  
  :link: [GitHub](https://github.com/danielmiessler/Fabric)

- **OpenCTI** – Threat intelligence management platform  
  :link: [opencti.io](https://www.opencti.io/)

- **Ollama AI** – Run LLMs locally for tool integration and automation  
  :link: [ollama.com](https://ollama.com/)

*This guide was created to provide someone brand new with a simple starting point. It is not intended to be a comprehensive or thorough resource, but rather a helpful introduction to get you moving in the right direction.
