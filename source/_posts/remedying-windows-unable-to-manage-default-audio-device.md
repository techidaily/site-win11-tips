---
title: Remedying 'Windows Unable to Manage Default Audio Device'
date: 2024-09-25T16:12:04.275Z
updated: 2024-09-28T19:05:48.114Z
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
<a href="https://imp.i357552.net/c/5597632/863035/11832" target="_top" id="863035">
  <img src="//a.impactradius-go.com/display-ad/11832-863035" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/863035/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Hardware and Devices troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hardware-and-devices-troubleshooter4.jpg)
5. The troubleshooter might ask you to select a device. If it does, select your connected USB storage device.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997680/19272" target="_top" id="1997680">
  <img src="//a.impactradius-go.com/display-ad/19272-1997680" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997680/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![A USB Attached option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/usb-attached-option.jpg)
6. Click **Apply this fix** if the Hardware and Devices troubleshooter suggests a resolution.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135393/19272" target="_top" id="2135393">
  <img src="//a.impactradius-go.com/display-ad/19272-2135393" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135393/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Select the Quick Removal Option

 Selecting the **Quick Removal** option is another confirmed fix for the “Windows can’t stop your generic volume device” error. The **Quick Removal** option disables write caching. You can select the **Quick Removal** option for an affected drive using the following steps:

1. Click File Explorer’s taskbar shortcut and select This PC.
2. Right-click your USB drive and select **Properties**.
3. Click the **Hardware** tab.  
![The Hardware tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-hardware-tab.jpg)
4. Then press the **Properties** button.

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/1943647/22993" target="_top" id="1943647">
  <img src="//a.impactradius-go.com/display-ad/22993-1943647" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://homestyler.sjv.io/i/5597632/1943647/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Click **Change settings** to bring up another window.  
![The Change settings button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-settings-button.jpg)
6. Select **Policies** in the second window.
7. Then click the **Quick removal (default)** option.  
![The Quick removal radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/quick-removal-option.jpg)
8. Select **OK** to exit the device properties window.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087239/19272" target="_top" id="2087239">
  <img src="//a.impactradius-go.com/display-ad/19272-2087239" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087239/19272" style="position:absolute;visibility:hidden;" border="0" />
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
`select disk <drive number>`
6. Finally, set the selected disk to offline by executing this command:  
`offline disk`  
![The offline command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/offline-command.jpg)

 You will need to replace **<drive number>** for the select disk command with the actual number of your USB drive listed by Diskpart. For example, if your USB drive is disk 1, the required command would look like this:

`select disk 1`

 Setting a drive offline changes its status to missing. You can set the same drive back to an online status by repeating steps one to five above and then executing this command:

`online disk`

<!-- affiliate ads begin -->
<a href="https://jalbum-affiliate-program.sjv.io/c/5597632/1584040/17916" target="_top" id="1584040">
  <img src="//a.impactradius-go.com/display-ad/17916-1584040" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://jalbum-affiliate-program.sjv.io/i/5597632/1584040/17916" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Assign a Different Letter to the USB Drive

 Some users have also resolved the “Windows can’t stop your generic volume device” by changing the letters of their USB drives. Assigning a different letter to a USB drive will disconnect it from certain processes.

 You can even change the drive letter back to what it originally was another time. To apply this fix, check out this [guide to changing a drive’s letter in Windows](https://www.makeuseof.com/tag/change-drive-letter-windows/).

![The Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disk-management-window.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135370/19272" target="_top" id="2135370">
  <img src="//a.impactradius-go.com/display-ad/19272-2135370" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135370/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Safely Eject Your USB Drive

 Removing a USB drive from a PC without safely ejecting it can corrupt the data on it. So, it’s not a good idea to ignore the “Windows can’t stop your generic volume device” error.

 Applying the potential solutions covered here will resolve the error for most users. Then, you can safely remove your USB drive in Windows 11/10 with alternative methods.

 Of course, you can still safely remove a USB drive with a PC off. However, many users still prefer to be able to safely eject their connected drives without shutting down their computer. This is how you can fix the “Windows can’t stop your generic volume device” error.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://twitter-videos.techidaily.com/updated-essential-guide-fetching-twitter-videos-directly-from-mobile/"><u>[Updated] Essential Guide Fetching Twitter Videos Directly From Mobile</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-online-broadcasting-basics-a-streamers-guide-to-capture/"><u>[Updated] Online Broadcasting Basics A Streamer’s Guide to Capture</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-ultimate-guide-the-top-11-waterproof-camcorders-for-kids-vloggers-for-2024/"><u>[Updated] Ultimate Guide The Top 11 Waterproof Camcorders For Kids Vloggers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/2024s-best-windows-computers-for-enhanced-productivity/"><u>2024'S Best Windows Computers for Enhanced Productivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-your-online-gaming-experience-with-discord-on-windows/"><u>Accelerating Your Online Gaming Experience with Discord on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapting-fn-key-operations-in-the-latest-windows-os/"><u>Adapting FN Key Operations in the Latest Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-disasterous-dism-error-0x800f082f-on-windows/"><u>Banishing Disasterous DISM: Error 0X800F082F on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-efficiency-6-must-have-windows-productivity-tools/"><u>Boosting Efficiency: 6 Must-Have Windows Productivity Tools</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/facebooks-visual-journey-capturing-videos-for-2024/"><u>Facebook's Visual Journey Capturing Videos for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-mp4-and-avi-files-of-nokia-c12-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair corrupt MP4 and AVI files of Nokia C12? </u></a></li>
<li><a href="https://extra-guidance.techidaily.com/navigating-character-customization-with-ease-and-excitement-for-2024/"><u>Navigating Character Customization with Ease and Excitement for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unpacking-samsung-2025-detailed-schedule-latest-tech-news-hype-and-speculations/"><u>Unpacking Samsung 2025: Detailed Schedule, Latest Tech News, Hype and Speculations</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/what-pokemon-evolve-with-a-dawn-stone-for-honor-90-gt-drfone-by-drfone-virtual-android/"><u>What Pokémon Evolve with A Dawn Stone For Honor 90 GT? | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    