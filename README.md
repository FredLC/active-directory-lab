<h1>Active Directory Lab</h1>

<h2>Description</h2>
This project's goal is to replicate a mini corporate environment using Active Directory. The lab consists of one Windows Server 2019 machine and a Windows 10 Pro client. The lab was created in Oracle VirtualBox. Future iterations of this project will utilize Microsoft Azure instead (or a combination of local and cloud using Azure AD Connect). A PowerShell script was also integrated to automate and facilitate user creation. The Windows Server machine will act as both a Domain Controller, DHCP server, Remote Access Server and default gateway.
<br />

<h2>Technologies and Environments Used </h2>

- <b>Windows 10 Pro</b>
- <b>Windows Server 2019</b>
- <b>PowerShell</b>
- <b>Oracle VirtualBox</b>

<h2>Lab walk-through:</h2>

<p align="center">
Project architecture: <br/>
<img src="https://i.imgur.com/YuNdDhq.png" height="80%" width="80%" alt="project architecture"/>
<br />
<br />
Basic VM info:  <br/>
<img src="https://i.imgur.com/pQ4MB49.png" height="80%" width="80%" alt="basic vm info"/>
<br />
<br />
RAM and CPU settings: <br/>
<img src="https://i.imgur.com/jr2LQVk.png" height="80%" width="80%" alt="ram and cpu settings"/>
<br />
<br />
Hard drive settings:  <br/>
<img src="https://i.imgur.com/wlTD8tx.png" height="80%" width="80%" alt="hard drive settings"/>
<br />
<br />
Added a network interface attached to internal network:  <br/>
<img src="https://i.imgur.com/K0fGpHA.png" height="80%" width="80%" alt="new network interface"/>
<br />
<br />
Final Windows Server VM settings:  <br/>
<img src="https://i.imgur.com/9cqVWIs.png" height="80%" width="80%" alt="Final Windows Server VM settings"/>
<br />
<br />
Server 2019 installation:  <br/>
<img src="https://i.imgur.com/fgp2upI.png" height="80%" width="80%" alt="server 2019 installation"/>
</p>
Start installation:  <br/>
<img src="https://i.imgur.com/Tv6ZnSX.png" height="80%" width="80%" alt="start installation"/>
</p>
Selecting operating system:  <br/>
<img src="https://i.imgur.com/e4k1JrF.png" height="80%" width="80%" alt="Selecting operating system"/>
</p>
Agree to license:  <br/>
<img src="https://i.imgur.com/ehz5P5X.png" height="80%" width="80%" alt="agree to license"/>
</p>
Select custom install:  <br/>
<img src="https://i.imgur.com/1TnIT5C.png" height="80%" width="80%" alt="select custom install"/>
</p>
Select partition:  <br/>
<img src="https://i.imgur.com/7Hw6pGJ.png" height="80%" width="80%" alt="select partition"/>
</p>
Installing Windows:  <br/>
<img src="https://i.imgur.com/sCmf4WV.png" height="80%" width="80%" alt="installing windows"/>
</p>
Default administrator account creation:  <br/>
<img src="https://i.imgur.com/oTl6Rq6.png" height="80%" width="80%" alt="default administrator account creation"/>
</p>
Renamed network interfaces:  <br/>
<img src="https://i.imgur.com/Y52Ho9g.png" height="80%" width="80%" alt="renamed network interfaces"/>
</p>
Modified internal NIC IP configuration:  <br/>
<img src="https://i.imgur.com/7PKKgdc.png" height="80%" width="80%" alt="modified internal NIC IP configuration"/>
</p>
Renamed machine to DC:  <br/>
<img src="https://i.imgur.com/8zvrsaa.png" height="80%" width="80%" alt="renamed to DC"/>
</p>
Install Active Direcoty Domain Services:  <br/>
<img src="https://i.imgur.com/PsUKI87.png" height="80%" width="80%" alt="install AD domain services"/>
</p>
Select role-based:  <br/>
<img src="https://i.imgur.com/zEnt9Mf.png" height="80%" width="80%" alt="select role-based"/>
</p>
Select destination server:  <br/>
<img src="https://i.imgur.com/XmAgtxq.png" height="80%" width="80%" alt="select destination server"/>
</p>
Select server roles:  <br/>
<img src="https://i.imgur.com/tre4VCO.png" height="80%" width="80%" alt="select server roles"/>
</p>
Select features (click next):  <br/>
<img src="https://i.imgur.com/uMy7QtV.png" height="80%" width="80%" alt="select features"/>
</p>
AD Domain Services (click next):  <br/>
<img src="https://i.imgur.com/RydKT5O.png" height="80%" width="80%" alt="AD domain services"/>
</p>
Launch installation:  <br/>
<img src="https://i.imgur.com/EcqmObk.png" height="80%" width="80%" alt="launch installation"/>
</p>
Promote this server to domain controller:  <br/>
<img src="https://i.imgur.com/4cIa7eI.png" height="80%" width="80%" alt="promote server to DC"/>
</p>
Launch installation:  <br/>
<img src="https://i.imgur.com/EcqmObk.png" height="80%" width="80%" alt="launch installation"/>
</p>
Launch installation:  <br/>
<img src="https://i.imgur.com/EcqmObk.png" height="80%" width="80%" alt="launch installation"/>
</p>
Launch installation:  <br/>
<img src="https://i.imgur.com/EcqmObk.png" height="80%" width="80%" alt="launch installation"/>
</p>
Launch installation:  <br/>
<img src="https://i.imgur.com/EcqmObk.png" height="80%" width="80%" alt="launch installation"/>
</p>
Launch installation:  <br/>
<img src="https://i.imgur.com/EcqmObk.png" height="80%" width="80%" alt="launch installation"/>
</p>
Launch installation:  <br/>
<img src="https://i.imgur.com/EcqmObk.png" height="80%" width="80%" alt="launch installation"/>
</p>
Launch installation:  <br/>
<img src="https://i.imgur.com/EcqmObk.png" height="80%" width="80%" alt="launch installation"/>
</p>
Launch installation:  <br/>
<img src="https://i.imgur.com/EcqmObk.png" height="80%" width="80%" alt="launch installation"/>
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
