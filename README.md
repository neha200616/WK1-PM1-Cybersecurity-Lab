 WK1-PM1: Cybersecurity Testing Lab Setup
Project Overview

Successfully configured a cybersecurity testing lab environment using Oracle VirtualBox and Kali Linux.

The purpose of this project is to create a virtual environment for learning cybersecurity and practicing ethical hacking.

Tools and Technologies Used
Oracle VirtualBox
Kali Linux
7-Zip
Windows Host Operating System
NAT Network
Network Configuration
Configuration	Value
Network Name	CyberLab
Network Type	NAT Network
Network Subnet	10.0.0.0/24
Kali Linux IP	10.0.0.2/24
Default Gateway	10.0.0.1
DNS Servers	1.1.1.1, 8.8.8.8
Tasks Completed
Installed 7-Zip.
Installed Oracle VirtualBox.
Created a custom NAT Network.
Configured network subnet 10.0.0.0/24.
Downloaded and imported Kali Linux.
Configured Kali Linux static IP address.
Enabled bidirectional shared clipboard.
Enabled bidirectional drag and drop.
Configured shared folders.
Verified internet connectivity.
Created Kali Linux virtual machine snapshot.
Network Testing

The following commands were used to verify connectivity:

bash
ip addr
ip route
ping -c 4 10.0.0.1
ping -c 4 8.8.8.8
ping -c 4 google.com

Shared Folder Configuration
Host folder: C:\downloads
Kali Linux shared folder: /downloads
Screenshots

Screenshots of the completed lab configuration will be uploaded in the screenshots folder.

Learning Outcomes
Learned VirtualBox installation and configuration.
Understood NAT Network configuration.
Practiced static IP configuration in Kali Linux.
Learned Linux networking commands.
Configured shared folders and clipboard integration.
Tested internet connectivity.
Conclusion

Successfully completed WK1-PM1 by setting up a cybersecurity testing lab using Oracle VirtualBox and Kali Linux.

This environment will be used for authorized cybersecurity learning and ethical hacking practice.
