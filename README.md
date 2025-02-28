<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system "osTicket".<br />


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
Download this zipfile which includes all the necessary installs required for this installation (https://tinyurl.com/252s4yv6). To enable IIS in Windows with CGI, go to Control Panel\Programs\Programs and Features, then on the left side column "Turn Windows features on or off"
</p>
<br />

![image](https://github.com/user-attachments/assets/b8fd7147-f15e-49f0-bc49-0155acc4e006)

<p>
Install PHP Manager for IIS and  Rewrite Module
</p>
<br />

![image](https://github.com/user-attachments/assets/d0936cb1-7125-4eef-9861-756fabbeaf73)

<p>
Create a new folder called "PHP" in the "C:" drive. Then unzip the PHP 7.3.8 folder into the newly creacted "C:\PHP" folder.
</p>
<br />


![image](https://github.com/user-attachments/assets/d86e277c-a3c2-4e7c-8f05-9885d16c8b86)


<p>
Install Microsoft Visual C++ and MYSQL
</p>
<br />

![image](https://github.com/user-attachments/assets/fba3c584-1d39-4c36-8002-554c522aedeb)

<p>
Install osTicket and copy the “upload” folder into “c:\inetpub\wwwroot” - Rename “upload” to “osTicket”. Open IIS and navigate to Sites ---> Default Web Site ---> osTicket, then on the right click “Browse *:80”.
</p>
<br />

![image](https://github.com/user-attachments/assets/2c43c5eb-447a-47a4-9862-e6d9420d6d6b)


<p>
On IIS navigate to Sites ---> Default Web Site ---> osTicket ---> PHP manager. Click "Enable or disable an extension", then enable these extensions, php_imap.dll, php_intl.dll, php_opcache.dll After that refresh the browser, and you'll notice some extensions are now enabled.
</p>
<br />

![image](https://github.com/user-attachments/assets/0ffc293e-55f7-482c-8f4d-62cea70e7ddd)

<p>
Go to "C:\inetpub\wwwroot\osTicket\include\" and find the folder "ost-sampleconfig.php" and rename it to "ost-config.php"
</p>
<br />

![image](https://github.com/user-attachments/assets/cff71dd1-376c-4d9f-8c0d-334ccfe76b02)


<p>
Go to the properties of "ost-config.php" then go to the security tab and click "advanced". Then click "disable inheritance". After that, add "everyone", give them full access.
</p>
<br />

![image](https://github.com/user-attachments/assets/38687ba5-9167-44c0-b739-8e7d136fbcd9)


<p>
Install HeidiSQL and continue setting up osTicket on the browser
</p>
<br />
