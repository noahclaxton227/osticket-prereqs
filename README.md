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

- Item 1: VM Machine
- Item 2: Enable IIS
- Item 3: Register PHP
- Item 4: Install & store osTicket
- Item 5: Add MySQL Database and signin
- Item 6: Completion!

<h2>Installation Steps</h2>

![image](https://github.com/noahclaxton227/osticket-prereqs/assets/150629711/c9177440-5764-4904-942f-00e500a0ac82)


<p>
</p>
<p>
Created two Virtual Machines on portal.azure.com. These machines can be utilized by Remote Desktop in order to download + experiment with osTicket on a "different" operating and file system. 
</p>
<br />

<p>

![image](https://github.com/noahclaxton227/osticket-prereqs/assets/150629711/32527e87-a300-49df-be7d-9b4e74061a59)


</p>
<p>
By right clicking on start menu --> run --> control  --> programs --> turn windows features on/off, we install IIS (Internet Information Services), the webserver that osTicket runs on.
</p>
<br />

<p>
  
![image](https://github.com/noahclaxton227/osticket-prereqs/assets/150629711/8fed1b12-155f-4013-809b-d4bf2dd2b33c)
</p>
<p>
By opening up IIS (as administrator) --> PHP Manager --> Register --> PHP Folder, we register PHP into IIS!
</p>
<br />

<p>

![image](https://github.com/noahclaxton227/osticket-prereqs/assets/150629711/6436e861-5b55-4e16-b827-4f188295ee9a)

</p>
<p>
After downloading the osTicket zip file --> extracting the upload file (renamed osTicket) --> use IIS to "Browse*:80" --> Installed!!!
</p>
<br />

<p>

![image](https://github.com/noahclaxton227/osticket-prereqs/assets/150629711/e9f089ab-db3d-4630-b2d8-9ebc6fcfc6f4)

</p>
<p>
Opened HeidiSQL --> Created a new database titled "osTicket" --> Plugged that into the osTicket login browser. 
</p>
<br />

<p>
  
![image](https://github.com/noahclaxton227/osticket-prereqs/assets/150629711/4d088104-0416-4cf0-8c83-dbc6c8b4a34d)

</p>
<p>
Complete!
</p>
<br />
