# 🔐 Secure Remote Access for On-Premises Apps with Microsoft Entra Application Proxy

This lab demonstrates how to **securely publish internal web apps** without exposing your network — using Microsoft Entra Application Proxy.

A cloud-native, Zero Trust alternative to traditional DMZ or VPN architectures.

---

## 🧭 Lab Objectives

- Deploy Microsoft Entra Application Proxy
- Secure on-prem apps without VPN or DMZ
- Enable Conditional Access, SSO, and MFA
- Bridge hybrid apps with cloud identity

---

## 🏚️ The Old Way (Legacy DMZ Access)

Traditionally required:

- DMZ zones with exposed proxy servers
- Fragile reverse proxy setups
- No Conditional Access or Entra ID integration
- High maintenance & risk if DMZ fails

---

## 🚀 The New Way: Entra Application Proxy

Modern hybrid access using:

- Lightweight App Proxy Connector installed on-prem
- No need to expose apps to the internet
- Entra ID handles authentication
- Conditional Access, MFA, and SSO ready
- Serves internal app traffic securely from Microsoft’s cloud

---

## 🛠️ How to Deploy

1. Go to **Microsoft Entra ID → Application Proxy**
2. Download & install the **App Proxy Connector** on a Windows Server (2012 R2+)
3. Open firewall for outbound traffic
4. Register the connector in the portal
5. Publish the internal app and assign users

> 🔒 Requires Entra ID Premium P1/P2 and hybrid identity

---

## 🎯 Why It Matters

| Legacy DMZ Setup              | Entra App Proxy                           |
|------------------------------|-------------------------------------------|
| Requires exposed reverse proxy | Uses outbound-only connector (no exposure) |
| No Conditional Access         | Supports CA + SSO + MFA                   |
| High maintenance              | Cloud-based and scalable                  |
| No identity integration       | Fully integrated with Microsoft Entra     |

---

## 📄 File Included
- `Secure Remote Access with Entra App Proxy.pdf`

---

## 👤 Author

Perparim Abdullahu  
Azure Solutions Architect Expert  
SC-300 Certified  
#PerparimLabs #MicrosoftEntra #ZeroTrust #HybridIdentity #AppProxy
