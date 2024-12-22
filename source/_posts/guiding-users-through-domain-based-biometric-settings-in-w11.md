---
title: Guiding Users Through Domain-Based Biometric Settings in W11
date: 2024-12-17T16:54:42.149Z
updated: 2024-12-22T06:23:25.848Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guiding Users Through Domain-Based Biometric Settings in W11
excerpt: This Article Describes Guiding Users Through Domain-Based Biometric Settings in W11
keywords: BioID Domain Config,Biometric Domain Guide,W11 User Settings,Secure Access Biometrics,Digital Identity Setup,Adaptive Authentication Tech,Precision Biometrics System
thumbnail: https://thmb.techidaily.com/c6291d176ca52af593ed97a64202c588c0b54ac6b9ff66af20d69e9744d56a33.jpeg
---

## Guiding Users Through Domain-Based Biometric Settings in W11

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Enable option in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-option.png)
6. Click **Apply** \> **OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/7JBG_O3Vnh4?si=lUO0fta6YPJ50qjg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=LvxQhsEJoymsM2iZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fm0XhU5H8R4?si=cFPk6XK3X3CQSI7Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-lab.techidaily.com/n-2024-sportscasting-your-pathway-to-highlight-videos/"><u>[New] In 2024, Sportscasting Your Pathway to Highlight Videos</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-in-2024-ultimate-guide-to-zooming-in-on-effective-win11-meetings/"><u>[New] In 2024, Ultimate Guide to Zooming In on Effective Win11 Meetings</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-enhancing-mac-use-top-5-recommended-sniping-apps/"><u>[Updated] 2024 Approved Enhancing Mac Use Top 5 Recommended Sniping Apps</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-youtube-video-animation-tools-and-techniques-for-efficient-gif-making/"><u>[Updated] 2024 Approved YouTube Video Animation Tools and Techniques for Efficient Gif Making</u></a></li>
<li><a href="https://win11-tips.techidaily.com/counteracting-busy-resource-status-on-windows-11-systems/"><u>Counteracting Busy Resource Status on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decibels-dominance-the-ultimate-list-of-programs-for-above-100-output/"><u>Decibels Dominance: The Ultimate List of Programs for Above-100% Output</u></a></li>
<li><a href="https://tech-hub.techidaily.com/facebook-login-theft-uncovering-the-deceptive-chrome-fake-chatgpt-extension/"><u>Facebook Login Theft: Uncovering the Deceptive 'Chrome Fake ChatGPT' Extension</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-change-your-honor-magic-5-lite-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How to Change Your Honor Magic 5 Lite Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/introductory-walkthrough-how-to-employ-mobizen-screensaver-tools-for-2024/"><u>Introductory Walkthrough How to Employ Mobizen Screensaver Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-fn-key-modifications-in-win-1011/"><u>Mastering FN Key Modifications in Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/moving-beyond-flashy-features-to-essentials/"><u>Moving Beyond Flashy Features to Essentials</u></a></li>
<li><a href="https://extra-support.techidaily.com/revealing-hidden-aspects-in-minecraft-for-2024/"><u>Revealing Hidden Aspects in Minecraft for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-path-to-a-more-dynamic-menu-adding-directories-in-windows-11/"><u>The Path to a More Dynamic Menu: Adding Directories in Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-oppo-reno-8t-drfone-by-drfone-virtual-android/"><u>The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Oppo Reno 8T | Dr.fone</u></a></li>
</ul></div>

