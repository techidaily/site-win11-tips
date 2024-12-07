---
title: Demystifying the Intricaciplinary Workings of Windows Policy Settings (3 Ways)
date: 2024-12-01T16:30:44.978Z
updated: 2024-12-06T22:41:36.678Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Demystifying the Intricaciplinary Workings of Windows Policy Settings (3 Ways)
excerpt: This Article Describes Demystifying the Intricaciplinary Workings of Windows Policy Settings (3 Ways)
keywords: Window's Policy Guide,Policies in Windows,Deciphering Windows Rules,Unraveling System Permissions,Understanding Win Settings,Exploring OS Privileges,Decoding Windows Regulations
thumbnail: https://thmb.techidaily.com/8dec14c118d7ee81f46eabd3dcf3a5188bbf56bf80fdef23b5e5cacf3addecc5.jpg
---

## Demystifying the Intricaciplinary Workings of Windows Policy Settings (3 Ways)

 The Local Group Policy is a tool that allows you to easily manage a wide range of system settings, from the appearance of the desktop to the security of the operating system. At times, you may need to review the policies applied to your Windows computer, either for troubleshooting purposes or to ensure that your system is configured correctly.

 This guide will walk you through three quick and easy ways to view applied group policies on your Windows 10 or 11 PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to View Applied Group Policies Using the Sort or Filter Options in Local Group Policy Editor

 The Local Group Policy Editor on Windows allows you to organize policies by their current state, so you can quickly see which ones are enabled or disabled.

 Use one of the [many ways to open the Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) on your PC. Then, use the left pane to head to **Computer Configuration > Administrative Templates > All Settings**. On your right, you will see a list of policies. Click the **State** column to sort policies based on their current status.

![Sort Group Policies on Windows by Their State](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/sort-group-policies-on-windows-by-their-state.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K7fATC_lI7o?si=UFotPJqflDRZr-mv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once the Group Policy Editor sorts all the policies, you can review or modify them as you see fit.

 Another way to see applied policies based on specific criteria is to use the filter option in the Local Group Policy Editor. This can be useful if you want to see all the applied policies in a particular area or folder.

 Simply right-click on a folder in the Local Group Policy Editor and select **Filter Options**. In the following window, select **Yes** in the **Configured** drop-down menu and click **OK**. After that, the Group Policy Editor will only show the folders and policies you have applied.

![Filter Group Policies on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/filter-group-policies-on-windows.jpg)

## 2\. How to View Applied Group Policies Using the Resultant Set of Policy Tool

 Windows also has a specialized tool called Resultant Set of Policy (RSoP), which shows all the group policies that have been applied to a user or computer. This tool eliminates the need to sort and filter policies in the Group Policy Editor.

 Press **Win + S** to open the search menu. Type **rsop.msc** in the box and press **Enter**. Wait for the Resultant Set of Policy tool to start [scanning your system for group policies on Windows](https://www.makeuseof.com/find-group-policy-windows/) that are applied.

![Resultant Set of Policy Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/resultant-set-of-policy-window.jpg)

 The management console has a similar appearance to the Local Group Policy Editor. However, it will only show policies that have been applied. You can double-click a setting to view more information.

![View Applied Policies in Resultant Set of Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/view-applied-policies-in-resultant-set-of-policy.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Jfq2Wx1Bcs?si=YQrYpTy0g4aV5QaO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##

 It is important to note that the Resultant Set of Policy tool does not allow you to modify any policies. To do that, you will need to use the Local Group Policy Editor.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gyGoQi7hsZk?si=8OcKcPUj2wSBmVZ1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. How to View Applied Group Policies With PowerShell

 Another method for determining which policies are applied to a Windows user or computer involves using PowerShell. If you are someone who prefers using command-line tools to interact or make changes to your computer, this method can come in handy.

 To view applied group policies using PowerShell, use these steps:

1. Press **Win + S** to open the search menu.
2. Type **powershell** in the text box and select **Run as administrator**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Type the following command in the PowerShell window and press **Enter**:  
`gpresult /Scope User /v`  
![See Applied Policies for a User on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/see-applied-policies-for-a-user-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=EdMRoNAFi0Q6mP7G" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you run the above command, you will see all the applied policies under the **Resultant Set Of Policies for User** section. If you want to view all policies applied to the computer, use the following command instead:

`gpresult /Scope Computer /v`

 For more useful commands, make sure to check our guide on the [best PowerShell commands for Windows](https://www.makeuseof.com/windows-powershell-commands-cmdlets/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LI9nKlbhnw8?si=uUXFVbuEqXtFHHv0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Checking the Applied Group Policies on Windows Is Easy

 Knowing how to check the policies applied to your Windows computer can be useful when troubleshooting issues with a program or feature, or when you have concerns about your privacy or security. Fortunately, doing so is a breeze with the methods mentioned above.

 This guide will walk you through three quick and easy ways to view applied group policies on your Windows 10 or 11 PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-files.techidaily.com/updated-in-2024-how-to-flawlessly-merge-streamlabs-and-obs-on-mac/"><u>[Updated] In 2024, How to Flawlessly Merge Streamlabs & OBS on Mac</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-premier-10plus-free-video-intro-creators-for-2024/"><u>[Updated] Premier 10+ Free Video Intro Creators for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-overcoming-iphone-lens-focus-discrepancies/"><u>2024 Approved Overcoming iPhone Lens Focus Discrepancies</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/boost-your-pc-experience-download-the-microsoft-wireless-mouse-5000-drivers-today/"><u>Boost Your PC Experience - Download the Microsoft Wireless Mouse 5000 Drivers Today!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-11s-advanced-setup/"><u>Decoding Windows 11'S Advanced Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-windows-error-unresponsive-audio-device-stopped/"><u>Eradicating Windows Error: Unresponsive Audio Device Stopped</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-gpresult-the-ultimate-gpo-report-tool/"><u>Exploring GPResult: The Ultimate GPO Report Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/game-gateway-3-steps-to-direct-folder-entry-on-pc/"><u>Game Gateway: 3 Steps to Direct Folder Entry on PC</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-oppo-a1-5g-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Oppo A1 5G? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-apple-iphone-15-drfone-by-drfone-virtual-ios/"><u>How To Teleport Your GPS Location On Apple iPhone 15? | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-apple-iphone-11-drfone-by-drfone-virtual-ios/"><u>In 2024, Unova Stone Pokémon Go Evolution List and How Catch Them For Apple iPhone 11 | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-is-a-sim-network-unlock-pin-get-your-motorola-moto-g34-5g-phone-network-ready-by-drfone-android/"><u>In 2024, What Is a SIM Network Unlock PIN? Get Your Motorola Moto G34 5G Phone Network-Ready</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/in-depth-analysis-of-the-180hz-titan-army-p27a2g-a-savvy-buyers-guide-for-gamers/"><u>In-Depth Analysis of the 180Hz Titan Army P27A2G - A Savvy Buyer's Guide for Gamers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-missing-display-configurations-on-nvidia/"><u>Overcoming Missing Display Configurations on Nvidia</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-image-previews-top-4-win-friendly-viewers/"><u>Perfecting Image Previews: Top 4 Win-Friendly Viewers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-ms-teams-error-80080300-on-windows-11-a-guide/"><u>Resolving MS Teams Error 80080300 on Windows 11: A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-windows-11-remedy-six-steps-to-resurrect-lost-panes/"><u>The Ultimate Windows 11 Remedy: Six Steps to Resurrect Lost Panes</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    