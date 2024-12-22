---
title: How to Reset and Customize Your Touch Panel's Start Position
date: 2024-12-19T00:24:52.820Z
updated: 2024-12-22T03:34:11.805Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Reset and Customize Your Touch Panel's Start Position
excerpt: This Article Describes How to Reset and Customize Your Touch Panel's Start Position
keywords: Touch Panel Start Pos,Reset TP Positioning,Customize TP Layout,TP Start Configuration,Adjust Touch Panel Screen,Touch TP Initial View,Modify TP Display Setup
thumbnail: https://thmb.techidaily.com/02857e9a5729a034df5799d80242303ce172ee6947ee8ec278b9096d58e3459c.jpg
---

## How to Reset and Customize Your Touch Panel's Start Position

 Are you using a Windows touchscreen device and experiencing keyboard issues? This often occurs when certain keys are difficult to use or scrolling becomes tricky because the keyboard pops up in the wrong spot.

 To help with this issue, we'll explain two methods to reset the default opening position of your touch keyboard in Windows 11\. The first method requires running a batch file, while the second involves tweaking the Windows Registry Editor.

Let's explore each one.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oeSN3u4fO9M?si=Ua3Hzcil6u6akDgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Tweak Registry Editor to Reset Touch Keyboard Default Open Position

 The Registry Editor is an advanced tool and requires caution when editing. But if you want to reset the default opening position of the touch keyboard efficiently, this is the method to use. However, as I have said before, you have to be especially careful when editing the Registry Editor as any mistake could cause serious damage.

 It is always a good idea to[create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) or to take a[backup of the registry editor](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before starting. This can help if something goes wrong. It is now time to reset the default open position of the touch keyboard. To do so, follow these steps:

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/vQbNyknjJJ8?si=RGVIEWLdPbvRC_r6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Similarly, delete the**OptimizedKeyboardRelativeYPositionOnScreen** key value in the same folder.

 After deleting both values, close the Registry Editor and restart your PC to apply the changes. Now, when you open the touch keyboard, it will start showing up at the default opening position.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fo4lNZ84x9Q?si=WdcYPZp-9VJnZEnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In the File name field, type "ResetTouch.bat", and choose**All Files** from the Save as type. After that, select Desktop from the left-hand side and click**Save** .

 Once the batch file is saved, close the Notepad window. Next, double-click**ResetTouch.bat** on your Desktop to run it. This should reset your touch keyboard's default open position.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1KKovVi9epE?si=EF7KA7b4KsEpWA-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://twitter-videos.techidaily.com/new-sync-twitch-with-snapchat-a-step-by-step-guide-for-2024/"><u>[New] Sync Twitch with Snapchat A Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-best-companions-premium-mac-programs-for-videography/"><u>[Updated] Best Companions Premium Mac Programs for Videography</u></a></li>
<li><a href="https://howto.techidaily.com/8-workable-fixes-to-the-sim-not-provisioned-mm2-error-on-motorola-razr-40-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Workable Fixes to the SIM not provisioned MM#2 Error on Motorola Razr 40 | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/webp-tiff-movavi/"><u>在網路上無成本 WEBP 檔案變更TIFF - 利用Movavi對準器</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-install-official-hp-printer-drivers-with-ease/"><u>Download and Install Official HP Printer Drivers with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-faded-windows-reviving-your-displays-palette/"><u>Fixing Faded Windows: Reviving Your Display's Palette</u></a></li>
<li><a href="https://win11-tips.techidaily.com/functional-failures-cure-win10-key-issues-now/"><u>Functional Failures? Cure Win10 Key Issues Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-your-browsing-on-windows-11-adding-reliable-domains/"><u>Secure Your Browsing on Windows 11: Adding Reliable Domains</u></a></li>
<li><a href="https://win11-tips.techidaily.com/syncing-two-networks-a-guide-to-using-wi-fi-and-ethernet-together-on-windows/"><u>Syncing Two Networks: A Guide to Using Wi-Fi & Ethernet Together on Windows</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-best-cheap-action-cameras-to-purchase-for-under-100-for-2024/"><u>The Best Cheap Action Cameras to Purchase for Under $100 for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/unleash-your-creativity-10-top-rated-music-video-makers-for-2024/"><u>Unleash Your Creativity 10 Top-Rated Music Video Makers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-windows-11-notepads-potential-the-theme-and-font-method/"><u>Unlock Windows 11 Notepad's Potential: The Theme and Font Method</u></a></li>
</ul></div>

