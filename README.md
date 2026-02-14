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

---

### Step 2: Open RDP Client `[0:10]`

- Locate the **Remote Desktop Protocol (RDP)** client on your system.
- Launch the application.

---

### Step 3: Retrieve Password `[0:22]`

- Locate the remote desktop file associated with the virtual machine.
- Decrypt or retrieve the administrator password from the file.
- Securely copy the password for later use.

---

### Step 4: Connect to the Virtual Machine `[0:59]`

- In the RDP client, enter the **IP address** of the virtual machine.
- Paste the decrypted password into the password field.
- Verify credentials before proceeding.

---

### Step 5: Launch Remote Desktop Session

- Click **Connect**.
- Accept any security or certificate prompts if prompted.
- Wait for the remote desktop session to load.

---

### Step 6: Open Server Manager

- Once logged in, locate and open **Server Manager** on the virtual machine.
- Confirm the dashboard loads successfully.

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



