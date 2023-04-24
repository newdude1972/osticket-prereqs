# osticket-prereqs<p align="center">
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

- Install / Enable Internet Information Services (IIS) in Windows with CGI
- Download and install PHP Manager for IIS (PHPManagerForIIS_V1.5.0.msi)
- Download and install the Rewrite Module (rewrite_amd64_en-US.msi)
- Download PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) 
- Download and install VC_redist.x86.exe
- Download and install MySQL 5.5.62 (mysql-5.5.62-win32.msi)
<h2>Installation Steps</h2>

<p>
The first step to installing osTicket ticketing system to your computer or virtual machine is to install Information Services from windows start menu and enable it to use CGI. This step will allow your computer to serve up a website to use the ticketing system. Right click the windows start menu. Click run and enter "control panel" into the field. Select "Programs" then select "Turn Windows features on or off." Next check the "Internet Information Services" box. Expand the field with the + button. Expand the "World Wide Web Services" tab. Next expand the "Applications Development Features" field. Next check the box for "CGI" and select "OK".
</p>
<br />

<p>
<img src="https://i.imgur.com/uDmGjwI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/7BiIn8D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/8WHiGKb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/zGvDJjA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/2Payf5Y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/4a4BoPg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>  
</p>

<p>
Next download and install PHP Manager for IIS. (PHPManagerForIIS_V1.5.0.msi)
</p>
<br />

<p>
<img src="https://i.imgur.com/Q72snqK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/0VkHmfE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/bBsWdds.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/uEL22sl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>  
</p>

<p>
Next download and install the Rewrite Module file (rewrite_amd64_en-US.msi)
</p>
<br />


<p>
<img src="https://i.imgur.com/OtK2PEw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/TXIqrPA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
</p>
<p>
Next we will create a directory of C:\PHP on the main drive to store and run our remaining osTicket files out of.
</p>
<br />

<p>
<img src="https://i.imgur.com/ISVTDuK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/AxFncqE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/X3scxw8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>  
</p>

<p>
Next we will download the file PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) and unzip the contents into our newly created directory C:\PHP.
<br />
  
<p>
<img src="https://i.imgur.com/cdkBx5r.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/bvHM6WJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/I8k9zx0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


