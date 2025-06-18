## Advanced Networking for Cybersecurity

### A. Network Segmentation & Microsegmentation
- **Segmentation**: Breaks the network into smaller parts for improved security.
- **Microsegmentation**: Applies security policies to **individual devices or VMs**.
- Prevents **lateral movement** by attackers inside a network.

### B. Network Access Control (NAC)
- Ensures only **trusted and compliant devices** can connect to the network.
- Uses **802.1X authentication**, **device posture checks**, and security policies.
- Blocks **rogue or vulnerable devices** from accessing resources.

### C. Software-Defined Networking (SDN)
- Provides **centralized control** of the network via a **controller**.
- Enables **automation, scalability, and dynamic threat response**.
- Common protocol: **OpenFlow**.

### D. IPv6 Security
- **Larger address space** and **built-in IPsec** support.
- Security concerns include:
  - **Extension header abuse**
  - **Rogue router advertisements**

### E. Deep Packet Inspection (DPI)
- Analyzes the **entire content of packets** (not just headers).
- Detects **malware, data leaks, and policy violations**.
- Used in **Next-Gen Firewalls (NGFWs)** and **Data Loss Prevention (DLP)** systems.

### F. SIEM (Security Information and Event Management)
- Collects and correlates **log data from multiple sources**.
- Helps detect and respond to **cyberattacks in real-time**.
- Examples: **Splunk, IBM QRadar, ELK Stack**.

### G. Cloud Networking
- Platforms like **AWS, Azure, and GCP** use **virtual networks** (VPC/VNet).
- Security components include:
  - **Security Groups**
  - **Network Access Control Lists (NACLs)**
  - **Subnets**
- Requires understanding the **Shared Responsibility Model**.

### H. Zero Trust Architecture
- Assumes **no implicit trust**, even within the internal network.
- Relies on **identity-based access control**, **least privilege**, and **continuous monitoring**.

### I. Network Forensics
- Involves capturing and analyzing **network traffic** after an incident.
- Tools analyze **PCAP files**, **logs**, and event correlation.
- Useful for identifying the **source and timeline** of an attack.

### J. IoT and SCADA Networks
- Found in **smart devices** and **industrial control systems**.
- Often have **insecure protocols** and **lack built-in security**.
- Secure them via:
  - **Segmentation**
  - **Protocol monitoring** (e.g., **Modbus**, **BACnet**)
