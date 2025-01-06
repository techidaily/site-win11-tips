---
title: How To Engage Copy & Paste Functionality Within Edge's Secure Mode for W11 OS
date: 2025-01-03T08:52:15.329Z
updated: 2025-01-05T21:53:29.342Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/jf0JvOqiAXc?si=kHEHQGC_PhBv4xij" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Enable Copy and Paste via Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-via-windows-settings.jpg)
7. The UAC prompt will appear on the screen. Click**Yes** to continue.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’ve completed the steps, restart your computer for the changes to work. Now, you can securely transfer data between a virtualized environment and your device without any worries about security risks - malicious websites and applications will be blocked even with this setting enabled.

 If you ever need to disable copy and paste in Application Guard for Edge, you can follow the same steps mentioned above. Just be sure to toggle off the Copy and Paste setting from the Isolated browsing menu instead.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GFHH14XlFCk?si=2HcjQbDx5eG0ZQAt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
6. Finally, click**OK** to save your changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/it8VkxDUdAc?si=ef6VZWR7kW4P9ikh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://video-capture.techidaily.com/new-2024-approved-top-fbx-capture-tools-beyond-traditional-recorders/"><u>[New] 2024 Approved Top FBX Capture Tools Beyond Traditional Recorders</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-decoding-ios-digital-screen-snatcher-secrets/"><u>[New] Decoding IO's Digital Screen Snatcher Secrets</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-experts-choice-gimbals-top-ranked-for-4k-cameras/"><u>[New] Expert's Choice Gimbals Top-Ranked For 4K Cameras</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-xiaomi-civi-3-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on Xiaomi Civi 3 Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disarming-windows-11-security-error-messages-quickly/"><u>Disarming Windows 11 Security Error Messages Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-opposite-worlds-to-one-android-pc-harmony-plan/"><u>From Opposite Worlds to One: Android-PC Harmony Plan</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/from-viewer-to-victor-step-by-step-windows-pc-guide-for-high-quality-live-recording-for-2024/"><u>From Viewer to Victor Step-by-Step Windows PC Guide for High-Quality Live Recording for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-eradicate-recycle-bin-error-in-win1011/"><u>How to Eradicate Recycle Bin Error in WIN10/11</u></a></li>
<li><a href="https://fox-glue.techidaily.com/periscope-insights-how-to-access-and-create-user-account/"><u>Periscope Insights How to Access and Create User Account</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reigniting-stalled-wsreset-utility-in-windows-systems/"><u>Reigniting Stalled WSReset Utility in Windows Systems</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210882811-9781088186596-source-and-interpretation-of-dreams-with-fasting-prayer-for-fulfilment-of-good-dreams/"><u>Source And Interpretation Of Dreams With Fasting & Prayer For Fulfilment Of Good Dreams | Free Book</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-multiple-instances-problem-in-windows/"><u>Tackling 'Multiple Instances' Problem in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-list-of-trustworthy-win-friendly-downloads/"><u>The Ultimate List of Trustworthy Win-Friendly Downloads</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/top-19-affordable-audio-extractors-to-get-youtube-music-on-your-device-for-2024/"><u>Top 19 Affordable Audio Extractors to Get YouTube Music on Your Device for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-character-mapping-windows-11-guide/"><u>Unlocking Character Mapping: Windows 11 Guide</u></a></li>
</ul></div>

