<p align="center">
<img src="https://i.imgur.com/niNd7I2.jpg" height="60%" width="60%" alt="Cybersecurity"/>
</p>

<h1>Active Directory Home Lab for Security Testing</h1>
I utilize an Active Directory home lab to test defensive/offensive security tools and concepts. <br />


<h2>Technology Utilized</h2>

- VMware Workstation Pro
- Various Offensvie and Defensive Security Tools
- Active Directory Domain Services
- PowerShell
- Bash

<h2>Operating Systems</h2>

- Windows Server 2022 Core
- Windows 11 Enterprise
- Kali Linux
- Ubuntu Linux

<h2>General Overview</h2>
I have created an Active Directory home lab to explore and learn different cybersecurity tools and concepts. This page will serve as a showcase of interesting things I have learned. My plan for this home lab is to deploy a SIEM/EDR solution. 

<h2>Creating the Machines</h2>

<p>
<img src="https://i.imgur.com/1aykBff.png" height="30%" width="30%" alt="VMware"/>
</p>
<p>
I created base template machines for Windows Server 2022 and Windows 11. New machines of either operating system can be cloned from these.
</p>
<br />

<h2>Setting up Active Directory</h2>

<p>
<img src="https://i.imgur.com/hAWWkjS.png" height="80%" width="80%" alt="Server 2022 Core"/>
</p>
<p>
<img src="https://i.imgur.com/EfCLQlF.png" height="80%" width="80%" alt="AD Deployment"/>
</p>
<p>
I installed Active Directory Domain Services on the Windows Server 2022 machine and turned it into a domain controller. I created a Windows 11 machine to act as a management client and a Windows 11 machine to be a workstation on the domain. I utilized a PowerShell script to generate domain users and passwords. 
</p>
<br />

<h2>Crackmapexec</h2>

<p><p align="center">
<img src="https://i.imgur.com/tDtwvJn.jpg" height="30%" width="30%" alt="CME logo"/>
</p>
<p>
<img src="https://i.imgur.com/RkTxmJp.png" height="80%" width="80%" alt="CME output"/>
</p>
<p>
I created a Kali Linux machine and utilized Crackmapexec to brute force passwords for domain users over SMB. 
</p>
<br />
