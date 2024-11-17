---
title: "Correcting WinError: Misconfigured File History Settings"
date: 2024-11-14T19:13:11.991Z
updated: 2024-11-17T19:34:39.888Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Correcting WinError: Misconfigured File History Settings"
excerpt: "This Article Describes Correcting WinError: Misconfigured File History Settings"
keywords: Fix Windows Error FHS,Resolve File History FS Error,Adjust File History Issue,Correct HFS Misconfiguration,Address WinError FH Settings,Mend FileHistory WinErr,Tweak FileHistory Configs
thumbnail: https://thmb.techidaily.com/8823459ab6574b19c976d6905c67df41ee5da35193b7ba8be663bba21950e5e8.jpg
---

## Correcting WinError: Misconfigured File History Settings

 File History is a nifty feature on Windows that allows you to back up your important files and folders to an external drive. Although the feature works as expected most of the time, it can occasionally trouble you with errors like the “We found errors in your File History settings” on Windows.

 Let’s see how you can resolve this error and get the File History feature to work again on Windows.

## 1\. Restart the File History Service

 File History Service is a small program that needs to be running in the background for the File History feature to work. If this service is experiencing any problems, you could run into the "We found errors in your File History settings" error. In most cases, you can fix any temporary issues with File History Service by simply restarting it.

To restart the File History Service in Windows:

1. Right-click on the**Start icon** and select**Run** from the resulting menu.
2. Type**services.msc** in the text box and press**Enter** .
3. In the Services windows, scroll down to locate**File History Service** . Right-click on it and select**Restart** . If the service is not running, select**Start** .  
![Restart File Hisotry Service Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/restart-file-hisotry-service-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139114/17108" target="_top" id="2139114">
  <img src="//a.impactradius-go.com/display-ad/17108-2139114" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139114/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Disconnect and Reconnect the Backup Drive

 Connection problems with your external drive can also cause Windows to display the "We found errors in your File History settings" error. If it’s nothing major, you should be able to resolve the error by disconnecting and reconnecting your backup drive.

 While you're at it, try using a different USB port. This will help you determine if there’s a[problem with the USB port](https://www.makeuseof.com/tag/dead-usb-port-heres-how-to-diagnose-and-fix-it/) you’re using. If you suspect a port is malfunctioning, check out how to diagnose and fix a faulty USB port on Windows.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136545/16384" target="_top" id="2136545">
  <img src="//a.impactradius-go.com/display-ad/16384-2136545" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136545/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Re-Select the Backup Drive and Restart File History

 Next, you can try re-selecting your backup drive in File History settings and see if that helps. Here are the steps for the same.

1. Press**Win + R** or use one of the[many ways to open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**control** in the box and press**Enter** .
3. Click the**View by** drop-down menu and select**Large icons** .
4. Select**File History** from the Control Panel menu items.
5. Click the**Select drive** option from the left sidebar.
6. Select your preferred drive from the list and click**OK** .  
![Select File History Drive Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/select-file-history-drive-windows.jpg)

 After selecting your preferred drive, you’ll have to restart the File History feature on Windows. To do so, use the following steps:

1. Click the magnifying icon on the taskbar or use the**Win + S** keyboard shortcut to open the search menu.
2. Type**file history** in the search box and select the first result that appears.
3. In the Control Panel window that opens, click the**Turn off** button.
4. Wait for a few seconds and click the**Turn on** button.  
![Turn On File History in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-on-file-history-in-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528689/16446" target="_top" id="1528689">
  <img src="//a.impactradius-go.com/display-ad/16446-1528689" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528689/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the error message persists even after this, you can try using a different drive for the File History backup and see if that works.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997657/19272" target="_top" id="1997657">
  <img src="//a.impactradius-go.com/display-ad/19272-1997657" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997657/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Reset File History

 Finally, if nothing else works, resetting File History may be your only option. You can accomplish this by deleting the File History data files from your computer.

 In order to delete File History data files, you’ll have to ensure that your PC is configured to[show hidden files and folders on Windows](https://www.makeuseof.com/windows-11-show-hidden-files-folders/) . Here’s how to check.

1. Open the Windows search menu.
2. Type**File Explorer Options** in the search box and press**Enter** .
3. Switch to the**View** tab and check the**Show hidden files, folders, and drives** option.
4. Hit**Apply** followed by**OK** .

 Now, delete the File History data from your system by following the steps below.

1. Press**Win + E** to open File Explorer.
2. Type the following path in the File Explorer’s address bar and press**Enter** .  
`%UserProfile%\AppData\Local\Microsoft\Windows\FileHistory`
3. Press**Ctrl + A** to select all the folders and click the**trash icon** at the top to delete them.  
![Delete File Hisotry AppData](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/delete-file-hisotry-appdata.jpg)

## Fixing File History Errors on Windows

 After you apply the fixes listed above, the File History error should no longer bother you.

 Tired of dealing with File History errors on your Windows device? It might be a good idea to use a cloud storage service or third-party backup software to protect your important data.

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
<li><a href="https://some-guidance.techidaily.com/new-the-ultimate-gopro-camera-showdown/"><u>[New] The Ultimate GoPro Camera Showdown</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-capture-clarity-enjoy-convenience-with-our-top-5-recorder-recommendations-for-2024/"><u>[Updated] Capture Clarity, Enjoy Convenience with Our Top 5 Recorder Recommendations for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-crafting-an-epic-unboxing-journey/"><u>2024 Approved Crafting an Epic Unboxing Journey</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-professional-drone-use-in-visual-storytelling/"><u>2024 Approved Professional Drone Use in Visual Storytelling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-erratic-windows-updates-x8019/"><u>Dealing with Erratic Windows Updates: X8019</u></a></li>
<li><a href="https://buynow-info.techidaily.com/discover-why-the-linksys-wrt3200acm-is-hailed-as-an-exceptional-open-source-solution/"><u>Discover Why the Linksys WRT3200ACM Is Hailed as an Exceptional Open Source Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-win-11-gaming-with-these-top-7-essentials/"><u>Elevate Win 11 Gaming with These Top 7 Essentials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-the-intricacies-of-windows-11s-data-recovery-functionality/"><u>Exploring the Intricacies of Windows 11'S Data Recovery Functionality</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-iphone-se-2022-icloud-activation-lock-bypass-by-drfone-ios/"><u>In 2024, iPhone SE (2022) iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://tech-hub.techidaily.com/secure-or-not-third-party-gpt-software/"><u>Secure or Not? Third-Party GPT Software</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/silent-symphonies-tranquil-audio-transitioning-tools-for-2024/"><u>Silent Symphonies Tranquil Audio Transitioning Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/six-steps-to-unearth-the-mystery-of-your-window-based-pc-name/"><u>Six Steps to Unearth the Mystery of Your Window-Based PC Name</u></a></li>
<li><a href="https://win11-tips.techidaily.com/three-techniques-to-delete-windows-11-store/"><u>Three Techniques to Delete Windows 11 Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winerror-0x80070091-demystified-how-to-clear-not-empty-directive/"><u>WinError 0X80070091 Demystified: How to Clear 'Not Empty' Directive</u></a></li>
</ul></div>

