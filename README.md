<!-- 
  👋 Hi, I'm Chidubem — Cybersecurity Practitioner & Lab Builder
  🔐 Focused on offensive security, automation, and clear technical communication
-->

# 👋 Hi, I'm Okwor Chidubem Evaristus

> **Cybersecurity Practitioner | Threat Emulator | Technical Educator**  
> I build realistic lab environments and automation tools that mirror real-world attack flows — because **you can’t defend what you haven’t seen**.

---

## 🛠️ Tech Stack & Tools

![Parrot OS](https://img.shields.io/badge/Parrot-303030?logo=linux&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-FF6600?logo=metasploit&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp%20Suite-5700FF?logo=burpsuite&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?logo=wireshark&logoColor=white)

---

## 🌟 Featured Project

### 🔹 [Realistic Credential Traffic Generator for Wireshark Training](https://github.com/Evaristus230/wireshark-traffic-simulator)

> A **production-grade traffic simulator** that generates *authentic, multi-protocol login flows* — designed to train analysts in spotting credential exposure, protocol quirks, and attack patterns **in real packet captures**.

🛠️ **What it simulates — safely & ethically**:
- ✅ HTTP POST logins (e.g., web forms)  
- ✅ Basic/Digest/NTLM auth (Base64, challenge-response)  
- ✅ FTP, Telnet, SMTP, IMAP — **cleartext credentials**  
- ✅ LDAP binds, MySQL/PostgreSQL auth, SMB sessions  
- ✅ JWT, API keys, fake RDP/VNC handshakes  

🔐 **Key Features**:
- Generates **19+ protocol flows** with *realistic usernames/passwords* (all fake, no risk)  
- Mimics human timing (pauses, retries, errors) → no robotic traffic  
- Works out-of-the-box on **Parrot Linux** (no external dependencies beyond `requests` & `scapy`)  
- Used in my internal lab training to teach **packet-level threat hunting**

📥 **Get Started**:
```bash
git clone https://github.com/Evaristus230/wireshark-traffic-simulator
cd wireshark-traffic-simulator
pip3 install -r requirements.txt
sudo python3 enterprise_cred_simulator.py
