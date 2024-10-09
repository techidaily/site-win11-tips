---
title: Solving Operation Failure 0X0000011B in Windows 11
date: 2024-10-02T16:49:36.154Z
updated: 2024-10-09T06:32:18.140Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solving Operation Failure 0X0000011B in Windows 11
excerpt: This Article Describes Solving Operation Failure 0X0000011B in Windows 11
keywords: Fixing Win11 Error Code,Solve OS 11 Halt Error,Addressing 0X11B Failure,Troubleshoot Windows XP Error,Resolving Operation X Error,Remedy 0X Error in Win11,Windows 11 Crash Fix Guide
thumbnail: https://thmb.techidaily.com/55f69c473ce05e56332fdc0fd3becc5010779e559c1a26eb52ce7f94ac706c0b.jpg
---

## Solving Operation Failure 0X0000011B in Windows 11

 A new security patch released by Microsoft may have caused printers shared over the network to malfunction, resulting in the operation failed 0x0000011B error. The error has primarily affected Windows 10 21H1 build running computers. However, you may also experience it on Windows 11 systems.

 You can fix the error by installing the latest patch for the bug in the Windows update section. If not, here are other troubleshooting steps to fix the error and get your printer working again.

 Note that all the fixes must be applied to the host system that has the printer connected to it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Restart the Print Spooler Service

 A common troubleshooting step to fix issues with your printer is to restart the print spooler service. It is an essential service that handles the print job between your computer and printer. If the[print spooler service is not running](https://www.makeuseof.com/print-spooler-service-not-running-windows/) , you can manually start it from the Services snap-in. Here’s how to do it.

1. Press**Win + R** to open**Run** .
2. Type**services.msc** and click**OK** .
3. In the**Service** snap-in, locate the**Print Spooler** service.  
![print spooler service properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/print-spooler-service-properties.jpg)
4. Next, right-click on the service and select**Properties** .  
![print spooler service startup type automatic](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/print-spooler-service-startup-type-automatic.jpg)
5. In the**Properties** dialog, open the**General** tab.  
![restart print spooler service 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/restart-print-spooler-service-1.jpg)
6. Click the**Startup type** drop-down and set it to**Automatic** .
7. Click**Apply** and**OK** to save the changes.
8. Right-click on**Print** **Spooler** again and click**Restart** .
9. Once the Print Spooler service is up and running, create a new print job and check for any improvements.

## 2\. Install All the Pending Windows Updates

![check windows 10 updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-windows-10-updates.jpg)

 If it’s a widespread issue, you’ll likely receive a bug fix via Windows update. So, begin with checking if a new Windows update is available. These are often small hotfixes released to fix widespread issues.

To check and install Windows updates:

1. Press**Win + I** to open the**Settings** app.
2. In the left pane, open the**Windows Update** tab. Open**Update & Security** on Windows 10.
3. Click on**Check for updates** . Windows will look for pending updates and list them here.
4. Click on**Download & install** to install the updates.
5. Once installed, restart your PC and check for any improvements.

## 3\. Install the Printer Manually via the Local Port

 A little complicated, yet a working solution to fix the operation failed error 0x0000011B is to[add your printer manually to Windows](https://www.makeuseof.com/windows-11-add-wired-wireless-printer/) for the local port. Here’s how to do it.

1. Press**Win + I** to open**Settings** .
2. Next, click on**Devices** and then open the**Printers & scanners** tab.
3. Next, click on**Add a printer or scanner** . Windows will scan for available printers.  
![the printer that i want isnt listed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-printer-that-i-want-isnt-listed.jpg)
4. Click on the**The printer that I want isn’t listed** option. If you don't see the option immediately, wait for a few seconds after clicking on the**Add a printer or scanner** option.
5. In the**Add Printer** dialog, select **Add a local printer or network printer with manual settings.**  
![add local printer network printer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/add-local-printer-network-printer.jpg)

1. Under**Choose a printer por** t, select**Create a new port.**  
![create new port local port add printer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/create-new-port-local-port-add-printer.jpg)
2. Click the drop-down for**Type of port** and select**Local Port.**
3. Click**Next** .  
![enter port name printer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enter-port-name-printer.jpg)
4. Type your network printer file path and the network printer name in the**Enter a port name** field. You can use the username or the IP address for the computer name and then the printer name you want to share.

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2141688/17094" target="_top" id="2141688">
  <img src="//a.impactradius-go.com/display-ad/17094-2141688" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluetties.sjv.io/i/5597632/2141688/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Click**OK** to save the printer.

1. Next, select your printer manufacturer from the list to install the printer driver.
2. Next, select the correct printer driver under the**Printers** column.
3. Click**Next** .
4. Choose a name for your printer driver and click**Install** .
5. Click**Next** and wait for the installation to complete.

 Your newly added printer will now appear under**Device and Printer** in**Control Panel** and the**Settings** app. Give a new print job to see if the error is resolved.

<!-- affiliate ads begin -->
<span id="1982570">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982570.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982570">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982570.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982570%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982570/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Disable the CVE-2021-1678 Registry Fix

 The problematic security update included a security fix to patch the Printer Spooler Spoofing vulnerability dubbed CVE-2021-1678\. However, the new changes seem to have triggered the 0x0000011B operation failed error.

 To fix the error without uninstalling the security update, you’ll need to create a new registry entry to disable the feature. Here’s how to do it.

 Note that modifying your Windows Registry involves risk. We recommend you[back up your Windows registry](http://www.makeuseof.com/tag/backup-restore-windows-registry/) and[create a system restore](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps below.

Next, follow these steps to disable CVE-2021-1678 mitigation:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor.
3. In Registry Editor, navigate to the following location. Copy and paste the registry path for quick navigation:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Print`
4. Next, right-click on**Print > New > DWORD (32-bit) Value.**  
![create new dword 32 bit value registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/create-new-dword-32-bit-value-registry-editor.jpg)
5. Rename the**DWORD value** as**RpcAuthnLevelPrivacyEnabled.**  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896555/19272" target="_top" id="1896555">
  <img src="//a.impactradius-go.com/display-ad/19272-1896555" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896555/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![registry editor modify rpcauthlevelprivacyenabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor-modify-rpcauthlevelprivacyenabled.jpg)
6. Right-click on the**RpcAuthnLevelPrivacyEnabled** value and select**Modify** .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006955/19272" target="_top" id="2006955">
  <img src="//a.impactradius-go.com/display-ad/19272-2006955" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006955/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Type**0** in the**Value data** field and click**OK** to save the changes.  
![registry editor modify rpcauthlevelprivacyenabled 0 disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor-modify-rpcauthlevelprivacyenabled-0-disabled.jpg)
8. Close**Registry Editor** and restart your PC to apply the changes.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098705/14409" target="_top" id="2098705">
  <img src="//a.impactradius-go.com/display-ad/14409-2098705" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098705/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. After the restart, try to use your shared printer and check if the error is resolved.

## 5\. Uninstall Recently Installed Updates

 Assuming the issue is triggered after you installed a Windows security update, uninstalling the update should undo the changes and fix the error. You can uninstall some individual updates from the Windows updates section. This feature is specifically available to undo issues that may have occurred after installing an update.

 Note that the concerned update (KB5005565) was released to fix a print spooler vulnerability on Windows OS. Uninstalling the update can leave your computer vulnerable again. Use this as a last resort if none of the above methods helped resolve the error.

To uninstall Windows updates:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**  
![control panel uninstall programs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/control-panel-uninstall-programs.jpg)
3. Next, click on**Programs** .  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880944/19272" target="_top" id="1880944">
  <img src="//a.impactradius-go.com/display-ad/19272-1880944" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880944/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![control panel uninstall programs view installed updatges](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/control-panel-uninstall-programs-view-installed-updatges.jpg)
4. Click on**View installed updates** under**Programs and Features** . This will open the**Uninstall updates** section in the**Settings** app. Alternatively, go to **Settings > Windows Update > Update history > Uninstall updates** to access the same.  
![uninstall windows updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/uninstall-windows-updates.jpg)
5. Locate the problematic update (**KB5005565**) and click on**Uninstall** .
6. Click**Uninstall** again to confirm the action. Wait for the update to uninstall and restart your PC to apply the changes.

## Fixing the 0x0000011b Printing Error on Windows

 This error has largely affected Windows 10 computers. To fix the issue, try to install all the pending Windows updates that may include a hotfix. You can also add the printer manually to a local port or edit the registry entry to disable the problematic setting. If nothing works, uninstalling the security update may be the last resort. However, doing so can put your computer at risk of print spooler spoofing vulnerability.

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
<li><a href="https://youtube-web.techidaily.com/024-approved-rethink-your-youtube-videos-with-these-non-youtube-edits/"><u>[New] 2024 Approved Rethink Your YouTube Videos with These Non-Youtube Edits</u></a></li>
<li><a href="https://youtube-web.techidaily.com/op-picks-7-exceptional-android-adblocking-apps-for-2024/"><u>[New] Top Picks 7 Exceptional Android AdBlocking Apps for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-from-ordinary-to-outstanding-mastering-instagram-editing-skills/"><u>[Updated] 2024 Approved From Ordinary to Outstanding Mastering Instagram Editing Skills</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-channel-personality-complimentary-youtube-graphics-for-2024/"><u>[Updated] Channel Personality Complimentary YouTube Graphics for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-four-straightforward-methods-for-lenovo-screenshots-for-2024/"><u>[Updated] Four Straightforward Methods for Lenovo Screenshots for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-live-stream-reader/"><u>[Updated] Live Stream Reader</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-unleash-the-power-of-seo-skyrocketing-through-youtube-rankings/"><u>[Updated] Unleash the Power of SEO Skyrocketing Through YouTube Rankings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-the-hidden-addresses-of-installed-pc-apps/"><u>Demystifying the Hidden Addresses of Installed PC Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-the-user-experience-with-drive-views/"><u>Enhancing the User Experience with Drive Views</u></a></li>
<li><a href="https://extra-resources.techidaily.com/exclusive-win-audio-experience/"><u>Exclusive Win Audio Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-the-capabilities-of-microsoft-family-safety/"><u>Exploring the Capabilities of Microsoft Family Safety</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/maximizing-audience-reach-twitch-livest-writes-for-youtube/"><u>Maximizing Audience Reach Twitch Livest Writes for YouTube</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-vlogs-and-travel-content-are-incomplete-without-a-fast-motion-effect-learn-step-by-step-how-to-make-fast-motion-video-on-an-iphone-in-this/"><u>New 2024 Approved Vlogs and Travel Content Are Incomplete without a Fast-Motion Effect. Learn Step-by-Step How to Make Fast Motion Video on an iPhone in This Article</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proper-planning-essential-steps-for-using-wsl-2-right/"><u>Proper Planning: Essential Steps for Using WSL 2 Right</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safety-switch-stopping-windows-11-tasks/"><u>Safety Switch: Stopping Windows 11 Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-data-how-to-use-controlling-access-settings-in-windows/"><u>Securing Data: How to Use Controlling Access Settings in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-pathway-for-windows-11-emulation-on-workstation-17/"><u>The Ultimate Pathway for Windows 11 Emulation on Workstation 17</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbocharge-workflows-utilize-flow-launcher-for-maximum-output/"><u>Turbocharge Workflows: Utilize Flow Launcher for Maximum Output</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-windows-canary-an-easy-to-follow-guide/"><u>Understanding Windows Canary: An Easy-to-Follow Guide</u></a></li>
</ul></div>

