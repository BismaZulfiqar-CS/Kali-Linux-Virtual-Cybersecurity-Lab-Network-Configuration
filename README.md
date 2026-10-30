Kali Linux Virtual Cybersecurity Lab – Network Configuration

1. Project Introduction
This project demonstrates the creation and configuration of a virtual cybersecurity laboratory using Oracle VirtualBox and Kali Linux. The main objective was to establish a virtual network, configure IP addressing, and verify internet connectivity within the Kali Linux environment.

The lab provides a foundation for learning networking concepts and practising cybersecurity activities in a controlled virtual environment. It can also be expanded in the future by introducing additional virtual machines for network analysis and authorized penetration-testing exercises.

2. Lab Environment and Configuration
The following technologies and settings were used to build the laboratory:
* Domain: Cybersecurity and Networking
* Virtualization Software: Oracle VirtualBox
* Operating System: Kali Linux
* Network Configuration: NAT Network
* Network Name: NatNetwork
* Network Address: 10.0.0.0/24
* IP Address: 10.0.0.2 (additional static address)
* Subnet Mask: 255.255.255.0
* Default Gateway: 10.0.0.1
* DNS Server: 10.0.0.1
* DHCP: Enabled

3. Implementation Process
   
Step 1 – Creating the Virtual Network
A custom NAT Network named NatNetwork was configured through Oracle VirtualBox.
The IPv4 network range was set to 10.0.0.0/24, and the DHCP service was enabled to support automatic IP address allocation.
This network provides a private environment for virtual machines while allowing controlled access to external networks.
<img width="1365" height="729" alt="image" src="https://github.com/user-attachments/assets/a4297cfa-d304-4932-acba-7fcb7d438c99" />

Step 2 – Setting Up Kali Linux
Kali Linux was installed and launched as a virtual machine in Oracle VirtualBox.
The operating system provides a suitable platform for learning cybersecurity concepts and exploring security-testing tools.


Step 3 – Configuring Network Connectivity
The virtual machine’s wired network connection was configured through the Kali Linux Network Manager.
The IPv4 configuration included:
* Network method: Automatic (DHCP)
* Additional IP address: 10.0.0.2
* Prefix: /24
* Gateway: 10.0.0.1
* DNS: 10.0.0.1
These settings associate the additional IP address with the configured virtual network.
<img width="1366" height="720" alt="image" src="https://github.com/user-attachments/assets/631dd322-0089-4f94-9a2b-a05a183830d7" />

Step 4 – Saving the Virtual Machine State
A snapshot was created in Oracle VirtualBox to preserve the virtual machine’s state.
This provides a recovery point that can be useful when experimenting with future network configurations or cybersecurity practicals.
<img width="760" height="587" alt="image" src="https://github.com/user-attachments/assets/f0c61f12-8870-4f1c-8632-d8b60eb9bf4d" />

4. Network Connectivity Testing
After configuring the network, connectivity was checked by launching Firefox inside Kali Linux.
The Google homepage (google.com) loaded successfully.
This provided visual confirmation that the virtual machine had working internet access and could resolve and access a website.
<img width="1366" height="732" alt="image" src="https://github.com/user-attachments/assets/40a6318f-4a50-4834-89f7-b7d2dd76c0e2" />

5. Project Results
The following tasks were completed during the laboratory setup:
* Created a custom NAT Network in VirtualBox.
* Configured the Kali Linux network connection.
* Added an additional IPv4 address.
* Specified the gateway and DNS settings.
* Successfully accessed Google through the Kali Linux browser.
* Created a VirtualBox snapshot for environment preservation.

6. Learning Outcomes
Through this practical exercise, I gained experience with:
* Virtual machine management using Oracle VirtualBox.
* Basic Linux network configuration.
* IPv4 addressing and subnet masks.
* Understanding NAT Network functionality.
* DHCP and static IP address concepts.
* Gateway and DNS configuration.
* Testing network connectivity.
* Managing virtual machine snapshots.

7. Future Improvements
The laboratory can be extended by:
* Adding another virtual machine to the private network.
* Practising network discovery and scanning.
* Learning packet analysis using Wireshark.
* Exploring vulnerability assessment tools.
* Performing authorized penetration-testing exercises in the isolated lab.

Conclusion
This project provided practical experience in establishing a virtual cybersecurity environment using Kali Linux and Oracle VirtualBox. The successful browser connectivity test demonstrated that the configured environment could access external websites.

The completed setup serves as a starting point for developing practical networking knowledge and exploring more advanced cybersecurity laboratory activities.

Project Status: Initial laboratory setup and connectivity verification completed.
