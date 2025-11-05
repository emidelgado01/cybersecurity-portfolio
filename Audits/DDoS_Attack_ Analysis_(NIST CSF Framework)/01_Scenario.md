# Scenario
---
This scenario is based on a fictional multimedia company:

The organization provides web design, graphic design, and social media marketing services to small businesses. Recently, the company experienced a Distributed Denial of Service (DDoS) attack that compromised its internal network for approximately two hours before being resolved.

During the incident, network services became unresponsive due to a massive flood of ICMP packets, which prevented normal internal traffic from accessing network resources. The incident response team acted quickly by blocking incoming ICMP packets, shutting down non-critical services, and restoring essential network operations.

Following the containment of the attack, the company’s cybersecurity team conducted an internal investigation. They discovered that the attack had exploited an unconfigured firewall, allowing a malicious actor to send a high volume of ICMP pings into the network. This vulnerability made it possible for the attacker to overwhelm the company’s infrastructure and disrupt business continuity.

To mitigate the issue and prevent future incidents, the network security team implemented several measures, including:

A new firewall rule to limit the rate of incoming ICMP packets

Source IP address verification to identify spoofed traffic

Network monitoring software to detect abnormal patterns

An IDS/IPS system to filter suspicious ICMP activity

As a cybersecurity analyst, your task is to use this incident to create a plan for improving the organization’s network security posture.
You will analyze the situation using the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF), applying its five core functions — Identify, Protect, Detect, Respond, and Recover — to assess risks, strengthen defenses, and develop recommendations to enhance the company’s resilience against similar attacks.
