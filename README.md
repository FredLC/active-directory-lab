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
<br />
<br />
Start installation:  <br/>
<img src="https://i.imgur.com/Tv6ZnSX.png" height="80%" width="80%" alt="start installation"/>
<br />
<br />
Selecting operating system:  <br/>
<img src="https://i.imgur.com/e4k1JrF.png" height="80%" width="80%" alt="Selecting operating system"/>
<br />
<br />
Agree to license:  <br/>
<img src="https://i.imgur.com/ehz5P5X.png" height="80%" width="80%" alt="agree to license"/>
<br />
<br />
Select custom install:  <br/>
<img src="https://i.imgur.com/1TnIT5C.png" height="80%" width="80%" alt="select custom install"/>
<br />
<br />
Select partition:  <br/>
<img src="https://i.imgur.com/7Hw6pGJ.png" height="80%" width="80%" alt="select partition"/>
<br />
<br />
Installing Windows:  <br/>
<img src="https://i.imgur.com/sCmf4WV.png" height="80%" width="80%" alt="installing windows"/>
<br />
<br />
Default administrator account creation:  <br/>
<img src="https://i.imgur.com/oTl6Rq6.png" height="80%" width="80%" alt="default administrator account creation"/>
<br />
<br />
Renamed network interfaces:  <br/>
<img src="https://i.imgur.com/Y52Ho9g.png" height="80%" width="80%" alt="renamed network interfaces"/>
<br />
<br />
Modified internal NIC IP configuration:  <br/>
<img src="https://i.imgur.com/7PKKgdc.png" height="80%" width="80%" alt="modified internal NIC IP configuration"/>
<br />
<br />
Renamed machine to DC:  <br/>
<img src="https://i.imgur.com/8zvrsaa.png" height="80%" width="80%" alt="renamed to DC"/>
<br />
<br />
Install Active Direcoty Domain Services:  <br/>
<img src="https://i.imgur.com/PsUKI87.png" height="80%" width="80%" alt="install AD domain services"/>
<br />
<br />
Select role-based:  <br/>
<img src="https://i.imgur.com/zEnt9Mf.png" height="80%" width="80%" alt="select role-based"/>
<br />
<br />
Select destination server:  <br/>
<img src="https://i.imgur.com/8AdeeGp.png" height="80%" width="80%" alt="select destination server"/>
<br />
<br />
Select server roles:  <br/>
<img src="https://i.imgur.com/tre4VCO.png" height="80%" width="80%" alt="select server roles"/>
<br />
<br />
Select features (click next):  <br/>
<img src="https://i.imgur.com/uMy7QtV.png" height="80%" width="80%" alt="select features"/>
<br />
<br />
AD Domain Services (click next):  <br/>
<img src="https://i.imgur.com/RydKT5O.png" height="80%" width="80%" alt="AD domain services"/>
<br />
<br />
Launch installation:  <br/>
<img src="https://i.imgur.com/EcqmObk.png" height="80%" width="80%" alt="launch installation"/>
<br />
<br />
Promote this server to domain controller:  <br/>
<img src="https://i.imgur.com/4cIa7eI.png" height="80%" width="80%" alt="promote server to DC"/>
<br />
<br />
Created new domain:  <br/>
<img src="https://i.imgur.com/zKDeILT.png" height="80%" width="80%" alt="created new domain"/>
<br />
<br />
Type in password:  <br/>
<img src="https://i.imgur.com/B3gq1d8.png" height="80%" width="80%" alt="type in password"/>
<br />
<br />
NetBIOS domain name is automatically generated:  <br/>
<img src="https://i.imgur.com/tQWcmao.png" height="80%" width="80%" alt="NetBIOS domain name"/>
<br />
<br />
DNS options (click next):  <br/>
<img src="https://i.imgur.com/xnW9OZE.png" height="80%" width="80%" alt="DNS options"/>
<br />
<br />
AD database and SYSVOL paths are automatically populated (click next):  <br/>
<img src="https://i.imgur.com/9sWM5ao.png" height="80%" width="80%" alt="paths"/>
<br />
<br />
Review selections (click next):  <br/>
<img src="https://i.imgur.com/GYgoM5n.png" height="80%" width="80%" alt="review selections"/>
<br />
<br />
Click install after all checks pass:  <br/>
<img src="https://i.imgur.com/iEWSrm9.png" height="80%" width="80%" alt="install"/>
<br />
<br />
Created new admin user:  <br/>
<img src="https://i.imgur.com/emrtUKk.png" height="80%" width="80%" alt="created new admin user"/>
<br />
<br />
Added new user to domain admins group:  <br/>
<img src="https://i.imgur.com/cY07CBl.png" height="80%" width="80%" alt="added new user to domain admins"/>
<br />
<br />
Added remote access server role for NAT networking:  <br/>
<img src="https://i.imgur.com/FDdVHcB.png" height="80%" width="80%" alt="added remote access server role"/>
<br />
<br />
Add features:  <br/>
<img src="https://i.imgur.com/cE7Ylur.png" height="80%" width="80%" alt="add features"/>
<br />
<br />
Add routing (RAS is automatically checked):  <br/>
<img src="https://i.imgur.com/Sq2rwZH.png" height="80%" width="80%" alt="add routing"/>
<br />
<br />
Web server role (click next):  <br/>
<img src="https://i.imgur.com/1pl02qu.png" height="80%" width="80%" alt="web server role"/>
<br />
<br />
Select role services (click next):  <br/>
<img src="https://i.imgur.com/FgFPg7h.png" height="80%" width="80%" alt="select role services"/>
<br />
<br />
Click install:  <br/>
<img src="https://i.imgur.com/vKyTL8D.png" height="80%" width="80%" alt="click install"/>
<br />
<br />
Go to tools->Routing and Remote Access to configure NAT:  <br/>
<img src="https://i.imgur.com/za6cFdQ.png" height="80%" width="80%" alt="configure NAT"/>
<br />
<br />
Select Network Address Translation (NAT):  <br/>
<img src="https://i.imgur.com/v4iUUPr.png" height="80%" width="80%" alt="select NAT"/>
<br />
<br />
Select public (Internet) network interface:  <br/>
<img src="https://i.imgur.com/Ws6uQQf.png" height="80%" width="80%" alt="select public interface"/>
<br />
<br />
Click finish:  <br/>
<img src="https://i.imgur.com/lERANVu.png" height="80%" width="80%" alt="click finish"/>
<br />
<br />
Add DHCP server:  <br/>
<img src="https://i.imgur.com/adCTLgd.png" height="80%" width="80%" alt="add DHCP server"/>
<br />
<br />
Click add features:  <br/>
<img src="https://i.imgur.com/Qe1TjSe.png" height="80%" width="80%" alt="click add features"/>
<br />
<br />
Select DHCP server and click next:  <br/>
<img src="https://i.imgur.com/9rfMM1e.png" height="80%" width="80%" alt="select DHCP server"/>
<br />
<br />
Install:  <br/>
<img src="https://i.imgur.com/grhIgYW.png" height="80%" width="80%" alt="install DHCP"/>
<br />
<br />
In Tools -> DHCP -> Expand domain and right click on IPv4, then click New Scope:  <br/>
<img src="https://i.imgur.com/uDnl4GM.png" height="80%" width="80%" alt="new scope"/>
<br />
<br />
I named the scope the same as the range:  <br/>
<img src="https://i.imgur.com/lnQsf1p.png" height="80%" width="80%" alt="name scope"/>
<br />
<br />
Create range:  <br/>
<img src="https://i.imgur.com/N8McVa6.png" height="80%" width="80%" alt="create range"/>
<br />
<br />
We don't want any exclusion, click next:  <br/>
<img src="https://i.imgur.com/VzSqQ5z.png" height="80%" width="80%" alt="no exclusions"/>
<br />
<br />
Leaving lease duration as default is fine for the lab:  <br/>
<img src="https://i.imgur.com/5HP6YqP.png" height="80%" width="80%" alt="lease duration"/>
<br />
<br />
Select yes to configure options:  <br/>
<img src="https://i.imgur.com/OHpMcg1.png" height="80%" width="80%" alt="select yes"/>
<br />
<br />
Add domain controller address as default gateway:  <br/>
<img src="https://i.imgur.com/9Mi1FJb.png" height="80%" width="80%" alt="default gateway"/>
<br />
<br />
Add domain controller address for the DNS server:  <br/>
<img src="https://i.imgur.com/pLjYO0W.png" height="80%" width="80%" alt="dns server"/>
<br />
<br />
Click next for WINS servers:  <br/>
<img src="https://i.imgur.com/iuVa9JB.png" height="80%" width="80%" alt="wins servers"/>
<br />
<br />
Click yes to activate the scope:  <br/>
<img src="https://i.imgur.com/imnCRBL.png" height="80%" width="80%" alt="activate scope"/>
<br />
<br />
Click finish to complete the new scope:  <br/>
<img src="https://i.imgur.com/g8SDJyY.png" height="80%" width="80%" alt="finish scope"/>
<br />
<br />
</p>

<h3>Time to install Windows 10! The client VM configuration is the same as the Windows Server machine. The only difference is that there is one network interface on the internal network, no public interface. The installation is also the same up until the final configurations.</h3>

<p>
After the Windows 10 files have been installed, time for some user configurations:  <br/>
<img src="https://i.imgur.com/oveVydd.png" height="80%" width="80%" alt="select region"/>
<br />
<br />
Select appropriate keyboard layout:  <br/>
<img src="https://i.imgur.com/iuVa9JB.png" height="80%" width="80%" alt="keyboard layout"/>
<br />
<br />
Click skip for secondary keyboard layout:  <br/>
<img src="https://i.imgur.com/HNCzAWE.png" height="80%" width="80%" alt="secondary keyboard layout"/>
<br />
<br />
Select I don't have internet:  <br/>
<img src="https://i.imgur.com/2sqfpyl.png" height="80%" width="80%" alt="no internet"/>
<br />
<br />
Click continue with limited setup:  <br/>
<img src="https://i.imgur.com/V3U6r7r.png" height="80%" width="80%" alt="limited setup"/>
<br />
<br />
Enter any user name, it doesn't matter for now:  <br/>
<img src="https://i.imgur.com/Zl9mfJQ.png" height="80%" width="80%" alt="username"/>
<br />
<br />
No need to enter a password:  <br/>
<img src="https://i.imgur.com/Or9I9wh.png" height="80%" width="80%" alt="password"/>
<br />
<br />
Uncheck all privacy settings:  <br/>
<img src="https://i.imgur.com/BmR0A7A.png" height="80%" width="80%" alt="uncheck privacy settings"/>
<br />
<br />
Click not now on Cortana screen:  <br/>
<img src="https://i.imgur.com/TjgMrgX.png" height="80%" width="80%" alt="cortana screen"/>
<br />
<br />
While Windows 10 is installing, I'm running a PowerShell script to create a thousand users:  <br/>
<img src="https://i.imgur.com/wmGvFaZ.png" height="80%" width="80%" alt="powershell script execution"/>
<br />
<br />
After Windows 10 has finished installed, I'll check the connectivity:  <br/>
<img src="https://i.imgur.com/yHXLvhm.png" height="80%" width="80%" alt="check connectivity"/>
<br />
<br />
I joined the client to the domain and renamed the PC at the same time:  <br/>
<img src="https://i.imgur.com/oFC8OPK.png" height="80%" width="80%" alt="join domain"/>
<br />
<br />
Checking DHCP leases to see if everything works:  <br/>
<img src="https://i.imgur.com/8r24Jvl.png" height="80%" width="80%" alt="DHCP leases"/>
<br />
<br />
Checking if client computer has successfully joined the domain:  <br/>
<img src="https://i.imgur.com/JnmEVwJ.png" height="80%" width="80%" alt="checking computers"/>
<br />
<br />
Finally, I'll test to see if I can sign in with any of the newly created users:  <br/>
<img src="https://i.imgur.com/9eJ8ArO.png" height="80%" width="80%" alt="testing sign in"/>
<br />
<br/>
<img src="https://i.imgur.com/UMnER1R.png" height="80%" width="80%" alt="whoami"/>
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
