# SOC Incident Response Lab

**Module:** COMP3010 – Security Operations and Incident Management

## Overview
Created a fake malicious PCAP simulating an obfuscated download of a Chrome executable and developed a full short-term and long-term incident response plan for persistent network scans.
Simulates alert analysis, traffic investigation, timeline creation, false positive reduction, and structured incident response.

## Tools Used
- Wireshark
- SSLKEYLOGFILE + ssldump (TLS decryption)
- Tor + Proxychains
- wget (with obfuscation)

## What I Did
- Captured obfuscated malicious traffic using custom User-Agent, HTTP headers, and URL shortener
- Analysed the PCAP with decrypted TLS sessions
- Produced a professional incident response report including:
  - Short-term plan (detection, containment, recovery using Snort, Wireshark, Splunk)
  - Long-term strategy (baseline monitoring, threat hunting, endpoint protection)
  - Individual threat evolution predictions

## Skills Demonstrated
- Alert triage and network traffic analysis
- Timeline reconstruction and root cause analysis
- Creation of incident response playbooks
- Technical documentation and reporting
- Threat obfuscation understanding

## Deliverables
- [Malicious PCAP](pcap/cd7286db3b061f72fc23128debe9c8bd.pcap)
- [Individual PCAP Report](reports/individual-pcap-report.pdf)
- [Group Incident Response Report](reports/group-incident-response-report.pdf)

## Screenshots
![](pcap/wireshark_timeline.jpg)
![](pcap/pcap_properties.jpg)
![](pcap/pcap_properties2.jpg)
