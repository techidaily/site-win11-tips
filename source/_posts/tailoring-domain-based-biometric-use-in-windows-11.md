---
title: Tailoring Domain-Based Biometric Use in Windows 11
date: 2024-06-25T16:27:03.232Z
updated: 2024-06-26T16:27:03.232Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tailoring Domain-Based Biometric Use in Windows 11
excerpt: This Article Describes Tailoring Domain-Based Biometric Use in Windows 11
keywords: Bio-ID in Win11,Windows Biometrics,Fingerprint Tech Win,Windows Facial ID,Secure Login Win11,Personalized User IDs,Biometric Security Win
thumbnail: https://thmb.techidaily.com/747f020dba73f73220750a642a58d9200a84cba1b61684b0bd89a4b6e70d1ea8.jpg
---

## Tailoring Domain-Based Biometric Use in Windows 11

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

## Control Biometrics Logins on Your Computer

 Securing sensitive information has now become more important than ever. If you want to allow or block a domain user from logging on using biometrics, you can do that using the above methods.

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/how-to-handle-iphone-photo-import-errors-on-computers/"><u>How to Handle iPhone Photo Import Errors on Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridge-gap-for-sd-detectability-by-explore-window/"><u>Bridge Gap for SD Detectability by Explore Window</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-common-print-issues-related-to-domain-services-in-modern-windows-oses/"><u>How to Rectify Common Print Issues Related to Domain Services in Modern Windows OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-resolve-win11s-blue-screen-through-these-tips/"><u>Swiftly Resolve Win11's Blue Screen Through These Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-typical-windows-rainmeter-setbacks-and-how-to-overcome-them/"><u>Unraveling Typical Windows Rainmeter Setbacks and How to Overcome Them</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-driver-initialization-failure-in-windows-11/"><u>Solutions for Driver Initialization Failure in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixes-for-inadequate-screen-shots-in-windows-snip-and-sketch-app/"><u>Fixes for Inadequate Screen Shots in Windows’ Snip & Sketch App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/underrated-yet-stunning-best-windows-11-themes/"><u>Underrated, Yet Stunning: Best Windows 11 Themes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-prevent-windowed-app-relocations/"><u>Methods to Prevent Windowed App Relocations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/obscure-yet-outstanding-windows-11-themes/"><u>Obscure yet Outstanding Windows 11 Themes</u></a></li>
<li><a href="https://android-location-track.techidaily.com/best-anti-tracker-software-for-vivo-y28-5g-drfone-by-drfone-virtual-android/"><u>Best Anti Tracker Software For Vivo Y28 5G | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-switch-off-guide-instagrams-igtv/"><u>[New] Switch-Off Guide  Instagram's IGTV</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-nokia-xr21-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How to Change Your Nokia XR21 Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-pioneers-in-digital-avengers-landscapes/"><u>[Updated] Pioneers in Digital Avengers Landscapes</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-2024-approved-mastering-live-stream-entry-tiktok-edition/"><u>[Updated] 2024 Approved  Mastering Live-Stream Entry  TikTok Edition</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-nokia-130-music-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Nokia 130 Music? | Dr.fone</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-do-you-want-to-know-how-to-remove-audio-from-a-video-without-a-watermark-keep-reading-this-article-since-we-have-the-answers-for-you-complete-with-t/"><u>Updated Do You Want to Know How to Remove Audio From a Video without a Watermark? Keep Reading This Article Since We Have the Answers for You. Complete with the Guide on How to Do It</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-exploring-the-world-of-green-screens-a-beginners-visual-effect-guide/"><u>2024 Approved  Exploring the World of Green Screens  A Beginner’s Visual Effect Guide</u></a></li>
<li><a href="https://fake-location.techidaily.com/prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-samsung-galaxy-a05s-drfone-by-drfone-virtual-android/"><u>Prank Your Friends! Easy Ways to Fake and Share Google Maps Location On Samsung Galaxy A05s | Dr.fone</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-gopro-video-editing-on-mac-made-easy-tips-and-tricks/"><u>New In 2024, GoPro Video Editing on Mac Made Easy Tips and Tricks</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>