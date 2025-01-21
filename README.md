<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>





<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Step 1-Set Up Virtual Machines
- Step 2-Install Wireshark
- Step 3-Configure Network Security Groups
- Step 4-Analyze Traffic

<h2>Actions and Observations</h2>


![image](https://github.com/user-attachments/assets/4f1279e5-8f23-48b1-a5cd-73b43878973d)



This screenshot showcases the initial setup of a Virtual Machine in Microsoft Azure. It highlights the configuration of essential details, such as the subscription, resource group, region, availability options, and security type. These settings determine how and where the VM will be deployed, ensuring it meets organizational and operational requirements.
<br />


![image](https://github.com/user-attachments/assets/ebd7426c-f0f8-4a66-9c0f-9e7282026158)

 This image shows the Wireshark setup process, with the installation wizard extracting files. Wireshark is a key tool used to capture and analyze network traffic, making it essential for monitoring communication between Azure Virtual Machines in this project."
This step ensures the necessary tools are installed to analyze traffic between Azure Virtual Machines effectively.



![image](https://github.com/user-attachments/assets/dca84d7a-0fce-4601-a3fa-db25f5c0870b)


This screenshot demonstrates the configuration of an inbound security rule in Azure's NSG settings. The rule specifies source, destination, port range, and protocol to control incoming traffic. Here, a custom rule is being created to allow traffic on port 8080 using TCP, with a priority set to ensure proper rule enforcement. This setup is part of securing Azure virtual machines and managing access to services effectively.







![image](https://github.com/user-attachments/assets/dba43ee7-e3ce-4614-a345-5bcab335f8c2)






This screenshot captures DNS queries and responses in Wireshark. It highlights the process of resolving domain names to IP addresses, a critical aspect of network communication. This analysis helps in troubleshooting DNS-related issues and understanding how name resolution works within a network environment."

