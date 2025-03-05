---
title: "Optimizing User Authentication: Windows 11, Domains"
date: 2025-03-03T16:32:55.163Z
updated: 2025-03-05T01:34:46.202Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Optimizing User Authentication: Windows 11, Domains"
excerpt: "This Article Describes Optimizing User Authentication: Windows 11, Domains"
keywords: Win11 Auth Optimize,Domain Authentication,Secure Login Windows,Access Control Windows 11,Identity Verification PC,User Credentials Management,Security Windows Protocols
thumbnail: https://thmb.techidaily.com/85be9153d8c81024583588a94ed9e00fc880777ac2a8c7cff5efd5d21044d91c.jpg
---

## Optimizing User Authentication: Windows 11, Domains

 Biometric authentication allows you to quickly log in to the system using fingerprint, facial, or iris recognition. However, what if you want to prevent a domain user from logging in using biometrics?

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

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
![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  
![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

## Control Biometrics Logins on Your Computer

 Securing sensitive information has now become more important than ever. If you want to allow or block a domain user from logging on using biometrics, you can do that using the above methods.

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-chrome-crashes-or-wont-open-on-nokia-c22-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Chrome Crashes or Wont Open on Nokia C22 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-scheduling-combining-to-do-and-ifttt-services/"><u>Efficient Scheduling: Combining To-Do and IFTTT Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-windows-11-tpm-removal-techniques-explored/"><u>Effortless Windows 11 TPM Removal Techniques Explored</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-and-upgrade-to-the-current-intel-hd-graphics-driver-version-for-optimal-performance/"><u>Get & Upgrade to the Current Intel HD Graphics Driver Version for Optimal Performance</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/harnessing-ai-for-superior-content-synthesis/"><u>Harnessing AI for Superior Content Synthesis</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-the-spys-guide-to-unearthing-hidden-youtube-videos/"><u>In 2024, The Spy's Guide to Unearthing Hidden YouTube Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-tips-for-setting-windows-time-locally/"><u>Instant Tips for Setting Windows Time Locally</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-your-windows-11-temporary-files-reliable-and-valid/"><u>Keeping Your Windows 11 Temporary Files Reliable & Valid</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723201208684-laptop-microphone-woes-find-out-how-to-get-it-working-again/"><u>Laptop Microphone Woes? Find Out How to Get It Working Again!</u></a></li>
<li><a href="https://android-unlock.techidaily.com/pattern-locks-are-unsafe-secure-your-vivo-s17-pro-phone-now-with-these-tips-by-drfone-android/"><u>Pattern Locks Are Unsafe Secure Your Vivo S17 Pro Phone Now with These Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-functional-lock-screen-wait-period-in-windows/"><u>Reinstating Functional Lock Screen Wait Period in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-vanishing-steam-icon-graphics/"><u>Reviving Vanishing Steam Icon Graphics</u></a></li>
<li><a href="https://win-cloud.techidaily.com/simplified-steps-zum-verschieben-von-windows-11-auf-eine-kleinere-ssd/"><u>Simplified Steps Zum Verschieben Von Windows 11 Auf Eine Kleinere SSD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-windows-11-way-mastery-of-software-uninstallation/"><u>The Windows 11 Way: Mastery of Software Uninstallation</u></a></li>
<li><a href="https://fox-info.techidaily.com/tiny-feature-plot-outline/"><u>Tiny Feature Plot Outline</u></a></li>
</ul></div>

