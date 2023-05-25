<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create a Virtual Machines in Azure with its Resource Group.
- Remote desktop into the Virtual Machine
- Set up installation files and IIS
- Set up the installation files to install OSticket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/KF0pArg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/tyH9P25.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
</p>
<p>
Log into Azure and placed in the search bar Resouce Groups. After, I named my group and verified that it was established, I put Virtual Machine in the search bar and clicked create. Then, I chose the resource group I created, set up a VM name, selected a region and Image (whether windows or ubuntu), and selected the size for to set up the amount of Vcpu's that I will need to successfully deploy the VM. 
</p>
<br />

<p>
<img src="https://i.imgur.com/0p3oyOV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/y6awEGx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
</p>
<p>
Using windows search bar, I located remote desktop. I took the Public IP address of my Virtual Machine and logged into it. After, I started the process of setting up the installation files and configuring the IIS to help with installing and deploying OSticket system. 
</p>
<br />

<p>
<img src="https://i.imgur.com/CWTClWP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After configuration of IIS is complete, I installed the OSticketing system. Once the install was complete I went back to IIS to enable some extensions and refresh the OSticket site to observe the changes. Then I continued completing the last few set up requirements in order to start creating an admin user with multiple end users who can submit tickets.   
</p>
<br />
