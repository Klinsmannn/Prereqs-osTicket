<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation 🎫</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com/watch?v=K7T_JjvEamg)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create Resource group in Azure with Virtual Machine
- Enable IIS (Internet Information Services)
- Install,Register and Enable Required Programs
- Register OS
- Log in and Claim Ticket

<h2>Installation Steps</h2
<p>
<img src="https://github.com/Klinsmannn/osticket-prereqs/assets/146140975/1cf80ad1-1ab7-4f51-bad6-16261becb755">  <p></p>   <img src="https://github.com/Klinsmannn/osticket-prereqs/assets/146140975/09a27be6-ee54-4e41-80a5-628b4fbeb5ea">


</p>
<p>
Go to the Azure Portal and create your Virtual Machine. You can make your resource group as you create your virtual machine. Copy the public ip address of your virtual machine and log in Remotely to Windows Remote Desktop Connection. If you have Mac or other OS than download windows remote desktop app.  
</p>
<br />

<p>
<img src="https://github.com/Klinsmannn/osticket-prereqs/assets/146140975/5345f981-0332-4b81-800f-13560807391b">
</p>
<p>
  Go to start menu and go into control panel. In control panel go to programs and click on Windows features on or off. From there you can enable World Wide Web Services -> Application Development Features ->
[X] CGI
[X] Common HTTP Features
Internet Information Services -> Web Management Tools -> IIS Management Console
	[X] IIS Management Console

</p>
<br />

<p>
<img src="https://github.com/Klinsmannn/Prereqs-osTicket/assets/146140975/557e7920-2d27-401f-9cb4-7a5a1b121b53">
</p>
<p>
⬆️Install, Configure, and Register required programs that are needed to run osTicket. Heidi SQL, PHP Manager for IIS, Rewrite Module, My SQL, VC Redist, and then the actual osTicket itself. These versions might need updating.	
</p>
<br />

<p>
<img src="https://github.com/Klinsmannn/Prereqs-osTicket/assets/146140975/c7f216a6-cbd2-47d9-8cda-f8a7c9f83a19">
<img src="https://github.com/Klinsmannn/Prereqs-osTicket/assets/146140975/ac28f3ca-5835-4b8a-81a7-922710dbafd8">
</p>
<p>
Install your osTicket as either an Admin or Client. Before installing make sure My SQL is registered at the bottom of the page before installing osTicket or it wont let you move on to the next page. Dont forget username and password for both SQL and osTicket. Click Install
</p>
<br />

<p>
<img src="https://github.com/Klinsmannn/Prereqs-osTicket/assets/146140975/90896273-231c-4b1c-98be-78cd5b9359bd">
</p>
<p>
Go into your Osticket as either the end user to make your ticket for whatever troubleshooting issue your having or as an Agent to resolve tickets for the customer. As much information as possible is appreciated like the time of day, whos affected, when was issued first noticed, were there any updates, severity of SLA  etc...
OsTicket is free open source and you shouldn't have to pay.
