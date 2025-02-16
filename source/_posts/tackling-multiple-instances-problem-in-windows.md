---
title: Tackling 'Multiple Instances' Problem in Windows
date: 2025-02-12T16:05:02.787Z
updated: 2025-02-16T02:19:30.637Z
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

 Wait for the scan to complete and then run the DISM (or Deployment Image Servicing and Management) scan by entering the following command:

`DISM.exe /Online /Cleanup-image /Restorehealth`

 After the process is complete, exit the Command Prompt window and restart your PC. The error should not appear anymore after the reboot.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

 You should see a right checkmark next to the Repair button once the process is complete.

 Alternatively, you can repair your apps and programs from Control Panel. To learn more about this, check our guide on[how to repair apps and programs on Windows](https://www.makeuseof.com/windows-repair-apps-programs/) and follow the steps outlined there.

## 5\. Reinstall the Problematic App

 Repairing the app may not help much if the existing app data is corrupted or missing. In that case, your only option is to uninstall the problematic app and install it again.

1. Press**Win + S** to open the search menu.
2. Type in the name of your app or program and select**Uninstall** from the right pane.
3. Select**Uninstall** again to confirm.  
![Uninstall App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Uninstall-App-on-Windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Head over to Microsoft Store and install the app again. Following this, the error should not bother you.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/poI1NQxHfjc?si=ZLG0wziYcTKIKwL5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Scan for Malware

 If your computer is infected with malware, you may encounter such errors when launching apps and programs. To check for this possibility, you can run a full system scan of your PC with Windows Defender. You can also use one of the[best third-party antivirus programs for Windows](https://www.makeuseof.com/tag/best-antivirus-for-windows-10/) for this.

 If the scan uncovers anything suspicious, take the recommended steps to fix the issue and reboot your PC after that.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aIx71tPaWKg?si=lG5OiUe-M6eBJf5b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 7\. Install Pending Windows Updates

 Microsoft regularly releases updates for the Windows operating system. Aside from new features and security patches, these updates also bring much-needed fixes for bugs and other errors. You can try updating Windows to its most recent version to see if that makes a difference.

 Press**Win + I** to open the Settings app and navigate to the**Windows Update** section. Click on**Check for updates** to download and install pending updates.

![Check for System Updates on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Check-for-System-Updates-on-Windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nmj7aVvEeAs?si=OcR7USXKGyLcn09q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-blurring-the-focus-bokeh-wonders-in-stories/"><u>[New] 2024 Approved Blurring the Focus Bokeh Wonders in Stories</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-fine-tuning-your-fly-top-tips-for-choosing-drone-propellers/"><u>[New] Fine-Tuning Your Fly Top Tips for Choosing Drone Propellers</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-auditory-purity-in-ffmpeg-a-format-friendly-perspective/"><u>[Updated] 2024 Approved Auditory Purity in FFmpeg A Format-Friendly Perspective</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-full-spectrum-review-exploring-digital-performances-evolution/"><u>[Updated] 2024 Approved Full Spectrum Review Exploring Digital Performance's Evolution</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-your-guide-to-the-top-5-chromebook-sniping-software/"><u>[Updated] Your Guide to the Top 5 Chromebook Sniping Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/establishing-custom-default-typography-setting-standard-fonts-and-sizes-in-new-excel-sheets/"><u>Establishing Custom Default Typography: Setting Standard Fonts & Sizes in New Excel Sheets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/excel-tutorial-building-your-first-radar-chart-from-scratch/"><u>Excel Tutorial: Building Your First Radar Chart From Scratch</u></a></li>
<li><a href="https://win-forum.techidaily.com/expert-advice-how-to-clean-up-your-windows-email-protected-with-revouninstaller/"><u>Expert Advice: How to Clean Up Your Windows ^[Email Protected] With RevoUninstaller</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/full-guide-on-mirroring-your-oppo-reno-11f-5g-to-your-pcmac-drfone-by-drfone-android/"><u>Full Guide on Mirroring Your Oppo Reno 11F 5G to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-clustering-multiple-pie-graphs-together-in-microsoft-excel-easily-and-accurately/"><u>Guide to Clustering Multiple Pie Graphs Together in Microsoft Excel Easily and Accurately</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-how-to-implement-mac-os-x-quick-look-functionality-in-windows/"><u>Guide: How to Implement Mac OS X Quick Look Functionality in Windows</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-create-an-apple-developer-account-on-apple-iphone-12-pro-max-by-drfone-ios/"><u>In 2024, How To Create an Apple Developer Account On Apple iPhone 12 Pro Max</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-data-representation-crafting-graphs-using-microsoft-excel-tutorials/"><u>Mastering Data Representation: Crafting Graphs Using Microsoft Excel Tutorials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-excel-macros-streamline-your-workflow-and-eliminate-repetitive-chores/"><u>Mastering Excel Macros: Streamline Your Workflow and Eliminate Repetitive Chores</u></a></li>
</ul></div>

