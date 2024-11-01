---
title: Fixing Failed Application Start Due to Qt Platform Absence
date: 2024-10-26T17:50:06.195Z
updated: 2024-11-01T17:42:28.657Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Failed Application Start Due to Qt Platform Absence
excerpt: This Article Describes Fixing Failed Application Start Due to Qt Platform Absence
keywords: App Start Error,QT Platform Failure,Qt Absence Issue,Fix App Startup,Resolve Qt Error,Application Launching,Overcome Qt Missing
thumbnail: https://thmb.techidaily.com/6a3b42ee0f491feaaae6060437bee4c1fe86f210fd6ba7270c68a358652e000e.jpg
---

## Fixing Failed Application Start Due to Qt Platform Absence

 Have you recently run into the “Application failed to start because no Qt platform plugin could be initialized” error? QT is a cross-platform app that is used to generate graphical user interfaces. Even if QT support for Windows platforms is extensive, your system might display the error message when you try to open OneDrive, OBS Studio, Python, or even video games.

 While this isn’t one of the common errors on Windows, you can still fix it using the tips below.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Change the QT Files Location

 Sometimes, a simple trick such as changing the QT files location is enough to get rid of the error. Here’s how you can do it:

1. Launch File Explorer and open**This PC** .
2. Using the**Search** field, search for**pyqt5\_tools** .
3. When Windows finishes the search, right-click the**pyqt5\_tools** and head to**Open folder location** .
4. Head to**PyQt5 > Qt > bin** . Copy the**platforms** folder.  
![Fix qt error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/platforms-folder-1.jpg)
5. Make a new search for**site-packages** and open the folder.
6. There, paste the**platforms** folder.
7. Windows will warn you there’s already a folder with the same name. Click**Replace the files in the destination** .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006914/19272" target="_top" id="2006914">
  <img src="//a.impactradius-go.com/display-ad/19272-2006914" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006914/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Run an SFC Scan

 There’s a chance Windows display the “Application failed because no QT platform plugin could be initialized” error due to corrupt system files. Fortunately, Windows has a built-in tool to help you fix the problem.

 In the Start menu search bar, search for**command prompt** and select**Run as administrator** . Then, run the**sfc /scannow** command line. Windows will scan and automatically replace any corrupted system file.

![sfc-scan-1-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/sfc-scan-1-1.jpg)

 If the System File Checker didn’t fix the problem, there are[more built-in tools to repair corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) .

## 3\. Perform a Clean Boot

 One of the installed third-party apps might be the reason why you get the “Application failed because no QT platform plugin could be initialized” error. To test it,[perform a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) , which will force it to boot with a minimal list of programs and drivers.

 If Windows stops displaying the error, it means something you've installed on your PC is causing the problem. Take a look at your installed apps, and remove any software that might be causing the problem. If you're unsure as to what might be doing it, slowly re-enable apps through the clean boot until the issue reappears.

## 4\. Update the Malfunctioning App

 An outdated version of the app you're trying to use might be the reason for the QT error. In this case, simply updating the app should solve the issue.

 If you’ve downloaded the app from Microsoft Store, launch it and head to**Library** . There, you’ll see a list of available updates. You can update the apps individually, or click**Get updates** to update them all.

![Update Microsoft Store apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mcirosoft-store-1.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528689/16446" target="_top" id="1528689">
  <img src="//a.impactradius-go.com/display-ad/16446-1528689" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528689/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Reinstall the Troublesome App

 As the error message hints, reinstalling the app might fix the problem. When reinstalling the app, make sure you get it from its official website, to avoid any future problems.

 If you're having issues getting rid of the app, check out[how to fix Windows when it won't allow you to uninstall a program](https://www.makeuseof.com/windows-cant-uninstall-program-fix/) .

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134223/18498" target="_top" id="2134223">
  <img src="//a.impactradius-go.com/display-ad/18498-2134223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134223/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Uninstall Any Recent Windows Updates

 Sometimes, Windows display the “Application failed because no QT platform plugin could be initialized” error after a system update. In this case, you can load a restore point to undo the change and get rid of the error.

 But if there’s no restore point available, you can manually uninstall Windows updates.

1. Launch Windows Settings by pressing**Win + I** .
2. From the left pane, click**Windows Update > Update History** .
3. Head to**Related Settings** and click**Uninstall updates** .
4. Right-click the latest update and select**Uninstall** .

![Uninstall recent Windows updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-updates-1.jpg)

<!-- affiliate ads begin -->
<span id="1531882">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1531882.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1531882">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1531882.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1531882%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1531882/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Rid of the QT Error on Windows

 Hopefully, one or more of the above solutions helped you fix the “Application failed to start because no Qt platform plugin could be initialized” error.

 Sometimes, it’s difficult to figure out the exact cause of a Windows error, and reinstalling the app every time might not be the most efficient solution. To speed up the troubleshooting process, you should use one of the many Windows repair tools.

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
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-smart-editing-tricks-how-to-embed-dates-in-photo-albums/"><u>[New] In 2024, Smart Editing Tricks How to Embed Dates in Photo Albums</u></a></li>
<li><a href="https://win-wonderful.techidaily.com/44cm44oh44oq44kk44k55l255so5lit44cn44ko44op44o844gr5aplusplus44gx44gm44cb5lplusu5q2j5pa55rov44ks5lia44gk5lia44gk5lib5aplusn44gr6kej6kqs/"><u>「デバイス使用中」エラーに対して、修正方法を一つ一つ丁寧に解説</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-expressive-film-conclusions-available-on-the-free-shelf/"><u>2024 Approved Expressive Film Conclusions Available on the Free Shelf</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-quality-matters-the-advantages-and-disadvantages-of-different-fps/"><u>2024 Approved Quality Matters The Advantages & Disadvantages of Different FPS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detailed-analysis-of-windows-11s-automated-data-management-system/"><u>Detailed Analysis of Windows 11'S Automated Data Management System</u></a></li>
<li><a href="https://facebook.techidaily.com/facebooks-next-destination-understanding-the-top-6-shifts-in-its-metaverse-vision/"><u>Facebook's Next Destination: Understanding the Top 6 Shifts in Its Metaverse Vision</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/failed-to-play-hevc-files-on-xiaomi-14-ultra-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Failed to play HEVC files on Xiaomi 14 Ultra</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/livestream-titans-clash-facebook-youtube-and-twitspaces/"><u>Livestream Titans Clash FACEbook, YOUTube, and TWITSpaces</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-taskbar-icon-size-in-win11-a-guide/"><u>Maximizing Taskbar Icon Size in Win11: A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/method-for-limiting-user-permissions-in-windows-10-filesystem/"><u>Method for Limiting User Permissions in Windows 10 Filesystem</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-connection-difficulties-with-bungies-destiny-2-gaming-platform/"><u>Overcoming Connection Difficulties with Bungie's Destiny 2 Gaming Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-settings-application-one-user-many-options-in-windows-1011/"><u>Tailored Settings Application: One User, Many Options in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-digital-landscape-with-windows-11-features/"><u>Tailoring Your Digital Landscape with Windows 11 Features</u></a></li>
<li><a href="https://activate-lock.techidaily.com/the-10-best-tools-to-bypass-icloud-activation-lock-from-apple-iphone-7-plus-you-should-try-out-by-drfone-ios/"><u>The 10 Best Tools to Bypass iCloud Activation Lock From Apple iPhone 7 Plus You Should Try Out</u></a></li>
</ul></div>

