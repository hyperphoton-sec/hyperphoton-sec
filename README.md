👋 Hi, I'm Arnav | Future Cyber Defense Architect & Enterprise Defender

🚀 Managing a high-velocity sprint to master Infrastructure Security, Log Analytics, and Cloud Defense Systems. 
🛡️ Training to safeguard critical enterprise architectures while tracking towards global remote security operations.


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



# TryHackMe: Cyber Security 101 — Search Skills Room
**Path:** Cyber Security 101 (Foundational Path)
**Focus Area:** Threat Intelligence, OSINT, Engine Filtering, and Technical Verification
**Status:** 100% Completed

## [1] OSINT & Infrastructure Enumeration (Shodan)
- **Core Architecture:** Shodan maps globally exposed IP addresses, critical industrial control systems (ICS), network routing hardware, and Internet of Things (IoT) endpoints.
- **Data Extraction:** Extracts banner responses from open diagnostic ports to determine running software instances and structural configurations.
- **Query Filter Logic:**
  - `country:CODE` -> Isolates network scanning to precise geographic boundaries (e.g., `country:IE`).
  - `port:NUMBER` -> Restricts search arrays to systems exposing specific access services (e.g., `port:22` for SSH).
  - `org:ASN/NAME` -> Limits exposure scanning to autonomous network segments or enterprise subnets (e.g., `org:AS7224` for AWS).
  - `hostname:DOMAIN` -> Matches target configurations directly against target domain infrastructures.

## [2] Reputation Analytics & Malware Triage (VirusTotal)
- **Consensus Aggregator:** Collects telemetry logs and analytical engines from over 70 external antivirus suites and web domain scanners.
- **Ingestion Vectors:** Processes operational queries via absolute file uploads, malicious URLs, target fully qualified domains, or cryptographic file hashes (MD5, SHA-1, SHA-256).
- **Analytical Constraints:** Not entirely foolproof against Fully Undetectable (FUD) or complex polymorphic malware architectures. Used by SOC analysts to establish quick baseline reputation alerts during initial triage phases.

## [3] Vulnerability Tracking & Standardization (CVE / CVSS Framework)
- **Universal Catalog:** The Common Vulnerabilities and Exposures (CVE) database acts as the primary global record for disclosed software and hardware infrastructure security flaws.
- **Naming Constraints:** Standardized registry formatting follows the `CVE-YEAR-NUMBER` blueprint (e.g., `CVE-2025-55182`), with major systemic exploits receiving monikers (e.g., Log4Shell, Heartbleed).
- **Risk Assessment:** The Common Vulnerability Scoring System (CVSS) calculates risk metrics based on technical Impact, Exploit Complexity, and Exploit Availability to prioritize mitigation queues.
- **Exploit Verification:** Integrates with public code databases like ExploitDB to match technical CVE indexes with functional Proof of Concept (PoC) scripts.

## [4] Native System Documentation (Linux MAN Engine)
- **Local Telemetry Ground-Truth:** Native tool manual systems are more definitive than arbitrary third-party walkthroughs for understanding syntax execution constraints.
- **Local Shell Ingestion:** The `man <command>` syntax displays local, text-based operational guides for active utility packages directly inside the terminal interface.
- **Dissection Mechanics:** Reading the SYNOPSIS array outlines mandatory positions, positional parameters, and active arguments required to manage critical network binaries such as Netcat (`nc`).

## [5] Open-Source Intelligence Validation (GitHub Repositories)
- **Velocity Advantages:** Independent threat researchers deploy tactical exploit codes and vulnerability scanning mechanics on GitHub faster than vendor patching intervals.
- **Verification Mandate:** Publicly hosted PoC configurations present structural risks. Scripts can contain syntax defects, deliberate execution bugs, or malicious obfuscated strings designed to compromise the analyst's workstation. Verification before local deployment is mandatory.


# Linux Fundamentals Part 1

## Commands I learned

### 1. `ls`

`ls` is used to list the files and folders in a directory.

```bash
ls
ls -l
ls -a
```

- `ls` shows the files and folders in the current directory.
- `ls -l` shows more details like permissions, owner, size and date.
- `ls -a` also shows hidden files, whose names usually start with a dot (`.`).

### 2. `cat`

`cat` is used to display the contents of a file.

```bash
cat filename
```

It can also display the contents of multiple files.

```bash
cat file1 file2
```

I can use it to read text files and check what is written inside them.

### 3. `file`

The `file` command helps identify what type of file something is.

```bash
file filename
```

A file's extension does not always tell us what it actually contains, so this command can be useful when checking an unfamiliar file.

### 4. `find`

`find` is used to search for files and directories.

```bash
find /path -name "filename"
```

Some other useful examples:

```bash
find /path -type f
find /path -type d
```

- `-name` searches by name.
- `-type f` searches for regular files.
- `-type d` searches for directories.

The search starts from the path I specify. Permissions can affect which results I can access.

## Linux operators

### `&` — Run in the background

Adding `&` at the end of a command lets it run in the background, so I can use the terminal for other commands without waiting for it to finish.

```bash
command &
```

### `&&` — Run the next command after success

`&&` runs the second command only if the first command succeeds.

```bash
command1 && command2
```

### `>` — Write output to a file

This redirects command output into a file. If the file already contains something, its old contents are overwritten.

```bash
echo "TryHackMe" > thm
```

To check the contents:

```bash
cat thm
```

Output:

```text
TryHackMe
```

### `>>` — Add output to a file

This works like `>`, but it adds the new output at the end instead of replacing the existing contents.

```bash
echo "thm" >> thm
```

Now `cat thm` displays:

```text
TryHackMe
thm
```

Both `>` and `>>` can create a file if it does not exist, provided I have permission to write there.

## Quick revision

| Command / operator | What it does |
|---|---|
| `ls` | Lists files and directories |
| `cat` | Displays file contents |
| `file` | Identifies the likely file type |
| `find` | Searches for files and directories |
| `&` | Runs a command in the background |
| `&&` | Runs the next command if the first succeeds |
| `>` | Writes output and overwrites existing contents |
| `>>` | Appends output to existing contents |

## What I learned

# Linux Fundamentals Part 2 — Learning Notes

**Learning platform:** [TryHackMe](https://tryhackme.com/)  
**Status:** Completed  
**Focus:** SSH, File Operations, Filesystem Navigation, Permissions, Users & Groups

These are my personal notes from completing the Linux Fundamentals Part 2 room on TryHackMe. I have documented the commands, concepts, practical examples, and mistakes that helped me understand Linux better.

## 1. SSH (Secure Shell)

SSH is used to connect to and manage a remote machine over an encrypted connection.

### Connecting to a remote machine

```bash
ssh tryhackme@MACHINE_IP
```

- `ssh` starts an SSH connection.
- `tryhackme` is the username.
- `MACHINE_IP` must be replaced with the actual IP address of the target machine.

On the first connection, SSH may display the server's host-key fingerprint and ask for confirmation. The fingerprint should be verified when possible before trusting the host.

### Useful commands after connecting

```bash
whoami
hostname
pwd
```

- `whoami` displays the current username.
- `hostname` displays the machine's hostname.
- `pwd` displays the current working directory.

**What I learned:** The AttackBox and the target machine are separate environments. Before running commands, I should verify which machine I am connected to.

## 2. File and Directory Operations

| Command | Purpose |
|---|---|
| `ls` | Lists directory contents |
| `ls -a` | Includes hidden entries |
| `ls -l` | Shows detailed file information |
| `cd Documents` | Enters the Documents directory |
| `cd ..` | Moves to the parent directory |
| `cd ~` | Goes to the current user's home directory |
| `pwd` | Shows the current location |
| `touch file.txt` | Creates an empty file if it does not exist |
| `mkdir folder` | Creates a directory |
| `cp source destination` | Copies a file |
| `mv source destination` | Moves or renames a file |
| `rm file.txt` | Removes a file |
| `rm -R folder` | Removes a directory and its contents recursively |
| `cat file.txt` | Displays a file's contents |

### Copying a file

To copy a file named `note` from the home directory into `Documents`:

```bash
cd ~
cp note Documents/
ls Documents
```

The last command can be used to verify that the file exists in the destination directory.

The `cp` command needs both a source and a destination. Running `cp note` alone produces an error because the destination is missing.

### Case sensitivity

Linux distinguishes uppercase and lowercase letters in path names.

```bash
cd Documents
```

is not necessarily equivalent to:

```bash
cd documents
```

**What I learned:** When a path does not work, check its spelling and capitalization before assuming the directory does not exist.

## 3. Navigating the Filesystem

The following symbols are useful when working with paths:

- `.` refers to the current directory.
- `..` refers to the parent directory.
- `~` refers to the current user's home directory.
- `/` is the root of the filesystem.

Examples:

```bash
ls ./
cd ..
cd ~
cd /
```

The `tree` command displays files and directories in a hierarchical structure.

```bash
tree
```

To limit the displayed depth:

```bash
tree -L 2 /
```

The `tree` utility may not be installed on every Linux system.

## 4. Important Linux Directories

Linux organises its filesystem beneath `/`, the filesystem root.

### `/etc` — Configuration

Contains system and application configuration files.

Examples:

- `/etc/passwd` — Stores user-account information.
- `/etc/sudoers` — Defines sudo privileges and related rules.

### `/var` — Variable Data

Contains data that changes during normal system operation, including logs and application data.

An important location is:

```bash
/var/log
```

Many Linux services and applications store their logs here.

### `/root` — Root User's Home

The home directory of the `root` administrator account. It is different from `/`, which is the top-level directory of the entire filesystem.

### `/tmp` — Temporary Files

Used for temporary data. Files may be removed during reboot or by scheduled cleanup, depending on the system configuration.

### `/home` — User Home Directories

Contains home directories for regular users, such as `/home/tryhackme`.

**What I learned:** Knowing the purpose of these directories makes it easier to navigate Linux systems and locate relevant configuration files, user data, and logs.

## 5. Linux File Permissions

The `ls -l` command displays detailed information about files and directories, including their permissions and ownership.

Example:

```text
-rw-r--r-- 1 tryhackme tryhackme 0 Feb 19 10:37 file1
```

The permission string is:

```text
-rw-r--r--
```

It can be broken down into four parts:

| Part | Meaning |
|---|---|
| `-` | Regular file |
| `rw-` | Owner can read and write |
| `r--` | Group can read |
| `r--` | Other users can read |

The permission symbols are:

- `r` — Read
- `w` — Write
- `x` — Execute
- `-` — Permission not granted

For regular files, read allows viewing contents, write allows modifying contents, and execute allows running the file as a program or script when applicable.

For directories, permissions work differently:

- Read allows listing directory entries.
- Write allows creating or removing entries, subject to other restrictions.
- Execute allows traversing the directory and accessing entries when other permissions allow it.

## 6. Users and Groups

Each file has an owner and an associated group. Linux can assign different permissions to:

1. The owner
2. Members of the file's group
3. Other users

This allows administrators to control who can read, modify, or execute files without giving every user administrative access.

In the example below:

```text
-rw-r--r-- 1 tryhackme tryhackme 0 Feb 19 10:37 file1
```

The first `tryhackme` identifies the owner, and the second identifies the associated group.

## 7. Switching Users with `su`

The `su` command allows a user to switch to another account, subject to authentication and permission requirements.

To switch to `user2` with a login-style shell:

```bash
su -l user2
```

The `-l` option requests a login-style environment for the target user.

After entering the password provided by the training room, verify the active account:

```bash
whoami
```

The expected username is:

```text
user2
```

The contents of a file can then be displayed with:

```bash
cat important
```

This exercise demonstrated that access to a file can depend on the current user's permissions.

## 8. Troubleshooting and Lessons Learned

During the practical exercises, I encountered errors that helped me understand Linux commands more clearly.

- **Incorrect option:** `su -1` uses the number `1`, whereas `su -l` uses the lowercase letter `l`.
- **Missing destination:** `cp` requires both a source and a destination.
- **Case sensitivity:** `Documents` and `documents` may refer to different paths.
- **Wrong environment:** The AttackBox and the target machine are separate systems.
- **Password input:** Password prompts generally do not display typed characters.
- **Command versus argument:** A username such as `user2` must be passed to `su`; entering it alone makes the shell attempt to execute it as a command.

These mistakes helped me practise troubleshooting instead of repeatedly running commands without understanding the errors.

## 9. Relevance to Blue Team Security

These Linux fundamentals are useful when investigating systems and security incidents.

- **SSH:** Understanding remote access and administration.
- **Filesystem navigation:** Locating files and system directories.
- **Logs:** Finding relevant records during an investigation.
- **Permissions:** Understanding access restrictions and potential permission-related risks.
- **Users and groups:** Investigating ownership and access privileges.
- **Command-line troubleshooting:** Working more confidently in Linux environments.

## Progress

- Completed TryHackMe Linux Fundamentals Part 2.
- Practised SSH access, file copying, directory navigation, and switching users.
- Studied filesystem structure, file permissions, and user/group concepts.
- Identified and corrected command-line mistakes during practical exercises.

**Next focus:** Continue strengthening Linux and networking fundamentals before moving deeper into Blue Team and SOC-related skills.

*These notes are written for personal revision and reflect my learning from the room. I will update them as I revisit concepts and apply them in future labs.*

I learned how to list files, read their contents, identify file types and search for files. I also learned the difference between `>` and `>>`. The main thing to remember is that `>` can overwrite existing data, while `>>` preserves the old content and adds new output.

## Progress

- Platform: TryHackMe
- Room: Linux Fundamentals Part 1
- Status: Completed
- Next: Linux Fundamentals Part 2



# Linux Fundamentals Part 3 — Learning Notes

**Learning platform:** [TryHackMe](https://tryhackme.com/)  
**Topic:** Linux Fundamentals Part 3  
**Purpose:** Personal notes, command practice, and revision.

> These notes summarize concepts studied while working through the TryHackMe Linux Fundamentals Part 3 room. Examples are for learning and authorized lab environments.

## 1. Nano — Command-Line Text Editor

Nano is a terminal-based text editor used to create and edit files.

### Open or create a file

```bash
nano filename
```

If the file already exists, Nano opens it. If it does not exist, Nano lets you create it.

### Useful Nano keyboard shortcuts

| Shortcut | Function |
|---|---|
| `Ctrl + O` | Save/write the file |
| `Ctrl + X` | Exit Nano |
| `Ctrl + W` | Search within the file |
| `Ctrl + K` | Cut the current line |
| `Ctrl + G` | Open Nano's help |

### Practical example

```bash
nano myfile
```

Type some text, save it with `Ctrl + O`, confirm the filename if prompted, and exit with `Ctrl + X`.

Verify the saved contents:

```bash
cat myfile
```

**Key takeaway:** Nano edits the file; `cat` can display its contents in the terminal.

## 2. File Transfers in Linux

Files can be transferred between systems using different tools. The appropriate method depends on the environment and access available.

### A. `wget` — Download a file

`wget` downloads files from a URL over supported protocols such as HTTP and HTTPS.

```bash
wget https://example.com/file.txt
```

The file is normally saved in the current working directory.

To read a downloaded text file:

```bash
cat file.txt
```

### B. `scp` — Securely copy files over SSH

`scp` copies files between local and remote systems using SSH.

**Copy a local file to a remote machine:**

```bash
scp file.txt username@REMOTE_IP:/destination/path/
```

**Copy a remote file to the local machine:**

```bash
scp username@REMOTE_IP:/path/file.txt ./file.txt
```

Replace the example username, IP address, and paths with the actual values for the authorized system.

### C. Python HTTP server

Python can serve files from the current directory over HTTP.

Start a server on port 8000:

```bash
python3 -m http.server 8000
```

Keep the server terminal running while clients connect. From another terminal or authorized lab machine, a client can download an accessible file using its server IP and port.

Example:

```bash
wget http://SERVER_IP:8000/file.txt
```

Replace `SERVER_IP` with the actual server IP.

**Important:** The server exposes files from its serving directory to clients that can reach it. Use a trusted, authorized lab network and avoid exposing sensitive files.

### Practical learning

In the TryHackMe lab, I used a Python HTTP server on the deployed machine and downloaded a hidden file named `.flag.txt` to the AttackBox with `wget`. The download returned `200 OK`, confirming a successful HTTP response.

The file was then ready to be inspected locally:

```bash
cat .flag.txt
```

**Key takeaway:**
- `wget` downloads from a URL.
- `scp` securely copies files over SSH.
- `python3 -m http.server 8000` serves files over HTTP from the current directory.

## 3. Processes and PIDs

A **process** is a running instance of a program. The operating system's kernel manages processes.

Each process has a **PID (Process ID)** that identifies it.

### View processes

Show processes associated with the current terminal session:

```bash
ps
```

Show a detailed list of processes visible on the system:

```bash
ps aux
```

Display a live, continuously refreshed process view:

```bash
top
```

Press `q` to quit `top`.

### Understanding `ps aux`

The output can contain many rows because numerous processes may be running simultaneously.

Common columns include:

- `USER` — user associated with the process
- `PID` — process ID
- `%CPU` — CPU usage
- `%MEM` — memory usage
- `COMMAND` — command or program associated with the process

`ps aux` displays a snapshot; `top` is useful for ongoing monitoring.

### Stop or signal a process

The `kill` command sends a signal to a process identified by its PID.

```bash
kill PID
```

Replace `PID` with the actual process ID.

Common signals:

| Signal | Purpose |
|---|---|
| `SIGTERM` | Requests termination and allows cleanup where possible |
| `SIGKILL` | Forces termination without normal cleanup |
| `SIGSTOP` | Suspends a process |

The default signal for `kill PID` is normally `SIGTERM`.

**Safety note:** Identify a process before signalling it. Avoid terminating system-critical processes or processes you do not control.

## 4. `systemd` and `systemctl`

On many Linux distributions, `systemd` initializes and manages system services.

`systemctl` is used to interact with services managed by `systemd`.

### Common commands

Check service status:

```bash
systemctl status apache2
```

Start a service now:

```bash
systemctl start apache2
```

Stop a service:

```bash
systemctl stop apache2
```

Configure a service to start automatically at boot:

```bash
systemctl enable apache2
```

Disable automatic startup at boot:

```bash
systemctl disable apache2
```

These examples use Apache's service name on systems where it is called `apache2`. Service names and permissions can vary by Linux distribution.

### Important distinction

- `start` — starts the service now.
- `enable` — configures automatic startup at boot.
- `status` — checks the service's current state.
- `stop` — stops the service.
- `disable` — disables automatic startup at boot.

Enabling a service does not generally mean that it starts immediately.

## 5. Foreground and Background Processes

A foreground process runs attached to the terminal, so its interaction or output occupies that terminal session.

A background process runs without requiring the terminal to wait for it in the same way.

### Run a command in the background

Add `&` at the end of a command:

```bash
sleep 300 &
```

The shell starts the job in the background and normally returns control to the prompt.

### Suspend a foreground job

Press:

```text
Ctrl + Z
```

This suspends the foreground job. It does not necessarily terminate the process.

### Bring a job back to the foreground

```bash
fg
```

This brings the current background or suspended job into the foreground. If multiple jobs exist, job selection may be necessary.

### Stop a foreground command

```text
Ctrl + C
```

This normally sends an interrupt to the foreground process. The exact result depends on the program.

### Quick comparison

| Action | Typical use |
|---|---|
| `&` | Start a command as a background job |
| `Ctrl + Z` | Suspend the current foreground job |
| `fg` | Bring a job to the foreground |
| `Ctrl + C` | Interrupt a foreground command |

## 6. Commands to Revise

| Command | Purpose |
|---|---|
| `nano filename` | Open or create a file in Nano |
| `cat filename` | Display file contents |
| `wget URL` | Download a file from a URL |
| `scp SOURCE DESTINATION` | Copy files securely over SSH |
| `python3 -m http.server 8000` | Start a simple HTTP file server on port 8000 |
| `ps` | View processes associated with the current session |
| `ps aux` | View a detailed process listing |
| `top` | Monitor processes and resource usage live |
| `kill PID` | Send the default signal to a process |
| `systemctl status SERVICE` | Check service status |
| `systemctl start SERVICE` | Start a service |
| `systemctl enable SERVICE` | Configure automatic startup at boot |
| `sleep 300 &` | Run a sleep command as a background job |
| `fg` | Bring a job into the foreground |

## 7. Revision Notes

- Do not expect to memorize every command after reading it once. Repeating commands in a terminal improves recall.
- Understand what a command does before running it on a real system.
- Use TryHackMe's authorized lab machines for practical exercises.
- Record the tasks actually completed and the concepts genuinely understood; do not claim uncompleted tasks.

**Progress note:** These notes cover the topics studied so far in Linux Fundamentals Part 3. Add further topics and practical results as the room progresses.

**Credit:** Learning material and lab exercises from TryHackMe — Linux Fundamentals Part 3. These are personal notes written for revision.

## Task 5: Processes 101

**Learning platform:** TryHackMe
**Room:** Linux Fundamentals Part 3

### 1. Processes and PIDs

A process is a running instance of a program. The Linux kernel manages processes, and each process has a Process ID (PID).

- **PID:** Identifies a process.
- **Parent and child processes:** Processes can start other processes.
- PIDs are allocated by the operating system; they do not always increase consecutively because IDs can be reused or allocated differently.

### 2. Viewing Processes

#### `ps`

```bash
ps
```

Displays a snapshot of processes associated with the current terminal session.

#### `ps aux`

```bash
ps aux
```

Displays a detailed list of processes visible to the command, including processes associated with other users.

Useful columns include:

| Column    | Meaning                             |
| --------- | ----------------------------------- |
| `USER`    | User associated with the process    |
| `PID`     | Process ID                          |
| `%CPU`    | CPU usage                           |
| `%MEM`    | Memory usage                        |
| `COMMAND` | Command associated with the process |

#### `top`

```bash
top
```

Shows a continuously refreshed view of processes and resource usage. Press `q` to exit.

**Remember:** `ps` provides a snapshot, while `top` is useful for live monitoring.

### 3. Process Signals

The `kill` command sends a signal to a process identified by its PID.

```bash
kill PID
```

Replace `PID` with the actual process ID.

| Signal    | Purpose                                                        |
| --------- | -------------------------------------------------------------- |
| `SIGTERM` | Requests termination and allows the process to perform cleanup |
| `SIGKILL` | Forces termination without normal cleanup                      |
| `SIGSTOP` | Suspends a process                                             |

The default signal sent by `kill PID` is `SIGTERM`.

Memory aid:

- `TERM` → request termination
- `KILL` → force termination
- `STOP` → suspend

### 4. `systemd` and Services

`systemd` is an init system and service manager used by many Linux distributions. On systems using systemd, it commonly runs as PID 1.

`systemctl` is used to manage systemd services.

```bash
systemctl status apache2
systemctl start apache2
systemctl stop apache2
systemctl enable apache2
systemctl disable apache2
```

| Option    | Purpose                             |
| --------- | ----------------------------------- |
| `status`  | Check service state                 |
| `start`   | Start a service now                 |
| `stop`    | Stop a service now                  |
| `enable`  | Configure automatic startup at boot |
| `disable` | Disable automatic startup at boot   |

`start` and `enable` have different purposes: one starts a service immediately, while the other configures its startup behaviour.

The example uses the service name `apache2`; names and permissions can vary by system.

### 5. Foreground and Background Jobs

A foreground job runs attached to the current terminal. A background job allows the shell to return control so other commands can be entered.

#### Start a command in the background

```bash
sleep 300 &
```

The `&` operator starts the command as a background job.

#### Suspend a foreground job

Press:

```text
Ctrl + Z
```

This suspends the current foreground job rather than terminating it.

#### Bring a job to the foreground

```bash
fg
```

Brings the current or selected job back to the foreground.

#### Interrupt a foreground command

Press:

```text
Ctrl + C
```

This normally sends an interrupt signal to the foreground command.

**Important distinction:**

- `Ctrl + C` → interrupt
- `Ctrl + Z` → suspend
- `fg` → foreground a job
- `&` → start a command in the background

### 6. Namespaces and Process Isolation

Linux namespaces help isolate certain system resources and views between groups of processes. They are useful in security and containerization.

The exact isolation depends on the namespace type; namespaces do not simply divide CPU and RAM into fixed slices.

### Revision Checklist

- [ ] Explain what a process and PID are.
- [ ] Know the difference between `ps`, `ps aux`, and `top`.
- [ ] Distinguish `SIGTERM`, `SIGKILL`, and `SIGSTOP`.
- [ ] Understand `systemctl start` versus `systemctl enable`.
- [ ] Explain the difference between foreground and background jobs.
- [ ] Recall the purpose of `&`, `Ctrl + C`, `Ctrl + Z`, and `fg`.

**Source credit:** TryHackMe — Linux Fundamentals Part 3, Task 5: Processes 101. These are personal learning and revision notes.
# Linux Fundamentals Part 3 — Additional Notes

## Task 6: Automation — Cron Jobs

### Key Concepts
- `cron` is a Linux service used to schedule commands or scripts to run automatically.
- `crontab` is used to manage scheduled cron jobs.
- Cron schedule format:

  `MIN HOUR DOM MON DOW COMMAND`

### Useful Commands
- `crontab -l` — List the current user's cron jobs.
- `crontab -e` — Edit the current user's crontab.

### Special Syntax
- `*` — Any value.
- `*/12` — Every 12 units in that field.
- `@reboot` — Run the scheduled command when the system boots.

### Example
`0 */12 * * * command`

This runs the command at minute 0 every 12 hours.

**Remember:** Cron jobs automate recurring or scheduled tasks. Check the actual crontab configuration to determine when a job runs.

---

## Task 7: Maintaining Your System — Package Management

### Key Concepts
- A **package** contains software and the files needed to install it.
- A **repository** is a source from which packages can be obtained.
- APT is a package-management tool used on Ubuntu and other Debian-based distributions.
- GPG keys help verify the authenticity of packages and repositories.

### Useful Commands
- `apt update` — Refresh package lists.
- `apt install package-name` — Install a package.
- `apt remove package-name` — Remove a package.
- `add-apt-repository` — Add a software repository.
- `add-apt-repository --remove repository-name` — Remove a repository.

Repository configuration is commonly stored in `/etc/apt/sources.list` and `/etc/apt/sources.list.d/`.

**Remember:** `apt update` refreshes package information; it does not itself upgrade all installed software.

---

## Task 8: Maintaining Your System — Logs

### Key Concepts
- Linux logs are commonly stored in `/var/log`.
- Logs help administrators investigate system health, application errors, authentication attempts and suspicious activity.
- Log rotation manages old logs and helps prevent log files from growing indefinitely.

### Apache Logs
Apache logs are commonly found in `/var/log/apache2/`.

- `access.log` — Records HTTP requests made to the web server.
- `error.log` — Records errors reported by Apache.
- Rotated files, such as `access.log.1`, may contain older log entries.

### Useful Commands
- `cd /var/log/apache2` — Navigate to the Apache log directory.
- `ls -la` — List files, including hidden files, with details.
- `cat access.log` — Read the current access log if permissions allow.
- `cat access.log.1` — Read the first rotated access log if permissions allow.

### Reading an Access Log Entry

Example:

`10.9.232.111 - - [04/May/2021:18:18:16 +0000] "GET /catsanddogs.jpg HTTP/1.1" 200 51395`

- `10.9.232.111` — Client IP address.
- `GET` — HTTP request method.
- `/catsanddogs.jpg` — Requested resource.
- `200` — HTTP status code indicating success.

**Practical takeaway:** Apache access logs can help identify which IP address made a request and which resource it requested.

---

## Revision Checklist

- [ ] Explain what cron jobs do and interpret a basic schedule.
- [ ] Distinguish `crontab -l` from `crontab -e`.
- [ ] Explain the difference between `apt update` and `apt install`.
- [ ] Locate Apache logs in `/var/log/apache2/`.
- [ ] Identify a client IP, requested resource and HTTP status code in an access log.

Source: TryHackMe — Linux Fundamentals Part 3.



