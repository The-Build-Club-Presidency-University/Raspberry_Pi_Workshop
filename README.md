<h1 align="center">Raspberry Pi Workshop</h1>

## Initial Kickstart Learning Resources
### Setup for First-time
  * **Setup Headless Mode** - [hackster.io](https://www.hackster.io/435738/how-to-setup-your-raspberry-pi-headless-8a905f)
  * Some Software you may have to install during this process are:
    * VNC Viewer - [DOWNLOAD Link](https://www.realvnc.com/en/connect/download/viewer/) 
    * PuTTY - [DOWNLOAD Link](https://www.putty.org/) (Only Windows User)
    > PuTTY is an SSH and telnet client. So if you are a Mac/Linux user then you have to enable SSH
    * Enable the SSH Server on a Mac - [Reference](https://osxdaily.com/2022/07/08/turn-on-ssh-mac/)
    * Enable the SSH Server on a Linux - [Reference](https://www.cyberciti.biz/faq/ubuntu-linux-install-openssh-server/)
    * Connect to Raspberry Pi throgh SSH go to shell and type ```ssh pi@192.168.x.x``` [pi - username , 192.168.x.x - IP address of RPi]
    > If Default Username and Password is: username: pi, password: raspberry
  * There are many People who don't feel like working on CLI (command-line interface)... So, to see the complete GUI (Graphical user interface) for better interaction and use it as your standard PC we have some of the Most Popular remote desktop Software... and one of them comes onBoard, VNC Server So, we need to enable it from Raspberry Pi.
So, to do that the following steps are:
    * **Step 01 -** open PuTTy and get connected to Raspberry Pi over SSH 
    * **Step 02 -** enter the command: ```sudo raspi-config```
    * **Step 03 -** Use the arrow keys to select Interfacing Options and press Enter
    * **Step 04 -** Use the arrow keys to select VNC and press Enter
    * **Step 05 -** You will be prompted to enable VNC Server. Select Yes and press Enter
    * **Step 06 -** Use the arrow keys to select Ok and then Finish, to return to the terminal
  * Now if you are are a **WINDOWS** User there is a inbuild Remote Desktoping Software. So the following steps are:
    * **Step 01 -** open PuTTy and get connected to Raspberry Pi over SSH 
    * **Step 02 -** enter the command: ```sudo apt install xrdp```
    * **Step 03 -** after its get install go to your Main Windows Machine and At the Search bar, type > ```Remote Desktop Connection```
    * **Step 04 -** Computer : type the IP address of the Raspberry Pi
    * **Step 05 -** clink Connect button
    * **Step 06 -** Clink YES to confirm [ its for first time connection only ]
    * **Step 07 -** At the login screen, type Username/Password of our Raspberry and then click on OK button. and u are in...
    
> Supportable for All OS like: Windows, MacOS, Linux. During this Setuping part Internet, Connective is imported for the initial stage 

### How to Enable Few Ports/ Protocols for better connectivity with other Raspberry Pi Hats or any electronic module
