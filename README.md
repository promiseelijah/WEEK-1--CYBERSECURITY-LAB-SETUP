WEEK 1 CYBERSECURITY LAB SETUP

INTRODUCTION

This project documents my Week 1 practical cybersecurity lab setup using Kali Linux and Oracle VirtualBox.

TOOLS USED

- Kali Linux
- Oracle VirtualBox
- 7-Zip
- Windows Operating System

LAB CONFIGURATION

Network Configuration

- Configured the NAT Network.
- Network address: 10.0.0.0/24
- DHCP enabled.
- Connected Kali Linux to the NAT Network.

IP Address Configuration

- Verified Kali Linux IP address: 10.0.0.2/24.

Internet and DNS Testing

- Tested gateway connectivity.
- Tested internet connectivity.
- Configured DNS using 1.1.1.1 and 8.8.8.8.
- Confirmed successful DNS resolution.

Shared Folder

- Configured Windows Downloads as a shared folder.
- Enabled Auto-mount.

Clipboard and Drag-and-Drop

- Enabled Bidirectional Shared Clipboard.
- Enabled Bidirectional Drag and Drop.

Virtual Machine Snapshot

Created a snapshot named Cybersecurity Lab - Initial Setup.

TROUBLESHOOTING EXPERIENCE

DNS Resolution Problem

Kali Linux could connect using an external IP address but could not resolve domain names. I corrected this by configuring DNS servers in the resolv.conf file.

Network Adapter Problem

The network adapter could not be enabled while Kali Linux was running. I shut down the virtual machine and changed the setting.

Shared Folder Problem

The shared folder path contained a typing error. I corrected the path and saved the configuration.

CONCLUSION

Successfully configured a Kali Linux cybersecurity lab using Oracle VirtualBox. Tested network connectivity, corrected DNS resolution, configured shared folder access, and created a virtual machine snapshot.

SCREENSHOTS

Screenshots of the practical setup and testing process will be uploaded to this repository.
