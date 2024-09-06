---
title: In-Depth Analysis of PC's Performance Spectrum
date: 2024-09-05T19:41:25.862Z
updated: 2024-09-06T19:41:25.862Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes In-Depth Analysis of PC's Performance Spectrum
excerpt: This Article Describes In-Depth Analysis of PC's Performance Spectrum
keywords: PC Performance Review,System Speed Testing,PC Efficiency Analysis,Optimal PC Settings,Computer Speed Benchmark,Performance Metrics PC,Tech Specs Exploration
thumbnail: https://thmb.techidaily.com/4344716e214d80fc0302240776bca3183fcb221b8492651a99a24a405c1e3fa0.jpg
---

## In-Depth Analysis of PC's Performance Spectrum

 Have you ever tried to tweak the minimum and maximum processor states on your Windows PC, only to find them hidden? Or perhaps you want to hide the options to prevent others from tampering with them?

 Whichever you're trying to do, we're here to help by showing you how to add or remove them in the Power Options menu.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115920/19272" target="_top" id="2115920">
  <img src="//a.impactradius-go.com/display-ad/19272-2115920" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115920/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Show or Hide the Minimum or Maximum Processor State Using Command Prompt

 To use Command Prompt to show or hide these power states, press**Win + R** to open Windows Run. Then, enter**cmd** in the text box and hit the**Enter** key on your keyboard. You can also use one of the many[ways to open the Command Prompt on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

![Cmd in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-cmd.jpg)

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/2139557/4704" target="_top" id="2139557">
  <img src="//a.impactradius-go.com/display-ad/4704-2139557" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139557/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
To show the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c -ATTRIB_HIDE`

To hide the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c +ATTRIB_HIDE`

To show the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec -ATTRIB_HIDE`

To hide the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec +ATTRIB_HIDE`

 After you have typed in the command you want in the CMD window, hit the**Enter** key on your keyboard to run it.

<!-- affiliate ads begin -->
<span id="1834906">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1834906.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1834906">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1834906.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1834906%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1834906/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out[how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123728/7443" target="_top" id="2123728">
  <img src="//a.impactradius-go.com/display-ad/7443-2123728" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123728/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

<!-- affiliate ads begin -->
<span id="1328683">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1328683.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1328683">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1328683.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1328683%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1328683/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

<!-- affiliate ads begin -->
<span id="1983551">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983551.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983551">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983551.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983551%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983551/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Add or Remove the Minimum and Maximum Processor States From Power Options

 Setting the minimum or maximum processor state on your Windows computer is vital to helping you get the performance you want from it. If you can’t see these options in the Power Options menu, you can easily reveal them with either Command Prompt or the Registry Editor. And after you’re done tweaking the states, you can hide them for their protection.


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
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-explore-mastery-in-photography-and-videography-on-apple-and-android-phones/"><u>[New] In 2024, Explore Mastery in Photography & Videography on Apple & Android Phones</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-perfecting-podcast-production-an-ultimate-tutorial-for-high-quality-zoom-recordings/"><u>[New] In 2024, Perfecting Podcast Production An Ultimate Tutorial for High-Quality Zoom Recordings</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-innovate-how-you-connect-with-tech-best-text-interpretation-tools-on-mac/"><u>[New] Innovate How You Connect with Tech Best Text Interpretation Tools on Mac</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-the-definitive-guide-to-du-recorders-capabilities/"><u>[Updated] 2024 Approved The Definitive Guide to Du Recorder's Capabilities</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-interface-to-enlarge-videography-elements/"><u>[Updated] Interface to Enlarge Videography Elements</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-complete-guide-to-adding-powerful-narrations/"><u>[Updated] The Complete Guide to Adding Powerful Narrations</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-capturing-movement-with-clarity-implementing-motion-blur-on-peoples-photos-with-picsart/"><u>2024 Approved Capturing Movement with Clarity Implementing Motion Blur on People's Photos with Picsart</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-master-the-art-of-video-sending-from-youtube-to-dailymotion/"><u>2024 Approved Master the Art of Video Sending From YouTube to Dailymotion</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/a-guide-nokia-g310-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>A Guide Nokia G310 Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/all-you-need-to-know-about-mega-greninja-for-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>All You Need To Know About Mega Greninja For Samsung Galaxy A05 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-retrieve-lost-contacts-from-tecno-pop-8-by-fonelab-android-recover-contacts/"><u>Best Android Data Recovery - Retrieve Lost Contacts from Tecno Pop 8.</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/comprehensive-guide-for-high-quality-presentation-capture-for-2024/"><u>Comprehensive Guide for High-Quality Presentation Capture for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-edge-features-essential-tips-for-windows-11-widgets/"><u>Cutting-Edge Features: Essential Tips for Windows 11 Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-windows-gpo-a-complete-guide-for-users/"><u>Deciphering Windows GPO: A Complete Guide for Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dismiss-incompatible-prerequisite-message-in-win11/"><u>Dismiss Incompatible Prerequisite Message in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-ipadiphone-picture-upload-error-a-detailed-guide-for-windows-users/"><u>Fixing the iPad/iPhone Picture Upload Error: A Detailed Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-disabling-games-on-windows-11-list/"><u>Guide to Disabling Games on Windows 11 List</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-delete-all-photos-from-iphone-xs-beyond-scope-of-recovery-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Delete All Photos from iPhone XS Beyond Scope of Recovery? | Stellar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-disable-app-launch-tracking-in-windows/"><u>How to Disable App Launch Tracking in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-network-discovery-is-turned-off-error-on-windows/"><u>How to Fix the “Network Discovery Is Turned Off” Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-errors-related-to-printmanagement-in-windows/"><u>How to Resolve Errors Related to 'Printmanagement' In Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-winerror-incorrect-file-backup-settings/"><u>How to Resolve WinError: Incorrect File Backup Settings</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-use-google-assistant-on-your-lock-screen-of-samsung-galaxy-a05s-phone-by-drfone-android/"><u>How to Use Google Assistant on Your Lock Screen Of Samsung Galaxy A05s Phone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insight-microsofts-vcplusplus-release-rationale/"><u>Insight: Microsoft's VC++ Release Rationale</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-efficiency-incorporating-law-filters-into-windows/"><u>Maximizing Efficiency: Incorporating LAW Filters Into Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methodology-for-amending-lost-drive-issue/"><u>Methodology for Amending Lost Drive Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-file-movement-in-windows-via-python-servers/"><u>Navigating File Movement in Windows via Python Servers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-your-mouse-trail-on-windows-machines/"><u>Personalizing Your Mouse Trail on Windows Machines</u></a></li>
<li><a href="https://media-tips.techidaily.com/quick-and-effortless-guide-to-converting-videos-for-your-blackberry-device-2024-edition/"><u>Quick and Effortless Guide to Converting Videos for Your BlackBerry Device - 2024 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-reading-voice-in-ms-windows-document-editor/"><u>Reactivating Reading Voice in MS Windows Document Editor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-wlanextexe-low-cpu-drain-techniques/"><u>Reducing WLANEXT.EXE: Low CPU Drain Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-reliable-windows-protection-on-win-11/"><u>Reinstating Reliable Windows Protection on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rise-above-the-norm-with-these-excellent-win-11-widgets/"><u>Rise Above the Norm with These Excellent Win 11 Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-file-management-activating-windows-controlled-folder-access/"><u>Secure File Management: Activating Window’s Controlled Folder Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sever-onedrive-connection-with-ms-account-on-windows/"><u>Sever OneDrive Connection with MS Account on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-wins-most-unusual-error-codes/"><u>Solutions for Win's Most Unusual Error Codes</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/solving-the-pc-reset-issue-a-step-by-step-guide/"><u>Solving the 'PC Reset Issue': A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-rectifying-path-not-found-error/"><u>Strategies for Rectifying Path Not Found Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-resource-occupied-errors-152-chars/"><u>Strategies to Overcome 'Resource Occupied' Errors (152 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-6-methods-for-scaling-photos-on-windows-11/"><u>Top 6 Methods for Scaling Photos on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-app-interference-with-windows-power-control/"><u>Troubleshooting App Interference with Windows Power Control</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-control-enable-users-and-groups-in-windows-homes/"><u>Unleash Control: Enable Users & Groups in Windows Homes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-secrets-of-win-11-gaming-top-seven-strategies-for-gamers/"><u>Unlock the Secrets of Win 11 Gaming: Top Seven Strategies for Gamers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-past-enhance-retro-games-using-retroarchs-tools/"><u>Unlocking the Past: Enhance Retro Games Using RetroArch’s Tools</u></a></li>
</ul></div>
