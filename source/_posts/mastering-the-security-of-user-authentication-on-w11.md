---
title: Mastering the Security of User Authentication on W11
date: 2024-11-05T13:13:35.786Z
updated: 2024-11-07T07:47:02.367Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Security of User Authentication on W11
excerpt: This Article Describes Mastering the Security of User Authentication on W11
keywords: AuthSecureW11,SafeAuthW11,W11LoginSecurity,SecureUserAuthW11,IdentityProtectW11,W11AuthGuard,UserAuthDefenseW11
thumbnail: https://thmb.techidaily.com/bdbc1bb211547c18c849de30d5eb74ca5d67d9e0fc552f041d0a6f6f88d073bb.jpg
---

## Mastering the Security of User Authentication on W11

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
<a href="https://imp.i357552.net/c/5597632/1006793/11832" target="_top" id="1006793">
  <img src="//a.impactradius-go.com/display-ad/11832-1006793" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1006793/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  

<!-- affiliate ads begin -->
<span id="1983552">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983552.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983552">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983552.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983552%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983552/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130875/7443" target="_top" id="2130875">
  <img src="//a.impactradius-go.com/display-ad/7443-2130875" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130875/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123726/7443" target="_top" id="2123726">
  <img src="//a.impactradius-go.com/display-ad/7443-2123726" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123726/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-blog.techidaily.com/n-2024-break-bot-patterns-enhance-organic-video-reach/"><u>[New] In 2024, Break Bot Patterns, Enhance Organic Video Reach</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-a-diy-approach-downloading-and-personalizing-your-whatsapp-ringtone/"><u>[Updated] A DIY Approach Downloading & Personalizing Your WhatsApp Ringtone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-hidden-harmony-harvesters-ios-and-android-secret-audio-apps/"><u>2024 Approved Hidden Harmony Harvesters IOS & Android Secret Audio Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-exe-execution-challenges-on-win-10/"><u>Conquering EXE Execution Challenges on Win 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-devhome-your-stepping-stone-into-windows-11/"><u>Demystifying DevHome: Your Stepping Stone Into Windows 11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-detect-and-stop-mspy-from-spying-on-your-vivo-y56-5g-drfone-by-drfone-virtual-android/"><u>How to Detect and Stop mSpy from Spying on Your Vivo Y56 5G | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-xiaomi-redmi-12-phone-by-drfone-android/"><u>In 2024, How to Use Google Assistant on Your Lock Screen Of Xiaomi Redmi 12 Phone</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-perfecting-zoom-techniques-for-tiktok-engagement/"><u>In 2024, Perfecting Zoom Techniques for TikTok Engagement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstart-dead-sound-system-on-windows-pcs/"><u>Jumpstart Dead Sound System on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-restrictions-non-standard-software-in-modern-oses/"><u>Overcoming Restrictions: Non-Standard Software in Modern OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-inbox-access-gmail-on-the-windows-taskbar/"><u>Simplifying Inbox Access: Gmail on the Windows Taskbar</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/unboxing-lg-gram-17-review-surprising-strength-in-an-ultra-light-package/"><u>Unboxing LG Gram 17 Review: Surprising Strength in an Ultra-Light Package</u></a></li>
</ul></div>

