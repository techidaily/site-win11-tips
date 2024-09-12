---
title: Mitigating Low Virtual Memory Situations in VmWare
date: 2024-09-11T01:21:42.213Z
updated: 2024-09-12T01:21:42.213Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mitigating Low Virtual Memory Situations in VmWare
excerpt: This Article Describes Mitigating Low Virtual Memory Situations in VmWare
keywords: VMware RAM Management,Memory Optimization VMware,VmWare Memory Allocation,Enhance VM Memory Use,Low Mem VMSolutions,Reduce Virtual Memory Issues,VmWare Space Efficiency
thumbnail: https://thmb.techidaily.com/cce90de001854095939cd22c7e555d9393bc0bdf8a9fe07be68597eb9b7713ab.jpg
---

## Mitigating Low Virtual Memory Situations in VmWare

 VMware Workstation is one of the best virtualization software packages for Windows. However, some users see an error message when they try to start virtual machines in VMware Workstation. That error message says, “not enough physical memory is available to power on this virtual machine,” and virtual machines won’t start up.

 This VMware issue can arise when there’s more than enough RAM available on a PC. However, there are numerous possible causes for the “not enough physical memory” error. This is how you can fix the “not enough physical memory” WMware error in Windows 10 and 11.


>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>







<!-- affiliate ads begin -->
<span id="1542129">
					<video width="864" height="1152" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1542129.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1542129">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1542129.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1542129%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1542129/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 1\. Configure VMware to Run as an Administrator

 Not running VMware as an administrator places restrictions on its system permissions and access to resources. So, run the software with elevated rights to ensure a lack of permissions isn’t causing any issues.

 You can check out[how to run any program as an administrator on Windows](https://www.makeuseof.com/tag/ways-to-run-a-program-as-administrator-in-windows/) for more help, or you can set VMware to always run as an administrator like this:

1. If there’s a VMware shortcut on your desktop, right-click it and select**Open** file location. Manually open VMware’s installation directory in File Explorer if you can’t right-click a shortcut for the software.
2. Then click the VMware EXE file with the right mouse button to select its**Properties** context menu option.
3. Select**Compatibility** to view that tab’s settings.
4. Click the checkbox for the**Run this program as administrator** option to select it.  
![The Compatibility tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-compatibility-tab2.jpg)
5. Select**Apply** to save the new administrator option for VMware.
6. Then select**OK** to close WMware’s properties window.

## 2\. Edit the Config File

 Lots of users have been able to fix the “not enough physical memory” by editing VMWare’s**config.ini** file. Those users disabled a Host parameter within the software’s configuration file. To disable that Host parameter, open and edit VMware’s**config.ini** file as follows:

1. Press**Win + E** to access File Explorer.
2. Open this VMware directory in Explorer:  
`C:\ProgramData\VMware\VMware Workstation`
3. Right-click the**config.ini** file and select**Open with** .  
![The Open with option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-open-with-option.jpg)
4. Select**Notepad** to view the configuration file in that text editor.
5. Then **input vmmon.disableHostParameters = “TRUE”** at the bottom of the configuration file as in the image below.  
![WMware's config.ini file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-config-ini-file.jpg)
6. Click**File** on Notepad’s menubar.
7. Select the menu’s**Save** option.  
![The Save option in Notepad](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-save-option-in-notepad.jpg)





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130886/7443" target="_top" id="2130886">
  <img src="//a.impactradius-go.com/display-ad/7443-2130886" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130886/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->








<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2121331/18498" target="_top" id="2121331">
  <img src="//a.impactradius-go.com/display-ad/18498-2121331" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2121331/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 3\. Expand the Virtual Memory for the Virtual Machine

 The “not enough physical memory” error can occur because not enough virtual memory has been allocated to the virtual machine. You can expand a virtual machine’s memory allocation in VMWare like this:

1. Open your VMware software.
2. Right-click the virtual machine for which you need to fix the error and select**Settings** .
3. Increase the virtual machine’s memory allocation with the bar slider. That amount should always be higher than your PC’s available RAM.  
![The memory bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-memory-bar.jpg)
4. Click**OK** to apply.

## 4\. Update VMware

 The “not enough physical memory” error will more likely arise on outdated WMware versions. So, ensure you’re utilizing the latest version of the software. This is how you can update VMware:

1. Bring up the VMware window.
2. Click the**Help** menu.
3. Select**Software Updates** to view that window.  
![The Software Updates option in VMware](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-software-updates-option.jpg)
4. Then click the**Check for Updates** button.  




<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136622/26400" target="_top" id="2136622">
  <img src="//a.impactradius-go.com/display-ad/26400-2136622" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136622/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




![The Check for updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-check-for-updates-option4.jpg)
5. Press the**Get More Information** button for an available update.




<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123481/16836" target="_top" id="2123481">
  <img src="//a.impactradius-go.com/display-ad/16836-2123481" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123481/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->





1. Log into an account profile on the website that opens.
2. Select the**Download Now** option on the website for the latest VMware Workstation version.
3. Then you’ll need to select an**Accept** option for the EULA agreement.
4. Click another**Download Now** option.
5. Then click File Explorer’s taskbar shortcut.
6. Go to the downloads folder that includes the WMware setup wizard.
7. Double-click the downloaded VMware installer to open it. Go through the setup wizard to install the latest VMware version.

## 5\. Delete a Recent Windows Update

 The “not enough physical memory” error can be caused by a Windows update that conflicts with VMware. So, uninstalling a recent update could fix that issue for some users. Check out our guide about[uninstalling Windows updates](https://www.makeuseof.com/windows-11-uninstall-updates/) for further details on how to apply this potential solution.

![The Installed Updates Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-uninstall-update-option.jpg)





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115931/19272" target="_top" id="2115931">
  <img src="//a.impactradius-go.com/display-ad/19272-2115931" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115931/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 6\. Perform a Clean Boot

 Performing a clean boot will disable non-essential apps and services from the Windows startup. Clean booting can potentially resolve the “not enough physical memory” in two ways. Applying this troubleshooting method will ensure there aren’t any third-party programs conflicting with VMware and free up RAM for the software.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-services-tab-in-msconfig.jpg)





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135350/19272" target="_top" id="2135350">
  <img src="//a.impactradius-go.com/display-ad/19272-2135350" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135350/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 To disable all third-party startup programs and services, check out the guidelines in our guide on[how to clean boot in Windows](https://www.makeuseof.com/clean-boot-windows-11/) . This will perform a clean boot whenever you restart Windows.

 Try utilizing your VMware virtual machine after clean booting. If this works,





<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136548/16384" target="_top" id="2136548">
  <img src="//a.impactradius-go.com/display-ad/16384-2136548" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136548/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 7\. Set Up a New Virtual Machine

 If the issue persists despite applying the resolutions above, consider setting up a new virtual machine to replace the one that needs fixing. Download the latest ISO for the virtual machine’s platform. Then you can set up the virtual machine again, as outlined on the[VMware support page](https://kb.vmware.com/s/article/1018415) .

## Jump Into Your WMware Virtual Machine Again

 Those Windows fixes for the “Not enough physical memory” error have worked for many VMware Workstation users. So, there’s a decent enough chance one will kick-start your VMWare virtual machine too. However, users who still need more possible fixes for this issue can submit a support request via the[VMware Customer Connect](https://customerconnect.vmware.com/home?bmctx=89E60DF848C641FD518EB9F6B9A6E5334F602FA3A762B409625CD531863AC847&password=secure%5Fstring&contextType=external&username=string&challenge%5Furl=https:%2F%2Fcustomerconnect.vmware.com%2Fhome&request%5Fid=-8453692679675997712&authn%5Ftry%5Fcount=0&locale=en%5FGB&resource%5Furl=https%253A%252F%252Fcustomerconnect.vmware.com%252Fweb%252Fvmware%252Fchecksession) page.

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
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-from-fast-pace-to-deliberate-motion-making-slow-movies-on-insta/"><u>[New] 2024 Approved From Fast Pace to Deliberate Motion Making Slow Movies on Insta</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-jumpstart-your-recording-with-this-obs-mac-setup-guide/"><u>[New] 2024 Approved Jumpstart Your Recording with This OBS Mac Setup Guide</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-navigating-slack-integration-with-filmora-for-seamless-video-conferences/"><u>[New] In 2024, Navigating Slack Integration with Filmora for Seamless Video Conferences</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-terminate-discord-access-dual-devices/"><u>[New] In 2024, Terminate Discord Access - Dual Devices</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-mysterious-video-issue-with-sony-a6400/"><u>[New] Mysterious Video Issue with Sony A6400</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-customizing-your-watch-the-art-of-altering-youtube-video-pace/"><u>[Updated] Customizing Your Watch The Art of Altering YouTube Video Pace</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-big-should-a-good-thumbnail-be-youtubes-ultimate-guide/"><u>[Updated] In 2024, How Big Should a Good Thumbnail Be? YouTube's Ultimate Guide</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-techniques-for-text-overlays-in-igtv-content/"><u>[Updated] In 2024, Techniques for Text Overlays in IGTV Content</u></a></li>
<li><a href="https://driver-download.techidaily.com/amd-rx-6700-xt-graphics-card-driver-update-optimized-for-windows-10-8-and-vista-users/"><u>AMD RX 6700 XT Graphics Card Driver Update - Optimized for Windows 10, 8 & Vista Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-invalid-user-alerts-fix-guide-for-windows-1111/"><u>Disabling Invalid User Alerts: Fix Guide for Windows 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-updater-error-0x80246007-in-windows-1011-os/"><u>Disabling Updater Error 0X80246007 in Windows 10/11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-stubborn-windows-printers-a-swift-guide/"><u>Eliminating Stubborn Windows Printers: A Swift Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicate-entryways-four-slick-steps-to-disable-a-user-on-win11/"><u>Eradicate Entryways: Four Slick Steps to Disable a User on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-data-recovery-offer-immediate-access-and-assurance/"><u>Exclusive Data Recovery Offer: Immediate Access & Assurance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hide-or-reveal-window-11s-clock-and-date/"><u>Hide or Reveal Window 11'S Clock & Date</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-engage-clipboard-utility-within-microsoft-edges-app-guard-for-windows-11/"><u>How to Engage Clipboard Utility Within Microsoft Edge's App Guard for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-halt-screen-flashes-on-windows-11-devices/"><u>How to Halt Screen Flashes on Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-make-the-taskbar-bigger-or-smaller-on-windows-11/"><u>How to Make the Taskbar Bigger or Smaller on Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-messages-files-from-asus-rog-phone-7-ultimate-by-fonelab-android-recover-messages/"><u>How To Restore Missing Messages Files from Asus ROG Phone 7 Ultimate</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-android-unlock-code-sim-unlock-your-motorola-moto-g04-phone-and-remove-locked-screen-by-drfone-android/"><u>In 2024, Android Unlock Code Sim Unlock Your Motorola Moto G04 Phone and Remove Locked Screen</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-honor-x50iplus-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Honor X50i+ Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-soundtrack-synergy-inshot-edition/"><u>In 2024, Soundtrack Synergy InShot Edition</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-two-ways-to-track-my-boyfriends-infinix-smart-7-without-him-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Two Ways to Track My Boyfriends Infinix Smart 7 without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innocuous-looking-apps-notorious-for-slowing-down-pcs/"><u>Innocuous-Looking Apps, Notorious for Slowing Down PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-driver-verifier-via-control-panel-on-w11/"><u>Launching Driver Verifier via Control Panel on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-basic-window-aids-for-beginners/"><u>Mastering Basic Window Aids for Beginners</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-file-explorer-settings-tailor-your-folder-views-on-mac/"><u>Mastering File Explorer Settings: Tailor Your Folder Views on Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-make-taskview-harder-to-find-in-win-11/"><u>Methods to Make TaskView Harder to Find in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modernizing-the-user-experience-with-windows-1011-shortcuts/"><u>Modernizing the User Experience with Windows 10/11 Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-non-starting-display-on-windows-11-pc/"><u>Overcoming Non-Starting Display on Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/patching-up-a-purple-problem-desktop-restoration-steps/"><u>Patching Up a Purple Problem: Desktop Restoration Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-to-stop-vscode-from-crashing-w11/"><u>Quick Fixes to Stop VSCode From Crashing W11</u></a></li>
<li><a href="https://os-tips.techidaily.com/quick-solutions-how-to-free-up-space-on-your-iphones-nearly-full-storage/"><u>Quick Solutions: How to Free Up Space on Your iPhone's Nearly Full Storage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-lsa-error-local-sec-admin-disabled-alert/"><u>Resolving LSA Error: Local Sec Admin Disabled Alert</u></a></li>
<li><a href="https://techidaily.com/samsung-won-t-play-hevc-h-265-media-how-to-fix-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Samsung won’t play HEVC H.265 media, how to fix? </u></a></li>
<li><a href="https://solve-help.techidaily.com/step-by-step-guide-backing-up-your-mac-using-an-external-hdd-with-and-without-time-machine/"><u>Step-by-Step Guide: Backing Up Your Mac Using an External HDD – With and Without Time Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-implementing-windows-hello-fingerprints/"><u>Step-by-Step Guide: Implementing Windows Hello Fingerprints</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-solve-launch-failure-of-obs-studio/"><u>Strategies to Solve Launch Failure of OBS Studio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-tasks-with-mspcm-toolbar-in-windows-11/"><u>Streamlining Tasks with MSPCM Toolbar in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-impact-of-ignoring-win-11-notification-pushes/"><u>The Impact of Ignoring Win 11 Notification Pushes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-procedure-for-restoring-icons-on-windows-11s-search-bar/"><u>The Procedure for Restoring Icons on Windows 11'S Search Bar</u></a></li>
<li><a href="https://article-posts.techidaily.com/the-ultimate-exploration-of-yis-4k-hero-series-for-2024/"><u>The Ultimate Exploration of Yi’s 4K HERO Series for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-managing-text-highlighting-in-windows-11/"><u>Tips for Managing Text Highlighting in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-non-microsoft-tools-for-immediate-and-accurate-screen-sniping/"><u>Top Non-Microsoft Tools For Immediate and Accurate Screen Sniping</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/triumph-in-educations-freedom-journey/"><u>Triumph in Education's Freedom Journey</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-full-potential-of-service-management-on-windows-11/"><u>Unlock the Full Potential of Service Management on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mysteries-of-windows-iscsi-initiator-access/"><u>Unraveling the Mysteries of Windows iSCSI Initiator Access</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unveiling-the-future-of-transportation-insights-on-teslas-autonomous-taxi-service-and-its-anticipated-cost/"><u>Unveiling the Future of Transportation: Insights on Tesla's Autonomous Taxi Service & Its Anticipated Cost</u></a></li>
<li><a href="https://win11-tips.techidaily.com/update-windows-11-admin-credentials-quickly/"><u>Update Windows 11 Admin Credentials Quickly</u></a></li>
<li><a href="https://tech-haven.techidaily.com/vector-databases-demystified-boosting-ai-capabilities-with-efficient-data-structures/"><u>Vector Databases Demystified: Boosting AI Capabilities with Efficient Data Structures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-strategies-for-outlook-malfunctions/"><u>Winning Strategies for Outlook Malfunctions</u></a></li>
</ul></div>




