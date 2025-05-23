# Install-VMWare-Install-Kali-Linux-and-Install-Sleuth-Kit
## AIM:
To install VMware, set up Kali Linux as a virtual machine, and install Sleuth Kit for digital forensic analysis.

## DESIGN STEPS:
### Step 1: Install VirtualBox

### Installation Steps:

1.Download the Windows hosts .exe file from the official VirtualBox website.

2.Run the installer and follow the on-screen instructions.

3.Once installed, launch VirtualBox to verify the installation.

### Step 2: Install Kali Linux on VirtualBox

🔗 Download Kali Linux VM: (https://www.kali.org/get-kali/#kali-platforms)

### Installation Steps:

1.Download the Kali Linux ISO file.Open VirtualBox, click New, enter "Kali Linux", select Type: Linux and Version: Debian (64-bit).

2.Set RAM to at least 4GB ,Set disk storage to at least 30GB, choose Dynamically Allocated or Fixed Size, and create the VM.

3.Go to Settings > Storage, click Empty under Controller: IDE.

4.Select Graphical Install, follow the prompts to set language, location, username, and password.

5.Choose Partitioning Method (Guided - Use Entire Disk) and wait for installation to complete.

### Step 3: Install Sleuth Kit (CLI-based Forensic Tools)

🔗 Download Sleuth Kit: https://www.sleuthkit.org/

### Installation Steps:

1.Download the Windows ZIP package from the official website.

2.Extract the ZIP folder and move it to a suitable directory (e.g., C:\sleuthkit).

3.Add the bin folder to Windows PATH:

Open Control Panel → System → Advanced System Settings.

Click Environment Variables → Edit Path.

Add the Sleuth Kit bin folder path and save changes.
Step 4.Verify installation by running:

```
fls -version
```

## OUTPUT:

```
Name: RAJESH A
Reg No: 212222100042
```
## VIRTUAL BOX:

![433006963-16145c2a-2d23-4ce3-98b3-782704b51d21](https://github.com/user-attachments/assets/6cde0e73-1b7d-49b7-b486-908c146f502e)


## KALI LINUX:

![433007099-cd1adf4e-3cf9-457c-9bc6-bd892704ffa7](https://github.com/user-attachments/assets/44a3c439-957b-4c0e-ba7f-af7399e2956e)


## SLEUTH-KIT:

![432366920-ad3b60f8-8ad6-4c6c-9cae-4de229dfaf84](https://github.com/user-attachments/assets/b5e085a8-ed2f-4b18-882f-9b1b0d408421)

## RESULT:
The setup and installation of VMware, Kali Linux, and Sleuth Kit was completed successfully.
