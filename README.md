<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

In every ticketing software, there are always the stages of the ticketing system's lifecycle. As an end user who’s asking for help, they create a new ticket to explain their issue. From there, the agent will open the ticket and resolve it immediately, or place it in pending status to request more information from the end user. Sometimes, the agent will reassign the ticket to another agent with a higher status to properly resolve it. Once that is completed, the agent must close the ticket ASAP to inform the end user that their issue has been resolved. 

In this tutorial, we will simulate the ticketing lifecycle of a day-to-day business from the Help Desk Agent’s perspective and from the end user's perspective. There will be three simulated exercises to help explain the issues. However, before we begin, some housekeeping tasks need to take place to ensure osTicket is effective.

**Before the Simulation**

Please verify that the SysAdmins department is Top Level
 
The next step is to delete the Maintenance department in this exercise, as it won’t be needed
 
Make sure you select the correct box for Maintenance and confirm deletion
 
You have successfully deleted the Maintenance department
 
**Simulation #1**

For every tech issue that arises, all end users must submit a ticket form. Every ticketing software may vary in how to open a new ticket, but here is an example of how the end user opens a new ticket on osTicket:
 
In this simulation, the end user’s name is Karen, and she is submitting a ticket under the “Report a Problem” category because the entire online banking system is down. Her employees can’t access or log in. Here is an example of the ticket.
 
After Karen submitted her ticket, the help desk agent John Doe will now review it and read the description. Below is an example of how the ticket appears to John Doe.
 
After John Doe observed the ticket, he would then change the “assigned to” to the Online Banking team and change the SLA to Sev-A, as this needs to be addressed ASAP before handing it off to Jane Doe, who has higher priority in osTicket as an admin over John. 
 
From there, Jane Doe would inform the Online Banking team that she will take full responsibility for handling this ticket by reassigning it to herself.
 
Jane then follows up with Karen to ensure the issues are being addressed before resolving them.
 
After Jane Doe resolved the issues with the online banking systems not working, she would respond to Karen to explain the problems before closing out the ticket.
 
After the issue is resolved, Jane must close the ticket to mark it as officially resolved.
 
**Simulation # 2**

In this second simulated exercise, Karen submits a ticket under the category of “General Inquiry”. In this scenario, the accounting department can’t use its Adobe software. Here is an example of the ticket
 
Just so you know, for end users, if the ticket goes to the wrong support agent, it can be transferred as shown below, where Jane transfers the ticket to John.
 
After Jane transfers the ticket to John, he will review it and act accordingly.
 
After reviewing the ticket, the SLA plan is prioritized as Sev-C because only two employees are experiencing issues with Adobe.
 
After reassigning the SLA, John Doe takes sole responsibility for resolving this ticket
 
John must then explain to Karen what the problem was and then give an estimated time of completion.
 
Once John has resolved the issue, he follows up with Karen to confirm it has been resolved before closing the ticket.
 
John officially closes the ticket with a comment on what the issue was
 
**Simulation #3**

In this third and final simulated exercise, Karen would submit a ticket regarding a personal computer problem. In this case, she explains that the CFO can’t turn on his computer.
 
After Karen submitted the ticket, Jane Doe reviewed it and transferred it to John Doe. He then updated the priority to “Emergency” as this issue is coming from an executive.
 
John would then assign the SLA to Sev-B, as this is a priority to resolve, but not at the level of Sev-A yet. However, he keeps his options open to change the SLA if needed.
 
John Doe later informs the team that he will take over this ticket
 
John would later explain to Karen that the CFO’s laptop wasn’t working even though it was charged because the power charger was broken. He would follow up by informing Karen that the CFO had received a new charger.
 
John Doe officially closes the ticket, explaining that the CFO’s laptop charger was broken and that a new charger was required to power his laptop.
 
**Conclusion**

To sum it up, every day in business, there will always be an issue from the end user, ranging from minor (a laptop charger not working) to major (a server down). As a help desk agent, it’s your responsibility to respond to each task that comes up and occasionally delegate if there’s a need for help. 
  
It’s always important to communicate with the end user to explain the problem and follow up, since tensions can arise; the best thing to do is ease the pain. On occasion, tickets are created via phone, chat, email, a web form, or in person when you run into someone in your hall or when someone approaches you at your desk. A lot of the time, people will ask you to fix stuff on the spot. While it’s acceptable to fix things on the spot, it’s always a good idea to create a ticket for everything that you do.

This officially concludes the osTicket tutorial. As always, make sure you clean up your virtual machines and delete them to avoid charges to your Microsoft Azure account.

</p>
<br />
