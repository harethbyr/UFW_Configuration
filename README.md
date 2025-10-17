<h1>Uncomplicated Firewall Configuration</h1>



<h2>Description</h2>
 This project displays the setting up and configuration of the Uncomplicated Firewall in the Ubuntu Linux environment.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Terminal</b> 
- <b>Firewall configuration untilities (sudo, ufw, status, deny, allow)</b>
- <b>Oracle VirtualBox</b>

<h2>Environments Used </h2>

- <b>Virtual Environment</b>
- <b>Ubuntu Linux Distro</b>


<h2>Configuring UFW</h2>

<p align ="center">
 Boot up Ubuntu machine using virtual box: <br/>
<img src="https://i.imgur.com/4KGuVNj.png" height="80%" width="80%" alt=""/>
<br />
<br />
 Open the terminal application: <br/>
<img src="https://i.imgur.com/BSWi645.png" height="80%" width="80%" alt=""/>
<br />
<br />
 Check the Uncomplicated Firewall Status: <br/>
<img src="https://i.imgur.com/Ulpqyeb.png" height="80%" width="80%" alt=""/>
<br />
<br />
 Enable the Uncomplicated Firewall:  <br/>
<img src="https://i.imgur.com/STnVrjl.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Use Verbose to view more specific policies and configurations:  <br/>
<img src="https://i.imgur.com/BTIHZuR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 If defaults aren't set, the commands below can be used to set the default firewall rules: <br/>
<img src="https://i.imgur.com/0afMml3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Allow incoming connections coming from SSH (port 22), HTTP (port 80), and HTTPS (port 443):  <br/>
<img src="https://i.imgur.com/wucUvWS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 View UFW status in a numbered sequence to confirm: <br/>
<img src="https://i.imgur.com/8ndVyxP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Deny trafic incoming from FTP (port 21): <br/>
<img src="https://i.imgur.com/kTGvh7M.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>Adding Logging:</h2>

<p align="center">
 If logging is disabled, then the command below can be used to enable it: <br/>
<img src="https://i.imgur.com/9XYFecq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
  View stored logs: <br/>
<img src="https://i.imgur.com/OIzQ48n.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


