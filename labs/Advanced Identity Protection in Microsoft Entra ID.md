# 🔐 Advanced Identity Protection in Microsoft Entra ID

This real-world lab demonstrates how to implement **core identity protection features** using Microsoft Entra ID and on-prem Active Directory.

---

## 🔑 What’s Covered

- ✅ Self-Service Password Reset (SSPR)  
- 🔒 Cloud-based password protection  
- 🧱 On-prem password policies via Group Policy (GPO)  
- 🚫 Tenant restrictions to block external login

These align directly with **SC-300 exam** objectives and **Zero Trust principles**.

---

## 🧪 Lab Highlights

### ✅ SSPR (Self-Service Password Reset)

- Enabled for a scoped group
- Required 2 auth methods (email + phone)
- Configured via Authentication Methods blade
- Modern replacement for legacy SSPR config

### 🔒 Cloud Password Protection

- 5 failed sign-ins → lockout
- 5-minute lockout duration
- Custom banned password list (weak/common credentials)
- Enforce mode ON = real-time protection
- Applies to **cloud-only users**

### 🧱 On-Prem Password Policy (AD DS)

- Configured via **Default Domain Policy**
- Password complexity, length, expiration, history
- Applies to synced users from Active Directory
- Avoids reversible encryption
- Synced to Entra ID using Entra Connect

---

## 💬 Why This Matters

- Empowers users while reducing helpdesk load  
- Protects both cloud and on-prem identities  
- Meets compliance and Zero Trust goals  
- SC-300 relevant & ready for real organizations

---

## 📄 File

- `Advanced Identity Protection in Microsoft Entra ID.pdf`

---

## 👤 Author

Perparim Abdullahu  
Azure Solutions Architect Expert  
SC-300 in Progress  
#PerparimLabs
