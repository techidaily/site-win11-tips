---
title: How to Fix Unsaved Windows Run Actions
date: 2024-10-13T22:35:58.493Z
updated: 2024-10-21T00:45:12.784Z
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137203/26400" target="_top" id="2137203">
  <img src="//a.impactradius-go.com/display-ad/26400-2137203" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137203/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2115932/19272" target="_top" id="2115932">
  <img src="//a.impactradius-go.com/display-ad/19272-2115932" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115932/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Restart your PC after this for the changes to take effect. Following this, the Run command should start saving your history on Windows.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012429/19272" target="_top" id="2012429">
  <img src="//a.impactradius-go.com/display-ad/19272-2012429" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012429/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Apply Generic Fixes

 If the problem persists even after implementing the above tips, you can try applying some basic fixes to resolve the underlying issue.

* **Restart Your PC:** This may appear rudimentary, but temporary OS-related glitches can sometimes cause such anomalies. If it’s nothing major, [restarting your PC](https://www.makeuseof.com/windows-restart-methods/) should fix any issues with the Run command.
* **Run an SFC Scan:** Such issues can also arise if some of the critical system files on your PC are corrupt. [Running a System File Checker (SFC) scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) can help detect and repair any damaged system files on your PC.
* **Scan for Malware:** It’s possible that your system is infected by malware, which is why the Run command is having trouble saving your history. To rule out this possibility, you can [scan Windows for malware using PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or Windows Defender.

<!-- affiliate ads begin -->
<span id="1975648">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975648.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975648">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975648.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975648%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975648/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get the Run Tool to Save Your History on Windows

 It can be inconvenient if the Run command dialog box stops saving your history on Windows. Hopefully, one of the solutions provided above has successfully resolved the issue for you.

 If you feel that the Run utility in Windows lacks advanced features, you can always switch to alternative tools like Run-Command or PowerToys Run.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-hints.techidaily.com/updated-amc-explorer-ghost-drift-cam-analysis/"><u>[Updated] AMC Explorer Ghost Drift Cam Analysis</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-free-software-less-method-to-save-youtube-videos/"><u>[Updated] Free Software-Less Method to Save YouTube Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-windows-cant-detect-network-proxies/"><u>Correcting Windows Can't Detect Network Proxies</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-remove-or-bypass-knox-enrollment-service-on-nokia-g42-5g-by-drfone-android/"><u>In 2024, How To Remove or Bypass Knox Enrollment Service On Nokia G42 5G</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-share-location-in-messenger-on-vivo-y77t-drfone-by-drfone-virtual-android/"><u>In 2024, How to Share Location in Messenger On Vivo Y77t? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-windows-11s-video-call-problem-code-1132/"><u>Mending Windows 11'S Video Call Problem: Code 1132</u></a></li>
<li><a href="https://sound-issues.techidaily.com/resolving-issues-with-your-hyperx-cloud-alpha-headset-mic-a-comprehensive-guide/"><u>Resolving Issues with Your HyperX Cloud Alpha Headset Mic: A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-wmps-server-failure-error/"><u>Resolving WMP's Server Failure Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-frozen-photoapp-win11-edition-photoshop-not-opening/"><u>Reviving Frozen PhotoApp, Win11 Edition (Photoshop) Not Opening</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-web-safety-filters-in-win-1011/"><u>Setting up Web Safety Filters in Win 10/11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/stepping-stones-from-youtube-ads-to-monetary-success-for-2024/"><u>Stepping Stones From YouTube Ads to Monetary Success for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-art-of-animated-text-in-video-landscapes-for-2024/"><u>The Art of Animated Text in Video Landscapes for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-complete-guide-to-vivo-v30-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>The Complete Guide to Vivo V30 FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://win11-tips.techidaily.com/triumph-over-error-0x80242016-during-updates/"><u>Triumph Over Error 0X80242016 During Updates</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-genuine-adobe-on-pc/"><u>Troubleshooting Non-Genuine Adobe on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-potential-the-top-5-wsl-2-tips/"><u>Unlocking Potential: The Top 5 WSL 2 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-hardware-acceleration-and-cooling-policies/"><u>Windows Hardware Acceleration and Cooling Policies</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    