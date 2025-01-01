# README: Demonstration of Encrypting File System (EFS)

## Overview
This project demonstrates the execution of the Encrypting File System (EFS) on a Windows operating system. The steps cover encrypting a file, encrypting a folder, and testing access to encrypted files when moved to an unencrypted folder. Screenshots accompany each stage to illustrate the process.

## Key Features
1. **File and Folder Encryption**:
   - Demonstrates the process of encrypting individual files and entire folders using EFS.
   - Highlights the seamless integration of EFS into the Windows OS for secure data storage.

2. **File Access Testing**:
   - Includes a test scenario where an encrypted file is moved from an encrypted folder to an unencrypted folder to verify access permissions.
   - Explains whether the encryption is retained or lost during the transfer.

3. **Screenshots for Clarity**:
   - Detailed screenshots are provided at each step, making the process easy to follow.

## Prerequisites
- A Windows operating system with EFS enabled.
- Administrative access to the system.

## Steps to Reproduce
1. **Encrypt a File**:
   - Right-click on the file you want to encrypt.
   - Go to `Properties > Advanced > Encrypt contents to secure data`.
   - Apply the settings.

2. **Encrypt a Folder**:
   - Repeat the process for a folder to encrypt all its contents.
   - Select the option to apply encryption to all subfolders and files.

3. **Move Encrypted File**:
   - Move the encrypted file from the encrypted folder to an unencrypted folder.
   - Test if the file remains encrypted or becomes accessible without decryption.

4. **Verify Encryption**:
   - Attempt to open the file in the new location.
   - Document the results and behavior.

## Notes on Encryption Behavior
- Files encrypted with EFS retain their encryption status even when moved to an unencrypted folder, provided they are on the same NTFS volume.
- If the file is moved to a different volume that does not support EFS, it may lose encryption.

## Benefits of EFS
- Provides robust, file-level encryption natively within the Windows environment.
- Ensures data remains secure without the need for additional software.

## Limitations
- EFS is only supported on NTFS file systems.
- Moving encrypted files to unsupported volumes may result in data exposure.

## Conclusion
This project showcases the practical use of Encrypting File System (EFS) for securing sensitive data on Windows systems. By following these steps, users can protect their files and folders against unauthorized access effectively.

---
**For more details and accompanying screenshots, refer to the attached PDF.**
