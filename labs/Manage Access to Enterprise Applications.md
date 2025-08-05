# 🔐 Manage Access to Enterprise Applications in Microsoft Entra

A practical SC-300 lab demonstrating how to securely assign access to SaaS apps, delegate admin roles with least privilege, and apply conditional access — all powered by Microsoft Entra.

---

## 🧭 Lab Objectives

- Add and assign SaaS applications in Microsoft Entra  
- Manage user access via **Enterprise Applications**  
- Delegate app management using **Application Administrator** or **Cloud App Administrator** roles  
- Enforce secure access with **SSO and Conditional Access**

---

## ⚠️ The Challenge: SaaS Access Chaos

Organizations rely heavily on SaaS tools like Salesforce, Box, Adobe, etc.  
Without centralized control, users may:

- Access apps they don’t need  
- Share credentials  
- Accept dangerous consent prompts  
- Leave gaps in governance

---

## 🎯 Key Concepts

### 🔹 Tenant-Level vs Application-Level Access
- **Tenant-Level**: Global controls over all apps  
- **App-Level**: Assign access per application via Entra ID

---

## ➕ Add a SaaS App & Assign Access

1. Go to **Microsoft Entra ID → Enterprise Applications**  
2. Click **+ New Application**  
3. Select a gallery app like **Box**, **Adobe**, or **Salesforce**  
4. Click **Create**  
5. Assign users or groups to the app  
6. They access it from [myapps.microsoft.com](https://myapps.microsoft.com)

✅ Users only see what they’ve been assigned

---

## 🛡️ Delegate App Management Securely

Avoid assigning **Global Administrator**.

Instead, use:

- **Application Administrator**  
  - Manage all apps, SSO, user consent

- **Cloud Application Administrator**  
  - Manage only assigned or created apps  
  - Perfect for scoped responsibility

Assign roles via:
`Microsoft Entra ID → Roles and Administrators → Add Assignment`

---

## ✅ Lab Outcome

| Goal                                      | Achieved |
|-------------------------------------------|----------|
| Add enterprise SaaS apps                  | ✅        |
| Assign users or groups securely           | ✅        |
| Avoid Global Admin for app control        | ✅        |
| Use least privilege roles (App Admin)     | ✅        |
| Centralized access via MyApps portal      | ✅        |

---

## 📄 File Included
- `Manage Access to Enterprise Applications.pdf`

---

## 👤 Author

Perparim Abdullahu  
Azure Solutions Architect Expert  
SC-300 Certified  
#PerparimLabs #MicrosoftEntra #SC300 #EnterpriseApps #ZeroTrust #IAM
