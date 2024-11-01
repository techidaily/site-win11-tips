---
title: Troubleshooting Outlook Error in Windows Environments
date: 2024-10-29T16:32:57.741Z
updated: 2024-11-01T19:21:42.613Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Outlook Error in Windows Environments
excerpt: This Article Describes Troubleshooting Outlook Error in Windows Environments
keywords: WinOutlookErrorSolve,OutlookWinFixTips,FixWindowsEmailIssue,ResolveOfficeErrors,OvercomeOutlookWins,TroubleshootExchangeOS,WindowsMailTroubleResolution
thumbnail: https://thmb.techidaily.com/32b091bb5633d3a9c4c2a4da4b60ec3b4374fdb769db4d47d5b0ac420926fc16.jpg
---

## Troubleshooting Outlook Error in Windows Environments

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068433/7443" target="_top" id="2068433">
  <img src="//a.impactradius-go.com/display-ad/7443-2068433" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068433/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Clear the Outlook Cache

 Outdated or corrupted cache data can cause Outlook to misbehave and display unusual errors. If this is the cause of your problems, clearing the Outlook app cache should get things going again. To do so, use these steps:

1. Press **Win + R** to open the Run command (see [how to open the Windows Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more information).
2. Type **%localappdata%\\Microsoft\\Outlook** in the text box and press **Enter**.
3. In the **RoamCache** folder that opens, press **Ctrl + A** to select all the files, and click the **trash** icon at the top to delete them.  
![Delete Outlook Cache Data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-outlook-cache-data.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118312/7443" target="_top" id="2118312">
  <img src="//a.impactradius-go.com/display-ad/7443-2118312" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118312/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Repair Your Outlook Profile

 Another reason why you may get the “Something went wrong” error in Outlook is if there is an issue with your Outlook profile. You can try repairing your Outlook profile to see if that restores normalcy. Here are the steps for the same.

1. Open the Outlook app and click the **File** menu at the top.
2. In the Info tab, click on **Account Settings** and select **Account Settings**.
3. Select your profile under the **Email** tab and click **Repair**.  
![Repair Outlook Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-outlook-account.jpg)

<!-- affiliate ads begin -->
<span id="1975636">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975636.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975636">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975636.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975636%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975636/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Allow Outlook to repair your profile and then restart the app.

<!-- affiliate ads begin -->
<span id="1983582">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983582.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983582">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983582.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983582%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983582/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Remove and Re-Add Your Account

 If repairing your Outlook profile does not help, your next best option is to remove your email account from the Outlook app and add it back. Here's how to do it.

1. Open the Outlook app.
2. Navigate to **File > Info > Account Settings > Account Settings**.
3. Under the **Email** tab, select your account and click **Remove**.
4. Select **Yes** to continue.  
![Remove Outlook Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/remove-outlook-account.jpg)

 Once removed, click the **New** option under the **Email** tab and set up your account again.

## 6\. Remove Outlook Password From Credential Manager

 Are you getting the "Something went wrong" error while adding an account in Outlook? That might be caused by outdated data in the [Credential Manager](https://www.makeuseof.com/windows-credential-manager-guide/). You can try removing any Outlook entries from the Credential Manager to fix the issue.

1. Click the **magnifying icon** on the taskbar.
2. Type **credential manager** in the box and select the first result that appears.
3. Select **Windows Credentials**.
4. Select the entry related to your account and click **Remove**.  
![Remove Outlook Credentials From Windows PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/remove-outlook-credentials-from-windows-pc.jpg)

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

 If the problem persists even after this, repeat the above steps to perform an **Online Repair**. This process may take a little longer, but it’s most likely to resolve the issue.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151872/7443" target="_top" id="2151872">
  <img src="//a.impactradius-go.com/display-ad/7443-2151872" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151872/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Fixing Outlook's “Something Went Wrong” Error on Windows

 Encountering such errors in the Outlook app can affect your productivity and leave you frustrated. We hope that the solutions listed above have helped in resolving the “Something went wrong” error in Microsoft Outlook.

 That said, if all of the above tips prove ineffective, we recommend you contact the official Microsoft support team for further assistance.

 To help out, we have listed all the possible ways to fix the “Something went wrong” error in Outlook for Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://snapchat-videos.techidaily.com/new-two-easy-steps-for-altering-snapchats-audio-effects/"><u>[New] Two Easy Steps for Altering Snapchat's Audio Effects</u></a></li>
<li><a href="https://discover-extraordinary.techidaily.com/3-simple-fixes-when-goodnotes-and-macos-dont-sync-easy-troubleshooting/"><u>3 Simple Fixes When GoodNotes and MacOS Don't Sync - Easy Troubleshooting</u></a></li>
<li><a href="https://win-amazing.techidaily.com/boost-gaming-results-with-an-updated-asus-radeon-r9-fury-x/"><u>Boost Gaming Results with an Updated ASUS Radeon R9 Fury X</u></a></li>
<li><a href="https://extra-hints.techidaily.com/complete-analysis-of-theta-ss-advanced-tech-for-2024/"><u>Complete Analysis of Theta S's Advanced Tech for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-and-remedying-error-0x8007000d-on-pcs/"><u>Deciphering and Remedying 'Error 0X8007000D' On PCs</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/68197795-direct-youtube-tunes-to-mp3s-online-and-offline-options/"><u>Direct YouTube Tunes to MP3s Online & Offline Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-add-trusted-sites-on-windows-11/"><u>How to Add Trusted Sites on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-inactive-wsreset-troubleshooting-steps/"><u>Navigating Through Inactive WSReset Troubleshooting Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-based-thx-audio-glitches/"><u>Overcoming Windows-Based THX Audio Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-keyboard-use-redefine-functionality-via-fn-keys-on-windows-11/"><u>Revolutionize Keyboard Use: Redefine Functionality via FN Keys on Windows 11</u></a></li>
<li><a href="https://win-answers.techidaily.com/top-strategies-for-converting-mov-videos-to-mp4-with-windows-10-a-comprehensive-how-to/"><u>Top Strategies for Converting MOV Videos to MP4 with Windows 10 - A Comprehensive How-To</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-of-windows-drives-c-and-d/"><u>Unraveling the Mystery of Windows Drives (C & D)</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    