---
title: Deciphering Win Error Logs Post-Blue Screen
date: 2024-08-23T07:01:15.940Z
updated: 2024-08-24T07:01:15.940Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Deciphering Win Error Logs Post-Blue Screen
excerpt: This Article Describes Deciphering Win Error Logs Post-Blue Screen
keywords: Blue Screen Fix Guide,BS Error Analysis,Windows Diagnostics,Troubleshoot Codes,PC Failsafe,System Log Decryption,Post-Blue Recovery
thumbnail: https://thmb.techidaily.com/fea69578f265b77158961ce9649233eee0ace50ab1ad8d0ca655a5decd1786bf.jpg
---

## Deciphering Win Error Logs Post-Blue Screen

 When your computer crashes and you face a Blue Screen of Death (BSOD), your system saves the details of the crash as a BSOD log, in a pre-defined location in Windows. This information gives you details about when the crash happened, what caused it, and sometimes even what to do to fix the problem.

 In this guide, we will first discuss where are the BSOD files located in Windows and then how to identify them. Once you have located a BSOD file, we will show you how to read it properly to understand the potential causes of the error and resolve the problem.

## Where Are the BSOD Log Files Located in Windows?

 You can find the BSOD log files in the Event Viewer, Control Panel, and Registry Editor in Windows. Below, we have listed the detailed steps for finding these files in all three of these utilities.

### 1\. Find and Read the BSOD Log Files in the Event Viewer

 The Event Viewer is a tool developed by Microsoft for users to view system and program-related events in Windows. These events can include system errors, warnings, informational messages, and more. In other words, every issue you encounter (whether a minor glitch or a major crash) will be logged in the Event Viewer for later investigation and sharing with Microsoft.

 You can check out our detailed guide on [what the Event Viewer is and how it can be useful](https://www.makeuseof.com/windows-event-viewer-guide/) if you are unfamiliar with it.

 Here is how you can find the BSOD log files in the Event Viewer:

1. Right-click on the Windows icon in the taskbar and choose **Event Viewer** from the context menu.  
![Choose Event Viewer in the context menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/event-viewer.jpg)
2. Head over to the **Action** menu located at the top, and choose **Create Custom View** from the context menu.  
![Create a custom view in the Event viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/create-custom-view.jpg)
3. In the following dialog, expand the dropdown for **Logged** and choose the time when you encountered the issue.  
![Check the logged section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/custom-time.jpg)
4. Now, move to the Event Level section and choose **Error**.  
![Event level of the error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/error-event-level.jpg)
5. Expand the dropdown for **Event Logs** and checkmark the box for **Windows Logs**.  
![Choose Windows logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-logs.jpg)

1. Click **OK** to proceed.
2. You will now be prompted to enter a name and description for the custom view you just created. Enter these details and click **OK**.  
![Create a filter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/name-event-viewer.jpg)
3. Once the view is created, you will be presented with a list of errors that occurred during the time frame you selected earlier. You can sort this information further in the Date and time section.  
![Check the Event Viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/event-viewer-11.jpg)
4. Next, locate the BSOD using details like the date and time again.
5. Once you find the targeted log, click on it.
6. Check both the General and Details tabs to get information about this error.

 Once you find the error code associated with the crash and the cause, you can look for solutions online, or head over to our guide that discusses [how to fix blue screen errors in Windows](https://www.makeuseof.com/tag/4-tips-fix-blue-screen-error/) if it's a bsod.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Find and Read the BSOD Log Files in the Registry Editor

 In case using the Event Viewer does not work for you for some reason, you can use another Windows utility to locate and study the BSOD log files—the Registry Editor.

 Windows Registry Editor is an administrative-level utility that lets you control how Windows operates and interacts with hardware and software. The Registry stores information related to the hardware and software components of your system. This information in the Registry is stored in the form of keys and values, and by modifying these with the dedicated Registry Editor, you can customize the operations of your system.

 Listed below are the steps for finding the BSOD log files in the Registry Editor. Make sure you are logged into your system as an administrator before you proceed.

1. Press the **Win + R** keys to open Run.
2. Type "regedit" in Run and press **Ctrl + Shift + Enter** to launch the Registry Editor as an administrator.
3. Now, select **Yes** in the User Account Prompt.
4. Once you are inside the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\CrashControl`
5. Next, move to the right pane and right-click on an empty space anywhere.
6. Choose **New** \> **DWORD (32-bit) Value**.  
![Create a new DWORD value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/dword-policies.jpg)
7. Name this value as **DisplayParameters** and double-click on it.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
8. Under Value data, type 1 and click **OK**.  
![Change the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/value-data-1.jpg)
9. Once done, restart your PC.

 Upon reboot, you should be able to view the log files without any problems.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
### 3\. Find and Read the BSOD Log Files in the Control Panel

 The third way of finding and reading the BSOD log files is via the Control Panel. This approach offers a graphical representation of the log files using the Windows Reliability Monitor, unlike the methods we have explored previously.

 The Reliability Monitor, which is different than the Performance Monitor (see [Reliability Monitor vs. Performance Monitor](https://www.makeuseof.com/reliability-monitor-vs-performance-monitor/)) will show you a timeline of important system events that occurred on your computer including BSOD occurrences, software installations, application crashes, and other relevant events.

 Here is how you can use it to identify and fix problems that may affect your system:

1. Type Control Panel in the search area of the taskbar and click **Open**.
2. In the following window, choose **System and Security** \> **Security and Maintenance**.  
![Security and maintenance settings in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/security-maintenance.jpg)
3. Click on **Maintenance** and then select **View reliability history**.  
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
![Check the reliability history of the system](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/view-realability-history.jpg)
4. You should now see a graph showing the reliability data. Look for red cross icons and blue (i) icons in the graph, as they show problematic events.  
![Reliability graph](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/realability-graph.jpg)
5. Click on each of the icons to view its details. Keep repeating the process to locate the event you are looking for.
<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You will be presented with information like the faulting application path, its name, fault module timestamp, exception code, etc. If this app caused a BSOD crash, then you can try ending its process via the Task Manager or uninstalling the app if it is not necessary.

 It is also a good idea to copy this information and send it to Microsoft for review if you cannot find a solution online.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## Learn How to Read Your BSOD Log Files and Resolve Your Crashes

 ​​​​​​Windows blue screen errors are nothing new, but since they only display messages like "Your PC encountered a problem" without describing the cause, it can be difficult to find a fix. Understanding how to read BSOD log files can not only help you identify the exact cause of the problem but also help you find the right solution.

 Whenever a component causes your system to crash, you can disable it and switch to a better alternative to avoid the problem.

 In this guide, we will first discuss where are the BSOD files located in Windows and then how to identify them. Once you have located a BSOD file, we will show you how to read it properly to understand the potential causes of the error and resolve the problem.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-capture.techidaily.com/new-windows-wonders-top-9-tools-to-capture-and-save-animated-gif-art/"><u>[New] Windows Wonders  Top 9 Tools to Capture and Save Animated GIF Art</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-avoid-being-overwhelmed-by-tiktok-drafts-edits-for-orderliness/"><u>[Updated] Avoid Being Overwhelmed by TikTok Drafts  Edits for Orderliness</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-economical-audience-expansion-buy-subscribers-not-time/"><u>[Updated] In 2024, Economical Audience Expansion  Buy Subscribers, Not Time</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-marketing-layers-deconstructing-strategys-packaging-for-2024/"><u>[Updated] Marketing Layers  Deconstructing Strategy's Packaging for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-acquire-unlimited-stock-images-via-top-4-youtube-sources/"><u>2024 Approved  Acquire Unlimited Stock Images via Top 4 YouTube Sources</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-through-win11s-disconnecting-gifs-dilemma-fixes-in-discord/"><u>Cutting Through Win11's Disconnecting GIFs Dilemma: Fixes in Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-error-a00f4289-from-your-windows-11-webcam/"><u>Eliminating Error A00F4289 From Your Windows 11 Webcam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-windows-11-steam-error-missing-files/"><u>Eliminating Windows 11 Steam Error: Missing Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-silent-slack-alerts-a-win-11-strategy-guide/"><u>Enhance Silent Slack Alerts: A Win 11 Strategy Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-techniques-to-manage-windows-key-settings/"><u>Expert Techniques to Manage Windows Key Settings</u></a></li>
<li><a href="https://techtrends.techidaily.com/exploring-online-capabilities-in-modern-televisions/"><u>Exploring Online Capabilities in Modern Televisions</u></a></li>
<li><a href="https://tech-haven.techidaily.com/exploring-the-reasons-for-heightened-ai-control-advocacy-by-openais-ceo-what-you-need-to-know/"><u>Exploring the Reasons for Heightened AI Control Advocacy by OpenAI's CEO – What You Need to Know</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/fast-techniques-to-recover-deleted-reddit-posts/"><u>Fast Techniques to Recover Deleted Reddit Posts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fine-tuning-the-password-reset-counter-in-windows-11-and-11-after-fails/"><u>Fine-Tuning the Password Reset Counter in Windows 11 and 11 After Fails</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/get-into-a-friends-live-showcase-effortlessly-for-2024/"><u>Get Into a Friend's Live Showcase Effortlessly for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-cut-down-clutter-spot-and-reduce-big-file-usage-windows/"><u>How to Cut Down Clutter: Spot and Reduce Big File Usage Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-fix-pokemon-go-route-not-working-on-lava-blaze-pro-5g-drfone-by-drfone-virtual-android/"><u>How to Fix Pokemon Go Route Not Working On Lava Blaze Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/1721958102553-immediate-guide-to-using-openais-new-gpt-based-shop-get-started-today/"><u>Immediate Guide to Using OpenAI's New GPT-Based Shop – Get Started Today</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-capturing-attention-a-guide-to-captivate-videos/"><u>In 2024, Capturing Attention  A Guide to Captivate Videos</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-essential-tips-building-an-instagram-money-machine/"><u>In 2024, Essential Tips  Building an Instagram Money Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keep-your-usb-active-disabling-hibernation-in-win-11/"><u>Keep Your USB Active: Disabling Hibernation in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-manual-time-adjustment-in-windows-systems/"><u>Master Manual Time Adjustment in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-usb-security-in-modern-operating-systems/"><u>Optimizing USB Security in Modern Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-start-guide-access-to-computer-controls/"><u>Quick Start Guide: Access to Computer Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functionality-to-windows-touchpad-commands/"><u>Restoring Functionality to Windows Touchpad Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-pc-efficiently-eliminate-extra-software-on-win11/"><u>Revamp Your PC: Efficiently Eliminate Extra Software on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-lost-power-options-in-ws-11-interface/"><u>Reviving Lost Power Options in WS 11 Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-windows-navigation-replacing-ls-command-usage/"><u>Simplifying Windows Navigation: Replacing LS Command Usage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-methods-for-naming-and-arranging-window-writings-max-156/"><u>Streamlined Methods for Naming and Arranging Window' Writings (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essentials-of-setting-up-pc-manager-on-windows-11/"><u>The Essentials of Setting Up PC Manager on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-clearing-up-windows-update-jams/"><u>The Ultimate Guide to Clearing Up Windows Update Jams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turn-off-sound-boosters-in-windows-settings/"><u>Turn Off Sound Boosters in Windows Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unifying-chrome-and-system-time-in-windows-land/"><u>Unifying Chrome and System Time in Windows Land</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-potential-on-app-and-browser/"><u>Unlocking Windows' Potential on App & Browser</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-portable-executable-format/"><u>Unraveling Windows' Portable Executable Format</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>