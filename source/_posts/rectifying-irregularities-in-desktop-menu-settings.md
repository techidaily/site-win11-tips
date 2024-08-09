---
title: Rectifying Irregularities in Desktop Menu Settings
date: 2024-08-08T11:01:50.783Z
updated: 2024-08-09T11:01:50.783Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Rectifying Irregularities in Desktop Menu Settings
excerpt: This Article Describes Rectifying Irregularities in Desktop Menu Settings
keywords: Fixing Desk Top Issues,Menu Setting Corrections,Resolve Menu Errors,Adjust Desktop Menu,Rectify UI Mistakes,Correct Menu Layout,Menu Settings Revision
thumbnail: https://thmb.techidaily.com/543a8e6d7f06f3d9129829edd8982dbf9c6a6048e52160481e81c4276bc515b3.jpg
---

## Rectifying Irregularities in Desktop Menu Settings

 Right-clicking the Windows desktop will usually open the context menu, which many users need to access regularly. However, some users have reported that the right-click menu gets stuck loading forever with a spinning cursor or doesn’t display correctly. Users can’t access the context menu for the desktop when it’s not working right.

 Although desktop context menu access is seldom essential, it offers handy shortcuts, especially when you've customized it. So, it’s important to fix the desktop context menu when it’s not working. If your Windows desktop context menu isn’t functioning right, try applying the troubleshooting methods below.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Restart the File Explorer Process

 File Explorer handles the right-click context menu on the Windows desktop. Users confirm that refreshing File Explorer can sometimes fix the context menu when it’s not working. Our article about [how to restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) explains how to apply this potential resolution with Task Manager.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
![The Windows Explorer process](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-process.jpg)

<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
## 2\. Scan Your PC With System File Checker and Deployment Image Servicing Management

 Corrupted system files can be a cause for menus not displaying correctly in Windows. So, we recommend users run system image and file scans when the context menu isn’t working right.

 You can run SFC and DISM scans as covered for methods one and two in this guide to [repairing corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/).

![The sfc /scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-sfc-scannow-command.jpg)

## 3\. Deactivate Tablet Mode (for Windows 10)

 The context menu loses functionality when Windows 10 is in Tablet Mode. So, check whether you've inadvertently set your PC to Tablet Mode. Our [turning off Windows 10’s tablet mode](https://www.makeuseof.com/turn-off-tablet-mode-windows-10/) provides details about how to disable that mode via the Action Center.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
## 4\. Change the "Remove File Explorer" Context Menu Policy Setting

 The Windows Group Policy has a "Remove File Explorer" setting that disables the desktop’s right-click menu when enabled. If you’re a Windows Pro or Enterprise user, check that policy to see if it is enabled and disable it if it is.

 This is how you can disable that policy:

1. Press the **Win + R** shortcut to open Run.
2. Type **gpedit.msc** inside the **Open** text box and click **OK** to bring up the Group Policy Editor.
3. Next, double-click the **User Configuration** navigation option in Group Policy Editor’s sidebar.
4. Double-click **Administrative Templates** \> **Windows Components** to expand those navigation options.  
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
![Windows Components in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/group-policy-editor.jpg)
5. Then click **File Explorer** to view its policy settings.
6. Double-click on the **Remove File Explorer’s default context menu** option.
7. Select the policy’s **Not Configured** radio button.  
![The Not Configured radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/not-configured-radio-button.jpg)
8. Click **Apply** to set the policy change.
9. Select **OK** to exit the Remove File Explorer’s default context menu window.

## 5\. Create a NoViewContextMenu Registry DWORD

 Some users confirm they’ve been able to fix their context menus by creating a new **NoViewContextMenu** DWORD in the **Explorer** registry key. Creating such a DWORD can reactivate the context menu.

 Although this sounds like a complex solution, it’s quite straightforward to apply. You can create a **NoViewContextMenu** DWORD like this:

1. Run the Registry Editor app by pressing **Win + S**, entering **regedit**, and selecting its search result.
2. Click on the address bar in the registry editor and input this key path:  
`Computer\HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\Explorer`
3. Right-click the **Explorer** key and select **New**.
4. Click **DWORD (32-bit) Value** on the submenu.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
![The New > DWORD options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-new-key-options2.jpg)
5. Type **NoViewContextMenu** in the text box for the DWORD.
6. The **NoViewContextMenu** DWORD will probably be set to 0 by default when you create it. However, double-click the **NoViewContextMenu** just to check its value.  
![The Edit DWORD (32-bit) Value window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/edit-dword-window.jpg)
7. Set the **NoViewContextMenu** value to **0** in the **data** box if it’s not already and click **OK**.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Modify the ContextMenuHandlers Key

 Modifying the ContextMenuHandlers key is another widely confirmed way to fix the context menu. However, this registry tweak involves deleting some keys. So, we recommend you [create a System Restore point](https://www.makeuseof.com/windows-11-create-restore-point/) or [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before applying this potential solution. Then modify the ContextMenuHandlers key as follows:

1. Launch Registry Editor and go to this key location:  
`Computer\HKEY_CLASSES_ROOT\Directory\Background\shellex\ContextMenuHandlers`
2. Now delete all subkeys within the **ContextMenuHandlers** key except **New**, **Sharing**, **WorkFolders**, and **FileSyncEx**. To do so, right-click a subkey and select **Delete**.  
![The Delete registry key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-delete-option.jpg)
3. Click **Yes** when prompted to provide confirmation.
4. Repeat the previous two steps to erase the other subkeys in **ContextMenuHandlers**, but do not delete **WorkFolders**, **FileSyncEx**, **New**, and **Sharing**.  
![The ContextMenuHandlers key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/contextmenuhandlers-key.jpg)
5. Exit Registry Editor and select to restart your Windows PC.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Update Your Mouse’s Driver

 The mouse is the peripheral with which users activate the context menu. Although not an especially likely cause, it’s possible your context menu isn’t working because your mouse’s driver is faulty or outdated. So, try updating the driver for your mouse. We have a guide about [finding and replacing old device drivers](https://www.makeuseof.com/tag/find-replace-outdated-windows-drivers/) that provides details for how you can apply this potential fix.

![A mouse driver download page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-download-option.jpg)

 Incidentally, you check if the context menu not working is a mouse issue by utilizing the hotkey for that menu. Try pressing the **Shift** \+ **F10** hotkey when on the desktop to see if that opens the context menu. Or select a desktop shortcut and press that keyboard shortcut. If the context menu works then, there could be an issue with your mouse or its right button.

## 8\. Perform a Clean Boot

 A conflicting third-party program might be crashing your context menu. For example, mouse managers or software packages with right-click shell extensions could be causing context menu issues. For example, Google Drive, WinZip, and 7-Zip are software packages that add right-click shell extensions.

 To eliminate such a possible cause, try clean booting your Windows PC. Applying this troubleshooting method disables third-party startup programs and services set to run automatically. Our guide to [performing a clean boot on Windows](https://www.makeuseof.com/how-perform-clean-boot-windows-10/) provides step-by-step instructions for how you can disable those startup items with Task Manager and System Configuration.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-services-tab3.jpg)

 When you’ve set the clean boot, restart Windows and right-click on the desktop to see if the context menu works ok. If it does, then it’s probably better to leave the boot configuration as set. However, you can try to identify what program or service was causing the issue by gradually re-enabling disabled startup apps and services until the context menu stops working again.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 9\. Disable Third-Party Context Menu Shell Extensions With CCleaner

 You can also directly select to turn off third-party shell extensions included in the startup that might be causing context menu issues with CCleaner. So, try turning off superfluous context menu add-ons with that software as follows:

1. Go to the [CCleaner website](https://www.anrdoezrs.net/links/7251228/type/dlg/sid/UUmuoUeUpU2027967/https://www.ccleaner.com/ccleaner/download?ppc%5Fcode=012&ppc=a&gclsrc=aw.ds&gclid=CjwKCAjwtuOlBhBREiwA7agf1ofUbIfUK8X-GzUG-CBD%5F%5F1dyp8qqSnTPOOlQqX1d7ocUDK5BxqH-hoCw1oQAvD%5FBwE) and click **Free Download** there.
2. Activate File Explorer (simultaneously press **Win + E**) and navigate to the folder that includes the downloaded CCleaner setup file.
3. Double-click **ccsetup614.exe** to start the setup wizard.
4. Select **Install** to add the software with default installation settings.  
![The Install option for CCleaner](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-install-button.jpg)
5. Open CCleaner and click its **Tools** tab.
6. Click the **Startup** and **Context Menu** tabs.
7. Look at the Program column to identify third-party shell extensions listed there.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
![The Context Menu tab in CCleaner](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-context-menu-tab-in-cccleaner.jpg)
8. Select third-party shell extensions and click **Disable** to turn them off.

## Get the Desktop Context Menu Fixed With These Resolutions

 The troubleshooting methods above are quite thorough and will likely resolve most Windows context menu issues. Lots of users have been able to fix the context menu not working by applying the registry tweak solutions.

 If the potential solutions here don’t work for you, you may need to try something more drastic, like resetting Windows or performing an in-place upgrade reinstallation.

 Although desktop context menu access is seldom essential, it offers handy shortcuts, especially when you've customized it. So, it’s important to fix the desktop context menu when it’s not working. If your Windows desktop context menu isn’t functioning right, try applying the troubleshooting methods below.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-blog.techidaily.com/024-approved-navigating-youtube-for-ultimate-virtual-reality-adventures/"><u>[New] 2024 Approved  Navigating YouTube for Ultimate Virtual Reality Adventures</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-tailoring-your-content-for-split-screen-audiences-via-facebook-lives/"><u>[New] 2024 Approved  Tailoring Your Content for Split Screen Audiences via Facebook Lives</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-clandestine-watching-of-stories-by-the-best-5-apps/"><u>[New] Clandestine Watching of Stories by the Best 5 Apps</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-the-art-of-cross-platform-content-sharing-for-2024/"><u>[New] The Art of Cross-Platform Content Sharing for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-screen-recording-for-professionals-choosing-between-bandicam-and-camtasia/"><u>[Updated] 2024 Approved  Screen Recording for Professionals  Choosing Between Bandicam & Camtasia</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-free-to-download-movie-cast-releases/"><u>[Updated] Free-to-Download Movie Cast Releases</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-x-master-recorder-software-pc-edition/"><u>[Updated] In 2024, X-Master Recorder Software, PC Edition</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-unveiling-premium-screen-recorders-in-tech/"><u>[Updated] Unveiling Premium Screen Recorders in Tech</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-game-masters-and-youtube-earning-strategies/"><u>2024 Approved  Game Masters & YouTube Earning Strategies</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-leveraging-obs-for-high-quality-livestreams-youtube-and-twitch/"><u>2024 Approved  Leveraging OBS for High-Quality Livestreams, YouTube & Twitch</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-photo-text-editing-made-simple-tools-and-techniques/"><u>2024 Approved  Photo Text Editing Made Simple  Tools & Techniques</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/-money-making-moves-for-youtube-rookies/"><u>8 Key Money-Making Moves for YouTube Rookies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/approaches-to-addressing-critical-app-issues/"><u>Approaches to Addressing Critical App Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configure-touch-input-in-windows-enabledisable-steps/"><u>Configure Touch Input in Windows: Enable/Disable Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-methods-for-repairing-nonfunctional-itunes-on-windows/"><u>Efficient Methods for Repairing Nonfunctional iTunes on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-crashing-file-explorer-on-windows-11-now/"><u>Fix Crashing File Explorer on Windows 11 Now</u></a></li>
<li><a href="https://program-issues.techidaily.com/ghostwire-tokyo-overcoming-persistent-pc-malfunctions-and-crashes/"><u>Ghostwire: Tokyo - Overcoming Persistent PC Malfunctions and Crashes</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-full-guide-to-unlock-your-itel-a70-by-drfone-android/"><u>In 2024, Full Guide to Unlock Your Itel A70</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-hardware-controls-quick-keys-for-windows-disk-editor-entrance/"><u>Master Hardware Controls: Quick Keys for Windows Disk Editor Entrance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-removing-window-search-artifacts/"><u>Mastery Over Removing Window Search Artifacts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-windows-barriers-to-download-icloud-immediately/"><u>Overcome Windows' Barriers to Download iCloud Immediately</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-challenge-of-restarting-windows-sound-on-booting/"><u>Overcoming the Challenge of Restarting Windows Sound on Booting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/portable-apps-integration-guide-for-w11/"><u>Portable Apps Integration Guide for W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-leaks-auto-shutdown-at-low-activity-windows-11-style/"><u>Preventing Leaks: Auto-Shutdown at Low Activity, Windows 11 Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-discrepancies-in-computers-processor-utilization/"><u>Resolving Discrepancies in Computers' Processor Utilization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-error-code-30015-26-in-m365-for-windows-computers/"><u>Resolving Error Code 30015-26 in M365 for Windows Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-widespread-connectivity-problem-in-steam-windows-11/"><u>Resolving Widespread Connectivity Problem in Steam Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-system-space-essential-windows-extras-for-elimination/"><u>Revamp Your System Space: Essential Windows Extras for Elimination</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stay-connected-tips-for-disabling-usb-power-save-mode/"><u>Stay Connected - Tips for Disabling USB Power Save Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-browsing-efficiency-on-windows/"><u>Streamlining Browsing Efficiency on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-path-to-reinstating-default-windows-backups/"><u>The Path to Reinstating Default Windows Backups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-role-of-windows-11-in-software-installation-harmony/"><u>The Role of Windows 11 in Software Installation Harmony</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trouble-locating-astra-pilot-help-for-windows-11-pcs/"><u>Trouble Locating Astra Pilot? Help For Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-missing-5ghz-network-on-windows-11-top-7-solutions/"><u>Troubleshoot Missing 5GHz Network on Windows 11: Top 7 Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-your-windows-11-integrating-cutting-edge-run-commands/"><u>Upgrade Your Windows 11: Integrating Cutting-Edge Run Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-folder-customization-adding-movecopy-context-functionality/"><u>Windows 11 Folder Customization - Adding Move/Copy Context Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/your-ultimate-toolkit-to-counteract-bsod-on-win10/"><u>Your Ultimate Toolkit to Counteract BSOD on Win10</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>