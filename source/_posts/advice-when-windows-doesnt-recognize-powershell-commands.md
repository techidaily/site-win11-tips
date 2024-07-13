---
title: Advice When Windows Doesn't Recognize PowerShell Commands
date: 2024-07-12T18:08:38.961Z
updated: 2024-07-13T18:08:38.961Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Advice When Windows Doesn't Recognize PowerShell Commands
excerpt: This Article Describes Advice When Windows Doesn't Recognize PowerShell Commands
keywords: PowerShell Command Recognition,Unrecognized Windows Powershell,Resolving PowerShell Errors,Enhancing Powershell Functionality,Troubleshooting Powershell Issues,Improve Windows Powershell Usage,Fixing Commands Not Found in Win10
thumbnail: https://thmb.techidaily.com/34898e0ebb1abca68099d2acba8fac3a4c33b87872f768fed60cc168fcf66601.jpg
---

## Advice When Windows Doesn't Recognize PowerShell Commands

 PowerShell is a handy tool that lets you automate tasks, troubleshoot various errors, and manage a variety of Windows settings. But what if it suddenly goes missing from your computer?

 If you use PowerShell frequently, it can be aggravating when Windows cannot find it. Thankfully, it’s possible to restore the missing PowerShell with a few troubleshooting tips. In this post, we'll walk you through all of them.

## 1\. Make Sure Windows PowerShell Is Enabled

 On Windows, you can enable or disable optional features and programs from the Control Panel. To start, you need to ensure that PowerShell isn’t disabled on your computer. Here’s how to check.

1. Press**Win + R** to open the Run dialog.
2. Type**control** in the box and press**Enter** to open Control Panel.
3. Click the drop-down menu in the top right corner to select**Large icons** .
4. Go to**Programs and Features** .
5. Click the**Turn Windows features on or off** link from the left pane.
6. When the User Account Control (UAC) prompt appears, select**Yes** to continue.
7. In the Windows Features dialog, locate**Windows PowerShell** and select its checkbox.
8. Click**OK** to save the changes.  
![Enable PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Enable-PowerShell-on-Windows.jpg)

 Restart your computer after this (see [how to restart a Windows computer](https://www.makeuseof.com/windows-restart-methods/) ) and then try to launch PowerShell using the search menu.

## 2\. Launch PowerShell Using Run Command or File Explorer

 If you are unable to open PowerShell via the search menu, you can try using the Run dialog box. Press**Win + R** to open the Run dialog. Type**powershell** in the box and press**Enter** . If you want to launch PowerShell with admin rights, press**Ctrl + Shift + Enter** instead.

![Open PowerShell via Run Command on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Open-PowerShell-via-Run-Command-on-Windows.jpg)

 You can also open PowerShell from the File Explorer address bar. To do so, press**Win + E** to open File Explorer. Type**PowerShell** in the address bar and press**Enter** .

## 3\. Create a Desktop Shortcut for PowerShell

 Windows may fail to open PowerShell if it does not know the exact file path to the PowerShell executable file. If that’s the case, you can manually locate the PowerShell executable file on your computer and create a desktop shortcut for it. Here are the steps for doing the same.

1. Right-click on the**Start icon** to open the Power User menu and select**File Explorer** from the list.
2. Navigate to**This PC** .
3. Head over to**C: > Windows > SysWOW64** and locate**WindowsPowerShell** folder.
4. Open the WindowsPowerShell folder and go to the**v1.0** folder.
5. Double-click on the PowerShell executable file and see if it works. If it does, right-click on it and select**Send to > Desktop (create shortcut)** .  
![Create Desktop Shortcut for PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Create-Desktop-Shortcut-for-PowerShell-on-Windows.jpg)

 You can then use the newly created desktop shortcut to launch PowerShell. For added convenience, you can assign a keyboard shortcut to PowerShell. To learn more about this, check our guide on [how to assign keyboard shortcuts to programs in Windows](https://www.makeuseof.com/windows-keyboard-shortcuts-programs/) .

## 4\. Scan Your Computer for Corrupted System Files

 Damaged or corrupted system files can also interfere with Windows operations and prevent PowerShell from launching. Fortunately, your Windows PC comes with a few built-in tools, such as SFC (System File Checker) and DISM (or Deployment Image Servicing and Management) that can help you with such issues. If Windows suffers from system file corruption, running these tools will fix the problem.

To run the SFC scan on Windows:

1. Click the magnifying glass icon on the taskbar or press**Win + S** to open the search menu.
2. Type**command prompt** in the search box and select**Run as administrator** from the right panel.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Type**SFC /scannow** in the console and press**Enter** .

 The SFC scan will start verifying the integrity of your system files and fix any issues with them. The scan might take a while, so be patient.

 Next, you need to run the DISM scan. This is another diagnostic tool that Windows offers. It can automatically detect any issues with the system image and fix them. If you want to learn more about them, check out our guide on the [differences between CHKDSK, SFC, and DISM](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) .

 To run DISM,[open Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) again. Paste the following command in the console and press**Enter** .

`DISM.exe /Online /Cleanup-image /Restorehealth`

![DISM Scan Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/DISM-Scan-Windows.jpg)

 Wait for the command to execute successfully, and then restart your PC. Following that, see if Windows can find PowerShell on your computer.

## 5\. Update Windows PowerShell

 If Windows still can't find PowerShell at this point, there could be a problem with the PowerShell app itself. You can try updating the PowerShell app to see if that makes any difference.

To update PowerShell on Windows:

1. Press**Win + X** to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. When the User Account Control (UAC) prompt shows up, select**Yes** .
4. Type the following command and press**Enter** .  
`winget install --id Microsoft.Powershell --source winget`  
![Update PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Update-PowerShell-on-Windows.jpg)

 Windows will download and install the most recent version of PowerShell. Following that, you should be able to access PowerShell.

 Using Command Prompt isn't the only way to update PowerShell on Windows. If you want to learn other methods, check our guide on [how to install or update PowerShell on Windows](https://www.makeuseof.com/windows-11-powershell-install-update/) .

## 6\. Create a New User Account

 It's possible that the PowerShell not opening problem is limited to your current user account. In that case, you can create and switch to a new user account and see if that works.

To create a new user account on Windows, use these steps.

1. Open the start menu and click the**gear icon** to open the Settings app.
2. Navigate to**Accounts** .
3. Select**Other users** .
4. Click the**Add account** button.
5. Click on **I don't have this person's sign-in information** and follow the on-screen prompts to create a new user account.  
![Microsoft Account Sign-In](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Microsoft-Account-Sign-In.jpg)

 Sign in with your newly created account, and see if Windows can find PowerShell now.

## Access Windows PowerShell Again

 Hopefully, one of the above fixes has proven useful, and you're able to access PowerShell once again. If not, you may have to consider resetting your Windows computer as a last resort.

 PowerShell isn't the only command-line tool available on Windows. You can also use the Command Prompt to communicate with your system.


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
<li><a href="https://win11-tips.techidaily.com/adjust-and-control-windows-screenshots-for-better-use/"><u>Adjust and Control Windows Screenshots for Better Use</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-navigating-voice-logging-on-apples-facetime-service/"><u>[New] Navigating Voice Logging on Apple's FaceTime Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-to-the-latest-windows-11-maintain-linux-subsystem-efficiency/"><u>Adjusting to the Latest Windows 11, Maintain Linux Subsystem Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-your-digital-experience-adding-directories-to-taskbar-menu/"><u>Amplify Your Digital Experience: Adding Directories to Taskbar Menu</u></a></li>
<li><a href="https://facebook.techidaily.com/break-time-unveiling-instagrams-plea-for-digital-detox/"><u>Break Time: Unveiling Instagram's Plea for Digital Detox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/androidwindows-twinning-effortless-sync-instructions/"><u>Android/Windows Twinning: Effortless Sync Instructions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-winerror-740-easy-to-follow-tips-for-windows-users/"><u>Avoiding WinError 740: Easy-to-Follow Tips for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-performance-essential-wsl-2-approaches-for-win-users/"><u>Boost Performance: Essential WSL 2 Approaches for Win Users</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-next-level-play-the-best-gaming-tech-on-display/"><u>In 2024, Next-Level Play  The Best Gaming Tech on Display</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-clashes-among-windows-icons/"><u>Avoid Clashes Among Window's Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-with-these-5-unique-windows-pc-time-saver-tools/"><u>Boost Productivity with These 5 Unique Windows PC Time Saver Tools</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-effortlessly-merge-platforms-tweets-to-instagram-media/"><u>[Updated] 2024 Approved  Effortlessly Merge Platforms  Tweets to Instagram Media</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-pen-tablet-glitches-and-freezes/"><u>Addressing Windows PEN Tablet Glitches and Freezes</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-12-prominent-realme-fingerprint-not-working-solutions-by-drfone-android/"><u>Top 12 Prominent Realme Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/seamless-search-for-your-youtube-comments-across-platforms-for-2024/"><u>Seamless Search for Your YouTube Comments Across Platforms for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-investigative-summary-the-state-of-the-art-in-sound-forges-design/"><u>New In 2024, Investigative Summary The State-of-the-Art in Sound Forges Design</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-system-management-via-cmd/"><u>Boost Your System Management via CMD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-shortcuts-fast-paste-of-set-text/"><u>Advanced Shortcuts: Fast Paste of Set Text</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blue-screen-errors-finding-their-windows-footprint/"><u>Blue Screen Errors: Finding Their Windows Footprint</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/transforming-content-into-multilingual-masterpieces-a-filmora-based-approach-to-video-dubbing/"><u>Transforming Content Into Multilingual Masterpieces A Filmora-Based Approach to Video Dubbing</u></a></li>
<li><a href="https://location-fake.techidaily.com/8-solutions-to-fix-find-my-friends-location-not-available-on-zte-blade-a73-5g-drfone-by-drfone-virtual-android/"><u>8 Solutions to Fix Find My Friends Location Not Available On ZTE Blade A73 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-techniques-for-picture-adjustment-on-windows-11-unveiled/"><u>Advanced Techniques for Picture Adjustment on Windows 11 Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automate-file-disposal-in-windows-for-efficiency-gains/"><u>Automate File Disposal in Windows for Efficiency Gains</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-virtual-disk-startup-issues-in-windows-disk-manager/"><u>Addressing Virtual Disk Startup Issues in Windows Disk Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/audacity-sound-error-step-by-step-windows-fix-guide/"><u>Audacity Sound Error: Step-by-Step Windows Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-windows-flexibility-with-additional-menus/"><u>Boost Windows Flexibility with Additional Menus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-unwanted-updates-in-windows-11-with-proactive-measures/"><u>Avoid Unwanted Updates in Windows 11 with Proactive Measures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/awaken-your-system-conquering-power-save-errors/"><u>Awaken Your System: Conquering Power Save Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/auditory-capture-made-simple-with-microsofts-win-11/"><u>Auditory Capture Made Simple with Microsoft's Win 11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-techniques-for-harvesting-hd-facebook-videos/"><u>[New] Techniques for Harvesting HD Facebook Videos</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-the-compre-written-in-the-stars-harnessing-hidden-opportunities-for-insta-sponsorships/"><u>[New] The Compre Written in the Stars  Harnessing Hidden Opportunities for Insta-Sponsorships</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-delving-into-magix-photo-editors-features-for-2024/"><u>[Updated] Delving Into MAGIX Photo Editor's Features for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-frustrations-mastering-windows-11-management-tool-access/"><u>Avoiding Frustrations: Mastering Windows 11 Management Tool Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/asus-s15-oled-experience-merging-chic-and-versatile-features/"><u>Asus S15 OLED Experience: Merging Chic & Versatile Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-code-ai-reshaping-windows-tech-landscape/"><u>Beyond Code: AI Reshaping Windows Tech Landscape</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-typing-velocity-with-windows-powertools/"><u>Boost Typing Velocity with Windows' PowerTools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-automatic-windows-updates/"><u>Banishing Automatic Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-privilege-levels-for-non-administrators-on-windows-os/"><u>Altering Privilege Levels for Non-Administrators on Windows OS</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-pathway-to-popular-youtube-thumbnails-mac-edition/"><u>In 2024, The Pathway to Popular Youtube Thumbnails  Mac Edition</u></a></li>
</ul></div>
