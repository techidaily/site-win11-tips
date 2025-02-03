---
title: "Biometric Permissions: Managing Domain Users in W11"
date: 2025-01-29T04:22:52.803Z
updated: 2025-01-31T17:01:40.605Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Biometric Permissions: Managing Domain Users in W11"
excerpt: "This Article Describes Biometric Permissions: Managing Domain Users in W11"
keywords: Biometric Access Control,User Authentication W11,Domains User Management,Security W11 Permissions,Authorized Domain Users,Advanced User Verification,Enhanced Privacy W11
thumbnail: https://thmb.techidaily.com/88d3ccdcb9182fe6ab85d78619b5ff79c9f842144c7f0589af82188a3ec75add.jpg
---

## Biometric Permissions: Managing Domain Users in W11

 Biometric authentication allows you to quickly log in to the system using fingerprint, facial, or iris recognition. However, what if you want to prevent a domain user from logging in using biometrics?

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Q8Feep0Rc0?si=YkPhRxXGvrRRMJtb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyMZxS9479s?si=0T6zZpyN2LBftFTM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/umvX4ZdWbxk?si=tPXL0-Kzf9SQaY8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Allow or Block a Biometrics Log-On Using the Registry Editor

 Another way to configure biometrics log-on for the domain users is through the Registry Editor. Here's how:

 Editing the registry is risky, as one wrong edit can make your system unstable. Therefore, make sure to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps.

1. Open the Run tool, type **regedit** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Biometrics\Credential Provider`
3. Right-click the **Credential Provider** key in the left sidebar, hover the cursor to **New,** and choose **DWORD (32-bit) Value**.  
![DWORD (32-bit) Value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/dword-32-bit-value.jpg)
4. Name the value **Domain Accounts.**  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZblaBc-v2vs?si=CKW1gJwXQT2vZJYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  
![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oB9V7rZzotw?si=d4xrCbq1jKHXGAWN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Control Biometrics Logins on Your Computer

 Securing sensitive information has now become more important than ever. If you want to allow or block a domain user from logging on using biometrics, you can do that using the above methods.

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-guidance.techidaily.com/new-uncover-top-8-spots-to-find-free-3d-text-psdfiles/"><u>[New] Uncover Top 8 Spots to Find Free 3D Text PSDFiles</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-unlocking-sound-potential-mastering-mac-audio-with-audacity-for-2024/"><u>[Updated] Unlocking Sound Potential Mastering Mac Audio with Audacity for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-itel-p55-drfone-by-drfone-virtual-android/"><u>In 2024, The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Itel P55 | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/inside-the-samsung-galaxy-z-flip-6-release-schedule-pricing-details-and-cutting-edge-capabilities-revealed/"><u>Inside the Samsung Galaxy Z Flip 6: Release Schedule, Pricing Details, and Cutting-Edge Capabilities Revealed</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/1724766424792-iphoneitunes/"><u>IPhoneと接続するとiTunesが固まってしまう？悲鳴を上げずに解決方法！</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-originality-in-windows-11s-search-feature/"><u>Regaining Originality in Windows 11'S Search Feature</u></a></li>
<li><a href="https://fox-info.techidaily.com/strategic-approaches-to-subtitle-embedding-on-facebook-reddit-for-2024/"><u>Strategic Approaches to Subtitle Embedding on Facebook, Reddit for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-resolving-failed-connection-attempts-fixing-windows-11e-try-connecting-error/"><u>Strategies for Resolving Failed Connection Attempts: Fixing Windows 11'E Try Connecting Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-role-of-aliases-in-coding-a-practical-guide/"><u>The Role of Aliases in Coding: A Practical Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-tutorial-for-analyzing-and-managing-windows-drive-space-with-diskusage/"><u>The Ultimate Tutorial for Analyzing and Managing Windows Drive Space with DiskUsage</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-5-non-root-auto-clicker-android-apps-enhance-your-mobile-productivity/"><u>Top 5 Non-Root Auto-Clicker Android Apps: Enhance Your Mobile Productivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11s-sticky-feature-universal-device-synergy/"><u>Windows 11'S Sticky Feature: Universal Device Synergy</u></a></li>
</ul></div>

