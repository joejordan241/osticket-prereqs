<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Enable Internet Information Services (IIS)
- Install Web Platform Installer
- Install MySQL and create user name and password
- Install C++Redistributable
- Configure permissions and install OSTICKET

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/abP4fmc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this step I opened the control panel and clicked programs and features to select Internet Information Services (IIS). Once selected I expanded the (ISS) feature and verified that the required components are enabled.
</p>
<br />

<p>
<img src="https://i.imgur.com/sVkdwcR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this step I had to install MySQL inorder to install osTicket. MySQL is required for osTicket to store all the critical information related to tickets,users,agents,and system settings.
</p>
<br />

<p>
<img src="https://i.imgur.com/ZyDW9dU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this step I downloaded the osTicket package, uploaded it to my web server, accessed the installation URL in my browser, created a database, set appropriate file permissions, and then followed the on-screen instructions to complete the installation process.
</p>
<br />
