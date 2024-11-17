---
title: "Step-by-Step Guide: Win11 Network Drives"
date: 2024-11-14T18:17:52.865Z
updated: 2024-11-17T20:13:11.436Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Step-by-Step Guide: Win11 Network Drives"
excerpt: "This Article Describes Step-by-Step Guide: Win11 Network Drives"
keywords: Windows Network Drive Setup,Win11 Drives Configuration,Setting Up Win11 Shared Drives,Enable Network Drives in Win11,Guide to Win11 NAS Sharing,Win11 File System Sync,Accessing Win11 Network Drive
thumbnail: https://thmb.techidaily.com/7886b93aef2a0639ec1e094763681d9231c505608c149e23de7fcb6df36e4813.JPG
---

## Step-by-Step Guide: Win11 Network Drives

 Mapping a network drive helps you access shared folders and files on a network. It allows you to access such resources as if they were on your local computer, making it easy to work with files stored on a network.

 This can be particularly useful for businesses or organizations with multiple computers or servers that want to share files and resources between them easily.

 But is it really that simple to set up mapping? Keep reading to learn how to map a network drive in Windows 11 using different methods.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Configure Network Discovery in Windows

 Windows has a feature called[network discovery](https://www.makeuseof.com/windows-network-discovery-turn-on-off/) that allows your computer to discover and access other devices on the same network, such as computers, servers, and printers.

 This allows you to share any file or folder with other devices on the same network. Before mapping a network drive, make sure that network discovery is enabled on your computer.

Follow the sets below to enable network discovery on Windows:

1. Press**Win + I** to open the Settings app.
2. Head over to**Network & internet** from the left pane and click on**Advanced network settings** on the right.
3. Next, click on the**Advanced sharing settings** option under**More Settings** .  
![Windows Advanced Network Sharing Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-advanced-network-settings.jpg)
4. Open the**Private networks** settings and set the toggle next to**Network discovery** to**On** .  
![Windows Advanced Sharing Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-advanced-sharing-settings.jpg)
5. If you're looking to access a printer on the network, make sure to enable**File and printer sharing** .

 Once you turn on network discovery, other devices on the same network can see your computer and access it.

 Select**Private networks** if you are connected to a trusted network, such as your home network. But if you're connected to an unfamiliar network, you should select the**Public networks** option.

 Remember that enabling network discovery may make your computer more vulnerable to security risks as it allows other devices on the network to access your computer.

 Therefore, it's crucial to ensure that you have a strong password and[customize your default Windows Firewall](https://www.makeuseof.com/windows-firewall-control-guide/) to protect your device in case something goes wrong.

## 1\. Map a Network Drive Using File Explorer

 Once you have turned on network discovery, you can map a network drive in Windows 11 using File Explorer.

Here's what you need to do to use File Explorer for mapping:

1. Press**Win + E** to open File Explorer directly, and click on**This PC** in the left pane.
2. Right-click on**This PC** and select the**Map network drive...** button in the context menu that appears.  
![This PC Context Menu In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/this-pc-context-menu-in-windows.jpg)
3. Choose a unique drive letter in the**Map Network Drive** window. This is the drive you'll use to access the shared folder from your computer. As an example, we've selected**A:** as the drive letter.

<!-- affiliate ads begin -->
<span id="1977006">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977006.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977006">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977006.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977006%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977006/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Enter the path to the shared folder you want to map in the**Folder:** field. This can be a local path on the computer, such as**\\\\YourComputer\\SharedFolder** , or a network path, such as**\\\\ServerName\\SharedFolder** .  
![Windows Shared Network Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-shared-network-folder.jpg)
5. If you need a username and password to access the shared folder, check the**Connect using different credentials** box and enter the required information.
6. Click**Finish** to complete the mapping process.  
![Map Network Drive In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/map-network-drive-in-windows.jpg)

 Once you have completed these steps, it'll map the folder to the specified drive letter in File Explorer. You can access the shared folder at any time by double-clicking on the drive.

 Want to access the shared folder in milliseconds? You can create a shortcut to the mapped network drive on your desktop for quick access.

## 2\. Use Windows PowerShell for Mapping

 Windows PowerShell is a Windows command-line utility that provides a powerful set of tools and commands. One of the tasks you can perform using PowerShell is to map a network drive.

Follow these instructions to map a drive using Windows PowerShell:

1. Open the Start menu and type**PowerShell** into the search bar.
2. Select the best match and choose**Run as administrator.**
3. In the PowerShell window, type the following command, replacing**DRIVE** with the drive letter you want to use and**\\** **\\ServerName\\SharedFolder** with the path to the shared folder:  
New-PSDrive -Name DRIVE -PSProvider FileSystem -Root \\ServerName\SharedFolder  
![PowerShell Mapping Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/powershell-mapping-command.jpg)
4. If the shared folder requires a username and password to access, you can add the -Credential parameter to the command, followed by a username and password in the format username and password. For example:  
New-PSDrive -Name X -PSProvider FileSystem -Root \\ServerName\SharedFolder -Credential username password
5. Hit**Enter** to allow PowerShell to map the network drive. You can access the mapped drive from File Explorer now.

 Besides mapping, you can do a wide range of things, like managing and automating tasks on Windows. For that, you must know some[useful PowerShell commands](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) .

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528703/16446" target="_top" id="1528703">
  <img src="//a.impactradius-go.com/display-ad/16446-1528703" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528703/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Use Command Prompt for Mapping

 Just like you used PowerShell earlier, you can use the Windows Command Prompt tool to map a network drive.

So, follow these simple instructions:

1. Open[Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
2. Type the command line given below, but replace**DRIVE** with any drive letter and**\\\\ServerName\\SharedFolder** with the shared folder's path:  
net use DRIVE \\ServerName\SharedFolder
3. If the shared folder requires a username and password to access, you can add the /user parameter to the command, followed by a username and password in the format**username** and**pass** . For example:  
net use DRIVE \\ServerName\SharedFolder /user:username pass  
![Mapping In Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/mapping-in-command-prompt.jpg)
4. Once you've made the required changes, hit**Enter** to execute the command.

 That's it. It'll take a few seconds, and then you can access the mapped drive from File Explorer with one click.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532">
  <img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Disconnect a Mapped Network Drive

 Disconnecting the network drive is a no-brainer if you no longer need access to the files on it.

 Here's how you can disconnect a mapped network drive in a few steps:

1. Press**Win + E** to open File Explorer.
2. Right-click on**Network** in the left pane and choose**Disconnect network drive** from the context menu.  
![Disconnect Mapped Drive In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disconnect-mapped-drive.jpg)
3. In the next window, choose the drive letter or name of the network drive you want to disconnect. Click**OK** to disconnect it from your system.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134237/18498" target="_top" id="2134237">
  <img src="//a.impactradius-go.com/display-ad/18498-2134237" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134237/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The mapped network drive will now disappear from File Explorer, and you can no longer access it from the drive letter you created earlier.

## Map Network Drives Easily in Windows 11

 Mapping a network drive in Windows 11 is a great way to access shared folders on other computers or servers. This can save you time and make managing and organizing your files easier.

 While mapping is only useful in the case of network drives, there are many other methods to share files without a network setup. For example, you can use external storage, cloud storage services, a data transfer cable, etc.

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-precision-recording-tips-for-gamers-and-videographers/"><u>[New] In 2024, Precision Recording Tips for Gamers and Videographers</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-transform-photos-with-the-premier-11-edits-for-2024/"><u>[New] Transform Photos with the Premier 11 Edits for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-instantly-professional-masterful-thumbnails-created-fast/"><u>2024 Approved Instantly Professional Masterful Thumbnails Created Fast</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/dive-into-high-quality-audio-7-royalty-free-selections-for-2024/"><u>Dive Into High-Quality Audio 7 Royalty-Free Selections for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-life360-notify-when-you-log-out-on-lava-yuva-3-drfone-by-drfone-virtual-android/"><u>Does Life360 Notify When You Log Out On Lava Yuva 3? | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/enigmas-of-death-decoded-by-artificial-intelligence/"><u>Enigmas of Death Decoded by Artificial Intelligence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-side-by-side-fault-in-windows/"><u>Eradicating Side-by-Side Fault in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-techniques-for-calls-tracking/"><u>Essential Windows Techniques for Calls Tracking</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-google-frp-lock-on-oppo-find-x6-pro-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock on Oppo Find X6 Pro Devices</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-12-prominent-xiaomi-civi-3-fingerprint-not-working-solutions-by-drfone-android/"><u>In 2024, Top 12 Prominent Xiaomi Civi 3 Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-xp-error-code-0xfffffddd/"><u>Overcoming Window's XP Error Code 0xFFFFFDDD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recommendations-for-setting-a-preferred-cli-window/"><u>Recommendations for Setting a Preferred CLI Window</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-enabling-and-using-hyper-v-on-w11-homes/"><u>Step-by-Step Guide to Enabling and Using Hyper-V on W11 Homes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-win11-mouse-access-for-comfort/"><u>Tailoring Win11 Mouse Access for Comfort</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbocharge-office-performance-on-windows-with-key-shortcuts/"><u>Turbocharge Office Performance on Windows With Key Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-fixes-for-unreachable-geforce-x-configuration-errors/"><u>Uncovering Fixes for Unreachable GeForce X Configuration Errors</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-in-2024-burstsplit-pro-speedy-methods-for-efficient-mp3-file-partitioning/"><u>Updated In 2024, BurstSplit Pro Speedy Methods for Efficient MP3 File Partitioning</u></a></li>
</ul></div>

