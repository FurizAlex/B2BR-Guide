## Born2BeRoot Guide 
This guide has 8 Parts: 
- Part 1 - Downloading Debian
- Part 2 - Starting Your Virtual Machine
- Part 3 - Configurating Your Virtual Machine
- Part 4 - Connecting to Virtual Machine using SSH
- Part 5 - Continue Configurating Your Virtual Machine
- Part 6 - Creating sudo.log
- Part 7 - Signature.txt
- Part 8 - Your Born2BeRoot Defence Evaluation with Answers

## This guide assumes Virtual Box is downloaded on your system

## Part 1 - Downloading Debian

1. Click on this link <ins>**https://www.debian.org** 

2. click Download

3. click on 'debian-11.6.0-amd64-netinst.iso' to download it.

### Part 1.1 - Creating folder for the VM, (this part is important for projects completed on the 42 computers) 

1. Open the terminal

<!-- <img width="622" alt="Screen Shot 2022-07-26 at 4 26 06 PM" src="https://user-images.githubusercontent.com/58959408/180943494-9c25b321-4cae-4c39-89bb-92271a245489.png"> -->

2. From the home directory type `cd sgoinfre/students`

<!-- <img width="622" alt="Screen Shot 2022-07-26 at 4 26 27 PM" src="https://user-images.githubusercontent.com/58959408/180943649-42dba828-3bd3-45ee-92ea-4e7218d65674.png"> -->

3. Then make a directory `mkdir <your intra>`

<!-- <img width="622" alt="Screen Shot 2022-07-26 at 4 26 38 PM" src="https://user-images.githubusercontent.com/58959408/180943705-d9705f63-59a9-4b2d-9130-75d8711a25d3.png"> -->

4. Then type `chmod 700 <your intra> && cd <your intra>`

5. Then make directory called `born2beroot` (don't change the permisions)

<!-- <img width="622" alt="Screen Shot 2022-07-26 at 4 26 48 PM" src="https://user-images.githubusercontent.com/58959408/180943745-09427be5-f0ff-4100-aaa3-56b4cfcea2af.png"> -->

6. Add your Debian Download (from earlier) to the "born2beroot" folder you just created.

<!-- ### Part 1.2 - Virtual Box

#### Now head over to Virtual Box to continue on.
<img width="264" alt="Screen Shot 2022-06-24 at 12 18 12 PM" src="https://user-images.githubusercontent.com/58959408/175452234-79c7f008-10b2-4e4b-a602-95886d9e2508.png">

#### Don't have Virtual Box Installed?
Download it from Managed Software Center on an Apple Computer/Laptop.

<img width="1307" alt="Screen Shot 2022-06-24 at 12 27 24 PM" src="https://user-images.githubusercontent.com/58959408/175453219-e30d058a-946c-482b-85de-4feaad7b970d.png">
 -->

## Part 2 - Starting your Virtual Machine

1. Open `Virtual Box`

2. Click on `New`

![1*tkjZEbnHKqPGN24HQw_kRA](https://user-images.githubusercontent.com/58959408/174700376-2862e8e9-0a7a-4681-af3b-e82dbc7d9aa5.png)

2. Change Machine Folder to `sgoinfre/students/your_intra_login/Virtual Machine Name` and then click `continue` to move to the next step.

![1*WyFDl98AZfft999XCKD6kA](https://user-images.githubusercontent.com/58959408/174700651-8dc8e0a9-7709-4202-8a12-12a384ff6e3e.png)

3. Set Memory Size as `1024 MB` and click continue.

![1*SoVNIKT340ARlLvQ7RuwDA](https://user-images.githubusercontent.com/58959408/174701125-7a285b0d-7036-4bef-926b-271b0032d7ad.png)

4. Click `Create a Virtual Hard Disk Now` and then click `Create` to create the Hard Disk.

![1*PzVboJLyLTs7qJmgbdoBYA](https://user-images.githubusercontent.com/58959408/174701209-a5d10ea3-c634-4d49-b099-01d538fe0517.png)

5. Click `VDI (VirtualBox Disk Image)` and then click `Continue` to select VDI.

![1*6_D9jIyOW0jE3a6vF_UzXg](https://user-images.githubusercontent.com/58959408/174701340-d84f6c80-e09b-43ae-b31a-6dd5d6306f23.png)

6. Click `Dyamically Allocated` and then click `Continue` to only use space on your Hard Disk.

![1*HagpR-UD0HWCb7zRTeSQXQ](https://user-images.githubusercontent.com/58959408/174744677-eac5b679-49f7-4881-a59b-00a420cbe640.png)

7. Set Size as `8.00 GB` and then click `Continue`.

![1*rYdYJbPswCVCUa5pwKcRZA](https://user-images.githubusercontent.com/58959408/174745855-73880988-be69-45cc-bb6d-7c6c1a40c1ac.png)

8. Click `Settings` and then click `Storage` to view your Virtual Machine Storage.
	
<img width="1309" alt="Screen Shot 2022-06-24 at 12 51 09 PM" src="https://user-images.githubusercontent.com/58959408/175455682-e1b4c977-2f33-41cf-b3cc-3ad78b3254ce.png">

9. Click on `Optical Drive` (Optical Drive - far right blue small box).
	
![1*je75kGWjXl0M6PlqEzHgoA](https://user-images.githubusercontent.com/58959408/174701924-0c69938f-10ec-498f-adec-bacf073b4b99.png)

10. Click on `Choose a disk file...` (2nd option in the drop down).
	
![1*VDy31g0tePnUOuJ1cZQsxQ](https://user-images.githubusercontent.com/58959408/174702002-9b4fe4d2-3008-4375-9ec1-57f5e1425eb8.png)

11. Then click on the Virtual Machine file (.iso). 
	
![1*FOldzHFaQ2JS_phe6z6T4g](https://user-images.githubusercontent.com/58959408/174702161-957eb0b6-2803-407f-b018-c02f7615f027.png)

12. Click on your `Virtual Machine` and then click `'ok` to confirm you Virtual Machine Storage.
	
![1*Evj7Z2EOq102A1zUVgUnQg](https://user-images.githubusercontent.com/58959408/174702820-824e0acf-f919-4bfb-a619-eea8068fe309.png)

13. Click `Start` (The Green Arrow ➡️) to start your Virtual Machine.
	
![1*Yg53c1-01g4VzTqhcVEEcA](https://user-images.githubusercontent.com/58959408/174702806-1bd8fce3-aac6-44b3-84d9-c76252dfecd8.png)


## Part 3 - Configurating Your Virtual Machine

#### In the Virtual Machine, you will not have access to your mouse and will only use your Keyboard to operate your Virtual Machine. 

0. To increase your Virtual Machine size, press `command` + `c` on your Apple Keyboard at the same time and then use your mouse to drag the screen to the size you wish or do the following: 

<img width="666" alt="178788620-61064b58-0c0c-4f48-815e-60b4a8eaecae" src="https://user-images.githubusercontent.com/58959408/181727316-9a16b307-ea00-4116-a20a-261512f63a20.png">
	
1. Use the arrow keys on your keyboard 🔼 🔽 and press `Enter` on `Install` (This will start the installation proccess).

![1*-tV-M-4g6MH8h6pWJ27bCg](https://user-images.githubusercontent.com/58959408/174728861-fb9435a5-04e5-402c-80a3-f366c9b51be8.png)

2. Press `enter` on `English - English` or your language of preference.

![1*xeb8quQ-ccd5X51d8ToZRw](https://user-images.githubusercontent.com/58959408/174729529-f51630be-4206-4bfc-a13f-6278c67eb633.png)

3. Press `enter` on `Australia` or the country your installing this Virtual Machine.

![1*WixFq3GJF9OjeH-zTBTN7Q](https://user-images.githubusercontent.com/58959408/174729594-92ba0cdc-483c-4499-84ee-2d8f3b62f0b3.png)

4. Press `enter` on `American English` or your keyboard of preference.

![1*zKUk6R9tls_jiyY81ue8kA](https://user-images.githubusercontent.com/58959408/174729629-4f111978-4fc1-47ae-891f-aea693929480.png)

## ⚠️ NOTE: Whenever you are told to create a password, use the same password as everything.

5. Create a Host Name as your login, with 42 at the end (eg. `YOUR INTRA`42) - write down your Host Name, as you will need this later on.
	
![1*r0fzgkzXOjK2DfsBCh7wEQ](https://user-images.githubusercontent.com/58959408/174729750-fbd2d215-b526-42c6-8ff0-b83f886c1f3c.png)

6. Leave this blank, press `enter` on Continue.
	
![1*81XjZBZg2bbNXunuxgnFPQ](https://user-images.githubusercontent.com/58959408/174729840-a85c3319-3a70-4922-9335-e4bb6f765ee9.png)

7. Create a Password for the Host Name - write this down as well, as you will need this later on. 
	
![1*ft498oj7syh4zVjI48U_tw](https://user-images.githubusercontent.com/58959408/174729894-d0fc794f-add8-49e7-9015-521f9e93958f.png)

8. Create a User Name without 42 at the end (eg. `YOUR INTRA`) - write down your Host Name, as you will need this later on. 
	
![1*rhJWnMKN0TPBZwqRey9OeQ](https://user-images.githubusercontent.com/58959408/174729939-06933a35-5dd1-4924-848e-78d2023bb66e.png)

9. Create a Password for the User Name (you might as well use the same password as your Host Password) write this down as well, as you will need this later on. 

10. Press `enter` on your `Timezone` (The timezone your currently doing this project in).
	
![1*2i7svoURih_UIlRJ87rj5w](https://user-images.githubusercontent.com/58959408/174730349-76a4e74f-822b-4040-8d95-554d44fcb67c.png)

11. Press `enter` on `Guided - use entire disk and set up encrypted LVM` (Second to last option from the list).
	
![1*CsSx-ALmn8mMxvWicsNVAQ](https://user-images.githubusercontent.com/58959408/174730389-03e5dcd7-9472-4cab-bf88-fe3cc4dc0f4c.png)

12. Press `enter` on Select Disk to Partition.
	
![1*BTLz5sT6noL_SVQ7eq3u-A](https://user-images.githubusercontent.com/58959408/174730452-e267df43-2883-4760-85c4-010970fee329.png)

13. Press `enter` on Select `Separate /home partition` (Last option from the list).
	
![1*r5zFPA7R_9BtIqwyOpCCVw](https://user-images.githubusercontent.com/58959408/174730481-2641b9c0-c50d-4f2b-9e71-3896a0760e10.png)

14. Select `Yes` and press `Enter` to write the changes to disks and configure LVM.
	
![1*NHdo3JbApICz0Co2epPLFA](https://user-images.githubusercontent.com/58959408/174730521-780f5eb2-4955-48df-8c59-af9914674ee7.png)

15. Press `Enter` to `cancel` Erasing data as you won't need this for your Virtual Machine.
	
![1*KHmnCUJUWhf1minIdHNS4g](https://user-images.githubusercontent.com/58959408/174730626-c132041c-3070-405f-a8d8-60d620a1d770.png)

16. Create a Encryption passphrase - write this down as well, as you will need this later on.
	
![1*B0QL-gX7rZW5-RJyTD1uWw](https://user-images.githubusercontent.com/58959408/174730733-f306e051-4b0e-40de-93ab-56f2cdce45d5.png)

17. Retype the Encryption passphrase you just created.
	
![1*xE1owXa0ttpvcioaEwnutA](https://user-images.githubusercontent.com/58959408/174730804-796f6db1-8b59-4f8e-900c-1416f957db30.png)

18. Type in `max` and press enter on `Continue` to assign the amount of volume group to use for guided partitioning.
	
![1*SUFMu-qy3rBwIe9B0Bq3kg](https://user-images.githubusercontent.com/58959408/174730857-2de10217-3d42-41ca-8f43-fc91fddb64c6.png)

19. Press enter on `Finish partitioning and write changes to disk`. 

<img width="806" alt="Screen_Shot_2022-09-05_at_5 33 43_PM" src="https://user-images.githubusercontent.com/58959408/188408125-7c93acc1-b37f-4b9f-8189-b3cc4a83da8c.png">

20. Press enter on `Yes` for Partition Disks.
	
![1*yfXpHyGD37OGAOX7qs1Avw](https://user-images.githubusercontent.com/58959408/174730895-f70df93e-eb7e-493c-9374-edf58a47408c.png)

21. Press enter on `No` for Configure the package manager.
	
![1*Mfb1YHt4K3pZJ12TF2dXAw](https://user-images.githubusercontent.com/58959408/174730933-615891f8-d9fa-4312-ad78-d691bd648773.png)

22. Press `enter` in the country that your in.
	
![1*vqV-bN3zDMqTBAKz_u548w](https://user-images.githubusercontent.com/58959408/174731009-ca532fcf-ac41-4cde-bdae-2cf18c8bf519.png)

23. Press `enter` on deb.debian.org.
	
![1*bLnFC6MebhW1-YZlI2n9_A](https://user-images.githubusercontent.com/58959408/174731066-6bef2e53-c891-477f-8a29-7e9984a6d911.png)

24. Leave this blank and press `enter` on continue.
	
![1*e08pS8shLNmhZuFUrmuBwA](https://user-images.githubusercontent.com/58959408/174731175-bf4949d2-a832-4a1f-9282-c91195203c84.png)

25. Press `enter` on `no` for Configuring popularity-contest.
	
![1*1I6fHG3MHuovrarqj9PNnA](https://user-images.githubusercontent.com/58959408/174731301-88d7c53d-f5e2-46c3-b221-a8b40f70f81f.png)

26. Deselect `SSH server` and `standard system utilities` by pressing the `Space key` and then press `enter` on `Continue`.
	
![1*lGsuAQEwT0WBhb4kdUMp9g](https://user-images.githubusercontent.com/58959408/174731387-b4859ded-9a9f-409a-a9c9-57d1ec77cbfd.png)

27. Press `enter` on `Yes` to Install the GRUB boot loader on a hard disk.
	
![1*b2qXPye_kX8EudSvbO4yww](https://user-images.githubusercontent.com/58959408/174731448-b7b22a70-de87-4535-b8aa-3fb3294c9661.png)

28. Press `enter` on /dev/sda
	
![174731491-7215eca8-f5e0-4862-a6ef-c49077c94cbe](https://user-images.githubusercontent.com/58959408/176393352-ed5223c7-ddf1-4c1f-97af-089be23572b2.png)

29. Press `enter` on `continue` to finish the installation.
	
![1*riuXLYYgESxdq-lpkivFXQ](https://user-images.githubusercontent.com/58959408/174731601-b5949892-28b5-4b5a-94dd-9b50e6f0662b.png)

30. Before we move onto starting your Virtual Machine, make sure you have your Host, Username and Password/s saved or written down somewhere. 

## Part 3.1 - Starting Your Virtual Machine

1. Press enter on `Debian GNU/Linux` 

2. Enter your encryption password you had created before

3. Login in as the your_username you had created before

4. Type `lsblk` in your Virtual Machine to see the partition

### Part 3.2 - Installing Sudo (Super User Do)

1. First type `su -` to login in as the root user.
2. Then type `apt-get update -y` 
3. Then type `apt-get upgrade -y` 
4. Then type `apt install sudo`
5. Then type `usermod -aG sudo your_username` to add user in the sudo group (To check if user is in sudo group, type `getent group sudo`)
6. Type `sudo visudo` to open sudoers file
7. Lastly find - # User privilege specification, type `your_username  	ALL=(ALL) ALL`

### Part 3.3 - Installing Git and Vim

1. Then type `apt-get install git -y` to install Git
2. Then type `git --version` to check the Git Version
3. Then type `apt-get install vim -y` to install Vim

### Part 3.4 - Installing and Configuring SSH (Secure Shell Host)

1. Type `sudo apt install openssh-server`
2. Type `sudo systemctl status ssh` to check SSH Server Status
3. Type `sudo vim /etc/ssh/sshd_config`
4. Find this line `#Port22` 
5. Change the line to `Port 4242` without the # (Hash) in front of it
6. Find this line `#PermitRootLogin`
7. Change to `PermitRootLogin no`

![1*riuXLYYgESxdq-lpkivFXQ](https://github.com/Javiff8/Born2beRoot/blob/master/Screenshots/Untitled%203.png)

8. Save and Exit Vim (press `esc` then `shift ZZ`)
9. Then type `sudo grep Port /etc/ssh/sshd_config` to check if the port settings are right

### Part 3.4.1

1. Type `sudo nano /etc/ssh/ssh_config`
2. Find line containing `#Port 22`
3. Change it to `Port 4242`

![1*riuXLYYgESxdq-lpkivFXQ](https://github.com/Javiff8/Born2beRoot/blob/master/Screenshots/Untitled%204.png)

4. Lastly type `sudo service ssh restart` to restart the SSH Service 

### Part 3.5 - Installing and Configuring UFW (Uncomplicated Firewall)

#### These steps are important as they will allow you to connect to your virtual machine through your host machine with iterm.

1. First type `apt-get install ufw` to install UFW
2. Type `sudo ufw enable` to inable UFW
3. Type `sudo ufw status numbered` to check the status of UFW
4. Type `sudo ufw allow ssh` to configure the Rules
5. Type `sudo ufw allow 4242` to configure the Port Rules
6. Lastly Type `sudo ufw status numbered` to check the status of UFW 4242 Port

## Part 4 Connecting to Virtual Machine using SSH

0. To exit your Virtual Machine and use your mouse, press `command` on your Apple Keyboard and your mouse should appear
1. Go to your Virtual Box Program
2. Click on your Virtual Machine and select `Settings`
3. Click `Network` then `Adapter 1` then `Advanced` and then click on `Port Forwarding`
![1*rCj_FeuZ5Rm2abz48qhulg](https://user-images.githubusercontent.com/58959408/174720900-39eda7e0-9be8-453c-94f1-4aa1a6b10951.png)
4. Change the Host Port and Guest Port to `4242`
![1*61-KSUCFcerO1wPqBcYISg](https://user-images.githubusercontent.com/58959408/174720987-e8de3bf9-2ffa-40ca-9d5c-4d0dea9d0b30.png)
5. Then head back to your Virtual Machine
6. Type `sudo systemctl restart ssh` to restart your SSH Server
7. Type `sudo service sshd status` to check your SSH Status

### part 4.1 connect your host computer to the VM

1. Open an iTerm and type the following `ssh your_username@127.0.0.1 -p 4242`
2. In case an error occurs, then type `rm ~/.ssh/known_hosts` in your iTerm and then retype `ssh your_username@127.0.0.1 -p 4242`
	- 2.2 now you are connect.
3. Lastly type `exit` to quit your SSH iTerm Connection 

## Part 5 - Continue Configurating Your Virtual Machine

### Part 5.1 - Setting Password Policy

1. First type `sudo apt-get install libpam-pwquality` to install Password Quality Checking Library
2. Then type `sudo vim /etc/pam.d/common-password`

3. Find this line. `password		requisite		pam_deny.so` or
<img width="828" alt="Screen Shot 2022-07-29 at 6 40 34 PM" src="https://user-images.githubusercontent.com/58959408/181726262-8f8b7027-1929-4dda-8ac5-3957d3a1bd3a.png">
4. Add this to the end of that line `minlen=10 ucredit=-1 dcredit=-1 maxrepeat=3 reject_username difok=7 enforce_for_root`

- 4.1 The line should now look like this - `password  requisite     pam_pwquality.so  retry=3 minlen=10 ucredit=-1 dcredit=-1 maxrepeat=3 reject_username difok=7 enforce_for_root`
<img width="800" alt="179329787-1b718843-9272-43e4-8d92-8d83933cc938" src="https://user-images.githubusercontent.com/58959408/181725921-c1e6c2b1-9dd3-46c5-b738-111467bdb394.png">

5. Save and Exit Vim
6. Next type in your Virtual Machine `sudo vim /etc/login.defs`
7. Find this part `PASS_MAX_DAYS 9999` `PASS_MIN_DAYS 0` `PASS_WARN_AGE 7`
8. Change that part to `PASS_MAX_DAYS 30` and `PASS_MIN_DAYS 2` keep `PASS_WARN_AGE 7` as the same
9. Lastly type `sudo reboot` to reboot the change affects

## Part 6 - Creating sudo.log

1. First type `su -`, then type your password.
2. Then type `cd ..`
4. Then type `cd var/log`
5. Then type `mkdir sudo` (if it already exists, then continue to the next step).
6. Then type `cd sudo && touch sudo.log`
7. Then type `cd ~/../`

### Part 6.1 - Configuring Sudoers Group

1. First type `sudo nano /etc/sudoers` to go the sudoers file
2. Now edit your sudoers file to look like the following by adding in all of the defaults in the image below - ![1*N4Ad-9k0vfvnWKNC5q6MjQ](https://user-images.githubusercontent.com/58959408/174725518-0ebf1dac-4126-4869-9ba0-b1d05ce313c9.png)

```
Defaults	env_reset
Defaults	mail_badpass
Defaults	secure_path="/usr/local/sbin:/usr/local/bin:/usr/bin:/sbin:/bin"
Defaults	badpass_message="Password is wrong, please try again!"
Defaults	passwd_tries=3
Defaults	logfile="/var/log/sudo.log"
Defaults	log_input, log_output
Defaults	requiretty
```

### Part 6.2 - Crontab Configuation

1. Then type `apt-get install -y net-tools` to install the netstat tools
2. Then type `cd /usr/local/bin/`
3. Then type `touch monitoring.sh`
4. Lastly type `chmod 777 monitoring.sh`

### Part 6.2.1 - Copy Text Below onto Virtual Machine 
## The clip board of the host machine and VM are not connected so we will have to connect to the VM with ssh.

1. Copy this text (To copy the text below, hover with your mouse to the right corner of the text below and a copy icon will appear). 
```
#!/bin/bash
arc=$(uname -a)
pcpu=$(grep "physical id" /proc/cpuinfo | sort | uniq | wc -l) 
vcpu=$(grep "^processor" /proc/cpuinfo | wc -l)
fram=$(free -m | awk '$1 == "Mem:" {print $2}')
uram=$(free -m | awk '$1 == "Mem:" {print $3}')
pram=$(free | awk '$1 == "Mem:" {printf("%.2f"), $3/$2*100}')
fdisk=$(df -BG | grep '^/dev/' | grep -v '/boot$' | awk '{ft += $2} END {print ft}')
udisk=$(df -BM | grep '^/dev/' | grep -v '/boot$' | awk '{ut += $3} END {print ut}')
pdisk=$(df -BM | grep '^/dev/' | grep -v '/boot$' | awk '{ut += $3} {ft+= $2} END {printf("%d"), ut/ft*100}')
cpul=$(top -bn1 | grep '^%Cpu' | cut -c 9- | xargs | awk '{printf("%.1f%%"), $1 + $3}')
lb=$(who -b | awk '$1 == "system" {print $3 " " $4}')
lvmu=$(if [ $(lsblk | grep "lvm" | wc -l) -eq 0 ]; then echo no; else echo yes; fi)
ctcp=$(ss -neopt state established | wc -l)
ulog=$(users | wc -w)
ip=$(hostname -I)
mac=$(ip link show | grep "ether" | awk '{print $2}')
cmds=$(journalctl _COMM=sudo | grep COMMAND | wc -l)
wall "	#Architecture: $arc
	#CPU physical: $pcpu
	#vCPU: $vcpu
	#Memory Usage: $uram/${fram}MB ($pram%)
	#Disk Usage: $udisk/${fdisk}Gb ($pdisk%)
	#CPU load: $cpul
	#Last boot: $lb
	#LVM use: $lvmu
	#Connections TCP: $ctcp ESTABLISHED
	#User log: $ulog
	#Network: IP $ip ($mac)
	#Sudo: $cmds cmd"
```
2. Then open up a iTerm2 seperate from your Virtual Machine and type in iTerm `ssh your_host_name42@127.0.0.1 -p 4242` and then type your password, when it asks for it. 
3. Then type `cd /usr/local/bin`.
4. Then type `nano monitoring.sh` and paste the text above into the vim monitoring.sh you just created, by doing `command` + `v` on your Apple keyboard.
5. Save and Exit your `monitoring.sh`
- 5.1 - Then type `exit` to exit the iTerm SSH Login.
- 5.2 - Then go back to your Virtual Machine (not iTerm) and continue on with the steps below. 
6. Then type `sudo visudo` to open your sudoers file 
7. Add in this line `your_username ALL=(ALL) NOPASSWD: /usr/local/bin/monitoring.sh` under where its written %sudo ALL=(ALL:ALL) ALL
8. It should look like this
![1*l-7LtAqCon1gRkV3dY3qiQ](https://user-images.githubusercontent.com/58959408/174727595-11dbb2f9-9c34-4d11-870b-f832ea4a9224.png)
9. Then exit and save your sudoers file
10. Now type `sudo reboot` in your Virtual Machine to reboot sudo
11. Type `sudo /usr/local/bin/monitoring.sh` to execute your script as su (super user)
12. Type `sudo crontab -u root -e` to open the crontab and add the rule
13. Lastly at the end of the crontab, type the following `*/10 * * * * /usr/local/bin/monitoring.sh` this means that every 10 mins, this script will show

## Part 7 - Signature.txt (Last Part Before Defence)

⚠️ Warning: before you generate a signature number, turn off your Virtual Machine. ⚠️

1. Open iTerm and type `cd`
1. Then type `cd sgoinfre/students/<your_intra_username>/VirtualBox VMs`
2. Type `shasum VirtualBox.vdi` or whatever your Virtual Machine is called (This can take from a few seconds to 5 mins).
3. Copy the output number and create a signature.txt file and paste that number in the file. 
3. Now you submit the signature.txt file with the output number in it. 

⚠️ Warning: if you configure your VM after getting the signature, you have to regenerate the signiture. ⚠️

### 🥳 CONGRATULATIONS! YOU HAVE NOW FINISHED! NEXT IS THE EVALUATION 🔽
<br>

## Part 8 - Born2BeRoot Defence Evaluation with Answers

[Link](https://docs.google.com/document/d/1-BwCO0udUP7MhRh81Y681zz0BalXtKFtte_FHJc6G4s/edit) to the [Born2BeRoot Evaluation Checklist](https://docs.google.com/document/d/1-BwCO0udUP7MhRh81Y681zz0BalXtKFtte_FHJc6G4s/edit) created by [Adrian Musso-Gonzalez](https://github.com/AdrianMussoGonzalez).

### The Evaluation Questions

### Why did I choose Debian?
Easier to install and configure so better for personal servers.

### Difference between Debian and Rocky
The main difference between Debian and Rocky is that Debian is an independent, community-driven Linux distribution with a focus on stability, while Rocky Linux is a community enterprise Operating System (OS) based on CentOS, a previously popular Linux distribution that was discontinued by Red Hat. Additionally, Debian has a larger user community, a broader range of packages, and a more diverse set of supported architectures, while Rocky Linux aims to provide a stable, secure, and reliable enterprise-grade platform for organizations.

### What is a Virtual Machine?
Is a resource that uses software instead of a physical computer to run programs or apps. Each VM has its own operating system and functions separately, so you can have more than one VM per machine. Can be used to test applications in a safe, separate environment. Works by using software to simulate virtual hardware and run on a host machine.

### What is the difference between aptitude and APT (Advanced Packaging Tool)?
* Aptitude is a high-level package manager while APT is lower level which can be used by other higher level package managers
* Aptitude is smarter and will automatically remove unused packages or suggest installation of dependent packages
* Apt will only do explicitly what it is told to do in the command line

### What is AppArmor?
Linux security system that provides Mandatory Access Control (MAC) security. Allows the system admin to restrict the actions that processes can perform. It is included by default with Debian. Run `aa-status` to check if it is running.

### Password Rules
For the password rules, we use the password quality checking library and there are two files the common-password file which sets the rules like upper and lower case characters, duplicate characters etc and the login.defs file which stores the password expiration rules (30 days etc).
`Sudo nano /etc/login.defs`
`Sudo nano /etc/pam.d/common-password`

### What is LVM
Logical Volume Manager – allows us to easily manipulate the partitions or logical volume on a storage device. 

### UFW (Uncomplicated Firewall) 
UFW is a interface to modify the firewall of the device without compromising security. You use it to configure which ports to allow connections to and which ports to close. This is useful in conjunction with SSH, can set a specific port for it to work with.

### What is SSH?
SSH or Secure Shell is an authentication mechanism between a client and a host. It uses encryption techniques so that all communication between clients and hosts is done in encrypted form. User on Mac or Linux can use SSH the terminal to work on their server via SSH.

### What is Cron?
Cron or cron job is a command line utility to schedule commands or scripts to happen at specific intervals or a specific time each day. Useful if you want to set your server to restart at a specific time each day. 

- `cd /usr/local/bin` – to show monitoring.sh
- `sudo crontab -u root -e` – to edit the cron job
- `change script to */1 * * * * sleep 30s && script path` – to run it every 30 seconds, delete the line to stop the job from running.

### Creating a Group

1. First type `sudo groupadd user42` to create a group
2. Then type `sudo groupadd evaluating` to create an evaluating group
3. Lastly type `getent group` to check if the group has been created

### Creating a User and Assigning Them Into The Group

1. First type `cut -d: -f1 /etc/passwd` to check all local users
2. Type `sudo adduser new_username` to create a username - write down your new_username, as you will need this later on. 
- 2.1 Type `sudo usermod -aG user42 your_username`
- 2.2 Type `sudo usermod -aG evaluating your_new_username`
3. Type `getent group user42` to check if the user is the group
4. Type `getent group evaluating` to check the group
5. Type `groups` to see which groups the user account belongs to
6. Lastly type `chage -l your_new_username` to check if the password rules are working in users

### Evaluation Commands for UFW, Group, Host, lsblk and SSH

- `sudo ufw status`
- `sudo systemctl status ssh`
- `getent group sudo`
- `getent group user42`
- `sudo adduser new username`
- `sudo groupadd groupname`
- `sudo usermod -aG groupname username`
- `sudo chage -l username` - check password expire rules
- `hostnamectl`
- `hostnamectl set-hostname new_hostname` - to change the current hostname
- Restart your Virtual Machine.
- `sudo nano /etc/hosts` - change current hostname to new hostname
- `lsblk` to display the partitions
- `dpkg -l | grep sudo –` to show that sudo is installed
- `sudo ufw status numbered`
- `sudo ufw allow port-id`
- `sudo ufw delete rule number`
- `ssh your_user_id@127.0.0.1 -p 4242` -  do this in terminal to show that SSH to port 4242 is working
