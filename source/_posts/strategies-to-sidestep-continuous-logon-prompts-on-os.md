---
title: Strategies to Sidestep Continuous Logon Prompts on OS
date: 2024-10-18T19:43:17.356Z
updated: 2024-10-20T21:49:34.863Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies to Sidestep Continuous Logon Prompts on OS
excerpt: This Article Describes Strategies to Sidestep Continuous Logon Prompts on OS
keywords: Avoid Login Interruptions,Bypass OS Logons,Eliminate Auto Login,Skip Logon Prompts OS,Dodge System Sign-Ins,Evasive Login Avoidance,Reduce Login Requests
thumbnail: https://thmb.techidaily.com/d8236c8823bf190018d4a9a0035905199e51992e3c45e7b977770451483aa69d.jpg
---

## Strategies to Sidestep Continuous Logon Prompts on OS

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

## 4\. Create a New User Account on Both Devices

 There are times when user accounts become corrupt and stop you from performing certain actions. If this has happened, either on your PC or the target computer, it can interrupt the file-sharing process.

 To fix this problem, first, try [switching to a different user account](https://www.makeuseof.com/windows-11-switch-user-accounts/) on your own computer and see if that works. If this strategy fails, then we recommend [creating a new user account](https://www.makeuseof.com/windows-11-create-local-user-account/) on both devices with the same username and password. Make sure that both accounts have administrative privileges. While you are at it, we also suggest temporarily disabling any third-party antivirus program that you might be using, as it can sometimes block network access.

 If the root of your issue was a corrupt user account, this should be enough to fix the issue.

<!-- affiliate ads begin -->
<span id="1982485">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982485.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982485">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982485.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982485%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982485/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135357/19272" target="_top" id="2135357">
  <img src="//a.impactradius-go.com/display-ad/19272-2135357" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135357/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Credential Manager service properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/credential-manager-service.jpg)
8. Click **Apply** \> **OK** to save the changes.

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

<!-- affiliate ads begin -->
<span id="1977023">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977023.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977023">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977023.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977023%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977023/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

 In case you cannot access this Windows state using the steps outlined above, you can try [other ways of booting into Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068439/7443" target="_top" id="2068439">
  <img src="//a.impactradius-go.com/display-ad/7443-2068439" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068439/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Share Data Over Network Without Issues

 Windows has made it simpler to share your files and other data across networks, but there are times when you run into unexpected errors. Hopefully, one of the methods mentioned above did the trick for you in fixing the issue under consideration.

 A common problem is when the network credential manager keeps displaying the "Enter network credentials" dialog, even when you enter the correct credentials. In this guide, we will walk you through some troubleshooting methods you can try to fix this issue for good.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/updated-mobile-vr-experience-best-10-headsets-list/"><u>[Updated] Mobile VR Experience Best 10 Headsets List</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-techniques-for-fabulous-photo-collage-artistry/"><u>[Updated] Techniques for Fabulous Photo Collage Artistry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comparative-analysis-of-windows-toolsets-chkdsk-sfc-and-dissect/"><u>Comparative Analysis of Windows Toolsets: CHKDSK, SFC, & Dissect</u></a></li>
<li><a href="https://facebook.techidaily.com/comprerancial-online-presence-facebook-profiles-vs-usernames/"><u>Comprerancial Online Presence: Facebook Profiles Vs Usernames</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-package-fail-message-a-windows-10-11-solution-guide/"><u>Decoding the 'Package Fail' Message: A Windows 10, 11 Solution Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-android-software-for-windows-desktop-owners/"><u>Essential Android Software for Windows Desktop Owners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-new-ui-in-windows-11/"><u>Exploring New UI in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-resolving-dxgierror-on-windows-11-devices/"><u>Guidelines for Resolving DXGIError on Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reclaim-write-permissions-on-windows-folders/"><u>How to Reclaim Write Permissions on Windows Folders</u></a></li>
<li><a href="https://vp-tips.techidaily.com/il-meglio-dei-programmi-gratuiti-per-la-trasformazione-di-musica-e-audio-top-15-raccomandati/"><u>Il Meglio Dei Programmi Gratuiti per La Trasformazione Di Musica E Audio: Top 15 Raccomandati</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-tiktok-to-see-more-content-on-your-apple-iphone-13-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Change Location on TikTok to See More Content On your Apple iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-a-vivo-y200e-5g-easily-by-drfone-android/"><u>In 2024, How To Unlock a Vivo Y200e 5G Easily?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/navigating-chatgpts-stream-errors-successfully/"><u>Navigating ChatGPT's Stream Errors Successfully</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-sony-camcorder-video-editing-tutorial-from-capture-to-masterpiece-for-2024/"><u>New Sony Camcorder Video Editing Tutorial From Capture to Masterpiece for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-directdraw-hurdles-in-windows-1011-systems/"><u>Resolving DirectDraw Hurdles in Windows 10/11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-address-error-incorrect-token-usage-in-windows-os/"><u>Steps to Address “Error: Incorrect Token Usage” In Windows OS</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/telechargez-les-meilleurs-extracteurs-de-dvd-pour-windows-10-and-11-gratuitement-edition-complete/"><u>Téléchargez Les Meilleurs Extracteurs De DVD Pour Windows 10 & 11 Gratuitement - Édition Complète</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-complete-walkthrough-on-reactivating-your-iphone-15/"><u>The Complete Walkthrough on Reactivating Your iPhone 15</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-hidden-search-box-how-to-use-it-in-win11-tm/"><u>Unveiling the Hidden Search Box – How to Use It in Win11 TM</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    