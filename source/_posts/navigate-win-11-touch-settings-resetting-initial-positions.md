---
title: "Navigate Win 11 Touch Settings: Resetting Initial Positions"
date: 2024-10-01T17:50:42.784Z
updated: 2024-10-03T18:10:18.109Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Navigate Win 11 Touch Settings: Resetting Initial Positions"
excerpt: "This Article Describes Navigate Win 11 Touch Settings: Resetting Initial Positions"
keywords: Win 11 Setup Guide,Reset Win 11 Positions,Navigate Win 11 Layouts,Win 11 Touch Configurations,Reinitialize Win Settings,Win 11 Initial Positioning,Win 11 Interface Adjustments
thumbnail: https://thmb.techidaily.com/8873a1de6b737b1bdaf613e6b23cabb06e207ebbce95a2d263cbd7e4a2de27ba.jpg
---

## Navigate Win 11 Touch Settings: Resetting Initial Positions

 Are you using a Windows touchscreen device and experiencing keyboard issues? This often occurs when certain keys are difficult to use or scrolling becomes tricky because the keyboard pops up in the wrong spot.

 To help with this issue, we'll explain two methods to reset the default opening position of your touch keyboard in Windows 11\. The first method requires running a batch file, while the second involves tweaking the Windows Registry Editor.

Let's explore each one.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
7. Similarly, delete the**OptimizedKeyboardRelativeYPositionOnScreen** key value in the same folder.

 After deleting both values, close the Registry Editor and restart your PC to apply the changes. Now, when you open the touch keyboard, it will start showing up at the default opening position.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123749/7443" target="_top" id="2123749">
  <img src="//a.impactradius-go.com/display-ad/7443-2123749" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123749/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1896527/19272" target="_top" id="1896527">
  <img src="//a.impactradius-go.com/display-ad/19272-1896527" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896527/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In the File name field, type "ResetTouch.bat", and choose**All Files** from the Save as type. After that, select Desktop from the left-hand side and click**Save** .

 Once the batch file is saved, close the Notepad window. Next, double-click**ResetTouch.bat** on your Desktop to run it. This should reset your touch keyboard's default open position.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036486/19272" target="_top" id="2036486">
  <img src="//a.impactradius-go.com/display-ad/19272-2036486" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036486/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-enhance-engagement-with-these-4-looping-video-techniques/"><u>[New] In 2024, Enhance Engagement with These 4 Looping Video Techniques</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-quick-diy-tricks-for-professional-quality-homemade-films/"><u>[Updated] Quick DIY Tricks for Professional-Quality Homemade Films</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/easy-steps-to-access-windows-10-advanced-startup-settings/"><u>Easy Steps to Access Windows 10 Advanced Startup Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-network-discovery-is-turned-off-error-on-windows/"><u>How to Fix the “Network Discovery Is Turned Off” Error on Windows</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-fake-snapchat-location-without-jailbreak-on-motorola-edge-40-neo-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fake Snapchat Location without Jailbreak On Motorola Edge 40 Neo | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-paving-the-path-for-creativity-turning-gifs-to-stickers-on-all-social-platforms/"><u>In 2024, Paving the Path for Creativity Turning GIFS to Stickers on All Social Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insight-microsofts-vcplusplus-release-rationale/"><u>Insight: Microsoft's VC++ Release Rationale</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methodology-for-amending-lost-drive-issue/"><u>Methodology for Amending Lost Drive Issue</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/palette-perfection-essential-techniques-to-brighten-your-photos-for-2024/"><u>Palette Perfection Essential Techniques to Brighten Your Photos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-app-interference-with-windows-power-control/"><u>Troubleshooting App Interference with Windows Power Control</u></a></li>
</ul></div>

