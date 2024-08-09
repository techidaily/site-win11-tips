---
title: Removing 'Limited Administrator Power' From Security Issue
date: 2024-08-08T11:02:48.111Z
updated: 2024-08-09T11:02:48.111Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Removing 'Limited Administrator Power' From Security Issue
excerpt: This Article Describes Removing 'Limited Administrator Power' From Security Issue
keywords: Admin Power Removal,Limited Access Control,Security Permission Fix,Enhancing User Privileges,Disable Admin Limits,Secure Account Moderation,Restore Unlimited Authority
thumbnail: https://thmb.techidaily.com/b46dbabb50d5277c1ad28a5993cc958234753eefedba62d12174cf3ff84234d4.jpg
---

## Removing 'Limited Administrator Power' From Security Issue

 Some users have posted on troubleshooting forums about a “Page not available” error that occurs when they open Windows Security. The “Page not available” error message says, “Your IT Administrator has limited access to some areas of this app.” That error message appears within Windows Security, and users can’t access that app’s antivirus settings because of it.

 This error message suggests another administrative user has applied restrictions to Windows Security. However, it often arises on standalone PCs that aren’t connected to an organization network. This is how you can fix the “Your IT administrator has limited access” error.

## 1\. Change Your User Account to an Admin Account

 You shouldn’t usually need admin rights to access Windows Security. However, make sure you’re signed in to an admin account to ensure you have full system permissions. If you’re utilizing a standard account, change it to an administrator one. You can do that with one of the methods outlined in this guide to[changing user account type in Windows](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) .

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Access work or school account settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/work-or-school-accounts.jpg)

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
## 2\. Uninstall Third-Party Security Software

 Have you installed a third-party antivirus app on your PC? If so, that security software could be by conflicting with Microsoft Defender and causing the “Page not available” error. Try uninstalling the third-party antivirus utility you’ve installed with a method in our guide to[removing Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) . Or utilize a dedicated removal tool for your antivirus app if there’s one available.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/uninstall-option-3.jpg)

## 3\. Remove Any Work or School Accounts

 Have you connected your PC with any school or work organization account? If so, such an account could be restricting access to Windows Security settings. Try disconnecting your PC from the school or work in Settings as follows:

1. Bring up Settings and click that app’s**Accounts** tab (or category).
2. Scroll down to select the**Access work or school navigation** option.
3. Click a connected work or school account to expand it.  
![The Access work or school account settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/work-or-school-accounts.jpg)
4. Press the**Disconnect** button and select**Yes** .

## 4\. Disable the Turn Off Microsoft Defender Antivirus Policy

 Some Windows Pro and Enterprise users have confirmed they’ve fixed the “Page not available” error by disabling a**Turn off Microsoft Defender Antivirus** policy. So, check that policy setting even if you can’t recall changing it yourself. This is how you can check and disable the**Turn Off Microsoft Defender Antivirus** Group Policy setting in Windows Pro and Enterprise:

1. To access the file search box, hold the Windows logo key and press S.
2. Type**gpedit.msc** inside the file search box.
3. Double-click**gpedit.msc** to[open the Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) window.
4. Next, double-click**Computer Configuration** and**Administrative Templates** within Group Policy Editor’s sidebar.
5. Expand the**Windows Components** folder in the sidebar.

1. Click**Microsoft Defender Antivirus** to select that policy.  
![Microsoft Defender Antivirus settings in Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-defender-antivirus-settings.jpg)
2. Then double-click**Turn off Microsoft Defender Antivirus** .
3. Click**Disabled** if the**Turn off Microsoft Defender Antivirus** policy is enabled.  
![The Turn off Microsoft Defender Antivirus window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-turn-off-microsoft-defender-antivirus-window.jpg)
4. Select the policy’s**Apply** and**OK** options.
5. Double-click**Allow antimalware to startup with normal priority** and select to disable that policy as outlined in the previous two steps as well.  
<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Allow antimalware service to startup with normal priority window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-antimalware-service-window.jpg)
6. Next, click**Client Interface** within the Microsoft Defender Antivirus settings.  
![Allow antimalware service to startup with normal priority](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/client-interface-setting.jpg)
7. Double-click the**Enable headless UI mode** policy to view it.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
![The Client Interface settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/enable-headless-ui-mode.jpg)
8. Select**Disabled** \>**Apply** \>**OK** in the Enable headless UI mode policy window.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
## 5\. Run a PowerShell Command

 Running a set-MpPreference PowerShell command is a widely confirmed potential resolution for the “Page not available” error. The confirmed command disables Microsoft Defender’s UI lockdown mode. You can run that PowerShell command like this:

1. Activate the Windows search utility.
2. Input a**PowerShell** search phrase to find that command-line app.
3. Open PowerShell with elevated permissions by right-clicking the search result for that command-line app and selecting**Run as administrator** .
4. Input this**MpPreference** command and press**Return** :  
`set-MpPreference -UILockdown`  
![The set-Mppreference PowerShell command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-set-mppreference-command.jpg)
5. Exit PowerShell and open Windows Security again to see if the error persists.

## 6\. Repair/Reset Windows Security

 Windows Security is a UWP app for which you can select**Repair** and**Reset** Settings options that can resolve various issues. Those options are there to help users fix apps that aren’t working right. So, try selecting Windows Security’s**Repair** and**Reset** options to see if they make any difference.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
![The Reset button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-button.jpg)

 Our article[about resetting Windows apps](https://www.makeuseof.com/windows-reset-app/) tells you how to access the**Reset** button. The**Repair** button is just above the**Reset** option. It’s recommended to select**Repair** first since that doesn’t affect app data.

## 7\. Modify the Registry via Command Prompt

 Users also confirm that running a series of Command Prompt commands that modify the registry can resolve the “Page not available” issue. As those are reg delete commands, we recommend you back up the registry before applying this potential fix. Then try running the registry commands for erasing policies like this:

 Open the utility for finding files and apps with the**Windows** logo +**S** key combination.

1. Find the Command Prompt by typing in a**CMD** search phrase.
2. Click the Command Prompt app with the mouse’s right button to select a**Run as administrator** context menu option.
3. Execute the following commands separately, pressing**Enter** after inputting each one:  
`reg delete "HKLM\Software\Microsoft\Windows\CurrentVersion\Policies" /f  

reg delete "HKLM\Software \Microsoft\WindowsSelfHost" /f  

reg delete "HKLM\Software\Policies" /f  

reg delete "HKLM\Software\WOW6432Node\Microsoft\Policies" /f  

reg delete "HKLM\Software\WOW6432Node\Microsoft\Windows\CurrentVersion\Policies" /f  

reg delete "HKLM\SOFTWARE\Policies\Microsoft\Windows Defender" /v DisableAntiSpyware  

reg delete "HKCU\Software\Microsoft\Windows\CurrentVersion\Policies" /f  

reg delete "HKCU\Software\Microsoft\WindowsSelfHost" /f  

reg delete "HKCU\Software\Policies" /f  

reg delete "HKLM\Software\Microsoft\Policies" /f`
4. Input**exit** in the Command Prompt to close the app.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
![The reg delete command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reg-delete.jpg)
5. Open the Start menu, select**Power** , and press the**Restart** button.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## 8\. Perform a System Restore

 If the “Page not available” error remains after applying other potential solutions, try performing a system restore. That might work if you can select a restore point predating the “Page not available” error on your PC. Rolling Windows back to an earlier time could undo any system changes that caused the issue to arise.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-resotre-window.jpg)

 Our guide on[creating and utilizing restore points](https://www.makeuseof.com/windows-11-create-restore-point/) provides instructions for rolling back Windows with System Restore. Choose the oldest restore point you can. However, remember that you’ll probably need to reinstall some software packages installed after the restore point’s date.

## Start Utilizing Windows Security Again

 The potential solutions covered in this guide address many of the primary causes for that error occurring. So, they’ll probably get the “Page not available” error sorted on most users’ Windows 11/10 PCs. Fixing the “Page not available” error will enable you to access all the settings in Windows Security again.

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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-foster-community-with-unique-insta-story-questions/"><u>[New] 2024 Approved  Foster Community with Unique Insta Story Questions</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-proven-techniques-to-elevate-your-igtv-videos-on-mobile-and-professional-cameras/"><u>[New] Proven Techniques to Elevate Your IGTV Videos on Mobile & Professional Cameras</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-unveiling-15-favorite-youtube-video-intros/"><u>[New] Unveiling 15 Favorite YouTube Video Intros</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-unveiling-premium-peak-performance-emoji-makers-for-discord-for-2024/"><u>[New] Unveiling Premium, Peak-Performance Emoji Makers for Discord for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-dish-on-titles-creative-concepts-for-cookery-vids/"><u>[Updated] In 2024, Dish on Titles  Creative Concepts for Cookery Vids</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-discovering-top-notch-hdr-cameras-an-expedition/"><u>2024 Approved  Discovering Top-Notch HDR Cameras  An Expedition</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-expert-recommendations-prime-apps-for-mac-video-recording/"><u>2024 Approved  Expert Recommendations  Prime Apps for Mac Video Recording</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-sky-surfing-in-hd-with-the-yuneec-drone-review/"><u>2024 Approved  Sky Surfing in HD with the Yuneec Drone Review</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-streamlined-screen-recording-on-mac-best-apps-of-choice/"><u>2024 Approved  Streamlined Screen Recording on Mac  Best Apps of Choice</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-top-platforms-for-amplifying-youtube-content/"><u>2024 Approved  Top Platforms for Amplifying YouTube Content</u></a></li>
<li><a href="https://activate-lock.techidaily.com/3-effective-ways-to-bypass-activation-lock-from-iphone-12-mini-by-drfone-ios/"><u>3 Effective Ways to Bypass Activation Lock from iPhone 12 mini</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-things-you-need-to-know-about-wipe-datafactory-reset-for-infinix-note-30-drfone-by-drfone-reset-android-reset-android/"><u>All Things You Need to Know about Wipe Data/Factory Reset For Infinix Note 30 | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/automate-productivity-implementing-auto-gpt-now/"><u>Automate Productivity: Implementing Auto-GPT Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-gpu-performance-the-best-six-tools-guide/"><u>Boosting Windows GPU Performance: The Best Six Tools Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaching-windows-11-theme-shields-with-registry-insights/"><u>Breaching Windows 11 Theme Shields with Registry Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-and-solving-windows-steams-error-e84/"><u>Breaking Down and Solving Windows Steam's Error E84</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-free-from-defenders-history-windows-strategies-unveiled/"><u>Breaking Free From Defender's History: Windows Strategies Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-freeze-on-dormant-windows-batch-file-functionality/"><u>Breaking the Freeze on Dormant Windows Batch File Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-through-the-barrier-of-ms-store-access/"><u>Breaking Through the Barrier of MS Store Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-through-windows-11-tpm-release-methods/"><u>Breaking Through Windows 11: TPM Release Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathe-life-into-your-old-videos-using-madvr-in-the-windows-sphere/"><u>Breathe Life Into Your Old Videos: Using MadVR in the Windows Sphere</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathing-life-into-frozen-windows-hibernate/"><u>Breathing Life Into Frozen Windows Hibernate</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-systems-android-to-windows-shared-files/"><u>Bridging Systems: Android to Windows Shared Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-the-gap-between-internet-access-methods-a-guide-to-dual-connectivity-on-windows/"><u>Bridging the Gap Between Internet Access Methods: A Guide to Dual Connectivity on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-the-gap-fixing-win11-ccleaner-problems/"><u>Bridging the Gap: Fixing Win11 CCleaner Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-the-forgotten-how-to-locate-the-hidden-enhancement-in-windows-11/"><u>Bring Back the Forgotten: How to Locate the Hidden Enhancement in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-windows-update-service-quickly/"><u>Bring Back Windows Update Service Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-back-missing-apps-windows-11s-window-reunification-methods/"><u>Bringing Back Missing Apps: Windows 11'S Window Reunification Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/browser-barriers-overcome-top-strategies-for-website-access-in-win-os/"><u>Browser Barriers Overcome: Top Strategies for Website Access in Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/building-sfx-archives-a-windows-11-guide-for-beginners/"><u>Building SFX Archives: A Windows 11 Guide for Beginners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-pin-for-smooth-projections-on-windows-11/"><u>Bypass PIN for Smooth Projections on WIndows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-clogged-right-click-menus-in-windows-os/"><u>Bypassing Clogged Right-Click Menus in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-ssi-on-windows-easy-installation-of-unchecked-drivers/"><u>Bypassing SSI on Windows: Easy Installation of Unchecked Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-updates-failure-0x800f0845/"><u>Bypassing Updates Failure: 0X800F0845</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-tricky-email-mishap-defeating-error-code-0x800713f/"><u>Bypassing Windows' Tricky Email Mishap: Defeating Error Code 0X800713F</u></a></li>
<li><a href="https://win11-tips.techidaily.com/c-vs-d-key-differences-in-windows-disk-drives/"><u>C vs D: Key Differences in Windows Disk Drives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cable-free-controller-configuration-windows-plus-playstation-3/"><u>Cable-Free Controller Configuration: Windows + PlayStation 3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/capturing-your-desktop-prtsc-vs-snipping-tool-in-windows-10/"><u>Capturing Your Desktop: PrtSc Vs. Snipping Tool in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-defender-firewall-protection-on-windows-11/"><u>Cease Defender Firewall Protection on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-windows-11-user-monitoring-a-guide/"><u>Cease Windows 11 User Monitoring: A Guide</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-microsoft-excel-2023-has-stopped-working-error-by-stellar-guide/"><u>How to fix Microsoft Excel 2023 has stopped working error?</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-phone-touchscreen-of-motorola-razr-40-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Phone Touchscreen Of Motorola Razr 40 | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-the-two-factor-authentication-on-iphone-12-mini-by-drfone-ios/"><u>How To Remove the Two Factor Authentication On iPhone 12 mini</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-iphone-7-with-a-mask-on-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 7 with a Mask On</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-techniques-for-smooth-audio-amplification-in-lumafusion/"><u>In 2024, Techniques for Smooth Audio Amplification in Lumafusion</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/quick-reference-guide-to-screencastifys-tools-for-2024/"><u>Quick Reference Guide to Screencastify's Tools for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/strategic-boxes-opened-marketing-excellence/"><u>Strategic Boxes Opened  Marketing Excellence</u></a></li>
</ul></div>
