---
title: How To Address the “Invalid Token Access” Error on Win10
date: 2024-08-08T11:02:27.540Z
updated: 2024-08-09T11:02:27.540Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How To Address the “Invalid Token Access” Error on Win10
excerpt: This Article Describes How To Address the “Invalid Token Access” Error on Win10
keywords: Win10 Invalid Token Fix,Windows 10 Token Error Solution,Solve Token Access Issue in Win10,Correcting Invalid Tokens in Win10,Resolving Token Access Error on PC,Win10 Password Error Troubleshooting,Fix Invalid Auth Token on Windows
thumbnail: https://thmb.techidaily.com/bf32c159170edbc355c721b22ee8ee6c67dda36feed408fdb0ec7f3ca8b4ddc2.jpg
---

## How To Address the “Invalid Token Access” Error on Win10

 Windows includes numerous pre-installed apps and tools like File Explorer, Device Manager, and Microsoft Management Console users often need to access. However, some users have reported they can’t access those pre-installed apps or others because of an error that says, “an attempt was made to reference a token that does not exist.” That error pops up when some users try to open Explorer or other native tools.

 Does the same error message pop up when you try to access Explorer, Device Manager, or another native Windows tool? If yes, try applying these potential remedies for the “reference a token” error.

## 1\. End and Restart File Explorer

 If the “reference a token” error occurs when you try to access File Explorer or folders, try restarting the Explorer process. Some users who’ve needed to fix the token reference error have said ending that Windows Explorer process and starting it again worked for them. You can end and restart Explorer as follows:

1. [Launch Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) by simultaneously pressing the **Ctrl** \+ **Shift** \+ **Esc** keyboard keys.
2. Scroll down to the Windows Explorer on the **Processes** tab.
3. Then right-click Windows Explorer and select **End task**.  
![The End task option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/end-task-option.jpg)
4. Select **End process** to confirm. The background Windows desktop will go blank when you do that, and restarting Explorer will restore it.
5. Click **File** at the top of Task Manager.  
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Run new task option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-new-task.jpg)
6. Select **Run new task** to access a Create new task box.
7. Input **Explorer.exe** inside the **Open** text box.  
<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Create new task window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/create-new-task.jpg)
8. Select **Create this task with administrative privileges** and click **OK** to restart Explorer.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
## 2\. Reregister Windows DLL Files

 Users who’ve needed to fix the “reference a token” error have confirmed reregistering the Windows DLL (Dynamic Link Library) files works. That highlights the token reference error can occur because some Windows DLL files aren’t correctly registered. This is how you can reregister Windows DLL files:

1. Bring up the **Type here to search** text box for finding files with the **Windows** logo key + **S** hotkey.
2. Next, type a **CMD** search phrase in the file finder text box.
3. Right-click on **Command Prompt** inside the file search tool to select **Run as administrator**.
4. Now enter and execute this command for reregistering DLL files:  
`for /f %s in ('dir /b *.dll') do regsvr32 /s %s`  
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
![The reregister DLL command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/reregister-dll-commands.jpg)
5. Wait for the command to finish reregistering DLLs.
6. Close your Command Prompt app, bring up the Start menu, and select **Restart**.

## 3\. Try Some More Generic Windows Fixes

 If nothing has worked, try these Windows fixes that can fix a wide variety of errors, including this one.

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
### Scan and Repair System Files With SFC

 The “reference a token” error is often a result of corrupted Windows system files. So, repairing system files is a likely potential solution for that error. You can check for and repair corrupted system files by [running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) within the Command Prompt.

![The sfc /scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/sfc-scannow-command5.jpg)

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
### Go Back to a Previous Windows Build Version

 If the “reference a token” error occurs after a recent Windows feature update, restoring the previous build version might resolve that issue. However, you can only restore a previous build version for a limited period. This is how you can restore a previous Windows build version:

1. Activate the file search box and input the keyword **recovery options**.
2. Select **Recovery** **options** to bring up Settings.
3. Click the **Go back** or **Get started** button for restoring the previous Windows version.  
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Get started button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/get-started-button.jpg)

 If that option is grayed out, you can also try restoring the previous Windows build from the **Advanced options** menu. Open recovery options in Settings as outlined in steps one and two above and click **Restart** **now**. Then select **Troubleshoot** \> **Advanced** options and the **Go back** **to previous build** option if available.

### Go Back to a Previous Restore Point

 System Restore is another tool that can resolve system file issues causing the “reference a token” error, but only if you have that utility enabled on your PC. If there’s a suitable restore point on your PC, you can roll back Windows to a previous point in time that predates the token reference error. Doing so might undo updates and other system changes that triggered the issue.

![The System Restore tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/system-restore-point.jpg)

 To apply this resolution, check out our [article about creating and utilizing restore points](https://www.makeuseof.com/windows-11-create-restore-point/). Choose a restore point that will roll Windows back to when you didn’t need to fix the token reference error. However, note that a system restore point will remove software packages installed after its date.

### Reset Windows

 Resetting Windows 11/10 is a last resort for fixing the “reference a token” error that will probably work. It’s best to save this probable resolution until last because you’ll need to reinstall all third-party UWP and desktop apps installed before the reset. You can apply this possible resolution as instructed within method one of our [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/#:~:text=To%20run%20a%20Windows%20factory,%3E%20Update%20%26%20Security%20%3E%20Recovery.) guide.

## Get the “Reference a Token” Error Sorted Out

 The “reference a token” error is serious when users can’t access essential native apps like File Explorer because of it. In many cases, corrupted Windows files are usually the culprit. Most of the resolutions in this guide will address that cause, and restarting File Explorer can also work when the issue affects that app or folders.

 Does the same error message pop up when you try to access Explorer, Device Manager, or another native Windows tool? If yes, try applying these potential remedies for the “reference a token” error.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-innovative-5-web-video-capturing-technologies/"><u>[New] 2024 Approved  Innovative 5 Web Video Capturing Technologies</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-windows-10s-complete-guide-to-saving-mov-content-with-ease/"><u>[New] 2024 Approved  Windows 10'S Complete Guide to Saving .mov Content with Ease</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-enjoy-classic-games-anywhere-with-the-top-5-pc-based-gb-emulators-for-2024/"><u>[New] Enjoy Classic Games Anywhere with the Top 5 PC-Based GB Emulators for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-harness-your-pcs-power-for-high-dynamic-range-video-magic/"><u>[Updated] Harness Your PC's Power for High Dynamic Range Video Magic</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-a-step-by-step-for-delving-into-fb-archives/"><u>[Updated] In 2024, A Step-by-Step for Delving Into FB Archives</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-screen-capturing-on-snapchat-a-guide-for-smartphones/"><u>[Updated] In 2024, Screen Capturing on Snapchat - A Guide for Smartphones</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-streamlining-audio-integration-in-youtube-videos-for-professionals/"><u>[Updated] Streamlining Audio Integration in YouTube Videos for Professionals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-proven-strategies-to-solve-windows-update-woes/"><u>10 Proven Strategies to Solve Windows Update Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-common-complaints-users-have-about-windows-11/"><u>5 Common Complaints Users Have About Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-key-strategies-for-optimizing-windows-11s-bar/"><u>5 Key Strategies for Optimizing Windows 11'S Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-secure-windows-strategies-when-bitlocker-fails/"><u>5 Secure Windows Strategies When Bitlocker Fails</u></a></li>
<li><a href="https://win11-tips.techidaily.com/50plus-innovative-ideas-to-customize-your-windows-11-layout/"><u>50+ Innovative Ideas to Customize Your Windows 11 Layout</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-walkthrough-to-setting-up-dns-on-windows-11/"><u>A Complete Walkthrough to Setting Up DNS on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-altering-lockout-frequency-in-windows-11-successor/"><u>A Step-by-Step Guide to Altering Lockout Frequency in Windows 11 Successor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-using-windows-iscsi-initiator/"><u>A Step-by-Step Guide to Using Windows iSCSI Initiator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-thoroughly-detailed-guide-to-windows-boot-options/"><u>A Thoroughly Detailed Guide to Windows Boot Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-compute-with-essential-wintoy-tech/"><u>Accelerate Your Compute with Essential WinToy Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-ui-skills-with-windows-11-widgets/"><u>Accelerate Your UI Skills with Windows 11 Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/access-denied-reconnecting-to-windows-shared-items/"><u>Access Denied: Reconnecting to Windows Shared Items</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-academic-success-winning-strategies-for-windows/"><u>Achieve Academic Success: Winning Strategies for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-lunar-client-startup-failures-on-windows-systems/"><u>Addressing “Lunar Client Startup Failures” On Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-vscode-shutdown-problems-on-windows-11/"><u>Addressing VSCode Shutdown Problems on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-sfx-strategies-for-windows-11-users/"><u>Advanced SFX Strategies for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/asus-zenbook-14-oled-ux3405-review-is-this-the-macbook-of-windows/"><u>ASUS Zenbook 14 OLED (UX3405) Review: Is This the MacBook of Windows?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/batch-processing-closure-for-busy-windows-users/"><u>Batch-Processing Closure for Busy Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beat-the-blues-swift-remedies-to-hypervisor-bsos-in-winxose/"><u>Beat the Blues: Swift Remedies to Hypervisor BSOS in WINXOSE</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bitlock-cracked-staying-secure-yet-unmoved/"><u>BitLock Cracked: Staying Secure Yet Unmoved</u></a></li>
<li><a href="https://driver-error.techidaily.com/bluetooth-mouse-disconnects-without-warning/"><u>Bluetooth Mouse Disconnects Without Warning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-amd-graphics-efficiency-windows-11-updates-guide/"><u>Boosting AMD Graphics Efficiency: Windows 11 Updates Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-call-productivity-on-windows-11-with-the-intel-unison-app/"><u>Boosting Call Productivity on Windows 11 with the Intel Unison App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719244514852-enhancing-your-windows-snipping-experience-with-proven-fixes/"><u>Enhancing Your Windows Snipping Experience with Proven Fixes</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-the-role-of-content-filtering-in-ai-chatbots/"><u>Exploring the Role of Content Filtering in AI Chatbots</u></a></li>
<li><a href="https://extra-hints.techidaily.com/handling-soundtracks-opening-srt-on-pcmac/"><u>Handling Soundtracks  Opening SRT on PC/Mac</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-change-your-apple-id-password-on-your-iphone-6-drfone-by-drfone-ios/"><u>How To Change Your Apple ID Password On your iPhone 6 | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-a-lost-poco-m6-5g-for-free-drfone-by-drfone-virtual-android/"><u>How to Track a Lost Poco M6 5G for Free? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719294305886-ignite-performance-gains-in-winoutlook-today/"><u>Ignite Performance Gains in WinOutlook, Today</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-efficiently-saving-your-screen-the-dell-approach/"><u>In 2024, Efficiently Saving Your Screen  The Dell Approach</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-full-guide-to-fix-itoolab-anygo-not-working-on-apple-iphone-xs-max-drfone-by-drfone-virtual-ios/"><u>In 2024, Full Guide to Fix iToolab AnyGO Not Working On Apple iPhone XS Max | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-shade-smarts-mastering-the-art-of-color-correction-with-speed/"><u>In 2024, Shade Smarts  Mastering the Art of Color Correction with Speed</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-unlock-your-boost-mobile-apple-iphone-12-pro-max-before-the-plan-expires-by-drfone-ios/"><u>In 2024, Unlock Your Boost Mobile Apple iPhone 12 Pro Max Before the Plan Expires</u></a></li>
<li><a href="https://technical-tips.techidaily.com/is-everyone-struggling-with-playstation-online-services-or-is-it-just-my-connection/"><u>Is Everyone Struggling with PlayStation Online Services, Or Is It Just My Connection?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719367478733-overcome-windows-obstacles-expert-advice-awaits/"><u>Overcome Windows Obstacles: Expert Advice Awaits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719266622683-rejuvenate-your-locked-shift-key-in-windows/"><u>Rejuvenate Your Locked Shift Key in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719276426207-saving-the-day-with-win1011s-recycle-bin-corruption-fixed/"><u>Saving the Day with Win10/11's Recycle Bin Corruption Fixed</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-best-ispoofer-alternative-to-try-on-sony-xperia-10-v-drfone-by-drfone-virtual-android/"><u>The Best iSpoofer Alternative to Try On Sony Xperia 10 V | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-directx-installation-and-upgrades/"><u>The Ultimate Guide to DirectX Installation and Upgrades</u></a></li>
<li><a href="https://program-issues.techidaily.com/ultimate-troubleshooting-guide-for-warcraft-ninja-defeating-game-crashes-on-pc-updated-tips/"><u>Ultimate Troubleshooting Guide for Warcraft Ninja: Defeating Game Crashes on PC - Updated Tips</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/ways-to-find-unlocking-codes-for-samsung-galaxy-s24-phones-by-drfone-android/"><u>Ways To Find Unlocking Codes For Samsung Galaxy S24 Phones</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>