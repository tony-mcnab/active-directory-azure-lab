# Active Directory Azure Lab
Active Directory lab built in Microsoft Azure

## Project Overview

This project documents the Active Directory lab I completed using Microsoft Azure. The lab involved building a Windows Server domain environment and practicing common IT support and system administration tasks.

## Technologies Used

- Microsoft Azure
- Windows Server 2022
- Windows 10
- Active Directory Domain Services
- PowerShell
- DNS
- Group Policy


## Lab Architecture
![Azure resource group showing the Active Directory lab resources](images/azure-resource-group.png)

The lab was built in Microsoft Azure using two virtual machines connected to the same virtual network.

- **DC-1** - Windows Server 2022 virtual machine used as the domain controller and DNS server.
- **Client-1** - Windows 10 virtual machine used as the client computer.
- Both virtual machines were connected to the same Azure virtual network.
- DC-1 was configured with a static private IP address.
- Client-1 was configured to use DC-1 as its DNS server.


## Part 1: Preparing the Active Directory Infrastructure

I created the basic Azure environment needed for the Active Directory lab.


### Azure Network Setup

- Created a Resource Group in Microsoft Azure.
- Created a Virtual Network and subnet.
- Created a Windows Server 2022 virtual machine named **DC-1**.
- Created a Windows 10 virtual machine named **Client-1**.
- Connected both virtual machines to the same Virtual Network.
- Configured DC-1 with a static private IP address.

![DC-1 static private IP configuration](images/dc1-static-private-ip.png)

- Configured Client-1 to use DC-1's private IP address as its DNS server.

![Client-1 custom DNS configuration pointing to DC-1](images/client1-dns-configuration.png)

