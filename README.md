# 🐚 Kali Linux VM Lab  
## Deploying Kali Linux in Azure for Future Pentesting Labs

---

## 🚀 Why I Created This Lab

Before diving deeper into ethical hacking simulations, I needed to get comfortable provisioning my own virtual machines. This lab walks through how I deployed a Kali Linux VM using Microsoft Azure and connected to it using SSH.

---

## ☁️ What I Did

### Step 1: Chose the Kali Image

I searched for an image that included the latest version of Kali Linux. I made sure to use a supported publisher and verified that I had permissions to deploy the VM.

### Step 2: Provisioned the VM in Azure

- Region: East US  
- Image: Kali Linux by "kali-linux"  
- Authentication type: Password (since it's what I’m most comfortable with right now)  
- Opened port 22 for SSH

📸 `1_kali_vm_created.png`

---

### Step 3: Verified It Was Running

After provisioning, I made sure the VM status was “Running” and grabbed the public IP address to connect.

📸 `2_kali_vm_running.png`

---

### Step 4: Connected Using SSH

I used my terminal and ran:

```bash
ssh feeadmin@20.75.89.168
```

📸 `3_kali_vm_ssh_connected.png`

I entered the password I set during provisioning. Once inside, I used simple commands like `ls` and `uname -a` to confirm I was in a Kali environment.

---

## 📸 Screenshots

| # | Description               | File Name                    |
|---|---------------------------|------------------------------|
| 1 | VM Created in Azure       | `1_kali_vm_created.png`      |
| 2 | VM Status Running         | `2_kali_vm_running.png`      |
| 3 | SSH Connection Successful | `3_kali_vm_ssh_connected.png`|

---

## 📝 Reflection

This lab was more than just setting up a virtual machine. It helped me build comfort with cloud resources, networking ports, and managing Linux systems remotely. It also set the foundation for future hands on hacking labs.

---

## ⚠️ Disclaimer

This lab is for ethical learning purposes only. Always follow your organization’s rules and never test exploits outside of approved environments.

---
