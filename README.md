<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2></h2>


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents(Workers)/Users(Customers)
- Configure SLA/Help Topics

<h2>Configuration Steps</h2>

<p>

![image](https://github.com/Sunnyyvaj/Post-Install-Config/assets/165757391/c2633bf8-b84b-43e9-9d81-7906c127ecb8)

In the image above. It will show you the main page for yourself, but if you clicked on the word "admin" right next to your name it will show a different screen, which will be shown in the picture below.

![image](https://github.com/Sunnyyvaj/Post-Install-Config/assets/165757391/e15834f0-6124-417d-9ac5-82f094faf3f3)



So in the image below, we will start creating "Roles". We should already be in the admin panel. If you look at the top right corner and see your name. You should see that the word has changed from "Admin" -> "Agent". Click on the word agent and it will bring you to the image below on the website. Next we can click on the tab named "Roles."
![image](https://github.com/Sunnyyvaj/Post-Install-Config/assets/165757391/98c7ddb7-2f61-4df6-be68-3e4c749e29cb)



Now we can start adding roles. So we can go ahead and click the button "add new roles" Look at the image below for the next step.
![image](https://github.com/Sunnyyvaj/Post-Install-Config/assets/165757391/3b8a456d-9440-4e69-9c27-0381cd915d1a)


In this part we can put down whatever name we want. In my case I will just put down supreme admin. In the 2nd image below we will click on the permissions tab and give permissions to the newly created role of "supreme admin".
Now in the 2nd image below. We will check everybox in every tab to give permission for our supreme admin role. Once we are done we can hit the add role tab and that completes creating the supreme admin role.
![image](https://github.com/Sunnyyvaj/Post-Install-Config/assets/165757391/4af8120e-0b19-4c16-8dba-eb3dbe5c85db)
![image](https://github.com/Sunnyyvaj/Post-Install-Config/assets/165757391/82a518fc-31e9-4d28-9961-24c08865bc1d)




In this next step. We will be creating departments. So in the same tab section where you saw the word "roles" there should be another word called "department". We can click on that and move forward with the next step. In the 2nd image below we will click on the button "add new department." **Just a side note, there will be preloaded departments already, so don't mind that and just create a new department.** In the 3rd picture below, you'll see that there is a lot to do, but the main things we will focus on is naming the department and giving it a manager. **In this case you don't need to give it a new manage, since you're already the manager** So now that we have given the department a new name we can just click the finished button and move onto creating "teams."



![image](https://github.com/Sunnyyvaj/Post-Install-Config/assets/165757391/084b3850-aaed-4ba9-a769-cf51ab644de8)
![image](https://github.com/Sunnyyvaj/Post-Install-Config/assets/165757391/fcc54c1f-c4b7-4665-b6c9-f3af132bbca8)
![image](https://github.com/Sunnyyvaj/Post-Install-Config/assets/165757391/941c2f70-6db2-4cec-a59d-5833bd6d86c5)
![image](https://github.com/Sunnyyvaj/Post-Install-Config/assets/165757391/a53cd366-ad4f-4d08-bac7-398b0d75c5c3)


Now we are in the same section as before. We just have to click on the "teams" tab and you'll see the same image as shown below. We will also click on the "add team" button to create a new team. Teams can be created for example the first group of teams would be dedicated to important tickets that needs to be done within the day. Another team example would be a team that focused on tickets that has a low importance.
![image](https://github.com/Sunnyyvaj/Post-Install-Config/assets/165757391/33115914-214d-4df6-8368-c4ade7e14188)


In the image above it already has a team called level 1 support. In this case we will create a level 2 support team in the image below.
![image](https://github.com/Sunnyyvaj/Post-Install-Config/assets/165757391/ae3ab896-d400-4eae-b9ab-75c909e211f5)


This part of the guide. We will pretend to give allowence to anyone to create tickets. So in the image below we will click on the settings tab and once the tab is open. We will click on the "User's box."

![image](https://github.com/Sunnyyvaj/Post-Install-Config/assets/165757391/ca394b67-1459-48a3-9ed9-1e2ad829f02f)


As you can see in the image below. To allow everyone to create a ticket, we would have to uncheck the box called "Registration Required". After that is done everyone will be able to create any tickets they want.
![image](https://github.com/Sunnyyvaj/Post-Install-Config/assets/165757391/7bf65708-c1f3-47ae-8305-fb344e170094)



The next step is to create some agents. They will act as IRL employees to handle any tickets that comes through osTicket. 
![image](https://github.com/Sunnyyvaj/Post-Install-Config/assets/165757391/744d1bf9-395a-4886-9318-6bda42e081bc)


So in the 1st image below. We can create one or two agents. Either one is up to you, and you can also name those agents however you want. But in this case I will name my agents Worker one and Worker two.
In the 2nd image below you can see that I have already created one of my agents. Now we have to set up a password for them, which essentially creates a login for them. In the 3rd image, we have created a password for the agent. Make sure to uncheck the first box and the last box and hit the button "set".
![image](https://github.com/Sunnyyvaj/Post-Install-Config/assets/165757391/e0d2ba62-2ccc-465a-9ad5-9641daf1a6d2)
![image](https://github.com/Sunnyyvaj/Post-Install-Config/assets/165757391/083a1e9d-6748-42c0-b7de-ad5ccafc7a6e)
![image](https://github.com/Sunnyyvaj/Post-Install-Config/assets/165757391/de169ab6-966f-4b8a-893c-6aaee7a0b6c7)


**This will also be the same step to create agent 2.**


Another note. We can add/give permissions to the agents by looking at the tabs called "Access","Permissions",and "Teams"
So I will go ahead and add worker one to level II support team, while also giving them access as system adminnistrators.
![image](https://github.com/Sunnyyvaj/Post-Install-Config/assets/165757391/6477d840-4286-46a8-bc86-c0645f1c2c28)


This step we will be adding in users. So to do that we will need to click in the upper right corner where it says Agent. Once we do that we can click on the small tab that says "users".
In the 2nd image we can click on "add user". In this case we will create two users. You can name them whatever you want. In the 3rd image as you can see I just filled out that section and once I was done I added the user and now we have created one user. Now we have two users that are created.
![image](https://github.com/Sunnyyvaj/Post-Install-Config/assets/165757391/cad4185f-5975-4c5f-8812-a6fc4972f16a)
![image](https://github.com/Sunnyyvaj/Post-Install-Config/assets/165757391/1bdec025-7860-4eb6-a96e-a3b28518721c)
![image](https://github.com/Sunnyyvaj/Post-Install-Config/assets/165757391/a2b505c1-1bb1-4f1a-8e72-9837768ae1f5)
![image](https://github.com/Sunnyyvaj/Post-Install-Config/assets/165757391/58114248-d8b1-4676-91e0-7fd9996ab8f0)
![image](https://github.com/Sunnyyvaj/Post-Install-Config/assets/165757391/ccaa4a59-9b9d-4f2c-9fab-5ef334761922)


SLA are basically a time table for when tickets needs to get done. So for example a ticket that needs help with resetting their password could take maybe 4 hours or during business hours. In this step we will be creating SLA. To start creating SLA, we will need to go into our admin profile and click on the manage tab. Once there we will click on the small tab called "SLA".
![image](https://github.com/Sunnyyvaj/Post-Install-Config/assets/165757391/0012fad2-00b8-4ca9-be01-8b2dd4c3c767)
![image](https://github.com/Sunnyyvaj/Post-Install-Config/assets/165757391/c4dee3ce-b8fb-451a-a229-7a30420bc1b2)


In this step I am creating SLA which would be called Sev-A, Sev-B, and Sev-C. These are important to so that us help desk employees can keep track of which tickets needs the quickest attention.
![image](https://github.com/Sunnyyvaj/Post-Install-Config/assets/165757391/7c08ad6b-7e9b-4006-9b57-4a9327c806d4)
![image](https://github.com/Sunnyyvaj/Post-Install-Config/assets/165757391/d042e97e-019f-49a3-82b3-87a273eb9a2f)
![image](https://github.com/Sunnyyvaj/Post-Install-Config/assets/165757391/aa77d441-fac4-4a06-9eb7-0d9354725f80)





</p>
<p>

</p>
<br />

<p>

</p>
<p>

</p>
<br />

<p>

</p>
<p>

</p>
<br />
