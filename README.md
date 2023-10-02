<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This Demonstration outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Install / Enable IIS in Windows WITH
CGI and Common HTTP Features

-  Install PHP Manager for IIS 
- Install the Rewrite Module
- Create the directory C:\PHP
- Download PHP 7.3.8 
- Install VC_redist.x86.exe.
- Install MySQL 5.5.62
- Open IIS as an Admin
- Register PHP from within IIS
- Install osTicket v1.15.8
<h2>Installation Steps</h2>
1.
<p>
<img <img width="320" alt="Screen Shot 2023-10-02 at 5 45 34 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/175612eb-7b5e-43c3-9c4f-66b4e3111848">
</p>
<p>
In control panel find-> programs ->Turn Windows features on and off-> Install / Enable IIS in Windows WITH
CGI and Common HTTP Features
World Wide Web Services -> Application Development Features ->
[X] CGI
[X] Common HTTP Features
AND IIS Management Console
Internet Information Services -> Web Management Tools -> IIS Management Console
	[X] IIS Management Console

</p>
<br />
2.
<p>
<img width="555" alt="Screen Shot 2023-10-02 at 6 03 03 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/f52b19e1-6178-4149-9268-99da6a2494a4">

</p>
<p>
Download and Install PHP Manager for IIS
</p>
<br />
3.
<p>
<img width="523" alt="Screen Shot 2023-10-02 at 6 07 41 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/d63d45cf-70be-4a6f-8554-ad99666aa9ac">
  
Download and Install the Rewrite Module
</p>
<br />
4.
<img width="970" alt="Screen Shot 2023-10-02 at 6 20 01 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/bdd03c06-0409-4ac0-8ef7-309f6e339d14">
<img width="911" alt="Screen Shot 2023-10-02 at 6 20 12 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/e444f246-3eb9-4682-b204-27fc5d09fe10">
</p>
<br />
Create the directory C:\PHP
</p>
<br /

5.
<p>
<img width="523" alt="Screen Shot 2023-10-02 at 6 11 25 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/47d9c4fe-bb32-4dcd-a47e-f3d433a18e74">
<img width="782" alt="Screen Shot 2023-10-02 at 6 27 23 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/bf270b7b-8264-4370-a2df-af9e338e0589">
<img width="790" alt="Screen Shot 2023-10-02 at 6 30 36 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/fcfe6104-9f33-4f11-bff0-99f7be032b60">
</p>
<br />
Download and Install PHP files. It will be zipped and downloaded in the downloads folder in File Explorer. From the File Explorer download folder right-click the PhP zip file and extract. Then Browse to directory C:\PHP and dump all files 
</p>
<br /
6.
<img width="521" alt="Screen Shot 2023-10-02 at 6 58 22 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/feda9458-d5be-41bf-a513-2f0c2805d2cc">
