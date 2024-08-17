---
title: Stepwise Approach to Editing Windows Registry with Command Prompt
date: 2024-08-16T02:04:31.630Z
updated: 2024-08-17T02:04:31.630Z
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

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Add and Delete Keys in the Windows Registry

 To add a key to the registry using Command Prompt, you need to use the **reg add** command while specifying the path to the new key and whether you want to force the operation with the **/f** switch(this will bypass the need for the confirmation prompt).

 As always, when it comes to editing the Windows Registry, we recommend that the first thing you do is [create a system restore point on Windows](https://www.makeuseof.com/use-system-restore-windows/).

 Here's an example:

`REG Add HKLM\SOFTWARE\MyNewKey /f`

 In the above command, we're adding the **MyNewKey** subkey to the **KHLM/Software** key. If you go to the Registry Editor and expand that key, you'll be able to see the **MyNewKey** subkey within it.

 Deleting the key is simple as well, as you just need to replace **add** with **delete** in the above example. Here's how:

`reg delete HKLM\SOFTWARE\MyNewKey /f`

 Now the **MySubKey** key will disappear in the Registry Editor.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Add, Modify, and Delete Values in the Windows Registry
![adding a value to Windows registry in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/adding-a-value-to-windows-registry-in-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35408920&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/FR-200-1.png" border="0">Glarysoft File Recovery Pro - Helps to recover your lost file/data, even permanently deleted data. </a>
<!-- affiliate ads end -->
## How to Export Registry Entries
![exproting a registry key in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/exproting-a-registry-key-in-command-prompt.jpg)

 You can export a key in the registry using the **reg export** command while specifying the path of the key you want to export and the file you want to create. This comes in handy when you need to back up certain keys and values to restore them elsewhere. Here's an example:

`reg export "HKLM\SOFTWARE\MyNewKey" D:\Reg_Backup\CHIFUNDO\Desktop\MyRegFile.reg`

 After you run the command successfully, check the location you entered, and you'll find the key and its associated subkeys and values have been exported successfully. In our case, it will create a file called **MyRegFile.reg** and save it on the desktop.

 You can also export a specific value using the **reg query** command and include the key, value, and path to the registry file you want to export the value to. Here's an example.

`reg query HKLM\SOFTWARE\MyNewKey /v MyValue > C:\Users\CHIFUNDO\Desktop\MyRegFile.reg`

 The resulting registry file will only contain the key and the specific value you exported.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Save Registry Entries
![saving-a-key-to-a-registry-file-in-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/saving-a-key-to-a-registry-file-in-windows.jpg)

 If you already have a registry file or any other text file, you can add keys to it using Command Prompt and the **reg save** command, which will overwrite the file with the new information. You just need to specify the name of the key and the registry file you want to save it to. Here's an example:

`reg save HKLM\SOFTWARE\MyNewKey2 C:\Users\CHIFUNDO\Desktop\MyRegFile.hiv /y`

 The **/y** switch at the end of the command above overwrites the file you're saving the key to without bringing up a prompt. When you open the file, you won't be able to read the contents since it will be saved as a binary file.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-justifying-itop-as-your-primary-recording-software/"><u>[New] In 2024, Justifying ITop as Your Primary Recording Software?</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-11-ultimate-phantom-4-accessories-to-purchase/"><u>[Updated] 11 Ultimate Phantom 4 Accessories to Purchase</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-mastering-the-art-of-capturing-live-hulu-content-across-platforms/"><u>[Updated] Mastering the Art of Capturing Live Hulu Content Across Platforms</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-lilliputian-storyboard-outline/"><u>2024 Approved  Lilliputian Storyboard Outline</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-the-gap-using-ical-with-windows-operating-systems/"><u>Bridging the Gap: Using iCal with Windows Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-forth-forgotten-windows-top-6-techniques-in-win11/"><u>Bringing Forth Forgotten Windows: Top 6 Techniques in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-traditional-visuals-the-iconic-window-11-search-return/"><u>Bringing Traditional Visuals: The Iconic Window 11 Search Return</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-devhome-your-nexus-for-windows-11-innovation/"><u>Discovering DevHome: Your Nexus for Windows 11 Innovation</u></a></li>
<li><a href="https://windows11.techidaily.com/easily-identify-last-opened-files-in-windows-explorer/"><u>Easily Identify Last Opened Files in Windows Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-pc-speed-for-swift-steam-content-delivery/"><u>Enhance PC Speed for Swift Steam Content Delivery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-techniques-to-open-wordpad-in-windows/"><u>Essential Techniques to Open WordPad in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-windows-power-management-options/"><u>Exploring Windows' Power Management Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-small-icons-a-guide-for-your-win-11-desktop/"><u>Fixing Small Icons: A Guide for Your Win 11 Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gain-full-system-access-through-cmd-elevation/"><u>Gain Full System Access Through CMD Elevation</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/googles-kid-nutrition-pioneer-mondly-kids-guide-of-2017/"><u>Google’s Kid Nutrition Pioneer: Mondly Kids Guide of 2017</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-exiting-wows-unprecedented-crash-132/"><u>Guide to Exiting WoW’s Unprecedented Crash 132</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-xiaomi-redmi-k70e-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>How to Cast Xiaomi Redmi K70E to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-flush-the-steam-dns-cache-on-windows/"><u>How to Flush the Steam DNS Cache on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reinstate-windows-photo-viewer-on-win11-pcs/"><u>How to Reinstate Windows Photo Viewer on Win11 PCs</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-14-pro-with-an-apple-watch-and-what-to-do-if-it-doesnt-work-drfone-by-drfone-ios/"><u>How to Unlock iPhone 14 Pro With an Apple Watch & What to Do if It Doesnt Work | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-upgrade-to-windows-11-22h2-on-unsupported-hardware/"><u>How to Upgrade to Windows 11 22H2 on Unsupported Hardware</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-unlocking-popularity-a-comprehensive-list-of-instagrams-top-25-tags/"><u>In 2024, Unlocking Popularity  A Comprehensive List of Instagram's Top 25 Tags</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-action-steps-for-correcting-workspace-glitches-on-winos/"><u>Instant Action Steps for Correcting Workspace Glitches on WINOS</u></a></li>
<li><a href="https://facebook.techidaily.com/is-fb-messenger-a-fortress-of-privacy/"><u>Is FB Messenger a Fortress of Privacy?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leading-emulators-selecting-best-windows-imitations-for-switch-games/"><u>Leading Emulators: Selecting Best Windows Imitations for Switch Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/learn-how-to-setup-touch-typing-feature-on-your-windows-device/"><u>Learn How To Setup Touch Typing Feature on Your Windows Device</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/master-the-art-of-cutting-a-video-editors-handbook-for-instagram-for-2024/"><u>Master the Art of Cutting  A Video Editor's Handbook for Instagram for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-invisible-wi-fi-on-windows/"><u>Master the Art of Invisible Wi-Fi on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterclass-in-microsoft-essential-gratis-tools-for-win11/"><u>Masterclass in Microsoft: Essential Gratis Tools for Win11</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-technology-choices-the-ultimate-resource-by-toms-hardware-pro/"><u>Mastering Technology Choices - The Ultimate Resource by Tom's Hardware Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-win-lsa-troubleshooting/"><u>Mastering the Art of Win LSA Troubleshooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11s-voice-commands-keyboard-shortcut-essentials/"><u>Mastering Windows 11'S Voice Commands: Keyboard Shortcut Essentials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/memory-and-cpu-efficiency-in-browsers-a-windowsmacoschromeos-comparison/"><u>Memory and CPU Efficiency in Browsers: A Windows/macOS/ChromeOS Comparison</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-black-windows-display-with-ease/"><u>Navigate Black Windows Display with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-net-speeds-unlock-efficient-adapter-checking/"><u>Navigate Net Speeds: Unlock Efficient Adapter Checking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-dns-configuration-process-on-windows-11/"><u>Navigating the DNS Configuration Process on Windows 11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-stepping-through-sound-decline-a-step-by-step-approach-to-audio-fade-outs/"><u>New Stepping Through Sound Decline A Step-by-Step Approach to Audio Fade Outs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/old-vs-new-why-users-favor-windows-10-over-11/"><u>Old vs New: Why Users Favor Windows 10 Over 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-and-fixing-system-call-error-on-windows-11/"><u>Preventing and Fixing System Call Error on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/purple-pandemonium-restore-your-pcs-color-calibration/"><u>Purple Pandemonium? Restore Your PC's Color Calibration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectify-corner-design-in-win11/"><u>Rectify Corner Design in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-microsoft-store-functionality-in-windows-11/"><u>Restoring Microsoft Store Functionality in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-file-sharing-using-dropboxgoogle-drive-from-windows-paths/"><u>Streamlining File Sharing: Using Dropbox/Google Drive From Windows Paths</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-windows-11-to-your-needs-active-hours-and-updates/"><u>Tailoring Windows 11 to Your Needs: Active Hours & Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/triggering-windows-11s-stealthy-taskbar-spotlight/"><u>Triggering Windows 11'S Stealthy Taskbar Spotlight</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-slow-downloads-in-steam-a-windows-guide/"><u>Troubleshoot Slow Downloads in Steam - A Windows Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-full-potential-multitasking-with-windows-11-in-mac-os-using-parallels/"><u>Unlock Full Potential: Multitasking with Windows 11 in Mac OS Using Parallels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11s-potential-masterful-docx-to-pdf-migration/"><u>Unlocking Windows 11'S Potential: Masterful DOCX to PDF Migration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-high-cpu-usage-by-windows-ums-for-vanguard-users/"><u>Unraveling High CPU Usage by Windows’ UMS for Vanguard Users</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-when-xiaomi-redmi-13c-has-black-screen-of-death-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do When Xiaomi Redmi 13C Has Black Screen of Death? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-unseen-an-inevitable-ai-revolution/"><u>Windows Unseen: An Inevitable AI Revolution</u></a></li>
</ul></div>
