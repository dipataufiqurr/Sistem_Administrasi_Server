# Sistem_Administrasi_Server UTS
------
## Difa Taufiqurrahman
## 1202199005
## IT - 02 - 01
------
**Question**
------
![Soal](https://user-images.githubusercontent.com/92538741/143682939-bd452a3c-2811-46f3-a507-de5c3ee4ea0f.PNG)

------
**Answer**
------
### A. Instalasi windows server 2022

Download ISO Installer windows server 2022

   https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022
   
   Select download the ISO then follow it step by step.
   
   ![1](https://user-images.githubusercontent.com/92538741/143684222-65e654f6-2c6a-4d11-841c-068f3641294c.PNG)


- Then open Oracle VM
   ![2](https://user-images.githubusercontent.com/92538741/143684286-463a6683-fbf0-49db-83a4-5855c3e20855.PNG)

- Next Klik New, Choose name and operating system (Windows Server 2022)
  
![3 fix](https://user-images.githubusercontent.com/92538741/143684309-7416575a-187a-4ca6-95d1-3ac3c7dfddb1.PNG)


- Select the amount of memory (RAM)
![4](https://user-images.githubusercontent.com/92538741/143684594-c81680b8-b131-44b0-b6f5-909c35c25c14.PNG)
- Create a virtual hard disk
![5](https://user-images.githubusercontent.com/92538741/143684603-a06d63d3-4808-4e91-9a8c-5f5fe52d107f.PNG)
- Choose virtual hard disk file type
![6](https://user-images.githubusercontent.com/92538741/143684605-0d494620-1245-43d8-9119-def62219db0f.PNG)
- Choose storage on physical hard disk
![7](https://user-images.githubusercontent.com/92538741/143684608-9dd4062c-0350-4fd1-ba14-41126e23ec58.PNG)
- Select file location and size of the virtual hardisk
![8](https://user-images.githubusercontent.com/92538741/143684611-6423f4c1-1313-47b9-be4b-64ecfa5c5a65.PNG)

- Setting storage iso

![10](https://user-images.githubusercontent.com/92538741/143684902-b24c161c-b07b-49c0-9a99-c891412d50c9.PNG)
![11](https://user-images.githubusercontent.com/92538741/143684904-555ea187-dac2-41d0-a759-b609bb236589.PNG)
![12](https://user-images.githubusercontent.com/92538741/143684907-a910b262-838a-4170-aee1-750ecbdbcc69.PNG)
![13](https://user-images.githubusercontent.com/92538741/143684909-3c021251-1271-4bf8-bec5-dfce0805a1a3.PNG)
![14](https://user-images.githubusercontent.com/92538741/143684913-49d2faf9-e543-4e00-8e6a-836bfe7ce73d.PNG)

- Go to the machine configuration and in the Network section set Bridge adapter

![15](https://user-images.githubusercontent.com/92538741/143684939-9847aac5-ccb4-499c-8be2-3702e9d0c77f.PNG)



- Start virtual machine windows server 2022 and instalasi wizzard windows server 2022

![16](https://user-images.githubusercontent.com/92538741/143685016-8f8ea3d3-5e78-4537-aeae-ecd9a2a8190e.PNG)

- Install windows server click on install now 

![17](https://user-images.githubusercontent.com/92538741/143685104-371e707c-e0a5-4938-81c6-338d20ba8acf.PNG)

- Select windows server 2022 desktop experience

![18](https://user-images.githubusercontent.com/92538741/143685130-35cee710-a7a4-450d-ba7c-c27b46614ca9.PNG)


- Accept the license and then proceed with the installation of Windows Server 2022

![19 fix](https://user-images.githubusercontent.com/92538741/143685142-91331ef7-b813-4491-b002-de4e2ff411de.PNG)


- Select windows server 2022 install microsoft server advanced (Custom)
![20](https://user-images.githubusercontent.com/92538741/143685160-667c7def-ab17-4fb8-90d7-2b60a9a57f60.PNG)

- Location installation of windows server 2022
![21](https://user-images.githubusercontent.com/92538741/143685167-ca77770e-ca41-4989-9d9c-8a9be18cb91e.PNG)

- installation progress
![22](https://user-images.githubusercontent.com/92538741/143685179-5fbdc4c6-e8b6-49ac-b218-51e7d69511a1.PNG)

- The system will reboot to complete the process
![24](https://user-images.githubusercontent.com/92538741/143685213-ed36858b-5bb9-435f-9e13-69ac05283c7d.PNG)

- Custom password administrator and login to administrator with Input – Keyboard – Insert Ctrl + Alt + Del
![25](https://user-images.githubusercontent.com/92538741/143685302-8c867ec8-b4a7-4dc8-b510-c9cbb5e92751.PNG)

- Windows Server 2022 has been successfully installed
![26](https://user-images.githubusercontent.com/92538741/143685322-e1ade16f-589b-4952-8756-7c2633e9db09.PNG)


### B. Instalasi Active Directory Domain Services
-  Before doing the installation, we change the computer name first by going to windows powershell.
   Then type rename-computer -Newname Server2022
      - Open the start menu and select Windows PowerShell
      
    ![27](https://user-images.githubusercontent.com/92538741/143685352-b84262a5-83c9-4ca4-9313-7a546fa4e6df.PNG)
    ![27 5](https://user-images.githubusercontent.com/92538741/143685522-1631864a-42ef-478a-b3d7-2868a5299f25.jpeg)

      - Then Restart, and open erver Manager Select Menu manage, Then Add Rules and Features 
   ![28](https://user-images.githubusercontent.com/92538741/143685533-b995bd6b-dc02-4c61-9442-e6421704e652.PNG)  
   
      - Select Next
      
   ![29](https://user-images.githubusercontent.com/92538741/143685584-88e67ea0-d6b7-4f7e-9c08-f02f1e5c72eb.PNG)

      - Select option Role-based or feature-based installation.
      
   ![30](https://user-images.githubusercontent.com/92538741/143685607-dc3f9213-b1d2-4ea1-be58-e80935757a31.PNG)

      - Select a server from the server pool to select a local storage directory. 
      
   ![31](https://user-images.githubusercontent.com/92538741/143685649-348b8f06-d7a5-4a51-8901-e8b35f41068e.PNG)

      - put a check mark in the Active Directory Domain Services box. When you check the box, on the right appears 
        a brief description of ADDS and how it works. Then click Add Features.
   ![32](https://user-images.githubusercontent.com/92538741/143685654-2cded90f-1c33-4347-a0bc-3a1b598401d0.PNG)

   
   
### C. Instalasi DNS server
   - We need to install and configure the Active Directory role and DNS server to work together.
     Checklist DNS Servers then add features 
   
   ![33](https://user-images.githubusercontent.com/92538741/143685745-e8b032a3-570c-4c4a-b0e4-00f1579d9691.PNG)
   ![34](https://user-images.githubusercontent.com/92538741/143685754-1450f62a-01c8-4557-93cc-d6da340dd0b5.PNG)


### D. Instalasi Net Framework 3.5
   - Checklist NET Framework 3.5 features
   
   ![35](https://user-images.githubusercontent.com/92538741/143685767-7b922643-66d9-4fde-a91b-8f034f0b0304.PNG)

   - Choose Next
   
   ![36](https://user-images.githubusercontent.com/92538741/143685802-a3d0ab15-5f45-4d11-9317-fb880a8b5c5b.PNG)

   - Choose Next
   
   ![37](https://user-images.githubusercontent.com/92538741/143685823-9e660d13-d438-420e-84bb-3295a8c3f166.PNG)

   - Then Install
   
   ![38](https://user-images.githubusercontent.com/92538741/143685837-400c4397-4e09-42f6-b646-91e369f7786d.PNG)

   - And Success 
   
   ![39](https://user-images.githubusercontent.com/92538741/143685902-003f9e78-6214-4cea-a6c2-36df67a0afa1.PNG)
   ![40](https://user-images.githubusercontent.com/92538741/143685894-50d9aeaa-c826-457e-95ac-903ded0a4a6d.PNG)


### E. Promote Server to a Domain Controller
- Setting to static ip Go to command prompt and type "sconfig"
   
   ![41](https://user-images.githubusercontent.com/92538741/143686013-31392f4b-220d-4e21-9016-569d8ba760d8.PNG)
- Choose Network Settings
   ![42](https://user-images.githubusercontent.com/92538741/143686038-958869f5-faab-416c-9fbd-a8a2527449ee.PNG)

- Setting IP to static

   ![43](https://user-images.githubusercontent.com/92538741/143686052-761be4b9-b01a-447e-b2f0-80be1fb64d70.PNG)
   ![44](https://user-images.githubusercontent.com/92538741/143686059-fb2ae2c4-4dd5-40ab-9ff3-8c8e92b4f952.PNG)
   
-  Setting the IP Address Server-ADDS and pointing the DNS to the static IP address used.
   ![45](https://user-images.githubusercontent.com/92538741/143686080-0dcf35de-13ba-46a4-a443-d62c94bd8965.PNG)
 
-  Click Promote this server to a domain controller for ADD configuration and Select Add a new forest and enter the domain name to be used in the Root Domain Name. difa.com
   ![46](https://user-images.githubusercontent.com/92538741/143686100-4a69ab83-480a-487a-ad16-b86519edfcf3.PNG)

-  fill in the Directory Services Restore Mode password what you want.
   ![47](https://user-images.githubusercontent.com/92538741/143686212-f578468a-ab69-4e22-9cda-47174deaf52a.PNG)


-  click Next

   ![48](https://user-images.githubusercontent.com/92538741/143686250-7334723d-5fda-47ad-8b46-896fac538e1a.PNG)


-  Verify NetBios Domain Name
   ![49](https://user-images.githubusercontent.com/92538741/143686261-a800e860-fc28-4bd9-8ef4-cb219d22915b.PNG)


-  Skip the Paths section, click Next.

   ![50](https://user-images.githubusercontent.com/92538741/143686277-9d18e739-666c-48e0-92f8-9d4f2cfb87c0.PNG)


-  Rivew configuration specified in Review Options, and then. Click Next.
   ![51](https://user-images.githubusercontent.com/92538741/143686283-d93bb915-a138-47a1-8ab4-73b4f8659caf.PNG)


-  If there is All prerequisite checks passed successfully. Click Install to apply the specified configuration.
   ![52](https://user-images.githubusercontent.com/92538741/143686291-6f6f2992-e9bd-4b76-bd57-cc5302b1f778.PNG)


-  After the installation is complete, the laptop will restart automatically. 
  ![53](https://user-images.githubusercontent.com/92538741/143686319-56b8542e-ff8d-4f41-b918-5b524ec1642f.PNG)
  ![54](https://user-images.githubusercontent.com/92538741/143686325-155f05fe-d231-471e-a7e3-0307a1ed6d66.PNG)



- check the configuration results
  ![55](https://user-images.githubusercontent.com/92538741/143686339-66c36b7d-f844-4677-98b7-be05d0048057.PNG)

------
## Finish


