<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/m81F0ju.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the Admin panel click Agents.
</p>
<br />

<p>
<img src="https://i.imgur.com/5z5ZIPN.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Select Roles.
</p>
<br />

<p>
<img src="https://i.imgur.com/RJ80sAZ.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click add new roles.
</p>
<br />

<p>
<img src="https://i.imgur.com/ZDQJRa2.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Name the new role Supreme Admin and click the permissions tab.
</p>
<br />

<p>
<img src="https://i.imgur.com/Z4xLk51.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Check all boxes under the Tickets section and select Tasks.
</p>
<br />

<p>
<img src="https://i.imgur.com/BqGfy5m.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Check all boxes under the Tasks section and click add role.
</p>
<br />

<p>
<img src="https://i.imgur.com/7c3H6PG.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Supreme Admin should now be in the roles section after creation.
</p>
<br />

<p>
<img src="https://i.imgur.com/eREwzCq.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Select Departments and  click add new department.
</p>
<br />


<p>
<img src="https://i.imgur.com/o4OCLsx.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Name new department System Administrators and click add Dept.
</p>
<br />

<p>
<img src="https://i.imgur.com/UwV5Cid.png height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
System Administrators should be in the Departments section after creation.
</p>
<br />

<p>
<img src="https://i.imgur.com/SeUsHwC.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click on the Teams tab and select add new team.
</p>
<br />

<p>
<img src="https://i.imgur.com/BFaE2rF.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Name the new team Level II Support and click on the members tab.
</p>
<br />

 <p>
<img src="https://i.imgur.com/6FxfKD7.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Add yourself as a team member and click create team.
</p>
<br /> 
                                                                                                   
<p>
<img src="https://i.imgur.com/gy6T7a6.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Level II support is successfully created.
</p>
<br />                                                                                                 

                                                                                                   <p>
<img src="https://i.imgur.com/5z5ZIPN.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the Agent subsection click add new agent.
</p>
<br /> 

<img src="https://i.imgur.com/2jAJRhJ.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Fill in the information of the new agent and select the access tab.
</p>
<br /> 
                                                                                                   
<img src="https://i.imgur.com/U3bCemE.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the access tab give the new agent System Admin and Supreme Admin and select the Teams tab.
</p>
<br />

<img src="https://i.imgur.com/QtIHe83.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the Teams tab add the new Agent as a level ii support and click create.
</p>
<br />
                                                                                                    
<img src="https://i.imgur.com/Xf7i9Vx.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
The new Agent is now successfully created.
</p>
<br />
                                                                                                   
<img src="https://i.imgur.com/5z5ZIPN.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the Agent subsection click add new agent again.
</p>
<br /> 
                                                                                                   
<img src="https://i.imgur.com/7SusNMd.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Fill in the information for agent 2 and select the access tab.
</p>
</p>
  
<img src="https://i.imgur.com/CluXANO.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the access tab give the new agent Support, view only and Support Admin and click create.
</p>
</p>                                                                                                   
<br />
                                                                                                   
<img src="https://i.imgur.com/OxhglpU.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
The new Agent is now successfully created.
</p>
</p>                                                                                                   
<br />                                                                                                    

<img src="https://i.imgur.com/AfnUkNt.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click the Agent panel and select the users tab. Click add user.
</p>
</p>                                                                                                   
<br /> 

<img src="https://i.imgur.com/u6X48cG.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Fill in the email address and full name of the new user. Click add user
</p>
</p>                                                                                                   
<br />
                                                                                                   
<img src="https://i.imgur.com/68ghSuh.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
The new user is successfully created.
</p>
</p>                                                                                                   
<br />                                                                                                  

<img src="https://i.imgur.com/1dD9IFm.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go back to the users tab and select add user again. Fill in the email address of another user and click add user
</p>
</p>                                                                                                   
<br /> 
                                                                                                   
<img src="https://i.imgur.com/ZyOagWg.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
The new user is successfully created.
</p>
</p>                                                                                                   
<br />  
                                                                                                   
<img src="https://i.imgur.com/iRppNRa.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the Admin Panel select the manage tab. Select SLA and click add new SLA plan.
</p>
</p>                                                                                                   
<br /> 
                                                                                                  
<img src="https://i.imgur.com/uMxjG7K.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Name the new SLA Plan SEV-A, fill out the details and add plan.
</p>
</p>                                                                                                   
<br />   
                                                                                                   
<img src="https://i.imgur.com/SnttfRk.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
SEV-A should be successfully created.
</p>
</p>                                                                                                   
<br />                                                                                                    

<img src="https://i.imgur.com/y26LB4p.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
After SEV-A has been successfully created click on add new SLA plan. Name the SLA plan SEV-B, fill in the details and add plan.
</p>
</p>                                                                                                   
<br />      
                                                                                                   
<img src="https://i.imgur.com/97d83Eq.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
SEV-B should be successfully created.
</p>
</p>                                                                                                   
<br />                                                                                                     

<img src="https://i.imgur.com/JbMoLdD.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
After SEV-B has been successfully created click on add new SLA plan. Name the SLA plan SEV-C, fill in the details and add plan.
</p>
</p>                                                                                                   
<br />                                                                                                      
  
<img src="https://i.imgur.com/SVGtE5o.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
SEV-C should be successfully created.
</p>
</p>                                                                                                   
<br />                                                                                                     
                                                                
<img src="https://i.imgur.com/3AafJPv.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
After SEV-C has been successfully select Hot Topics.
</p>
</p>                                                                                                   
<br />
                                                                                                   
<img src="https://i.imgur.com/aXJ6Fb5.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click Add New Hot Topic. Name the Hot Topic Business Critical Outage. Fill in the information and add topic.
</p>
</p>                                                                                                   
<br />                                                                                                 

<img src="https://i.imgur.com/jKInhEd.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
After Business Critical Outage is created select Hot Topics. Click Add New Topic. Name the Hot Topic Personal Computer Issues. Fill in the information and add topic
</p>
</p>                                                                                                   
<br /> 
                                                                                                   
<img src="https://i.imgur.com/IFt07SX.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
After Personal Computer Issues is created select Hot Topics. Click Add New Topic. Name the Hot Topic Equipment Requests. Fill in the information and add topic
</p>
</p>                                                                                                   
<br /> 
                                                                                                   
<img src="https://i.imgur.com/O6LcVQ8.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
After Equipment Requests is created select Hot Topics. Click Add New Topic. Name the Hot Topic Password Reset. Fill in the information and add topic
</p>
</p>                                                                                                   
<br />                                                                                                         

This conclude the post-install configuration of the open-source help desk ticketing system osTicket .                                                                                                   
                                                                                                   
                                                                                                   
                                                                                                   
                                                                                                   
                                                                                                   
                                                                                                   
                                                                                                   
                                                                                                   
                                                                                                   
                                                                                                   
                                                                   
