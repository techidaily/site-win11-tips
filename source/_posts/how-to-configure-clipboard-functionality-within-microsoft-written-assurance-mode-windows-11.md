---
title: How to Configure Clipboard Functionality Within Microsoft' Written Assurance Mode, Windows 11
date: 2024-11-21T18:06:53.542Z
updated: 2024-11-27T16:15:19.521Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Configure Clipboard Functionality Within Microsoft' Written Assurance Mode, Windows 11
excerpt: This Article Describes How to Configure Clipboard Functionality Within Microsoft' Written Assurance Mode, Windows 11
keywords: Configuring Clipboard Win11,Microsoft Write Modes Clipboard,Clipboard Settings Windows 11,Enhancing Clipboard Functionality,MS Windows Clipboard Adjustment,W11 Clipboard Configure Steps,Assurance Mode Copy/Paste Window
thumbnail: https://thmb.techidaily.com/bfe8f97d519484170998bced830c25ea7c96c9f9fefb2b304db02c765d66484d.jpg
---

## How to Configure Clipboard Functionality Within Microsoft' Written Assurance Mode, Windows 11

 Looking to improve the security of your device? Microsoft Edge's Application Guard feature is an ideal solution, as it creates a virtualized atmosphere and blocks malicious websites. However, copy and paste functionality is disabled by default in this setting for extra precautionary measures.

 If you would like to switch on copy and paste within Application Guard for Edge on Windows 11, then this guide will assist you in doing so.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Enable Copy and Paste via Windows Settings

 To enable copy and paste in Application Guard for Edge, follow the steps below:

1. Right-click on Start and select**Settings** from the menu list. For more information, check out our guide on[how to open the Settings window](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Privacy & security** from the left pane.
3. Then click the**Windows Security** option on the right-hand side.
4. On the following screen, select**App & browser control** .
5. Go to the Isolated browsing section and click the link "Change Applications Guard settings."  
![Change Application Guard Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-application-guard-settings.jpg)
6. Search for the**Copy and paste** option, then click the toggle to enable it.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LT4sdZgUvRQ?si=SvQD5FouEzu4UHpJ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Enable Copy and Paste via Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-via-windows-settings.jpg)
7. The UAC prompt will appear on the screen. Click**Yes** to continue.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qv4Qm7kpeMs?si=9fv5SOS5a2DvixTK&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’ve completed the steps, restart your computer for the changes to work. Now, you can securely transfer data between a virtualized environment and your device without any worries about security risks - malicious websites and applications will be blocked even with this setting enabled.

 If you ever need to disable copy and paste in Application Guard for Edge, you can follow the same steps mentioned above. Just be sure to toggle off the Copy and Paste setting from the Isolated browsing menu instead.

## 2\. How to Enable Copy and Paste Using Registry Editor

 The Windows Registry is another method you can use to copy and paste within Application Guard for Edge on your Windows 11 PC. But, please be aware that editing the registry can have severe consequences if done incorrectly. To be safe,[back up the registry data](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you begin making any changes.

 Follow these steps to enable copy and paste using the Windows Registry Editor:

1. Press**Win + R** on your keyboard to open the Run dialog box.
2. Type "regedit" in the text box and press the Enter key.
3. If UAC prompts appear on the screen, click**Yes** to confirm your action.
4. In the Registry Editor window, navigate to the following location:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Hvsi`
5. If you don't find the Hvsi key there, you will need to create it. To do this, right-click on Microsoft and select**New > Key** .

1. In the box that appears, give it the name**Hvsi** , and then hit Enter to save the file.
2. Now right-click on**Hvsi** and select**New > DWORD (32-bit) Value** .  
![Creating a new DWORD (32-bit) Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-dword-enableclipboard-key.jpg)
3. Put**EnableClipboard** as the name for the new DWORD key, then press Enter.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
6. Finally, click**OK** to save your changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3hS27nZVi9Y?si=_Zqj_l4a4XkPqT2S&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

## Copy and Paste Now Works With Edge Application Guard

 With Application Guard for Edge, your device can remain secure while browsing the web. Unfortunately, certain functionalities such as copy and paste are disabled by default - but don't worry! This guide will explain two methods to activate them quickly and easily.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-ultimate-psd-style-boosting/"><u>[New] 2024 Approved Ultimate PSD Style Boosting</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-essential-youtube-equipment-for-starting-your-channel-what-do-you-really-need/"><u>[New] In 2024, Essential YouTube Equipment For Starting Your Channel - What Do You Really Need?</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-your-journey-through-telegrams-web-functionality/"><u>[New] In 2024, Your Journey Through Telegram's Web Functionality</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-free-youtube-revenue-predictor-tools/"><u>[Updated] 2024 Approved Free YouTube Revenue Predictor Tools</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-the-value-of-a-million-viewing-spree-on-youtube/"><u>[Updated] In 2024, The Value of a Million-Viewing Spree on YouTube</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-magix-acid-pro-review-a-look-at-similar-programs/"><u>[Updated] Magix ACID Pro Review A Look at Similar Programs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detailed-guide-to-resolving-outlooks-error-0x80040610-on-windows/"><u>Detailed Guide to Resolving Outlook's Error 0X80040610 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-apk-setup-for-win-11-power-users/"><u>Effortless APK Setup for Win 11 Power Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-win-11-gaming-with-these-top-7-essentials/"><u>Elevate Win 11 Gaming with These Top 7 Essentials</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-communication-mastery-for-impactful-interviews/"><u>In 2024, Communication Mastery For Impactful Interviews</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-console-capturer-pro-report/"><u>In 2024, Console Capturer Pro Report</u></a></li>
<li><a href="https://win11-tips.techidaily.com/malwarebytes-restoring-link-between-services-on-windows-11-pcs/"><u>Malwarebytes: Restoring Link Between Services on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-control-fixing-freezing-netflix-app-windows/"><u>Regaining Control: Fixing Freezing Netflix App Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalize-your-pcs-keys-with-these-fixes/"><u>Revitalize Your PC's Keys with These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/three-techniques-to-delete-windows-11-store/"><u>Three Techniques to Delete Windows 11 Store</u></a></li>
<li><a href="https://techtrends.techidaily.com/transforme-vos-fichiers-aiff-au-format-mp3-avec-le-convertisseur-de-movavi/"><u>Transforme Vos Fichiers AIFF Au Format MP3 Avec Le Convertisseur De Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trio-of-tiles-windows-11-widgets-configuration-for-peak-performance/"><u>Trio of Tiles: Windows 11 Widgets Configuration for Peak Performance</u></a></li>
</ul></div>

