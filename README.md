Ansible Role: SSHD Configuration (`sshd_config_role`)
=========

## 📌 Description

This Ansible role secures the **SSHD service** by disabling direct root login (`PermitRootLogin no`).  
It also **validates the SSH configuration** before restarting the service to prevent accidental loss of access.

---

## 📦 Requirements

- **Target OS**: Debian 11 / 12 (can be adapted for other distributions)
- **Ansible ≥ 2.9** installed on the control machine
- SSH access with sudo privileges