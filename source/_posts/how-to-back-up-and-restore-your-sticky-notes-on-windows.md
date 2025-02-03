---
title: How to Back Up and Restore Your Sticky Notes on Windows
date: 2025-01-26T22:24:18.330Z
updated: 2025-01-31T22:56:02.639Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/jpdGEJJwMLY?si=eKgXOPpNeYvYKcel" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/slm2NjVPNtk?si=9ow6g1ucmf0TnT4T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To restore the notes on another computer, open the Sticky Notes app (make sure the PC is connected to the internet) and sign in with your Microsoft account. Once signed in, the app will load all the notes you previously synced. Furthermore, every time you finish writing a Sticky Note or edit one, the app will automatically back it up to the cloud.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MTb4xHzeQEk?si=9Sqq-gFWnHc8x3_P" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Manually Back Up and Restore Your Sticky Notes

 If you don't want to use a Microsoft account or want to have an extra backup of your sticky notes, then you can manually back them up yourself. While it's not as easy as just syncing them to the cloud, it can definitely come in handy when you don't have internet access and want to restore the notes.

 To manually back up your sticky notes, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.  
![opening tne Local State folder in Windows Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/opening-local-state-folder-in-windows-run.jpg)
3. In the **LocalState** folder, copy the **plum.sqlite** file.  

![the plum database for Sticky Notes on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/the-plum-database-for-sticky-notes-on-windows.jpg)
4. Paste the **plum.sqlite** file to an external drive, such as a flash drive or external SDD, or upload it to cloud storage, such as OneDrive or Google Drive, for safekeeping.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l4R7_qNIQvY?si=2zJOPfEcm6_3udzn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To manually restore your sticky notes on another Windows computer, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.
3. Go to where you saved the backup of your sticky notes (the **plum.sqlite** file) and copy it.
4. In the **LocalState** folder, delete the current **plum.sqlite** file.
5. Paste the backup **plum.sqlite** file in the **LocalState** folder.

 Now when you open Sticky Notes, it will load the **plum.sqlite** file, and you should see all your notes appear in the app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZeYbTVeaXg0?si=rwLL1DbBoX26BGjm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://extra-hints.techidaily.com/2024-approved-8-best-film-cameras-for-beginners-from-35mm-to-point-and-shoot/"><u>2024 Approved 8 Best Film Cameras for Beginners (From 35Mm to Point-and-Shoot)</u></a></li>
<li><a href="https://howto.techidaily.com/4-solutions-to-fix-unfortunately-your-app-has-stopped-error-on-samsung-galaxy-a25-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Solutions to Fix Unfortunately Your App Has Stopped Error on Samsung Galaxy A25 5G | Dr.fone</u></a></li>
<li><a href="https://win-hacks.techidaily.com/como-preservar-el-arranque-de-tu-pc-con-windows-11-mediante-metodos-gratuitos-y-faciles/"><u>Cómo Preservar El Arranque De Tu PC Con Windows 11 Mediante Métodos Gratuitos Y Fáciles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ease-of-use-tactics-for-stuck-windows-update/"><u>Ease-of-Use Tactics for Stuck Windows Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-the-chrome-error-code-aw-snap-in-windows/"><u>Eliminating the Chrome Error Code “Aw, Snap!” In Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-windows-11-error-code-0x0000011b/"><u>Fixing the Windows 11 Error: Code 0X0000011B</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-started-fast-free-easycap-drivers-downloads-here/"><u>Get Started Fast: Free EasyCap Drivers Downloads Here</u></a></li>
<li><a href="https://apple-account.techidaily.com/guide-on-how-to-remove-apple-id-from-iphone-xs-max-by-drfone-ios/"><u>Guide on How To Remove Apple ID From iPhone XS Max</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-can-tecno-pop-7-promirror-share-to-pc-drfone-by-drfone-android/"><u>How Can Tecno Pop 7 ProMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-core-principles-of-e-storytelling/"><u>In 2024, Core Principles of E-Storytelling</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-simulate-gps-movement-in-ar-games-on-sony-xperia-5-v-drfone-by-drfone-virtual-android/"><u>In 2024, How to Simulate GPS Movement in AR games On Sony Xperia 5 V? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-photo-editing-essentials-cut-out-unwanted-borders-smoothly/"><u>In 2024, Photo Editing Essentials Cut Out Unwanted Borders Smoothly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keep-it-constant-wallpapers-in-windows-11/"><u>Keep It Constant: Wallpapers in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-your-windows-zone-visible-or-not/"><u>Securing Your Windows Zone, Visible or Not</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-pcs-appearance-with-personalized-wallpapers/"><u>Transform Your PC's Appearance with Personalized Wallpapers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-invalid-user-profile-issue-in-windows-os/"><u>Troubleshooting Invalid User Profile Issue in Windows OS</u></a></li>
</ul></div>

