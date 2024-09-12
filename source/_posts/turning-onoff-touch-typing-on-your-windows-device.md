---
title: Turning On/Off Touch Typing on Your Windows Device
date: 2024-09-11T01:27:56.127Z
updated: 2024-09-12T01:27:56.127Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Turning On/Off Touch Typing on Your Windows Device
excerpt: This Article Describes Turning On/Off Touch Typing on Your Windows Device
keywords: Turn On Keyboard Shortcuts,Off Typing Feature Windows,Activate Windows Touch Typing,Deactivate Computer Keystroke,Enable Tipi Mode Windows,Switch Keyboard Input Windows,Disable On-Screen Typing Windows
thumbnail: https://thmb.techidaily.com/cdf4d7c5a6e11bc2ecb600573fb51d6d46dc48a05d2a33906086e284e9c970a7.jpg
---

## Turning On/Off Touch Typing on Your Windows Device

 The fingertip writing feature in Windows allows users to write on a touch-enabled device using their fingertips, without a stylus or a pen. You can use it to input text directly into documents or applications easily.

 Below, we talk about the different ways to enable or disable the fingertip writing feature in the Handwriting Panel in Windows.


>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>







<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130869/7443" target="_top" id="2130869">
  <img src="//a.impactradius-go.com/display-ad/7443-2130869" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130869/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 1\. Use the Settings App to Enable/Disable Fingertip Writing

 The easiest, most straightforward way to enable or disable the fingertip writing feature is by using the Settings app. You can make these changes in the Bluetooth & devices section and do not need to have administrative access to the system as well.

Here is how you can proceed:

1. Press the**Win** +**I** keys to open the Settings app.
2. Choose**Bluetooth & devices** from the left pane.
3. Move to the right side of the window and click on**Pen & Windows Ink** .  
![Access the Pen & Windows Ink section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/pen-and-windows-ink.jpg)
4. Expand the**Use your handwriting to enter text** section under Handwriting.
5. Checkmark the box associated with**Write with your fingertip** .  
![Write with your fingertip option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/write-with-you-fingertip-1.jpg)

 You can now close the Settings app if you want. To disable the feature in the future, simply follow these steps again and uncheck the Write with your fingertip option.





<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098700/14409" target="_top" id="2098700">
  <img src="//a.impactradius-go.com/display-ad/14409-2098700" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098700/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 2\. Enable/Disable Fingertip Writing via the Registry Editor

 If the "Write with your fingertip" option is disabled in the Settings app, you can also make these changes using the Registry Editor.

 Windows Registry is a powerful tool that is typically used to manage important system settings and configurations. This is an administrative-level utility, so you will need to log into your administrator account if you are using a standard user account to use it. You can also[convert your standard user account into an administrator account](https://www.makeuseof.com/windows-standard-adminstrator-account-differences/) .

 Once you have logged into Windows as an administrator,[create a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) , just to be safe.

Then, proceed with these steps:

1. Press the**Win** +**R** keys together to open Run.
2. Type "regedit" in the text field of Run and click**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you have launced the Registry Editor, navigate to the location below:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\TabletTip`
5. Right-click on**TableTip** and choose**New** \>**Key** .  
![Create a new key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/create-new-key.jpg)

1. Name this key as EmbeddedInkControl.
2. Now, move to the right pane and right-click anywhere on an empty space.
3. Choose**New** \>**DWORD (32-bit) Value** .
4. Rename this key as EnableInkingWithTouch.
5. Double-click on**EnableInkingWithTouch** and under Value data, type 1\. This will enable the fingertip writing feature.  
![Enter 1 under Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enableinking-with-touch.jpg)
6. Click**OK** to save the changes.




<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/2139563/4704" target="_top" id="2139563">
  <img src="//a.impactradius-go.com/display-ad/4704-2139563" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139563/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




7. Close the Registry Editor and restart your computer.

 Upon reboot, you should be able to use the fingertip writing feature. To disable this feature, follow the aforementioned steps again and change the value data of the EnableInkingWithTouch key to 0.





<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139107/17108" target="_top" id="2139107">
  <img src="//a.impactradius-go.com/display-ad/17108-2139107" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139107/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 3\. Enable/Disable Fingertip Writing Via the Group Policy Editor

 The third way of enabling/disabling the fingertip writing feature is via the Group Policy Editor. Like the Windows Registry, this utility also allows the administrators to manage the advanced-level system settings in Windows.

 To use the Group Policy Editor for managing the fingertip writing feature, follow these steps:

1. Press the**Win** +**R** keys simultaneously to open Run.
2. Type "gpedit.msc" in Run and click**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you are in the Group Policy Editor, navigate to the location below:  
`Computer Configuration > Administrative Templates > Windows Components > Handwriting`
5. Locate the**Handwriting Panel Default Mode Docked** policy in the right pane and double-click on it.  
![Access the Handwriting panel default mode docked policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/handwriting-policy.jpg)
6. To enable the feature, choose**Not configured** . If you want to disable it, choose**Disable** .  




<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130533/26400" target="_top" id="2130533">
  <img src="//a.impactradius-go.com/display-ad/26400-2130533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130533/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




![Enable the handwriting panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-handwriting-panel-1.jpg)
7. Click**Apply** \>**OK** to save the changes.

 You can now close the Group Policy Editor and begin using the fingertip writing feature with ease.





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115910/19272" target="_top" id="2115910">
  <img src="//a.impactradius-go.com/display-ad/19272-2115910" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115910/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Use Your Fingertips to Write Away on Windows

 The fingertip writing feature can be a great tool for those who do not prefer using a stylus or a writing pen. You can use it to take handwritten notes and have them automatically converted into digital text which you then further organize and share.

 The three methods we have listed above should help you manage this feature easily. However, it is important to exercise caution and create a backup before you make any changes to the system settings and configurations.


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
<li><a href="https://extra-information.techidaily.com/new-advanced-computers-at-your-fingertips/"><u>[New] Advanced Computers at Your Fingertips</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-essential-guidelines-for-tiktok-web-on-a-mac/"><u>[New] In 2024, Essential Guidelines for TikTok Web on a Mac</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-seamless-conversion-of-video-content-to-dynamic-gif-formats/"><u>[New] In 2024, Seamless Conversion of Video Content to Dynamic GIF Formats</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-the-ultimate-guide-to-earning-on-youtube-shorts/"><u>[New] The Ultimate Guide to Earning on Youtube Shorts</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-boosting-video-impact-integrating-free-luts-into-your-obs-workflow-for-2024/"><u>[Updated] Boosting Video Impact Integrating Free LUTs Into Your OBS Workflow for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-glow-up-guide-3-masterful-instagram-highlight-tricks-for-2024/"><u>[Updated] Glow-Up Guide 3 Masterful Instagram Highlight Tricks for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-ensure-your-video-fits-the-instagram-aesthetic-perfectly/"><u>[Updated] In 2024, Ensure Your Video Fits the Instagram Aesthetic Perfectly</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-prevent-video-playback-issues-in-android-apps/"><u>[Updated] In 2024, Prevent Video Playback Issues in Android Apps</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-monetize-mastery-turning-views-into-revenue-on-vimeo/"><u>2024 Approved Monetize Mastery Turning Views Into Revenue on Vimeo</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-unleash-creativity-with-these-4-simple-steps-to-loops-on-instagram/"><u>2024 Approved Unleash Creativity with These 4 Simple Steps to Loops on Instagram</u></a></li>
<li><a href="https://extra-tips.techidaily.com/architectural-marvels-for-vr-display/"><u>Architectural Marvels for VR Display</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/1719581577843-bangladesh-by-ten-minutes-a-day/"><u>Bangladesh by Ten Minutes a Day</u></a></li>
<li><a href="https://fake-location.techidaily.com/best-10-mock-location-apps-worth-trying-on-realme-12-5g-drfone-by-drfone-virtual-android/"><u>Best 10 Mock Location Apps Worth Trying On Realme 12 5G | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/cellular-network-not-available-for-voice-calls-on-vivo-y17s-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Cellular Network Not Available for Voice Calls On Vivo Y17s | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-print-sharing-woes-on-windows-11/"><u>Clearing Up Print Sharing Woes on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-unsuccessful-windows-update-error-0x8024800c/"><u>Correcting Unsuccessful Windows Update (Error 0X8024800C)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detect-and-prevent-cyber-risks-without-antivirus-help/"><u>Detect and Prevent Cyber Risks Without Antivirus Help</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/effective-solutions-for-handling-overheating-smartphones/"><u>Effective Solutions for Handling Overheating Smartphones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortlessly-download-adobe-reader-through-microsoft-platform/"><u>Effortlessly Download Adobe Reader Through Microsoft Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-disconnected-application-problems-in-win10/"><u>Eliminating Disconnected Application Problems in Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-integrity-stick-to-proven-methods-for-win-11-keys/"><u>Ensuring Integrity: Stick to Proven Methods for Win 11 Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-prominent-positioning-of-sticky-notes-in-win-11/"><u>Ensuring Prominent Positioning of Sticky Notes in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-to-repairing-your-computer-or-device-a-comprehensive-guide/"><u>Essential Steps to Repairing Your Computer or Device: A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-advice-for-google-chromes-filesync-on-your-pc-win/"><u>Expert Advice for Google Chrome's Filesync on Your PC, WIN</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-the-efficiency-microsofts-bluetooth-linked-app/"><u>Exploring the Efficiency: Microsoft's Bluetooth-Linked App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-inactive-lock-screen-countdown-in-windows-os/"><u>Fixing Inactive Lock Screen Countdown in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/graphical-integration-with-application-guard-on-edge/"><u>Graphical Integration with Application Guard on Edge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-fixing-zero-x-eight-oh-three-one-f-mail-problem/"><u>Guide to Fixing Zero X Eight Oh Three One F Mail Problem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-cleanse-your-saved-wi-fi-list-in-win-11/"><u>How to Cleanse Your Saved Wi-Fi List in Win 11</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-come-up-with-the-best-pokemon-team-on-honor-70-lite-5g-drfone-by-drfone-virtual-android/"><u>How to Come up With the Best Pokemon Team On Honor 70 Lite 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reactivate-your-deactivated-key-on-win11/"><u>How to Reactivate Your Deactivated Key on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-uninstall-oneself-avoiding-admin-restrictions-in-windows/"><u>How To Uninstall Oneself: Avoiding Admin Restrictions in WINDOWS</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-from-screenshots-to-art-the-8-best-photo-collage-tools/"><u>In 2024, From Screenshots to Art The 8 Best Photo Collage Tools</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-in-class-video-production-smooth-editing-skills/"><u>In 2024, In-Class Video Production Smooth Editing Skills</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-unveiling-splitcams-camera-capabilities/"><u>In 2024, Unveiling SplitCam's Camera Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-filter-keys-a-comprehensive-windows-guide/"><u>Mastering Filter Keys: A Comprehensive Windows Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-faulty-windows-apps/"><u>Mastering the Art of Fixing Faulty Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-startup-configurations/"><u>Mastering Windows Startup Configurations</u></a></li>
<li><a href="https://hardware-help.techidaily.com/microsoft-windows-bluetooth-drivers-free-downloads-and-latest-updates/"><u>Microsoft Windows Bluetooth Drivers: Free Downloads and Latest Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-windows-11-load-with-smart-media-management/"><u>Optimizing Windows 11 Load with Smart Media Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-internal-server-errors-windows-1011-tips/"><u>Overcoming Internal Server Errors: Windows 10/11 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unsupported-boots-in-windows-the-5-essential-fixes/"><u>Overcoming Unsupported Boots in Windows: The 5 Essential Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-troubleshoot-steps-to-resurrect-xbox-app/"><u>Quick Troubleshoot Steps to Resurrect Xbox App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-the-aesthetic-load-of-windows-search/"><u>Reducing the Aesthetic Load of Windows Search</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-normal-operations-fixing-windows-enter-key-issues/"><u>Reinstating Normal Operations: Fixing Windows Enter Key Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-windows-to-its-fundamental-backup-state/"><u>Resetting Windows to Its Fundamental Backup State</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionizing-ui-8-bubble-ui-personalization-tricks-for-win1011/"><u>Revolutionizing UI: 8 Bubble UI Personalization Tricks for Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safeguard-windows-effortlessly-with-these-free-generators/"><u>Safeguard Windows Effortlessly with These Free Generators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-minimizing-minecraft-crashes-in-windows/"><u>Solutions for Minimizing Minecraft Crashes in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-battlenet-access-in-windows-1011-operating-system/"><u>Streamlining Battle.net Access in Windows 10/11 Operating System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-overcoming-the-error-the-definitive-guide-to-fixed-xbox-game-passwindows-11/"><u>Swiftly Overcoming the Error: The Definitive Guide to Fixed Xbox Game Pass/Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-for-win-based-file-conversions/"><u>The Ultimate Guide for Win-Based File Conversions</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ing-as-an-online-gaming-content-creator/"><u>Thriving as an Online Gaming Content Creator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-fixing-windows-alpha-key-problems-61-characters/"><u>Tips for Fixing Windows Alpha Key Problems (61 Characters)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-the-default-user-home-path-on-w11-os/"><u>Transforming the Default User Home Path on W11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-impact-of-eradicating-windows-11s-taskbar-chatting-functionality/"><u>Unveiling the Impact of Eradicating Windows 11'S Taskbar Chatting Functionality.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/virtual-vintage-the-dosbox-x-guide-to-classic-pc-gaming/"><u>Virtual Vintage: The DOSBox-X Guide to Classic PC Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-audit-examining-active-connections/"><u>Windows Audit: Examining Active Connections</u></a></li>
</ul></div>




