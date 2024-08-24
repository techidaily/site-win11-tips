---
title: "Easy Windows IP/MAC: Using PowerShell Techniques"
date: 2024-08-23T06:58:14.833Z
updated: 2024-08-24T06:58:14.833Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Easy Windows IP/MAC: Using PowerShell Techniques"
excerpt: "This Article Describes Easy Windows IP/MAC: Using PowerShell Techniques"
keywords: PowerShell IP Addressing,MAC with PowerShell,Easy Windows Scripting,PowerShell Network Tools,Windows IP Management,Advanced Mac Query,Simple PowerShell Commands
thumbnail: https://thmb.techidaily.com/485fa639637af95e40bb39955015be2d5660936e6475a435b4a4c85695223b88.jpg
---

## Easy Windows IP/MAC: Using PowerShell Techniques

 Have you been facing some network or troubleshooting issues on your PC? Or maybe you simply need to fix your access control or networking problems caused by your device or hardware. In cases like this, knowing your MAC or IP address will come in handy.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

## How to Find Your IP or MAC Address on a Windows Using the PowerShell

 Figuring out your IP address using [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) is easy. Here's how you can get started:

1. Head to the **Start menu** search bar, type in 'powershell,' and select the best match.
2. Once the PowerShell is up, type in the following command and hit **Enter**:  
`Get-NetIPAddress <code class="language-powershell" lang="powershell">-AddressFamily IPV4`

 That's it; as soon as you type in this command, the PowerShell will give you the IPv4 addresses of all network adapters of your Windows system. As you can see below, you will get your PC's IP address, subnet mask, default gateway, etc.

![windows powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-3.jpg)

## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
## Finding Your IP or MAC Address on Windows PC

 So that's all about your IP or MAC address on your Windows PC. Type in the above commands, and you will get your MAC or IP addresses instantly. Of course, PowerShell is just one way of doing that. For instance, you can even find out your IP address on Windows with both settings menu and Command prompt. Knowing all the different methods, then, will come in handy in places like this.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/new-a-brief-guide-to-download-install-and-use-ez-grabber/"><u>[New] A Brief Guide to Download, Install, and Use EZ Grabber</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-from-buffer-to-broadcast-learn-how-to-convert-your-youtube-viewing-into-a-screenshot-for-free-for-2024/"><u>[New] From Buffer to Broadcast  Learn How to Convert Your YouTube Viewing Into a Screenshot for Free for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-the-essential-guide-to-du-recorder-functionality/"><u>[New] In 2024, The Essential Guide to Du Recorder Functionality</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-speak-out-altering-soundtracks-in-ps4ps5-games/"><u>[New] Speak Out  Altering Soundtracks in PS4/PS5 Games</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-top-8-picks-for-excellent-free-srt-translation-tools/"><u>[New] Top 8 Picks for Excellent Free SRT Translation Tools</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-windowsmac-recording-skype-chats-and-calls-for-2024/"><u>[New] Windows/Mac  Recording Skype Chats & Calls for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-elevating-your-presence-a-guide-to-discord-broadcasts-for-2024/"><u>[Updated] Elevating Your Presence  A Guide to Discord Broadcasts for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-leading-the-charge-smart-transcription-in-professional-slides/"><u>[Updated] Leading the Charge  Smart Transcription in Professional Slides</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-simplified-guide-to-movie-recording-on-diverse-systems/"><u>[Updated] Simplified Guide to Movie Recording on Diverse Systems</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-vivo-y100i-power-5g-drfone-by-drfone-virtual-android/"><u>15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Vivo Y100i Power 5G | Dr.fone</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-easy-tweaks-changing-fishy-vocal-patterns-on-windows/"><u>2024 Approved  Easy Tweaks  Changing Fishy Vocal Patterns on Windows</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-transparency-in-tracking-youtube-viewers/"><u>2024 Approved  Transparency in Tracking YouTube Viewers</u></a></li>
<li><a href="https://howto.techidaily.com/4-solutions-to-fix-unfortunately-your-app-has-stopped-error-on-vivo-y77t-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Solutions to Fix Unfortunately Your App Has Stopped Error on Vivo Y77t | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/commanding-pcs-reactive-devices-during-rest/"><u>Commanding PC's Reactive Devices During Rest</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-oppo-find-x6-by-drfone-android/"><u>Complete Review & Guide to Techeligible FRP Bypass and More For Oppo Find X6</u></a></li>
<li><a href="https://win11-tips.techidaily.com/designing-individualized-win11-screensavers/"><u>Designing Individualized Win11 Screensavers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/developing-a-feature-to-showcase-latest-updates-in-explorer/"><u>Developing a Feature to Showcase Latest Updates in Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/differences-highlighted-microsoft-and-local-account-divergences-on-pc/"><u>Differences Highlighted: Microsoft and Local Account Divergences on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-as-pie-fixing-the-top-11-windows-11-issues/"><u>Easy as Pie: Fixing the Top 11 Windows 11 Issues</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/easy-guide-to-tecno-spark-20c-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Tecno Spark 20C FRP Bypass With Best Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-unidentified-device-errors-on-w11w10/"><u>Eliminating Unidentified Device Errors on W11/W10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-quickly-engaging-windows-support-services/"><u>Expert Tips for Quickly Engaging Windows' Support Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/faster-start-up-methods-modify-windows-11s-booting-timeout/"><u>Faster Start-Up Methods: Modify Windows 11'S Booting Timeout</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-portable-windows-devices/"><u>Five Portable Windows Devices</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/focused-growth-instagrams-must-use-tags-to-watch-out-for-for-2024/"><u>Focused Growth  Instagram's Must-Use Tags to Watch Out For for 2024</u></a></li>
<li><a href="https://driver-download.techidaily.com/free-downloads-logitech-steering-wheel-g29-driver-for-windows-1087-users/"><u>Free Downloads: Logitech Steering Wheel G29 Driver for Windows 10/8/7 Users</u></a></li>
<li><a href="https://network-issues.techidaily.com/gpu-limitation-in-overwatch-cleared-update-completed/"><u>GPU Limitation in Overwatch Cleared, Update Completed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-add-a-check-for-updates-context-menu-option-in-windows-11-and-11/"><u>How to Add a Check for Updates Context Menu Option in Windows 11 and 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-realme-gt-5-240w-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>How to Cast Realme GT 5 (240W) Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-your-ethernet-speed-capped-at-100mbps-on-windows/"><u>How to Fix Your Ethernet Speed Capped at 100Mbps on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-regain-file-viewing-rights-on-your-pc/"><u>How to Regain File Viewing Rights on Your PC</u></a></li>
<li><a href="https://media-tips.techidaily.com/how-to-transform-mpeg-files-into-mp3s-a-guide-to-retrieving-pure-audio/"><u>How to Transform MPEG Files Into MP3s: A Guide to Retrieving Pure Audio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-and-fixing-windows-headset-mic-glitches/"><u>Identifying & Fixing Windows Headset Mic Glitches</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-easy-ways-to-copy-contacts-from-motorola-g24-power-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Easy Ways to Copy Contacts from Motorola G24 Power to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-automating-the-creation-of-youtube-subscriber-links/"><u>In 2024, Automating the Creation of YouTube Subscriber Links</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-foundation-principles-of-tale-telling/"><u>In 2024, Foundation Principles of Tale-Telling</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-navigating-to-superior-websites-for-tamil-ringtone-saves/"><u>In 2024, Navigating to Superior Websites for Tamil Ringtone Saves</u></a></li>
<li><a href="https://extra-skills.techidaily.com/inside-kinemaster-the-ultimate-guide-to-its-android-avatar-for-2024/"><u>Inside KineMaster  The Ultimate Guide to Its Android Avatar for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-windows-tech-for-premium-macos-experience/"><u>Integrating Windows Tech for Premium macOS Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lightning-fast-virtual-machines-on-windows-heres-how/"><u>Lightning-Fast Virtual Machines on Windows - Here's How</u></a></li>
<li><a href="https://win11-tips.techidaily.com/locate-windows-picture-cache-point/"><u>Locate Window’s Picture Cache Point</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-computers-sound-output-on-windows-with-updated-drivers/"><u>Master Your Computer's Sound Output on Windows with Updated Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-device-conflict-multiple-ms-logins/"><u>Mastering Device Conflict: Multiple MS Logins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-gaps-between-explore-elements/"><u>Mending Gaps Between Explore Elements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-automatic-shutdowns-in-windows-11-os/"><u>Mitigating Automatic Shutdowns in Windows 11 OS</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-the-best-free-video-editing-software-for-mp4-files-updated/"><u>New 2024 Approved The Best Free Video Editing Software for MP4 Files (Updated)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-disk-read-issue-in-windows/"><u>Overcoming Disk Read Issue in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-low-valorant-download-rate-woes-in-windows/"><u>Overcoming Low Valorant Download Rate Woes in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-the-looks-like-youre-stranded-from-xbox-app-windows/"><u>Removing the 'Looks Like You're Stranded' From Xbox App Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safe-haven-10-secure-sites-for-windows-free-apps/"><u>Safe Haven: 10 Secure Sites for Windows FREE Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-windows-11-photos-experience-with-slide-shows-and-image-spot-repair/"><u>Streamline Your Windows 11 Photos Experience with Slide Shows & Image Spot Repair</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-fixing-the-to-do-syncheroom-dilemma/"><u>Swiftly Fixing the To Do Syncheroom Dilemma</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-realign-windows-desktop-elements/"><u>Swiftly Realign Windows Desktop Elements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tap-into-a-world-of-innovation-with-ms-store-apps/"><u>Tap Into a World of Innovation with MS Store Apps</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-evolution-of-portability-tracing-the-origins-and-development-of-laptops/"><u>The Evolution of Portability: Tracing the Origins and Development of Laptops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-pathway-to-easier-network-management-windows-guide/"><u>The Pathway to Easier Network Management: Windows Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-quick-and-easy-route-to-your-pcs-credential-vault-on-win11/"><u>The Quick and Easy Route to Your PC's Credential Vault on Win11</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-ultimate-guide-to-baking-your-imagination-into-reality-with-a-cocoapress-3d-printer/"><u>The Ultimate Guide to Baking Your Imagination Into Reality with a CocoaPress 3D Printer</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-4-ways-to-trace-itel-p55t-location-drfone-by-drfone-virtual-android/"><u>Top 4 Ways to Trace Itel P55T Location | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/top-hits-on-reddit-a-compilation-of-the-best-ten-for-2024/"><u>Top Hits on Reddit - A Compilation of the Best Ten for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-for-smooth-captions-essential-tips-on-windows-10/"><u>Troubleshoot for Smooth Captions: Essential Tips on Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-0xc000003e-application-launch-failure-on-windows-11/"><u>Troubleshooting 0xC000003E Application Launch Failure on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turn-off-windows-monitoring-for-opened-apps/"><u>Turn Off Windows Monitoring for Opened Apps</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/video-editors-toolkit-10-must-have-software/"><u>Video Editors Toolkit 10 Must-Have Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-pagefilesys-in-windows-should-you-delete-it/"><u>What Is Pagefile.sys in Windows? Should You Delete It?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-edge-removal-made-simple/"><u>Win11 Edge Removal Made Simple</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-against-ps4-input-drop-outs-on-personal-computers/"><u>Winning Against PS4 Input Drop-Outs on Personal Computers</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>