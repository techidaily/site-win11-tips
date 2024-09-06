---
title: How to Engage Clipboard Utility Within Microsoft Edge's App Guard for Windows 11
date: 2024-09-05T19:34:03.023Z
updated: 2024-09-06T19:34:03.023Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Engage Clipboard Utility Within Microsoft Edge's App Guard for Windows 11
excerpt: This Article Describes How to Engage Clipboard Utility Within Microsoft Edge's App Guard for Windows 11
keywords: Edge App Guard Tips,Windows 11 Security,Clipboard Usage,Edge App Guards,Utility Engagement,Microsoft Protection,Secure Data Transfer
thumbnail: https://thmb.techidaily.com/fea6185edc685da72ba963a46eed57a3a71d461697393364ab3bd89b9977de72.jpg
---

## How to Engage Clipboard Utility Within Microsoft Edge's App Guard for Windows 11

 Looking to improve the security of your device? Microsoft Edge's Application Guard feature is an ideal solution, as it creates a virtualized atmosphere and blocks malicious websites. However, copy and paste functionality is disabled by default in this setting for extra precautionary measures.

 If you would like to switch on copy and paste within Application Guard for Edge on Windows 11, then this guide will assist you in doing so.

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
<a href="https://bluettius.sjv.io/c/5597632/2139114/17108" target="_top" id="2139114">
  <img src="//a.impactradius-go.com/display-ad/17108-2139114" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139114/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Enable Copy and Paste via Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-via-windows-settings.jpg)
7. The UAC prompt will appear on the screen. Click**Yes** to continue.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135364/19272" target="_top" id="2135364">
  <img src="//a.impactradius-go.com/display-ad/19272-2135364" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135364/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you’ve completed the steps, restart your computer for the changes to work. Now, you can securely transfer data between a virtualized environment and your device without any worries about security risks - malicious websites and applications will be blocked even with this setting enabled.

 If you ever need to disable copy and paste in Application Guard for Edge, you can follow the same steps mentioned above. Just be sure to toggle off the Copy and Paste setting from the Isolated browsing menu instead.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130891/7443" target="_top" id="2130891">
  <img src="//a.impactradius-go.com/display-ad/7443-2130891" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130891/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2123727/7443" target="_top" id="2123727">
  <img src="//a.impactradius-go.com/display-ad/7443-2123727" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123727/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
6. Finally, click**OK** to save your changes.
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136620/26400" target="_top" id="2136620">
  <img src="//a.impactradius-go.com/display-ad/26400-2136620" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136620/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137208/26400" target="_top" id="2137208">
  <img src="//a.impactradius-go.com/display-ad/26400-2137208" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137208/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-captivate-audiences-with-perfectly-tailored-youtube-descriptions/"><u>[New] 2024 Approved Captivate Audiences with Perfectly Tailored Youtube Descriptions</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-link-up-titles-video-upload-to-twittertumblr/"><u>[New] In 2024, Link-Up Titles Video Upload to Twitter/Tumblr</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-sim-inspired-memories-a-comprehensive-guide-to-capturing-life-events-with-gameplay-recordings/"><u>[New] In 2024, Sim-Inspired Memories A Comprehensive Guide to Capturing Life Events with Gameplay Recordings</u></a></li>
<li><a href="https://youtube-web.techidaily.com/apping-into-youtubes-earnings-how-much-do-you-make-from-adsense-per-kv/"><u>[New] Tapping Into Youtube's Earnings How Much Do You Make From AdSense Per KV?</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-11-easy-to-produce-vlog-projects-at-home/"><u>[Updated] 2024 Approved 11 Easy-to-Produce Vlog Projects at Home</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-top-choreographers-for-visual-and-auditory-crafting/"><u>[Updated] In 2024, Top Choreographers for Visual & Auditory Crafting</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-streamline-your-media-experience-with-pip-in-safari-for-2024/"><u>[Updated] Streamline Your Media Experience with PIP in Safari for 2024</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/2024-approved-dynamic-sound-design-modifying-audio-velocity-and-frequency-in-adobe-rush/"><u>2024 Approved Dynamic Sound Design Modifying Audio Velocity & Frequency in Adobe Rush</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-framed-perfection-websites-and-apps-to-elevate-your-images/"><u>2024 Approved Framed Perfection Websites and Apps to Elevate Your Images</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-personal-narratives-for-online-connection-and-growth/"><u>2024 Approved Personal Narratives for Online Connection and Growth</u></a></li>
<li><a href="https://solve-popular.techidaily.com/abbyy-dominates-2022-spark-matrix-rankings-by-quadrant-knowledge-solutions-for-advanced-document-analysis/"><u>ABBYY Dominates 2022 SPARK Matrix Rankings by Quadrant Knowledge Solutions for Advanced Document Analysis</u></a></li>
<li><a href="https://media-tips.techidaily.com/comprehensive-guide-expanding-youtubes-consistent-sound-balance-across-multiple-gadgets/"><u>Comprehensive Guide: Expanding YouTube's Consistent Sound Balance Across Multiple Gadgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/core-functionality-within-vcplusplus-releases/"><u>Core Functionality Within VC++ Releases</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-windows-layouts-with-a-macos-vibe-using-these-5-techniques/"><u>Crafting Windows Layouts with a MacOS Vibe Using These 5 Techniques</u></a></li>
<li><a href="https://extra-resources.techidaily.com/cutting-edge-meme-creation-app/"><u>Cutting-Edge Meme Creation App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decode-your-pc-secrets-of-finding-windows-1011-keys/"><u>Decode Your PC: Secrets of Finding Windows 10/11 Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-ai-systems-their-uniqueness/"><u>Decoding AI Systems: Their Uniqueness</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-not-supported-errors-in-windows-a-quick-guide/"><u>Eliminate 'Not Supported' Errors in Windows: A Quick Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/end-the-frustration-of-non-scrolling-cells-ranges-and-sheets-excel-36516/"><u>End the Frustration of Non-Scrolling Cells, Ranges, and Sheets (Excel 365/16)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-words-in-a-flash-windows-11-definiton-hub/"><u>Explore Words in a Flash - Windows 11 Definiton Hub</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-system-call-issues-on-windows-11-and-11/"><u>Fixing System Call Issues on Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gaining-insight-into-your-gpus-potential-using-these-6-essential-windows-apps/"><u>Gaining Insight Into Your GPU's Potential Using These 6 Essential Windows Apps</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/guide-to-adding-dynamic-captions-to-instagram-media/"><u>Guide to Adding Dynamic Captions to Instagram Media</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-through-keyboard-driven-program-resizing-for-windows-11/"><u>Guiding Through Keyboard-Driven Program Resizing for Windows 11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-gps-location-on-poco-c55-easily-and-safely-drfone-by-drfone-virtual-android/"><u>How to Change GPS Location on Poco C55 Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-correct-the-incorrect-tags-in-onedrives-reparse-buffer/"><u>How to Correct the Incorrect Tags in OneDrive’s Reparse Buffer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-get-the-best-macos-features-with-windows-apps/"><u>How to Get the Best macOS Features With Windows Apps</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-iphone-11-pro-max-drfone-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 11 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-motorola-edge-40-pro-phone-without-password-by-drfone-android/"><u>In 2024, How To Unlock Motorola Edge 40 Pro Phone Without Password?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-xiaomi-redmi-note-12-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Xiaomi Redmi Note 12 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-methods-to-change-gps-location-on-honor-magic-vs-2-drfone-by-drfone-virtual-android/"><u>In 2024, Methods to Change GPS Location On Honor Magic Vs 2 | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-15-apps-to-hack-wifi-password-on-vivo-v30-pro-by-drfone-android/"><u>In 2024, Top 15 Apps To Hack WiFi Password On Vivo V30 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/incorporating-update-info-into-right-click-context-menu/"><u>Incorporating Update Info Into Right-Click Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/increasing-yuzu-response-time-on-windows/"><u>Increasing Yuzu Response Time on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-system-support-setting-up-custom-hotkeys-for-windows-fixes/"><u>Instant System Support: Setting Up Custom Hotkeys for Windows Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstart-your-valorant-pace-on-windows-pc/"><u>Jumpstart Your Valorant Pace on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-error-correction-0x0000004e-in-windows/"><u>Mastering Error Correction: 0X0000004E in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-running-cmd-with-elevated-rights/"><u>Mastering Windows: Running CMD with Elevated Rights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/msvcr110dll-missing-understanding-and-resolution/"><u>MSVCR110.dll Missing: Understanding & Resolution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-admin-command-challenges-in-windows/"><u>Navigating Admin Command Challenges in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-non-working-windows-alt-codes-51-characters/"><u>Navigating Non-Working Windows ALT Codes (51 Characters)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-windows-11s-past-text-recall-capabilities/"><u>Optimizing Windows 11'S Past Text Recall Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/post-update-anomalies-restoring-your-discord-on-windows/"><u>Post-Update Anomalies: Restoring Your Discord On Windows</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/-youtube-snippets-explained-simply/"><u>Quick YouTube Snippets Explained Simply</u></a></li>
<li><a href="https://extra-hints.techidaily.com/revolutionize-video-crafting-mastering-the-integration-of-windows-11-and-storyremix/"><u>Revolutionize Video Crafting Mastering the Integration of Windows 11 & StoryRemix</u></a></li>
<li><a href="https://extra-hints.techidaily.com/select-your-perfect-outro-soundtrack-online-for-free/"><u>Select Your Perfect Outro Soundtrack Online For Free</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocketing-download-speeds-preventing-steam-slowdowns/"><u>Skyrocketing Download Speeds: Preventing Steam Slowdowns</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/solutions-for-playback-problems-with-paramount-channel-on-roku-firestick/"><u>Solutions for Playback Problems with Paramount Channel on Roku Firestick</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-yellow-screen-problem-windows-display-correction-tips/"><u>Solving Yellow Screen Problem: Windows Display Correction Tips</u></a></li>
<li><a href="https://extra-skills.techidaily.com/srt-fundamentals-explored-in-detail-and-clarity-for-2024/"><u>SRT Fundamentals Explored in Detail and Clarity for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/surviving-youtubes-copyright-enforcement-hurdles-for-2024/"><u>Surviving YouTube's Copyright Enforcement Hurdles for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/synchronize-effortlessly-utilizing-one-phone-number-on-various-mobile-and-smart-devices/"><u>Synchronize Effortlessly: Utilizing One Phone Number on Various Mobile and Smart Devices</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-easy-way-to-retain-and-transfer-your-chatgpt-engagements/"><u>The Easy Way to Retain and Transfer Your ChatGPT Engagements</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/thrilling-timeline-how-to-systematically-savor-every-classic-and-new-release-of-the-james-bond-saga/"><u>Thrilling Timeline: How to Systematically Savor Every Classic and New Release of the James Bond Saga</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-5-methods-verifying-windows-11-devices-availability/"><u>Top 5 Methods: Verifying Windows 11 Devices' Availability</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/forming-skincare-secrets-into-social-stardom-for-2024/"><u>Transforming Skincare Secrets Into Social Stardom for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-blue-screen-dumps-a-comprehensible-guide/"><u>Understanding Blue Screen Dumps: A Comprehensible Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unravel-windows-user-entry-attempts-successes-and-setbacks/"><u>Unravel Windows User Entry Attempts: Successes and Setbacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-how-to-prioritize-taskmanager/"><u>Unveiling How to Prioritize TaskManager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-home-vs-pro-which-is-best-for-you/"><u>Windows 11 Home Vs. Pro: Which Is Best for You?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-hello-fingerprint-login-configuration-guide/"><u>Windows Hello Fingerprint Login Configuration Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-strategies-unzipping-multiple-files-simultaneously/"><u>Windows Strategies: Unzipping Multiple Files Simultaneously</u></a></li>
</ul></div>
