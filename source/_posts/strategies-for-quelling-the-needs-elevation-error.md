---
title: Strategies for Quelling the Needs Elevation Error
date: 2024-10-20T04:19:18.502Z
updated: 2024-10-21T03:19:19.541Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies for Quelling the Needs Elevation Error
excerpt: This Article Describes Strategies for Quelling the Needs Elevation Error
keywords: NeedElevationControl,ReduceNeedError,StrategyQuellNeeds,ElevateNeedMitigation,NeedsManagementTips,ErrorReductionMethod,NeedsErrorBalancing
thumbnail: https://thmb.techidaily.com/78fc2ce8486dc3d6564f3f5f4f837891a8fa189d01a8b699d519ecb10291bd82.jpg
---

## Strategies for Quelling the Needs Elevation Error

 Some users have reported in support forum posts that error 740 occurs when they try to run programs or access folders on Windows PCs. The error 740 message says, “The requested operation requires elevation.” Users can’t access software, folders, or files for which error 740 occurs.

 This is how you can fix error 740 within Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run the Affected Programs With Admin Rights

 The error 740 message mentions the need for operation elevation. That’s a hint to try running affected programs with elevated (administrator) rights. Check out this guide on [always running apps as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) to set affected EXE files to run with elevated rights.

![The Run this program as an administrator checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-as-an-administrator.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657396/16446" target="_top" id="1657396">
  <img src="//a.impactradius-go.com/display-ad/16446-1657396" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657396/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Set Programs to Run in Compatibility Mode

 It’s also recommended to set older programs to run in compatibility mode. Doing so might address a compatibility issue causing error 740\. You can set an affected program to run in compatibility mode like this:

1. Open the affected software’s installation within File Explorer.
2. Right-click an affected program’s EXE (application file) and select **Properties** \> **Compatibility**.
3. Select **Run this program in compatibility mode for** and choose Windows 8 or an older platform on the drop-down menu. It’s best to select the Windows platform for which the publisher originally released the software.  
![The Run this program in compatibility mode drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-in-compatibility-mode.jpg)
4. Press the **Apply** \> **OK** buttons to set the compatibility mode setting.

## 3\. Turn Off the User Account Control Feature

 User Account Control is the security feature that throws up notifications when programs try to make changes. UAC could be a potential cause of error 740 when it’s set very high. So, try turning off UAC before running affected apps. Our [guide to disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) tells you how to turn off that feature.

![The User Account Control Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/user-account-control-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130869/7443" target="_top" id="2130869">
  <img src="//a.impactradius-go.com/display-ad/7443-2130869" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130869/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Adjust Folder Permission Settings

 This potential resolution is recommended for users who can’t access specific folders because of error 740\. In that scenario, this error can be a folder permissions issue that selecting the **Replace all child object permission entries** option could feasibly address.

 Try selecting the **Replace all child object permission** setting for an affected folder as follows:

1. Press **Win + E** to bring up File Explorer.
2. Open whatever directory contains the folder for which error 740 occurs.
3. Right-click the affected folder and select that directory’s **Properties** option.
4. Select **Security** on the window’s tab bar.
5. Click **Advanced** to access more security settings.  
![The Security tab and Advanced button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-security-tab3.jpg)
6. Select the **Replace all child object permissions entries with inheritable permission entries from this object** checkbox.  
![The Replace all child object permission entries checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/replace-all-child-objects-option.jpg)
7. Click **Apply** on the Advanced Security Settings window.
8. Select **Yes** when asked to continue.
9. Exit the folder’s properties window and restart your PC.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938682/19272" target="_top" id="1938682">
  <img src="//a.impactradius-go.com/display-ad/19272-1938682" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938682/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Modify the Behavior of the UAC Elevation Prompt

 If your Windows PC has the Group Policy Editor, try changing the behavior of UAC’s elevation prompt with that tool. Selecting the **Elevate without prompting** setting for the User Account Control: Behavior policy could fix error 740 for some users.

 You can select that option within Windows Enterprise and Pro editions like this:

1. Open the Local Group Policy Editor. If you need help, check out the [ways to open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
2. Next, double-click **Computer Configuration** to expand that sidebar navigation option.
3. Double-click **Windows Settings** and select **Security S** **ettings**.
4. Then go to **Local Policies** and **Security Options** to access User Account Control Policy settings.  
![Security Options within Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/security-options.jpg)
5. Double-click the **User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode** policy.
6. Select the **Elevate without prompting** option on the drop-down menu.  
![The Elevate without prompting option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/elevate-without-prompting.jpg)
7. Click **Apply** to set the **Elevate without prompting policy**.
8. Select **OK** to close the policy setting’s window.
9. Then reboot Windows after closing Group Policy Editor.

## 6\. Disable Admin Approval Mode

 Admin Approval Mode prompts administrative users for task permissions when enabled. It’s a strict Group Policy Editor security policy that can potentially cause elevation issues. Follow these steps to turn off Admin Approval Mode.

1. Go to **Security Options** in Group Policy Editor as outlined for steps one to four of resolution five.
2. Double-click the **User Account Control: Admin Approval Mode for the Built-in Administrator account** policy setting.  
![The Admin Approval Mode policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/admin-approval-mode-policy.jpg)
3. Click the **Disabled** radio button if this policy is enabled.  
![the-enabled-radio-button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enabled-radio-button.jpg)
4. Select **Apply** to turn off Admin Approval Mode.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134497/18498" target="_top" id="2134497">
  <img src="//a.impactradius-go.com/display-ad/18498-2134497" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134497/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. To close the policy window, select the **OK** option.

## 7\. Disable Third-Party Antivirus Software Packages

 Have you installed a third-party antivirus or security app on your PC? If you have, your third-party security software could be causing error 740 by blocking the EXE file you’re trying to run. This can happen when the antivirus software flags the application file as malicious.

 The potential solution, in this case, is to temporarily disable third-party antivirus software before trying to run affected programs. Look for and select an option that turns off the antivirus shield by right-clicking on the antivirus software’s system tray icon. If there are time options available, select to turn the real-time protection off for about an hour or so.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 If disabling the security software works, you don’t necessarily have to turn the security software off whenever you want to run the application file. Your antivirus software will probably include an exclusion list to which you can add trustworthy program file exceptions. Add the affected EXE file there to exclude it from the antivirus protection.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1610918/18409" target="_top" id="1610918">
  <img src="//a.impactradius-go.com/display-ad/18409-1610918" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://coinrule.sjv.io/i/5597632/1610918/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 8\. Migrate to a New Admin User Account

 If the “requested operation requires elevation” error persists after trying other resolutions, your user account might be corrupted. Then you might need to create and utilize a new admin account to resolve this issue. You can migrate to that account by copying files from your old user account into the new one.

![The Add account option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-account-option.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135350/19272" target="_top" id="2135350">
  <img src="//a.impactradius-go.com/display-ad/19272-2135350" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135350/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To apply this troubleshooting method for the “requested operation requires elevation” error, follow the instructions within this article about [how to fix Windows issues by creating new user accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/). First, you’ll need to set up and sign in to the new admin account to see if the error occurs there. If not, transfer user files into the new account as covered there.

## Get Error 740 Sorted on Windows

 The “requested operation requires elevation” error is an inconvenient admin access privilege issue many users have needed to fix. Users have resolved that issue by applying the potential resolutions in this guide. So, try applying those fixes for the “requested operation requires elevation” error in the order specified to find one that works on your Windows 10 or 11 PC.

 This is how you can fix error 740 within Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-sure.techidaily.com/n-2024-eliminate-your-streaming-darkness-on-youtube/"><u>[New] In 2024, Eliminate Your Streaming Darkness on YouTube</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-elite-listing-top-10-windows-11-cam-capture-devices/"><u>[Updated] 2024 Approved Elite Listing Top 10 Windows 11 Cam Capture Devices</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-understanding-the-basics-of-motion-design/"><u>[Updated] In 2024, Understanding the Basics of Motion Design</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-quick-guide-youtube-soundtracks-to-mp3-for-macos-2shift/"><u>[Updated] Quick Guide YouTube Soundtracks to MP3 for MacOS 2Shift</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-revolutionizing-video-revenue-a-conducive-guide-to-youtube-profits-for-2024/"><u>[Updated] Revolutionizing Video Revenue A Conducive Guide to Youtube Profits for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1080p-vs-4k-quels-sont-les-avantages-de-la-video-en-haute-definition-et-comment-upscaler-a-partir-de-1080p/"><u>1080P vs 4K : Quels Sont Les Avantages De La Vidéo en Haute Définition Et Comment Upscaler À Partir De 1080P</u></a></li>
<li><a href="https://some-guidance.techidaily.com/efficient-ways-to-reduce-your-video-size-perfectly-a-guide-for-smooth-sharing-on-whatsapp/"><u>Efficient Ways to Reduce Your Video Size Perfectly: A Guide For Smooth Sharing on WhatsApp</u></a></li>
<li><a href="https://howto.techidaily.com/fixes-for-apps-keep-crashing-on-honor-x50-gt-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixes for Apps Keep Crashing on Honor X50 GT | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/flac-wav-movavi-wi-fi/"><u>FLAC 파일을 WAV로 쉽게 바꾸기: Movavi의 원형 제공 Wi-Fi 사용 가능성</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-converter-change-mp2-audio-files-into-mp3-format-with-movavi/"><u>Free Online Converter: Change MP2 Audio Files Into MP3 Format with Movavi</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-5-easy-ways-to-change-location-on-youtube-tv-on-apple-iphone-se-2022-drfone-by-drfone-virtual-ios/"><u>In 2024, 5 Easy Ways to Change Location on YouTube TV On Apple iPhone SE (2022) | Dr.fone</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/master-your-pc-with-toms-hardware-insights-and-in-depth-analysis/"><u>Master Your PC with Tom's Hardware Insights and In-Depth Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavis-effortless-wav-to-m4r-file-converter-download-and-use-it-for-free/"><u>Movavi's Effortless WAV-to-M4R File Converter - Download & Use It For Free!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavis-online-mp3-to-m4r-service-convert-your-songs-free/"><u>Movavi's Online MP3-to-M4R Service - Convert Your Songs Free!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movaviflv3gp/"><u>Movaviで簡単にフリーオンライン変換:FLVを3GPに</u></a></li>
<li><a href="https://win11-tips.techidaily.com/scambia-il-tuo-file-video-tta-con-un-formato-flac-senza-costi-usando-leditor-di-codici-video-online-movavi-passaggi-semplici-per-tutti/"><u>Scambia Il Tuo File Video TTA Con Un Formato FLAC Senza Costi Usando L'editor Di Codici Video Online Movavi - Passaggi Semplici per Tutti</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-audio-formats-effortlessly-convert-m4a-to-m4v-at-no-cost-via-web-services/"><u>Switching Audio Formats Effortlessly - Convert M4A to M4V at No Cost via Web Services</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ultimate-guide-mastering-emoji-usage-on-your-iphone/"><u>Ultimate Guide: Mastering Emoji Usage on Your iPhone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/veelvoudig-maken-van-flac-liedjes-in-mp4-online-gratis-movavi-online-konverter/"><u>Veelvoudig Maken Van FLAC-Liedjes in MP4 Online, Gratis - Movavi Online Konverter</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    