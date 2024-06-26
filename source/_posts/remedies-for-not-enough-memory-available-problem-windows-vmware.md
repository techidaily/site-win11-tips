---
title: Remedies for 'Not Enough Memory Available' Problem (Windows VmWare)
date: 2024-06-25T16:41:19.584Z
updated: 2024-06-26T16:41:19.584Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remedies for 'Not Enough Memory Available' Problem (Windows VmWare)
excerpt: This Article Describes Remedies for 'Not Enough Memory Available' Problem (Windows VmWare)
keywords: Windows VM Memory Issue,Remedy Low Mem Error,Fix Vmware RAM Shortage,Overcome Not Enough Memory,Solve VmWare Memory Problem,Increase VM Memory Usage,Optimize Windows Virtual Memory
thumbnail: https://thmb.techidaily.com/00f9a98dfa9706757d2d82934bc9dc5159ac52a4f0751dc6a02d7459f2560fde.jpg
---

## Remedies for 'Not Enough Memory Available' Problem (Windows VmWare)

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
6. Click**File** on Notepad’s menubar.
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

## 5\. Delete a Recent Windows Update

 The “not enough physical memory” error can be caused by a Windows update that conflicts with VMware. So, uninstalling a recent update could fix that issue for some users. Check out our guide about [uninstalling Windows updates](https://www.makeuseof.com/windows-11-uninstall-updates/) for further details on how to apply this potential solution.

![The Installed Updates Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-uninstall-update-option.jpg)

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
<li><a href="https://win11-tips.techidaily.com/fixing-csgo-start-problems-on-w11/"><u>Fixing CS:GO Start Problems on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stay-connected-disable-usb-sleep-on-windows-11-pc/"><u>Stay Connected: Disable USB Sleep on Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-windows-storage-the-top-free-volume-boosters-list/"><u>Enhance Your Windows Storage: The Top Free Volume Boosters List</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-responsive-spotify-app-on-windows-11-pcs/"><u>Fixing Non-Responsive Spotify App on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-1011-photography-setup/"><u>Streamlining Windows 10/11 Photography Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-failed-remotes-a-step-by-step-guide-for-windows-users/"><u>Resetting Failed Remotes: A Step-By Step Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-error-code-31-in-windows-os/"><u>Mastering the Art of Fixing Error Code 31 in Windows OS</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-minicam-record-evaluation-and-backup-software/"><u>[New] 2024 Approved  MiniCam Record Evaluation & Backup Software</u></a></li>
<li><a href="https://howto.techidaily.com/top-10-fixes-for-phone-keep-disconnecting-from-wi-fi-on-oppo-a56s-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 10 Fixes for Phone Keep Disconnecting from Wi-Fi On Oppo A56s 5G | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/eyeview-scrutiny-exploration/"><u>Eyeview Scrutiny Exploration</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-boosting-youtube-productions-best-mac-mp4-editors-guide/"><u>[Updated] Boosting YouTube Productions  Best Mac MP4 Editors Guide</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-beats-and-bars-mastering-video-sounds-on-instagram/"><u>[New] In 2024, Beats & Bars  Mastering Video Sounds on Instagram</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-on-honor-x7b-by-drfone-android/"><u>How to Bypass FRP on Honor X7b?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-5-ways-to-track-nokia-xr21-without-app-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Ways to Track Nokia XR21 without App | Dr.fone</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-transitioning-photos-from-physical-to-digital-storage/"><u>2024 Approved  Transitioning Photos  From Physical to Digital Storage</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-apps-and-online-tools-to-track-nokia-g22-phone-withwithout-imei-number-by-drfone-android/"><u>In 2024, Top Apps and Online Tools To Track Nokia G22 Phone With/Without IMEI Number</u></a></li>
</ul></div>
