---
title: Optimizing Biometric Use for Domains on Windows 11
date: 2024-10-13T04:24:42.707Z
updated: 2024-10-15T09:44:29.988Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Optimizing Biometric Use for Domains on Windows 11
excerpt: This Article Describes Optimizing Biometric Use for Domains on Windows 11
keywords: Bio-Use Optimization,WINDOWS Biometrics,Domain Security Win11,Windows 11 Facial Recognition,Win11 Fingerprint Tech,Enhanced Win11 Access,Secure Domains Win11
thumbnail: https://thmb.techidaily.com/9eb4aae367e8d7c80e3c075f7bffa3926b7f3e2ef755ab623092abbe72eca2c0.jpg
---

## Optimizing Biometric Use for Domains on Windows 11

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
<a href="https://bluettius.sjv.io/c/5597632/2148619/17108" target="_top" id="2148619">
  <img src="//a.impactradius-go.com/display-ad/17108-2148619" border="0" alt="https://techidaily.com" width="100" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2148619/17108" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925549/19272" target="_top" id="1925549">
  <img src="//a.impactradius-go.com/display-ad/19272-1925549" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925549/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135374/19272" target="_top" id="2135374">
  <img src="//a.impactradius-go.com/display-ad/19272-2135374" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135374/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896541/19272" target="_top" id="1896541">
  <img src="//a.impactradius-go.com/display-ad/19272-1896541" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896541/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Control Biometrics Logins on Your Computer

 Securing sensitive information has now become more important than ever. If you want to allow or block a domain user from logging on using biometrics, you can do that using the above methods.

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-top-rated-components-for-smooth-live-transmissions/"><u>[New] In 2024, Top-Rated Components for Smooth Live Transmissions</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-quality-monitors-showdown-best-4k-edition-ranked-1-10/"><u>2024 Approved Quality Monitors Showdown Best 4K Edition, Ranked #1-10</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/android-essentials-for-immersive-video-and-vr-content-for-2024/"><u>Android Essentials for Immersive Video and VR Content for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-ms-teams-error-80080300-fixes-for-w11-users/"><u>Breaking Down MS Teams Error 80080300: Fixes for W11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-broken-enter-button-on-pc/"><u>Fixing Broken Enter Button on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gaming-smoother-with-warhammer-40k-on-windows-no-more-stutters/"><u>Gaming Smoother with Warhammer 40K on Windows, No More Stutters</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-phone-touchscreen-of-tecno-camon-20-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Phone Touchscreen Of Tecno Camon 20 | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-oppo-reno-10-pro-5g-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>How to Unlock Oppo Reno 10 Pro 5G Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-gps-location-on-infinix-note-30-pro-easily-and-safely-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change GPS Location on Infinix Note 30 Pro Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-merge-skype-and-zoom-easy-techniques-for-effective-communication/"><u>In 2024, Merge Skype and Zoom Easy Techniques for Effective Communication</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/insta-cover-chronicles-top-tier-tech-edition-for-2024/"><u>Insta Cover Chronicles Top-Tier Tech Edition for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-science-of-storage-sizing-in-windows-through-powershell/"><u>Mastering the Science of Storage Sizing in Windows Through Powershell</u></a></li>
<li><a href="https://solve-outstanding.techidaily.com/new-features-and-improvements-in-the-latest-version-of-winx-hd-video-converter-for-mac/"><u>New Features and Improvements in the Latest Version of WinX HD Video Converter for Mac</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    