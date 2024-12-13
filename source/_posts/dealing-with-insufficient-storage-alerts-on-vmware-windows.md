---
title: Dealing with Insufficient Storage Alerts on VMware Windows
date: 2024-12-10T19:41:51.982Z
updated: 2024-12-12T16:57:18.879Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Dealing with Insufficient Storage Alerts on VMware Windows
excerpt: This Article Describes Dealing with Insufficient Storage Alerts on VMware Windows
keywords: Storage Space Alert VMware,InsufStorage Warning Windows,Manage Low Disk VMWare,Handle Storage Error Windows,Limitless Storage Guide VMware,Addressing Storage Lack Windows,Optimizing VM Storage Alerts
thumbnail: https://thmb.techidaily.com/700293ffdf9a4730d9df7fa5093979f42d9fa58b0347dc31082bc6c29ca2c642.jpg
---

## Dealing with Insufficient Storage Alerts on VMware Windows

 VMware Workstation is one of the best virtualization software packages for Windows. However, some users see an error message when they try to start virtual machines in VMware Workstation. That error message says, “not enough physical memory is available to power on this virtual machine,” and virtual machines won’t start up.

 This VMware issue can arise when there’s more than enough RAM available on a PC. However, there are numerous possible causes for the “not enough physical memory” error. This is how you can fix the “not enough physical memory” WMware error in Windows 10 and 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QRaEdFMU-Xc?si=OjaiTvlogJy5wHhN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gyGoQi7hsZk?si=8OcKcPUj2wSBmVZ1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Then select**OK** to close WMware’s properties window.

## 2\. Edit the Config File

 Lots of users have been able to fix the “not enough physical memory” by editing VMWare’s**config.ini** file. Those users disabled a Host parameter within the software’s configuration file. To disable that Host parameter, open and edit VMware’s**config.ini** file as follows:

1. Press**Win + E** to access File Explorer.
2. Open this VMware directory in Explorer:  
`C:\ProgramData\VMware\VMware Workstation`
3. Right-click the**config.ini** file and select**Open with** .  
![The Open with option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-open-with-option.jpg)
4. Select**Notepad** to view the configuration file in that text editor.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/grbt-5VvbuI?si=qnoirlmljslpqcQj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Then **input vmmon.disableHostParameters = “TRUE”** at the bottom of the configuration file as in the image below.  
![WMware's config.ini file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-config-ini-file.jpg)
6. Click**File** on Notepad’s menubar.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qNrOsjUdRz0?si=xGzhmNmtgxNTsRxN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Select the menu’s**Save** option.  
![The Save option in Notepad](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-save-option-in-notepad.jpg)

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
![The Check for updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-check-for-updates-option4.jpg)
5. Press the**Get More Information** button for an available update.

1. Log into an account profile on the website that opens.
2. Select the**Download Now** option on the website for the latest VMware Workstation version.
3. Then you’ll need to select an**Accept** option for the EULA agreement.
4. Click another**Download Now** option.
5. Then click File Explorer’s taskbar shortcut.
6. Go to the downloads folder that includes the WMware setup wizard.
7. Double-click the downloaded VMware installer to open it. Go through the setup wizard to install the latest VMware version.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HSFNIAYChbA?si=4TIlsUrYmY5vP2il" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Delete a Recent Windows Update

 The “not enough physical memory” error can be caused by a Windows update that conflicts with VMware. So, uninstalling a recent update could fix that issue for some users. Check out our guide about[uninstalling Windows updates](https://www.makeuseof.com/windows-11-uninstall-updates/) for further details on how to apply this potential solution.

![The Installed Updates Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-uninstall-update-option.jpg)

## 6\. Perform a Clean Boot

 Performing a clean boot will disable non-essential apps and services from the Windows startup. Clean booting can potentially resolve the “not enough physical memory” in two ways. Applying this troubleshooting method will ensure there aren’t any third-party programs conflicting with VMware and free up RAM for the software.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-services-tab-in-msconfig.jpg)

 To disable all third-party startup programs and services, check out the guidelines in our guide on[how to clean boot in Windows](https://www.makeuseof.com/clean-boot-windows-11/) . This will perform a clean boot whenever you restart Windows.

 Try utilizing your VMware virtual machine after clean booting. If this works,

## 7\. Set Up a New Virtual Machine

 If the issue persists despite applying the resolutions above, consider setting up a new virtual machine to replace the one that needs fixing. Download the latest ISO for the virtual machine’s platform. Then you can set up the virtual machine again, as outlined on the[VMware support page](https://kb.vmware.com/s/article/1018415) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LdVT_-3gESA?si=_HfjpbUEHSRKTXjt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-files.techidaily.com/new-leveraging-hashtags-to-enhance-fb-user-engagement-for-2024/"><u>[New] Leveraging Hashtags to Enhance FB User Engagement for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-peak-creation-suite-insightful-2023-analysis/"><u>[New] Peak Creation Suite Insightful 2023 Analysis</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-conquering-common-challenges-easy-steps-for-your-ipad-capture-process-for-2024/"><u>[Updated] Conquering Common Challenges Easy Steps for Your iPad Capture Process for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-renowned-crafters-exquisite-instagram-hlv-designers-online-for-2024/"><u>[Updated] Renowned Crafters Exquisite Instagram HLV Designers Online for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/convertir-facilement-des-mp4-en-images-jpeg-en-ligne-votre-guide-ultime-pour-une-gestion-optimisee-de-la-video-et-de-limage-sans-frais/"><u>Convertir Facilement Des MP4 en Images JPEG en Ligne : Votre Guide Ultime Pour Une Gestion Optimisée De La Vidéo Et De L'image Sans Frais.</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/discover-the-leading-mp3-devices-comprehensive-review-by-zdnet/"><u>Discover the Leading MP3 Devices - Comprehensive Review by ZDNet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-faulty-tackling-corrupt-win1011-recycle-bin/"><u>Fixing the Faulty: Tackling Corrupt WIN10/11 Recycle Bin</u></a></li>
<li><a href="https://tech-haven.techidaily.com/get-ready-to-play-here-are-chatgpts-top-6-entertaining-gaming-selections/"><u>Get Ready to Play! Here Are ChatGPT's Top 6 Entertaining Gaming Selections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-fix-windows-sandboxs-no-hypervisor-error/"><u>Guide to Fix Windows Sandbox's No Hypervisor Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-get-rid-of-silence-in-google-meet-chat/"><u>How to Get Rid of Silence in Google Meet Chat</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-mitigate-playback-problems-in-android-and-ios-apps/"><u>In 2024, Mitigate Playback Problems in Android & iOS Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-a-failed-windows-discord-update-seamlessly/"><u>Navigating a Failed Windows Discord Update Seamlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-control-fixing-a-stalled-resource-monitor-on-windows-11/"><u>Regaining Control: Fixing a Stalled Resource Monitor on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-chromes-aw-snap-windows-alert/"><u>Resolving Chrome's Aw, Snap! Windows Alert</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-error-incorrect-file-history-configurations/"><u>Resolving Windows Error: Incorrect File History Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-connectivity-how-to-fix-network-errors-in-windows-11/"><u>Seamless Connectivity: How to Fix Network Errors in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-visual-studio-code-against-windows-11-glitches/"><u>Secure Visual Studio Code Against Windows 11 Glitches</u></a></li>
</ul></div>

