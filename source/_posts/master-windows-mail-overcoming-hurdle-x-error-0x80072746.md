---
title: "Master Windows Mail: Overcoming Hurdle X, Error 0X80072746"
date: 2024-11-12T16:21:09.567Z
updated: 2024-11-17T16:01:14.651Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Master Windows Mail: Overcoming Hurdle X, Error 0X80072746"
excerpt: "This Article Describes Master Windows Mail: Overcoming Hurdle X, Error 0X80072746"
keywords: MailError0X80072746,EmailClientHurdles,WinMailOverrideErrors,FixWindowsEmailIssues,XboxMailTroubleshooting,OvercomingWinMailsErrors,MasteringWindowsMailProblems
thumbnail: https://thmb.techidaily.com/749e7224dc77351db9654f3d5b625401a4538e3e09d897a36274e3de6aadbd39.jpg
---

## Master Windows Mail: Overcoming Hurdle X, Error 0X80072746

 The Mail app error 0x80072746 often occurs when users try to access their newly received emails, and it indicates network-related issues within Windows. This error message typically points towards a problem with the mail server or the network connection.

 Below, we take a look at the different troubleshooting methods that can help fix this issue for good.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Allow svchost.exe in the Firewall

 The 0x80072746 error in the Mail app commonly occurs when a third-party firewall interferes with a critical Windows program called svchost.exe.

 This process is responsible to host various essential services necessary for the proper functioning of your Windows operating system. Among these services, the Mail app heavily relies on svchost.exe to establish network connections and download messages.

 If you have installed a third-party security program on your computer, there is a possibility that it is mistakenly blocking svchost.exe. This might be preventing the Mail app from fetching or sending emails, leading to the 0x80072746 error.

 To address this issue, you can check your firewall settings and whitelist svchost.exe. Alternatively, you can [temporarily disable the security program](https://www.makeuseof.com/windows-features-error-0x80071a90/)and check if that fixes the problem.

![Disable antivirus in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-antivirus-windows.jpg)

 It's worth noting that the exact steps of performing this action can vary depending on the specific program you are using. Typically, this information is available in the application settings of the app.

<!-- affiliate ads begin -->
<span id="1484963">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1484963.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1484963">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1484963.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1484963%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1484963/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Modify VPN Settings

 Active VPNs can also interfere with the Mail app's ability to establish network connections, leading to the problem at hand.

 If you are using a VPN on your computer, you can try the following steps to troubleshoot the issue:

* **Disconnect from the VPN**: Temporarily disable the VPN and then try loading messages in the Mail app again. If this fixes the problem, it implies that VPN was causing the problem.
* **Whitelist Mail app or email server**: Launch the VPN settings and look to whitelist the Mail app or email server’s IP address to prevent VPN from interfering with the program’s network connections.
* **Modify VPN protocols or settings**: If it is essential to use the VPN while using the Mail app, you can modify the protocol and check if that makes any difference.

 Here is how you can modify the VPN settings to resolve the Mail app error:

1. Press the **Win** \+ **I** keys together to open the Settings app.
2. Choose **Network & Internet** \> **VPN**.  
![VPN settings in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/vpn-settings-windows.jpg)
3. Enable the **Allow VPN over metered network** option.  
![Allow VPN over metered network in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/vpn-over-metered-network.jpg)
4. Now, head over to the "Related settings" section and choose **Change adapter options**.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137218/26400" target="_top" id="2137218">
  <img src="//a.impactradius-go.com/display-ad/26400-2137218" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137218/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Right-click on your LAN (Wi-Fi) connectivity and choose **Properties** from the context menu.
6. Select **Internet Protocol Version 6 (TCP/PV6)** and click **OK** to save the changes.

 You can now close the Settings app and check if the issue is resolved.

## 3\. Set Up Your Account Manually

 Another reason behind the Mail error 0x80072746 is incorrect server settings and incompatibility with specific email providers, which typically occurs when you rely on the automatic setup process.

 You can eliminate these potential issues with the automatic configuration process by setting up your account manually.

 Therefore, if you previously configured your Mail account using the automatic setup process, you might want to try setting it up manually this time in order to bypass any errors or conflicts.

 Here is how you can do that:

1. Launch the Mail client and click on the **gear icon** at the bottom.
2. Choose **Manage Accounts**.  
![Manage accounts option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/manage-accounts.jpg)
3. Select the problematic email and choose **Delete account from this device** from the options available.  

![Delete the account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/delete-mail-app.jpg)
4. Confirm your action in the next window.
5. Once the email account is removed, launch the official website of your email provider and copy the manual settings for IMAP. If these settings are not available, choose POP3\.

1. Now, head back to the Mail client and launch the settings.
2. Head over to the Manage Account section and choose **Add account**.  
![Add account option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/add-account.jpg)
3. Scroll down and choose **Advanced Setup**.  

![Choose Advanced setup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/advanced-setup-option.jpg)
4. Click on **Internet email** and enter the manual settings you copied earlier.  

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139116/17108" target="_top" id="2139116">
  <img src="//a.impactradius-go.com/display-ad/17108-2139116" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139116/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Click Internet email](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/internet-email-option.jpg)
5. Finally, click on **Sign in** and check if the issue is resolved.

## 4\. Update the Mail App

 Your Mail app might also be outdated, which is preventing it from being fully compatible with the latest email server configurations and security protocols, leading to the error at hand.

 To check if this is the case, you can head over to Microsoft Store and check for the pending updates that might be available for the Mail app. If you find any, take your time to install them and then check if the Mail app can display emails.

 Follow these steps to proceed:

1. Click on the **Microsoft Store icon** in the taskbar to launch the program.
2. Choose the **Library icon** in the bottom left pane.
3. In the following window, click on the **Get updates** button. This should display all the available updates for the installed apps. MS Store will begin to download them automatically.  
![The Get updates button in MS Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-get-updates-button.jpg)
4. Wait for the updates to download and check if the problem is resolved.

 While you are at it, we also recommend installing any system updates that might be available in the Settings app.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014848/22899" target="_top" id="2014848">
  <img src="//a.impactradius-go.com/display-ad/22899-2014848" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014848/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Fix Corruption Issues Within the Mail App

 If updating the application did not help, there are also some other fixes that can help you resolve any corruption issues within the Mail app that might be leading to the problem. This involves [repairing and resetting the Mail application](https://www.makeuseof.com/mail-app-cant-get-mail-windows/).

 The Repair option attempts to fix any damaged or missing files that might be contributing to the error, while the Reset option will restore the default, error-free state of the application. It is important to note, however, that while these solutions are effective at fixing the underlying problem, you are likely to lose your settings and preferences within the Mail app.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075483/7443" target="_top" id="2075483">
  <img src="//a.impactradius-go.com/display-ad/7443-2075483" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075483/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Multiple Ways to Fix the Windows Mail App

 Encountering issues with the Mail app can be incredibly frustrating, especially if you rely on it for your important work. Hopefully, the solutions listed above will help you fix the 0x80072746 error once and for all.

 To avoid problems like this from occurring in the future, we recommend keeping your Mail app up-to-date and whitelisting it in the firewall as well as the VPN.

 Below, we take a look at the different troubleshooting methods that can help fix this issue for good.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-earning-streaming-strategies-8-beginners-tips/"><u>[New] 2024 Approved Earning Streaming Strategies - 8 Beginners' Tips</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-premiere-pros-guide-to-avoiding-overlit-iphone-hdr-videos-for-2024/"><u>[Updated] Premiere Pro's Guide to Avoiding Overlit iPhone HDR Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-files-write-access-no-more-restrictions/"><u>Adjusting Windows Files: Write Access No More Restrictions</u></a></li>
<li><a href="https://some-approaches.techidaily.com/conversione-mkv-a-mp3-online-gratuita-come-usare-movavi-senza-costi/"><u>Conversione MKV a MP3 Online Gratuita: Come Usare Movavi Senza Costi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-windows-service-failure-error-1053/"><u>Correcting Windows Service Failure Error 1053</u></a></li>
<li><a href="https://tech-revival.techidaily.com/discover-the-ultimate-list-of-15-no-cost-subtitle-software-options/"><u>Discover the Ultimate List of 15 No-Cost Subtitle Software Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-onedrives-cant-add-your-folder-right-now-error-on-windows/"><u>How to Fix OneDrive's Can’t Add Your Folder Right Now Error on Windows</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-poco-f5-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Catch or Beat Sleeping Snorlax on Pokemon Go For Poco F5 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://article-posts.techidaily.com/in-2024-liftoff-to-high-end-imagery-on-a-budget/"><u>In 2024, Liftoff to High-End Imagery on a Budget</u></a></li>
<li><a href="https://common-error.techidaily.com/maintaining-data-security-overcoming-memory-corruption-in-ftdis-with-compatible-drivers/"><u>Maintaining Data Security: Overcoming Memory Corruption in FTDIS with Compatible Drivers</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/master-the-art-of-preserving-your-musical-journey-for-2024/"><u>Master the Art of Preserving Your Musical Journey for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefine-access-restoring-standard-user-privileges-in-win11/"><u>Redefine Access: Restoring Standard User Privileges in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-complications-caused-by-latest-windows-updates/"><u>Resolving Complications Caused by Latest Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-selection-of-4-webp-viewer-software/"><u>The Ultimate Selection of 4 WebP Viewer Software</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-guide-to-choosing-a-superior-screen-recording-tool-for-windows-users/"><u>Ultimate Guide to Choosing a Superior Screen Recording Tool for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-the-true-power-of-windows-screen-capture-toolkit/"><u>Unleash the True Power of Windows' Screen Capture Toolkit.</u></a></li>
</ul></div>

