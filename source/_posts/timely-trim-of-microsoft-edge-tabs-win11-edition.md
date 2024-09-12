---
title: Timely Trim of Microsoft Edge Tabs, Win11 Edition
date: 2024-09-11T01:25:05.842Z
updated: 2024-09-12T01:25:05.842Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Timely Trim of Microsoft Edge Tabs, Win11 Edition
excerpt: This Article Describes Timely Trim of Microsoft Edge Tabs, Win11 Edition
keywords: Edge Tab Cleanup,Win11 Tab Reduce,Timely Edge Update,Microsoft Edge Tabs,EdTabs Trim,WinTabs Cleanup,Edge Optimization
thumbnail: https://thmb.techidaily.com/a5249e9b13fd437412102feed5c7841b8ccf98fdf0188fbbf3a215fd35680a08.JPG
---

## Timely Trim of Microsoft Edge Tabs, Win11 Edition

 Microsoft Edge is the default browser in Windows and comes pre-installed on the operating system without any easy way of getting rid of it. The browser uses "tab preloading," which preloads the Start and New Tab page while you sign in to your PC.

 For Edge lovers, it is a boon, but if you don’t use the default browser and prefer something else, it is a waste of resources. Fortunately, you can easily disable Edge's tab preloading in Windows 11\.


>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>







<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137215/26400" target="_top" id="2137215">
  <img src="//a.impactradius-go.com/display-ad/26400-2137215" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137215/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 1\. How to Disable Edge Tab Preloading Using the Group Policy Editor

 Windows Pro, Education, and Enterprise users get the perks of the Group Policy Editor by default. You can use it to configure system policies on your PC and personalize it. If you're on Windows Home, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

 Repeat the following steps to disable Edge tab preloading using the Group Policy Editor:

1. Press **Win + S** to open Windows Search. Type **gpedit.msc** in the text box and press the **Enter** key to open the Group Policy Editor.
2. Click on the **User Configuration** option in the left-hand side pane.
3. Navigate to **Administrative Templates > Windows Components > Microsoft Edge**.
4. Find the “**Allow Microsoft Edge to start and load the Start and New Tab page at Windows startup and each time Microsoft Edge is closed**” policy. Right-click on it and select the **Edit** option from the context menu.  
![Disable Microsoft Edge Tab Preloading Using GPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-gpe.jpg)
5. Click on the **Enabled** radio button.




<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139107/17108" target="_top" id="2139107">
  <img src="//a.impactradius-go.com/display-ad/17108-2139107" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139107/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




6. Scroll down and click on the drop-down list next to the **Configure tab preloading** option. Select the **Prevent tab preloading** option.
7. Click on the **Apply** button. Then click on the **OK** button to save the changes.  
![Disable Microsoft Edge Tab Preloading Using GPE 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-gpe-2.jpg)
8. **Exit** the Group Policy Editor window.
9. **Restart** your PC for the policy changes to take effect and disable the tab preloading feature.

## 2\. How to Disable Edge Tab Preloading Using the Registry Editor

 If you use the Home version of Windows 11, it may be easier to take a different approach instead of going through the Group Policy Editor method. If you want, you can tweak the registry manually to disable the Edge tab preloading feature in Windows 11\. Repeat the following steps to do so:

 Before making changes to the Windows Registry, [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) for safety purposes.

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **regedit** in the text box and press the **Enter** key.
2. Go to the address bar at the top and click on it. Paste the following path in the text box and press the **Enter** key:  
HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\Main
3. Go to the right-hand side section and right-click on the empty area. Select **New > DWORD (32-bit) Value**.
4. Click on the newly created DWORD value and name it “**AllowPrelaunch**”.
5. Right-click on the **AllowPrelaunch** value and select the **Modify** option from the context menu.
6. Go to the **Value Data** field and type **0** in it. Set the **Base** to **Hexadecimal** and click on the **OK** button.  
![Disable Microsoft Edge Tab Preloading Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-registry-editor.jpg)

 Now, you need to create a new subkey and add a new DWORD value:

1. Right-click on the Microsoft Edge key and select the **New > Key** option.
2. Name the key “**TabPreloader**” and click on it to select it.
3. Go to the right-hand side section and right-click on it. Select **New > DWORD (32-bit) Value**.
4. Click on the DWORD value and name it “**AllowTabPreloading**”.
5. Right-click on the **AllowTabPreloading** value and select the **Modify** option.
6. Go to the **Value Data** field and type **0** in it. Set the **Base** to **Hexadecimal** and click on the **OK** button.  
![Disable Microsoft Edge Tab Preloading Using Registry Editor 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-registry-editor-2.jpg)
7. **Close** the Registry Editor window.




<!-- affiliate ads begin -->
<span id="1982462">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982462.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982462">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982462.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982462%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982462/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




8. **Restart** your PC to apply the changes made to the registry.





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118322/7443" target="_top" id="2118322">
  <img src="//a.impactradius-go.com/display-ad/7443-2118322" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118322/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 3\. How to Disable Edge Tab Preloading Using CMD or PowerShell

 If you find the Registry Editor method too cumbersome, you can use the Command Prompt or PowerShell to modify the Registry and disable Edge tab preloading. Here’s how to do it:

1. [Open the Command Prompt with administrator privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) on your PC.
2. Execute the following commands to add two new registry entries:  
`reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\Main" /v AllowPrelaunch /t REG_DWORD /d 00000000 /f  
 reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\TabPreloader" /v AllowTabPreloading /t REG_DWORD /d 00000000 /f`
3. **Close** the Command Prompt window and **restart** your PC.  
![Disable Microsoft Edge Tab Preloading Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-cmd.jpg)





<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134234/18498" target="_top" id="2134234">
  <img src="//a.impactradius-go.com/display-ad/18498-2134234" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134234/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 4\. How to Disable Edge Tab Preloading Using the Ultimate Windows Tweaker App

 You can also use a third-party app like the Ultimate Windows Tweaker to disable Edge tab preloading in Windows 11\. Download the [Ultimate Windows Tweaker](https://www.thewindowsclub.com/ultimate-windows-tweaker-4-windows-10) app and install it on your PC. After that, repeat the following steps:

1. Press **Win + S** to open the Windows Search app. Type **Ultimate Windows Tweaker** and then click on the **Run as administrator** option.
2. Click on the **Search For Tweaks** option. Type “**edge tab**” in the search box and click on the **Go** button.  
![Disable Microsoft Edge Tab Preloading Using Ultimate Windows Tweaker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-ultimate-windows-tweaker.jpg)
3. Click on the **Disable Edge Tab Preloading** checkbox to enable it. Then, click on the **Apply Tweaks** button.  
![Disable Microsoft Edge Tab Preloading Using Ultimate Windows Tweaker 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-ultimate-windows-tweaker-2.jpg)
4. **Close** the Ultimate Windows Tweaker app and **restart** your PC to apply the changes.





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123740/7443" target="_top" id="2123740">
  <img src="//a.impactradius-go.com/display-ad/7443-2123740" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123740/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Disable Edge Tab Preloading for Good on Windows 11

 Edge tab preloading serves no useful purpose if you use other browsers. You can disable it using the Group Policy Editor or the Registry Editor. Lastly, if you want a GUI app to disable the feature, you can use the Ultimate Windows Tweaker app.

 For Edge lovers, it is a boon, but if you don’t use the default browser and prefer something else, it is a waste of resources. Fortunately, you can easily disable Edge's tab preloading in Windows 11\.





<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-copyright-woes-instant-video-ban/"><u>[New] In 2024, Copyright Woes Instant Video Ban</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-inspire-your-recruitment-process-with-pioneering-tapes/"><u>[Updated] Inspire Your Recruitment Process with Pioneering Tapes</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-save-money-save-time-the-best-22-audio-crackers-for-youtube-downloads/"><u>[Updated] Save Money, Save Time The Best 22 Audio Crackers for YouTube Downloads</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-sharpen-your-visual-storytelling-advanced-kinemaster-zoom-techniques/"><u>[Updated] Sharpen Your Visual Storytelling Advanced Kinemaster Zoom Techniques</u></a></li>
<li><a href="https://android-location-track.techidaily.com/2-ways-to-monitor-oneplus-11r-activity-drfone-by-drfone-virtual-android/"><u>2 Ways to Monitor OnePlus 11R Activity | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-turning-talk-into-top-tier-podcasts-writing-and-samples-included/"><u>2024 Approved Turning Talk Into Top-Tier Podcasts Writing & Samples Included</u></a></li>
<li><a href="https://win11-tips.techidaily.com/asus-bw-16d1x-u-blu-ray-burner-analysis-elegant-design-and-minor-imperfections/"><u>Asus BW-16D1X-U Blu-Ray Burner Analysis: Elegant Design & Minor Imperfections</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/dell-latitude-e6430-drivers-download-and-update-for-windows-solved/"><u>Dell Latitude E6430 Drivers Download & Update for Windows [SOLVED]</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-updater-error-0x80246007-in-windows-1011-os/"><u>Disabling Updater Error 0X80246007 in Windows 10/11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-audio-integrity-audacity-and-windows-interface/"><u>Enhancing Audio Integrity: Audacity & Windows Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-the-sinister-windows-c0000022-flaw/"><u>Eradicating the Sinister Windows C0000022 Flaw</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-blank-game-listings-on-windows-with-discord/"><u>Fixing Blank Game Listings on Windows with Discord</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/from-blurred-to-clean-picsarts-background-elimination/"><u>From Blurred to Clean Picsart's Background Elimination</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-latest-hp-spectre-x360-drivers-compatible-with-windows-full-set/"><u>Get the Latest HP Spectre X360 Drivers Compatible with Windows - Full Set!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hide-or-reveal-window-11s-clock-and-date/"><u>Hide or Reveal Window 11'S Clock & Date</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-configure-safe-storage-for-files-in-win1011/"><u>How to Configure Safe Storage for Files in Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-engage-clipboard-utility-within-microsoft-edges-app-guard-for-windows-11/"><u>How to Engage Clipboard Utility Within Microsoft Edge's App Guard for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-a-device-which-does-not-exist-was-specified-error-in-windows-11-and-11/"><u>How to Fix the “A Device Which Does Not Exist Was Specified” Error in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-halt-screen-flashes-on-windows-11-devices/"><u>How to Halt Screen Flashes on Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ical-on-windows-setup-for-a-cross-platform-schedule/"><u>ICal on Windows: Setup for a Cross-Platform Schedule</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-3-ways-for-android-pokemon-go-spoofing-on-motorola-g24-power-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways for Android Pokemon Go Spoofing On Motorola G24 Power | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-masterclass-adding-subtitles-as-chapter-indicators-on-youtube/"><u>In 2024, Masterclass Adding Subtitles as Chapter Indicators on YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innocuous-looking-apps-notorious-for-slowing-down-pcs/"><u>Innocuous-Looking Apps, Notorious for Slowing Down PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/inside-look-windows-command-center/"><u>Inside Look: Windows' Command Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-network-speed-into-system-ui/"><u>Integrating Network Speed Into System UI</u></a></li>
<li><a href="https://screen-capture.techidaily.com/key-tips-to-capture-youtube-streams-effectively-for-2024/"><u>Key Tips to Capture YouTube Streams Effectively for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-mouseclicklock-a-guide-to-smoother-windows-navigation/"><u>Mastering MouseClickLock: A Guide to Smoother Windows Navigation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-windows-11s-frozen-search-within-the-user-interface/"><u>Mending Windows 11'S Frozen Search Within the User Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-make-taskview-harder-to-find-in-win-11/"><u>Methods to Make TaskView Harder to Find in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-non-starting-display-on-windows-11-pc/"><u>Overcoming Non-Starting Display on Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-entry-not-found-error-in-windows/"><u>Quick Fix for Entry Not Found Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-steam-auth-timeout-in-rust/"><u>Quick Fix for Steam Auth Timeout in Rust</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-to-stop-vscode-from-crashing-w11/"><u>Quick Fixes to Stop VSCode From Crashing W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-tests-verifying-webcam-and-microphone-on-windows-pcs/"><u>Quick Tests: Verifying Webcam & Microphone on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-baseline-for-windows-11-terminal/"><u>Reinstating Baseline for Windows 11 Terminal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-built-in-keyboard-from-a-windows-machine/"><u>Removing Built-In Keyboard From a Windows Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-lsa-error-local-sec-admin-disabled-alert/"><u>Resolving LSA Error: Local Sec Admin Disabled Alert</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-error-resolution-in-windows-11s-setup-process/"><u>Simplifying Error Resolution in Windows 11'S Setup Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-implementing-windows-hello-fingerprints/"><u>Step-by-Step Guide: Implementing Windows Hello Fingerprints</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-solve-launch-failure-of-obs-studio/"><u>Strategies to Solve Launch Failure of OBS Studio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-storage-merging-files-on-windows-11/"><u>Streamlining Storage: Merging Files on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-made-win11-keys-personal-setup-guide/"><u>Tailor-Made Win11 Keys: Personal Setup Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-impact-of-ignoring-win-11-notification-pushes/"><u>The Impact of Ignoring Win 11 Notification Pushes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-power-of-shortcut-commands-with-windows-narrator/"><u>Unraveling the Power of Shortcut Commands with Windows Narrator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/window-wonders-find-the-best-8-video-trimmer-apps-here/"><u>Window Wonders: Find the Best 8 Video Trimmer Apps Here</u></a></li>
</ul></div>







<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    