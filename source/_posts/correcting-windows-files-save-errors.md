---
title: Correcting Windows Files' Save Errors
date: 2024-08-28T01:10:20.476Z
updated: 2024-08-29T01:10:20.476Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Windows Files' Save Errors
excerpt: This Article Describes Correcting Windows Files' Save Errors
keywords: Fix Windows Saving Issues,Windows Save Failure Troubleshoot,Resolve Windows File Save Errors,Stop Windows Save Crashes,Windows Save Glitch Repair,Mend Windows Save Problems Quickly,Tackle Windows Files' Saving Errors
thumbnail: https://thmb.techidaily.com/03446fa7c6c4437cc78cf994a5cd500e9e19b7398656e9b5a14acb95e0d9c21d.jpg
---

## Correcting Windows Files' Save Errors

 Users have reported error 0x80070005 or 0x80070539 arises when they try to set new apps to save to different external drive locations with Settings. Those error codes have the same message that says, “We couldn’t set your default save location.” This means users can’t change the default save location for apps.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

## 1\. Set Your User Account to Administrator

 If you’re utilizing a standard Windows account, [change your user account type](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) to an administrative one. A standard user account will prevent you from applying any more complicated system changes. Changing the save location for apps is something you might need admin privileges for.

![The Account type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-account-type-window.jpg)

## 2\. Rename the WindowsApps Directory

 This error can arise because the WindowsApps folder where apps save is corrupted. Renaming the WindowsApps folder on the drive or partition you want to save apps can address such an issue. To do so, rename that folder as follows:

1. If you’re trying to set apps to save on an external drive, connect that hard drive to your PC.
2. [Open the File Explorer folder navigator](https://www.makeuseof.com/windows-open-file-explorer/) and click **This PC**.
3. Double-click the drive/partition you want to set as your default save location for apps.
4. Then, right-click on the WindowsApps folder and select its **Rename** context menu option. You should find that directory within the drive’s root directory.  
![The Rename option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-button.jpg)
5. Rename the folder to **WindowsApps.old** and press **Enter**.
6. Thereafter, try changing the default save location for apps again via Settings.

 If that still doesn’t work, then proceed to the next resolution.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
## 3\. Delete or Rename the WpSystem Folder

 Many users confirm that renaming or deleting the WpSystem folder fixes error 0x80070005\. WpSystem is a folder created to store app data. Try renaming that folder to **WpSystem.old** on the drive you can’t set to be a save location for apps, as outlined for the previous method. The WpSystem will be in the same directory as the WindowsApps folder.

 Alternatively, delete the WpSystem folder. You can [erase a file or folder in Explorer](https://www.makeuseof.com/windows-11-delete-select-files/) by right-clicking it and selecting **Delete**. If you can’t find that folder or this potential solution doesn’t work, try the next resolution.

![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-option.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
## 4\. Set Full System Permission for the System Volume Folder

 Setting full permission for the System Volume folder is another confirmed fix for error 0x80070005\. Follow these steps to set full permission for the System Volume directory:

1. Go into File Explorer and click the three-dot **See more** menu > **Options**. In Windows 10, click **Options** on the **View** tab.
2. Select **View** on the Folder Options window.
3. Deselect the **Hide protected operating system files (Recommended)** option.  
![The Hide protected operating system files checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hide-protected-operating-system-files.jpg)
4. Select the **Show hidden files, folders and drives** radio button.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
5. Click **Apply** to save the new Explorer settings.

1. Select the drive you need to set as the default save location for apps.
2. Right-click the System Volume Information folder and select **Properties**.
3. Click **Security > Advanced** to bring up an Advanced Security Settings window.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/security-tab.jpg)
4. Press the **Continue** button.
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
5. Next, click **Add** to view a Permission Entry window.

1. Click the **Select a principal** option.
2. Input **SYSTEM** inside the object name box.  
![The Select User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-user-group.jpg)
3. Click on the **OK** button.
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
4. Select the **Full control permission** setting.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-option.jpg)
5. Then select the **OK** options on the Permission Entry and Advanced Security Settings windows.

 Close all remaining open windows. Then, restart your PC and try changing the default save location.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->
## Set a New Default Save Location in Windows 11/10

 Many users have needed to fix error 0x80070005 and have done so by applying the potential solutions in this guide. The WpSystem folder is often the source of the error, and resolution two is the most widely confirmed method for fixing this issue.

 However, some users have also fixed the issue by applying the less widely cited fourth method.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-tips.techidaily.com/new-10-leading-mobile-vr-headsets-ranked/"><u>[New] 10 Leading Mobile VR Headsets Ranked</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-chrome-os-screen-capture-mastering-the-art-in-four-steps-for-2024/"><u>[New] Chrome OS Screen Capture  Mastering the Art in Four Steps for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-achieving-video-clarity-with-obs-in-zoom-environments/"><u>[New] In 2024, Achieving Video Clarity with OBS in Zoom Environments</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-in-2024-mastering-visual-enhancements-in-tiktok/"><u>[New] In 2024, Mastering Visual Enhancements in TikTok</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-saving-instagrams-finest-in-your-photo-gallery/"><u>[Updated] 2024 Approved  Saving Instagram's Finest in Your Photo Gallery</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-best-in-class-elite-4k-televisions-for-2024/"><u>[Updated] Best in Class  Elite 4K Televisions for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-detailed-walkthrough-monitoring-and-managing-your-off-facebook-activities-for-2024/"><u>[Updated] Detailed Walkthrough  Monitoring and Managing Your Off-Facebook Activities for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-finest-pencil-masters-free-vs-paid-windows-apps-reviewed/"><u>[Updated] Finest Pencil Masters  Free vs Paid Windows Apps Reviewed</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-screenflow-exploration-a-mac-focused-journey-through-video-editing/"><u>[Updated] In 2024, ScreenFlow Exploration  A Mac-Focused Journey Through Video Editing</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-starting-point-learning-to-thrive-in-instagrams-virtual-spaces/"><u>[Updated] In 2024, Starting Point  Learning to Thrive in Instagram's Virtual Spaces</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-optimal-solution-for-actions-screening-for-2024/"><u>[Updated] Optimal Solution for Actions Screening for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-streamlined-methods-for-documenting-overwatch-engagements-for-2024/"><u>[Updated] Streamlined Methods for Documenting Overwatch Engagements for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-transform-video-beats-into-ringtones-must-visit-sites-explored/"><u>[Updated] Transform Video Beats Into Ringtones  Must-Visit Sites Explored</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-scrutinizing-vrs-enchantment-and-challenges-ahead/"><u>2024 Approved  Scrutinizing VR's Enchantment and Challenges Ahead</u></a></li>
<li><a href="https://tech-haven.techidaily.com/a-comparative-analysis-spotlighting-8-major-discrepancies-between-my-snapchat-ai-and-bing-chat/"><u>A Comparative Analysis: Spotlighting 8 Major Discrepancies Between My Snapchat AI and Bing Chat</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/best-free-3d-text-psd-files-for-2024/"><u>Best Free 3D Text PSD Files for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/bypass-stuck-on-configuration-quick-tips-for-a-smooth-windows-installation/"><u>Bypass 'Stuck on Configuration' - Quick Tips for a Smooth Windows Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-line-concoctions-5-hilarious-tricks-at-work/"><u>Command Line Concoctions: 5 Hilarious Tricks at Work</u></a></li>
<li><a href="https://driver-install.techidaily.com/confront-uartusb-incompatibility/"><u>Confront UART/USB Incompatibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correction-of-windows-1011-zoom-failure-code-1132/"><u>Correction of Windows 10/11 Zoom Failure - Code 1132</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/elevate-conversations-with-these-top-50-latin-quotables/"><u>Elevate Conversations with These Top 50 Latin Quotables</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expanding-user-experience-customizing-window-11-menus/"><u>Expanding User Experience: Customizing Window 11 Menus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-steam-error-on-windows-no-more-blank-screens/"><u>Fixing Steam Error on Windows: No More Blank Screens</u></a></li>
<li><a href="https://program-issues.techidaily.com/fortnite-troubleshooting-what-to-do-if-you-cant-play-due-to-permission-issues/"><u>Fortnite Troubleshooting: What to Do If You Can’t Play Due to Permission Issues</u></a></li>
<li><a href="https://extra-hints.techidaily.com/get-acquainted-with-the-10-best-sketching-apps-for-chrome-os/"><u>Get Acquainted with The 10 Best Sketching Apps for Chrome OS</u></a></li>
<li><a href="https://howto.techidaily.com/gmail-not-working-on-honor-x9a-7-common-problems-and-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Gmail Not Working on Honor X9a 7 Common Problems & Fixes | Dr.fone</u></a></li>
<li><a href="https://driver-install.techidaily.com/harmonize-intel-drivers-with-latest-windows-11-7-and-81-standards/"><u>Harmonize Intel Drivers with Latest Windows 11, 7 & 8.1 Standards</u></a></li>
<li><a href="https://iphone-location.techidaily.com/how-to-enable-disable-and-change-safari-location-on-apple-iphone-6s-plus-drfone-by-drfone-virtual-ios/"><u>How to Enable, Disable, and Change Safari Location on Apple iPhone 6s Plus | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-connection-to-the-remote-computer-could-not-be-established-windows-vpn-error/"><u>How to Fix the “Connection to the Remote Computer Could Not Be Established” Windows VPN Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tweak-win11s-connection-behavior/"><u>How to Tweak Win11's Connection Behavior</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-oneplus-nord-n30-se-phone-password-without-factory-reset-by-drfone-android/"><u>How to Unlock OnePlus Nord N30 SE Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-full-guide-to-unlock-your-samsung-galaxy-s24-ultra-by-drfone-android/"><u>In 2024, Full Guide to Unlock Your Samsung Galaxy S24 Ultra</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-google-meet-screen-record-tips-for-iphoneandroid-users/"><u>In 2024, Google Meet Screen Record Tips for iPhone/Android Users</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-live-viewing-archive/"><u>In 2024, Live Viewing Archive</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-is-a-sim-network-unlock-pin-get-your-vivo-t2-pro-5g-phone-network-ready-by-drfone-android/"><u>In 2024, What Is a SIM Network Unlock PIN? Get Your Vivo T2 Pro 5G Phone Network-Ready</u></a></li>
<li><a href="https://driver-install.techidaily.com/install-updated-audio-protocols-for-windows-7-by-idt/"><u>Install Updated Audio Protocols for Windows 7 by IDT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instantly-install-hyper-v-on-your-windows-11-homesystem/"><u>Instantly Install Hyper-V on Your Windows 11 Homesystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-phone-calls-into-your-workflow-intel-unison-and-windows-11-guide/"><u>Integrating Phone Calls Into Your Workflow: Intel Unison & Windows 11 Guide</u></a></li>
<li><a href="https://article-tips.techidaily.com/iphone-data-recovery-software-recover-data-with-confidence/"><u>IPhone Data Recovery Software: Recover Data with Confidence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lighten-system-load-streamlining-media-consumption-on-pcs/"><u>Lighten System Load: Streamlining Media Consumption on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-fingertip-input-windows-tutorial/"><u>Mastering Fingertip Input: Windows Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-mobility-control-deactivation-in-w11/"><u>Mastering Mobility Control Deactivation in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-guide-to-bypass-ms-teams-error-80080300-on-windows-11/"><u>Mastery Guide to Bypass MS Teams Error 80080300 on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-in-security-4-streamlined-methods-to-deactivate-windows-users/"><u>Mastery in Security: 4 Streamlined Methods to Deactivate Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-windows-charmap-problems-with-ease/"><u>Mending Windows CharMap Problems with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-graphics-shortage-on-enchanted-magic-school-platform/"><u>Overcoming Graphics Shortage on Enchanted Magic School Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-steams-non-syncing-library-files/"><u>Quick Fix for Steam's Non-Syncing Library Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-eradicating-xbox-service-interruption/"><u>Quick Fixes: Eradicating Xbox Service Interruption</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-powerful-cpu-usage-a-compre-cookie/"><u>Reducing Powerful CPU Usage: A Compre Cookie</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-the-disk-read-failure-issue-in-windows/"><u>Remedying the Disk Read Failure Issue in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-unresponsive-windows-webcam/"><u>Remedying Unresponsive Windows Webcam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrecting-disconnected-win-ethernet/"><u>Resurrecting Disconnected Win Ethernet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/selecting-optimal-windows-options-for-switch-gaming-enthusiasts/"><u>Selecting Optimal Windows Options for Switch Gaming Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-taskbar-customization-with-portables/"><u>Simplifying Taskbar Customization with Portables</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-rectifying-white-login-screens-on-win1011-oses/"><u>Steps for Rectifying White Login Screens on Win10/11 OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-locate-and-open-windowsstore-folder/"><u>Steps to Locate and Open WindowsStore Folder</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-prevent-and-correct-operational-error-0x0000011b-on-win11/"><u>Steps to Prevent and Correct Operational Error 0X0000011B on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solutions-to-22h2-windows-setbacks/"><u>Swift Solutions to 22H2 Windows Setbacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-error-0x0000007b-quick-fixes-for-windows/"><u>Taming Error 0X0000007B - Quick Fixes for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-halt-windows-shutdown-clock/"><u>Techniques to Halt Windows Shutdown Clock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/telnet-setup-for-network-connectivity-in-windows-11/"><u>Telnet Setup for Network Connectivity in Windows 11</u></a></li>
<li><a href="https://article-helps.techidaily.com/the-ultimate-mobile-cinema-showcase-apples-best-freepluspaid-film-watchers-guide-for-2024/"><u>The Ultimate Mobile Cinema Showcase  Apple's Best FREE+Paid Film Watchers Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-issue-code-30005-failed-file-creation-on-windows/"><u>Troubleshooting Issue Code 30005 - Failed File Creation on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-gpu-potential-win-friendly-tools-ranked-1-6/"><u>Unleash GPU Potential: Win-Friendly Tools Ranked #1-#6</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-optimized-web-linkage-in-your-windows-applications-today/"><u>Unlock Optimized Web Linkage in Your Windows Applications Today</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unveiling-chatgpts-native-tools/"><u>Unveiling ChatGPT’s Native Tools</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-videopad-video-editor-the-good-the-bad-and-the-ugly-a-review-and-buying-guide-for-2024/"><u>Updated Videopad Video Editor The Good, the Bad, and the Ugly - A Review and Buying Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/utilizing-windows-11s-auto-hdr-effectively/"><u>Utilizing Windows 11'S Auto HDR Effectively</u></a></li>
<li><a href="https://extra-tips.techidaily.com/virtual-explorers-toolkit-select-these-7-must-have-tech/"><u>Virtual Explorers' Toolkit - Select These 7 Must-Have Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-wisdom-secrets-to-instant-dossiers-creation/"><u>Win11 Wisdom: Secrets to Instant Dossiers Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-edge-less-design-tips/"><u>Windows 11 Edge-Less Design Tips</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>