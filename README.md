# 🔧 DevicesFiltering

> PowerShell script to **list devices** and **set permissions** using SetACL — restricts device registry access to Console Logon group only.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 📋 **Device Listing** | Enumerates all PnP devices via WMI |
| 🔒 **Permission Lockdown** | Grants full control to Console Logon (S-1-2-1) only |
| 🛡️ **SetACL** | Uses SetACL.exe for registry ACL manipulation |
| ⚡ **Bulk Processing** | Iterates through all devices and updates ACLs |

---

## 📋 Requirements

| Requirement | Details |
|-------------|---------|
| **OS** | Windows 10/11 |
| **PowerShell** | 5.1+ |
| **SetACL.exe** | Must be in the script folder |
| **Privileges** | Administrator |

---

## 🚀 Usage

1. Download [SetACL](https://helgeklein.com/setacl/) and place `SetACL.exe` in the script directory.
2. Run:
   ```powershell
   .\DevicesFiltering.ps1
   ```

---

## ⚠️ Warning

Restricting device registry access can affect driver installation and hardware functionality. Use with caution. Create a restore point first.

---

<p align="center">
  <sub>🛡️ Gorstak Security Hardening</sub>
</p>
