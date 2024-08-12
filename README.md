# ITSM

This is a ITSM tool created on Powerapps.

It's focused on centralizing all the IT Activities in one Canvas APP.

I am using a lot of connections and tools on it, such as Power Automate, Sharepoint online, Azure AD & office 365 connectors. (I am currently migrating the data to dataverse)

I created it because my department was having a lot of pain receiving requests in differents platforms, we had no trackbility nor was impossible to give feedback for the users.

Main screen - Shows the user information and which IT devices they have.

![image](https://github.com/user-attachments/assets/0bde3e28-9e48-4ed1-8d3a-47484f936141)

note that I have created a menu when you click on the Icon. It allows me to navigate through the Equipament, Requisition and support screens.

![image](https://github.com/user-attachments/assets/c9c9b70e-23e1-439c-945e-64f2a92ec315)

Now talking about the Asset requisition session, well... I have tried to create a really friendly screen so the users don't have any doubt and also add a cart screen so they can request as many assets/license they need.

![image](https://github.com/user-attachments/assets/f9662c51-7024-4903-903d-1b5a3db102f7)

To control these requests, I have a power automate approver flow running, which sends an approval request to their manager and then to IT. if both approves, user gets what they requested.
![image](https://github.com/user-attachments/assets/f051f8f7-98aa-4a8e-af00-b06e27e2bb0d)


When an users needs to create a support ticket, he/she gets to this screen and new fields appears according to what they selected. (OBS: some fields stays hidden, I'm adm so i see everything).

![image](https://github.com/user-attachments/assets/043fdb53-bd40-4ceb-8c90-9e53437c7b5f)

both support and requisition tickets have follow up screens so people can track it and also add comments in case they need any help or notify IT. When an comment is added, everyone receives an e-mail.

![image](https://github.com/user-attachments/assets/dba4530a-ec24-4c91-ba95-4f58721d1df4)


Last but not least. The equipment section.

we have too many equipmants including Sim cards, printers, network devices, display screens and etc. 

Here is an example of Computer screens (it's filtered)
![image](https://github.com/user-attachments/assets/a9a5de9d-c487-477f-b145-03eaf5488d05)
