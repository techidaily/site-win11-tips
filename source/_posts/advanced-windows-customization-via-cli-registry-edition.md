---
title: "Advanced Windows Customization via CLI: Registry Edition"
date: 2024-08-16T01:54:38.695Z
updated: 2024-08-17T01:54:38.695Z
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
## How to Copy Registry Entries From One Key to Another
![transfering entries from one registry key to another in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/transfering-entries-from-one-registry-key-to-another-in-command-prompt.jpg)

 Sometimes, you might want to copy the values from one key to another in the registry. This is as easy as using the **reg copy** command while specifying the key you're copying them from and the one you're copying them to (keep in mind that both keys have to already exist before you run the command). Here's an example:

`reg copy HKLM\SOFTWARE\MyNewKey1 HKLM\SOFTWARE\MyNewKey2 /s`

 The **/s** switch at the end tells Command Prompt that it should copy every subkey and value in the first key (**MyNewKey1**) into the second one (**MyNewKey2**).

 Unfortunately, there's no way to copy specific values from one key to another. You'll have to use the Registry Editor for that.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Import Registry Entries
![importing a registry file in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/importing-a-registry-file-in-command-prompt.jpg)

 If you have [created a Windows Registry file](https://www.makeuseof.com/windows-registry-file-guide/) or downloaded it elsewhere, you can import it into the registry using the **reg import** command. All you need to do is specify the path to the registry file and Command Prompt will do the rest. Here's an example:

`reg import C:\Users\CHIFUNDO\Desktop\MyRegFile.reg`

 Once you run that command, the contents of the reg file will be merged with the registry.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## How to Save Registry Entries
![saving-a-key-to-a-registry-file-in-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/saving-a-key-to-a-registry-file-in-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you already have a registry file or any other text file, you can add keys to it using Command Prompt and the **reg save** command, which will overwrite the file with the new information. You just need to specify the name of the key and the registry file you want to save it to. Here's an example:

`reg save HKLM\SOFTWARE\MyNewKey2 C:\Users\CHIFUNDO\Desktop\MyRegFile.hiv /y`

 The **/y** switch at the end of the command above overwrites the file you're saving the key to without bringing up a prompt. When you open the file, you won't be able to read the contents since it will be saved as a binary file.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
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
<li><a href="https://fox-helps.techidaily.com/new-in-2024-a-deep-dive-into-selecting-tiktok-screenshots/"><u>[New] In 2024, A Deep Dive Into Selecting TikTok Screenshots</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-decoding-the-mystery-of-youtube-shorts/"><u>[New] In 2024, Decoding the Mystery of YouTube Shorts</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-leading-9-mic-technology-a-comprehensive-analysis/"><u>[New] In 2024, Leading 9 Mic Technology  A Comprehensive Analysis</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-smile-and-shine-transform-photos-at-no-expense/"><u>[New] Smile & Shine  Transform Photos at No Expense</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-virtual-playstation-experience-at-your-fingertips-top-5-for-2024/"><u>[New] Virtual PlayStation Experience at Your Fingertips (Top 5) for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-mastering-asmr-the-ultimate-list-of-mics/"><u>[Updated] Mastering ASMR - The Ultimate List of Mics</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-premium-combo-exclusive-afx-design-tools-for-2024/"><u>[Updated] Premium Combo  Exclusive AFX Design Tools for 2024</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-social-laughter-downloaded-iphoneandroid-tutorial-for-gifs/"><u>[Updated] Social Laughter Downloaded  IPhone/Android Tutorial for GIFS</u></a></li>
<li><a href="https://fox-info.techidaily.com/20-leading-no-cost-digital-editing-platforms-for-2024/"><u>20 Leading No-Cost Digital Editing Platforms for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-art-of-incorporating-b-roll-in-video-production/"><u>2024 Approved  The Art of Incorporating B Roll in Video Production</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/about-poco-f5-5g-frp-bypass-by-drfone-android/"><u>About Poco F5 5G FRP Bypass</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/best-5-viral-video-marketing-techniques-for-big-sellers/"><u>Best 5 Viral Video Marketing Techniques For Big Sellers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bootstrapping-a-powershell-session-as-an-admin-on-windows-11/"><u>Bootstrapping a PowerShell Session as an Admin on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breached-bitlocker-hold-firm-on-current-security/"><u>Breached BitLocker: Hold Firm on Current Security</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-barriers-for-skyrims-script-enhancement/"><u>Breaking Barriers for Skyrim's Script Enhancement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridge-the-gap-addressing-continuous-ps4-controller-disconnection/"><u>Bridge the Gap: Addressing Continuous PS4 Controller Disconnection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-tasks-and-power-in-win11-shortcut-setup/"><u>Bridging Tasks & Power in Win11 Shortcut Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-the-store-reactivation-steps-for-ms-in-windows-11/"><u>Bring Back the Store: Reactivation Steps for MS in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-outdated-computers-into-the-win11-era/"><u>Bringing Outdated Computers Into the Win11 Era</u></a></li>
<li><a href="https://win11-tips.techidaily.com/browser-download-techniques-after-windows-installation/"><u>Browser Download Techniques After Windows Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/building-a-window-for-secure-hardware-removal-on-windows-11/"><u>Building a Window for Secure Hardware Removal on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-hidden-taskbar-scan-shield-in-windows-11/"><u>Bypass Hidden Taskbar Scan Shield in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-the-barrier-taking-down-security-questions-on-local-account-win-11/"><u>Bypass the Barrier: Taking Down Security Questions on Local Account (Win 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-unknown-device-error-step-by-step-guide-for-windows-users/"><u>Bypassing 'Unknown Device Error': Step-by-Step Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-do-not-have-access-error-when-uninstalling-apps/"><u>Bypassing Do Not Have Access Error When Uninstalling Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-firewall-restrictions-allow-browser-networking-in-windows/"><u>Bypassing Firewall Restrictions: Allow Browser Networking in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-11-admin-lockdown/"><u>Bypassing Windows 11 Admin Lockdown</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-your-geforce-experience-scanning-problem-in-win/"><u>Bypassing Your GeForce Experience Scanning Problem in Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cableless-game-controls-connecting-ps3-to-pc/"><u>Cableless Game Controls: Connecting PS3 to PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cant-delete-temporary-files-in-windows-try-these-fixes/"><u>Can’t Delete Temporary Files in Windows? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/capturing-critical-windows-user-alerts-in-action/"><u>Capturing Critical Windows User Alerts in Action</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-windows-record-of-app-openings/"><u>Cease Windows Record of App Openings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/celebrate-yuletide-in-stunning-windowscapes/"><u>Celebrate Yuletide in Stunning Windowscapes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/charting-course-past-the-lost-at-sea-xbox-error-in-win11/"><u>Charting Course Past the Lost at Sea Xbox Error in Win11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/exclusive-fb-picturevid-producer-no-fee-for-2024/"><u>Exclusive FB Picture/Vid Producer - No Fee for 2024</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-vivo-v29-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Vivo V29 | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/how-to-clean-up-your-figma-compositions-effectively-for-2024/"><u>How To Clean Up Your Figma Compositions Effectively for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-remove-nokia-c300-pin-by-drfone-android-unlock-android-unlock/"><u>How to remove Nokia C300 PIN</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-the-meme-formula-combining-humor-trendiness-and-viral-video-potential/"><u>In 2024, The Meme Formula  Combining Humor, Trendiness & Viral Video Potential</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-shorter-path-cutting-video-duration-on-youtube/"><u>In 2024, The Shorter Path  Cutting Video Duration on YouTube</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-transformative-techniques-looping-videos-that-engage-instagram-users/"><u>In 2024, Transformative Techniques  Looping Videos That Engage Instagram Users</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/prioritizing-visibility-a-guide-to-insta-highlights-perfection/"><u>Prioritizing Visibility  A Guide to Insta Highlights Perfection</u></a></li>
<li><a href="https://dvd-bd.techidaily.com/top-rated-dvd-menu-design-software-create-stunning-menus-easily/"><u>Top Rated DVD Menu Design Software: Create Stunning Menus Easily</u></a></li>
<li><a href="https://facebook.techidaily.com/1719150176344-watch-for-verdict-facebook-board-to-decide-on-presidential-block/"><u>Watch For Verdict: Facebook Board to Decide on Presidential Block.</u></a></li>
</ul></div>
