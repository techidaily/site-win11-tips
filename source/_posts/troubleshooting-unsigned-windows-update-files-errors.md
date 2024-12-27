---
title: Troubleshooting Unsigned Windows Update Files Errors
date: 2024-12-20T19:58:26.428Z
updated: 2024-12-27T18:13:08.547Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Unsigned Windows Update Files Errors
excerpt: This Article Describes Troubleshooting Unsigned Windows Update Files Errors
keywords: Windows Update Fix Guide,Update Error Resolution,Windows Security Patches,Signed Update Troubleshoot,Update File Validation,Unsigned Error Remedy,Windows Updates Support
thumbnail: https://thmb.techidaily.com/0171a03fcfaa97ca9a37fd62265ffdf540832c9ac080e870fc5542fba83032d5.jpg
---

## Troubleshooting Unsigned Windows Update Files Errors

 Users frequently report Windows 11/10 update errors on software support forums. One such update issue reported is an error message that says, “Some update files aren’t signed.” Some users see that error message appear within Settings’ Windows Update tab when trying to update Windows.

 Windows updates fail to install when this issue occurs. This error usually includes either a 0x800b0109 or 0x800b0100 code after its message. This is how you can resolve the “Some update files aren’t signed” error 0x800b0109 on a Windows 11/10 PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fm0XhU5H8R4?si=cFPk6XK3X3CQSI7Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/startup-type-drop-down-menu.jpg)
6. Click **Start** (inside the properties windows) to run the Windows Update service.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cKRBWf1EDZo?si=CTNd4q450biit4eM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BR4gsW-J7as?si=9a56UDKZKhREZnwz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Thereafter, it’s also recommended to restart the Windows Update and BITS services. To do so, open Services as covered in the first three steps of resolution three. Then, select the **Restart** context menu options for Windows Update and BITS.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GBWcw6rXIdg?si=Tlue44bW-bPA4tH9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://snapchat-videos.techidaily.com/new-no-trace-snapcaptures-discreet-photo-taking-techniques/"><u>[New] No Trace SnapCaptures Discreet Photo-Taking Techniques</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-audience-expansion-with-immersive-360-videos-on-social-media/"><u>2024 Approved Audience Expansion with Immersive 360 Videos on Social Media</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-power-losses-how-to-schedule-auto-shutdown-on-win11-pcs/"><u>Cutting Power Losses: How to Schedule Auto-Shutdown on Win11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-and-solving-defenders-0x80004004-error/"><u>Decoding and Solving Defender's 0X80004004 Error</u></a></li>
<li><a href="https://extra-resources.techidaily.com/exploring-the-best-of-gopro-cameras-side-by-side/"><u>Exploring the Best of GoPro Cameras Side by Side</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-up-to-speed-with-quick-copy-paste-in-powertoys/"><u>Get Up to Speed With Quick Copy-Paste in PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-d3dx939dll-missing-error-on-windows-11/"><u>How to Fix the D3DX9_39.dll Missing Error on Windows 11</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-change-your-apple-id-on-iphone-se-with-or-without-password-drfone-by-drfone-ios/"><u>In 2024, How To Change Your Apple ID on iPhone SE With or Without Password | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-15-apps-to-hack-wifi-password-on-itel-p55plus-by-drfone-android/"><u>In 2024, Top 15 Apps To Hack WiFi Password On Itel P55+</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/in-2024-videography-101-crafting-attractive-haul-and-try-on-vids/"><u>In 2024, Videography 101 Crafting Attractive Haul & Try-On Vids</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimized-file-picking-toggle-windows-11-checkboxes/"><u>Optimized File Picking: Toggle Windows 11 Checkboxes</u></a></li>
<li><a href="https://win-deluxe.techidaily.com/rapid-site-crawling-with-ultrafast-achieve-google-indexation-in-just-6-simple-steps-using-massmail/"><u>Rapid Site Crawling with UltraFast: Achieve Google Indexation in Just 6 Simple Steps Using Massmail!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-dxgidll-absence-on-win11-steps-guide/"><u>Resolving Dxgi.dll Absence on Win11 - Steps Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-keeping-calculator-as-windowtop-focus/"><u>Steps for Keeping Calculator as Windowtop Focus</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210811623-9798890300997-the-divine-volumes-of-power/"><u>The Divine Volumes of Power | Free Book</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-guide-to-windows-group-policy-interpretation-3-ways/"><u>The Essential Guide to Windows Group Policy Interpretation (3 Ways)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-guide-to-disabling-gpu-aided-process-ordering-in-widno/"><u>The Guide to Disabling GPU-Aided Process Ordering in WIDNO</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ale-of-two-platforms-youtube-and-dailymention/"><u>The Tale of Two Platforms YouTube and DailyMention</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/unlocking-iphone-11-pro-max-lock-screen-3-foolproof-methods-that-actually-work-drfone-by-drfone-ios/"><u>Unlocking iPhone 11 Pro Max Lock Screen 3 Foolproof Methods that Actually Work | Dr.fone</u></a></li>
</ul></div>

