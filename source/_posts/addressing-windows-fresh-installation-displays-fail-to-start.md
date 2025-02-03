---
title: "Addressing Windows' Fresh Installation: Displays Fail To Start"
date: 2025-01-29T07:30:13.782Z
updated: 2025-01-31T21:12:32.393Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Addressing Windows' Fresh Installation: Displays Fail To Start"
excerpt: "This Article Describes Addressing Windows' Fresh Installation: Displays Fail To Start"
keywords: Windows Install Troubleshooting,New PC Boot Issue,Display Not Starting Post-Install,Fix Windows Start Screen,Fresh OS Setup Problems,Boot Failure Windows Device,Resolve Laptop Screens Blank
thumbnail: https://thmb.techidaily.com/6152b7c969d91f2eaae0be3b9bf8b8ec86f6a4683a1dd9c2aefb366c737706ad.jpg
---

## Addressing Windows' Fresh Installation: Displays Fail To Start

 The “display driver failed to start” error message usually appears when you try to launch a game on Windows. The error message appears in the form of a Windows notification above the system tray area. When this error occurs, it causes your screen to go completely black. Sometimes it will recover, but sometimes it will require a hard reset.

 When this error is at its worst, it can prevent you from playing your favorite games. As such, here is how you can fix the “display driver failed to start” error on a Windows 10 or 11 PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kx-Pb0otJCs?si=Mvr49yQVesmJA8-O" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Perform Some Display Driver-Related Fixes

 The error message points to your display driver as the main culprit. As such, before you try anything else, you can try these display driver-related fixes to see if they do the job.

### Roll Back the Latest Graphics Driver Update

![The Roll Back Driver option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/roll-back-driver-button.jpg)

 If your graphics card’s driver has recently been updated, try rolling back to the old GPU driver. A **Roll Back Driver** option is usually only available for a short time (typically a few days) after updating a driver. Check out our guide to [rolling back drivers in Windows](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) for further details about how to apply this potential resolution.

### Install the Latest Driver for Your PC’s Graphics Card

 People plagued with this error message have confirmed that updating your graphics drivers is a good solution for the “display driver failed to start” error. And while Windows usually handles driver updates through Windows Update, it sometimes won't update NVIDIA and AMD GPU drivers.

 You can update your graphics card’s driver yourself with the methods discussed in our guide to [updating GPU drivers on Windows](http://www.makeuseof.com/update-graphics-drivers-in-windows-10/).

### Reinstall Your Graphics Driver

 If your PC’s GPU already has the newest graphics driver available, consider reinstalling the graphics driver. It's best to do a clean install to ensure your GPU's driver is back to its factory defaults.

 Check out [how to cleanly install and reinstall GPU drivers on Windows](https://www.makeuseof.com/how-to-cleanly-install-and-reinstall-gpu-drivers-on-windows/) for more information.

## 2\. Utilize the Hardware and Devices Troubleshooter

 Windows has a Hardware and Devices troubleshooter that can help resolve the “display driver failed to start” error. This troubleshooting tool is no longer available within Settings or Control Panel, but it is still accessible via Command Prompt.

 You can access and run the Hardware and Devices troubleshooting utility like this:

1. First, locate the Command Prompt by pressing **Win + S**, typing "cmd," and clicking on **Command Prompt**.
2. Enter and execute the Hardware and Devices command:  
`msdt.exe -id DeviceDiagnostic`
3. Click **Next** to start the troubleshooting.  
![The Hardware and Devices troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/hardware-and-devices-troubleshooter-troubleshooter-2.jpg)
4. Select **Apply this fix** to rectify any issues Windows finds.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Lower the Windows Visual Effect Settings

 Windows has various visual effect settings that can affect performance. Having too many visual effects enabled can potentially cause issues on PCs with more limited GPUs.

 So, it’s recommended to select the "adjust for best performance" mode in the visual effect settings like this:

1. Right-click **Start**, select **Search**, and input "advanced system settings" in the text box.
2. Press the **Settings** button in the **Performance** category.  
![The Advanced tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/advanced-tab-2.jpg)
3. Click the **Adjust for best performance** radio button, which will deselect most if not all of the effect checkboxes.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jpdGEJJwMLY?si=eKgXOPpNeYvYKcel" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![The "adjust for best performance" button selected](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adjust-for-best-performance-radio-button.jpg)
4. Select **Apply** to set the new performance settings.
5. Click the Performance Options window’s **OK** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eMEJvwMM0vk?si=EQF_jo_4u9v5iJ_C" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Edit the GraphicsDrivers Registry Key

 Some users have got the “display driver failed to start” error fixed by editing the GraphicsDriver registry key. This tweaking involves adding a new **TdrDelay** DWORD value to that key for extending Timeout Detection Delay.

 You can edit the GraphicsDriver registry key like this:

1. Open the Run dialog with **Win + R** and enter "regedit".
2. Click **OK** or press **Enter** to open the Registry Editor window.
3. Then enter this GraphicsDrivers key location inside the registry address bar:  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\GraphicsDrivers`
4. Right-click **GraphicsDrivers** and select the **New** context menu option.
5. Select **DWORD (32-bit) Value** to add a new entry.  
![The New > DWORD options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dword-32-bit-value-2.jpg)
6. Type **TdrDelay** within the new DWORD’s text box.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0OxkndZbIA4?si=TWJlkTbYKsVag8-q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Double-click the **TdrDelay** DWORD.
8. Input a value of **5** in the data box and select **OK**.  
![The Value data box the TdrDelay](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/value-data-box-2.jpg)
9. Now close the Registry Editor and reboot your PC.

## 5\. Roll Back Windows to a Previous Restore Point

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-restore-window.jpg)

 If you have System Restore enabled, restoring Windows to an earlier date is worth a try if nothing else has worked so far. Rolling back Windows will undo every system change made after a selected date.

 As such, you can use System Restore to put your PC "back in time" to a moment when the error didn't occur. It does mean you may lose some apps or data, so be sure to back up anything you want to keep.

 Our guide to [utilizing System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) provides step-by-step instructions for how to roll back Windows 10 and 11\. Select a restore point date created before you needed to fix the “display driver failed to start” error.

 If this fixes the problem, be careful when re-installing the apps and drivers that got wiped during the restore. If you do, keep tabs on what you reinstalled and when. If the "display driver failed to start" error resurfaces, uninstall everything you recently reinstalled.

## 6\. Perform a Windows Factory Reset

 If System Restore is not an option or it doesn't resolve the issue, you can try a factory reset as the last resort. Performing a factory reset will likely fix the “display driver failed to start” error. However, factory resetting a PC deletes all the apps that weren't pre-installed with Windows. So, be prepared to reinstall all third-party apps you installed yourself.

![The Keep my Files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/keep-my-files-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can apply a factory reset with the Reset this PC utility. That tool includes a **Keep my files** option you can select to keep files in your user folders (Documents, Pictures, Videos, etc). Our guide for [factory resetting Windows 10 and 11](http://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer) provides details on how to access and utilize that tool.

## Enjoy Your Windows Gaming Again

 Applying those potential solutions will almost certainly be enough to fix the “display driver failed to start” error in most cases. However, you may need to try applying more than one of them to find one that works on your PC. Then you can get back to playing all your favorite Windows games again without further issues.

 When this error is at its worst, it can prevent you from playing your favorite games. As such, here is how you can fix the “display driver failed to start” error on a Windows 10 or 11 PC.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-lab.techidaily.com/n-2024-nailing-your-online-visibility-with-optimal-youtube-thumbnail-dimensions/"><u>[New] In 2024, Nailing Your Online Visibility with Optimal YouTube Thumbnail Dimensions</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-gaining-exposure-cost-effective-promotion-hacks-for-youtubers/"><u>[Updated] 2024 Approved Gaining Exposure Cost-Effective Promotion Hacks for YouTubers</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-expert-filmmaking-skills-on-youtube-and-diverse-platforms-for-2024/"><u>[Updated] Expert Filmmaking Skills on YouTube and Diverse Platforms for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-unveiling-the-hidden-mastering-the-mask-of-background-blur/"><u>[Updated] Unveiling the Hidden Mastering the Mask of Background Blur</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-ultimate-blueprint-for-mastering-picsart/"><u>2024 Approved The Ultimate Blueprint for Mastering PicsArt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combatting-unstable-pointer-in-windows-environments/"><u>Combatting Unstable Pointer in Windows Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/defeating-xbox-game-pass-error-0-a-comprehensive-guide-for-windows-11-users/"><u>Defeating Xbox Game Pass Error 0: A Comprehensive Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-strategies-to-delete-wi-fi-on-win-11/"><u>Five Strategies to Delete Wi-Fi on Win 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-examining-video-sharing-platforms-the-vimeo-and-youtube-divide/"><u>In 2024, Examining Video Sharing Platforms The Vimeo & YouTube Divide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-access-essential-windows-keyboard-tricks-for-efficiency/"><u>Quick Access: Essential Windows Keyboard Tricks for Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-minimum-spec-requirements-conflicts-with-intel-graphics-errors/"><u>Resolving Minimum Spec Requirements Conflicts with Intel Graphics Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/savvy-shoppers-secret-buy-now-for-612-life-win10/"><u>Savvy Shoppers' Secret: Buy Now for $6.12 Life Win10</u></a></li>
<li><a href="https://driver-error.techidaily.com/streamlined-connectivity-for-asus-usb-webcam-with-win10-update/"><u>Streamlined Connectivity for ASUS USB Webcam with Win10 Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-zero-x-eight-oh-three-one-f-error-in-email-app/"><u>Tackling Windows' Zero X Eight Oh Three One F Error in Email App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-significance-and-risks-of-deleting-pagefilesys/"><u>The Significance and Risks of Deleting Pagefile.sys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unallocated-drive-letters-in-windows-explained-and-how-to-fix-it/"><u>Unallocated Drive Letters in Windows Explained & How to Fix It</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-transform-your-video-footage-shape-size-and-more/"><u>Updated In 2024, Transform Your Video Footage Shape, Size, and More</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/what-to-expect-from-apples-newest-launch-the-macbook-pro-m3-release-info-cost-analysis-and-feature-guide/"><u>What to Expect From Apple's Newest Launch: The MacBook Pro (M3) - Release Info, Cost Analysis & Feature Guide</u></a></li>
<li><a href="https://discover-cheats.techidaily.com/wiederherstellung-fehlender-datentragerpartitions-in-windows-10-erklart/"><u>Wiederherstellung Fehlender Datenträgerpartitions in Windows 10 Erklärt</u></a></li>
</ul></div>

