---
title: Adjust and Reset Windows 11'S Touch Keyboard Layout
date: 2025-01-30T19:55:56.827Z
updated: 2025-02-01T10:45:31.592Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjust and Reset Windows 11'S Touch Keyboard Layout
excerpt: This Article Describes Adjust and Reset Windows 11'S Touch Keyboard Layout
keywords: Windows 11 Keyboard Setup,Reset Keyboard Layout,Windows 11 Adjustment,Keyboard Settings Win11,Change Touch Keys Win11,Reset Windows 11 Layout,Update Keyboard Win11
thumbnail: https://thmb.techidaily.com/1b3acf6f92837e9104aa399e6aa268354b94b6b827af6bb095b68b19082ca48f.png
---

## Adjust and Reset Windows 11'S Touch Keyboard Layout

 Are you using a Windows touchscreen device and experiencing keyboard issues? This often occurs when certain keys are difficult to use or scrolling becomes tricky because the keyboard pops up in the wrong spot.

 To help with this issue, we'll explain two methods to reset the default opening position of your touch keyboard in Windows 11\. The first method requires running a batch file, while the second involves tweaking the Windows Registry Editor.

Let's explore each one.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Tweak Registry Editor to Reset Touch Keyboard Default Open Position

 The Registry Editor is an advanced tool and requires caution when editing. But if you want to reset the default opening position of the touch keyboard efficiently, this is the method to use. However, as I have said before, you have to be especially careful when editing the Registry Editor as any mistake could cause serious damage.

 It is always a good idea to [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) or to take a [backup of the registry editor](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before starting. This can help if something goes wrong. It is now time to reset the default open position of the touch keyboard. To do so, follow these steps:

1. Press**Win + R** on your keyboard to open the Run dialog box.
2. Type**regedit** in the text box and press Enter. This will launch the Registry Editor.
3. Click**Yes** if the UAC (User Account Control) window asks for permission.
4. Once you're in the Registry Editor, navigate to this location:  
`HKEY_CURRENT_USER\Software\Microsoft\TabletTip\1.7`  
 Alternatively, you can copy and paste the given path into the Registry Editor's address bar. This will take you to the specified location.
5. On the left side of the menu, select the**1.7** folder.  
![Tweak Registry Editor to Reset Touch Keyboard Default Open Position](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/tweak-registry-editor-to-reset-touch-keyboard-default-open-position.jpg)
6. Then go to its corresponding right pane, where you will find the**OptimizedKeyboardRelativeXPositionOnScreen** REG\_DOWRD value. Right-click on the key and delete it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mHFtYJppXFk?si=ylFaAT4nXqCmlV8F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Similarly, delete the**OptimizedKeyboardRelativeYPositionOnScreen** key value in the same folder.

 After deleting both values, close the Registry Editor and restart your PC to apply the changes. Now, when you open the touch keyboard, it will start showing up at the default opening position.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Sj2QNA-JXI?si=V-_h73iE3VlE214k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Run a Batch File to Reset the Touch Keyboard's Default Open Position

 Resetting the default opening position of your touch keyboard can be done quickly and easily by running a batch file. This method is especially useful if you prefer to automate the reset process instead of manually tweaking the registry editor. Here is how to do it.

 To get started, you first need to open the Notepad application. For this, you can type "Notepad" in either Windows Search or the Run dialog box and press**Enter** .

 Once you're in Notepad, copy and paste the following code into it:

`@echo off  
REG Delete "HKCU\SOFTWARE\Microsoft\TabletTip\1.7" /V OptimizedKeyboardRelativeXPositionOnScreen /F  
REG Delete "HKCU\SOFTWARE\Microsoft\TabletTip\1.7" /V OptimizedKeyboardRelativeYPositionOnScreen /F  
taskkill /f /im explorer.exe  
start explorer.exe`

 Now click**File** in the upper-left corner and select**Save As** from the menu list.

![Run Batch File to Reset Touch Keyboard Default Open Position](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-batch-file-to-reset-touch-keyboard-default-open-position.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In the File name field, type "ResetTouch.bat", and choose**All Files** from the Save as type. After that, select Desktop from the left-hand side and click**Save** .

 Once the batch file is saved, close the Notepad window. Next, double-click**ResetTouch.bat** on your Desktop to run it. This should reset your touch keyboard's default open position.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n-66V-LRK3Y?si=fNeB2pXCePeQli6E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Resetting the Default Position of the Touch Keyboard

 If you're using a Windows touchscreen device, typing with a touch keyboard can be easy. However, you might have noticed an inconvenience where the keyboard opens in an awkward position.

 This can make typing on specific keys difficult, especially if you're used to accessing the keyboard from a certain spot. To fix this issue, refer to this guide on resetting the default open position of your touch keyboard.

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
<li><a href="https://some-techniques.techidaily.com/new-how-to-stand-out-in-snapchat-spotlight/"><u>[New] How to Stand Out in Snapchat Spotlight</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-learn-the-insider-tricks-of-screening-instagram-stories/"><u>[New] In 2024, Learn the Insider Tricks of Screening Instagram Stories</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/treamline-your-video-strategy-tubebuddys-guide-for-2024/"><u>[New] Streamline Your Video Strategy TubeBuddy's Guide for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-enriching-videos-with-no-cost-sounds-legally-for-2024/"><u>[Updated] Enriching Videos with No-Cost Sounds Legally for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-legal-implications-and-tips-when-archiving-whatsapp-call-recordings/"><u>[Updated] Legal Implications & Tips When Archiving WhatsApp Call Recordings</u></a></li>
<li><a href="https://location-social.techidaily.com/4-most-known-ways-to-find-someone-on-tinder-for-motorola-defy-2-by-name-drfone-by-drfone-virtual-android/"><u>4 Most-Known Ways to Find Someone on Tinder For Motorola Defy 2 by Name | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-enabledisable-registry-access-in-win11/"><u>Command: Enable/Disable Registry Access in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/designing-safe-quick-access-tool-for-hardware-in-win11/"><u>Designing Safe, Quick Access Tool for Hardware in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-to-add-outlook-preview-on-pcs/"><u>Essential Tips to Add Outlook Preview on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-steam-disconnect-on-a-windows-pc/"><u>Fixing Steam Disconnect on a Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-unavailable-roblox-on-windows-due-to-account-configs/"><u>Fixing Unavailable Roblox on Windows Due to Account Configs</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-foremost-websites-accelerating-youtube-traffic/"><u>In 2024, Foremost Websites Accelerating YouTube Traffic</u></a></li>
<li><a href="https://extra-tips.techidaily.com/secrets-to-perfecting-snapchats-playback-speed-settings/"><u>Secrets to Perfecting Snapchat's Playback Speed Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unseen-solutions-to-windows-monitoring-woes/"><u>Unseen Solutions to Windows Monitoring Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-file-harmony-aoemis-sync-solution-tutorial/"><u>Windows File Harmony: AOEMi's Sync Solution Tutorial</u></a></li>
</ul></div>

