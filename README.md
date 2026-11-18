
# Networkwalks Cybersecurity Internship — Week 3

This repository documents the Week 3 practical activities completed as part of the **Networkwalks Cybersecurity Internship (Batch B084)**.

The exercises focused on understanding password recovery techniques through password-protected PDF files using John the Ripper and Networkwalks' online password-cracking tools.

## Completed Modules

| Module | Practical | Tools Used |
|---|---|---|
| W3-PM1 | Password Cracking with JTR | John the Ripper (JTR), Johnny |
| W3-PM2 | Password Cracking with Networkwalks Tools | Networkwalks Hash Calculator, Networkwalks Password Cracker |

## Practical Overview

### W3-PM1 — Password Cracking with John the Ripper

Performed a password recovery exercise using John the Ripper and its graphical interface, Johnny.

Key activities included:

- Installing and configuring John the Ripper on Windows.
- Configuring Johnny to use the John executable.
- Extracting the password hash from instructor-provided protected PDF files.
- Loading the extracted hash into Johnny.
- Executing a password recovery attack.
- Verifying the recovered password by opening the protected PDF.

### W3-PM2 — Password Cracking with Networkwalks Tools

Performed a password recovery exercise using Networkwalks' browser-based tools.

Key activities included:

- Extracting the PDF password hash using the Networkwalks Hash Calculator.
- Submitting the extracted hash to the Networkwalks Password Cracker.
- Running the password recovery process.
- Verifying the recovered password by opening the corresponding protected PDF.

## Repository Structure

```text
NETWORKWALKS-B084-WK3-PASSWORD-CRACKING/
│
├── README.md
│
├── W3-PM1-JTR/
│   ├── README.md
│   ├── evidence/
│   └── notes/
│
└── W3-PM2-Networkwalks-Tools/
    ├── README.md
    ├── evidence/
    └── notes/
```

## Learning Outcomes

Through these practical exercises, I gained hands-on experience with:

- Understanding password hashes extracted from protected PDF documents.
- Using John the Ripper and Johnny for password recovery.
- Understanding the workflow of dictionary-based password attacks.
- Working with browser-based hash extraction and password recovery tools.
- Verifying password recovery results.
- Understanding the importance of strong and unique passwords.

## Security and Responsible Use

- All exercises were performed using instructor-provided practice files in an educational environment.
- No personal or confidential documents were used.
- Recovered passwords, complete hash values, and unlocked PDF files are intentionally excluded from this public repository.
- Evidence screenshots are selected and reviewed before publication to prevent disclosure of sensitive information.
- Password recovery tools should only be used on files and systems owned by the practitioner or where explicit authorization has been granted.

## Evidence and Documentation

Each module has a dedicated directory containing its practical documentation and selected screenshots.

The documentation focuses on the methodology, tools, workflow, and learning outcomes of each exercise.

## Disclaimer

This repository is intended for educational purposes and independent cybersecurity learning. The practical activities demonstrate password recovery techniques using instructor-provided files and should not be interpreted as authorization to access or recover passwords from third-party documents.
