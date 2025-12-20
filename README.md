# CYBote
```
+--------------------------------------------------------+      
            ▄▀ ▀▄░▄▀ █▀▄ ▄▀▄ ▀█▀ █▀▀                     |     
            █░ ░░█░░ █▀█ █░█ ░█░ █▀▀                     |
            ░▀ ░░▀░░ ▀▀░ ░▀░ ░▀░ ▀▀▀                     |
                                                         |
CYBote is the                                            |
Cybersecurity On The Edge                                |                               
A tool to learn and have a nice day with Ports/OSI/Tools |
---------------------------------------------------------+```
---
Try it here, you can swithch to EN/ES langs

> **"A Single-File Cyber Intelligence Dashboard for the Modern Operator."**
CYBote is an ultra-lightweight, offline-first dashboard designed to bridge the gap between **OSI Theory**, **Kali Linux Tools**, and **Port/Service knowledge**. It serves as an interactive HUD (Heads-Up Display) for students, CTF players, and cybersecurity professionals.
![CYBote Interface](https://via.placeholder.com/800x450?text=CYBote+Dashboard+Preview)
---
## 🚀 Key Features
### 1. 🌐 Semantic OSI Analyzer (Layer 1-7)
Navigate the OSI model interactively. CYBote features a **Semantic Relation Engine**:
*   Clicking **"Spoofing"** (Layer 2) won't just search for text. It intelligently fetches tools associated with **MITM, ARP, Sniffing, and DNS Poisoning**.
*   **Gap-Filled Arsenal:** Covers everything from `Minicom` (Hardware/L1) to `Wafw00f` (L7/Firewall).
### 2. 🛠️ Intelligent Kali Arsenal
A curated database of top-tier security tools, mapped to:
*   **Categories:** Information Gathering, Post-Exploitation, Forensics, etc.
*   **Tags:** Semantic tags (`#rpc`, `#smb`, `#kerberos`) allow for cross-referencing.
*   **Docs:** One-click access to official Kali documentation.
### 3. ⚡ Omni-Search Port Scanner
Instantly identify ports and services.
*   Type `22`, `ssh`, or even `encrypt` to find relevant ports.
*   Cross-links automatically with the OSI panel (e.g., searching "SMB" highlights Layer 5/7 and relevant tools like `Enum4linux`).
### 4. 🌎 Bilingual Support (i18n)
Full support for **English** and **Spanish**, switchable instantly.
*   **Smart Definitions:** The generic "Definición" button adapts its search query based on your language (`define:term +en+español` vs `define:term`).
### 5. 📦 Zero Dependencies (Single-File)
*   **No React, No Angular, No Node_modules.**
*   Just **Standard Web Technologies** (ES6+, CSS3 Variables).
*   Runs in **any browser**, from a local `file://` URL. Perfect for air-gapped systems or USB usage.
---
## 📥 Installation
Since CYBote is a **Single-File Application (SFA)**, installation is trivial:
1.  Download `Cybersecurity_On_The_Edge.html`.
2.  Open it in your browser (Chrome, Firefox, Edge).
3.  **Done.**
---
## 🎮 How To Use
### The "Omni-Link" Workflow
The interface is designed around the concept of **Cross-Grid Filtering**:
1.  **Select a Context:** Click on **"SESIÓN"** (Session Layer 5).
2.  **Drill Down:** The panel expands to show protocols like `RPC`, `SMB`, `NetBIOS`.
3.  **Cross-Filter:** Click on **`SMB`**.
    *   **⚡ Ports Panel:** Filters to show Port 445, 139.
    *   **🛠️ Tools Panel:** Filters to show `Enum4linux`, `Impacket`, `Responder`.
4.  **Define:** Click the **`?`** button on any card to look up a precise definition.
---
## 🔧 Technical Details
*   **Core:** Vanilla JavaScript (ES6 Modules pattern).
*   **Style:** Custom "Glassmorphism" CSS with Neon aesthetics (`--neon-cyan`, `--neon-pink`).
*   **Data Structure:** JSON-based constant databases (`DB_PORTS`, `DB_TOOLS`, `DB_OSI`, `TAG_RELATIONS`) embedded directly for speed.
---
## 📜 License
*   **Author:** Germán Company Mangano
*   **License:** MIT / Educational Use. 
*   *Designed for Cybersecurity Education & Quick Reference.*
