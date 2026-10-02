# 👋 Hi, I'm Arnav | Future Penetration Tester

🚀 Managing a high-velocity sprint to master the core pillars of Systems Engineering and Offensive Security.

### 🛡️ Core Targets & Focus Fields:
- **Foundational Infrastructure:** Mastering the TryHackMe Pre-Security Learning Path.
- **Active Milestones:** Network Architecture, Windows/Linux CLI Basics, Data Representation & Advanced Data Encoding formats.
- **Current Sprint:** Low-level programming fundamentals, script automation, and exploit logic.

### 📈 Verified Execution Progress:
- 🔥 **TryHackMe Continuous Streak:** 8 Days and compounding daily!
- 🏆 **Competitive Standings:** Actively climbing positions within the Bronze League grid.

*"Consistency defeats talent every single day. Constructing the absolute baseline to secure the horizon."*


### 🧠 Simple Hacker Knowledge Logs

#### 🐍 Python Basics:
- `while` loop: This is a repeat button. It keeps running code over and over as long as a condition is true. [IMPORTANT CONCEPT]
- `!=` symbol: This simply means **"Does Not Equal"**. [MUST REMEMBER]
- Indentation (Spaces): Python needs correct spaces on the left side. One wrong space will crash your script. [MUST REMEMBER]

#### 🌐 JavaScript Basics:
- `let` vs `const`: Use `let` for variables that can change (like your score). Use `const` for locked numbers that never change (like a target IP address). [MUST REMEMBER]
- `||` symbol: This means **"OR"**. The computer checks if condition A OR condition B is true. [MUST REMEMBER]
- `try` and `finally`: A `try` block stops your hacking tools from crashing if there is an error. A `finally` block is the cleanup crew that closes open connections no matter what happens. [IMPORTANT CONCEPT]


#### 🔁 Loop Control & Brute-Forcing:
- `while (condition)` loop: An automation engine that keeps repeating blocks of code infinitely as long as the condition stays true. [IMPORTANT CONCEPT]
- `!==` symbol: This means **"Strictly Not Equal To"**. It evaluates both the value and data type to make sure things are completely different. [MUST REMEMBER]
- Infinite Loop Crash: If you forget to update your tracking variables inside a `while` loop, the code runs forever and freezes the server (used in Denial of Service attacks). [MUST REMEMBER]


### 🛢️ SQL Basics & Database Structure

#### 📊 How Databases Work:
- Columns vs Rows: Columns go straight up and down (like a list of Usernames). Rows go left to right (like one single user's profile info). [MUST REMEMBER]
- `SELECT`: This command tells the database exactly **WHAT** column data you want to see. [IMPORTANT CONCEPT]
- `FROM`: This command tells the database **WHERE** the table is hidden. [IMPORTANT CONCEPT]

#### 🎯 How Hackers Attack It (SQL Injection):
- Attackers type malicious database commands straight into normal website login boxes. [IMPORTANT CONCEPT]
- If the website code is weak, the database runs the hacker's input as real code. [MUST REMEMBER]
- This trick lets hackers steal entire lists of passwords or log in as the Admin without a password. [MUST REMEMBER]

### 🌐 DNS Infrastructure & Record Layout

#### 📞 The Global Phonebook:
- `A Record`: Connects a website name directly to a standard IPv4 address. [MUST REMEMBER FOR CYBERSECURITY]
- `CNAME Record`: A nickname that points a website name to another website name instead of a number. [MUST REMEMBER FOR CYBERSECURITY]
- `Recursive DNS Server`: The middleman server (usually run by your ISP) that searches the web to find your website numbers. [IMPORTANT CONCEPT]
- `Authoritative DNS Server`: The master server that holds the final, official list of records for a domain. [MUST REMEMBER FOR CYBERSECURITY]
- `TTL (Time To Live)`: The exact expiration timer in seconds that tells your PC how long to save a website address before deleting it. [MUST REMEMBER FOR CYBERSECURITY]


### 🕸️ Day 3: LAN Topologies & Local Hardware Framework

#### 📐 Network Layout Shapes:
- Star Topology: Every device hooks into one main central Switch box. It is the most reliable, modern design used everywhere today. [MUST REMEMBER FOR CYBERSECURITY]
- Bus Topology: All devices share one straight main cable line. If that single line snaps, the entire network drops. [IMPORTANT CONCEPT]
- Ring Topology: Devices connect in a giant circle. If even one device fails, the whole loop breaks down instantly. [IMPORTANT CONCEPT]
- Single Point of Failure: A structural weakness where a single hardware crash (like a main switch dying) completely kills the entire network. [MUST REMEMBER FOR CYBERSECURITY]

#### 🔌 Smart Infrastructure Boxes:
- Switch: A smart box that checks MAC addresses and forwards data ONLY to the exact device port intended, keeping internal local traffic quiet and clean. [MUST REMEMBER FOR CYBERSECURITY]
- Router: A digital bridge that connects completely separate networks together and routes packets across the internet. [MUST REMEMBER FOR CYBERSECURITY]


### 🌐 Day 4: Subnet Segmentation & The DHCP DORA Loop

#### 🛡️ Advanced Network Segmentation:
- Subnetting: Slicing a massive network space into quiet, isolated miniature rooms to maximize security and control the blast radius. [MUST REMEMBER FOR CYBERSECURITY]
- Flat Network Vulnerability: A risky network architecture with zero internal walls. If one client machine is breached, malware can spread laterally to all endpoints unimpeded. [IMPORTANT CONCEPT]
- Network Address (.0): Represents the identifier of the entire network street. Inputted directly into scanning engines (like Nmap) for host discovery. [MUST REMEMBER FOR CYBERSECURITY]
- Default Gateway (.1 or .254): The critical exit door router that handles cross-subnet traffic mapping. Highly targeted during Man-in-the-Middle (MITM) attacks. [MUST REMEMBER FOR CYBERSECURITY]

#### 🔄 The DHCP / DORA Handshake:
- Dynamic Host Configuration Protocol (DHCP): An automated server architecture that loans out IP leases to incoming hardware. [MUST REMEMBER FOR CYBERSECURITY]
- DORA Packet Sequence: The 4-step communication lifecycle used to retrieve an IP layout automatically:
  1. Discover (Client network broadcast shout looking for a server)
  2. Offer (Server unicast proposing an available address)
  3. Request (Client confirmation locking down the lease slot)
  4. Acknowledge / ACK (Server validation finaly making the client live)
- Rogue DHCP Exploit: A critical attack vector where an imposter server replies to a client's Discover broadcast first, forcing target traffic to route directly through a hacker's terminal. [MUST REMEMBER FOR CYBERSECURITY]

- #### 🪜 OSI Model Architecture (Layers 1 - 3):
- Open Systems Interconnection (OSI): A 7-layer universal blueprint framework dictating how all networked devices send, receive, and interpret data. [MUST REMEMBER FOR CYBERSECURITY]
- Encapsulation: The systematic process of sealing data inside protective technical containers (adding control headers/footers) as it moves down the network stack. [MUST REMEMBER FOR CYBERSECURITY]
- Layer 1 (Physical): The absolute baseline level where physical hardware equipment, copper cords, fiber optic lines, and raw binary signals (bits) live. [MUST REMEMBER FOR CYBERSECURITY]
- Layer 2 (Data Link): The physical addressing layer running on Network Interface Cards (NICs). Stamped with manufacturer-burned MAC addresses. Data unit is strictly called a **Frame**. [MUST REMEMBER FOR CYBERSECURITY]
- MAC Spoofing: An offensive software tactic used to alter a network card's apparent hardware ID to bypass MAC filtering rules or impersonate trusted endpoints. [MUST REMEMBER FOR CYBERSECURITY]
- Layer 3 (Network): The global logical routing floor operating via unique IP Addresses. Data unit is strictly called a **Packet**. [MUST REMEMBER FOR CYBERSECURITY]
- Layer 3 Devices (Routers): Specialized hardware nodes that inspect packet IP headers and execute optimal path calculations using protocols like OSPF and RIP. [MUST REMEMBER FOR CYBERSECURITY]


