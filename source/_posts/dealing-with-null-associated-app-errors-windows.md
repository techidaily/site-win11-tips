---
title: Dealing with Null Associated App Errors (Windows)
date: 2024-11-05T10:53:21.287Z
updated: 2024-11-07T02:31:16.634Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Dealing with Null Associated App Errors (Windows)
excerpt: This Article Describes Dealing with Null Associated App Errors (Windows)
keywords: NullError Windows Fix,NullAppWindows Troubleshoot,ZeroValue App Windows,Null Values Window Error,Null Fix Win App,Null Handling Windows,Null Errors Resolve Win
thumbnail: https://thmb.techidaily.com/4bb09ddf21259f8aa35372dd3bddaab5a52e4c2f70a7e62b027db40747b04fa4.jpeg
---

## Dealing with Null Associated App Errors (Windows)

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043617/7443" target="_top" id="2043617">
  <img src="//a.impactradius-go.com/display-ad/7443-2043617" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043617/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2145009/26400" target="_top" id="2145009">
  <img src="//a.impactradius-go.com/display-ad/26400-2145009" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2145009/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Computer\HKEY_CLASSES_ROOT\lnkfile
3. Select the**Inkfile** key. Then, look in the right pane and see if there is a string value called**"IsShortcut** .**"**  
![Locate the IsShortcut String Value in the Inkfile Key of Registry Editor App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/5-1.jpg)
4. If it's not there, right-click in the blank area and go to**New > String Value** . Then rename it to**"IsShortcut** .**"**  
![Create and Rename the New String Value in Windows Registry Editor App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/6.jpg)
5. If the string value is already there, right-click on it and select**Delete** .  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2112007/7443" target="_top" id="2112007">
  <img src="//a.impactradius-go.com/display-ad/7443-2112007" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2112007/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Select Delete by Right-clicking on the String Value in Windows Registry Editor App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/7.jpg)
6. After that, follow step four to recreate it. Don't forget to rename it appropriately so you don't encounter any issues.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934254/19272" target="_top" id="1934254">
  <img src="//a.impactradius-go.com/display-ad/19272-1934254" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934254/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Restart your device once after that.

## Do You Encounter the Error When Opening Folders? Follow These Tips

 If you get the "This file does not have an app associated with it" error when opening folders, try these checks:

* Restart File Explorer (see[how to restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) for tips).
* If you're opening a folder by searching it in Windows Search or Quick Access, consider opening it directly from File Explorer.

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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-beauty-blogging-101-starting-up-as-an-aesthetic-vlogger/"><u>[New] 2024 Approved Beauty Blogging 101 Starting Up as an Aesthetic Vlogger</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-the-secret-behind-the-blue-status-update-sticker-for-2024/"><u>[New] The Secret Behind the Blue Status Update Sticker for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-nikon-d500-review-breaking-boundaries-in-4k/"><u>[Updated] Nikon D500 Review Breaking Boundaries in 4K</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-oneplus-ace-2v-is-off-drfone-by-drfone-virtual-android/"><u>Can Life360 Track You When Your OnePlus Ace 2V is off? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-top-3-techniques-to-fasten-windows-11-bootup-time/"><u>Explore Top 3 Techniques to Fasten Windows 11 Bootup Time</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/full-guide-to-bypass-xiaomi-redmi-note-12-4g-frp-by-drfone-android/"><u>Full Guide to Bypass Xiaomi Redmi Note 12 4G FRP</u></a></li>
<li><a href="https://driver-install.techidaily.com/gtx-1650-graphics-update-download-nvidia-drivers/"><u>GTX 1650 Graphics Update - Download Nvidia Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-change-lockout-duration-after-failed-logon-attempts-in-windows-10-and-11/"><u>How to Change Lockout Duration After Failed Logon Attempts in Windows 10 and 11</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-the-art-of-smooth-video-transitioning/"><u>In 2024, The Art of Smooth Video Transitioning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instalwin11nonet-preparing-your-system/"><u>InstalWin11NoNet: Preparing Your System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-invalid-reparse-buffer-tag-error-with-onedrive/"><u>Mitigating Invalid Reparse Buffer Tag Error with OneDrive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-glitched-netflix-on-windows-pc/"><u>Resetting Glitched Netflix on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rise-to-the-top-essential-ms-store-winners-2023/"><u>Rise to the Top: Essential MS Store Winners, 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-adjusting-net-settings-in-win11/"><u>Steps for Adjusting Net Settings in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-overcome-windows-task-sequence-error-0x8007000f/"><u>Steps to Overcome Windows Task Sequence Error 0X8007000f</u></a></li>
<li><a href="https://win-able.techidaily.com/1726029590268-wav/"><u>WAV形式音声ファイルの音量設定手順と、使いやすい無料アプリ・ウェブサービス</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/1719581230819-what-language-is-spoken-in-croatia/"><u>What Language Is Spoken In Croatia?</u></a></li>
</ul></div>

