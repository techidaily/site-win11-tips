---
title: Navigating the Labyrayer of Windows Registry via Command Line
date: 2024-10-21T23:43:56.227Z
updated: 2024-10-26T16:44:42.833Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating the Labyrayer of Windows Registry via Command Line
excerpt: This Article Describes Navigating the Labyrayer of Windows Registry via Command Line
keywords: Registry Exploration CLI,WinReg CmdUsage,RegEdit TerminalAccess,PowerShell Registry Insight,Windows Registry QueryCmd,Admin EditKey Command,Registy Window Navigation
thumbnail: https://thmb.techidaily.com/bae70dc1da321109f70e787435e8a7bf8638e992652aa5e9b27c3e355526ca4c.jpg
---

## Navigating the Labyrayer of Windows Registry via Command Line

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
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394">
  <img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105864/7443" target="_top" id="2105864">
  <img src="//a.impactradius-go.com/display-ad/7443-2105864" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105864/7443" style="position:absolute;visibility:hidden;" border="0" />
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

 If you have [created a Windows Registry file](https://www.makeuseof.com/windows-registry-file-guide/) or downloaded it elsewhere, you can import it into the registry using the **reg import** command. All you need to do is specify the path to the registry file and Command Prompt will do the rest. Here's an example:

`reg import C:\Users\CHIFUNDO\Desktop\MyRegFile.reg`

 Once you run that command, the contents of the reg file will be merged with the registry.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047406/19272" target="_top" id="2047406">
  <img src="//a.impactradius-go.com/display-ad/19272-2047406" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047406/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2094415/7443" target="_top" id="2094415">
  <img src="//a.impactradius-go.com/display-ad/7443-2094415" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094415/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Save Registry Entries

![saving-a-key-to-a-registry-file-in-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/saving-a-key-to-a-registry-file-in-windows.jpg)

 If you already have a registry file or any other text file, you can add keys to it using Command Prompt and the **reg save** command, which will overwrite the file with the new information. You just need to specify the name of the key and the registry file you want to save it to. Here's an example:

`reg save HKLM\SOFTWARE\MyNewKey2 C:\Users\CHIFUNDO\Desktop\MyRegFile.hiv /y`

 The **/y** switch at the end of the command above overwrites the file you're saving the key to without bringing up a prompt. When you open the file, you won't be able to read the contents since it will be saved as a binary file.

## How to Restore Registry Entries

![restoring-a-registry-key-in-command-prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/restoring-a-registry-key-in-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1013424/11832" target="_top" id="1013424">
  <img src="//a.impactradius-go.com/display-ad/11832-1013424" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1013424/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 So, let's say something has happened to the keys and values within the **MyNewKey2** we saved in the previous section, you can use the backup file you created to restore it. You'll need to use the **reg restore** command. Here's how to run it:

`reg restore HKLM\SOFTWARE\MyNewKey2 C:\Users\CHIFUNDO\Desktop\MyRegFile.hiv`

 Now the **MyNewKey2** key should return to the state it was in when you made the backup.

## Tweak the Registry Without the Registry Editor

 While Command Prompt can't do everything the Registry Editor does, it does offer a quick way to edit the registry without opening the aforementioned tool. While using Command Prompt to tweak the registry is quite advanced, even if you're the average user, you should be able to get by if you follow along closely.

 Just don't forget to do what we mentioned earlier to avoid permanently ruining your Windows computer and create a system restore point first

 Although using it takes a little more know-how than the Registry Editor, our guide should be able to get you started.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/024-approved-rise-on-youtube-initiating-your-chanel-and-earning-pathway/"><u>[New] 2024 Approved Rise on YouTube Initiating Your Chanel & Earning Pathway</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-unveiling-sharex-analyses-and-options/"><u>[Updated] Unveiling ShareX Analyses & Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-dual-users-ms-error-on-windows-os/"><u>Addressing Dual Users' MS Error on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-error-0x800700e1-on-modern-windows/"><u>Addressing Error 0X800700E1 on Modern Windows</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/beat-the-time-barrier-and-learn-slovak-in-smart-10-minute-chunks/"><u>Beat the Time Barrier & Learn Slovak in Smart 10-Minute Chunks!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206298676-complete-guide-to-overcome-the-error-5-notification-in-windows-1178-systems-now-solved/"><u>Complete Guide to Overcome the Error 5 Notification in Windows 11/7/8 Systems – Now Solved!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-techniques-to-open-wordpad-in-windows/"><u>Essential Techniques to Open WordPad in Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/guide-transferring-your-imovie-edit-without-idvd-dvd-creation-steps/"><u>Guide: Transferring Your iMovie Edit Without iDVD - DVD Creation Steps</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-does-the-stardust-trade-cost-in-pokemon-go-on-realme-gt-5-240w-drfone-by-drfone-virtual-android/"><u>How does the stardust trade cost In pokemon go On Realme GT 5 (240W)? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-unpair-and-reconnect-devices-effortlessly-on-win-11/"><u>How to Unpair and Reconnect Devices Effortlessly on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-screen-quiet-disable-win11-folders/"><u>Mastering Screen Quiet: Disable Win11 Folders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-win-lsa-troubleshooting/"><u>Mastering the Art of Win LSA Troubleshooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-troubled-waters-in-windows-mail-app-with-0x800713f/"><u>Navigating Through Troubled Waters in Windows Mail App with 0X800713F</u></a></li>
<li><a href="https://tech-hub.techidaily.com/smartwatch-showdown-in-depth-comparison-between-googles-pixel-watch-and-apples-latest-apple-watch-series-n/"><u>Smartwatch Showdown: In-Depth Comparison Between Google's Pixel Watch and Apple's Latest Apple Watch Series N</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-first-5-things-you-should-do-with-your-new-computer/"><u>The First 5 Things You Should Do With Your New Computer</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/top-5-strategies-for-advancing-your-career-path-toward-chief-information-officer-cio-success-insights-from-zdnet/"><u>Top 5 Strategies for Advancing Your Career Path Toward Chief Information Officer (CIO) Success: Insights From ZDNet</u></a></li>
<li><a href="https://tech-revival.techidaily.com/transform-workflows-dive-into-8-customized-ai-models/"><u>Transform Workflows: Dive Into 8 Customized AI Models</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformative-power-for-photo-renewal-with-windows/"><u>Transformative Power for Photo Renewal with Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-access-decoding-password-demand/"><u>Winning Back Access: Decoding Password Demand</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    