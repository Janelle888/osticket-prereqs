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

- Install / Enable IIS in Windows WITH CGI and Common HTTP Features
- Download and Install PHP Manager for IIS
- Download and Install Rewrite Module
- Create New PHP Folder in Directory C: Drive
- Unzip and Extract PHP Files into New PHP Folder
- Download VC Redistributable
- Download MYSQL Server
- Open IIS as an Admin
- Register PHP from within IIS
- Install osTicket v1.15.8
- Set up osTicket

<h2>IIS Installation Steps</h2>

<p>

![image](https://github.com/Janelle888/osticket-prereqs/assets/142438143/6d4913fe-9d69-4c13-9c82-d4abe57c8863)


</p>
<p>
  
- Press Windows and "R" on your keyboard, in the window search "control" and then press enter. On the first window select "program" and then " Turn Windows features on or off".
</p>
<br />

<p>

![image](https://github.com/Janelle888/osticket-prereqs/assets/142438143/c56b1983-a64d-43c4-a067-6a3c9fc3ad82)


</p>
<p>

- In this window click on the box next to IIS(Internet information Services ), now expand this category by clicking the plus next to it. Go to "World Wide Web Services" and expand this category, then go to "Application Development Features" and turn on "CGI" after turning that on minimize this category and open "Common HTTP Features". In "Common HTTP Features" click the two unchecked boxes "HTTP Redirection" and "WebDAV Publishing".
</p>
<br />

<p>
  
![image](https://github.com/Janelle888/osticket-prereqs/assets/142438143/3b265151-381b-4a3b-b9e6-ca83f1cba41b)

</p>


<p>

![image](https://github.com/Janelle888/osticket-prereqs/assets/142438143/27ec9dda-01d4-4e21-883c-582e3ba3e88f)


<p>
<p>
  
- Press okay and let those install. After installation go to your browser and in the search bar type in "127.0.0.1" If you have correctly installed IIS then the IIS page should appear. </a>👍
<p>
<br />

<p>

![image](https://github.com/Janelle888/osticket-prereqs/assets/142438143/98fa1ed1-2437-4f9d-bcad-cd9a50c2f237)

<p>
<br />
  
<p>

<p>
  
- Download and Install [PHP Manager](https://drive.google.com/file/d/1RHsNd4eWIOwaNpj3JW4vzzmzNUH86wY_/view?usp=share_link) completely.
<p>

![image](https://github.com/Janelle888/osticket-prereqs/assets/142438143/370ac715-0732-4a1f-98b4-d7bbabb9a4c2)


<p>
<br />

<p>
  
- Download and Install [Rewrite Module](https://drive.google.com/file/d/1tIK9GZBKj1JyUP87eewxgdNqn9pZmVmY/view?usp=share_link) completely.
<p>

![image](https://github.com/Janelle888/osticket-prereqs/assets/142438143/a0f06db4-206e-4e4a-85a4-8a7aecb8c586)

<p>
<br />
  
<p>
  
- Go to your "C Drive " and create a folder labled PHP
<p>

![image](https://github.com/Janelle888/osticket-prereqs/assets/142438143/9f695f02-c1fd-4d53-a1af-363376f2d9a2)


<p>
<br />

<p>
  
- Download [PHP 7.3.8](https://drive.google.com/file/d/1snNMtLdCOpMtkCyD4mvl9yOOmvVIp9fP/view?usp=share_link) it will take a moment to download. Go to your download folder and locate the "PHP 7.3.8 zip file". Right click on this folder and select "Extract All" extract this folders files into the "PHP" folder in your "C Drive".

<p>

![image](https://github.com/Janelle888/osticket-prereqs/assets/142438143/c9f949c5-7435-477e-a177-9ec815788e8c)

<p>

![image](https://github.com/Janelle888/osticket-prereqs/assets/142438143/9dad33e2-caa5-4605-a434-73fdedb860a1)

<p>
<br />

<p>

- Download [VC Redistributable](https://drive.google.com/file/d/1s1OsGF3-ioO0_9LYizPRiVuIkb3lFJgH/view?usp=share_link) completely.
  <p>

  ![image](https://github.com/Janelle888/osticket-prereqs/assets/142438143/80920d5d-622b-4d2c-9de6-978d40dcd911)

  <p>
  <br />

  <p>

- Download [MySQL Server](https://drive.google.com/file/d/1_OWh9p7VQLcrB0q_V7qT8yHl0xo5gv7z/view?usp=share_link) when prompted make sure you choose a "Typical" download. Once the "FInished" screen appears check the box that says "Launch the MYSQL Instance"
  <p>

![image](https://github.com/Janelle888/osticket-prereqs/assets/142438143/40b0690d-eb0a-4364-b91d-ac88854255c9)

<p>
  
  ![image](https://github.com/Janelle888/osticket-prereqs/assets/142438143/5141589e-e2a5-4c78-bce2-5bc7829c97a2)

<p>
<br />
  
- Begin to run the program and select "Standard Configuration", press next untill you get to " Configure server instance" our user name will be "root", enter a password. <b>Make sure you remember this password!</b>

<p>

![image](https://github.com/Janelle888/osticket-prereqs/assets/142438143/aed886f1-bb3b-4ac6-ba9a-16a8331f2295)

<p>

![image](https://github.com/Janelle888/osticket-prereqs/assets/142438143/af511134-6382-45f0-80df-549ac54a7766)

<p>
<br \>
  
- Press "Next", "Execute" and then "Finish"

  <p>
  <br \>
- Go to the start menu on your computer and search IIS the right click and run the program as an administrator.

 <p>

![image](https://github.com/Janelle888/osticket-prereqs/assets/142438143/cfbd2fa7-5e7c-4a3a-a7dd-a687cff95405)

<p>
<br \>

- When the window appears double click "PHP Manager"

<p>

  ![image](https://github.com/Janelle888/osticket-prereqs/assets/142438143/99bd5f16-8f51-4705-afea-d0fe9b287f01)

  <p>

- In the window that pops up you want to "Register new PHP Version", go to the "C: Drive" into the "PHP" folder that we created and

  <p>

![image](https://github.com/Janelle888/osticket-prereqs/assets/142438143/786e0929-d192-41d1-b7f5-28bbf840c247)

<p>
