---
title: "Convenient Start: Unveiling Sticky Notes at System Launch"
date: 2024-08-23T07:03:07.058Z
updated: 2024-08-24T07:03:07.058Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Convenient Start: Unveiling Sticky Notes at System Launch"
excerpt: "This Article Describes Convenient Start: Unveiling Sticky Notes at System Launch"
keywords: Convenient Start,Sticky Notes Launch,System Launch Tips,Note-Taking Systems,Product Introduction,Easy Access Tools,Launch Day Essentials
thumbnail: https://thmb.techidaily.com/641461279d3ad9059bf4fdcda2c6b1609c3c8007cc281a812d3b0157adab9f77.jpg
---

## Convenient Start: Unveiling Sticky Notes at System Launch

 Are you tired of opening Sticky Notes every time you turn on your computer? What if it could open automatically each time Windows starts?

 Well, there's good news for you: Sticky Notes can launch at startup in Windows. This article illustrates how to set up and use Sticky Notes at startup.

## 1\. Keep Sticky Notes Open at Shutdown

 When you're done working with Sticky Notes, make sure not to close the window. Instead, leave it open as you shut down your computer. This will ensure that when you turn on your computer, Sticky Notes opens automatically.

 Although the solution is simple, it may not work, or you may find it difficult to remember to keep it open when you turn off your PC. In that case, there are other alternatives; add Sticky Notes to the startup folder or use Task Scheduler.

## 2\. Add Sticky Notes to the Startup Folder

 If you don't want to keep Sticky Notes open at shutdown, you can add it to the startup folder. The Startup folder is a special directory in File Explorer. It stores applications that launch automatically when Windows starts.

 To add Sticky Notes to the Startup folder, follow these steps.

1. Press **Win + R** and type **shell:startup** in the Run dialog.
2. Click **OK** or press Enter. This opens a folder containing all the applications that launch at startup.
3. Press **Windows** to open the Start menu, then click **All apps**. Now scroll down and find **Sticky Notes** in the list.
4. Drag and drop **Sticky Notes** into the Startup folder.

 After performing these steps, close File Explorer and restart your computer. Sticky Notes should now open at startup.

## 3\. Use the Task Scheduler

 Task Scheduler is another way to open Sticky Notes at startup. This Windows feature schedules and automates tasks at specific times or conditions.

 To add Sticky Notes using this tool, follow these steps:

1. [Open Task Scheduler](https://www.makeuseof.com/windows-11-open-task-scheduler/).
2. Click **Create Basic Task** from the **Actions** panel on the right. This opens a wizard that guides you through the setup.  
![Create Basic Task in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-in-task-scheduler.jpg)
3. In the first step, give your task a name and click **Next**.  
![Startup Sticky Notes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-sticky-notes.jpg)
4. Now select **When I log on** as the trigger and click **Next** at the bottom.  
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Create Basic Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-wizard.jpg)
5. Choose **Start a program** in the Action window and click **Next**.  
![Start a program in Action tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-action-tab.jpg)
6. In the **Program/script** field, type the path below:  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->
C:\Windows\System32\cmd.exe
7. In the Add arguments (optional) field, copy and paste the following command:  
/c start shell:appsfolder\Microsoft.MicrosoftStickyNotes_8wekyb3d8bbwe!App  
![Start a Program in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-task-scheduler.jpg)
8. Click **Next** and review all the settings.
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
9. Now click **Finish** to save your work.  
![Finish Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/finish-task-wizard.jpg)

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The Task Scheduler will now run Sticky Notes each time you log in. This way, Sticky Notes launches automatically at startup.

<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Tweak the Registry Editor

 If you're comfortable editing the Windows registry, you can tweak it to open Sticky Notes at startup. This method requires knowledge of how the Registry Editor works and caution when editing it. If done incorrectly, it can cause serious system errors. It's best to [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing anything.

 To open Sticky Notes at startup using the Registry Editor, follow these steps:

1. [Open Windows Search](https://www.makeuseof.com/windows-search-use-guide/).
2. Type **regedit** in the search bar and click on the Registry Editor option.
3. If the UAC dialog appears, click **Yes** to grant access.
4. In the Registry Editor window, navigate to the following path:  
Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\PenWorkspace\Notes
5. Double-click the **LaunchOnNextUserSession** key on the right.  
![Tweak Registry Editor to Open Sticky Notes at Startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tweak-registry-editor-to-open-sticky-notes-at-startup.jpg)
6. Change the Value data from 0 to **1** in the Edit DWORD (32-bit) Value window and click **OK**.  
 If you can't find the **LaunchOnNextUserSession** key, right-click on the **Notes** folder and select **New > DWORD (32-bit) Value**. Name the newly created key “LaunchOnNextUserSession” and assign it the Value data of **1**.
7. Close the Registry Editor and restart your computer to save the changes. Sticky Notes should now open at startup.

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Windows Now Starts With Sticky Notes Open

 This article outlines several ways to open Sticky Notes at startup in Windows. If you want an easier solution, leave Sticky Notes open when you shut down your computer; it will launch automatically when Windows starts. If not, add Sticky Notes to the startup folder. If you want more control over when Sticky Notes launches, use Task Scheduler or tweak the Registry Editor.

 Well, there's good news for you: Sticky Notes can launch at startup in Windows. This article illustrates how to set up and use Sticky Notes at startup.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-help.techidaily.com/new-harmony-and-rhythm-discover-the-best-15-youtube-educational-videos/"><u>[New] Harmony & Rhythm  Discover the Best 15 YouTube Educational Videos</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-facebook-cover-video-widthheight-guide/"><u>[New] In 2024, Facebook Cover Video Width/Height Guide</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-mastering-facebooks-live-features-for-optimal-performance/"><u>[New] In 2024, Mastering Facebook's Live Features for Optimal Performance</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-quick-fixes-to-keep-your-photos-app-fixed-on-win-11/"><u>[New] Quick Fixes to Keep Your Photos App Fixed on Win 11</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-the-comprehensive-blueprint-for-vimeo-video-logging/"><u>[New] The Comprehensive Blueprint for Vimeo Video Logging</u></a></li>
<li><a href="https://youtube-data.techidaily.com/he-essential-guide-to-youtube-trailer-editing-with-filmora/"><u>[New] The Essential Guide to YouTube Trailer Editing with Filmora</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-a-journey-through-time-best-history-youtubes-for-scholars-and-enthusiasts/"><u>[Updated] 2024 Approved  A Journey Through Time  Best History YouTubes for Scholars & Enthusiasts</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-inventive-story-naming-mastering-over-120-ways-for-snapchat-exclusivity/"><u>[Updated] 2024 Approved  Inventive Story Naming  Mastering Over 120 Ways for Snapchat Exclusivity</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-top-9-fb-scraper-apps-for-films/"><u>[Updated] 2024 Approved  Top 9 FB Scraper Apps for Films</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-free-visual-magic-for-your-videos-online/"><u>[Updated] Free Visual Magic for Your Videos Online</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-go-from-camera-to-cellphone-vt-adjustments-in-fcpx/"><u>[Updated] In 2024, Go From Camera to Cellphone  VT Adjustments in FCPX</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-the-filmmakers-guide-producing-engaging-youtube-splits/"><u>[Updated] The Filmmaker's Guide  Producing Engaging YouTube Splits</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-3-ways-to-record-lectures-on-mac/"><u>2024 Approved  3 Ways to Record Lectures on Mac</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-best-phones-for-video-stability-optimal-image-stabilization-included/"><u>2024 Approved  Best Phones for Video Stability  Optimal Image Stabilization Included</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-poco-x5-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On Poco X5</u></a></li>
<li><a href="https://howto.techidaily.com/cellular-network-not-available-for-voice-calls-on-infinix-hot-30-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Cellular Network Not Available for Voice Calls On Infinix Hot 30 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-corrupted-file-error-0x80070570-anxiety-in-windows-11/"><u>Conquering Corrupted File (Error 0X80070570) Anxiety in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/converting-oculus-rift-into-a-windows-vr-device/"><u>Converting Oculus Rift Into a Windows VR Device</u></a></li>
<li><a href="https://extra-information.techidaily.com/cutting-edge-podcasting-garageband-edition/"><u>Cutting Edge Podcasting  GarageBand Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delving-into-disabling-gpgpu-task-prioritization-windows-wise/"><u>Delving Into Disabling GPGPU Task Prioritization Windows-Wise</u></a></li>
<li><a href="https://activate-lock.techidaily.com/easy-tutorial-for-activating-icloud-on-iphone-8-plus-safe-and-legal-by-drfone-ios/"><u>Easy Tutorial for Activating iCloud on iPhone 8 Plus Safe and Legal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-computer-experience-top-10-must-know-powertoy-features/"><u>Elevate Your Computer Experience: Top 10 Must-Know PowerToy Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-barriers-fix-steam-remote-play-woes/"><u>Eliminating Barriers: Fix Steam Remote Play Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-restrictions-save-permissions-fix-windows-way/"><u>Eliminating Restrictions: Save Permissions Fix Window's Way</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-spotify-link-errors-on-windows-systems/"><u>Eliminating Spotify Link Errors on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-user-experience-with-win-1011s-fn-keys/"><u>Enhance Your User Experience with Win 10/11'S Fn Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-new-features-in-windows-11s-yearly-update-extension/"><u>Exploring New Features in Windows 11'S Yearly Update Extension</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixes-for-endless-stuck-in-bios-during-windows-boot-up/"><u>Fixes for Endless Stuck in BIOS During Windows Boot-Up</u></a></li>
<li><a href="https://some-techniques.techidaily.com/from-shipping-secrets-to-surprises-unveiling-new-strategies-for-2024/"><u>From Shipping Secrets to Surprises  Unveiling New Strategies for 2024</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-the-latest-magic-mouse-drivers-for-seamless-windows-experience/"><u>Get the Latest Magic Mouse Drivers for Seamless Windows Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-microsoft-store-error-code-0x80073cf3-in-windows-11-and-11/"><u>How to Fix the Microsoft Store Error Code 0X80073CF3 in Windows 11 & 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-is-greyed-out-from-apple-iphone-15-plus-how-to-bypass-by-drfone-ios/"><u>In 2024, Apple ID is Greyed Out From Apple iPhone 15 Plus How to Bypass?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-check-distance-and-radius-on-google-maps-for-your-oneplus-11r-drfone-by-drfone-virtual-android/"><u>In 2024, How to Check Distance and Radius on Google Maps For your OnePlus 11R | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-oppo-reno-10-5g-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Oppo Reno 10 5G Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-process-of-screen-sharing-xiaomi-redmi-13c-to-pc-detailed-steps-drfone-by-drfone-android/"><u>In 2024, Process of Screen Sharing Xiaomi Redmi 13C to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlocking-the-power-of-smart-lock-a-beginners-guide-for-samsung-galaxy-a24-users-by-drfone-android/"><u>In 2024, Unlocking the Power of Smart Lock A Beginners Guide for Samsung Galaxy A24 Users</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-official-epson-perfection-v6n-driver-free-tutorial/"><u>Install Official Epson Perfection V6n Driver - Free Tutorial</u></a></li>
<li><a href="https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-vivo-y100i-drfone-by-drfone-virtual-android/"><u>Is pgsharp legal when you are playing pokemon On Vivo Y100i? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-your-android-for-windows-11-webcam-functionality/"><u>Leveraging Your Android for Windows 11 Webcam Functionality</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/mastering-gadgets-and-components-with-toms-essential-hardware-wisdom/"><u>Mastering Gadgets and Components with Tom's Essential Hardware Wisdom</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-task-management-through-ifttt-linkup/"><u>Mastering Task Management Through IFTTT Linkup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/method-for-altering-reset-counter-after-failed-logins/"><u>Method for Altering Reset Counter After Failed Logins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-pioneers-new-assistance-pathways-without-cortana/"><u>Microsoft Pioneers New Assistance Pathways without Cortana</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modify-the-default-view-for-win11s-task-manager/"><u>Modify the Default View for Win11's Task Manager</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-go-viral-with-your-ps4-gaming-moments-online-sharing-secrets-revealed/"><u>New 2024 Approved Go Viral with Your PS4 Gaming Moments Online Sharing Secrets Revealed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-discord-load-times-in-windows-operating-system/"><u>Optimizing Discord Load Times in Windows Operating System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-user-experience-adding-shortcut-keys-for-wordpad-to-windows-ui/"><u>Personalizing User Experience: Adding Shortcut Keys for Wordpad to Windows UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reestablishing-active-search-in-windows-11/"><u>Reestablishing Active Search in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-defender-past-techniques-for-windows-cleanse/"><u>Revamp Your Defender Past: Techniques for Windows Cleanse</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-connectivity-restored-reveal-the-hidden-fixes-for-missing-bluetooth-on-win-11/"><u>Seamless Connectivity Restored: Reveal the Hidden Fixes for Missing Bluetooth on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-protection-stick-to-single-antivirus-software-in-windows/"><u>Simplify Protection: Stick to Single Antivirus Software in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slip-through-security-gaps-stealthy-remote-access-on-windows-11/"><u>Slip Through Security Gaps: Stealthy Remote Access on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-implementing-dark-mode-for-calc/"><u>Step-by-Step: Implementing Dark Mode for Calc</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-securing-administrator-access-on-windows/"><u>Steps for Securing Administrator Access on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correctly-handle-0x8007045d-errors-in-win11/"><u>Steps to Correctly Handle 0X8007045D Errors in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-iphone-image-failure-in-windows-os/"><u>Steps to Resolve iPhone Image Failure in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sudos-arrival-streamlining-windows-tasks/"><u>Sudo's Arrival: Streamlining Windows Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-format-rejection-by-windows-vlc/"><u>Tackling the Format Rejection by Windows-VLC</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-modern-shoppers-guide-to-360-degree-imaging-tech/"><u>The Modern Shopper's Guide to 360-Degree Imaging Tech</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-trending-and-most-popular-movies-to-binge-on-disneyplus-this-week/"><u>Top Trending & Most Popular Movies to Binge on Disney+ This Week</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-camera-issue-saving-imagesvideos-problems/"><u>Troubleshooting Windows Camera Issue: Saving Images/Videos Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-and-rectifying-windows-struggling-charmap-problems/"><u>Unraveling and Rectifying Windows' Struggling CharMap Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-fixes-reactivating-windows-batch-file-operations/"><u>Unveiling Fixes: Reactivating Windows Batch File Operations</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-when-infinix-hot-30i-has-black-screen-of-death-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do When Infinix Hot 30i Has Black Screen of Death? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/whats-bothering-you-common-complaints-about-windows-11/"><u>What's Bothering You? Common Complaints About Windows 11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>