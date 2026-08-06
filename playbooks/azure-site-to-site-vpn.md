# Azure Site-to-Site VPN Playbook

Version: 1.0

Owner: Elevate Infrastructure Consulting

Status: Active

---

# Objective

Establish secure connectivity between on-premises infrastructure and Azure using a Site-to-Site VPN.

---

# Business Outcomes

- Secure hybrid connectivity
- Reduced latency
- Business continuity
- Secure cloud access

---

# Prerequisites

- Public IP available
- Compatible firewall/router
- Azure Virtual Network deployed
- VPN Gateway subnet created

---

# Phase 1 - Discovery

## Tasks

- Identify ISP
- Identify firewall model
- Identify public IP
- Document LAN networks
- Identify routing requirements

---

# Phase 2 - Assessment

## Tasks

- Verify VPN compatibility
- Verify firmware
- Verify supported encryption
- Validate IP addressing

---

# Phase 3 - Design

## Tasks

- Design VPN Gateway
- Design Local Network Gateway
- Design Address Spaces
- Define encryption settings
- Define routing strategy

---

# Phase 4 - Implementation

## Tasks

- Deploy VPN Gateway
- Deploy Local Network Gateway
- Create VPN Connection
- Configure on-premises firewall
- Configure routing
- Configure firewall rules

---

# Phase 5 - Validation

## Tasks

- Test ICMP
- Test RDP
- Test DNS
- Test SMB
- Test Active Directory replication
- Validate latency

---

# Phase 6 - Documentation

Update:

- VPN Diagram
- Firewall Rules
- Routing Tables
- VPN Configuration Backup

---

# Lessons Learned

Document tunnel issues, routing changes and recommendations.

---

# References

Azure VPN Gateway Documentation
Infrastructure Modernization Framework (IMF)
