---
title: Correcting False Listings of Devices in Windows Error Logs
date: 2024-08-23T07:02:34.463Z
updated: 2024-08-24T07:02:34.463Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting False Listings of Devices in Windows Error Logs
excerpt: This Article Describes Correcting False Listings of Devices in Windows Error Logs
keywords: Device Log Correction Windows,Erroneous Device Logs,Fix Device Listing Windows,Correcting Error Logs,False Device Logs Windows,Untrue Devices in Error Log,Rectifying Windows Log Incorrectities
thumbnail: https://thmb.techidaily.com/b11cfa6cab7ceb94681fcab83e62d05efa3e76c07b0a1fd703161df853374929.jpg
---

## Correcting False Listings of Devices in Windows Error Logs

 Many users partition their hard drives or utilize external storage devices with their PCs. However, such drives become inaccessible when the “A device which does not exist was specified” error arises. Users have reported seeing this strange error message when they try to open connected external storage devices or drive partitions inside Windows File Explorer.

 That error is most unwelcome since it means users can’t open whatever drives it arises for. Consequently, they can’t access files on affected drives. This is how you can fix the “device which does not exist was specified” error in Windows 10 and 11.

## 1\. Plug the Affected Device Into a Different USB Slot

 If this error is affecting an external storage device, try reconnecting the USB drive. There might be an issue with the port you’ve connected the drive with. Plug the USB drive into a different port to see if the same error occurs.

 If you need to resolve this error for an internal drive, check the drive’s internal connections. To do that, you’ll need to open the case for a desktop PC. Then make sure none of the drive’s connection cables are in any way loose.

## 2\. Run the SFC Tool

 Users have confirmed the System File Checker tool can resolve this drive error. That highlights system file corruption can cause this issue, which an SFC scan will likely resolve. Our guide to[running a System File Checker scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to execute the SFC command in Windows.

![The sfc /scannow](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/sfc-scannow.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
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
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You’ll need to replace X in the above command with the actual letter of the affected drive you need to scan. For example, the command for a drive labeled D would be:

`chkdsk D: /f /r`

<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Try Changing the Drive’s Letter

 Changing the affected drive’s letter is a potential fix that users have confirmed to work. You can change the drive’s letter with the Disk Management tool like this:

1. If you need to fix this issue for an external drive, connect that storage device to your PC.
2. Open Disk Management by right-clicking**Start** and selecting the shortcut for that tool.
3. Right-click the affected drive and select**Change Drive Letter and Paths** .  
![The Change Drive Letter and Paths option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-drive-letter-paths.jpg)
4. Press the**Change** button.  
![The Change Drive Letter window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-drive-letter-window.jpg)
5. Click the drop-down menu for the**Assign the following drive lette** r option.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
![The Assign the following drive letter option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/assign-the-following-drive-letter.jpg)
6. Select a drive letter that you’ve never used.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
7. Click**OK** on the Change Drive Letter or Path window.
8. Select**Yes** on the Disk Management confirmation dialog.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
## 5\. Rescan a Drive

 Disk Management includes a**Rescan Disk** option for troubleshooting drives. That option detects disk changes and updates drive info accordingly when selected. So, rescanning the disk is a viable troubleshooting method for resolving this “device which does not exist” error. This is how you can rescan a drive:

1. Plug the drive into your PC if necessary.
2. Bring up the Disk Management tool.
3. Click the drive for which the error occurs in Disk Management.
4. Then click the**Action** menu.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/properties-option2.jpg)
5. Select**Rescan Disks** on the menu.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
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
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
## 7\. Reinstall the Affected Drive

 If you need to fix this issue for an external storage device, try reinstalling the affected drive. Doing so will reinstall the drivers for the affected storage device. This is how you can reinstall the drive:

Insert the affected drive into one of your PC’s USB ports.

1. Click**Start** with the right mouse button to select a**Device Manager** shortcut.
2. Double-click**Disk drives** in Device Manager.
3. Right-click your drive and select**Uninstall device** .  
![The Uninstall device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/uninstall-device2.jpg)
4. Then select the**Uninstall** option on the dialog box prompt.  
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/uninstall-option3.jpg)
5. Disconnect the drive plugged into the PC.
6. Plug the drive back into the computer to reinstall its driver.

## 8\. Update Your Motherboard’s Chipset Driver

 It might be necessary for some users to update motherboard drivers to fix this issue. To do so manually, you’ll need the motherboard model and manufacturer details. You can check those details as follows:

1. Open the Windows search box, and type a**System Information** keyword there.
2. Click**System Information** to view that app’s window.
3. Note down the**BaseBand Product** and**BaseBand Manufacturer** details.  
![Baseboard specs in System Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/baseboard-specs.jpg)
4. [Open the Command Prompt](https://www.makeuseof.com/windows-11-open-command-prompt/) if the System Information app doesn’t include a serial number for the motherboard.
5. Execute this baseboard command:  
`wmic baseboard get product,Manufacturer,version,serialnumber`  
![The baseboard command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/baseboard-command.jpg)
6. Copy and paste the serial number for the motherboard shown within the Command Prompt into Notepad or another text editor.

 Then open the download section of your motherboard manufacturer’s website. Select your motherboard model and download its latest chipset driver from there. You can install the new driver for your motherboard with the downloaded driver (setup.exe) package file.

 The driver package might be included within a ZIP archive, which you’ll need to extract as outlined within this guide to[unzipping files in Windows](https://www.makeuseof.com/unzip-files-windows-10/) .

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
<li><a href="https://youtube-web.techidaily.com/024-approved-elevating-slideshows-incorporate-youtube-videos/"><u>[New] 2024 Approved  Elevating Slideshows  Incorporate YouTube Videos</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-dynamic-duo-combining-multiple-photos-for-impactful-stories/"><u>[New] Dynamic Duo  Combining Multiple Photos for Impactful Stories</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-guided-pathway-for-large-file-exchange-in-apple-ecosystem/"><u>[Updated] Guided Pathway for Large File Exchange in Apple Ecosystem</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-movavi-pro-what-to-expect-from-the-newest-video-edition-2024/"><u>[Updated] Movavi Pro – What to Expect From the Newest Video Edition, 2024</u></a></li>
<li><a href="https://howto.techidaily.com/11-proven-solutions-to-fix-google-play-store-not-working-issue-on-xiaomi-mix-fold-3-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Proven Solutions to Fix Google Play Store Not Working Issue on Xiaomi Mix Fold 3 | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/brightening-up-post-fall-windows-experience/"><u>Brightening Up Post-Fall Windows Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-system-call-failure-in-win11/"><u>Eliminating System Call Failure in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensure-win11-stay-up-to-date-essential-uptime-checks/"><u>Ensure Win11 Stay Up-to-Date: Essential Uptime Checks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-and-solving-roblox-error-403-for-windows-devices/"><u>Exploring & Solving Roblox Error 403 for Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-server-crashes-in-media-software/"><u>Fixing Server Crashes in Media Software</u></a></li>
<li><a href="https://extra-information.techidaily.com/gigglegallery-craft-and-share-your-own-funny-faces/"><u>GiggleGallery  Craft and Share Your Own Funny Faces</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-keep-your-desktop-spotless-with-windows-self-clean-feature/"><u>How to Keep Your Desktop Spotless with Windows Self-Clean Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reinstate-absence-of-key-dll-mfc71u-in-os/"><u>How to Reinstate: Absence of Key DLL – Mfc71u in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-swiftly-force-remove-a-print-spooler-from-pc/"><u>How to Swiftly Force Remove a Print Spooler From PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-causes-behind-missing-regedit-application/"><u>Identifying Causes Behind Missing Regedit Application</u></a></li>
<li><a href="https://win11-tips.techidaily.com/illuminate-interruption-5-solutions-to-bring-back-keyboard-glow/"><u>Illuminate Interruption: 5 Solutions to Bring Back Keyboard Glow</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-facts-you-need-to-know-about-screen-mirroring-vivo-y100-drfone-by-drfone-android/"><u>In 2024, 3 Facts You Need to Know about Screen Mirroring Vivo Y100 | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-xiaomi-civi-3-disney-100th-anniversary-edition-drfone-by-drfone-virtual/"><u>In 2024, 9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Xiaomi Civi 3 Disney 100th Anniversary Edition | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-spy-on-text-messages-from-computer-and-oneplus-ace-3-drfone-by-drfone-virtual-android/"><u>In 2024, How to Spy on Text Messages from Computer & OnePlus Ace 3 | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-streamlining-audio-exploration-how-to-add-apple-podcasts-to-your-device/"><u>In 2024, Streamlining Audio Exploration  How to Add Apple Podcasts to Your Device</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-the-ultimate-guide-to-xiaomi-civi-3-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Ultimate Guide to Xiaomi Civi 3 Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jump-over-jerks-top-techniques-to-address-win-11s-typing-latency/"><u>Jump Over Jerks: Top Techniques to Address Win 11'S Typing Latency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-absent-items-from-file-explorer-list/"><u>Mending Absent Items From File Explorer List</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-error-0x80070570s-maze-of-corruption/"><u>Navigating Through Windows Error 0X80070570's Maze of Corruption</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-widows-handbrake-freeze-woes/"><u>Overcome Widows' HandBrake Freeze Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-opengl-error-code-3-with-nvidia/"><u>Overcoming OpenGL Error Code 3 with NVIDIA</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-find-functionality-a-step-by-step-guide-for-win11-users/"><u>Quick Find Functionality – A Step-by-Step Guide for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-your-digital-label-changing-username-in-windows-11/"><u>Revolutionize Your Digital Label: Changing UserName in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-windows-partition-union-explained/"><u>Seamless Windows Partition Union Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-file-distribution-the-ultimate-sefx-guide-for-win11/"><u>Streamlining File Distribution: The Ultimate SEFx Guide for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-tutorial-review-and-purge-windows-activity-records/"><u>Tech Tutorial: Review & Purge Windows Activity Records</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-controlling-content-filter-on-windows-11/"><u>Tips for Controlling Content Filter on Windows 11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/top-cover-photo-creators-facebook-edition-top-11-list-for-2024/"><u>Top Cover Photo Creators  Facebook Edition - Top 11 List for 2024</u></a></li>
</ul></div>
