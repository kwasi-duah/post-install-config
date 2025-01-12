<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" height="75%" width="100%" alt="osTicket logo" />
</p>

<h1>osTicket - Easy Setup and Configuration</h1>
<p>This guide walks through setting up and configuring the osTicket Help Desk System step by step. Let's make it simple!</p>

<h2>Tools and Technology Used</h2>
<ul>
  <li>Microsoft Azure (Virtual Machines)</li>
  <li>Remote Desktop</li>
  <li>Internet Information Services (IIS)</li>
</ul>

<h2>Operating System Used</h2>
<ul>
  <li>Windows 10</li>
</ul>

<h2>Goals for Setting Up osTicket</h2>
<ul>
  <li>Set up Roles (Who can do what?)</li>
  <li>Create Departments (Organize teams!)</li>
  <li>Build Teams (Group workers!)</li>
  <li>Add Agents (The helpers)</li>
  <li>Add Users (The customers)</li>
  <li>Set SLAs (How fast to fix things?)</li>
  <li>Make Help Topics (Quick ticket categories)</li>
</ul>

<h2>Step-by-Step Instructions</h2>

<h3 align="center">Set Up Roles</h3>
<p>
  Go to <strong>Admin Panel -> Agents -> Roles</strong>.<br />
  Create a role like "Supreme Admin" to give full permissions.<br />
</p>
<p>
  <img src="https://i.imgur.com/SXpTf20.png" height="75%" width="100%" alt="Roles setup example" />
</p>

<h3 align="center">Create Departments</h3>
<p>
  Go to <strong>Admin Panel -> Agents -> Departments</strong>.<br />
  Add departments like "System Administrators" to organize work.<br />
</p>
<p>
  <img src="https://i.imgur.com/83gWQsO.png" height="75%" width="100%" alt="Department setup example" />
</p>

<h3 align="center">Build Teams</h3>
<p>
  Go to <strong>Admin Panel -> Agents -> Teams</strong>.<br />
  Create teams like "Level II Support" for special jobs.<br />
</p>
<p>
  <img src="https://i.imgur.com/BnPrcDH.png" height="75%" width="100%" alt="Team setup example" />
</p>

<h3 align="center">Allow Everyone to Create Tickets</h3>
<p>
  Go to <strong>Admin Panel -> Settings -> User Settings</strong>.<br />
  Make sure the option "Require registration and login to create tickets" is NOT checked.<br />
</p>
<p>
  <img src="https://i.imgur.com/QsJjOuM.png" height="75%" width="100%" alt="Ticket creation settings" />
</p>

<h3 align="center">Add Agents (Workers)</h3>
<p>
  Go to <strong>Admin Panel -> Agents -> Add New</strong>.<br />
  Add agents like "Jane Doe" and "John Doe" to help customers.<br />
</p>
<p>
  <img src="https://i.imgur.com/ujpOdKM.png" height="75%" width="100%" alt="Agent setup example" />
</p>

<h3 align="center">Add Users (Customers)</h3>
<p>
  Go to <strong>Admin Panel -> Users -> Add New</strong>.<br />
  Add users like "Ken User" to submit tickets.<br />
</p>
<p>
  <img src="https://i.imgur.com/vbPd3uK.png" height="75%" width="100%" alt="User setup example" />
</p>

<h3 align="center">Set Up SLAs (Response Time Rules)</h3>
<p>
  Go to <strong>Admin Panel -> Manage -> SLA</strong>.<br />
  Create rules like:<br />
  <ul>
    <li><strong>Sev-A</strong>: 1 hour (Urgent issues)</li>
    <li><strong>Sev-B</strong>: 4 hours</li>
    <li><strong>Sev-C</strong>: 8 hours (Normal issues)</li>
  </ul>
</p>
<p>
  <img src="https://i.imgur.com/6AAF3Ju.png" height="75%" width="100%" alt="SLA setup example" />
</p>

<h3 align="center">Create Help Topics</h3>
<p>
  Go to <strong>Admin Panel -> Manage -> Help Topics</strong>.<br />
  Add common topics like:<br />
  <ul>
    <li>Business Critical Outage</li>
    <li>Personal Computer Issues</li>
    <li>Equipment Request</li>
    <li>Password Reset</li>
  </ul>
</p>
<p>
  <img src="https://i.imgur.com/Xdhp63v.png" height="75%" width="100%" alt="Help topics setup example" />
</p>

<h3>You're Done!</h3>
<p>
  Your osTicket is now fully configured and ready to use. <br />
  Remember to practice solving and triaging tickets—this is an important skill for help desk specialists.<br />
</p>
<p>Thank you for following along, and happy ticketing!</p>
