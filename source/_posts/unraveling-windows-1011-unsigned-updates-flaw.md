---
title: Unraveling Windows 10/11 Unsigned Updates Flaw
date: 2024-08-28T01:21:07.595Z
updated: 2024-08-29T01:21:07.595Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unraveling Windows 10/11 Unsigned Updates Flaw
excerpt: This Article Describes Unraveling Windows 10/11 Unsigned Updates Flaw
keywords: Win10FlawsUnauthorizedUpdates,Windows11UnsignedUpdateRisk,SignedUpdateWindowsSecure,UnsignedWindows10Security,UpdatingWindowsNoSignature,Windows10/11Vulnerability,SecurityFlawUnsignedUpdates
thumbnail: https://thmb.techidaily.com/5b0ce9c020094ad31bdc87530c31e032109184ed98794f1ba27d0b681ad3c785.jpg
---

## Unraveling Windows 10/11 Unsigned Updates Flaw

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
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Save the settings by pressing the **Apply** and **OK** buttons.
8. Double-click the **Background Intelligent Transfer Service** to view its settings.
9. Select a **Manual** startup option.
10. Click the **Start** option for the BITS service if it’s stopped.
11. Then click on the **Apply** and **OK** options to set that service’s options.

 If you find both services to be already enabled and running, try restarting them. You can do so by right-clicking the BITS and Windows Update service names and selecting a **Restart** option on their context menus.

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Reset Components for Windows Updates

 Resetting components for Windows updates will completely refresh the catroot2 and SoftwareDistribution folders, which store update data. This troubleshooting method also reregisters all DLL files for important update services. Applying such a potential resolution can fix corrupted components causing error 0x800b0109\.

 To apply this possible error 0x800b0109 resolution, check out our article on [resetting Windows update components](https://www.makeuseof.com/reset-windows-update-components/). That guide includes a command-line and batch file method. Creating and running a batch file is the quicker and more straightforward way to reset Windows update components.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Deactivate Third-Party Security Software

 A third-party security (antivirus) app can potentially conflict with Windows update processes. This can happen when the antivirus protection of a security app locks files needed by Windows Update. It’s not something that happens often, but temporarily disable any third-party antivirus protection on your PC just in case.

 Security apps typically include options for disabling antivirus protection on their system tray context menus. Right-click your security app’s icon in Windows 11’s system tray area to find and select its option for temporarily disabling the antivirus shield. Then, return to the Settings app to see if error 0x800b0109 still happens with the antivirus shield disabled.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 8\. Apply an In-Place Windows Upgrade

 An in-place Windows upgrade is the last resort for fixing error 0x800b0109\. Applying this potential resolution will reinstall Windows on your PC with its latest ISO file. The installation of a fresh Windows copy will likely resolve other issues causing the 0x800b0109 update error that other potential solutions couldn’t fix.

 The good thing about an in-place upgrade is that it won’t eradicate your installed software or user files. This [how-to perform an in-place upgrade](https://www.makeuseof.com/in-place-upgrade-windows-11/) guide tells you how to apply this potential solution for Windows 11\. The steps are quite similar for Windows 10, but you’ll need to download its ISO with the Media Creation Tool available on this [Microsoft page](https://www.microsoft.com/en-gb/software-download/windows10).

![The Windows 10 Media Creation tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-10-setup-window.jpg)

## Get Windows Updated Again

 There isn’t a surefire way to fix error 0x800b0109 since there are varied possible reasons for that Windows 11/10 issue occurring. However, it’s likely at least one of the eight potential resolutions in this guide will fix that update issue on your PC.

 Some of the best third-party Windows repair tools might also be helpful for resolving the “Some update files aren’t signed” error.

 Windows updates fail to install when this issue occurs. This error usually includes either a 0x800b0109 or 0x800b0100 code after its message. This is how you can resolve the “Some update files aren’t signed” error 0x800b0109 on a Windows 11/10 PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://driver-download.techidaily.com/download-realtek-asio-driver-for-windows-10-quick-and-easy/"><u>[Download] Realtek Asio Driver for Windows 10 | Quick & Easy</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-elite-choices-top-8-tripods-for-cinematic-4k-experiences-for-2024/"><u>[New] Elite Choices  Top 8 Tripods for Cinematic 4K Experiences for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-empowering-remote-teams-with-google-meets-whiteboard-features-on-various-devices-for-2024/"><u>[New] Empowering Remote Teams with Google Meet's Whiteboard Features on Various Devices for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-video-vanguard-vs-studio-giants/"><u>[New] In 2024, Video Vanguard VS Studio Giants</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-high-income-content-makers/"><u>[Updated] 2024 Approved  High-Income Content Makers</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-cam-protection-the-ultimate-10-guide-for-2024/"><u>[Updated] Cam Protection  The Ultimate 10 Guide for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-amplify-your-videos-the-best-text-effects-guide/"><u>2024 Approved  Amplify Your Videos  The Best Text Effects Guide</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-master-the-craft-streamlining-your-online-television-recordings/"><u>2024 Approved  Master the Craft  Streamlining Your Online Television Recordings</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-secure-sharpening-hiding-unwanted-details/"><u>2024 Approved  Secure Sharpening  Hiding Unwanted Details</u></a></li>
<li><a href="https://ai-video.techidaily.com/2024-approved-5-best-apps-for-voice-translation-from-english-to-bangla/"><u>2024 Approved 5 Best Apps for Voice Translation From English to Bangla</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-non-detected-bluetooth-on-windows-mgr/"><u>Correcting Non-Detected Bluetooth On Windows Mgr</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-software-failure-amd-195-for-windows/"><u>Correcting Software Failure: AMD 195 for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-and-correcting-bios-boot-errors-on-winos/"><u>Decoding & Correcting BIOS Boot Errors on WinOS</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/disabling-apple-iphone-15-pro-parental-restrictions-withwithout-password-by-drfone-ios/"><u>Disabling Apple iPhone 15 Pro Parental Restrictions With/Without Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easily-achieve-optimal-security-with-ms-defender-aguard-on-windows-11s-edge/"><u>Easily Achieve Optimal Security with MS Defender Aguard on Windows 11'S Edge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-outdated-video-quality-using-madvr-on-pcs/"><u>Elevate Outdated Video Quality Using MadVR on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enablingdisabling-tpm-support-in-virtualbox-70/"><u>Enabling/Disabling TPM Support in VirtualBox 7.0</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-for-high-dpi-scaling-in-windows-os/"><u>Essential Fixes for High DPI Scaling in Windows OS</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/everything-you-need-to-know-about-lock-screen-settings-on-your-nubia-by-drfone-android/"><u>Everything You Need to Know about Lock Screen Settings on your Nubia</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/fb-content-conversion-turn-vids-into-mp3s-in-seconds-for-2024/"><u>FB Content Conversion  Turn Vids Into MP3s in Seconds for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-essential-steps-to-overcome-windows-os-hypervisor-faults/"><u>Five Essential Steps to Overcome Windows OS Hypervisor Faults</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-unsuccessful-file-transfers-on-windows-pcs/"><u>Fixing Unsuccessful File Transfers on Windows PCs</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-check-distance-and-radius-on-google-maps-for-your-realme-11-5g-drfone-by-drfone-virtual-android/"><u>How to Check Distance and Radius on Google Maps For your Realme 11 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-exclude-email-address-in-windows-login-settings/"><u>How to Exclude Email Address in Windows Login Settings</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-a-simple-path-to-enhanced-youtube-sign-ups-create-animated-subscription-bar-using-filmora/"><u>In 2024, A Simple Path to Enhanced YouTube Sign-Ups - Create Animated Subscription Bar Using Filmora</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-avoiding-storage-woes-removing-youtube-media/"><u>In 2024, Avoiding Storage Woes  Removing YouTube Media</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-best-settings-audience-focused-screen-shots/"><u>In 2024, Best Settings  Audience-Focused Screen Shots</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-expert-tips-to-improve-skype-broadcasts-using-obs/"><u>In 2024, Expert Tips to Improve Skype Broadcasts Using OBS</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-radiant-spectrum-enhancer/"><u>In 2024, Radiant Spectrum Enhancer</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-set-your-preferred-job-location-on-linkedin-app-of-your-meizu-21-drfone-by-drfone-virtual-android/"><u>In 2024, Set Your Preferred Job Location on LinkedIn App of your Meizu 21 | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-understanding-asmrs-potential-benefits-for-you/"><u>In 2024, Understanding ASMR's Potential Benefits for You</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-unlocking-potential-your-guide-to-obs-android-broadcasts/"><u>In 2024, Unlocking Potential  Your Guide to OBS Android Broadcasts</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-will-ispoofer-update-on-nokia-105-classic-drfone-by-drfone-virtual-android/"><u>In 2024, Will iSpoofer update On Nokia 105 Classic | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/logitech-mk710-downloading-and-installing-your-mouses-latest-drivers/"><u>Logitech MK710: Downloading & Installing Your Mouse's Latest Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-command-line-integration-in-windows-11s-task-manager/"><u>Mastering Command Line Integration in Windows 11'S Task Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-folder-inclusion-in-win11s-context-menu/"><u>Mastering Folder Inclusion in Win11's Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11s-action-center-mixer-for-immersive-sound/"><u>Mastering Windows 11'S Action Center Mixer for Immersive Sound</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-microsoft-store-for-customizing-your-interface/"><u>Navigating Through Microsoft Store for Customizing Your Interface</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-expert-guide-to-displaying-audio-waves-and-adding-motion-graphics-in-premiere-pro-for-2024/"><u>New Expert Guide to Displaying Audio Waves and Adding Motion Graphics in Premiere Pro for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-your-screen-and-sound-recordings-with-the-updated-windows-11-snipping-tool-max-156/"><u>Optimizing Your Screen & Sound Recordings with the Updated Windows 11 Snipping Tool (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recover-unseen-second-screen-in-w11/"><u>Recover Unseen Second Screen in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectify-steam-error-missing-files-on-modern-windows-11-pc/"><u>Rectify Steam Error: Missing Files on Modern Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-the-absence-of-supported-scanner-for-windows-hello/"><u>Remedying the Absence of Supported Scanner for Windows Hello</u></a></li>
<li><a href="https://extra-tips.techidaily.com/renaming-your-podcast-leading-ai-generators-explored/"><u>Renaming Your Podcast  Leading AI Generators Explored</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-11-get-help-issue/"><u>Resolving Windows 11 'Get Help' Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-defaults-of-the-modern-terminal-win11/"><u>Restoring Defaults of the Modern Terminal (Win11)</u></a></li>
<li><a href="https://media-tips.techidaily.com/step-by-step-tutorial-rm-to-mp4-conversion-mastery-with-aiseesofts-top-tool/"><u>Step-by-Step Tutorial: RM to MP4 Conversion Mastery with Aiseesoft's Top Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/subtlety-saved-master-disappearing-buttons-in-1011/"><u>Subtlety Saved: Master Disappearing Buttons in 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-route-for-gpo-discovery-in-pcs/"><u>The Essential Route for GPO Discovery in PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-8-windows-compatible-ios-apps-for-android-users/"><u>Top 8 Windows-Compatible iOS Apps for Android Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-system-potential-enhancing-virtual-memory/"><u>Unlocking System Potential: Enhancing Virtual Memory</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-to-do-when-your-update-fails-at-0x800f0845/"><u>What to Do When Your Update Fails at 0X800F0845?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-woes-rescue-your-operators-download/"><u>Windows Woes? Rescue Your Operator's Download</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winerror-zeroed-out-mastery-over-error-0x800f0831/"><u>WinError Zeroed Out: Mastery Over Error 0X800F0831</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>