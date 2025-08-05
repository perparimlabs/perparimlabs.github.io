# 🚫 Why We Replace Security Defaults with Conditional Access in Real Environments

This lab explains the critical differences between **Security Defaults** and **Conditional Access**, and why real organizations should transition to more granular identity governance.

---

## 🔍 What Are Security Defaults?

- Basic, free identity protection
- Enforces MFA for all users and admins
- Blocks legacy authentication
- Not customizable — all or nothing

---

## ⚠️ Limitations of Security Defaults

- No ability to scope to specific users, apps, or conditions
- Conflicts with Conditional Access
- Cannot perform report-only testing
- Lacks flexibility required in enterprise environments

> “You can’t build real Zero Trust with Security Defaults alone.”

---

## ✅ Why Conditional Access Wins

- Customizable rules based on **user, device, location, risk, app**
- Enforce MFA only when needed
- Block legacy authentication with scoped logic
- Enable **report-only mode** for safe rollout
- Supports Zero Trust architecture

---

## 🔄 Lab Breakdown

- Replaced Security Defaults with Conditional Access policies  
- Scoped policies to target users and admins  
- Enforced MFA using Microsoft Authenticator  
- Blocked legacy protocols like IMAP, POP, SMTP  
- Deployed in **report-only** to test safely before enforcing

---

## 💡 Summary Table

| Feature                      | Security Defaults | Conditional Access |
|-----------------------------|-------------------|--------------------|
| MFA Enforcement             | All or nothing    | Fully customizable |
| Legacy Auth Blocking        | Basic             | Scoped             |
| Risk-Based Controls         | ❌                | ✅ (Entra P2)      |
| Target Users/Groups         | ❌                | ✅                 |
| Report-only Testing         | ❌                | ✅                 |
| Best Fit For                | Small Orgs        | Enterprises        |

---

## 📄 File

- `Why We Replace Security Defaults with Conditional Access in Real Environments.pdf`

---

## 👤 Author

Perparim Abdullahu  
Azure Solutions Architect Expert  
SC-300 in Progress  
#PerparimLabs
