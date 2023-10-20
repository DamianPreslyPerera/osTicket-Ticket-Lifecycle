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

<h2>Lifecycle Stages - Ticket Intake</h2>

- In this section, I will demonstrate the procedure that an end user will take to login to osTicket and create a ticket, which will then be worked on by a help desk agent
- The user must first navigate to osTicket using the link and login to osTicket using their credentials
- When the user navigates to the osTicket website, they will be presented with this page
- Click on "Open a New Ticket"

  <img width="776" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-Ticket-Lifecycle/assets/89204562/d97390e6-225a-4257-a5dc-9f56b9c4782b">

- The user will be presented with this page

  <img width="777" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-Ticket-Lifecycle/assets/89204562/a988f755-ffcc-4c1a-901f-801c6dae41ab">

- The user can now enter in their information such as their Email Address, Full Name, Help Topic and Issue Summary
- The Help Topics are what we created prior in the configuration steps
- For this ticket, the user will choose "Business Critical Outage" as a Help Topic
- The user can also provide a brief description of the issue
- When all the informatio is entered in, the user can click on "Create Ticket" to create the ticket

  <img width="731" alt="createticket" src="https://github.com/DamianPreslyPerera/osTicket-Ticket-Lifecycle/assets/89204562/8c08546b-8f3a-4835-a72a-fc9ce1b87b37">

- The user will be presented with this confirmation page

  <img width="773" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-Ticket-Lifecycle/assets/89204562/758c4535-ea89-46a8-b4a7-9e12164cc09d">


- Using the same procedure, another user can create a ticket to log their issue as well 
  
  <img width="774" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-Ticket-Lifecycle/assets/89204562/e6d089f6-a7c1-4c9a-97f9-aefa81471b31">

- The user will be presented with a confirmation page as well

  <img width="776" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-Ticket-Lifecycle/assets/89204562/fe4f7487-fb3f-4829-93f5-c3ec7ba1e136">

- A user can create multiple tickets as well, they can provide the same contact information and choose another Help Topic and Issue.
- In this instance, the previous user "Tania Smith" is opening up another ticket under the Help Topic "General Inquiry" regarding a status update on a "Hardware Refresh"

  <img width="731" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-Ticket-Lifecycle/assets/89204562/fc403486-5fbf-4e26-aeda-c9357747efec">

- The user is presented with a confirmation page for their additional ticket as well

  <img width="733" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-Ticket-Lifecycle/assets/89204562/fa1e4867-1fdf-4941-954e-ab0a48682937">


## Assignment and Communication

- Now that the tickets have been opened, we can act as if we are the help desk agents and login to osTicket to view, manage/assign and resolve the open tickets in the ticket queue
- Login to osTicket as a Help Desk Agent (Jane Doe) using the previously created credentials

  <img width="776" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-Ticket-Lifecycle/assets/89204562/ac814c2b-a4e8-4603-951d-4dbf0465686e">

- Upon loggin in, the Help Desk Agent is able to view the newly created tickets of end users

  <img width="776" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-Ticket-Lifecycle/assets/89204562/d6de2ec0-9918-439f-88de-161127f80d98">

- As of now, all the tickets have a priority of "Normal" and none of them are assigned to any help desk agents
- We will act as if we are a help desk lead and proceed to create priority levels and assign the tickets to help desk agents
- We can begin by clicking on the ticket "Mobile Banking App Down" which is the first ticket that is in the queue

  <img width="579" alt="firstticket" src="https://github.com/DamianPreslyPerera/osTicket-Ticket-Lifecycle/assets/89204562/606b1286-fb0e-471a-a072-a9bbab827abe">

- By looking at the details of the ticket, we can see that the issue is regarding the customers being unable to access the bank application, and since this can have a major negative impact on the business if it is not resolved, we can assign a priority level of "Emergency" to this ticket
- We can assign the priority level by clicking on the default priority level, which is currently set to "Normal"

  <img width="581" alt="bankappdown" src="https://github.com/DamianPreslyPerera/osTicket-Ticket-Lifecycle/assets/89204562/98a477c5-e8af-4168-a78e-eb43ebe19141">

- Update the priority level by choosing "Emergency" from the drop down menu

  <img width="576" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-Ticket-Lifecycle/assets/89204562/48c81965-871a-4a41-9c7e-73aa8eaff150">

- We can also create a note for the priority level as well
- Click "Update" to assign the new priority level to the ticket

  <img width="574" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-Ticket-Lifecycle/assets/89204562/f0bd2beb-acec-4e0f-b615-b07b9e8216c2">

- The ticket's priortiy level has now been elevated to "Emergency"

  <img width="577" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-Ticket-Lifecycle/assets/89204562/d2a60173-92c3-4a83-85c1-5a35cacb3095">

- We can now proceed to assign the ticket to a help desk agent
- Click on the "Unassigned" tab to assign a help desk agent

  <img width="578" alt="unassigned" src="https://github.com/DamianPreslyPerera/osTicket-Ticket-Lifecycle/assets/89204562/d68433e2-29d1-4fee-b342-0a7f7d0f9141">

- The help desk agent can assign the ticket to themselves
- In this scenario, Jane Doe is both the help desk lead as well as an agent so they can assign the ticket to themselves
- Click "Assign" to assign the ticket 

  <img width="577" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-Ticket-Lifecycle/assets/89204562/e79cd4fb-5ec5-4c4f-b49a-c5059f657910">

- We can now proceed to update the SLA (Service Level Agreement)
- Click on the "Default SLA" tab to update the SLA

  <img width="577" alt="slaupdate" src="https://github.com/DamianPreslyPerera/osTicket-Ticket-Lifecycle/assets/89204562/61958935-c168-4357-a237-a7c58b8d164e">

- Since the ticket has a priority level of "Emergency" we can set the tickets SLA to "SEV-A"
- The "SEV-A" SLA indicates that the ticket must be resolved within an hour on a 24/7 schedule
- We can also provide a brief note about the SLA level and indicate that it is a  "Business Impacting, Critical Incident"
- Click on "Update" to put the changes into effect

  <img width="578" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-Ticket-Lifecycle/assets/89204562/b38766fa-88b8-4fd8-abf2-ffdd4ba80a0a"> <br />
   
  <img width="575" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-Ticket-Lifecycle/assets/89204562/96215c01-8e63-4cd1-8df5-d840805d9650">

- The SLA has now been updated succesfully

  <img width="573" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-Ticket-Lifecycle/assets/89204562/f2e1d618-98f4-475a-8b30-7327101d21cc">

 
- We can reassign/transfer this ticket to the appropriate department as well
- Currently, the ticket is assigned to the "Support" Department, we can reassign it to a more appropriate department such as "System Adminstrators"
- Click on the "Department" tab and click on "Support" to change the department

  <img width="573" alt="changedepartment" src="https://github.com/DamianPreslyPerera/osTicket-Ticket-Lifecycle/assets/89204562/98ab75a0-f3d1-491a-8219-3b7d6bcc6a3c">

- Choose the "System Administrators" option from the drop down menu

  <img width="579" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-Ticket-Lifecycle/assets/89204562/6745c2b0-1af9-476e-9f01-b503d97811bd">

- An optional message can be entered in as well
- Click on "Transfer" to reassign the ticket over to the System Administrator's department

  <img width="578" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-Ticket-Lifecycle/assets/89204562/27462f2b-16a9-4e9d-bf86-709bfedae62f">



## Working the Issue

- After logging in all the necessary information such as the Priority, Department, Assignee, and SLA plan, we can proceed to work on the actual issue that is presented in the ticket
- For this demonstration, I will assume the the help desk agent "Jane Doe" has worked on solving the issue and is posting a reply/comment regarding the status of the ticket
- The agent can give a repsonse to the ticket by typing in the "Response" section
- The reply can be attached by clicking on "Post Reply"

  <img width="577" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-Ticket-Lifecycle/assets/89204562/6438f504-fe74-480f-80ec-0c39c4273e29">

- The status of the ticket can now be viewed from the ticket dashboard

  <img width="589" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-Ticket-Lifecycle/assets/89204562/c48efc70-ed53-4538-81bd-73f9e9d4c77d">

- Assuming that the help desk agent has worked on solving the ticket, the agent can go back into the ticket and mark it as "Solved" to close off the ticket 


  




  
