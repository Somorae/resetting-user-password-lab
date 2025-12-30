# 🔐 Active Directory: Resetting a User Password (AWS Lab)

## 🎬 Watch Me Build This Lab!
https://www.loom.com/share/81762771568c4540ac3966b99d9564a6

## 🎯 Objective
Demonstrate administrative control of user accounts by resetting a domain user password using **Active Directory Users and Computers (ADUC)** on a Windows Server hosted in AWS.

## 🛠️ Tools & Technologies
- AWS EC2 (Windows Server)
- Active Directory Domain Services (AD DS)
- Active Directory Users and Computers (ADUC)
- Windows Server

## 📝 Procedure
1. Logged into the EC2 Windows Server instance.
![Reset AD step 1 ](https://github.com/user-attachments/assets/ae5c4360-85ea-42e3-b6e8-8f9a8f155ca8)

3. Opened **Active Directory Users and Computers** from the Windows search bar.
<img width="954" height="579" alt="Reset Ad step 2" src="https://github.com/user-attachments/assets/5c05fd6a-9c7b-49b3-abc9-ec8ce86cb157" />

5. Expanded the **skool.local** domain.
6. Navigated to the **Users** container.
7. Right-clicked the user account **Jane Doe** and selected **Reset Password**.
8. Entered and confirmed a new password.
9. Applied the change successfully.

## ✅ Outcome
The domain user **Jane Doe** had their password successfully reset, confirming proper configuration of Active Directory and administrative privileges within the AWS-hosted Windows Server environment.

## 📌 Key Skills Demonstrated
- Active Directory user management
- Windows Server administration
- AWS EC2 Windows environments
- Identity and access management (IAM fundamentals)

