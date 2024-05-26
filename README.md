<h1>Active Directory Home Lab</h1>


<h2>Description</h2>
In this home lab, we use Oracle Virtual Box to adding new user accounts to an internal network and connecting said users to the internet through a domain controller in Active Directory. Configuring and running this lab will help develop our understanding of Active Directory and Windows networking. When correctly executed, our users will have an IP address within the scope we set for the DHCP server.
</b>

<h2>Languages and Utilities Used</h2>

- PowerShell
- Active Directory

<h2>Environments Used </h2>

 - Windows 10
 - Server 2019
 
<h2>Program walk-through:</h2>

<br />
Create Domain Controller: <br/>
<img src="https://github.com/thethirdbirthday/Active-Directory/blob/6c7a8c425a4ad37ac90788a08732228f3e5bf11b/ad_1.PNG" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
Destinguish home internet and internal network:  <br/>
<img src="https://github.com/thethirdbirthday/Active-Directory/blob/8e11fbd13f3c7f92931649f6af4e0a81fe6129e2/ad_2.PNG" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
Add roles - Domain Services:  <br/>
<img src="https://github.com/thethirdbirthday/Active-Directory/blob/c56f4168b394a8ee4a9b3f5a7b3cf970400eb2ca/ad_3.PNG" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
Set DHCP scope:  <br/>
<img src="https://github.com/thethirdbirthday/Active-Directory/blob/09c3e5ab3206ffd6c4f1bf0df7dcb9bc02be1298/ad_35.PNG" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
Create Users with PowerShell Script:  <br/>
<img src="https://github.com/thethirdbirthday/Active-Directory/blob/38450070c8b55da60fb7d6030b146afb7ead7185/ad_39.PNG" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
Create a second VM connected only to internal network:  <br/>
<img src="https://github.com/thethirdbirthday/Active-Directory/blob/526843839ad02511e6ed99c83c8740c835c988b5/ad_46.PNG" height="80%" width="80%" alt="Active Directory"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
