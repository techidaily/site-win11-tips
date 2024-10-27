---
title: "Professionals' Insight: Mastery of CMD-Based Windows Registry Adjustments"
date: 2024-10-20T16:25:25.185Z
updated: 2024-10-26T21:30:27.955Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Professionals' Insight: Mastery of CMD-Based Windows Registry Adjustments"
excerpt: "This Article Describes Professionals' Insight: Mastery of CMD-Based Windows Registry Adjustments"
keywords: CMD Registry Expertise,Win Registry Skills,Professional RegEditing,Admin Registry Controls,Mastery Registry Config,Tech Registry Professionals,Windows Registry Masters
thumbnail: https://thmb.techidaily.com/0177669a9f7e47198243a9fecb2a2f8d7897c9576df374da55c9c20dfb4332d6.jpg
---

## Professionals' Insight: Mastery of CMD-Based Windows Registry Adjustments

 The Registry Editor is the first thing Windows users bring up when it comes to editing the Windows Registry. However, if you don't want to deal with a distracting GUI and too many clicks, there's a simpler-looking tool you can use: the Command Prompt.

 Although using it takes a little more know-how than the Registry Editor, our guide should be able to get you started.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<a href="https://appsumo.8odi.net/c/5597632/2044582/7443" target="_top" id="2044582">
  <img src="//a.impactradius-go.com/display-ad/7443-2044582" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2044582/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135404/19272" target="_top" id="2135404">
  <img src="//a.impactradius-go.com/display-ad/19272-2135404" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135404/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144310/7443" target="_top" id="2144310">
  <img src="//a.impactradius-go.com/display-ad/7443-2144310" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144310/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137378/7443" target="_top" id="2137378">
  <img src="//a.impactradius-go.com/display-ad/7443-2137378" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137378/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 So, let's say something has happened to the keys and values within the **MyNewKey2** we saved in the previous section, you can use the backup file you created to restore it. You'll need to use the **reg restore** command. Here's how to run it:

`reg restore HKLM\SOFTWARE\MyNewKey2 C:\Users\CHIFUNDO\Desktop\MyRegFile.hiv`

 Now the **MyNewKey2** key should return to the state it was in when you made the backup.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/947746/11832" target="_top" id="947746">
  <img src="//a.impactradius-go.com/display-ad/11832-947746" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/947746/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Tweak the Registry Without the Registry Editor

 While Command Prompt can't do everything the Registry Editor does, it does offer a quick way to edit the registry without opening the aforementioned tool. While using Command Prompt to tweak the registry is quite advanced, even if you're the average user, you should be able to get by if you follow along closely.

 Just don't forget to do what we mentioned earlier to avoid permanently ruining your Windows computer and create a system restore point first

 Although using it takes a little more know-how than the Registry Editor, our guide should be able to get you started.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-transform-your-visual-content-on-instagram-using-these-6-tools/"><u>[New] In 2024, Transform Your Visual Content on Instagram Using These 6 Tools</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-photoshop-simplified-beginner-friendly-editing-secrets-for-2024/"><u>[New] Photoshop Simplified Beginner-Friendly Editing Secrets for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-channelart-essentials-10-digital-tools-to-design-logos-and-themes-for-2024/"><u>[Updated] ChannelArt Essentials 10 Digital Tools to Design Logos & Themes for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-does-youtube-count-views-its-not-as-simple-as-you-think/"><u>[Updated] In 2024, How Does YouTube Count Views? It's Not as Simple as You Think</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-failure-windows-update-issue-code-0x80242016/"><u>Avoid Failure: Windows Update Issue Code 0X80242016</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-customized-keyboard-tricks-for-win-os/"><u>Boost Efficiency: Customized Keyboard Tricks for WIN OS</u></a></li>
<li><a href="https://extra-resources.techidaily.com/complete-activity-assessment-guide-for-2024/"><u>Complete Activity Assessment Guide for 2024</u></a></li>
<li><a href="https://win-solutions.techidaily.com/effective-strategies-for-resolving-witcher-3-game-failures-on-startup/"><u>Effective Strategies for Resolving Witcher 3 Game Failures on Startup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-strategies-for-disconnected-steam-content-servers-on-pc/"><u>Fix Strategies for Disconnected Steam Content Servers on PC</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-itel-p40plus-drfone-by-drfone-virtual-android/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Itel P40+? | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/inside-toms-electronic-emporium-unlocking-hardware-secrets/"><u>Inside Tom's Electronic Emporium: Unlocking Hardware Secrets</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/iphone-reset-protocols-unveiled-the-ultimate-guide-to-data-erasure/"><u>IPhone Reset Protocols Unveiled: The Ultimate Guide to Data Erasure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pioneering-gpu-performance-unveiling-the-top-6-tools-for-windows-users/"><u>Pioneering GPU Performance: Unveiling the Top 6 Tools for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-windows-store-error-code-0x80073cf3/"><u>Steps to Resolve Windows Store Error Code 0X80073CF3</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/mline-your-youtube-watch-with-no-black-or-white-edges/"><u>Streamline Your YouTube Watch with No Black or White Edges</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-printer-removal-procedures-for-windows-11-users/"><u>Swift Printer Removal Procedures for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-fn-keys-adjustments-for-microsoft-windows-1011/"><u>Tailored FN Keys Adjustments for Microsoft Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-the-art-of-toggling-between-window-terminals-concentration-and-normalcy/"><u>Uncovering the Art of Toggling Between Window Terminal's Concentration and Normalcy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-advanced-capabilities-with-windows-powershell-policy-settings/"><u>Unlock Advanced Capabilities with Windows PowerShell Policy Settings</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    