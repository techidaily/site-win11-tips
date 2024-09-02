---
title: "Navigating the Transition: WSL and Windows 11' Written by [Your Name]"
date: 2024-09-01T05:17:30.192Z
updated: 2024-09-02T05:17:30.192Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Navigating the Transition: WSL and Windows 11' Written by [Your Name]"
excerpt: "This Article Describes Navigating the Transition: WSL and Windows 11' Written by [Your Name]"
keywords: WSL Basics,Windows 11 Updates,WinShell Environment,Linux on PC,MSYS2 Tools,Cygwin Interface,Windows Subsystem
thumbnail: https://thmb.techidaily.com/62017b9a75f2be738008dfd82e88e32736119212be885f48835d0be5b0d3459a.jpg
---

## Navigating the Transition: WSL and Windows 11' Written by [Your Name]

 There are several potential reasons why Windows Subsystem for Linux (WSL) stopped working after your PC was upgraded to Windows 11\. Thankfully, the breakdown is unlikely to be terminal, although you might have to try a few different fixes to get it working once again.

 **MUO VIDEO OF THE DAY**

 **SCROLL TO CONTINUE WITH CONTENT**

 Here are several ways to get the Windows Subsystem for Linux working again after upgrading to Windows 11.

## 1\. Check That WSL Is Enabled

 It isn't unusual that upgrading to a newer version of the OS will break some apps and features. So although it might sound obvious, checking WSL hasn't simply been disabled during the upgrade process should be your first step. Here's how to check:

![checking if WSL is enabled in Windows Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-enabled.jpg)

1. In Windows Search, type**Turn Windows features on or off** and click the search result that should appear at the top.
2. In the Windows System dialog, scroll down until you see**Windows Subsystem for Linux** .
3. If the checkbox for the feature is not selected, do so now. Then click**Ok** .
4. You might also need to restart your computer before checking to see if that fixed the problem.

 Hopefully, WSL is now working, and you can begin using the tool. If not, read on for some other possible solutions.

 Learn more about the[things you can do with WSL and Linux](https://www.makeuseof.com/pros-cons-windows-subsystem-for-linux/) on your Windows computer.

## 2\. Enable Hyper-V and Virtual Machine Platform

 If you want to use a subsystem such as WSL in Windows, you'll also need to enable the virtualization tools. These include Hyper-V and the Virtual Machine Platform.

![Error message in the command line interface](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-feature-missing.jpg)

 If a command line interface opens, telling you a required feature is not installed, when you try to run your Linux distribution, this is likely what it refers to.

1. Search for**Turn Windows features on or off** and click the search result.
2. In Windows Features, scroll down to find**Virtual Machine Platform** and**Windows Hypervisor Platform** .
3. Check the boxes next to each of these features and then click**Ok** .
4. You will need to restart your computer to complete the installation of these tools.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Repair the Linux Distribution App

 Your Linux distribution app, such as Ubuntu, Kali, or Debian, could be corrupted or require updating. This can cause WSL to appear to be broken. Repairing Windows apps is very easy.

1. Open**Settings > Apps > App & Features** .
2. Scroll down to the list of your apps to find your Linux distro app.
3. Click the**three dots** to the right of the app name, and select**Advanced options** .  
![Advanced app options in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl.jpg)
4. Click the**Repair** button and follow the on-screen instructions if repairs are necessary.  
![repairing an app in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl-app.jpg)

 Check if WSL is working. If not, try uninstalling and reinstalling the Linux distribution app.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
## 4\. Force WSL to Open Using the Microsoft Store

 If WSL is enabled but still refuses to open, you can try forcing launch through the Microsoft Store app. This can sometimes fix temporary glitches when opening WSL directly doesn't work.

1. Open the Microsoft Store app and search for**WSL** .
2. On the store page for WSL, you should see an**Open** button. If the button says**Update** , click it to update the app.  
![opening the WSL app in the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/force-open-store.jpg)
3. Click the**Open** button, and the default Linux distro app should launch.
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
4. If a command line interface window opens instead, it will probably tell you a required feature is missing. See**Enable Hyper-V and Virtual Machine Platform** above.

 If forcing WSL to open doesn't work, try the same with the Linux distro app you are using. Open the Store, search for your distro, and click the**Open** button.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
## 5\. Uninstall Recent Updates to Fix WSL

 If WSL stopped working after installing an update, the update could be the cause. You can uninstall the most recent update to see if that fixes the problem.

[Uninstalling Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) isn't a complicated process, even if you have never done it before.

 If, after uninstalling the update, WSL still does not work, it is a good idea to reinstall it. Updates can often include security and performance tweaks, so it is generally recommended to keep Windows updated.

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Check That Malware Isn't Blocking WSL

 The final thing to try to get WSL working is scanning for malware. The potential for malware to prevent Windows Subsystem for Linux from working is low but not unheard of.

 Run a[full scan in Microsoft Defender](https://www.makeuseof.com/easy-ways-boost-security-microsoft-defender-and-windows-10/) or whichever third-party antivirus software you use. Quarantine or remove any malware your antivirus scan finds. Then restart your computer and try using WSL to see if that was the issue.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
## Fixing WSL After Upgrading to Windows 11

 Upgrading to Windows 11 usually goes smoothly, but apps and features can occasionally break. If you find that WSL is no longer working after upgrading to the newest Windows OS, don't worry, there is usually an easy fix. You might only need to re-enable the feature in the Windows system settings, but if not, running through the other fixes here will usually solve the problem.


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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-harness-the-full-potential-of-video-tags-in-youtube/"><u>[New] 2024 Approved  Harness the Full Potential of Video Tags in YouTube</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-immersive-viewing-microsoft-edges-pip/"><u>[New] Immersive Viewing  Microsoft Edge's PIP</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-the-essential-guide-to-capturing-skype-conversations-on-windowsmac/"><u>[New] The Essential Guide to Capturing Skype Conversations on Windows/Mac</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-amplify-impact-strategies-for-instagram-video-waves/"><u>[Updated] 2024 Approved  Amplify Impact  Strategies for Instagram Video Waves</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-facebook-lives-demystified-the-best-ways-to-record-a-stream/"><u>[Updated] 2024 Approved  Facebook Lives Demystified  The Best Ways to Record a Stream</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-optimal-screen-record-settings-for-facetime-conversations/"><u>[Updated] In 2024, Optimal Screen Record Settings for FaceTime Conversations</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-stellar-background-choices-for-effective-video-conferencing/"><u>[Updated] In 2024, Stellar Background Choices for Effective Video Conferencing</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/10-top-free-online-photo-editor/"><u>10 Top Free Online Photo Editor</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-direct-guide-saving-twitter-videos-on-your-mobile-device/"><u>2024 Approved  Direct Guide  Saving Twitter Videos on Your Mobile Device</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-effortless-voice-memo-recording-on-your-iphone/"><u>2024 Approved  Effortless Voice Memo Recording on Your iPhone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-the-ultimate-guide-clearing-out-the-unwanted-space-around-images-with-affinity/"><u>2024 Approved  The Ultimate Guide  Clearing Out the Unwanted Space Around Images with Affinity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-the-0x0-error-essential-fixes-for-win11-users/"><u>Conquer the 0X0 Error: Essential Fixes for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-error-e1-for-surface-go-win10/"><u>Correcting Error E1 for Surface Go (Win10)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-memory-the-easy-way-to-identify-ram/"><u>Decoding Windows Memory: The Easy Way to Identify RAM</u></a></li>
<li><a href="https://facebook.techidaily.com/digital-defenders-how-facebook-and-google-can-thwart-scam-advertising/"><u>Digital Defenders: How Facebook & Google Can Thwart Scam Advertising</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-hidden-patterns-in-data-usage-through-windows-diskusage-command/"><u>Discovering Hidden Patterns in Data Usage Through Windows' DiskUsage Command</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-vivo-y100-5g-drfone-by-drfone-virtual-android/"><u>Dose Life360 Notify Me When Someone Checks My Location On Vivo Y100 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-phone-to-windows-audio-streaming-tips/"><u>Effortless Phone-to-Windows Audio Streaming Tips</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/eliminating-loneliness-chatgpt-as-a-supportive-companion/"><u>Eliminating Loneliness: ChatGPT as a Supportive Companion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-seamless-live-stream-quality-with-steam/"><u>Ensuring Seamless Live Stream Quality with Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-knowledge-on-vcplusplus-distribution/"><u>Essential Knowledge on VC++ Distribution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-non-windows-apps-for-modern-computing/"><u>Essential Non-Windows Apps For Modern Computing</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-non-ad-focused-start-menu-win-11/"><u>Exclusive, Non-Ad Focused Start Menu Win 11</u></a></li>
<li><a href="https://facebook.techidaily.com/experience-streaming-purely-focused-ig-livestream/"><u>Experience Streaming Purely Focused IG Livestream</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-theme-options-a-comprehensive-guide-for-windows-users/"><u>Exploring Theme Options: A Comprehensive Guide for Windows Users</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/fixed-freeze-panes-not-working-in-excel-2021-by-stellar-guide/"><u>Fixed Freeze Panes not Working in Excel 2021</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-grayed-out-memory-protection-in-win11-update/"><u>Fixing Grayed-Out Memory Protection in Win11 Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-opengl-issue-3-with-nvidia-on-windows-11-os/"><u>Fixing OpenGL Issue #3 with NVIDIA on Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/getting-to-your-capture-application-fast-in-windows-11/"><u>Getting to Your Capture Application Fast in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-through-the-maze-of-windows-10-crash-modes/"><u>Guide Through the Maze of Windows 10 Crash Modes</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-can-i-catch-the-regional-pokemon-without-traveling-on-oppo-find-n3-flip-drfone-by-drfone-virtual-android/"><u>How Can I Catch the Regional Pokémon without Traveling On Oppo Find N3 Flip | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-critical-js-error-affecting-discord-on-modern-windows-devices/"><u>How to Resolve Critical JS Error Affecting Discord on Modern Windows Devices</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-htc-u23-pro-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from HTC U23 Pro to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-3-things-you-must-know-about-fake-snapchat-location-on-realme-11-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Things You Must Know about Fake Snapchat Location On Realme 11 Pro+ | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-itel-p40plus-phone-without-any-data-loss-by-drfone-android/"><u>In 2024, How to Unlock Itel P40+ Phone without Any Data Loss</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-imageharmony-pro-8-version-visualizer/"><u>In 2024, ImageHarmony Pro  8-Version Visualizer</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-windows-11-excellent-video-capture-tools-compared/"><u>In 2024, Windows 11  Excellent Video Capture Tools Compared</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-analysis-executing-powerful-registry-changes-via-terminal/"><u>In-Depth Analysis: Executing Powerful Registry Changes via Terminal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/initiating-quick-assistance-on-windows-11/"><u>Initiating Quick Assistance on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insight-into-vcplusplus-redistributable-needs/"><u>Insight Into VC++ Redistributable Needs</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/leading-12-screen-recorders-no-time-limit-in-2024/"><u>Leading 12 Screen Recorders, No Time Limit, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-desktop-art-windows-1011-tutorials/"><u>Mastering Desktop Art: Windows 10/11 Tutorials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-fix-loaded-lol-screens/"><u>Mastering Windows: Fix Loaded LOL Screens</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/navigating-the-ups-and-downsides-of-webex-meetings-platform/"><u>Navigating the Ups and Downsides of WebEx Meetings Platform</u></a></li>
<li><a href="https://extra-support.techidaily.com/overview-of-magix-audio-enhancer-for-2024/"><u>Overview of MAGIX Audio Enhancer for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-windows-inbuilt-pdf-renderer/"><u>Personalizing Windows' Inbuilt PDF Renderer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/protecting-privacy-the-ultimate-windows-encryption-list-152-chars/"><u>Protecting Privacy: The Ultimate Window's Encryption List (152 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefine-the-point-of-interest-with-new-cursor-style/"><u>Redefine the Point of Interest with New Cursor Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-online-status-for-wow-gamers/"><u>Restoring Online Status for WoW Gamers</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/securing-your-games-in-motion-top-5-for-windows-10/"><u>Securing Your Games in Motion  Top 5 for Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sidestep-mobility-center-stay-in-full-screen/"><u>Sidestep Mobility Center, Stay In Full Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snapping-into-action-activate-snipping-tool-in-windows-11/"><u>Snapping Into Action: Activate Snipping Tool in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-dealing-with-immutable-energy-states-in-windows-11/"><u>Solutions for Dealing with Immutable Energy States in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-security-for-browsers-trustable-sites-in-windows-11/"><u>Tailored Security for Browsers: Trustable Sites in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tame-excessive-system-update-notifications-in-windows-11/"><u>Tame Excessive System Update Notifications in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tcp-port-identification-on-windows-devices/"><u>TCP Port Identification on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-fix-errors-with-windows-alt-codes/"><u>Techniques to Fix Errors with Windows ALT Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-unblock-overloaded-gpt-windows-errors/"><u>Tips to Unblock Overloaded GPT Windows Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-error-0x803f700f-in-windows-activation/"><u>Troubleshooting Error 0X803F700F in Windows Activation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-bar-icon-failures/"><u>Troubleshooting Windows Bar Icon Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tweaking-your-pcs-touchpad-response-speed/"><u>Tweaking Your PC's Touchpad Response Speed</u></a></li>
<li><a href="https://extra-information.techidaily.com/ultimate-guide-to-7-superior-vids-on-mac/"><u>Ultimate Guide to 7 Superior Vids on Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-code-0x80780119-restore-mishap/"><u>Unraveling Windows' Code 0X80780119 Restore Mishap</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-easter-eggstravaganza-get-your-wondershare-filmora-promo-code-now/"><u>Updated Easter Eggstravaganza Get Your Wondershare Filmora Promo Code Now</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-samsung-galaxy-s24-ultra-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Live Location is Not Updating and How to Fix on your Samsung Galaxy S24 Ultra | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-narrative-engagement-startup/"><u>Windows 11 Narrative Engagement Startup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-start-button-revived-an-instruction-guide/"><u>Windows Start Button Revived: An Instruction Guide</u></a></li>
</ul></div>
