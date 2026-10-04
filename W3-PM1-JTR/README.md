# W3-PM1 — Password Cracking with John the Ripper (JTR)

## Objective

Demonstrate the recovery and verification of a password-protected PDF using **John the Ripper (Jumbo)** and **Johnny GUI** in the authorized Week 3 laboratory environment.

## Tools Used

- John the Ripper Jumbo 1.9.0
- Johnny GUI
- PDF hash extraction utility
- Protected PDF supplied with the lab

## Practical Workflow

1. **JTR verification** — Confirm that the John the Ripper Jumbo installation is working and identify the installed build.
2. **Johnny configuration** — Configure Johnny GUI to use the `john.exe` executable from the JTR `run` directory.
3. **Hash extraction** — Extract the password hash from the protected PDF using the method specified by the project.
4. **Hash preparation** — Save the extracted hash in the required text-file format (`hash1.txt`).
5. **Hash loading** — Import the hash file into Johnny GUI.
6. **Password recovery** — Start the password-cracking process and wait for the recovered credential.
7. **Verification** — Use the recovered password to open the protected PDF and confirm successful recovery.

## Evidence

The `screenshots/` directory contains numbered evidence corresponding to the practical workflow:

| Evidence | Description |
|---|---|
| `01-jtr-build-info.jpg` | JTR build/version verification |
| `02-john-exe-working.jpg` | JTR executable verification |
| `03-pdf1-hash-extracted.jpg` | PDF1 hash extraction |
| `04-hash-loaded-in-johnny.jpg` | Hash loaded into Johnny |
| `05-pdf1-password-cracked.jpg` | Successful password recovery |
| `06-pdf1-opened.jpg` | PDF1 opened after password recovery |

## Result

The password-cracking workflow was completed successfully and the recovered credential was verified by opening the protected PDF.

> **Security note:** The recovered password, standalone hash file, and original locked PDF are intentionally not stored in this public repository.

## Ethical Use

This procedure was performed only against the supplied project material in an authorized educational environment. Password-cracking techniques must not be applied to systems or files without explicit permission.
