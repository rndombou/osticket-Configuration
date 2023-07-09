<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Configuration


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- STEP 1 - Logging Into osTicket
- STEP 2 - Configure Departments
- STEP 3 - Setting Up Users and Agents
- STEP 4 - Setting Up Teams
- STEP 5 - Settting Up Service Level Agreements
- STEP 6 - Creating Help Topics

<h2>Installation Steps</h2>

osTicket was installed on a virtual machine through Azure, the installation instructions are not included in this tutorial as STEP 1 begins with the software already installed. 

STEP 1 – LOGGING INTO OSTICKET
<p>
Go to portal.azure.com to connect to the Virtual Machine that was created to look up the IP address and then use remote desktop to log into the VM. Then we open osTicket on the webbrowser with localhost/osTicket/. When we select "Settings" we see what is shwon in EXAMPLE 1A.
<p>
EXAMPLE 1A
<p>
<img src="https://i.imgur.com/sKTIgXc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We will add agents in the "Agents" section while being logged in as an admin. We will then add information and preview items.
</p>
EXAMPLE 1B
<p>
<img src="https://i.imgur.com/iHp42vC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
STEP 2 – CONFIGURE DEPARTMENTS
<p>
<br />
We can configure departments by selecting the “Departments” button while still in the “Agents” tab. We can then “Add New Department”, see EXAMPLE 2A and EXAMPLE 2B.
</p>
<br />
EXAMPLE 2A
<p>
<img src="https://i.imgur.com/mgdybmP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
EXAMPLE 2B
<p>
<img src="https://i.imgur.com/Qs47jVs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
STEP 3 - SETTING UP USERS AND AGENTS
</p>
<br />
In the users tab a few agents have been created to populate this project. In EXAMPLE 3A John Doe has been created along with his employee information, access, permissions, and teams. 
</p>
<br />
EXAMPLE 3A
<p>
<img src="https://i.imgur.com/iGWlgTG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Additionally by going to Admin Panel>Settings>User Settings we can allow anyone to create tickets by having the item unchecked named “Require registration and login to create tickets”. 
To add users (non-IT employees) go to the “Agent Panel” by selecting the icon on the top right of the screen. Here we can enter employees into the system. 
</p>
<br />
EXAMPLE 3B
<p>
<img src="https://i.imgur.com/6GuiYLr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<br />
STEP 4 – SETTING UP TEAMS
</p>
<br />
We can set up team by continuing to be in the admin panel>Agents>Teams as seen in EXAMPLE 4A. We can select “Add New Team” button to add a new team. 
</p>
<br />
EXAMPLE 4A
<p>
<img src="https://i.imgur.com/ZodIGoN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<br />
STEP 5 – SETTING UP SLA
</p>
<br />
Go to the “Admin Panel” at the top right of the page then select the tab Manage>SLA.
</p>
<br />
EXAMPLE 5A
<img src="https://i.imgur.com/pPfKjZx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In EXAMPLE 5B we have created different SLA’s for the tickets depending on their severity. 
</p>
<br />
EXAMPLE 5B
<img src="https://i.imgur.com/Xo9ml9w.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
STEP 6 – CREATING HELP TOPICS
</p>
<br />
Going to the tab “Manager” we see “Help Topics” display. We can add help topics to be unique to the business we are supporting, see EXAMPLE 6A.
</p>
<br />
EXAMPLE 6A
<img src="https://i.imgur.com/HHXG23M.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Below we see several additional Help Topics have been added to the list such as Business Critical Outage, Personal Computer Issues, Equipment Request, and Password Reset in EXAMPLE 6B.
</p>
<br />
EXAMPLE 6B
<img src="https://i.imgur.com/Wh0eoDI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This concludes this project in setting up the osTicketing system which will allow for a good starting framework.
</p>
<br />
END OF TUTORIAL
