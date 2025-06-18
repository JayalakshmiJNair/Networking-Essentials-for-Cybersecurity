## Firewalls

A **firewall** filters **incoming** and **outgoing** network traffic.

It uses **rules** based on **IP addresses**, **port numbers**, and **protocols** to either **allow or block traffic**.

### Types of Firewalls

**Packet Filtering Firewall**  
Performs basic filtering based on **source IP**, **destination IP**, **port numbers**, and **protocol types**.  
Limited in capability since it does **not track connection states** or inspect the contents of packets.

**Stateful Firewall**  
Tracks the **state of active connections** and makes decisions based on the **context of the traffic**.  
More secure and intelligent than simple packet filtering.

**Application Layer Firewall** (Proxy Firewall)  
Analyzes **application-level data** such as **HTTP requests and responses**.  
Provides deeper **inspection and control** over traffic based on the **application type**.

**Next-Generation Firewall (NGFW)**  
Combines multiple advanced features:  
- **Deep Packet Inspection (DPI)**  
- **Intrusion Detection/Prevention Systems (IDS/IPS)**  
- **Antivirus and malware protection**  
- **Application awareness and control**

NGFWs provide **comprehensive protection** against modern network threats.

