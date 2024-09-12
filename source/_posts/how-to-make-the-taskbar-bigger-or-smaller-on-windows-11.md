---
title: How to Make the Taskbar Bigger or Smaller on Windows 11
date: 2024-09-11T01:20:50.303Z
updated: 2024-09-12T01:20:50.303Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Make the Taskbar Bigger or Smaller on Windows 11
excerpt: This Article Describes How to Make the Taskbar Bigger or Smaller on Windows 11
keywords: Windows Taskbar Size Control,Resize Taskbar Windows 11,Adjusting Taskbar Width,Increase Taskbar Size Windows,Decrease Windows Taskbar,Enlarge WinTaskbar,Reduce Windows Bar Dimensions
thumbnail: https://thmb.techidaily.com/826e213581d156558e6f234936866c0f136b901791e5cc9453b472a1e6024dd2.jpeg
---

## How to Make the Taskbar Bigger or Smaller on Windows 11

 Ever looked at the Windows 11 Taskbar and thought it looks too small for your liking? Or maybe you feel it could be a little smaller? If that’s the case, you can change its size to suit your needs by making it bigger or smaller.

 Unlike Windows 10, you can’t just unlock the Taskbar and adjust its size freely in Windows 11\. While Microsoft has removed this way of going about it in Windows 11, there is a workaround that you can use, although it’s not as elegant.





<!-- affiliate ads begin -->
<span id="1983575">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983575.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983575">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983575.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983575%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983575/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## How Do I Make the Windows 11 Taskbar Bigger or Smaller?

 The only way to change the size of the Taskbar is to use the Registry Editor. However, we advise caution when dealing with the Windows Registry because if something goes wrong, you might experience performance issues on your Windows 11 PC. If you’re unfamiliar with it, we recommend reading our guides on[what the Windows Registry is](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) and[how to not mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/) .

 Once you’re all caught up or are already familiar with the Windows Registry, and you know what you’re doing, you can make the Taskbar bigger or smaller. To do that:

1. Start by pressing**Win + R** to open Windows Run.
2. Type**regedit** in the text box and hit the**Enter** key.
3. Then, click**Yes** on the UAC prompt to launch the Registry Editor.
4. Copy and paste the below text in the address bar of the Registry Editor and hit the**Enter** key:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. In the**Advanced** key, look for a value called**TaskbarSi** . If it’s not there, right-click**Advanced** , select**New > DWORD (32-bit) Value** , and name that value**TaskbarSi.**  
![creating a new dword in the advanced key in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/new-dword-advanced-regedit.jpg)
6. Double-click**TaskbarSi** to edit it, and then enter**2** in the**Value data** text box and click**OK** to make the Taskbar bigger.  




<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2126492/26400" target="_top" id="2126492">
  <img src="//a.impactradius-go.com/display-ad/26400-2126492" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2126492/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




![changing the taskbarsi value to 2 in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/taskbarsi-value-2.jpg)





<!-- affiliate ads begin -->
<span id="1374820">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1374820.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1374820">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1374820.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1374820%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1374820/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 Once you restart your computer, you will see the result: an enlarged Taskbar.

![an enlarged Taskbar on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-enlarged-taskbar.jpg)





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118319/7443" target="_top" id="2118319">
  <img src="//a.impactradius-go.com/display-ad/7443-2118319" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118319/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 To make the Taskbar smaller, enter**0** in the**Value data** text box, click**OK** , and then restart your computer. You will then see that the Taskbar has shrunk.

![a smaller taskbar in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-small-taskbar.jpg)





<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2126493/26400" target="_top" id="2126493">
  <img src="//a.impactradius-go.com/display-ad/26400-2126493" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2126493/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 If you decide to go back to the Taskbar’s default size, you can easily set**Value data** to**1** or simply delete the**TaskbarSi** value.





<!-- affiliate ads begin -->
<span id="2135472">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135472.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135472">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135472.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135472%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135472/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Adjust the Taskbar’s Size to Suit Your Needs on Windows 11

 Even though you can’t make the Taskbar bigger or smaller on Windows 11 as easily as you can on Windows 10, a little know-how can help. And as long as you followed the instructions mentioned above correctly, you shouldn’t worry about messing up the Windows Registry. However, we still recommend that you use this method only if you know what you’re doing.


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
<li><a href="https://video-screen-grab.techidaily.com/new-elite-firefox-screencap-add-ons/"><u>[New] Elite Firefox Screencap Add-Ons</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-10-premium-yoga-channels-for-ultimate-fitness-journey/"><u>[New] In 2024, 10 Premium Yoga Channels for Ultimate Fitness Journey</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-from-everyday-snaps-to-professional-videos-the-top-9-mobile-filmmaking-gadgets/"><u>[New] In 2024, From Everyday Snaps to Professional Videos - The Top 9 Mobile Filmmaking Gadgets</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-effortless-ways-to-grab-high-quality-images-at-no-cost/"><u>[Updated] 2024 Approved Effortless Ways To Grab High Quality Images at No Cost</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-elite-audio-modifying-tools-tailored-to-youtube-creators/"><u>[Updated] Elite Audio Modifying Tools Tailored to YouTube Creators</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-niche-marketing-through-periscope-broadcasts/"><u>[Updated] Niche Marketing Through Periscope Broadcasts</u></a></li>
<li><a href="https://unlock-android.techidaily.com/10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-nokia-c12-plus-by-drfone-android/"><u>10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Nokia C12 Plus</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-hiring-guide-locating-excellent-film-capturers/"><u>2024 Approved Hiring Guide Locating Excellent Film Capturers</u></a></li>
<li><a href="https://change-location.techidaily.com/4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-vivo-t2-5g-drfone-by-drfone-virtual-android/"><u>4 solution to get rid of pokemon fail to detect location On Vivo T2 5G | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/4-solutions-to-fix-unfortunately-your-app-has-stopped-error-on-realme-note-50-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Solutions to Fix Unfortunately Your App Has Stopped Error on Realme Note 50 | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-infinix-hot-40i-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Infinix Hot 40i without App | Dr.fone</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/aprovechando-la-pronunciacion-para-colores/"><u>Aprovechando La Pronunciación Para Colores</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/bandicam-a-user-centric-review-and-guide/"><u>Bandicam A User-Centric Review & Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-game-recommendations-on-win11/"><u>Disabling Game Recommendations on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-maximizing-your-windows-11-entry-point-strategies/"><u>Efficiently Maximizing Your Windows 11 Entry Point Strategies</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/elevate-your-visual-storytelling-advanced-zooming-on-snapchat/"><u>Elevate Your Visual Storytelling Advanced Zooming on Snapchat</u></a></li>
<li><a href="https://win11-tips.techidaily.com/empower-your-windows-experience-with-ai-through-vivetool/"><u>Empower Your Windows Experience with AI Through ViveTool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-window-management-skills-using-keyboard-in-win11/"><u>Enhance Your Window Management Skills Using Keyboard in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-performance-four-routes-to-windows-disk-explorer/"><u>Enhancing Performance: Four Routes to Windows Disk Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guaranteeing-remote-device-connections-on-windows-systems/"><u>Guaranteeing Remote Device Connections on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-internal-error-has-occurred-remote-desktop-connection-error-in-windows-10-and-11/"><u>How to Fix the “Internal Error Has Occurred” Remote Desktop Connection Error in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-handle-runtime-errors-when-malwarebytes-cant-call-proc/"><u>How to Handle Runtime Errors when Malwarebytes Can't Call Proc</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-music-from-oppo-reno-10-pro-5g-by-fonelab-android-recover-music/"><u>How to Rescue Lost Music from Oppo Reno 10 Pro 5G</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-how-to-bypass-tecno-phantom-v-flip-frp-android-10111213-by-drfone-android/"><u>In 2024, Easy Guide How To Bypass Tecno Phantom V Flip FRP Android 10/11/12/13</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-music-from-honor-magic-6-pro-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Music from Honor Magic 6 Pro to iPod | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-reasons-why-pokemon-gps-does-not-work-on-oppo-k11x-drfone-by-drfone-virtual-android/"><u>In 2024, Reasons why Pokémon GPS does not Work On Oppo K11x? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/ispoofer-is-not-working-on-apple-iphone-11-pro-max-fixed-drfone-by-drfone-virtual-ios/"><u>iSpoofer is not working On Apple iPhone 11 Pro Max? Fixed | Dr.fone</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/key-danish-films-to-elevate-your-danish-comprehension/"><u>Key Danish Films to Elevate Your Danish Comprehension</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-upgrade-rectification-error-0x80246007-in-win11/"><u>Mastering the Art of Upgrade Rectification: Error 0X80246007 in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-to-activate-end-task-feature-in-windows-11/"><u>Navigating to Activate End Task Feature in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/off-screen-woes-reverse-them-with-these-top-6-window-revival-strategies/"><u>Off-Screen Woes? Reverse Them with These Top 6 Window Revival Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-device-interaction-post-windows-sleep-mode/"><u>Optimizing Device Interaction Post-Windows Sleep Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pathways-to-the-system32-folder-in-win11/"><u>Pathways to the System32 Folder in Win11</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/perfecting-your-snapchat-story-cinematography/"><u>Perfecting Your Snapchat Story Cinematography</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proactive-measures-for-error-0x800700e1-on-windows-11-devices/"><u>Proactive Measures for Error 0X800700E1 on Windows 11 Devices</u></a></li>
<li><a href="https://techidaily.com/recover-apple-iphone-7-plus-data-from-ios-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover Apple iPhone 7 Plus Data From iOS iCloud | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-resource-consumption-from-windows-default-browser/"><u>Reducing Resource Consumption From Windows' Default Browser</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-non-detectable-razer-peripherals-in-synapse-and-windows/"><u>Solutions for Non-Detectable Razer Peripherals in Synapse & Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speed-up-victory-top-tips-for-cs-go-gaming/"><u>Speed Up Victory: Top Tips for CS GO Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/starting-windows-media-player-made-simple/"><u>Starting Windows Media Player Made Simple</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-unsignaled-update-files-on-pcs/"><u>Steps to Fix Unsignaled Update Files on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-pc-must-uninstall-windows-programs/"><u>Streamline Your PC: Must-Uninstall Windows Programs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-resurrection-without-the-windows-era/"><u>Tech Resurrection Without the Windows Era</u></a></li>
<li><a href="https://win11-tips.techidaily.com/terminal-and-powershell-dissecting-their-unique-characteristics/"><u>Terminal & PowerShell: Dissecting Their Unique Characteristics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-trouble-free-opening-of-csgo-on-windows-11/"><u>Tips for Trouble-Free Opening of CS:GO on Windows 11</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-audio-output-fixing-speaker-and-headphones-issues-in-windows-operating-systems/"><u>Troubleshooting Audio Output: Fixing Speaker and Headphones Issues in Windows Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-non-functional-file-consolidation-tool/"><u>Troubleshooting Non-Functional File Consolidation Tool</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-below-is-a-list-of-top-5-free-wmv-splitters-which-can-help-you-split-your-frames-without-damaging-the-quality-of-your-video/"><u>Updated Below Is a List of Top 5 Free WMV Splitters Which Can Help You Split Your Frames without Damaging the Quality of Your Video</u></a></li>
<li><a href="https://some-guidance.techidaily.com/upgrade-clips-adding-effects-to-videos-pcmobile-for-2024/"><u>Upgrade Clips Adding Effects to Videos (PC/Mobile) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-avoid-robot-generated-windows-11-access-codes/"><u>Why Avoid Robot-Generated Windows 11 Access Codes?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-default-apps-how-to-change-them-and-what-to-do-if-you-cant/"><u>Windows 11 Default Apps: How to Change Them and What to Do If You Can't</u></a></li>
</ul></div>
