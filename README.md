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

<p>
Next download and install the VC_redist.x86.exe file. 
</p>
<br />

<p>
<img src="https://i.imgur.com/dQKXbo6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Next we will download and install MySQL 5.5.62 (mysql-5.5.62-win32.msi) with these steps:
Typical Setup ->
Launch Configuration Wizard (after install) ->
Standard Configuration ->
Password1
<br />
  
<p>
<img src="https://i.imgur.com/iHMPhdc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/R3xOWn4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/cP4f2DN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/hkEkM97.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/hDgCHpv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/kRiQZIO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/mOYsfCJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Dcx3eXt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/MOKDsTY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Open IIS as an administrator and register PHP from within IIS. Type in IIS in the windows search box. Select run as administrator. Reload IIS  (Open IIS, Stop and Start the server)
<br />
  
<p>
<img src="https://i.imgur.com/fy3oL4p.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/5nyMF5G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/CTW5RF1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/ZTTTRSS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/gXHC5nd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
  
<p>
Install osTicket v1.15.8. 
<br />
  
<p>
<img src="https://i.imgur.com/1ayAxEJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/V3x4uiZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/m1tNiIE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/yXImjDF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Mlvxsvw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/KO1mzj0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/evUzil7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/UwmOUz8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
</p> 

<p>
Note that some of the extensions are not enabled. Go back to IIS, sites -> Default -> osTicket. Double-click PHP Manager. Click “Enable or disable an extension”. Enable: php_imap.dll. Enable: php_intl.dll. Enable: php_opcache.dll. Refresh the osTicket site in your browse, observe the changes.
<br />
  
<p>
<img src="https://i.imgur.com/wGipn7o.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/uJty81c.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Zqs9nY7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/OGfTAxP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Xy3L2ee.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/iNwvvPZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


<p>
Rename: ost-config.php from C:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php to C:\inetpub\wwwroot\osTicket\include\ost-config.php.
<br />
  

<p>
<img src="https://i.imgur.com/qXqmrGt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/mCNpcTk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

