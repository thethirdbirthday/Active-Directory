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
Add AD Domain Services and appropriate roles: <br/>
<img src=https://github.com/thethirdbirthday/Active-Directory/blob/main/ad_3.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
