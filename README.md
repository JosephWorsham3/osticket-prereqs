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

- Download the osTicket-Installation-Files.zip
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Installation Steps</h2>

- Log into the VM with Remote Desktop

- Within the VM (osticket-vm), download the osTicket-Installation-Files.zip and unzip it onto your desktop. The folder should be called “osTicket-Installation-Files”
Use the files in this folder to install osTicket and some of the dependencies.




![image](https://github.com/user-attachments/assets/f27e5610-7c0d-48bc-8159-19f102811fdf)




<p>

- Install / Enable IIS in Windows WITH CGI
World Wide Web Services -> Application Development Features -> [X] CGI

</p>


![image](https://github.com/user-attachments/assets/f1ed115b-5063-4fc6-b92d-feb93bdab38d)


<p>
    
- From the “osTicket-Installation-Files” folder, install PHP Manager for IIS (PHPManagerForIIS_V1.5.0.msi)

</p>


![image](https://github.com/user-attachments/assets/f998361f-4254-4d13-83ce-17a7aede11fb)

- From the “osTicket-Installation-Files” folder install the Rewrite Module (rewrite_amd64_en-US.msi)



<br />


![image](https://github.com/user-attachments/assets/66183552-5d4f-40a0-90ac-bf08d056479f)



<p>

    
- Create the directory C:\PHP

- From the “osTicket-Installation-Files” folder, unzip PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) into the “C:\PHP” folder

</p>
<br />


![image](https://github.com/user-attachments/assets/16dc0486-cd02-4068-8b02-de8e268da09d)


<p>

- From the “osTicket-Installation-Files” folder, install VC_redist.x86.exe.

</p>
<br />

![image](https://github.com/user-attachments/assets/2687b4a8-ccd2-4354-9c25-b4e0f3c9f90c)


<p>

- From the “osTicket-Installation-Files” folder, install MySQL 5.5.62 (mysql-5.5.62-win32.msi)
- Typical Setup ->
- Launch Configuration Wizard (after install) ->
- Standard Configuration ->

  </p>
<br />

![image](https://github.com/user-attachments/assets/ca9d3396-44d2-4287-8fbd-b9eb33c953c5)









