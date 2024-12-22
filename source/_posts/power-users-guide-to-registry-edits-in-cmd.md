---
title: Power Users' Guide to Registry Edits in CMD
date: 2024-12-21T04:01:28.788Z
updated: 2024-12-22T09:19:36.612Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Power Users' Guide to Registry Edits in CMD
excerpt: This Article Describes Power Users' Guide to Registry Edits in CMD
keywords: Registry Editing Guide,CMD Power Users,CMD Registry Tweaks,Advanced Registry Mods,System Command Edits,Power Tools for RegEdit,Mastering Registry via CMD
thumbnail: https://thmb.techidaily.com/3c9a0c6a221fee25e096fdddf37ef07f9a19a2323a0faabfa25ea26bfdcf4c13.jpg
---

## Power Users' Guide to Registry Edits in CMD

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XIUatTFH0Zw?si=ZCtoBtIy18y2F5Vc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Sj2QNA-JXI?si=V-_h73iE3VlE214k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## How to Copy Registry Entries From One Key to Another

![transfering entries from one registry key to another in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/transfering-entries-from-one-registry-key-to-another-in-command-prompt.jpg)

 Sometimes, you might want to copy the values from one key to another in the registry. This is as easy as using the **reg copy** command while specifying the key you're copying them from and the one you're copying them to (keep in mind that both keys have to already exist before you run the command). Here's an example:

`reg copy HKLM\SOFTWARE\MyNewKey1 HKLM\SOFTWARE\MyNewKey2 /s`

 The **/s** switch at the end tells Command Prompt that it should copy every subkey and value in the first key (**MyNewKey1**) into the second one (**MyNewKey2**).

 Unfortunately, there's no way to copy specific values from one key to another. You'll have to use the Registry Editor for that.

## How to Import Registry Entries

![importing a registry file in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/importing-a-registry-file-in-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/May-pLCUkEA?si=PGlcFZAlsp3S3beI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you have [created a Windows Registry file](https://www.makeuseof.com/windows-registry-file-guide/) or downloaded it elsewhere, you can import it into the registry using the **reg import** command. All you need to do is specify the path to the registry file and Command Prompt will do the rest. Here's an example:

`reg import C:\Users\CHIFUNDO\Desktop\MyRegFile.reg`

 Once you run that command, the contents of the reg file will be merged with the registry.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6nvb0775GOM?si=peBB_Mo_4zcZFuci" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Export Registry Entries

![exproting a registry key in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/exproting-a-registry-key-in-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aIx71tPaWKg?si=lG5OiUe-M6eBJf5b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can export a key in the registry using the **reg export** command while specifying the path of the key you want to export and the file you want to create. This comes in handy when you need to back up certain keys and values to restore them elsewhere. Here's an example:

`reg export "HKLM\SOFTWARE\MyNewKey" D:\Reg_Backup\CHIFUNDO\Desktop\MyRegFile.reg`

 After you run the command successfully, check the location you entered, and you'll find the key and its associated subkeys and values have been exported successfully. In our case, it will create a file called **MyRegFile.reg** and save it on the desktop.

 You can also export a specific value using the **reg query** command and include the key, value, and path to the registry file you want to export the value to. Here's an example.

`reg query HKLM\SOFTWARE\MyNewKey /v MyValue > C:\Users\CHIFUNDO\Desktop\MyRegFile.reg`

 The resulting registry file will only contain the key and the specific value you exported.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-fb-streams-save-as-mp3-beat-for-easy-playback/"><u>[New] 2024 Approved FB Streams Save as MP3 Beat for Easy Playback</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-convert-spoken-words-into-text-effortlessly-using-ms-word-for-2024/"><u>[Updated] Convert Spoken Words Into Text Effortlessly Using MS Word for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-decipher-youtubes-mysteries-with-advanced-insights-from-social-blade/"><u>[Updated] In 2024, Decipher YouTube's Mysteries with Advanced Insights From Social Blade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-art-of-windows-11s-glossy-title-bar/"><u>Discover the Art of Windows 11'S Glossy Title Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/function-failures-on-win10-quick-remedies-available/"><u>Function Failures on Win10? Quick Remedies Available!</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/o-seamlessly-incorporate-video-game-banners/"><u>How to Seamlessly Incorporate Video Game Banners</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-film-titles-that-spur-positive-change-and-action-steps/"><u>In 2024, Film Titles That Spur Positive Change & Action Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leapfrog-past-slow-downloads-with-utorrent-on-windows/"><u>Leapfrog Past Slow Downloads with uTorrent on Windows</u></a></li>
<li><a href="https://discover-answers.techidaily.com/master-the-technique-of-reflecting-iphone-display-onto-an-ipad/"><u>Master the Technique of Reflecting iPhone Display Onto an iPad</u></a></li>
<li><a href="https://fox-http.techidaily.com/master-your-mobile-photos-ios-and-androids-finest-apps/"><u>Master Your Mobile Photos IOS & Android's Finest Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-system-fixes-establishing-quick-troubleshooter-access/"><u>Optimizing System Fixes: Establishing Quick Troubleshooter Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-spotify-connect-issues-on-windows-10-and-11/"><u>Overcoming Spotify Connect Issues on Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconciling-code-0x0001-in-geforce-for-windows-11-users/"><u>Reconciling Code 0X0001 in GeForce for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-renderer-glitch-in-overwatch-2-on-windows-systems/"><u>Restoring Renderer Glitch in Overwatch 2 on Windows Systems</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/troubleshooting-tips-resolving-playback-issues-with-dji-videos/"><u>Troubleshooting Tips: Resolving Playback Issues with DJI Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-the-admin-powershell-potential-in-windows-11-environment/"><u>Unleashing the Admin PowerShell Potential in Windows 11 Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-paths-to-printer-control-on-windows-11-max-56-chars/"><u>Unveiling the Paths to Printer Control on Windows 11 (Max 56 Chars)</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/1985919-9781780282558-what-islam-did-for-us/"><u>What Islam Did For Us | Free Book</u></a></li>
<li><a href="https://howto.techidaily.com/xiaomi-redmi-12-bootloop-problem-how-to-fix-it-without-data-loss-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Xiaomi Redmi 12 Bootloop Problem, How to Fix it Without Data Loss | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    