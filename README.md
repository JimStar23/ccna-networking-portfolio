# Cisco CCNA (200-301 v2.0) Networking Portfolio & Study Lab

A structured repository of technical blueprints, Packet Tracer lab topologies, diagnostic workflows, and AI-assisted network operations guides mapped directly to the **Cisco Certified Network Associate (CCNA 200-301 v2.0)** blueprint.

---

## 📚 Curriculum & Repository Navigation

| Domain | Exam Weight | Core Focus Topics | Key Artifacts |
| :--- | :---: | :--- | :--- |
| **[00-student-resources](./00-student-resources/)** | — | Lab setup, CLI navigation modes, Subnetting Matrix guides, VLAN references | Onboarding PDFs, Cheat Sheets |
| **[01-network-infrastructure-connectivity](./01-network-infrastructure-connectivity/)** | 25% | Cable/interface diagnostics (copper/fiber), VMs vs containers, IPv4/IPv6 subnetting, wireless RF/principles, client reachability, DHCPv4 relay | Addressing Sheets, Cabling Specs |
| **[02-switching-network-access](./02-switching-network-access/)** | 25% | 802.1Q trunks, LACP EtherChannel, SVIs, edge-host port attributes (PoE, VoIP, APs, IoT), CDP/LLDP discovery, Rapid PVST+ | Switch Configs, STP Topologies |
| **[03-ip-routing](./03-ip-routing/)** | 20% | Routing table analysis, IPv4/IPv6 static & floating routes, single-area OSPFv2/OSPFv3, FHRP redundancy (HSRP/VRRP) | OSPF Labs, Route Tables |
| **[04-network-services-security](./04-network-services-security/)** | 20% | AAA (TACACS+/RADIUS), SFTP/SCP, NAT/PAT, DNS diagnostics, IPsec VPNs, ACLs, Layer 2 security (DAI, DHCP Snooping, Port Security) | Security Baselines, NAT Configs |
| **[05-ai-network-operations-management](./05-ai-network-operations-management/)** | 10% | Agentic AI in NetOps, GenAI prompt engineering, cloud-managed networking (Meraki), SNMP, Ansible automation, Syslog analysis | AI Prompt Templates, Meraki Labs, Ansible Playbooks |
| **[packet-tracer-labs](./packet-tracer-labs/)** | — | End-to-end troubleshooting scenarios, multi-domain break-fix challenges | `.pkt` / `.pka` Topologies & Guides |

---

## 🛠️ Lab Environment & Operational Tools
* **Simulation Platforms:** Cisco Packet Tracer (v8.x+), Cisco Meraki Dashboard
* **Terminal & Automation:** Git Bash, Sublime Text, Ansible, Python
* **Diagnostic & AI Frameworks:** Agentic Network Assistants, LLM Prompt Workflows, Syslog/SNMP Collectors

---

## 📝 Systematic Troubleshooting Methodology
Every lab walkthrough adheres to a structured, foundational diagnosis process:
1. **Physical & Cable Layer:** Verify interface statuses (`show ip interface brief`), transceiver signal levels, copper/fiber integrity, and speed/duplex negotiation.
2. **Layer 2 Access & Discovery:** Validate VLAN assignments, 802.1Q encapsulation, STP root paths, and neighbor discovery via CDP/LLDP.
3. **Layer 3 Forwarding & Redundancy:** Inspect routing tables (`show ip route`), default route paths, OSPF neighbor states, and FHRP active/standby roles.
4. **Security & Services:** Verify DHCP pools/relays, NAT translation tables, DNS resolution, and L2 security filters (DHCP snooping, DAI, ACLs).