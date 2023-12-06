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

- Install PHP Manager for IIS 
- Install the Rewrite Module
- Create the directory C:\PHP
- Download PHP 7.3.8 
- Install VC_redist.x86.exe.
- Install MySQL 5.5.62
- Open IIS as an Admin
- Register PHP from within IIS
- Install osTicket v1.15.8
- Log in and Test
<h2>Installation Steps</h2>
1.

<p>
<img <img width="320" alt="Screen Shot 2023-10-02 at 5 45 34 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/175612eb-7b5e-43c3-9c4f-66b4e3111848">
</p>
<p>
In control panel find-> programs ->Turn Windows features on and off-> Install / Enable IIS in Windows WITH
CGI and Common HTTP Features:
	
World Wide Web Services -> Application Development Features ->
[X] CGI

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

5 .
<p>
<img width="523" alt="Screen Shot 2023-10-02 at 6 11 25 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/47d9c4fe-bb32-4dcd-a47e-f3d433a18e74">
<img width="782" alt="Screen Shot 2023-10-02 at 6 27 23 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/bf270b7b-8264-4370-a2df-af9e338e0589">
<img width="790" alt="Screen Shot 2023-10-02 at 6 30 36 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/fcfe6104-9f33-4f11-bff0-99f7be032b60">
</p>
<br />
Download and Install PHP files. It will be zipped and downloaded in the downloads folder in File Explorer. From the File Explorer download folder right-click the PhP zip file and extract. Then Browse to directory C:\PHP and dump all files 
</p>
<br 
	
6 .

<img width="521" alt="Screen Shot 2023-10-02 at 6 58 22 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/feda9458-d5be-41bf-a513-2f0c2805d2cc">
</p>
<br />
Download and Install VC_redist.x86.exe.
</p>
<br />
7 .
</p>
<img width="502" alt="Screen Shot 2023-10-02 at 8 13 52 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/afb93af8-3bd4-4ab3-8e72-296827416901">
<img width="495" alt="Screen Shot 2023-10-02 at 8 14 40 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/35addaba-1008-497f-8d17-afc6d524a6cf">

</p>
<br /

Download the MySQL Installer. Create the root password in the installer, then execute and Install MySQL 5.5.62  
</p>
<br /

8 .

<img width="788" alt="Screen Shot 2023-10-02 at 8 26 47 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/eb0c36d7-62f8-430a-88f2-f1529e84904d">
<img width="947" alt="Screen Shot 2023-10-02 at 8 27 04 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/0b518316-db86-40bb-bd03-0eb367489ed4">
<img width="942" alt="Screen Shot 2023-10-02 at 8 27 31 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/61dadc9e-47f0-44b5-b1c2-a94d516e5a55">
<img width="663" alt="Screen Shot 2023-10-02 at 8 28 22 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/86bc6d2d-0db2-46f3-8357-b6d3cda230da">
<img width="737" alt="Screen Shot 2023-10-02 at 8 28 39 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/5336c68d-b72a-4593-ab99-da95cfb66a9c">
</p>
<br /

Search and open Internet Infromation Services (IIS). Locate and open PHP Manager. Click register new PHP version. Browse for C:\PHP -> php-cgi and hit OK. 
</p>
<br /

9 .

<img width="683" alt="Screen Shot 2023-12-04 at 11 08 57 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/a050e4fe-ded5-42d0-95e8-edcb293666aa">
<img width="1275" alt="Screen Shot 2023-10-02 at 8 48 58 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/79e8ffd3-8eda-4ed5-bcab-d7f902ef36f9">
<img width="638" alt="Screen Shot 2023-10-02 at 9 10 41 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/317b11cf-8619-4c9b-801f-bd445046c15d">

</p>
<br /

Download the osTicket zip file and locate and open it in File Explorer. Locate the Upload folder. On a separate File Explorer open Windows(C:) -> inetpub -> wwwroot -> Drag and drop uploud folder from osTicket zip file to wwwroot. Then rename the upload folder to "osTicket"
</p>
<br /

10 .

<img width="931" alt="Screen Shot 2023-10-02 at 9 14 24 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/780a30b0-f7b6-44bf-b5b9-14d42c2b426f">
<img width="942" alt="Screen Shot 2023-10-02 at 9 19 42 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/34c81b1a-cd33-435d-a6fd-aae08f5a5e9f">
</p>
<br /

Open IIS again and reset it. Then locate and open the osTicket folder in IIS. Click to highlight and on the right side of the screen click Browse *:80(HTTP) to open the osTicket installer.
</p>
<br /

11 .

<img width="814" alt="Screen Shot 2023-10-02 at 9 36 19 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/7d258e97-dcd1-48c1-9f47-580ba63c3c68">
<img width="890" alt="Screen Shot 2023-10-02 at 9 38 21 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/cb0766f6-e3f4-4992-8373-9b6fa1692aab">
<img width="900" alt="Screen Shot 2023-10-02 at 9 38 08 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/be5cc988-bd63-4201-9a5f-9c6d9e7101a3">
<img width="820" alt="Screen Shot 2023-10-02 at 9 49 40 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/c5f89e97-a989-4dc9-b5d9-878b0c7b16ee">

</p>
<br /

osTicket recommends some extensions to be installed. Reopen IIS and open PHP Manager again. At the bottom of the PHP Manager locate and open "Enable or disable an extension". Enable: php_imap.dll , Enable: php_intl.dll , Enable: php_opcache.dll located from the Disabled list. Reset osTicket in web browser and observe changes. 
</p>
<br /

 12 .

 <img width="787" alt="Screen Shot 2023-10-02 at 9 55 08 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/3180cbc7-8b3a-491d-a71f-5bc1182b4f9c">
<img width="776" alt="Screen Shot 2023-10-02 at 9 56 18 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/f084f12c-4b56-4720-b97f-6b04439515bd">
<img width="1159" alt="Screen Shot 2023-10-02 at 9 59 42 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/3830c402-334d-46cc-9a45-fa03903934f0">
</p>
<br /

From Windows(C:) -> inetpub -> wwwroot -> osTicket -> Include. Locate the ost-sampleconfig.php file and rename the file to ost-config.php. Right-click on the file and open properties. Click the "Security" tab on the top and select "Advanced" at the bottom. "Disabled inheritance" and  then click "Add". Click "Select a principal" at the top of the page. In the text box write "everyone" then hit " Ok". Then Select the full control box and hit "OK". Note: this step is only to finish installing and setting up osTicket without figuring out who has access to the file.
</p>
<br /

13 .

<img width="583" alt="Screen Shot 2023-10-02 at 10 31 24 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/077e77f5-2066-487c-bb6c-2a8693728d66">
<img width="680" alt="Screen Shot 2023-10-02 at 10 32 13 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/7679ddc6-f00f-4714-8291-cbbe05c1a19a">
<img width="680" alt="Screen Shot 2023-10-02 at 10 32 23 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/48b58a32-b520-434e-8a12-39c7daeb6978">
<img width="939" alt="Screen Shot 2023-10-02 at 10 34 07 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/29e1556b-c8fc-430f-9486-584502e867bd">
<img width="915" alt="Screen Shot 2023-10-02 at 10 34 33 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/81a4f513-8482-4ba3-9ba0-fc540dad9cd9">
<img width="941" alt="Screen Shot 2023-10-02 at 10 34 43 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/bc60879e-277e-4812-87da-cb140edc36cf">
</p>
<br /

To access MySQL database install the HeidiSQL client. Once Installed open HeidiSQL and click "New" at the bottom left. Then put the password that was created in the MySQL installer. Then Right-click unnamed -> Create New -> Database. Name the new database as osTicket.
</p>
<br /

14 .

<img width="905" alt="Screen Shot 2023-10-02 at 10 25 42 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/46a2a6ad-b361-473f-acf9-d23142eae420">
<img width="971" alt="Screen Shot 2023-10-02 at 10 52 38 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/7e6e752e-ef3f-4f7a-ae27-65113a9034fb">
<img width="865" alt="Screen Shot 2023-10-02 at 10 53 02 PM" src="https://github.com/Jaybelson/osticket-prereqs/assets/146674787/2e3a42f8-792e-465b-b482-0512ea86b410">
</p>
<br /

Finish filling out osTicket System settings, Admin user, and Database settings to complete osTicket installation. Note: MySQL database name was created in HeidiSQL. Once information is fully filled out click install and osTicket is officially installed.
