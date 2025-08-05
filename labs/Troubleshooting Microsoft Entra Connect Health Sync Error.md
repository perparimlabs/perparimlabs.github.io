# 🛠 Troubleshooting Microsoft Entra Connect Health Sync Error

In this real-world lab, I demonstrate how I diagnosed and resolved a Microsoft Entra Connect Health sync issue and restored the status to ✅ **Healthy**.

---

## ❌ What Was the Problem?

- Sync status showed **Error** in the Azure portal
- Microsoft Entra Connect Health Agent wasn’t running properly
- Installation kept failing with no clear "CriticalError" in the logs
- Root cause: .NET Framework version was below requirements

---

## ✅ How I Fixed It

- Updated .NET Framework from 4.6.1 to the required version
- Restarted system
- Reinstalled Health Agent successfully
- Sync status changed to **Healthy**

---

## 📌 Key Takeaways

- Always check .NET prerequisites for the health agent
- Use **Azure portal** logs for troubleshooting clues
- Sometimes small versions can break entire sync
- Connect Health is a real-time diagnostic tool

---

## 📄 File

- `Troubleshooting Microsoft Entra Connect Health Sync Error.pdf`

---

## 👤 Author

Perparim Abdullahu  
Azure Solutions Architect Expert  
SC-300 in Progress  
