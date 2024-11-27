---
title: Eliminating Vital Components Failures on Windows 10&11
date: 2024-11-21T16:46:45.523Z
updated: 2024-11-27T17:58:34.590Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminating Vital Components Failures on Windows 10&11
excerpt: This Article Describes Eliminating Vital Components Failures on Windows 10&11
keywords: Win10+11 Error Reduction,Windows Fixes Critical Issues,Boot Stability Enhancement,System Reliability Improvement,OS Vulnerability Mitigation,PC Crash Prevention,Failures Remediation Windows
thumbnail: https://thmb.techidaily.com/e703390679e2e9d8302a199135d745cf8f0f1e64473e58f7a002cd7e0675d8bb.jpg
---

## Eliminating Vital Components Failures on Windows 10&11

 Some users have posted on software (or gaming) support forums about an error message that says, “the following components are required to run this program.” The error message also specifies the component to be either Visual C++ or DirectX Runtime.

 This error typically occurs when users try to launch Windows games. Consequently, players cannot play games for which the “following components are required” error occurs. This is how you can fix the “following components are required” error on a Windows 10 or 11 PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RBN1gYY5hUs?si=p89CMiMzeJzU0wGu&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Check for and Install Any Pending Windows Updates

![The Check for updates option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-for-updates.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_7AYCS7zBU0?si=7R9oIpE4hyEbtk3x&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 First, try checking for and installing all pending Windows patch updates. This is because some updates will feature fixes for DirectX, so if the error message points to DirectX as the culprit, this will hopefully put it to rest.

 Check out [how to update Windows manually](https://www.makeuseof.com/update-windows-manually/) and ensure your PC is on the latest build.

## 2\. Repair Visual C++ Packages on Your PC

 The “following components are required” error often complains about missing Visual C++ or DirectX runtimes. If it specifies a missing Visual C++ runtime, you may need to repair your PC's version of Visual C++.

 So, try repairing the installed Visual C++ packages on your PC like this:

1. Press **Win + I** to open Settings.
2. Select the **Apps** category or tab and click **Apps & Features** from there.
3. Click the **three-dot button** beside the Visual C++ package version specified in the error message and select **Modify**. In Windows 10, you will need to select a Visual C++ package and click **Modify**.  
![The Modify option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/modify-option.jpg)
4. Select the **Repair** option in the Visual C++ window that opens.  
![The Repair option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-repair-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/q4-YQ9Wjtfg?si=6afn1fydg_Wb9B8z&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Install the 2015-2022 Visual Studio C++ Packages

 If repairing doesn’t work, or you can’t find the Visual C++ package specified in the error, you may need to install missing C++ runtime libraries. Microsoft has a webpage from which you can download numerous different C++ Redistributable packages.

 Try downloading and installing C++ runtimes from the Visual Studio 2015-2022 package as follows:

1. Open this [Visual C++ Redistributable](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170) page.
2. Then click the X64 (64-bit) architecture download link for Visual Studio 2015-2022.  
![The x64 download link for Visual Studio 2015-2022](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-x64-link.jpg)
3. Click **I agree** \> **Install** in the Microsoft Visual C++ 2015-2022 window.  
![The Install option for Visual C++](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-install-button.jpg)
4. Repeat steps two and three to download and install the 32-bit version of Visual Studio 2015-2022\. To do so, you’ll need to click on the X86 download link for Visual Studio 2015-2022\.

## 4\. Install DirectX Runtime Libraries

 If the error message mentions DirectX, that means your PC might be missing DirectX runtime components required for a game. That’s more likely to be the case if you’re trying to play an older game on a Windows 11/10 PC.

 In which case, try installing missing legacy DirectX runtime libraries with the DirectX End-User Runtime Web Installer as follows:

1. Open this [DirectX installer webpage](https://www.microsoft.com/en-gb/download/details.aspx?id=35) and download the file to your PC.
2. Next, double-click **dxwebsetup.exe**.
3. Select **I accept the agreement** inside the "Installing Microsoft DirectX" window.  
![The I accept the agreement radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-i-accept-radio-button.jpg)
4. Click **Next** to proceed to an offer for installing a Bing Bar.
5. Uncheck the **Install the Bing Bar** checkbox if you don’t want that software.  
![The Install the Bing Bar checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-install-bing-bar-option.jpg)
6. Select **Next** to install the required DirectX components.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aRMCbJxLuwE?si=E5sfJvoqkv1qCMWz&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Repair .NET Framework Components

![The Repair option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-repair-option.jpg)

 Users have confirmed they fixed the “following components are required” error by reinstalling .NET Framework components. Thus, you might need to repair .NET Framework components on your PC to resolve the “following components are required” error.

 Check out [how to repair the .NET Framework](https://www.makeuseof.com/windows-repair-net-framework/) for more information.

## 6\. Verify the Affected Game Within Your Game Launcher

![The Verify option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-verify-option.jpg)

 A few users say verifying games’ files works for fixing the “following components are required” error. You can only perform this step if you bought and downloaded the game using one of the big game launcher apps, such as Steam, Epic Games, EA Desktop, and Origin.

 If you're unsure how to do this, check out [how to repair game files on different launchers](https://www.makeuseof.com/how-to-verify-game-file-integrity-different-launchers/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 7\. Reinstall the Affected Game or Software

 If the “following components are required” issue continues after applying all fixes above, reinstalling the game or software is the last thing to try. Some players might be concerned about losing saved data for games after reinstalling them. However, you can [back up saved game progress](https://www.makeuseof.com/tag/protect-your-game-saves/#:~:text=To%20turn%20on%20cloud%20saves,keep%20it%20in%20the%20cloud.) before uninstalling titles in different ways.

 Reinstalling games or any other software this error affects is worth a try since that will restore any missing files. You can uninstall some games via **Programs and Features** as covered in our guide to [uninstalling Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/). If you don’t see the game listed there, you’ll probably have to uninstall it via its client software, such as Epic Games.

![The Programs and Features applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/programs-and-features.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9wiIVztRIqQ?si=GBgdwQ78k5hbeFDv&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Then reinstall the latest version of the game by downloading it from its official site. If installed with Steam or Epic, or other launcher software, you’ll need to select to reinstall the game via its gaming client. Or reinstall the game from its Microsoft Store page if that’s where you purchased it.

 Also, note that some players have been able to resolve the “following components are required” error by reinstalling Steam. So, reinstalling that client software might be worth a try if you need to fix this issue for Steam games.

## Kick-Start Your Windows Games Again

 Lots of users have needed to fix the “following components are required” error, and they have done so by applying the potential resolutions outlined above. So, at least one of those potential solutions will likely kick-start your affected Windows games.

 However, we can’t guarantee those potential resolutions will always fix the “following components are required” error. Check whether an affected game has a technical support service you can contact for further troubleshooting guidance if needed. If this error occurs for a new game, consider requesting a refund for it while you still can.

 This error typically occurs when users try to launch Windows games. Consequently, players cannot play games for which the “following components are required” error occurs. This is how you can fix the “following components are required” error on a Windows 10 or 11 PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-clips.techidaily.com/dissecting-the-financial-lifeblood-of-tseries-via-youtube-engagement-for-2024/"><u>Dissecting the Financial Lifeblood of TSeries via YouTube Engagement for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-data-maintenance-in-windows-10-and-11/"><u>Effortless Data Maintenance in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elite-selection-of-windows-based-nintendo-switch-imitations/"><u>Elite Selection of Windows-Based Nintendo Switch Imitations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-common-windows-error-0x80072f8f-0x20000/"><u>Fixing Common Windows Error: 0X80072f8f-0x20000</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-vivo-y28-5g-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your Vivo Y28 5G Location Settings | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/innovative-photography-adding-stylish-borders-to-instagram-pics/"><u>Innovative Photography Adding Stylish Borders to Instagram Pics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-system-resources-boosting-android-studio-on-windows/"><u>Leveraging System Resources: Boosting Android Studio on Windows</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/r-the-motion-personalized-animation-techniques/"><u>Master the Motion Personalized Animation Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-connectivity-assurance-on-your-pc/"><u>Mastering Connectivity Assurance on Your PC</u></a></li>
<li><a href="https://discover-alternatives.techidaily.com/mastering-the-art-of-vob-conversion-tips-for-handling-all-dvd-types/"><u>Mastering the Art of VOB Conversion: Tips for Handling All DVD Types</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-through-chrome-time-discreprancies-windows/"><u>Navigate Through Chrome Time Discreprancies (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/separate-cloud-storage-onedrive-from-microsoft-id-on-pcs/"><u>Separate Cloud Storage (OneDrive) From Microsoft ID on PCs</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-fix-for-nonfunctional-qualcomm-atheros-bluetooth-in-windows-10/"><u>Step-by-Step Fix for Nonfunctional Qualcomm Atheros Bluetooth in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncover-the-ultimate-password-solutions-on-your-pc-with-these-tools/"><u>Uncover the Ultimate Password Solutions on Your PC with These Tools</u></a></li>
<li><a href="https://fox-glue.techidaily.com/understanding-diverse-flavors-in-windows-movie-maker/"><u>Understanding Diverse Flavors in Windows Movie Maker</u></a></li>
<li><a href="https://common-error.techidaily.com/unfreeze-gameplay-easy-steps-to-smooth-computer-gaming/"><u>Unfreeze Gameplay: Easy Steps to Smooth Computer Gaming</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/upcoming-apple-indoor-robot-speculation-prospective-price-tag-release-date-insights-and-detailed-hardware-review/"><u>Upcoming Apple Indoor Robot Speculation: Prospective Price Tag, Release Date Insights & Detailed Hardware Review</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    