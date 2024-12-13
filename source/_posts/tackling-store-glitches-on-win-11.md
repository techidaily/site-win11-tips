---
title: Tackling Store Glitches on Win 11
date: 2024-12-11T20:15:52.220Z
updated: 2024-12-12T21:13:35.496Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling Store Glitches on Win 11
excerpt: This Article Describes Tackling Store Glitches on Win 11
keywords: Win 11 Bug Fixing,Win 11 Glitch Solving,Win 11 Error Management,Win 11 System Stability,Win 11 Performance Tuning,Win 11 Issue Resolution,Win 11 Software Debugging
thumbnail: https://thmb.techidaily.com/214585cc6f04e9f51b09b50240658d386b443c6b610883b05f292e6c6a7a4335.jpg
---

## Tackling Store Glitches on Win 11

 Error code 0x00000000 is another of those Microsoft Store issues commonly reported on support forums. This error occurs when users try to install new UWP apps or update ones already installed. The error 0x00000000 messages say, “Something unexpected happened” or “Try that again.”

 Users can’t download new apps or updates from the Microsoft Store in Windows 11/10 because of error 0x00000000\. Thus, error 0x00000000 is a big deal for users who get most of their software from Microsoft’s storefront. This is how you can resolve Microsoft Store’s error x00000000 in Windows 11 and 10\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run the Troubleshooter for Windows Store Apps

 First, start with potential error 0x00000000 resolutions that are more straightforward to apply, such as running the Windows Store Apps troubleshooter. Microsoft Store is itself a UWP app for which the Windows Store Apps troubleshooter can fix issues. So, try running the Windows Store Apps troubleshooting tool like this:

1. Press **Start** to select a **Settings** cog button or pinned shortcut on the Windows 11/10 menu.
2. Click Settings’ **System** tab and the **Troubleshoot** navigation option.
3. Select **Other trouble-shooters** to reach the troubleshooting tools in Settings.
4. Click the **Run** option for starting the Windows Store Apps troubleshooter.  
![The Run Windows Store Apps option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-run-button.jpg)
5. Then select to apply any potential solution presented within Windows Store Apps.  
![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-store-apps-troubleshooter.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XA_wP7rS9ww?si=LarMG3sEHAhSoL6q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In Windows 10, the steps for opening Windows Store Apps aren’t quite the same. Click the **Update & Security** category in Windows 10’s Settings app and select the **Troubleshoot** tab. Then you can click an **Additional troubleshooter** navigation option to reach the list of troubleshooting utilities.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-G7cU8dYvuI?si=JaKqRcW6qq9CDvty" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Enable the Microsoft Store Install Service

 The Microsoft Store Install Service has a description that says app installations can’t function properly when it’s disabled. So, that’s a necessary service to have enabled to utilize the Microsoft Store without issues. This is how you can check and enable the Microsoft Store Install Service.

1. Click **Start** by pressing the right mouse button and select **Search**.
2. Type a **Services** search phrase into the text box.
3. Next, launch Services by selecting the search result for that app.
4. Double-click **Microsoft Store Install Service** to access its settings.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-services-window-1.jpg)
5. Open the **Startup type** menu by clicking on it and selecting **Automatic**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fo4lNZ84x9Q?si=WdcYPZp-9VJnZEnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Settings for the Microsoft Store Install Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-install-service-properties-window.jpg)
6. Then select **Start** in the Microsoft Store Install Service Properties window.
7. Select **Apply** to save the selected settings for the service.
8. Click the Microsoft Store Install Service window’s **OK** button.

## 3\. Clear the Microsoft Store Cache

 Some Microsoft Store users have confirmed they fixed error 0x00000000 by resetting that app’s cache. So, try clearing Microsoft Store’s cached data.

 Press **Win + R**, type in "cmd," press **Enter**, and enter the command for resetting the Microsoft Store’s cache:

`WSReset.exe`

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YezPJZzPJ8Q?si=xF1t4BQHFquzvnzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Try Some General Windows Troubleshooting Tips

 There are a few Windows-based fixes you can try that fix general Windows Store issues. So, give these a try:

### Run the System File Checker Command

 Error 0x00000000 can occur because of a wider PC issue with corrupted system files. You can address such a potential cause by running the System File Checker utility. Our [post about running the SFC tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to apply this potential solution within the Command Prompt.

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/sfc-scannow-command.jpg)

 It’s also recommended to run a Deployment Image Servicing Management scan along with the SFC tool. That utility services and repairs the system image. You can run the Deployment Image Servicing Management tool by executing this command:

`DISM.exe /Online /Cleanup-image /Restorehealth`

### Disable Any Active Proxy Servers

 A proxy server is an intermediary, or middleman, for handling PC client resource requests. Enabling a proxy server might be good for bypassing geographical website restrictions, but it’s a common cause of Microsoft Store errors such as 0x00000000\. So, we recommend that you [disable proxy server settings](https://www.makeuseof.com/windows-11-disable-proxy/) on your Windows 11/10 PC if they’re enabled to resolve error 0x00000000\.

![The Use a proxy server option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-use-a-proxy-server-option.jpg)

### Reinstall the Microsoft Store

![An uninstall Microsoft Store command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-apppackage-command.jpg)

 Reinstalling Microsoft Store is a slightly more drastic potential fix for error 0x00000000 to apply when others fail. This potential resolution will replace the Microsoft Store’s files.

 However, you cannot simply uninstall the Microsoft Store in Settings and download the app from a web source. Instead, you’ll need to remove that app and reinstall it again by inputting PowerShell commands. Our article about [how to reinstall Microsoft Store](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) includes step-by-step instructions for applying this potential error 0x00000000 solution.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Set Up a New Windows User Account

![The Add account button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/add-account-option.jpg)

 You might need to fix error 0x00000000 because of a corrupted user account. Setting up a fresh new user account would then be a probable fix. Note that you can create a new user account and transfer the data from the old one to it.

 Our guide on [creating a new Windows user account](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) explains how to apply such a potential resolution.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Perform a Windows System Restore

 System Restore is a utility that saves Windows system snapshots. Those system snapshots, otherwise restore points, enable you to roll back Windows to the dates saved. Thus, System Restore is kind of like a time machine with which you can undo system changes applied after selected restore point dates.

 Performing a system restore might repair system file corruption causing the 0x00000000 error. However, it’s only a viable solution if you can select a restore point predating error 0x00000000 on your PC. Note that rolling Windows back also removes apps, drivers, and updates installed after restoration point dates.

 Check out this guide to [setting up and utilizing Windows System Restore points](https://www.makeuseof.com/windows-11-create-restore-point/) for instructions about how to perform a system restore.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-restore-window.jpg)

### Do an In-Place Windows Upgrade

 An in-place upgrade effectively installs a new copy of Windows. That may sound like a drastic solution but applying it won’t affect user files or third-party software installed on your PC. Furthermore, upgrading Windows in such a way will probably fix any system issues causing error 0x00000000\.

 Performing an in-place upgrade involves downloading the latest Windows 11 ISO file from Microsoft’s website. Then you can install the latest Windows version by clicking setup.exe within the Windows ISO file and going through the setup wizard. This guide tells you how to [perform an in-place Windows 11 upgrade](https://www.makeuseof.com/in-place-upgrade-windows-11/) in such a way.

![The Windows 11 setup window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-11-setup-window.jpg)

Screenshot captured by Jack Slater - No attribution required

 To apply the same potential solution in Windows 10, click **Download tool now** on the [Microsoft Windows 10 download page](https://www.microsoft.com/en-gb/software-download/windows10).

 Open the downloaded Windows 10 Setup wizard and select the **Upgrade this PC Now** option. Then click the **Keep personal files and apps** option and select **Install**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qv4Qm7kpeMs?si=9fv5SOS5a2DvixTK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Download Everything You Need on Microsoft Store

 Going through the nine potential resolutions above will likely resolve Microsoft Store error code 0x00000000 on your PC. You’ll probably have to apply more than one of those potential fixes to find one that works because this error has numerous causes. With error 0x00000000 fixed, you can then download all apps and updates again within Microsoft Store.

 Users can’t download new apps or updates from the Microsoft Store in Windows 11/10 because of error 0x00000000\. Thus, error 0x00000000 is a big deal for users who get most of their software from Microsoft’s storefront. This is how you can resolve Microsoft Store’s error x00000000 in Windows 11 and 10\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-proven-tactics-for-saving-lol-events/"><u>[New] 2024 Approved Proven Tactics for Saving LOL Events</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-navigating-color-grading-a-look-at-luts-significance-for-2024/"><u>[New] Navigating Color Grading A Look at LUT's Significance for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-earn-through-engagement-securing-youtube-partnership-membership/"><u>[Updated] In 2024, Earn Through Engagement Securing YouTube Partnership Membership</u></a></li>
<li><a href="https://discover-advanced.techidaily.com/abbyy-compreno-crowned-innovative-leader-of-2016-by-kmworld-magazine/"><u>ABBYY Compreno Crowned 'Innovative Leader of 2016' By KMWorld Magazine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ease-your-program-interactions-with-context-menu-upgrades/"><u>Ease Your Program Interactions with Context Menu Upgrades</u></a></li>
<li><a href="https://sound-issues.techidaily.com/effective-solutions-for-fixing-mute-speakers-in-windows-7/"><u>Effective Solutions for Fixing Mute Speakers in Windows 7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortlessly-enhanced-top-free-must-have-tools-for-windows-11/"><u>Effortlessly Enhanced: Top Free Must-Have Tools for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/evanescence-of-audio-glitch-overcoming-code-0xd36b4/"><u>Evanescence of Audio Glitch: Overcoming Code 0Xd36b4</u></a></li>
<li><a href="https://technical-tips.techidaily.com/guide-how-to-switch-off-subtitle-features-in-amazon-prime-video/"><u>Guide: How to Switch Off Subtitle Features in Amazon Prime Video</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-hitching-a-ride-in-high-flying-tiktok-live-shows/"><u>In 2024, Hitching a Ride in High-Flying TikTok Live Shows</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-unlimited-editing-discover-these-9-free-cloud-tools/"><u>In 2024, Unlimited Editing Discover These 9 Free Cloud Tools</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/latest-guide-how-to-bypass-vivo-v30-pro-frp-without-computer-by-drfone-android/"><u>Latest Guide How To Bypass Vivo V30 Pro FRP Without Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-your-start-menu-experience-in-windows-11/"><u>Maximize Your Start Menu Experience in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/set-your-system-for-effortless-file-disposal-in-windows/"><u>Set Your System for Effortless File Disposal in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-invisible-zip-file-encryption-within-pixels/"><u>The Art of Invisible ZIP File Encryption Within Pixels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-ancestry-the-surviving-features-from-the-seventh-era/"><u>Windows Ancestry: The Surviving Features From the Seventh Era</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-access-fixing-past-login-phrase-problem/"><u>Winning Back Access: Fixing Past Login Phrase Problem</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    