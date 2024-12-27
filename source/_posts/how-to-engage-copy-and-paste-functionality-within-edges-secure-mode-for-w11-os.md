---
title: How To Engage Copy & Paste Functionality Within Edge's Secure Mode for W11 OS
date: 2024-12-20T18:56:40.199Z
updated: 2024-12-27T17:22:50.651Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How To Engage Copy & Paste Functionality Within Edge's Secure Mode for W11 OS
excerpt: This Article Describes How To Engage Copy & Paste Functionality Within Edge's Secure Mode for W11 OS
keywords: Edge Copy Security,Copy Paste in Secure Mode,W11 OS Secure Copy,Edge Secure Engagement,Pasting in W11,Secure Copy Feature,Edge Paste Security Mode
thumbnail: https://thmb.techidaily.com/6c7b51dcfdae2a8da726c75853a324eb9a3939b33880d7b4a364119150ff2caf.jpg
---

## How To Engage Copy & Paste Functionality Within Edge's Secure Mode for W11 OS

 Looking to improve the security of your device? Microsoft Edge's Application Guard feature is an ideal solution, as it creates a virtualized atmosphere and blocks malicious websites. However, copy and paste functionality is disabled by default in this setting for extra precautionary measures.

 If you would like to switch on copy and paste within Application Guard for Edge on Windows 11, then this guide will assist you in doing so.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mMYEK2gtY5c?si=ytxNz_JHZkTrwb4b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/fm0XhU5H8R4?si=cFPk6XK3X3CQSI7Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Enable Copy and Paste via Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-via-windows-settings.jpg)
7. The UAC prompt will appear on the screen. Click**Yes** to continue.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
6. Finally, click**OK** to save your changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_1g4U13PBk0?si=xJLJtlc4hKBTBH8M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zAzTErKy6h8?si=vi5z3M9_7fW6qiAJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-ideal-ps2-emulation-software-for-ios-users/"><u>[Updated] In 2024, Ideal PS2 Emulation Software for IOS Users</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-sketch-humorous-images-with-adobe/"><u>2024 Approved Sketch Humorous Images with Adobe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/complete-deletion-of-wsl-in-windows-11-environment/"><u>Complete Deletion of WSL in Windows 11 Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-to-reactivate-stalled-wsreset-on-pcs/"><u>Essential Steps to Reactivate Stalled WSReset on PCs</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-the-gaping-security-risk-in-apples-updated-anti-theft-technology-and-how-to-patch-it-up-cyberguardian-news/"><u>Exploring the Gaping Security Risk in Apple's Updated Anti-Theft Technology & How to Patch It Up | CyberGuardian News</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tune-your-devices-touch-sensitivity-in-windows-11/"><u>How to Tune Your Device's Touch Sensitivity in Windows 11</u></a></li>
<li><a href="https://win-extraordinary.techidaily.com/introducing-the-latest-addition-to-fxmagnetic-the-revolutionary-rsi-trader-for-mt4-pros/"><u>Introducing the Latest Addition to FXmagnetic: The Revolutionary RSI Trader for MT4 Pros</u></a></li>
<li><a href="https://win-manuals.techidaily.com/losungen-zur-einstellung-automatischer-loschvorgange-und-wiederherstellung-wichtiger-dll-dateien/"><u>Lösungen Zur Einstellung Automatischer Löschvorgänge Und Wiederherstellung Wichtiger DLL-Dateien</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-system-performance-with-fewer-processes/"><u>Optimizing System Performance with Fewer Processes</u></a></li>
<li><a href="https://common-error.techidaily.com/speed-up-your-pc-by-reviving-corrupted-hardware-drivers-easily/"><u>Speed Up Your PC by Reviving Corrupted Hardware Drivers Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-blueprint-to-utilizing-devs-space-in-win11/"><u>The Essential Blueprint to Utilizing Devs Space in Win11</u></a></li>
</ul></div>

