---
title: Eliminate Windows 11'S Rounded Edges
date: 2024-08-16T01:25:10.735Z
updated: 2024-08-17T01:25:10.735Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminate Windows 11'S Rounded Edges
excerpt: This Article Describes Eliminate Windows 11'S Rounded Edges
keywords: Eliminate Windows Rounding,Remove Windows Edge Effect,Get Squared Windows 11,Square Window 11 Designs,No Round Edges in Win11,Edge-Less Windows 11,Fixed Shape Windows 11
thumbnail: https://thmb.techidaily.com/add496faff3567ece40d0c0a25d683b37093fb191cb1e756a607d3720738205f.png
---

## Eliminate Windows 11'S Rounded Edges

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
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
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->

 If you want to reverse the above change later, repeat the same steps mentioned earlier and change the value data for the **UseWindowFrameStagingBuffer** to **1**.

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->

 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-genres-to-gems-building-a-personalized-youtube-music-mix-onlinemobile/"><u>[New] 2024 Approved  From Genres to Gems  Building a Personalized YouTube Music Mix Online/Mobile</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-simplified-guide-integrating-snapchat-with-your-mac/"><u>[New] 2024 Approved  Simplified Guide  Integrating Snapchat with Your Mac</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-streamline-screen-recording-with-these-windows-tools/"><u>[New] 2024 Approved  Streamline Screen Recording with These Windows Tools</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-in-2024-embrace-audio-wonders-streaming-podcasts-with-an-iphone/"><u>[New] In 2024, Embrace Audio Wonders  Streaming Podcasts with an iPhone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-properly-posted-tweets-with-professional-videos/"><u>[New] In 2024, Properly Posted Tweets with Professional Videos</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-how-to-download-gif-images-from-twitter/"><u>[Updated] 2024 Approved  How to Download GIF Images From Twitter</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-the-complete-roadmap-downloading-editing-and-customizing-whatsapp-tones/"><u>[Updated] In 2024, The Complete Roadmap  Downloading, Editing & Customizing WhatsApp Tones</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-pro-level-drone-racing-techniques-and-quintessential-fpvs/"><u>[Updated] Pro-Level Drone Racing Techniques & Quintessential FPVs</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-avoiding-common-nocturnal-photography-errors/"><u>2024 Approved  Avoiding Common Nocturnal Photography Errors</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-celebrating-stop-motion-excellence-top-15-films/"><u>2024 Approved  Celebrating Stop-Motion Excellence  Top 15 Films</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-decoding-the-functionality-of-youtubes-media-hub/"><u>2024 Approved  Decoding the Functionality of YouTube's Media Hub</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-quick-ways-to-look-up-definitions-in-windows-11/"><u>3 Quick Ways to Look Up Definitions in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-easy-tips-for-memo-making-in-windows/"><u>7 Easy Tips for Memo-Making in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-tutorial-on-windows-1011s-audio-upgrade/"><u>A Comprehensive Tutorial on Windows 10/11'S Audio Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-windows-11-and-parallels-confluence-in-macos/"><u>Achieving Windows 11 and Parallels Confluence in MacOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activatedarkinterfaceinnotepadwinoses/"><u>ActivateDarkInterfaceInNotepadWinOSes</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/adding-pizzazz-to-your-footage-with-moving-text/"><u>Adding Pizzazz to Your Footage with Moving Text</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-no-supported-devices-problem-when-updating-windows/"><u>Addressing 'No Supported Devices' Problem When Updating Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-deactivated-outlook-mail-signals/"><u>Addressing Deactivated Outlook Mail Signals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-discrepancies-in-disk-based-discord-queries/"><u>Addressing Discrepancies in Disk-Based Discord Queries</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-issues-with-googles-nearby-sharing-on-desktop-pc/"><u>Addressing Issues with Google's Nearby Sharing on Desktop PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-operative-brightness-fn-button-on-windows-11/"><u>Addressing Non-Operative Brightness Fn Button on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-usb-connection-issues-on-windows-11/"><u>Addressing USB Connection Issues on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-winrars-summation-anomalies-with-six-fixes/"><u>Addressing WinRAR's Summation Anomalies with Six Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-shortcuts-fast-paste-of-set-text/"><u>Advanced Shortcuts: Fast Paste of Set Text</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-tips-for-docx-to-pdf-conversion-on-modern-windows/"><u>Advanced Tips for Docx-to-PDF Conversion on Modern Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altwindirstat-strategies-for-effective-disk-space-management/"><u>AltWinDirStat Strategies for Effective Disk Space Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assisting-with-utorrent-download-stalls-in-microsoft-environments/"><u>Assisting with uTorrent Download Stalls in Microsoft Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-procedures-for-win-11-mobility-center/"><u>Avoidance Procedures for Win 11 Mobility Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-auto-lock-on-windows-tips-and-tricks/"><u>Avoiding Auto-Lock on Windows: Tips & Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beat-the-blues-smooth-operations-for-11-windows-errors/"><u>Beat the Blues: Smooth Operations for 11 Windows Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-the-system-a-strategy-for-fixing-0x800700e9-in-xbox-game-passwindows-11/"><u>Beating the System: A Strategy for Fixing 0X800700E9 in Xbox Game Pass/Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginning-your-quake-experience-via-terminal/"><u>Beginning Your Quake Experience via Terminal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-practices-for-photographing-windows-user-acknowledgments/"><u>Best Practices for Photographing Windows' User Acknowledgments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blueprints-for-crafting-safe-dialog-box-for-hardware-disconnect/"><u>Blueprints for Crafting Safe Dialog Box for Hardware Disconnect</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-print-output-in-seconds-fix-windows-printer/"><u>Boost Print Output in Seconds, Fix Windows Printer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-productivity-windows-task-scheduler-strategies/"><u>Boosting Productivity: Windows Task Scheduler Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719278811623-bypassing-chrome-block-strategies-for-w11-users/"><u>Bypassing Chrome Block: Strategies for W11 Users.</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/from-live-demos-to-replays-tapping-into-aiseesoft-screencast-potential-for-2024/"><u>From Live Demos to Replays  Tapping Into Aiseesoft Screencast Potential for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/high-speed-visual-snapshot-and-voice-commentary-feature-for-2024/"><u>High-Speed Visual Snapshot & Voice Commentary Feature for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-leave-a-life360-group-on-honor-x9a-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How To Leave a Life360 Group On Honor X9a Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-reset-a-oppo-a78-5g-phone-that-is-locked-by-drfone-android/"><u>How to Reset a Oppo A78 5G Phone that is Locked?</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-12-mini-to-other-iphone-12-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 12 mini To Other iPhone 12 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-forgotten-the-voicemail-password-of-itel-p55-try-these-fixes-by-drfone-android/"><u>In 2024, Forgotten The Voicemail Password Of Itel P55? Try These Fixes</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-ultimate-durecorder-handbook-insights-and-evaluation/"><u>In 2024, Ultimate DuRecorder Handbook  Insights & Evaluation</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-vimeos-global-distribution-guide/"><u>In 2024, Vimeo's Global Distribution Guide</u></a></li>
<li><a href="https://fake-location.techidaily.com/ispoofer-is-not-working-on-oppo-a18-fixed-drfone-by-drfone-virtual-android/"><u>iSpoofer is not working On Oppo A18? Fixed | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-blockchain-with-gpt-top-10-chatbot-prompts-revealed/"><u>Mastering Blockchain with GPT: Top 10 Chatbot Prompts Revealed</u></a></li>
<li><a href="https://vp-tips.techidaily.com/mastering-media-best-twittersave-converters-for-2024/"><u>Mastering Media  Best Twittersave Converters for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/unlocking-the-secrets-to-perfect-zoom-recordings-for-2024/"><u>Unlocking the Secrets to Perfect Zoom Recordings for 2024</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-oneplus-nord-n30-se-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset OnePlus Nord N30 SE | Dr.fone</u></a></li>
</ul></div>
