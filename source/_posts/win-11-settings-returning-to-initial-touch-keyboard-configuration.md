---
title: "Win 11 Settings: Returning to Initial Touch Keyboard Configuration"
date: 2024-06-25T16:29:53.872Z
updated: 2024-06-26T16:29:53.872Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win 11 Settings: Returning to Initial Touch Keyboard Configuration"
excerpt: "This Article Describes Win 11 Settings: Returning to Initial Touch Keyboard Configuration"
keywords: Win 11 Keyboard Setup,Windows 11 Default Input,Revert Win 11 Keyboard,Initial Touch Keys Win,Win 11 Key Configuration,Restore Windows 11 Icons,Reset Windows 11 Keyboard
thumbnail: https://thmb.techidaily.com/a1972899444c7fd6c447adfaf7d10b9ab8c7ebd024be2fc74b2760fa4d84aacb.jpg
---

## Win 11 Settings: Returning to Initial Touch Keyboard Configuration

 Are you using a Windows touchscreen device and experiencing keyboard issues? This often occurs when certain keys are difficult to use or scrolling becomes tricky because the keyboard pops up in the wrong spot.

 To help with this issue, we'll explain two methods to reset the default opening position of your touch keyboard in Windows 11\. The first method requires running a batch file, while the second involves tweaking the Windows Registry Editor.

Let's explore each one.

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
7. Similarly, delete the**OptimizedKeyboardRelativeYPositionOnScreen** key value in the same folder.

 After deleting both values, close the Registry Editor and restart your PC to apply the changes. Now, when you open the touch keyboard, it will start showing up at the default opening position.

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

 In the File name field, type "ResetTouch.bat", and choose**All Files** from the Save as type. After that, select Desktop from the left-hand side and click**Save** .

 Once the batch file is saved, close the Notepad window. Next, double-click**ResetTouch.bat** on your Desktop to run it. This should reset your touch keyboard's default open position.

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
<li><a href="https://win11-tips.techidaily.com/boosting-your-battlenet-downloads-win-pc-style/"><u>Boosting Your Battle.net Downloads, Win-PC Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-network-access-on-windows-10-and-11-through-telnet/"><u>Boosting Network Access on Windows 10 & 11 Through Telnet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-overheat-in-laptops-with-intensive-play/"><u>Preventing Overheat in Laptops with Intensive Play</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-9-analytical-points-showcasing-pcs-edge-over-macs/"><u>Top 9 Analytical Points Showcasing PC's Edge Over Macs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-how-you-use-the-mouse-cross-border-efficiency-via-powertoys/"><u>Transforming How You Use the Mouse: Cross-Border Efficiency via PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instantly-power-off-windows-11-when-not-in-use/"><u>Instantly Power Off Windows 11 When Not in Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-text-selection-in-windows-compatible-pdfs/"><u>Mastering Text Selection in Windows-Compatible PDFs</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-navigate-through-youtube-content-with-flexibility/"><u>[Updated] Navigate Through YouTube Content with Flexibility</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-how-to-make-asmr-videos-all-you-need-to-know/"><u>In 2024, How to Make ASMR Videos  All You Need to Know</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-ultimate-guide-to-digital-green-magic-comprecipate-free-lessons-from-4-masterful-channels-for-2024/"><u>The Ultimate Guide to Digital Green Magic  Comprecipate Free Lessons From 4 Masterful Channels for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-swift-solutions-for-auditory-clarity-banishing-buildup-noise-for-2024/"><u>New Swift Solutions for Auditory Clarity Banishing Buildup Noise for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-music-enhanced-imagery-web-edition/"><u>In 2024, Music-Enhanced Imagery Web Edition</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-from-zte-nubia-z60-ultra-by-drfone-android/"><u>How to Bypass FRP from ZTE Nubia Z60 Ultra?</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-innovative-strategies-for-capturing-live-lectures-a-mac-centric-approach/"><u>[Updated] In 2024, Innovative Strategies for Capturing Live Lectures  A Mac-Centric Approach</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-recommended-best-applications-for-mirroring-your-realme-v30-screen-drfone-by-drfone-android/"><u>In 2024, Recommended Best Applications for Mirroring Your Realme V30 Screen | Dr.fone</u></a></li>
</ul></div>
