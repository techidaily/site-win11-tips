---
title: How to Back Up and Restore Your Sticky Notes on Windows
date: 2025-01-05T23:49:01.046Z
updated: 2025-01-12T22:19:00.948Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/TJCye_oCTTw?si=6bVyBphcSgSFdyuq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To restore the notes on another computer, open the Sticky Notes app (make sure the PC is connected to the internet) and sign in with your Microsoft account. Once signed in, the app will load all the notes you previously synced. Furthermore, every time you finish writing a Sticky Note or edit one, the app will automatically back it up to the cloud.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XS1nQCe95LU?si=A2dhdFkSAI61_nKA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Manually Back Up and Restore Your Sticky Notes

 If you don't want to use a Microsoft account or want to have an extra backup of your sticky notes, then you can manually back them up yourself. While it's not as easy as just syncing them to the cloud, it can definitely come in handy when you don't have internet access and want to restore the notes.

 To manually back up your sticky notes, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.  
![opening tne Local State folder in Windows Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/opening-local-state-folder-in-windows-run.jpg)
3. In the **LocalState** folder, copy the **plum.sqlite** file.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rdNq2Sp031s?si=3FcJa3dQLraUDHKv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-data.techidaily.com/024-approved-pre-production-meets-post-production-premiere-and-youtube/"><u>[New] 2024 Approved Pre-Production Meets Post-Production Premiere and YouTube</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-riders-eye-view-unveiling-23s-finest-action-camera-hats-for-bike-enthusiasts/"><u>[New] The Rider's Eye View – Unveiling '23’S Finest Action Camera Hats for Bike Enthusiasts</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-cutting-down-complexity-the-simplified-guide-to-youtube-4k-submissions/"><u>2024 Approved Cutting Down Complexity The Simplified Guide to Youtube 4K Submissions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-for-the-runtime-brokers-abnormal-cpu-usage-spikes-on-windows-10/"><u>Easy Fixes for the Runtime Broker's Abnormal CPU Usage Spikes on Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/echoes-of-the-past-utilizing-windows-7-product-key-for-windows-11/"><u>Echoes of the Past: Utilizing Windows 7 Product Key for Windows 11</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/escape-high-prices-of-official-revamps-craft-custom-versions-via-modding-techniques/"><u>Escape High Prices of Official Revamps - Craft Custom Versions via Modding Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixes-to-overcome-remote-connection-errors-on-windows/"><u>Fixes to Overcome Remote Connection Errors on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/getting-to-grips-with-windows-11s-audio-settings-quickly/"><u>Getting to Grips with Windows 11'S Audio Settings Quickly</u></a></li>
<li><a href="https://some-tips.techidaily.com/harnessing-insights-from-paris-olympic-data-to-enhance-energy-efficiency-for-future-sporting-events-zdnet-exclusive/"><u>Harnessing Insights From Paris Olympic Data to Enhance Energy Efficiency for Future Sporting Events - ZDNet Exclusive</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-pause-life360-location-sharing-for-honor-magic-6-pro-drfone-by-drfone-virtual-android/"><u>How To Pause Life360 Location Sharing For Honor Magic 6 Pro | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-changeadd-location-filters-on-snapchat-for-your-itel-p55-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Add Location Filters on Snapchat For your Itel P55 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-shadows-add-stealthy-menu-in-win11/"><u>Navigating the Shadows: Add Stealthy Menu in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-hurdles-of-windows-11s-search-functionality/"><u>Overcoming the Hurdles of Windows 11'S Search Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sharpen-performance-the-most-unnecessary-windows-applications/"><u>Sharpen Performance: The Most Unnecessary Windows Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-chrome-blackout-on-a-pc/"><u>Solving Chrome Blackout on a PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-hidden-benefits-in-maintaining-your-win-11-notification-signals/"><u>The Hidden Benefits in Maintaining Your Win 11 Notification Signals</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/top-7-iosandroid-apps-for-mobile-friendly-youtube-streaming/"><u>Top 7 iOS/Android Apps for Mobile-Friendly YouTube Streaming</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/unearthing-inshots-video-magic-for-editors-for-2024/"><u>Unearthing InShot’s Video Magic for Editors for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-dormant-pane-panes-ultimate-guide-to-win11/"><u>Unlocking Dormant Pane Panes: Ultimate Guide to Win11</u></a></li>
</ul></div>

