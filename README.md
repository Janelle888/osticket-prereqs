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
- Download and install PHP Manager for IIS
- Item 3
- Item 4
- Item 5

<h2>Installation Steps</h2>

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
