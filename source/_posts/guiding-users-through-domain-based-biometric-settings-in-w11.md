---
title: Guiding Users Through Domain-Based Biometric Settings in W11
date: 2024-12-09T01:21:36.490Z
updated: 2024-12-13T01:59:44.509Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZblaBc-v2vs?si=CKW1gJwXQT2vZJYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/E1ax-vnGdeo?si=bgTkOhOEwDTlRQE3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Enable option in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-option.png)
6. Click **Apply** \> **OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DEqoiNArwjQ?si=oaL_lgnI-RxY5Qy_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5FWCFI3f_cs?si=Kt2Onr_E4c616tbH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

## Control Biometrics Logins on Your Computer

 Securing sensitive information has now become more important than ever. If you want to allow or block a domain user from logging on using biometrics, you can do that using the above methods.

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-skills.techidaily.com/new-review-and-insight-into-movavi-editor-plus-now-available/"><u>[New] Review & Insight Into Movavi Editor Plus, Now Available</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-effortless-strategies-to-detect-duplicate-and-phony-likes/"><u>[Updated] In 2024, Effortless Strategies to Detect Duplicate and Phony Likes</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-your-android-and-iphone-companion-to-igtv-downloads/"><u>[Updated] In 2024, Your Android & iPhone Companion to IGTV Downloads</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ai-date-coach-chatgpt-for-romance/"><u>AI Date Coach: ChatGPT for Romance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/all-about-bmp-image-files-exploring-opening-techniques-and-uses/"><u>All About BMP Image Files – Exploring Opening Techniques & Uses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-video-smoothing-applications-of-202-the-year-with-pay-free-choices-available/"><u>Best Video Smoothing Applications of 202 the Year, With Pay-Free Choices Available</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/bright-spotlight-spk10-037s-adaptable-softbox-advantages/"><u>Bright Spotlight: SPK10-037's Adaptable Softbox Advantages</u></a></li>
<li><a href="https://driver-error.techidaily.com/clearing-full-disk-capacity-in-windows-task-manager/"><u>Clearing Full Disk Capacity in Windows Task Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/descargar-convertidor-de-archivos-online-gratuito-mp4-a-ogg-por-movavi/"><u>Descargar Convertidor De Archivos Online Gratuito: MP4 a OGG Por Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/descargas-gratuitas-de-conversion-transformar-archivos-aif-a-formato-wmv-con-movavi/"><u>Descargas Gratuitas De Conversión: Transformar Archivos AIF a Formato WMV Con Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-offline-vob-to-m4a-transformation-try-the-no-cost-movavi-solution/"><u>Easy Offline VOB to M4A Transformation - Try the No Cost Movavi Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-conversion-of-m4b-audio-book-files-using-movavis-easy-tool/"><u>Free Online Conversion of M4B Audio Book Files - Using Movavi's Easy Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/i-migliori-strumenti-per-la-fusione-musicale-del-2024-scelta-definitiva-secondo-movavi/"><u>I Migliori Strumenti per La Fusione Musicale Del 2024: Scelta Definitiva Secondo Movavi</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-xiaomi-14-phone-without-password-by-drfone-android/"><u>In 2024, How To Unlock Xiaomi 14 Phone Without Password?</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-instagram-music-copyright-rules/"><u>In 2024, Instagram Music Copyright Rules</u></a></li>
<li><a href="https://win11-tips.techidaily.com/m4a-aac-movavi/"><u>M4A를 AAC로 자유성 변환하는 웹 기회 - Movavi에서 시작!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726220879793-2024/"><u>𝗠𝗮'𝘃'𝗶𝘁𝗵-2024: 𝗕𝗲𝗼𝗿𝗸𝗮𝗹𝗹𝗹 𝗧𝗵𝗮'𝘁 𝗶𝘀𝗰𝗲𝗻𝘂𝘇𝗶𝗱𝗮𝘁 🚹🚺 | 𝗡𝗼𝘃𝗼𝘀𝘄𝗶𰨒: 𝗦𝗸𝗶𝘀 𝗮𝗹𝗱'𝘁𝘂𝗿𝗻𝗲𝗻𝘀</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/the-prime-strategies-in-zoom-video-to-zoom-outcomes/"><u>The Prime Strategies in Zoom Video to Zoom Outcomes</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-take-your-videos-to-the-next-level-advanced-effects-tutorial/"><u>Updated In 2024, Take Your Videos to the Next Level Advanced Effects Tutorial</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    