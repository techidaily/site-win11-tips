---
title: "Tailoring Biometric Access Control: Windows 11, Domains"
date: 2024-08-28T01:12:00.111Z
updated: 2024-08-29T01:12:00.111Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tailoring Biometric Access Control: Windows 11, Domains"
excerpt: "This Article Describes Tailoring Biometric Access Control: Windows 11, Domains"
keywords: BioAccess Control Win11,Domains Biometrics,W11 Domain Security,Biometric Windows 11,Access Control Systems,Domain-Level Security,Windows Biometrics Integration
thumbnail: https://thmb.techidaily.com/a13a6e974ab2cc36089a6059bc5652aa7fea0848996089325ea48fd7dd51fd22.jpg
---

## Tailoring Biometric Access Control: Windows 11, Domains

 Biometric authentication allows you to quickly log in to the system using fingerprint, facial, or iris recognition. However, what if you want to prevent a domain user from logging in using biometrics?

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

## How to Allow or Block a Biometrics Log-On via the Local Group Policy Editor

 The quickest way to configure your computer to allow or block a biometrics scan for domain users is through the Local Group Policy Editor. Here are the steps you need to follow:

1. Press the **Win + R** key to open the **Run tool.**
2. Type **gpedit.msc** in the search bar and click OK.
3. In the Local Group Policy Editor, head towards the following location:  
`Computer Configuration > Administrative Templates > Windows Components > Biometrics`
4. Double-click on the **Allow domain users to log on using biometrics** policy in the right pane.  
![Allow domain users to log on using biometrics policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/allow-domain-users-to-log-on-using-biometrics-policy.jpg)
5. Choose the **Enabled** option to allow biometrics log on for the domain users. And choose the **Disabled** option to block biometrics log on for the domain users.  
![Enable option in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-option.png)
6. Click **Apply** \> **OK** to save the changes.

## How to Allow or Block a Biometrics Log-On Using the Registry Editor

 Another way to configure biometrics log-on for the domain users is through the Registry Editor. Here's how:

 Editing the registry is risky, as one wrong edit can make your system unstable. Therefore, make sure to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps.

1. Open the Run tool, type **regedit** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Biometrics\Credential Provider`
3. Right-click the **Credential Provider** key in the left sidebar, hover the cursor to **New,** and choose **DWORD (32-bit) Value**.  
![DWORD (32-bit) Value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/dword-32-bit-value.jpg)
4. Name the value **Domain Accounts.**  
![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  
![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Control Biometrics Logins on Your Computer

 Securing sensitive information has now become more important than ever. If you want to allow or block a domain user from logging on using biometrics, you can do that using the above methods.

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-techniques.techidaily.com/updated-first-film-crews-guide-to-gopro-add-ons/"><u>[Updated] First Film Crew's Guide to GoPro Add-Ons</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/best-realme-narzo-60-pro-5g-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>Best Realme Narzo 60 Pro 5G Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convenient-customization-windows-11-and-11-portable-menu-addition/"><u>Convenient Customization: Windows 11 & 11 Portable Menu Addition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-context-menus-to-signal-software-patches/"><u>Creating Context Menus to Signal Software Patches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diagnosing-and-resolving-non-functional-gesture-inputs/"><u>Diagnosing and Resolving Non-Functional Gesture Inputs</u></a></li>
<li><a href="https://location-social.techidaily.com/does-xiaomi-redmi-note-12r-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>Does Xiaomi Redmi Note 12R Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-messages-from-motorola-g54-5g-by-fonelab-android-recover-messages/"><u>Easy steps to recover deleted messages from Motorola G54 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-windows-discover-2023s-community-favorites/"><u>Elevate Windows: Discover 2023'S Community Favorites</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-gaming-experience-using-intel-graphics-hub/"><u>Enhance Your Gaming Experience: Using Intel Graphics Hub</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-or-downgrade-iphone-13-pro-max-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade iPhone 13 Pro Max Without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-life360-notify-when-you-log-out-on-vivo-v30-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Does Life360 Notify When You Log Out On Vivo V30 Pro? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-samsung-galaxy-s23-ultra-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>In 2024, How to Cast Samsung Galaxy S23 Ultra to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-show-wi-fi-password-on-realme-narzo-60-pro-5g-by-drfone-android/"><u>In 2024, How to Show Wi-Fi Password on Realme Narzo 60 Pro 5G</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-xs-max-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone XS Max?</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-simple-snippets-for-iphone-sound-capture/"><u>In 2024, Simple Snippets for iPhone Sound Capture</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/leading-premium-notebooks-and-superior-laptops-for-tech-enthusiasts/"><u>Leading Premium Notebooks and Superior Laptops for Tech Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-your-work-and-play-with-exclusive-ms-picks/"><u>Maximize Your Work & Play with Exclusive MS Picks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-inconsistent-gestures-on-your-windows-device/"><u>Mending Inconsistent Gestures on Your Windows Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-missing-windows-logins-with-ease/"><u>Navigating Through Missing Windows Logins with Ease</u></a></li>
<li><a href="https://extra-tips.techidaily.com/no-experience-big-income-try-these-13-reddit-methods/"><u>No Experience, Big Income? Try These 13 Reddit Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-playnite-for-a-comprehensive-gaming-library/"><u>Optimizing Playnite for a Comprehensive Gaming Library</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-media-tool-errors-0x8007043c-and-0x90017-fixes/"><u>Overcoming Media Tool Errors: 0X8007043C and 0X90017 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reopening-hidden-nvidia-control-panel-on-w11/"><u>Reopening Hidden Nvidia Control Panel on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-password-inclusion-for-your-windows-file-system/"><u>Seamless Password Inclusion for Your Windows File System</u></a></li>
<li><a href="https://network-issues.techidaily.com/secured-endless-flicker-in-portable-computing-panel/"><u>Secured: Endless Flicker in Portable Computing Panel</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-oculus-go-for-windows-vr-compatibility/"><u>Setting up Oculus Go for Windows VR Compatibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-email-management-pin-gmail-to-windows-taskbar/"><u>Streamline Email Management: Pin Gmail to Windows Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-note-visibility-with-tips-for-modern-windows-users/"><u>Streamlining Note Visibility with Tips for Modern Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-video-conversion-mkv-to-mp4-on-pcs/"><u>Streamlining Video Conversion: MKV to MP4 on PCs</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/tailoring-text-features-in-ae-compositions/"><u>Tailoring Text Features in AE Compositions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/telnet-configuration-made-simple-for-win11-users/"><u>Telnet Configuration Made Simple: For Win11 Users</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/the-ultimate-guide-to-the-affordable-yet-capable-samsung-galaxy-a20/"><u>The Ultimate Guide to the Affordable Yet Capable Samsung Galaxy A20</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-from-pin-based-login-on-windows-11-to-traditional-passwords/"><u>Transitioning From PIN-Based Login on Windows 11 to Traditional Passwords</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uninterrupted-powertoys-experience-with-system-switch-up/"><u>Uninterrupted PowerToys Experience with System Switch-Up</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-secrets-how-to-fix-null-input-sounds/"><u>Unlocking the Secrets: How to Fix Null Input Sounds</u></a></li>
<li><a href="https://howto.techidaily.com/why-your-oppo-f25-pro-5g-screen-might-be-unresponsive-and-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Your Oppo F25 Pro 5G Screen Might be Unresponsive and How to Fix It | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-woes-how-to-re-enable-the-hidden-enhancement-panel/"><u>Windows 11 Woes: How to Re-Enable the Hidden Enhancement Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-strategies-6-fast-tips-for-overcoming-ppt-save-failures/"><u>Winning Strategies: 6 Fast Tips for Overcoming PPT Save Failures</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>