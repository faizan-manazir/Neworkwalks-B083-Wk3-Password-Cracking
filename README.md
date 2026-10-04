# Networkwalks B083 — Week 3 Password Cracking

![Cybersecurity](https://img.shields.io/badge/Domain-Cybersecurity-red)
![Training](https://img.shields.io/badge/Program-Networkwalks-blue)
![Batch](https://img.shields.io/badge/Batch-B083-green)
![Project](https://img.shields.io/badge/Week%203-Password%20Cracking-orange)

## 📌 Project Overview

This repository contains the documentation, practical evidence, and final task report for the **Week 3 Password Cracking practical project** completed as part of the **Networkwalks B083 Cybersecurity & Ethical Hacking program**.

The project focuses on understanding and practically performing password-recovery workflows against protected PDF files within an **authorized educational laboratory environment**.

The practical work is divided into two modules:

- **W3-PM1 — Password Cracking with John the Ripper**
- **W3-PM2 — Password Cracking with Networkwalks Tools**

The repository contains the practical evidence, module documentation, and the final project report.

---

## 🎯 Project Objectives

The main objectives of this project were to:

- Understand the concept of password cracking and password recovery.
- Extract password hashes from protected PDF files.
- Configure and use **John the Ripper (JTR)**.
- Work with the **Johnny GUI** for JTR.
- Use Networkwalks password-cracking tools.
- Perform controlled password-recovery activities.
- Verify recovered passwords against the original protected PDFs.
- Capture and organize practical evidence.
- Document security risks associated with weak passwords.
- Apply cybersecurity tools within an authorized testing scope.

---

# 🧪 Practical Modules

## W3-PM1 — Password Cracking with John the Ripper

The first module focuses on using **John the Ripper (JTR)** and **Johnny GUI** for password recovery.

### Activities Performed

1. Verified the John the Ripper installation and build.
2. Configured Johnny to use the `john.exe` executable.
3. Extracted the password hash from the protected PDF.
4. Loaded the extracted hash into Johnny.
5. Started the password-recovery process.
6. Captured the successful password-recovery result.
7. Used the recovered password to open the protected PDF.
8. Captured evidence of the successful verification.

### Evidence

The W3-PM1 evidence is available in:

`W3-PM1-JTR/`

### Evidence Sequence

| # | Evidence | Description |
|---|---|---|
| 01 | JTR Build Information | John the Ripper build and version verification |
| 02 | John.exe Working | Johnny/JTR executable configuration |
| 03 | PDF1 Hash Extracted | Hash extracted from the protected PDF |
| 04 | Hash Loaded in Johnny | Extracted hash loaded into Johnny |
| 05 | PDF1 Password Cracked | Successful password-recovery result |
| 06 | PDF1 Opened | Verification of the recovered password |

---

# 🌐 W3-PM2 — Password Cracking with Networkwalks

The second module focuses on password recovery using the **Networkwalks Hash Calculator** and **Networkwalks Password Cracker**.

### Activities Performed

1. Submitted the protected PDF to the Networkwalks Hash Calculator.
2. Extracted the required password hash.
3. Submitted the hash to the Password Cracker.
4. Performed the password-recovery process.
5. Captured the successful recovery result and flag.
6. Used the recovered password to open the protected PDF.
7. Captured the final verification evidence.

### Evidence

The W3-PM2 evidence is available in:

`W3-PM2-Networkwalks/`

### Evidence Sequence

| # | Evidence | Description |
|---|---|---|
| 01 | PDF2 Hash Extracted | Hash extracted using the Networkwalks Hash Calculator |
| 02 | PDF2 Password Cracked | Successful password recovery and flag capture |
| 03 | PDF2 Opened | Verification of the recovered password |

---

# 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| **John the Ripper (JTR)** | Password-recovery and password-strength testing |
| **Johnny GUI** | Graphical interface for John the Ripper |
| **Networkwalks Hash Calculator** | Extraction of the required PDF password hash |
| **Networkwalks Password Cracker** | Password-recovery testing against the extracted hash |
| **Protected PDF Files** | Authorized challenge files used during the practical |

---

# 📊 Project Workflow

The overall practical workflow followed these stages:

```text
Protected PDF
     │
     ▼
Hash Extraction
     │
     ▼
Password Hash
     │
     ├───────────────┐
     ▼               ▼
   JTR/Johnny    Networkwalks
     │               │
     └───────┬───────┘
             ▼
     Password Recovery
             │
             ▼
      Password Verification
             │
             ▼
       Evidence Capture
             │
             ▼
       Final Documentation
```

---

# 📁 Repository Structure

```text
Neworkwalks-B083-Wk3-Password-Cracking/
│
├── README.md
│
├── Report/
│   └── Networkwalks_B083_Wk3_Password_Cracking_Report.pdf
│
├── W3-PM1-JTR/
│   ├── README.md
│   ├── 01-jtr-build-info.jpg
│   ├── 02-john-exe-working.jpg
│   ├── 03-pdf1-hash-extracted.jpg
│   ├── 04-hash-loaded-in-johnny.jpg
│   ├── 05-pdf1-password-cracked.jpg
│   └── 06-pdf1-opened.jpg
│
└── W3-PM2-Networkwalks/
    ├── README.md
    ├── 01-pdf2-hash-extracted.jpg
    ├── 02-pdf2_password_cracked.jpg
    └── 03-pdf2-opened.jpg
```

---

# 📄 Final Project Report

The complete project report documents the practical work, methodology, evidence, technical understanding, risk analysis, recommendations, learning outcomes, and conclusion.

### 📥 Report

**[View / Download the Full Week 3 Password Cracking Report](Report/Networkwalks_B083_Wk3_Password_Cracking_Report.pdf)**

---

# 🔎 Key Learning Outcomes

This practical project provided hands-on experience with:

- Password-hash extraction.
- John the Ripper.
- Johnny GUI.
- Networkwalks password-cracking tools.
- Password-recovery workflows.
- Protected PDF verification.
- Practical cybersecurity evidence collection.
- Technical security documentation.
- Password-risk assessment.
- Security recommendations.
- Responsible use of penetration-testing tools.

---

# ⚠️ Security & Risk Considerations

The practical demonstrated that password protection can be significantly affected by password strength.

Security risks highlighted by the exercise include:

- Weak or predictable passwords.
- Reuse of passwords.
- Common password patterns.
- Exposure of password hashes.
- Unauthorized password-recovery attempts.
- Improper handling of recovered credentials.

Strong, unique passwords and appropriate protection mechanisms should therefore be used for sensitive documents and systems.

---

# 🔐 Ethical Use & Disclaimer

All activities documented in this repository were performed within the **authorized Networkwalks educational environment** using the supplied project materials.

The techniques and tools demonstrated in this project are intended for:

- Cybersecurity education
- Authorized security testing
- Ethical hacking
- Security research

Do **not** use these techniques against systems, accounts, files, or networks without explicit authorization.

Unauthorized password recovery or access may violate organizational policies and applicable laws.

---

# 🎓 Training Information

**Program:** Cybersecurity & Ethical Hacking  
**Training Provider:** Networkwalks  
**Batch:** B083  
**Project:** Week 3 — Password Cracking  
**Modules:** W3-PM1 & W3-PM2  

---

# 👤 Author

**Faizan Manazir**

Cybersecurity & Ethical Hacking Learner

---

## ⭐ Project Status

**W3-PM1:** ✅ Completed  
**W3-PM2:** ✅ Completed  
**Final Report:** ✅ Uploaded  
**Practical Evidence:** ✅ Documented  

---

> **Note:** This repository is maintained for educational and professional portfolio purposes and demonstrates practical cybersecurity learning within an authorized environment.
