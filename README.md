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

 Create a couple of tickets as an external user (Customer):

  - Open your browser, and go to http://localhost/osticket/
  -  Click 'Open a New Ticket'
  -  Enter the customers Contact Information -> Email Address\ Full Name\ Help Topics (Choose from the ones created in post-installation or any)
  -  Fill out the 'Ticket Details' -> Issue Summary (create your own) -> Breif sentence in the empty detail box (create your own)
  - Click 'Create Ticket' 
  - Once the ticket is created you'll get an automatic thank you message from the Support Team


![image](https://github.com/user-attachments/assets/92715456-515b-4b42-8d09-1e16aa58fbf6)


![image](https://github.com/user-attachments/assets/e15ff832-9444-4282-a89f-de6ac7351ce2)



![image](https://github.com/user-attachments/assets/cd48dcdb-cb35-4589-a8b3-cda96dc3d0ff)

![image](https://github.com/user-attachments/assets/2265e615-5bf3-4fa9-81aa-d94d0bd0dd9b)








Work your Tickets!

- Close out your osTicket browser as an external user and log back in as an Agent (Help Desk Professional) -> http://localhost/osTicket/scp/login.php
  
   *Note: Log in is as Jane Doe or John Doe (Agents created from post-installation)

![image](https://github.com/user-attachments/assets/fbcacd5b-9f68-4f1e-8137-fd37a76a45fe)

  
   *Note: If you do not see any tickets after logging in as an Agent, log back out and log back in with your admin credentials (the credentials created when installing osTicket)
           - Go to the Admin Panel -. Agents -> Select the Agent having trouble viewing tickets -> Go to the Access tab -> Add Extended Access -> Save Changes


 ![image](https://github.com/user-attachments/assets/2f238eef-e9b4-4bbe-b4e5-99e68a88fc37)


![image](https://github.com/user-attachments/assets/95fa8035-1e1f-40ac-84cb-b830b3736a62)



Congratulations, your troubleshoot was sucessful! Back to working tickets!

- Log out and log back in with your Jane Doe credentials
- Open a ticket (select either of the ones created)
- Make sure the the priority settings, and the SLA's are set on the tickets
- Assign the ticket to an agent
- Enter a brief note in the empty reponse box
- Post Reply 
    *Note: Only assign a ticket to a different department if it cannot be solved by the default assigned department.
- Go back to 'Open Tickets' to view the ticket you made updates on
- Click on the ticket you recently worked and set the Ticket Status to 'Resolved' indicating something was actually done
    *Note: Enter a brief note in the emppty detail box explaining what was done
     -Post Reply
- To view 'Closed' tickets, simply click 'Closed' and you should see the ticket that was just resolved

 ![image](https://github.com/user-attachments/assets/a18ef2f2-c25d-43ab-ad2b-bf2491423a85)


  ![image](https://github.com/user-attachments/assets/cef28729-e995-4a63-994b-e6613ccf5dd1)

 ![image](https://github.com/user-attachments/assets/40ddde5c-ffed-4f31-986d-5ea58bee0998)

![image](https://github.com/user-attachments/assets/e43c4e05-f4c2-4bcf-9d03-171871ba7cb8)

 ![image](https://github.com/user-attachments/assets/63fba82e-46a2-4845-9309-7e91d68ec2c0)


  ![image](https://github.com/user-attachments/assets/b848837b-b95b-45ff-a080-fc56702b13f6)


Going back to Open Tickets: 

 - Select another ticket
 - Repeat the steps as needed and be sure to set the Priority and SLA appropriately
 - Assign to a different Agent, i.e John Doe
 - Enter a brief note in the empty reponse box
 - Post Reply
 - Click on Open Tickets and view that the ticket is now Assigned to John Doe
     *Note: If you need to delete a ticket, select the box next to the ticket number and click delete on the far righr (mini trash can
 

   ![image](https://github.com/user-attachments/assets/da0d6845-0c9c-4696-9ae5-e75ac39476c8)

  ![image](https://github.com/user-attachments/assets/ce79d199-201f-445e-918e-6860ec2a678e)


   ![image](https://github.com/user-attachments/assets/4b0e2187-8b5b-4f96-b557-415207f37c60)



Work your last ticket:

- Select the ticket
- Repeat the steps as needed and be sure to set the Priority and SLA appropriately
- Assign to an Agent (either Jane or John)
- Enter a brief note in the empty reponse box
- Resolve the ticket if you are already signed in as the Agent assigned for the ticket

![image](https://github.com/user-attachments/assets/fe1f329f-a38f-4c0a-91b4-128a5d1a5b82)

![image](https://github.com/user-attachments/assets/71ca9524-7619-437f-87cf-cec3ad21dc91)


Log back in as John and resolve that ticket:
 - Select the ticket that was assigned
 - Look through the history of the ticket
 - Enter a brief note in the empty response box
 - Select the 'Ticket Status' as 'Resolved'
 - Post Reply
   
![image](https://github.com/user-attachments/assets/1bb8a894-8512-42f3-94d9-266548c43b77)


![image](https://github.com/user-attachments/assets/b85dbfae-f651-43b9-b76f-ee31196cd283)


![image](https://github.com/user-attachments/assets/6801c919-8ecd-4a85-81e6-06fc9711a004)

![image](https://github.com/user-attachments/assets/f74b7fbf-a74a-4c7f-b8d5-860518a6f4f7)


 *Note: If you were unable to select 'Resolve' under John Doe, log out and log back in with your admin credentials (created when osTicket was installed), go to 'Admin Panel' -> Agents -> Agents -> Select John Doe -> click the Access tab -> Change the 'View Only' access to 'Supreme Admin' -> Save Changes

 ![image](https://github.com/user-attachments/assets/fa4aa58d-9aed-483f-a53d-05df70809150)


![image](https://github.com/user-attachments/assets/436a93d8-0252-49a4-95fd-032858dddbf4)




Congratulations, all tickets have been resolved and/or closed!

![image](https://github.com/user-attachments/assets/52d63bfa-8832-4c03-925a-94dfd6c36b82)

