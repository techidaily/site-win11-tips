---
title: Address 'Unsigned' Files Issue for Updated PCs
date: 2024-08-16T01:11:19.147Z
updated: 2024-08-17T01:11:19.147Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Address 'Unsigned' Files Issue for Updated PCs
excerpt: This Article Describes Address 'Unsigned' Files Issue for Updated PCs
keywords: Fix Unsigned Update Error,Address PC Update Issues,Resolve File Signature Problems,Handle New PC Signatures,Cure Updated Software Fails,Solve Upgraded PC Snags,Correct PC Files Not Verified
thumbnail: https://thmb.techidaily.com/1155b908ebc8fe078487b3227b97ba044636fc4713be9d07ea00e7f8a9937936.jpeg
---

## Address 'Unsigned' Files Issue for Updated PCs

 Users frequently report Windows 11/10 update errors on software support forums. One such update issue reported is an error message that says, “Some update files aren’t signed.” Some users see that error message appear within Settings’ Windows Update tab when trying to update Windows.

 Windows updates fail to install when this issue occurs. This error usually includes either a 0x800b0109 or 0x800b0100 code after its message. This is how you can resolve the “Some update files aren’t signed” error 0x800b0109 on a Windows 11/10 PC.

## 1\. Utilize the Windows Update Troubleshooter

 The Windows Update troubleshooting tool is there to help you fix any issues encountered when trying to update Windows 11/10\. That troubleshooter doesn’t necessarily fix every update error, but it can at least resolve some issues.

 So, utilizing that troubleshooter is always worth a try, which you can access in Settings as covered within this guide to [running any troubleshooter on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/).

![The Windows Update troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-update-troubleshooter.jpg)

## 2\. Run Deployment Imaging and System File Scans

 System file corruption is among the [most common reasons for Windows update errors](https://www.makeuseof.com/reasons-why-windows-updates-fail/). For that reason, running a System File Checker scan to address system file corruption is a recommended troubleshooting method for error 0x800b0109\.

 It’s also advisable to utilize the Deployment Imaging and Servicing Management to repair possible Windows image corruption.

 Both Deployment Imaging and System File Checker are Command Prompt tools. You can run them by inputting and executing two commands within the Command Prompt. Our article on [repairing corrupted Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) includes instructions on how to utilize the SFC and DISM command-line tools.

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-sfc-scannow.jpg)

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Check the Windows Update and BITS Services Are Enabled

 Windows Updates and Background Intelligent Transfer Service (BITS) are two services that need to be enabled for updates. So, check those services are correctly set like this:

1. Simultaneously press the **Windows** logo + **S** keys on your keyboard.
2. Enter the search phrase "services" to find the app with a matching title.
3. Click on **Services** inside the search results.
4. Double-click **Windows Update** to access settings for that service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/services-window.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
5. Set the **Startup type** setting to the **Automatic** option.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/startup-type-drop-down-menu.jpg)
6. Click **Start** (inside the properties windows) to run the Windows Update service.
7. Save the settings by pressing the **Apply** and **OK** buttons.
8. Double-click the **Background Intelligent Transfer Service** to view its settings.
9. Select a **Manual** startup option.
10. Click the **Start** option for the BITS service if it’s stopped.
11. Then click on the **Apply** and **OK** options to set that service’s options.

 If you find both services to be already enabled and running, try restarting them. You can do so by right-clicking the BITS and Windows Update service names and selecting a **Restart** option on their context menus.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
## 4\. Reset Components for Windows Updates

 Resetting components for Windows updates will completely refresh the catroot2 and SoftwareDistribution folders, which store update data. This troubleshooting method also reregisters all DLL files for important update services. Applying such a potential resolution can fix corrupted components causing error 0x800b0109\.

 To apply this possible error 0x800b0109 resolution, check out our article on [resetting Windows update components](https://www.makeuseof.com/reset-windows-update-components/). That guide includes a command-line and batch file method. Creating and running a batch file is the quicker and more straightforward way to reset Windows update components.

## 5\. Deactivate Third-Party Security Software

 A third-party security (antivirus) app can potentially conflict with Windows update processes. This can happen when the antivirus protection of a security app locks files needed by Windows Update. It’s not something that happens often, but temporarily disable any third-party antivirus protection on your PC just in case.

 Security apps typically include options for disabling antivirus protection on their system tray context menus. Right-click your security app’s icon in Windows 11’s system tray area to find and select its option for temporarily disabling the antivirus shield. Then, return to the Settings app to see if error 0x800b0109 still happens with the antivirus shield disabled.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->

## 6\. Erase the Windows Update Key

 Deleting the Windows Update registry key is a potential resolution some users confirm to fix error 0x800b0109\. However, we always recommend [backing up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or saving a system restoration point before deleting registry keys.

 When you’ve done that, try deleting the Windows Update key like this:

1. Open Run, accessible by pressing **Windows** logo key + **R**, and type a **regedit** command into that accessory.
2. Select Run’s **OK** option to open the Registry Editor.
3. Next, clear the registry address bar and input this key path there:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\WindowsUpdate`
4. Right-click the WindowsUpdate registry key to select **Delete**.  
![The Delete context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-delete-option-1.jpg)
5. Click **Yes** when prompted for confirmation to delete the key.  
![The Confirm Key Delete prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-key-confirmation-1.jpg)

 Thereafter, it’s also recommended to restart the Windows Update and BITS services. To do so, open Services as covered in the first three steps of resolution three. Then, select the **Restart** context menu options for Windows Update and BITS.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Try Downloading the Failed Update From Microsoft Update Catalog

 If error 0x800b0109 still isn’t fixed after applying the potential resolutions above, try going around it by manually downloading the affected update from [Microsoft Update Catalog](https://www.catalog.update.microsoft.com/Home.aspx). Then, you can install the update with an MSU file downloaded from there.

 You will first need to identify what update is failing as follows:

1. Simultaneously press your keyboard’s **Windows** logo + **I** keys to access Settings.
2. Click **Windows Update** (or **Update & Security**) in Settings.
3. Select **Update history** to view installed and failed updates.  
![The update history in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-history4.jpg)
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Note down the KB code for your recently failed Windows update.

 Then, you can find and download that failed update on the Microsoft Update Catalog website. This article about [updating Windows manually](https://www.makeuseof.com/update-windows-manually/) includes instructions for utilizing the Microsoft Update Catalog.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
## 8\. Apply an In-Place Windows Upgrade

 An in-place Windows upgrade is the last resort for fixing error 0x800b0109\. Applying this potential resolution will reinstall Windows on your PC with its latest ISO file. The installation of a fresh Windows copy will likely resolve other issues causing the 0x800b0109 update error that other potential solutions couldn’t fix.

 The good thing about an in-place upgrade is that it won’t eradicate your installed software or user files. This [how-to perform an in-place upgrade](https://www.makeuseof.com/in-place-upgrade-windows-11/) guide tells you how to apply this potential solution for Windows 11\. The steps are quite similar for Windows 10, but you’ll need to download its ISO with the Media Creation Tool available on this [Microsoft page](https://www.microsoft.com/en-gb/software-download/windows10).

![The Windows 10 Media Creation tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-10-setup-window.jpg)
<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Windows Updated Again

 There isn’t a surefire way to fix error 0x800b0109 since there are varied possible reasons for that Windows 11/10 issue occurring. However, it’s likely at least one of the eight potential resolutions in this guide will fix that update issue on your PC.

 Some of the best third-party Windows repair tools might also be helpful for resolving the “Some update files aren’t signed” error.

 Windows updates fail to install when this issue occurs. This error usually includes either a 0x800b0109 or 0x800b0100 code after its message. This is how you can resolve the “Some update files aren’t signed” error 0x800b0109 on a Windows 11/10 PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-exclusive-review-10-best-free-video-meeting-apps-iosandroid/"><u>[New] 2024 Approved  Exclusive Review  10 Best Free Video Meeting Apps iOS/Android</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-efficient-tools-seamless-extraction-of-vimeo-media-for-2024/"><u>[New] Efficient Tools  Seamless Extraction of Vimeo Media for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-livestream-grabber-by-fb/"><u>[New] In 2024, LiveStream Grabber by FB</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-how-to-instantly-design-custom-coverage-for-your-short-videos/"><u>[Updated] In 2024, How To Instantly Design Custom Coverage For Your Short Videos</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-precision-editing-in-photopea-sculpting-cleaner-visual-space/"><u>[Updated] Precision Editing in Photopea  Sculpting Cleaner Visual Space</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-maximum-clarity-video-transformer-windowsmac/"><u>2024 Approved  Maximum Clarity Video Transformer (Windows/Mac)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-approach-to-using-and-revoking-windows-terminal-focus/"><u>A Practical Approach to Using & Revoking Windows Terminal Focus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-tactics-removing-onedrive-in-file-explorer-window/"><u>Avoidance Tactics: Removing OneDrive in File Explorer Window</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathing-life-into-your-inactive-windows-11-wi-fi-hotspot/"><u>Breathing Life Into Your Inactive Windows 11 Wi-Fi Hotspot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/changing-windows-security-pin-made-simple/"><u>Changing Windows Security PIN Made Simple</u></a></li>
<li><a href="https://win11-tips.techidaily.com/circumventing-the-failed-to-launch-lunar-client-windows-message/"><u>Circumventing the Failed to Launch: Lunar Client Windows Message</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/comprehensive-strategies-to-drop-multiple-geo-tags-in-google-maps/"><u>Comprehensive Strategies to Drop Multiple Geo-Tags in Google Maps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-the-task-of-installing-gmaps-on-windows/"><u>Conquering the Task of Installing GMaps on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/determine-disk-technology-in-windows-1011/"><u>Determine Disk Technology in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-not-empty-assertion-a-practical-guide-to-x80070091-fixes/"><u>Disabling 'Not Empty' Assertion: A Practical Guide to X80070091 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-windows-11-key-combinations-for-screenshot-taking/"><u>Discover Windows 11 Key Combinations for Screenshot Taking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719218779653-expert-tips-reinstating-functionality-of-wwinplusp-in-os/"><u>Expert Tips: Reinstating Functionality of WWin+P in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-actions-and-activation-labels-in-dev-tools/"><u>Exploring Actions & Activation Labels in Dev Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-11-mail-tips-for-resolving-html-code-displays-in-emails/"><u>Fixing Windows 11 Mail: Tips for Resolving HTML Code Displays in Emails</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/forgot-apple-iphone-14-pro-backup-password-heres-what-to-do-drfone-by-drfone-ios/"><u>Forgot Apple iPhone 14 Pro Backup Password? Heres What to Do | Dr.fone</u></a></li>
<li><a href="https://fox-that.techidaily.com/how-to-completely-restore-your-apple-device-settings-iphoneipad/"><u>How To Completely Restore Your Apple Device Settings (iPhone/iPad)</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-xiaomi-redmi-k70-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Xiaomi Redmi K70 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reactivate-an-inactive-windows-11-license/"><u>How to Reactivate an Inactive Windows 11 License</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-after-format-on-poco-c65-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos from Android Gallery after format on Poco C65</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-swiftly-clear-windows-cached-data/"><u>How to Swiftly Clear Windows' Cached Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tackle-the-windows-exception-breaking-point-issue/"><u>How to Tackle the Windows Exception Breaking Point Issue</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-detailed-guide-on-removing-apple-iphone-14-pro-activation-lock-without-previous-owner-by-drfone-ios/"><u>In 2024, Detailed Guide on Removing Apple iPhone 14 Pro Activation Lock without Previous Owner?</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-peering-into-triller-its-distinctive-features-and-identity/"><u>In 2024, Peering Into Triller  Its Distinctive Features and Identity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/introducing-ad-free-innovation-windows-11s-modernized-start/"><u>Introducing Ad-Free Innovation: Windows 11'S Modernized Start</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-prevent-windowed-app-relocations/"><u>Methods to Prevent Windowed App Relocations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-winscomrssvsvc-error-on-initial-startup/"><u>Mitigating WinscomrssvSvc Error on Initial Startup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-wi-fi-setup-woes-reconciling-missing-steps-in-prompts/"><u>Navigating Wi-Fi Setup Woes: Reconciling Missing Steps in Prompts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overhauling-your-operating-systems-state-a-windows-1011-reboot-guide/"><u>Overhauling Your Operating System's State: A Windows 10/11 Reboot Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectify-restore-responsive-shortcut-keys-in-windows-11/"><u>Rectify: Restore Responsive Shortcut Keys in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rushing-past-stuck-warcraft-64-patches/"><u>Rushing Past Stuck Warcraft 6.4 Patches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safe-stepping-stones-on-windows-11-top-8-to-skip/"><u>Safe Stepping Stones on Windows 11: Top 8 To Skip</u></a></li>
<li><a href="https://win11-tips.techidaily.com/smooth-switch-the-best-windows-apps-for-ex-mac-users/"><u>Smooth Switch: The Best Windows Apps for Ex-Mac Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-reactivate-deactivated-windows-email-rule-settings/"><u>Steps to Reactivate Deactivated Windows Email Rule Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-rebuilding-windows-icons/"><u>Strategies for Rebuilding Windows Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-resolve-the-blue-screen-error-code-0x8007007e/"><u>Strategies to Resolve the Blue Screen Error: Code 0X8007007E</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-error-1152-temporary-file-extract-failure/"><u>Tackling 'Error 1152: Temporary File Extract Failure'</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-win11-ui-with-enlarged-icons/"><u>Transform Your Win11 UI with Enlarged Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transition-trio-top-apps-making-pc-switch-easier/"><u>Transition Trio: Top Apps Making PC Switch Easier</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719284663391-version-compatibility/"><u>Version Compatibility:</u></a></li>
</ul></div>
