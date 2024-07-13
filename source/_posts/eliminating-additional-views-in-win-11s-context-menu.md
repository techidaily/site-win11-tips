---
title: Eliminating Additional Views in Win 11'S Context Menu
date: 2024-07-12T17:16:03.600Z
updated: 2024-07-13T17:16:03.600Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminating Additional Views in Win 11'S Context Menu
excerpt: This Article Describes Eliminating Additional Views in Win 11'S Context Menu
keywords: Win 11 Menu Cleanup,Eliminate W11 Extras,Remove Windows Menu Items,Clear W11 Menu Views,Streamline Win 11 UI,Optimize W11 ContextMenu,Tidy Up Windows 11 Menus
thumbnail: https://thmb.techidaily.com/4546ddfed47c887fd8822a083e53e55a360fbac19fd97cadc5d42f68a2d04c9c.png
---

## Eliminating Additional Views in Win 11'S Context Menu

 Windows 11 comes with a fresh new look and has mainly got a positive response for its new interface. However, there are a couple of features that are not being welcomed by the users. For instance, the addition of the "show more options" entry to the right-click context menu.

 Although it was introduced to simplify things, many users still prefer the old context menu from Windows 10\. Fortunately, you can remove Show more options from the context menu on Windows 11 by following the below methods.

## 1\. How to Remove "Show More Options" From the Context Menu With Folder Options

 The [Windows Folder Options](https://www.makeuseof.com/windows-folder-options-guide/) in File Explorer is the go-to place to view and manage File Explorer settings. You can use it to [enable compact view in File Explorer on Windows 11](https://www.makeuseof.com/how-to-enable-compact-view-windows-11-file-explorer/) , manage file thumbnails, remove the "show more options" entry, and much more.

 Here's how to use the folder option to remove the "show more options" entry from the context menu:

1. Press the**Win + E** hotkey to open the**File Explorer.**
2. Click the three horizontal dots at the top bar and choose**Options.**
3. In the**Folder Options,** switch to the**View** tab.
4. Check the**Launch folder** **windows in a separate process** box.  
![Launch folder windows in a separate process box in the Folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/launch-folder-windows-in-a-separate-process-box.jpg)
5. Click**Apply** \>**OK** to save the changes.

Next, restart your computer for the changes to take effect.

## 2\. Remove Show More Options From the Context Menu Using the Command Prompt

 If you're a power user, you can use Command Prompt to remove the "show more options" entry from the context menu. Here's how:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane.
3. Click**Yes** to the UAC that crops up.
4. In the elevated Command Prompt window, type the following command and press**Enter** :  
`reg add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve`

![Command to Remove Context menu in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/command-to-remove-context-menu.jpg)

 After executing the command, you'll see the "The operation completed successfully" message to confirm that it went through.

 Now, you will have to restart Windows Explorer to see the changes. To do that, open the**Task Manager** (see how to [launch the Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) ), right-click on**Windows Explorer,** and choose**Restart.**

 Check if you can see the changes. If not, then you will have to restart your computer for the changes to take effect.

 In the future, if you want to add the "show more options" entry to the context menu, then open Command Prompt with admin rights and run the following command:

`reg delete "HKEY_CURRENT_USER\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}" /f​`

## 3\. Remove Show More Options From the Context Menu Using the Registry Editor

 Another quick way to remove the "show more options" entry is through the Registry Editor. Here's what you need to do:

 Before making any changes to the registry, ensure you've [created a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) or [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . This will ensure your system settings and files are secure, and you can quickly access them if something goes wrong.

1. Open the Start Menu, type**Registry Editor** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID`
3. Right-click on the empty space on the right pane, click**New,** and then select**DWORD** **(32-bit) Value** from the context menu.
4. Name the value as**"UndockingDisabled"** and press**Enter** .  
![UndockingDisabled entry in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/undockingdisabled-entry.jpg)
5. Double-click on the UndockingDisabled key, type**1** in the**Value data,** and click**OK** to save the changes.  
![Editing UndockingDisabled in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-undockingdisabled.jpg)

## 4\. Remove the "Show More Options" Entry From the Context Menu Using Winaero Tweaker

 There are plenty of third-party tools using which you can customize the look of your Windows 11 computer. For this guide, we will use Winaero Tweaker.

 Here's how to download Winaero Tweaker and use it to remove the "show more options" entry from the context menu:

1. Download the [Winaero Tweaker zip file](https://winaero.com/downloads/winaerotweaker.zip) on your computer.
2. Unzip the file, open the executable, and then follow the on-screen instructions to install it on your computer.
3. Launch Winaero Tweaker and choose the**Classic Full Context Menus** option from the left sidebar.  
![Classic Full Context Menus option of Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/classic-full-context-menus-option.jpg)
4. Check the**Enable classic full context menus** box.  
![Enable classic full context menus option in Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-classic-full-context-menus.jpg)
5. Click the**Restart Explorer** button that appears.

## Enjoy an Old School Context Menu on Windows 11

 The desktop context menu lets you quickly access areas like the personalization menu, display settings, and much more. In Windows 11, you get the new "Show more options" entry in the context menu. But if you prefer the old design, you can quickly disable the "Show more options" entry from the context using either of the above methods.


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
<li><a href="https://fox-blue.techidaily.com/updated-elevating-reality-with-top-10-mobile-virtual-reality-headsets-for-2024/"><u>[Updated] Elevating Reality with Top 10 Mobile Virtual Reality Headsets for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-a-lasting-deletion-toolbar-on-windows-systems/"><u>Personalizing a Lasting Deletion Toolbar on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-controller-reviving-it-from-steams-oblivion/"><u>Master the Controller: Reviving It From Steam's Oblivion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-launch-chrome-in-your-newest-windows-11-pc/"><u>How to Launch Chrome in Your Newest Windows 11 PC</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-the-ultimate-guide-to-free-public-domain-video-downloads/"><u>Updated The Ultimate Guide to Free Public Domain Video Downloads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-prevent-steam-file-sync-failures-in-windows/"><u>Methods to Prevent Steam File Sync Failures in Windows</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-fixed-tiktok-freezes-on-chromebook-quick-tips/"><u>2024 Approved  Fixed TikTok Freezes on Chromebook - Quick Tips</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-ace-your-shots-top-cameras-and-lenses-for-youtubers/"><u>[New] 2024 Approved  Ace Your Shots  Top Cameras & Lenses for YouTubers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-cure-the-msconfig-missing-gpeditmsc-bug/"><u>Solutions to Cure the Msconfig Missing Gpedit.msc Bug</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unchangeable-power-configurations-in-windows-11/"><u>Overcoming Unchangeable Power Configurations in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-unbootable-windows-vms-via-vmware-in-win11/"><u>Eliminating Unbootable Windows VMs via VMware in Win11</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-capturing-audio-masterpieces-using-audacity/"><u>[New] Capturing Audio Masterpieces Using Audacity</u></a></li>
<li><a href="https://extra-support.techidaily.com/spectacular-hooks-title-crafter-for-2024/"><u>Spectacular Hooks Title Crafter for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-with-style-adding-emoji-15-to-win11-setup/"><u>Navigate with Style: Adding Emoji 15 to Win11 Setup</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-harmonizing-technology-with-taste-your-guide-to-mastering-audio-format-selection/"><u>2024 Approved Harmonizing Technology with Taste Your Guide to Mastering Audio Format Selection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sharpen-skills-quickly-winning-techniques-from-windows-experts/"><u>Sharpen Skills Quickly: Winning Techniques From Windows Experts</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-optimal-logitech-webcam-settings-for-professional-video-outputs/"><u>[Updated] In 2024, Optimal Logitech Webcam Settings for Professional Video Outputs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/productivity-hack-instant-open-of-windows-sticky-notes-on-login/"><u>Productivity Hack: Instant Open of Windows' Sticky Notes on Login</u></a></li>
<li><a href="https://extra-information.techidaily.com/comprehensive-guide-to-oculus-rift-setup/"><u>Comprehensive Guide to Oculus Rift Setup</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-full-screen-vimeo-video-details-with-aspect-ratio-information/"><u>In 2024, Full Screen Vimeo Video Details with Aspect Ratio Information</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-captivating-clips-incorporating-text-deformation-artistry/"><u>[New] Captivating Clips  Incorporating Text Deformation Artistry</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-visualizing-stories-turning-your-favorite-vimeo-into-dynamic-gifs/"><u>In 2024, Visualizing Stories  Turning Your Favorite Vimeo Into Dynamic GIFs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-restoring-saved-settings-in-nvidia-gui-on-win11/"><u>Solutions for Restoring Saved Settings in Nvidia GUI on Win11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-straightforward-methods-for-recording-iphone-display/"><u>2024 Approved  Straightforward Methods for Recording iPhone Display</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-windows-event-viewer-usability/"><u>Restoring Windows Event Viewer Usability</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-remove-or-bypass-knox-enrollment-service-on-realme-narzo-n53-by-drfone-android/"><u>How To Remove or Bypass Knox Enrollment Service On Realme Narzo N53</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11s-code-0x0000004e-problem/"><u>Overcoming Windows 11'S Code 0X0000004E Problem</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-2024-approved-twitta-videos-new-audio-formats/"><u>[New] 2024 Approved  Twitta Videos  New Audio Formats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-window-11-style-hacks-and-themes/"><u>Exclusive Window 11 Style Hacks & Themes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-editing-the-windows-registry-via-terminal/"><u>Essential Tips for Editing the Windows Registry via Terminal</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-s-top-rated-free-mod-video-editing-tools/"><u>Updated In 2024, S Top-Rated Free MOD Video Editing Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-revert-windows-settings-after-restart/"><u>Methods to Revert Windows Settings After Restart</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-frozen-lock-screen-timing-windows/"><u>Overcoming Frozen Lock Screen Timing Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-format-missing-error-on-pc-windows/"><u>Overcoming 'Format Missing' Error on PC Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-network-address-translation-win1110-edition-explained/"><u>Navigating Network Address Translation: Win11/10 Edition Explained</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/20-quick-video-concepts-for-aspiring-vloggers-for-2024/"><u>20 Quick Video Concepts for Aspiring Vloggers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-mail-alert-failures-with-9-practical-tips-for-windows-users/"><u>Fixing Mail Alert Failures with 9 Practical Tips for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-windows-experience-fixes-for-elusive-optional-components/"><u>Revamp Your Windows Experience: Fixes for Elusive Optional Components</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-terminal-settings-on-windows-pc/"><u>Optimizing Terminal Settings on Windows PC</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-from-concept-to-creation-a-blueprint-for-powerful-snap-campaigns/"><u>[Updated] 2024 Approved  From Concept to Creation  A Blueprint for Powerful Snap Campaigns</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-files-essential-pitfalls-prevention-in-windows-11/"><u>Navigating Files: Essential Pitfalls Prevention in Windows 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-change-your-sim-pin-code-on-your-meizu-21-pro-phone-by-drfone-android/"><u>How To Change Your SIM PIN Code on Your Meizu 21 Pro Phone</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-what-is-an-ai-voice-generator/"><u>Updated What Is an AI Voice Generator?</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-the-top-10-most-jaw-dropping-4k-video-samples/"><u>New In 2024, The Top 10 Most Jaw-Dropping 4K Video Samples</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-overheat-in-laptops-with-intensive-play/"><u>Preventing Overheat in Laptops with Intensive Play</u></a></li>
<li><a href="https://screen-capture.techidaily.com/ultimatevision-recorder-for-w10/"><u>UltimateVision Recorder for W10</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-vivo-x-flip-by-phone-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Vivo X Flip by Phone Number | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-optimal-strategies-for-youtube-to-mpeg-conversion/"><u>[Updated] Optimal Strategies for YouTube-to-MPEG Conversion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-absence-of-critical-dll-mfc71u-on-pc/"><u>Resolving Absence of Critical DLL: Mfc71u on PC</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-navigating-the-lands-marketplace-of-product-sponsored-youtube-content/"><u>2024 Approved  Navigating the Lands Marketplace of Product-Sponsored YouTube Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocketing-through-efficiency-top-7-strategies-with-windows-11-39/"><u>Skyrocketing Through Efficiency: Top 7 Strategies with Windows 11 (39)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-into-the-world-of-windows-11-home/"><u>Step Into the World of Windows 11 Home</u></a></li>
<li><a href="https://win11-tips.techidaily.com/screenscape-symphony-composing-personalized-displays-in-windows-1011/"><u>Screenscape Symphony: Composing Personalized Displays in Windows 10/11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/open-access-mindful-harmonies-for-2024/"><u>Open Access Mindful Harmonies for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-interface-quick-menu-install/"><u>Enhancing Windows Interface: Quick Menu Install</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-discovering-if-quick-youtube-subscriptions-really-work/"><u>[Updated] 2024 Approved  Discovering if Quick YouTube Subscriptions Really Work</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-car-locator-apps-for-realme-c51-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Car Locator Apps for Realme C51 | Dr.fone</u></a></li>
</ul></div>
