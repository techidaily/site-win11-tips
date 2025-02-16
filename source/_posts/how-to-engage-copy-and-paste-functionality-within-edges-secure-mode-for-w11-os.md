---
title: How To Engage Copy & Paste Functionality Within Edge's Secure Mode for W11 OS
date: 2025-02-11T20:04:57.498Z
updated: 2025-02-15T20:13:36.432Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/zmXpl6irBYk?si=BXjGpQr6PXFcqhCI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

![Enable Copy and Paste via Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-via-windows-settings.jpg)
7. The UAC prompt will appear on the screen. Click**Yes** to continue.

 Once you’ve completed the steps, restart your computer for the changes to work. Now, you can securely transfer data between a virtualized environment and your device without any worries about security risks - malicious websites and applications will be blocked even with this setting enabled.

 If you ever need to disable copy and paste in Application Guard for Edge, you can follow the same steps mentioned above. Just be sure to toggle off the Copy and Paste setting from the Isolated browsing menu instead.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GPk8_xpN_rA?si=YbAdgsjAKsCn_UsB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
6. Finally, click**OK** to save your changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kx-Pb0otJCs?si=Mvr49yQVesmJA8-O" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jnITUsxMz5s?si=ohwRVH6eWhVnC6Xf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-screening-the-modern-internet-best-capture-apps-reviewed/"><u>[New] In 2024, Screening the Modern Internet Best Capture Apps Reviewed</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-leading-websites-for-acoustic-phone-alerts-for-2024/"><u>[New] Leading Websites for Acoustic Phone Alerts for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-collaborative-listening-made-simple-on-youtube-for-2024/"><u>[Updated] Collaborative Listening Made Simple on YouTube for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-enhance-video-appeal-with-filmmaker-friendly-subscribe-button-tutorials-filmora-for-2024/"><u>[Updated] Enhance Video Appeal with Filmmaker-Friendly Subscribe Button Tutorials (Filmora) for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-how-to-render-and-upload-your-youtube-video-faster-for-2024/"><u>[Updated] How to Render and Upload Your YouTube Video Faster for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-unveiling-the-top-watermarking-tools-in-photography/"><u>2024 Approved Unveiling the Top Watermarking Tools in Photography</u></a></li>
<li><a href="https://fox-search.techidaily.com/5lplusu5b6p5asx5pwi55qe6zqo6lqr56kf6loh5paz77ya5a6m5pw05oyh5y2x5lplusd5a2y5oma5pyj6yen6kab5lplush5ogv/"><u>修復失效的隨身碟資料：完整指南保存所有重要信息</u></a></li>
<li><a href="https://buynow-help.techidaily.com/expert-picks-leading-cable-modems-available/"><u>Expert Picks: Leading Cable Modems Available</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-use-special-features-virtual-location-on-xiaomi-redmi-note-13-5g-drfone-by-drfone-virtual-android/"><u>How To Use Special Features - Virtual Location On Xiaomi Redmi Note 13 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-preventing-minecraft-crashes/"><u>Master the Art of Preventing Minecraft Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pushing-limits-top-4-software-for-exceeding-windows-maxed-volume/"><u>Pushing Limits: Top 4 Software for Exceeding Windows’ Maxed Volume</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-requirements-not-met-error-on-windows-oses-10and11/"><u>Resolving Requirements Not Met Error on Windows OSes 10&11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/samsungs-solution-for-device-synergy-flow-streamlined/"><u>Samsung's Solution for Device Synergy - Flow Streamlined</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-remedying-unsettable-windows-nvidia-configs/"><u>Strategies for Remedying Unsettable Windows Nvidia Configs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-defeat-windows-error-0xfffffff/"><u>Strategies to Defeat Windows' Error 0xFFFFFFF</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-tasks-creating-windows-11-shortcuts-for-uwp/"><u>Streamlining Tasks: Creating Windows 11 Shortcuts for UWP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/syncing-ios-calendars-seamlessly-on-your-windoze-1011-pc/"><u>Syncing iOS Calendars Seamlessly on Your Windoze 10/11 PC</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/top-rated-portable-gaming-devices-in-2/"><u>Top Rated Portable Gaming Devices in 2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/your-first-steps-in-windows-accessibility-features/"><u>Your First Steps in Windows Accessibility Features</u></a></li>
</ul></div>

