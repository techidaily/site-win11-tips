---
title: Solutions for Device Not Found on Windows Systems
date: 2024-09-01T05:20:30.953Z
updated: 2024-09-02T05:20:30.953Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solutions for Device Not Found on Windows Systems
excerpt: This Article Describes Solutions for Device Not Found on Windows Systems
keywords: Windows Device Recovery,Fix Unrecognized Devices,Windows Connect Issue,Restore Missing Hardware,Resolve Device Errors,PC Hardware Detection,Reconnect Lost Devices
thumbnail: https://thmb.techidaily.com/84dab43ab035d91cb56a4eae408b40758af9a9a2b096c95f61afee80ed15090c.jpg
---

## Solutions for Device Not Found on Windows Systems

 Many users partition their hard drives or utilize external storage devices with their PCs. However, such drives become inaccessible when the “A device which does not exist was specified” error arises. Users have reported seeing this strange error message when they try to open connected external storage devices or drive partitions inside Windows File Explorer.

 That error is most unwelcome since it means users can’t open whatever drives it arises for. Consequently, they can’t access files on affected drives. This is how you can fix the “device which does not exist was specified” error in Windows 10 and 11.

## 1\. Plug the Affected Device Into a Different USB Slot

 If this error is affecting an external storage device, try reconnecting the USB drive. There might be an issue with the port you’ve connected the drive with. Plug the USB drive into a different port to see if the same error occurs.

 If you need to resolve this error for an internal drive, check the drive’s internal connections. To do that, you’ll need to open the case for a desktop PC. Then make sure none of the drive’s connection cables are in any way loose.

## 2\. Run the SFC Tool

 Users have confirmed the System File Checker tool can resolve this drive error. That highlights system file corruption can cause this issue, which an SFC scan will likely resolve. Our guide to[running a System File Checker scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to execute the SFC command in Windows.

![The sfc /scannow](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/sfc-scannow.jpg)

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Run a Check Disk Scan for the Drive

 You might need to fix the “device which does not exist was specified” error because your drive has some bad sectors. Running a CHKDSK (Check Disk) scan command is a potential remedy for bad drive sectors. This is how you can run the Windows Check Disk tool from the Command Prompt:

1. Open the search tool by simultaneously pressing the**Windows** logo +**S** keys.
2. Enter the search phrase**cmd** inside the text box.
3. Click**Run as administrator** to start Command Prompt with elevated permissions.
4. Then execute the Check Disk scan by inputting this command:  
`chkdsk X: /f /r`  
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/chkdsk-scan.jpg)
5. Press**Enter** to initiate the scan.
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You’ll need to replace X in the above command with the actual letter of the affected drive you need to scan. For example, the command for a drive labeled D would be:

`chkdsk D: /f /r`

## 4\. Try Changing the Drive’s Letter

 Changing the affected drive’s letter is a potential fix that users have confirmed to work. You can change the drive’s letter with the Disk Management tool like this:

1. If you need to fix this issue for an external drive, connect that storage device to your PC.
2. Open Disk Management by right-clicking**Start** and selecting the shortcut for that tool.
3. Right-click the affected drive and select**Change Drive Letter and Paths** .  
![The Change Drive Letter and Paths option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-drive-letter-paths.jpg)
4. Press the**Change** button.  
![The Change Drive Letter window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-drive-letter-window.jpg)
5. Click the drop-down menu for the**Assign the following drive lette** r option.  
![The Assign the following drive letter option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/assign-the-following-drive-letter.jpg)
6. Select a drive letter that you’ve never used.
7. Click**OK** on the Change Drive Letter or Path window.
8. Select**Yes** on the Disk Management confirmation dialog.

## 5\. Rescan a Drive

 Disk Management includes a**Rescan Disk** option for troubleshooting drives. That option detects disk changes and updates drive info accordingly when selected. So, rescanning the disk is a viable troubleshooting method for resolving this “device which does not exist” error. This is how you can rescan a drive:

1. Plug the drive into your PC if necessary.
2. Bring up the Disk Management tool.
3. Click the drive for which the error occurs in Disk Management.
4. Then click the**Action** menu.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/properties-option2.jpg)
5. Select**Rescan Disks** on the menu.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
## 6\. Select the Full Control Option for a Drive Location

 The “device which does not exist” error can arise because of restricted drive permissions. In that scenario, users need to select a**Full control** permission option for their drives. These are the steps for selecting the**Full control** permission setting:

1. First, activate the file management tool with Explorer’s**Windows** logo +**E** hotkey.
2. Then click**This PC** in Explorer’s left sidebar.
3. Right-click the affected drive to select**Properties** .  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/properties-option2.jpg)
4. Click the drive’s**Security** tab.
5. If the**Full control** option isn’t ticked, click the**Edit** button.
6. Select the**Allow** box for the**Full control** option.  
![The Full control option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/full-control-checkbox.jpg)
7. Click**Apply** \>**OK** on the drive’s permissions window.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Reinstall the Affected Drive

 If you need to fix this issue for an external storage device, try reinstalling the affected drive. Doing so will reinstall the drivers for the affected storage device. This is how you can reinstall the drive:

Insert the affected drive into one of your PC’s USB ports.

1. Click**Start** with the right mouse button to select a**Device Manager** shortcut.
2. Double-click**Disk drives** in Device Manager.
3. Right-click your drive and select**Uninstall device** .  
![The Uninstall device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/uninstall-device2.jpg)
4. Then select the**Uninstall** option on the dialog box prompt.  
![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/uninstall-option3.jpg)
5. Disconnect the drive plugged into the PC.
6. Plug the drive back into the computer to reinstall its driver.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## 8\. Update Your Motherboard’s Chipset Driver

 It might be necessary for some users to update motherboard drivers to fix this issue. To do so manually, you’ll need the motherboard model and manufacturer details. You can check those details as follows:

1. Open the Windows search box, and type a**System Information** keyword there.
2. Click**System Information** to view that app’s window.
3. Note down the**BaseBand Product** and**BaseBand Manufacturer** details.  
![Baseboard specs in System Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/baseboard-specs.jpg)
4. [Open the Command Prompt](https://www.makeuseof.com/windows-11-open-command-prompt/) if the System Information app doesn’t include a serial number for the motherboard.
<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Execute this baseboard command:  
`wmic baseboard get product,Manufacturer,version,serialnumber`  
![The baseboard command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/baseboard-command.jpg)
6. Copy and paste the serial number for the motherboard shown within the Command Prompt into Notepad or another text editor.
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then open the download section of your motherboard manufacturer’s website. Select your motherboard model and download its latest chipset driver from there. You can install the new driver for your motherboard with the downloaded driver (setup.exe) package file.

 The driver package might be included within a ZIP archive, which you’ll need to extract as outlined within this guide to[unzipping files in Windows](https://www.makeuseof.com/unzip-files-windows-10/) .

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
## Access Your Drive Again on Windows

 Those potential solutions will probably fix the “device which does not exist” drive error for most users. If they’re not enough, there could be an issue with your PC’s motherboard headers. In that case, consider taking your PC to a reputable repair service to resolve such an issue.

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
<li><a href="https://instagram-clips.techidaily.com/new-mac-tricks-for-dynamic-instagram-video-size-adjustment/"><u>[New] Mac Tricks for Dynamic Instagram Video Size Adjustment</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-phantom-3-battle-disguise-4-comes-out/"><u>[Updated] 2024 Approved  Phantom 3 Battle  Disguise 4 Comes Out</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-best-youtube-banner-size-and-channel-art-dimension-the-ultimate-guide/"><u>[Updated] Best YouTube Banner Size and Channel Art Dimension (The Ultimate Guide)</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-simplified-guide-efficient-screen-recording-for-dell-users/"><u>[Updated] In 2024, Simplified Guide  Efficient Screen Recording for Dell Users</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-vsdc-vs-alternatives-a-comprehensive-evaluation/"><u>[Updated] In 2024, VSDC vs Alternatives  A Comprehensive Evaluation</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-transforming-movs-to-mp4mkv-on-pc-for-2024/"><u>[Updated] Transforming MOVs to MP4/MKV on PC for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpt-plus-reviewed-insights-into-its-strengths-and-weaknesses/"><u>ChatGPT Plus Reviewed: Insights Into Its Strengths and Weaknesses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-breakdown-understanding-windows-odbc-system/"><u>Comprehensive Breakdown: Understanding Windows' ODBC System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-main-panel-of-windows-11-task-manager/"><u>Customizing Main Panel of Windows 11 Task Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/direct-download-methods-for-newcomers-to-windows/"><u>Direct Download Methods for Newcomers to Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ease-of-access-disabling-security-interrogation-for-windows-11-admin/"><u>Ease of Access: Disabling Security Interrogation for Windows 11 Admin</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-verizon-is-shaping-the-future-with-its-advancements-in-5g/"><u>How Verizon Is Shaping the Future with Its Advancements in 5G</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-forgot-your-apple-id-password-and-email-on-apple-iphone-13-pro-heres-the-best-fixes-by-drfone-ios/"><u>In 2024, Forgot Your Apple ID Password and Email On Apple iPhone 13 Pro? Heres the Best Fixes</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-activate-and-use-life360-ghost-mode-on-infinix-smart-8-hd-drfone-by-drfone-virtual-android/"><u>In 2024, How To Activate and Use Life360 Ghost Mode On Infinix Smart 8 HD | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-xiaomi-mix-fold-3-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Xiaomi Mix Fold 3 Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterclass-creating-multiple-subfolders-with-ease-in-windows/"><u>Masterclass: Creating Multiple Subfolders with Ease in Windows</u></a></li>
<li><a href="https://unlock-android.techidaily.com/mastering-lock-screen-settings-how-to-enable-and-disable-on-itel-p40-by-drfone-android/"><u>Mastering Lock Screen Settings How to Enable and Disable on Itel P40</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-window-11s-help-service-disruption/"><u>Mending Window 11'S Help Service Disruption</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/navigate-to-the-forefront-a-guide-to-the-webs-10-giants-in-popularity/"><u>Navigate to the Forefront: A Guide to the Web’s 10 Giants in Popularity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-11s-elevation-conflict-overcoming-error-740/"><u>Navigating Windows 11'S Elevation Conflict: Overcoming Error #740</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-visuals-on-win1011-by-driver-rebooting/"><u>Optimizing Visuals on Win10/11 by Driver Rebooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-vanished-recorded-run-events/"><u>Preventing Vanished Recorded Run Events</u></a></li>
<li><a href="https://win11-tips.techidaily.com/propel-your-productivity-key-strategies-with-windows-11/"><u>Propel Your Productivity: Key Strategies with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrecting-off-screen-windows-6-steps-for-win11/"><u>Resurrecting Off-Screen Windows: 6 Steps for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-windows-files-with-top-tricks-max-156/"><u>Simplify Windows Files with Top Tricks (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-prevalent-anydesk-glitches-in-windows-os/"><u>Solving Prevalent AnyDesk Glitches in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stabilizing-the-sweep-of-your-cursor-deactivating-mouse-accel-in-win-11/"><u>Stabilizing the Sweep of Your Cursor: Deactivating Mouse Accel in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-to-resolve-failing-windows-discord-updates/"><u>Step by Step to Resolve Failing Windows Discord Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-address-critical-javascript-failure-in-discord-on-windows/"><u>Steps to Address Critical JavaScript Failure in Discord on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-correct-token-misreference-errors-on-win10win11/"><u>Strategies to Correct Token Misreference Errors on Win10/Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-value-proposition-of-windows-11s-interactive-elements/"><u>The Value Proposition of Windows 11'S Interactive Elements</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-autonomous-vehicle-brands-taking-over-roads-the-top-4-companies/"><u>Top Autonomous Vehicle Brands Taking Over Roads : The Top 4 Companies</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/tracking-youtubes-signature-interactions-for-2024/"><u>Tracking YouTube's Signature Interactions for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-to-enhanced-widget-display-interface-in-windows-11/"><u>Transitioning to Enhanced Widget Display Interface in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/triple-threat-tweaks-for-personalized-win11-preferences/"><u>Triple-Threat Tweaks for Personalized Win11 Preferences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1011-hack-abruptly-delete-non-responsive-printers/"><u>Windows 10/11 Hack: Abruptly Delete Non-Responsive Printers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-sound-system-enhancement-through-drivers-update-tutorial/"><u>Windows Sound System Enhancement Through Drivers Update Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/xbox-not-launching-regain-control-with-these-tricks/"><u>Xbox Not Launching? Regain Control with These Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/your-pathway-to-elevated-settings-windows-11s-higher-power/"><u>Your Pathway to Elevated Settings: Windows 11'S Higher Power</u></a></li>
</ul></div>
