---
title: "Undo Customization: Reverting Win11 User Permissions"
date: 2024-08-16T02:34:33.179Z
updated: 2024-08-17T02:34:33.179Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Undo Customization: Reverting Win11 User Permissions"
excerpt: "This Article Describes Undo Customization: Reverting Win11 User Permissions"
keywords: Win11 RevPerms Undo,Win11 User Backtrack,Permissions Win11 Unlock,Windows 11 Revert Perms,Win11 Privilege Restore,Win11 Access Reset,Win11 Rights Reverse
thumbnail: https://thmb.techidaily.com/e874e7774ed1bae47e14908261fcbf31de304eed1c8fec16cc5f931b201e9fca.jpg
---

## Undo Customization: Reverting Win11 User Permissions

 Having issues with apps or programs not running properly on your Windows computer? Resetting Windows Update permissions could be the solution you need. Similarly, if you're troubleshooting user profile problems, you can restore user permissions.

 This article covers three different methods to reset all user permissions – using the Icacls command, the Secedit command, and the Subinacl tool.

Let's now explore them in detail.

## 1\. Run the Icacls Command

 The Icacls command allows you to view, modify, and reset file system permissions on files and folders. To reset Windows Update permissions using this command, you will first have to[take ownership of the folders on Windows](https://www.makeuseof.com/windows-10-11-own-folder/) . Then[open an elevated Command Prompt on Windows](https://www.makeuseof.com/windows-run-command-prompt-admin/) and type in the following command:

`icacls * /t /q /c /reset`

 Now press Enter on your keyboard to execute the command. This will reset all user permissions to default for every folder, subfolder, and file within the current working directory.

In the above command, here are the parameters explained:

* \* – This is a wildcard character that includes all folders within the current directory.
* /t – It targets all the subfolders and files within the current folder.
* /q – Run command without displaying success messages.
* /c – Continues the operation even if errors occur.
* /reset – This parameter resets the permission options to their default values.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Run the Secedit command

 Windows provides the Secedit command to configure and analyze system security. To reset all user permissions using this command, run the command prompt with admin access, then type in the following command:

![Run the Secedit command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-the-secedit-command.jpg)

`secedit /configure /cfg %windir%\inf\defltbase.inf /db defltbase.sdb /verbose`

 Now press Enter to execute the command. Wait for the process to finish and restart your computer. This will reset the user permissions to the default system settings.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## 3\. Run the Subinacl Tool

 If you're not comfortable using the command prompt, you may use the Subinacl tool. This is a command-line utility from Microsoft that can be used to reset user permissions. Here's how to do it:

1. [Download the Subinacl tool from Microsoft's webpage](https://web.archive.org/web/20190830103837/http://www.microsoft.com/en-us/download/confirmation.aspx?id=23510) . When you open the page, the download starts automatically. If not, wait 30 seconds and click the link.
2. Once downloaded, double-click on the installer package. This will open the installation wizard.  
![Open the installation wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-the-installation-wizard.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
3. Click on**Next** and then accept the license agreement terms.  
![Install the Subinacl tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-the-subinacl-tool.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
4. Next, copy and paste the following path into the Destination folder:  
`C:\Windows\System32`  
 Note: If you have installed Windows on a different drive, use that path instead.
5. Now click on**Install now** and wait for the Subinacl tool to be installed. This may take several minutes, so be patient.

1. When the installation is complete,[open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and type in the following commands:  
`subinacl /subkeyreg HKEY_LOCAL_MACHINE /grant=administrators=f  
subinacl /subkeyreg HKEY_CURRENT_USER /grant=administrators=f  
subinacl /subkeyreg HKEY_CLASSES_ROOT /grant=administrators=f  
subinacl /subdirectories %SystemDrive% /grant=administrators=f  
subinacl /subkeyreg HKEY_LOCAL_MACHINE /grant=system=f  
subinacl /subkeyreg HKEY_CURRENT_USER /grant=system=f  
subinacl /subkeyreg HKEY_CLASSES_ROOT /grant=system=f  
subinacl /subdirectories %SystemDrive% /grant=system=f`
2. On the Save As window, set the File name to**Reset.cmd** and then select**All Files** from the drop-down menu next to it.  
![Reset Windows Update permissions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-update-permissions.jpg)
<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
3. Next, select**Desktop** from the left pane and click on**Save** .
4. Now double-click on it to reset the user permissions to default.
5. This may take a while to complete the procedure, so wait for it to finish.

 Once done, close any running program, and then restart your computer. Your Windows Update permissions will be reset to their default settings. These are three different methods you can use to reset the user permission settings on Windows.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## Restore User Permissions to Default on Windows

 User permissions play a crucial role in computer security. If you're experiencing user permission issues, you must reset them to their default settings. This guide helps you reset all user permissions on Windows using three different methods. You can use the ICACLS command, Secedit command, or Subinacl tool, depending on your preference.


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
<li><a href="https://vp-tips.techidaily.com/new-in-2024-comprehensive-insights-streamlined-iphone-podcast-downloads/"><u>[New] In 2024, Comprehensive Insights  Streamlined iPhone Podcast Downloads</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-keeping-the-connection-strong-avoiding-livestream-interruptions-on-facebook-for-2024/"><u>[New] Keeping the Connection Strong  Avoiding Livestream Interruptions on Facebook for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-polaroid-camplus-cube-analysis-when-life-is-on-screen/"><u>[Updated] Polaroid Cam+ Cube Analysis  When Life Is on Screen</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-nostalgic-narratives-capturing-moments-with-xiphone/"><u>2024 Approved  Nostalgic Narratives  Capturing Moments with XiPhone</u></a></li>
<li><a href="https://howto.techidaily.com/6-fixes-to-unfortunately-whatsapp-has-stopped-error-popups-on-nokia-c110-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Fixes to Unfortunately WhatsApp has stopped Error Popups On Nokia C110 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-the-annoyance-of-a-never-ending-update-loop/"><u>Avoid the Annoyance of a Never-Ending Update Loop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensively-tackle-the-icloud-install-issue-on-windows/"><u>Comprehensively Tackle the iCloud Install Issue on Windows</u></a></li>
<li><a href="https://article-tips.techidaily.com/converging-music-and-imagery-online-for-2024/"><u>Converging Music and Imagery Online for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/everything-you-need-to-know-about-lock-screen-settings-on-your-itel-a60s-by-drfone-android/"><u>Everything You Need to Know about Lock Screen Settings on your Itel A60s</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explaining-the-red-x-its-role-in-file-system-navigation/"><u>Explaining the Red “X”: Its Role in File System Navigation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hidden-potential-utilize-hotkeys-to-control-windows-taskbar/"><u>Hidden Potential: Utilize Hotkeys to Control Windows Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hide-post-display-adjustment-in-windows-power-configuration/"><u>Hide Post-Display Adjustment in Windows Power Configuration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-master-windows-blue-screen-troubleshooting/"><u>How to Master Windows Blue Screen Troubleshooting</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-quickly-fix-bluetooth-not-working-on-infinix-note-30-vip-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Quickly Fix Bluetooth Not Working on Infinix Note 30 VIP | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-successfully-bypass-icloud-activation-lock-from-iphone-xs-max-by-drfone-ios/"><u>How to Successfully Bypass iCloud Activation Lock from iPhone XS Max</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-is-greyed-out-from-iphone-11-pro-max-how-to-bypass-by-drfone-ios/"><u>In 2024, Apple ID is Greyed Out From iPhone 11 Pro Max How to Bypass?</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-delete-gmail-account-withwithout-password-on-samsung-galaxy-f14-5g-by-drfone-android/"><u>In 2024, Delete Gmail Account With/Without Password On Samsung Galaxy F14 5G</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-do-you-get-sun-stone-evolutions-in-pokemon-for-oneplus-open-drfone-by-drfone-virtual-android/"><u>In 2024, How Do You Get Sun Stone Evolutions in Pokémon For OnePlus Open? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-learn-how-everything-works-on-xiaomi-13t-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Learn How Everything Works On Xiaomi 13T Pro | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-10-password-cracking-tools-for-tecno-spark-10-5g-by-drfone-android/"><u>In 2024, Top 10 Password Cracking Tools For Tecno Spark 10 5G</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-imei-unlokers-for-your-motorola-moto-g34-5g-phone-by-drfone-android/"><u>In 2024, Top IMEI Unlokers for Your Motorola Moto G34 5G Phone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-windows-apps-into-linux-world/"><u>Integrating Windows Apps Into Linux World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-windows-hello-recognition-work-again/"><u>Making Windows Hello Recognition Work Again</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-malware-discovery-without-software-assistance/"><u>Mastering Malware Discovery without Software Assistance</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-windows-functionality-through-knowledge-of-the-registry/"><u>Mastering Windows Functionality Through Knowledge of the Registry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-your-networks-security-keys-five-steps-towards-error-elimination-in-windows/"><u>Mastering Your Network's Security Keys: Five Steps Towards Error Elimination in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modern-standby-uncovering-its-defects-and-criticisms/"><u>Modern Standby: Uncovering Its Defects and Criticisms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-hidden-dangers-on-a-computer-screen/"><u>Navigating Hidden Dangers on a Computer Screen</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/navigating-name-change-in-google-meet-laptopmobile-for-2024/"><u>Navigating Name Change in Google Meet (Laptop/Mobile) for 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/overcoming-fatal-hurdles-easy-ways-to-stop-batman-arkham-knight-from-crashing-down/"><u>Overcoming Fatal Hurdles: Easy Ways to Stop Batman: Arkham Knight From Crashing Down</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-copypaste-anomalies/"><u>Overcoming Windows 11 Copy/Paste Anomalies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-and-easy-cures-for-your-computers-messaging-woes/"><u>Quick & Easy Cures for Your Computer's Messaging Woes</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-how-to-stop-your-pc-from-falling-asleep-unintentionally/"><u>Quick Fixes: How to Stop Your PC From Falling Asleep Unintentionally</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-resetting-graphics-drivers-on-latest-oses/"><u>Quick Guide to Resetting Graphics Drivers on Latest OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-establishing-windows-11-support-features/"><u>Re-Establishing Windows 11 Support Features</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-apple-iphone-se-drfone-by-drfone-virtual-ios/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Apple iPhone SE | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-old-password-needed-on-windows-11-errors/"><u>Remedy for 'Old Password Needed' On Windows 11 Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-your-windows-11-the-most-impactful-settings-to-modify/"><u>Revolutionize Your Windows 11: The Most Impactful Settings to Modify</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-to-streamline-your-windows-netconnection-access/"><u>Step-By Step to Streamline Your Windows NetConnection Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-talk-the-key-to-a-visible-mouse-indicator-in-windows-os/"><u>Tech Talk: The Key to a Visible Mouse Indicator in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-guide-to-engaging-windows-11s-calculator/"><u>The Essential Guide to Engaging Windows 11'S Calculator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/time-saving-techniques-for-a-functional-windows-time-service/"><u>Time-Saving Techniques for a Functional Windows Time Service</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-4-ways-to-trace-nokia-c22-location-drfone-by-drfone-virtual-android/"><u>Top 4 Ways to Trace Nokia C22 Location | Dr.fone</u></a></li>
<li><a href="https://article-helps.techidaily.com/top-5-methods-to-record-high-quality-audio-on-windows/"><u>Top 5 Methods to Record High-Quality Audio on Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-imei-unlokers-for-your-zte-blade-a73-5g-phone-by-drfone-android/"><u>Top IMEI Unlokers for Your ZTE Blade A73 5G Phone</u></a></li>
<li><a href="https://windows11.techidaily.com/1719359377017-unfreeze-shift-button-on-your-pc/"><u>Unfreeze Shift Button on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-mechanism-disabling-dim-display-option/"><u>Unveiling the Mechanism: Disabling 'Dim Display' Option</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windowing-wonderland-personalized-monitor-settings-in-win1011/"><u>Windowing Wonderland: Personalized Monitor Settings in Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-memory-assessment-made-easy/"><u>Windows Memory Assessment Made Easy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-newbies-guide-to-easier-access/"><u>Windows Newbies' Guide to Easier Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-ways-the-best-fixes-to-skip-the-long-wait-in-install-steps/"><u>Winning Ways: The Best Fixes to Skip the Long Wait in Install Steps</u></a></li>
</ul></div>
