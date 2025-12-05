# Active Directory Homelab (Hyper-V)

This project is my personal Windows Active Directory lab, built on Hyper-V, to practice real-world IT skills like domain management, Group Policy, user and group administration, and troubleshooting.

---

## Lab Overview

- **Hypervisor:** Hyper-V on Windows 10/11
- **Domain:** `middle-earth.local`
- **Servers & Clients:**
  - 1 × Windows Server (Domain Controller, DNS)
  - 1 × Windows 11 workstation (domain-joined)
  - (Optional) 1 × pfSense or router VM for simulated WAN

- **Virtual Networking:**
  - Internal virtual switch for LAN
  - NAT/External switch for internet access from the lab

---

## What I Configured

- **Active Directory Domain Services (AD DS)**
  - New forest and domain: `middle-earth.local`
  - Custom OU structure for users, groups, and computers

- **Users and Groups**
  - Test users (e.g., Gandalf, Frodo, Aragorn, etc.)
  - Security groups for role-based access (e.g., IT-Admins, Fellowship)

- **Group Policy**
  - Login banner (“Welcome to Middle-Earth”)
  - Password policy
  - Screen lock timeout
  - (Optional) Mapped drives for file shares

- **File & Permission Management**
  - Shared folders with NTFS and share permissions
  - Access based on security groups

---

## Repository Contents

- `diagrams/` – Network and domain diagrams
- `screenshots/` – Screenshots of AD, OU structure, GPOs, shares, etc.
- `scripts/` – PowerShell scripts used in the lab (e.g., bulk user creation)
- `notes/` – Troubleshooting notes and lessons learned

---

## Skills Demonstrated

- Installing and configuring Windows Server roles (AD DS, DNS)
- Creating and managing OUs, users, computers, and groups
- Designing and applying Group Policy Objects (GPOs)
- Managing NTFS and share permissions
- Working with virtual networking in Hyper-V
- Troubleshooting domain join, DNS, and authentication issues
