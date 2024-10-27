---
title: How to Fix Unsaved Windows Run Actions
date: 2024-10-24T00:02:31.387Z
updated: 2024-10-26T22:27:07.815Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix Unsaved Windows Run Actions
excerpt: This Article Describes How to Fix Unsaved Windows Run Actions
keywords: Save Windows Run Actions,Fixing Unsaved Run Commands,Resetting Windows Runs Errors,Reverting Failed Window Executions,Correct Unsaved Windows Inputs,Mend Missed Run Scripts,Restore Screensaver Actions
thumbnail: https://thmb.techidaily.com/f2d53ebba5315caabb937b6a02076182259db722e8470506c861929020be203d.jpg
---

## How to Fix Unsaved Windows Run Actions

 The Run command dialog box in Windows makes it easy to launch apps, access system tools, and perform various other tasks. It also has an auto-complete feature that makes it easy to re-use your commands later. However, the auto-complete feature in the Run tool may not work if it fails to save your command history in the first place.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Check Your Privacy Settings

 A common reason why Windows may not save the Run command history is if you have previously blocked it from tracking your app launches. Here’s how you can change that.

1. Press **Win + I** to open the Settings app.
2. Select **Privacy & security** from the left sidebar.
3. Under Windows permissions, click on **General**.
4. Enable the toggle next to **Let Windows improve Start and search results by tracking app launches**.  
![Allow Windows to Track App Launches on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-windows-to-track-app-launches-on-windows.jpg)

 After completing the above steps, try running a few commands via the Run dialog box. Then, check if it is saving your command history and providing auto-complete suggestions.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130530/26400" target="_top" id="2130530">
  <img src="//a.impactradius-go.com/display-ad/26400-2130530" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130530/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Edit Registry Files

 Is the **Let Windows improve Start and search results by tracking app launches** option grayed out on your PC? If so, you can take help from the Registry Editor to get Windows to save your Run command history.

 As you may already be aware, registry files on your PC store essential settings for Windows and its services. Making incorrect modifications to these files can render your system inoperable. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Click the search icon on the taskbar or press the **Win + S** keyboard shortcut to open the search menu.
2. Type **registry editor** in the search box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > Advanced**.
5. Locate the **Start\_TrackProgs** entry in the right pane. If you can’t find it, right-click on the **Advanced** key and select **New > DWORD (32-bit) Value**. Rename it to **Start\_TrackProgs**.
6. Double-click the newly created DWORD and enter **1** in the **Value data** field.
7. Click **OK**.  
![Edit Registry DWORD on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-registry-dword-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137972/21526" target="_top" id="2137972">
  <img src="//a.impactradius-go.com/display-ad/21526-2137972" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137972/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Restart your PC after this for the changes to take effect. Following this, the Run command should start saving your history on Windows.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118305/7443" target="_top" id="2118305">
  <img src="//a.impactradius-go.com/display-ad/7443-2118305" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118305/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Apply Generic Fixes

 If the problem persists even after implementing the above tips, you can try applying some basic fixes to resolve the underlying issue.

* **Restart Your PC:** This may appear rudimentary, but temporary OS-related glitches can sometimes cause such anomalies. If it’s nothing major, [restarting your PC](https://www.makeuseof.com/windows-restart-methods/) should fix any issues with the Run command.
* **Run an SFC Scan:** Such issues can also arise if some of the critical system files on your PC are corrupt. [Running a System File Checker (SFC) scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) can help detect and repair any damaged system files on your PC.
* **Scan for Malware:** It’s possible that your system is infected by malware, which is why the Run command is having trouble saving your history. To rule out this possibility, you can [scan Windows for malware using PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or Windows Defender.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151859/7443" target="_top" id="2151859">
  <img src="//a.impactradius-go.com/display-ad/7443-2151859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151859/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get the Run Tool to Save Your History on Windows

 It can be inconvenient if the Run command dialog box stops saving your history on Windows. Hopefully, one of the solutions provided above has successfully resolved the issue for you.

 If you feel that the Run utility in Windows lacks advanced features, you can always switch to alternative tools like Run-Command or PowerToys Run.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-recordings.techidaily.com/new-story-keepers-at-the-click-no-limits-allowed-for-2024/"><u>[New] Story Keepers at the Click, No Limits Allowed for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-creative-reactors-the-10-premier-video-responses/"><u>[Updated] 2024 Approved Creative Reactors The 10 Premier Video Responses</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-how-instagram-algorithm-update-will-affect-you/"><u>[Updated] 2024 Approved How Instagram Algorithm Update Will Affect You</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-crafting-the-best-video-aspect-ratio-experience/"><u>[Updated] Crafting the Best Video Aspect Ratio Experience</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-snap-edit-share-your-initial-guide-to-lunapic/"><u>[Updated] In 2024, Snap, Edit, Share Your Initial Guide to LunaPic</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-mac-enthusiasts-take-on-screenflow-software-review/"><u>2024 Approved Mac Enthusiast's Take on ScreenFlow Software Review</u></a></li>
<li><a href="https://buynow-info.techidaily.com/discover-luxe-setup-agg814-studio-kit-overview/"><u>Discover Luxe Setup: AGG814 Studio Kit Overview</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-techniques-for-leveraging-windows-11s-start-screen/"><u>Essential Techniques for Leveraging Windows 11'S Start Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-active-directory-print-failures-on-windows-11-os/"><u>Fixing Active Directory Print Failures on Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/initiating-your-systems-inner-workings/"><u>Initiating Your System's Inner Workings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-your-gaming-experience-on-windows-hardware/"><u>Optimizing Your Gaming Experience on Windows Hardware</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successfully-installing-oddworld-soulstorm-on-your-windows-computer/"><u>Successfully Installing Oddworld: Soulstorm on Your Windows Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-pc-display-rgb-control-guide-for-win11/"><u>Tailoring Your PC Display: RGB Control Guide for Win11</u></a></li>
<li><a href="https://video-capture.techidaily.com/the-new-wave-of-fbx-free-gaming-analysis-tools-for-2024/"><u>The New Wave of FBX-Free Gaming Analysis Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-windows-steam-link-issues-effectively/"><u>Unblocking Windows Steam Link Issues Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unite-windows-devices-for-streamlined-transcoding-operations-using-tdarr/"><u>Unite Windows Devices for Streamlined Transcoding Operations Using Tdarr</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-hidden-gems-of-windows-11-mouse-settings/"><u>Unveiling the Hidden Gems of Windows 11 Mouse Settings</u></a></li>
</ul></div>

