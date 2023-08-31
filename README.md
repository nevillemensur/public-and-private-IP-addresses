# public-and-private-IP-addresses
<p align="center">
<img src=https://i.imgur.com/QdWOADa.png"/>
</p>

<h1>AWS - Objectives</h1>
This tutorial outlines the differece between a private and public IP address. In this lab I will investigate the customer scenario then I will develop a solution to the customers issue in this lab.<br />

<h2>Ticket from the customer</h2>

Hello, Cloud Support!

We currently have one virtual private cloud (VPC with a CIDR range of 10.0.0.0/16. In this VPC, we have two Amazon Elastic Compute Cloud (Amazon EC2) instances: instance A and instance B. EVen though both are in the same subnet and have the same configurations with AWS resources, instance A cannot reach the internet, and instance B can reach the internet. I think it has something to do with the EC2 instances, but I'm not sure. I also had a question about using a public IP address such as 12.0.0.0/16 for a VPC that I would like to launch. What that cause any issues? Attached is our architecture for reference.


Thanks!

Jess

Cloud Admin

<p>
<img src=https://i.imgur.com/NpI57NW.png/>
</p>

<p>
Figure: The customer's architecture, which consists of a VPC, internet gateway, public subnet with instance A, and a public subnet with instance B.
</p>
<br />





<h2>Environments and Technologies Used</h2>

- AWS Management Console
- Remote Desktop SSH


<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create a resource group in Azure
- Create an Azure virtual machine windows 10, 4 vCPUs
- Add your PC connection in Microsoft Remote Desktop
- Enable Internet Information Services (IIS) WITH CGI
- Download and install PHP manager
- Download and install Rewrite module
- Create a directory folder in Windows C drive and label the folder PHP
- Download and install PHP 7.3.8
- Download and install C++
- Download and install My SQL server
- Open (IIS) as an Admin
- Register PHP from within IIS
  

<h2>Installation Steps</h2>

<p>
Start by creating a resource group inside Microsoft Azure. This resource group is where will store our virtual machines.
</p>

<p>
<img src="https://i.imgur.com/TmqScaP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Name your resource group "RG-osticket" and select a region. I recommend using a region that is near you. Then click "Review+Create"
</p>

<p>
<img src="https://i.imgur.com/7BcAZb8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Create a virtual machine.
</p>

<p>
<img src="https://i.imgur.com/tuJOw9A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Create a virtual machine that runs on Windows and add it to the resource group labeled "RG-osticket"
</p>

<p>
<img src="https://i.imgur.com/q3SgSuI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Create a username and password. The username and password will be used to log into remote desktop.
</p>

<p>
<img src="https://i.imgur.com/QQFd529.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
