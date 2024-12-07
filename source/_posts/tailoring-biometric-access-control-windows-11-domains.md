---
title: "Tailoring Biometric Access Control: Windows 11, Domains"
date: 2024-11-29T23:42:46.355Z
updated: 2024-12-06T19:27:01.075Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=LvxQhsEJoymsM2iZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/KF793jv1LIc?si=fJOogQJ2f8JUfTzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Jfq2Wx1Bcs?si=YQrYpTy0g4aV5QaO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iPCr_bxZjMQ?si=ubOsoq5umPEXL9xL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AcAYRX0cwwA?si=DxqWU39vqksZbe1s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://some-approaches.techidaily.com/new-top-8-enhanced-peripherals-for-a-richer-metaverse-experience/"><u>[New] Top 8 Enhanced Peripherals for a Richer Metaverse Experience</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-gopro-showdown-full-review-and-ratings/"><u>[Updated] 2024 Approved GoPro Showdown Full Review and Ratings</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-enriching-vlog-topics-to-share/"><u>[Updated] In 2024, Enriching Vlog Topics to Share</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-apple-iphone-6s-plus-drfone-by-drfone-virtual-ios/"><u>4 solution to get rid of pokemon fail to detect location On Apple iPhone 6s Plus | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comparative-study-of-nvidia-drivers-for-gamersstudios/"><u>Comparative Study of Nvidia Drivers for Gamers/Studios</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/effective-techniques-for-skyrocketing-black-friday-sales-in-2020-using-massmail-solutions/"><u>Effective Techniques for Skyrocketing Black Friday Sales in 2020 Using MassMail Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-app-guard-graphics-in-windows-11-os/"><u>Enhancing App Guard Graphics in Windows 11 OS</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-does-enter-puk-code-mean-and-why-did-the-sim-get-puk-blocked-on-xiaomi-redmi-k70e-device-by-drfone-android/"><u>In 2024, What Does Enter PUK Code Mean And Why Did The Sim Get PUK Blocked On Xiaomi Redmi K70E Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modifying-failed-logon-lockout-period-for-win1011/"><u>Modifying Failed Logon Lockout Period for Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/no-window-no-problem-revive-off-screen-apps-with-6-easy-fixes-for-win-1011/"><u>No Window, No Problem! Revive Off-Screen Apps with 6 Easy Fixes for Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/phoenix-revival-atlasos-for-vintage-setup/"><u>Phoenix Revival: AtlasOS for Vintage Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-print-conflicts-in-windows-1011/"><u>Resolving Print Conflicts in Windows 10/11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/step-by-step-method-for-capturing-internet-radio-frequencies-for-2024/"><u>Step-by-Step Method for Capturing Internet Radio Frequencies for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-windows-schedules-solve-problems-easily/"><u>Streamline Windows Schedules, Solve Problems Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-no-errors-resolve-the-0x0-glitch-in-windows-11/"><u>Tackling No Errors: Resolve the 0X0 Glitch in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-update-difficulties-fixing-win11s-error-0x80246007/"><u>Tackling Update Difficulties: Fixing Win11’s Error 0X80246007</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210245445-9781098037093-the-making-of-a-prayer-princess/"><u>The Making of a Prayer Princess | Free Book</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ultimate-iphone-emoji-user-manual-how-to-express-with-digital-smiles/"><u>The Ultimate iPhone Emoji User Manual: How to Express with Digital Smiles</u></a></li>
<li><a href="https://facebook.techidaily.com/top-4-signs-declining-user-numbers-on-facebook/"><u>Top 4 Signs: Declining User Numbers on Facebook</u></a></li>
</ul></div>

