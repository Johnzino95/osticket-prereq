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

- 1.Azure VM Setup and Configuration
- 2.Database Setup
- 2.Web Server Installation

<h2>Installation Steps</h2>

<p>
<img width="565" alt="image" src="https://github.com/user-attachments/assets/fb77783d-c772-4ac9-886d-1518938314fd">
</p>
<p>
<h1>Step 1: Set Up the Azure VM</h1>
  
  Create an Azure VM: Use Azure Portal or CLI to create a VM with Ubuntu or Windows Server (choose based on your osTicket requirements).

  Select VM Size: Pick a size that meets the needs of the ticketing system, typically starting with a moderate size like Standard_B2s.

  Secure Access: Set up Network Security Groups (NSGs) to allow HTTP/HTTPS traffic for web access and restrict SSH/RDP access to secure IPs.
</p>
<br />

<p>
<img width="809" alt="image" src="https://github.com/user-attachments/assets/dba6b50a-f8a2-4f93-8191-caca673a0f16">
</p>
<p>
<h1>Step 2: Install Required Software (Database and Web Server)</h1>
  
  Install a Database: Install MySQL or another compatible database on the VM (or a separate VM) to store ticketing data.
  
  Install Web Server: Set up Apache or IIS (on Windows) to serve the osTicket application. Enable the necessary firewall rules for web access.
  
  Download and Configure osTicket: Download osTicket, configure database settings, and upload the osTicket files to the web server’s directory.

