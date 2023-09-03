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
<img src="https://i.imgur.com/8AdeeGp.png" height="80%" width="80%" alt="select destination server"/>
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
Created new domain:  <br/>
<img src="https://i.imgur.com/zKDeILT.png" height="80%" width="80%" alt="created new domain"/>
</p>
Type in password:  <br/>
<img src="https://i.imgur.com/B3gq1d8.png" height="80%" width="80%" alt="type in password"/>
</p>
NetBIOS domain name is automatically generated:  <br/>
<img src="https://i.imgur.com/tQWcmao.png" height="80%" width="80%" alt="NetBIOS domain name"/>
</p>
DNS options (click next):  <br/>
<img src="https://i.imgur.com/xnW9OZE.png" height="80%" width="80%" alt="DNS options"/>
</p>
AD database and SYSVOL paths are automatically populated (click next):  <br/>
<img src="https://i.imgur.com/9sWM5ao.png" height="80%" width="80%" alt="paths"/>
</p>
Review selections (click next):  <br/>
<img src="https://i.imgur.com/GYgoM5n.png" height="80%" width="80%" alt="review selections"/>
</p>
Click install after all checks pass:  <br/>
<img src="https://i.imgur.com/iEWSrm9.png" height="80%" width="80%" alt="install"/>
</p>
Created new admin user:  <br/>
<img src="https://i.imgur.com/emrtUKk.png" height="80%" width="80%" alt="created new admin user"/>
</p>
Added new user to domain admins group:  <br/>
<img src="https://i.imgur.com/cY07CBl.png" height="80%" width="80%" alt="added new user to domain admins"/>
</p>
Added remote access server role for NAT networking:  <br/>
<img src="https://i.imgur.com/FDdVHcB.png" height="80%" width="80%" alt="added remote access server role"/>
</p>
Add features:  <br/>
<img src="https://i.imgur.com/cE7Ylur.png" height="80%" width="80%" alt="add features"/>
</p>
Add routing (RAS is automatically checked):  <br/>
<img src="https://i.imgur.com/Sq2rwZH.png" height="80%" width="80%" alt="add routing"/>
</p>
Web server role (click next):  <br/>
<img src="https://i.imgur.com/1pl02qu.png" height="80%" width="80%" alt="web server role"/>
</p>
Select role services (click next):  <br/>
<img src="https://i.imgur.com/FgFPg7h.png" height="80%" width="80%" alt="select role services"/>
</p>
Click install:  <br/>
<img src="https://i.imgur.com/vKyTL8D.png" height="80%" width="80%" alt="click install"/>
</p>
Go to tools->Routing and Remote Access to configure NAT:  <br/>
<img src="https://i.imgur.com/za6cFdQ.png" height="80%" width="80%" alt="configure NAT"/>
</p>
Select Network Address Translation (NAT):  <br/>
<img src="https://i.imgur.com/v4iUUPr.png" height="80%" width="80%" alt="select NAT"/>
</p>
Select public (Internet) network interface:  <br/>
<img src="https://i.imgur.com/Ws6uQQf.png" height="80%" width="80%" alt="select public interface"/>
</p>
Click finish:  <br/>
<img src="https://i.imgur.com/lERANVu.png" height="80%" width="80%" alt="click finish"/>
</p>
Add DHCP server:  <br/>
<img src="https://i.imgur.com/adCTLgd.png" height="80%" width="80%" alt="add DHCP server"/>
</p>
Click add features:  <br/>
<img src="https://i.imgur.com/Qe1TjSe.png" height="80%" width="80%" alt="click add features"/>
</p>
Select DHCP server and click next:  <br/>
<img src="https://i.imgur.com/9rfMM1e.png" height="80%" width="80%" alt="select DHCP server"/>
</p>
Install:  <br/>
<img src="https://i.imgur.com/grhIgYW.png" height="80%" width="80%" alt="install DHCP"/>
</p>
In Tools -> DHCP -> Expand domain and right click on IPv4, then click New Scope:  <br/>
<img src="https://i.imgur.com/uDnl4GM.png" height="80%" width="80%" alt="new scope"/>
</p>
I named the scope the same as the range:  <br/>
<img src="https://i.imgur.com/lnQsf1p.png" height="80%" width="80%" alt="name scope"/>
</p>
Create range:  <br/>
<img src="https://i.imgur.com/N8McVa6.png" height="80%" width="80%" alt="create range"/>
</p>
We don't want any exclusion, click next:  <br/>
<img src="https://i.imgur.com/VzSqQ5z.png" height="80%" width="80%" alt="no exclusions"/>
</p>
Leaving lease duration as default is fine for the lab:  <br/>
<img src="https://i.imgur.com/5HP6YqP.png" height="80%" width="80%" alt="lease duration"/>
</p>
Select yes to configure options:  <br/>
<img src="https://i.imgur.com/OHpMcg1.png" height="80%" width="80%" alt="select yes"/>
</p>
Add domain controller address as default gateway:  <br/>
<img src="https://i.imgur.com/9Mi1FJb.png" height="80%" width="80%" alt="default gateway"/>
</p>
Add domain controller address for the DNS server:  <br/>
<img src="https://i.imgur.com/pLjYO0W.png" height="80%" width="80%" alt="dns server"/>
</p>
Click next for WINS servers:  <br/>
<img src="https://i.imgur.com/iuVa9JB.png" height="80%" width="80%" alt="wins servers"/>
</p>
Click yes to activate the scope:  <br/>
<img src="https://i.imgur.com/imnCRBL.png" height="80%" width="80%" alt="activate scope"/>
</p>
Click finish to complete the new scope:  <br/>
<img src="https://i.imgur.com/g8SDJyY.png" height="80%" width="80%" alt="finish scope"/>
</p>
:  <br/>
<img src="https://i.imgur.com/iuVa9JB.png" height="80%" width="80%" alt="wins servers"/>
</p>

<h3>Time to install Windows 10! The client VM configuration is the same as the Windows Server machine. The only difference is that there is one network interface on the internal network, no public interface.</h3>

Click next for WINS servers:  <br/>
<img src="https://i.imgur.com/iuVa9JB.png" height="80%" width="80%" alt="wins servers"/>
</p>
Click next for WINS servers:  <br/>
<img src="https://i.imgur.com/iuVa9JB.png" height="80%" width="80%" alt="wins servers"/>
</p>
Click next for WINS servers:  <br/>
<img src="https://i.imgur.com/iuVa9JB.png" height="80%" width="80%" alt="wins servers"/>
</p>
Click next for WINS servers:  <br/>
<img src="https://i.imgur.com/iuVa9JB.png" height="80%" width="80%" alt="wins servers"/>
</p>
Click next for WINS servers:  <br/>
<img src="https://i.imgur.com/iuVa9JB.png" height="80%" width="80%" alt="wins servers"/>
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
