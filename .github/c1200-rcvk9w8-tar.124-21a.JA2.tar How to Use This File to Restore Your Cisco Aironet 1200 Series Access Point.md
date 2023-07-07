# How to Upgrade Cisco Aironet 1200 Series Access Point Firmware with c1200-rcvk9w8-tar.124-21a.JA2.tar
 
If you have a Cisco Aironet 1200 Series Access Point and you want to upgrade its firmware to the latest version, you might be interested in using the c1200-rcvk9w8-tar.124-21a.JA2.tar file. This file is a lightweight recovery image that can be used to register the access point to a wireless LAN controller (WLC) and download the full firmware from there.
 
**Download File &gt;&gt;&gt; [https://kneedacexbrew.blogspot.com/?d=2uK8nd](https://kneedacexbrew.blogspot.com/?d=2uK8nd)**


 
In this article, we will show you how to use the c1200-rcvk9w8-tar.124-21a.JA2.tar file to upgrade your Cisco Aironet 1200 Series Access Point firmware in a few simple steps.
 
## Step 1: Download the c1200-rcvk9w8-tar.124-21a.JA2.tar file
 
The first step is to download the c1200-rcvk9w8-tar.124-21a.JA2.tar file from the Internet Archive[^1^]. This file is part of the cIOS-firmware-images collection that contains various firmware images for Cisco devices. You can also find other firmware images for different models of Cisco Aironet access points in the same collection.
 
Once you have downloaded the file, save it to a convenient location on your computer.
 
## Step 2: Connect the access point to your computer
 
The next step is to connect the access point to your computer using an Ethernet cable. You will need to configure your computer's network settings to match the default IP address of the access point, which is 10.0.0.1. You can do this by following these steps:
 
- Open the Control Panel on your computer and click on Network and Internet.
- Click on Network and Sharing Center and then click on Change adapter settings.
- Right-click on the Ethernet adapter that is connected to the access point and select Properties.
- Select Internet Protocol Version 4 (TCP/IPv4) and click on Properties.
- Select Use the following IP address and enter 10.0.0.2 as the IP address, 255.255.255.0 as the subnet mask, and 10.0.0.1 as the default gateway.
- Click OK to save the changes and close the windows.

Now you should be able to ping the access point from your computer by opening a command prompt and typing ping 10.0.0.1.
 
## Step 3: Upload the c1200-rcvk9w8-tar.124-21a.JA2.tar file to the access point
 
The next step is to upload the c1200-rcvk9w8-tar.124-21a.JA2.tar file to the access point using a TFTP server on your computer. You can use any TFTP server software that you prefer, such as TFTPD32 or SolarWinds TFTP Server. You will need to configure the TFTP server software to use the same folder where you saved the c1200-rcvk9w8-tar.124-21a.JA2.tar file as the root directory.
 
Once you have set up the TFTP server, you will need to access the access point's console using a serial cable and a terminal emulator software such as PuTTY or HyperTerminal. You will need to use these settings for the serial connection:
 
c1200-rcvk9w8-tar.124-21a.JA2.tar download,  c1200-rcvk9w8-tar.124-21a.JA2.tar upgrade,  c1200-rcvk9w8-tar.124-21a.JA2.tar release notes,  c1200-rcvk9w8-tar.124-21a.JA2.tar md5,  c1200-rcvk9w8-tar.124-21a.JA2.tar cisco,  c1200-rcvk9w8-tar.124-21a.JA2.tar ios,  c1200-rcvk9w8-tar.124-21a.JA2.tar wireless,  c1200-rcvk9w8-tar.124-21a.JA2.tar autonomous,  c1200-rcvk9w8-tar.124-21a.JA2.tar lightweight,  c1200-rcvk9w8-tar.124-21a.JA2.tar ap,  c1200-rcvk9w8-tar.124-21a.JA2.tar archive,  c1200-rcvk9w8-tar.124-21a.JA2.tar extract,  c1200-rcvk9w8-tar.124-21a.JA2.tar install,  c1200-rcvk9w8-tar.124-21a.JA2.tar tftp,  c1200-rcvk9w8-tar.124-21a.JA2.tar ftp,  c1200-rcvk9w8-tar.124-21a.JA2.tar scp,  c1200-rcvk9w8-tar.124-21a.JA2.tar sftp,  c1200-rcvk9w8-tar.124-21a.JA2.tar http,  c1200-rcvk9w8-tar.124-21a.JA2.tar https,  c1200-rcvk9w8-tar.124-21a.JA2.tar ssh

- Baud rate: 9600
- Data bits: 8
- Parity: None
- Stop bits: 1
- Flow control: None

After connecting to the console, you will see a prompt like this:

    ap:

You will need to enter these commands at the prompt:

    ap: set IP_ADDR 10.0.0 8cf37b1e13

    
