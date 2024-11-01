---
title: "Tech Guru Guide: Free Up Space by Removing Windows' Temp"
date: 2024-10-25T18:03:18.183Z
updated: 2024-11-01T16:22:33.719Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tech Guru Guide: Free Up Space by Removing Windows' Temp"
excerpt: "This Article Describes Tech Guru Guide: Free Up Space by Removing Windows' Temp"
keywords: Tech Space Optimization,Free Temp Files Cleanup,Remove Windows Cache,Gadget Cleaning Guide,Speed Up PC Removal,Deletion Temp Files Guide,Free Space Optimization Tips
thumbnail: https://thmb.techidaily.com/c2d68683c182adeb644872ae9b6efd92813d48ae83b60547183327ca40ae4d54.jpg
---

## Tech Guru Guide: Free Up Space by Removing Windows' Temp

 Temporary files, as the name implies, aren’t meant to stick around on your Windows computer forever. Although Windows makes it simple to delete temporary files, there can be times when these files refuse to leave.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Use the Disk Cleanup Tool

[Windows offers several options for clearing temporary files](http://www.makeuseof.com/windows-11-delete-temporary-files/) on your PC. If you are unable to delete temporary files via the Settings app or File Explorer, try using the Disk Cleanup tool instead.

 Here are the steps you can follow:

1. Press **Win + S** to access the search menu.
2. Type **disk cleanup** in the box and press **Enter**.
3. Use the drop-down menu to select the drive from which you want to clear temporary files.
4. Click **OK**.
5. Under **Files to delete**, use the checkboxes to select the files you want to remove.
6. Click **OK** to proceed.
7. Click the **Delete Files** to confirm.  
![Delete Temp Files Using Disk Cleanup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-disk-cleanup.jpg)

 Wait for a few moments until the Disk Cleanup tool clears all the temporary files.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139115/17108" target="_top" id="2139115">
  <img src="//a.impactradius-go.com/display-ad/17108-2139115" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139115/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Use Command Prompt

 If the Disk Cleanup utility fails to delete some or all of the temporary files on Windows, you can try using the Command Prompt instead. Don’t worry, the process isn’t as complex as it might sound.

 Follow these steps to continue:

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt appears.
3. Copy and paste the following command into the console and hit **Enter**.  
del /q /f /s %temp%\* && del /s /q C:\Windows\temp\*  
![Delete Temp Files Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<span id="1374820">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1374820.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1374820">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1374820.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1374820%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1374820/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Wait for the above command to run and delete the temporary files.

## 3\. Empty the SoftwareDistribution Folder

 Windows saves all the downloaded update files in the SoftwareDistribution folder before installing them. If a [Windows system update gets stuck](https://www.makeuseof.com/tag/windows-update-stuck/), the OS will not delete the temporary files associated with it.

 To fix this, you can try emptying the SoftwareDistribution folder manually using these steps:

1. Press **Win + S** to open the search menu.
2. Type **services** in the box and press **Enter**.
3. In the Services window, locate the **Windows Update** service. Right-click on it and select **Stop**.
4. Press **Win + R** to open the Run dialog box.
5. Type the following path in the text field and hit **Enter**.  
C:\Windows\SoftwareDistribution\Download
6. In the File Explorer window, press **Ctrl + A** to select all the files and click the **trash icon** at the top to delete them.
7. Return to the Services window, right-click on the **Windows Update** service, and select **Start**.  
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/clear-softwaredistribution-folder.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918703/19272" target="_top" id="1918703">
  <img src="//a.impactradius-go.com/display-ad/19272-1918703" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918703/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you run into issues while emptying the SoftwareDistribution folder, you can [force delete files in Windows](https://www.makeuseof.com/windows-11-delete-stubborn-files/) using Command Prompt or a third-party tool.

## 4\. Edit Registry Files

 By default, the Disk Cleanup utility does not delete temporary files that are less than seven days old. This is because Windows marks these files as active. However, if you want to delete all the temporary files, regardless of their age, you can make changes to the Windows Registry.

 Since editing registry files is slightly risky, make sure to [back up all registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) as a precaution. Once done, follow these steps to edit registry files:

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > VolumeCaches > Temporary Files**.
5. In the right pane, double-click the **LastAccess** key.
6. Enter **0** in the Value data field.
7. Click **OK**.  
![Edit DWORD in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-dword-in-registry.jpg)

 Restart your PC after this and try to delete temporary files once again.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135410/19272" target="_top" id="2135410">
  <img src="//a.impactradius-go.com/display-ad/19272-2135410" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135410/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Boot Into Safe Mode

 It's possible that a third-party program or background service is preventing Windows from erasing temporary files on your system. Booting your PC in safe mode can help you avoid any interference, as Windows will only run with essential drivers and services.

 Use one of the many ways to [boot into safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) and try to delete temporary files one more time.

## Get Rid of Temporary Files on Windows

 Clearing temporary files is a great way to free up storage space without deleting any of your apps or important data.

 We hope that one of the above tips was helpful and you were able to delete the temporary files without any problems.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-hovers.techidaily.com/updated-unveiling-ace-video-capturers-guide-for-2024/"><u>[Updated] Unveiling Ace Video Capturers Guide for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-price-point-in-online-advertising/"><u>2024 Approved The Price Point in Online Advertising</u></a></li>
<li><a href="https://win11-tips.techidaily.com/descargue-e-importe-archivos-gratis-desde-jpg-a-png-con-convertidor-de-imagenes-online-movavi/"><u>Descargue E Importe Archivos Gratis Desde JPG a PNG Con Convertidor De Imágenes Online - Movavi</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-life360-shows-wrong-location-on-samsung-galaxy-z-fold-5-drfone-by-drfone-virtual-android/"><u>How to Fix Life360 Shows Wrong Location On Samsung Galaxy Z Fold 5? | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-quickly-fix-bluetooth-not-working-on-tecno-camon-20-premier-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Quickly Fix Bluetooth Not Working on Tecno Camon 20 Premier 5G | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-remove-screen-lock-pin-on-oneplus-ace-2-like-a-pro-5-easy-ways-by-drfone-android/"><u>How To Remove Screen Lock PIN On OnePlus Ace 2 Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-motorola-g24-power-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Motorola G24 Power to New Android? | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/leading-techniques-for-video-transformation-youtube-to-mpeg/"><u>Leading Techniques for Video Transformation - YouTube-to-MPEG</u></a></li>
<li><a href="https://fake-location.techidaily.com/methods-to-change-gps-location-on-samsung-galaxy-a15-5g-drfone-by-drfone-virtual-android/"><u>Methods to Change GPS Location On Samsung Galaxy A15 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-12-playermp3-di-file-audio-liberi-e-ottimizzati-per-windows-and-mac/"><u>Top 12 PlayerMP3 Di File Audio Liberi E Ottimizzati Per Windows & Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trasforma-i-file-flac-in-m4a-online-gratuitamente-con-convertitore-di-movavi/"><u>Trasforma I File Flac in M4A Online Gratuitamente Con Convertitore Di Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cr2-tiff-movavi/"><u>컴퓨터에서 무료 CR2 포트라이트를 TIFF로 전환하는 방법 - Movavi</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    