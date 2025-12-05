# Active Directory Homelab (Hyper-V)

This project is my personal Windows Active Directory lab, built on Hyper-V, to practice real-world IT skills like domain management, Group Policy, user and group administration, and troubleshooting.

---

## Lab Overview

- **Hypervisor:** Hyper-V on Windows 10/11
- **Domain:** `middle-earth.local`
- **Servers & Clients:**
  - 1 × Windows Server (Domain Controller, DNS)
  - 1 × Windows 11 workstation (domain-joined)

- **Virtual Networking:**
  - Internal virtual switch for LAN

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
  - Local admin group

- **File & Permission Management**
  - Shared folders with share permissions
  - Access based on security groups
  - Mapped network drives

