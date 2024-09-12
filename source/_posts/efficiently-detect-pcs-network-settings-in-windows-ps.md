---
title: Efficiently Detect PC's Network Settings in Windows PS
date: 2024-09-11T01:20:51.538Z
updated: 2024-09-12T01:20:51.538Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Efficiently Detect PC's Network Settings in Windows PS
excerpt: This Article Describes Efficiently Detect PC's Network Settings in Windows PS
keywords: WinPSNetworkCheck,PsWindowsConfig,NetInfoWinPC,SetupDetectorPS,WINPSNetSettings,ConfigDetectionWin,PSNetworkDiagnose
thumbnail: https://thmb.techidaily.com/26dcef27c207b8605e3fcf4585ee0822110eeb8a794c85ff8e27071c7786d452.jpg
---

## Efficiently Detect PC's Network Settings in Windows PS

 Have you been facing some network or troubleshooting issues on your PC? Or maybe you simply need to fix your access control or networking problems caused by your device or hardware. In cases like this, knowing your MAC or IP address will come in handy.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.





<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139122/17108" target="_top" id="2139122">
  <img src="//a.impactradius-go.com/display-ad/17108-2139122" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139122/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## How to Find Your IP or MAC Address on a Windows Using the PowerShell

 Figuring out your IP address using [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) is easy. Here's how you can get started:

1. Head to the **Start menu** search bar, type in 'powershell,' and select the best match.
2. Once the PowerShell is up, type in the following command and hit **Enter**:  
`Get-NetIPAddress <code class="language-powershell" lang="powershell">-AddressFamily IPV4`

 That's it; as soon as you type in this command, the PowerShell will give you the IPv4 addresses of all network adapters of your Windows system. As you can see below, you will get your PC's IP address, subnet mask, default gateway, etc.

![windows powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-3.jpg)





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135372/19272" target="_top" id="2135372">
  <img src="//a.impactradius-go.com/display-ad/19272-2135372" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135372/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->








<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134240/18498" target="_top" id="2134240">
  <img src="//a.impactradius-go.com/display-ad/18498-2134240" border="0" alt="https://techidaily.com" width="540" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134240/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135362/19272" target="_top" id="2135362">
  <img src="//a.impactradius-go.com/display-ad/19272-2135362" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135362/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".





<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134229/18498" target="_top" id="2134229">
  <img src="//a.impactradius-go.com/display-ad/18498-2134229" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134229/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Finding Your IP or MAC Address on Windows PC

 So that's all about your IP or MAC address on your Windows PC. Type in the above commands, and you will get your MAC or IP addresses instantly. Of course, PowerShell is just one way of doing that. For instance, you can even find out your IP address on Windows with both settings menu and Command prompt. Knowing all the different methods, then, will come in handy in places like this.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-types-of-facebook-video-aspect-ratios/"><u>[New] 2024 Approved Types of Facebook Video Aspect Ratios</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-mastering-youtubes-prominent-channel-placement/"><u>[New] In 2024, Mastering YouTube's Prominent Channel Placement</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-transform-your-profile-into-an-instagram-powerhouse-with-these-verification-insights/"><u>[New] In 2024, Transform Your Profile Into an Instagram Powerhouse with These Verification Insights</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-the-clear-sky-route-to-free-unmarked-tiktok-videos/"><u>[New] The Clear-Sky Route to Free, Unmarked TikTok Videos</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-visual-narrative-weaver/"><u>[Updated] Visual Narrative Weaver</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-youtube-outro-complete-guide-plusbest-makers-and-templates/"><u>[Updated] YouTube Outro Complete Guide [+Best Makers & Templates]</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-unveiling-sites-that-link-you-to-youtube-promo-deals/"><u>2024 Approved Unveiling Sites That Link You to YouTube Promo Deals</u></a></li>
<li><a href="https://win-blog.techidaily.com/1722993104539-cyberpunk-2077-launch-woes-discover-proven-fixes-that-can-help-you-play/"><u>Cyberpunk 2077 Launch Woes? Discover Proven Fixes That Can Help You Play!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-enigma-unraveling-wacatacbmls-mechanism-on-windows/"><u>Deciphering the Enigma: Unraveling Wacatac.B!ml's Mechanism on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-how-to-modify-window-glow-on-your-pc/"><u>Discover How to Modify Window Glow on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-data-management-linking-onedrive-and-microsoft/"><u>Effortless Data Management: Linking OneDrive and Microsoft</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-reading-view-as-default-in-word-for-email-attachments/"><u>Enabling Reading View as Default in Word for Email Attachments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enablingdisabling-microsofts-smartfilter-in-win11/"><u>Enabling/Disabling Microsoft’s SmartFilter in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-side-by-side-fault-in-windows/"><u>Eradicating Side-by-Side Fault in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-techniques-for-calls-tracking/"><u>Essential Windows Techniques for Calls Tracking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-picks-best-torrent-software-for-windows-devices/"><u>Expert Picks: Best Torrent Software for Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-hidden-5ghz-network-issues-in-windows-11-effectively/"><u>Fix Hidden 5GHz Network Issues in Windows 11 Effectively</u></a></li>
<li><a href="https://change-location.techidaily.com/how-does-the-stardust-trade-cost-in-pokemon-go-on-vivo-x100-drfone-by-drfone-virtual-android/"><u>How does the stardust trade cost In pokemon go On Vivo X100? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-detect-and-remove-spyware-on-xiaomi-redmi-note-12-pro-4g-drfone-by-drfone-virtual-android/"><u>How to Detect and Remove Spyware on Xiaomi Redmi Note 12 Pro 4G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-disable-or-remove-hyper-v-in-windows-11/"><u>How to Disable or Remove Hyper-V in Windows 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-fix-oem-unlock-missing-on-oppo-find-n3-flip-by-drfone-android/"><u>How To Fix OEM Unlock Missing on Oppo Find N3 Flip?</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/how-to-shoot-slow-motion-video-on-iphone/"><u>How to Shoot Slow Motion Video on iPhone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-beat-the-beast-instagram-video-troubleshooting-guide/"><u>In 2024, Beat the Beast Instagram Video Troubleshooting Guide</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-change-location-on-yik-yak-for-your-asus-rog-phone-7-ultimate-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>In 2024, Change Location on Yik Yak For your Asus ROG Phone 7 Ultimate to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-itel-p55-5g-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Itel P55 5G Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-microsofts-mspcm-toolbar-on-w11-os/"><u>Leveraging Microsoft's MSPCM Toolbar on W11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-fast-forward-youtube-on-windows-chrome/"><u>Mastering Fast-Forward YouTube on Windows Chrome</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-microsofts-family-safety-landscape/"><u>Navigating Microsoft's Family Safety Landscape</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-disabled-file-consolidation-feature/"><u>Overcoming Disabled File Consolidation Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-dism-error-0x800f082f-in-microsofts-os/"><u>Overcoming DISM Error 0X800F082F in Microsoft's OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-xp-error-code-0xfffffddd/"><u>Overcoming Window's XP Error Code 0xFFFFFDDD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalized-group-policy-application-on-windows-users-versions-1111/"><u>Personalized Group Policy Application on Windows Users, Versions 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-guide-stop-vmware-virtual-machine-error-in-win11/"><u>Quick Fix Guide: Stop VMware Virtual Machine Error in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rebooting-astra-pilot-link-on-latest-os-ws11/"><u>Rebooting Astra Pilot Link on Latest OS, WS11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recommendations-for-setting-a-preferred-cli-window/"><u>Recommendations for Setting a Preferred CLI Window</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefining-digital-canvas-4-key-upgrades-to-microsoft-paint/"><u>Redefining Digital Canvas: 4 Key Upgrades to Microsoft Paint</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simple-way-to-construct-a-windows-speech-recognition-app-using-autohotkey/"><u>Simple Way to Construct a Window's Speech Recognition App Using AutoHotkey</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-enabling-and-using-hyper-v-on-w11-homes/"><u>Step-by-Step Guide to Enabling and Using Hyper-V on W11 Homes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-extending-hard-drive-size-at-zero-cost-in-windows/"><u>Strategies for Extending Hard Drive Size at Zero Cost in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-handling-windows-11s-read-only-files/"><u>Strategies for Handling Windows 11'S Read-Only Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-that-clear-up-common-system-errors/"><u>Strategies that Clear Up Common System Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-windows-top-video-converters-reviewed/"><u>Streamline Your Windows: Top Video Converters Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swivel-pictures-perfectly-in-windows-11/"><u>Swivel Pictures Perfectly in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-win11-mouse-access-for-comfort/"><u>Tailoring Win11 Mouse Access for Comfort</u></a></li>
<li><a href="https://techidaily.com/top-iphone-14-pro-message-recovery-software-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Top iPhone 14 Pro Message Recovery Software | Stellar</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/transforming-onenote-workflow-insights-and-tips-on-using-the-onetastic-add-in/"><u>Transforming OneNote Workflow: Insights and Tips on Using the Onetastic Add-In</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbocharge-office-performance-on-windows-with-key-shortcuts/"><u>Turbocharge Office Performance on Windows With Key Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-fixes-for-unreachable-geforce-x-configuration-errors/"><u>Uncovering Fixes for Unreachable GeForce X Configuration Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-file-writing-obstructions-in-windows-devices/"><u>Unraveling File Writing Obstructions in Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-windows-app-interactivity-via-streamlined-connection-solutions/"><u>Upgrade Window's App Interactivity via Streamlined Connection Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-against-windows-unlock-exe-file-functionality/"><u>Win Against Windows: Unlock EXE File Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-developing-a-security-focused-removal-applet/"><u>Windows 11: Developing a Security-Focused Removal Applet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/xbox-wont-start-try-these-fixes-for-windows-users/"><u>Xbox Won't Start? Try These Fixes for Windows Users</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>