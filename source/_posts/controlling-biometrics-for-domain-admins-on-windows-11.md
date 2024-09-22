---
title: Controlling Biometrics for Domain Admins on Windows 11
date: 2024-09-18T01:59:44.061Z
updated: 2024-09-21T16:55:34.406Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Controlling Biometrics for Domain Admins on Windows 11
excerpt: This Article Describes Controlling Biometrics for Domain Admins on Windows 11
keywords: Admin Biometric Control,W11 Security Keys,Windows Domain Access,Biometric Authentication,Tech Windows Update,Secure Windows Admins,Bio-ID Management
thumbnail: https://thmb.techidaily.com/831f2f90478586ac086abfd43f6d32639656f49a2d8163ca6c49196e0614246e.jpg
---

## Controlling Biometrics for Domain Admins on Windows 11

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

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-top-10-gratuitous-video-chats-with-desktop-viewing/"><u>2024 Approved Top 10 Gratuitous Video Chats with Desktop Viewing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-income-with-movavis-rewarding-affiliate-network/"><u>Boost Your Income with Movavi's Rewarding Affiliate Network</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comment-transformer-facilement-un-video-mkv-en-format-avi/"><u>Comment Transformer Facilement Un Vidéo MKV en Format AVI?</u></a></li>
<li><a href="https://windows11.techidaily.com/distinguishing-characteristics-of-exe-and-msi-files/"><u>Distinguishing Characteristics of EXE and MSI Files</u></a></li>
<li><a href="https://tech-hub.techidaily.com/googles-gemini-navigating-through-its-artificial-intelligence-landscape/"><u>Google’s Gemini: Navigating Through Its Artificial Intelligence Landscape</u></a></li>
<li><a href="https://program-issues.techidaily.com/overcoming-oxygen-not-included-game-freezing-expert-advice-for-smooth-play/"><u>Overcoming 'Oxygen Not Included' Game Freezing: Expert Advice for Smooth Play</u></a></li>
<li><a href="https://techtrends.techidaily.com/revive-your-tiktok-experience-a-comprehensive-troubleshooting-manual/"><u>Revive Your TikTok Experience: A Comprehensive Troubleshooting Manual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-12-caddy-per-display-per-computer-portatili-suggerimenti-e-consigli-di-ottimizzazione-seo/"><u>Top 12 Caddy Per Display Per Computer Portatili: Suggerimenti E Consigli Di Ottimizzazione SEO</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trasforma-i-tuoi-wma-in-ogg-gratuitamente-online-utilizzando-movavi/"><u>Trasforma I Tuoi WMA in Ogg Gratuitamente Online Utilizzando Movavi!</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137214/26400" target="_top" id="2137214">
  <img src="//a.impactradius-go.com/display-ad/26400-2137214" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137214/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

