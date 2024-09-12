---
title: How to Enable an End Task Option on the Windows 11 Taskbar
date: 2024-09-11T01:29:43.530Z
updated: 2024-09-12T01:29:43.530Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Enable an End Task Option on the Windows 11 Taskbar
excerpt: This Article Describes How to Enable an End Task Option on the Windows 11 Taskbar
keywords: Windows 11 Taskbar Setup,Enable End Task Icon,Taskbar Options Guide,Turn On Windows Exit Button,Close Taskbar Window Tips,EndTask Feature in Win11,Windows 11 Taskbar Customize
thumbnail: https://thmb.techidaily.com/66f3a5314b7f0b6f994f976b66c33a57ff0466854aa08d5996bdfaffcb47f66d.jpg
---

## How to Enable an End Task Option on the Windows 11 Taskbar

 The "end task" option in Windows 11 is your best friend when a program has stopped responding or has frozen. It allows you to close those unresponsive applications without restarting your PC. However, the "end task" may not be easy to find on Windows 11, especially if you are new to the operating system.

 In this article, we are sharing tricks to bring the End task option to the Windows 11 taskbar by using ViveTool. After enabling it, you will be only a click away from closing all the unresponsive applications.


>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>







<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2129042/19576" target="_top" id="2129042">
  <img src="//a.impactradius-go.com/display-ad/19576-2129042" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129042/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## What Is ViveTool, And Why Do You Need It to Enable End Task in Taskbar?

 ViveTool is a third-party program designed to enable Windows 11 features that Microsoft is testing internally and are not available for Insiders or general users. Using this app, ViveTool can give you an idea about what the software company plans to introduce to the next Windows 11 updates.

 At the time of writing, the "end task" option on Windows 11 taskbar is currently hidden in Windows 11 Dev Insider build 25300, meaning that even Insiders can't get it just yet. And this is where the ViveTool comes in.

 You can enable feature ID 42592269 to make the end task option appear on the taskbar jump list. However, before we hop into ViveTool and enable this handy feature, you should keep your expectations low regarding the functionality and reliability of the features you're about to enable.





<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2120863/26400?prodsku=Mercury" target="_top" id="2120863">
  <img src="//a.impactradius-go.com/display-ad/26400-2120863" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2120863/26400?prodsku=Mercury" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## How to Enable End Task Option in Windows 11 Taskbar

![End task option in Windows 11 Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/end-task-option-in-taskbar.jpg)





<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137206/26400" target="_top" id="2137206">
  <img src="//a.impactradius-go.com/display-ad/26400-2137206" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137206/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 Besides ViveTool, you also need to ensure that your PC is running Windows 11 Dev Channel build 25300 or later. You should see the build number in the bottom right corner of the desktop. Alternatively, you can navigate to**Settings** \>**System** \>**About** to check the OS build number.

 After ensuring your PC is running build 25300 or newer,[download the ViveTool zip file from the GitHub page](https://github.com/thebookisclosed/ViVe/releases) . Now, open File Explorer and find the zipped file. To unzip it, right-click on the file and select**Extract All** . You can also[unzip the file by using Command Prompt and PowerShell](https://www.makeuseof.com/zip-unzip-files-command-prompt-powershell/) . For the sake of simplicity, the extracted content should be in the folder**C:/ViVeTool** .

![Enable End Task option in Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/feature-id-in-command-prompt-edit.jpg)





<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136622/26400" target="_top" id="2136622">
  <img src="//a.impactradius-go.com/display-ad/26400-2136622" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136622/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 Now that you are done with setting up ViveTool on Windows 11, follow the below steps to enable the feature ID responsible for adding the "end task" option on the Windows 11 taskbar:

1. Open Command Prompt as an Administrator (see[how to open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for steps).
2. Type the following command and hit**Enter** :  
cd C:\ViVeTool
3. Copy and paste the following command and press**Enter:**  
vivetool /enable /id:42592269

 Command Prompt will display a message that says "Successfully set feature configuration (s)" after successfully running the command. To make the changes take effect, restart your computer. After the restart, open a program and right-click its icon on the taskbar to display the jump list containing the**End task** option.





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135411/19272" target="_top" id="2135411">
  <img src="//a.impactradius-go.com/display-ad/19272-2135411" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135411/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## An End Task Button on the Windows 11 Taskbar Is Now at Your Fingertips

 Adding the "end task" option onto the Windows 11 taskbar is currently available only via ViveTool. However, in the coming days, Microsoft will likely introduce it to every Windows 11 Insider, then eventually to the public either via a Moment update or through the Windows Web Experience pack. But before that happens, you are now familiar with the trick to terminate any task or process right from the Windows 11 taskbar.


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
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-accelerating-productivity-microsoft-azure-speech-recognition/"><u>[New] 2024 Approved Accelerating Productivity Microsoft Azure Speech Recognition</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-hue-harmony-masterclass-for-audience-enthusiasts/"><u>[New] Hue Harmony Masterclass for Audience Enthusiasts</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-genius-behind-effective-podcast-visual-identity/"><u>[New] The Genius Behind Effective Podcast Visual Identity</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unraveling-the-mystery-of-iphone-based-podcast-access/"><u>[New] Unraveling the Mystery of iPhone-Based Podcast Access</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-crafting-captivating-online-ads-for-facebook/"><u>[Updated] 2024 Approved Crafting Captivating Online Ads for Facebook</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-navigating-through-essential-zoom-recording-equipment/"><u>[Updated] 2024 Approved Navigating Through Essential Zoom Recording Equipment</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-top-picks-the-most-advanced-online-mic-recorders-of-23-for-2024/"><u>[Updated] Top Picks The Most Advanced Online Mic Recorders of '23 for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-profit-power-for-the-uninitiated-top-13-income-tips-on-reddit/"><u>2024 Approved Profit Power for the Uninitiated! Top 13 Income Tips on Reddit</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-the-unseen-viewers-route-navigating-instagram-stories-with-anonymous-viewing/"><u>2024 Approved The Unseen Viewer's Route Navigating Instagram Stories with Anonymous Viewing</u></a></li>
<li><a href="https://android-location-track.techidaily.com/9-best-phone-monitoring-apps-for-oppo-k11x-drfone-by-drfone-virtual-android/"><u>9 Best Phone Monitoring Apps for Oppo K11x | Dr.fone</u></a></li>
<li><a href="https://facebook.techidaily.com/behind-the-scenes-of-news-feed-curation-by-fb/"><u>Behind-the-Scenes of News Feed Curation by FB</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/comprehensive-guide-to-samsungs-photographic-editing-app/"><u>Comprehensive Guide to Samsung's Photographic Editing App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-winerror-misconfigured-file-history-settings/"><u>Correcting WinError: Misconfigured File History Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-game-recommendations-on-win11/"><u>Disabling Game Recommendations on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disarming-error-0x80040610-a-practical-guide-to-outlook-recovery/"><u>Disarming Error 0X80040610: A Practical Guide to Outlook Recovery</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-asus-usb-bt500-bluetooth-50-drivers-for-windows-11-10-and-8-free-update/"><u>Download Asus USB-BT500 Bluetooth 5.0 Drivers for Windows 11, 10 & 8 – Free Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-maximizing-your-windows-11-entry-point-strategies/"><u>Efficiently Maximizing Your Windows 11 Entry Point Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-apex-legends-crashes-with-w11-fixes/"><u>Eliminating Apex Legends Crashes with W11 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/empower-your-windows-experience-with-ai-through-vivetool/"><u>Empower Your Windows Experience with AI Through ViveTool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-window-management-skills-using-keyboard-in-win11/"><u>Enhance Your Window Management Skills Using Keyboard in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-performance-four-routes-to-windows-disk-explorer/"><u>Enhancing Performance: Four Routes to Windows Disk Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-altering-keyboard-layout-on-windows-11/"><u>Expert Tips for Altering Keyboard Layout on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guaranteeing-remote-device-connections-on-windows-systems/"><u>Guaranteeing Remote Device Connections on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-internal-error-has-occurred-remote-desktop-connection-error-in-windows-10-and-11/"><u>How to Fix the “Internal Error Has Occurred” Remote Desktop Connection Error in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-handle-runtime-errors-when-malwarebytes-cant-call-proc/"><u>How to Handle Runtime Errors when Malwarebytes Can't Call Proc</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-12-pro-max-without-passcode-or-face-id-drfone-by-drfone-ios/"><u>How to Unlock iPhone 12 Pro Max without Passcode or Face ID | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improve-window-placement-on-windows-os-defeat-overscan/"><u>Improve Window Placement on Windows OS: Defeat Overscan</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-itel-p55-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Itel P55</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-best-oppo-reno-8t-5g-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>In 2024, Best Oppo Reno 8T 5G Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-how-to-fix-the-apple-iphone-14-pro-max-gps-not-working-issue-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Fix the Apple iPhone 14 Pro Max GPS not Working Issue | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-pushing-the-envelope-how-srgb-replaces-conventional-rgb/"><u>In 2024, Pushing the Envelope How Srgb Replaces Conventional Rgb</u></a></li>
<li><a href="https://article-tips.techidaily.com/inside-story-stock-pictures-and-their-internet-fame-for-2024/"><u>Inside Story Stock Pictures and Their Internet Fame for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/launching-linux-virtualization-effortlessly-within-hyper-v-windows/"><u>Launching Linux Virtualization Effortlessly Within Hyper-V Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-teamwork-eradicating-ms-teams-error-80080300/"><u>Mastering the Art of Teamwork: Eradicating MS Teams Error 80080300</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-upgrade-rectification-error-0x80246007-in-win11/"><u>Mastering the Art of Upgrade Rectification: Error 0X80246007 in Win11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/navigate-the-world-of-gadgets-and-pc-parts-with-toms-advice/"><u>Navigate the World of Gadgets and PC Parts with Tom’s Advice</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-maze-of-win1011s-error-0x800704b3/"><u>Navigating the Maze of Win10/11's Error 0X800704B3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-world-of-windows-shields/"><u>Navigating the World of Windows Shields</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-to-activate-end-task-feature-in-windows-11/"><u>Navigating to Activate End Task Feature in Windows 11</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-transform-your-videos-into-cinematic-masterpieces-with-fcpx/"><u>New 2024 Approved Transform Your Videos Into Cinematic Masterpieces with FCPX</u></a></li>
<li><a href="https://win11-tips.techidaily.com/off-screen-woes-reverse-them-with-these-top-6-window-revival-strategies/"><u>Off-Screen Woes? Reverse Them with These Top 6 Window Revival Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-device-interaction-post-windows-sleep-mode/"><u>Optimizing Device Interaction Post-Windows Sleep Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-intel-unison-not-working-woes-on-win11/"><u>Overcoming Intel Unison Not Working Woes on Win11</u></a></li>
<li><a href="https://win-blog.techidaily.com/overcoming-windows-11-hurdles-for-a-functional-corsair-icue-experience/"><u>Overcoming Windows 11 Hurdles for a Functional Corsair iCUE Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pathways-to-the-system32-folder-in-win11/"><u>Pathways to the System32 Folder in Win11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/photographic-presentation-prowess-frame-tech/"><u>Photographic Presentation Prowess Frame Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pro-typers-playbook-custom-keys-for-pre-set-snippet-pasting-in-windows-11/"><u>Pro-Typers' Playbook: Custom Keys for Pre-Set Snippet Pasting in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proactive-measures-for-error-0x800700e1-on-windows-11-devices/"><u>Proactive Measures for Error 0X800700E1 on Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-resource-consumption-from-windows-default-browser/"><u>Reducing Resource Consumption From Windows' Default Browser</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-monitor-configuration-on-desktops/"><u>Reversing Monitor Configuration on Desktops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-non-detectable-razer-peripherals-in-synapse-and-windows/"><u>Solutions for Non-Detectable Razer Peripherals in Synapse & Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speed-up-victory-top-tips-for-cs-go-gaming/"><u>Speed Up Victory: Top Tips for CS GO Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/starting-windows-media-player-made-simple/"><u>Starting Windows Media Player Made Simple</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-unsignaled-update-files-on-pcs/"><u>Steps to Fix Unsignaled Update Files on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-pc-must-uninstall-windows-programs/"><u>Streamline Your PC: Must-Uninstall Windows Programs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-resurrection-without-the-windows-era/"><u>Tech Resurrection Without the Windows Era</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-recover-failed-steamuidll-load/"><u>Techniques to Recover Failed Steamui.dll Load</u></a></li>
<li><a href="https://win11-tips.techidaily.com/terminal-and-powershell-dissecting-their-unique-characteristics/"><u>Terminal & PowerShell: Dissecting Their Unique Characteristics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-trouble-free-opening-of-csgo-on-windows-11/"><u>Tips for Trouble-Free Opening of CS:GO on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-non-functional-file-consolidation-tool/"><u>Troubleshooting Non-Functional File Consolidation Tool</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-identify-some-outdated-your-drivers-on-windows-7-by-drivereasy-guide/"><u>Use Device Manager to identify some outdated your drivers on Windows 7</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/where-is-the-best-place-to-catch-dratini-on-nokia-c110-drfone-by-drfone-virtual-android/"><u>Where Is the Best Place to Catch Dratini On Nokia C110 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-avoid-robot-generated-windows-11-access-codes/"><u>Why Avoid Robot-Generated Windows 11 Access Codes?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-default-apps-how-to-change-them-and-what-to-do-if-you-cant/"><u>Windows 11 Default Apps: How to Change Them and What to Do If You Can't</u></a></li>
<li><a href="https://fake-location.techidaily.com/wondering-the-best-alternative-to-hola-on-vivo-x90s-here-is-the-answer-drfone-by-drfone-virtual-android/"><u>Wondering the Best Alternative to Hola On Vivo X90S? Here Is the Answer | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/your-pathway-to-a-functional-windows-sandbox/"><u>Your Pathway to a Functional Windows Sandbox</u></a></li>
</ul></div>




