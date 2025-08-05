# 🔐 Custom Azure RBAC Role for Key Vault Secrets Access

A hands-on lab to create and assign a custom Azure RBAC role that grants **read-only access to secrets** in Azure Key Vault — enforcing least privilege access for sensitive resources.

---

## 🧭 Lab Objectives

- Understand why built-in roles are not always secure  
- Create a custom RBAC role with minimal Key Vault permissions  
- Assign the role at the vault scope  
- Test and verify access  

---

## 🛠 Key Steps

### 1. **Why Create a Custom Role?**
- Built-in roles like Reader/Contributor grant broad access
- Custom roles allow exact permissions like:
  - `secrets/list`
  - `secrets/get`
- Enforces Zero Trust & least privilege

---

### 2. **Create the Custom Role**
- Go to **Subscriptions → Access Control (IAM)**  
- Click `+ Add → Add Custom Role`  
- Choose `Start from scratch`  
- Name: `Key Vault Secrets Reader - Custom`  
- Add optional description

---

### 3. **Define Permissions**
- Click `+ Add permissions`  
- Search for:
  - `Microsoft.KeyVault/vaults/secrets/list`
  - `Microsoft.KeyVault/vaults/secrets/get`
- Add only needed permissions  
- Click **Add** → **Next**

---

### 4. **Create a New Key Vault**
- Go to `portal.azure.com → Key Vaults → + Create`
- Use RBAC access model
- Example:
  - Resource Group: `KeyVaultDemo-RG`
  - Name: `MyCustomKV`
  - Region: East US
  - Access Model: Azure Role-Based Access Control (RBAC)

---

### 5. **Assign the Custom Role**
- Go to the new Key Vault → **Access control (IAM)**
- Click `+ Add → Add role assignment`
- Select the custom role created earlier
- Assign to a user, group, or service principal

---

### 6. **Confirm the Role Assignment**
- Still in IAM, check the **Role assignments** tab
- Click the user to see assigned permissions
- Optional: Use `Check access` to validate
- Test by attempting to list/get secrets

---

## 📄 File Included:
- `Custom Azure RBAC Role for Key Vault Secrets Access.pdf`

---

## ✅ Key Takeaways

- Created a custom RBAC role for Azure Key Vault
- Assigned only minimal `secrets/list` and `secrets/get` permissions
- Assigned the role using IAM at the resource scope
- Verified access using portal + manual secret test

---

## 👤 Author

Perparim Abdullahu  
Azure Solutions Architect Expert  
SC-300 Certified  
#PerparimLabs #KeyVault #AzureSecurity #RBAC #ZeroTrust
