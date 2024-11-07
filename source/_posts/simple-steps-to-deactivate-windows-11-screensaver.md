---
title: Simple Steps to Deactivate Windows 11 Screensaver
date: 2024-11-04T13:07:31.051Z
updated: 2024-11-07T02:06:23.093Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Simple Steps to Deactivate Windows 11 Screensaver
excerpt: This Article Describes Simple Steps to Deactivate Windows 11 Screensaver
keywords: Deactivate Screen Saver,Disable Windows 11 Screensaver,Turn Off Screensaver,Remove Windows Screensaver,Stop Windows Screensaver,End Screensaver Feature,Cease Windows SafeScreen
thumbnail: https://thmb.techidaily.com/a6017269d4c04c5e1e1b5dd34c08e1f92a0a41c1ec409bdbe7a0807e99cdc6f4.jpg
---

## Simple Steps to Deactivate Windows 11 Screensaver

 Windows 11 has a gorgeous lock screen that serves as a gateway to the system. After that, you encounter the logon screen, which requires a password/PIN/fingerprint. But not everyone needs a lock screen and beautiful wallpaper every time they boot up their system.

 Call it a personal observation, but the lock screen adds an extra step to the login process. So, if you want to remove the lock screen and go directly to the logon screen in Windows 11, this post will offer many methods to do it.

## Why Consider Disabling Your Lock Screen?

 The Windows lock screen is the first barrier to getting to the desktop. It displays a background image, date and time, and app notifications. But if you don't want to see any of those things, then disabling it makes sense. After removing the lock screen, you can go straight to the desktop after entering your PIN/Password. You can also set up a lock screen-free computer for a public computer.

 Disabling the lock screen doesn't remove the logon screen. You still have to input the PIN/Password to enter the system. You can also remove the PIN/Password requirement on the logon screen to go to the desktop faster (and if privacy isn't a concern).

 Now, you are aware of the pros and cons of disabling the lock screen. Here are the four easy methods to disable the lock screen on Windows 11.

## 1\. Use the Group Policy Editor

 The Group Policy Editor is an essential Windows administration tool. You can adjust password requirements, startup programs, and other features. Note that GPE is only available for the Professional, Ultimate, and Enterprise Windows versions. You can refer to our complete[Group Policy Editor guide](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

Here's how to disable the lock screen using Group Policy:

1. Press**Win + R** to launch the**Run** command box on your system.
2. Now, type**gpedit.msc** and hit the**Enter** key to open the**Group Policy Editor** .
3. Then go to the left-hand side panel. Navigate to **Computer Configuration > Administrative Templates > Control Panel > Personalization** .
4. Double-click on the**Do not display the lock screen** option in the Personalization options.  
![Group policy editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/Group-policy-editor-1-1.jpg)
5. A new window with detailed settings for the option will open. The**enabled** option will be active by default which means that the lock screen is active.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144297/7443" target="_top" id="2144297">
  <img src="//a.impactradius-go.com/display-ad/7443-2144297" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144297/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Click on the**Disabled** Radio button to disable the lock screen on your system.  
![Disable lock screen settings in Group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/Group-policy-editor-2.jpg)
7. Now, click on the**Apply** button and click the**OK** button to finalize the changes.
8. You need to restart your system. You will notice that there is no lock screen, and you enter the login screen straight away.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049383/7443" target="_top" id="2049383">
  <img src="//a.impactradius-go.com/display-ad/7443-2049383" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049383/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Use the Registry Editor

 You can also disable the lock screen on Windows by tweaking the registry settings. But make sure to export a copy of your registry for safety purposes. It will help you revert to the previous registry settings in case of corruption. Check our detailed guide on[how to perform a registry backup](https://www.makeuseof.com/windows-11-automatic-registry-backups/) for more info.

Here's how to remove the lock screen through the registry:

1. Press the**Win key + R** to launch the**Run** command box. Now, type**regedit** in the text input box and hit the**Enter** key to launch Registry Editor.
2. Now, paste the following path in the text input area and then hit the enter key: **Computer\\HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Policies\\Microsoft\\Windows**
3. Navigate to the left-hand panel and right-click on the**Windows** key. Then select**New > Key** and name it**Personalization** .  
![Creating a new key in Registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/Registry-editor-lockscreen-1.jpg)
4. Right-click on Personalization and select**New > DWORD (32-bit) Value** . Name it as**NoLockScreen** .

5. Double-click on the**NoLockScreen** value and set the**Value Data** to**1** . Keep the base hexadecimal.
6. Click on**OK** to apply changes and**Restart** your system. You won't see the lock screen when your computer boots up.  
![Adding a DWORD value in Registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/Registry-editor-lockscreen-2.jpg)
7. To bring back the lock screen, revert the**NoLockScreen** key value to**0** .

## 3\. Use Winaero Tweaker

 You can try the Winaero Tweaker app if you find registry tweaking cumbersome. It is a free app that allows you to customize Windows beyond the basic options. The app offers a GUI interface with detailed information about what each option does.

Follow these steps to remove the lock screen with this tool:

1. Go to the[Winaero website](http://winaero.com/download-winaero-tweaker/) and download the app.**Install** the app and launch it.  
![Winaero tweaker home window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/Winaero-tweaker-1.jpg)
2. Now, go to the**Boot and Logon** option on the left-hand side menu.
3. Find the**Disable Lock Screen** option under the**Boot and Logon** section. Click on the**Disable Lock Screen** checkbox.  
![Disable lock screen in Winaero Tweaker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/Winaero-tweaker-2.jpg)
4. Now,**Restart** your system to apply the changes. You will notice that the lock screen doesn't appear anymore.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118305/7443" target="_top" id="2118305">
  <img src="//a.impactradius-go.com/display-ad/7443-2118305" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118305/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Use Ultimate Windows Tweaker

 Like Winaero Tweaker, Ultimate Windows Tweaker is a Windows customization app with a GUI interface. You can disable Windows 11 lock screen with this app with just one click. However, make sure to create a system restore point to avoid breaking an operating system feature.

 Here's how to disable the lock screen on Windows 11 using Ultimate Windows Tweaker:

1. Visit the[Ultimate Windows Tweaker website](https://www.thewindowsclub.com/ultimate-windows-tweaker-4-windows-10) and download the app.
2. Extract the Ultimate Windows Tweaker archive to a new folder.
3. Now, right-click on the**UltimateWindowsTweaker.exe** file, and select the**Run as administrator** option.
4. Click on the**Search for Tweaks** option. Type**disable lock screen** and press the**Enter** key.  
![Ultimate Windows Tweaker Search tool running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/ultimate-windows-tweaker-search-tool.jpg)
5. Double-click on the search result and the corresponding setting will appear in the app. Close the search window.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082530/7443" target="_top" id="2082530">
  <img src="//a.impactradius-go.com/display-ad/7443-2082530" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082530/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Click on the**Disable Lock Screen** checkbox. Then, click on the**Apply Tweaks** button and close the program.  
![Disabling Lock Screen in Ultimate Windows Tweaker on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disabling-lock-screen-in-ultimate-windows-tweaker.jpg)
7. Press**Win + L** to log off. The Windows logon screen will appear instead of the usual lock screen.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885943/19272" target="_top" id="1885943">
  <img src="//a.impactradius-go.com/display-ad/19272-1885943" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885943/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Disable the Lock Screen and Log In Faster

 Using the Group Policy Editor is a bit of a learning curve. Moreover, Windows Home users do not have access to it. So, you can try out the registry tweak to disable the lock screen on Windows 11\. But if you want a GUI tool that helps you customize Windows, then Winaero Tweaker and Ultimate Windows Tweaker are both useful free app alternatives.

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
<li><a href="https://youtube-tips.techidaily.com/024-approved-get-the-facts-about-youtube-keyword-research/"><u>[New] 2024 Approved Get the Facts About YouTube Keyword Research</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-igtvs-top-picks-for-next-weeks-feed-for-2024/"><u>[Updated] IGTV's Top Picks for Next Week's Feed for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-convert-and-share-with-ease-selecting-the-top-flv-to-youtube-applications/"><u>[Updated] In 2024, Convert & Share with Ease Selecting the Top FLV-to-YouTube Applications</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-elevating-your-teaching-toolkit-how-to-craft-exceptional-videos-for-learning/"><u>[Updated] In 2024, Elevating Your Teaching Toolkit How to Craft Exceptional Videos for Learning</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-from-unverified-beginnings-to-high-flying-fame-on-instagram-unveil-the-6-keys/"><u>[Updated] In 2024, From Unverified Beginnings to High-Flying Fame on Instagram Unveil the 6 Keys</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-transforming-social-media-traffic-into-revenue/"><u>2024 Approved Transforming Social Media Traffic Into Revenue</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/a-comprehensive-list-selecting-best-free-srt-translators-for-2024/"><u>A Comprehensive List Selecting Best FREE SRT Translators for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-win32keygen-virus-steps-for-secure-removal/"><u>Deciphering Win32/Keygen Virus: Steps for Secure Removal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-network-analysis-win-ipandmac-via-powershell/"><u>Enhancing Network Analysis: Win IP&MAC via PowerShell</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-infinix-note-30-pro-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Infinix Note 30 Pro Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-i-transferred-messages-from-lava-blaze-2-to-iphone-12xs-max-in-seconds-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How I Transferred Messages from Lava Blaze 2 to iPhone 12/XS (Max) in Seconds | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-failing-displays-a-guide-for-windows-users/"><u>Remedying Failing Displays: A Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-malwarebytes-access-on-windows-10-11-after-failure/"><u>Restoring Malwarebytes Access on Windows 10, 11 After Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-best-windows-way-to-enjoy-classic-quests-in-ultra-hd-via-scummvm/"><u>The Best Windows Way to Enjoy Classic Quests in Ultra-HD via ScummVM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-insiders-guide-unlocking-the-potential-of-windows-connections/"><u>The Insider's Guide: Unlocking the Potential of Windows Connections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transcribing-spoken-language-fast-whisper-desktop-skills/"><u>Transcribing Spoken Language Fast: Whisper Desktop Skills</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-guide-fixing-the-dreaded-steamvr-error-308/"><u>Troubleshooting Guide: Fixing the Dreaded SteamVR Error #308</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-task-managers-misleading-cpu-data/"><u>Troubleshooting Windows Task Manager's Misleading CPU Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-win11s-potential-for-ai-visual-creation-via-paint-cocreator/"><u>Unleashing Win11’s Potential for AI Visual Creation via Paint Cocreator</u></a></li>
</ul></div>

