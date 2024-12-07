---
title: "Handling Error: No Qt Platform Engine Available for Startup"
date: 2024-12-02T16:09:28.574Z
updated: 2024-12-06T23:37:45.525Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Handling Error: No Qt Platform Engine Available for Startup"
excerpt: "This Article Describes Handling Error: No Qt Platform Engine Available for Startup"
keywords: Qt Engine Not Found,QT Platform Engine Error,Engine Initialization Failure,Qt Startup Issue,Missing Qt Plugin,No Qt Platform Available,Qt Engine Unavailable at Launch
thumbnail: https://thmb.techidaily.com/f244a4b607ff1304250df827a08b69767edd00f8e4433a759d16a32700c891a6.jpg
---

## Handling Error: No Qt Platform Engine Available for Startup

 Have you recently run into the “Application failed to start because no Qt platform plugin could be initialized” error? QT is a cross-platform app that is used to generate graphical user interfaces. Even if QT support for Windows platforms is extensive, your system might display the error message when you try to open OneDrive, OBS Studio, Python, or even video games.

 While this isn’t one of the common errors on Windows, you can still fix it using the tips below.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Change the QT Files Location

 Sometimes, a simple trick such as changing the QT files location is enough to get rid of the error. Here’s how you can do it:

1. Launch File Explorer and open**This PC** .
2. Using the**Search** field, search for**pyqt5\_tools** .
3. When Windows finishes the search, right-click the**pyqt5\_tools** and head to**Open folder location** .
4. Head to**PyQt5 > Qt > bin** . Copy the**platforms** folder.  
![Fix qt error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/platforms-folder-1.jpg)
5. Make a new search for**site-packages** and open the folder.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GFHH14XlFCk?si=2HcjQbDx5eG0ZQAt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. There, paste the**platforms** folder.
7. Windows will warn you there’s already a folder with the same name. Click**Replace the files in the destination** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/omWG4u39lmE?si=yk1AEo_gzDpGjYbl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## 5\. Reinstall the Troublesome App

 As the error message hints, reinstalling the app might fix the problem. When reinstalling the app, make sure you get it from its official website, to avoid any future problems.

 If you're having issues getting rid of the app, check out[how to fix Windows when it won't allow you to uninstall a program](https://www.makeuseof.com/windows-cant-uninstall-program-fix/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/grbt-5VvbuI?si=qnoirlmljslpqcQj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/OdlXe5RELW0?si=Iz1H1QnLQVw-Eu3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-web.techidaily.com/ritical-game-analysis-from-top-creators/"><u>[New] Critical Game Analysis From Top Creators</u></a></li>
<li><a href="https://youtube-web.techidaily.com/mpowering-audiences-the-playlist-sharing-approach-for-2024/"><u>[New] Empowering Audiences The Playlist Sharing Approach for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-excellent-applications-reshaping-the-art-of-virtual-broadcasting-for-2024/"><u>[New] Excellent Applications Reshaping the Art of Virtual Broadcasting for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-producing-dynamic-content-for-discord-channels/"><u>[Updated] 2024 Approved Producing Dynamic Content for Discord Channels</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/windows-11c/"><u>簡單三法：在Windows 11系統中擴大C檔案的存取空間</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/could-dells-breakthrough-concept-luna-assembled-with-building-blocks-revolutionize-the-tech-world-zdnet/"><u>Could Dell’s Breakthrough Concept Luna, Assembled with Building Blocks, Revolutionize the Tech World? | ZDNET</u></a></li>
<li><a href="https://media-tips.techidaily.com/guide-watching-the-2016-rio-olympics-on-your-apple-tv/"><u>Guide: Watching the 2016 Rio Olympics on Your Apple TV</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-specified-user-does-not-have-a-valid-profile-app-error-in-windows-11-and-11/"><u>How to Fix the Specified User Does Not Have a Valid Profile App Error in Windows 11 & 11</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/learn-catalan-online-in-just-10-minutes-a-day/"><u>Learn Catalan Online In Just 10 Minutes A Day</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/mastering-smooth-playback-on-instagram-videos/"><u>Mastering Smooth Playback on Instagram Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-your-windowed-yuzu-experience/"><u>Maximize Your Windowed Yuzu Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-unresponsive-sound-settings-on-windows/"><u>Reviving Unresponsive Sound Settings on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tutorial-enhancing-windows-11-sounds-with-dolby-atmos/"><u>Tutorial: Enhancing Windows 11 Sounds with Dolby Atmos</u></a></li>
</ul></div>

