---
title: How to Turn Your Terminal Back To Standard (Win11)
date: 2024-09-11T01:28:27.362Z
updated: 2024-09-12T01:28:27.362Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Turn Your Terminal Back To Standard (Win11)
excerpt: This Article Describes How to Turn Your Terminal Back To Standard (Win11)
keywords: Win11 Terminal Defaults,Restore Terminal Settings,Terminal Configuration Win11,Win11 Command Prompt,Terminal Baseline Windows,Win11 Terminal Revert,Standard Terminal Win11
thumbnail: https://thmb.techidaily.com/3371d97eae392c322e9b82d456ad7eef262a0a211072cf38379ccece2b069d93.jpg
---

## How to Turn Your Terminal Back To Standard (Win11)

 Windows Terminal is the next-generation command line platform in Windows 11\. It provides an improved user experience with modern command line tools that enable you to access multiple command lines in a single window. The tool is essential for developers and administrators alike, but sometimes your terminal settings need to be reset to default.

 In this article, we will explain how to reset your Windows Terminal settings back to their original state.


>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>







<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098701/14409" target="_top" id="2098701">
  <img src="//a.impactradius-go.com/display-ad/14409-2098701" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098701/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Why Would You Reset Your Windows Terminal?

 Windows Terminal is an amazing tool for power users and developers. It allows you to access a variety of tools, all in one place, with custom settings and themes that make it easy to work from anywhere. But over time, your Windows Terminal may become cluttered with old settings or themes that have become redundant or are no longer relevant.

 It also helps clear out any potentially harmful malware or corrupt files that might be lurking in the background of your system, hindering your productivity. By doing so, you will ensure that your computer works as fast and as smoothly as possible - giving you the most optimal experience when using this powerful tool.

 Let's now move to the below sections and see how it can be reset.





<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139110/17108" target="_top" id="2139110">
  <img src="//a.impactradius-go.com/display-ad/17108-2139110" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139110/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## How to Reset Windows Terminal Settings by Clearing JSON Files

 In order to reset the settings back to the original defaults, you will need to delete the settings.json file. Here's how to do it.

1. Right click on Start and select**Terminal** from the menu list.
2. Next, click the down-arrow icon and select**Settings** .
3. From the left pane of the Settings page, click**Open JSON file** .  
![Open JSON file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-json-file.jpg)
4. If you're asked which app to use to open the file, then double-click on**Notepad** .




<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123469/16836" target="_top" id="2123469">
  <img src="//a.impactradius-go.com/display-ad/16836-2123469" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123469/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




5. On the next page, select all the contents and**Delete** them.
6. Now press**Ctrl + S** on your keyboard to save it.

 Next time you open the app, a new configuration with all the default settings will be created automatically.





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115920/19272" target="_top" id="2115920">
  <img src="//a.impactradius-go.com/display-ad/19272-2115920" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115920/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## How to Reset Windows Terminal Settings Using Command Prompt

 The Command Prompt is a command line tool that can help you accomplish a number of tasks on your computer. It lets you run programs, manage files, and even troubleshoot problems with the operating system. We covered a lot of its functionality in our[beginner's guide to the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) , but for now, we'll just explore resetting the Windows Terminal settings.

 To reset Windows Terminal Settings back to their defaults, follow these steps:

1. Open the Command Prompt. For this, use the Taskbar search or type "cmd" in the Run dialog.
2. In the Command Prompt window, copy and paste the following command:  
![Reset Windows Terminal Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-command-prompt.jpg)  
del /f /s /q /a "%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json"




<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137974/21526" target="_top" id="2137974">
  <img src="//a.impactradius-go.com/display-ad/21526-2137974" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137974/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




3. Now press the**Enter** key to delete the settings.json file.
4. You can now exit the command prompt.

## How to Reset Windows Terminal Settings Using Windows PowerShell

 Windows PowerShell is another command line application that you can use to restore Windows Terminal Settings to their default state. To figure out how, follow these steps:

1. Open Windows PowerShell. You can do this by pressing**Win + R** , typing "PowerShell", and then pressing**Enter** . You can also one of the other[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
2. In the PowerShell window, copy and paste the following command:  
![Reset Windows Terminal Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-powershell.jpg)  
Remove-Item -Path "$env:LOCALAPPDATA\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json" -Force
3. Press**Enter** to execute the command.

## How to Reset Windows Terminal Settings From File Explorer

 If you don't prefer the command line process, you can use Windows File Explorer to reset the settings. In this way, the Terminal will be reset to its default settings, and you can continue using it. Here's how to do it:

1. Open Windows File Explorer. For this, right-click Start and choose**File Explorer** , or press**Win + E** on your keyboard.
2. Copy and paste the following path into the address bar:  
![Reset Windows Terminal Using File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-file-explorer.jpg)  
%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState
3. On the next page, right-click on**settings.json** and select**Delete** from the context menu.

 Once you perform the above steps, Settings.json will automatically be created with the default settings.





<!-- affiliate ads begin -->
<span id="1993647">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993647.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993647">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993647.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993647%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993647/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Resetting the Windows Terminal, Made Easy

 After reading this post, you now know some useful tips that will help you reset the terminal to default settings in Windows 11\. Try them out and find out which one works best for you.


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
<li><a href="https://youtube-lab.techidaily.com/024-approved-enhancing-visuals-the-role-of-a-tripod-in-video-content/"><u>[New] 2024 Approved Enhancing Visuals The Role of a Tripod in Video Content</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-seamless-chromeos-screeen-logging/"><u>[New] 2024 Approved Seamless ChromeOS Screeen Logging</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-ranking-creative-photo-and-video-shows-on-iphones-xr-i-for-2024/"><u>[New] Ranking Creative Photo & Video Shows on iPhones (XR-I) for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-become-a-youtube-star-essential-skills-training/"><u>[Updated] 2024 Approved Become a YouTube Star Essential Skills Training</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-obs-and-streamlabs-battle-who-will-triumph-in-live-broadcasts/"><u>[Updated] 2024 Approved OBS and Streamlabs Battle Who Will Triumph in Live Broadcasts?</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-mastering-the-craft-of-igtv-video-production-with-phones-and-dslrs-for-2024/"><u>[Updated] Mastering the Craft of IGTV Video Production with Phones and DSLRs for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-tiktok-profile-boost-smartly-insert-linktree-into-about-section/"><u>[Updated] TikTok Profile Boost Smartly Insert Linktree Into About Section</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-easy-setup-making-a-direct-path-for-youtube-subscribers/"><u>2024 Approved Easy Setup Making a Direct Path for YouTube Subscribers</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-economical-desktop-encoder-software-guide-revealed/"><u>2024 Approved Economical Desktop Encoder Software Guide Revealed</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-mastering-filming-techniques-on-tiktok-platforms/"><u>2024 Approved Mastering Filming Techniques on TikTok Platforms</u></a></li>
<li><a href="https://activate-lock.techidaily.com/bypass-icloud-activation-lock-with-imei-code-on-your-apple-iphone-11-by-drfone-ios/"><u>Bypass iCloud Activation Lock with IMEI Code On your Apple iPhone 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-dual-displays-in-windows-11-easy-guide/"><u>Configuring Dual Displays in Windows 11 Easy Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decision-guide-choosing-a-superior-windows-coder/"><u>Decision Guide: Choosing a Superior Windows Coder</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/demystifying-youtube-shorts-content-strategy-guide-for-2024/"><u>Demystifying YouTube Shorts Content Strategy Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diagnosing-missing-display-in-boot-sequence/"><u>Diagnosing Missing Display in Boot Sequence</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/easy-steps-on-how-to-create-a-new-apple-id-account-on-iphone-12-mini-by-drfone-ios/"><u>Easy Steps on How To Create a New Apple ID Account On iPhone 12 mini</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-windows-methods-to-record-conversations/"><u>Effective Windows Methods to Record Conversations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-security-with-extended-pins-on-win1011/"><u>Elevate Security with Extended PINs on Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/error-2e-in-windows-how-to-resume-update-process/"><u>Error 2E in Windows: How to Resume Update Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-0x80072efd-a-windows-store-error-solution/"><u>Fixing 0X80072EFD: A Windows Store Error Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-errors-with-copypaste-feature-on-windows-11/"><u>Fixing Errors with Copy/Paste Feature on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hacks-improve-reading-of-excel-data-on-windows-notepad/"><u>Hacks: Improve Reading of Excel Data on Windows Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-sign-out-other-users-on-windows-11/"><u>How to Sign Out Other Users on Windows 11</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-your-iphone-13-pro-passcode-4-easy-methods-with-or-without-itunes-drfone-by-drfone-ios/"><u>How to Unlock Your iPhone 13 Pro Passcode 4 Easy Methods (With or Without iTunes) | Dr.fone</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-elevating-speech-synthesis-converting-ssaxml-to-professional-srts/"><u>In 2024, Elevating Speech Synthesis Converting SSA/XML to Professional SRTs</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-vivo-y78t-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Vivo Y78t to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-premier-video-editors-transforming-igtv-videos/"><u>In 2024, Premier Video Editors Transforming IGTV Videos</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-top-tier-hdr-cameras-explained-and-compared/"><u>In 2024, Top-Tier HDR Cameras Explained & Compared</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-administrative-access-through-cmd/"><u>Leveraging Administrative Access Through CMD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-guide-to-restore-lost-pin-after-win-11-crashes/"><u>Master Guide to Restore Lost PIN After Win 11 Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-browser-interactivity-enable-gesture-navigation-in-windows-11s-edge/"><u>Maximizing Browser Interactivity: Enable Gesture Navigation in Windows 11'S Edge</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-free-dailymotion-converter-download-and-convert-videos-in-seconds-for-2024/"><u>New Free Dailymotion Converter Download and Convert Videos in Seconds for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-stream-your-personal-video-collection-to-chromecast-a-beginners-guide/"><u>New Stream Your Personal Video Collection to Chromecast A Beginners Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-and-streamline-commands-in-modern-windows-systems/"><u>Optimize and Streamline Commands in Modern Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/outpace-the-windowed-wired-limit-transcending-100mbps-on-windows-pcs/"><u>Outpace the Windowed Wired Limit: Transcending 100Mbps on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfectly-positioned-win11s-6-image-rotation-methods/"><u>Perfectly Positioned: Win11's 6 Image Rotation Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rejuvenate-right-click-menus-with-effective-fixes/"><u>Rejuvenate Right-Click Menus with Effective Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-connection-breakdown-with-mbs-services-in-windows-11/"><u>Resolving Connection Breakdown with MB's Services in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversal-of-read-only-settings-in-windows-11-storage/"><u>Reversal of Read-Only Settings in Windows 11 Storage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-multidevice-scribbling-with-win11s-notes-feature/"><u>Simplify Multidevice Scribbling with WIN11'S Notes Feature</u></a></li>
<li><a href="https://howto.techidaily.com/super-easy-ways-to-deal-with-nokia-xr21-unresponsive-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Super Easy Ways To Deal with Nokia XR21 Unresponsive Screen | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-made-interface-task-manager-on-win11/"><u>Tailor-Made Interface: Task Manager on Win11</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/the-complete-guide-to-affordable-online-passport-photo-services-for-2024/"><u>The Complete Guide to Affordable Online Passport Photo Services for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-20-critical-command-prompt-commands/"><u>The Ultimate Guide to 20 Critical Command Prompt Commands</u></a></li>
<li><a href="https://buynow-info.techidaily.com/transform-your-workspace-with-the-acer-aspire-c27-high-quality-low-profile-computing/"><u>Transform Your Workspace with the Acer Aspire C27: High Quality, Low Profile Computing</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ultimate-troubleshooting-techniques-correcting-errors-with-ntldr-on-your-computer/"><u>Ultimate Troubleshooting Techniques: Correcting Errors with NTLDR on Your Computer</u></a></li>
<li><a href="https://buynow-help.techidaily.com/unveiling-the-features-and-performance-of-garmin-forerunner-265/"><u>Unveiling The Features and Performance of Garmin Forerunner 265</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-ousting-the-focused-wallpaper-symbol/"><u>Windows 11: Ousting the Focused Wallpaper Symbol</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-system-lifespan-indicator/"><u>Windows System Lifespan Indicator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/your-own-voice-recognition-tool-building-with-ahk-and-whisper-on-windows/"><u>Your Own Voice Recognition Tool: Building with AHK and Whisper on Windows</u></a></li>
</ul></div>




