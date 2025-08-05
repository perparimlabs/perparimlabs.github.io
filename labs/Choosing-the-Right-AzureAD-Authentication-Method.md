README.md
# 🔐 Choosing the Right Azure AD Authentication Method for Hybrid Identity

This short lab explains the three main authentication methods used when syncing on-prem Active Directory with Microsoft Entra ID (Azure AD):

- ✅ Password Hash Sync (PHS)
- 🔁 Pass-Through Authentication (PTA)
- 🛡 Federated Authentication (AD FS)

Each method is broken down with pros and cons, plus a visual chart comparing:

- Whether Microsoft knows the password
- If on-prem is required
- Who each method is best for

---

## 🧪 My Lab Choice

For this lab, I used **Password Hash Sync (PHS)** because:

- It’s easy to set up with Azure AD Connect  
- Doesn’t rely on on-prem being online  
- Supports cloud-based remote sign-in

Unless your org has strict compliance needs or 3rd-party MFA, PHS is a great choice.

---

## 🛠 Tools Used

- Microsoft Entra ID (Azure AD)  
- Azure AD Connect  
- Windows Server (on-prem AD)

---

## 📁 File

- `Choosing-the-Right-AzureAD-Authentication-Method.pdf`

---

## 👨‍💻 Author

**Perparim Abdullahu**  
*Microsoft Certified: Azure Solutions Architect Expert*  
*SC-300 in Progress*
