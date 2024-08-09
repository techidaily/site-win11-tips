---
title: "Freeing Up Windows File Access: Disable Read-Lock"
date: 2024-08-08T11:12:08.156Z
updated: 2024-08-09T11:12:08.156Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Freeing Up Windows File Access: Disable Read-Lock"
excerpt: "This Article Describes Freeing Up Windows File Access: Disable Read-Lock"
keywords: Free File Locks,Disable File Access,Unlock Windows Files,Remove Read Lock,Optimize File Access,Eliminate File Lock,Windows File Permission
thumbnail: https://thmb.techidaily.com/e7b26cce85084898820694a03b988f46853880c83b86563e047e92a3e8096101.jpg
---

## Freeing Up Windows File Access: Disable Read-Lock

 When a file is marked as read-only on Windows, you can only view it and not change it in any way. This essentially protects important files from unauthorized changes.

 On Windows, you can set or remove the read-only attribute for a file by modifying its properties. Alternatively, you can also run a command in Command Prompt or Windows PowerShell to do the same. In this article, we take a look at all of them.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. How to Change the Read-Only Attribute for Files by Modifying Properties

 The easiest way to set or remove the read-only attribute for a file on Windows is by modifying its properties. Here’s how you can go about it.

1. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the file for which you want to change the read-only attribute.
2. Right-click on your file and select**Properties** .
3. Under the**General** tab, check or uncheck the**Read-only** box.
4. Click**Apply** followed by**OK** .  
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
![Change Read-Only Attribute by Modifying Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-by-Modifying-Properties.jpg)

 Note that Windows may prevent you from changing the read-only attribute of a file if you don’t have the necessary permissions to modify the folder in which the file is located. In that case, you must take ownership of the folder first. If you need help, check our guide on[how to take ownership of folders on Windows](<http://How> to Take Ownership of Folders in Windows 10 & 11) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
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
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![Change Read-Only Attribute With PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-PowerShell.jpg)

 Alternatively, if you want to remove the read-only attribute for a file, use this command:

`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $False`

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
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
<li><a href="https://video-capture.techidaily.com/new-diverse-iptv-content-distribution/"><u>[New] Diverse IPTV Content Distribution</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-taking-your-instagram-game-up-a-notch-advanced-tracking-tools-overview/"><u>[New] In 2024, Taking Your Instagram Game Up a Notch  Advanced Tracking Tools Overview</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-boost-your-finances-with-these-8-essential-tiktok-strategies-for-2024/"><u>[Updated] Boost Your Finances with These 8 Essential TikTok Strategies for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-elevate-conversations-via-curated-creativity-in-stories-lives/"><u>[Updated] Elevate Conversations via Curated Creativity in Stories Lives</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-advancements-in-quantum-hdr-technology-explained/"><u>[Updated] In 2024, Advancements in Quantum HDR Technology Explained</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-exploring-animated-selfies-snapchats-fun-face-filters-explained/"><u>[Updated] In 2024, Exploring Animated Selfies  Snapchat's Fun Face Filters Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-essential-solutions-for-troubleshooting-missing-wireless-connections-in-windows-10/"><u>10 Essential Solutions for Troubleshooting Missing Wireless Connections in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-solutions-for-a-fully-operational-windows-search-bar/"><u>11 Solutions for a Fully Operational Windows Search Bar</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-maximize-engagement-uploading-and-posting-funny-gifs-on-instagram-easy-guide/"><u>2024 Approved  Maximize Engagement  Uploading & Posting Funny GIFs on Instagram (Easy Guide)</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/approved-unlock-the-potential-of-your-youtube-videos-in-movie-maker/"><u>2024 Approved  Unlock the Potential of Your YouTube Videos in Movie Maker</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/1719581430573-9-english-grammar-tips-from-an-esl-speaker/"><u>9 English Grammar Tips From An ESL Speaker</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-customize-win11-mouse-controls/"><u>A Guide to Customize Win11 Mouse Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-eradicating-d3d11-errors-in-w11-and-w10/"><u>A Step-by-Step Approach to Eradicating D3D11 Errors in W11 & W10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-stalled-downloads-with-qbittorrent-fixes/"><u>Accelerating Stalled Downloads with qBittorrent Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/access-strongest-passwords-effortlessly-with-these-7-free-generators/"><u>Access Strongest Passwords Effortlessly With These 7 Free Generators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-locked-windows-11-themes-through-registry-expertise/"><u>Accessing Locked Windows 11 Themes Through Registry Expertise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-renovated-widget-display-tool-for-windows-11/"><u>Accessing Renovated Widget Display Tool for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-network-unity-wi-fi-plus-ethernet-integration-in-windows/"><u>Achieving Network Unity: Wi-Fi + Ethernet Integration in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-empty-directory-alert-in-windows-11/"><u>Addressing Empty Directory Alert in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-unified-sticky-note-syncing-on-win11/"><u>Addressing Non-Unified Sticky Note Syncing on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-default-screen-saver-in-windows-11/"><u>Adjusting Default Screen Saver in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-tips-for-efficient-voice-access-on-windows/"><u>Advanced Tips for Efficient Voice Access on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-integration-in-windows-11-for-effective-multitasking/"><u>Android Integration in Windows 11 for Effective Multitasking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-linking-to-windows-shared-drives/"><u>Android Linking to Windows Shared Drives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/arrow-key-calm-a-guide-for-win-users/"><u>Arrow Key Calm: A Guide for Win Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-interruptions-resolving-steams-error-code-e84/"><u>Avoid Interruptions: Resolving Steam’s Error Code E84</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-inquiries-stealthy-strategies-for-secure-credentials-in-win-11/"><u>Avoiding Inquiries: Stealthy Strategies for Secure Credentials in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-yellow-shade-from-laptop-panels/"><u>Banishing Yellow Shade From Laptop Panels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/battle-bugs-tackling-skyrims-extension-failure/"><u>Battle Bugs: Tackling Skyrim's Extension Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-fit-selecting-vms-that-thrive-on-windows-11-platforms/"><u>Best Fit: Selecting VMs That Thrive On Windows 11 Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/black-friday-special-612-unlimited-win10-life/"><u>Black Friday Special: $6.12, Unlimited Win10 Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blockchain-against-breaches-7-windows-strategies/"><u>Blockchain Against Breaches: 7 Windows Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boldly-hiding-extra-commands-within-window-contexts-win-10/"><u>Boldly Hiding Extra Commands Within Window Contexts (Win 10)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boltgun-playtime-maximized-overcoming-computer-delays-in-warhammer-40k/"><u>Boltgun Playtime Maximized: Overcoming Computer Delays in Warhammer 40K</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-dedicated-video-ram-capacity-on-modern-windows/"><u>Boost Dedicated Video RAM Capacity on Modern Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-performance-by-rebooting-windows-11-ram/"><u>Boost Performance by Rebooting Windows 11 RAM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-by-mastering-task-management-on-a-windows-11-pc/"><u>Boost Productivity by Mastering Task Management on a Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-harness-windows-smart-launcher-techniques/"><u>Boost Productivity: Harness Windows' Smart Launcher Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-start-menu-efficiency-in-the-world-of-windows-11/"><u>Boost Your Start Menu Efficiency in the World of Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-typing-copy-pasting-expertise/"><u>Boost Your Typing, Copy-Pasting Expertise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-windows-apps-with-efficient-internet-fixes/"><u>Boost Your Windows Apps with Efficient Internet Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-edges-app-guard-with-enhanced-graphics/"><u>Boosting Edge's App Guard with Enhanced Graphics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-taskbar-performance-on-win11/"><u>Boosting Taskbar Performance on Win11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-photos-from-reno-11-5g-by-fonelab-android-recover-photos/"><u>Easy steps to recover deleted photos from Reno 11 5G.</u></a></li>
<li><a href="https://location-social.techidaily.com/edit-and-send-fake-location-on-telegram-for-your-vivo-x90s-in-3-ways-drfone-by-drfone-virtual-android/"><u>Edit and Send Fake Location on Telegram For your Vivo X90S in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://fox-blue.techidaily.com/elite-film-preview-spectacles-for-2024/"><u>Elite Film Preview Spectacles for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/enhance-video-speed-in-minutes-on-tiktok-filming-for-2024/"><u>Enhance Video Speed in Minutes on TikTok Filming for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/in-2024-how-to-changefake-your-itel-s23-location-on-viber-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Fake Your Itel S23 Location on Viber | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-use-pokemon-go-joystick-on-vivo-y56-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Pokemon Go Joystick on Vivo Y56 5G? | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-transforming-video-into-melody-cutting-edge-audio-retrieval-in-multimedia-for-2024/"><u>New Transforming Video Into Melody Cutting-Edge Audio Retrieval in Multimedia for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719327147890-secrets-to-perfect-full-screen-snipping-with-windows-toolkit/"><u>Secrets to Perfect Full-Screen Snipping with Windows' Toolkit</u></a></li>
<li><a href="https://apple-account.techidaily.com/troubleshooting-error-connecting-to-the-apple-id-server-from-iphone-6s-plus-by-drfone-ios/"><u>Troubleshooting Error Connecting to the Apple ID Server From iPhone 6s Plus</u></a></li>
<li><a href="https://extra-information.techidaily.com/turning-clutter-into-clarity-managing-massive-tiktok-drafters/"><u>Turning Clutter Into Clarity  Managing Massive TikTok Drafters</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/youtube-video-creation-secrets-of-the-professionals-unveiled-for-2024/"><u>YouTube Video Creation  Secrets of the Professionals Unveiled for 2024</u></a></li>
</ul></div>
