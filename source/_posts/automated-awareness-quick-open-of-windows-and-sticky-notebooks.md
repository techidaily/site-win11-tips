---
title: "Automated Awareness: Quick Open of Windows and Sticky Notebooks"
date: 2024-08-16T01:08:19.351Z
updated: 2024-08-17T01:08:19.351Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Automated Awareness: Quick Open of Windows and Sticky Notebooks"
excerpt: "This Article Describes Automated Awareness: Quick Open of Windows and Sticky Notebooks"
keywords: Quick Window Access,Automatic Notification,Fast Opens Systems,Rapid Window Closure,Enhanced Sticky Notes,Immediate System Response,Faster Notebook Opening
thumbnail: https://thmb.techidaily.com/95c7607cc85834758f594e36f86b8274633568f32ba37267dd79e6e802f121e2.png
---

## Automated Awareness: Quick Open of Windows and Sticky Notebooks

 Are you tired of opening Sticky Notes every time you turn on your computer? What if it could open automatically each time Windows starts?

 Well, there's good news for you: Sticky Notes can launch at startup in Windows. This article illustrates how to set up and use Sticky Notes at startup.

## 1\. Keep Sticky Notes Open at Shutdown

 When you're done working with Sticky Notes, make sure not to close the window. Instead, leave it open as you shut down your computer. This will ensure that when you turn on your computer, Sticky Notes opens automatically.

 Although the solution is simple, it may not work, or you may find it difficult to remember to keep it open when you turn off your PC. In that case, there are other alternatives; add Sticky Notes to the startup folder or use Task Scheduler.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
4. Now select **When I log on** as the trigger and click **Next** at the bottom.  
![Create Basic Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-wizard.jpg)
5. Choose **Start a program** in the Action window and click **Next**.  
![Start a program in Action tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-action-tab.jpg)
6. In the **Program/script** field, type the path below:  
C:\Windows\System32\cmd.exe
7. In the Add arguments (optional) field, copy and paste the following command:  
/c start shell:appsfolder\Microsoft.MicrosoftStickyNotes_8wekyb3d8bbwe!App  
![Start a Program in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-task-scheduler.jpg)
<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Click **Next** and review all the settings.
9. Now click **Finish** to save your work.  
![Finish Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/finish-task-wizard.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The Task Scheduler will now run Sticky Notes each time you log in. This way, Sticky Notes launches automatically at startup.

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
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Change the Value data from 0 to **1** in the Edit DWORD (32-bit) Value window and click **OK**.  
 If you can't find the **LaunchOnNextUserSession** key, right-click on the **Notes** folder and select **New > DWORD (32-bit) Value**. Name the newly created key “LaunchOnNextUserSession” and assign it the Value data of **1**.
7. Close the Registry Editor and restart your computer to save the changes. Sticky Notes should now open at startup.

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-start-your-social-media-show-going-live-on-facebook/"><u>[Updated] In 2024, Start Your Social Media Show  Going Live on Facebook</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-quick-and-easy-online-photo-cropping-hacks-for-2024/"><u>[Updated] Quick and Easy Online Photo Cropping Hacks for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-shotchrome-ultra-premium-chromeos-snapshooter/"><u>[Updated] ShotChrome Ultra  Premium ChromeOS Snapshooter</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-step-by-step-process-of-amplifying-your-channel-with-high-impact-placement-for-2024/"><u>[Updated] Step-by-Step Process of Amplifying Your Channel with High-Impact Placement for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-top-10-free-tools-to-convert-srt-into-engaging-video-content/"><u>2024 Approved  Top 10 FREE Tools to Convert SRT Into Engaging Video Content</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-unveiling-the-techniques-for-autoplay-youtube-videos-on-fb/"><u>2024 Approved  Unveiling the Techniques for Autoplay YouTube Videos on FB</u></a></li>
<li><a href="https://win11-tips.techidaily.com/curbing-cpu-fatigue-adjusting-the-workload-of-vanguards-sleep-service/"><u>Curbing CPU Fatigue: Adjusting the Workload of Vanguard's Sleep Service</u></a></li>
<li><a href="https://extra-tips.techidaily.com/economical-aether-fileshare-for-bulk-digital-storing/"><u>Economical Aether Fileshare for Bulk Digital Storing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-strategies-for-icon-placement-repair/"><u>Effective Strategies for Icon Placement Repair</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-methods-to-test-active-tcp-ports-on-windows/"><u>Efficient Methods to Test Active TCP Ports on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-workflow-add-software-menus-to-windows-desktop/"><u>Enhance Workflow: Add Software Menus to Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-to-mend-windows-store-error-0x0-failure/"><u>Expert Tips to Mend Windows Store Error 0X0 Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-to-resolve-rd-connectivity-issues-on-win-10plus/"><u>Expert Tips to Resolve RD Connectivity Issues on WIN 10+</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-system-failures-a-guide-to-repairing-fs-in-win11/"><u>Fixing System Failures: A Guide to Repairing FS in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-correct-the-save-location-error-on-pcs/"><u>How to Correct the Save Location Error on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-virtualboxs-0x80004005-failure-in-windows/"><u>How to Resolve VirtualBox's 0X80004005 Failure in Windows</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-13-to-other-iphone-13-pro-max-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 13 to other iPhone 13 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-integrating-dolby-atmos-audio/"><u>Mastering Windows 11: Integrating Dolby Atmos Audio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-new-horizons-the-developers-guide-to-dev-drive-win11/"><u>Navigating New Horizons: The Developer's Guide to Dev Drive Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-installation-blocks-in-the-windows-store/"><u>Overcoming Installation Blocks in the Windows Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precision-time-management-chrome-and-windows-harmony/"><u>Precision Time Management: Chrome and Windows Harmony</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-irregularities-in-desktop-menu-settings/"><u>Rectifying Irregularities in Desktop Menu Settings</u></a></li>
<li><a href="https://techidaily.com/reset-pattern-lock-tutorial-for-vivo-v27e-by-drfone-android-unlock-android-unlock/"><u>Reset pattern lock Tutorial for Vivo V27e</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-resolving-missing-gpeditmsc-error-on-pcs/"><u>Solutions for Resolving Missing Gpedit.msc Error on PCs</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/the-guide-to-turn-off-ig-predictions-for-2024/"><u>The Guide to Turn Off IG Predictions for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-correcting-reverse-character-entry-on-pcs/"><u>Tips for Correcting Reverse Character Entry on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-make-excel-compatible-with-notepad/"><u>Tips: Make Excel Compatible with Notepad</u></a></li>
<li><a href="https://youtube-data.techidaily.com/0-decibel-upgraders-for-every-os-for-2024/"><u>Top 10 Decibel Upgraders for Every OS for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncover-your-global-address-through-the-cli-win-1110/"><u>Uncover Your Global Address Through the CLI, Win 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-your-pc-6-methods-for-discovering-its-identity/"><u>Unveiling Your PC: 6 Methods for Discovering Its Identity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-disk-structure-c-vs-d-in-focus/"><u>Windows Disk Structure: C vs D in Focus</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/youtubes-best-love-stories-perfectly-captured-weddings/"><u>YouTube's Best Love Stories  Perfectly Captured Weddings</u></a></li>
</ul></div>
