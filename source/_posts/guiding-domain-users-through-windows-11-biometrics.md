---
title: Guiding Domain Users Through Windows 11 Biometrics
date: 2024-11-12T16:14:53.525Z
updated: 2024-11-17T18:48:56.994Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guiding Domain Users Through Windows 11 Biometrics
excerpt: This Article Describes Guiding Domain Users Through Windows 11 Biometrics
keywords: Win11 Biometric Guide,Biometrics in Windows 11,Windows 11 Facial Recognition,Windows 11 Fingerprint Login,Navigating Windows 11 Security,Enhancing Windows 11 Access,Mastering Windows 11 Biometrics
thumbnail: https://thmb.techidaily.com/aca28fbc907b3b2134a063785955f99d7ee87845f83996484c29a6f763ca253a.jpg
---

## Guiding Domain Users Through Windows 11 Biometrics

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925544/19272" target="_top" id="1925544">
  <img src="//a.impactradius-go.com/display-ad/19272-1925544" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925544/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087234/19272" target="_top" id="2087234">
  <img src="//a.impactradius-go.com/display-ad/19272-2087234" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087234/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975807/19272" target="_top" id="1975807">
  <img src="//a.impactradius-go.com/display-ad/19272-1975807" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975807/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886019/19272" target="_top" id="1886019">
  <img src="//a.impactradius-go.com/display-ad/19272-1886019" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886019/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-zero.techidaily.com/024-approved-unlocking-user-engagement-through-strategic-tags/"><u>[New] 2024 Approved Unlocking User Engagement Through Strategic Tags</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-shaping-imagery-the-most-innovative-vector-designers-ranked/"><u>2024 Approved Shaping Imagery The Most Innovative Vector Designers Ranked</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-voiceverse-review-audio-deep-dive/"><u>2024 Approved VoiceVerse Review Audio Deep Dive</u></a></li>
<li><a href="https://solve-latest.techidaily.com/digitizing-costains-finances-with-abbyy-technology-insights-from-recent-developments-in-the-newsroom/"><u>Digitizing Costain's Finances with ABBYY Technology: Insights From Recent Developments in the Newsroom</u></a></li>
<li><a href="https://win11-tips.techidaily.com/direct-playback-of-gameplay-on-windows-through-intel-software/"><u>Direct Playback of Gameplay on Windows Through Intel Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-file-coherence-aoemi-techniques-for-double-window-computers/"><u>Ensuring File Coherence: AOEMi Techniques for Double Window Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-battlenet-not-opening-on-a-windows-1110-pc/"><u>How to Fix Battle.net Not Opening on a Windows 11/10 PC</u></a></li>
<li><a href="https://program-issues.techidaily.com/if-switching-entirely-begin-with-a-gradual-transition-rather-than-an-abrupt-change/"><u>If Switching Entirely, Begin with a Gradual Transition Rather than an Abrupt Change.</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722900762008-investigating-aol-mail-problems-how-to-tell-if-its-a-general-downtvein-or-personal-internet-concern/"><u>Investigating AOL Mail Problems: How to Tell If It's a General Downtvein or Personal Internet Concern</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-ultimate-guide-to-text-tracking-software-2023-edition/"><u>New Ultimate Guide to Text Tracking Software 2023 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-win11s-notepad-with-ai-coach/"><u>Optimize Win11's Notepad with AI Coach</u></a></li>
<li><a href="https://buynow-info.techidaily.com/sony-sensory-3d-audio-gear-test/"><u>Sony Sensory 3D Audio Gear Test</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-moment-update-paves-the-way-for-next-level-experience/"><u>Windows 11: Moment Update Paves the Way for Next-Level Experience</u></a></li>
</ul></div>

