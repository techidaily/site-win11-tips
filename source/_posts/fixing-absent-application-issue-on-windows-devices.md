---
title: Fixing Absent Application Issue on Windows Devices
date: 2024-10-03T02:32:58.466Z
updated: 2024-10-08T18:25:55.145Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Absent Application Issue on Windows Devices
excerpt: This Article Describes Fixing Absent Application Issue on Windows Devices
keywords: Fix App Install Errors,Resolve Windows App Failures,Troubleshoot Missing Windows Updates,Address Windows Application Crashes,Stop Absent Software on PC,Tackle Devices Not Loading Apps,Eliminate Failed Windows Apps
thumbnail: https://thmb.techidaily.com/5b0ce9c020094ad31bdc87530c31e032109184ed98794f1ba27d0b681ad3c785.jpg
---

## Fixing Absent Application Issue on Windows Devices

 The error "this file does not have an app associated with it" mainly occurs when Windows can't find a compatible app for opening a specific file type. If you have the relevant app installed, it might not be set as default to open files of that format, or the app or file itself could be corrupted or damaged.

 The error can also occur when opening folders, mainly from Windows Search, and even when running apps and games. Here are some solutions you can apply to resolve this error regardless of where you get it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Ensure You Have an App Installed That Can Open Such Files

 Windows presents this error primarily when it fails to find the appropriate app to open files. Therefore, first, you should check whether you have the right app installed to open files in this particular format. There are several ways to check this, but here is one of the easiest:

1. Navigate to the file that is displaying this error when you open it.
2. Right-click the file and select**Properties** .
3. Navigate to the**General** tab and look for the file format next to**Type of file** .  
![Check the File Format in Properties Window of File in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/1-1.jpg)

 If it's a commonly used file format, such as PDF, JPEG, PNG, Docx, etc., for which you have the appropriate app installed, move on directly to heading #2\. However, if you see an unusual file format here—something you haven't seen before, make sure you have the appropriate app installed.

 To confirm this, right-click the file and navigate to**Open with > Choose another app** .

![Click on Choose Another App by Right-clicking on the File in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/2-1.jpg)

 If you have a relevant app installed, Windows will suggest you select it to open the file. If you don't see any app suggestions here, you probably don't have any apps installed capable of opening this file type.

![Windows Suggesting Some Apps to Open the Image File in PNG Format](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-suggesting-some-apps-to-open-the-image-file-in-png-format.jpg)

 If that's the case, simply go to any of your browsers, search for Windows apps that can run files in that format, and download them. After downloading the appropriate app, make it the default for opening this file type.

## 2\. Set the Default Application for the File Type

 The error message states that if the app is already installed, you need to create an association in the Default Programs. If you already had the compatible app installed or have just downloaded it, your next step should be to set it as default for files having that file type or format. Setting the compatible application as default may solve this problem right away.

 If you haven't changed a default app before, check out our article on[Windows 11 default apps](https://www.makeuseof.com/change-windows-11-default-apps/) . The article discusses various ways to change the default app, but we recommend using the second method, which is using the Settings app. That's because this method lets you search for specific file formats and choose a default app for them.

## 3\. Is the Default App Already Selected? Repair or Change It

 If the app you intend to set as default for a particular file format is already selected as a default application, but Windows still displays this error, the app has likely become corrupt, thus causing the error.

 To rule out this possibility, you should run the App troubleshooter, update the problematic app, reset its cache, or repair and reset it. You can find instructions for performing these steps in our[g](https://www.makeuseof.com/apps-arent-working-properly-windows/) uide for[fixing apps that don't work on Windows](https://www.makeuseof.com/apps-arent-working-properly-windows/) .

 Try these steps to see if they fix the problem. If the issue persists after that, we recommend you reinstall the app or select a different one as the default. If you don't have a different app installed on your device that supports these files, install one that does.

## 4\. Check for Specific File Issues

 If you're opening the file in a compatible app, it's working normally, and you've already set it as default, but you're still encountering the error, verify the file itself isn't corrupt. To confirm that, open any other file having the same file format and see if it returns the same error.

 If other files open without error, but the issue persists with one file, it's likely that the file is corrupt. If that's the case, follow our[guide on using Windows built-in tools to fix corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) . If that doesn't fix the problem, try using one of the[dedicated tools for repairing corrupted files](https://www.makeuseof.com/tag/best-tools-repair-corrupted-damaged-files-windows/) .

 Misconfiguring the Registry settings can result in undesirable outcomes and even render your device unbootable. Before you try the next fix, create a[backup of the Windows Registry so you can restore it](https://www.makeuseof.com/tag/backup-restore-windows-registry/) if something goes wrong.

## 5\. Use the Registry

 If none of the above fixes have been successful, try this registry tweak as a last resort:

1. Type**"regedit"** in Windows Search and open the**Registry Editor** .  
![Open Registry Editor App From Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/4-1.jpg)
2. Paste the path below into the address bar of Registry Editor.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080347/19272" target="_top" id="2080347">
  <img src="//a.impactradius-go.com/display-ad/19272-2080347" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080347/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Computer\HKEY_CLASSES_ROOT\lnkfile
3. Select the**Inkfile** key. Then, look in the right pane and see if there is a string value called**"IsShortcut** .**"**  
![Locate the IsShortcut String Value in the Inkfile Key of Registry Editor App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/5-1.jpg)
4. If it's not there, right-click in the blank area and go to**New > String Value** . Then rename it to**"IsShortcut** .**"**  

![Create and Rename the New String Value in Windows Registry Editor App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/6.jpg)
5. If the string value is already there, right-click on it and select**Delete** .  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118320/7443" target="_top" id="2118320">
  <img src="//a.impactradius-go.com/display-ad/7443-2118320" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118320/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Select Delete by Right-clicking on the String Value in Windows Registry Editor App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/7.jpg)
6. After that, follow step four to recreate it. Don't forget to rename it appropriately so you don't encounter any issues.

7. Restart your device once after that.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014859/22899" target="_top" id="2014859">
  <img src="//a.impactradius-go.com/display-ad/22899-2014859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014859/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Do You Encounter the Error When Opening Folders? Follow These Tips

 If you get the "This file does not have an app associated with it" error when opening folders, try these checks:

* Restart File Explorer (see[how to restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) for tips).
* If you're opening a folder by searching it in Windows Search or Quick Access, consider opening it directly from File Explorer.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972684/19272" target="_top" id="1972684">
  <img src="//a.impactradius-go.com/display-ad/19272-1972684" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972684/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Do You Encounter the Error When Opening Apps or Games? Try These Tips

 If you get the "This file does not have an app associated with it" error when opening an app or game, perform the following checks:

* If you're using a shortcut to open games, especially the ones installed in a gaming client, open them from the gaming client or the installation directory.
* In case the game launcher requires you to log in before playing any of the installed games, ensure you do so.
* If you're experiencing this error in a specific game or app, ensure its files haven't been corrupted.

## Easily Open Your Apps, Files, and Folders Again on Windows

 Seeing the error "this file does not have an app associated with it" when opening a file, folder, or app can be frustrating. If the file or folder isn't corrupt, the above fixes will help you identify and resolve the issue's root cause. If nothing works, you can reinstall the app or restore the older version of the file or folder from your backup.

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
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-seamless-transition-transferring-exclusive-youtube-content-to-gmail/"><u>[Updated] 2024 Approved Seamless Transition Transferring Exclusive YouTube Content to Gmail</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-live-viewers-choice-obs-or-shadowtoolkit/"><u>2024 Approved Live Viewers' Choice OBS or ShadowToolkit</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-complete-guide-to-affordable-online-passport-photo-services/"><u>2024 Approved The Complete Guide to Affordable Online Passport Photo Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplifying-explorer-tooltips-with-auto-update-notifications/"><u>Amplifying Explorer Tooltips with Auto-Update Notifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-eradicate-robloxs-access-denied-error-403/"><u>How to Eradicate Roblox's Access Denied (Error 403)</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-forgot-locked-iphone-6-password-learn-the-best-methods-to-unlock-by-drfone-ios/"><u>In 2024, Forgot Locked iPhone 6 Password? Learn the Best Methods To Unlock</u></a></li>
<li><a href="https://review-topics.techidaily.com/itel-a60s-unlock-tool-remove-android-phone-password-pin-pattern-and-fingerprint-by-drfone-android-unlock-android-unlock/"><u>Itel A60s Unlock Tool - Remove android phone password, PIN, Pattern and fingerprint</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/kid-friendly-tablets-rating-guide-what-the-experts-parents-say-on-zdnet/"><u>Kid-Friendly Tablets Rating Guide: What the Experts (Parents) Say on ZDNet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-your-presentations-physical-form-essential-strategies-for-prints-in-windows/"><u>Mastering Your Presentations' Physical Form: Essential Strategies for Prints in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-complexities-of-docker-with-wsl-2/"><u>Navigating the Complexities of Docker with WSL 2</u></a></li>
<li><a href="https://win-solutions.techidaily.com/phoenix-point-crash-dilemma-heres-how-you-can-get-back-on-track/"><u>Phoenix Point Crash Dilemma? Here's How You Can Get Back on Track</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-messages-from-infinix-smart-7-hd-by-fonelab-android-recover-messages/"><u>Possible solutions to restore deleted messages from Infinix Smart 7 HD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precise-methods-to-address-windows-activation-failure-code-0x803f700f/"><u>Precise Methods to Address Windows Activation Failure Code 0X803F700f</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-instant-addition-problems-with-windows-onedrive-a-compreenhensive-guide/"><u>Resolving Instant Addition Problems with Windows OneDrive - A Compreenhensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-successful-installation-in-the-windows-store/"><u>Securing Successful Installation in the Windows Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-printer-linkup/"><u>Streamlining Windows Printer Linkup</u></a></li>
<li><a href="https://video-capture.techidaily.com/the-verdict-on-screen-recording-does-obs-surpass-fraps/"><u>The Verdict on Screen Recording Does OBS Surpass Fraps?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-windows-into-macos-style-ui-these-5-tips-to-try/"><u>Transforming Windows Into MacOS Style UI: These 5 Tips to Try</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-pubg-loads-failure-for-in-game-structures/"><u>Troubleshooting PUBG Loads Failure for In-Game Structures</u></a></li>
</ul></div>

