---
title: Tackling 'Multiple Instances' Problem in Windows
date: 2025-01-17T16:01:46.075Z
updated: 2025-01-18T17:21:07.359Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling 'Multiple Instances' Problem in Windows
excerpt: This Article Describes Tackling 'Multiple Instances' Problem in Windows
keywords: WinMSI Solutions,Multiple Instances Handling,Windows Duplicate Fix,MSI Issue Resolution,MSI Error Mitigation,Dual Instance Strategies,Unique OS Applications
thumbnail: https://thmb.techidaily.com/503d593f9428317b9217e37989fa613e5c3305adb6e8017e4b8755b0efa649e5.png
---

## Tackling 'Multiple Instances' Problem in Windows

 It's frustrating when you can't launch your favorite apps and programs on Windows due to the "Side-by-side configuration is incorrect" error. While determining the exact cause of this error can be difficult, it is possible to resolve it.

 In most cases, the “Side-by-side configuration is incorrect” error occurs due to a damaged Visual C++ package or a compatibility issue. However, there can be other reasons for it. So, what can you do to resolve this unforeseen error on Windows? Let's find out.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Reinstall Microsoft Visual C++ Packages

 Problems with the current Visual C++ packages on your PC can often result in the “Side-by-side configuration is incorrect” error on Windows. If that's the case, you must reinstall the problematic Visual C++ package on your computer. To do so, you'll need to find its version number using Event Viewer. Here's how you can go about it.

1. Press**Win + S** to open the search menu.
2. Type**event viewer** in the search box and select the first result that appears.
3. Use the left pane to navigate to**Custom Views > Summary page events** .  
![Event Viewer on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Event-Viewer-on-Windows.jpg)
4. Choose the most recent side-by-side error from the middle pane and note down the version number under the**General** tab.

5. Open up your web browser and head over to the[Microsoft Visual C++ Redistributable download page](https://learn.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170) .
6. Download and install the Visual C++ package corresponding to your version number.

 Restart your PC after this (see[how to restart your Windows PC](https://www.makeuseof.com/windows-restart-methods/) ) and try to launch your app or program one more time.

## 2\. Run the SFC and DISM Scans

 Corrupted or missing system files on your computer can also trigger such errors. Fortunately, Windows includes a useful command-line utility called SFC (or System File Checker) scan for such occasions. It can automatically detect any damaged system files on your PC and replace them with their cached versions.

To run the SFC scan on your computer:

1. Press**Win + X** to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt shows up.
4. In the console, type**sfc /scannow** and press**Enter** .  
![Run SFC Scan on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Run-SFC-Scan-on-Windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Wait for the scan to complete and then run the DISM (or Deployment Image Servicing and Management) scan by entering the following command:

`DISM.exe /Online /Cleanup-image /Restorehealth`

 After the process is complete, exit the Command Prompt window and restart your PC. The error should not appear anymore after the reboot.

## 3\. Run the Program Compatibility Troubleshooter

 If the “Side-by-side configuration is incorrect” error only appears when you try to launch a specific program, you can run the program compatibility troubleshooter on Windows. It’ll try to fix any compatibility issues with your program and help you fix the error. Here’s how you can run it.

1. Right-click on your app or program that’s producing the error and select**Troubleshoot compatibility** .
2. In the Program Compatibility Troubleshooter window, select**Troubleshoot program** .
3. Mark the checkbox that reads **The program worked in earlier versions of Windows but won’t install or run now** and hit**Next** .
4. Follow the on-screen prompts to run the troubleshooter and see if the error occurs again.  
![Program Compatibility Troubleshooter Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Program-Compatibility-Troubleshooter-Windows.jpg)

## 4\. Repair the Problematic App

 If the Windows troubleshooter fails to find any problems, you can try repairing the problematic app on Windows. Here's how to do it.

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Apps** tab.
3. Go to**Installed apps** .
4. Scroll down to locate the problematic app on the list. Click the**three-dot menu icon** next to it and select**Advanced options** .
5. Scroll down to the Reset section and click on**Repair** .  
![Repair App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Repair-App-on-Windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Dn-24B6AURY?si=ErES2KWVnintY6h9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You should see a right checkmark next to the Repair button once the process is complete.

 Alternatively, you can repair your apps and programs from Control Panel. To learn more about this, check our guide on[how to repair apps and programs on Windows](https://www.makeuseof.com/windows-repair-apps-programs/) and follow the steps outlined there.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SDUPd69Qfls?si=uIGZG-riskwmVZYg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Reinstall the Problematic App

 Repairing the app may not help much if the existing app data is corrupted or missing. In that case, your only option is to uninstall the problematic app and install it again.

1. Press**Win + S** to open the search menu.
2. Type in the name of your app or program and select**Uninstall** from the right pane.
3. Select**Uninstall** again to confirm.  
![Uninstall App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Uninstall-App-on-Windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OZQJUTr44rA?si=ADA0nD1VnXjR_sH0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Head over to Microsoft Store and install the app again. Following this, the error should not bother you.

## 6\. Scan for Malware

 If your computer is infected with malware, you may encounter such errors when launching apps and programs. To check for this possibility, you can run a full system scan of your PC with Windows Defender. You can also use one of the[best third-party antivirus programs for Windows](https://www.makeuseof.com/tag/best-antivirus-for-windows-10/) for this.

 If the scan uncovers anything suspicious, take the recommended steps to fix the issue and reboot your PC after that.

## 7\. Install Pending Windows Updates

 Microsoft regularly releases updates for the Windows operating system. Aside from new features and security patches, these updates also bring much-needed fixes for bugs and other errors. You can try updating Windows to its most recent version to see if that makes a difference.

 Press**Win + I** to open the Settings app and navigate to the**Windows Update** section. Click on**Check for updates** to download and install pending updates.

![Check for System Updates on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Check-for-System-Updates-on-Windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UcplMvRBulA?si=iBonbwDS1v7RAlHK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 8\. Perform a System Restore

 Windows System Restore performs a backup of the entire system on a regular basis. You can use it to revert your system to a point before the error first started appearing.

To perform a system restore on Windows:

1. Press**Win + R** to open the Run dialog box.
2. Type**sysdm.cpl** in the box and press**Enter** .
3. In the System Properties window, switch to the**System Protection** tab.
4. Click on**System Restore** .
5. Click**Next** .
6. Select a restore point before the first appeared and hit**Next** .
7. Check all the details and hit**Finish** .  
![System Restore Dialog on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/System-Restore-Dialog-on-Windows.jpg)

 Windows will restart and revert to the specified restore point. Following that, the error should be resolved.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zWYVKFk3yPQ?si=Yu7xsjIYgRiq8zHk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Start Using Your Apps Again

 By applying the above fixes, you should be able to fix the “Side-by-side configuration is incorrect” error in no time. However, if none of the solutions work, you may have to reset your Windows computer as a last resort.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/n-2024-understanding-and-exploiting-youtubes-featured-slot-for-maximum-reach/"><u>[New] In 2024, Understanding and Exploiting YouTube's Featured Slot for Maximum Reach</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-step-by-step-guide-to-brighter-youtube-video-editing/"><u>[New] Step-by-Step Guide to Brighter YouTube Video Editing</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-picture-perfect-in-the-sky-free-and-paid-cloud-solutions-reviewed-for-2024/"><u>[Updated] Picture Perfect in the Sky Free & Paid Cloud Solutions Reviewed for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-real-time-unfollowers-detection-on-insta/"><u>[Updated] Real-Time Unfollowers Detection on Insta</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-inside-ustream-review-alternatives-on-hand/"><u>2024 Approved Inside Ustream Review, Alternatives on Hand</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-best-free-methods-for-transforming-your-avi-files-into-a-playable-dvd-format/"><u>5 Best Free Methods for Transforming Your AVI Files Into a Playable DVD Format</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cambia-tu-fotografia-de-alta-calidad-sin-costo-convertir-raw-a-tiff-en-linea-mediante-imagemaster-pro/"><u>Cambia Tu Fotografía De Alta Calidad Sin Costo: Convertir RAW a TIFF en Línea Mediante ImageMaster Pro</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-itel-phone-without-any-data-loss-by-drfone-android/"><u>How to Unlock Itel Phone without Any Data Loss</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-the-step-by-step-pathway-to-youtube-mastery/"><u>In 2024, The Step-by-Step Pathway to YouTube Mastery</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-transformative-visuals-unleash-the-power-of-6-video-types/"><u>In 2024, Transformative Visuals Unleash the Power of 6 Video Types</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-cloud-storage-enhance-your-data-management-with-centrum-podpory/"><u>Movavi Cloud Storage: Enhance Your Data Management with Centrum Podpory</u></a></li>
<li><a href="https://win11-tips.techidaily.com/online-wijzer-om-gratis-raam-in-wmv-formaat-te-veranderen-de-meest-gewone-movavi-oplage/"><u>Online Wijzer Om Gratis RAAM in WMV Formaat Te Veranderen - De Meest Gewone Movavi Oplage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-and-simple-guide-to-downloading-mp3s-from-your-videos-gratis/"><u>Quick and Simple Guide to Downloading MP3s From Your Videos, Gratis!</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-complete-pathway-to-personalized-ios-ringtones-for-2024/"><u>The Complete Pathway to Personalized iOS Ringtones for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformation-gratuite-de-fichiers-wmv-a-la-norme-vob-sur-internet-avec-movavi/"><u>Transformation Gratuite De Fichiers WMV À La Norme VOB Sur Internet Avec Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tv-mp4avi-mpe/"><u>오토바이오어 TV를 전자보간용 영상으로 자유소부터 MP4/AVI 변환 - MPE</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movaviwebm-to-ogg/"><u>ウィスパーオーディオファイルにリアルタイム変換! - Movaviの無料オンラインWEBM to OGG</u></a></li>
</ul></div>

