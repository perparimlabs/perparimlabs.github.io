# Zero Trust Security Architecture (Real-World Project)

A practical breakdown of how I implemented Zero Trust principles across Microsoft Entra, Azure, and Microsoft Defender.

---

### 🔐 Identity & Access

- Enforced Conditional Access policies for all users and admins  
- Enabled MFA via Microsoft Entra authentication methods policy  
- Applied PIM for Just-In-Time access to privileged roles

---

### 🧱 Network & Infrastructure

- Used Azure Application Gateway with Web Application Firewall (WAF)  
- Segmented resources using NSGs and private endpoints  
- Applied Azure Policy to enforce tagging and region restrictions

---

### 🎯 Threat Protection

- Connected Microsoft Defender for Cloud to monitor workloads  
- Enabled Microsoft Sentinel for real-time detection & response  
- Defined analytics rules to detect privilege escalation and lateral movement

---

### ✅ Business Impact

- Reduced attack surface across hybrid identities  
- Gained visibility into risky sign-ins and access abuse  
- Enabled faster response through alert-based automation

---

*Built using live Azure resources during lab simulations and real client-style scenarios.*
