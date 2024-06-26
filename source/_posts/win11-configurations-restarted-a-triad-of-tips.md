---
title: "Win11 Configurations Restarted: A Triad of Tips"
date: 2024-06-25T16:46:57.922Z
updated: 2024-06-26T16:46:57.922Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win11 Configurations Restarted: A Triad of Tips"
excerpt: "This Article Describes Win11 Configurations Restarted: A Triad of Tips"
keywords: Win11 Setup Guide,Windows 11 Reboot Advice,Resetting Win11 Settings,Win11 Config Tips,Safe Win11 Restart,Win11 Optimization Steps,Reconfigure Win11 Faster
thumbnail: https://thmb.techidaily.com/a691a544cb7cde4aeceab56e4cf68f393a99f1feb2da71ac3ca94b7300f4d4b3.jpg
---

## Win11 Configurations Restarted: A Triad of Tips

 The Settings app in Windows 11 makes it simple for you to manage various settings and preferences on your computer. Whether you want to customize your computer's theme, manage network connections or check for system updates, the Windows Settings app is a central location for all your computer management needs.

 If the Windows 11 Settings app stops working, or if you want to restore it to its default settings, you can always reset it. You can reset the Windows Settings app using the search menu, Command Prompt or PowerShell. Let's go over all three methods in detail.

## 1\. How to Reset the Windows 11 Settings App Using the Search Menu

 The quickest way to reset the Windows 11 Settings app is through the search menu. So, let's start with that.

To reset the Windows 11 Settings app with the search menu:

1. Click the magnifying icon on the taskbar or use the**Win + S** keyboard shortcut to access the search menu.
2. Type**Settings** in the search box.
3. Select the**App settings** option from the right pane.
4. Scroll down to the Reset section and click the**Reset** button.
5. Select**Reset** again to confirm.  
![Reset Settings App in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reset-settings-app-in-windows-11.jpg)

 After completing the above steps, you can use one of the [many ways to access the Windows Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) and configure it again.

## 2\. How to Reset the Windows 11 Settings App via PowerShell

 If you prefer to interact with your computer through a command-line interface, you can also use PowerShell to reset the Windows Settings app. Don’t worry, the process isn’t as intimidating as it might sound.

 Use these steps to reset the Windows 11 Settings app using PowerShell.

1. Click the**search icon** on the taskbar to open the search menu.
2. Type**Windows PowerShell** in the search box.
3. Select**Run as administrator** from the right side.
4. When the User Account Control (UAC) prompt appears, select**Yes** to continue.
5. In the console, type the following command and press**Enter** to reset the Settings app.  
`Get-AppxPackage *Windows.ImmersiveControlPanel* | Reset-AppxPackage`  
![Reset Settings App Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reset-settings-app-using-powershell.jpg)

 If you're a PowerShell enthusiast, why not take the time to learn these [useful Windows PowerShell commands](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) to improve efficiency?

## 3\. How to Reset the Windows 11 Settings App Using Command Prompt

 Another way to reset the Windows 11 Settings app is via Command Prompt. Similar to the method above, resetting the Settings app using Command Prompt only requires you to run a single command.

 To reset the Windows 11 Settings app using Command Prompt, use these steps:

1. Press**Win + X** or right-click the**start icon** to open the Power User menu and select**Run** from the list.
2. Type**cmd** in the text box and then press**Ctrl + Shift + Enter** on your keyboard to [open Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/#how-to-run-command-prompt-as-an-administrator-through-the-windows-search-tool) .
3. Select**Yes** when the User Account Control (UAC) prompt shows up.
4. In the console, paste the following command and hit**Enter** :  
`PowerShell -ExecutionPolicy Unrestricted -Command "& {$manifest = (Get-AppxPackage *immersivecontrolpanel*).InstallLocation + '\AppxManifest.xml' ; Add-AppxPackage -DisableDevelopmentMode -Register $manifest}"`

![Reset Settings App Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reset-settings-app-using-command-prompt.jpg)

 Once you run the above command, Windows will reset the Settings app on your computer.

 Do you find Command Prompt to be too complicated or boring to use? Here are some of [the best Command Prompt alternatives for Windows](https://www.makeuseof.com/best-command-prompt-alternatives-for-windows/) worth trying.

## Resetting the Windows 11 Settings App

 Regardless of the method you use, resetting Windows 11 Settings app shouldn’t take more than a couple of minutes of your time. After that, you can start configuring your computer settings from scratch.

 If, however, resetting the Settings app does not solve your problem, you can try creating a new user account. Alternatively, you can consider factory resetting your Windows 11 computer and starting over.


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
<li><a href="https://win11-tips.techidaily.com/gain-early-access-the-way-into-windows-11-beta/"><u>Gain Early Access: The Way Into Windows 11 Beta</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-windows-error-loadlib-err-87/"><u>Mitigating Windows Error LoadLib Err 87</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-pinnacle-clarity-to-your-w11-desktop-wallpaper/"><u>Bringing Pinnacle Clarity to Your W11 Desktop Wallpaper</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-usability-faster-uninstall-options-in-win/"><u>Enhancing Usability: Faster Uninstall Options in Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-reviving-non-functioning-reading-aloud-in-word-2016plus/"><u>Quick Guide to Reviving Non-Functioning Reading Aloud in Word 2016+</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-browser-security-with-trusted-site-listing/"><u>Upgrade Browser Security with Trusted Site Listing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augment-windows-management-with-a-disk-space-analysis-tool/"><u>Augment Windows Management with a Disk Space Analysis Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cortana-ends-new-windows-aid-emerges/"><u>Cortana Ends, New Windows Aid Emerges</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-mechanics-behind-failed-usb-attachment-in-virtualbox/"><u>Decoding the Mechanics Behind Failed USB Attachment in VirtualBox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-printer-error-0x8000ffff-in-windows/"><u>How to Fix the Printer Error 0X8000ffff in Windows</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-premium-choice-10-leading-webcams-for-win-11/"><u>[New] In 2024, Premium Choice  10 Leading Webcams for Win 11</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/easy-guide-how-to-bypass-tecno-pova-5-frp-android-10111213-by-drfone-android/"><u>Easy Guide How To Bypass Tecno Pova 5 FRP Android 10/11/12/13</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/transforming-your-reel-game-on-instagram-in-days/"><u>Transforming Your Reel Game on Instagram in Days</u></a></li>
<li><a href="https://extra-tips.techidaily.com/conquer-the-vr-world-your-first-vr-adventure-for-2024/"><u>Conquer the VR World  Your First VR Adventure for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-the-premier-10-webinar-applications/"><u>[New] The Premier 10 Webinar Applications</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-mobile-animation-made-easy-top-10-apps-for-android-and-ios/"><u>New In 2024, Mobile Animation Made Easy Top 10 Apps for Android and iOS</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-captivate-crowds-mastering-hashtag-use-in-high-traffic-short-videos/"><u>[New] Captivate Crowds  Mastering Hashtag Use in High-Traffic Short Videos</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-3-simple-ways-to-color-grading-in-adobe-photoshop/"><u>[Updated] 3 Simple Ways to Color Grading in Adobe Photoshop</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-future-of-interaction-with-microsofts-hololens-review/"><u>The Future of Interaction with Microsoft's HoloLens Review</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-lava-yuva-2-by-drfone-android-unlock-android-unlock/"><u>How to unlock Lava Yuva 2</u></a></li>
</ul></div>
