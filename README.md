# Network Intrusion Detection & SIEM Lab

## Overview

This project was completed as part of the IUPUI Living Lab,
where I designed and implemented an open-source network security
monitoring solution.

The goal was to deploy an Intrusion Detection System (IDS) and
centralized logging platform capable of monitoring network
traffic, generating security alerts, analyzing network activity,
and supporting packet and file analysis.

The solution integrated Suricata with the ELK Stack
(Elasticsearch, Logstash, and Kibana), Filebeat, and
Zeek (formerly Bro IDS).

> **Original Project:** IUPUI Living Lab — Spring 2017  
> This repository is a portfolio reconstruction of the original
> project. Product names and versions reflect the technologies
> used at the time.

---

## Project Objectives

- Deploy an open-source network Intrusion Detection System
- Monitor network traffic and generate security alerts
- Centralize IDS logs using the ELK Stack
- Visualize security events through Kibana
- Capture and analyze network traffic
- Perform file extraction from captured traffic
- Document configuration and troubleshooting procedures

---

## Technologies Used

| Technology | Purpose |
|---|---|
| Suricata | Network intrusion detection |
| Elasticsearch | Security event storage and search |
| Logstash | Log processing and transformation |
| Kibana | Security event visualization |
| Filebeat | Suricata log forwarding |
| Zeek (formerly Bro) | Network analysis and file extraction |
| Ubuntu Linux | Security monitoring server |
| VMware vSphere | Virtual infrastructure |
| tcpdump | Packet capture |
