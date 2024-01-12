
![download](https://github.com/jmart375/pfSense/assets/91294710/6231c28f-34dc-4a42-84c4-f4377e62d897)


<h1>Setting Up pfSense on VirtualBox</h1>


<h2>Description</h2>
In this project, the user successfully set up a secure network environment by deploying pfSense on a VirtualBox virtual machine,  configuring the system, and ensuring optimal firewall settings and network configurations for enhanced security and performance.
<br />


<h2>Languages Used</h2>

- <b>n/a</b> 


<h2>Environments Used </h2>

- <b>Oracle VM VirtualBox</b> (x86)
- <b>pfSense software. An open source firewall and router.</b>

<h2>Project walk-through:</h2>

<p align="center">
1. Download pfSense ISO:
visit the pfSense download page: pfSense Download and choose the architecture (64-bit): <br/>
<img src="https://imgur.com/8ZxjFG2.png" height="80%" width="80%" alt="pfSense"/>
<br />
<br />
2. Install VirtualBox and configure virtual machine settings:  <br/>
<img src="https://imgur.com/s2nblqH.png" height="80%" width="80%" alt="pfSense"/>
<br />
<br />
3. Start the VM and install pfSense. i.e., follow on-screen instruction and assign interfaces as needed (e..g, WAN and LAN). <br/>

![lab 2 (B)](https://github.com/jmart375/pfSense/assets/91294710/65386760-8707-47ba-b257-12dba8d8b474)


<br />
<br />
4. Complete pfSense Configuration: <br/>

![lab 2 (c)](https://github.com/jmart375/pfSense/assets/91294710/16ce5523-793a-4734-9470-f6517b173f30)

<br />
<br />
5. Access pfSense Web Interface: 
Open a web browser and enter the LAN IP address you set during the setup. Log in using the default credentials (admin/ password).  <br/>

<br />![lab 2](https://github.com/jmart375/pfSense/assets/91294710/2326e2d1-c32a-4050-9f5a-0d0fb63b097e)

6. Configure Firewall Rules, DHCP, etc.:
Access the pfSense webConfigurator to configure firewall rules, DHCP settings, and any addtional services needed.   <br/>
<img src="https://imgur.com/GpUb5kd.png" height="80%" width="80%" alt="pfSense"/>
<br />
<br />
Project complete:  <br/>
<img src="https://imgur.com/izPwC3k.png" height="80%" width="80%" alt="pfSense"/>
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
