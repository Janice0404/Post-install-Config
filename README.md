# Post-install-Config<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1
- Item 2
- Item 3


<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
When discussing Os ticket configuaration, one would look at the mutiple roles and permissions granted with a agency to employees per that particular department, that would allow the employees access to certain admin roles, agents, etc. Within Os tickets each role has a set of specific permissions that can be checked/unchecked for employees given that role in association with their department they have access to. There are several roles that an employee can have such as Assign, create,close,delete, edit, completing task etc. Within the permissions tab of the employee Os ticket profile there is a section that the employee has, that allows functionality within the help desk which are not department specific access.  Areas such as the User Directory, Organization, and Knowledge Base can be limited per employee for need to know bases. This includes the ability to search for and see the ticket metadata for tickets the Agent does not have access to, the email ban list, and other staff statistics on the dashboard. User are ticket owners of the tickets in the help desk. When a ticket is created the help desk associate the ticket with the employees email address in the user directory of the helpesk.
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/116759326/199104775-2fa6163a-9749-468c-b87c-30242deb9108.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
There are mutiple departements that tickets are routed through departments in the help desk, there are also many settings that can be set for each department within a agency. There are five main  departements Parent,Status,Active, Archived, & Disable. These departments all play a important role. Parent dept is used as a nesting departement. Status dept determine its visibility as well as if tickets can be routed to the specific department. Active dept available when transferring tickets to mutiple dept. Archived dept is no longer in use and cannot be selected to transfer any tickets. Disable dept no tickets can be sent to this dept.  These departements all have (SLA), that they must adhere to. (SLA) Service Level Agreement for tickets routed to department within a agency. SLA are the expected amount of time (in hours) that a ticket is expected to be closed once opened via Os ticket. If the ticket is not closed in the allotted amount of time, it will then be Overdue, at this point immediately follow up will be needed. SLA basically just ensures that all help desk tickets are being worked in a timley manner. There should be a great deal of understanding SLA and the importance they play within a agnecy or organzation success. There are three types of SLAs customer, internal, and multilevel SLA. You can also use SLA performance metrics to measure the performance which is important. There  are diffrent Service levels such as Sev -A (1 hour, 24/7), Sev-B (4 hours, 24/7), and Sev-C (8 hours, business hours) and teses are all turn around times for SLA.

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Metadata is in your help desk, the Dashboard will provide you an overview of tickets in your help desk que. The data can be filtered by date as well as Departments, Help Topics, and Agents. This data can also be exported into a CSV file. Metadata is good for looking at ratios of tickets outstanding and completed.
</p>
<br />
