<h1>Active Directory home Lab</h1>


<h2>Description</h2>
Projet involves using Oracle Virtual Box to create a VM Domain Controller to connect a second VM client to the internet through an internal network. A PowerShell script is used to create a bulk of user accounts. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Active Directory/b>

<h2>Environments Used </h2>

- <b>Windows 10</b>
- <b>Server 2019</b>

<h2>Program walk-through:</h2>

<p align="center">
Create a Domain Controller VM installed with Server 2019: <br/>
<img src="https://github.com/thethirdbirthday/Active-Directory/blob/main/ad_1.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Distinguish home internet and internal network:  <br/>
<img src="https://github.com/thethirdbirthday/Active-Directory/blob/main/ad_2.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Add Active Directory Domain Services: <br/>
<img src="https://github.com/thethirdbirthday/Active-Directory/blob/8cf3a9f5c735d42d45c55cfb79462702e2eed85e/ad_3.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create admin account: <br/>
<img src="https://github.com/thethirdbirthday/Active-Directory/blob/d16bfe521e26cce607b68e6115dadc69c66e12a3/images/ad_5.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Set DHCP IP address scope:  <br/>
<img src="https://github.com/thethirdbirthday/Active-Directory/blob/3d1348440261b9f3aeda47158482a7c1f5d75ad0/ad_35.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create User Accounts with PowerShell script:  <br/>
<img src="https://github.com/thethirdbirthday/Active-Directory/blob/3d1348440261b9f3aeda47158482a7c1f5d75ad0/ad_39.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create client VM connected only to internal network :  <br/>
<img src="https://github.com/thethirdbirthday/Active-Directory/blob/3d1348440261b9f3aeda47158482a7c1f5d75ad0/ad_46.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Client account will be automatically provided an address within DHCP:  <br/>
<img src="https://github.com/thethirdbirthday/Active-Directory/blob/6213365fb54b9b32adfe5fd92645ef47120e44d9/ad_homelab_outline.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
