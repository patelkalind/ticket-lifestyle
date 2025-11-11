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

In every ticketing software, there are always the stages of the ticketing system's lifecycle. As an end user who’s asking for help, they create a new ticket to explain their issue. From there, the agent will open the ticket and resolve it immediately, or place it in pending status to request more information from the end user. Sometimes, the agent will reassign the ticket to another agent with a higher status to ensure it is appropriately resolved. Once that is completed, the agent must close the ticket ASAP to inform the end user that their issue has been resolved. 

In this tutorial, we will simulate the ticketing lifecycle of a day-to-day business from the perspective of a Help Desk Agent and from that of an end user. There will be three simulated exercises to help explain the issues. However, before we begin, some housekeeping tasks need to be taken care of to ensure osTicket is effective.

**Before the Simulation**

Please verify that the SysAdmins department is Top Level


<img width="975" height="523" alt="image" src="https://github.com/user-attachments/assets/f92ff368-e132-47a3-bef5-efbaa3130573" />
 
The next step is to delete the Maintenance department in this exercise, as it won’t be needed


<img width="975" height="523" alt="image" src="https://github.com/user-attachments/assets/66d4603d-289d-4af5-b64d-e582a95ab57b" />
 
Make sure you select the correct box for Maintenance and confirm deletion


<img width="975" height="523" alt="image" src="https://github.com/user-attachments/assets/54bb8576-df5d-4bbb-9c57-31dcf5c303e9" />
 
You have successfully deleted the Maintenance department


<img width="975" height="523" alt="image" src="https://github.com/user-attachments/assets/51c24024-7950-41be-817a-59874c31ac36" />



**Simulation #1**


For every tech issue that arises, all end users must submit a ticket form. Every ticketing software may vary in how to open a new ticket, but here is an example of how the end user opens a new ticket on osTicket:


<img width="975" height="523" alt="image" src="https://github.com/user-attachments/assets/24bac98d-a3f5-42b4-9bea-bbc3e25e3a20" />
 
In this simulation, the end user’s name is Karen, and she is submitting a ticket under the “Report a Problem” category because the entire online banking system is down. Her employees can’t access or log in. Here is an example of the ticket.


<img width="975" height="523" alt="image" src="https://github.com/user-attachments/assets/39710017-ebd7-46d9-b278-7321726024ba" />
 
After Karen submitted her ticket, the help desk agent John Doe will now review it and read the description. Below is an example of how the ticket appears to John Doe.


<img width="975" height="523" alt="image" src="https://github.com/user-attachments/assets/c4232f7c-16de-44a9-8ac0-921bdb68d4df" />
 
After John Doe observed the ticket, he would then update the “assigned to” field to the Online Banking team and change the SLA to Sev-A, as this issue needs to be addressed ASAP before handing it off to Jane Doe, who has a higher priority in osTicket as an admin over John. 


<img width="975" height="255" alt="image" src="https://github.com/user-attachments/assets/36762f40-80a1-45da-b829-23185657182b" />
 
From there, Jane Doe would inform the Online Banking team that she will take full responsibility for handling this ticket by reassigning it to herself.


<img width="975" height="523" alt="image" src="https://github.com/user-attachments/assets/c111bc0d-6753-4b70-bce9-7d66f2daccda" />
 
Jane then follows up with Karen to ensure the issues are being addressed before resolving them.


<img width="975" height="496" alt="image" src="https://github.com/user-attachments/assets/515e8c25-90ed-4a75-9591-46229ab9e136" />
 
After Jane Doe resolved the issues with the online banking systems not working, she would respond to Karen to explain the problems before closing out the ticket.


<img width="975" height="566" alt="image" src="https://github.com/user-attachments/assets/a2a39f57-25a4-4ea3-ad1a-f684554c6791" />
 
After the issue is resolved, Jane must close the ticket to mark it as officially resolved.


<img width="975" height="523" alt="image" src="https://github.com/user-attachments/assets/b2a4a2fc-cc7f-44b0-a9b2-5da1058fee72" />



**Simulation # 2**

In this second simulated exercise, Karen submits a ticket under the category of “General Inquiry”. In this scenario, the accounting department can’t use its Adobe software. Here is an example of the ticket
 
Just so you know, for end users, if a ticket is assigned to the wrong support agent, it can be transferred as shown below, where Jane transfers the ticket to John.
 
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
