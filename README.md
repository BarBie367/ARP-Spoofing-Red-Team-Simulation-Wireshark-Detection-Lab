# ARP-Spoofing-Red-Team-Simulation-Wireshark-Detection-Lab
A controlled ARP spoofing simulation with Wireshark packet analysis and Windows ARP-cache validation.

# ARP Spoofing: Red Team Simulation & Wireshark Detection Lab

A controlled red team and blue team laboratory demonstrating ARP spoofing
indicators, packet-capture analysis, ARP-cache validation, and defensive
detection methods in an isolated virtual network.

## Red Team Objective

Simulate a ARP-spoofing scenario in an authorized laboratory to
understand how IP-to-MAC address mappings can be manipulated and how this
activity appears on the network.

## Blue Team Objective

Detect and investigate suspicious ARP behavior using Wireshark and Windows
ARP-cache inspection.

## Key Findings

- Wireshark identified duplicate IP-address activity.
- Multiple MAC addresses appeared associated with the same IP address.
- Repeated ARP replies were visible in the capture.
- Windows `arp -a` output was used to validate observed IP-to-MAC mappings.
