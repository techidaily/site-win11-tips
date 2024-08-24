---
title: Fixing Too Little Memory Warning for Virtual Machines
date: 2024-08-23T07:06:13.833Z
updated: 2024-08-24T07:06:13.833Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Too Little Memory Warning for Virtual Machines
excerpt: This Article Describes Fixing Too Little Memory Warning for Virtual Machines
keywords: VM Memory Limit Fix,Low Memory Alert VM,Increase VM RAM,Resolve VM Memory Error,Enhance VM Performance,Optimize VM Storage,Boost Virtual Machine Memory
thumbnail: https://thmb.techidaily.com/13a1f9ec7eefb2f2d2c19f961783b576aae3496864dc942793b7f634c661d531.jpg
---

## Fixing Too Little Memory Warning for Virtual Machines

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

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Expand the Virtual Memory for the Virtual Machine

 The “not enough physical memory” error can occur because not enough virtual memory has been allocated to the virtual machine. You can expand a virtual machine’s memory allocation in VMWare like this:

1. Open your VMware software.
2. Right-click the virtual machine for which you need to fix the error and select**Settings** .
3. Increase the virtual machine’s memory allocation with the bar slider. That amount should always be higher than your PC’s available RAM.  
![The memory bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-memory-bar.jpg)
4. Click**OK** to apply.

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
## 4\. Update VMware

 The “not enough physical memory” error will more likely arise on outdated WMware versions. So, ensure you’re utilizing the latest version of the software. This is how you can update VMware:

1. Bring up the VMware window.
2. Click the**Help** menu.
3. Select**Software Updates** to view that window.  
![The Software Updates option in VMware](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-software-updates-option.jpg)
4. Then click the**Check for Updates** button.  
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
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
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Delete a Recent Windows Update

 The “not enough physical memory” error can be caused by a Windows update that conflicts with VMware. So, uninstalling a recent update could fix that issue for some users. Check out our guide about[uninstalling Windows updates](https://www.makeuseof.com/windows-11-uninstall-updates/) for further details on how to apply this potential solution.

![The Installed Updates Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-uninstall-update-option.jpg)

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Perform a Clean Boot

 Performing a clean boot will disable non-essential apps and services from the Windows startup. Clean booting can potentially resolve the “not enough physical memory” in two ways. Applying this troubleshooting method will ensure there aren’t any third-party programs conflicting with VMware and free up RAM for the software.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-services-tab-in-msconfig.jpg)

 To disable all third-party startup programs and services, check out the guidelines in our guide on[how to clean boot in Windows](https://www.makeuseof.com/clean-boot-windows-11/) . This will perform a clean boot whenever you restart Windows.

 Try utilizing your VMware virtual machine after clean booting. If this works,

## 7\. Set Up a New Virtual Machine

 If the issue persists despite applying the resolutions above, consider setting up a new virtual machine to replace the one that needs fixing. Download the latest ISO for the virtual machine’s platform. Then you can set up the virtual machine again, as outlined on the[VMware support page](https://kb.vmware.com/s/article/1018415) .

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-facebook-fix-reappear-hidden-watch-video-icon/"><u>[New] 2024 Approved  Facebook Fix  Reappear Hidden Watch Video Icon</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-mastering-youtube-cards-and-markup-tips/"><u>[New] 2024 Approved  Mastering YouTube Cards & Markup Tips</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-efficient-image-capture-try-these-top-5-pc-tools-for-2024/"><u>[New] Efficient Image Capture? Try These Top 5 PC Tools for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-enhancing-iphone-selfies-with-water-surface-highlights-for-2024/"><u>[New] Enhancing iPhone Selfies with Water Surface Highlights for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-mastering-facebook-broadcasts-via-pc-and-mac-with-obs/"><u>[Updated] 2024 Approved  Mastering Facebook Broadcasts via PC & Mac with OBS</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-budget-friendly-interactive-face-to-face-games-for-2024/"><u>[Updated] Budget-Friendly Interactive Face-to-Face Games for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-cutting-edge-webcam-editing-emphasize-focus-not-the-fence-for-2024/"><u>[Updated] Cutting Edge Webcam Editing – Emphasize Focus, Not the Fence for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-avoid-these-8-steps-that-newcomers-often-miss-on-youtube/"><u>[Updated] In 2024, Avoid These 8 Steps that Newcomers Often Miss on YouTube</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-quizzical-quests-top-trivia-video-platforms/"><u>[Updated] Quizzical Quests  Top Trivia Video Platforms</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-the-ace-guide-to-smooth-laptop-video-editing-via-inshot/"><u>[Updated] The Ace Guide to Smooth Laptop Video Editing via Inshot</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-winning-windows-sound-engineers/"><u>[Updated] Winning Windows Sound Engineers</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-full-guide-streamlining-your-files-in-the-digital-age-with-adobe-and-beyond/"><u>2024 Approved  Full Guide  Streamlining Your Files in the Digital Age with Adobe & Beyond</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/a-comprehensive-look-at-ffpm-your-pip-guide/"><u>A Comprehensive Look at FFPM  Your PIP Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-steam-downloads-enhancing-windows-performance/"><u>Boosting Steam Downloads: Enhancing Windows Performance</u></a></li>
<li><a href="https://article-posts.techidaily.com/conquering-zoom-meetings-a-tech-savvy-setup-strategy/"><u>Conquering Zoom Meetings  A Tech-Savvy Setup Strategy</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/crafting-new-tones-top-7-recording-changer-applications-reviewed-for-2024/"><u>Crafting New Tones  Top 7 Recording Changer Applications Reviewed for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decreasing-processor-load-while-engaged-in-virtual-battles/"><u>Decreasing Processor Load While Engaged in Virtual Battles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-ui-context-menu-with-disk-space-insight-tool/"><u>Enhancing Windows UI: Context Menu with Disk Space Insight Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enrich-windows-11-notepad-through-synergistic-tech/"><u>Enrich Windows 11 Notepad Through Synergistic Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-top-displayed-calculator-on-pcs/"><u>Ensuring Top-Displayed Calculator on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-edits-for-enhanced-user-control-in-win11/"><u>Essential Edits for Enhanced User Control in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-for-resolving-windows-camera-issues/"><u>Essential Steps for Resolving Windows Camera Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-windows-auditory-service-auto-restart-feature/"><u>How to Enable Windows Auditory Service Auto-Restart Feature</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-enhance-your-outdoor-adventures-with-google-maps-live-view-functionality/"><u>How to Enhance Your Outdoor Adventures with Google Maps Live View Functionality</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-oppo-reno-11-5g-drfone-by-drfone-virtual-android/"><u>How to Get and Use Pokemon Go Promo Codes On Oppo Reno 11 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-page-not-rendered-in-ms-marketplace/"><u>How to Rectify Page Not Rendered in MS Marketplace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-microsoft-defender-blocking-third-party-antivirus-software-on-windows/"><u>How to Stop Microsoft Defender Blocking Third-Party Antivirus Software on Windows</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-the-quintessential-ten-hexa-flights/"><u>In 2024, The Quintessential Ten Hexa-Flights</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-unlock-your-disabled-iphone-13-pro-max-without-itunes-in-5-ways-by-drfone-ios/"><u>In 2024, Unlock Your Disabled iPhone 13 Pro Max Without iTunes in 5 Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-upgrade-for-ancient-computers-running-windows-11-using-to-go-and-rufus/"><u>Instant Upgrade for Ancient Computers: Running Windows 11 Using To Go & Rufus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/loudness-levelers-essential-apps-for-taking-windows-audio-above-100/"><u>Loudness Levelers: Essential Apps for Taking Windows' Audio Above 100%%</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ring-360-degree-videos-secure-youtube-uploads/"><u>Mastering 360-Degree Videos  Secure YouTube Uploads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/opera-installer-stuck-downloading-on-windows-try-these-fixes/"><u>Opera Installer Stuck Downloading on Windows? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-this-non-adobe-windows-errors/"><u>Overcoming 'This Non-Adobe' Windows Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-missing-display-in-windows-11/"><u>Overcoming Missing Display in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-fetching-ip-and-mac-addresses-windows-wise/"><u>Quick Guide: Fetching IP & MAC Addresses, Windows-Wise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regular-maintenance-rebuilding-win-icon-cache/"><u>Regular Maintenance: Rebuilding Win Icon Cache</u></a></li>
<li><a href="https://win11-tips.techidaily.com/retrieve-your-wingman-copilot-in-ws11s-struggle/"><u>Retrieve Your Wingman (Copilot) In WS11's Struggle</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/step-by-step-enhancing-clarity-in-google-meet-calls-for-2024/"><u>Step-by-Step  Enhancing Clarity in Google Meet Calls for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-unlocking-telnet-on-wins-os-x/"><u>Step-by-Step Guide: Unlocking Telnet on Wins OS X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-autonomous-restarts-win11-strategy/"><u>Stop Autonomous Restarts: Win11 Strategy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-screech-start-scroll-mouse-adjustment-guide/"><u>Stop Screech, Start Scroll: Mouse Adjustment Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-improve-file-transfers-on-win11-pcs-1/"><u>Strategies to Improve File Transfers on WIN11 PCs (1)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-tweaks-lessening-apps-resource-consumption/"><u>System Tweaks: Lessening Apps' Resource Consumption</u></a></li>
<li><a href="https://android-unlock.techidaily.com/the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-oppo-a38-device-by-drfone-android/"><u>The Ultimate Guide How to Bypass Swipe Screen to Unlock on Oppo A38 Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-empty-directory-error-code-x80070091/"><u>Troubleshooting Windows' Empty Directory Error Code X80070091</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/turning-twitter-video-into-engaging-customizable-gifs-for-2024/"><u>Turning Twitter Video Into Engaging Customizable GIFs for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-captcha-on-steam-for-successful-logins/"><u>Unblocking CAPTCHA on Steam for Successful Logins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-lan-world-play-windows-mc-solutions/"><u>Unleashing LAN World Play: Windows MC Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-your-displays-potential-with-these-simple-steps/"><u>Unlock Your Display's Potential with These Simple Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-insights-what-patch-wxx-brings-to-windows-11/"><u>Upgrade Insights: What Patch W.x.x Brings to Windows 11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/visionary-designs-for-future-mojave-dwellings-for-2024/"><u>Visionary Designs for Future Mojave Dwellings for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-back-your-elusive-5ghz-connection-with-these-solutions/"><u>Win Back Your Elusive 5GHz Connection with These Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win10-drawing-delights-the-ultimate-7-app-guide/"><u>Win10 Drawing Delights: The Ultimate 7 App Guide</u></a></li>
</ul></div>
