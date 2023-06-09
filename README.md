<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- Active Directory

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Sample 1
- Sample 2
- Sample 3
- Sample 4

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/iEohnnU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>[
](https://i.imgur.com/DXAdNLJ.png)<p>
The image above is showing Resource Groups and Virtual Machines running in Microsoft Azure. Multiple IP addresses connected to the subnet up to the virtual machines.
</p>
<br />

<p>
<img src="https://i.imgur.com/MxdkGj0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p> Here displays the Remote Desktop made for one of the Virtual Machines. This Remote Desktop was made on the Mac Book version 
</p>
<br />

<p>
<img src="https://i.imgur.com/aXrWjdU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The example above is showing IIS instillation. IIS was use in this demonstration to download & install CGI to creat the OS-Ticketing software.  
</p>
<br />

<p align="center">
<img src="https://imgur.com/bUuL616.png alt="Traffic Examination"/>  
</p>
<br />
<br />

<h2>Azure Active Directory Overview (User & Group Creation/Access Management Configuration</h2>

In this tutorial I demonstrate Azure Active Directory user account creation, group creation and access management configuration.


<h2>Environments and Technologies Used</h2>

- Microsoft Azure Cloud Platform


<h2>Resources Used </h2>

- Azure Resource Groups
- Access Control (IAM)


<h2>Video Demonstrations</h2>

1. Configure and Observe Tenant-Level Global Reader

   - Create a user within Azure Active Directory (AAD) (username: globalreaderjohn)
   - Assign Tenant-Level Global Reader
   - In a new browser/incognito, log in as globalreaderjohn and observe result of being a Tenant Level “Global Reader” (Users, Active Directory)
   - Close browser/incognito when satisfied
   
   
   [![Part 1](https://i.vimeocdn.com/video/1650062289-7ccc552d70b43340cca69ae434e376aa8f955e319d47e0fecf7aada8277bf8fd-d_295x166?r=pad)](https://vimeo.com/814446209 "Azure AD Lab Part 1")
   <br />
   <br />
   
   
2. Configure and Observer Subscription Reader
    - Back in main browser, create another user within AAD  (username: subreaderjane)
    - Assign Subscription-Level Reader 
    - In a new browser/incognito, log in as subreaderjane and observe result of being a Subscription Level “Global Reader” (Subscriptions, Resource Groups) 
    - Close browser/incognito when satisfied
    
   [![Part 2](https://i.vimeocdn.com/video/1650062530-df7c05e5d4d7947027ec4343beb30337a184bbca53d1776856bfb94d7c29efd3-d_295x166?r=pad)](https://vimeo.com/814445455 "Azure AD Lab Part 2")
   <br />
   <br /> 
   
   
 3. Configure and Observe Resource Group Contributor (like an admin)
    - Back in main browser, create another user within AAD  (username: rgcontributordave)
    - Create a new resource group called “Permissions-Tester”
    - Assign Resource Group-level Contributor and  Subscription Level Reader
    - For our resource group “Permissions-Tester” assign Contributor Permissions
    - In a new browser/incognito, log in as rgcontributordave and observe result of being a Subscription Level Reader and Resource Group-level Contributor
    - Observe the result of being a Resource Group Level Contributor (Storage Account Creation)
    
    
   [![Part 3](https://i.vimeocdn.com/video/1650062688-f002defe9163278411c198fc03cde5436e68fad140f57c2b66cfed3eb049118f-d_295x166?r=pad)](https://vimeo.com/814445527 "Azure AD Lab Part 3")
   <br />
   <br />
