## Security Devices

- Firewall
- Intrusion Detection System (IDS)
- Intrusion Prevention System (IPS)

---

### Firewall

- Can be **hardware or software**
- Works at **Layers 2,3,4 & 7 of the OSI model**
- Blocks unwanted traffic entering or leaving a network
- **Stateless inspection**: Checks each packet aganist rules
- Acts like a police force of the network- first line of defense

  ---

 ### Intrusion Detection System (IDS)

- **Passive system** that detects attacks
-  Not able to stop attacks
- Analyzes copy of traffic using
   - **Signature-based** (Known patterns)
   - **Anomaly-based** (Unusual behaviour)
   - **Policy-based** (Custom rules)
- **Host-based IDS (HIDS)**: Deployed on individual devices

  ---

### Intrusion Prevention System (IPS)

- **Active system** that can detect and stop attack
- Sits inline in the network
- **Blocks, shut down, redirects or alerts** upon attack detection
- Best placed between firewall/router and internal network
