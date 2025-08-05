# 🔐 Lab Protecting Identities with Microsoft Entra ID Protection

This hands-on lab demonstrates how to secure accounts by configuring **User Risk** and **Sign-in Risk** policies using Microsoft Entra ID Protection (P2 license required).

---

## 🎯 Lab Objectives

- Configure **Sign-in Risk Policy**
- Configure **User Risk Policy**
- Monitor **Risky Users** and **Risky Sign-ins**
- Simulate risk using Tor Browser
- Learn real-world **alerting and remediation**

---

## 🛠️ Key Configurations

### ✅ Sign-in Risk Policy
- Target: All Users or test group
- Risk Level: Medium and above (or Low to test)
- Access Control: Require MFA

### ✅ User Risk Policy
- Target: All Users
- Risk Level: Low and above
- Access Control: Require Password Change

> 🧪 For lab testing, you can use “Block Access” to simulate denial.

---

## 🔍 Monitoring

- Risky Users = compromised accounts flagged by Microsoft
- Risky Sign-ins = sign-ins flagged by:
  - Anonymous IP
  - Malicious browser
  - Atypical travel

✅ Filter by time range to observe trends and risk types.

---

## 🚨 Simulate Risk (Optional)

Use the **Tor Browser** to trigger risky sign-ins and test policy response (e.g., blocked access or password reset).

---

## 📄 File

- `Lab Protecting Identities with Microsoft Entra ID Protection.pdf`

---

## 👤 Author

Perparim Abdullahu  
Azure Solutions Architect Expert  
SC-300 in Progress  
#PerparimLabs
