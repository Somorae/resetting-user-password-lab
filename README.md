# 🔐 Active Directory: Resetting a User Password (AWS Lab)

## 🎬 Watch Me Build This Lab!
https://www.loom.com/share/81762771568c4540ac3966b99d9564a6

## 🎯 Objective
Demonstrate administrative control of user accounts by resetting a domain user password using **Active Directory (AD)** on a Windows Server hosted in AWS.

## 🛠️ Tools & Technologies
- AWS EC2 (Windows Server)
- Active Directory Domain Services (AD DS)
- Active Directory Users and Computers (ADUC)
- Windows Server

## 📝 Steps Taken
1. Logged into the EC2 Windows Server instance.
2. Opened **Active Directory Users and Computers** from the Windows search bar.
<img width="954" height="579" alt="Reset Ad step 2" src="https://github.com/user-attachments/assets/5c05fd6a-9c7b-49b3-abc9-ec8ce86cb157" />

3. Expanded the **skool.local** domain.
4. Navigated to the **Users** container.

![Reset AD step 3 ](https://github.com/user-attachments/assets/24a64a77-a9b7-4c16-b10f-a24c54a5b20b)

5. Right-clicked the user account **Jane Doe** and selected **Reset Password**.
![Reset AD step 4](https://github.com/user-attachments/assets/521bd4b8-89e7-4b15-bb88-fd0fcdbb0d2b)

6. Entered and confirmed a new password.
<img width="654" height="440" alt="Screenshot 2025-12-30 130307" src="https://github.com/user-attachments/assets/cf63ac81-c73d-4b58-aa5f-318a4128c13f" />

7. Applied the change successfully.
![Reset AD step 5](https://github.com/user-attachments/assets/b08fae00-e32d-4a81-b027-f607d401ab5a)

## ✅ Outcome
The domain user **Jane Doe** had their password successfully reset, confirming proper configuration of Active Directory and administrative privileges within the AWS-hosted Windows Server environment.

## 📌 Key Skills Demonstrated
- Active Directory user management
- Windows Server administration
- AWS EC2 Windows environments
- Identity and access management (IAM fundamentals)

