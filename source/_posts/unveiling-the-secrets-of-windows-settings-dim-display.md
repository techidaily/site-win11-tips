---
title: "Unveiling the Secrets of Windows Settings: 'Dim Display'"
date: 2024-07-12T16:58:58.911Z
updated: 2024-07-13T16:58:58.911Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unveiling the Secrets of Windows Settings: 'Dim Display'"
excerpt: "This Article Describes Unveiling the Secrets of Windows Settings: 'Dim Display'"
keywords: Dim Windows View,Windows Display Tips,Low Contrast Mode,Adjust Windows Brightness,Reduce Screen Glare,Optimize Windows UI,Custom Dark Theme Settings
thumbnail: https://thmb.techidaily.com/0b81880445efb7746c34685a24a5e53155bfff0ac907d2d7a06d83968e5eaef1.jpg
---

## Unveiling the Secrets of Windows Settings: 'Dim Display'

 There are times when you need to step away from your PC, and if you’re gone long enough, the screen will automatically dim. Windows does this to preserve your battery, and you can adjust when your display should darken in the Power Options menu by editing the **Dim display after** option.

 If for some reason you can’t see the **Dim display after** option in the Power Options menu, or it’s there and you want to remove it, you can use PowerShell or the Registry Editor to show or hide it. Here’s how.

## How to Show or Hide the “Dim Display After” Option Using PowerShell

 First, launch Windows PowerShell. There are many [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/), but the easiest method is to press **Win + S** to open Windows Search. Then, enter **powershell** in the search box and click on **Windows PowerShell** when it appears in the search results.

![windows powershell in the windows search results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-powershell-search.jpg)

 In PowerShell, enter the following command to show the **Dim Display after** option in the Power Options menu:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee -ATTRIB_HIDE

 To hide it, enter the following command:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee +ATTRIB_HIDE

 After entering the command you want, hit the **Enter** key on your keyboard for PowerShell to execute it. Afterward, the **Dim display after** option should appear or disappear accordingly in the Power Options menu.

## How to Show or Hide the “Dim display after” Option Using the Registry Editor

 Considering how vital the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is for the smooth operation of Windows, you might want to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you edit it. Afterward, open the Registry Editor by pressing **Win + R**, typing **regedit** in the text box, and clicking **OK**.

![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/regedit.jpg)

 Click **Yes** to bypass the UAC prompt.

 In the address bar of the Registry Editor, copy and paste the following text into it:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\7516b95f-f776-4464-8c53-06167f40cc99\17aaa29b-8b43-4b94-aafe-35f64daaf1ee

 On the right panel, double-click the **Attributes** entry to open it up for editing.

![the attributes entry in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-dim-display-after-attributes-entry.jpg)

 Then, in the **Value data** text box, enter **1** to hide **Dim display after** in the Power Options menu or **2** to show it.

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

 Now you can open the Power Options menu (see [how to open the power options on Windows 10](https://www.makeuseof.com/windows-10-open-power-options/)) and check under **Display** to see if the **Dim display after** option is there or not.

## Controlling the “Dim Display After” Option in the Power Options Menu

 Now that you know how to show or hide **Dim display after**, you know what to do when you can’t find it in the Power Options menu or need to remove it. We recommend keeping it hidden and then bringing it up whenever you need it. This will make sure that no one messes with this important display setting when you’ve set it up perfectly.

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
<li><a href="https://win11-tips.techidaily.com/resolving-windows-11-pin-access-issues/"><u>Resolving Windows 11 PIN Access Issues</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-activation-lock-on-mac-for-apple-iphone-se-2022-by-drfone-ios/"><u>In 2024, How To Bypass iCloud Activation Lock on Mac For Apple iPhone SE (2022)?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-audible-acuity-ending-echo-of-empty-spaces/"><u>Regain Audible Acuity: Ending Echo of Empty Spaces</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-capture-and-share-the-art-of-using-zooms-snaps/"><u>[New] Capture & Share  The Art of Using Zoom's Snaps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/address-stuck-function-keys-on-windows-11-desktop/"><u>Address: Stuck Function Keys on Windows 11 Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncompromised-security-in-windows-app-downloads/"><u>Uncompromised Security in Windows App Downloads</u></a></li>
<li><a href="https://unlock-android.techidaily.com/tips-and-tricks-for-setting-up-your-vivo-s18-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Vivo S18 Phone Pattern Lock</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-gmail-to-zoom-tips-for-smooth-virtual-meeting-transitions/"><u>[Updated] Gmail to Zoom  Tips for Smooth Virtual Meeting Transitions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-virtualboxs-usb-failure-message-a-step-by-step-guide-for-windows-users/"><u>Resolving VirtualBox's USB Failure Message: A Step-by-Step Guide for Windows Users</u></a></li>
<li><a href="https://extra-resources.techidaily.com/expert-tips-for-crafting-professional-slug-line-notations/"><u>Expert Tips for Crafting Professional Slug Line Notations</u></a></li>
<li><a href="https://driver-install.techidaily.com/install-hp-envy-5530-driver-on-your-windows-11/"><u>Install HP Envy 5530 Driver on Your Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windowing-wonderland-personalized-monitor-settings-in-win1011/"><u>Windowing Wonderland: Personalized Monitor Settings in Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefine-access-restoring-standard-user-privileges-in-win11/"><u>Redefine Access: Restoring Standard User Privileges in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-selection-of-4-webp-viewer-software/"><u>The Ultimate Selection of 4 WebP Viewer Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-windows-cached-data-for-optimal-performance/"><u>Taming Window’s Cached Data for Optimal Performance</u></a></li>
<li><a href="https://extra-information.techidaily.com/boost-your-periscope-broadcast-speed-a-guide/"><u>Boost Your Periscope Broadcast Speed  A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-analysis-of-windows-lav-filter-usage-and-outputs/"><u>A Comprehensive Analysis of Windows LAV Filter Usage and Outputs</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-unleash-the-full-potential-of-your-audio-files-with-mp3-converter-windows-a-step-by-step-guide/"><u>New Unleash the Full Potential of Your Audio Files with Mp3 Converter Windows A Step-by-Step Guide</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-from-clips-to-masterpiece-a-beginners-guide-to-video-editing-in-windows/"><u>New In 2024, From Clips to Masterpiece A Beginners Guide to Video Editing in Windows</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-bandicam-revisited-a-deep-dive-into-screen-recording/"><u>[Updated] 2024 Approved  Bandicam Revisited  A Deep Dive Into Screen Recording</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-maximizing-sound-the-best-online-tools-for-amplifying-video-volumes-for-2024/"><u>Updated Maximizing Sound The Best Online Tools for Amplifying Video Volumes for 2024</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-in-2024-step-by-step-tiktok-usage-for-mac-and-pc-users/"><u>[Updated] In 2024, Step-by-Step TikTok Usage for Mac and PC Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-power-of-ping-windows-application-essentials/"><u>Unveiling the Power of Ping: Windows Application Essentials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-windows-program-functionality-with-ease/"><u>Restoring Windows Program Functionality with Ease</u></a></li>
<li><a href="https://some-guidance.techidaily.com/top-10-live-broadcast-gaming-applications-for-2024/"><u>Top 10 Live Broadcast Gaming Applications for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/time-saving-techniques-for-a-functional-windows-time-service/"><u>Time-Saving Techniques for a Functional Windows Time Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-ways-the-best-fixes-to-skip-the-long-wait-in-install-steps/"><u>Winning Ways: The Best Fixes to Skip the Long Wait in Install Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-old-password-needed-on-windows-11-errors/"><u>Remedy for 'Old Password Needed' On Windows 11 Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/asus-vivobook-s-15-a-comprehensive-compromise-of-design/"><u>ASUS Vivobook S 15 - A Comprehensive Compromise of Design</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-8-to-other-iphone-12-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 8 to other iPhone 12 devices? | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-streamlining-your-workflow-with-macs-finest-snipers/"><u>2024 Approved  Streamlining Your Workflow with Mac's Finest Snipers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-prevent-expiring-notifications-on-win11/"><u>Strategies to Prevent Expiring Notifications on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-defenders-error-0x80004004/"><u>Troubleshooting Defender's Error 0X80004004</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfreezing-stuck-photoshopping-in-windows-11-versions-2023/"><u>Unfreezing Stuck Photoshopping in Windows 11, Versions 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-talk-the-key-to-a-visible-mouse-indicator-in-windows-os/"><u>Tech Talk: The Key to a Visible Mouse Indicator in Windows OS</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-exploring-updates-to-sonys-s6500-model/"><u>2024 Approved  Exploring Updates to Sony's S6500 Model</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-steering-to-your-own-musical-selections-on-youtube/"><u>2024 Approved  Steering to Your Own Musical Selections on Youtube</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-snappro-v3-windows-screen-mastery/"><u>In 2024, SnapPro V3  Windows Screen Mastery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-deskanywhere-failures-in-windows-11/"><u>Troubleshooting DeskAnywhere Failures in WIndows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-guide-to-engaging-windows-11s-calculator/"><u>The Essential Guide to Engaging Windows 11'S Calculator</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-in-2024-masterful-14-textual-movement-illustrations/"><u>[New] In 2024, Masterful 14 Textual Movement Illustrations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-the-true-power-of-windows-screen-capture-toolkit/"><u>Unleash the True Power of Windows' Screen Capture Toolkit.</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-achieving-professional-grade-motion-blur-using-photoshop-tools/"><u>2024 Approved  Achieving Professional-Grade Motion Blur Using Photoshop Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-slacks-missing-notifications-issue-in-win-11/"><u>Solving Slack's Missing Notifications Issue in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-your-windows-11-the-most-impactful-settings-to-modify/"><u>Revolutionize Your Windows 11: The Most Impactful Settings to Modify</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-bring-your-vision-to-life-top-free-and-paid-3d-video-creators/"><u>2024 Approved Bring Your Vision to Life Top Free and Paid 3D Video Creators</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-channel-growth-strategy-going-with-studio-or-beta-progression/"><u>[Updated] Channel Growth Strategy  Going with Studio or Beta Progression</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-memory-assessment-made-easy/"><u>Windows Memory Assessment Made Easy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-experience-implementing-appxappxbundle-files-from-store/"><u>Seamless Experience: Implementing Appx/Appxbundle Files From Store</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-diligent-duplication-in-the-world-of-insta/"><u>[New] Diligent Duplication in the World of Insta</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-complete-guide-on-unlocking-iphone-xr-with-a-broken-screen-by-drfone-ios/"><u>In 2024, Complete Guide on Unlocking iPhone XR with a Broken Screen?</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/swaying-scripts-an-introduction-to-bouncy-text-animations-for-2024/"><u>Swaying Scripts  An Introduction to Bouncy Text Animations for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-revive-vanished-watch-video-icon-for-2024/"><u>[Updated] Revive Vanished Watch Video Icon for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-easing-through-administrative-denial-of-installers/"><u>Strategies for Easing Through Administrative Denial of Installers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winservicesexe-explained-troubleshooting-guide/"><u>WinServices.exe Explained: Troubleshooting Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-to-streamline-your-windows-netconnection-access/"><u>Step-By Step to Streamline Your Windows NetConnection Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-complications-caused-by-latest-windows-updates/"><u>Resolving Complications Caused by Latest Windows Updates</u></a></li>
<li><a href="https://network-issues.techidaily.com/enhanced-clarity-for-all-windows/"><u>Enhanced Clarity for All Windows</u></a></li>
</ul></div>
