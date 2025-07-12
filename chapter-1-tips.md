## ✅ Security+ SY0-701 – Chapter 1: Today’s Security Professional  
**🎯 High-Yield Exam TIPS – Technical Summary**

### 🔐 CIA Triad  
CIA = Confidentiality + Integrity + Availability  
- Confidentiality ➜ Encryption, access control  
- Integrity ➜ Hashing, digital signatures  
- Availability ➜ Load balancing, redundancy, backups

### 🧠 DAD Triad  
DAD = Disclosure + Alteration + Denial  
- Disclosure ➜ Info leaks (violation of confidentiality)  
- Alteration ➜ Unauthorized changes (violation of integrity)  
- Denial ➜ Service disruption (violation of availability)

### 🧾 Compliance & Legal Frameworks  
| Regulation | Full Name | Purpose |
|-----------|-----------|---------|
| HIPAA | Health Insurance Portability and Accountability Act | Protects healthcare data  
| PCI DSS | Payment Card Industry Data Security Standard | Secures card payment data  
| GLBA | Gramm-Leach-Bliley Act | Secures financial customer data  
| SOX | Sarbanes-Oxley Act | Regulates financial reporting for public companies  

### 🔄 Compensating Controls (PCI DSS Context)  
- Used when original control can't be implemented  
- Must provide **equivalent security strength**, not just intent  
- ❌ Wrong: “must meet the intent”  
- ✅ Correct: “must match the rigor and defense level of original requirement”

### 🔒 Data Protection Techniques  
| Technique | Reversible? | Use Case |
|----------|-------------|----------|
| Tokenization | ✅ Yes | Replace sensitive fields like credit card numbers  
| Masking | ❌ No | Show part of data only (e.g., ***-**-1234)  
| Hashing | ❌ No | Secure password storage  
| Shredding | ❌ No | Physically destroy documents/files  

### 🛡️ Access Control Types  
- **Administrative** ➜ Policies, procedures, awareness training  
- **Technical (Logical)** ➜ Firewalls, encryption, ACLs  
- **Physical** ➜ Guards, locks, CCTV

### ⚠️ Security Awareness  
- Always classified as **Administrative Control**  
- Training users is not a technical mechanism

### 🔍 Obfuscation vs Masking  
- **Obfuscation** ➜ Make data/code harder to understand  
- **Masking** ➜ Hide sensitive data from users

### 🌐 Key Network Ports  
| Port | Protocol | Usage |
|------|----------|-------|
| 443 | HTTPS | Secure web traffic  
| 22 | SSH | Remote CLI access (Linux/Unix)  
| 3389 | RDP | GUI remote desktop (Windows)

### 🧭 Control Plane vs Data Plane (Zero Trust)  
| Plane | Responsibility |
|-------|----------------|
| Control Plane | Identity, threat detection, policy decisions  
| Data Plane | Apply and enforce policies on systems/users  

### 🧾 Must-Know Acronyms from Chapter 1  
- CIA ➜ Confidentiality, Integrity, Availability  
- DAD ➜ Disclosure, Alteration, Denial  
- PII ➜ Personally Identifiable Information  
- PHI ➜ Protected Health Information  
- HIPAA ➜ Healthcare data privacy law  
- PCI DSS ➜ Payment security standard  
- GLBA ➜ Financial data privacy  
- SOX ➜ Corporate accountability law  
- IDS ➜ Intrusion Detection System  
- DLP ➜ Data Loss Prevention  
- DRM ➜ Digital Rights Management  
- ACLs ➜ Access Control Lists
