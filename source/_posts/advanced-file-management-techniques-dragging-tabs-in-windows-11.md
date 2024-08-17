---
title: "Advanced File Management Techniques: Dragging Tabs in Windows 11"
date: 2024-08-16T01:06:55.860Z
updated: 2024-08-17T01:06:55.860Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Advanced File Management Techniques: Dragging Tabs in Windows 11"
excerpt: "This Article Describes Advanced File Management Techniques: Dragging Tabs in Windows 11"
keywords: Win11 FileDragTechnique,TabManagementWin11,AdvancedFileManageTabs,TechDragWindowsFiles,ManageDataWindowTab,FileOrganizingTools11,DragTabsEffectiveWin
thumbnail: https://thmb.techidaily.com/a691a544cb7cde4aeceab56e4cf68f393a99f1feb2da71ac3ca94b7300f4d4b3.jpg
---

## Advanced File Management Techniques: Dragging Tabs in Windows 11

 Microsoft added the much-awaited tabs feature in Windows File Explorer in 2022\. While it is not the best implementation we had hoped for, it certainly gets the job done. You don’t have to open separate File Explorer windows to access two different locations on the disk. But there is still a lot missing from the tabs feature; you cannot drag tabs out from a File Explorer window.

 This feature is available in many browsers, but Microsoft took notice and is now testing the file drag feature in Windows 11 Insider builds. Here’s how to enable the feature on your system.

## Is Dragging File Explorer Tabs Out Really That Useful?

 If you recall your experience with using a web browser, you know that using a split screen has its advantages. If you want to stack two tabs side by side, you can just open two browser tabs, drag one out, and use snap layouts to arrange them. It is very easy to drag out a tab in a browser, but that feature is missing in the current version of File Explorer.

![Dragging out tabs in Chrome Browser](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dragging-out-tabs-in-chrome-browser.jpg)

 So, you can have two file locations open in two separate tabs in File Explorer. But if you have to stack them side by side, there is no such option. You will have to close one tab (if you like) and open another instance of File Explorer and then use the split-screen layout.

 Thankfully, the latest Insider build 25290 has a hidden feature that makes it possible to drag out tabs.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
## How to Enable the Drag-Out Feature in File Explorer

 This feature is exclusive to Windows 11 Insider builds and is in the testing phase. So, you will have to download and install the build version 25290 and then use the ViveTool to enable the feature.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
### 1\. Update to the Latest Insider Build

 To update to the latest insider build, head over to the Settings page and [check for Windows updates](https://www.makeuseof.com/tag/update-windows-software-guide/) . After that, install the latest 25920 build or newer on your system. You will have to restart your system for the changes to take effect.

 If you haven’t enrolled in the Windows Insider program and still want to try out this new feature, take the help of UUP Dump. You can easily [download the latest Windows Insider builds using UUP Dump](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) . Install the build and then proceed to the next step.

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Enable the Feature Using ViveTool

 Now, you have the Insider build running on your system. You will have to use the ViveTool to enable the hidden experimental feature to drag tabs out of the File Explorer. But first,[download ViveTool from GitHub](https://github.com/thebookisclosed/ViVe/releases) and install the ViveTool on your system. After that, repeat the following steps:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) on your system.
2. Type**cmd** in the text input area and then press**Ctrl + Shift + Enter** key to launch the command prompt with admin privileges.
3. Now, locate the ViveTool directory using the**cd** command. We placed the ViveTool in a folder named Vive on C drive, So the command to change to that directory will be**cd\\** .
4. Once you are in the C directory, type**cd Vive** and press the**Enter** key.
5. After that, type**vivetool /enable /id:39661369** command and press the**Enter** key.  
![Enabling Tabs Dragging Feature In File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enabling-tabs-dragging-feature-in-file-explorer.jpg)
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. **Exit** the command prompt window after the ViveTool command executes successfully.
7. Restart your system to apply the changes.
8. Log into Windows and press**Win + E** to launch File Explorer. Now, open two tabs and click and hold on any of the open tabs.  
![Tabs Dragging Feature in Action in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tabs-dragging-feature-in-action-in-file-explorer.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->
9. Try to drag the tabs out of File Explorer. It will open in a second window. You can stack them on each side if you like.

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Can You Restore the Tab to the File Explorer Window?

 Yes, you can indeed restore the dragged tab back to a File Explorer window. But the process is very clunky. You have to drag and hold the tab onto another open tab in a different File Explorer window.

 If you aren’t able to accurately position the tab, it will not merge with the File Explorer tab bar. In Chrome browser, dragging out and restoring them to the same window is pretty easy. You can even hover the tab and position it between two open tabs.

## Drag Tabs Out Like a Pro in File Explorer

 Microsoft is trying to make File Explorer more useful. But we cannot expect File Explorer to exactly work like a browser. After, it happens to be a means to access different types of files and open them with a compatible app or program in a new window. Still, dragging tabs out is a slick feature, and we hope Microsoft fixes the kinks and adds it in future updates.


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
<li><a href="https://youtube-clips.techidaily.com/new-crafting-engaging-youtube-videos-using-finalcut-pro-expertise/"><u>[New] Crafting Engaging YouTube Videos Using FinalCut Pro Expertise</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-mastering-media-management-on-instagram/"><u>[New] In 2024, Mastering Media Management on Instagram</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-investigating-unmodified-audio-from-ffmpeg-output/"><u>[New] Investigating Unmodified Audio From FFmpeg Output</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-ios-leading-psp-emulators-five-star-selections/"><u>[New] IOS Leading PSP Emulators  Five Star Selections</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-how-to-host-a-webinar-on-youtube-for-free-for-2024/"><u>[Updated] How to Host a Webinar on YouTube for Free for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-proven-methods-for-twitter-brand-awareness/"><u>[Updated] Proven Methods for Twitter Brand Awareness</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-10-youtube-havens-for-entrepreneurs-and-business-gurus/"><u>2024 Approved  10 YouTube Havens for Entrepreneurs & Business Gurus</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-effortless-repetition-replay-your-youtube-videos-via-tv-connection/"><u>2024 Approved  Effortless Repetition  Replay Your YouTube Videos via TV Connection</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-in-depth-review-is-aurora-revolutionary/"><u>2024 Approved  In-Depth Review  Is Aurora Revolutionary?</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-the-essentials-for-seamless-system-evolutions/"><u>2024 Approved  The Essentials for Seamless System Evolutions</u></a></li>
<li><a href="https://extra-tips.techidaily.com/a-deep-dive-into-cutting-edge-vr-technology-for-2024/"><u>A Deep Dive Into Cutting-Edge VR Technology for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-the-noise-wake-on-idle-restarts-in-w10w11/"><u>Cutting the Noise: Wake on Idle Restarts in W10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-and-rectifying-windows-steam-e84-problems/"><u>Decoding and Rectifying Windows Steam E84 Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-system-unveiling-best-apps-of-the-year/"><u>Elevate Your System: Unveiling Best Apps of the Year</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exposing-windows-11s-data-collection-strategies/"><u>Exposing Windows 11'S Data Collection Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-selecthighlight-issues-in-pdfs-on-windows-pcs/"><u>Fix Select/Highlight Issues in PDFs on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-steam-folder-permissions-on-windows-11/"><u>Fixing Steam Folder Permissions on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-service-did-not-respond-errors-a-compreranble-solution/"><u>Fixing Windows Service Did Not Respond Errors: A Compreranble Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-correct-procedure-calls-failure-in-malwarebytes-on-win10win11/"><u>How to Correct Procedure Calls Failure in Malwarebytes on Win10/Win11</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-8-to-the-previous-ios-system-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 8 to the Previous iOS System Version? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-oppo-reno-11f-5g-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your Oppo Reno 11F 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tackle-file-corruption-problems-error-0x80070570-on-windows-11/"><u>How to Tackle File Corruption Problems (Error 0X80070570) on Windows 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-infinix-smart-8-pro-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>How to Unlock Infinix Smart 8 Pro Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-oppo-reno-10-pro-5g-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Oppo Reno 10 Pro 5G to New Android? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-set-your-preferred-job-location-on-linkedin-app-of-your-apple-iphone-11-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, Set Your Preferred Job Location on LinkedIn App of your Apple iPhone 11 Pro Max | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-understanding-and-applying-luts-to-ae-projects/"><u>In 2024, Understanding and Applying LUTs to AE Projects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insights-into-artificial-intelligence-computers-uniqueness/"><u>Insights Into Artificial Intelligence Computers' Uniqueness</u></a></li>
<li><a href="https://win-blog.techidaily.com/mastering-stability-resolving-constant-collapses-in-pc-version-of-tower-of-fantasy/"><u>Mastering Stability: Resolving Constant Collapses in PC Version of Tower of Fantasy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-microsofts-xbox-sound-setup/"><u>Optimizing Microsoft's Xbox Sound Setup</u></a></li>
<li><a href="https://program-issues.techidaily.com/outlook-wont-connect-fix-it-now-with-these-expert-tips/"><u>Outlook Won't Connect? Fix It Now with These Expert Tips!</u></a></li>
<li><a href="https://win-solutions.techidaily.com/1723007221983-play-the-exciting-days-gone-first-person-shooter-on-your-personal-computer/"><u>Play the Exciting 'Days Gone' First-Person Shooter on Your Personal Computer!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preempt-potential-problems-installing-virtualbox-on-win-with-care/"><u>Preempt Potential Problems: Installing VirtualBox on Win with Care</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-methods-to-fix-file-or-directory-is-corrupt-error-x70-in-windows/"><u>Proven Methods To Fix 'File or Directory Is Corrupt' Error X70 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-rectify-0x80072af9-on-windows-os/"><u>Quick Guide to Rectify 0X80072AF9 on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-working-activation-numbers-in-win11/"><u>Reinstating Working Activation Numbers in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedies-for-black-screen-crisis-in-win-based-playing/"><u>Remedies for Black Screen Crisis in Win-Based Playing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-sign-out-error-caused-by-intrusive-windows-software/"><u>Resolving Sign Out Error Caused by Intrusive Windows Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-your-win1011s-recycle-bin-with-these-fixes/"><u>Revive Your WIN10/11's Recycle Bin with These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sky-high-output-with-these-top-7-masterful-win-11-widgets/"><u>Sky-High Output with These Top 7 Masterful Win 11 Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stealthy-apps-in-disguise-hurt-your-windows-11-performance/"><u>Stealthy Apps in Disguise Hurt Your Windows 11 Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-language-barriers-use-windows-hotkeys-for-translation/"><u>Streamline Language Barriers: Use Windows Hotkeys for Translation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-data-exchange-with-python-and-windows-server/"><u>Streamlining Data Exchange with Python and Windows Server</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-action-for-spotify-error-4-windows-11-fixes/"><u>Swift Action for Spotify Error 4: Windows 11 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solution-for-handling-windows-update-failures-and-errors-0x80070003/"><u>Swift Solution for Handling Windows Update Failures & Errors: 0X80070003</u></a></li>
<li><a href="https://screen-capture.techidaily.com/tackling-frame-rate-glitches-in-obs-outputs/"><u>Tackling Frame Rate Glitches in OBS Outputs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-windows-media-creation-tool-error-x90017/"><u>Unblocking Windows' Media Creation Tool Error X.90017</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-cdrive-and-ddrive-distinctions/"><u>Understanding C:Drive & D:Drive Distinctions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-importance-of-winservicesexe/"><u>Understanding the Importance of WinServices.exe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-fuller-sounds-4-tools-to-exceed-windows-limit/"><u>Unleash Fuller Sounds: 4 Tools to Exceed Windows' Limit</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-how-to-translate-videos-in-tamil-for-a-wider-reach-for-2024/"><u>Updated How To Translate Videos in Tamil for a Wider Reach for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-walks-unlocking-your-gaming-archives/"><u>Windows Walks: Unlocking Your Gaming Archives</u></a></li>
</ul></div>
