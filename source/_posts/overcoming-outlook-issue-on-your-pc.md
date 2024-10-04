---
title: Overcoming Outlook Issue on Your PC
date: 2024-10-02T23:32:58.429Z
updated: 2024-10-04T01:17:21.373Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Outlook Issue on Your PC
excerpt: This Article Describes Overcoming Outlook Issue on Your PC
keywords: Fix Outlook Errors,Resolve Outlook Crashes,Stop Outlook Freezing,Eliminate Outlook Glitches,Solve Outlook Sync Issue,Correct Outlook Login Failure,Prevent Outlook Data Loss
thumbnail: https://thmb.techidaily.com/a131e22df3df2377fb881bb5a1b4cf5042cfae5314bdf30aa6391ae79d2a6b0c.jpg
---

## Overcoming Outlook Issue on Your PC

 Microsoft Outlook's somewhat vague "Something went wrong" error message may appear when you are trying to set up your account or using the app in general. Without a clear indication of what’s going wrong, fixing such Outlook errors can be tricky.

 To help out, we have listed all the possible ways to fix the “Something went wrong” error in Outlook for Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Edit Registry Files

 Autodiscover is a nifty feature that allows Outlook to automatically configure email account settings without requiring manual input from the user. If this service receives any unexpected results from the third-party web server, Outlook might display the "Something went wrong" error message. To resolve this, you will need to make a few changes to the registry files on your PC.

 As you may be aware, making incorrect changes to the registry files can render your system inoperable. Hence, it is advisable to [back up all of your registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Paste the following path in the address bar at the top and press **Enter** to quickly navigate to the **AutoDiscover** key.  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Office\XX.0\Outlook\AutoDiscover`  
 Replace **XX.0** in the above path with your version of Office (**16.0** \= Office 365, Office 2019, and Office 2016, **15.0** \= Office 2013).
5. Right-click on the **AutoDiscover** key and select **New > DWORD (32-bit) Value**.  
![Create DWORD in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-dword-in-registry.jpg)

1. Rename the DWORD to **ExcludeHttpsRootDomain**.
2. Double-click the newly created DWORD and set its value to **1**.
3. Right-click on the **AutoDiscover** key again and select **New > DWORD (32-bit) Value**. Name the DWORD **ExcludeHttpsAutoDiscoverDomain**.
4. Double-click the **ExcludeHttpsAutoDiscoverDomain** DWORD and set its value to **1**.
5. Create two more DWORD values named **ExcludeSrvRecord** and **ExcludeLastKnownGoodUrl** and set their values to **1**.  
![AutoDiscover in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/autodiscover-in-registry-editor.jpg)

 Restart your PC after this and check if you still get the “Something went wrong” error in Microsoft Outlook.

## 2\. Open Outlook in Safe Mode

 At times, third-party add-ins in Outlook can disrupt app processes and trigger such errors. To verify if this is the case, you can [try starting Outlook in safe mode](https://www.makeuseof.com/outlook-safe-mode/).

 If Outlook works as expected, it means one of your add-ins is causing the issue. To find the culprit, you'll need to disable all the add-ins and re-enable them one at a time. Here are the steps for the same.

1. In the Outlook app, click on **File > Options**.
2. In the **Outlook Options** window, select the **Add-ins** tab from the left sidebar.
3. Click the **Go** button next to **COM Add-ins**.
4. Clear all the checkboxes to disable your add-ins and then click **OK**.  
![Disable Outlook Add-Ins-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-outlook-add-ins-1.jpg)

 Restart the Outlook app and enable your add-ins one by one until the error occurs again. Once you find the troublesome add-in, consider removing it to avoid such issues.

## 3\. Clear the Outlook Cache

 Outdated or corrupted cache data can cause Outlook to misbehave and display unusual errors. If this is the cause of your problems, clearing the Outlook app cache should get things going again. To do so, use these steps:

1. Press **Win + R** to open the Run command (see [how to open the Windows Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more information).
2. Type **%localappdata%\\Microsoft\\Outlook** in the text box and press **Enter**.
3. In the **RoamCache** folder that opens, press **Ctrl + A** to select all the files, and click the **trash** icon at the top to delete them.  
![Delete Outlook Cache Data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-outlook-cache-data.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997690/19272" target="_top" id="1997690">
  <img src="//a.impactradius-go.com/display-ad/19272-1997690" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997690/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Repair Your Outlook Profile

 Another reason why you may get the “Something went wrong” error in Outlook is if there is an issue with your Outlook profile. You can try repairing your Outlook profile to see if that restores normalcy. Here are the steps for the same.

1. Open the Outlook app and click the **File** menu at the top.
2. In the Info tab, click on **Account Settings** and select **Account Settings**.
3. Select your profile under the **Email** tab and click **Repair**.  
![Repair Outlook Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-outlook-account.jpg)

 Allow Outlook to repair your profile and then restart the app.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151854/7443" target="_top" id="2151854">
  <img src="//a.impactradius-go.com/display-ad/7443-2151854" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151854/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Remove and Re-Add Your Account

 If repairing your Outlook profile does not help, your next best option is to remove your email account from the Outlook app and add it back. Here's how to do it.

1. Open the Outlook app.
2. Navigate to **File > Info > Account Settings > Account Settings**.
3. Under the **Email** tab, select your account and click **Remove**.
4. Select **Yes** to continue.  
![Remove Outlook Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/remove-outlook-account.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148638/16836" target="_top" id="2148638">
  <img src="//a.impactradius-go.com/display-ad/16836-2148638" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148638/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once removed, click the **New** option under the **Email** tab and set up your account again.

## 6\. Remove Outlook Password From Credential Manager

 Are you getting the "Something went wrong" error while adding an account in Outlook? That might be caused by outdated data in the [Credential Manager](https://www.makeuseof.com/windows-credential-manager-guide/). You can try removing any Outlook entries from the Credential Manager to fix the issue.

1. Click the **magnifying icon** on the taskbar.
2. Type **credential manager** in the box and select the first result that appears.
3. Select **Windows Credentials**.
4. Select the entry related to your account and click **Remove**.  
![Remove Outlook Credentials From Windows PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/remove-outlook-credentials-from-windows-pc.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135416/19272" target="_top" id="2135416">
  <img src="//a.impactradius-go.com/display-ad/19272-2135416" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135416/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Run the Office Repair Tool

 Running Microsoft’s Office repair tool is an effective way to resolve issues with Office apps like Outlook. So, if the above tips don't help, you can run the Office repair tool as a last resort.

1. Press **Win + S** to open the search menu.
2. Type **Control Panel** in the box and press **Enter**.
3. Click the drop-down menu in the top right corner to select **Large icons**.
4. Click on **Programs and Features**.
5. Select **Microsoft Office suite** on the list and click the **Change** button at the top.
6. Select the **Quick Repair** option.
7. Click the **Repair** button.  
![Repair Microsoft Office](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-microsoft-office.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105867/7443" target="_top" id="2105867">
  <img src="//a.impactradius-go.com/display-ad/7443-2105867" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105867/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the problem persists even after this, repeat the above steps to perform an **Online Repair**. This process may take a little longer, but it’s most likely to resolve the issue.

## Fixing Outlook's “Something Went Wrong” Error on Windows

 Encountering such errors in the Outlook app can affect your productivity and leave you frustrated. We hope that the solutions listed above have helped in resolving the “Something went wrong” error in Microsoft Outlook.

 That said, if all of the above tips prove ineffective, we recommend you contact the official Microsoft support team for further assistance.

 To help out, we have listed all the possible ways to fix the “Something went wrong” error in Outlook for Windows.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-approaches.techidaily.com/updated-mastering-close-ups-quick-minecraft-enhancements/"><u>[Updated] Mastering Close-Ups Quick Minecraft Enhancements</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-the-ultimate-ios-screenshoting-hack-for-2024/"><u>[Updated] The Ultimate iOS Screenshoting Hack for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-a-comprehensive-examination-of-lg-27ud68-display-tech/"><u>2024 Approved A Comprehensive Examination of LG 27UD68 Display Tech</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-elite-nine-cutting-edge-4k-filmmaking-gear/"><u>2024 Approved Elite Nine Cutting-Edge 4K Filmmaking Gear</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/all-you-need-to-know-about-mega-greninja-for-xiaomi-14-ultra-drfone-by-drfone-virtual-android/"><u>All You Need To Know About Mega Greninja For Xiaomi 14 Ultra | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/comprehensive-guide-downloading-and-updating-windows-compatible-hp-laptop-drivers/"><u>Comprehensive Guide: Downloading & Updating Windows-Compatible HP Laptop Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/displaying-d-drive-on-explorer-navigation-pane/"><u>Displaying D: Drive on Explorer Navigation Pane</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-use-of-function-fn-button-in-windows-os/"><u>Efficient Use of Function (Fn) Button in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-multipurpose-close-on-modern-windows-pcs/"><u>Effortless Multipurpose Close on Modern Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-correctly-transfer-and-import-apple-images-in-windows/"><u>How to Correctly Transfer and Import Apple Images in Windows</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-becoming-a-pro-in-spotify-ad-deals/"><u>In 2024, Becoming a Pro in Spotify Ad Deals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/introducing-advanced-firewall-configurations-for-windows-11/"><u>Introducing Advanced Firewall Configurations for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-nuances-of-user-rights-management-in-windows/"><u>Navigating the Nuances of User Rights Management in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-accessing-and-leaving-focus-in-windows-terminal/"><u>Quick Guide to Accessing & Leaving Focus in Windows Terminal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-marketplace-failure-0x80131500/"><u>Resolving Windows Marketplace Failure #0X80131500</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-tip-erase-spotlight-icons-on-win11/"><u>Tech Tip: Erase Spotlight Icons on Win11</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-guide-resolving-issues-with-final-exam-platform-launches/"><u>Troubleshooting Guide: Resolving Issues with Final Exam Platform Launches</u></a></li>
<li><a href="https://some-guidance.techidaily.com/troubleshooting-steps-for-resolving-airdrop-problems-in-macos-monterey-and-iphone-15/"><u>Troubleshooting Steps for Resolving AirDrop Problems in macOS Monterey and iPhone 15</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-elevate-your-video-storytelling-with-professional-voiceovers/"><u>Updated In 2024, Elevate Your Video Storytelling with Professional Voiceovers</u></a></li>
</ul></div>

