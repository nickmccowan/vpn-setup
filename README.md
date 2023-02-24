<p align="center">
<img src="https://i.imgur.com/C6h2cB6.jpg"/>
</p>

<h1>VPN Setup and Usage</h1>
This tutorial outlines the implementation of a VPN in remote desktop.<br />




<h2>Environments and Technologies Used</h2>

- Proton VPN
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- whatismyipaddress.com

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Browse to "whatismyipaddress.com" on home network
- Connect to a virtual machine via remote desktop
- Browse to "whatismyipaddress.com" through the remote desktop
- Download Proton VPN and connect to a server
- Browse to "whatismyipaddress.com" through the VPN server

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/1BrdE7b.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Browse to whatismyipaddress.com to see IP address of home PC.
</p>
<br />

<p>
<img src="https://i.imgur.com/KmL6iSX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a Virtual Machine in Azure, change the region to a foreign country i.e. South Africa.
</p>
<br />

<p>
<img src="https://i.imgur.com/IlpBRzS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Use Remote Desktop to login to the newly created Virtual Machine.
</p>
<br />
<p>
<img src="https://i.imgur.com/MucZfbA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
From the Virtual Machine browse to whatismyipaddress.com, notice the change in IP address from the previous entry.
</p>
<br />
<p>
<img src="https://i.imgur.com/w9r5YYC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
From the home PC Create a Proton VPN account, this will allow the usage of Proton VPN.
</p>
<br />
<p>
<img src="https://i.imgur.com/01uhAsn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
From the Virtual Machine download Proton VPN for Windows.
</p>
<br />
<p>
<img src="https://i.imgur.com/egUK87A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Login to the Proton VPN account to gain access to the VPN.
</p>
<br />
<p>
<img src="https://i.imgur.com/j8RG7YP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once logged in choose a location for the VPN i.e. Japan.
</p>
<br />
<p>
<img src="https://i.imgur.com/fALntMu.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The VPN has been created.
</p>
<br />
<p>
<img src="https://i.imgur.com/rsxIHVL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
From the VPN browse to whatismyipaddress.com, notice the change in IP address.
</p>
<br />
