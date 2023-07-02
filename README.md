

<h1>VPN Set UP On Microsoft Azure Virtual Machine</h1>

<p align="center">
<img src="https://imgur.com/Yf2LGik.png" alt="Windows 10 Virtual Machine Desktop"/>
</p>
<br />

This tutorial outlines the Set Up of VPN within Azure Virtual.<br />

<h2>Environments and Technologies Used</h2>
- Microsoft Azure Virtual Machines
- Proton VPN 
- Windows 10
- Azure Storage 
- Azure Resource Group

<h2> Operating System Used</h2>
Windows 10
<h2>High-Level Deployment and Configuration Steps</h2>

 Create A Resource Group Within Mircosoft Azure
 
 Create Azure Virtual Machine 
 
 Login into Virtual Machine on Remote Desktop 
 
 Install Proton VPN on Virtual
 
 Browse to (https://whatismyipaddress.com/) On Azure Virtual Machine and Copy IP Address 
 
 Connect IP Address To Proton VPN

<h2>Deployment and Configuration Steps</h2>

<p align="center">
<img src="https://imgur.com/tIL0E79.png" alt="Creation Of Resource Group"/>
</p>
To create a resource group in Microsoft Azure, sign in to the Azure portal and navigate to the Resource Groups section. Click on "Add" and provide the necessary details such as subscription, resource group name, and region. Review the information and click "Create" to create the resource group
</p>
<br />


<p align="center">
<img src="https://imgur.com/sYKuFqy.png" alt="Creation Of Mircosoft Azure Virtual Machine"/>
</p>
Sign in to the Azure portal, search and select "Virtual Machine," and fill in the required details and select your created resource groups.Configure the VM settings and review the information, then click "Create" to start the deployment.
</p>
<br />


<p align="center">
<img src="https://imgur.com/shxuaFh.png" alt="Login Into Virtual Machine Via Remote Desktop Connection"/>
</p>
Log in to Azure VM via Remote Desktop Connection application, You will need to obtain the VM's public IP address, Then open Remote Desktop Connection, Finally enter the IP address and login credentials, and connect securely.
</p>
<br />


<p align="center">
<img src="https://imgur.com/DFrNRck.png" alt="Install Proton VPN"/>
</p>
Open Mircosoft Edge, Then download google chrome, open google chrome and go to (https://protonvpn.com/download) to install Proton VPN.
</p>
<br />


<p align="center">
<img src="https://imgur.com/PL8A0K9.png" alt="Find Public IP Address"/>
</p>
Search (https://whatismyipaddress.com/) to find public IP Address on Mircosoft Virtual Machine. Then Copy that IP Address to insert into Proton VPN, if it is not already inserted
</p>
<br />


<p align="center">
<img src="https://imgur.com/y6GpCwl.png" alt="Connect and Open within Proton VPN"/>
</p>
Login into Proton VPN and check that your public IP Address is correct. Then connect to a different server anywhere in the world that you choose. Finally go to (https://whatismyipaddress.com/) and it will show the different server you connected to
<p align="center">
<img src="https://imgur.com/XcyJKtC.png" alt="Server Proton VPN"/>
</p>
