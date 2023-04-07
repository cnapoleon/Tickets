# osTickets Ticket Lifecycle
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

- Install / Enable IIS in windows with CGI
- Download and Install programs for osTicket
     - PHP Manager for IIS,  Rewrite Module, PHP 7.3.8,  Visual C++ redistributeable, MySQL.
- Install osTicket
- 

<h2>Installation Steps</h2>

<p>
I started off the lab by creating a virtual machine in Microsoft Azure. I connected to the VM using Windows Remote Desktop. Once inside of the VM I located the Internet information services inside of the control panel.
</p>

<p>
<img src="https://i.imgur.com/bEeAUXn.png" height="80%" width="80%" alt="Internet Infromation Services"/>
</p>

<p>
From there, I downloaded it and installed PHP manager for IIS. I downloaded a rewrite module. I created a directory in my C folder for PHP. Continuing, I downloaded the latest version of PHP into my newly created folder in my C drive directory. To get PHP to work I downloaded and installed C++ redistributable, and mySQL
</p>
<br />

<p>
<img src="https://i.imgur.com/pKINoTu.png" height="80%" width="80%" alt="IIS with downloaded software"/>
</p>
<p>
Now downloading and installing osTicket. I extracted and copied the “upload” folder to c:\inetpub\wwwroot. Then within c:\inetpub\wwwroot i renamed the folder “upload” to “osTicket”. In IIS to launch osTicket I went to sites then to default the to ‘Browse *80’.
</p>
<br />
