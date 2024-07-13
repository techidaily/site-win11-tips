---
title: "Advanced Windows Customization via CLI: Registry Edition"
date: 2024-07-12T17:11:42.567Z
updated: 2024-07-13T17:11:42.567Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Advanced Windows Customization via CLI: Registry Edition"
excerpt: "This Article Describes Advanced Windows Customization via CLI: Registry Edition"
keywords: Windows CLI Editing,Registry Tweaking,WinCLI Tools,System Configuring,Command Line Windows,Advanced Customization,Windows Registry CLI
thumbnail: https://thmb.techidaily.com/8952485f60295f3d1e3d2e7fb384d7f4849fc0ba1ac13c5b58f754ed696cbd0a.jpg
---

## Advanced Windows Customization via CLI: Registry Edition

 The Registry Editor is the first thing Windows users bring up when it comes to editing the Windows Registry. However, if you don't want to deal with a distracting GUI and too many clicks, there's a simpler-looking tool you can use: the Command Prompt.

 Although using it takes a little more know-how than the Registry Editor, our guide should be able to get you started.

## How to View the List of Registry Commands in Command Prompt
![the command to view all reg commands](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/the-command-to-view-all-reg-commands.jpg)

 There aren't a lot of commands when it comes to editing the registry using Command Line. To view them all, [open Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) and run the below command in Command Prompt:

`reg /?`

 Command Prompt will then list the commands, such as **reg add**, **reg delete**, **reg copy**, and **reg save**.

![the list reg commands in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/the-list-reg-commands-in-command-prompt.jpg)

 If you want to see more information about them, just add the **/?** switch at the end of the command. For, example, if you want to find out what the **reg add** command does, you'd enter the below command:

`reg add /?`

 After you run it, you'll get all the details on what it does and how to use it.

![details of the reg add command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/details-of-the-reg-add-command-in-command-prompt.jpg)

 If you're finding it hard the commands out on your own, don't worry. We will simplify it for you and show you how to get started using them.

## Add and Delete Keys in the Windows Registry

 To add a key to the registry using Command Prompt, you need to use the **reg add** command while specifying the path to the new key and whether you want to force the operation with the **/f** switch(this will bypass the need for the confirmation prompt).

 As always, when it comes to editing the Windows Registry, we recommend that the first thing you do is [create a system restore point on Windows](https://www.makeuseof.com/use-system-restore-windows/).

 Here's an example:

`REG Add HKLM\SOFTWARE\MyNewKey /f`

 In the above command, we're adding the **MyNewKey** subkey to the **KHLM/Software** key. If you go to the Registry Editor and expand that key, you'll be able to see the **MyNewKey** subkey within it.

 Deleting the key is simple as well, as you just need to replace **add** with **delete** in the above example. Here's how:

`reg delete HKLM\SOFTWARE\MyNewKey /f`

 Now the **MySubKey** key will disappear in the Registry Editor.

## How to Add, Modify, and Delete Values in the Windows Registry
![adding a value to Windows registry in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/adding-a-value-to-windows-registry-in-command-prompt.jpg)

 To add or modify a value key in the registry using Command Prompt, you'll still use the **reg add** command like above. However, this time, you'll also have to specify the following parameters: value (**/v**), value type (**/t**), and value data (**/d**). Here's an example of what the command would like:

`reg add HKLM\SOFTWARE\MyNewKey /v MyValue /t REG_DWORD /d "1" /f`

 Once you run the command, you will be able to find the value in the Registry Editor. And if the key doesn't exist, Command Prompt will create it.

 The Windows Registry uses several value types, and here's a table of the common ones:

| Value Type      | Description           |
| --------------- | --------------------- |
| REG\_NONE       | No value type         |
| REG\_SZ         | String value          |
| REG\_MULTI\_SZ  | Multi-string value    |
| REG\_EXPAND\_SZ | Expanded string value |
| REG\_DWORD      | 32-bit DWORD value    |
| REG\_QWORD      | 64-bit QWORD value    |
| REG\_BINARY     | Binary value          |

 To delete the value, you just need to use the **reg delete** command while specifying the path to the key, and the name of the value. Here's an example of deleting the value we created earlier:

`reg delete HKLM\SOFTWARE\MyNewKey /v MyValue /f`

 After running the above command successfully, the value should disappear from the Registry Editor.

## How to Copy Registry Entries From One Key to Another
![transfering entries from one registry key to another in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/transfering-entries-from-one-registry-key-to-another-in-command-prompt.jpg)

 Sometimes, you might want to copy the values from one key to another in the registry. This is as easy as using the **reg copy** command while specifying the key you're copying them from and the one you're copying them to (keep in mind that both keys have to already exist before you run the command). Here's an example:

`reg copy HKLM\SOFTWARE\MyNewKey1 HKLM\SOFTWARE\MyNewKey2 /s`

 The **/s** switch at the end tells Command Prompt that it should copy every subkey and value in the first key (**MyNewKey1**) into the second one (**MyNewKey2**).

 Unfortunately, there's no way to copy specific values from one key to another. You'll have to use the Registry Editor for that.

## How to Import Registry Entries
![importing a registry file in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/importing-a-registry-file-in-command-prompt.jpg)

 If you have [created a Windows Registry file](https://www.makeuseof.com/windows-registry-file-guide/) or downloaded it elsewhere, you can import it into the registry using the **reg import** command. All you need to do is specify the path to the registry file and Command Prompt will do the rest. Here's an example:

`reg import C:\Users\CHIFUNDO\Desktop\MyRegFile.reg`

 Once you run that command, the contents of the reg file will be merged with the registry.

## How to Export Registry Entries
![exproting a registry key in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/exproting-a-registry-key-in-command-prompt.jpg)

 You can export a key in the registry using the **reg export** command while specifying the path of the key you want to export and the file you want to create. This comes in handy when you need to back up certain keys and values to restore them elsewhere. Here's an example:

`reg export "HKLM\SOFTWARE\MyNewKey" D:\Reg_Backup\CHIFUNDO\Desktop\MyRegFile.reg`

 After you run the command successfully, check the location you entered, and you'll find the key and its associated subkeys and values have been exported successfully. In our case, it will create a file called **MyRegFile.reg** and save it on the desktop.

 You can also export a specific value using the **reg query** command and include the key, value, and path to the registry file you want to export the value to. Here's an example.

`reg query HKLM\SOFTWARE\MyNewKey /v MyValue > C:\Users\CHIFUNDO\Desktop\MyRegFile.reg`

 The resulting registry file will only contain the key and the specific value you exported.

## How to Save Registry Entries
![saving-a-key-to-a-registry-file-in-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/saving-a-key-to-a-registry-file-in-windows.jpg)

 If you already have a registry file or any other text file, you can add keys to it using Command Prompt and the **reg save** command, which will overwrite the file with the new information. You just need to specify the name of the key and the registry file you want to save it to. Here's an example:

`reg save HKLM\SOFTWARE\MyNewKey2 C:\Users\CHIFUNDO\Desktop\MyRegFile.hiv /y`

 The **/y** switch at the end of the command above overwrites the file you're saving the key to without bringing up a prompt. When you open the file, you won't be able to read the contents since it will be saved as a binary file.

## How to Restore Registry Entries
![restoring-a-registry-key-in-command-prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/restoring-a-registry-key-in-command-prompt.jpg)

 So, let's say something has happened to the keys and values within the **MyNewKey2** we saved in the previous section, you can use the backup file you created to restore it. You'll need to use the **reg restore** command. Here's how to run it:

`reg restore HKLM\SOFTWARE\MyNewKey2 C:\Users\CHIFUNDO\Desktop\MyRegFile.hiv`

 Now the **MyNewKey2** key should return to the state it was in when you made the backup.

## Tweak the Registry Without the Registry Editor

 While Command Prompt can't do everything the Registry Editor does, it does offer a quick way to edit the registry without opening the aforementioned tool. While using Command Prompt to tweak the registry is quite advanced, even if you're the average user, you should be able to get by if you follow along closely.

 Just don't forget to do what we mentioned earlier to avoid permanently ruining your Windows computer and create a system restore point first

 Although using it takes a little more know-how than the Registry Editor, our guide should be able to get you started.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-discovering-facebooks-quintessential-updates/"><u>[New] 2024 Approved  Discovering Facebook's Quintessential Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-new-depths-noteworthy-alterations-in-windows-11s-interface/"><u>Exploring New Depths: Noteworthy Alterations in Windows 11'S Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-device-connectivity-troubleshooting-on-win-os/"><u>Mastering Device Connectivity Troubleshooting on Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-spotify-application-is-not-responding-error-in-windows-11-and-11/"><u>How to Fix the “Spotify Application Is Not Responding” Error in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-quickly-remove-bloatware-from-windows-11/"><u>How to Quickly Remove Bloatware From Windows 11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-explore-multimedia-craftsmanship-with-xp-movie-maker/"><u>[New] Explore Multimedia Craftsmanship with XP Movie Maker</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-from-footage-to-fortune-unveiling-the-secrets-of-sj-cam-s6/"><u>[New] From Footage to Fortune  Unveiling the Secrets of SJ-CAM S6</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unrestricted-media-playback-free-on-windows-and-macos/"><u>[Updated] Unrestricted Media Playback  FREE on Windows & MacOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-apply-local-group-policies-to-a-specific-user-account-in-windows-10-and-11/"><u>How to Apply Local Group Policies to a Specific User Account in Windows 10 and 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-11-fixes-22h2-edition/"><u>Essential Windows 11 Fixes: 22H2 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-how-to-resolve-windows-11s-nvidia-cp-issue/"><u>Quick Guide: How to Resolve Windows 11'S Nvidia CP Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-starting-csgo-in-w11/"><u>Mastering the Art of Starting CS:GO in W11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-top-12-tycoons-where-every-decision-forges-your-path-to-glory/"><u>In 2024, Top 12 Tycoons - Where Every Decision Forges Your Path to Glory</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-virtual-disk-service-not-started-in-windows/"><u>Remedy for Virtual Disk Service Not Started in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-messages-failed-to-load-error-on-discord-for-windows/"><u>How to Fix the Messages Failed to Load Error on Discord for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-discord-from-launching-at-startup-and-searching-for-updates-on-windows/"><u>How to Stop Discord From Launching at Startup and Searching for Updates on Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-best-free-iphone-11-pro-imei-checker-by-drfone-ios/"><u>In 2024, Best Free iPhone 11 Pro IMEI Checker</u></a></li>
<li><a href="https://extra-information.techidaily.com/navigating-the-landscape-of-motion-sensing-technology/"><u>Navigating the Landscape of Motion Sensing Technology</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-efficiency-in-windows-photos-via-shortcuts/"><u>Maximize Efficiency in Windows Photos via Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-audio-service-restart-process-before-boot-up/"><u>Simplifying Audio Service Restart Process Before Boot Up</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-exploring-remote-desktop-capabilities-within-zoom-on-win11/"><u>2024 Approved  Exploring Remote Desktop Capabilities Within Zoom on Win11</u></a></li>
<li><a href="https://extra-information.techidaily.com/10-ultimate-online-destinations-for-enigmatic-boxes/"><u>10 Ultimate Online Destinations for Enigmatic Boxes</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-vivo-y27-5g-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Location is Not Updating and How to Fix On Vivo Y27 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-jot-down-techniques-in-windows-11-no-apps/"><u>Quick Jot-Down Techniques in Windows 11, No Apps</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-transformative-tools-for-uploading-videos-to-twitter/"><u>2024 Approved  Transformative Tools for Uploading Videos to Twitter</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/unraveling-facebooks-latest-hits-a-rundown-of-top-vids/"><u>Unraveling Facebook's Latest Hits  A Rundown of Top Vids</u></a></li>
<li><a href="https://win11-tips.techidaily.com/routine-steps-to-engage-windows-11s-calculator/"><u>Routine Steps to Engage Windows 11'S Calculator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restarting-affected-windows-netflix-functions/"><u>Restarting Affected Windows Netflix Functions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-disconnection-issues-with-ea-services-in-win/"><u>Overcoming Disconnection Issues with EA Services in Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-batch-renaming-like-a-pro-with-powertoys/"><u>Master Batch Renaming Like a Pro with PowerToys</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-exclusive-photo-safekeeping-top-free-and-paid-cloud-storage-solutions/"><u>2024 Approved  Exclusive Photo Safekeeping  Top Free & Paid Cloud Storage Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-unique-devices-names-erase-in-use-issues-on-pcs/"><u>Mastering Unique Devices Names: Erase 'In Use' Issues on PCs</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-top-strategies-to-boost-your-obs-editing-skills/"><u>[Updated] 2024 Approved  Top Strategies to Boost Your OBS Editing Skills</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securely-building-win11-self-extractables/"><u>Securely Building Win11 Self-Extractables</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slaying-windows-beast-error-code-0xc00ce556/"><u>Slaying Window's Beast Error: Code 0xC00CE556</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/5-video-editing-platforms-that-dont-feature-in-youtoo-for-2024/"><u>Best 5 Video Editing Platforms That Don't Feature in YouToo for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-core-principles-in-crafting-persuasive-facebook-ads/"><u>[Updated] Core Principles in Crafting Persuasive Facebook Ads</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-pixelpilots-perspective-leading-screen-recording-tools-of-the-year/"><u>[Updated] PixelPilot's Perspective  Leading Screen Recording Tools of the Year</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-a-step-by-step-guide-to-utilizing-bandicams-capture-feature/"><u>2024 Approved  A Step-by-Step Guide to Utilizing Bandicam's Capture Feature</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/10-minutes-a-day-bengali-made-simple/"><u>10 Minutes a Day: Bengali Made Simple</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-open-and-use-the-windows-terminal-in-quake-mode/"><u>How to Open and Use the Windows Terminal in Quake Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-failed-directx-file-downloads-on-pcs/"><u>Fixing Failed DirectX File Downloads on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-silenced-microphone-for-xbox-console/"><u>Reviving Silenced Microphone for Xbox Console</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-top-5-lava-yuva-2-pro-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>In 2024, Top 5 Lava Yuva 2 Pro Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-best-online-video-montage-makers-for-trailers/"><u>In 2024, Best Online Video Montage Makers for Trailers</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-the-ultimate-checklist-for-recording-whatsapp-discussions/"><u>[New] 2024 Approved  The Ultimate Checklist for Recording WhatsApp Discussions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-roblox-needs-quitting-on-windows-without-hesitation/"><u>How to Stop Roblox Needs Quitting on Windows Without Hesitation</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-unlocking-twitters-potential-with-live-videos/"><u>[New] In 2024, Unlocking Twitter's Potential with Live Videos</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-best-hd-cameras-for-comprehensive-social-media-broadcasts/"><u>2024 Approved  Best HD Cameras for Comprehensive Social Media Broadcasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-solutions-for-windows-missing-lsass-components/"><u>Quick Solutions for Windows' Missing Lsass Components</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-setup-for-bings-ai-assistance-in-windows-11-search-shortcuts/"><u>Instant Setup for Bing's AI Assistance in Windows 11 Search Shortcuts</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-tailoring-your-timing-strategy-the-ultimate-instagram-guide/"><u>[New] Tailoring Your Timing Strategy  The Ultimate Instagram Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-cab-files-usage-and-installation-insights/"><u>Mastering Windows CAB Files: Usage and Installation Insights</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-stream-viewer-unraveler/"><u>[New] 2024 Approved  Stream Viewer Unraveler</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-navigating-the-voice-recorder-app-samsung-s10s9-edition/"><u>New In 2024, Navigating the Voice Recorder App Samsung S10/S9 Edition</u></a></li>
</ul></div>
