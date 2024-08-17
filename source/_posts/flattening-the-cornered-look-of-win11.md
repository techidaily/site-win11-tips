---
title: Flattening the Cornered Look of Win11
date: 2024-08-16T01:24:15.280Z
updated: 2024-08-17T01:24:15.280Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Flattening the Cornered Look of Win11
excerpt: This Article Describes Flattening the Cornered Look of Win11
keywords: WIN11 Aesthetics,Windows UI Update,Flat Design Win11,Modern Win11 Interface,Streamlined Win11 UI,New Edge Theme Win11,Cornerless Win11 Look
thumbnail: https://thmb.techidaily.com/8d3e36af5d5a0091c440dec8233de5f6c2799ee80a3e4e061f918707ae8b7038.jpg
---

## Flattening the Cornered Look of Win11

 With Windows 11, Microsoft brought several visual changes to its desktop operating system, including the notable addition of rounded corners for windows, menus, and dialog boxes. While the new design update has been widely embraced by many users, there are those who prefer a more traditional look with sharp corners.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

## 1\. How to Disable Rounded Corners in Windows 11 Using a Third-Party Tool

**Win11DisableOrRestoreRoundedCorners** is an open-source tool available on GitHub that can help you disable rounded corners on your Windows 11 PC. Since this tool modifies your PC's system files to remove the rounded corners, it's a good idea to [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before using it.

1. Head over to GitHub’s website to [download the Win11DisableOrRestoreRoundedCorners tool](https://github.com/valinet/Win11DisableRoundedCorners/releases).
2. Double-click the downloaded executable file to run it.
3. If you see the Microsoft Defender SmartScreen window, click on **More info** and then select **Run anyway**.
4. Select **Yes** when the User Account Control (UAC) prompt appears.  
![Microsoft Defender SmartScreen Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-defender-smartscreen-window.jpg)

 Once you complete the above steps, a PowerShell window should appear and disable rounded corners on your PC. Here’s a glimpse of how your windows will look once the rounded corners are disabled.

![Square Corners in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/square-corners-in-windows-11.jpg)

 Note that this tool will not disable rounded corners in the Start menu or some modern apps. If you want to revert the changes later, simply run the downloaded EXE file again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## 2\. How to Disable Rounded Corners in Windows 11 Using the Registry Editor

 Don't want to use a third-party tool? No problem. You can also disable rounded corners in Windows 11 by making changes to the Windows Registry. However, it's crucial to exercise caution, as modifying registry files without proper knowledge can be risky.

 Before you proceed, consider [backing up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/), just in case. After that, use these steps to disable rounded corners via the Registry Editor:

1. Press **Win + S** to open the search menu.
2. Type in **registry editor** and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Navigate to **Computer > HKEY\_CURRENT\_USER > Software > Microsoft > Windows > DWM**.
5. Right-click on the **DWM** key and select **New > DWORD (32-bit) Value**. Rename it to **UseWindowFrameStagingBuffer**.
6. Double-click the newly created DWORD and enter **0** in the **Value data** field. Then, click **OK**.
7. [Restart your PC](https://www.makeuseof.com/windows-restart-methods/) to apply the changes.  
![Disable Rounded Corners in Windows 11 via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-rounded-corners-in-windows-11-via-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->

 If you want to reverse the above change later, repeat the same steps mentioned earlier and change the value data for the **UseWindowFrameStagingBuffer** to **1**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->
## 3\. How to Disable Rounded Corners in Windows 11 via Device Manager

 Another way to remove rounded corners in Windows 11 is by disabling the graphics driver on your PC. However, it is important to consider a few caveats. Firstly, disabling the graphics driver will result in reduced display performance, lower screen resolutions, and the deactivation of any visual effects. Secondly, this will also prevent you from running any graphics-intensive applications or games on your PC.

 If you are fine with these trade-offs, use these steps to disable rounded corners via Device Manager.

1. Press **Win + X** to open the Power User menu.
2. Select **Device Manager** from the list.
3. Double-click on **Display adapters** to expand it.
4. Right-click on your display driver and select **Disable device**.  
![Disable Graphics Driver on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-graphics-driver-on-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
## Disabling Rounded Corners in Windows 11 Is Easy

 Using a third-party tool is arguably the most convenient way to remove rounded corners in Windows 11\. However, if you prefer to rely on the native methods, you can use the Registry Editor or Device Manager instead.

 Disabling rounded corners isn’t the only way to get the classic look of previous Windows versions. You can also use a third-party tool like the ExplorerPatcher to make Windows 11 look like Windows 10\.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-efficient-strategies-to-log-facetime-discussions-for-2024/"><u>[New] Efficient Strategies to Log FaceTime Discussions for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-harness-the-power-of-storytelling-making-captivating-reels-on-facebook-for-2024/"><u>[New] Harness the Power of Storytelling  Making Captivating Reels on Facebook for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-how-to-reverse-video-on-instagram-complete-guide/"><u>[New] In 2024, How to Reverse Video on Instagram? [Complete Guide]</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-voice-logger-innovations-for-mac-users-unveiling-the-best-5-apps/"><u>[New] In 2024, Voice Logger Innovations for Mac Users  Unveiling the Best 5 Apps</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-the-ultimate-guide-to-ai-infused-gaming-broadcasts-for-2024/"><u>[New] The Ultimate Guide to AI-Infused Gaming Broadcasts for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-extensive-look-at-djis-inspire-1-drone/"><u>[Updated] 2024 Approved  Extensive Look at DJI's Inspire 1 Drone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-best-beams-microphones-for-education/"><u>[Updated] Best Beams  Microphones for Education</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-cutting-edge-techniques-for-incorporating-soundtracks-in-youtube-creations-for-2024/"><u>[Updated] Cutting-Edge Techniques for Incorporating Soundtracks in YouTube Creations for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-filmoras-quick-start-approach-for-youtube-trailers-for-2024/"><u>[Updated] Filmora's Quick-Start Approach for YouTube Trailers for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-how-to-capitalize-on-your-youtube-shorts-for-cash-flow/"><u>[Updated] How to Capitalize on Your YouTube Shorts for Cash Flow</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-how-to-upload-a-video-on-twitter-in-2024/"><u>[Updated] How to Upload a Video on Twitter, In 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-accelerated-conversion-of-yt-content-for-mac-screens/"><u>[Updated] In 2024, Accelerated Conversion of YT Content for MAC Screens</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-xml-ssa-ttml-conversion-your-pathway-to-perfected-srts/"><u>[Updated] In 2024, XML, SSA, TTML Conversion  Your Pathway to Perfected SRTs</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-uncovering-budget-friendly-video-conferencing-tools-for-multiple-systems/"><u>[Updated] Uncovering Budget-Friendly Video Conferencing Tools for Multiple Systems</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/approved-rank-higher-on-youtube-essential-seo-tips-unveiled/"><u>2024 Approved  Rank Higher on YouTube  Essential SEO Tips Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-default-cmd-settings-with-ease/"><u>Altering Default CMD Settings with Ease</u></a></li>
<li><a href="https://facebook.techidaily.com/deciphering-online-ambiguity-a-study-on-vague-content-sharing/"><u>Deciphering Online Ambiguity: A Study on Vague Content Sharing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-directory-size-a-powershell-approach/"><u>Dissecting Directory Size: A PowerShell Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-method-for-deleting-steam-dns-from-windows-os/"><u>Efficient Method for Deleting Steam DNS From Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-handling-widget-notifications-win-11-style/"><u>Efficiently Handling Widget Notifications Win 11 Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-experience-locate-the-lost-feature-in-windows-11/"><u>Enhance Your Experience: Locate the Lost Feature in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explaining-and-mending-error-code-0x8007251d-a-guide/"><u>Explaining and Mending Error Code 0X8007251d: A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-crash-of-windows-update-error-x712/"><u>Fixing the Crash of Windows Update Error X712</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-androidprocessmedia-has-stopped-on-motorola-moto-e13-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android.Process.Media Has Stopped on Motorola Moto E13 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-there-are-no-more-files-error-on-windows-10-and-11/"><u>How to Fix the “There Are No More Files” Error on Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-solve-media-creator-tool-errors-winerror-0x8007043c/"><u>How to Solve Media Creator Tool Errors: WinError 0X8007043C</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-watch-avchd-mts-video-on-samsung-galaxy-f14-5g-by-aiseesoft-video-converter-play-mts-on-android/"><u>How to watch AVCHD MTS video on Samsung Galaxy F14 5G?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-realme-narzo-n53-to-pc-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Realme Narzo N53 to PC? | Dr.fone</u></a></li>
<li><a href="https://buynow-help.techidaily.com/in-depth-analysis-of-genius-widecam-f100-understanding-its-blurry-images-and-reverberant-audio/"><u>In-Depth Analysis of Genius WideCam F100: Understanding Its Blurry Images & Reverberant Audio</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/inspiring-14-animated-text-concepts-for-2024/"><u>Inspiring 14 Animated Text Concepts for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/intense-meetings-perfect-your-screen-focus-in-msteams-for-2024/"><u>Intense Meetings  Perfect Your Screen Focus in MSTEAMS for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-recordings-best-no-fee-windows-editors/"><u>Master Your Recordings: Best No-Fee Windows Editors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-error-code-31-in-windows-os/"><u>Mastering the Art of Fixing Error Code 31 in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-revive-network-router-page-on-windows/"><u>Methods to Revive Network Router Page on Windows</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/microsoft-sculpt-keyboard-balancing-quality-and-cost-for-optimal-typing-comfort/"><u>Microsoft Sculpt Keyboard: Balancing Quality and Cost for Optimal Typing Comfort</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-comics-an-intuitive-approach-for-win11-users/"><u>Navigating Comics: An Intuitive Approach for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-valorant-microphone-failures-on-windows-10/"><u>Overcoming Valorant Microphone Failures on Windows 10</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/perfecting-slide-deck-sharing-how-to-use-your-webcam-for-2024/"><u>Perfecting Slide Deck Sharing  How to Use Your Webcam for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-geforce-experience-setup-failure-windows-11-edition/"><u>Resolving GeForce Experience Setup Failure, Windows 11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-microsoft-store-blockage-issue-on-win11/"><u>Resolving Microsoft Store Blockage Issue on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-unidentified-window-second-screen/"><u>Resolving Unidentified Window Second Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalize-your-windows-11-interface-with-these-tips/"><u>Revitalize Your Windows 11 Interface with These Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-grades-with-these-top-8-windows-study-hacks/"><u>Skyrocket Grades with These Top 8 Windows Study Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-0x8024800c-in-windows-update/"><u>Steps to Resolve 0X8024800C in Windows Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-correcting-severe-browser-js-problem-in-discord/"><u>Strategies for Correcting Severe Browser JS Problem in Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-win11-space-to-perfection/"><u>Tailoring Your Win11 Space to Perfection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/telnet-integration-in-modern-windows-11/"><u>Telnet Integration in Modern Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-unseen-resurrect-off-screen-windows-in-win1011/"><u>Unlock the Unseen: Resurrect Off-Screen Windows in Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-secrets-efficient-qr-codes-on-windows-systems/"><u>Unlocking Secrets: Efficient QR Codes on Windows Systems</u></a></li>
<li><a href="https://games-able.techidaily.com/unveiling-discords-gaming-potential-chesspoker-edition/"><u>Unveiling Discord's Gaming Potential: Chess/Poker Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11s-secure-testing-solution-enabling-and-configuring-sandbox/"><u>Win 11'S Secure Testing Solution: Enabling and Configuring Sandbox</u></a></li>
</ul></div>
