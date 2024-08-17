---
title: "Start-Up Sync: Automatic Windows Entry with Sticky Notes"
date: 2024-08-16T01:47:09.750Z
updated: 2024-08-17T01:47:09.750Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Start-Up Sync: Automatic Windows Entry with Sticky Notes"
excerpt: "This Article Describes Start-Up Sync: Automatic Windows Entry with Sticky Notes"
keywords: Start-Up Syncs,Auto Window Entry,Sticky Notes Integrate,Windows Sync Tip,Quick Start Setup,Automated Entry Alert,Efficient Note Linking
thumbnail: https://thmb.techidaily.com/485fa639637af95e40bb39955015be2d5660936e6475a435b4a4c85695223b88.jpg
---

## Start-Up Sync: Automatic Windows Entry with Sticky Notes

 Are you tired of opening Sticky Notes every time you turn on your computer? What if it could open automatically each time Windows starts?

 Well, there's good news for you: Sticky Notes can launch at startup in Windows. This article illustrates how to set up and use Sticky Notes at startup.

## 1\. Keep Sticky Notes Open at Shutdown

 When you're done working with Sticky Notes, make sure not to close the window. Instead, leave it open as you shut down your computer. This will ensure that when you turn on your computer, Sticky Notes opens automatically.

 Although the solution is simple, it may not work, or you may find it difficult to remember to keep it open when you turn off your PC. In that case, there are other alternatives; add Sticky Notes to the startup folder or use Task Scheduler.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Add Sticky Notes to the Startup Folder

 If you don't want to keep Sticky Notes open at shutdown, you can add it to the startup folder. The Startup folder is a special directory in File Explorer. It stores applications that launch automatically when Windows starts.

 To add Sticky Notes to the Startup folder, follow these steps.

1. Press **Win + R** and type **shell:startup** in the Run dialog.
2. Click **OK** or press Enter. This opens a folder containing all the applications that launch at startup.
3. Press **Windows** to open the Start menu, then click **All apps**. Now scroll down and find **Sticky Notes** in the list.
4. Drag and drop **Sticky Notes** into the Startup folder.

 After performing these steps, close File Explorer and restart your computer. Sticky Notes should now open at startup.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Use the Task Scheduler

 Task Scheduler is another way to open Sticky Notes at startup. This Windows feature schedules and automates tasks at specific times or conditions.

 To add Sticky Notes using this tool, follow these steps:

1. [Open Task Scheduler](https://www.makeuseof.com/windows-11-open-task-scheduler/).
2. Click **Create Basic Task** from the **Actions** panel on the right. This opens a wizard that guides you through the setup.  
![Create Basic Task in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-in-task-scheduler.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
3. In the first step, give your task a name and click **Next**.  
![Startup Sticky Notes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-sticky-notes.jpg)
4. Now select **When I log on** as the trigger and click **Next** at the bottom.  
![Create Basic Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-wizard.jpg)
5. Choose **Start a program** in the Action window and click **Next**.  
![Start a program in Action tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-action-tab.jpg)
6. In the **Program/script** field, type the path below:  
C:\Windows\System32\cmd.exe
7. In the Add arguments (optional) field, copy and paste the following command:  
/c start shell:appsfolder\Microsoft.MicrosoftStickyNotes_8wekyb3d8bbwe!App ![Start a Program in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-task-scheduler.jpg)
8. Click **Next** and review all the settings.
9. Now click **Finish** to save your work.  
![Finish Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/finish-task-wizard.jpg)
<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->

 The Task Scheduler will now run Sticky Notes each time you log in. This way, Sticky Notes launches automatically at startup.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
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
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Change the Value data from 0 to **1** in the Edit DWORD (32-bit) Value window and click **OK**.  
 If you can't find the **LaunchOnNextUserSession** key, right-click on the **Notes** folder and select **New > DWORD (32-bit) Value**. Name the newly created key “LaunchOnNextUserSession” and assign it the Value data of **1**.
7. Close the Registry Editor and restart your computer to save the changes. Sticky Notes should now open at startup.

## Windows Now Starts With Sticky Notes Open

 This article outlines several ways to open Sticky Notes at startup in Windows. If you want an easier solution, leave Sticky Notes open when you shut down your computer; it will launch automatically when Windows starts. If not, add Sticky Notes to the startup folder. If you want more control over when Sticky Notes launches, use Task Scheduler or tweak the Registry Editor.

 Well, there's good news for you: Sticky Notes can launch at startup in Windows. This article illustrates how to set up and use Sticky Notes at startup.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-from-lurker-to-leader-the-roadmap-to-higher-fb-page-rankings/"><u>[New] In 2024, From Lurker to Leader  The Roadmap to Higher FB Page Rankings</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-humor-hierarchy-ranking-10-memes-in-order-of-delight/"><u>[Updated] Humor Hierarchy  Ranking #10 Memes in Order of Delight</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-revolutionize-your-mobile-viewing-experience/"><u>2024 Approved  Revolutionize Your Mobile Viewing Experience</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-streamline-your-watching-enabling-youtube-autoplay-in-facebook-feeds/"><u>2024 Approved  Streamline Your Watching  Enabling YouTube Autoplay in Facebook Feeds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-lifeline-for-gaming-ensuring-persistent-connection-of-your-ps4-controller-in-windows/"><u>A Lifeline for Gaming: Ensuring Persistent Connection of Your PS4 Controller in Windows</u></a></li>
<li><a href="https://win-amazing.techidaily.com/boost-your-windows-7-wifi-experience-with-hassle-free-driver-downloads-and-updates/"><u>Boost Your Windows 7 WiFi Experience with Hassle-Free Driver Downloads & Updates!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-system-startup-with-auto-auditory-restart-mechanism/"><u>Boosting System Startup with Auto Auditory Restart Mechanism</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-restricted-it-administrator-message-in-os/"><u>Eliminating 'Restricted IT Administrator' Message in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-firewall-essential-fixes-for-a-shutdown-system/"><u>Enabling Firewall: Essential Fixes for a Shutdown System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-file-sharing-capabilities-in-geforce/"><u>Enhancing File-Sharing Capabilities in GeForce</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-usability-faster-uninstall-options-in-win/"><u>Enhancing Usability: Faster Uninstall Options in Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-11-taskbar-responsiveness/"><u>Enhancing Windows 11 Taskbar Responsiveness</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-solutions-to-resolve-windows-update-error-0x800f080a/"><u>Essential Solutions to Resolve Windows Update Error 0X800F080A</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-1011-camera-error-0xa00f425d/"><u>Fixing Windows 10/11 Camera Error: 0XA00F425D</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-11-pro-drfone-by-drfone-ios/"><u>How to Unlock iPhone 11 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/income-streams-from-windows-11-an-examination/"><u>Income Streams From Windows 11: An Examination</u></a></li>
<li><a href="https://win11-tips.techidaily.com/incorporating-external-disk-into-explorer-nav-pane/"><u>Incorporating External Disk Into Explorer Nav Pane</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/maximizing-energy-the-impressive-beatit-bt-d11-jump-starter-examined/"><u>Maximizing Energy: The Impressive Beatit BT-D11 Jump Starter Examined</u></a></li>
<li><a href="https://win11-tips.techidaily.com/put-a-halt-on-application-start-tracking-in-windows/"><u>Put a Halt on Application Start-Tracking in Windows</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/record-computer-sound-and-microphone/"><u>Record Computer Sound and Microphone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/reset-itunes-backup-password-of-apple-iphone-8-plus-prevention-and-solution-by-drfone-ios/"><u>Reset iTunes Backup Password Of Apple iPhone 8 Plus Prevention & Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sharpen-windows-safety-edge-context-menu-firewall-customization-guide/"><u>Sharpen Windows Safety Edge: Context Menu Firewall Customization Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speed-spectrum-mastering-windows-network-adapter-assessment-methods/"><u>Speed Spectrum: Mastering Windows' Network Adapter Assessment Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-resetting-windows-settings-on-reboot/"><u>Steps for Resetting Windows Settings on Reboot</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-complete-guide-to-xiaomi-14-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>The Complete Guide to Xiaomi 14 FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-csgo-launch-failures-on-w11/"><u>Troubleshooting CS:GO Launch Failures on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-and-fixing-the-msvcr110dll-gap/"><u>Uncovering & Fixing the Msvcr110.dll Gap</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-door-on-stuck-wow-61-patches/"><u>Unlocking the Door on Stuck WoW 6.1 Patches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrading-widely-used-directx-classics-through-dxvk/"><u>Upgrading Widely-Used DirectX Classics Through DXVK</u></a></li>
</ul></div>
