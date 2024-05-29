<h1>JActive Directory Home Lab</h1>


<h2>Description</h2>
Project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Oracle VirtualBox</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>
- <b>Server 2019</b>

<h2>Program walk-through:</h2>

<p align="center">
Create a Domain Controller VM in Virtual Box: <br/>
<img src="https://github.com/thethirdbirthday/Active-Directory/blob/2e1a4e95db718910d63a04508dfda34b9c1a4962/ad_1.PNG" height="80%" width="80%" alt="Active Directory Home Lab Steps"/>
<br />
<br />
With Server 2019 installed, distinguish home internet from internal network :  <br/>
<img src="https://github.com/thethirdbirthday/Active-Directory/blob/2f651b816539a522e124434c158652ce7092b1a6/ad_2.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Add roles - Domain Services: <br/>
<img src="https://github.com/thethirdbirthday/Active-Directory/blob/2f651b816539a522e124434c158652ce7092b1a6/ad_3.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Set the scope of domain addresses to be assigned to new users:  <br/>
<img src="https://github.com/thethirdbirthday/Active-Directory/blob/2f651b816539a522e124434c158652ce7092b1a6/ad_35.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create new users using PowerShell script:  <br/>
<img src="https://github.com/thethirdbirthday/Active-Directory/blob/2f651b816539a522e124434c158652ce7092b1a6/ad_39.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Connect second Client VM solely to internal network:  <br/>
<img src="https://github.com/thethirdbirthday/Active-Directory/blob/2f651b816539a522e124434c158652ce7092b1a6/ad_46.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
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
