---
title: Troubleshooting 'Not Signed' Update Problem in Win11/Win10
date: 2024-08-16T02:11:49.344Z
updated: 2024-08-17T02:11:49.344Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting 'Not Signed' Update Problem in Win11/Win10
excerpt: This Article Describes Troubleshooting 'Not Signed' Update Problem in Win11/Win10
keywords: Windows Update Issue Fix,Win10 Unsigned Error Resolve,Win11 Signature Troubleshoot,System Updates 'Not Signed' Guide,Resolving Update Validation Fail,Microsoft OS Update Signing Fix,Windows 10/11 'Unsigned' Solution
thumbnail: https://thmb.techidaily.com/3b3d53f3a3456319783aa99ca770516fad2e58dbe2bd45f2ec6f3eb305fb3d58.png
---

## Troubleshooting 'Not Signed' Update Problem in Win11/Win10

 Users frequently report Windows 11/10 update errors on software support forums. One such update issue reported is an error message that says, “Some update files aren’t signed.” Some users see that error message appear within Settings’ Windows Update tab when trying to update Windows.

 Windows updates fail to install when this issue occurs. This error usually includes either a 0x800b0109 or 0x800b0100 code after its message. This is how you can resolve the “Some update files aren’t signed” error 0x800b0109 on a Windows 11/10 PC.

## 1\. Utilize the Windows Update Troubleshooter

 The Windows Update troubleshooting tool is there to help you fix any issues encountered when trying to update Windows 11/10\. That troubleshooter doesn’t necessarily fix every update error, but it can at least resolve some issues.

 So, utilizing that troubleshooter is always worth a try, which you can access in Settings as covered within this guide to [running any troubleshooter on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/).

![The Windows Update troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-update-troubleshooter.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
## 2\. Run Deployment Imaging and System File Scans

 System file corruption is among the [most common reasons for Windows update errors](https://www.makeuseof.com/reasons-why-windows-updates-fail/). For that reason, running a System File Checker scan to address system file corruption is a recommended troubleshooting method for error 0x800b0109\.

 It’s also advisable to utilize the Deployment Imaging and Servicing Management to repair possible Windows image corruption.

 Both Deployment Imaging and System File Checker are Command Prompt tools. You can run them by inputting and executing two commands within the Command Prompt. Our article on [repairing corrupted Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) includes instructions on how to utilize the SFC and DISM command-line tools.

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-sfc-scannow.jpg)

## 3\. Check the Windows Update and BITS Services Are Enabled

 Windows Updates and Background Intelligent Transfer Service (BITS) are two services that need to be enabled for updates. So, check those services are correctly set like this:

1. Simultaneously press the **Windows** logo + **S** keys on your keyboard.
2. Enter the search phrase "services" to find the app with a matching title.
3. Click on **Services** inside the search results.
4. Double-click **Windows Update** to access settings for that service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/services-window.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
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
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Reset Components for Windows Updates

 Resetting components for Windows updates will completely refresh the catroot2 and SoftwareDistribution folders, which store update data. This troubleshooting method also reregisters all DLL files for important update services. Applying such a potential resolution can fix corrupted components causing error 0x800b0109\.

 To apply this possible error 0x800b0109 resolution, check out our article on [resetting Windows update components](https://www.makeuseof.com/reset-windows-update-components/). That guide includes a command-line and batch file method. Creating and running a batch file is the quicker and more straightforward way to reset Windows update components.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Deactivate Third-Party Security Software

 A third-party security (antivirus) app can potentially conflict with Windows update processes. This can happen when the antivirus protection of a security app locks files needed by Windows Update. It’s not something that happens often, but temporarily disable any third-party antivirus protection on your PC just in case.

 Security apps typically include options for disabling antivirus protection on their system tray context menus. Right-click your security app’s icon in Windows 11’s system tray area to find and select its option for temporarily disabling the antivirus shield. Then, return to the Settings app to see if error 0x800b0109 still happens with the antivirus shield disabled.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Click **Yes** when prompted for confirmation to delete the key.  
![The Confirm Key Delete prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-key-confirmation-1.jpg)
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Thereafter, it’s also recommended to restart the Windows Update and BITS services. To do so, open Services as covered in the first three steps of resolution three. Then, select the **Restart** context menu options for Windows Update and BITS.

## 7\. Try Downloading the Failed Update From Microsoft Update Catalog

 If error 0x800b0109 still isn’t fixed after applying the potential resolutions above, try going around it by manually downloading the affected update from [Microsoft Update Catalog](https://www.catalog.update.microsoft.com/Home.aspx). Then, you can install the update with an MSU file downloaded from there.

 You will first need to identify what update is failing as follows:

1. Simultaneously press your keyboard’s **Windows** logo + **I** keys to access Settings.
2. Click **Windows Update** (or **Update & Security**) in Settings.
3. Select **Update history** to view installed and failed updates.  
![The update history in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-history4.jpg)
4. Note down the KB code for your recently failed Windows update.

 Then, you can find and download that failed update on the Microsoft Update Catalog website. This article about [updating Windows manually](https://www.makeuseof.com/update-windows-manually/) includes instructions for utilizing the Microsoft Update Catalog.

## 8\. Apply an In-Place Windows Upgrade

 An in-place Windows upgrade is the last resort for fixing error 0x800b0109\. Applying this potential resolution will reinstall Windows on your PC with its latest ISO file. The installation of a fresh Windows copy will likely resolve other issues causing the 0x800b0109 update error that other potential solutions couldn’t fix.

 The good thing about an in-place upgrade is that it won’t eradicate your installed software or user files. This [how-to perform an in-place upgrade](https://www.makeuseof.com/in-place-upgrade-windows-11/) guide tells you how to apply this potential solution for Windows 11\. The steps are quite similar for Windows 10, but you’ll need to download its ISO with the Media Creation Tool available on this [Microsoft page](https://www.microsoft.com/en-gb/software-download/windows10).

![The Windows 10 Media Creation tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-10-setup-window.jpg)

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
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
<li><a href="https://extra-lessons.techidaily.com/new-27-significant-metaverse-demonstrations-unveiled/"><u>[New] 27 Significant Metaverse Demonstrations Unveiled</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-engaging-audiences-perfecting-the-art-of-igtv-titles-and-summaries/"><u>[New] Engaging Audiences  Perfecting the Art of IGTV Titles & Summaries</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-skype-recording-procedures-streamlined-techniques-for-windows-and-os-x/"><u>[Updated] 2024 Approved  Skype Recording Procedures - Streamlined Techniques for Windows & OS X</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-efficient-ad-elimination-select-7-android-adblockers-for-2024/"><u>[Updated] Efficient Ad Elimination  Select 7 Android AdBlockers for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-how-to-screen-capture-high-quality-snaps-with-ease/"><u>[Updated] How to Screen-Capture High-Quality Snaps with Ease</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-nextgen-tv-including-the-best-local-channels-online/"><u>[Updated] NextGen TV  Including the Best Local Channels Online</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-automating-video-display-in-facebook-feeds/"><u>2024 Approved  Automating Video Display in Facebook Feeds</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-implementing-invisible-sound-transitions-in-premiere-pro/"><u>2024 Approved  Implementing Invisible Sound Transitions in Premiere Pro</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-navigating-microsoft-azure-for-text-conversion/"><u>2024 Approved  Navigating Microsoft Azure for Text Conversion</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/8-persuasive-reasons-for-educators-to-embrace-ai/"><u>8 Persuasive Reasons for Educators to Embrace AI</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/a-guide-to-the-finest-apps-for-instagram-reel-creation/"><u>A Guide to the Finest Apps for Instagram Reel Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-disrupted-microphone-input-in-valorant-windows/"><u>Addressing Disrupted Microphone Input in Valorant (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-admin-username-on-windows-11-step-by-step-guide/"><u>Altering Admin Username on Windows 11: Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-language-skills-using-windows-1011-hotkeys/"><u>Boost Your Language Skills Using Windows 10/11 Hotkeys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breakdown-of-microsofts-earnings-through-windows-11/"><u>Breakdown of Microsoft's Earnings Through Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-no-wi-fi-in-windows-network/"><u>Breaking Down No Wi-Fi in Windows Network</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-through-windows-11-theme-barriers-using-registry/"><u>Breaking Through Windows 11 Theme Barriers Using Registry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-a-secure-quick-launch-button-for-hardware-removal/"><u>Creating a Secure, Quick-Launch Button for Hardware Removal</u></a></li>
<li><a href="https://win-solutions.techidaily.com/deathloop-release-woes-heres-how-you-can-overcome-them/"><u>Deathloop Release Woes? Here's How You Can Overcome Them!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diminish-noise-restoring-your-keys-sound-functionality/"><u>Diminish Noise: Restoring Your Key's Sound Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-reasons-to-never-turn-off-your-windows-11-push-notifications/"><u>Discover Reasons to Never Turn Off Your Windows 11 Push Notifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-device-safety-increase-win11-pin-length/"><u>Elevate Your Device Safety: Increase Win11 PIN Length</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-file-sharing-capabilities-in-geforce/"><u>Enhancing File-Sharing Capabilities in GeForce</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-11-taskbar-responsiveness/"><u>Enhancing Windows 11 Taskbar Responsiveness</u></a></li>
<li><a href="https://games-able.techidaily.com/entertainment-evolution-showdown-ps5-vs-thrifty-computer-setup/"><u>Entertainment Evolution Showdown: PS5 vs Thrifty Computer Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-to-updating-username-on-windows-11/"><u>Essential Guide to Updating Username on Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-music-files-from-itel-s23-by-fonelab-android-recover-music/"><u>How To  Restore Missing Music Files from Itel S23</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-netflix-location-to-get-more-country-version-on-realme-c53-drfone-by-drfone-virtual-android/"><u>How to Change Netflix Location to Get More Country Version On Realme C53 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-cut-down-on-menus-in-windows-11/"><u>How to Cut Down on Menus in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reactivate-a-nonfunctional-nvidia-cp-on-windows-11/"><u>How to Reactivate a Nonfunctional Nvidia CP on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-spot-and-dismantle-unused-windows-folders-easily/"><u>How to Spot & Dismantle Unused Windows Folders Easily</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-vivo-y28-5g-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Vivo Y28 5G to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-expertise-for-changing-meet-usernames-laptopmobile/"><u>In 2024, Expertise for Changing Meet Usernames (Laptop/Mobile)</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-quicker-scaling-ensure-perfect-youtubemac-ratios/"><u>In 2024, Quicker Scaling  Ensure Perfect Youtube/Mac Ratios</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-streamline-your-academic-notes-mac-recording-guide/"><u>In 2024, Streamline Your Academic Notes  MAC Recording Guide</u></a></li>
<li><a href="https://fox-info.techidaily.com/incandescent-ideas-innovations-for-stellar-cinematography-for-2024/"><u>Incandescent Ideas  Innovations for Stellar Cinematography for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/incorporating-external-disk-into-explorer-nav-pane/"><u>Incorporating External Disk Into Explorer Nav Pane</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-the-dxgidll-file-missing-in-windows-11-heres-how-to-fix-it/"><u>Is the Dxgi.dll File Missing in Windows 11? Here's How to Fix It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-disabling-xbox-game-pass-error/"><u>Mastering the Art of Disabling Xbox Game Pass Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-terminal-configuration-basics/"><u>Mastering Windows Terminal Configuration Basics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-mouse-controls-in-win11-effortlessly/"><u>Navigating Mouse Controls in Win11 Effortlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-depths-of-diablos-first-adventure/"><u>Navigating the Depths of Diablo's First Adventure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/power-up-your-device-instantly-mastering-win-11s-double-clicked-apk-method/"><u>Power Up Your Device Instantly: Mastering Win 11'S Double-Clicked APK Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/put-a-halt-on-application-start-tracking-in-windows/"><u>Put a Halt on Application Start-Tracking in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-your-lost-dxgidll-with-these-win11-hacks/"><u>Restore Your Lost Dxgi.dll with These Win11 Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-initiate-sfc-process-in-windows-1087/"><u>Steps to Initiate SFC Process in Windows 10/8/7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-tackling-windows-1011-interrupt-crashes/"><u>Strategies for Tackling Windows 10/11 INTERRUPT Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-file-denial-in-steam-for-windows-11-users/"><u>Tackling File Denial in Steam for Windows 11 Users</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-art-of-testimonials-techniques-for-persuasive-video-credibility/"><u>The Art of Testimonials  Techniques for Persuasive Video Credibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-hidden-pathways-open-directory-games-in-windows/"><u>The Hidden Pathways: Open Directory Games in Windows</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/the-most-useful-tips-for-pokemon-go-ultra-league-on-apple-iphone-7-plus-drfone-by-drfone-virtual-ios/"><u>The Most Useful Tips for Pokemon Go Ultra League On Apple iPhone 7 Plus | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/tips-to-find-the-best-videographer/"><u>Tips to Find The Best Videographer</u></a></li>
<li><a href="https://driver-install.techidaily.com/tp-link-usb-wi-fi-adapter-windows-get-it-free-today/"><u>TP Link USB Wi-Fi Adapter: Windows, Get It Free Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-your-mouse-icon-with-ease-on-win-os/"><u>Transforming Your Mouse Icon with Ease on Win OS</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/value-flight-in-depth-analysis-of-holy-stones-hs170-predator-mini-drone/"><u>Value Flight: In-Depth Analysis of Holy Stone's HS170 Predator Mini Drone</u></a></li>
</ul></div>
