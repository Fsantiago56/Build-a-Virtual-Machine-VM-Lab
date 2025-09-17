<h1>Build a Virtual Machine (VM) Lab with VirtualBox</h1>



<h2>Description</h2>
I created a personal IT lab using VirtualBox to set up and configure multiple operating systems (Windows 11 and Ubuntu Linux). The goal was to gain hands-on experience with OS installation, system administration, and basic networking in a safe virtual environment..
<br />

<h2>Environments Used </h2>
- <b>Windows 11</b> 
<h2>Commands Used:</h2>
- <b>sudo adduser labuser (creates new user account)<br />
- <b>cat /etc/passwd | grep labuser (Verify User Exists)<br />
- <b>sudo deluser labuser (Deletes User)<br />
- <b>ip addr show (Shows Network addresses)<br />
- <b>ip route (Displays Routing)<br />
- <b>ping -c 4 'insert IP Address' (Test internet connection)<br />
- <b>ping -c 4 'insert website' (Test DNS resolution)<br />
- <b>sudo apt install ufw -y (Install UFW)<br />
- <b>sudo ufw status (Check Firewall status)<br />
- <b>sudo enable ufw enable (Enable Firewall)<br />
- <b>sudo ufw allow 80/tcp (Allow HTTP Traffic)<br />
- <b>sudo apt install apache2 -y (Install Apache) <br />
- <b>sudo systemctl status apache2 (Verifying Apache is running)<br />
<h2>Lab walk-through:</h2>
<p align="center">
Download Virtual Box: <br/>
<img src="https://i.imgur.com/BpG26ro.png" height="80%" width="80%" alt="Build a Virtual Machine (VM) Lab with VirtualBox"/>
<br />
<br />
Set Up Virtual Box Manager:  <br/>
<img src="https://i.imgur.com/YjQCkrq.png" height="80%" width="80%" alt="Build a Virtual Machine (VM) Lab with VirtualBox"/>
<br />
<br />
Set Up First Virtual Machine: <br/>
<img src="https://i.imgur.com/YzHXCCZ.png" height="80%" width="80%" alt="Build a Virtual Machine (VM) Lab with VirtualBox"/>
<br />
<br />
Set Up Second Virtual Machine:  <br/>
<img src="https://i.imgur.com/yquOJBx.png" height="80%" width="80%" alt="Build a Virtual Machine (VM) Lab with VirtualBox"/>
<br />
<br />
Run System Upgrades(Patching):  <br/>
<img src="https://i.imgur.com/6GdXJIj.png" height="80%" width="80%" alt="Build a Virtual Machine (VM) Lab with VirtualBox"/>
<br />
<br />
<h2>Learning Point</h2>
Initially, I ran sudo (sudo apt update && sudo apt upgrade -y) to ensure an successful update to package index and upgraded available software packages. This ensures the system is patched, stable, and secure. Then notice I was unsure why certain packages remained unpatched, which led me to run (sudo apt full-upgrade) to ugrade all packages to their latest version.
<br />
<br />
<p align="center">  
Run Full-Upgrades: <br/>
<img src="https://i.imgur.com/TMGaywO.png" height="80%" width="80%" alt="Build a Virtual Machine (VM) Lab with VirtualBox"/>
<br />
<br />
Create a User in Linux:  <br/>
<img src="https://i.imgur.com/HaHg7fJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
Verify the User Exists:  <br/>
<img src="https://i.imgur.com/Ov5EOk3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
Delete the User(Clean Up):  <br/>
<img src="https://i.imgur.com/8KDdW3E.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
Conducting Basic Network Checks:  <br/>
<img src="https://i.imgur.com/VKhQsNC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
Displaying routing:  <br/>
<img src="https://i.imgur.com/XDBjo8m.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
Test Network to ensure internet connection exists:  <br/>
<img src="https://i.imgur.com/yWxIqrQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
Ping DNS Resolution to check for any DNS issues:  <br/>
<img src="https://i.imgur.com/oYojo40.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/><!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
<!--
**joshmadakor1/joshmadakor1** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
