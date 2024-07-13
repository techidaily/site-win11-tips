---
title: "Rejoining Fall Guys: Fixing Connectivity Issues on PC"
date: 2024-06-25T16:09:01.183Z
updated: 2024-06-26T16:09:01.183Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Rejoining Fall Guys: Fixing Connectivity Issues on PC"
excerpt: "This Article Describes Rejoining Fall Guys: Fixing Connectivity Issues on PC"
keywords: Fixing Fall Guys PC,Fall Guys Connection Troubleshoot,Resolve Fall Guys PC Links,Restore Fall Guys Online Access,Reconnect Fall Guys Gameplay,Enhance Fall Guys PC Play,Optimize Fall Guys Networking
thumbnail: https://thmb.techidaily.com/10b343d090bf904bc6bf8fe5ac35deb164bc4c88645e3dc6ba8f681d6f6e808f.jpg
---

## Rejoining Fall Guys: Fixing Connectivity Issues on PC

 Connection errors are a real curse for online games like Fall Guys. Not only do they spoil the gaming mood, but they also stop you from continuing your ranked hot streak. Luckily, it's very easy to fix connection errors in Fall Guys.

 In this article, we'll see all the possible culprits behind a connection error in Fall Guys, along with ways to eliminate them. So, let's get started.

## What Causes a Connection Error in Fall Guys for Windows?

 It's very easy to log in to Fall Guys and play it on your computer. But if you're unable to log in and see a connection error, the following can be the reasons behind it:

1. Your internet connection is weak or unstable.
2. You're using a VPN or proxy server.
3. Windows Firewall is blocking Fall Guys from accessing the internet.

 Now that we know all the possible culprits behind the issue, let's jump into the fixes.

## 1\. Check Your Connection

 Before making any changes to your network settings, ensure that a weak internet connection is not causing the issue. You can check this by visiting an [internet-speed testing website](https://www.makeuseof.com/best-free-websites-test-internet-speed/) .

 If the results show that your connection is unstable and weak, then you'll have to troubleshoot your connection. Check out our guide on [network diagnostic tricks you can try](https://www.makeuseof.com/tag/7-simple-steps-diagnose-network-problem/) for ways to get your connection fixed again.

 f manual troubleshooting makes no difference, consider contacting your ISP.

## 2\. Close Network Hogging Applications from Background

 Connection errors in most online games often result from network-hogging applications running in the background. These applications consume most of the available bandwidth, leaving the main application (Fall Guys, in this case) with limited options.

 In this case, the best thing to do is to locate and close all such applications from the background. You can do this with the help of the Task Manager.

 To begin with,[launch the Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) and look for applications consuming the maximum bandwidth. You can detect them by looking at the Network section. Note that the higher the network value, the more bandwidth the application consumes.

![End high network apps in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/end-high-network-apps.jpg)

 Then, right-click on all such applications, and choose**End task.** After that, restart Fall Guys and check if the problem persists.

## 3\. Temporarily Disable the Windows Firewall

 Windows Firewall can interfere with the working of Fall Guys and cause connection errors. The solution, in this case, is to temporarily disable the Windows Firewall.

Here's how you can do that:

1. Open the**Windows Search** by pressing the**Win + S** hotkey, type**Windows Defender Firewall,** and press Enter.
2. Choose**Windows Defender Firewall on or off** in the left sidebar.  
![Turn Windows Defender on or off option in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/turn-windows-defender-on-or-off.jpg)
3. Choose**Turn off Windows Defender Firewall (not recommended)** option for both**private** and**public** network settings.  
![Turn off firewall option in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/turn-off-firewall.jpg)

 Now, check if the problem continues. If not, enable the Windows Defender Firewall and then add Fall Guys to the Windows Firewall exception list. Here's how:

1. In the Windows Search, type**Allow an app through Windows Firewall** and press**Enter** .
2. Click the**Change settings** button and then choose the**Allow another app** option.
3. Click**Browse** from the window that crops up.  
![Browse option in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/browse-option.jpg)
4. Go to the Fall Guys installation folder. It'd be**C:\\Program Files\\Epic Games\\FallGuys** if you kept the same target location during installation.
5. Select**FallGuys\_client.exe** and click**Add.**  
![FallGuys file in browse option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/fallguys-file.jpg)

 That's it! Fall Guys has now been added to the Windows Firewall exception list.

## 4\. Disable Any Active Proxy Servers

 If you're connected to a [proxy server](https://www.makeuseof.com/tag/what-is-a-proxy-server/) , there's a chance it can cause connection issues. So, disable any proxies you are using and check if it resolves the problem. Here's how you can do it:

1. Open the Windows Search, type**Command Prompt,** and choose**Run as administrator** from the right pane.
2. In the console, type**netsh winhttp reset proxy** and press**Enter** .  
![Disabling proxy command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disabling-proxy.jpg)

## 5\. Connect to a Different DNS Server

 Sometimes, the DNS you're using might not be the fastest. The best thing to do in this situation is to switch to a public DNS like Google DNS. Switching to a public DNS will ensure that you get better connectivity and performance from your internet connection.

Follow the below steps to change to Google DNS:

1. Use one of the many [ways to open the Control Panel](https://www.makeuseof.com/windows-11-open-control-panel/) .
2. Navigate to**Network and Internet** \>**Network and Sharing Center** .
3. Click on your connection name and choose**Properties** from the window that crops up.
4. Select**Internet Protocol Version 4 (TCP/ IPv4)** or**Internet Protocol Version 6 (TCP/ IPv6)** and then click**Properties.**  
![IPv6 option in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/ipv6-option.jpg)
5. Select the**Use the following DNS server addresses** option.
6. If you're on IPv4, type**8.8.8.8** in the**Preferred DNS server** and**8.8.4.4** in the**Alternate DNS server.**
7. If you're on IPv6, type**2001:4860:4860::8888** in the**Preferred DNS server** and**2001:4860:4860::8844** in the**Alternate DNS** server.  
![Editing IPv6 properties in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/editing-ipv6-properties.jpg)
8. Click**OK.**

## 6\. Edit the Fall Guys Engine.ini File

 The next thing you can try to fix the connection error in Fall Guys is to edit the Engine.ini file. Here's how to do it:

1. Open the Run dialog box by pressing the**Win + R** hotkeys, type**%localappdata%,** and click**OK.**
2. Navigate to**EpicGamesLauncher** \>**Saved** \>**Config** \>**Windows.**
3. Right-click on the**Engine.ini** file, hover the cursor to**Open** with, and choose**Notepad** from the context menu.
4. In the Notepad window that appears, type the following lines and then press**Ctrl + S** to save it.  
`[HTTP]  
HttpTimeout=10  
HttpConnectionTimeout=10  
HttpReceiveTimeout=10  
HttpSendTimeout=10  

[Portal.BuildPatch]  
ChunkDownloads=3  
ChunkRetries=20  
RetryTime=0.5`

![Editing the Engine.ini file in Notepad](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/editing-the-engine-ini-file.jpg)

Launch Fall Guys and check if the problem persists.

## 7\. Reset Winsock Settings

 Winsock is a program that allows programs to connect to the internet through Transmission Control Protocol/ Internet Protocol (TCP/IP). If there's something wrong with this program, apps like Fall Guys will struggle to connect to the internet.

 To fix this, you will have to reset the Winsock data. You can do this by following the below steps:

1. Open Command Prompt with admin rights, as we covered in method four above.
2. Type**netsh winsock reset** and press**Enter** .  
![Reset Winsock command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reset-winsock-command.jpg)

Now, restart your computer and check if the problem is fixed.

## Your Fall Guys Connection Errors, Fixed

 Fall Guys, like most multiplayer games, requires an internet connection to function. But when it fails to connect to the internet, it is of little use. Fortunately, it is a very common issue and can easily be fixed using the above fixes.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>


