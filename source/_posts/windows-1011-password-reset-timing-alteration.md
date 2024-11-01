---
title: Windows 10/11 Password Reset Timing Alteration
date: 2024-10-27T17:55:22.703Z
updated: 2024-11-01T19:07:26.838Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Windows 10/11 Password Reset Timing Alteration
excerpt: This Article Describes Windows 10/11 Password Reset Timing Alteration
keywords: Windows 10+Password Change,PC PassResetTimer,Windows Update Logon,Reset WindowPasswords,11/10 Credential Update,Adjust Password Windows,Altered Login Timesync
thumbnail: https://thmb.techidaily.com/0f08e68155172a78a589fb6b8f18fbb5a0a1a4069ed8867faff7b1ab4f999000.jpg
---

## Windows 10/11 Password Reset Timing Alteration

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  
![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  
![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1557747/17382" target="_top" id="1557747">
  <img src="//a.impactradius-go.com/display-ad/17382-1557747" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1557747/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098703/14409" target="_top" id="2098703">
  <img src="//a.impactradius-go.com/display-ad/14409-2098703" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098703/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144297/7443" target="_top" id="2144297">
  <img src="//a.impactradius-go.com/display-ad/7443-2144297" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144297/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975836/19272" target="_top" id="1975836">
  <img src="//a.impactradius-go.com/display-ad/19272-1975836" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975836/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-innovate-or-stagnate-the-must-know-fb-ad-trends-for-24/"><u>[Updated] 2024 Approved Innovate or Stagnate – The Must-Know FB Ad Trends for '24</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-deciphering-the-legacy-of-free-visual-works/"><u>[Updated] In 2024, Deciphering the Legacy of Free Visual Works</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-link-and-leverage-your-fb-story-for-greater-impact/"><u>[Updated] Link & Leverage Your FB Story for Greater Impact</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavioggflac/"><u>「音質を上げるためのフリーコネクト: MovaviでOGG形式をFLACに簡単変換する方法」</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-techniques-for-efficiently-blending-flv-files/"><u>2024 Approved Techniques for Efficiently Blending FLV Files</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-technology-with-toms-hardware-hub-your-source-for-cutting-edge-insights/"><u>Exploring Technology with Tom's Hardware Hub – Your Source for Cutting-Edge Insights</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/flip-monitor-settings-for-optimal-view/"><u>Flip Monitor Settings for Optimal View</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-oggmp3-video-converter-by-movavi-convert-your-files-easily/"><u>Free Online OGG/MP3 Video Converter by Movavi - Convert Your Files Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/los-10-lideres-indiscutibles-programas-mas-eficaces-de-voz-en-off-libre-y-pago-del-2024/"><u>Los 10 Líderes Indiscutibles: Programas Más Eficaces De Voz en Off Libre Y Pago Del 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavis-no-cost-web-service-easily-convert-your-wma-audio-to-m4b-format/"><u>Movavi's No-Cost Web Service: Easily Convert Your WMA Audio to M4B Format</u></a></li>
<li><a href="https://fox-making.techidaily.com/1728470726929-onedrive/"><u>OneDriveファイルの不整合を修正: データは確実に再現されます</u></a></li>
<li><a href="https://some-skills.techidaily.com/step-by-step-guide-installing-iso-files-on-pcs-with-windows-7810/"><u>Step-by-Step Guide: Installing ISO Files on PCs with Windows 7/8/10</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-ultimate-guide-to-the-mobvoi-ticwatch-pro-3-revolutionary-gps-capabilities-meet-enhanced-battery-life/"><u>The Ultimate Guide to the Mobvoi TicWatch Pro 3: Revolutionary GPS Capabilities Meet Enhanced Battery Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformez-votre-image-tiff-en-format-jpeg-faites-le-sans-frais-online-avec-movavi/"><u>Transformez Votre Image TIFF en Format JPEG Faites-Le Sans Frais - Online Avec Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trasforma-i-file-mpeg-in-formato-flv-gratuitamente-online-con-movavi/"><u>Trasforma I File MPEG in Formato FLV Gratuitamente Online Con Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amv-mpeg-movavi/"><u>무료 AMV MPEG 이미지 크론 원자 바이트로 직막 전환 - Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/web-ogm-movavi/"><u>원활한 코어를 사용하여 Web 상호 작용 중인 오클리지 이미지에서 무료 OGM 파일로의 영상 변환 – Movavi</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    