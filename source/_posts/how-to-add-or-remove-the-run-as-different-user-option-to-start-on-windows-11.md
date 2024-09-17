---
title: How to Add or Remove the “Run as Different User” Option to Start on Windows 11
date: 2024-09-13T01:00:06.993Z
updated: 2024-09-16T21:45:14.983Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Add or Remove the “Run as Different User” Option to Start on Windows 11
excerpt: This Article Describes How to Add or Remove the “Run as Different User” Option to Start on Windows 11
keywords: Windows 11 User Switching,Run As Admin Window,Adjust Startup Rights,Modify User Controls Windows,Change Default User Mode,Alter Start Menu Policy,Manage Windows Security Options
thumbnail: https://thmb.techidaily.com/010139d6077f90333f3025af8c182332c9900266fd1f6067fe122889069013d2.jpg
---

## How to Add or Remove the “Run as Different User” Option to Start on Windows 11

 There are times when you want to run programs and processes as a different user in the Start menu, only to find the **Run as different user** option missing in the context menu. Other times, you might want to prevent other users from using that option due to security and privacy reasons.

 No matter the case, there are several ways to add or remove the **Run as different user** option from the Start menu on Windows 11\. Here are three of them.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Add or Remove “Run as Different User” Using Settings

 Press **Win + I** to open the Settings app. In the left pane, select **Privacy & security** and then click on **For developers** in the right pane.

![the security section of the Privacy and security settings on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-settings-security.jpg)

 Expand the **File Explorer** section and then click on the toggle next to **Show option to run as different user in Start**. If the toggle was **On**, it would now become **Off** and vice-versa.

![the File Explorer section of the For developers page in Windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-settings-for-devs-file-explorer.jpg)

## 2\. How to Add or Remove “Run as Different User” to Start Using the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, enter **gpedit.msc** in the text box, and then click **OK** to open the Local Group Policy Editor. Then, head to **User Configuration > Start Menu and Taskbar** in the left pane and double-click on the **Show “Run as different user” command on Start** policy in the right pane.

![The Show Run as different user command on Start policy in the Local Group Policy Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-as-different-user-policy-windows.jpg)

 To add **Run as different user** to the context menu in Start, set the radio button to **Enabled** and click **OK** to apply the changes. If you want to remove the option, set the radio button to **Not Configured** or **Disabled** instead.

![Editing the Show Run as different user command on Start policy in the Local Group Policy Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-run-as-different-user-policy-windows.jpg)

 Now that user profile won’t be able to use the **Run as different user** optionin the Start menu**.**

## 3\. How to Add or Remove “Run as Different User” to Start Using the Registry Editor

 Press **Win + R** to open Windows Run, enter **regedit** in the text box, and then click **OK**. Then, click **Yes** when the UAC prompt comes up. The Registry Editor will now launch.

 Since you’ll be making changes to the Windows registry in this section, which can potentially break Windows if you make a mistake, it’s a good idea to create some sort of backup. To do that, we recommend that you either [back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) before moving forward.

 In the Registry Editor, you can add or remove the **Run as different user** in the Start menu for the current user or all users. We will look at how to do both.

 For the current user only, head to the following registry key using the Registry Editor’s navigation pane on the left: **HKEY\_CURRENT\_USER > SOFTWARE > Policies > Microsoft > Windows > Explorer**.

![run-as-different-user-value-current-user-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-as-different-user-value-current-user-windows.jpg)

 If you want to add or remove the option for all users, head to the following key: **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows > Explorer**.

![run-as-different-user-value-all-users-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-as-different-user-value-all-users-windows.jpg)

 In the right pane, look for the **ShowRunAsDifferentUserInStart** value. If it's not available, right-click the **Explorer** key in the left pane and select **New > DWORD (32-bit) Value**. Then, name the newly-created value **ShowRunAsDifferentUserInStart**.

![new-dword-explorer-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/new-dword-explorer-windows.jpg)

 Now, double-click the **ShowRunAsDifferentUserInStart** value to edit it.To add the **Run as different user** option in the Start menu, set **Value Data** to **1**.

![edit-showrunasdifferentuserinstart-value-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-showrunasdifferentuserinstart-value-windows.jpg)

 To remove it, set **Value data** to **0**.

<!-- affiliate ads begin -->
<span id="1975503">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975503.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975503">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975503.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975503%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975503/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Access to the “Run as Different User” Option in the Start Menu

 Sometimes, it’s useful to run a program or process as a different user on Windows, and other times, it’s not. As the admin, you have the power to add or remove the option to do so in the Start menu. We recommend you do that in Settings or with the Local Group Policy Editor, though—only tweak the Registry if you have to.

 Keep in mind that even though people using your computer won’t be able to run programs and processes as different users in Start, they can still do so using other methods.

 No matter the case, there are several ways to add or remove the **Run as different user** option from the Start menu on Windows 11\. Here are three of them.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-24-hour-film-size-gb-measurement-guide/"><u>[New] 2024 Approved 24-Hour Film Size GB Measurement Guide</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-innovative-gb-recorder-for-games-on-fbx/"><u>[Updated] 2024 Approved Innovative GB Recorder for Games on FBX</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/a-complete-guide-to-oem-unlocking-on-honor-x9b-by-drfone-android/"><u>A Complete Guide To OEM Unlocking on Honor X9b</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-complex-policies-gpresult-techniques-explored/"><u>Conquering Complex Policies: GPResult Techniques Explored</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-glowing-cursors-on-your-computer-screen/"><u>Guidelines for Glowing Cursors on Your Computer Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-0x80049dd3-voice-typing-error-in-windows-11/"><u>How to Fix the 0X80049dd3 Voice Typing Error in Windows 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-samsung-galaxy-f54-5g-to-mac-drfone-by-drfone-android/"><u>How to Mirror Samsung Galaxy F54 5G to Mac? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-11-pro-max-to-other-iphone-13-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 11 Pro Max to other iPhone 13 devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-win11-printer-headaches-with-simple-steps/"><u>Stop Win11 Printer Headaches with Simple Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-guide-to-wintoys-unleashing-the-full-potential-of-a-powerful-windows-app/"><u>The Complete Guide to WinToys: Unleashing the Full Potential of a Powerful Windows App</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-windows-registry-explained-how-it-affects-software-management/"><u>The Windows Registry Explained: How It Affects Software Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-steams-unsyncable-files-issue-on-pc/"><u>Troubleshooting Steam's Unsyncable Files Issue on PC</u></a></li>
<li><a href="https://win-answers.techidaily.com/wmamp3mp3wma/"><u>WMAとMP3ファイル形式の明確な比較：それぞれの特徴とMP3からWMAへ変換する手順を深く掘り下げて解説</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    