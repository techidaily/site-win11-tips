---
title: Steps to Disable Persistent Network Login Notifications
date: 2024-11-14T20:24:47.762Z
updated: 2024-11-17T17:05:36.399Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Disable Persistent Network Login Notifications
excerpt: This Article Describes Steps to Disable Persistent Network Login Notifications
keywords: Stop Network Login Alerts,Quiet Network Access Alert,Disabling Network Login Prompts,Halt Network Login Notifications,End Repeated Login Notifications,Silence Network Login Messages,Block Persistent Login Warnings
thumbnail: https://thmb.techidaily.com/829637766daad5158a0e2799ab45977f98c34111cdb4f87264835a3e2bfe371a.jpg
---

## Steps to Disable Persistent Network Login Notifications

 The network credentials on your PC are important because they prevent others from using your computer across the network. While this feature is essential to protect your important files and improve the overall security of your system, it can sometimes cause issues as well.

 A common problem is when the network credential manager keeps displaying the "Enter network credentials" dialog, even when you enter the correct credentials. In this guide, we will walk you through some troubleshooting methods you can try to fix this issue for good.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Modify the Advanced Sharing Settings

 An incorrectly set Advanced Sharing setting is one of the most common causes of this error. Ideally, your PC should be allowed to manage homegroup connections. You can also use the Advanced Sharing settings page to disable password-protected sharing, which will allow you to share files without needing to log in.

 Here is how you can configure the Advanced Sharing settings correctly:

1. Locate the network icon on your taskbar and right-click on it.
2. Choose **Network and Internet settings** from the context menu.  
![Network and Internet settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/network-and-internet-settings.jpg)
3. In the following window, select **Network and Sharing Center**.
4. Choose **Change advanced sharing settings** option in the left pane.
5. Now, enable the **Allow Windows to manage homegroup connections (recommended)** option under Homegroup connections.
6. Click **Save changes** (you will need administrative access for this).
7. Now, expand the **All Networks** section and enable the **Turn off password protected sharing** option.  
![Turn off password sharing option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/turn-off-pasword-sharing.jpg)
8. Hit the **Save changes** button to complete the process.

 After you've transferred the files, re-enable password-protected sharing so that others don't get easy access to your PC.

## 2\. Use Your Microsoft Account Credentials or the Computer's Name

 You can also try logging onto the target PC using the Microsoft account credentials instead of the local username and password.

 Alternatively, you can also try using the name of the computer you are using alongside your username in the text field associated with the Username. Do not enter a space, bar, or any other symbol between the names.

 If the problem is associated with the credentials, one of these two methods is likely to help you get rid of it for good.

## 3\. Manually Add the Credentials of the Target Computer to the Credential Manager

 Another way to fix the issue is by manually adding the credentials of the targeted computer in the Credential Manager and seeing if that makes a difference.

 Here is how you can do that:

1. Type "Credential Manager" into Windows Search and click **Open**.
2. Select **Windows Credential** and click on **Add a Windows Credential**.  
![Windows credentials](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/windows-credentials-1.jpg)
3. Now, add the username, computer name, and password of the computer you are trying to access. Check if you can now share files with the other device successfully.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047411/19272" target="_top" id="2047411">
  <img src="//a.impactradius-go.com/display-ad/19272-2047411" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047411/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Create a New User Account on Both Devices

 There are times when user accounts become corrupt and stop you from performing certain actions. If this has happened, either on your PC or the target computer, it can interrupt the file-sharing process.

 To fix this problem, first, try [switching to a different user account](https://www.makeuseof.com/windows-11-switch-user-accounts/) on your own computer and see if that works. If this strategy fails, then we recommend [creating a new user account](https://www.makeuseof.com/windows-11-create-local-user-account/) on both devices with the same username and password. Make sure that both accounts have administrative privileges. While you are at it, we also suggest temporarily disabling any third-party antivirus program that you might be using, as it can sometimes block network access.

 If the root of your issue was a corrupt user account, this should be enough to fix the issue.

## 5\. Restart the Credential Manager Service

 The issue might also be with the Credential Manager service itself instead of the targeted computer or the network settings of your device. In this method, we will first enable the Credential Manager service if the service is disabled.

 If it is working already, then we will proceed with restarting the service and see if that does the trick.

 Here is what you need to do:

1. Press **Win** \+ **R** to open Run.
2. Type services.msc in the Run and click **Enter**.
3. In the following window, look for the Credential Manager service and right-click on it.
4. Choose **Properties** from the context menu.
5. If the service is disabled, click on the **Start button** to enable it.
6. In case it is working already, click on the **Stop button**, wait for a few seconds, and then hit the **Start button**.
7. ![Credential Manager properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/credential-manager-properties.jpg)  
 Make sure that the Startup type is set to **Automatic**.  

![Credential Manager service properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/credential-manager-service.jpg)
8. Click **Apply** \> **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528689/16446" target="_top" id="1528689">
  <img src="//a.impactradius-go.com/display-ad/16446-1528689" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528689/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now try connecting to the targeted computer and see if you can do so without any problems.

## 6\. Make Changes to the Local Security Policy

 Several users also managed to fix the problem by modifying the settings of the "Accounts: Limit local account use of blank passwords to console logon only" policy. Here is how you can give it a try too:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "secpol.msc" in Run and click **Enter**.
3. In the following window, navigate to the following location:  
Local Policies > Security Options > Accounts: Limit local account use of blank passwords to console logon only
4. Choose **Disabled** and click **Apply** \> **OK** to save the changes.  
![Make changes to the Local Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-security-policy.jpg)
5. Restart your computer and check if the issue is resolved.

## 7\. Try Using Safe Mode With Networking

 If the credentials you are entering and all the network configurations on the system are correct, something might have gone wrong on a system level.

 In this case, you can boot into Safe Mode to determine the cause of the issue. Safe Mode starts Windows with only the basic set of drivers and apps — the ones that are essential for the operating system to function.

 There are several types of Safe Mode including Minimal, Alternate Shells, Active Directory Repair, and Network. In this method, we will be booting Windows into Safe Mode with Networking. This mode launches Windows with the drivers and programs required to connect the system to the internet or other devices over the network.

 If the error at hand does not appear in Safe Mode, then there is a chance that malware or other software issues are causing the problem.

 Here is what you need to do:

1. Head over to the Start menu and click on the **Power button**.
2. Choose **Restart** while holding the **Shift key**.
3. Wait for the Windows to boot into the recovery mode and then choose **Troubleshoot** \> **Advanced Options**.
4. Navigate to **Startup Settings** \> **Restart**.
5. In the following window, press the **F5 key** on your keyboard to boot into Safe Mode with Networking.  
![Pick safe mode with Networking option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/Tweak-Startup-Settings-1.jpg)
6. Once you are logged into Safe Mode, try connecting to the device you were previously trying to connect to. If the error does not appear in Safe Mode, then you might want to report this issue to Microsoft’s official support team and wait for a fix from their side.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132160/7443" target="_top" id="2132160">
  <img src="//a.impactradius-go.com/display-ad/7443-2132160" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132160/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In case you cannot access this Windows state using the steps outlined above, you can try [other ways of booting into Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/).

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136627/26400" target="_top" id="2136627">
  <img src="//a.impactradius-go.com/display-ad/26400-2136627" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136627/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Share Data Over Network Without Issues

 Windows has made it simpler to share your files and other data across networks, but there are times when you run into unexpected errors. Hopefully, one of the methods mentioned above did the trick for you in fixing the issue under consideration.

 A common problem is when the network credential manager keeps displaying the "Enter network credentials" dialog, even when you enter the correct credentials. In this guide, we will walk you through some troubleshooting methods you can try to fix this issue for good.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/n-2024-essential-guide-to-hashtagging-for-game-focused-yt-channels/"><u>[New] In 2024, Essential Guide to Hashtagging for Game-Focused YT Channels</u></a></li>
<li><a href="https://youtube-web.techidaily.com/tudents-guide-to-top-10-best-history-youtube-sources/"><u>[New] Student's Guide to Top 10 Best History YouTube Sources</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-watching-the-future-on-screen-androids-2023-update-on-vr/"><u>2024 Approved Watching the Future on Screen - Android's 2023 Update on VR</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/audio-from-visuals-making-mp3s-from-instagram-content-for-2024/"><u>Audio From Visuals Making Mp3s From Instagram Content for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-using-github-desktop-in-windows-step-by-step-guide/"><u>Efficiently Using GitHub Desktop in Windows: Step-by-Step Guide</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fixing-persistent-sound-cutouts-in-discord-comprehensive-2-steps-to-stability/"><u>Fixing Persistent Sound Cutouts in Discord - Comprehensive 2# Steps to Stability</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-detect-and-remove-spyware-on-motorola-g54-5g-drfone-by-drfone-virtual-android/"><u>How to Detect and Remove Spyware on Motorola G54 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-remove-the-spotlight-wallpaper-icon-from-windows-11s-desktop/"><u>How to Remove the Spotlight Wallpaper Icon From Windows 11’S Desktop</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-nailing-the-perfect-aspect-ratio-on-tweets/"><u>In 2024, Nailing the Perfect Aspect Ratio on Tweets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-wsl-upgrades-in-new-windows-environments/"><u>Navigating WSL Upgrades in New Windows Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-obstacles-in-onedrive-folder-integration-on-windows/"><u>Overcoming Obstacles in OneDrive Folder Integration on Windows</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/securing-stability-techniques-for-quality-video-with-logitech-for-2024/"><u>Securing Stability Techniques for Quality Video with Logitech for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sound-and-sight-synergy-on-windows-an-efficient-drivers-upgrade-guide/"><u>Sound and Sight Synergy on Windows: An Efficient Drivers Upgrade Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-untapped-potential-within-windows-11s-offerings/"><u>The Untapped Potential Within Windows 11'S Offerings</u></a></li>
<li><a href="https://facebook.techidaily.com/timing-your-marketing-to-reach-more-users/"><u>Timing Your Marketing to Reach More Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-desktop-with-customizable-animated-clock-themed-screensaver-creation-tools/"><u>Transform Your Desktop with Customizable, Animated Clock-Themed Screensaver Creation Tools</u></a></li>
<li><a href="https://win-comparisons.techidaily.com/unveiling-the-mechanics-of-adware-exploring-its-structure-and-profit-driving-schemes/"><u>Unveiling the Mechanics of Adware: Exploring Its Structure & Profit-Driving Schemes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-over-windows-woes-unraveling-and-fixed-11-issues/"><u>Win Over Windows Woes - Unraveling & Fixed 11 Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-search-removing-visuals/"><u>Windows Search: Removing Visuals</u></a></li>
</ul></div>

