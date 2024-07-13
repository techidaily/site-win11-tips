---
title: Stepwise Approach to Editing Windows Registry with Command Prompt
date: 2024-07-12T17:03:00.006Z
updated: 2024-07-13T17:03:00.006Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stepwise Approach to Editing Windows Registry with Command Prompt
excerpt: This Article Describes Stepwise Approach to Editing Windows Registry with Command Prompt
keywords: Editing Windows Registry,Command Prompt Methods,Registry Cleanup Tips,Admin Tools for WinReg,System File Optimization,PowerShell Registry Edit,Safe Keyboard Shortcuts Edit
thumbnail: https://thmb.techidaily.com/a6435a313e4469213bebd5ae38a7530a7b0364be00feda91bc9b60c48edb8ed3.jpg
---

## Stepwise Approach to Editing Windows Registry with Command Prompt

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
<li><a href="https://win11-tips.techidaily.com/addressing-error-code-a00f4289-for-windows-11-webcam/"><u>Addressing Error Code A00F4289 for Windows 11 Webcam</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-top-15-apps-for-high-quality-windows-video-capture-for-2024/"><u>[New] Top 15 Apps for High-Quality Windows Video Capture for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-the-game-changer-elevating-your-virtual-reality-film-quality/"><u>[Updated] In 2024, The Game Changer  Elevating Your Virtual Reality Film Quality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-end-task-bar-functionality-in-windows-11/"><u>Activating End Task Bar Functionality in Windows 11</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/eamless-integration-of-youtube-melodies-into-imovie-for-2024/"><u>[New] Seamless Integration of YouTube Melodies Into iMovie for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-selectable-items-on-microsofts-new-os/"><u>Addressing Non-Selectable Items on Microsoft's New OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719278811623-bypassing-chrome-block-strategies-for-w11-users/"><u>Bypassing Chrome Block: Strategies for W11 Users.</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-fake-android-location-without-rooting-for-your-oppo-f23-5g-drfone-by-drfone-virtual/"><u>In 2024, Fake Android Location without Rooting For Your Oppo F23 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-using-the-mspcm-bar-tools-windows-11-style/"><u>A Step-by-Step Guide to Using the MSPCM Bar Tools, Windows 11 Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-deactivated-outlook-mail-signals/"><u>Addressing Deactivated Outlook Mail Signals</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-from-free-to-paid-subscriber-count-surpasses-500/"><u>[Updated] In 2024, From Free to Paid  Subscriber Count Surpasses 500</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719341599288-windows-chatbot-simulation-localize-for-free-with-gpt4all/"><u>Windows ChatBot Simulation: Localize for Free with GPT4All</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-seamless-streaming-experience-a-youtube-playlist-creation-guide/"><u>[New] Seamless Streaming Experience  A YouTube Playlist Creation Guide</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-craft-your-future-with-instagram-video-marketing-step-by-step-guide/"><u>[New] 2024 Approved  Craft Your Future with Instagram Video Marketing  Step-by-Step Guide</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-edit-videos-freely-no-watermarks-with-these-10-trimmers-for-2024/"><u>Updated Edit Videos Freely No Watermarks with These 10 Trimmers for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-full-analysis-of-camstudio-screen-capture-tech-for-2024/"><u>[New] Full Analysis of CamStudio Screen Capture Tech for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapting-oculus-quest-2-for-windows-vr-software/"><u>Adapting Oculus Quest 2 for Windows VR Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-set-up-image-slideshows-in-windows-11-without-installing-extra-software/"><u>7 Ways to Set Up Image Slideshows in Windows 11 Without Installing Extra Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-printer-offline-errors-in-windows-11/"><u>Addressing 'Printer Offline' Errors in Windows 11</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-15-crucial-strategies-for-accessing-international-sport-events/"><u>2024 Approved  15 Crucial Strategies for Accessing International Sport Events</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-network-unity-wi-fi-plus-ethernet-integration-in-windows/"><u>Achieving Network Unity: Wi-Fi + Ethernet Integration in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-1drive-errors-steps-to-success-in-w11/"><u>Addressing 1Drive Errors: Steps to Success in W11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-stabilize-your-lens-no-trips-only-tricks/"><u>In 2024, Stabilize Your Lens  No Trips, Only Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719370971554-xbox-not-responding-unfreeze-and-get-back-in/"><u>Xbox Not Responding? Unfreeze and Get Back In!</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/best-love-video-maker-with-music-for-2024/"><u>Best Love Video Maker with Music for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719355984111-troubleshooting-made-simple-your-guide-to-windows-help/"><u>Troubleshooting Made Simple: Your Guide to Windows Help</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-strategies-reviving-failed-google-drive-windows-links/"><u>7 Strategies: Reviving Failed Google Drive Windows Links</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-nine-crucial-strategies-to-elevate-your-youtube-presence/"><u>In 2024, Nine Crucial Strategies to Elevate Your Youtube Presence</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-virtual-memoirs-best-tools-and-practices-for-downloading-twitter-content/"><u>[New] Virtual Memoirs  Best Tools and Practices for Downloading Twitter Content</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-premium-6-networks-maximizing-biz-potential/"><u>[New] Premium 6 Networks Maximizing Biz Potential</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/curated-cinematic-journeys-the-best-yt-film-selections/"><u>Curated Cinematic Journeys  The Best YT Film Selections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-restoring-the-non-responsive-service-control-panel/"><u>A Comprehensive Guide: Restoring the Non-Responsive Service Control Panel</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/in-2024-best-options-top-live-streaming-platforms-according-to-types/"><u>In 2024, Best Options Top Live Streaming Platforms According to Types</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensible-windows-screentime-intermission/"><u>A Comprehensible Window's Screentime Intermission</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-beginners-path-to-implementing-hyper-v-on-win-11-homes/"><u>A Beginner's Path to Implementing Hyper-V on Win 11 Homes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-printers-under-edge-guard-on-windows-11/"><u>Accessing Printers Under Edge Guard on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-key-methods-windows-11-uses-to-intrude-on-privacy/"><u>5 Key Methods Windows 11 Uses to Intrude on Privacy</u></a></li>
<li><a href="https://youtube-data.techidaily.com/-subscriptions-upward-through-effective-youtube-branding-for-2024/"><u>Drive Subscriptions Upward Through Effective YouTube Branding for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-2024s-premier-gadget-review-channel-selections/"><u>[New] 2024'S Premier Gadget Review Channel Selections</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-6-ways-to-convert-video-to-audio-for-free/"><u>2024 Approved 6 Ways to Convert Video to Audio for FREE</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-fixing-windows-error-xffffff/"><u>A Comprehensive Guide to Fixing Windows' Error XFFFFFF</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-androids-answer-to-imovie-top-10-video-editing-apps/"><u>Updated 2024 Approved Androids Answer to iMovie Top 10 Video Editing Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-elevation-failure-overcoming-error-740-in-windows/"><u>Addressing Elevation Failure: Overcoming Error 740 in Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-oneplus-ace-2-pro-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from OnePlus Ace 2 Pro to iPhone XS/11 | Dr.fone</u></a></li>
</ul></div>
