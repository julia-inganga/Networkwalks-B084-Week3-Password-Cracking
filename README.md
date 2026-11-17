# NetworkWalks Internship – Week 3: Password Cracking

## Overview

This repository documents my Week 3 practical exercises as part of the NetworkWalks Cybersecurity Internship.

The exercises focused on password cracking using two approaches: NetworkWalks Hash Calculator and Password Cracker tools, and John the Ripper (JTR).

The practical work involved analysing an encrypted PDF, extracting its password hash, performing password-recovery operations and verifying the results.

## Objectives

- Understand the process of extracting password hashes from encrypted PDF files.
- Practise password cracking using NetworkWalks tools.
- Gain practical experience using John the Ripper.
- Understand the role of hash extraction in password recovery.
- Verify successful password recovery through the challenge results.

## Exercise 1: NetworkWalks Hash Calculator and Password Cracker

**Objective:** Crack the password of the supplied PDF file using the NetworkWalks Hash Calculator and Password Cracker tools on a Windows PC.

### Tools Used
- NetworkWalks Hash Calculator
- NetworkWalks Password Cracker
- Windows PC

### Activities Performed
1. Selected the supplied PDF file, `My Locked PDF1.pdf`.
2. Uploaded the PDF to the NetworkWalks Hash Calculator.
3. Used the calculator to extract the password hash.
4. Used the NetworkWalks Password Cracker to perform the password-cracking exercise.
5. Verified the result by opening the PDF with the recovered password.
6. Captured the challenge flag displayed after successful completion.

### Outcome

The password-recovery exercise was successful, and a NetworkWalks challenge flag was captured.

## Exercise 2: Password Cracking Using John the Ripper (JTR)

**Objective:** Crack the password of the supplied PDF file using JTR John and JTR Johnny tools on a Windows PC.

### Tools Used
- PDF Hash Extractor
- John the Ripper (`john.exe`)
- Johnny graphical user interface (GUI)
- Windows PC

### Activities Performed
1. Selected the supplied PDF file, `My Locked PDF1.pdf`.
2. Used a PDF Hash Extractor to extract the password hash.
3. Loaded the extracted hash file into Johnny.
4. Initiated the password-cracking process.
5. Reviewed the results displayed in the Johnny interface.
6. Verified the successful challenge result and captured the corresponding flag.

### Outcome

John the Ripper successfully processed the loaded PDF hash entries. Johnny displayed two cracked entries, with the status showing 100% completion and zero remaining entries.

The exercise resulted in the successful capture of a JTR challenge flag.

## Evidence and Screenshots

The repository includes screenshots documenting the practical exercises.

### Exercise 1: NetworkWalks Tools
- Hash extraction using the NetworkWalks Hash Calculator.
- Password-cracking results from the NetworkWalks Password Cracker.
- Captured challenge flag.

### Exercise 2: John the Ripper
- PDF hash extraction.
- Johnny interface showing the cracking results.
- Captured JTR challenge flag.

## Skills Developed

- PDF hash extraction and analysis.
- Password auditing and recovery.
- Practical use of John the Ripper.
- Familiarity with graphical interfaces for cybersecurity tools.
- Understanding encrypted PDF documents.
- Interpreting password-cracking results.
- Technical documentation and evidence collection.

## Conclusion

The Week 3 exercises provided practical exposure to password cracking and PDF hash analysis. By working with NetworkWalks tools and John the Ripper, I gained experience extracting password hashes, performing password-recovery operations and verifying challenge results.

These activities strengthened my understanding of password security and introduced me to practical tools used in cybersecurity assessments.

---

**Disclaimer:** These exercises were completed as part of an authorised cybersecurity learning activity using the files provided for the internship.
