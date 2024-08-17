---
title: Tailoring Domain-Based Biometric Use in Windows 11
date: 2024-08-16T02:13:37.459Z
updated: 2024-08-17T02:13:37.459Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tailoring Domain-Based Biometric Use in Windows 11
excerpt: This Article Describes Tailoring Domain-Based Biometric Use in Windows 11
keywords: Bio-ID in Win11,Windows Biometrics,Fingerprint Tech Win,Windows Facial ID,Secure Login Win11,Personalized User IDs,Biometric Security Win
thumbnail: https://thmb.techidaily.com/747f020dba73f73220750a642a58d9200a84cba1b61684b0bd89a4b6e70d1ea8.jpg
---

## Tailoring Domain-Based Biometric Use in Windows 11

 Biometric authentication allows you to quickly log in to the system using fingerprint, facial, or iris recognition. However, what if you want to prevent a domain user from logging in using biometrics?

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

## How to Allow or Block a Biometrics Log-On via the Local Group Policy Editor

 The quickest way to configure your computer to allow or block a biometrics scan for domain users is through the Local Group Policy Editor. Here are the steps you need to follow:

1. Press the **Win + R** key to open the **Run tool.**
2. Type **gpedit.msc** in the search bar and click OK.
3. In the Local Group Policy Editor, head towards the following location:  
`Computer Configuration > Administrative Templates > Windows Components > Biometrics`
4. Double-click on the **Allow domain users to log on using biometrics** policy in the right pane.  
![Allow domain users to log on using biometrics policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/allow-domain-users-to-log-on-using-biometrics-policy.jpg)
5. Choose the **Enabled** option to allow biometrics log on for the domain users. And choose the **Disabled** option to block biometrics log on for the domain users.  
![Enable option in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-option.png)
6. Click **Apply** \> **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Allow or Block a Biometrics Log-On Using the Registry Editor

 Another way to configure biometrics log-on for the domain users is through the Registry Editor. Here's how:

 Editing the registry is risky, as one wrong edit can make your system unstable. Therefore, make sure to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps.

1. Open the Run tool, type **regedit** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Biometrics\Credential Provider`
3. Right-click the **Credential Provider** key in the left sidebar, hover the cursor to **New,** and choose **DWORD (32-bit) Value**.  
![DWORD (32-bit) Value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/dword-32-bit-value.jpg)
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Name the value **Domain Accounts.**  
![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  
![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Control Biometrics Logins on Your Computer

 Securing sensitive information has now become more important than ever. If you want to allow or block a domain user from logging on using biometrics, you can do that using the above methods.

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-add-a-pop-of-color-to-your-videos-implementing-neons-in-youtubes/"><u>[New] 2024 Approved  Add a Pop of Color to Your Videos  Implementing Neons in YouTubes</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-download-free-sound-effects-for-youtubers/"><u>[New] 2024 Approved  Download Free Sound Effects for YouTubers</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-efficient-shortening-of-instagram-video-content-mac/"><u>[New] 2024 Approved  Efficient Shortening of Instagram Video Content (Mac)</u></a></li>
<li><a href="https://youtube-data.techidaily.com/20645895-new-2024-approved-unlock-brand-potential-access-50-banners-at-no-cost/"><u>[New] 2024 Approved  Unlock Brand Potential - Access 50 Banners at No Cost!</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-prime-selection-of-invisible-android-recorders/"><u>[New] In 2024, Prime Selection of Invisible Android Recorders</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-in-2024-the-art-of-edible-entertainment-7-steps-to-perfect-plating-on-camera/"><u>[New] In 2024, The Art of Edible Entertainment  7 Steps to Perfect Plating on Camera</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-broadcasting-brevity-news-outro-tips/"><u>[Updated] 2024 Approved  Broadcasting Brevity  News Outro Tips</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-guide-to-supercharged-video-engagement-with-youtube-notes/"><u>[Updated] 2024 Approved  Guide to Supercharged Video Engagement with YouTube Notes</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-enhance-interaction-share-your-custom-youtube-playlist/"><u>[Updated] Enhance Interaction  Share Your Custom YouTube Playlist</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-flawless-approach-securing-gotomeeting-recordings/"><u>[Updated] Flawless Approach  Securing GoToMeeting Recordings</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-mastering-chroma-key-techniques-for-professional-videos-for-2024/"><u>[Updated] Mastering Chroma Key Techniques for Professional Videos for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-best-in-class-meme-layout-essentials/"><u>2024 Approved  Best-in-Class Meme Layout Essentials</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-enhance-audience-reach-share-twitch-videos-on-facebook/"><u>2024 Approved  Enhance Audience Reach  Share Twitch Videos on Facebook</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-innovating-with-iphone-for-complete-360-video-capture/"><u>2024 Approved  Innovating with iPhone for Complete 360 Video Capture</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-professional-graphics-with-asus-pa32u-true-to-color/"><u>2024 Approved  Professional Graphics with ASUS PA32U  True to Color</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-ways-to-check-for-open-tcpip-ports-on-windows/"><u>3 Ways to Check for Open TCP/IP Ports on Windows</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/affordable-audio-capture-tools-ranked-1-to-10/"><u>Affordable Audio Capture Tools Ranked #1 to #10</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/alternative-high-quality-gaming-video-recording-solutions-for-2024/"><u>Alternative High-Quality Gaming Video Recording Solutions for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augment-windows-management-with-a-disk-space-analysis-tool/"><u>Augment Windows Management with a Disk Space Analysis Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-windows-net-runtime-requirement-hurdle/"><u>Avoiding Windows' .NET Runtime Requirement Hurdle</u></a></li>
<li><a href="https://media-tips.techidaily.com/best-7-software-solutions-for-converting-flac-files-into-mp3-format/"><u>Best 7 Software Solutions for Converting FLAC Files Into MP3 Format</u></a></li>
<li><a href="https://win11-tips.techidaily.com/circumventing-non-changeable-sleepwake-modes-in-windows-11/"><u>Circumventing Non-Changeable Sleep/Wake Modes in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/create-individualized-keystroke-rules-in-windows-11/"><u>Create Individualized Keystroke Rules in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cure-for-unresponsive-wired-gaming-accessories/"><u>Cure for Unresponsive Wired Gaming Accessories</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customize-your-computing-conduct-setting-active-hours-to-mitigate-updates-in-windows-11/"><u>Customize Your Computing Conduct: Setting Active Hours to Mitigate Updates in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cut-down-clutter-tackling-large-storage-consumers-in-windows/"><u>Cut Down Clutter: Tackling Large Storage Consumers in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detailed-guide-to-overcoming-steam-auth-problems-with-rust-on-windows/"><u>Detailed Guide to Overcoming Steam Auth Problems with Rust on Windows</u></a></li>
<li><a href="https://facebook.techidaily.com/digital-interactions-upsides-top-9-positive-aspects-explained/"><u>Digital Interaction's Upsides: Top 9 Positive Aspects Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-strategies-to-fix-windows-error-code-0x800704b3/"><u>Effective Strategies to Fix Windows' Error Code: 0X800704B3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-win-10s-cc-troubleshooting/"><u>Essential Tips for Win 10'S CC Troubleshooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-for-loss-of-pin-access-in-windows-11-post-update-fallout/"><u>Fix for Loss of PIN Access in Windows 11 Post-Update Fallout</u></a></li>
<li><a href="https://games-able.techidaily.com/fortnite-lovers-mac-users-uncover-the-restrictions/"><u>Fortnite Lovers, Mac Users! Uncover the Restrictions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gearing-up-with-best-laptops-from-ifa-2023/"><u>Gearing Up with Best Laptops From IFA 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-quickly-enable-or-disable-bing-chat-ai-in-windows-11-taskbar-search/"><u>How to Quickly Enable or Disable Bing Chat AI in Windows 11 Taskbar Search</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-screen-lock-pin-on-honor-magic-6-like-a-pro-5-easy-ways-by-drfone-android/"><u>How To Remove Screen Lock PIN On Honor Magic 6 Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-text-messages-from-vivo-y100a-to-new-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Text Messages from Vivo Y100A to New Phone | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-steps-to-correct-windows-operating-system-office-errors/"><u>Immediate Steps to Correct Windows Operating System Office Errors</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-methods-to-mirror-motorola-moto-g34-5g-to-roku-drfone-by-drfone-android/"><u>In 2024, 3 Methods to Mirror Motorola Moto G34 5G to Roku | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-3-ways-for-android-pokemon-go-spoofing-on-motorola-moto-g14-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways for Android Pokemon Go Spoofing On Motorola Moto G14 | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-8-ways-to-transfer-photos-from-samsung-galaxy-f04-to-iphone-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 8 Ways to Transfer Photos from Samsung Galaxy F04 to iPhone Easily | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-lava-by-drfone-android/"><u>In 2024, AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Lava</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-easiest-guide-how-to-clone-tecno-phantom-v-flip-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Easiest Guide How to Clone Tecno Phantom V Flip Phone? | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-enhance-video-pace-youtube-via-desktops-and-phones/"><u>In 2024, Enhance Video Pace - YouTube via Desktops & Phones</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-change-oppo-find-x6-lock-screen-clock-in-seconds-by-drfone-android/"><u>In 2024, How To Change Oppo Find X6 Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-memorable-narratives-in-book-videos/"><u>In 2024, Memorable Narratives in Book Videos</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-minecraft-branding-resources-for-youtubers/"><u>In 2024, Minecraft Branding Resources for YouTubers</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-navigating-the-best-ways-to-record-screens-on-hp-systems/"><u>In 2024, Navigating the Best Ways to Record Screens on HP Systems</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-synching-youtube-songs-to-video-frameworks/"><u>In 2024, Synching YouTube Songs to Video Frameworks</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-unlock-your-disabled-apple-iphone-6s-without-itunes-in-5-ways-by-drfone-ios/"><u>In 2024, Unlock Your Disabled Apple iPhone 6s Without iTunes in 5 Ways</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/inside-toms-digital-workshop-in-depth-reviews-on-cutting-edge-hardware/"><u>Inside Tom's Digital Workshop: In-Depth Reviews on Cutting-Edge Hardware</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-internal-error-in-windows-11-remote/"><u>Mastering the Art of Fixing Internal Error in Windows 11 Remote</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-win1011-recycle-bin-repair-strategies/"><u>Mastering WIN10/11 Recycle Bin Repair Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-store-wont-let-you-sign-in-try-these-fixes/"><u>Microsoft Store Won’t Let You Sign In? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/msix-extension-mastery-a-practical-guide-to-microsoft-store-add-ons/"><u>MSIX Extension Mastery: A Practical Guide to Microsoft Store Add-Ons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-with-ease-to-windows-11s-security-management/"><u>Navigate with Ease to Windows 11’S Security Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-mspcm-interface-on-windows-11-easily/"><u>Navigating the MSPCM Interface on Windows 11 Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-limited-access-install-troubleshooting-on-win-1110/"><u>Navigating Through Limited Access Install Troubleshooting on Win 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-steam-connectivity-woes-in-w11/"><u>Navigating Through Steam Connectivity Woes in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-screen-guide-to-windows-11-gpus/"><u>Optimize Your Screen: Guide to Windows 11 GPUs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-device-inactivity-in-new-os-sleep-mode/"><u>Overcoming Device Inactivity in New OS Sleep Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-challenge-xfffffddd-print-error-in-xp/"><u>Overcoming the Challenge: XFFFFFDDD Print Error in XP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-windows-11s-file-order-preferences/"><u>Realigning Windows 11'S File Order Preferences</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/recorded-reality-facebook-live-2023/"><u>Recorded Reality  Facebook Live, 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-itunes-operational-status-on-your-pc/"><u>Restoring iTunes Operational Status on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-connection-attempted-bluetooth-hiccup-on-pcs/"><u>Solving 'Connection Attempted' Bluetooth Hiccup on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-walkthrough-switching-nat-type-on-wins-10-and-11/"><u>Step-By-Step Walkthrough: Switching NAT Type on Wins 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-tackle-dxgierrordevicehunk-on-windows-11/"><u>Steps to Tackle DXGI_ERROR_DEVICE_HUNK on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-future-of-windows-interface-winbubbles-8-innovations/"><u>The Future of Windows Interface: WinBubble's 8 Innovations</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-learners-handbook-of-av1-technology/"><u>The Learner's Handbook of AV1 Technology</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-secret-techniques-for-a-transparent-windows-11-title-bar/"><u>The Secret Techniques for a Transparent Windows 11 Title Bar</u></a></li>
<li><a href="https://activate-lock.techidaily.com/the-ultimate-guide-to-bypassing-icloud-activation-lock-from-iphone-x-by-drfone-ios/"><u>The Ultimate Guide to Bypassing iCloud Activation Lock from iPhone X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-picks-for-trusted-free-software-downloads-on-windows/"><u>Top Picks for Trusted, Free Software Downloads on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turning-android-into-a-compatible-webcam-for-windows-11/"><u>Turning Android Into a Compatible Webcam for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ways-to-wipe-old-windows-protection-markers-from-microsofts-record/"><u>Ways to Wipe Old Windows Protection Markers From Microsoft's Record</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-lsass-component-resolution-a-user-friendly-guide/"><u>Win LSass Component Resolution: A User-Friendly Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-against-unwanted-scroll-events/"><u>Winning Against Unwanted Scroll Events</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-over-old-titles-directing-them-to-my-pictures/"><u>Winning Over Old Titles: Directing Them to My Pictures</u></a></li>
</ul></div>
