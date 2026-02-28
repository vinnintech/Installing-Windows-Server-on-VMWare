<p align="center">
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/220f67a3-f115-4efc-b15a-b066eb303b78" />
  
# Installing Windows Server on VMWare
## Description
This guide shows you how to install Windows Server 2022 on VMware. It includes checking virtualization, downloading necessary software, setting up a virtual machine, and completing the server installation. Perfect for creating a virtual environment for testing and development.

## Utiliities & Enviroments Used
- Server Manager
- Active Directory Users and Computers
- Windows Sever 2025
- Windows 11
## Project Walkthrough:
## Download Windows Server 2025 ISO
- Head to [Microsoft's Download Page.](https://www.microsoft.com/en-us/windows-server)
   <img width="1906" height="864" alt="image" src="https://github.com/user-attachments/assets/b7927787-30c3-414b-bf64-64b791295df8" />
- Click "Try it free"
- Download the ISO from their site.
  <img width="975" height="528" alt="image" src="https://github.com/user-attachments/assets/d9f94064-6067-4a4c-bf85-07f1596bb21f" />
## Create a New Virtual Machine
1. Open VMware and choose Create a New Virtual Machine. To find how to install VMware, look back at the [Installing Windows on VMware Guide.](https://github.com/vinnintech/Installing-Windows-on-VMWare)
2. Proceed with recommended installation.
3. Choose your Windows Server .iso file that was just downloaded.
   <img width="584" height="587" alt="image" src="https://github.com/user-attachments/assets/05430213-af67-4eee-abe7-58f08133b1c0" />

4. Enter your username and passowrd for your account.
   <img width="669" height="672" alt="image" src="https://github.com/user-attachments/assets/0cd8ab85-1369-4df7-b14b-f2b7de34f887" />

5. Name your machine.

   <img width="669" height="672" alt="image" src="https://github.com/user-attachments/assets/828d24c0-4c9e-4197-bed2-7af0be168925" />

7. Use recommended disk space (60 GB).
   
    <img width="669" height="672" alt="image" src="https://github.com/user-attachments/assets/cf8b70cb-0b94-4361-80d0-db5fc38bf9c2" />

9. Select Customize Hardware and change the memory to 16 GB, confirm and Finish.
   <img width="669" height="672" alt="image" src="https://github.com/user-attachments/assets/8b9788db-8d96-4e07-8353-e89e07d10855" />
10. Allow it some time to install.
   <img width="975" height="530" alt="image" src="https://github.com/user-attachments/assets/6c1770c0-7908-4f42-be5d-592ec806dc3f" />
  <img width="975" height="530" alt="image" src="https://github.com/user-attachments/assets/a273b54c-3048-4a94-9cc7-29c5dec013f4" />

<h3> ****Congratulations, You have installed Windows Server!**** </h3>

<h2> Next, we will use [Windows Server to Install Active Directory]().</h2>
