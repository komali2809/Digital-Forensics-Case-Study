# Digital-Forensics-Case-Stud
Digital forensics project using FTK Imager and Autopsy

## Objective
To demonstrate the use of cryptographic hash functions in digital forensics by verifying the integrity of a PDF document and detecting modification.

## Description
This project compares hash values of an original PDF file and a slightly modified PDF file using different forensic tools and hashing algorithms.

## Files Included
- code1hash.pdf – Original PDF file
- code1_modified.pdf – Modified version of the PDF
- hash_results.txt – Hash values generated using MD5, SHA-1, and SHA-256

## Tools Used
- Manual / Online Hashing Tool – MD5
- FTK Imager – SHA-1
- Autopsy – SHA-256

## Methodology
1. An original PDF document was selected.
2. Hash values were calculated using different forensic tools.
3. The PDF was slightly modified.
4. Hash values were calculated again.
5. Hash values were compared to verify integrity.

## Result
The hash values of the original and modified PDF files were completely different across all hashing algorithms.

## Conclusion
This experiment proves that cryptographic hash functions are highly sensitive to changes and are effective for detecting tampering in digital documents. SHA-256 is preferred in modern digital forensics due to its stronger security.
