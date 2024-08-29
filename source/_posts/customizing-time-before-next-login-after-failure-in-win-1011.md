---
title: Customizing Time Before Next Login After Failure in Win 10/11
date: 2024-08-28T01:13:27.512Z
updated: 2024-08-29T01:13:27.512Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Customizing Time Before Next Login After Failure in Win 10/11
excerpt: This Article Describes Customizing Time Before Next Login After Failure in Win 10/11
keywords: Windows Login Customization,Timeout Settings Win 10,Win10 Session Limit Adjustment,Login Delay Mechanism Win11,Preventing Repeated Login Failure,User-Defined Login Timelimit,Secure Windows Login Retry Policy
thumbnail: https://thmb.techidaily.com/c44b3c2a949ed90a1a74d6b8f5c0458cbf8a943f8d64ce0fc757b91844bd2888.jpg
---

## Customizing Time Before Next Login After Failure in Win 10/11

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

## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.
4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-discover-the-leading-apps-for-instagrams-vertical-igtv-edits/"><u>[New] 2024 Approved  Discover the Leading Apps for Instagram's Vertical IGTV Edits</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-essential-tips-for-a-novice-using-facebook-analytics/"><u>[New] 2024 Approved  Essential Tips for a Novice Using Facebook Analytics</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-elevate-engagement-todays-must-use-instagram-hashtags/"><u>[New] In 2024, Elevate Engagement  Today's Must-Use Instagram Hashtags</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-photo-perfection-in-a-pinch-with-top-apps/"><u>[New] In 2024, Photo Perfection in a Pinch with Top Apps</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-detailed-look-logitechs-elite-4k-webcam-review-for-2024/"><u>[Updated] Detailed Look  Logitech’s Elite 4K Webcam Review for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-quick-guide-on-converting-videos-into-dynamic-gifs-online/"><u>2024 Approved  Quick Guide on Converting Videos Into Dynamic Gifs Online</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/7-ways-to-unlock-a-locked-nokia-c300-phone-by-drfone-android/"><u>7 Ways to Unlock a Locked Nokia C300 Phone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-computer-chronology-windows-edition/"><u>Deciphering Computer Chronology - Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enlightening-on-high-fidelity-window-images/"><u>Enlightening on High-Fidelity Window Images</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/evga-classified-x670e-the-ultra-premium-amd-motherboard-hits-the-market/"><u>EVGA Classified X670E: The Ultra-Premium AMD Motherboard Hits the Market</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-track-your-windows-ssd-with-win-plus-ssfresh-techniques/"><u>Fast-Track Your Windows SSD with Win + SSFresh Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-geforce-now-glitch-xc0f1103f-in-win-1011-oses/"><u>Fixing GeForce Now Glitch XC0F1103F in Win 10/11 OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-default-search-window-action-windows-11-guide/"><u>Halt Default Search Window Action, Windows 11 Guide</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-iphone-6s-plus-camera-roll-photos-and-photo-stream-pictures-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Recover Deleted iPhone 6s Plus Camera Roll Photos and Photo Stream Pictures? | Stellar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-regain-superuser-status-in-windows-terminal/"><u>How to Regain Superuser Status in Windows Terminal</u></a></li>
<li><a href="https://hardware-help.techidaily.com/hp-printer-driver-installation-guide-and-download-options/"><u>HP Printer Driver Installation Guide and Download Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immerse-yourself-in-a-three-dimensional-audio-world-on-windows-11/"><u>Immerse Yourself in a Three-Dimensional Audio World on Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-can-you-transfer-files-from-honor-x9b-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How Can You Transfer Files From Honor X9b To iPhone 15/14/13? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/intels-unison-and-microsofts-phone-link-for-wp-which-is-better/"><u>Intel's Unison and Microsoft's Phone Link for WP: Which Is Better?</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/jumpstart-your-win11-experience-with-a-pro-upgrade/"><u>Jumpstart Your Win11 Experience with a Pro Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-windows-canary-channel-basics/"><u>Navigating the Windows Canary Channel Basics</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/navigating-the-world-of-digital-sound-capture-a-deep-dive-for-2024/"><u>Navigating the World of Digital Sound Capture  A Deep Dive for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/push-beyond-the-limits-yuzu-emulator-speed/"><u>Push Beyond the Limits: Yuzu Emulator Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reigniting-your-computers-print-functionality-with-effective-wwin-solutions/"><u>Reigniting Your Computer's Print Functionality with Effective WWin Solutions.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-nvidia-display-issue-in-control-panel/"><u>Resolving Nvidia Display Issue in Control Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-scanning-condensed-viewing-for-file-finder/"><u>Simplified Scanning: Condensed Viewing for File Finder</u></a></li>
<li><a href="https://win11-tips.techidaily.com/smooth-sailing-from-noisy-error-0xc00d36b4-in-win1011/"><u>Smooth Sailing From Noisy Error 0XC00D36B4 in Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-ease-through-the-waiting-gpsvc/"><u>Strategies to Ease Through the Waiting GPSVC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-windows-navigation-for-iis-management-space/"><u>Swift Windows Navigation for IIS Management Space</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-repairing-iomap64-syscall-issues-on-windows-devices/"><u>Tips for Repairing IOMap64 SysCall Issues on Windows Devices</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/ultimate-8-linux-cutting-solutions/"><u>Ultimate 8 Linux Cutting Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-steps-to-engage-wordpad-in-win-os/"><u>Unveiling the Steps to Engage WordPad in Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-10-fix-overcoming-null-audio-device-problems/"><u>Win 10 Fix: Overcoming Null Audio Device Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-over-local-device-naming-problems-on-windows-pcs/"><u>Winning Over Local Device Naming Problems on Windows PCs</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>