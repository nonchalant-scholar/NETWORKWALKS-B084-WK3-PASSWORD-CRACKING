# W3-PM1 — Password Cracking with John the Ripper (JTR)

## Overview

This module documents a practical exercise in password recovery using **John the Ripper (JTR)** and its graphical interface, **Johnny**, on Windows 11.

The exercise involved extracting password-protection data from instructor-provided practice PDF files, preparing the extracted data for analysis, and using John the Ripper to recover the passwords required to access the protected documents.

## Tools and Environment

| Item | Details |
|---|---|
| Operating System | Windows 11 |
| Password Recovery Tool | John the Ripper (JTR) |
| Graphical Interface | Johnny |
| Target Files | Instructor-provided practice PDF files |
| Hash Extraction | PDF hash extraction utility |

## Practical Activities

The following activities were completed:

1. **Tool Setup:** Installed John the Ripper and configured the Johnny interface to use the `john.exe` executable from the JTR `run` directory.
2. **PDF Hash Extraction:** Extracted the password-protection data from the provided PDF files using a PDF hash extraction utility.
3. **Input Preparation:** Saved the extracted data in a text file and loaded it into Johnny.
4. **Password Recovery:** Initiated the password recovery process using John the Ripper.
5. **Verification:** Used the recovered passwords to open the corresponding protected PDF files and verify successful access.

## Learning Outcomes

- Understood the basic workflow of password recovery using John the Ripper.
- Learned how to configure and use Johnny as a graphical interface for JTR.
- Practised extracting password-protection data from PDF files.
- Understood how password recovery tools process extracted data to test possible passwords.
- Verified the recovered credentials by opening the protected practice documents.

## Evidence and Documentation

The `evidence/` directory contains selected screenshots documenting the practical workflow and successful completion.

The `notes/` directory is reserved for additional observations and practical notes.

**Security note:** Recovered passwords, complete extracted hashes, and unlocked PDF files are intentionally excluded from this public repository.

## Scope and Responsible Use

This exercise was performed on instructor-provided practice files for educational purposes.

Password recovery tools should only be used on files and systems that you own or have explicit permission to assess. This practical did not involve accessing third-party accounts or attempting to recover passwords from unauthorized systems.

## Disclaimer

This documentation is intended for educational purposes and independent cybersecurity learning. The techniques demonstrated should be used responsibly and only within an authorized scope.
