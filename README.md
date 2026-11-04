
# Cisco CCNA (200-301) Networking Portfolio & Study Lab

A structured repository of technical notes, configuration blueprints, Packet Tracer lab topologies, and student reference guides mapped to the Cisco Certified Network Associate (CCNA 200-301) curriculum.

---

## 📚 Curriculum & Repository Navigation

| Domain | Focus Topics | Artifacts & Reference |
| :--- | :--- | :--- |
| **[00-student-resources](./00-student-resources/)** | Lab setup, CLI navigation, initial device hardening | Setup Guides, CLI Cheat Sheets |
| **[01-network-fundamentals](./01-network-fundamentals/)** | TCP/IP vs OSI, IPv4/IPv6 subnetting, cabling, frame anatomy | Addressing Sheets, Architecture Notes |
| **[02-switching-lan](./02-switching-lan/)** | VLANs, 802.1Q trunks, RSTP/STP root bridges, EtherChannel | L2 Topologies, Switch Configs |
| **[03-routing-technologies](./03-routing-technologies/)** | Single/Multi-Area OSPFv2, static/floating routes, inter-VLAN | Routing Tables, CLI Snippets |
| **[04-ip-services](./04-ip-services/)** | NAT/PAT, DHCP Relay, NTP, DNS, Syslog, SNMP | Service Templates, Blueprints |
| **[05-security-fundamentals](./05-security-fundamentals/)** | Standard/Extended ACLs, Port Security, DAI, DHCP Snooping | Security Baseline Scripts |
| **[06-network-automation](./06-network-automation/)** | REST APIs, JSON/YAML payloads, Ansible basics, Cisco DNA Center | Python Scripts, API Blueprints |
| **[packet-tracer-labs](./packet-tracer-labs/)** | End-to-end troubleshooting scenarios & lab challenges | `.pkt` / `.pka` Labs & Solutions |

---

## 🛠️ Lab Environment & Tools
- **Simulation Platforms:** Cisco Packet Tracer (v8.x+)
- **Terminal Emulators:** Git Bash, PuTTY, SecureCRT
- **Editor:** Sublime Text / VS Code

---

## 📝 Troubleshooting & Methodology
Every lab walkthrough emphasizes a systematic, foundational troubleshooting framework:
1. **Physical & Data Link Verification:** Check interface states (`show ip interface brief`, speed/duplex, cable status).
2. **L2 Domain Isolation:** Verify VLAN tagging, trunk encapsulation, STP states, and port assignments.
3. **L3 Path & Routing:** Confirm subnetting, default gateways, routing tables (`show ip route`), and neighbor adjacencies.
4. **Services & Filtering:** Audit ACL placements, NAT overload pools, and DHCP bindings.