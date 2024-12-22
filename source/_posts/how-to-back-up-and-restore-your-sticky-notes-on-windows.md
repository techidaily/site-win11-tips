---
title: How to Back Up and Restore Your Sticky Notes on Windows
date: 2024-12-17T09:42:03.527Z
updated: 2024-12-21T17:09:59.203Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Back Up and Restore Your Sticky Notes on Windows
excerpt: This Article Describes How to Back Up and Restore Your Sticky Notes on Windows
keywords: Sticky Notebook Backup,Win Note Restoration,Save Windows Notes,Data Protect Notes,Recover Sticky Points,Notebook Filebackup,Sync Windows Stickies
thumbnail: https://thmb.techidaily.com/dab2ef0415897bd2885169e6ea9bd44d0885cdc86df8bf517d1ad2126bf71ef1.jpg
---

## How to Back Up and Restore Your Sticky Notes on Windows

 Sticky Notes on Windows turn your computer into a virtual board for posting notes, reminders, lists, and pretty much anything that you need to remember at a glance. So it makes sense that you wouldn't want to lose them, whether you're switching computers or a problem with your PC has caused you to lose your data.

 In this guide, we're going to show you a couple of ways to back up your sticky notes on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/e4Nt2xXXtmE?si=CtKwFry4b0AJXnaN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/RBN1gYY5hUs?si=p89CMiMzeJzU0wGu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To restore the notes on another computer, open the Sticky Notes app (make sure the PC is connected to the internet) and sign in with your Microsoft account. Once signed in, the app will load all the notes you previously synced. Furthermore, every time you finish writing a Sticky Note or edit one, the app will automatically back it up to the cloud.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hXIq2G0nShk?si=5Z4Fwv7ZB6oKWsdd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Manually Back Up and Restore Your Sticky Notes

 If you don't want to use a Microsoft account or want to have an extra backup of your sticky notes, then you can manually back them up yourself. While it's not as easy as just syncing them to the cloud, it can definitely come in handy when you don't have internet access and want to restore the notes.

 To manually back up your sticky notes, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.  
![opening tne Local State folder in Windows Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/opening-local-state-folder-in-windows-run.jpg)
3. In the **LocalState** folder, copy the **plum.sqlite** file.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HtM7d4dpN1I?si=2vN_xgVGD4eYGORu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![the plum database for Sticky Notes on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/the-plum-database-for-sticky-notes-on-windows.jpg)
4. Paste the **plum.sqlite** file to an external drive, such as a flash drive or external SDD, or upload it to cloud storage, such as OneDrive or Google Drive, for safekeeping.

 To manually restore your sticky notes on another Windows computer, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.
3. Go to where you saved the backup of your sticky notes (the **plum.sqlite** file) and copy it.
4. In the **LocalState** folder, delete the current **plum.sqlite** file.
5. Paste the backup **plum.sqlite** file in the **LocalState** folder.

 Now when you open Sticky Notes, it will load the **plum.sqlite** file, and you should see all your notes appear in the app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nl0Z0eth1u4?si=0eecOBNfc--51AJO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Never Lose Your Sticky Notes Again

 Losing your sticky notes means you could lose potentially important information. So it makes sense to always have a copy stored somewhere in case you need to restore them. We recommend using your Microsoft account to back up the notes, considering it's convenient to both sync and restore them later on, but it's also a good idea to know that there's a manual option available.

 In this guide, we're going to show you a couple of ways to back up your sticky notes on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-helps.techidaily.com/new-best-ways-to-get-high-quality-version-of-pictures-for-free-for-2024/"><u>[New] Best Ways To Get High Quality Version Of Pictures For Free for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-digital-domain-your-playground-for-1000-titles-for-2024/"><u>[New] Digital Domain Your Playground for 1,000 Titles for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-gaiety-media-download-review/"><u>[New] In 2024, Gaiety Media Download Review</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-crafting-collabs-that-attract-and-retain-viewers/"><u>[Updated] 2024 Approved Crafting Collabs that Attract and Retain Viewers</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-demystifying-the-purpose-what-is-a-blue-image-on-facebook-for-2024/"><u>[Updated] Demystifying the Purpose What Is a Blue Image on Facebook for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-become-a-snapchat-pro-securing-and-sharing-screen-videos/"><u>2024 Approved Become a Snapchat Pro Securing & Sharing Screen Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cut-down-time-and-clutter-with-multi-folder-creation-techniques-in-windows-1011/"><u>Cut Down Time and Clutter with Multi-Folder Creation Techniques in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/directing-power-the-art-of-appbrowser-control-in-winos/"><u>Directing Power: The Art of App/Browser Control in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-web-browsing-security-with-aguard-technology-on-windows-11/"><u>Elevate Your Web Browsing Security with Aguard Technology on Windows 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unlocking-creative-potential-turning-graphics-into-stickers-on-chat-apps/"><u>In 2024, Unlocking Creative Potential Turning Graphics Into Stickers on Chat Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-sidestep-these-8-common-errors/"><u>Mastering Windows 11: Sidestep These 8 Common Errors</u></a></li>
<li><a href="https://win11.techidaily.com/the-photographers-shield-preventing-windows-camera-problems/"><u>The Photographer’s Shield: Preventing Windows Camera Problems</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ling-hidden-details-in-asmr-recordings-for-2024/"><u>Unveiling Hidden Details in ASMR Recordings for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    