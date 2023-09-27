<h1>Three Tier Archtecture</h1>


<h2>Description</h2>
The three-tier architecture, which includes the presentation tier, application tier, and database tier
<br />

<h2>Environments Used</h2>
  - <b>AWS Web Services</b> 

<h2>Features</h2>
- <b>VPC</b>
- <b>Subnet</b> 
- <b>Internet Gateway</b>
- <b>Route Table</b>
- <b>RDS</b>

<h2>Networking Resources</h2>

<p align="center">
VPC: <br/>
<img src="https://i.postimg.cc/gjkM5TK6/vpc.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
<br />
<br />
Subnet:  <br/>
<img src="https://i.postimg.cc/TYcm7J7n/ss.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Instances in a private subnet can connect to services outside VPC using a NAT gateway, but external services cannot connect directly to those instance: <br/>
<img src="https://i.postimg.cc/V6cjvfKc/44.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
