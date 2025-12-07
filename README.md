<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)  
- Remote Desktop  
- Internet Information Services (IIS)  

<h2>Operating Systems Used</h2>

- Windows 10 (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles to define agent permissions  
- Create Departments for ticket assignment and workflow structure  
- Set Up Teams for cross-departmental collaboration  
- Configure SLA Plans to enforce response and resolution timelines  
- Create and Assign Agents/Users for proper ticket routing and access

<h2>Configuration Steps</h2>


The first thing I did was log into the admin analyst login page and end users os ticket url through by going through two links
<img width="1535" height="303" alt="image" src="https://github.com/user-attachments/assets/296aef96-6f99-484d-912e-09d9177c82eb" />
<img width="1529" height="463" alt="image" src="https://github.com/user-attachments/assets/b2190bff-4dde-4c07-b427-d946d7a43a2a" />

I then signed into my account and went to the admin panel then I went to the agents section and then I pressed on roles. I then pressed add a new role and named the new role supreme admin
<img width="719" height="986" alt="image" src="https://github.com/user-attachments/assets/5d8b140d-db1e-4c77-b6ac-00ea46e59ef1" />
<img width="723" height="429" alt="image" src="https://github.com/user-attachments/assets/6f602b07-1f70-4855-aa56-9b2d06c5f83c" />

I gave this new role access to all permissions
<img width="714" height="747" alt="image" src="https://github.com/user-attachments/assets/5e2215bf-238c-48df-ae68-0a2e4a71a27a" />
<img width="723" height="727" alt="image" src="https://github.com/user-attachments/assets/750e088b-d793-4e6a-a865-2fc9917e70e8" />
<img width="721" height="710" alt="image" src="https://github.com/user-attachments/assets/d03c86bc-da73-4aee-ba4e-99f28d0a51ef" />

I then went to the departments section and pressed add department I named it SysAdmins and the parent is Top level department and I left everything as default and pressed save changes.
<img width="722" height="984" alt="image" src="https://github.com/user-attachments/assets/ad690040-a2b6-4e06-99be-c28c3f6e786c" />
<img width="719" height="394" alt="image" src="https://github.com/user-attachments/assets/c4bdbc0f-4c5d-46b5-bdd8-4acf6873b00b" />

Next I went to the teams section then I pressed create team and named the team online banking.
<img width="718" height="229" alt="image" src="https://github.com/user-attachments/assets/ae5a012f-8641-421f-af47-b0653f853dd6" />
<img width="723" height="985" alt="image" src="https://github.com/user-attachments/assets/c6cf59cd-c137-4ca8-8852-2d12ed79bdb6" />

Then I went to settings and unchecked "unregistered users can create tickets" so anybody can create tickets
<img width="721" height="590" alt="image" src="https://github.com/user-attachments/assets/fb5f3deb-369d-468a-9585-c186f4cb3fcb" />

I then went to the admin panel went to agents and pressed add new then I added Jane Doe. I made jane apart of the sysadmins department, gave her the supremeadmin role and made her apart of the online banking team.

<img width="719" height="769" alt="image" src="https://github.com/user-attachments/assets/50b97617-9a92-45ed-bc38-fe741d93000d" />
<img width="722" height="490" alt="image" src="https://github.com/user-attachments/assets/e2b935db-e1e5-43b1-a389-f7272570ca7a" />
<img width="721" height="438" alt="image" src="https://github.com/user-attachments/assets/b0d9488b-63f1-411c-b019-a9f4df69f5f6" />

I then added another agent and named him Jhon Doe I gave him a Supporting role and I gave him view only acess and left everything elseas it is.

<img width="719" height="767" alt="image" src="https://github.com/user-attachments/assets/d8c400e1-fe55-491c-8bae-4c015c0d2883" />
<img width="720" height="493" alt="image" src="https://github.com/user-attachments/assets/fecefe7f-5db1-4518-b79c-b8a43c168aa6" />

I then went back to Jane and Jhons accounts and I set their passwords.

<img width="720" height="766" alt="image" src="https://github.com/user-attachments/assets/86e36c35-00a3-4e89-b1b1-8e9d00f3b7c1" />
<img width="723" height="771" alt="image" src="https://github.com/user-attachments/assets/81373698-299b-47ff-a0a2-74baf5f87981" />

I then went to the agent panel and pressed on users and added a user named Karen.

<img width="715" height="500" alt="image" src="https://github.com/user-attachments/assets/90867bbe-ae72-4295-b720-519941dabb2f" />
<img width="722" height="383" alt="image" src="https://github.com/user-attachments/assets/2b5b51e4-ccb2-4025-873e-0a6112bcc0e2" />

Next I went to the admin panel then I went to the manage section and pressed SLA. I then pressed add SLA and then added an SLA named Sev-A with grace period of 1 hour and I set the schedule to 24/7.

<img width="719" height="577" alt="image" src="https://github.com/user-attachments/assets/f96f5bbd-278c-4999-950c-6c59163d046b" />

I also made A SLA named Sev-B with a grace period of 4 hours, schedule 24/7.

<img width="723" height="575" alt="image" src="https://github.com/user-attachments/assets/e02c98c1-2cc8-49ba-bb2b-b21fc123faa4" />

I also made A SLA named Sev-C with a grace period of 8 hours, schedule 25/7/buisness hours

<img width="721" height="578" alt="image" src="https://github.com/user-attachments/assets/813a4311-3421-4169-8b37-c8e59ee5e50c" />

<img width="721" height="391" alt="image" src="https://github.com/user-attachments/assets/84a3a07c-213a-44db-9bf5-1fe4499873d3" />

I then went to the help topic section and I pressed add new  and made a help topic named buisness critical outage and I made the parent topic report a problem

<img width="720" height="986" alt="image" src="https://github.com/user-attachments/assets/56e76589-2fae-4848-99f5-d9401d8dc538" />

I made another help topic named personal computer issues I also madethe parent topic report a problem

<img width="722" height="555" alt="image" src="https://github.com/user-attachments/assets/def29796-c7a1-4a3c-a8c4-780bfc6657f9" />

I made another help topic named equipment request I made the parent topic general inquiry.

<img width="720" height="561" alt="image" src="https://github.com/user-attachments/assets/d0144d27-b640-4d67-8a85-ead46042db59" />

I made another help topic named password reset I made the parent topic report a problem.

<img width="720" height="558" alt="image" src="https://github.com/user-attachments/assets/41b8195c-0d95-4b3b-8151-d63985de4821" />
















  
 
