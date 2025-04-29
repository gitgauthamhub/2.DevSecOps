# 2.DevSecOps
Client server , Firewall , Authentication method , Keys generation , Launch Server , Connecting server


what is computer == IP enabled device

Computer = laptop, mobile, server, chip, tv 
Server = only to host applications

RAM, OS, HD, Processor == IP enabled device


1.Client Server Architecture  == Who is Clent & Who is Server
===========================    ============================

Software == Networking & Computers

1. Network           Note : We are connecting Amazon Server through Network
2. Amazon application   Note : We are not connect to Amazon application, may be the Amazon application Down 

Example 
Serve ==> Doctor serves to us, we are his client
Tcs is a Server   ==> Tcs clients is a Icici Bank 

Instagram is in Linux server, if problem comes we need to login to server

https://www.Instagram.com
Protocol == https >> Port == 443 >> IP == DNS IP >> Username and Password  == This is called Authentication

A Instagram Employee connects to Instagram Server you need to use == SSH 
SSH == Secure shell  >>  Port: 22  >> IP, Username and Password/private-key

2. Firewall --> Checks Inbound and Outbound Traffic
=================================================
Inbound --> incoming traffic --> port number 22, 103.149.59.114
Outbound --> outgoing traffic

Authentication
===============
1. what you know --> username password
2. what you have --> keys, tokens, authentication, rsa token
3. what you are --> fingerprint, retina, palm, face

Server = Node
Lock = Public
Key = Private

Key pairs --> public key and private key


1. Create key pair
2. Create firewall
3. Import public key to aws account
4. Create server and attach public key
5. Attach firewall to server


Git Bash --> Mini Linux in Windows
SSH client

Browser --> http/https client
Linux Server --> SSH Server

git bash = putty = super putty = mobaxterm = mac terminal = windows cmd

ssh clients

pwd --> present working directory

User Directory
C:\Users\siva --> windows format
/c/Users/siva --> linux format

Windows --> not case sensitive GIT == git == Git
Linux --> case sensitive --> Git != siva no space in linux

/c/devops/daws-84s == C:\devops\daws-84s

ssh-keygen -f <file-name>

ssh-keygen -f daws-84s

ssh-rsa long-random-code 

Region --> us-east-1

0.0.0.0/0

98.81.70.98, 22, SSH, ec2-user, private-key

ssh -i <private-key> ec2-user@98.81.70.98

OS --> Redhat, Ubuntu, centos, fedore, suse, oracle linux, amazon linux, debian, rocky linux, kali, solaris

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
