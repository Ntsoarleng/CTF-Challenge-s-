# 🔐 TryHackMe: Crypto Failures – CTF Walkthrough

📅 Date: 2025-04-23

🖥️ Category: Catch The Flag (CTF) Challenge  
🎯 Implementing your own military-grade encryption is usually not the best idea.


### 1️⃣ Enumeration
When starting out with any exploitation, enumeration is the first step. As much information about the service must be found first before moving to the exploitation phase.

The first step in enumeration is running a port scan and seeing services that are open and running.

**Command used:**
```bash
nmap -p- --open <target-IP>
```

**Findings:**

![Screenshot (392)](https://github.com/user-attachments/assets/f5fe5f5c-2465-4637-b7bb-276f26f0a1f6)

There are two open port here, port 80 (http) and port 22 (ssh).


