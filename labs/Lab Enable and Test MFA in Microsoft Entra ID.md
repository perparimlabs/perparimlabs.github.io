# 🔐 Lab: Enable and Test MFA in Microsoft Entra ID

In this hands-on lab, I demonstrate how to enable, enforce, and test multi-factor authentication (MFA) in Microsoft Entra ID using both legacy and modern configurations.

---

## 🧪 What You'll Learn

- Enable MFA using Per-user settings  
- Enforce Microsoft Authenticator using Authentication Methods policy  
- Block legacy authentication methods (like app passwords)  
- Simulate the end-user MFA registration experience  
- Understand how this aligns with SC-300 topics and real Zero Trust use cases

---

## 📝 Lab Steps Overview

1. **Go to Per-user MFA Settings**
   - Microsoft Entra ID → Users → ⋯ → Per-user MFA

2. **Enable & Enforce MFA for a test user**
   - Enable, then Enforce to make MFA mandatory

3. **Manage MFA Service Settings**
   - Disable legacy features like App Passwords  
   - Configure "Remember MFA on trusted devices"

4. **Enable Microsoft Authenticator**
   - Go to Authentication Methods → Enable Microsoft Authenticator

5. **Test the User Experience**
   - Sign in as the test user, simulate MFA registration  
   - Scan QR code or complete SMS verification  
   - Use InPrivate/Incognito mode for clean testing

---

## 📌 Key Takeaways

- ✅ MFA dramatically reduces identity-based attacks  
- 🔒 Blocking legacy protocols strengthens security  
- 📱 Microsoft Authenticator is the recommended method  
- 🔄 Authentication Methods blade now centralizes MFA + SSPR  
- 🧠 This lab directly maps to:
  - *SC-300: Implement and manage authentication methods*  
  - *SC-300: Plan and implement MFA in Microsoft Entra ID*

---

## 📄 File

- `Lab Enable and Test MFA in Microsoft Entra ID.pdf`

---

## 👤 Author

Perparim Abdullahu  
Azure Solutions Architect Expert  
SC-300 in Progress  
#PerparimLabs
