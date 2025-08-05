# 🔐 Secure Azure Access Using Managed Identity (No Passwords Needed)

Learn how to use **Managed Identity** to securely connect an Azure VM to a SQL Database — with **no secrets or credentials**.

This lab aligns with Microsoft Entra security best practices and the SC-300 exam.

---

## 🧭 Lab Objectives

- Assign **System-assigned** + **User-assigned** Managed Identity to a VM  
- Deploy SQL Database with **Microsoft Entra-only Authentication**  
- Use RBAC to authorize secure access from the VM  
- Ensure no credentials are used at any stage  

---

## 🛠 Key Steps

### 1. **Assign Managed Identities to Azure VM**
- Enable:
  - System-assigned identity (1:1 VM access)
  - User-assigned identity (e.g., `vm-db-account`)
- These identities allow the VM to authenticate without secrets

---

### 2. **Deploy Azure SQL Database**
- Configure with **Microsoft Entra authentication only**
- No SQL logins used
- Basic compute tier for lab testing
- Prepares the DB to accept identity-based access

---

### 3. **Grant Access with RBAC**
- Assign **SQL Server Contributor** to the user-assigned identity
- Scope the role to the SQL Server or specific DB
- Access is now controlled by Entra ID + RBAC (no connection strings)

---

### 🧪 Lab Result

- VM can now connect to SQL Database securely  
- No secrets, usernames, or passwords used  
- RBAC and identity are the only access controls  
- Real-world Zero Trust pattern

---

## 📄 File Included:
- `Secure Azure Access Using Managed Identity.pdf`

---

## ✅ Summary

| Feature                        | Status ✅ |
|-------------------------------|----------|
| System-assigned identity       | ✅ Enabled |
| User-assigned identity         | ✅ Enabled |
| SQL Database with Entra-only   | ✅ Deployed |
| RBAC role assigned             | ✅ Done |
| Secrets or passwords used?     | ❌ Never |

---

## 👤 Author

Perparim Abdullahu  
Azure Solutions Architect Expert  
SC-300 Certified  
#PerparimLabs #AzureSecurity #ManagedIdentity #ZeroTrust #SC300
