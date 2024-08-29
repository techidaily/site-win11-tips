---
title: Swift Remedies for Stalling Spotify Connectivity
date: 2024-08-28T01:13:36.928Z
updated: 2024-08-29T01:13:36.928Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Swift Remedies for Stalling Spotify Connectivity
excerpt: This Article Describes Swift Remedies for Stalling Spotify Connectivity
keywords: Swift Connect Fix,Quick Spotify Link,Speed Up Streaming,Restart Spotify Conn,Boost Music Playback,Resolve Spotify Lag,Enhance Audio Sync
thumbnail: https://thmb.techidaily.com/d558a627b87b79877888fadd197a60bce9f9f188240e22025a6fa593d0f053ec.jpg
---

## Swift Remedies for Stalling Spotify Connectivity

 Spotify is one of the best Windows apps for streaming and downloading music. However, some Spotify users can’t stream and download music with that app because of error code 4\. Error code 4 is a Spotify connectivity issue with a message that says, “No internet connection detected.” Yet, users can usually still open and view websites when that issue arises.

 Users who need to fix error code 4 can’t utilize the Spotify app online. That means things like radio and streaming don’t work. This is how you can fix Spotify error code 4 on a Windows 10 or 11 PC.

## 1\. Run the Flush DNS Command

![The flushdns command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/flushdns-command.jpg)

 One confirmed solution for error code 4 is to flush the DNS cache. The DNS (Domain Name System) cache is a local storage repository of IP addresses on your PC. Your web browser retrieves DNS lookup data from that cache.

 Clearing the DNS cache will flush out and refresh its data. You can clear the DNS cache by running a flush DNS command in Command Prompt or Run. Check out our guide about[how to flush the DNS](https://www.makeuseof.com/flush-dns-cache-windows-11/) on Windows for further details about how to apply this solution.

## 2\. Select the HTTP Option in Spotify

 Spotify includes alternative proxy settings you can select to configure how that app connects with the Internet. Changing the proxy option to**HTTP** can reputedly resolve error code 4\. You can select the**HTTP** option in Spotify as follows:

1. Open your Spotify app.
2. Click the username button at the top of Spotify to view its menu.
3. Select**Settings** to view Spotify’s options.  
![The Settings menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-settings-option.jpg)
4. Click the**Proxy type** drop-down menu to select**HTTP** .  
![The HTTP option in Spotify](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/http-option.jpg)
5. Then select**Restart App** to apply.

## 3\. Change DNS Server Settings

 Error code 4 often occurs because Spotify can’t recognize your PC’s default DNS server set by your ISP. In such a scenario, the app can’t load required online resources correctly, resulting in error 4\. Many users have addressed that issue by changing their PCs’ DNS server to the universally recognized Google DNS.

 Our guide to[changing the DNS server in Windows](https://www.makeuseof.com/windows-11-alternate-ways-change-dns-server-settings/) post includes step-by-step guidelines for how to apply this solution via the Control Panel and Settings among other methods. You’ll need to set the preferred and alternative DNS server settings to Google addresses. Input**8.8.8.8** for the preferred DNS server and**8.8.4.4** for the alternative DNS setting.

![DNS server settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dns-server-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Tweak the Registry

 Some Spotify users have confirmed tweaking a DWORD value in the registry resolved error 4 for them. Those users changed the EnableActiveProbing DWORD’s value, which was set to 0 (disabled) on their PCs. These are the steps for fixing error code 4 by editing the registry:

1. Press the search box’s**Win + S** hotkey.
2. To locate the Registry Editor, enter**regedit** inside the**Type here to search** box.
3. Select Registry Editor inside the search tool.
4. Next, click within the address bar at the top of Registry Editor to clear the current location in it.
5. Go to the Internet key by inputting the following path:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\NlaSvc\Parameters\Internet`
6. Then right-click the**EnableActiveProbing** DWORD and select**Modify** .  
![The Modify option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/modify-option.jpg)
7. If**EnableActiveProbing** is set to**0** , clear the**Value data** box. Then input**1** inside that data box.  
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
![The Edit DWORD window for the EnableActiveProbing DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/edit-dword-window.jpg)
8. Select**OK** to save the new**EnableActiveProbing** value.

## 5\. Exclude Spotify From Your Antivirus Software

 You might need to fix error code 4 because of antivirus software interference with the Spotify app. Both third-party antivirus apps and Windows Security can feasibly block Spotify’s internet connectivity. You can select to exclude Spotify from antivirus protection by adding it to an exception (trusted software) list most security apps include.

![Windows Security's app exclusion settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-security-s-exclusion-list-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
 Our article about[setting Windows Security exclusions](https://www.makeuseof.com/windows-11-security-exclusions/) includes instructions for adding software to that app’s exception list. If you’re utilizing a third-party antivirus tool, look for an exclusion list within its settings tab. The antivirus software’s website will also likely include guidelines for how to use its exclusion list.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## 6\. Turn Off the Windows Defender Firewall

 Windows Defender Firewall is a component of Windows Security for filtering network traffic. Turning that firewall off could resolve error 4 if Spotify isn’t allowed through it. You can turn off WDF as outlined in our guide to[disabling the Windows Defender firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) .

![The turn off firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-firewall-s-allow-app-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Should this solution work, it’s not a good idea to keep the firewall disabled. Open Windows Defender Firewall’s allowed app list and select the Spotify checkboxes there to permit that app through it. Check out our how to guide about[allowing apps through the Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) for further details.

![The firewall's allowed apps settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/allowed-app-settings.jpg)

 Of course, numerous standalone third-party firewalls can block Spotify much the same. If you have installed a third-party firewall, try disabling it to see if that resolves error 4\. Then add Spotify to its allowed apps and turn the firewall back on if it does.

## 7\. Reinstall Spotify

 Reinstalling Spotify could resolve unknown reasons for error code 4 arising and will at least ensure you’re using the latest app version. However, note that reinstalling the app will wipe your Spotify playlists. Back up (export) any playlists you wish to keep so you can restore them. Then reinstall Spotify with the following steps:

1. Press the Start menu button and select**All apps** (in Windows 11).
2. Scroll down to the Spotify app on the Start menu.
3. Right-click Spotify and select**Uninstall** .  
![Spotify's Uninstall option on the Start menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-start-menu-s-uninstall-option.jpg)
4. If you’ve installed the desktop Spotify app, Programs and Features will open from which you can select the software and click**Uninstall** . Users who’ve installed the UWP Spotify app can select**Uninstall** on a confirmation prompt.
5. Then open the[Spotify Windows](https://www.spotify.com/us/download/windows/) download page.
6. Click**Download** to get the installer for the desktop Spotify app.  
![The Download Spotify option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/download-option.jpg)
7. Open the Explorer file manager along with the folder in which Spotify downloaded.
<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Double-click the**SpotifySetup.exe** file to bring up the setup wizard and install Spotify.

 Another option is to install the Spotify UWP (Universal Windows Platform) app on Microsoft Store. Click the**Get it From Microsoft Store** button on the linked Spotify download page to bring up that app’s MS store page. Then click the**Get in Store app** \>**Open Microsoft Store** options and select**Get** to install the UWP app.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
## Enjoy Spotify Music Online Again

 There’s a very good chance at least one Windows troubleshooting method in this guide will resolve Spotify error code 4 on your PC. They’re user-confirmed fixes that address the most common reasons for error 4 arising. With that app connection issue sorted, you can then enjoy all the best online music and radio Spotify has to offer again.

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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-decoding-youtubes-legal-framework-for-video-creators/"><u>[New] 2024 Approved  Decoding YouTube's Legal Framework for Video Creators</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-connecting-with-real-time-tiktoks-practical-guide/"><u>[New] Connecting with Real-Time TikToks  Practical Guide</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-crafting-stunning-visuals-how-to-master-use-of-luts-in-photoshop-suite/"><u>[New] Crafting Stunning Visuals  How to Master Use of LUTs in Photoshop Suite</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-exploring-vivas-video-experience-for-2024/"><u>[New] Exploring Viva's Video Experience for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/nverse-viewing-in-youtube-original-ideas-for-rewinders-for-2024/"><u>[New] Inverse Viewing in YouTube  Original Ideas for Rewinders for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-rapid-growth-on-instagram-the-like-video-duo-power/"><u>[Updated] In 2024, Rapid Growth on Instagram  The Like-Video Duo Power</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-terminating-your-linkedin-membership-an-essential-guide-for-2024/"><u>[Updated] Terminating Your LinkedIn Membership  An Essential Guide for 2024</u></a></li>
<li><a href="https://android-location.techidaily.com/10-free-location-spoofers-to-fake-gps-location-on-your-samsung-galaxy-f14-5g-drfone-by-drfone-virtual/"><u>10 Free Location Spoofers to Fake GPS Location on your Samsung Galaxy F14 5G | Dr.fone</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-learn-to-craft-instagram-ringtones-with-us/"><u>2024 Approved  Learn to Craft Instagram Ringtones with Us</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-the-essential-step-by-step-for-mac-file-formats/"><u>2024 Approved  The Essential Step-by-Step for Mac File Formats</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210979060-beat-the-drowsiness-alert-keep-your-computer-awake-easily/"><u>Beat the Drowsiness Alert - Keep Your Computer Awake Easily!</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/complete-guide-to-retrieving-accidentally-deleted-iphone-content-using-mac-software/"><u>Complete Guide to Retrieving Accidentally Deleted iPhone Content Using Mac Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-non-detected-bluetooth-on-windows-mgr/"><u>Correcting Non-Detected Bluetooth On Windows Mgr</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-software-failure-amd-195-for-windows/"><u>Correcting Software Failure: AMD 195 for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-and-correcting-bios-boot-errors-on-winos/"><u>Decoding & Correcting BIOS Boot Errors on WinOS</u></a></li>
<li><a href="https://tech-revival.techidaily.com/dive-into-character-depth-essential-chatgpt-prompts-for-writers/"><u>Dive Into Character Depth: Essential ChatGPT Prompts for Writers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easily-achieve-optimal-security-with-ms-defender-aguard-on-windows-11s-edge/"><u>Easily Achieve Optimal Security with MS Defender Aguard on Windows 11'S Edge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-outdated-video-quality-using-madvr-on-pcs/"><u>Elevate Outdated Video Quality Using MadVR on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enablingdisabling-tpm-support-in-virtualbox-70/"><u>Enabling/Disabling TPM Support in VirtualBox 7.0</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-for-high-dpi-scaling-in-windows-os/"><u>Essential Fixes for High DPI Scaling in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-building-shortcuts-to-uwp-apps-in-windows-11/"><u>Essential Tips: Building Shortcuts to UWP Apps in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-essential-steps-to-overcome-windows-os-hypervisor-faults/"><u>Five Essential Steps to Overcome Windows OS Hypervisor Faults</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-unsuccessful-file-transfers-on-windows-pcs/"><u>Fixing Unsuccessful File Transfers on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-exclude-email-address-in-windows-login-settings/"><u>How to Exclude Email Address in Windows Login Settings</u></a></li>
<li><a href="https://network-issues.techidaily.com/how-to-fix-this-computer-does-not-meet-the-minimum-requirement-for-installing-software-when-installing-intel-graphics-driver/"><u>How to Fix This Computer Does Not Meet the Minimum Requirement for Installing Software. When Installing Intel Graphics Driver</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-xiaomi-14-ultra-mirror-screen-to-pc-drfone-by-drfone-android/"><u>How Xiaomi 14 Ultra Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-realme-c67-5g-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>In 2024, Does Realme C67 5G Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-spotify-location-after-moving-to-another-country-on-xiaomi-14-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Spotify Location After Moving to Another Country On Xiaomi 14 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-command-line-integration-in-windows-11s-task-manager/"><u>Mastering Command Line Integration in Windows 11'S Task Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-folder-inclusion-in-win11s-context-menu/"><u>Mastering Folder Inclusion in Win11's Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11s-action-center-mixer-for-immersive-sound/"><u>Mastering Windows 11'S Action Center Mixer for Immersive Sound</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-microsoft-store-for-customizing-your-interface/"><u>Navigating Through Microsoft Store for Customizing Your Interface</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-looking-into-how-slow-mo-guys-have-changed-the-dynamics-of-slow-motion-for-2024/"><u>New Looking Into How Slow Mo Guys Have Changed the Dynamics of Slow-Motion for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-your-screen-and-sound-recordings-with-the-updated-windows-11-snipping-tool-max-156/"><u>Optimizing Your Screen & Sound Recordings with the Updated Windows 11 Snipping Tool (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-nonexistent-gadget-reference-on-win-11/"><u>Overcoming Nonexistent Gadget Reference on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectify-steam-error-missing-files-on-modern-windows-11-pc/"><u>Rectify Steam Error: Missing Files on Modern Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-the-absence-of-supported-scanner-for-windows-hello/"><u>Remedying the Absence of Supported Scanner for Windows Hello</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-11-get-help-issue/"><u>Resolving Windows 11 'Get Help' Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-defaults-of-the-modern-terminal-win11/"><u>Restoring Defaults of the Modern Terminal (Win11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/subtlety-saved-master-disappearing-buttons-in-1011/"><u>Subtlety Saved: Master Disappearing Buttons in 10/11</u></a></li>
<li><a href="https://howto.techidaily.com/tecno-phantom-v-flip-not-receiving-texts-10-hassle-free-solutions-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Tecno Phantom V Flip Not Receiving Texts? 10 Hassle-Free Solutions Here | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-route-for-gpo-discovery-in-pcs/"><u>The Essential Route for GPO Discovery in PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-8-windows-compatible-ios-apps-for-android-users/"><u>Top 8 Windows-Compatible iOS Apps for Android Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-strategies-to-overcome-no-server-woes-in-windows-pc-apex-legends-(156-chars/"><u>Top Strategies to Overcome No-Server Woes in Windows PC Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://data-wizards.techidaily.com/troubled-by-unresolved-advanced-video-fix/"><u>Troubled by Unresolved Advanced Video Fix</u></a></li>
<li><a href="https://youtube-data.techidaily.com/k-growth-potential-with-savvy-analysis-of-youtube-data/"><u>Unlock Growth Potential with Savvy Analysis of YouTube Data</u></a></li>
<li><a href="https://extra-resources.techidaily.com/unlocking-optimal-flight-the-lipo-selection-saga/"><u>Unlocking Optimal Flight  The LiPo Selection Saga</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-system-potential-enhancing-virtual-memory/"><u>Unlocking System Potential: Enhancing Virtual Memory</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-to-do-when-your-update-fails-at-0x800f0845/"><u>What to Do When Your Update Fails at 0X800F0845?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-woes-rescue-your-operators-download/"><u>Windows Woes? Rescue Your Operator's Download</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winerror-zeroed-out-mastery-over-error-0x800f0831/"><u>WinError Zeroed Out: Mastery Over Error 0X800F0831</u></a></li>
</ul></div>
