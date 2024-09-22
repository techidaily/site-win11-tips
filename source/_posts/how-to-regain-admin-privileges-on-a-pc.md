---
title: How to Regain Admin Privileges on a PC
date: 2024-09-19T06:59:27.852Z
updated: 2024-09-21T19:17:18.314Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Regain Admin Privileges on a PC
excerpt: This Article Describes How to Regain Admin Privileges on a PC
keywords: Reclaim PC Admin Rights,Gain Admin Access PC,Restore Computer Admin Perms,Reset Windows Admin Status,Re-Establish PC Admin Login,Regain Control of PC Admin,Fix PC Admin Denial
thumbnail: https://thmb.techidaily.com/3fc14c15f73df5f4c8b19f8291c51668294576df82a5964da7eda1f1831694f2.jpg
---

## How to Regain Admin Privileges on a PC

 Administrator accounts offer extensive control over the system, granting the ability to manage settings, install software, and access critical system files. However, occasionally, users may encounter issues when attempting to switch from their standard user account to an admin account.

 Below, we explore various effective fixes to resolve this problem permanently.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Modify the User Account Control (UAC) Settings

 User Account Control (UAC) is a security feature that prevents users from making unauthorized changes to the computer. It typically appears as a dialog box, prompting you to confirm the action by clicking the "Yes" or "No" option.

 In the case of this specific error, you might be facing the issue because of misconfigured or incorrect UAC settings. Here is how you can ensure UAC is enabled and set to a suitable level:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "control" in the text field and click **Enter**.
3. In the following window, navigate to **System and Security** \> **Security and Maintenance**.
4. Choose **Change User Account Control settings**.
5. In the dialog that appears, move the slider to the desired level (recommended: notify only when apps try to make changes to your computer) and click **OK** to save the changes.  
![The User Account Control Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-uac-settings.jpg)

 Once done, close the Command Prompt and check if the issue is resolved.

## 2\. Activate the Built-In Administrator Account

![Enable the built-in admin account in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-built-in-admin-account.jpg)

 Windows comes with a hidden administrator account that can allow you to have full control over the system. This account is typically disabled by default for security reasons but if you are having trouble switching to an administrator account, enabling the built-in Administrator account can be beneficial.

 Here's how to activate the built-in Administrator account:

1. Press the **Win** \+ **R** keys to open Run.
2. Type "cmd" in Run and press the **Ctrl** \+ **Shift** \+ **Enter** to open Command Prompt as an administrator.
3. Click **Yes** in the following dialog.
4. Once you are in the Command Prompt, type the command below and hit **Enter** to execute it:  
net user administrator /active:yes
5. After the command executes successfully, you should see a message in Command Prompt confirming it. If you want to set a password for this administrator account, execute the following command:  
​​​​​​​net user administrator *
6. Follow the prompts to set a new password.

 Alternatively, you can also use the Local Users and Groups management console to make these changes. Here is how you can do that:

1. Open Run by pressing **Win** \+ **R** keys together.
2. Type "lusrmgr.msc" in Run and click **Enter**.
3. In the left pane, expand **Users** and right-click on **Administrator**.
4. Choose **Properties** from the context menu.
5. Uncheck the **Account is disabled** option and click **OK**.  
![Enable the built-in admin account in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-admin-account.jpg)

 This should successfully activate the built-in administrator account. You can now access the Settings app again and check if you can switch the account type easily now.

## 3\. Make the Changes in Safe Mode

 It's possible that a background process or application is causing interference with system processes, which could be preventing you from switching to an administrator account.

 To determine if this is the cause of the issue, you can [boot your computer into Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/). Safe Mode launches the system with minimal drivers and programs, disabling any background processes that may be contributing to the problem. In this diagnostic state, you should be able to switch to the administrator account if such processes were previously causing the obstruction.

 Once you have booted into Safe Mode, try performing the action that was initially causing the problem. If it does not occur in Safe Mode, you can try eliminating the culprit by either uninstalling it manually or [using the System Restore utility](https://www.makeuseof.com/tag/system-restore-factory-reset-work-windows-10/) to revert to a stable, error-free state.

## 4\. Disable Your Antivirus Program

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 If you are using a third-party security program on your computer, it might be preventing you from switching to an admin account because of security reasons.

 In this case, you can try to temporarily disable your security program and see if that helps you switch to an administrator account. You can do this by right-clicking on your antivirus icon in the taskbar and choosing the **Shields Control** \> **Disable until the computer is restarted** option.

 If this works, you can consider [switching to a better security program for your Windows](https://www.makeuseof.com/windows-11-antivirus-apps/) to prevent issues like this from occurring in the future.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075483/7443" target="_top" id="2075483">
  <img src="//a.impactradius-go.com/display-ad/7443-2075483" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075483/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Create a New Administrator Account

## Finally, if none of the methods above have helped you, you can try creating a new administrator account in Windows

 This will help with any corruption issues in the current account, as well as help you determine if the permission-related problems were user-specific. It is, however, important to note that you will require admin access to the system to proceed with the steps in this method, so you must enable the built-in administrator account beforehand.

 Once that is done, here is how you can proceed:

1. Open the Settings app by pressing the **Win** \+ **I** keys together.
2. Choose **Accounts** from the left pane and click on **Other users**.
3. Hit the **Add account** button for **Add other users** in the following window.  
![The Add account option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-account-option.jpg)
4. Select **I don’t have this person’s sign-in information** \> **Add a user without a Microsoft account**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135364/19272" target="_top" id="2135364">
  <img src="//a.impactradius-go.com/display-ad/19272-2135364" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135364/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. In the next dialog, enter details like the username and password for the new account.
6. Click **Next**.
7. Once the account is created, click on the **Change account type** button associated with the newly created account.  
![The Change account type button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-change-account-type-option.jpg)
8. Expand the Account type dropdown and choose **Administrator** from the menu.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134243/18498" target="_top" id="2134243">
  <img src="//a.impactradius-go.com/display-ad/18498-2134243" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134243/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Click **OK** to save the changes.

 You can now log into the new administrator account and begin using it.

## Enjoy Administrative Access to Your Windows System

 The inability to change an account type to Administrator in Windows can be caused by a number of reasons, such as misconfigured User Account Control (UAC) settings or underlying system issues. However, with the right troubleshooting methods, you can overcome the account type change challenge and enjoy administrative access to the system.

 Below, we explore various effective fixes to resolve this problem permanently.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-tips.techidaily.com/new-6-alternative-apps-to-periscope-for-iphoneandroid-users/"><u>[New] 6 Alternative Apps to Periscope for iPhone/Android Users</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-academic-anchors-identifying-top-10-lecture-preservation-tools/"><u>[New] Academic Anchors Identifying Top 10 Lecture Preservation Tools</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-scripting-for-success-filmmakers-secrets-for-2024/"><u>[Updated] Scripting for Success Filmmaker's Secrets for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-best-6-cheap-4k-projectors/"><u>2024 Approved Best 6 Cheap 4K Projectors</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-tweetaudioextractor-quick-sound-maker/"><u>2024 Approved TweetAudioExtractor Quick Sound Maker</u></a></li>
<li><a href="https://win11-tips.techidaily.com/h264-h264/"><u>發現H.2#64格式: H.264媒體播放解決方案、設定及支持的作業系統比較分析</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movaviwmampeg/"><u>完美上線不用付費，使用Movavi將WMA改造成MPEG影片</u></a></li>
<li><a href="https://win11-tips.techidaily.com/descargar-y-convertir-archivos-de-audio-ogg-a-mp4-sin-costo-con-la-herramienta-online-de-movavi/"><u>Descargar Y Convertir Archivos De Audio OGG a MP4 Sin Costo Con La Herramienta Online De Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-and-fast-switch-vob-videos-to-mp4-formats-for-pc-and-mac-users-using-movavis-free-tool/"><u>Easy & Fast: Switch VOB Videos to MP4 Formats for PC and Mac Users Using Movavi's Free Tool</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-vivo-v27e-drfone-by-drfone-virtual-android/"><u>How to use Snapchat Location Spoofer to Protect Your Privacy On Vivo V27e? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-pc-screen-to-itel-p55plus-phones-drfone-by-drfone-android/"><u>In 2024, How to Mirror PC Screen to Itel P55+ Phones? | Dr.fone</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-to-track-apple-iphone-15-plus-by-phone-number-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Track Apple iPhone 15 Plus by Phone Number | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-strategies-to-enhance-minecraft-frame-rate-on-gaming-beasts-high-end-pcs-insights-from-2vectras-guide/"><u>Top Strategies to Enhance Minecraft Frame Rate on Gaming Beasts (High-End PCs) - Insights From 2Vectra's Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trasforma-file-webm-in-gif-gratuito-fast-e-versatile-conversion-tool/"><u>Trasforma File Webm in Gif Gratuito - Fast E Versatile Conversion Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pcx-jpg-movavi/"><u>온라인 PCX 이미지 교체를 위한 자세하고 JPG로의 가장 좋은 방법 - 무료 Movavi 프로그램</u></a></li>
</ul></div>

