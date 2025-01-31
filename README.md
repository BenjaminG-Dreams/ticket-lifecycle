<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket Lifecycle</h1>
In this tutorial, we will be going over the lifecycle of a ticket from creation to closing in osTicket. This tutorial has prerequisites that must be completed before continuing which will be linked below. </p>

- [osTicket: Prerequisites and Installation](https://github.com/bvongpradith/osticket-prereqs)
- [osTicket: Post-Installation Configuration](https://github.com/bvongpradith/osticket--post)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure
- Remote Desktop
- Internet Information Services (IIS)
- osTicket
- HeidiSQL

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Steps</h2>

- Ticket Creation
- Assignment and Communication
- Resolving Issue
- Resolution

<h2>Detailed Steps</h2>

![Screenshot 2025-01-30 231820](https://github.com/user-attachments/assets/1cf83e2c-5910-405c-8240-584f9b15a26f)

<p>
First, in the VM go to http://localhost/osTicket/ and open a new ticket.
</p>
<br />

![Screenshot 2025-01-30 232207](https://github.com/user-attachments/assets/49d15011-d221-430f-a045-608511159281)

<p>
Next, use Karen's email and full name for the ticket. Choose a help topic and create a fake scenario that a customer might face. For this tutorial, we will be asking for password reset.
</p>
<br />


![Screenshot 2025-01-30 232852](https://github.com/user-attachments/assets/a47c3439-a5ed-47da-b3d0-954ce1151d82)

<p>
Now go to http://localhost/osTicket/scp/login.php login as John Doe and go to the Agent Panel.
</p>
<br />



![Screenshot 2025-01-30 232956](https://github.com/user-attachments/assets/0d71c716-adb3-4c89-a4f1-8cc6bf1f0e1c)

![Screenshot 2025-01-30 233408](https://github.com/user-attachments/assets/1fac0ea1-8da4-49c6-aa02-e11a027ec4a7)


<p>
Afterwards, navigate to the tickets panel and select the ticket you created. Assign the ticket to either a user or admin and set the SLA plan to SEV-C since it can be done on a weekday when the customer will need to log in. Depending on the severity of the ticket, it will be assigned differently. But for this example, I will put the priority low, department: support, Assigned to: John Doe, and the SLA Plan: Sev-C.
</p>
<br />

![Screenshot 2025-01-30 233451](https://github.com/user-attachments/assets/6cf20b71-3d67-4d80-a5c1-e9f88080b1fc)

<p>
Finally, you will be able to respond to the ticket and decide if it can be resolved or stay open. 
<br />
