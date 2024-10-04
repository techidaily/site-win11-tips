---
title: Recovering Deleted Execution Records on Windows
date: 2024-10-02T21:12:49.679Z
updated: 2024-10-03T19:31:10.930Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Recovering Deleted Execution Records on Windows
excerpt: This Article Describes Recovering Deleted Execution Records on Windows
keywords: Windows Data Recovery,Deleted Files Restore,Executable File Recovery,Recover Deleted Execs,Windows System Logs Fix,Executable History Reinstate,Permanent Data Retrieval,Windows Recover Deletion,Recover Exec Files WIN,Data Restoration Windows,Execute Logs Recovery,Fix Deleted Exec Files,Recover WIN Execution,Permanent Recovery Tools
thumbnail: https://thmb.techidaily.com/151496d9a19ba95beb3641cc868ae237a3532fbd921c881e6672274d100dff06.jpg
---

## Recovering Deleted Execution Records on Windows

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
<a href="https://appsumo.8odi.net/c/5597632/2151864/7443" target="_top" id="2151864">
  <img src="//a.impactradius-go.com/display-ad/7443-2151864" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151864/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1993650">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Restart your PC after this for the changes to take effect. Following this, the Run command should start saving your history on Windows.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151873/7443" target="_top" id="2151873">
  <img src="//a.impactradius-go.com/display-ad/7443-2151873" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151873/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Apply Generic Fixes

 If the problem persists even after implementing the above tips, you can try applying some basic fixes to resolve the underlying issue.

* **Restart Your PC:** This may appear rudimentary, but temporary OS-related glitches can sometimes cause such anomalies. If it’s nothing major, [restarting your PC](https://www.makeuseof.com/windows-restart-methods/) should fix any issues with the Run command.
* **Run an SFC Scan:** Such issues can also arise if some of the critical system files on your PC are corrupt. [Running a System File Checker (SFC) scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) can help detect and repair any damaged system files on your PC.
* **Scan for Malware:** It’s possible that your system is infected by malware, which is why the Run command is having trouble saving your history. To rule out this possibility, you can [scan Windows for malware using PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or Windows Defender.

<!-- affiliate ads begin -->
<span id="1976998">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1976998.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1976998">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1976998.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1976998%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1976998/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-novice-cinematographers-initial-work-analysis-and-replacements/"><u>[New] 2024 Approved Novice Cinematographer's Initial Work Analysis & Replacements</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-immersive-windows-display-snapshots/"><u>[New] Immersive Windows Display Snapshots</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-unveiling-the-best-practices-for-uploading-videos-to-instagram-for-2024/"><u>[Updated] Unveiling the Best Practices for Uploading Videos to Instagram for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/4-solutions-to-fix-unfortunately-your-app-has-stopped-error-on-vivo-x-flip-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Solutions to Fix Unfortunately Your App Has Stopped Error on Vivo X Flip | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/direct-download-methods-for-newcomers-to-windows/"><u>Direct Download Methods for Newcomers to Windows</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/discovering-the-power-of-fraps-in-video-capture-for-2024/"><u>Discovering the Power of Fraps in Video Capture for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-google-pixel-8-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From Google Pixel 8 to iPhone | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/propel-your-productivity-key-strategies-with-windows-11/"><u>Propel Your Productivity: Key Strategies with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrecting-off-screen-windows-6-steps-for-win11/"><u>Resurrecting Off-Screen Windows: 6 Steps for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-windows-files-with-top-tricks-max-156/"><u>Simplify Windows Files with Top Tricks (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stabilizing-the-sweep-of-your-cursor-deactivating-mouse-accel-in-win-11/"><u>Stabilizing the Sweep of Your Cursor: Deactivating Mouse Accel in Win 11</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-steps-resolving-sound-issues-with-zoom-on-your-computer/"><u>Troubleshooting Steps: Resolving Sound Issues with Zoom on Your Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-sound-system-enhancement-through-drivers-update-tutorial/"><u>Windows Sound System Enhancement Through Drivers Update Tutorial</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1726224857848-bmp-movavi/"><u>オンラインで無料に！BMP画像をプログレスグードファイルに簡単変換 - Movavi</u></a></li>
</ul></div>

