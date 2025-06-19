# NIST CyberSecurity Framework (CSF)

The CSF is a voluntary framework that consists of standards, guidelines, and best practices to manage cybersecurity risks. Creating a quality cybersecurity incident report and applying the CSF demonstrates a proactive approach to security, improving communication and transparency with stakeholders, and improve security practices within an organization.

## Activity 

### Scenario

In this activity, I work as a cybersecurity analyst for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. My organization recently experienced a DDoS attack which compromised the internal network for two hours until it was resolved.

During the attack, network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

Our team then investigated the security event and found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 

- A new firewall rule to limit the rate of incoming ICMP packets

- Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets

- Network monitoring software to detect abnormal traffic patterns

- An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

### Task

As a cybersecurity analyst, I am tasked with using this security event to create a plan to improve my company’s network security, following the **National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF)** to help navigate through the different steps of analyzing this cybersecurity event and integrating my analysis into a general security strategy. 
