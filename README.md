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
Login to http://localhost/osTicket/scp/login.php, the local help desk page. <br/>

[Roles](https://docs.osticket.com/en/latest/Admin/Agents/Roles.html) are the permissions granted to Agents per Department that they have access to.
<br/>
<br/>
First, create a Role with all Permissions 
<p>
<img src="https://i.imgur.com/0M1crJ2.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click "Admin Panel" at the top right</p>
<p>
<img src="https://i.imgur.com/Fc9rlMe.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click "Agents" 
</p>
<p>
<img src="https://i.imgur.com/wflwidw.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click "Add New Role" 
</p>
<p>
<img src="https://i.imgur.com/tn6bTXm.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Name the new role
</p>
<p>
<img src="https://i.imgur.com/GAU42Gd.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Check all Permissions
</p>
<p>
<img src="https://i.imgur.com/H4GKFJx.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click "Add Role"
</p>
<p>
<img src="https://i.imgur.com/QvVA5DG.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click on Departments
</p>
<p>
<img src="https://i.imgur.com/xEZCaNU.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click on "Add New Deparment" 
</p>
<p>
<img src="https://i.imgur.com/XqEDWyA.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Name the new department "System Administrators"<br/>
Leave the other setting as default.</p>
<p>
<img src="https://i.imgur.com/B8ycHDD.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click "Create Department"
</p>
<p>
<img src="https://i.imgur.com/ZRHCX3a.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click on "Teams"
</p>
<p>
<img src="https://i.imgur.com/It1Xogm.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click on "Add New Team" at the bottom
</p>
<p>
<img src="https://i.imgur.com/CkY3sKx.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Name the team "Level II support" 
</p>
<p>
<img src="https://i.imgur.com/P2vW5v8.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click on "Members"
</p>
<p>
<img src="https://i.imgur.com/9JXh7AG.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click the drop down from select agent, and click you name, then click "Add"</p>

<p>
<img src="https://i.imgur.com/Ho7MR27.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click "Create Team" at the bottom </p>
<p>
<img src="https://i.imgur.com/kOERE2x.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click "Settings"</p>
<p>
<img src="https://i.imgur.com/II7dTRn.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click "Users"</p>

<p>
<img src="https://i.imgur.com/dvI2k4W.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Uncheck "Require registration and login to create tickets" <br/>
This allows customers to create tickets</p>

<p>
<img src="https://i.imgur.com/zWwhZ11.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click  "Save Changes"</p>
<h3>
Create Agents (Help Desk Workers) <h3/>
<p>
<img src="https://i.imgur.com/Gt3aLzT.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click  "Agents" (highlighted above) </p>

<p>
<img src="https://i.imgur.com/Ifvr6H5.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click  "Add New Agent"</p>

<p>
<img src="https://i.imgur.com/MhUk1DU.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Enter information for the new agent and click "Set Password" </p>

<p>
<img src="https://i.imgur.com/dJyiAHZ.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
The password may be changed through an email, on the spot, or require the agent to change at next login. <br/>
Uncheck "Send the agent a password reset email", chose a password and note it, and uncheck "Require a password at next login" </p>

<p>
<img src="https://i.imgur.com/xLj5qmn.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click on "Access" </p>

<p>
<img src="https://i.imgur.com/K050kMj.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Under "Primary Department", Click on Select Department and select the department "System Administrators" created earlier. <br/>
Click on "Select Role" and select the role "Supreme Admin" created earlier. <br/>
Under "Extended Access" click "Select Department" and click "Support"</p>

<p>
<img src="https://i.imgur.com/24QB7Zy.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Under "Extended Access" click "Select Role" and click "Supreme Admin" <br/>

<p>
<img src="https://i.imgur.com/IqucqPw.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Then click "Save Changes"</p>

<p>
<img src="https://i.imgur.com/eFDzhG7.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click on "Teams" </p>

<p>
<img src="https://i.imgur.com/DxKTIEZ.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click Select Team and select "Level II support" created earlier, and click "Add". </p>

<p>
<img src="https://i.imgur.com/dJyiAHZ.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click  "Create" at the bottom of the page</p>

<p>
<img src="https://i.imgur.com/MDHijxx.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click "Add New Agent" </p>

<p>
<img src="https://i.imgur.com/CoLEJrf.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Enter information for the new agent and click "Set Password"</p>

<p>
<img src="https://i.imgur.com/dJyiAHZ.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
The password may be changed through an email, on the spot, or require the agent to change at next login. <br/>
Uncheck "Send the agent a password reset email", chose a password and note it, and uncheck "Require a password at next login" and click "Set" </p>

<p>
<img src="https://i.imgur.com/m3BU8KD.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click "Create" at the bottom of the page </p>

<h3>
Create Agents (Customers) <h3/>
  
<p>
<img src="https://i.imgur.com/l3lvb93.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click "Agent" in the top right corner as seen above </p>

<p>
<img src="https://i.imgur.com/G3egXzV.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click  "Users" </p>

<p>
<img src="https://i.imgur.com/oPJRGiN.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click  "Add User" </p>

<p>
<img src="https://i.imgur.com/Tkmb9JN.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Enter the user's information and Click  "Add User" </p>

<p>
<img src="https://i.imgur.com/AZ8KpTM.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click  "Users" to add another user</p>

<p>
<img src="https://i.imgur.com/xrc0UyA.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click  "AddUser"</p>

<p>
<img src="https://i.imgur.com/EiNFxQz.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Enter the user's information and Click  "Add User" </p>

<h2>Create and SLA </h2>

<p>
<img src="https://i.imgur.com/Lqld3c8.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click  "Admin Panel" at the top right of the page</p>

<p>
<img src="https://i.imgur.com/ZPy4m7O.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click  "Manage"</p>

<p>
<img src="https://i.imgur.com/oD7zZBc.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click  "SLA"</p>

<p>
<img src="https://i.imgur.com/qgIQU5Z.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click  "Add New SLA Plan"</p>

<p>
<img src="https://i.imgur.com/ZDh4TEg.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Fill out the information needed, Name the SLA Plan, enter a grace period, and the schedule followed <br/>
Then Click  "Add Plan"</p>

<p>
<img src="https://i.imgur.com/gjpKOK4.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click  "Add New SLA Plan"</p>

<p>
<img src="https://i.imgur.com/flYDGkj.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Fill out the information needed, Name the SLA Plan, enter a grace period, and the schedule followed <br/>
Then Click  "Add Plan"</p>

<p>
<img src="https://i.imgur.com/nDXvYJo.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click  "Add New SLA Plan"</p>

<p>
<img src="https://i.imgur.com/qM3B4i9.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Fill out the information needed, Name the SLA Plan, enter a grace period, and the schedule followed <br/>
Then Click  "Add Plan"</p>

<p>
<img src="https://i.imgur.com/dKMgGlB.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click "Help Topics" </p>

<p>
<img src="https://i.imgur.com/DZEtKhu.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click "Add New Help Topic" </p>

<p>
<img src="https://i.imgur.com/DPOFvhs.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Enter the Help Topic Information and click "Add Topic" </p>

<p>
<img src="https://i.imgur.com/d14CEfI.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click "Help Topics" </p>

<p>
<img src="https://i.imgur.com/fCOdUmI.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click "Add New Help Topic" </p>

<p>
<img src="https://i.imgur.com/cIFYYOy.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Enter the Help Topic Information and click "Add Topic" </p>

<p>
<img src="https://i.imgur.com/XKxYdt8.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click "Help Topics" </p>

<p>
<img src="https://i.imgur.com/mUeGCZg.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click "Add New Help Topic" </p>

<p>
<img src="https://i.imgur.com/SyIijjy.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Enter the Help Topic Information and click "Add Topic" </p>

<p>
<img src="https://i.imgur.com/8OvoFFt.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click "Help Topics" </p>

<p>
<img src="https://i.imgur.com/BIutgR9.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Click "Add New Help Topic" </p>

<p>
<img src="https://i.imgur.com/wFlmr7F.png" height="65%" width="65%" alt="IIS"/>
</p>
<p>
Enter the Help Topic Information and click "Add Topic" </p>




