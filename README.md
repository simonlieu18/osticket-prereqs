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

- Enable IIS in Windows with CGI
- Install PHP Manager for IIS
- Install Rewrite Module
- Install MYSQL
- Install Microsoft Visual C++

<h2>Installation Steps</h2>

![image](https://github.com/user-attachments/assets/b4f7f358-a4d7-4fdd-af90-a9e5160a7e04)

<p>
To enable IIS in Windows with CGI, go to Control Panel\Programs\Programs and Features, then on the left side column "Turn Windows features on or off"
</p>
<br />

![image](https://github.com/user-attachments/assets/b9852971-c0a8-4c49-856d-c82116bc95f7)
<p>
Install PHP Manager for IIS, Rewrite Module, MYSQL, Microsoft Visual C++
</p>
<br />

![image](https://github.com/user-attachments/assets/fba3c584-1d39-4c36-8002-554c522aedeb)

<p>
Install osTicket and copy the “upload” folder into “c:\inetpub\wwwroot” - Rename “upload” to “osTicket”. In IIS go to sites, default, osTicket then on the right click “Browse *:80”. Then enable some extensions that were disabled, php_imap.dll, php_intl.dll, php_opcache.dll
</p>
<br />

![image](https://github.com/user-attachments/assets/38687ba5-9167-44c0-b739-8e7d136fbcd9)


<p>
Install HeidiSQL and continue setting up osTicket on the browser
</p>
<br />
