---
title: Remedying 'Windows Unable to Manage Default Audio Device'
date: 2024-10-03T01:01:32.053Z
updated: 2024-10-03T20:38:25.132Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remedying 'Windows Unable to Manage Default Audio Device'
excerpt: This Article Describes Remedying 'Windows Unable to Manage Default Audio Device'
keywords: Fix Windows Audio Issue,Manage Default Device,Resolve Audio Error,Unique Sound Driver,Audio Settings Repair,Default Device Recovery,WinAudio Troubleshoot
thumbnail: https://thmb.techidaily.com/33bb4081d4eeefa2b002761f140e6d8a1ab23c4b8fc2690daa04e9c88bdd81bd.jpg
---

## Remedying 'Windows Unable to Manage Default Audio Device'

 It’s advisable to safely eject a USB drive inserted in your Windows 11/10 PC. However, upon doing so, some users report seeing an error message that reads “Windows can’t stop your generic volume device.” Consequently, users can’t safely eject USB drives with their PCs on.

 Of course, you can still safely remove a USB drive with a PC off. However, many users still prefer to be able to safely eject their connected drives without shutting down their computer. This is how you can fix the “Windows can’t stop your generic volume device” error.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Disable Background App Processes

 Disabling background app processes is the first thing you should try when you see the “Windows can’t stop your generic volume device” error. Even the error message suggests closing programs that could still be using the device.

 Make sure there aren’t any minimized software windows on your taskbar; close unneeded apps within the system tray area by right-clicking their icons and selecting exit options.

![System tray icons](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/system-tray-programs.jpg)

 Beyond the taskbar and system tray, you’ll need to look for and disable background app processes with Task Manager. Task Manager is a tool that provides a comprehensive overview of app and service background processes.

 Our guide on [fixing too many background processes running](https://www.makeuseof.com/windows-pc-too-many-background-processes/) provides more detail on how to terminate unneeded background apps and services with Task Manager.

## 2\. End and Restart the Windows Explorer Process

 Some users confirm ending and restarting the File Explorer process fixes the “Windows can’t stop your generic volume device” error. That highlights File Explorer is causing the error and needs to be stopped from utilizing the USB drive.

 Follow these steps to end and restart File Explorer:

1. Right-click a taskbar space and select the **Task Manager** context menu option.
2. Scroll down the **Processes** tab in Task Manager until you see Windows Explorer.
3. Right-click Windows Explorer and select **End task**. Your desktop will go blank, but restarting Explorer will restore it.  
![The End task option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/end-task-option.jpg)
4. Click Task Manager’s **File** menu.
5. Select **Run new task** on the menu.
6. Then input **explorer** in Create new task.  
![The Create a new task tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-create-a-new-task-window.jpg)
7. Select **Create this task with administrative privileges**.
8. Click **OK** to restart Explorer.

<!-- affiliate ads begin -->
<span id="1424531">
					<video width="864" height="NaN" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424531.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424531">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424531.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424531%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424531/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Troubleshoot the Device

 You can troubleshoot a USB device by running the Hardware and Devices troubleshooter with the drive connected. That troubleshooter might address some drive ejection issues.

 The Hardware and Devices troubleshooter isn’t listed in Settings. However, you can still find and use it by opening it via the Command Prompt using these steps:

1. Press **Windows** key **+** **S** to activate a file search tool, and input Command Prompt within its text box.
2. Select **Command Prompt** to open it from the search results.
3. Input and execute this Hardware and Devices command:  
`msdt.exe -id DeviceDiagnostic`  
![The Hardware and Devices troubleshooter command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hardware-and-devices-troubleshooter.jpg)
4. Click **Next** to run the troubleshooting tool.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043638/7443" target="_top" id="2043638">
  <img src="//a.impactradius-go.com/display-ad/7443-2043638" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043638/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Hardware and Devices troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hardware-and-devices-troubleshooter4.jpg)
5. The troubleshooter might ask you to select a device. If it does, select your connected USB storage device.  

![A USB Attached option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/usb-attached-option.jpg)
6. Click **Apply this fix** if the Hardware and Devices troubleshooter suggests a resolution.

## 4\. Select the Quick Removal Option

 Selecting the **Quick Removal** option is another confirmed fix for the “Windows can’t stop your generic volume device” error. The **Quick Removal** option disables write caching. You can select the **Quick Removal** option for an affected drive using the following steps:

1. Click File Explorer’s taskbar shortcut and select This PC.
2. Right-click your USB drive and select **Properties**.
3. Click the **Hardware** tab.  
![The Hardware tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-hardware-tab.jpg)
4. Then press the **Properties** button.

5. Click **Change settings** to bring up another window.  
![The Change settings button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-settings-button.jpg)
6. Select **Policies** in the second window.
7. Then click the **Quick removal (default)** option.  
![The Quick removal radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/quick-removal-option.jpg)
8. Select **OK** to exit the device properties window.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918679/19272" target="_top" id="1918679">
  <img src="//a.impactradius-go.com/display-ad/19272-1918679" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918679/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Deselect the Index Drive Setting

 Having file indexing enabled for an external USB drive can cause the “Windows can’t stop your generic volume” error. If that option is enabled, files copied onto your USB drive will be indexed, which can keep it in use for some time after transferring lots of files onto it.

 Follow these steps to deselect indexing for a USB drive:

1. Go to This PC in File Explorer.
2. Right-click the USB drive connected and select **Properties**.
3. Deselect the **Allow files on this drive to have contents indexed in addition to file properties** option.  
![The Allow files on this drive to have contents indexed box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/index-option.jpg)
4. Select **Apply** and **OK** to set the drive’s new setting.

## 6\. Set the Connected USB Drive to Be in Offline Mode

 A lot of users have fixed the “Windows can’t stop your generic volume device” error by setting their USB drives into offline mode. So, try setting your connected USB drive to offline mode with the DiskPart command-line line tool using these steps:

1. Press the **Windows** logo + **R** key combo for activating Run.
2. Input **cmd** into Run, and press **Ctrl** \+ **Shift** \+ **Enter** to [open Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
3. Then input this Diskpart command and hit **Enter**:  
`diskpart`
4. To view a drive list, input the following text and press **Return**:  
`list disk`  
![The diskpart command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/list-disk-command.jpg)
5. Next, execute this command to select your USB drive:  

<!-- affiliate ads begin -->
<span id="1424529">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424529.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424529">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424529.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424529%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424529/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`select disk <drive number>`
6. Finally, set the selected disk to offline by executing this command:  
`offline disk`  
![The offline command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/offline-command.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139107/17108" target="_top" id="2139107">
  <img src="//a.impactradius-go.com/display-ad/17108-2139107" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139107/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You will need to replace **<drive number>** for the select disk command with the actual number of your USB drive listed by Diskpart. For example, if your USB drive is disk 1, the required command would look like this:

`select disk 1`

 Setting a drive offline changes its status to missing. You can set the same drive back to an online status by repeating steps one to five above and then executing this command:

`online disk`

## 7\. Assign a Different Letter to the USB Drive

 Some users have also resolved the “Windows can’t stop your generic volume device” by changing the letters of their USB drives. Assigning a different letter to a USB drive will disconnect it from certain processes.

 You can even change the drive letter back to what it originally was another time. To apply this fix, check out this [guide to changing a drive’s letter in Windows](https://www.makeuseof.com/tag/change-drive-letter-windows/).

![The Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disk-management-window.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135401/19272" target="_top" id="2135401">
  <img src="//a.impactradius-go.com/display-ad/19272-2135401" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135401/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115946/19272" target="_top" id="2115946">
  <img src="//a.impactradius-go.com/display-ad/19272-2115946" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115946/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Safely Eject Your USB Drive

 Removing a USB drive from a PC without safely ejecting it can corrupt the data on it. So, it’s not a good idea to ignore the “Windows can’t stop your generic volume device” error.

 Applying the potential solutions covered here will resolve the error for most users. Then, you can safely remove your USB drive in Windows 11/10 with alternative methods.

 Of course, you can still safely remove a USB drive with a PC off. However, many users still prefer to be able to safely eject their connected drives without shutting down their computer. This is how you can fix the “Windows can’t stop your generic volume device” error.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/new-youtube-playlist-rearrangement-made-simple/"><u>[New] YouTube Playlist Rearrangement Made Simple</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-accelerate-youtube-visibility-select-top-8-rank-watchers/"><u>[Updated] Accelerate YouTube Visibility - Select Top 8 Rank Watchers</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-precise-codex-of-conduct-in-the-digital-realm/"><u>[Updated] Precise Codex of Conduct in the Digital Realm</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-the-educators-roadmap-to-effective-multimedia-use/"><u>2024 Approved The Educator's Roadmap to Effective Multimedia Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-techniques-to-uninstall-printers-in-win11/"><u>Effective Techniques to Uninstall Printers in Win11</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-connect-an-xbox-one-controller-when-its-not-syncing/"><u>How to Connect an Xbox One Controller (When It’s Not Syncing)</u></a></li>
<li><a href="https://fox-helps.techidaily.com/including-a-cover-letter-in-profile-for-2024/"><u>Including a Cover Letter in Profile for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-solving-a-driverirqlnotlessorequal-error/"><u>Mastering the Art of Solving 'A DRIVER_IRQL_NOT_LESS_OR_EQUAL' Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-path-failure-in-win10/"><u>Steps to Rectify PATH Failure in Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stopping-windows-update-notifications/"><u>Stopping Windows Update Notifications</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/the-first-timers-blueprint-for-youtube-income-for-2024/"><u>The First-Timer's Blueprint for YouTube Income for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-system-overheats-rms-cpu-solution-guide/"><u>Troubleshooting System Overheats: RM's CPU Solution Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-potential-file-type-changes/"><u>Unlocking Windows' Potential: File Type Changes</u></a></li>
</ul></div>

