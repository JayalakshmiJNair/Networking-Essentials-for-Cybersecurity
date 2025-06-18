## Common Network Protocols

| **Protocol** | **Full Form**                             | **Port(s)**      | **Use**                                  | **Security Concerns**                                |
|--------------|-------------------------------------------|------------------|------------------------------------------|--------------------------------------------------    |
| **HTTP**     | HyperText Transfer Protocol               | 80               | Web traffic                              | Not encrypted; vulnerable to sniffing & MITM         |
| **HTTPS**    | HyperText Transfer Protocol Secure        | 443              | Secure web traffic (encrypted)           | Considered secure; uses SSL/TLS                      |
| **FTP**      | File Transfer Protocol                    | 21               | File transfer                            | Plaintext transmission; use SFTP or FTPS instead     |
| **SMTP**     | Simple Mail Transfer Protocol             | 25, 587, 465     | Sending emails                           | Vulnerable to spoofing/spam if not secured           |
| **DNS**      | Domain Name System                        | 53               | Domain name lookup                       | Vulnerable to DNS spoofing and cache poisoning       |
| **DHCP**     | Dynamic Host Configuration Protocol       | 67 (server), 68 (client) | Assigning IP addresses     | Can be abused for rogue DHCP attacks                       |
| **SSH**      | Secure Shell                              | 22               | Secure remote login                      | Strong encryption, but brute-forceable if weak creds |
| **Telnet**   | Teletype Network                          | 23               | Remote login (insecure)                  | Transmits in plaintext; deprecated in favor of SSH   |
| **SNMP**     | Simple Network Management Protocol        | 161/162          | Network management and monitoring        | SNMPv1/v2c lack encryption; prefer SNMPv3            |
| **ICMP**     | Internet Control Message Protocol         | N/A              | Network diagnostics (e.g., ping)         | Can be used in ping floods, reconnaissance           |
