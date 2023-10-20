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


  











  
