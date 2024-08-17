---
title: Comprehensive Manual for Registry Editing with Command Prompt
date: 2024-08-16T02:25:16.608Z
updated: 2024-08-17T02:25:16.608Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Comprehensive Manual for Registry Editing with Command Prompt
excerpt: This Article Describes Comprehensive Manual for Registry Editing with Command Prompt
keywords: Command Line RegEdit Guide,Windows Registry Modification,Registry Editor Commands,Mastering Registry Tweaks,Command Prompt Registry Edit,Advanced Registry Edits,PowerShell for Registry Change
thumbnail: https://thmb.techidaily.com/bb9708a331c4c3dd31e799c079bb73652a9e75d1a08dd178d051b1af275cc7e6.jpg
---

## Comprehensive Manual for Registry Editing with Command Prompt

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
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Sometimes, you might want to copy the values from one key to another in the registry. This is as easy as using the **reg copy** command while specifying the key you're copying them from and the one you're copying them to (keep in mind that both keys have to already exist before you run the command). Here's an example:

`reg copy HKLM\SOFTWARE\MyNewKey1 HKLM\SOFTWARE\MyNewKey2 /s`

 The **/s** switch at the end tells Command Prompt that it should copy every subkey and value in the first key (**MyNewKey1**) into the second one (**MyNewKey2**).

 Unfortunately, there's no way to copy specific values from one key to another. You'll have to use the Registry Editor for that.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->

 If you already have a registry file or any other text file, you can add keys to it using Command Prompt and the **reg save** command, which will overwrite the file with the new information. You just need to specify the name of the key and the registry file you want to save it to. Here's an example:

`reg save HKLM\SOFTWARE\MyNewKey2 C:\Users\CHIFUNDO\Desktop\MyRegFile.hiv /y`

 The **/y** switch at the end of the command above overwrites the file you're saving the key to without bringing up a prompt. When you open the file, you won't be able to read the contents since it will be saved as a binary file.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Restore Registry Entries
![restoring-a-registry-key-in-command-prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/restoring-a-registry-key-in-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 So, let's say something has happened to the keys and values within the **MyNewKey2** we saved in the previous section, you can use the backup file you created to restore it. You'll need to use the **reg restore** command. Here's how to run it:

`reg restore HKLM\SOFTWARE\MyNewKey2 C:\Users\CHIFUNDO\Desktop\MyRegFile.hiv`

 Now the **MyNewKey2** key should return to the state it was in when you made the backup.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
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
<li><a href="https://twitter-videos.techidaily.com/new-navigating-snapchat-for-twitter-vids-distribution/"><u>[New] Navigating Snapchat for Twitter Vids Distribution</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-the-best-for-broadcasting-duel-of-live-tools-for-2024/"><u>[New] The Best for Broadcasting? Duel of Live Tools for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-maximizing-engagement-essential-strategies-for-facebook-video-promotion/"><u>[Updated] 2024 Approved  Maximizing Engagement  Essential Strategies for Facebook Video Promotion</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-getting-started-with-obs-on-apple-a-comprehensive-guide/"><u>[Updated] In 2024, Getting Started with OBS on Apple  A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-straightforward-approach-to-discovering-ram-in-windows/"><u>A Straightforward Approach to Discovering RAM in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assisting-with-utorrent-sync-halt-on-microsoft-operating-systems/"><u>Assisting with uTorrent Sync Halt on Microsoft Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-boot-efficiency-with-windows-11-programs/"><u>Boosting Boot Efficiency with Windows 11 Programs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719373707174-check-physical-connections-make-sure-cables-are-firmly-connected-if-you-have-external-monitors-or-projectors-with-separate-brightness-controls/"><u>Check Physical Connections: Make Sure Cables Are Firmly Connected if You Have External Monitors or Projectors with Separate Brightness Controls.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/compute-discerning-window-systems-origins/"><u>Compute: Discerning Window Systems' Origins</u></a></li>
<li><a href="https://windows11.techidaily.com/decreasing-high-cpu-usage-in-wmi/"><u>Decreasing High Cpu Usage in WMI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-access-entry-error-in-microsoft-os/"><u>Disabling 'Access Entry' Error in Microsoft OS</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/disabling-apple-iphone-13-parental-restrictions-withwithout-password-by-drfone-ios/"><u>Disabling Apple iPhone 13 Parental Restrictions With/Without Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/drive-efficiency-to-new-heights-with-collective-windows-11-folder-creation/"><u>Drive Efficiency to New Heights with Collective Windows 11 Folder Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exposing-how-to-circumvent-secure-boot-mechanism-in-windows-11/"><u>Exposing How To Circumvent Secure Boot Mechanism in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-windows-securitys-unexpected-error-in-windows-11-and-11/"><u>How to Fix Windows Security’s “Unexpected Error” In Windows 11 & 11</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-realme-c53-drfone-by-drfone-virtual-android/"><u>How to get the dragon scale and evolution-enabled pokemon On Realme C53? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-leading-smartphototech-ai-edition-advantages/"><u>In 2024, Leading SmartPhotoTech  AI Edition Advantages</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-metaverse-inspiration-enhanced-by-ar-and-vr/"><u>In 2024, Metaverse Inspiration  Enhanced by AR & VR</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-the-updated-method-to-bypass-xiaomi-redmi-12-frp-by-drfone-android/"><u>In 2024, The Updated Method to Bypass Xiaomi Redmi 12 FRP</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-the-top-free-dvd-player-downloads-for-windows-10/"><u>New 2024 Approved The Top Free DVD Player Downloads for Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-restrictions-and-unlocking-full-ram-potential/"><u>Overcoming Restrictions and Unlocking Full RAM Potential</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pioneer-productivity-mass-folder-creation-on-modern-windows-systems/"><u>Pioneer Productivity: Mass Folder Creation on Modern Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-resolving-unreachable-device-error-on-pc/"><u>Quick Guide: Resolving Unreachable Device Error on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-your-personalized-mixer-settings-after-crashes/"><u>Reinstating Your Personalized Mixer Settings After Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/retro-game-revival-elevating-experiences-by-adding-achievements-using-retroarch/"><u>Retro Game Revival: Elevating Experiences by Adding Achievements Using Retroarch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-file-transfer-via-winrar-6-corrective-steps-for-sums/"><u>Secure File Transfer via WinRAR: 6 Corrective Steps for Sums</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-pc-gaming-with-yuzu-on-windows/"><u>Skyrocket PC Gaming with Yuzu on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-11s-cloud-storage-functionality/"><u>Streamlining Windows 11'S Cloud Storage Functionality</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/top-15-augmented-reality-games-like-pokemon-go-to-play-on-tecno-spark-20-pro-drfone-by-drfone-virtual-android/"><u>Top 15 Augmented Reality Games Like Pokémon GO To Play On Tecno Spark 20 Pro | Dr.fone</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/top-5-video-editors-for-macos-sierra-for-2024/"><u>Top 5 Video Editors for macOS Sierra for 2024</u></a></li>
<li><a href="https://os-tips.techidaily.com/top-7-effective-troubleshooting-tips-for-resolving-charging-issues-on-your-android-device/"><u>Top 7 Effective Troubleshooting Tips for Resolving Charging Issues on Your Android Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-microphone-issues-live-recording-fixes-in-obs-w11/"><u>Troubleshooting Microphone Issues: Live Recording Fixes in OBS, W11</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723125154751-unbeatable-price-elegoo-neptone-4-pro-laser-cutter-just-284/"><u>Unbeatable Price: Elegoo Neptone 4 Pro Laser Cutter - Just $284</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveil-windows-potential-get-the-outlook-preview-installed/"><u>Unveil Windows' Potential: Get the Outlook Preview Installed</u></a></li>
<li><a href="https://win11.techidaily.com/unwrapping-and-solving-isdonedll-failures-in-w10w11-oses/"><u>Unwrapping and Solving ISDone.dll Failures in W10/W11 OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-your-digital-desktop-top-5-apps-for-customizable-clock-screen-savers-on-windows/"><u>Upgrade Your Digital Desktop: Top 5 Apps for Customizable Clock Screen Savers on Windows</u></a></li>
</ul></div>
