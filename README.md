# active-directory-azure-lab

Active Directory lab built in Microsoft Azure



\## Project Overview



This project documents the Active Directory lab I completed using Microsoft Azure. The lab involved building a Windows Server domain environment and practicing common IT support and system administration tasks.

## Technologies Used



\- Microsoft Azure

\- Windows Server 2022

\- Windows 10

\- Active Directory Domain Services

\- PowerShell

\- DNS

\- Group Policy

## Lab Architecture



The lab was built in Microsoft Azure using two virtual machines connected to the same virtual network.



\- \*\*DC-1\*\* - Windows Server 2022 virtual machine used as the domain controller and DNS server.

\- \*\*Client-1\*\* - Windows 10 virtual machine used as the client computer.

\- Both virtual machines were connected to the same Azure virtual network.

\- DC-1 was configured with a static private IP address.

\- Client-1 was configured to use DC-1 as its DNS server.

