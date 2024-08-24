---
title: Fixing 'Limited Memory' Notifications on Virtual Machines
date: 2024-08-23T07:03:39.778Z
updated: 2024-08-24T07:03:39.778Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing 'Limited Memory' Notifications on Virtual Machines
excerpt: This Article Describes Fixing 'Limited Memory' Notifications on Virtual Machines
keywords: VM Memory Shortage Fix,Solve Limited Memory Errors,Clear VM Memory Limits,Remedy RAM Issues in VMs,Virtual Machine Mem Problems,Address Low VM Memory Notifications,Resolve VM Storage Constraints
thumbnail: https://thmb.techidaily.com/ed43cb68b7509790195a4106080566d9794dc5d45025fc9ee05e6abe84591529.jpg
---

## Fixing 'Limited Memory' Notifications on Virtual Machines

 VMware Workstation is one of the best virtualization software packages for Windows. However, some users see an error message when they try to start virtual machines in VMware Workstation. That error message says, “not enough physical memory is available to power on this virtual machine,” and virtual machines won’t start up.

 This VMware issue can arise when there’s more than enough RAM available on a PC. However, there are numerous possible causes for the “not enough physical memory” error. This is how you can fix the “not enough physical memory” WMware error in Windows 10 and 11.

## 1\. Configure VMware to Run as an Administrator

 Not running VMware as an administrator places restrictions on its system permissions and access to resources. So, run the software with elevated rights to ensure a lack of permissions isn’t causing any issues.

 You can check out[how to run any program as an administrator on Windows](https://www.makeuseof.com/tag/ways-to-run-a-program-as-administrator-in-windows/) for more help, or you can set VMware to always run as an administrator like this:

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
## 4\. Update VMware

 The “not enough physical memory” error will more likely arise on outdated WMware versions. So, ensure you’re utilizing the latest version of the software. This is how you can update VMware:

1. Bring up the VMware window.
2. Click the**Help** menu.
3. Select**Software Updates** to view that window.  
![The Software Updates option in VMware](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-software-updates-option.jpg)
4. Then click the**Check for Updates** button.  
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 5\. Delete a Recent Windows Update

 The “not enough physical memory” error can be caused by a Windows update that conflicts with VMware. So, uninstalling a recent update could fix that issue for some users. Check out our guide about[uninstalling Windows updates](https://www.makeuseof.com/windows-11-uninstall-updates/) for further details on how to apply this potential solution.

![The Installed Updates Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-uninstall-update-option.jpg)

## 6\. Perform a Clean Boot

 Performing a clean boot will disable non-essential apps and services from the Windows startup. Clean booting can potentially resolve the “not enough physical memory” in two ways. Applying this troubleshooting method will ensure there aren’t any third-party programs conflicting with VMware and free up RAM for the software.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-services-tab-in-msconfig.jpg)

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To disable all third-party startup programs and services, check out the guidelines in our guide on[how to clean boot in Windows](https://www.makeuseof.com/clean-boot-windows-11/) . This will perform a clean boot whenever you restart Windows.

 Try utilizing your VMware virtual machine after clean booting. If this works,

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Set Up a New Virtual Machine

 If the issue persists despite applying the resolutions above, consider setting up a new virtual machine to replace the one that needs fixing. Download the latest ISO for the virtual machine’s platform. Then you can set up the virtual machine again, as outlined on the[VMware support page](https://kb.vmware.com/s/article/1018415) .

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-zero.techidaily.com/024-approved-how-to-embed-a-youtube-playlist-on-a-website/"><u>[New] 2024 Approved  How to Embed A YouTube Playlist On a Website</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-capturing-the-moment-leading-tools-to-record-webinars-and-more/"><u>[New] Capturing the Moment - Leading Tools to Record Webinars & More</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-elevate-your-video-watchlist-activate-av1-on-youtube-for-2024/"><u>[New] Elevate Your Video Watchlist - Activate AV1 on YouTube for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-top-picks-for-free-virtual-conferencing-and-screensharing-software/"><u>[New] In 2024, Top Picks for FREE Virtual Conferencing & Screensharing Software</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-navigating-the-world-of-photo-reshaping/"><u>[New] Navigating the World of Photo Reshaping</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-elite-catch-footage-cameras-top-5-list/"><u>[Updated] 2024 Approved  Elite Catch Footage Cameras - Top 5 List</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-enhancing-video-reach-tactics-against-bot-visitors-for-2024/"><u>[Updated] Enhancing Video Reach  Tactics Against Bot Visitors for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-basic-tips-how-to-record-and-save-google-voice-calls/"><u>[Updated] In 2024, Basic Tips  How to Record and Save Google Voice Calls</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-pioneering-collage-apps-for-an-android-aesthetic/"><u>[Updated] Pioneering Collage Apps for an Android Aesthetic</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-elevate-zooms-audio-tailored-settings-for-immersive-listening/"><u>2024 Approved  Elevate Zoom's Audio  Tailored Settings for Immersive Listening</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-expert-advice-fixing-iphone-lens-blur-effectively/"><u>2024 Approved  Expert Advice  Fixing iPhone Lens Blur Effectively</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-quick-cash-on-reddit-here-are-13-ways-for-new-users/"><u>2024 Approved  Quick Cash on Reddit? Here Are 13 Ways for New Users</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-skills-for-photo-manipulation-mastery/"><u>2024 Approved  Skills for Photo Manipulation Mastery</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/rinting-engaging-content-layouts-on-youtube/"><u>Blueprinting Engaging Content Layouts on YouTube</u></a></li>
<li><a href="https://tech-revival.techidaily.com/can-you-rely-on-chatgpts-accuracy-examining-its-truthfulness/"><u>Can You Rely on ChatGPT's Accuracy: Examining Its Truthfulness</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/castwatch-inspection/"><u>CastWatch Inspection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-proxies-on-windows-11-pc/"><u>Configuring Proxies on Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/converting-oculus-rift-into-a-windows-vr-device/"><u>Converting Oculus Rift Into a Windows VR Device</u></a></li>
<li><a href="https://extra-hints.techidaily.com/crafting-visionary-art-top-10-apps-for-vector-enthusiasts-for-2024/"><u>Crafting Visionary Art  Top 10 Apps for Vector Enthusiasts for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-update-nomenclature-windows-edition/"><u>Deciphering Update Nomenclature: Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/determining-ideal-hibernation-on-windows-machines/"><u>Determining Ideal Hibernation on Windows Machines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-restrictions-save-permissions-fix-windows-way/"><u>Eliminating Restrictions: Save Permissions Fix Window's Way</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-run-command-keeps-activities-recorded/"><u>Ensuring Run Command Keeps Activities Recorded</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-security-in-free-apps-for-windows-os/"><u>Ensuring Security in Free Apps for Windows OS</u></a></li>
<li><a href="https://screen-recording.techidaily.com/expert-strategies-for-clear-communication-on-google-meet-for-2024/"><u>Expert Strategies for Clear Communication on Google Meet for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-fix-team-share-on-pc/"><u>Guide to Fix Team Share on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harmonize-windows-and-android-6-syncing-apps-to-elevate-your-experience/"><u>Harmonize Windows and Android: 6 Syncing Apps to Elevate Your Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harness-your-pc-power-multitask-effectively-on-windows-11/"><u>Harness Your PC Power: Multitask Effectively on Windows 11</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-15-pro-max-to-the-previous-iosipados-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 15 Pro Max to the Previous iOS/iPadOS Version? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-life360-shows-wrong-location-on-motorola-moto-g34-5g-drfone-by-drfone-virtual-android/"><u>How to Fix Life360 Shows Wrong Location On Motorola Moto G34 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reinstate-dormant-windows-update-protocols/"><u>How To Reinstate Dormant Windows Update Protocols</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-restore-missing-default-power-plans-on-windows-11/"><u>How to Restore Missing Default Power Plans on Windows 11</u></a></li>
<li><a href="https://games-able.techidaily.com/identifying-must-have-gaming-keyboards/"><u>Identifying Must-Have Gaming Keyboards</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-a-guide-vivo-s17-pro-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>In 2024, A Guide Vivo S17 Pro Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-complete-fixes-to-solve-apple-iphone-6-randomly-asking-for-apple-id-password-by-drfone-ios/"><u>In 2024, Complete Fixes To Solve Apple iPhone 6 Randomly Asking for Apple ID Password</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-eyes-on-the-digital-winners-top-channels/"><u>In 2024, Eyes on the Digital Winners  Top Channels</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-streamline-your-social-media-uploading-on-twitter/"><u>In 2024, Streamline Your Social Media  Uploading on Twitter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/investigating-the-ideal-state-of-windows-pcs/"><u>Investigating the Ideal State of Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-gif-resizing-obstacles-a-quick-fix-guide-to-win11s-issues/"><u>Navigating Through GIF Resizing Obstacles: A Quick Fix Guide to Win11's Issues</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-ai-avatar-wondershare-virbo-online-for-2024/"><u>New AI Avatar | Wondershare Virbo Online for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-windows-11-defense-adding-customizable-filter-options-to-context-menu/"><u>Perfecting Windows 11 Defense: Adding Customizable Filter Options to Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-methods-for-determining-your-devices-identification-through-windows/"><u>Proven Methods for Determining Your Devices’ Identification Through Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-access-tip-push-gmail-to-top-of-windows-desktop/"><u>Quick Access Tip: Push Gmail to Top of Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recapture-retro-essence-expert-tips-for-retroarcs-shader-use/"><u>Recapture Retro Essence: Expert Tips for RetroArc's Shader Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefining-assistance-four-new-options-post-cortana/"><u>Redefining Assistance: Four New Options Post-Cortana</u></a></li>
<li><a href="https://win11-tips.techidaily.com/replaying-rarieties-retro-gaming-in-dosbox-x/"><u>Replaying Rarieties: Retro Gaming in DOSBox-X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shift-windows-display-orientation-easily/"><u>Shift Windows Display Orientation Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simple-techniques-for-finding-hidden-gpeditmsc/"><u>Simple Techniques for Finding Hidden Gpedit.msc</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-your-tasks-with-notetaking-techniques-for-w11w10/"><u>Simplify Your Tasks with Notetaking Techniques for W11/W10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speed-up-windows-11-remedies-for-laggy-performance/"><u>Speed Up Windows 11: Remedies for Laggy Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-windows-from-prompting-for-updates/"><u>Stop Windows From Prompting for Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-prevent-changes-in-windows-time-settings/"><u>Techniques to Prevent Changes in Windows Time Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-six-essentials-for-restoring-frozen-menu-functions/"><u>The Six Essentials for Restoring Frozen Menu Functions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-read-only-recovery-on-windows-11-folders/"><u>Troubleshooting Read-Only Recovery on Windows 11 Folders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-share-issue-on-geforce-experience/"><u>Troubleshooting Share Issue on GeForce Experience</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/unlock-your-potential-with-outstanding-instagram-visuals-for-2024/"><u>Unlock Your Potential with Outstanding Instagram Visuals for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-hidden-outlook-folders-on-pc-a-step-by-step-guide/"><u>Unlocking Hidden Outlook Folders on PC: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-disk-management-secrets-insightful-guide-win-1011/"><u>Unveiling Disk Management Secrets: Insightful Guide (Win 10/11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-silent-workers-stopping-windows-apps/"><u>Unveiling Silent Workers: Stopping Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-and-its-disappearing-drive-letters-analysis-and-remedial-strategies/"><u>Windows and Its Disappearing Drive Letters: Analysis & Remedial Strategies</u></a></li>
</ul></div>
