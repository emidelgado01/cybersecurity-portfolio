# Summary
The multimedia company experienced a Distributed Denial of Service (DDoS) attack that disrupted its internal network for approximately two hours before being resolved.
The attack consisted of a flood of ICMP packets sent by a malicious actor, which overwhelmed network resources and caused internal services to become temporarily unavailable.
The company’s cybersecurity team conducted an investigation and discovered that the attacker was able to send ICMP traffic through an unconfigured firewall, which lacked proper filtering rules.

To mitigate the incident and prevent future occurrences, the network security team implemented several corrective actions:
- A new firewall rule to limit the rate of incoming ICMP packets.
- Source IP address verification on the firewall to detect and block spoofed IP addresses.
- Deployment of network monitoring software to identify abnormal traffic patterns.
- Installation of an Intrusion Detection and Prevention System (IDS/IPS) to filter malicious ICMP traffic based on suspicious characteristics.

---

# Identify
The cybersecurity team investigated the security event and audited the company’s firewall configuration, network devices, and ICMP traffic logs to identify anomalies in network security.
The investigation revealed that the firewall was not properly configured, which allowed a malicious actor to send a flood of ICMP ping packets, overwhelming the company’s internal network through a DDoS attack.
As a result, the organization’s internal services were disrupted for approximately two hours until the issue was resolved.

---

# Protect
After identifying the source and cause of the DDoS attack, the cybersecurity team implemented new firewall rules to restrict the rate of incoming ICMP packets and prevent excessive traffic from overwhelming the network.
The team also enabled source IP address verification to detect and block spoofed IP addresses used in the attack.
Additionally, they deployed network monitoring tools to track unusual spikes in ICMP traffic and installed an Intrusion Detection and Prevention System (IDS/IPS) to automatically identify and filter suspicious packets.

---

# Detect
To detect new unauthorized access attacks in the future, the cybersecurity team will implement new and enhanced firewall rules and configurations, Source IP address verification, Network monitoring (most likely SIEM) and an IDS/IPS system.

---

# Respond
The incident management team immediately began investigating the security event and blocked all incoming ICMP packets to stop the DDoS traffic.
They temporarily took non-critical network services offline to reduce load on the infrastructure and focused on restoring critical services to normal operation.
Once stability was confirmed, the team continued analyzing network logs to ensure the malicious traffic had been fully mitigated.

---

# Recover
After the DDoS incident was contained, the cybersecurity team verified network stability and restored all services to normal operation.
The team conducted a post-incident review to evaluate the effectiveness of the mitigation actions and to identify areas for improvement.
Firewall configurations and monitoring tools were updated based on the lessons learned, and a disaster recovery plan was reviewed to ensure faster response and recovery times in future incidents.
The organization also documented all recovery steps and shared a summary with management to maintain transparency and accountability.

---

**Framework used:** NIST Cybersecurity Framework (Identify, Protect, Detect, Respond, Recover)  
**Analyst:** Emiliano Delgado  
**Date:** November 5th, 2025
