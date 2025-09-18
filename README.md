<h1>Build a Virtual Machine (VM) Lab with VirtualBox</h1>



<h2>Description</h2>
I created a personal IT lab using VirtualBox to set up and configure multiple operating systems (Windows 11 and Ubuntu Linux). The goal was to gain hands-on experience with OS installation, system administration, and basic networking in a safe virtual environment.
<br />

<h2>Environments Used </h2>
- <b>Windows 11</b> 
- <b>Unbuntu</b> 
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
<img src="https://i.imgur.com/BpG26ro.png" height="60%" width="60%" alt="Build a Virtual Machine (VM) Lab with VirtualBox"/>
<br />
<br />
Set Up Virtual Box Manager:  <br/>
<img src="https://i.imgur.com/YjQCkrq.png" height="60%" width="60%" alt="Build a Virtual Machine (VM) Lab with VirtualBox"/>
<br />
<br />
Set Up First Virtual Machine: <br/>
<img src="https://i.imgur.com/YzHXCCZ.png" height="60%" width="60%" alt="Build a Virtual Machine (VM) Lab with VirtualBox"/>
<br />
<br />
Set Up Second Virtual Machine:  <br/>
<img src="https://i.imgur.com/yquOJBx.png" height="60%" width="60%" alt="Build a Virtual Machine (VM) Lab with VirtualBox"/>
<br />
<br />
Run System Upgrades(Patching):  <br/>
<img src="https://i.imgur.com/6GdXJIj.png" height="60%" width="60%" alt="Build a Virtual Machine (VM) Lab with VirtualBox"/>
<br />
<p align="center">  
Run Full-Upgrades: <br/>
<img src="https://i.imgur.com/TMGaywO.png" height="60%" width="60%" alt="Build a Virtual Machine (VM) Lab with VirtualBox"/>
<br />
<br />
Create a User in Linux:  <br/>
<img src="https://i.imgur.com/HaHg7fJ.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
Verify the User Exists:  <br/>
<img src="https://i.imgur.com/Ov5EOk3.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
Delete the User(Clean Up):  <br/>
<img src="https://i.imgur.com/8KDdW3E.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<br/>
Conducting Basic Network Checks:  <br/>
<img src="https://i.imgur.com/VKhQsNC.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
Displaying routing:  <br/>
<img src="https://i.imgur.com/XDBjo8m.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
Test Network to ensure internet connection exists:  <br/>
<img src="https://i.imgur.com/yWxIqrQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
Ping DNS Resolution to check for any DNS issues:  <br/>
<img src="https://i.imgur.com/oYojo40.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
Installation of Uncomplicated Firewall:  <br/>
<img src="https://i.imgur.com/8nX05Mc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
Check Firewall Status:  <br/>
<img src="https://i.imgur.com/eSjxqwl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
Enable FIrewall, Allow Web Traffic, and Reverify Firewall Status:  <br/>
<img src="https://i.imgur.com/bMPoYD5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
Install Apache for Web Page Test:  <br/>
<img src="https://i.imgur.com/Y3Fer9N.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
Start Apache:  <br/>
<img src="https://i.imgur.com/ERJ7vzS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
Verify Apache is running:  <br/>
<img src="https://i.imgur.com/7IUcNS1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
Test Apache on Virtual Machine Browser:  <br/>
<img src="https://i.imgur.com/I2Z7A5w.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<h2>Closing Notes:</h2>
This project successfully demonstrated the process of building a secure and functional virtual lab environment using VirtualBox and Ubuntu Linux. Through OS installation, user management, firewall configuration, and web server deployment, I gained practical skills in system administration and basic networking. This lab will serve as a foundation for more advanced IT and cybersecurity projects.
<br />
