 ### DOCUMENTATION OF PROJECT - 1
 ## <center>WEB STACK IMPLEMENTATION (LAMP STACK) IN AWS</center> 


1.Installed the following applications:

*Microsoft Visual Studio Code  [Download](https://code.visualstudio.com/download)

*git  [Download](https://git-scm.com/downloads)


*Windows Terminal [Download](https://apps.microsoft.com/store/detail/windows-terminal/9N0DX20HK701?hl=en-gb&gl=GB)

2.Created a Git Hub account, updated profile
![git profile](./Images/updated%20github%20profile.JPG)

3.Created a new repository 

![Created a respository](./Images/Created%20a%20repository.JPG)

4.Intergrated MS Visual Studio Code with Git Hub using following codes 

<code>git clone git@github.com:Adeseye/PROJECT-1.git</code>

![alt text](./Images/copying%20git%20code.JPG)

Copied and pasted code into vsc terminal

![alt text](./Images/git%20code.JPG)

5.Configured Git hub account with MS VSC via Terminal - using the following commands in VSC terminal :

<code>git add .</code>

<code> git commit -m "Writting project-1" </code>

<code>git push</code>

![alt text](./Images/git%20command%20profile%20setup.JPG)

4.Signed up for AWS freetier account and a root user account, logged into AWS Management Console Services ![aws management console](./Images/aws.JPG) 

*Launched an instance -  Using Ubuntu Server 20.04LTS(HVM)
![alt text](./Images/Launching%20an%20instance.JPG)


*Connected to instance via OpenSSH (SSH client)

![alt text](./Images/Connect%20to%20instance.JPG)

*Connected to Ubuntu Server via Windows Powershell using command

<code>ssh -i "Keypair.pem" ubuntu@ec2-54-147-140-31.compute-1.amazonaws.com</code>
![alt text](./Images/instances.JPG)

* Practiced other linux commands, ran the <code> sudo apt get-update</code> to update the OS.
![alt text](./Images/Ubuntu%20virtual%20server.JPG)


## <center>INSTALLING APACHE AND UPDATING THE FIREWALL</center>

To install Apache web server, open up Terminal and run the following commands ;

*First update a list of packages in the package manager

<code> sudo apt update</code>

![Updating package manager](./Images/apt%20update.JPG)


*Next Installing apache2 web server 

<code>sudo apt install apache2</code>

![Installing apache2 webserver](./Images/sudo%20install.JPG)


*To verify that the apache2 web server is running , run the command below

<code>sudo systemctl status apache2</code>

![Apache2 status](./Images/sudo%20status%20running.JPG)


Web Server succssfully launched! :sunglasses:

To enable Web Server to receive any traffic we need to open port HTTP port 80 by editing inbound rule by clicking on the instance > Security tabEC2 > Security>sg-0b43ccbb91eb6f08e (instance name)> edit inbound rules

![Inbound rules](./Images/inbound%20rule%20port%2080%20tcp.JPG)

