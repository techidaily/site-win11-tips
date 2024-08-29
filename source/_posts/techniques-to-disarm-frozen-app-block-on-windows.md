---
title: Techniques to Disarm Frozen App Block on Windows
date: 2024-08-28T01:12:18.282Z
updated: 2024-08-29T01:12:18.282Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques to Disarm Frozen App Block on Windows
excerpt: This Article Describes Techniques to Disarm Frozen App Block on Windows
keywords: Windows Freeze Fix,Unblock Frozen Apps,Bypass Frosty Windows,Stop App Blocking PC,De-Ice Windows Programs,Thaw Frozen Windows UI,Eliminate FrozApp Halt
thumbnail: https://thmb.techidaily.com/37cbd79bb1dc4f01076609d4f2040fc4f61e96fa43faa2585a2bbac8dade3639.jpg
---

## Techniques to Disarm Frozen App Block on Windows

 While Windows is designed to keep your computer secure, sometimes it can be overly zealous in its protection and block an app you know is safe. If you’re seeing the “This app has been blocked for your protection” error on Windows, your system has restricted the application from running for security reasons. This article clarifies the reasons behind the problem and guides you toward resolving it.

## 1\. Restart Your Computer

 When you experience the “This app has been blocked for your protection” error, the first step is to restart your computer. A simple reboot can often do the trick and allow you run a previously blocked application.

 If you don’t experience the error after rebooting, then it is likely a temporary glitch on Windows.

## 2\. Scan for Malicious Programs

 If restarting your computer doesn’t work, the next step is to run a full antivirus scan on your system. Chances are that the application is blocked due to a virus, malware or another malicious program.

 To be sure it's not the case, check whether a file is infected with a virus. If you find one, [scan your computer for viruses](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) and remove them.

 If you prefer command line tools, you can [scan and remove malicious components using Windows PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/). You should also use a [reputable anti-spyware program](https://www.makeuseof.com/windows-11-antivirus-apps/) to check for malicious programs that could be causing the error.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Run the Program as an Administrator

 Some programs require administrator privileges to function properly. If you try to launch them without elevated access, Windows will block their execution and display the error message. In such a case, you can right-click on the app’s shortcut or the executable file and select **Run as administrator**.

 If it runs successfully, you can adjust the app properties to [always run as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/). Don't forget to save the changes.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Disable the SmartScreen Filter

 SmartScreen is a security feature that protects your computer from unknown and potentially malicious applications. If it’s enabled, SmartScreen may block an application from running. To disable the feature, follow these steps.

1. Open the **Start** menu and search for _Windows Security_.
2. Click on **Windows Security** in the search results.
3. In the Windows Security app, select **App & browser control**.
4. On the right side of the window, click **Reputation-based protection settings**.  
![Disable the SmartScreen Filter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-the-smartscreen-filter.jpg)
5. Toggle off **Potentially unwanted app blocking** and **SmartScreen for Microsoft Store apps**.

 This will stop the system from blocking apps, but you should be careful with any programs you download. Once you do it, close the Windows Security app and try running the application again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 5\. Modify the Group Policy Settings

 The group policy editor allows you to adjust security settings on Windows and control which applications are blocked. If the other steps didn’t work, you can try to modify the group policy settings and unblock the application that triggered the error. Here's how to do it:

1. Press **Win + X** on your keyboard and select **Run** from the menu list.
2. Type **gpedit.msc** and press Enter to open the Local Group Policy Editor.  
![User Account Control Run all administrators in Admin Approval Mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/user-account-control-run-all-administrators-in-admin-approval-mode.jpg)
3. Once you're in the Local Group Policy Editor window, navigate to the following:  
`Local Computer Policy > Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options.`
4. From the list of settings, double-click on **User Account Control: Run all administrators in Admin Approval Mode** and set it to **Disabled**.
5. After making the changes, click **Apply > OK** and restart your computer to apply it.

 Keep in mind that modifying group policy settings can leave your computer vulnerable to malicious applications. Therefore, you should only do it as a last resort and revert the change as soon as you’re done.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Tweak the Registry Editor

 If you're running Windows Home edition, you can tweak the Registry Editor to adjust the User Account Control settings and unblock the application. Here's what you need to do:

1. [Open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** and press Enter to open the Registry Editor window.
3. If UAC prompts you for permission, click **Yes**.
4. Navigate to the following key location.  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System`
5. In the right pane, double-click on **EnableLUA** and set its value to **0** (zero).  
![Disable the EnableLUA key in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-the-enablelua-key-in-registry-editor.jpg)
6. Click **OK** to save the changes.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->

 After making the changes, close the Registry Editor and restart your computer.

## 7\. Reset Windows Update Components

 If the issue persists, you can reset the Windows Update components, which means restarting certain services that manage the update process and enable you to launch the application.

 To reset Windows Update components, do the following:

1. Click on Start and search for **Notepad**.
2. Right-click on the Notepad icon and select **Run as administrator**.
3. Copy and paste the following code into Notepad:  
`<code>net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc  
Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"  
rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%  
system32\catroot2 /S /Q  
sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
cd /d %windir%  
system32  
regsvr32.exe /s atl.dll  
regsvr32.exe /s urlmon.dll  
regsvr32.exe /s mshtml.dll  
regsvr32.exe /s shdocvw.dll  
regsvr32.exe /s browseui.dll  
regsvr32.exe /s jscript.dll  
regsvr32.exe /s vbscript.dll  
regsvr32.exe /s scrrun.dll  
regsvr32.exe /s msxml.dll  
regsvr32.exe /s msxml3.dll  
regsvr32.exe /s msxml6.dll  
regsvr32.exe /s actxprxy.dll  
regsvr32.exe /s softpub.dll  
regsvr32.exe /s wintrust.dll  
regsvr32.exe /s dssenh.dll  
regsvr32.exe /s rsaenh.dll  
regsvr32.exe /s gpkcsp.dll  
regsvr32.exe /s sccbase.dll  
regsvr32.exe /s slbcsp.dll  
regsvr32.exe /s cryptdlg.dll  
regsvr32.exe /s oleaut32.dll  
regsvr32.exe /s ole32.dll  
regsvr32.exe /s shell32.dll  
regsvr32.exe /s initpki.dll  
regsvr32.exe /s wuapi.dll  
regsvr32.exe /s wuaueng.dll  
regsvr32.exe /s wuaueng1.dll  
regsvr32.exe /s wucltui.dll  
regsvr32.exe /s wups.dll  
regsvr32.exe /s wups2.dll  
regsvr32.exe /s wuweb.dll  
regsvr32.exe /s qmgr.dll  
regsvr32.exe /s qmgrprxy.dll  
regsvr32.exe /s wucltux.dll  
regsvr32.exe /s muweb.dll  
regsvr32.exe /s wuwebv.dll  
netsh winsock reset  
netsh winsock reset proxy  
net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`
4. Now click **File** in the top left corner.
5. Then select **Save as** from the options list.
6. In the Save as window, name your script **Reset.bat** and set the Save as type to **All Files**.
7. Select **Desktop** from the left menu and click **Save**.
8. Double-click on the **Reset.bat** file to run it as an administrator.
9. If the UAC window pops up on the screen, click **Yes** to continue.

 Wait for the process to finish and restart your computer. After the reboot, try running the blocked app again. It should now work without issues.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get Access to Your Apps and Files on Windows

 Windows is known for its tight security which prevents malicious applications from launching and infecting your PC. However, sometimes even legitimate programs are blocked by the operating system and leave an error message saying “This app has been blocked for your protection.”

 There are several reasons why this error occurs. It includes outdated security software, the firewall interfering with the program, or the application not trusted by Windows. Read this guide to learn more about this error.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-shortcuts-to-turn-off-instagrams-igtv/"><u>[New] 2024 Approved  Shortcuts to Turn Off Instagram's IGTV</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-unseen-marvels-of-vr-elite-headset-comparisons-for-2024/"><u>[New] Unseen Marvels of VR  Elite Headset Comparisons for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-capturecrafter-your-ultimate-guide-to-screen-recording/"><u>[Updated] 2024 Approved  CaptureCrafter  Your Ultimate Guide to Screen Recording</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-your-journey-to-stylish-vlogging-a-beginners-guide-mac-edition/"><u>[Updated] Your Journey to Stylish Vlogging  A Beginner's Guide, Mac Edition</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/android-users-handbook-how-to-temporarily-disable-facebook-without-losing-data/"><u>Android Users' Handbook: How To Temporarily Disable Facebook Without Losing Data</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/broadcast-battleground-which-wins-obs-or-twitch/"><u>Broadcast Battleground  Which Wins, OBS or Twitch?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-editing-the-8-pinnacle-software-titles-for-windows-users/"><u>Conquer Editing: The 8 Pinnacle Software Titles for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-video-quality-chrome-and-youtube-optimization/"><u>Elevating Video Quality: Chrome and YouTube Optimization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-user-interface-widgets-for-windows-11/"><u>Enabling User Interface Widgets for Windows 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/everything-you-need-to-know-about-lock-screen-settings-on-your-samsung-galaxy-a14-4g-by-drfone-android/"><u>Everything You Need to Know about Lock Screen Settings on your Samsung Galaxy A14 4G</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/expert-picks-the-10-most-affordable-video-conferencing-for-ios-and-android/"><u>Expert Picks  The 10 Most Affordable Video Conferencing for iOS & Android</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/expert-tips-to-fix-the-persistent-cmos-checksum-discrepancy/"><u>Expert Tips to Fix the Persistent CMOS Checksum Discrepancy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-wows-catastrophic-glitch-in-windows-11/"><u>Fixing WoW’s Catastrophic Glitch in Windows 11</u></a></li>
<li><a href="https://win-solutions.techidaily.com/how-to-address-continuous-audio-on-frozen-youtube-videos-in-web-browsers-chrome-and-firefox-guide/"><u>How to Address Continuous Audio on Frozen YouTube Videos in Web Browsers: Chrome and Firefox Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-identify-must-have-components-in-a-gamers-dream-pc-setup/"><u>How to Identify Must-Have Components in a Gamer's Dream PC Setup</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/how-to-live-stream-facebook-from-pc-mac-or-laptop-with-obs-for-2024/"><u>How to Live Stream Facebook From PC, Mac or Laptop with OBS for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-regain-superuser-status-in-windows-terminal/"><u>How to Regain Superuser Status in Windows Terminal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immerse-yourself-in-a-three-dimensional-audio-world-on-windows-11/"><u>Immerse Yourself in a Three-Dimensional Audio World on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/inside-the-role-of-ai-in-microsofts-store/"><u>Inside: The Role of AI in Microsoft's Store</u></a></li>
<li><a href="https://win-dash.techidaily.com/latest-msi-z370-a-pro-driver-software-available-now-free/"><u>Latest MSI Z370-A Pro Driver Software Available Now – Free</u></a></li>
<li><a href="https://video-capture.techidaily.com/leading-webinar-solutions-explored-for-2024/"><u>Leading Webinar Solutions Explored for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-multiplayer-tactics-a-guide-to-team-up-hunts-in-monster-hunter-world/"><u>Mastering Multiplayer Tactics: A Guide to Team-Up Hunts in Monster Hunter World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-your-efficiency-with-concurrent-subfolder-creation-on-windows-pcs/"><u>Maximize Your Efficiency with Concurrent Subfolder Creation on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-productivity-with-reimagined-windows-11-widgets/"><u>Maximizing Productivity with Reimagined Windows 11 Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mkv-mp4-conversion-steps-for-windows-users/"><u>MKV-MP4 Conversion Steps for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-windows-canary-channel-basics/"><u>Navigating the Windows Canary Channel Basics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-experience-outlook-preview-for-windows-11-enthusiasts/"><u>Optimize Your Experience: Outlook Preview for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-disconnecting-woes-essential-fixes-for-windows-usb-wifi/"><u>Overcome Disconnecting Woes – Essential Fixes for Windows USB Wifi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-share-denial-in-microsoft-os/"><u>Overcome Share Denial in Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-insufficient-computer-specifications-intel-graphic-challenges/"><u>Overcoming Insufficient Computer Specifications: Intel Graphic Challenges</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-establishing-ethernet-connectivity-on-windows/"><u>Re-Establishing Ethernet Connectivity on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-default-view-configurations-in-windows/"><u>Reinstating Default View Configurations in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-non-transferring-usb-cases-in-the-windows-environment/"><u>Remedying Non-Transferring USB Cases in the Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrecting-your-invisible-connection-on-microsofts-new-os/"><u>Resurrecting Your Invisible Connection on Microsoft's New OS</u></a></li>
<li><a href="https://sound-issues.techidaily.com/revive-your-skype-audio-repairing-microphone-problems-in-windows-10/"><u>Revive Your Skype Audio: Repairing Microphone Problems in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secrets-to-clean-up-and-free-your-pc-in-windows/"><u>Secrets to Clean Up and Free Your PC in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/smooth-sailing-from-noisy-error-0xc00d36b4-in-win1011/"><u>Smooth Sailing From Noisy Error 0XC00D36B4 in Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sneaky-storage-concealing-drives-on-windows-os/"><u>Sneaky Storage: Concealing Drives on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-the-missing-wireless-network-in-windows-11/"><u>Solutions for the Missing Wireless Network in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-fix-for-windows-error-0x80071a90/"><u>Step-by-Step Fix for Windows Error 0X80071A90</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-address-resource-already-in-use-on-windows-pcs-152-chars/"><u>Steps to Address Resource Already In Use on Windows PCs (152 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-11-login-processes/"><u>Streamlining Windows 11 Login Processes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-windows-navigation-for-iis-management-space/"><u>Swift Windows Navigation for IIS Management Space</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-optimizing-phone-as-window-recording-device/"><u>Techniques for Optimizing Phone as Window Recording Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-blocking-insecure-device-connections-on-windows/"><u>Tips for Blocking Insecure Device Connections on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-fixing-drivers-that-wont-load-in-win11/"><u>Tips for Fixing Drivers that Won't Load in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-and-tailor-image-dimensions-with-these-key-steps-in-windows-11/"><u>Transform and Tailor Image Dimensions with These Key Steps in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-vlc-file-not-accepted-windows-error/"><u>Troubleshooting VLC File Not Accepted Windows Error</u></a></li>
<li><a href="https://change-location.techidaily.com/ultimate-guide-to-catch-the-regional-located-pokemon-for-samsung-galaxy-s24-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Catch the Regional-Located Pokemon For Samsung Galaxy S24 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncover-the-secrets-to-flawless-subtitle-display-on-windows-11/"><u>Uncover the Secrets to Flawless Subtitle Display on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/undoing-greyed-out-bin-fixes-on-win11/"><u>Undoing Greyed Out Bin Fixes on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unifying-your-windows-serial-with-ms-accounts/"><u>Unifying Your Windows Serial with MS Accounts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-productivity-with-w11s-quick-actions/"><u>Unleash Productivity with W11's Quick Actions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-over-local-device-naming-problems-on-windows-pcs/"><u>Winning Over Local Device Naming Problems on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/your-gateway-to-epic-victories-playing-games-on-windows/"><u>Your Gateway to Epic Victories: Playing Games on Windows</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>