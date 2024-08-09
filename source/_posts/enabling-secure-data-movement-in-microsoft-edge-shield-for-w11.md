---
title: Enabling Secure Data Movement in Microsoft Edge Shield for W11
date: 2024-08-08T11:05:49.332Z
updated: 2024-08-09T11:05:49.332Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enabling Secure Data Movement in Microsoft Edge Shield for W11
excerpt: This Article Describes Enabling Secure Data Movement in Microsoft Edge Shield for W11
keywords: Edge Security Shielding,MS Edge Privacy Advance,Safe Data Transfer Edge,Protective Edge W11,Secure Data Edge Move,Microsoft Edge Shield,Edge Data Safeguard
thumbnail: https://thmb.techidaily.com/23dc4857279699198e48a622a7713386fd30f7f47908caf6a0fe50229057f885.jpg
---

## Enabling Secure Data Movement in Microsoft Edge Shield for W11

 Looking to improve the security of your device? Microsoft Edge's Application Guard feature is an ideal solution, as it creates a virtualized atmosphere and blocks malicious websites. However, copy and paste functionality is disabled by default in this setting for extra precautionary measures.

 If you would like to switch on copy and paste within Application Guard for Edge on Windows 11, then this guide will assist you in doing so.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. How to Enable Copy and Paste via Windows Settings

 To enable copy and paste in Application Guard for Edge, follow the steps below:

1. Right-click on Start and select**Settings** from the menu list. For more information, check out our guide on[how to open the Settings window](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Privacy & security** from the left pane.
3. Then click the**Windows Security** option on the right-hand side.
4. On the following screen, select**App & browser control** .
5. Go to the Isolated browsing section and click the link "Change Applications Guard settings."  
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Change Application Guard Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-application-guard-settings.jpg)
6. Search for the**Copy and paste** option, then click the toggle to enable it.  
![Enable Copy and Paste via Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-via-windows-settings.jpg)
7. The UAC prompt will appear on the screen. Click**Yes** to continue.

 Once you’ve completed the steps, restart your computer for the changes to work. Now, you can securely transfer data between a virtualized environment and your device without any worries about security risks - malicious websites and applications will be blocked even with this setting enabled.

 If you ever need to disable copy and paste in Application Guard for Edge, you can follow the same steps mentioned above. Just be sure to toggle off the Copy and Paste setting from the Isolated browsing menu instead.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
![Creating a new DWORD (32-bit) Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-dword-enableclipboard-key.jpg)
3. Put**EnableClipboard** as the name for the new DWORD key, then press Enter.
4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
6. Finally, click**OK** to save your changes.

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-video-recordings.techidaily.com/new-enhancing-beauty-on-streams-via-color-grading/"><u>[New] Enhancing Beauty on Streams via Color Grading</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-file-funneling-features-5-techniques-to-desktops/"><u>[New] File Funneling Features  5 Techniques to Desktops</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-depth-and-design-text-in-three-dimensions/"><u>[New] In 2024, Depth and Design  Text in Three-Dimensions</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-mycam-reviewed-how-it-meets-expectations-for-home-recorders/"><u>[New] MyCam Reviewed  How It Meets Expectations for Home Recorders</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-the-quintessential-toptiktok-tweets-in-popularity-for-2024/"><u>[New] The Quintessential #TopTikTok Tweets in Popularity for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-essential-gear-for-capturing-skisnowboarding-moments/"><u>[Updated] In 2024, Essential Gear for Capturing Ski/Snowboarding Moments</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-from-aspect-ratio-woes-to-winning-instagram-square-video/"><u>[Updated] In 2024, From Aspect Ratio Woes to Winning Instagram Square Video</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-capture-attention-top-10-grids-for-stunning-pics/"><u>2024 Approved  Capture Attention  Top 10 Grids for Stunning Pics</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-game-masters-and-youtube-earning-strategies/"><u>2024 Approved  Game Masters & YouTube Earning Strategies</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-legendary-loops-leading-10-rogues/"><u>2024 Approved  Legendary Loops  Leading 10 Rogues</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-professional-post-processing-how-to-erase-image-borders-easily/"><u>2024 Approved  Professional Post-Processing  How to Erase Image Borders Easily</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-step-by-step-guide-embellishing-images-with-borders-on-instagram/"><u>2024 Approved  Step-by-Step Guide  Embellishing Images with Borders on Instagram</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-transform-your-video-chats-using-zooms-filters/"><u>2024 Approved  Transform Your Video Chats Using Zoom's Filters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-fix-the-no-such-interface-supported-error-in-windows/"><u>5 Ways to Fix the No Such Interface Supported Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-fix-the-secure-boot-state-unsupported-error-in-windows/"><u>5 Ways to Fix the Secure Boot State Unsupported Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-correcting-entry-not-found-message/"><u>A Guide to Correcting 'Entry Not Found' Message</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-approach-to-probing-program-hideouts-in-windows/"><u>A Practical Approach to Probing Program Hideouts in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-new-windows-pin/"><u>A Step-by-Step Approach to New Windows PIN</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-d-drive-folder-in-windows-explorer/"><u>Accessing D: Drive Folder in Windows Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-folder-and-file-unity-a-windows-exploration/"><u>Achieving Folder & File Unity: A Windows Exploration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-fingerprint-authentication-in-windows-11/"><u>Activating Fingerprint Authentication in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-blank-screens-on-system-ignition/"><u>Addressing Blank Screens on System Ignition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-faulty-volume-adjustment-sliders/"><u>Addressing Faulty Volume Adjustment Sliders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-frozen-windows-guard-in-windows-11/"><u>Addressing Frozen Windows Guard in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-absentee-tab-button-on-your-pc/"><u>Addressing the Absentee Tab Button on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplifying-windows-protection-integrating-additional-firewall-settings-into-context-menu/"><u>Amplifying Windows Protection: Integrating Additional Firewall Settings Into Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/approaches-to-address-roblox-glitches/"><u>Approaches to Address Roblox Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automate-the-journey-always-command-prompt-admin-style/"><u>Automate the Journey: Always Command Prompt, Admin Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-frustration-easily-setup-icloud-on-windows-pc/"><u>Avoid Frustration: Easily Setup iCloud on Windows PC</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/best-poco-c50-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>Best Poco C50 Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-steam-downloads-combatting-speedy-slowdowns/"><u>Boosting Steam Downloads: Combatting Speedy Slowdowns</u></a></li>
<li><a href="https://extra-tips.techidaily.com/comparing-vr-to-360-degree-video-whats-the-distinction-for-2024/"><u>Comparing VR to 360-Degree Video  What's the Distinction for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/from-full-size-photos-to-miniature-expert-thumbnail-crafting/"><u>From Full-Size Photos to Miniature  Expert Thumbnail Crafting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719274715388-how-to-organize-your-notes-visually-with-obsidian-canvas/"><u>How to Organize Your Notes Visually with Obsidian Canvas</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-exploring-audio-resources-for-video-game-creators/"><u>New In 2024, Exploring Audio Resources for Video Game Creators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719205412582-shed-light-on-dark-windows-11-desktops-tips-inside/"><u>Shed Light on Dark Windows 11 Desktops - Tips Inside</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-correcting-missing-or-damaged-physxloaderdll/"><u>Step-by-Step Guide: Correcting Missing or Damaged 'PhysXLoader.dll'</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/streamlined-video-conferencing-utilizing-the-power-of-zoom-in-win10/"><u>Streamlined Video Conferencing  Utilizing the Power of Zoom in Win10</u></a></li>
<li><a href="https://techidaily.com/will-mov-files-play-on-galaxy-f15-5g-by-aiseesoft-video-converter-play-mov-on-android/"><u>Will MOV files play on Galaxy F15 5G ?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719334255604-win11-chrome-issues-jumpstart-solution-suggestions/"><u>Win11 Chrome Issues? Jumpstart Solution Suggestions</u></a></li>
</ul></div>
