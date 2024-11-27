---
title: Safeguarding Your Note Applications on PCs
date: 2024-11-25T17:27:11.108Z
updated: 2024-11-27T16:02:38.915Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Safeguarding Your Note Applications on PCs
excerpt: This Article Describes Safeguarding Your Note Applications on PCs
keywords: Protecting Notes,Secure Note Storage,PC Note Security,Note Privacy PC,Safe Note Access,PC Notes Shield,Data Protection Notecare
thumbnail: https://thmb.techidaily.com/f9e691ab1179ca5da97e6ab8b312a61013e41cba8e3a02b301a39e9364b303a9.jpg
---

## Safeguarding Your Note Applications on PCs

 Sticky Notes on Windows turn your computer into a virtual board for posting notes, reminders, lists, and pretty much anything that you need to remember at a glance. So it makes sense that you wouldn't want to lose them, whether you're switching computers or a problem with your PC has caused you to lose your data.

 In this guide, we're going to show you a couple of ways to back up your sticky notes on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YB7Ou4-iKVM?si=7Fq8iUwI8voccMLx&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To restore the notes on another computer, open the Sticky Notes app (make sure the PC is connected to the internet) and sign in with your Microsoft account. Once signed in, the app will load all the notes you previously synced. Furthermore, every time you finish writing a Sticky Note or edit one, the app will automatically back it up to the cloud.

## How to Manually Back Up and Restore Your Sticky Notes

 If you don't want to use a Microsoft account or want to have an extra backup of your sticky notes, then you can manually back them up yourself. While it's not as easy as just syncing them to the cloud, it can definitely come in handy when you don't have internet access and want to restore the notes.

 To manually back up your sticky notes, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.  
![opening tne Local State folder in Windows Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/opening-local-state-folder-in-windows-run.jpg)
3. In the **LocalState** folder, copy the **plum.sqlite** file.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![the plum database for Sticky Notes on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/the-plum-database-for-sticky-notes-on-windows.jpg)
4. Paste the **plum.sqlite** file to an external drive, such as a flash drive or external SDD, or upload it to cloud storage, such as OneDrive or Google Drive, for safekeeping.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OZQJUTr44rA?si=ADA0nD1VnXjR_sH0&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To manually restore your sticky notes on another Windows computer, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.
3. Go to where you saved the backup of your sticky notes (the **plum.sqlite** file) and copy it.
4. In the **LocalState** folder, delete the current **plum.sqlite** file.
5. Paste the backup **plum.sqlite** file in the **LocalState** folder.

 Now when you open Sticky Notes, it will load the **plum.sqlite** file, and you should see all your notes appear in the app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eu4vwlZcMvM?si=4vEczfVU4BUUFP-t&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Never Lose Your Sticky Notes Again

 Losing your sticky notes means you could lose potentially important information. So it makes sense to always have a copy stored somewhere in case you need to restore them. We recommend using your Microsoft account to back up the notes, considering it's convenient to both sync and restore them later on, but it's also a good idea to know that there's a manual option available.

 In this guide, we're going to show you a couple of ways to back up your sticky notes on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-enhancing-playback-speed-in-tiktok-videos/"><u>[New] 2024 Approved Enhancing Playback Speed in TikTok Videos</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unlock-the-best-top-9-gamers-hubs/"><u>[New] Unlock the Best Top 9 Gamers' Hubs</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-dominate-search-results-powerful-youtube-seo-techniques-exposed-for-2024/"><u>[Updated] Dominate Search Results Powerful YouTube SEO Techniques Exposed for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-easy-obs-youtube-live-streaming-guide/"><u>[Updated] In 2024, Easy OBS YouTube Live Streaming Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-pc-manager-in-windows-11/"><u>Configuring PC Manager in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cure-frozen-shift-key-woes-quickly/"><u>Cure Frozen Shift Key Woes Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-performance-through-optimal-ram-use/"><u>Enhancing Windows Performance Through Optimal RAM Use</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-the-update-error-dealing-with-windows-1ves-0x80240034-troubleshooting-guide/"><u>How to Overcome the Update Error: Dealing with Windows 1Ve's 0X80240034 Troubleshooting Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reactivate-windows-dormant-discord-interface-widget/"><u>How to Reactivate Windows' Dormant Discord Interface Widget</u></a></li>
<li><a href="https://buynow-info.techidaily.com/immersive-world-of-tamriel-reimagined-for-the-switch-in-the-elder-scrolls-v-skyrim/"><u>Immersive World of Tamriel Reimagined for the Switch in The Elder Scrolls V: Skyrim</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-unveiling-video-sharing-secrets-examining-igtv-and-youtube-in-depth/"><u>In 2024, Unveiling Video Sharing Secrets Examining IGTV & YouTube in Depth</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/reset-itunes-backup-password-of-apple-iphone-12-prevention-and-solution-drfone-by-drfone-ios/"><u>Reset iTunes Backup Password Of Apple iPhone 12 Prevention & Solution | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-curtail-autonomous-cmd-display/"><u>Strategies to Curtail Autonomous CMD Display</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformative-taskbar-upgrades-for-enhanced-user-experience-in-windows-11/"><u>Transformative Taskbar Upgrades for Enhanced User Experience in Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/why-is-my-samsung-galaxy-f54-5g-offline-troubleshooting-guide-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Is My Samsung Galaxy F54 5G Offline? Troubleshooting Guide | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    