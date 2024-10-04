---
title: Ensuring Safe Copy/Restore of Notebooks
date: 2024-10-01T20:45:40.845Z
updated: 2024-10-04T00:54:17.726Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Ensuring Safe Copy/Restore of Notebooks
excerpt: This Article Describes Ensuring Safe Copy/Restore of Notebooks
keywords: Notebook Safety Restore,Secure Data Backup Laptop,Safe Data Recovery Book,Protecting Device Copies,Security Notebook Copy,Reliable Data Backup Books,Preserve Book Data Safely
thumbnail: https://thmb.techidaily.com/255abe49d787e06c0ed6c6f504e1d68fdfd70d2804f8cd2447f9f7cced35cd22.jpg
---

## Ensuring Safe Copy/Restore of Notebooks

 Sticky Notes on Windows turn your computer into a virtual board for posting notes, reminders, lists, and pretty much anything that you need to remember at a glance. So it makes sense that you wouldn't want to lose them, whether you're switching computers or a problem with your PC has caused you to lose your data.

 In this guide, we're going to show you a couple of ways to back up your sticky notes on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

 To restore the notes on another computer, open the Sticky Notes app (make sure the PC is connected to the internet) and sign in with your Microsoft account. Once signed in, the app will load all the notes you previously synced. Furthermore, every time you finish writing a Sticky Note or edit one, the app will automatically back it up to the cloud.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148636/16836" target="_top" id="2148636">
  <img src="//a.impactradius-go.com/display-ad/16836-2148636" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148636/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Manually Back Up and Restore Your Sticky Notes

 If you don't want to use a Microsoft account or want to have an extra backup of your sticky notes, then you can manually back them up yourself. While it's not as easy as just syncing them to the cloud, it can definitely come in handy when you don't have internet access and want to restore the notes.

 To manually back up your sticky notes, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.  
![opening tne Local State folder in Windows Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/opening-local-state-folder-in-windows-run.jpg)
3. In the **LocalState** folder, copy the **plum.sqlite** file.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036496/19272" target="_top" id="2036496">
  <img src="//a.impactradius-go.com/display-ad/19272-2036496" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036496/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![the plum database for Sticky Notes on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/the-plum-database-for-sticky-notes-on-windows.jpg)
4. Paste the **plum.sqlite** file to an external drive, such as a flash drive or external SDD, or upload it to cloud storage, such as OneDrive or Google Drive, for safekeeping.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135369/19272" target="_top" id="2135369">
  <img src="//a.impactradius-go.com/display-ad/19272-2135369" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135369/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To manually restore your sticky notes on another Windows computer, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.
3. Go to where you saved the backup of your sticky notes (the **plum.sqlite** file) and copy it.
4. In the **LocalState** folder, delete the current **plum.sqlite** file.
5. Paste the backup **plum.sqlite** file in the **LocalState** folder.

 Now when you open Sticky Notes, it will load the **plum.sqlite** file, and you should see all your notes appear in the app.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134242/18498" target="_top" id="2134242">
  <img src="//a.impactradius-go.com/display-ad/18498-2134242" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134242/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Never Lose Your Sticky Notes Again

 Losing your sticky notes means you could lose potentially important information. So it makes sense to always have a copy stored somewhere in case you need to restore them. We recommend using your Microsoft account to back up the notes, considering it's convenient to both sync and restore them later on, but it's also a good idea to know that there's a manual option available.

 In this guide, we're going to show you a couple of ways to back up your sticky notes on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-lessons.techidaily.com/new-apex-newcomer-catalogue-panzoid-edition/"><u>[New] Apex Newcomer Catalogue Panzoid Edition</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-premier-alternative-video-recording-software/"><u>[New] Premier Alternative Video Recording Software</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-discover-the-magic-behind-effective-youtube-short-videos-for-2024/"><u>[Updated] Discover the Magic Behind Effective YouTube Short Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-critical-considerations-when-buying-a-windows-laptop/"><u>Guide to Critical Considerations When Buying a WIndows Laptop</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-lava-yuva-3-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Lava Yuva 3 Phones with/without a PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-overcome-obstructed-calendarmail-access-on-w11/"><u>How to Overcome Obstructed Calendar/Mail Access on W11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-forgotten-pin-of-your-infinix-note-30-vip-by-drfone-android/"><u>How to Remove Forgotten PIN Of Your Infinix Note 30 VIP</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-image-innovation-for-windows-and-mac-photo-to-cartoon-software/"><u>In 2024, Image Innovation for Windows & Mac Photo-to-Cartoon Software</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-iphone-is-disabled-here-is-the-way-to-unlock-disabled-iphone-12-pro-max-by-drfone-ios/"><u>In 2024, iPhone Is Disabled? Here Is The Way To Unlock Disabled iPhone 12 Pro Max</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-set-your-preferred-job-location-on-linkedin-app-of-your-vivo-v29-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Set Your Preferred Job Location on LinkedIn App of your Vivo V29 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-tasks-essential-cmd-command-knowledge/"><u>Mastering Windows Tasks: Essential CMD Command Knowledge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-error-0x800704b3-on-your-win1011-machine/"><u>Overcoming Error 0X800704B3 on Your Win10/11 Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-dormant-recyclebin-icon-in-windows-11/"><u>Reviving Dormant Recyclebin Icon in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snippet-savvy-crafting-custom-keybinds-for-speed-and-precision-in-win11/"><u>Snippet Savvy: Crafting Custom Keybinds for Speed & Precision in Win11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/soundscape-symphony-crafting-concert-videos-with-these-15-tutorials/"><u>Soundscape Symphony Crafting Concert Videos with These 15 Tutorials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-pc-hurdles-steadying-cpu-load-in-rm-toolkit/"><u>Troubleshoot PC Hurdles: Steadying CPU Load in RM Toolkit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-elusive-results-in-your-windows-1011-search/"><u>Uncovering Elusive Results in Your Windows 10/11 Search</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    