<p align="center">
  <img src="https://i.imgur.com/e7WeUgn.png" alt="Image Description">
</p>
<h1>osTicket - Post Installation Configuration</h1>
This tutorial outlines configuration post installation of the open-source help desk ticketing system osTicket.<br />
<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS) with CGI

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- osTicket installed
<br/>
[Roles](https://docs.osticket.com/en/latest/Admin/Agents/Roles.html) are the permissions granted to Agents per Department that they have access to.
<br/>
<br/>
First, create a Role with all Permissions 
<p>
<img src="https://i.imgur.com/0M1crJ2.png" height="30%" width="30%" alt="IIS"/>
</p>
<p>
Click "Admin Panel" at the top right</p>
<p>
<img src="https://i.imgur.com/Fc9rlMe.png" height="30%" width="30%" alt="IIS"/>
</p>
<p>
Click "Agents" 
</p>
<p>
<img src="https://i.imgur.com/wflwidw.png" height="30%" width="30%" alt="IIS"/>
</p>
<p>
Click "Add New Role" 
</p>
<p>
<img src="https://i.imgur.com/tn6bTXm.png" height="30%" width="30%" alt="IIS"/>
</p>
<p>
Name the new role
</p>
<p>
<img src="https://i.imgur.com/GAU42Gd.png" height="30%" width="30%" alt="IIS"/>
</p>
<p>
Check all Permissions
</p>
<p>
<img src="https://i.imgur.com/H4GKFJx.png" height="30%" width="30%" alt="IIS"/>
</p>
<p>
Click "Add Role"
</p>
<p>
<img src="https://i.imgur.com/QvVA5DG.png" height="30%" width="30%" alt="IIS"/>
</p>
<p>
Click on Departments
</p>
<p>
<img src="https://i.imgur.com/xEZCaNU.png" height="30%" width="30%" alt="IIS"/>
</p>
<p>
Click on "Add New Deparment" 
</p>
<p>
<img src="https://i.imgur.com/XqEDWyA.png" height="30%" width="30%" alt="IIS"/>
</p>
<p>
Name the new department "System Administrators"<br/>
Leave the other setting as default.</p>
<p>
<img src="https://i.imgur.com/B8ycHDD.png" height="30%" width="30%" alt="IIS"/>
</p>
<p>
Click "Create Department"
</p>
<p>
<img src="https://i.imgur.com/ZRHCX3a.png" height="30%" width="30%" alt="IIS"/>
</p>
<p>
Click on "Teams"
</p>
<p>
<img src="https://i.imgur.com/It1Xogm.png" height="30%" width="30%" alt="IIS"/>
</p>
<p>
Click on "Add New Team" at the bottom
</p>
<p>
<img src="https://i.imgur.com/CkY3sKx.png" height="30%" width="30%" alt="IIS"/>
</p>
<p>
Name the team "Level II support" 
</p>
<p>
<img src="https://i.imgur.com/P2vW5v8.png" height="30%" width="30%" alt="IIS"/>
</p>
<p>
Click on "Members"
</p>
<p>
<img src="https://i.imgur.com/9JXh7AG.png" height="30%" width="30%" alt="IIS"/>
</p>
<p>
Click the drop down from select agent, and click you name, then click "Add"</p>

<p>
<img src="https://i.imgur.com/Ho7MR27.png" height="30%" width="30%" alt="IIS"/>
</p>
<p>
Click "Create Team" at the bottom </p>
<p>
<img src="https://i.imgur.com/kOERE2x.png" height="30%" width="30%" alt="IIS"/>
</p>
<p>
Click "Settings"</p>
<p>
<img src="https://i.imgur.com/II7dTRn.png" height="30%" width="30%" alt="IIS"/>
</p>
<p>
Click "Users"</p>

<p>
<img src="https://i.imgur.com/dvI2k4W.png" height="30%" width="30%" alt="IIS"/>
</p>
<p>
Uncheck "Require registration and login to create tickets" </p>

<p>
<img src="https://i.imgur.com/zWwhZ11.png" height="30%" width="30%" alt="IIS"/>
</p>
<p>
Click  "Save Changes"</p>
<h3>
Create Agents (Help Desk Workers) <h3/>
  https://i.imgur.com/
<p>
<img src="https://i.imgur.com/Gt3aLzT.png" height="30%" width="30%" alt="IIS"/>
</p>
<p>
Click  "Agents" (highlighted above) </p>

<p>
<img src="https://i.imgur.com/Ifvr6H5.png" height="30%" width="30%" alt="IIS"/>
</p>
<p>
Click  "Add New Agent"</p>

<p>
<img src="https://i.imgur.com/MhUk1DU.png" height="30%" width="30%" alt="IIS"/>
</p>
<p>
Enter information for the new agent and click "Set Password" </p>

<p>
<img src="https://i.imgur.com/dJyiAHZ.png" height="30%" width="30%" alt="IIS"/>
</p>
<p>
The password may be changed through an email, on the spot, or require the agent to change at next login. <br/>
Uncheck "Send the agent a password reset email", chose a password and note it, and uncheck "Require a password at next login" </p>

<p>
<img src="https://i.imgur.com/zWwhZ11.png" height="30%" width="30%" alt="IIS"/>
</p>
<p>
Click  "Save Changes"</p>

<p>
<img src="https://i.imgur.com/zWwhZ11.png" height="30%" width="30%" alt="IIS"/>
</p>
<p>
Click  "Save Changes"</p>


