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


### 🏆 Day 5: 100% OSI Model Vertical Stack Mastery

- Hardened conceptual retention from Layer 1 Physical hardware bits up to Layer 7 Application protocols. [MUST REMEMBER FOR CYBERSECURITY]
- Layer 4 Transport Mechanics: Analyzed the core rules governing Transmission Control Protocol (TCP) and User Datagram Protocol (UDP). [MUST REMEMBER FOR CYBERSECURITY]
- Layer 5 Virtual Dialogue Handling: Investigated the architecture of Session Cookies and Session Tokens. Mapped out exactly how attackers execute Session Hijacking / Pass-the-Cookie exploits to completely bypass active Two-Factor Authentication (2FA) arrays without a password. [MUST REMEMBER FOR CYBERSECURITY]
- Layer 6 Presentation Logic: Verified the application of cryptographic frameworks, encryption (SSL/TLS certificates), and file layout translations. [IMPORTANT CONCEPT]
- Finished 100% of the TryHackMe OSI Model Room dashboard tasks and successfully bypassed the final simulation lab matrix. Cleared a consistent learning streak milestone!



# 🏆 Milestone Reached: 'Network Fundamentals' Module Completed! 🚀
📅 **Date:** October 6, 2026  
🏅 **Badge Earned:** `Networking Nerd`  
⚡ **Current Learning Streak:** 14 Days  

---

## 🛠️ Technical Implementation Summary

### 📦 1. Packets & Frames Mechanics (OSI Layer 2 vs. Layer 3)
*   **Layer 3 (Network Layer):** Handled logical routing containers called **Packets**, which manage raw data payloads along with crucial source and destination **IP Headers**.
*   **Layer 2 (Data Link Layer):** Handled physical local transit containers called **Frames**. A frame encapsulates the packet inside a hardware delivery envelope marked with source and destination **MAC Addresses**.
*   **Packet Header Controls:** Evaluated the mechanics of critical header stickers:
    *   `Time to Live (TTL)`: Acted as an expiry countdown timer to destroy lost looping packets, preventing global network congestion.
    *   `Checksum`: Provided automated data integrity checking by comparing mathematical calculations to identify corrupt or modified payloads.

### 🔌 2. Transmission Control Protocol (TCP) Suite
*   **Connection-Based Security:** Explored how TCP establishes a reliable connection state between a client and server before allowing data bytes to travel down the wire.
*   **The 3-Way Handshake:** Documented the exact network synchronization steps used to open a session:
    1.  `SYN` -> Client sends its Initial Sequence Number (ISN) to synchronize.
    2.  `SYN/ACK` -> Server acknowledges the request and sends its own sequence tracking base.
    3.  `ACK` -> Client confirms receipt and initiates the data transmission.
*   **Connection Teardown Flags:** 
    *   `FIN`: Sent by a device to cleanly and gracefully close a completed data session.
    *   `RST`: Sent as a violent, immediate reset flag to tear down a session when a system encounters heavy resource faults or application crashes.

### ⚡ 3. User Datagram Protocol (UDP) Architecture
*   **Stateless Operations:** Analyzed UDP's lightweight, connectionless framework. It completely bypasses handshakes and synchronization states, creating a fast, "fire-and-forget" data pipeline.
*   **Deployment Metrics:** Mapped out protocol choice logic. Reliable tasks like **File Transfers** require zero dropped bytes and must use **TCP**, whereas high-speed streams like **Live Video Calls** or online gaming tolerate minor loss and rely on **UDP** for low-latency speed.

### 🛡️ 4. Extending Your Network: Ports, Firewalls, & VLANs
*   **Port Forwarding:** Configured edge routing rules on a **Router** to map incoming public internet gateway traffic directly to hidden private IP resources inside an Intranet LAN environment.
*   **Firewall Operations:** Reviewed packet inspection engines operating across **OSI Layers 3 & 4** to police network borders using IP addresses, ports, and protocols:
    *   `Stateless Firewalls`: Handled fast filtering against static rule checklists on an individual packet basis, making them elite weapons against massive traffic floods (DDoS attacks).
    *   `Stateful Firewalls`: Tracked the dynamic connection state over time, consuming high system resources but allowing the firewall to drop a host entirely if bad behavior is observed.
*   **VLAN Segregation:** Mastered how Virtual Local Area Networks split a single physical hardware switch into completely isolated logical departments, blocking internal lateral movement and securing core network infrastructure.


### 🕸️ Day 6: HTTP Protocol Framework & Live Token Hijacking

#### 🛠️ HTTP Request Methods & Structural Functions
- **GET Request:** Invoked exclusively to retrieve structural assets and data endpoints from a remote web server. [IMPORTANT CONCEPT]
- **POST Request:** Deployed to transmit user payloads, submit structured web forms, and actively create new records on the backend. [MUST REMEMBER FOR CYBERSECURITY]
- **PUT Request:** Utilized to upload or update existing record states and persistent information hosted on a server. [CONCEPT ONLY]
- **DELETE Request:** Issued to forcefully purge or wipe target files, data records, or resources from the web architecture. [CONCEPT ONLY]

#### 📊 HTTP Status Code Ranges & Core Diagnostics
- **100-199 (Informational):** Confirms initial request components are processed; legacy baseline. [CONCEPT ONLY]
- **200-299 (Success):** Verifies the incoming client application request was executed successfully without conflicts (e.g., `200 OK`, `201 Created`). [IMPORTANT CONCEPT]
- **300-399 (Redirection):** Points the browser agent to an alternate resource pathway, handling either permanent (`301 Moved Permanently`) or temporary (`302 Found`) layout shifts. [IMPORTANT CONCEPT]
- **400-499 (Client Errors):** Highlights malformed requests from the user, including permission barriers (`401 Not Authorised`, `403 Forbidden`), invalid verbs (`405 Method Not Allowed`), or missing pages (`404 Page Not Found`). [MUST REMEMBER FOR CYBERSECURITY]
- **500-599 (Server Errors):** Points directly to major backend engine collapses, code crashes (`500 Internal Server Error`), or database downtime (`503 Service Unavailable`). [MUST REMEMBER FOR CYBERSECURITY]

#### 📤 Common Request Headers (Client-to-Server Metadata)
- **Host:** Explicitly declares the specific target domain name requested, preventing server orientation failure when handling multi-site configurations. [IMPORTANT CONCEPT]
- **User-Agent:** Discloses the browser software version, engine build, and client operating system type to enable clean frontend rendering. [IMPORTANT CONCEPT]
- **Content-Length:** Enforces structural data validation by stating the exact byte size of an incoming data payload to prevent transmission drops. [MUST REMEMBER FOR CYBERSECURITY]
- **Accept-Encoding:** Announces the exact compression algorithms (e.g., Gzip) supported by the browser to optimize network speed. [CONCEPT ONLY]

#### 📥 Common Response Headers (Server-to-Client Metadata)
- **Content-Type:** Mandates how the local browser engine processes and renders the file payload based on explicit declarations (e.g., `text/html`, `image/png`, `application/pdf`). [MUST REMEMBER FOR CYBERSECURITY]
- **Cache-Control:** Dictates exactly how many seconds a client machine should store data assets locally before forcing a fresh network download request. [IMPORTANT CONCEPT]
- **Set-Cookie:** Issued by a remote server to instruct the local web browser to write a specific tracking or state token to local memory. [MUST REMEMBER FOR CYBERSECURITY]

#### 🔬 Session State Management & Practical Token Hijacking
- **The Stateless Problem:** HTTP retains no persistence memory across individual actions; cookies serve as the layer to maintain user authentication states. [IMPORTANT CONCEPT]
- **Session Tokens:** Security parameters employ unique, randomized, non-guessable token strings inside cookie arrays instead of using plain-text user passwords. [MUST REMEMBER FOR CYBERSECURITY]
- **Live Exploitation Lab (Session Hijacking):** Successfully extracted active authentication cookie parameters (`sessionid` & `ds_user_id`) from a live authenticated session context. Manually injected the intercepted token payload into a separate isolated browser profile to completely bypass the login screen and 2-Factor Authentication (2FA) walls. Verified the threat vector of Infostealer malware engines targeting local browser caching architecture.
- **Milestone Completed:** Solved the manual HTTP interactive request simulation lab to earn the official **"Webbed"** profile badge at 100% completion.


### 🕸️ Day 7: Web Frontend Exploitation & Client-Side Injection Mechanics

#### 🏗️ Core Frontend Architecture & Public Visibility Rule
- **HTML (Skeleton Framework):** Establishes the static structural data elements and raw presentation tags of a web application page.
- **CSS (Layout Template Engine):** Governs the global presentation, style design rules, visibility parameters, and operational visual properties.
- **JavaScript (Dynamic Logic Execution):** Operates as the functional engine managing runtime updates, interactive user events, and real-time DOM alterations.
- **The Visibility Constraint:** All client-side parameters, configurations, structural setups, and interactive code modules are fully readable by users via static page source tools (`Ctrl + U`).

#### 🕵️‍♂️ Information Gathering & Sensitive Data Exposure (CWE-200)
- **Comment Node Leakage:** Investigated security failures where developers accidentally leave authentication variables or server maps exposed inside HTML comments (`<!-- comment -->`).
- **Hidden Redirection Paths:** Evaluated architectural layout manipulation using specific CSS attributes (`style="display:none;"`) to conceal administrative routing directories from frontend menus while leaving the underlying paths fully exposed to manual source code audits.


### 🛡️ Day 7: Operational Security Foundations & The CIA Triad

#### 📐 The Core Security Framework Matrix (The CIA Triad)
- **Confidentiality (Data Restriction Constraints):** Governs strict access verification controls ensuring sensitive elements are only exposed to authorized entities. Checked failures include clear-text parameter leakage over unsecured public coffee shop networks.
- **Integrity (Data Veracity Protocols):** Assures digital strings remain completely unaltered during dynamic network transit loops. Failure vectors analyze mid-routing alteration of transaction destination fields or grade manipulation.
- **Availability (System Persistence Standards):** Guarantees high-availability metrics for operational infrastructure whenever authorized clients initiate connection requests. Primary mitigation loops target DDoS traffic spikes using load thresholds.

#### 🧪 Hands-On Threat Modeling Exercises
- **Incident Analysis Sorting:** Configured a 9-incident scenario data grid to accurately isolate infrastructure failures into independent triad vectors with a first-run precision score of 88.8%.
- **DDoS Adversarial Intel:** Evaluated operational target motivations behind Availability disruption vectors, highlighting Ransom DDoS (RDDoS) extortion tactics, competitor-hired revenue manipulation, and operational distraction/smoke-screen deployments hiding backend data theft.
- **Room Status:** Successfully finalized all core evaluation matrix variables to achieve a 100% complete green verification status flag.


#### 🧪 Client-Side HTML Injection (Input Validation Failure)
- **The Input Standard Constraint:** Evaluated the high-risk operational core rule of web application security: *"Never Trust User Input."*
- **Sanitization Failure Mechanics:** Explored instances where application input controllers fail to filter, validate, or sanitize input text strings before rendering them to the active viewport environment.
- **Payload Construction & Injection:** Developed and successfully deployed an arbitrary HTML anchor string injection (`<a href="http://target.com">Text</a>`) into an active web form field to forcefully restructure the page visual interface and generate authenticated platform flags.
- **Room Completed:** Fully closed out all conceptual testing elements to achieve 100% green score validation across the "How Websites Work" framework matrix.

#### 🔑 Cryptographic Engineering & Key Management Protocols
- **Symmetric Architecture:** Leverages a single shared key for both encryption and decryption execution loops. Highly efficient for bulk data processing but bounded by the Key Distribution Problem. Tested ciphers: Caesar Cipher (ROT13 Shift Framework).
- **Asymmetric Framework:** Utilizes mathematically linked Public/Private key pairs to eliminate the need for pre-shared network secrets. Recovering private keys from public keys is computationally secure against standard architectures.
- **Hybrid HTTPS Implementation:** Employs Asymmetric primitives and Certificate Authority (CA) validation metrics to securely establish a shared symmetric session seed, switching to symmetric arrays for low-latency bulk data encapsulation.
- **Automation Bypass:** Successfully automated Caesar Cipher ciphertext analysis (`XLMW MW XLI JMREP GSHI`) using custom shift logic (-4 position mapping to `THIS IS THE FINAL CODE`), clearing all active sandbox flags.


### 🛡️ Defensive Security Operations: Infrastructure Mapping & Blue Team Blueprints

#### 🏙️ Client Infrastructure Visibility (The City Analogy)
- **Asset Monitoring:** Established high-level infrastructure visibility parameters by mapping physical enterprise devices to conceptual city grids (Workstations to Homes, Web Servers to Shops, Mail Servers to Post Offices).
- **Perimeter Gateways:** Configured firewall boundary filters mapped as localized "City Gates" to structurally control external network transit loops and reject untrusted traffic vectors.

#### 🛠️ Blue Team Incident Response Operations
- **Prevention Controls:** Integrated deep boundary firewalls, local anti-malware programs, and endpoint software patching to stop structural vulnerability discovery.
- **Detection & Mitigation:** Tracked automated traffic logs and security alerts to isolate suspicious anomalies (repeated login errors or anomalous IP ranges), deploying containment blocks to minimize dynamic risk.
- **Risk Prioritization:** Applied structural auditing protocols to identify high-value system assets (core data stores and server clusters) to guide security engineering priorities.

#### 🎓 Path Graduation Milestone
- **Path Status:** 100% complete across all evaluation models.
- **Milestone Captured:** Official Pre Security Certification unlocked. Verified foundational core proficiency across Linux CLI, Windows Architecture, Advanced Network Protocols, Web Infrastructure Security, and Cryptographic Handshakes.


