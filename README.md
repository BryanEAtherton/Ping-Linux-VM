# Security Project 1

<p align="center">
  <img src="http://i.imgur.com/gMmsO4e.png"/>
   <img src="https://i.imgur.com/b9ryJrF.jpeg"/>
</p>

<h1> Ping and log into Linux VM using Microsoft Powershell (SSH) </h1>
We will ping the Linux VM and log into it using Microsoft PowerShell.

<h2>Operating System Used</h2>

-Windows 10

-Linux (Ubuntu)


<h2>Environments and Technologies Used</h2>

- Microsoft PowerShell


<h2> Ping the Linux VM </h2>

<br />


<p>
1. Open Microsoft PowerShell and find the public IP address of the Linux VM. 
</p>
<p>
<img src="https://i.imgur.com/ycNlNku.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
For instructions on finding the public IP address of an Azure VM, refer to step 9 in the Azure Virtual Machine Setup and Access section.
  
[Click here to view the Azure Virtual Machine Setup and Access section](https://github.com/BryanEAtherton/Azure-Virtual-Machine)

<br />

<p>
2. Use the ping command and type or paste the Linux VM IP address into the command line, then press Enter.  Observe the successful ping attempt that follows. 
</p>
<p>
<img src="https://i.imgur.com/OghKqZJ.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>

<h2> Log into the Linux VM  </h2>

<p>
3. Type the command ssh, followed by the username established when creating the Linux VM, and the IP address.  Type "yes" when asked "Are you sure you want to continue connecting?", and press Enter.
</p>
<p>
<img src="https://i.imgur.com/xKfD5s8.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>

<p>   
4. Enter the password established when creating the Linux VM.  Note: No text will appear when entering the password, but rest assured, it is being entered. Then press Enter.
<p>
<img src="https://i.imgur.com/4FmyNK0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
5. If done successfully, notice the change in user name and color of the text.  We are now logged into the Linux VM and can issue commands to the OS. 
<p>
<img src="https://i.imgur.com/mtHsCa1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

[Click here to return to the Homepage](https://github.com/BryanEAtherton)

<br />

