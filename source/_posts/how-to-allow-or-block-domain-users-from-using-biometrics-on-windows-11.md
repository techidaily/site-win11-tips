---
title: How to Allow or Block Domain Users From Using Biometrics on Windows 11
date: 2024-10-27T16:37:49.480Z
updated: 2024-11-01T20:02:08.061Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Allow or Block Domain Users From Using Biometrics on Windows 11
excerpt: This Article Describes How to Allow or Block Domain Users From Using Biometrics on Windows 11
keywords: Windows 11 Biometric Controls,Enable/Block Domains,Biometrics Windows Settings,Domain User Security Windows,Windows 11 Privacy Options,Regulate Biometric Access,Biometric Windows Management
thumbnail: https://thmb.techidaily.com/71005eecdd2fec9bde2d87e54e71962fc2dc07f266aaf5068a5f2270c6aff62a.jpeg
---

## How to Allow or Block Domain Users From Using Biometrics on Windows 11

 Biometric authentication allows you to quickly log in to the system using fingerprint, facial, or iris recognition. However, what if you want to prevent a domain user from logging in using biometrics?

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Allow or Block a Biometrics Log-On via the Local Group Policy Editor

 The quickest way to configure your computer to allow or block a biometrics scan for domain users is through the Local Group Policy Editor. Here are the steps you need to follow:

1. Press the **Win + R** key to open the **Run tool.**
2. Type **gpedit.msc** in the search bar and click OK.
3. In the Local Group Policy Editor, head towards the following location:  
`Computer Configuration > Administrative Templates > Windows Components > Biometrics`
4. Double-click on the **Allow domain users to log on using biometrics** policy in the right pane.  
![Allow domain users to log on using biometrics policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/allow-domain-users-to-log-on-using-biometrics-policy.jpg)
5. Choose the **Enabled** option to allow biometrics log on for the domain users. And choose the **Disabled** option to block biometrics log on for the domain users.  
![Enable option in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-option.png)
6. Click **Apply** \> **OK** to save the changes.

## How to Allow or Block a Biometrics Log-On Using the Registry Editor

 Another way to configure biometrics log-on for the domain users is through the Registry Editor. Here's how:

 Editing the registry is risky, as one wrong edit can make your system unstable. Therefore, make sure to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps.

1. Open the Run tool, type **regedit** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Biometrics\Credential Provider`
3. Right-click the **Credential Provider** key in the left sidebar, hover the cursor to **New,** and choose **DWORD (32-bit) Value**.  
![DWORD (32-bit) Value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/dword-32-bit-value.jpg)
4. Name the value **Domain Accounts.**  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151894/7443" target="_top" id="2151894">
  <img src="//a.impactradius-go.com/display-ad/7443-2151894" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151894/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144299/7443" target="_top" id="2144299">
  <img src="//a.impactradius-go.com/display-ad/7443-2144299" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144299/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137208/26400" target="_top" id="2137208">
  <img src="//a.impactradius-go.com/display-ad/26400-2137208" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137208/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425">
  <img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Control Biometrics Logins on Your Computer

 Securing sensitive information has now become more important than ever. If you want to allow or block a domain user from logging on using biometrics, you can do that using the above methods.

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-lab.techidaily.com/-peek-into-the-heart-of-youtubes-video-operations-for-2024/"><u>[New] A Peek Into the Heart of YouTube's Video Operations for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-hidden-melodic-markers-ios-and-android-recording-app-overview/"><u>[Updated] 2024 Approved Hidden Melodic Markers IOS & Android Recording App Overview</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-unlocking-mp3-from-pinterest-video-files-with-these-steps/"><u>[Updated] In 2024, Unlocking MP3 From Pinterest Video Files with These Steps</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-chromium-os-built-in-video-capturer/"><u>2024 Approved Chromium OS Built-In Video Capturer</u></a></li>
<li><a href="https://technical-tips.techidaily.com/code-39-trouble-heres-how-to-correctly-fix-it-in-windows/"><u>Code 39 Trouble? Here's How to Correctly Fix It in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/control-desktop-icon-and-thumbnail-pics-w11/"><u>Control Desktop Icon and Thumbnail Pics W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-mic-during-video-captures-using-powerpoint/"><u>Enabling Mic During Video Captures Using PowerPoint</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-latest-asus-bt50n-bluetooth-driver-for-windows-11108-download-now/"><u>Get the Latest Asus BT50n Bluetooth Driver for Windows 11/10/8 - Download Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-your-activation-key-not-working-in-windows-11-how-to-fix-it/"><u>Is Your Activation Key Not Working in Windows 11? How to Fix It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-tabs-a-step-by-step-to-windows-11-mastery/"><u>Navigating Tabs: A Step-by-Step to Windows 11 Mastery</u></a></li>
<li><a href="https://hardware-help.techidaily.com/navigating-the-market-with-toms-hardware-advice/"><u>Navigating the Market with Tom's Hardware Advice</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quicker-text-entry-typingaids-methodology/"><u>Quicker Text Entry: TypingAid's Methodology</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-windows-os-office-malfunction-error/"><u>Steps to Resolve Windows OS Office Malfunction Error</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    