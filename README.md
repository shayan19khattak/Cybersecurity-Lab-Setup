# Cybersecurity and Pentesting Lab Environment Setup

Building a controlled virtual lab for cybersecurity learning, penetration testing, and ethical hacking practice.

## Project Overview

This project documents the setup of a beginner-friendly cybersecurity lab using Oracle VirtualBox, Kali Linux, Windows 10 and Android vm on a Windows 11 host computer.

The purpose of this lab is to establish a controlled virtual environment for learning cybersecurity fundamentals, practicing authorized security testing, and conducting future hands-on security projects.

The setup includes a dedicated VirtualBox NAT Network, Kali Linux network configuration,Windows network configuration, Android network configuration, connectivity testing, and a clean virtual machine snapshot for recovery.

## Objectives

- Install and configure Oracle VirtualBox.
- Import and run the Kali Linux, Windows 10 and Android 9 virtual machine.
- Create a private NAT Network for the cybersecurity lab.
- Inspect and configure Kali Linux network, windows 10 and Android 9 settings.
- Verify network connectivity and DNS resolution.
- Take a clean VM snapshot for recovery.
- Document the lab setup process with screenshots.
- Prepare the environment for future cybersecurity projects and practical exercises.

## Purpose of the Lab

This lab provides a practical environment for developing foundational cybersecurity skills without conducting security experiments on unauthorized systems.

The environment will support future learning activities, including:

- Network security fundamentals.
- Linux system administration.
- Ethical hacking and authorized penetration testing.
- Digital forensics and evidence handling.
- Security monitoring and incident investigation.
- Hands-on cybersecurity portfolio development.


## Lab Architecture

The lab uses a Windows 11 host computer running Oracle VirtualBox, with Kali Linux, Windows 10 and Android 9 operating as a guest virtual machine.

A dedicated VirtualBox NAT Network provides a separate virtual networking environment for future lab machines. Network isolation settings should be reviewed before introducing additional virtual machines or conducting security exercises.


## Lab Setup Procedure

### Step 1: Install 7-Zip

Installed 7-Zip on the Windows 11 host computer to extract compressed files, including `.7z` archives, when preparing virtual machine installation files.

Download: [Official 7-Zip website](https://www.7-zip.org/)

### Step 2: Install Oracle VirtualBox

Installed Oracle VirtualBox on the Windows 11 host computer. VirtualBox allows Kali Linux to run inside a virtual machine without replacing the host operating system.

Download: [Official VirtualBox website](https://www.virtualbox.org/)

### Step 3: Create a Private NAT Network

Opened Oracle VirtualBox and created a dedicated NAT Network for the cybersecurity lab.

1. Opened VirtualBox's network configuration settings.
2. Createed a new NAT Network.
3. Assigned a suitable network name.
4. Reviewed the network address and DHCP settings.
5. Attached the Kali Linux virtual machine to the intended NAT Network.
6. Verified that the selected network configuration matches the lab requirements.

![image alt](https://github.com/shayan19khattak/Cybersecurity-Lab-Setup/blob/99227ca2c100bfd00405333c265c1a517da2d9c9/Screenshots/VitualBox_NATNetwork.png)

### Step 4: Import and Configure Kali Linux

The Kali Linux virtual machine was downloaded from the [official Kali Linux website](https://www.kali.org/get-kali/) and imported into Oracle VirtualBox.

Inspected the Kali Linux network settings through the graphical network settings interface.

1. Opened the Kali Linux network settings.
2. Reviewed the available network interface and connection status.
3. Confirmed that the virtual machine is connected to the intended VirtualBox network.
4. Reviewed the network configuration and confirm that the connection is active.

![image alt](https://github.com/shayan19khattak/Cybersecurity-Lab-Setup/blob/99227ca2c100bfd00405333c265c1a517da2d9c9/Screenshots/VirtualBox_Kali%20linux_27_10_2026_23_59_38.png)

### Step 5: Import and Configure Windows 10

The Windows virtual machine was downloaded from the [official Microsoft website](https://www.microsoft.com/en-us/software-download/windows10) and imported into Oracle VirtualBox.

Inspected the Wimdows network settings through the graphical network settings interface.

1. Opened the windows network settings.
2. Reviewed the available network interface and connection status.
3. Confirmed that the virtual machine is connected to the intended VirtualBox network.
4. Reviewed the network configuration and confirm that the connection is active.

![image alt](https://github.com/shayan19khattak/Cybersecurity-Lab-Setup/blob/99227ca2c100bfd00405333c265c1a517da2d9c9/Screenshots/VirtualBox_Win10_28_10_2026_00_37_34.png)

### Step 6: Import and Configure Android 9

The Android virtual machine was downloaded from the [Sourceforge website](https://sourceforge.net/projects/android-x86/postdownload) and imported into Oracle VirtualBox.

Inspected the Android network settings through the graphical network settings interface.

1. Opened the Android network settings.
2. Reviewed the available network interface and connection status.
3. Confirmed that the virtual machine is connected to the intended VirtualBox network.
4. Reviewed the network configuration and confirm that the connection is active.

![image alt](https://github.com/shayan19khattak/Cybersecurity-Lab-Setup/blob/99227ca2c100bfd00405333c265c1a517da2d9c9/Screenshots/VirtualBox_Android%20OS%209_28_10_2026_00_13_43.png )

## 🔎 Lab Verification
 Pinged all the virtual machines to test connectivity

 ![image alt](https://github.com/shayan19khattak/Cybersecurity-Lab-Setup/blob/99227ca2c100bfd00405333c265c1a517da2d9c9/Screenshots/ping%20from%20kali.png)

 ![image alt](https://github.com/shayan19khattak/Cybersecurity-Lab-Setup/blob/99227ca2c100bfd00405333c265c1a517da2d9c9/Screenshots/ping%20from%20windows.png)

 ![image alt](https://github.com/shayan19khattak/Cybersecurity-Lab-Setup/blob/99227ca2c100bfd00405333c265c1a517da2d9c9/Screenshots/ping%20from%20android.png)

 
## What I Learned

Through this project, I developed practical familiarity with:

- Preparing a virtualization environment on Windows 11.
- Importing and running Kali Linux, Windows 10 and Android 9 in Oracle VirtualBox.
- Creating a dedicated NAT Network for cybersecurity lab use.
- Inspecting Linux, Windows and Android network settings and testing basic connectivity.
- Using a web browser to check network access.
- Creating and documenting a clean virtual machine snapshot.
- Organizing project screenshots and technical documentation for GitHub.
- Preparing a foundation for future cybersecurity practice and portfolio projects.

## Security & Ethical Use

This lab is intended for educational purposes and authorized security testing only.

## Tools & Resources

- [Oracle VirtualBox](https://www.virtualbox.org/) — Virtualization platform.
- [Kali Linux](https://www.kali.org/) — Linux distribution for cybersecurity and penetration testing.
- [Windows 10](https://www.microsoft.com/en-us/software-download/windows10) — windows ISO file.
- [Android 9](https://sourceforge.net/projects/android-x86/postdownload) — Android vm for testing.
- [7-Zip](https://www.7-zip.org/) — File archiving and extraction utility.
- [GitHub](https://github.com/) — Source control and portfolio hosting.
  

