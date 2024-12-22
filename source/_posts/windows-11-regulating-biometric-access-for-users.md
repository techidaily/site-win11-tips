---
title: "Windows 11: Regulating Biometric Access for Users"
date: 2024-12-14T22:34:55.103Z
updated: 2024-12-22T00:23:35.708Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/5OmJZ4Z8jgk?si=YIoEaPI8geoiFSYE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/jjGL9wFdlbo?si=Vb1JgZqRXNc03UGG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Enable option in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-option.png)
6. Click **Apply** \> **OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fm0XhU5H8R4?si=cFPk6XK3X3CQSI7Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-save-instastories-infinite-the-liberation-app/"><u>[New] Save InstaStories Infinite The Liberation App</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-handy-tips-downloading-youtube-like-content-via-android/"><u>[Updated] In 2024, Handy Tips Downloading YouTube-Like Content via Android</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-your-first-step-to-successful-streaming/"><u>[Updated] Your First Step to Successful Streaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-getting-back-to-basics-in-windows/"><u>Essential Tips: Getting Back to Basics in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-overcoming-the-dxgierrordevicehunk-issue/"><u>Guide to Overcoming the DXGI_ERROR_DEVICE_HUNK Issue</u></a></li>
<li><a href="https://article-files.techidaily.com/in-2024-the-future-in-focus-premium-360-degree-professionals-cameras-2023/"><u>In 2024, The Future in Focus Premium 360-Degree Professionals' Cameras, 2023</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/may-17th-new-york-times-crossword-solutions-unveiling-clues-341/"><u>May 17Th New York Times Crossword Solutions - Unveiling Clues #341</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapid-typing-excellence-with-typingaid/"><u>Rapid Typing Excellence with TypingAid</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-textbook-script-troubles-a-quick-guide-for-windows/"><u>Tackling Textbook Script Troubles: A Quick Guide for Windows</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/the-art-of-enticing-instagram-followers-a-puzzle-post-primer/"><u>The Art of Enticing Instagram Followers A Puzzle Post Primer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-the-magic-turning-batch-files-into-winexe/"><u>Unleash the Magic: Turning Batch Files Into WinEXE</u></a></li>
</ul></div>

