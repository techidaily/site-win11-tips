---
title: Strategies for Removing Signature Rejection on PCs
date: 2024-07-12T17:40:37.083Z
updated: 2024-07-13T17:40:37.083Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies for Removing Signature Rejection on PCs
excerpt: This Article Describes Strategies for Removing Signature Rejection on PCs
keywords: Remove Signature Denial,Signatures Accepted PC,PC Signature Acceptance,Deny Signature Removal,Accept Signatures Fix,Rejected Sigs on PC,Clear Rejection Issues PC
thumbnail: https://thmb.techidaily.com/b55c24263d5a9a2d0075e95ed2cba33cc134d0a45b0aad772e33e1d818e77a97.jpg
---

## Strategies for Removing Signature Rejection on PCs

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

## 3\. Check the Windows Update and BITS Services Are Enabled

 Windows Updates and Background Intelligent Transfer Service (BITS) are two services that need to be enabled for updates. So, check those services are correctly set like this:

1. Simultaneously press the **Windows** logo + **S** keys on your keyboard.
2. Enter the search phrase "services" to find the app with a matching title.
3. Click on **Services** inside the search results.
4. Double-click **Windows Update** to access settings for that service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/services-window.jpg)
5. Set the **Startup type** setting to the **Automatic** option.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/startup-type-drop-down-menu.jpg)
6. Click **Start** (inside the properties windows) to run the Windows Update service.
7. Save the settings by pressing the **Apply** and **OK** buttons.
8. Double-click the **Background Intelligent Transfer Service** to view its settings.
9. Select a **Manual** startup option.
10. Click the **Start** option for the BITS service if it’s stopped.
11. Then click on the **Apply** and **OK** options to set that service’s options.

 If you find both services to be already enabled and running, try restarting them. You can do so by right-clicking the BITS and Windows Update service names and selecting a **Restart** option on their context menus.

## 4\. Reset Components for Windows Updates

 Resetting components for Windows updates will completely refresh the catroot2 and SoftwareDistribution folders, which store update data. This troubleshooting method also reregisters all DLL files for important update services. Applying such a potential resolution can fix corrupted components causing error 0x800b0109\.

 To apply this possible error 0x800b0109 resolution, check out our article on [resetting Windows update components](https://www.makeuseof.com/reset-windows-update-components/). That guide includes a command-line and batch file method. Creating and running a batch file is the quicker and more straightforward way to reset Windows update components.

## 5\. Deactivate Third-Party Security Software

 A third-party security (antivirus) app can potentially conflict with Windows update processes. This can happen when the antivirus protection of a security app locks files needed by Windows Update. It’s not something that happens often, but temporarily disable any third-party antivirus protection on your PC just in case.

 Security apps typically include options for disabling antivirus protection on their system tray context menus. Right-click your security app’s icon in Windows 11’s system tray area to find and select its option for temporarily disabling the antivirus shield. Then, return to the Settings app to see if error 0x800b0109 still happens with the antivirus shield disabled.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

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
<li><a href="https://some-guidance.techidaily.com/2024-approved-tailor-made-downloads-selecting-your-perfect-4k-app/"><u>2024 Approved  Tailor-Made Downloads  Selecting Your Perfect 4K App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-expanded-pinned-area-on-windows-11-ui/"><u>Techniques for Expanded Pinned Area on Windows 11 UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-auto-recommended-games-in-windows-11/"><u>Cease Auto-Recommended Games in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-xbox-mic-malfunctions-in-windows-os/"><u>Overcoming Xbox Mic Malfunctions in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-intel-unison-for-windows-11-calling/"><u>The Ultimate Guide to Intel Unison for Windows 11 Calling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rejoining-fall-guys-fixing-connectivity-issues-on-pc/"><u>Rejoining Fall Guys: Fixing Connectivity Issues on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-unsuited-file-vlc-problem/"><u>Overcoming Windows' 'Unsuited File' VLC Problem</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-free-video-hosting-solutions-10-best-options-for-individuals-and-businesses-for-2024/"><u>Updated Free Video Hosting Solutions 10 Best Options for Individuals and Businesses for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-the-non-verified-error-during-windows-file-installation/"><u>Solving the Non-Verified Error During Windows File Installation</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-methods-to-change-gps-location-on-vivo-x-flip-drfone-by-drfone-virtual-android/"><u>In 2024, Methods to Change GPS Location On Vivo X Flip | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11-display-options-with-these-10-tips/"><u>Unlocking Windows 11 Display Options with These 10 Tips</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-7-ways-to-unlock-a-locked-poco-m6-pro-5g-phone-by-drfone-android/"><u>In 2024, 7 Ways to Unlock a Locked Poco M6 Pro 5G Phone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-perfecting-visual-output-incorporating-luts-into-your-ae-projects/"><u>In 2024, Perfecting Visual Output  Incorporating LUTs Into Your AE Projects</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-infinix-smart-8-hd-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Infinix Smart 8 HD via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/smart-solutions-apply-apple-watch-open-mac-for-2024/"><u>Smart Solutions  Apply Apple Watch, Open Mac for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-guide-to-managing-win11-applications-via-winget/"><u>The Complete Guide to Managing Win11 Applications via Winget</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-system-tray-and-secret-icons-in-win11/"><u>Decoding System Tray & Secret Icons in Win11</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-the-ultimate-checklist-to-successful-video-marketing-with-tags/"><u>[New] 2024 Approved  The Ultimate Checklist to Successful Video Marketing with Tags</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-d3dx939dll-loss-in-windows-11/"><u>Resolving D3DX9_39.dll Loss in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-microsofts-ai-assistive-functions/"><u>Understanding Microsoft's AI Assistive Functions</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-check-distance-and-radius-on-google-maps-for-your-nokia-c210-drfone-by-drfone-virtual-android/"><u>How to Check Distance and Radius on Google Maps For your Nokia C210 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-windows-methods-to-identify-system-gadgets/"><u>Proven Windows Methods to Identify System Gadgets</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-videos-look-better-when-edited-professionally-if-youre-looking-to-edit-recorded-video-with-a-pro-level-editing-then-weve-got-you-covered-learn-about/"><u>Updated Videos Look Better when Edited Professionally. If Youre Looking to Edit Recorded Video with a Pro-Level Editing Then Weve Got You Covered. Learn About Editing Recorded Videos with the Best Toolkit Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-back-old-file-management-interface/"><u>Bringing Back Old File Management Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-driver-initialization-failure-in-windows-11/"><u>Solutions for Driver Initialization Failure in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-command-gain-admin-status/"><u>Regain Command - Gain Admin Status</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/in-2024-compilation-of-websites-offering-feline-inspired-mp3-sounds/"><u>In 2024, Compilation of Websites Offering Feline-Inspired MP3 Sounds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-resolving-user-not-found-issue-windows-1011/"><u>Steps for Resolving 'User Not Found' Issue: Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-your-mouse-icon-with-ease-on-win-os/"><u>Transforming Your Mouse Icon with Ease on Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-the-mechanics-of-windows-11s-compatibility-tool/"><u>Uncovering the Mechanics of Windows 11’S Compatibility Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719320946567-list-three-benefits-of-applying-a-cultural-relativist-approach-when-encountering-unfamiliar-customs-or-beliefs/"><u>List Three Benefits of Applying a Cultural Relativist Approach when Encountering Unfamiliar Customs or Beliefs</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-want-to-loop-a-video-to-extend-its-duration-you-can-use-imovie-to-loop-a-video-on-your-mac-and-iphone-and-we-will-illustrate-how-to-loop-a-video-in-/"><u>In 2024, Want to Loop a Video to Extend Its Duration? You Can Use iMovie to Loop a Video on Your Mac and iPhone and We Will Illustrate How to Loop a Video in iMovie</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-the-buzz-mastering-voice-recorder-shortcuts-in-windows-11/"><u>Beating the Buzz: Mastering Voice Recorder Shortcuts in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/storeroom-in-mp60-speed-still-scarce/"><u>Storeroom in MP60, Speed Still Scarce</u></a></li>
<li><a href="https://win11-tips.techidaily.com/counteracting-shutdownrestart-blockage-due-to-deceptive-apps-in-windows/"><u>Counteracting Shutdown/Restart Blockage Due to Deceptive Apps in Windows</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-full-tutorial-to-bypass-your-poco-x6-pro-face-lock-by-drfone-android/"><u>In 2024, Full Tutorial to Bypass Your Poco X6 Pro Face Lock?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-checklist-longer-pins-in-windows-11-and-11/"><u>The Ultimate Checklist: Longer PINs in Windows 11 and 11</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/unleash-your-creativity-top-10-free-online-video-editors-with-no-watermark-limits-for-2024/"><u>Unleash Your Creativity Top 10 Free Online Video Editors with No Watermark Limits for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-tackling-windows-1011-interrupt-crashes/"><u>Strategies for Tackling Windows 10/11 INTERRUPT Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-inadequate-usb-support-on-desktops/"><u>Addressing Inadequate USB Support on Desktops</u></a></li>
</ul></div>
