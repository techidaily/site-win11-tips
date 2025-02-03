---
title: Backup & Recovery for Windows Note Apps
date: 2025-01-28T14:20:39.475Z
updated: 2025-02-01T04:31:25.628Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Backup & Recovery for Windows Note Apps
excerpt: This Article Describes Backup & Recovery for Windows Note Apps
keywords: Windows Backup Services,Data Restore Procedures,Notepad Save Features,File Protection Windows,System Recovery Solutions,Data Safety Windows Apps,OS Data Recovery Tools
thumbnail: https://thmb.techidaily.com/d6c8d5c25a5b3ae8109b2957c3f404be919cf133b41c5b6f6638a7ed5bc1223b.jpg
---

## Backup & Recovery for Windows Note Apps

 Sticky Notes on Windows turn your computer into a virtual board for posting notes, reminders, lists, and pretty much anything that you need to remember at a glance. So it makes sense that you wouldn't want to lose them, whether you're switching computers or a problem with your PC has caused you to lose your data.

 In this guide, we're going to show you a couple of ways to back up your sticky notes on Windows.

## How to Back Up and Restore YourSticky Notes Using a Microsoft Account

 The easiest way to back up your sticky notes is to use a Microsoft account, which stores the notes on the cloud. If you don't have one already, then you can [learn how to create a Microsoft account](https://www.makeuseof.com/your-microsoft-account-things-windows-user-should-know/) or skip to the next section to learn how to back up the notes manually.

 If you've been using Windows with your Microsoft account all along, the notes could be synced to the cloud already. If you're not, you can [switch from a local account to a Microsoft account](https://www.makeuseof.com/windows-switch-local-account-to-microsoft-account/) for that to happen.

 To be sure if Sticky Notes is syncing your notes already or, if you're using a local account, give the app the ability to do so, follow the steps below:

1. Connect your Windows PC to the internet and open Sticky Notes.
2. Click on **Settings** (the gear icon) in the top right corner.
3. If you've already signed in, you'll see the details of your Microsoft account at the top with a **Sign out** link. If that's the case, you can skip to step #7 to sync the notes. If you're not signed in, click **Sign in**.
4. In the **Use one of these accounts** section, select the Microsoft account you want to sign in with. If there are no accounts there, select either **Microsoft account** or **Work or school account** in the **Use a different account** section.
5. Click **Continue** and follow the instructions to complete the sign-in process.
6. Once you're signed in, click on **Settings** again in the top right corner.
7. Scroll down and click **Sync now**.  
![the Sync Now button in Sticky Notes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/sync-now-button-in-sticky-notes.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To restore the notes on another computer, open the Sticky Notes app (make sure the PC is connected to the internet) and sign in with your Microsoft account. Once signed in, the app will load all the notes you previously synced. Furthermore, every time you finish writing a Sticky Note or edit one, the app will automatically back it up to the cloud.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XVsiIO7hWOc?si=UvWnqxaI_yHwEr74" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Manually Back Up and Restore Your Sticky Notes

 If you don't want to use a Microsoft account or want to have an extra backup of your sticky notes, then you can manually back them up yourself. While it's not as easy as just syncing them to the cloud, it can definitely come in handy when you don't have internet access and want to restore the notes.

 To manually back up your sticky notes, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.  
![opening tne Local State folder in Windows Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/opening-local-state-folder-in-windows-run.jpg)
3. In the **LocalState** folder, copy the **plum.sqlite** file.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![the plum database for Sticky Notes on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/the-plum-database-for-sticky-notes-on-windows.jpg)
4. Paste the **plum.sqlite** file to an external drive, such as a flash drive or external SDD, or upload it to cloud storage, such as OneDrive or Google Drive, for safekeeping.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To manually restore your sticky notes on another Windows computer, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.
3. Go to where you saved the backup of your sticky notes (the **plum.sqlite** file) and copy it.
4. In the **LocalState** folder, delete the current **plum.sqlite** file.
5. Paste the backup **plum.sqlite** file in the **LocalState** folder.

 Now when you open Sticky Notes, it will load the **plum.sqlite** file, and you should see all your notes appear in the app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n-66V-LRK3Y?si=fNeB2pXCePeQli6E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Never Lose Your Sticky Notes Again

 Losing your sticky notes means you could lose potentially important information. So it makes sense to always have a copy stored somewhere in case you need to restore them. We recommend using your Microsoft account to back up the notes, considering it's convenient to both sync and restore them later on, but it's also a good idea to know that there's a manual option available.

 In this guide, we're going to show you a couple of ways to back up your sticky notes on Windows.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vimeo-videos.techidaily.com/new-mastering-free-and-paid-tools-for-vimeo-video-downloads-for-2024/"><u>[New] Mastering Free & Paid Tools for Vimeo Video Downloads for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-2023s-best-screen-recorder-discover-with-camstudio/"><u>[Updated] In 2024, 2023'S Best Screen Recorder? Discover with CamStudio</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-direct-youtube-stream-of-google-meet-step-by-step-instructions/"><u>[Updated] In 2024, Direct YouTube Stream of Google Meet - Step-by-Step Instructions</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-streamlining-sound-speeds-in-spotify-without-compromise/"><u>2024 Approved Streamlining Sound Speeds in Spotify Without Compromise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-steam-access-failure-on-win11-platform/"><u>Correcting Steam Access Failure on Win11 Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dusk-drawings-with-digital-darkness-in-paint/"><u>Dusk Drawings with Digital Darkness in Paint</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/explore-the-new-world-of-computing-golden-socketed-cpu-on-gigabytes-misty-designed-iceberg-intel-z790-motherboard/"><u>Explore the New World of Computing: Golden Socketed CPU on Gigabyte's Misty-Designed Iceberg Intel Z790 Motherboard</u></a></li>
<li><a href="https://games-able.techidaily.com/fixing-big-picture-crashes-with-steam/"><u>Fixing Big Picture Crashes with Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-device-errors-in-new-windows-11-os/"><u>Overcoming Device Errors in New Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-forbidden-page-access-in-windows-os/"><u>Resolving Forbidden Page Access in Windows OS</u></a></li>
<li><a href="https://article-files.techidaily.com/telegrams-wonders-for-marketers-beginning-their-journey/"><u>Telegram’s Wonders for Marketers Beginning Their Journey</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-windows-update-hurdles-quick-solutions/"><u>Troubleshoot: Windows Update Hurdles - Quick Solutions!</u></a></li>
<li><a href="https://article-tips.techidaily.com/what-are-the-best-sites-to-download-tamil-ringtones-and-how-to-cut-a-son/"><u>What Are the Best Sites to Download Tamil Ringtones & How to Cut a Son</u></a></li>
</ul></div>

