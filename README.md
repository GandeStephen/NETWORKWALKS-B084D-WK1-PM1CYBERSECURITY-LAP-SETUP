Kali Linux VirtualBox Lab Setup

📌 Project Overview

This project documents my setup of Kali Linux 2026.2 in Oracle VirtualBox on a Windows computer. The goal was to prepare a virtual machine for learning cybersecurity, configure networking, test internet connectivity, and create a clean snapshot for recovery.

🎯 Project Objectives

- Install and run Kali Linux in Oracle VirtualBox.
- Configure the virtual machine's network adapter.
- Test network and internet connectivity.
- Create a clean virtual machine snapshot.
- Configure a shared folder between Windows and Kali Linux.
- Prepare a safe environment for cybersecurity practice.

🛠️ Tools and Technologies

- Operating System: Kali Linux 2026.2
- Host Operating System: Windows
- Virtualization Software: Oracle VirtualBox
- Network Mode: NAT Network
- Terminal: Kali Linux Terminal

⚙️ Lab Configuration

1. Virtual Machine Setup

I configured and launched Kali Linux 2026.2 in Oracle VirtualBox.

2. Network Configuration

I configured the virtual machine to use a NAT Network and enabled the virtual network cable.

3. Network Connectivity Testing

I used the Linux "ping" command to test connectivity.

Test internet connectivity:

ping -c 4 8.8.8.8

Test the virtual network gateway:

ping 10.0.0.1

Results: Both tests received replies, indicating that the tested destinations were reachable.

4. Virtual Machine Snapshot

I created a snapshot named "Clean Kali - Network Setup".

The snapshot provides a recovery point that I can return to if future lab experiments cause configuration problems.

5. Shared Folder Configuration

I configured a VirtualBox shared folder pointing to my Windows Downloads directory.

This provides a way to transfer files between the Windows host and Kali Linux, subject to the required VirtualBox Guest Additions and Linux permissions.

📸 Project Evidence

Screenshots included in this repository document:

- Kali Linux running in VirtualBox.
- The clean snapshot in VirtualBox Manager.
- VirtualBox system settings.
- NAT Network configuration.
- Successful ping tests.
- Shared folder configuration.

📚 Skills Practiced

- Linux fundamentals.
- Virtual machine management.
- Basic network troubleshooting.
- Connectivity testing using "ping".
- Virtual machine snapshot management.
- Shared folder configuration.
- Cybersecurity lab preparation.

🔐 Safety Considerations

This virtual machine is intended for authorized cybersecurity learning and testing.

Snapshots help restore a known configuration, but they do not replace backups or protect the host from every possible risk.

🚀 Future Improvements

- Configure a dedicated internal network for multiple lab virtual machines.
- Practise Linux commands and Python scripting.
- Capture and analyse network traffic using Wireshark.
- Perform authorized network scanning using Nmap.
- Document additional cybersecurity lab exercises.

👨‍💻 Author

Gande Stephen|Cybersecurity Beginner | Learning Linux, Networking, and Cybersecurity

---

Project Status: Initial lab setup and connectivity testing completed.
