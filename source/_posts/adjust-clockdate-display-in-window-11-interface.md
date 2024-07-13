---
title: Adjust Clock/Date Display in Window 11 Interface
date: 2024-07-12T18:02:43.987Z
updated: 2024-07-13T18:02:43.987Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjust Clock/Date Display in Window 11 Interface
excerpt: This Article Describes Adjust Clock/Date Display in Window 11 Interface
keywords: Set Windows Date,Adjust Window Time,Update Windows Display,Customize Date View,Alter Windows Calendar,Change Clock Appearance,Modify System Dates
thumbnail: https://thmb.techidaily.com/a3a9fc7f1967fe6814b7bcf229ad0c8c09fecb880f152e3279a23ce2f1e6acd7.jpg
---

## Adjust Clock/Date Display in Window 11 Interface

 The system tray clock on the right side of the Windows taskbar shows the date and time. While most users find this information useful, others might consider it a source of distraction.

 As such, if you want to hide the clock and date from the taskbar, then this is the place where you need to be. We'll share three different ways by which you can configure the taskbar to hide or show the clock and date.

## 1\. Hide or Show the Clock and Date from the Taskbar by Using Windows System Settings

 The System Settings is the central hub of a Windows PC. You can use it to update Windows, manage privacy settings,[customize the taskbar](https://www.makeuseof.com/windows-11-customize-taskbar/) , and more.

 It's also one of the places from where you can configure the taskbar to hide or show the clock and date. You can do this by following the below instructions:

 This method only works for Windows 10\. If you are using Windows 11, you can try any other method in this article.

1. Open the**Settings** menu by pressing the**Win + I** hotkeys.
2. Choose the**Personalization** option.
3. Select**Taskbar** from the left panel.
4. Scroll down and click the**Turn system icon on or off** option under the**Notification** area.  
![Turn system icons on or off option in Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-system-icons-on-or-off.png)
5. In the new window that crops up, disable the toggle next to**Clock.**  
![Disable the Clock in System Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-clock.png)

 That's it. You've disabled the clock and date from the taskbar.

 To enable them again, head towards the above settings again and enable the toggle.

## 2\. Hide or Show the Clock and Date from the Taskbar by Using the Local Group Policy Editor

 The next utility that will help you hide or show the clock and date from the taskbar is the Local Group Policy Editor. You can use this utility to manage Windows features, sign-in and shutdown processes, and more.

 The Local Group Policy Editor is disabled by default in the Windows Home edition. To enable it, check out our guide on how to [access the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 Nevertheless, here's how to use Local Group Policy Editor to configure the taskbar to hide the clock and date.

1. Open the Run dialog box, type**gpedit.msc,** and press Enter.
2. In the Local Group Policy Editor, select the**Administrative Templates** folder under**User configuration.**
3. Click the**Start Menu and Taskbar** folder.
4. Click the**Setting** option in the right pane.
5. Search for and right-click on the**Remove Clock from the system notification area** policy. Then, choose**Edit** from the context menu.
6. In the policy edit window, choose the**Enabled** option.  
![Disabling Clock and Date using the local group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disabling-clock-and-date.jpg)
7. Click**Apply** \>**OK** to save the changes.

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

## 3\. Hide or Show the Clock and Date from the Taskbar Using the Registry Editor

 The [Registry Editor](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is an extensive database of your Windows operating system configuration settings. You can use it to navigate the registry and edit its keys.

 Here's how to use the Registry Editor to hide the clock and date from the taskbar:

1. In the Run dialog box, type**regedit** and click**OK.** It'll [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Navigate to the following location:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies`
3. Right-click on the**Policies** key in the left panel, choose**New,** and then select**Key.**
4. Name the key**Explorer** and press Enter.  
![Creating new key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/creating-new-key.jpg)
5. In the Explorer key, right-click on the blank space, and choose**New** \>**DWORD (32-bit Value)** .
6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

## Remove Any Distraction from the Taskbar

 The system tray clock helps you to keep track of the date and time. But if it has become a distraction or you want to keep the taskbar clean, you can use either of the above methods to configure the taskbar to hide the clock and date.


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
<li><a href="https://win11-tips.techidaily.com/adjusting-lockout-interval-after-unsuccessful-windows-sign-in/"><u>Adjusting Lockout Interval After Unsuccessful Windows Sign In</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-elevating-your-youtube-presence-with-effective-tags-for-2024/"><u>[New] Elevating Your YouTube Presence with Effective Tags for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bargain-alert-key-enthusiasts-snag-612lifetime-windows-11-deal-today-only/"><u>Bargain Alert: Key Enthusiasts Snag $6.12/Lifetime Windows 11 Deal Today Only</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-gaming-tuning-amd-radeon-settings/"><u>Boost Your Gaming: Tuning AMD Radeon Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/backup-basics-cloning-without-external-help/"><u>Backup Basics: Cloning Without External Help</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-latest-series-captivating-qanda-for-podcast-audience/"><u>2024 Approved  Latest Series  Captivating Q&A for Podcast Audience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-resources-windows-task-management/"><u>Balancing Resources: Windows Task Management</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-prime-psd-visual-enhancements/"><u>[New] Prime PSD Visual Enhancements</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-the-complete-handbook-to-adding-auditory-elements-to-ae-projects-revised/"><u>Updated In 2024, The Complete Handbook to Adding Auditory Elements to AE Projects, Revised</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginners-guide-to-component-services-on-windows-11/"><u>Beginner’s Guide to Component Services on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/antivirus-alert-7-significant-windows-functions-under-scrutiny/"><u>Antivirus Alert: 7 Significant Windows Functions Under Scrutiny</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-power-visibility-customizing-full-charge-alerts-for-win11/"><u>Boost Power Visibility: Customizing Full Charge Alerts for Win11</u></a></li>
<li><a href="https://video-capture.techidaily.com/capture-comprehensive-screen-shot-for-2024/"><u>Capture Comprehensive Screen Shot for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-expert-techniques-in-creating-timelapses-on-black-hero5/"><u>In 2024, Expert Techniques in Creating Timelapses on Black Hero5</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-quick-focus-effortless-viewport-changes-on-iphone/"><u>[Updated] Quick Focus  Effortless Viewport Changes on iPhone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-ancient-tech-upgrade-with-atlasos/"><u>Boost Ancient Tech: Upgrade with AtlasOS</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-mastering-the-art-of-instagrams-visual-storytelling/"><u>In 2024, Mastering the Art of Instagram's Visual Storytelling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/atlasos-makeover-new-life-for-vintage-pcs/"><u>AtlasOS Makeover: New Life for Vintage PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-by-mastering-task-management-on-a-windows-11-pc/"><u>Boost Productivity by Mastering Task Management on a Windows 11 PC</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-time-lapse-mastery-the-best-mobile-apps-for-creating-breathtaking-videos-for-2024/"><u>New Time-Lapse Mastery The Best Mobile Apps for Creating Breathtaking Videos for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-bypassing-edgenuity-a-guide-to-focused-self-study/"><u>In 2024, Bypassing Edgenuity  A Guide to Focused Self-Study</u></a></li>
<li><a href="https://win11-tips.techidaily.com/app-aesthetics-overshadowing-computational-efficiency-issues/"><u>App Aesthetics Overshadowing Computational Efficiency Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-security-with-vbox-turn-onoff-secure-boot-and-tpm/"><u>Boost Security with VBox: Turn On/Off Secure Boot & TPM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-ssd-performance-with-windows-and-ssd-fresh/"><u>Boosting SSD Performance with Windows & SSD Fresh</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-from-boring-to-breathtaking-insta-video-tips/"><u>[New] In 2024, From Boring to Breathtaking  Insta Video Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bitguard-compromised-continue-now-not-tomorrow/"><u>BitGuard Compromised: Continue Now, Not Tomorrow</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-windows-capacity-securely-without-erasing-files/"><u>Boost Windows Capacity Securely without Erasing Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assessing-your-windows-11-activation-status/"><u>Assessing Your Windows 11 Activation Status</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-enhancing-your-mac-installation-manual-for-sierra-version/"><u>2024 Approved  Enhancing Your Mac  Installation Manual for Sierra Version</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-unpacking-features-a-deep-dive-into-free2xs-tools/"><u>2024 Approved  Unpacking Features  A Deep Dive Into Free2X's Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-editing-setup-office-products-word-for-text-only-opened-attachments/"><u>Avoid Editing: Setup Office Products (Word) for Text Only Opened Attachments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-a-blank-desktop-win-11-icon-fixes/"><u>Avoid a Blank Desktop: Win 11 Icon Fixes</u></a></li>
</ul></div>
