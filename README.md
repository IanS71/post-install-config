<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket. This project follows the prior pre-installation project starting with creating "Roles".<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Create Roles to define user permission
- Create Departments to outline group duties
- Configure Teams and Agents
- Configure SLA (Service Level Agreement)
- Configuring Help Topics

<h2>Configuration Step I - Roles</h2>

<p>
<img src="https://cdn.discordapp.com/attachments/677756436784218132/1095610767174275103/image.png"/>
</p>
<img src="https://cdn.discordapp.com/attachments/677756436784218132/1095415792490795088/image.png"/>
</p>
<p>
For my first line of action, I will create the Head Administrator role by navigating to the Admin Panel > Agents > Roles, this step ensures that management will be able to oversee and assist with any issues.
</p>
<br />

<p>
<h2>Creating Departments</h2>
<img src="https://cdn.discordapp.com/attachments/677756436784218132/1095419436082667580/image.png"/>
<p>
<h2>Creating Agents and Teams</h2>
Now I will create the 2 teams and my 2 agents by navigating to Agents > Roles/ Agents > Agents
- Level I Support

- Level II Support
</p>
<img src="https://cdn.discordapp.com/attachments/677756436784218132/1095419877147299920/image.png"/>
</p>
<p>
Level I Support will be responsible for simple tasks such as password resets or general information. 

Deep issues in the infrastructure of the website will be escalated to Level II Support for their evaluation.
</p>
<img src="https://cdn.discordapp.com/attachments/677756436784218132/1095421033554657391/image.png"/>

For my Head Administrator I will create Marlon Robinson, and Dominic Clark as my Level I support (names used for demo purposes do not reflect real people)


<p>
<h2>Configuring SLA (Service Level Agreement)</h2>
<p>
<img src="https://cdn.discordapp.com/attachments/677756436784218132/1095422542707167372/image.png"/>

</p>
<p>
Next, I'll configure SLA levels, with SEV-A being the most urgent usually used in cases of widespread service disruption, SEV-B will be utilized for deeper issues on a smaller scale, and SEV-C will be used for everything else.
</p>
<h2>Help Topics</h2>
<br />
<img src="https://cdn.discordapp.com/attachments/677756436784218132/1095430358037712907/image.png"/>
</p>
Help topics are used to guide what information is gathered from Users and how tickets are routed or assigned.

- Now with all of these steps, the Rainbow Help Desk is prepared to take incoming requests from clients 
