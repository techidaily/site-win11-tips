---
title: Breaking Free From File Read-Only Status on PC
date: 2024-07-29T08:12:13.645Z
updated: 2024-07-30T08:12:13.645Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Breaking Free From File Read-Only Status on PC
excerpt: This Article Describes Breaking Free From File Read-Only Status on PC
keywords: Unlock PC Files,Overcome Read-Only,Remove Read-Lock,Delete Read-Only,Erase Locked Files,Free File Access,Disable Read-Lock
thumbnail: https://thmb.techidaily.com/af6a241ce73781e980e91fb32b5f340b0c43ca449b76945212041b79725c225d.jpg
---

## Breaking Free From File Read-Only Status on PC

 When a file is marked as read-only on Windows, you can only view it and not change it in any way. This essentially protects important files from unauthorized changes.

 On Windows, you can set or remove the read-only attribute for a file by modifying its properties. Alternatively, you can also run a command in Command Prompt or Windows PowerShell to do the same. In this article, we take a look at all of them.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. How to Change the Read-Only Attribute for Files by Modifying Properties

 The easiest way to set or remove the read-only attribute for a file on Windows is by modifying its properties. Here’s how you can go about it.

1. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the file for which you want to change the read-only attribute.
2. Right-click on your file and select**Properties** .
3. Under the**General** tab, check or uncheck the**Read-only** box.
4. Click**Apply** followed by**OK** .  
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
![Change Read-Only Attribute by Modifying Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-by-Modifying-Properties.jpg)

 Note that Windows may prevent you from changing the read-only attribute of a file if you don’t have the necessary permissions to modify the folder in which the file is located. In that case, you must take ownership of the folder first. If you need help, check our guide on[how to take ownership of folders on Windows](<http://How> to Take Ownership of Folders in Windows 10 & 11) .

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to Change the Read-Only Attribute for Files Using the Command Prompt

 Command Prompt is one of two command-line tools available on Windows. You can use it to run batch files, troubleshoot errors, and perform various other tasks. It also lets you change a file's read-only attribute with a single command. Here are the steps you need to follow.

1. Right-click on the file for which you want to modify the read-only attribute and select**Copy as path** .
2. Press**Win + X** to open the Power User menu.
3. Select**Terminal (Admin)** from the list.
4. Select**Yes** when the User Account Control (UAC) prompt appears.
5. In the console, type the following command and press**Enter** to set your file as read-only.  
`attrib +r "FilePath"`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Change Read-Only Attribute With Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-Command-Prompt.jpg)

 Once you run the above command, the file will be set as read-only. Likewise, if you want to remove the read-only attribute for a file, use this command:

`attrib -r "FilePath"`

 Once you remove the read-only attribute for a file, you should be able to edit or modify it.

 Like using Command Prompt? Check our guide to learn[how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

## 3\. How to Change the Read-Only Attribute for Files Using Windows PowerShell

 You can also run a command in[Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) to change the read-only attribute for a file.

To change the read-only attribute using PowerShell:

1. Right-click on the file for which you want to change the read-only attribute and select**Copy as path** .
2. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
3. Type**Windows PowerShell** and select**Run as Administrator** .
4. Select**Yes** when the User Account Control (UAC) prompt shows up.
5. Paste the following command and press**Enter** to set your file as read-only.  
`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $True`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
![Change Read-Only Attribute With PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-PowerShell.jpg)

 Alternatively, if you want to remove the read-only attribute for a file, use this command:

`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $False`

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
## Modifying the Read-Only Attribute for Files on Windows

 It’s worth noting that most system files on Windows will have the read-only attribute by default. So, make sure you don't modify them by mistake. For your other files, you can pick any of the above methods listed above to set or unset their read-only attribute.

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
<li><a href="https://extra-hints.techidaily.com/new-20-high-end-editors-for-dji-drone-footage/"><u>[New] 20 High-End Editors for DJi Drone Footage</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-cutting-edge-techniques-for-backdrop-acquisition/"><u>[New] 2024 Approved  Cutting-Edge Techniques for Backdrop Acquisition</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-horizon-captured-which-camera-takes-the-lead/"><u>[New] Horizon Captured  Which Camera Takes the Lead?</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-mac-audio-tools-for-effective-classroom-capture/"><u>[New] Mac Audio Tools for Effective Classroom Capture</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-pro-video-creators-choice-10-exceptional-photo-background-alternators/"><u>[New] Pro Video Creators' Choice  10 Exceptional Photo-Background Alternators</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-revolutionizing-the-music-creation-process-through-magix-mentor-x/"><u>[New] Revolutionizing the Music Creation Process Through Magix Mentor X</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-blitz-30-second-guide-to-fast-thumbnails/"><u>[Updated] Blitz  30-Second Guide to Fast Thumbnails</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-integrating-obs-in-daily-skype-monitoring-for-2024/"><u>[Updated] Integrating OBS in Daily Skype Monitoring for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-learn-to-turn-videos-on-the-fly-using-vlc-for-2024/"><u>[Updated] Learn to Turn Videos on the Fly Using VLC for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-master-your-subtitles-with-top-10-free-converter-websites/"><u>[Updated] Master Your Subtitles with Top 10 Free Converter Websites</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-streamlining-the-experience-accessing-facebooks-video-features-through-apple-tv/"><u>[Updated] Streamlining the Experience  Accessing Facebook's Video Features Through Apple TV</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-chrome-crashes-or-wont-open-on-tecno-phantom-v-flip-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Chrome Crashes or Wont Open on Tecno Phantom V Flip | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-steps-to-tame-the-gpu-hungry-desktop-window-manager/"><u>7 Steps to Tame the GPU-Hungry Desktop Window Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-fixing-no-write-saves-winos/"><u>A Step-by-Step Guide to Fixing No Write Saves, WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-lately-used-files-in-windows/"><u>A Step-by-Step Guide to Lately Used Files in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-windows-in-minutes-with-handy-shorthand/"><u>Ace Windows in Minutes with Handy Shorthand</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-themed-settings-for-education-on-windows-11/"><u>Activating Themed Settings for Education on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-windows-11-privileges-and-permissions-panel/"><u>Activating Windows 11 Privileges and Permissions Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activation-essentials-making-most-of-win11s-widget-bar/"><u>Activation Essentials: Making Most of Win11's Widget Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-disabled-volume-shadow-copy-on-pcs/"><u>Addressing Disabled Volume Shadow Copy on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-empty-pages-in-the-explorer-bar/"><u>Addressing Empty Pages in the Explorer Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-inaccessible-values-in-windows-applications/"><u>Addressing Inaccessible Values in Windows Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-touch-keyboard-default-in-windows-11-pro/"><u>Adjust Touch Keyboard Default in Windows 11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplifying-ram-with-advanced-virtual-memory-settings/"><u>Amplifying RAM with Advanced Virtual Memory Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-the-impact-of-audio-device-isolation/"><u>Analyzing the Impact of Audio Device Isolation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/apps-masked-in-simplicity-secretly-slowing-down-your-system/"><u>Apps Masked in Simplicity: Secretly Slowing Down Your System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/artists-rejoice-best-windows-11-drawing-apps/"><u>Artists Rejoice: Best Windows 11 Drawing Apps</u></a></li>
<li><a href="https://extra-tips.techidaily.com/audacitys-guide-to-fading-sounds-invisibly-for-2024/"><u>Audacity's Guide to Fading Sounds Invisibly for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719315730924-avoid-frustration-fixing-the-missing-print-feature-on-windows/"><u>Avoid Frustration: Fixing the Missing Print Feature on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-wows-endless-loop-fix-error-132-in-win-editions/"><u>Avoid WoW's Endless Loop: Fix Error 132 in Win Editions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-common-pitfalls-of-roblox-error-262/"><u>Avoiding Common Pitfalls of Roblox Error 262</u></a></li>
<li><a href="https://win11-tips.techidaily.com/awaken-your-pc-to-god-like-powers-with-windows-11/"><u>Awaken Your PC to God-Like Powers with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-act-fixing-irq-for-clear-audio/"><u>Balancing Act: Fixing IRQ for Clear Audio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-security-and-usability-user-access-levels-on-windows/"><u>Balancing Security & Usability: User Access Levels on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-windows-11-highlighted-icons-for-tidy-desktop/"><u>Banish Windows 11 Highlighted Icons for Tidy Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/battery-saver-mastery-on-windows-laptops-essential-tips/"><u>Battery Saver Mastery on Windows Laptops - Essential Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-practices-for-eluding-windows-11-explorer-errors/"><u>Best Practices for Eluding Windows 11 Explorer Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blend-audio-and-video-recording-on-windows-11s-snipping-tool-max-156/"><u>Blend Audio and Video Recording on Windows 11'S Snipping Tool (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-speed-typing-aids-unleashed/"><u>Boost Your Speed: Typing Aids Unleashed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-usability-of-legacy-systems-for-seniors/"><u>Boosting Usability of Legacy Systems for Seniors</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-delete-icloud-account-on-iphone-7-without-password-by-drfone-ios/"><u>How to Delete iCloud Account On iPhone 7 without Password?</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-open-your-iphone-11-without-a-home-button-drfone-by-drfone-ios/"><u>How To Open Your iPhone 11 Without a Home Button | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-contacts-from-samsung-galaxy-f34-5g-by-fonelab-android-recover-contacts/"><u>How to recover deleted contacts from Samsung Galaxy F34 5G.</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-4-ways-to-transfer-music-from-apple-iphone-xs-max-to-ipod-touch-drfone-by-drfone-transfer-from-ios/"><u>In 2024, 4 Ways to Transfer Music from Apple iPhone XS Max to iPod touch | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-can-i-bypass-a-forgotten-phone-password-of-samsung-galaxy-m34-by-drfone-android/"><u>In 2024, Can I Bypass a Forgotten Phone Password Of Samsung Galaxy M34?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-effective-ways-to-fix-checkra1n-error-31-from-apple-iphone-15-pro-max-by-drfone-ios/"><u>In 2024, Effective Ways To Fix Checkra1n Error 31 From Apple iPhone 15 Pro Max</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-enhancing-engagement-with-solutions-to-common-shorts-challenges/"><u>In 2024, Enhancing Engagement with Solutions to Common Shorts Challenges</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-step-by-step-audio-recording-made-simple-with-iphone/"><u>In 2024, Step-By-Step Audio Recording Made Simple with iPhone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/mastering-srt-file-uploads-on-social-platforms-step-by-step-guide-for-2024/"><u>Mastering SRT File Uploads on Social Platforms  Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719306931208-opening-troubled-chrome-remediation-tips-for-win11-users-here/"><u>Opening Troubled Chrome: Remediation Tips for Win11 Users Here.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719228801666-streamline-help-process-for-windows-snags/"><u>Streamline Help Process for Windows Snags</u></a></li>
<li><a href="https://howto.techidaily.com/stuck-at-android-system-recovery-of-oppo-a59-5g-fix-it-easily-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Stuck at Android System Recovery Of Oppo A59 5G ? Fix It Easily | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719343275245-tackle-windows-geforce-failures-head-on-today/"><u>Tackle Windows GeForce Failures Head-On Today!</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/the-ultimate-guide-sharing-youtube-videos-on-fb/"><u>The Ultimate Guide  Sharing YouTube Videos on FB</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-4-ways-to-trace-realme-12plus-5g-location-drfone-by-drfone-virtual-android/"><u>Top 4 Ways to Trace Realme 12+ 5G Location | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/unlock-mastery-the-beginners-guide-to-editing-excellence-for-2024/"><u>Unlock Mastery  The Beginner's Guide to Editing Excellence for 2024</u></a></li>
</ul></div>
