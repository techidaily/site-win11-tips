---
title: Decoding the Window's Rule Book Through 3 Views
date: 2024-12-01T00:49:18.392Z
updated: 2024-12-06T18:25:41.501Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Decoding the Window's Rule Book Through 3 Views
excerpt: This Article Describes Decoding the Window's Rule Book Through 3 Views
keywords: Windows SEO Guide,Decoding Window Rules,Window Usage Insights,Understanding Windows Views,Mastering Window SEO,Exploring Windows Rules,Key to Windows Optimization
thumbnail: https://thmb.techidaily.com/2c72878e4c5b851b7d621c520b7075b9d80e911d0e1db9a60b0603055e403b62.jpg
---

## Decoding the Window's Rule Book Through 3 Views

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/YB7Ou4-iKVM?si=7Fq8iUwI8voccMLx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once the Group Policy Editor sorts all the policies, you can review or modify them as you see fit.

 Another way to see applied policies based on specific criteria is to use the filter option in the Local Group Policy Editor. This can be useful if you want to see all the applied policies in a particular area or folder.

 Simply right-click on a folder in the Local Group Policy Editor and select **Filter Options**. In the following window, select **Yes** in the **Configured** drop-down menu and click **OK**. After that, the Group Policy Editor will only show the folders and policies you have applied.

![Filter Group Policies on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/filter-group-policies-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-G7cU8dYvuI?si=JaKqRcW6qq9CDvty" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to View Applied Group Policies Using the Resultant Set of Policy Tool

 Windows also has a specialized tool called Resultant Set of Policy (RSoP), which shows all the group policies that have been applied to a user or computer. This tool eliminates the need to sort and filter policies in the Group Policy Editor.

 Press **Win + S** to open the search menu. Type **rsop.msc** in the box and press **Enter**. Wait for the Resultant Set of Policy tool to start [scanning your system for group policies on Windows](https://www.makeuseof.com/find-group-policy-windows/) that are applied.

![Resultant Set of Policy Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/resultant-set-of-policy-window.jpg)

 The management console has a similar appearance to the Local Group Policy Editor. However, it will only show policies that have been applied. You can double-click a setting to view more information.

![View Applied Policies in Resultant Set of Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/view-applied-policies-in-resultant-set-of-policy.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##

 It is important to note that the Resultant Set of Policy tool does not allow you to modify any policies. To do that, you will need to use the Local Group Policy Editor.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you run the above command, you will see all the applied policies under the **Resultant Set Of Policies for User** section. If you want to view all policies applied to the computer, use the following command instead:

`gpresult /Scope Computer /v`

 For more useful commands, make sure to check our guide on the [best PowerShell commands for Windows](https://www.makeuseof.com/windows-powershell-commands-cmdlets/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Checking the Applied Group Policies on Windows Is Easy

 Knowing how to check the policies applied to your Windows computer can be useful when troubleshooting issues with a program or feature, or when you have concerns about your privacy or security. Fortunately, doing so is a breeze with the methods mentioned above.

 This guide will walk you through three quick and easy ways to view applied group policies on your Windows 10 or 11 PC.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-hovers.techidaily.com/new-discover-other-pc-video-editing-programs-for-2024/"><u>[New] Discover Other PC Video Editing Programs for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-zoom-in-to-speed-boosting-video-playback-mobileonline/"><u>[New] In 2024, Zoom in to Speed Boosting Video Playback (Mobile/Online)</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-inside-the-world-of-superior-screen-recording-with-recmeister/"><u>[Updated] Inside the World of Superior Screen Recording with Recmeister</u></a></li>
<li><a href="https://discover-comparisons.techidaily.com/creative-tims-top-tier-argon-theme-for-tailwind-ui-developers-superior-premium-control-panel-experience/"><u>Creative Tim's Top-Tier Argon Theme for Tailwind UI Developers: Superior Premium Control Panel Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-phantom-device-name-misidentification-on-win-11/"><u>Fixing Phantom Device Name Misidentification on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-halt-games-from-appearing-in-recommendations-on-windows-11/"><u>How To Halt Games From Appearing in Recommendations on Windows 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-fix-locked-apple-id-from-apple-iphone-x-by-drfone-ios/"><u>In 2024, How to Fix Locked Apple ID from Apple iPhone X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaiming-default-energy-profiles-in-windows-11/"><u>Reclaiming Default Energy Profiles in Windows 11</u></a></li>
<li><a href="https://tech-hub.techidaily.com/step-by-step-guide-setting-up-and-troubleshooting-miracast-on-windows-11/"><u>Step-by-Step Guide: Setting Up and Troubleshooting Miracast on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-overcome-malfunctioning-ccleaner-in-windows-1011/"><u>Techniques to Overcome Malfunctioning CCleaner in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-performance-potential-with-effective-directx-downloads-on-your-computer/"><u>Unlock Performance Potential with Effective DirectX Downloads on Your Computer</u></a></li>
<li><a href="https://facebook.techidaily.com/unlocking-brand-potential-with-a-company-profile-on-facebook-top-8-insights/"><u>Unlocking Brand Potential with a Company Profile on Facebook - Top 8 Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unwinding-error-code-1132-in-windows-zoom/"><u>Unwinding Error Code 1132 in Windows Zoom</u></a></li>
</ul></div>

