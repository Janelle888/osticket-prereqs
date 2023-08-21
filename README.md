<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

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
- Create Directory C: PHP
- Item 5

<h2>IIS Installation Steps</h2>

<p>

![image](https://github.com/Janelle888/osticket-prereqs/assets/142438143/6d4913fe-9d69-4c13-9c82-d4abe57c8863)


</p>
<p>
Press Windows and "R" on your keyboard, in the window search "control" and then press enter. On the first window select "program" and then " Turn Windows features on or off".
</p>
<br />

<p>

![image](https://github.com/Janelle888/osticket-prereqs/assets/142438143/c56b1983-a64d-43c4-a067-6a3c9fc3ad82)


</p>
<p>
In this window click on the box next to IIS(Internet information Services ), now expand this category by clicking the plus next to it. Go to "World Wide Web Services" and expand this category, then go to "Application Development Features" and turn on "CGI" after turning that on minimize this category and open "Common HTTP Features". In "Common HTTP Features" click the two unchecked boxes "HTTP Redirection" and "WebDAV Publishing".
</p>
<br />

<p>
  
![image](https://github.com/Janelle888/osticket-prereqs/assets/142438143/3b265151-381b-4a3b-b9e6-ca83f1cba41b)

</p>


<p>

![image](https://github.com/Janelle888/osticket-prereqs/assets/142438143/27ec9dda-01d4-4e21-883c-582e3ba3e88f)


<p>
<p>
Press okay and let those install. After installation go to your browser and in the search bar type in "127.0.0.1" If you have correctly installed IIS then the IIS page should appear. </a>👍</h1
<p>

![image](https://github.com/Janelle888/osticket-prereqs/assets/142438143/98fa1ed1-2437-4f9d-bcad-cd9a50c2f237)

<p>

<h2>IIS Installation Steps</h2>
<p>
  
Download and Install [PHP Manager](https://drive.google.com/file/d/1RHsNd4eWIOwaNpj3JW4vzzmzNUH86wY_/view?usp=share_link) completely.
<p>

![image](https://github.com/Janelle888/osticket-prereqs/assets/142438143/370ac715-0732-4a1f-98b4-d7bbabb9a4c2)


<p>
  
<p>
  
Download and Install [Rewrite Module](https://drive.google.com/file/d/1tIK9GZBKj1JyUP87eewxgdNqn9pZmVmY/view?usp=share_link) completely.
<p>

![image](https://github.com/Janelle888/osticket-prereqs/assets/142438143/a0f06db4-206e-4e4a-85a4-8a7aecb8c586)

<p>

<p>
  
 Go to your "C Drive " and create a folder labled PHP
<p>

![image](https://github.com/Janelle888/osticket-prereqs/assets/142438143/9f695f02-c1fd-4d53-a1af-363376f2d9a2)


<p>

Download [PHP 7.3.8](https://drive.google.com/file/d/1snNMtLdCOpMtkCyD4mvl9yOOmvVIp9fP/view?usp=share_link) it will take a moment to download. Go to your download folder and locate the "PHP 7.3.8 zip file". Right click on this folder and select "Extract All" extract this folders files into the "PHP" folder in your "C Drive".

<p>

![image](https://github.com/Janelle888/osticket-prereqs/assets/142438143/c9f949c5-7435-477e-a177-9ec815788e8c)

<p>

