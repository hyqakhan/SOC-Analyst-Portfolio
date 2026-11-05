<img width="1600" height="595" alt="2" src="https://github.com/user-attachments/assets/eaad6b66-2ae1-46bb-8173-7043d0102280" />
<img width="1600" height="558" alt="1" src="https://github.com/user-attachments/assets/cd01b31a-7895-4599-ae77-9c8eb41a00b3" />
# Lab 01 — File Integrity Investigation Using SHA256

## 1. Objective
To understand file integrity and detect file modifications using SHA256 hashing.

## 2. Environment
- Operating System: Windows
- Tool: Windows PowerShell
- Algorithm: SHA256

## 3. Practical Procedure
1. Created a folder named SOC-Lab-01.
2. Created a sample text file named sample.txt.
3. Generated the original SHA256 hash.
4. Modified the file content from Version 1 to Version 2.
5. Generated the SHA256 hash again.
6. Compared both hash values.

## 4. Investigation Results

**Original SHA256 Hash:**
9060D8467A8F1BB78D8BC9F699D456A214516BCBA6455A6DE4A145BBF580482F


**Modified SHA256 Hash:**
A8FC54BEE8960D1BA62E9CFEEB3453A20BDEC8E653D809A0F8993823226E22AA

**Comparison:** Different

## 5. Conclusion
The SHA256 hash changed after the sample file was modified. This demonstrates how cryptographic hashing can help verify file integrity and detect file modifications.

## 6. Evidence
- Screenshot 1: Original file hash
- Screenshot 2: Modified file hash

## 7. Learning Outcomes
- Learned SHA256 hashing.
- Practiced PowerShell Get-FileHash.
- Understood file integrity verification.
- Learned how hash comparison helps in cybersecurity investigations.
