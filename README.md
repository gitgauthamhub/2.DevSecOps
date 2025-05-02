2.DEVSECOPS
============

Client Server , Firewall , Authentication Method , Keys Generation , Launch Server , Connecting Server
=======================================================================================================


What is computer == IP enabled device

Computer == laptop, mobile, server, chip, tv 
Server == only to host applications

RAM, OS, HD, Processor == IP enabled device


1.Client Server Architecture  == Who is Client & Who is Server
=============================================================

Software == Networking & Computers

1. Network                                    Note : We are connecting Amazon Server through Network
2. Amazon application                         Note : We are not connect to Amazon application, may be the Amazon application Down 

Example 
Serve ==> Doctor serves to us, we are his client
Tcs is a Server   ==> Tcs clients is a Icici Bank 

Instagram is in Linux server

https://www.Instagram.com
Protocol == https >> Port == 443 >> IP == DNS IP >> Username and Password  == This is called Authentication

If Issue on Instagram website
Instagram Employee connects to Instagram Server you need to use == SSH 
>>  SSH == Secure shell  
>>  Port: 22
>>  IP,
>>  Username and Password / Private-key


Note : Now we Create a Linux Server in AWS cloud == Aws Account
===============================================================

What is Firewall == A firewall is a Network Security Before we need to connect to particular Server 


2. Firewall ==> Checks Inbound and Outbound Traffic
====================================================
Inbound ==> Incoming Traffic >> Port no: 22,  >> IP : 106.222.229.55
                                              Note : What is my IP ? Search in google.com then you got ur sys IP Address
Outbound ==> Outgoing Traffic


3.Authentication
================
1. What you know ==> Username, Password
2. What you have ==> Keys, Tokens, Authentication, RSA Token
3. What you are ==> Fingerprint, Retina, Palm, Face


How to Authentication for the Server ==> Server == Node == Box
===============================================================
Example  >> Lock is a = Public  &&  Key is a  = Private

In Software we have Key Pairs ==> Public Key and Private Key


1. Create Key pair                           == 1st we generate key pair 
2. Create Firewall                           == 2nd in AWS cloud account create firewall
3. Import Public key to AWS account
4. Create Server and attach Public key
5. Attach Firewall to Server


=================================================================================================================================

Download ==> https://git-scm.com/downloads
Git Bash ==>  Mini Linux in Windows
SSH Client

Browser ==> http/https client             Note : browser is a http or https client
Linux Server ==> SSH Server               linux server is a ssh server    == Note : to connect this server , we need client software

git bash = putty = super putty = mobaxterm = mac terminal = windows cmd           

Above are called >> ssh clients           Note : Now use this ssh clients to connect the server


User Directory
C:\Users\grk ==> windows format
/c/Users/grk ==> linux format

Windows ==> not case sensitive, GIT == git == Git                    ==> C:\devops\daws-84s   Windows Format
Linux ==> case sensitive, Git != grk no space in linux              ==> /c/devops/daws-84s   Linux Format


=================================================================================================================================

Open >> git bash 
$ pwd 
$ cd  /c/devops/daws-84s

ssh-keygen -f <file-name>                    Note : To create keys we need a command 

$ ssh-keygen -f daws-84s                     Note : Goto c-drive let see u have 2 files  Public && Private 
                                                    Open Public key & copy to import AWS
                                                    Sign in to AWS account 

ssh-rsa long-random-code 
Region ==> us-east-1

LOGIN >> AWS CONSOLE 
goto  >> Security group                    Note : This is firewall, Firewall is nothing todo Security Group 
      >> Create security group
    

![image](https://github.com/user-attachments/assets/7ead6911-8392-4d8e-a64a-aaff45c9cc42)


     ![image](https://github.com/user-attachments/assets/66a86b2e-a6cc-475b-b39e-63f5c665faf1)

     ![image](https://github.com/user-attachments/assets/5f2c5cab-d1e0-495c-b270-595e1c68f848)
     


goto >> Key pair                         Note : Import Public Key here  ( Not Create )

![image](https://github.com/user-attachments/assets/42dc05e2-a144-487f-a50d-e1e8fe739e41)

lauch the Server >> Ec2 Instance

Note : Now connect from Internet it should be Public ID : 
Public Id : 108.22.54.28, Port no : 22, Protocol : SSH, User Name : ec2-user, private-key

=================================================================================================================================

Open >> git bash 
$ ssh -i daws-84s ec2-user@108.22.54.28            Note : ssh -i <private-key> ec2-user@108.22.54.28

=================================================================================================================================

What is OS --> Redhat, Ubuntu, centos, fedore, suse, oracle linux, amazon linux, debian, rocky linux, kali, solaris

Linux is OS or not --> Linux is Kernel

OS --> To interact with Hardware

Kernal --> heart and brain of OS

Kernel + UI == OS

Redhat --> kernel + user interface ==> Redhat OS
Debian --> Linux kernel + UI ==> Debian

99.9% same all Linux distros/flavours

Redhat --> Open source --> code is free
Redhat enterprise RHEL --> support

RHEL = AWS Linux = Centos = Fedora = Rocky Linux = AlmaLinux

command <options> <inputs>

/home/ec2-user --> linux home directory
/c/users/siva --> windows home directory

cd  //change directory

cd .. //one step back

ls //list subdirectories
