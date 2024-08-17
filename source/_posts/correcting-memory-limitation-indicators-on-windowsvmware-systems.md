---
title: Correcting Memory Limitation Indicators on Windows/VMware Systems
date: 2024-08-16T01:38:20.569Z
updated: 2024-08-17T01:38:20.569Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Memory Limitation Indicators on Windows/VMware Systems
excerpt: This Article Describes Correcting Memory Limitation Indicators on Windows/VMware Systems
keywords: Fix Memory Errors Win,RAM Fix in VMware,Overcoming Mem Limits WS,Windows Memory Faults,VMWare Memory Optimization,Enhance Windows RAM,Correcting Mem Indicator
thumbnail: https://thmb.techidaily.com/6af91e940bb187fedb6046d135c289160c909fca83f80b9023766807a5bb6dc8.png
---

## Correcting Memory Limitation Indicators on Windows/VMware Systems

 VMware Workstation is one of the best virtualization software packages for Windows. However, some users see an error message when they try to start virtual machines in VMware Workstation. That error message says, “not enough physical memory is available to power on this virtual machine,” and virtual machines won’t start up.

 This VMware issue can arise when there’s more than enough RAM available on a PC. However, there are numerous possible causes for the “not enough physical memory” error. This is how you can fix the “not enough physical memory” WMware error in Windows 10 and 11.

## 1\. Configure VMware to Run as an Administrator

 Not running VMware as an administrator places restrictions on its system permissions and access to resources. So, run the software with elevated rights to ensure a lack of permissions isn’t causing any issues.

 You can check out [how to run any program as an administrator on Windows](https://www.makeuseof.com/tag/ways-to-run-a-program-as-administrator-in-windows/) for more help, or you can set VMware to always run as an administrator like this:

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
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Click**File** on Notepad’s menubar.
7. Select the menu’s**Save** option.  
![The Save option in Notepad](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-save-option-in-notepad.jpg)
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Expand the Virtual Memory for the Virtual Machine

 The “not enough physical memory” error can occur because not enough virtual memory has been allocated to the virtual machine. You can expand a virtual machine’s memory allocation in VMWare like this:

1. Open your VMware software.
2. Right-click the virtual machine for which you need to fix the error and select**Settings** .
3. Increase the virtual machine’s memory allocation with the bar slider. That amount should always be higher than your PC’s available RAM.  
![The memory bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-memory-bar.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Click**OK** to apply.

## 4\. Update VMware

 The “not enough physical memory” error will more likely arise on outdated WMware versions. So, ensure you’re utilizing the latest version of the software. This is how you can update VMware:

1. Bring up the VMware window.
2. Click the**Help** menu.
3. Select**Software Updates** to view that window.  
![The Software Updates option in VMware](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-software-updates-option.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
4. Then click the**Check for Updates** button.  
![The Check for updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-check-for-updates-option4.jpg)
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Press the**Get More Information** button for an available update.

1. Log into an account profile on the website that opens.
2. Select the**Download Now** option on the website for the latest VMware Workstation version.
3. Then you’ll need to select an**Accept** option for the EULA agreement.
4. Click another**Download Now** option.
5. Then click File Explorer’s taskbar shortcut.
6. Go to the downloads folder that includes the WMware setup wizard.
7. Double-click the downloaded VMware installer to open it. Go through the setup wizard to install the latest VMware version.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## 5\. Delete a Recent Windows Update

 The “not enough physical memory” error can be caused by a Windows update that conflicts with VMware. So, uninstalling a recent update could fix that issue for some users. Check out our guide about [uninstalling Windows updates](https://www.makeuseof.com/windows-11-uninstall-updates/) for further details on how to apply this potential solution.

![The Installed Updates Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-uninstall-update-option.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Perform a Clean Boot

 Performing a clean boot will disable non-essential apps and services from the Windows startup. Clean booting can potentially resolve the “not enough physical memory” in two ways. Applying this troubleshooting method will ensure there aren’t any third-party programs conflicting with VMware and free up RAM for the software.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-services-tab-in-msconfig.jpg)

 To disable all third-party startup programs and services, check out the guidelines in our guide on [how to clean boot in Windows](https://www.makeuseof.com/clean-boot-windows-11/) . This will perform a clean boot whenever you restart Windows.

 Try utilizing your VMware virtual machine after clean booting. If this works,

## 7\. Set Up a New Virtual Machine

 If the issue persists despite applying the resolutions above, consider setting up a new virtual machine to replace the one that needs fixing. Download the latest ISO for the virtual machine’s platform. Then you can set up the virtual machine again, as outlined on the [VMware support page](https://kb.vmware.com/s/article/1018415) .

## Jump Into Your WMware Virtual Machine Again

 Those Windows fixes for the “Not enough physical memory” error have worked for many VMware Workstation users. So, there’s a decent enough chance one will kick-start your VMWare virtual machine too. However, users who still need more possible fixes for this issue can submit a support request via the [VMware Customer Connect](https://customerconnect.vmware.com/home?bmctx=89E60DF848C641FD518EB9F6B9A6E5334F602FA3A762B409625CD531863AC847&password=secure%5Fstring&contextType=external&username=string&challenge%5Furl=https:%2F%2Fcustomerconnect.vmware.com%2Fhome&request%5Fid=-8453692679675997712&authn%5Ftry%5Fcount=0&locale=en%5FGB&resource%5Furl=https%253A%252F%252Fcustomerconnect.vmware.com%252Fweb%252Fvmware%252Fchecksession) page.

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
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-how-to-screenshot-or-record-of-whats-showing-on-your-mac/"><u>[New] 2024 Approved  How to Screenshot or Record of What's Showing On Your Mac</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-viral-video-ventures-crafting-addictive-loops-on-ig/"><u>[New] 2024 Approved  Viral Video Ventures  Crafting Addictive Loops on IG</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-sketched-snicker-fits-kapwing-meme-artisan/"><u>[New] In 2024, Sketched Snicker-Fits  Kapwing Meme Artisan</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-tagging-towards-triumph-the-best-instagram-hashtags/"><u>[New] In 2024, Tagging Towards Triumph  The Best Instagram Hashtags</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-the-roadmap-for-success-mastering-the-art-of-fb-reel-production/"><u>[New] The Roadmap for Success  Mastering the Art of FB Reel Production</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/he-ultimate-guide-to-monetizing-youtube-content-2024-edition/"><u>[New] The Ultimate Guide to Monetizing YouTube Content - 2024 Edition</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-zero-price-windows-desktop-snapping-tutorials/"><u>[Updated] Zero Price  Windows Desktop Snapping Tutorials</u></a></li>
<li><a href="https://ai-video.techidaily.com/2024-approved-how-to-translate-videos-in-tamil-for-a-wider-reach/"><u>2024 Approved How To Translate Videos in Tamil for a Wider Reach</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/assessing-social-media-preference-the-case-for-tiktok-or-youtubes-shorts/"><u>Assessing Social Media Preference  The Case for TikTok or YouTubes' Shorts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-classroom-vibes-to-windows-11/"><u>Bringing Classroom Vibes to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-file-limit-on-windows-oses/"><u>Bypassing File Limit on Windows OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-protection-features-in-windows-11-with-rufus-expertise/"><u>Bypassing Protection Features in Windows 11 with Rufus Expertise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-restrictions-in-steam-libraries-windows-11-guide/"><u>Bypassing Restrictions in Steam Libraries: Windows 11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-unlaunched-lunar-client-issue-in-windows-environment/"><u>Bypassing Unlaunched Lunar Client Issue in Windows Environment</u></a></li>
<li><a href="https://fox-glue.techidaily.com/captivating-hdr-portraits-for-the-art-enthusiast-for-2024/"><u>Captivating HDR Portraits for the Art Enthusiast for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/choosing-between-windows-11-home-and-pro-your-ideal-edition/"><u>Choosing Between Windows 11 Home & Pro: Your Ideal Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-a-distinctive-look-with-customized-windows-11-monitor-walls/"><u>Creating a Distinctive Look with Customized Windows 11 Monitor Walls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-and-correcting-windows-11s-zoom-error-1132/"><u>Decoding and Correcting Windows 11'S Zoom Error #1132</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-amd-card-drivers-in-windows-11-an-overview/"><u>Effortless AMD Card Drivers in Windows 11: An Overview</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-windows-error-0xc0000001-quick-fixes/"><u>Eliminating Windows Error 0xC0000001: Quick Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-user-interface-showing-system-resources-on-taskbar/"><u>Enhancing User Interface: Showing System Resources on Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-transforming-word-docs-into-pdf-on-win-11/"><u>Essential Guide: Transforming Word Docs Into PDF on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-for-fixing-pubg-saving-issues-win/"><u>Expert Tips for Fixing PUBG Saving Issues (Win)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-intellij-unison-crashes-in-windows-11/"><u>Fixing IntelliJ Unison Crashes in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-bring-back-photo-viewer-features-on-win11/"><u>Guide to Bring Back Photo Viewer Features on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fine-tune-account-lockout-counter-after-failed-logins-on-windows-11-os/"><u>How to Fine-Tune Account Lockout Counter After Failed Logins on Windows 11 OS</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-motorola-edge-40-pro-phone-forgot-password-by-drfone-android-unlock-android-unlock/"><u>How to Unlock Motorola Edge 40 Pro Phone Forgot Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lowest-black-friday-keys-fan-discount-on-windows-11-free-forever/"><u>Lowest Black Friday Keys Fan Discount on Windows 11, Free Forever</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maintaining-app-order-within-windows-taskbar/"><u>Maintaining App Order Within Windows Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-powershell-a-key-for-administrators/"><u>Mastering PowerShell: A Key for Administrators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-of-windows-explorer-filters-as-an-alternative-to-ls/"><u>Mastery of Windows Explorer Filters as an Alternative to LS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-missing-file-detection-problems-on-win-11/"><u>Mitigating Missing File Detection Problems on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-past-error-x80072f30-in-windows-store/"><u>Navigate Past Error X80072F30 in Windows Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-the-tech-landscape-windows-11-installation-on-macos-through-parallels/"><u>Navigate the Tech Landscape: Windows 11 Installation on MacOS Through Parallels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-no-hypervisor-detection-in-windows-sandbox-environment/"><u>Overcoming No Hypervisor Detection in Windows Sandbox Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-windows-1011-auditory-conundrum/"><u>Overcoming the Windows 10/11 Auditory Conundrum</u></a></li>
<li><a href="https://win11-tips.techidaily.com/procedures-for-enablingdisabling-windows-component/"><u>Procedures for Enabling/Disabling Windows Component</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-adjusting-your-fax-covers-on-w11/"><u>Step-by-Step Guide: Adjusting Your Fax Covers on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-tackle-failed-system-call-on-windows-systems/"><u>Steps to Tackle Failed System Call on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-to-customized-pdf-program-on-pc/"><u>Switching to Customized PDF Program on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-dxgierrordeviceremoved-challenge/"><u>Tackling the DXGI_ERROR_DEVICE_REMOVED Challenge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-redefining-spacing-between-desktop-widgets-in-windows-1011/"><u>Title: Redefining Spacing Between Desktop Widgets in Windows 10/11</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-techniques-for-the-elusive-mfc42dll-file-not-found-problem/"><u>Troubleshooting Techniques for the Elusive MFC42.DLL File Not Found Problem</u></a></li>
<li><a href="https://techidaily.com/undeleted-lost-videos-from-vivo-s18-pro-by-fonelab-android-recover-video/"><u>Undeleted lost videos from Vivo S18 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-power-of-repair-for-compromised-system-files/"><u>Unlocking the Power of Repair for Compromised System Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-hidden-how-to-find-missing-wi-fi-networks-in-windows-11/"><u>Unveiling the Hidden: How to Find Missing Wi-Fi Networks in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-mastery-easy-to-follow-guide-to-building-bootable-usbs/"><u>Win 11 Mastery: Easy-to-Follow Guide to Building Bootable USBs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-makeover-implementing-animated-backgrounds-on-pc/"><u>Windows 11 Makeover: Implementing Animated Backgrounds on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-memory-mapping-uncovering-ram-types-easily/"><u>Windows Memory Mapping: Uncovering RAM Types Easily</u></a></li>
</ul></div>
