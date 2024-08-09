---
title: "Boost Productivity: Setting Up Automatic Deletions in Win11"
date: 2024-08-08T10:56:34.299Z
updated: 2024-08-09T10:56:34.299Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Boost Productivity: Setting Up Automatic Deletions in Win11"
excerpt: "This Article Describes Boost Productivity: Setting Up Automatic Deletions in Win11"
keywords: Win11 Auto-Delete Boost,Efficiency Win11 Cleanup,Productivity Win11 Routine,Quick Task Deletion Win11,Automated Win11 Organization,Speed Win11 Settings,Win11 Optimize Deletes
thumbnail: https://thmb.techidaily.com/250f73dd4b9929867a630f9b8f32aa45e2b59d5cab96411e7883925b75cba9fc.jpg
---

## Boost Productivity: Setting Up Automatic Deletions in Win11

 For many, a cluttered desktop and downloads folder is just a way of life—no matter how hard you try, they somehow always ends up disorganized. Need to do a bit of digital spring-cleaning? Fortunately, there are lots of ways you can keep your Windows 10 computer decluttered.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

<!-- affiliate ads begin -->
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->
## 1\. Auto-Delete Old Files or Folders Using Storage Settings

 The Settings menu lets you do and manage a lot of stuff on your Windows computer. From updates to tweaking the Windows appearance—you can do almost everything. It's no surprise then that you can also use it for setting up an auto-deletion setting on your Windows. Here's how:

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![storage settings on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-settings-on-windows.jpg)

1. Go to **Settings > System > Storage**.
2. Toggle on the **Storage Sense** feature.
3. Then, click **Configure Storage Sense or run it now**.
4. Under **Temporary Files**, set up your desired time frames fore deleting files in the recycle bin and files in your Downloads folder.  
![storage sense in windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-sense-in-windows-settings.jpg)

 Not all files in the Downloads folder will be deleted after the set time; just those that haven't been opened. This means if you download a file and want to open it later, it will still be deleted after the set time. If you turn this setting on, you should move anything out of the Downloads folder that you intend to keep.

 If you want, you can always turn off the setting by simply disabling the **Storage Sense** button later on.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Deleted Old Files or Folders With the Command Prompt

 Like most things on Windows, you can use the Command Prompt here as well. A replacement for the easy pin-and-point graphical user interface, the Command Prompt works with simple text-based commands to help you perform different admin functions and fix various troubleshooting issues on Windows.

 Here's how you can use it to fix your storage issues via the _ForFiles_ command on Windows:

1. Head to the **Start menu** search bar, type in 'cmd', and run the CMD as an administrator.
2. Now, to delete the files that you haven't modified in 30 days, type in the following command and hit **Enter**:  
`ForFiles /p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 The "C:\\path\\to\\folder" and /d -30 here refer to the folder path from where you want to delete files and the specific time for which you'd like to delete your file. Replace them with the settings that suit you.

![command prompt on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/command-prompt-on-windows.jpg)

 Your files will be removed as quickly as soon as you hit the above commands.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Use Task Scheduler on Windows

 Task Scheduler is a simple Windows tool that lets you easily automate your repetitive Windows tasks. Just set up the task, and the app will handle whatever you have asked it to do. When it comes to auto-deleting your files or folders, the _ForFiles_ command is what you will need to help you delete your older files or folders.

 Here's how you can automate the deletion:

1. Head to the **Start menu** search bar, type in 'task scheduler', and select the best match.
2. Right-click on **Task Scheduler Library** and select **New Folder**.
3. Put in any name and click on **OK**.
4. Right-click on the recently created folder and select the **Create Task** option.  
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
![task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/task-scheduler.jpg)
5. In the **Name** box, enter a name for the task.
6. Now, in the **General** tab, under the **Security options** section, select the **Run whether the user is logged on or not** option.
7. Make sure the **Do not store password** checkbox is unselected.
8. Click on the **Triggers** tab and select the **New** button.
9. Select **On a schedule** option using the **Begin the task** setting.  
![new trigger section on task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-trigger-section-on-windows.jpg)
10. Under the **Settings** section, set up the timings of the tasks you'd like to run. Finally, click on **OK**.

 Now, head to the **Actions** tab and click on the **New** button. From the **Actions** drop-down menu, select the **Start a program** option.

 In the Program/script box, type in the following command:

`ForFiles`

![new action tab on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-tab-on-windows.jpg)

 Similarly, in the **Add arguments** box, type in the following command:

`/p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 In the above command, tweak the _"C:\\path\\to\\folder_" to the path of the folder where your files are and replace "_/d -30_" with actual number you'd like pick. So, your command will become something like this:

`/p "%userprofile%\Users\[Your Username]\Downloads" /s /d -30 /c "cmd /c del /q @file"`

 Click on **OK**. Finally, from the **Settings** tab, check the following checkboxes and then click on **OK**:

* Allow task to be run on demand.
* Run the task as soon as possible after a scheduled start is missed.
* If the task fails, restart every.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->
![new action setting on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-setting-on-windows.jpg)

 That's it—finalize the changes by clicking **OK** once again, and you will be done in no time. From here forward, your files will be automatically deleted within the specified time. Of course, if you later change your mind you can always reverse this setting by simply deleting the new folder your created in first step (which in our case, will be **New Folder 1**).

## Auto-Deleting Old Files or Folders on a Windows Computer

 Keeping unnecessary files on your computer is seldom useful. They eat up memory space, hamper your PC's performance, and clog the file organization. Setting up auto-delete instructions, with whichever method you prefer, lets you rid your PC of this extra baggage.

 However, we'd add that auto-removing files or folders from your PC is just one part of cleaning up your Windows. There are many other important hacks such as removing unused apps, terminating pointless background processes, and tweaking settings to whatever is most relevant to your situation. So, make sure you follow all the best principles for running your Windows as smoothly as possible.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-docs.techidaily.com/024-approved-rising-viewers-rising-prosperity-the-youtube-route/"><u>[New] 2024 Approved  Rising Viewers, Rising Prosperity  The Youtube Route</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-innovating-your-viewing-experience-android-and-vr-videos/"><u>[New] Innovating Your Viewing Experience  Android & VR Videos</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-navigating-picture-in-picture-settings-for-iphone-and-ipad/"><u>[New] Navigating Picture-in-Picture Settings for iPhone & iPad</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/he-dos-and-donts-of-daily-vlogging/"><u>[New] The Dos and Don'ts of Daily Vlogging</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-monetizing-youtube-shorts-crucial-requirements-and-potential-income/"><u>[Updated] In 2024, Monetizing Youtube Shorts  Crucial Requirements and Potential Income</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-search-of-success-pivotal-youtube-gatherings-after-vidcon/"><u>[Updated] In Search of Success  Pivotal YouTube Gatherings (After VidCon)</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-masterful-moment-captures-with-expert-photo-frames-online/"><u>[Updated] Masterful Moment Captures with Expert Photo Frames Online</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-unseen-youtube-videos-the-meaning-of-unlisted-status/"><u>[Updated] Unseen YouTube Videos  The Meaning of 'Unlisted' Status</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/10-top-picks-for-total-data-cleanse-on-ios-devices/"><u>10 Top-Picks for Total Data Cleanse on iOS Devices</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-efficiently-documenting-your-fb-chats-and-meets/"><u>2024 Approved  Efficiently Documenting Your FB Chats & Meets</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-teaming-up-for-duet-video-on-tiktok/"><u>2024 Approved  Teaming Up for Duet Video on TikTok</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-window-into-evolution-noteworthy-windows-11-file-enhancements/"><u>A Window Into Evolution: Noteworthy Windows 11 File Enhancements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-11-reactivating-deactivated-voice-command/"><u>Addressing Windows 11: Reactivating Deactivated Voice Command</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-the-variance-in-procedures-for-local-and-remote-windows-reinstallations/"><u>Analyzing the Variance in Procedures for Local and Remote Windows Reinstallations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-the-hurdles-of-xbox-game-pass-error-code-0-essential-tips-for-windows-11-users/"><u>Avoiding the Hurdles of Xbox Game Pass Error Code 0: Essential Tips for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-11-visuality-with-app-sizing/"><u>Boosting Windows 11 Visuality with App Sizing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-the-new-os-build-a-focused-and-effective-windows-11-boot-drive-in-three-ways/"><u>Conquer the New OS – Build a Focused and Effective Windows 11 Boot Drive in Three Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-fatal-javascript-issue-with-ease-on-win-11-discord/"><u>Conquering Fatal Javascript Issue with Ease on Win 11 Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correct-camera-omission-from-windows-dm-display/"><u>Correct Camera Omission From Windows' DM Display</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-setup-ensure-your-pcs-microphone-and-webcam/"><u>Efficient Setup: Ensure Your PC's Microphone & Webcam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-webbrowsers-for-lighter-system-resource-use-on-os-x-windows-chromeos/"><u>Efficient Webbrowsers for Lighter System Resource Use on OS X, Windows, ChromeOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-scripts-the-winexe-transformation-tutorial/"><u>Elevate Your Scripts: The WinEXE Transformation Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tools-for-shaping-windows-esd-files-into-iso/"><u>Essential Tools for Shaping Windows' ESD Files Into ISO</u></a></li>
<li><a href="https://some-techniques.techidaily.com/experiencing-dji-inspire-2-in-full-scale-for-2024/"><u>Experiencing DJI Inspire 2 in Full Scale for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-fixing-windows-error-code-0xc00000f-instantly/"><u>Guidelines to Fixing Windows Error Code 0Xc00000f Instantly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guides-to-resolve-windows-11-search-tool-errors/"><u>Guides to Resolve Windows 11 Search Tool Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-adjust-colored-display-in-windows-based-devices/"><u>How to Adjust Colored Display in Windows-Based Devices</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-detect-and-remove-spyware-on-infinix-hot-30i-drfone-by-drfone-virtual-android/"><u>How to Detect and Remove Spyware on Infinix Hot 30i? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-highlight-the-mouse-cursor-in-windows-11-and-11/"><u>How to Highlight the Mouse Cursor in Windows 11 & 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-app-on-nubia-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to Recover Deleted Photos from Android Gallery App on Nubia</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-sharefake-location-on-whatsapp-for-apple-iphone-12-drfone-by-drfone-virtual-ios/"><u>How to Share/Fake Location on WhatsApp for Apple iPhone 12 | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-poco-c50-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos From Poco C50 to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-use-an-additional-monitor-without-gui-chipset/"><u>How to Use an Additional Monitor Without GUI Chipset</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-use-phone-clone-to-migrate-your-oppo-reno-8t-data-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Use Phone Clone to Migrate Your Oppo Reno 8T Data? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-itel-a60s-by-drfone-android/"><u>In 2024, 10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Itel A60s</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-enhancing-youtube-content-via-finalcut-pro-techniques/"><u>In 2024, Enhancing YouTube Content via FinalCut Pro Techniques</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-realme-11-5g-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Realme 11 5G? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-music-from-vivo-y100a-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Music from Vivo Y100A to iPod | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-oppo-reno-11-5g-drfone-by-drfone-android/"><u>In 2024, How To Use Allshare Cast To Turn On Screen Mirroring On Oppo Reno 11 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-mobile-mastery-youtube-video-thumbnails-made-easy/"><u>In 2024, Mobile Mastery  YouTube Video Thumbnails Made Easy</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-nikons-d500-takes-on-4k-clarity-and-quality/"><u>In 2024, Nikon's D500 Takes on 4K Clarity and Quality</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-sculpting-soundtracks-for-animation-using-movie-maker-tools/"><u>In 2024, Sculpting Soundtracks for Animation Using Movie Maker Tools</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-depth-analysis-the-essence-of-the-google-podcast-application-for-2024/"><u>In-Depth Analysis  The Essence of the Google Podcast Application for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-restoring-functionality-fix-media-on-win11/"><u>Mastering the Art of Restoring Functionality: Fix Media on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-the-stuck-windows-enter-function/"><u>Mending the Stuck Windows 'Enter' Function</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-options-picking-right-nvidia-driver-type-for-you/"><u>Navigating Options, Picking Right Nvidia Driver Type For You</u></a></li>
<li><a href="https://win-blog.techidaily.com/overcome-pc-stability-hurdles-fix-tormented-souls-gaming-applications/"><u>Overcome PC Stability Hurdles: Fix Tormented Souls Gaming Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-virtualbox-usb-connection-issue-on-windows-devices/"><u>Overcoming VirtualBox USB Connection Issue on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-xbox-mic-malfunctions-in-windows-os/"><u>Overcoming Xbox Mic Malfunctions in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-windows-methods-to-identify-system-gadgets/"><u>Proven Windows Methods to Identify System Gadgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-command-gain-admin-status/"><u>Regain Command - Gain Admin Status</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rejoining-fall-guys-fixing-connectivity-issues-on-pc/"><u>Rejoining Fall Guys: Fixing Connectivity Issues on PC</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-adjusting-your-amazon-kindle-paperwhites-display-clock/"><u>Step-by-Step Guide: Adjusting Your Amazon Kindle Paperwhite's Display Clock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/storeroom-in-mp60-speed-still-scarce/"><u>Storeroom in MP60, Speed Still Scarce</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-guide-to-managing-win11-applications-via-winget/"><u>The Complete Guide to Managing Win11 Applications via Winget</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-plating-palette-techniques-for-food-cinematography-for-2024/"><u>The Plating Palette  Techniques for Food Cinematography for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-checklist-longer-pins-in-windows-11-and-11/"><u>The Ultimate Checklist: Longer PINs in Windows 11 and 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-intel-unison-for-windows-11-calling/"><u>The Ultimate Guide to Intel Unison for Windows 11 Calling</u></a></li>
<li><a href="https://extra-resources.techidaily.com/top-picks-for-your-next-shot-in-4k-reflective-tech/"><u>Top Picks for Your Next Shot in 4K Reflective Tech</u></a></li>
<li><a href="https://techidaily.com/top-ways-to-unlock-iphone-8-screen-lock-by-drfone-ios-unlock-ios-unlock/"><u>Top ways to unlock iPhone 8 screen lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-the-mechanics-of-windows-11s-compatibility-tool/"><u>Uncovering the Mechanics of Windows 11’S Compatibility Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-microsofts-ai-assistive-functions/"><u>Understanding Microsoft's AI Assistive Functions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11-display-options-with-these-10-tips/"><u>Unlocking Windows 11 Display Options with These 10 Tips</u></a></li>
</ul></div>
