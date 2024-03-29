<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
In this lab i outline the post-install configuration of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Open azure virtual machine
- open osTicket Dashboard


<h2>Configuration Steps</h2>
<p>
Open osTicket
</p>

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/0b20315a-f0df-48e5-aac0-0bf7bb22b6b7)


<p>
Configure Roles
<br>- Admin Panel -> Agents -> Roles </b>
<br>- Add new role: Supreme Admin </b>
<br>- give the role all permissions </b>
</p>

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/5bf34439-276e-45c1-8ba7-76756bb0d85b)

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/adc92c8d-51c7-44ba-8562-50c192f13049)

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/88506e7b-0132-4cb3-b7ea-b24ae1e72c08)

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/c63872ec-be8f-4b97-956e-71b260bcbdd5)

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/0f03812b-f0fe-47b2-885b-0bae334faffb)


<p>
Configure Departments 
<br>- Admin Panel -> Agents -> Departments </b>
<br>- Add new Department: System Administrators </b>
</p>

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/386c2862-4a6c-4490-9301-9720a419f66d)

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/d2dcd750-c087-4339-a1d0-e977f293eba2)

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/002dc6c4-d5b6-40d9-a9e9-c2c7a3c43e4e)

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/424cc52c-821f-4c6d-af6a-57a360816806)

<p>
Configure Teams
<br>- Admin Panel -> Agents -> Teams </b>
<br>- Add Level 1 Support </b>
<br>- Add Level 2 Support </b>
</p>

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/9a0c9ab7-184d-4486-a940-71a3207bfeaa)

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/d7eacd79-f1cf-43b7-8c56-2f2f184635f8)

<p>
Allow anyone to create tickets
<br>- Admin Panel -> Settings -> User Settings </b>
<br>- Registration Required: Require registration and login to create tickets </b>
</p>

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/53559421-77c2-4e60-ad61-628117a13e44)

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/f0214d62-c740-4044-b8e0-e69637de182b)

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/a21c9dbd-d36a-4ba7-9ced-166f59abe2be)


<p>
Configure Agents (workers)
<br>- Admin Panel -> Agents -> Add New </b>
<br>- Jane </b>
<br>- John </b>
</p>

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/c870b5d3-727f-4b28-a58a-21128de36801)

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/19758297-1070-46fc-858e-469c14b3028e)

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/eef22995-bd73-44da-aa00-a165bc7da2a3)


<p>
Configure Users (Customers)
<br>- Agent Panel -> Users -> Add New </b>
<br>- Karen </b>
<br>- Ken </b>
</p>

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/631bfdee-adff-472c-a28a-fe1cc8b79d02)

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/9b719958-31a5-4595-bb90-f01bd2c5b3b0)

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/36b529e0-c696-4d73-97f8-6b70a0f64145)

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/b5c24bdc-afec-43ad-9d20-e890d97e766a)


<p>
Configure SLA
<br>- Admin Panel -> Manage -> SLA </b>
<br>- Sev-A (1 hour, 24/7) </b>
<br>- Sev-B (4 hours, 24/7) </b>
<br>- Sev-C (8 hours, business hours) </b>
</p>

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/ea7043dc-7f1d-4902-acba-22268a8904c0)

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/f0d357ad-c7cd-4408-8ed4-d296670c5af0)

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/5a47c188-8932-4a30-8454-e1fc00ede0d8)

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/40b50df5-16e4-46d0-ad7c-e5b07272a658)

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/d9fea7d7-03d3-471b-bcf0-00eeb15d4f12)

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/6a820b78-ea60-447d-8141-9e942021f316)


<p>
Configure Help Topics
<br>- Admin Panel -> Manage -> Help Topics </b>
<br>- Personal Computer Issues </b>
<br>- Equipment Request </b>
<br>- Password Reset </b>
</p>

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/d6a50e5a-a7cc-4579-b7c8-ab60d3cb8996)

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/0c2fd2c4-6c11-488e-be63-21e4fec253da)

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/682be95f-0c65-49b3-b5c9-a4f913a75e77)

![image](https://github.com/IZEK4K/osticket-post-install-config/assets/90485066/60a3da11-05c5-4bcb-b028-d7d027f7f180)

Post Installation Setup Complete!




