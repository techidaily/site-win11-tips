---
title: How to Change Lockout Duration After Failed Logon Attempts in Windows 11 and 11
date: 2024-08-16T02:07:13.590Z
updated: 2024-08-17T02:07:13.590Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Change Lockout Duration After Failed Logon Attempts in Windows 11 and 11
excerpt: This Article Describes How to Change Lockout Duration After Failed Logon Attempts in Windows 11 and 11
keywords: Windows Lockout Management,Extend Lockout Time,Change Login Delay,Reset Failed Logon Timer,Adjust Windows Security Duration,Increase Lockout Interval,Modify Login Lockout Time
thumbnail: https://thmb.techidaily.com/8979e8080587e2a8dc2c43407031e5a8747618e7ac4eca2f3b40cffb1bdf15c9.jpg
---

## How to Change Lockout Duration After Failed Logon Attempts in Windows 11 and 11

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  
![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  
![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
3. This will pull up information, among other things, about how long this account lockout duration is currently set.
4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-tips.techidaily.com/new-compiling-the-best-12-cost-free-video-apps-for-all-platforms/"><u>[New] Compiling the Best 12 Cost-Free Video Apps for All Platforms</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-clear-black-boards-in-your-youtube-videos-in-2024/"><u>[New] How to Clear Black Boards in Your YouTube Videos, In 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-the-10-steps-to-crafting-captivating-and-click-worthy-snap-ads/"><u>[New] In 2024, The 10 Steps to Crafting Captivating & Click-Worthy Snap Ads</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-upgrade-video-experience-activate-av1-on-youtube/"><u>[New] Upgrade Video Experience  Activate AV1 on YouTube</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-view-count-rewards-on-youtube-per-million/"><u>[New] View Count Rewards on YouTube – Per Million?</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-unleashing-the-power-of-online-cricket-broadcasts/"><u>[Updated] 2024 Approved  Unleashing the Power of Online Cricket Broadcasts</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-craft-engaging-youtube-stays-strategies-to-shine-without-thousand-supporters/"><u>[Updated] Craft Engaging YouTube Stays  Strategies to Shine without Thousand Supporters</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-in-depth-guide-to-full-transcription-and-archiving-of-fb-messages/"><u>[Updated] In 2024, In-Depth Guide to Full Transcription & Archiving of FB Messages</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-live-transmission-directly-to-instagram-via-obs/"><u>[Updated] Live Transmission Directly to Instagram via OBS</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-smart-solutions-apply-apple-watch-open-mac/"><u>[Updated] Smart Solutions  Apply Apple Watch, Open Mac</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-top-picks-in-affordable-home-cinema-setups-with-4k/"><u>[Updated] Top Picks in Affordable Home Cinema Setups with 4K</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-path-to-polished-projects-utilizing-fades-effectively/"><u>2024 Approved  The Path to Polished Projects  Utilizing Fades Effectively</u></a></li>
<li><a href="https://ai-video.techidaily.com/2024-approved-top-9-choices-for-video-auto-translate/"><u>2024 Approved Top 9 Choices for Video Auto Translate</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-the-windows-11-crash-code-errors/"><u>Clearing Up the Windows 11 Crash Code Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detailed-walkthrough-of-locating-and-using-component-services/"><u>Detailed Walkthrough of Locating and Using Component Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/direct-linking-dualshock-3-with-windows-gamepad/"><u>Direct Linking: DualShock 3 with Windows Gamepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-steps-to-customize-the-windows-11-tablet-bar-settings/"><u>Easy Steps to Customize the Windows 11 Tablet Bar Settings</u></a></li>
<li><a href="https://extra-information.techidaily.com/effortless-access-to-public-broadcast-c-span-videos/"><u>Effortless Access to Public Broadcast C-Span Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-pointer-accessibility-simple-steps-for-windows-users/"><u>Elevating Pointer Accessibility: Simple Steps for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-mouse-features-10-easy-steps-in-win11/"><u>Explore Mouse Features: 10 Easy Steps in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fine-tune-your-pcs-performance-avoiding-sudden-updates-on-windows-11/"><u>Fine-Tune Your PC's Performance: Avoiding Sudden Updates on Windows 11</u></a></li>
<li><a href="https://win-solutions.techidaily.com/fixing-issues-with-zombies-army-4-dead-war-pc-collision/"><u>Fixing Issues with Zombies, Army 4: Dead War PC Collision</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/free-avi-video-rotation-16-top-picks-for-windows-mac-android-iphone-and-online-platforms-for-2024/"><u>Free AVI Video Rotation 16 Top Picks for Windows, MAC, Android, iPhone, and Online Platforms for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-to-grips-with-powertoys-plain-text-methods/"><u>Get to Grips With PowerToys' Plain Text Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-rectify-non-signed-updates-in-w11w10/"><u>Guide to Rectify Non-Signed Updates in W11/W10</u></a></li>
<li><a href="https://change-location.techidaily.com/here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-vivo-v29-pro-drfone-by-drfone-virtual-android/"><u>Here are Some Pro Tips for Pokemon Go PvP Battles On Vivo V29 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-address-the-invalid-token-access-error-on-win10/"><u>How To Address the “Invalid Token Access” Error on Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-disassociate-onedrive-from-microsoft-account-in-windows/"><u>How to Disassociate OneDrive From Microsoft Account in Windows</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-samsung-galaxy-a25-5g-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Samsung Galaxy A25 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-initiate-a-fresh-start-in-windows-11/"><u>How to Initiate a Fresh Start in Windows 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-reset-the-security-questions-of-your-apple-id-on-your-apple-iphone-x-by-drfone-ios/"><u>How To Reset the Security Questions of Your Apple ID On Your Apple iPhone X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-recurring-image-importer-errors-with-ios-devices-on-w11/"><u>How to Resolve Recurring Image Importer Errors with iOS Devices on W11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-xiaomi-redmi-k70e-phone-without-any-data-loss-by-drfone-android/"><u>How to Unlock Xiaomi Redmi K70E Phone without Any Data Loss</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-update-the-dynamic-theme-on-windows-regularly/"><u>How to Update the Dynamic Theme on Windows Regularly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-fixes-for-lost-renderer-issue-in-ow2-on-windows/"><u>Immediate Fixes for Lost Renderer Issue in OW2 on Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-samsung-galaxy-xcover-7-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Samsung Galaxy XCover 7 Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-superior-smartphones-that-dominate-in-video-recording/"><u>In 2024, Superior Smartphones That Dominate in Video Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-in-minutes-unveil-the-windows-machine-you-use/"><u>Mastery in Minutes: Unveil the Windows Machine You Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/migrating-your-torrent-tracking-moving-qbittorrent-efficiently/"><u>Migrating Your Torrent Tracking: Moving qBittorrent Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/next-gen-windows-os-crafted-with-artificial-intelligence/"><u>Next-Gen Windows OS Crafted with Artificial Intelligence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-edge-browser-view2-memory-glitches/"><u>Overcoming Edge Browser: View2 Memory Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precision-guide-for-heic-to-jpeg-transformation-in-w11/"><u>Precision Guide for Heic to JPEG Transformation in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-anydesk-quirks-for-a-smooth-windows-experience/"><u>Resolving AnyDesk Quirks for a Smooth Windows Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-interruptexception-errors-in-windows-os/"><u>Resolving INTERRUPT_EXCEPTION Errors in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-error-how-to-retrieve-lost-geforce-x-configurations/"><u>Reversing Error: How to Retrieve Lost GeForce X Configurations</u></a></li>
<li><a href="https://some-approaches.techidaily.com/streamline-content-creation-leading-after-effects-plugins-for-2024/"><u>Streamline Content Creation  Leading After Effects Plugins for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-windows-11-photos-the-top-6-rescaling-methods/"><u>Transform Your Windows 11 Photos – The Top 6 Rescaling Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-usb-not-attached-error-in-virtualbox-on-windows-platform/"><u>Troubleshooting 'USB Not Attached' Error in VirtualBox on Windows Platform</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshooting-guide-resolving-iphone-personal-hotspot-issues/"><u>Troubleshooting Guide: Resolving iPhone Personal Hotspot Issues</u></a></li>
</ul></div>
