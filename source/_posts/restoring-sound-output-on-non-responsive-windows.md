---
title: Restoring Sound Output on Non-Responsive Windows
date: 2024-11-16T20:18:09.794Z
updated: 2024-11-17T18:22:06.842Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Sound Output on Non-Responsive Windows
excerpt: This Article Describes Restoring Sound Output on Non-Responsive Windows
keywords: Rescue Audio Windows,Fix Sound on Windows,Recover Noise Output,Resolve Silent PC,Amplify PC Sounds,Reactivate Windows Sound,Enhance Audible Feedback
thumbnail: https://thmb.techidaily.com/4708f3ad86d66e7ad10dd3b75bdecccf20aa6cf32be5cc5adbe8d57734cb7714.jpg
---

## Restoring Sound Output on Non-Responsive Windows

 Although Windows includes a dedicated audio troubleshooter that can help resolve most audio-related issues, it may not always be effective. At times, the Windows audio troubleshooter may fail to resolve the underlying issue and display the “Audio services not responding” error.

 If the audio services on your Windows computer have become unresponsive, don’t fret. This guide packs some useful troubleshooting tips that should help you resolve the issue in no time.

## 1\. Restart the Windows Audio Service

 Typically, the Windows Audio service starts automatically when your computer boots. However, if the service encounters any problems during startup, it may malfunction. If it's just a one-off glitch, restarting the Windows Audio service should fix the issue. Hence, you should start with that.

To restart the Windows Audio service:

1. Press**Win + S** to open the search menu.
2. Type**services** in the text box and press**Enter** .
3. In the Services window, scroll down to locate the**Windows Audio** service on the list. Then, right-click on it and select**Restart** .  
![Restart Windows Audio Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-windows-audio-service.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918666/19272" target="_top" id="1918666">
  <img src="//a.impactradius-go.com/display-ad/19272-1918666" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918666/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Make Sure the Supporting Audio Components Are Running

 Windows Audio service relies on several system components to function properly on your PC. If one of these components is not running, audio services may stop responding.

Here’s how to check if the required services are running.

1. Press**Win + R** to open the Run dialog box.
2. Type**services.msc** in the Open field and press**Enter** .
3. Locate the**RPC Endpoint Mapper** service on the list and double-click on it to open its properties.
4. Click the drop-down menu next to**Startup type** to select**Automatic** .
5. Click**Apply** followed by**OK** .
6. Similarly, change the startup type for**Remote Procedure Call (RPC)** and**DCOM Server Process Launcher** services as well.  
![Remote Procedure Call Service in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/remote-procedure-call-service-in-windows.jpg)

Restart your PC after this and check if the issue is still there.

## 3\. Add Local and Network Services Using Command Prompt

 Another thing you can do to resolve this issue is to register local and network services on Windows using Command Prompt. Here are the steps for the same.

1. Right-click on the**Start icon** or press**Win + X** to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Type the following command in the console and press**Enter** to register network services on your system.  
`net localgroup Administrators /add networkservice`
5. Now run the following command to register local services:  
`net localgroup Administrators /add localservice`
6. Exit the Command Prompt window and then restart your PC.  
![Add Local and Network Services Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-local-and-network-services-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087409/7443" target="_top" id="2087409">
  <img src="//a.impactradius-go.com/display-ad/7443-2087409" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087409/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Like using Command Prompt? Check our guide to learn[how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/947750/11832" target="_top" id="947750">
  <img src="//a.impactradius-go.com/display-ad/11832-947750" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/947750/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Update Audio Drivers

 Outdated or incompatible audio drivers on your PC can also cause the audio services to malfunction. If that's the case, updating the audio drivers on your PC should do the trick. If you need help with that, check our guide on[how to update audio drivers on Windows](https://www.makeuseof.com/update-audio-drivers-windows/) and follow the steps outlined there.

 If updating audio drivers manually sounds like a tedious task, you can get one of the[best driver updater for Windows](https://www.makeuseof.com/windows-best-free-driver-updaters/) to ease the process.

## 5\. Switch to the Default Sound Drivers

 Your Windows computer comes with its own set of sound drivers. If updating your current audio drivers does not help, you can switch to Windows' default sound drivers and see if that works. To do so, use the following steps:

1. Click the**magnifying icon** on the taskbar or press**Win + S** to open the search menu.
2. Type**control panel** in the text box and select the first result that appears.
3. Navigate to**System > Advanced System Settings** .
4. In the System Properties window, switch to the**Hardware** tab and click the**Device Installation Settings** button.
5. Select the**No (your device might not work as expected)** option and click**Save Changes** .

1. Select**Yes** when the User Account Control (UAC) prompt appears.  
![Device Installation Settings on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/device-installation-settings-on-windows.jpg)
2. Now use one of the[many ways to open Device Manager](https://www.makeuseof.com/windows-open-device-manager/) .
3. Expand the**Sound, video, and game controllers** .
4. Right-click on your sound driver and select**Uninstall device** .
5. Select**Uninstall** to confirm the action.
6. In the Device Manager window, click the**Action** menu at the top and select**Scan for hardware changes** from the list.  
![Uninstall Sound Driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/uninstall-sound-driver.jpg)

## 6\. Run the SFC and DISM Scans

 Corrupt or damaged system files on Windows can also cause audio services to stop responding. System File Checker (SFC) and Deployment Image Servicing and Management (DISM) are two Windows tools that can help you identify and repair such system files.

 The SFC scan will check your computer for missing or corrupt system files, whereas DISM will repair the Windows system image. You can run these tools using Command Prompt. To know more, check our guide on[how to repair corrupt Windows files with Windows built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/) and follow the steps outlined there.

## 7\. Perform a System Restore

 System Restore is a useful feature on Windows that creates a backup of your entire system at predefined intervals. It can help you restore your system to the point before the problem occurred.

 System Restore will undo any recent changes made to your computer and resolve the issue for good. Don’t worry, this process won’t affect any of your personal data.

To perform a system restore on Windows, use these steps:

1. Right-click on the**Start** icon and select**Run** from the list.
2. Type**sysdm.cpl** in the box and press**Enter** .
3. In the System Properties window, switch to the**System Protection** tab.
4. Click on**System Restore** .
5. Click**Next** .
6. Select a restore point before the issue first appeared and hit**Next** .
7. Review all the details and click**Finish** .  
![System Restore Dialog on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/system-restore-dialog-on-windows.jpg)

<!-- affiliate ads begin -->
<span id="1531882">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1531882.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1531882">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1531882.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1531882%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1531882/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Wait for Windows to restart and revert to the specified restore point. After that, the audio services should work fine.

## Fixing Audio Services on Windows Is Easy

 It can be confusing if the audio services on Windows suddenly become unresponsive. In most cases, manually restarting the audio services should resolve the issue. If not, you may have to go through the trouble of scanning the system files or performing a system restore.

 That said, if none of the above solutions work, you can consider resetting your Windows computer or performing an in-place upgrade as a last resort.

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
<li><a href="https://youtube-sure.techidaily.com/rom-raw-to-refined-mastering-the-art-of-pc-video-editing-on-windows/"><u>[New] From Raw to Refined Mastering the Art of PC Video Editing on Windows</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-sweep-through-your-contacts-with-speed-and-skill/"><u>[Updated] 2024 Approved Sweep Through Your Contacts with Speed and Skill</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-discovering-the-10-leading-low-cost-mobile-video-conferencing/"><u>[Updated] Discovering the 10 Leading Low-Cost, Mobile Video Conferencing</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/easily-unlock-your-tecno-spark-10-4g-device-sim-by-drfone-android/"><u>Easily Unlock Your Tecno Spark 10 4G Device SIM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-resetting-win-11-writable-memory-cache/"><u>Guide: Resetting Win 11' Writable Memory Cache</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-share-issues-on-nvidias-windows-software/"><u>How to Fix Share Issues on NVIDIA's Windows Software</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-capturing-moons-a-guide-to-proper-night-photography-techniques/"><u>In 2024, Capturing Moons A Guide to Proper Night Photography Techniques</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-edit-and-send-fake-location-on-telegram-for-your-oneplus-12-in-3-ways-drfone-by-drfone-virtual-android/"><u>In 2024, Edit and Send Fake Location on Telegram For your OnePlus 12 in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-your-iphone-7-plus-passcode-4-easy-methods-with-or-without-itunes-by-drfone-ios/"><u>In 2024, How to Unlock Your iPhone 7 Plus Passcode 4 Easy Methods (With or Without iTunes)</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-overview-of-the-best-lava-blaze-2-5g-screen-mirroring-app-drfone-by-drfone-android/"><u>In 2024, Overview of the Best Lava Blaze 2 5G Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-failed-installation-process-for-apps-from-microsoft-store/"><u>Reinstating Failed Installation Process for Apps From Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-prevent-heat-build-up-in-games-on-your-laptop/"><u>Strategies to Prevent Heat Build-Up in Games on Your Laptop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-solve-nvidias-geforce-error-x0001-on-windows/"><u>Strategies to Solve Nvidia's GeForce Error X0001 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-image-adjustment-on-your-pc-with-these-win-11-tips/"><u>Streamline Image Adjustment on Your PC with These Win 11 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-guide-to-icons-placement/"><u>The Essential Guide to Icons Placement</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/the-sony-playstation-5-examined-its-not-only-about-enhanced-strength/"><u>The Sony PlayStation 5 Examined: It's Not Only About Enhanced Strength</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-itel-s23-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Itel S23 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-error-correction-resolving-0x80070003-update-issue-in-windows/"><u>Win Error Correction: Resolving 0X80070003 Update Issue in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-personalized-edition-your-ultimate-guide/"><u>Windows 11 Personalized Edition: Your Ultimate Guide</u></a></li>
</ul></div>

