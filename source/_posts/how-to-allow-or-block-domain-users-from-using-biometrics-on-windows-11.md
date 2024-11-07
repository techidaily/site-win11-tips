---
title: How to Allow or Block Domain Users From Using Biometrics on Windows 11
date: 2024-11-04T17:38:00.095Z
updated: 2024-11-07T05:25:16.667Z
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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134498/18498" target="_top" id="2134498">
  <img src="//a.impactradius-go.com/display-ad/18498-2134498" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134498/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137226/26400" target="_top" id="2137226">
  <img src="//a.impactradius-go.com/display-ad/26400-2137226" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137226/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918661/19272" target="_top" id="1918661">
  <img src="//a.impactradius-go.com/display-ad/19272-1918661" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918661/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014857/22899" target="_top" id="2014857">
  <img src="//a.impactradius-go.com/display-ad/22899-2014857" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014857/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-the-essence-of-vimeo-user-friendly-video-service/"><u>[New] In 2024, The Essence of Vimeo User-Friendly Video Service</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-channel-expansion-through-smart-youtube-link-building-methods/"><u>[Updated] In 2024, Channel Expansion Through Smart YouTube Link-Building Methods</u></a></li>
<li><a href="https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-honor-magic-5-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Solutions to Fix Error 505 in Google Play Store on Honor Magic 5 | Dr.fone</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210666541-9781786787415-a-spell-a-day/"><u>A Spell a Day | Free Book</u></a></li>
<li><a href="https://buynow-info.techidaily.com/from-novices-to-enthusiasts-a-guide-to-making-everyone-love-video-games/"><u>From Novices to Enthusiasts: A Guide to Making Everyone Love Video Games</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-tips-on-troubleshooting-frozen-obs-fullscreen-problem/"><u>In 2024, Tips on Troubleshooting Frozen OBS Fullscreen Problem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-auditory-setup-crafting-win11-written-hotkeys/"><u>Mastering Auditory Setup: Crafting Win11' Written Hotkeys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-console-user-management/"><u>Mastering Windows Console User Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-erase-illustration-in-win-search/"><u>Methods to Erase Illustration in Win Search</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/navigating-the-world-of-consoles-5-must-know-tips-before-buying-one/"><u>Navigating the World of Consoles: 5 Must-Know Tips Before Buying One</u></a></li>
<li><a href="https://extra-tips.techidaily.com/pioneering-teams-changing-vrs-course/"><u>Pioneering Teams Changing VR's Course</u></a></li>
<li><a href="https://extra-support.techidaily.com/s3700-sony-bd-play-new-insights-for-2024/"><u>S3700 Sony BD PLAY New Insights for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-commands-prep-terminal-for-prominence/"><u>Supercharge Commands: Prep Terminal for Prominence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-role-of-winservicesexe/"><u>Understanding the Role of Winservices.exe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-blue-screen-dumps-usage-and-benefits/"><u>Unraveling Windows Blue Screen Dumps: Usage & Benefits</u></a></li>
</ul></div>

