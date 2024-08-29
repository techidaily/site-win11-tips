---
title: Reinstating Active State for Windows 11 Context Menu
date: 2024-08-28T01:12:48.987Z
updated: 2024-08-29T01:12:48.987Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinstating Active State for Windows 11 Context Menu
excerpt: This Article Describes Reinstating Active State for Windows 11 Context Menu
keywords: Win11 Menu Restore,Context Menu Active,Windows 11 Quick Fix,State Menu Reinstate,Win11 UI Update,Activate Window Menu,ContextMenu_Win11
thumbnail: https://thmb.techidaily.com/919573cc608b6cdec882b8be060a2b2c2cf20857c29aeec82d8f35e1cc72f6d6.jpg
---

## Reinstating Active State for Windows 11 Context Menu

 Right-clicking the Windows desktop will usually open the context menu, which many users need to access regularly. However, some users have reported that the right-click menu gets stuck loading forever with a spinning cursor or doesn’t display correctly. Users can’t access the context menu for the desktop when it’s not working right.

 Although desktop context menu access is seldom essential, it offers handy shortcuts, especially when you've customized it. So, it’s important to fix the desktop context menu when it’s not working. If your Windows desktop context menu isn’t functioning right, try applying the troubleshooting methods below.

## 1\. Restart the File Explorer Process

 File Explorer handles the right-click context menu on the Windows desktop. Users confirm that refreshing File Explorer can sometimes fix the context menu when it’s not working. Our article about [how to restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) explains how to apply this potential resolution with Task Manager.

![The Windows Explorer process](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-process.jpg)

## 2\. Scan Your PC With System File Checker and Deployment Image Servicing Management

 Corrupted system files can be a cause for menus not displaying correctly in Windows. So, we recommend users run system image and file scans when the context menu isn’t working right.

 You can run SFC and DISM scans as covered for methods one and two in this guide to [repairing corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/).

![The sfc /scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-sfc-scannow-command.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
## 3\. Deactivate Tablet Mode (for Windows 10)

 The context menu loses functionality when Windows 10 is in Tablet Mode. So, check whether you've inadvertently set your PC to Tablet Mode. Our [turning off Windows 10’s tablet mode](https://www.makeuseof.com/turn-off-tablet-mode-windows-10/) provides details about how to disable that mode via the Action Center.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
## 4\. Change the "Remove File Explorer" Context Menu Policy Setting

 The Windows Group Policy has a "Remove File Explorer" setting that disables the desktop’s right-click menu when enabled. If you’re a Windows Pro or Enterprise user, check that policy to see if it is enabled and disable it if it is.

 This is how you can disable that policy:

1. Press the **Win + R** shortcut to open Run.
2. Type **gpedit.msc** inside the **Open** text box and click **OK** to bring up the Group Policy Editor.
3. Next, double-click the **User Configuration** navigation option in Group Policy Editor’s sidebar.
4. Double-click **Administrative Templates** \> **Windows Components** to expand those navigation options.  
![Windows Components in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/group-policy-editor.jpg)
5. Then click **File Explorer** to view its policy settings.
6. Double-click on the **Remove File Explorer’s default context menu** option.
7. Select the policy’s **Not Configured** radio button.  
![The Not Configured radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/not-configured-radio-button.jpg)
8. Click **Apply** to set the policy change.
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
9. Select **OK** to exit the Remove File Explorer’s default context menu window.

## 5\. Create a NoViewContextMenu Registry DWORD

 Some users confirm they’ve been able to fix their context menus by creating a new **NoViewContextMenu** DWORD in the **Explorer** registry key. Creating such a DWORD can reactivate the context menu.

 Although this sounds like a complex solution, it’s quite straightforward to apply. You can create a **NoViewContextMenu** DWORD like this:

1. Run the Registry Editor app by pressing **Win + S**, entering **regedit**, and selecting its search result.
2. Click on the address bar in the registry editor and input this key path:  
`Computer\HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\Explorer`
3. Right-click the **Explorer** key and select **New**.
4. Click **DWORD (32-bit) Value** on the submenu.  
![The New > DWORD options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-new-key-options2.jpg)
5. Type **NoViewContextMenu** in the text box for the DWORD.
6. The **NoViewContextMenu** DWORD will probably be set to 0 by default when you create it. However, double-click the **NoViewContextMenu** just to check its value.  
![The Edit DWORD (32-bit) Value window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/edit-dword-window.jpg)
7. Set the **NoViewContextMenu** value to **0** in the **data** box if it’s not already and click **OK**.

## 6\. Modify the ContextMenuHandlers Key

 Modifying the ContextMenuHandlers key is another widely confirmed way to fix the context menu. However, this registry tweak involves deleting some keys. So, we recommend you [create a System Restore point](https://www.makeuseof.com/windows-11-create-restore-point/) or [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before applying this potential solution. Then modify the ContextMenuHandlers key as follows:

1. Launch Registry Editor and go to this key location:  
`Computer\HKEY_CLASSES_ROOT\Directory\Background\shellex\ContextMenuHandlers`
2. Now delete all subkeys within the **ContextMenuHandlers** key except **New**, **Sharing**, **WorkFolders**, and **FileSyncEx**. To do so, right-click a subkey and select **Delete**.  
![The Delete registry key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-delete-option.jpg)
3. Click **Yes** when prompted to provide confirmation.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
4. Repeat the previous two steps to erase the other subkeys in **ContextMenuHandlers**, but do not delete **WorkFolders**, **FileSyncEx**, **New**, and **Sharing**.  
![The ContextMenuHandlers key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/contextmenuhandlers-key.jpg)
5. Exit Registry Editor and select to restart your Windows PC.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Update Your Mouse’s Driver

 The mouse is the peripheral with which users activate the context menu. Although not an especially likely cause, it’s possible your context menu isn’t working because your mouse’s driver is faulty or outdated. So, try updating the driver for your mouse. We have a guide about [finding and replacing old device drivers](https://www.makeuseof.com/tag/find-replace-outdated-windows-drivers/) that provides details for how you can apply this potential fix.

![A mouse driver download page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-download-option.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 Incidentally, you check if the context menu not working is a mouse issue by utilizing the hotkey for that menu. Try pressing the **Shift** \+ **F10** hotkey when on the desktop to see if that opens the context menu. Or select a desktop shortcut and press that keyboard shortcut. If the context menu works then, there could be an issue with your mouse or its right button.

## 8\. Perform a Clean Boot

 A conflicting third-party program might be crashing your context menu. For example, mouse managers or software packages with right-click shell extensions could be causing context menu issues. For example, Google Drive, WinZip, and 7-Zip are software packages that add right-click shell extensions.

 To eliminate such a possible cause, try clean booting your Windows PC. Applying this troubleshooting method disables third-party startup programs and services set to run automatically. Our guide to [performing a clean boot on Windows](https://www.makeuseof.com/how-perform-clean-boot-windows-10/) provides step-by-step instructions for how you can disable those startup items with Task Manager and System Configuration.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-services-tab3.jpg)

 When you’ve set the clean boot, restart Windows and right-click on the desktop to see if the context menu works ok. If it does, then it’s probably better to leave the boot configuration as set. However, you can try to identify what program or service was causing the issue by gradually re-enabling disabled startup apps and services until the context menu stops working again.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
## 9\. Disable Third-Party Context Menu Shell Extensions With CCleaner

 You can also directly select to turn off third-party shell extensions included in the startup that might be causing context menu issues with CCleaner. So, try turning off superfluous context menu add-ons with that software as follows:

1. Go to the [CCleaner website](https://www.anrdoezrs.net/links/7251228/type/dlg/sid/UUmuoUeUpU2027967/https://www.ccleaner.com/ccleaner/download?ppc%5Fcode=012&ppc=a&gclsrc=aw.ds&gclid=CjwKCAjwtuOlBhBREiwA7agf1ofUbIfUK8X-GzUG-CBD%5F%5F1dyp8qqSnTPOOlQqX1d7ocUDK5BxqH-hoCw1oQAvD%5FBwE) and click **Free Download** there.
2. Activate File Explorer (simultaneously press **Win + E**) and navigate to the folder that includes the downloaded CCleaner setup file.
3. Double-click **ccsetup614.exe** to start the setup wizard.
4. Select **Install** to add the software with default installation settings.  
![The Install option for CCleaner](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-install-button.jpg)
5. Open CCleaner and click its **Tools** tab.
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Click the **Startup** and **Context Menu** tabs.
7. Look at the Program column to identify third-party shell extensions listed there.  
![The Context Menu tab in CCleaner](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-context-menu-tab-in-cccleaner.jpg)
8. Select third-party shell extensions and click **Disable** to turn them off.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## Get the Desktop Context Menu Fixed With These Resolutions

 The troubleshooting methods above are quite thorough and will likely resolve most Windows context menu issues. Lots of users have been able to fix the context menu not working by applying the registry tweak solutions.

 If the potential solutions here don’t work for you, you may need to try something more drastic, like resetting Windows or performing an in-place upgrade reinstallation.

 Although desktop context menu access is seldom essential, it offers handy shortcuts, especially when you've customized it. So, it’s important to fix the desktop context menu when it’s not working. If your Windows desktop context menu isn’t functioning right, try applying the troubleshooting methods below.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-knowledge.techidaily.com/new-exhaustive-evaluation-the-new-360-camera/"><u>[New] Exhaustive Evaluation  The New 360 Camera</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-elite-android-and-pc-mkv-software/"><u>[New] In 2024, Elite Android & PC MKV Software</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-top-5-non-bandicamp-capture-tools-for-mac-users/"><u>[Updated] Top 5 Non-Bandicamp Capture Tools for Mac Users</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-comprehensive-review-navigating-adobe-cloud-plus-comparing-rivals/"><u>2024 Approved  Comprehensive Review  Navigating Adobe Cloud + Comparing Rivals</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-crafting-unique-cellphone-alerts-from-popular-tiktok-music/"><u>2024 Approved  Crafting Unique Cellphone Alerts From Popular TikTok Music</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-essential-guide-converting-youtube-videos-to-mpegmp4/"><u>2024 Approved  Essential Guide  Converting YouTube Videos to MPEG/MP4</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-winning-art-tools-comparison-chart-free-and-paid-apps/"><u>2024 Approved  Winning Art Tools Comparison Chart  FREE & PAID Apps</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/archive-adrenaline-fueled-moments-in-galaxy-games-for-2024/"><u>Archive Adrenaline-Fueled Moments in Galaxy Games for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clandestine-file-storage-win11s-image-encryption-tricks/"><u>Clandestine File Storage: Win11's Image Encryption Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-security-turn-on-controlled-folder-access-in-windows-11/"><u>Command Security: Turn on Controlled Folder Access in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-approach-to-managing-svchostexe-netsvcs-and-its-high-bandwidth-use/"><u>Comprehensive Approach to Managing svchost.exe (Netsvcs) and Its High Bandwidth Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-windows-1011-ui-with-portable-apps-icons/"><u>Elevate Windows 10/11 UI with Portable Apps Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/empowering-powershell-mastery-of-execution-policy-settings/"><u>Empowering PowerShell: Mastery of Execution Policy Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-building-shortcuts-to-uwp-apps-in-windows-11/"><u>Essential Tips: Building Shortcuts to UWP Apps in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-insight-on-locating-windows-1110-product-key/"><u>Exclusive Insight on Locating Windows 11/10 Product Key</u></a></li>
<li><a href="https://some-techniques.techidaily.com/eye-twinkling-jokes-generate-on-kapwing-for-2024/"><u>Eye-Twinkling Jokes  Generate on Kapwing for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-essential-steps-to-overcome-windows-os-hypervisor-faults/"><u>Five Essential Steps to Overcome Windows OS Hypervisor Faults</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-unsuccessful-file-transfers-on-windows-pcs/"><u>Fixing Unsuccessful File Transfers on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-zero-to-dev-windows-11s-jdk-integration/"><u>From Zero to Dev: Windows 11'S JDK Integration</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-change-your-sim-pin-code-on-your-oppo-a78-phone-by-drfone-android/"><u>How To Change Your SIM PIN Code on Your Oppo A78 Phone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-pictures-on-iphone-7-plus-5-best-solutions-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Recover deleted pictures on iPhone 7 Plus? 5 Best Solutions | Stellar</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-wiped-messages-on-xiaomi-14-pro-by-fonelab-android-recover-messages/"><u>How to restore wiped messages on Xiaomi 14 Pro</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-samsung-galaxy-s24withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Samsung Galaxy S24with/without a PC</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-ultimate-guide-premium-plugins-boosting-ae-projects/"><u>In 2024, Ultimate Guide  Premium Plugins Boosting AE Projects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-command-line-integration-in-windows-11s-task-manager/"><u>Mastering Command Line Integration in Windows 11'S Task Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-folder-inclusion-in-win11s-context-menu/"><u>Mastering Folder Inclusion in Win11's Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11s-action-center-mixer-for-immersive-sound/"><u>Mastering Windows 11'S Action Center Mixer for Immersive Sound</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-top-6-best-free-divx-video-cutters-for-2024/"><u>New Top 6 Best Free Divx Video Cutters for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-double-click-quickness-on-pc-three-key-settings/"><u>Optimize Double-Click Quickness on PC: Three Key Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-your-screen-and-sound-recordings-with-the-updated-windows-11-snipping-tool-max-156/"><u>Optimizing Your Screen & Sound Recordings with the Updated Windows 11 Snipping Tool (Max 156)</u></a></li>
<li><a href="https://sound-issues.techidaily.com/overcoming-microphone-challenges-in-counter-strike-global-offensive/"><u>Overcoming Microphone Challenges in Counter-Strike Global Offensive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-nonexistent-gadget-reference-on-win-11/"><u>Overcoming Nonexistent Gadget Reference on Win 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/process-of-screen-sharing-xiaomi-redmi-k70e-to-pc-detailed-steps-drfone-by-drfone-android/"><u>Process of Screen Sharing Xiaomi Redmi K70E to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-the-absence-of-supported-scanner-for-windows-hello/"><u>Remedying the Absence of Supported Scanner for Windows Hello</u></a></li>
<li><a href="https://techidaily.com/repair-video-tool-repair-all-your-damaged-video-files-of-infinix-note-30i-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>Repair Video Tool - Repair all your damaged video files of Infinix Note 30i on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-faulty-ports-the-windows-way-to-reclaim-usb-health/"><u>Restoring Faulty Ports - The Windows Way to Reclaim USB Health</u></a></li>
<li><a href="https://win11-tips.techidaily.com/set-windows-calculator-display-to-dark/"><u>Set Windows Calculator Display to Dark</u></a></li>
<li><a href="https://driver-error.techidaily.com/stabilized-windows-11-display/"><u>Stabilized Windows 11 Display</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-8-windows-compatible-ios-apps-for-android-users/"><u>Top 8 Windows-Compatible iOS Apps for Android Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-strategies-to-overcome-no-server-woes-in-windows-pc-apex-legends-(156-chars/"><u>Top Strategies to Overcome No-Server Woes in Windows PC Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshooting-tips-reviving-your-iphones-control-center/"><u>Troubleshooting Tips: Reviving Your iPhone's Control Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-system-potential-enhancing-virtual-memory/"><u>Unlocking System Potential: Enhancing Virtual Memory</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-to-do-when-your-update-fails-at-0x800f0845/"><u>What to Do When Your Update Fails at 0X800F0845?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-woes-rescue-your-operators-download/"><u>Windows Woes? Rescue Your Operator's Download</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winos-tricks-for-program-stability/"><u>WinOS Tricks for Program Stability</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>