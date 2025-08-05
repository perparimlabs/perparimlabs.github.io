# 🔐 Deploy Microsoft Global Secure Access Client

A hands-on lab to configure Microsoft’s Global Secure Access (GSA) Client — part of Entra’s Secure Service Edge strategy — for Zero Trust network access without VPN.

---

## 🧭 Lab Objectives

- Enable Global Secure Access in Entra Portal  
- Turn on Adaptive Access for Conditional Access  
- Activate and assign Microsoft 365 Traffic Profile  
- Deploy GSA Client on a Windows device  
- Troubleshoot connection status and client health  

---

## 🛠 Key Steps

### 1. **Activate Global Secure Access**
- Portal: [entra.microsoft.com](https://entra.microsoft.com)
- Go to: `Global Secure Access → Settings → Session Management`
- Click **Activate**

---

### 2. **Turn On Adaptive Access**
- In `Session Management`
- Enable: `Enable CA Signaling for Entra ID`

🔒 Allows Conditional Access to recognize GSA traffic  
✅ Required for Zero Trust enforcement

---

### 3. **Activate Microsoft 365 Traffic Profile**
- Navigate to `Global Secure Access → Connect → Traffic Forwarding`
- Enable `Microsoft Traffic Profile`
- Assign to your user account

---

### 4. **Customize Traffic Forwarding**
- View services like:
  - Exchange Online
  - SharePoint Online
  - Microsoft Entra ID
- Choose Forward or Bypass  
- Save preferences

---

### 5. **Assign Traffic Profile to Users**
- Under the profile section, click `Assign`
- Choose `All users` or specific groups

---

### 6. **Download & Install GSA Client**
- Go to `Global Secure Access → Connect → Client Download`
- Install on Windows 10+ (VM or physical)
- After install, client appears in system tray

---

### 7. **Validate Client Connection**
- Right-click tray icon → `Advanced Diagnostics`
- Check:
  - Authentication Status = ✅ Authenticated  
  - Device Join Status = Entra Joined  
  - Forwarding Profile = Correct one applied  

---

### 🧪 Lab Note: Device Not Joined
In this demo, VM is **not Microsoft Entra Joined**, so the client shows “Disconnected.”  
In real environments, joining is required for:
- Conditional Access  
- Traffic Forwarding

---

## 📄 File Included:
- `Deploy Microsoft Global Secure Access Client.pdf`

---

## 🏁 Summary
- Modern, VPN-less secure access  
- Works with Conditional Access  
- Requires Entra ID device join  
- Ideal for remote/hybrid users

---

## 👤 Author

Perparim Abdullahu  
Azure Solutions Architect Expert  
SC-300 Certified  
#PerparimLabs #ZeroTrust #MicrosoftEntra #GlobalSecureAccess
