---
title: "Windows 11: Regulating Biometric Access for Users"
date: 2024-12-08T17:11:36.162Z
updated: 2024-12-12T17:53:51.314Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11: Regulating Biometric Access for Users"
excerpt: "This Article Describes Windows 11: Regulating Biometric Access for Users"
keywords: Windows 11 Biometrics,Biometric Access Control,User Authentication Windows,Windows Security Update,Facial Recognition Windows,Fingerprint Login Windows,Multi-Factor Windows Secure
thumbnail: https://thmb.techidaily.com/62d72eb39093270995757df1adc43019ed0e362b73decee245e264928d768a5a.jpg
---

## Windows 11: Regulating Biometric Access for Users

 Biometric authentication allows you to quickly log in to the system using fingerprint, facial, or iris recognition. However, what if you want to prevent a domain user from logging in using biometrics?

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oySc0DiqmKc?si=8pynRzuhlq2RUPZ6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlYIdWQc-jw?si=ZQ5809CbQGEar0vg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Allow or Block a Biometrics Log-On Using the Registry Editor

 Another way to configure biometrics log-on for the domain users is through the Registry Editor. Here's how:

 Editing the registry is risky, as one wrong edit can make your system unstable. Therefore, make sure to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps.

1. Open the Run tool, type **regedit** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Biometrics\Credential Provider`
3. Right-click the **Credential Provider** key in the left sidebar, hover the cursor to **New,** and choose **DWORD (32-bit) Value**.  
![DWORD (32-bit) Value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/dword-32-bit-value.jpg)
4. Name the value **Domain Accounts.**  
![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uzb-0C0xUYA?si=F4MPhdVqyVgx7_8X" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Control Biometrics Logins on Your Computer

 Securing sensitive information has now become more important than ever. If you want to allow or block a domain user from logging on using biometrics, you can do that using the above methods.

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-blog.techidaily.com/n-2024-the-infographic-index-youtubes-surprising-stat-treasury-2017/"><u>[New] In 2024, The Infographic Index YouTube's Surprising Stat Treasury (2017)</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-ranking-the-very-best-10-free-online-artists-on-youtube/"><u>[Updated] In 2024, Ranking the Very Best 10 Free Online Artists on YouTube</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-top-9-platforms-for-unparalleled-gamers-joy/"><u>[Updated] Top 9 Platforms for Unparalleled Gamers' Joy</u></a></li>
<li><a href="https://extra-hints.techidaily.com/augmenting-learning-with-vr-for-2024/"><u>Augmenting Learning with VR for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-down-background-computation-load/"><u>Cutting Down Background Computation Load</u></a></li>
<li><a href="https://win-dash.techidaily.com/guaranteed-compatibility-simple-way-to-get-wacom-intuos-pro-driver-for-windows-11-installed/"><u>Guaranteed Compatibility: Simple Way to Get Wacom Intuos Pro Driver for Windows 11 Installed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-regain-original-typing-positions-on-windows-11-devices/"><u>Guide to Regain Original Typing Positions on Windows 11 Devices</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/how-to-retrieve-your-files-a-step-by-step-guide-on-restoring-a-mistakenly-formatted-disk/"><u>How to Retrieve Your Files: A Step-by-Step Guide on Restoring a Mistakenly Formatted Disk</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-samsung-galaxy-s23plus-phone-with-broken-screen-by-drfone-android/"><u>In 2024, How to Unlock Samsung Galaxy S23+ Phone with Broken Screen</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/lost-your-iphone-unlock-code-easy-ways-to-reset-and-secure-your-phone-again/"><u>Lost Your iPhone Unlock Code? Easy Ways to Reset and Secure Your Phone Again</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-pc-troubleshooting-uncovering-and-resolving-error-codes-via-command-prompt/"><u>Mastering PC Troubleshooting: Uncovering & Resolving Error Codes via Command Prompt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-gaming-potential-tackling-fps-challenges-in-valorant/"><u>Maximize Gaming Potential: Tackling FPS Challenges in Valorant</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-sleep-how-to-schedule-idle-time-out-on-windows-11/"><u>Secure Sleep: How to Schedule Idle Time-Out on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-resolve-0xc0000005-problem-in-windows/"><u>Strategies to Resolve 0Xc0000005 Problem in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-overcoming-windows-11-error/"><u>Understanding and Overcoming Windows 11 Error</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    