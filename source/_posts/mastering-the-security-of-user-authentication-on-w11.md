---
title: Mastering the Security of User Authentication on W11
date: 2024-10-29T18:31:53.747Z
updated: 2024-11-01T17:04:47.324Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Security of User Authentication on W11
excerpt: This Article Describes Mastering the Security of User Authentication on W11
keywords: AuthSecureW11,SafeAuthW11,W11LoginSecurity,SecureUserAuthW11,IdentityProtectW11,W11AuthGuard,UserAuthDefenseW11
thumbnail: https://thmb.techidaily.com/bdbc1bb211547c18c849de30d5eb74ca5d67d9e0fc552f041d0a6f6f88d073bb.jpg
---

## Mastering the Security of User Authentication on W11

 Biometric authentication allows you to quickly log in to the system using fingerprint, facial, or iris recognition. However, what if you want to prevent a domain user from logging in using biometrics?

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<a href="https://appsumo.8odi.net/c/5597632/2144280/7443" target="_top" id="2144280">
  <img src="//a.impactradius-go.com/display-ad/7443-2144280" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144280/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135368/19272" target="_top" id="2135368">
  <img src="//a.impactradius-go.com/display-ad/19272-2135368" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135368/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118319/7443" target="_top" id="2118319">
  <img src="//a.impactradius-go.com/display-ad/7443-2118319" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118319/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094419/7443" target="_top" id="2094419">
  <img src="//a.impactradius-go.com/display-ad/7443-2094419" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094419/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Control Biometrics Logins on Your Computer

 Securing sensitive information has now become more important than ever. If you want to allow or block a domain user from logging on using biometrics, you can do that using the above methods.

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-streamlining-audacity-for-superior-audio-capture/"><u>[New] 2024 Approved Streamlining Audacity for Superior Audio Capture</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-how-does-youtube-count-views-its-not-as-simple-as-you-think/"><u>[New] How Does YouTube Count Views? It's Not as Simple as You Think!</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-xbox-one-mastering-live-gaming-broadcasts/"><u>[Updated] 2024 Approved Xbox One Mastering Live Gaming Broadcasts</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-free-best-youtube-video-editor-apps-for-android-for-2024/"><u>[Updated] FREE Best YouTube Video Editor Apps for Android for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-a-technophiles-manual-on-keeping-a-digital-log-of-live-tv/"><u>[Updated] In 2024, A Technophile's Manual on Keeping a Digital Log of Live TV</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-nailing-the-art-of-ppt-video-reproduction/"><u>[Updated] Nailing the Art of PPT Video Reproduction</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-why-are-social-media-suggested-videos-evanescent-in-2024/"><u>[Updated] Why Are Social Media Suggested Videos Evanescent, In 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/apples-intensified-push-in-ai-technology-discover-the-impressive-features-of-new-machine-learning-models/"><u>Apple's Intensified Push in AI Technology: Discover the Impressive Features of New Machine Learning Models</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/expert-advice-diagnosing-and-repairing-the-0xc000000e-bsod-issue/"><u>Expert Advice: Diagnosing and Repairing the 0xC000000E BSOD Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-cannot-find-gpeditmsc-in-windows-with-ease/"><u>Fixing Cannot Find Gpedit.msc in Windows with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-your-gear-use-through-windows-widgets/"><u>Navigating Your Gear Use Through Windows Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-dotnet-a-complete-windows-guide-max-156/"><u>Reviving DotNet: A Complete Windows Guide (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-no-media-found-error-on-hard-drive-windows/"><u>Stop 'No Media Found' Error on Hard Drive Windows</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    