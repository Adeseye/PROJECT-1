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

* Praticed other linux commands, ran the <code> sudo apt get-update</code> to update the OS.
![alt text](./Images/Ubuntu%20virtual%20server.JPG)


## <center>INSTALLING APACHE AND UPDATING THE FIREWALL</center>