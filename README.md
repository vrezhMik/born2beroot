# born2beroot
<ol>
  <li>
    <a href="#install">Instalation</a>
   </li>
  <li>
    <a href="#sudo">Installing sudo and adding users</a>
  </li>
  <li>
    <a href="#ssh">Installing SSH</a>
  </li>
    <li>
    <a href="#pw">Setting Password</a>
  </li>
</ol>

<h1 id="install">1.Installation</h1>
<p>During this project we will use Debian OS<br>
  For installation you will need to download :<br>
  <a href="https://www.virtualbox.org/wiki/Downloads">VirtualBox</a><br>
  <a href="https://www.debian.org/download">Debian OS </a><br>
 </p>
 <br>
 <br>
<h2><b>Virtual Box Installation </b></h2>
<img width="845" alt="Screen Shot 2022-04-30 at 23 14 47" src="https://user-images.githubusercontent.com/38406975/166120976-981e0d2a-e66d-4ca7-9545-71bfae9d6596.png">
<p align = "center">After installation of VBox open the app and press the "New" button</p>
<img width="659" alt="Screen Shot 2022-04-30 at 23 15 01" src="https://user-images.githubusercontent.com/38406975/166121213-4198c10f-bb9e-4520-834a-43cf731b4e15.png">
<p align = "center">Write your box name and choose it's type</p>
<img width="657" alt="Screen Shot 2022-04-30 at 23 15 22" src="https://user-images.githubusercontent.com/38406975/166121244-ce642cce-9bf0-4fc0-be6a-f36e7fd2e663.png">
<p align = "center">Choose memory size you need or leave it default</p>
<img width="659" alt="Screen Shot 2022-04-30 at 23 15 31" src="https://user-images.githubusercontent.com/38406975/166121265-f9f4f199-1c2a-4fe7-ad7e-e5ec80d194c7.png">
<p align = "center">Create a new virtual disk for your OS</p>
<img width="700" alt="Screen Shot 2022-04-30 at 23 16 09" src="https://user-images.githubusercontent.com/38406975/166121282-df8442e3-6ffe-4b3a-abeb-e0b06eb82e8e.png">
<p align = "center">Choose hard disk type</p>
<img width="702" alt="Screen Shot 2022-04-30 at 23 16 16" src="https://user-images.githubusercontent.com/38406975/166121309-126a6573-1ae0-4925-b119-7fee19d0396d.png">
<p align = "center">Choose storage type of your hard disk</p>
<img width="706" alt="Screen Shot 2022-04-30 at 23 16 23" src="https://user-images.githubusercontent.com/38406975/166121344-eb4d7065-d63a-43ad-9a95-ed57bea8f7cb.png">
<p align = "center">Choose your file location path</p>
<img width="851" alt="Screen Shot 2022-04-30 at 23 16 44" src="https://user-images.githubusercontent.com/38406975/166121349-bc9db0d8-c6f6-4c3d-8384-d37dbc0aeb73.png">
<p align = "center">As you done with disk installation open machine's settings</p>
<img width="647" alt="Screen Shot 2022-04-30 at 23 17 12" src="https://user-images.githubusercontent.com/38406975/166121368-b309c14f-95b3-4a5e-8806-9b40d354e030.png">
<p align = "center">Choose storage section and choose the empty disk</p>
<img width="904" alt="Screen Shot 2022-04-30 at 23 18 26" src="https://user-images.githubusercontent.com/38406975/166121398-ced0f652-e354-47fa-8db6-eaa1d6bae711.png">
<p align = "center">Click on disk icon and choose DebianOS ISO file location</p>
<img width="838" alt="Screen Shot 2022-04-30 at 23 18 53" src="https://user-images.githubusercontent.com/38406975/166121429-eb8f2916-d8cd-4f6e-a34f-7b052b2bcb5d.png">
<p align = "center">Now click on start to turn on your machine</p>
<br>
<br>
<h2>Debian Installation </h2>
<img width="627" alt="Screen Shot 2022-04-30 at 23 19 50" src="https://user-images.githubusercontent.com/38406975/166121478-e510b436-77b3-483a-bea5-567866ec0f73.png">
<p align = "center">Choose Install to start installtion without graphical interface</p>
<img width="795" alt="Screen Shot 2022-04-30 at 23 20 05" src="https://user-images.githubusercontent.com/38406975/166121497-f1dfa87d-7768-44a7-a730-5326169f989b.png">
<p align = "center">OS language selection</p>
<img width="798" alt="Screen Shot 2022-04-30 at 23 20 16" src="https://user-images.githubusercontent.com/38406975/166121509-50da6c14-f249-4ccf-9646-080f699accce.png">
<p align = "center">Location</p>
<img width="793" alt="Screen Shot 2022-04-30 at 23 20 26" src="https://user-images.githubusercontent.com/38406975/166121518-c4569342-07de-4bea-9aec-4ae31dff966a.png">
<p align = "center">Keyboard layout</p>
<img width="797" alt="Screen Shot 2022-04-30 at 23 21 10" src="https://user-images.githubusercontent.com/38406975/166121532-2b65abfb-1816-490a-afcc-4d7d167b7c68.png">
<p align = "center">By the subject it should be your username with 42 at the end</p>
<img width="794" alt="Screen Shot 2022-04-30 at 23 21 21" src="https://user-images.githubusercontent.com/38406975/166121543-c0273970-5fe2-450f-9456-2e0122dab03e.png">
<p align = "center">Leave it blank</p>
<img width="789" alt="Screen Shot 2022-04-30 at 23 21 39" src="https://user-images.githubusercontent.com/38406975/166121561-632361f1-8dce-4559-be45-a65aa354c1e3.png">
<img width="795" alt="Screen Shot 2022-04-30 at 23 21 56" src="https://user-images.githubusercontent.com/38406975/166121562-cdf8a3aa-177d-4933-884f-cb44cfe9d9b3.png">
<p align = "center">Create a password and re-enter it <br> *hint during the installation use the same and strong password eveywehere </p>
<img width="793" alt="Screen Shot 2022-04-30 at 23 22 16" src="https://user-images.githubusercontent.com/38406975/166121614-4094a0ac-298d-4491-8ef1-49db393d61d2.png">
<p align = "center">Name for your user. It can be whatever you want</p>
<img width="788" alt="Screen Shot 2022-04-30 at 23 22 44" src="https://user-images.githubusercontent.com/38406975/166121624-de265c0d-d220-4ca3-8425-98d7182d2087.png">
<p align = "center">Use your 42 username</p>
<img width="796" alt="Screen Shot 2022-04-30 at 23 23 01" src="https://user-images.githubusercontent.com/38406975/166121630-45e7f50b-8bcf-4d03-9928-496d4352ab72.png">
<img width="800" alt="Screen Shot 2022-04-30 at 23 23 19" src="https://user-images.githubusercontent.com/38406975/166121632-b51f1bf6-3925-4652-8ddb-f5ba68d871ab.png">
<p align = "center">Remember about the hint 😉</p>
<img width="792" alt="Screen Shot 2022-04-30 at 23 23 32" src="https://user-images.githubusercontent.com/38406975/166121652-8c0d1232-be3d-4fee-b2c6-5c902cf199dc.png">
<p align = "center">Time zone</p>
<img width="794" alt="Screen Shot 2022-04-30 at 23 23 51" src="https://user-images.githubusercontent.com/38406975/166121670-a36f0b98-01a6-45f1-8a90-883d3bced5ed.png">
<img width="800" alt="Screen Shot 2022-04-30 at 23 24 02" src="https://user-images.githubusercontent.com/38406975/166121674-aef49145-027f-421e-826d-b4b5f94e6460.png">
<img width="794" alt="Screen Shot 2022-04-30 at 23 24 10" src="https://user-images.githubusercontent.com/38406975/166121682-932e2e0a-339e-4afe-a896-06628c990810.png">
<p align = "center">We need /home, /var and /tmp folders separatrd for the signature</p>
<img width="794" alt="Screen Shot 2022-04-30 at 23 24 19" src="https://user-images.githubusercontent.com/38406975/166121698-8a700b86-c935-41f0-b82f-72b5ee6d385c.png">
<img width="795" alt="Screen Shot 2022-04-30 at 23 24 31" src="https://user-images.githubusercontent.com/38406975/166121701-e5eebb8d-2bce-49d6-a13d-47b64598f4ac.png">
<img width="788" alt="Screen Shot 2022-04-30 at 23 29 07" src="https://user-images.githubusercontent.com/38406975/166121703-bdf8d50f-69c3-4b2c-9866-adba4b70b22e.png">
<img width="788" alt="Screen Shot 2022-04-30 at 23 29 36" src="https://user-images.githubusercontent.com/38406975/166121707-892f2e3e-b1c1-4303-8248-7894856d9d53.png">
<p align = "center">Hint 🤓</p>
<img width="792" alt="Screen Shot 2022-04-30 at 23 30 04" src="https://user-images.githubusercontent.com/38406975/166121728-ef3dbc2b-e408-4073-bbd4-bf73a0a052a2.png">
<img width="795" alt="Screen Shot 2022-04-30 at 23 30 19" src="https://user-images.githubusercontent.com/38406975/166121729-9ba6f8f5-fd55-4084-8026-3f12e507f034.png">
<img width="797" alt="Screen Shot 2022-04-30 at 23 30 34" src="https://user-images.githubusercontent.com/38406975/166121737-9b4b55d7-38f1-4349-9f44-6601007b8071.png">
<img width="798" alt="Screen Shot 2022-04-30 at 23 43 34" src="https://user-images.githubusercontent.com/38406975/166121741-cba6fdc1-0ee8-43ce-8b9a-10c730da8bb0.png">
<img width="796" alt="Screen Shot 2022-04-30 at 23 43 42" src="https://user-images.githubusercontent.com/38406975/166121742-79b30161-66b2-4124-8ccd-cdf22ea02c3a.png">
<img width="792" alt="Screen Shot 2022-04-30 at 23 43 49" src="https://user-images.githubusercontent.com/38406975/166121744-6354819a-9604-4158-9d44-35b2df11a946.png">
<img width="787" alt="Screen Shot 2022-04-30 at 23 43 56" src="https://user-images.githubusercontent.com/38406975/166121746-1dbb82a4-4af6-4227-8b1c-77be7ad3d02f.png">
<img width="795" alt="Screen Shot 2022-04-30 at 23 45 05" src="https://user-images.githubusercontent.com/38406975/166121749-938f71ff-29d0-4f6b-8762-0e5f8b271974.png">
<img width="801" alt="Screen Shot 2022-04-30 at 23 56 38" src="https://user-images.githubusercontent.com/38406975/166121750-d9dc541d-f3ac-48fe-aaa3-b8f482705d50.png">
<img width="780" alt="Screen Shot 2022-04-30 at 23 58 35" src="https://user-images.githubusercontent.com/38406975/166121753-507a367c-eef6-49bc-b159-730d5f55cfb5.png">
<img width="781" alt="Screen Shot 2022-04-30 at 23 58 43" src="https://user-images.githubusercontent.com/38406975/166121755-c3420270-c39d-4ce9-aeba-e246eae4be7b.png">
<img width="784" alt="Screen Shot 2022-04-30 at 23 59 30" src="https://user-images.githubusercontent.com/38406975/166121758-b6f4c346-72b1-4dc3-9a4e-88a80b503918.png">
<img width="723" alt="Screen Shot 2022-05-01 at 00 00 03" src="https://user-images.githubusercontent.com/38406975/166121762-dcd9df24-6ef3-4d60-860b-b23d993978e5.png">
<p align = "center">Use your password 😂</p>
<img width="793" alt="Screen Shot 2022-05-01 at 00 00 34" src="https://user-images.githubusercontent.com/38406975/166121792-9e2c7fa7-3a3c-4b9a-b7cc-cb23ed29c168.png">
<p align = "center">Your username and password again 🤣</p>
<br>
<br>
<h1 id="sudo">2. Installing sudo and adding users</h1>
<p> At first switch to root<br>
  Root is the superuser account in Unix and Linux. It is a user account for administrative purposes, and typically has the highest access rights on the system.
</p>
<br>
<br>
<h2>Installing sudo</h2>

```
$ su
```
<p>
  Now we need to install the sudo command<br>
Sudo stands for either "substitute user do" or "super user do" and it allows you to elevate your current user account to have root privileges temporarily.
</p>

```
$ apt install sudo
```
<p>apt stands for Advanced Package Tool. It will help you to install packages you need. <br>
  There are also aptitude that can be used on same purpose. Here are their <a href="https://www.tecmint.com/difference-between-apt-and-aptitude/#:~:text=While%20apt%2Dget%20handles%20all,marking%20a%20package%20to%20be">difference</a>. You will need this for the defence.
</p> 

<p>Check whether sudo was installed</p>

```
$ dpkg -l | grep sudo
```
<p>You can use this command to check any program.</p>
<br>
<br>
<h2>Adding user </h2>
<p>Add your user to sudo group.</p>

```
$ adduser <yourusername> sudo 
```
OR

```
$ usermod -aG sudo <yourusername>
```
<p> Check usermod flags by following command. You might need this for the defence.</p>

```
$ man usermod
```
<p>Check if your user were added to sudo group.</p>

```
$ getent group sudo
```
<p>Now we need to give sudo privilege to our user.</p>

```
$ sudo visudo
```
<p>Add this command on line 21. </p>

```
<yourusername> ALL=(ALL)ALL
```
<p>!OPTIONAL. Installing vim .</p>

```
$ sudo apt install vim 
```
<br>
<br>
<h1 id='ssh'>3.Installing SSH</h1>
<p>Before installing any program update and upgrade your system </p>

```
$ sudo apt-get update
$ sudo apt-get upgrade
```
<p>Now we are ready to install SSH <br> <a href="https://www.techtarget.com/searchsecurity/definition/Secure-Shell">Here</a> you can learn what is SSH. You will need this on evaluation.</p>

```
$ sudo apt install openssh-server
```
<p>Check whether SSH was installed</p>

```
$ dpkg -l | grep sudo
```
<p>Check SSH status </p>

```
$ sudo systemctl status ssh
```
<p> Now we need to change the SSH default port from 22 to 4242.<br>Read about <a href="https://www.techtarget.com/searchnetworking/definition/port#:~:text=A%20port%20in%20networking%20is,that%20peripheral%20hardware%20plugs%20into.">ports</a></p>

```
$ sudo nano /etc/ssh/sshd_config
```
OR (If vim is installed)

```
$ sudo vim /etc/ssh/sshd_config
```

<p>Change Line :<br>
  <b>#Port 22</b><br>
  to <br>
  <b>Port 4242</b>
</p>

<p>Check whether port has been changed</p>

```
$ sudo grep Port /etc/ssh/sshd_config
```

<p>Restart SSH</p>

```
$ sudo service ssh restart
```
<p>Reboot your computer to apply all changes </p>
<br>
<br>

<h2>Firewall installation </h2>
<p>We need <a href="https://en.wikipedia.org/wiki/Uncomplicated_Firewall">firewall</a> to manage our ports. We are going to use UFW</p>

```
$ apt-get install ufw
```

<p>After the installation enable the ufw </p>

```
$ sudo ufw enable
```

<p>Let's check all ports that are allowed by the firewall</p>

```
$ sudo ufw status 
```
<p>It is empyt for now, but we are getting a message that says that firwall is active<br>
  Let's add ssh ports to firewall. We can add a specific port (8080,8888,5555,14...) or app (ssh, apache full ...).<br>
App is a file where multiple ports are listed.
</p>
  
 ```
 $ sudo ufw allow ssh
 $ sudo ufw allow 4242
 ```
 
 <p>Check the ufw status now</p>
 
 ```
 $ sudo ufw status 
 ```
 <p>You can see that 4242 port is added as well as 22/tcp (ssh default port which is written in ssh app file)</p>
 
 <h2>During the defencion you will be asked to add and remove some ports</h2>
 <p>Adding</p>
 
 ```
 $ sudo ufw allow <portnumber>
 ```
 
 <p>Looking at table its number. </p>
 
 ```
 $ sudo ufw status numbered
 ```
<p>Deleting</p>

```
$ sudo ufw delete <rownumber>
```
<br>
<br>

<h2> Connection with SSH server </h2>

<p>Now as we installed ssh and configured our firewall we can use this virtual machine as a server and connect to it from other computers.<br>
For this let's allow our VM to use 4242 port. We need to change VirtualBox settings.</p>
<img width="848" alt="Screen Shot 2022-05-01 at 11 46 20" src="https://user-images.githubusercontent.com/38406975/166137143-651e29ce-c726-46f4-9901-4901c078b376.png">
<p align="center">Go to your VBbox. Choose your machine and choose setting.</p>
<img width="641" alt="Screen Shot 2022-05-01 at 11 46 33" src="https://user-images.githubusercontent.com/38406975/166137145-ca450fd3-57ff-4466-ac4a-b7c247f79e12.png">
<p align="center">Go to Network section. Press on advanced and press Port Forwarding button.</p>
<img width="457" alt="Screen Shot 2022-05-01 at 11 46 59" src="https://user-images.githubusercontent.com/38406975/166137238-0e14cbf3-825c-426e-94cb-269caa8fdda2.png">
<p align="center">In the opened window press on "New" button and write 4242 on both port sections.</p>
<p>We need to restart ssh server</p>

```
$ sudo systemctl restart ssh
```

<p>Let's check ssh status.</p>

```
$ sudo service sshd status
```

<p>Our server is ready for connection. You can open terminal on your Mac and connect to your Debian server</p>

```
#this code is on MacOs
$ ssh <yourusername>@127.0.0.1 -p 4242
```
<p>As you entered you can continue the project by your Mac terminal.<br>
  To close the connection do: </p>
  
 ```
 $ exit
 ```
<br>
<br>
<h1 id="pw">4.Setting Password</h1>
<p>Read <a href="https://ostechnix.com/how-to-set-password-policies-in-linux/">this</a> article about passwords in Linux</p>
<p>In this case we need to install password quality checking library</p>

```
$ sudo apt-get install libpam-pwquality
```
<p>We need to change password length</p>

```
sudo vim /etc/pam.d/common-password
```
<p>Change 25th line so it looks like this</p>

```
password    requisite   pam_pwquality.so retry=3 lcredit =-1 ucredit=-1 dcredit=-1 maxrepeat=3 usercheck=0 difok=7 enforce_for_root
```

<p>Change 26th line so it looks like this</p>

```
password [success=1 default=ignore] pam_unix.so obscure use_authtok try_first_pass yessrypt minlen=10
```
<p>Time to chnage password exparation dates</p>

```
$ sudo nano /etc/login.defs
```

<p>Change this part</p>

```
PASS_MAX_DAYS 9999
PASS_MIN_DAYS 0
PASS_WARN_AGE 7
```
<p>To this</p>

```
PASS_MAX_DAYS 30
PASS_MIN_DAYS 2
PASS_WARN_AGE 7
```
<p>This changes will apply to any user you create after.<br>
  To change this setting for already created users you have to change their days manualy.</p>
  
```
$ sudo /etc/shadow
```
 
<p>Reboot your machin to apply the changes</p>

```
$ sudo reboot
```
<br>
<br>
<h2> Group Creation</h2>

<p>To create a group we do </p>

``` 
$sudo groupadd <groupname>
```
<p>Check if group created</p>

```
$ sudo getent group
```

<p>Now we will create a user and asign it to a group </p>

<p>To list all users do :</p>

```
$ sudo cut -d: -f1 /etc/passwd
```
<p>To create a user</p>

```
$ sudo adduser <newusername>
```
<p>Add user to the group</p>

```
$ sudo usermod -aG <groupname> <newusername>
```
<p>To check is the user in the group just do: </p>

```
$ getent group <groupname>
```
<p>To check all groups of your curent using user do :</p>

```
$ groups
```
<p>We also can check password rules for any user</p>

```
$ sudo -l <username>
```
<p>Now we need to configure <a href="https://help.ubuntu.com/community/Sudoers">sudoers</a> group.</p>
