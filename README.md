# Active Directory Homelab (Hyper-V)

A very simple Active Directory lab built on Hyper-V to practice real-world IT skills like domain management, Group Policy, and user/group administration.
Both the Windows Server and Windows 11 OS were fully updated on a NAT vSwitch before I sysprepped them both to save images of the VHDs for easy deployment later.

---

## Lab Overview

- **Hypervisor:** Hyper-V on Windows 11
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
  - Security groups for role-based access (e.g., Istari, The-Fellowship, etc.)

- **Group Policy**
  - Login banner (“Welcome to Middle-Earth”)
  - Password policy
  - Lockout policy
  - Desktop wallpaper policy
  - Local admin group

- **File & Permission Management**
  - Shared folders with share permissions
  - Access based on security groups
  - Mapped network drives
 
## See Screenshots for Examples
https://github.com/Justin-Klippert/active-directory-homelab/tree/main/screenshots


