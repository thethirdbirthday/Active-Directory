<h1>Active Directory home Lab</h1>


<h2>Description</h2>
Projet involves using Oracle VirtualBox to create a private network that allows new users a DHCP provided IP address to connect to the internet through NAT.A PowerShell script is used to create a bulk of user accounts. New users can also be simply be created and added manually. Great hands-on experience that demonstrates concepts in networking and cyber security.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Active Directory</b>
- <b>PowerShell</b>
- <b> Oracle Virtual Box </b>

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
<br/>
<br />
Add Active Directory Domain Services: <br/>
<img src="https://github.com/thethirdbirthday/Active-Directory/blob/8cf3a9f5c735d42d45c55cfb79462702e2eed85e/ad_3.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br/>
Create admin account: <br/>
<img src="https://github.com/thethirdbirthday/Active-Directory/blob/d16bfe521e26cce607b68e6115dadc69c66e12a3/images/ad_5.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br/>
Add Remote Access: <br/>
<img src="https://github.com/thethirdbirthday/Active-Directory/blob/2e89cf54db7acecf70c92f16cfd937e15d21f40c/images/ad_NAT.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 
<br/>
Configure NAT in Routing and Remote Access: <br/>
<img src="https://github.com/thethirdbirthday/Active-Directory/blob/2e89cf54db7acecf70c92f16cfd937e15d21f40c/images/ad_remoteaccess.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />  
<br />
Set DHCP server scope of IP addresses:  <br/>
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
Client IP address and default gateway will correspond with Domain Controller and DHCP:  <br/>
<img src="https://github.com/thethirdbirthday/Active-Directory/blob/2e89cf54db7acecf70c92f16cfd937e15d21f40c/images/ad_usercomplete.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
