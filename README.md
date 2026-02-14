<https://loom.com/share/7ea2b17ab0aa4600a43f74fd7577f584>
# Standard Operating Procedure (SOP)  
## Remote Desktop Connection Setup for Virtual Machine

---

## Objective

This SOP defines the step-by-step process for securely connecting to a virtual machine (VM) using **Remote Desktop Protocol (RDP)** and initiating **Active Directory (AD)** setup. The goal is to ensure a smooth, repeatable, and secure connection workflow.

---

## Scope

This procedure applies to administrators and technical personnel responsible for virtual machine access, server configuration, and Active Directory setup.

---

## Prerequisites

- Virtual machine is created and powered on  
- RDP client installed on the local machine  
- Access to the VM’s remote desktop file and credentials  
- Appropriate permissions to configure Active Directory  

---

## Procedure

### Step 1: Access the Virtual Machine `[0:01]`

- Confirm the virtual machine is running.
- Allow time for full initialization before attempting to connect.
- Prepare to establish a Remote Desktop connection.
<img width="1700" height="503" alt="image" src="https://github.com/user-attachments/assets/03d06f8c-8014-4327-ae79-1d21bb172870" />

---

### Step 2: Open RDP Client `[0:10]`

- Locate the **Remote Desktop Protocol (RDP)** client on your system.
- Launch the application.
<img width="1428" height="487" alt="image" src="https://github.com/user-attachments/assets/516f27f6-5255-4ffa-8885-c8a25bfd8ae6" />

---

### Step 3: Retrieve Password `[0:22]`

- Locate the remote desktop file associated with the virtual machine.
- Decrypt or retrieve the administrator password from the file.
- Securely copy the password for later use.
<img width="836" height="405" alt="image" src="https://github.com/user-attachments/assets/ca7ecae3-bb2a-497f-9818-d78f421ddfae" />

---

### Step 4: Connect to the Virtual Machine `[0:59]`

- In the RDP client, enter the **IP address** of the virtual machine.
- Paste the decrypted password into the password field.
- Verify credentials before proceeding.
<img width="950" height="449" alt="image" src="https://github.com/user-attachments/assets/151c261f-dc90-4aba-a9c8-b43554bc3e03" />
<img width="764" height="258" alt="image" src="https://github.com/user-attachments/assets/b5b9b425-9311-4d98-8ff1-8e0cc19289f2" />

---

### Step 5: Launch Remote Desktop Session

- Click **Connect**.
- Accept any security or certificate prompts if prompted.
- Wait for the remote desktop session to load.
<img width="937" height="480" alt="image" src="https://github.com/user-attachments/assets/93cd4ec2-8c5c-4bac-a1c2-150d4a6a61c2" />
<img width="857" height="417" alt="image" src="https://github.com/user-attachments/assets/3d5c8030-8912-43b0-9f7b-28f73a453f54" />

---

### Step 6: Open Server Manager

- Once logged in, locate and open **Server Manager** on the virtual machine.
- Confirm the dashboard loads successfully.
<img width="519" height="358" alt="image" src="https://github.com/user-attachments/assets/4b795aff-1466-4b66-9e9d-a3ddc2c6cd40" />
<img width="969" height="526" alt="image" src="https://github.com/user-attachments/assets/f5c23a8e-863f-446d-845d-e7414deaf55c" />

---

### Step 7: Set Up Active Directory `[2:24]`

- From Server Manager, begin the **Active Directory Domain Services (AD DS)** setup process.
- Follow on-screen instructions for role installation and configuration.

---

### Step 8: Monitor Progress

- Allow Server Manager to collect inventory and complete background processes.
- Monitor status indicators for successful loading.

---

### Step 9: Follow Up

- If the setup process is delayed or incomplete:
  - Document the current progress.
  - Plan to resume configuration during the next session.

---

## Cautionary Notes

- Do **not** attempt to connect before the VM has fully initialized.
- Treat decrypted passwords as sensitive information.
- Never share credentials with unauthorized individuals.

---

## Tips for Efficiency

- Store credentials securely using a password manager.
- Customize RDP client settings (display, clipboard, resolution) for faster workflows.
- Reuse this SOP for consistent VM access across environments.



