---
title: Addressing Taskbar Icon Glitches in Win 10/8
date: 2024-08-16T01:11:50.059Z
updated: 2024-08-17T01:11:50.059Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Taskbar Icon Glitches in Win 10/8
excerpt: This Article Describes Addressing Taskbar Icon Glitches in Win 10/8
keywords: Fix Win 10 Taskbar,Resolve Win 10 Issues,Stop Windows Icon Errors,Correcting Taskbar Glitches,Win 10 UI Flaws,Tackle Icon Problems,Remedy Taskbar Failures
thumbnail: https://thmb.techidaily.com/3c096ca7006d9a28f3f7e555f29e64435eb73c0052911cf681dfac2286fbe4f4.jpg
---

## Addressing Taskbar Icon Glitches in Win 10/8

 Taskbar thumbnail previews usually enable you to see an app window’s content without maximizing it. However, some Windows 11/10 users have posted on help forums about thumbnail previews not working. When taskbar thumbnail previews aren’t working, they don’t appear when users hover their cursors over minimized windows.

 This issue often arises when users have multiple windows open for apps. Consequently, users only see text labels for minimized window titles. Does a similar thing happen when you try to view taskbar previews? If so, this is how you can fix taskbar thumbnail previews not working on Windows 11/10 PCs.

## 1\. Restart File Explorer’s Process

 The File Explorer process handles the taskbar and many other Windows UI elements. So, restarting that process is a good place to start with troubleshooting this taskbar thumbnail preview issue. Doing so can address File Explorer glitches that could be causing the issue.

 You can restart File Explorer on the **Processes** tab inside Task Manager. Right-click the Windows Explorer process there and select **Restart**. Check out this guide to [restarting File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) for further instructions if needed.

![The Restart button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/restart-button.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
## 2\. Repair System Files

 It’s usually recommended to try repairing system files whenever a Windows function isn’t working right. In this case, taskbar window previews aren’t working correctly. Running a System File Checker scan might repair corrupted system files causing this issue. Our [how to run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide provides guidelines for utilizing the SFC command-line tool.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/sfc-scannow.jpg)

## 3\. Edit the Taskband and Advanced Registry Keys

 Editing the Taskbar registry key is a widely confirmed solution for fixing taskbar thumbnail previews not working. This potential resolution will fix the **NumThumbnails** DWORD in that key, which might be deleted or incorrectly set. That DWORD sets the maximum number of taskbar thumbnail previews for a single minimized window. This is how you should edit the **Taskband** registry key:

1. Click the magnifying glass or file finder text box on the Windows 11/10 taskbar and input a **regedit** search term.
2. Select the **Registry Editor** search result to access that utility.
3. Go to the **Taskbar** key by inputting this location in the registry address bar:  
`Computer\HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Taskband`
4. If you can’t see a **NumThumbnails** DWORD, right-click the **Taskbar** key in Registry Editor’s sidebar and select **New** \> **DWORD**.  
![The New > DWORD option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-dword-options.jpg)
5. Enter **NumThumbnails** inside the DWORD name text box.
6. Double-click the **NumThumbnails** DWORD.  
![The NumThumbnails DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/numthumbnails-dword.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
7. If that **DWORD** is set at **0**, erase that number and input **10** in the **Value** box.  
![The Edit DWORD (32-bit) Value window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/edit-dword-window3.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
8. Click **OK** to set the new **NumThumbnails** value.
9. Restart Windows 11/10 (or restart File Explorer) for this registry tweak to take effect.

 You might also need to delete a **DisablePreviewWindow** or **DisablePreviewDesktop** DWORD in the **Advanced** registry key to fix taskbar thumbnail previews not working. To do so, right-click the **DisablePreviewWindow** or **DisablePreviewDesktop** DWORD in the **Advanced** key and select **Delete** \> **Yes**. The registry location of the **Advanced** key is:

`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`

## 4\. Disable the Turn Off Taskbar Thumbnails Policy Setting

 Group Policy Editor includes a policy setting for disabling taskbar thumbnail policies. If you’re a Windows 11/10 Pro or Enterprise user, check that policy to make sure it’s not set to disable taskbar thumbnail previews. You can disable the **Turn off taskbar thumbnails** policy as follows:

1. [Open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) window by pressing the **Windows key + R** keyboard shortcut, inputting **gpedit.msc**, and selecting Run’s **OK** option.
2. Double-click **User Configuration** \> **Administrative Templates** \> **Start menu and taskbar** in the navigation sidebar.  
![The Local Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/local-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
3. Next, double-click **Turn off taskbar thumbnails** to access configuration options for that policy.
4. Click the **Disabled** or **Not Configured** option.  
![The Turn off taskbar thumbnail window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/turn-off-windows-taskbar-window.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
5. Select **Apply** \> **OK** to disable the **Turn off taskbar thumbnails** policy as configured.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Roll Windows Back With a System Restoration Point

 If you have System Restore enabled, that could be a useful troubleshooting tool for fixing taskbar thumbnail previews not working. Restoring Windows to a date when your taskbar window previews worked might undo background changes that caused the issue. However, this will only work if you can select a suitable restore point that predates the issue.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/system-restore-tool.jpg)

 You can roll back Windows by following the instructions in this guide to [utilizing System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/). Applying this potential solution will remove software packages installed after the date of the selected restore point. This will mean some reinstallation of software will probably be necessary after rolling back Windows.

## Get Your Taskbar Thumbnail Previews Fixed

 Taskbar thumbnail previews may not be the most essential feature, but many users will undoubtedly miss them when they’re not working. Applying the troubleshooting methods in this guide will usually get the Windows 11/10 taskbar thumbnails working again in most cases. So, give them a try if you can’t view taskbar thumbnail previews for minimized windows.

 This issue often arises when users have multiple windows open for apps. Consequently, users only see text labels for minimized window titles. Does a similar thing happen when you try to view taskbar previews? If so, this is how you can fix taskbar thumbnail previews not working on Windows 11/10 PCs.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-leading-edge-the-top-10-mobile-video-chat-platforms/"><u>[New] In 2024, Leading Edge  The Top 10 Mobile Video Chat Platforms</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-preventing-frame-skips-in-live-obs-broadcasts/"><u>[New] Preventing Frame Skips in Live OBS Broadcasts</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-instagram-artistry-the-top-image-enhancers/"><u>[Updated] Instagram Artistry  The Top Image Enhancers</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-sensual-sequence-capturing-culinary-creativity-on-camera/"><u>2024 Approved  Sensual Sequence  Capturing Culinary Creativity on Camera</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-unbox-the-latest-tomtom-bandit-camera/"><u>2024 Approved  Unbox the Latest TomTom Bandit Camera</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-manual-for-mending-screen-size-issues-on-windows/"><u>A Step-by-Step Manual for Mending Screen Size Issues on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-cross-language-communication-with-windows-11-hotkeys/"><u>Accelerate Cross-Language Communication with Windows 11 Hotkeys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-computer-experience-with-these-6-tools/"><u>Accelerate Your Computer Experience with These 6 Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-enterprise-restricted-chromeedge-settings-on-desktop-pcs/"><u>Addressing Enterprise-Restricted Chrome/Edge Settings on Desktop PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-failed-writable-operation-files-in-windows/"><u>Addressing Failed Writable Operation Files in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-failed-connectivity-issue-of-mb-in-windows-11/"><u>Addressing the Failed Connectivity Issue of MB in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-visual-fields-in-windows-systems/"><u>Altering Visual Fields in Windows Systems</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/altering-your-voice-for-stories-and-reels-on-instagram-for-2024/"><u>Altering Your Voice for Stories & Reels on Instagram for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-and-defusing-error-0x80070570-saving-your-damaged-files-in-windows-11/"><u>Deciphering and Defusing Error 0X80070570: Saving Your Damaged Files in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-purpose-and-use-of-microsofts-phone-link-app/"><u>Deciphering the Purpose and Use of Microsoft's 'Phone Link' App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decode-fn-key-operations-in-modern-windows-pcs/"><u>Decode FN Key Operations in Modern Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-fixes-for-alt-codes-failing-in-windows-60-characters/"><u>Effective Fixes for ALT Codes Failing in Windows (60 Characters)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-video-processing-on-windows-embrace-distributed-power-via-tdarr/"><u>Elevate Video Processing on Windows: Embrace Distributed Power via Tdarr</u></a></li>
<li><a href="https://android-location.techidaily.com/fake-android-location-without-rooting-for-your-tecno-spark-10-5g-drfone-by-drfone-virtual/"><u>Fake Android Location without Rooting For Your Tecno Spark 10 5G | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/game-on-gopro-top-tips-for-high-quality-gameplay-videoing/"><u>Game on, GoPro! Top Tips for High-Quality Gameplay Videoing</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-honor-x9b-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos From Honor X9b to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-seven-superior-cameras-defy-the-elements-waterproof/"><u>In 2024, Seven Superior Cameras Defy the Elements (Waterproof)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-the-most-of-intel-unison-for-convenient-windows-11-calls/"><u>Making the Most of Intel Unison for Convenient Windows 11 Calls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/no-more-keyboard-confusion-30-ways-to-fix/"><u>No More Keyboard Confusion: 30 Ways to Fix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-playback-lags-a-guide-for-chromium-users/"><u>Overcoming Playback Lags: A Guide for Chromium Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-snip-tool-text-edits-on-win-11/"><u>Perfecting Snip Tool Text Edits on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correct-device-opens-issue-on-audacity-in-windows/"><u>Steps to Correct Device Opens Issue on Audacity in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-the-wild-high-on-your-windows-desktop/"><u>Taming the Wild High on Your Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-student-essentials-asus-vivobook-s-15-reviewed/"><u>The Ultimate Student Essentials - ASUS Vivobook S 15 Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-teamsters-downtime-on-windows-11-10/"><u>Troubleshooting Teamsters Downtime on Windows 11, 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-vac-denied-access-in-steam-windows/"><u>Troubleshooting VAC Denied Access in Steam Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turn-your-spoken-words-into-written-sense-using-whisper/"><u>Turn Your Spoken Words Into Written Sense Using Whisper</u></a></li>
<li><a href="https://win-dash.techidaily.com/update-your-gaming-experience-with-new-gtx-1650-super-driver-software-on-windows-11/"><u>Update Your Gaming Experience with New GTX 1650 Super Driver Software on Windows 11</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-identify-malfunctioning-your-hardware-drivers-with-windows-device-manager-in-windows-10-and-7-by-drivereasy-guide/"><u>Use Device Manager to identify malfunctioning your hardware drivers with Windows Device Manager in Windows 10 & 7</u></a></li>
</ul></div>
