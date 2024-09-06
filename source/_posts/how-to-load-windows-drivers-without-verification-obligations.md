---
title: How to Load Windows Drivers without Verification Obligations
date: 2024-09-05T19:32:02.362Z
updated: 2024-09-06T19:32:02.362Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Load Windows Drivers without Verification Obligations
excerpt: This Article Describes How to Load Windows Drivers without Verification Obligations
keywords: Unverified Driver Loading,Non-Verifiable Windows Drivers,Bypassing Driver Checks,Windows Driver Installation,Drivers Without Verification,Loading Drivers Overtime,Windows Drivers, Unsigned
thumbnail: https://thmb.techidaily.com/a3b5ab34eaf3f37a9a75db4fff942183c1ae755ba8565a3523ea779e463db4b2.jpg
---

<!-- affiliate ads begin -->
<span id="1498635">
					<video width="320" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1498635.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/17326-1498635">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1498635.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:200px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fancheer.sjv.io%2Fc%2F5597632%2F1498635%2F17326'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1498635/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Load Windows Drivers without Verification Obligations

 Sometimes, Windows will block you from installing an unsigned driver, which is a driver you've downloaded elsewhere other than through a Windows Update or the device manufacturer's website. But if you need the driver, and you know it is perfectly safe, you can turn off driver signature enforcement and let it through.

 In this guide, we're going to show you several ways to do it.

## How to Disable Driver Signature Enforcement in the Startup Settings

 A temporary way to disable driver signature enforcement is through Startup Settings, allowing you to install the unsigned drivers. However, the moment you restart your PC, Windows will re-enable driver signature enforcement. The unsigned drivers you've installed will still work, but you may not be able to install new ones.

 To disable driver signature enforcement this way, you'll have to [access the Startup Settings screen](https://www.makeuseof.com/windows-startup-settings/). The **Disable driver signature enforcement** option will be the seventh one, so press **F7** or **7** on your keyboard to select it.

![windows 11 startup settings safe mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-startup-settings-safe-mode.jpg)

 Your computer will then restart, and when it reboots, you'll be able to install those unsigned drivers.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137226/26400" target="_top" id="2137226">
  <img src="//a.impactradius-go.com/display-ad/26400-2137226" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137226/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Disable Driver Signature Enforcement in the Local Group Policy Editor

 You can also disable driver signature enforcement by tweaking the **Code signing for driver packages** policy in the Local Group Policy Editor (LGPE). Doing this will allow you to install unsigned drivers even if you restart your computer.

 Unfortunately, you can only natively access the LGPE if you're on Windows Pro or Enterprise Edition. However, there is a way to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

1. Press **Win + S** to bring up Windows Search, enter **group policy** in the Search box, and select **Edit group policy** in the Search results.  
![Open Group Policy Editor Using Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-group-policy-editor-using-windows-search.jpg)
2. Once the LGPE opens up, head to **User Configuration > Administrative Templates > System > Driver Installation**.
3. Right-click **Code signing for driver packages** and select **Edit**.  
![editing the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-the-code-signing-for-driver-packages-policy.jpg)
4. Click the **Enabled** radio button, and then, in the **Options** section, click on the dropdown and select **Ignore**.  
![enabling the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/enabling-the-code-signing-for-driver-packages-policy.jpg)
5. Click on **OK**.
<!-- affiliate ads begin -->
<span id="1993652">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to enable driver signature enforcement again, go back to step #4 and set the radio button to **Not configured**.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134495/18498" target="_top" id="2134495">
  <img src="//a.impactradius-go.com/display-ad/18498-2134495" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134495/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Disable Driver Signature Enforcement in PowerShell

 Another way to disable driver signature enforcement is by running the command to turn off integrity checks in PowerShell (you'll have to run it as an administrator). And just like with the Local Group Policy Editor, it will remain disabled until you enable it again.

 Follow the steps below to turn off driver signature enforcement in PowerShell:

 You can disable driver signature enforcement by [opening Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) if you prefer it over PowerShell.

1. Right-click **Start** and select **Terminal (Admin)** on Windows 11 or **Windows PowerShell (Admin)** on Windows 10\.
2. Click **Yes** on the UAC prompt.
3. Copy **bcdedit /set nointegritychecks on** and paste it into PowerShell.  
![turning off driver signature enforcement in Terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/turning-off-driver-signature-enforcement-in-terminal.jpg)
4. Hit **Enter** to run the command.

 To turn on driver signature enforcement again, replace the command in step #3 with **bcdedit /set nointegritychecks off**.

 One potential problem you can run into when trying to turn off driver signature enforcement this way is an error stating **The value is protected by Secure Boot policy and cannot be modified or deleted**.

![Secure Boot error in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/secure-boot-error-powershell.jpg)

 If that is the case, you can try [turning off Secure Boot](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/) and trying again. But if you don't want to do this, using Startup Settings and the Local Group Policy Editor is perfectly okay.

 You can also put Windows in test mode, which disables driver signature enforcement, allowing you to install those unsigned drivers. To enter test mode, follow the steps below (keep in mind that you may run into the Secure Boot error):

1. Right-click **Start** and select **Terminal (Admin)** on Windows 11 or **Windows PowerShell (Admin)** on Windows 10\.
2. Click **Yes** on the UAC prompt.
3. Copy **bcdedit /set testsigning on** and paste it into PowerShell.  
![turning on Test Mode in Terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/turning-on-test-mode-in-terminal.jpg)
4. Hit **Enter** to run the command.
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137209/26400" target="_top" id="2137209">
  <img src="//a.impactradius-go.com/display-ad/26400-2137209" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137209/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now restart your computer, and when it boots back up, it will be in test mode. After you're done installing those drivers, don't forget to disable test mode. The command to do that is **bcdedit /set testsigning off**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2128842/7443" target="_top" id="2128842">
  <img src="//a.impactradius-go.com/display-ad/7443-2128842" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2128842/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Now You Can Install Unsigned Drivers on Windows

 Installing unsigned drivers on Windows is not recommended, since they can lead to unexpected behavior. However, if you trust the driver, there's no reason why the OS should block you from installing it. Just use one of the methods mentioned above, and you should be able to install and use unsigned drivers on your Windows PC.

 In this guide, we're going to show you several ways to do it.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-oculus-game-collection-top-8-popular-picks/"><u>[New] In 2024, Oculus Game Collection  Top 8 Popular Picks</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-mastering-amazing-ig-video-creation-for-2024/"><u>[New] Mastering Amazing IG Video Creation for 2024</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-in-2024-mastering-the-art-of-tweeting-video-uploads-on-instagram/"><u>[Updated] In 2024, Mastering the Art of Tweeting Video Uploads on Instagram</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-instas-funniest-and-touchiest-memetic-hub-a-list-of-10/"><u>[Updated] Insta's Funniest & Touchiest Memetic Hub  A List of 10</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-intro-to-photo-editing-mastering-lunapic-basics/"><u>2024 Approved  Intro to Photo Editing  Mastering LunaPic Basics</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-leading-sites-elevating-youtube-videos-reach/"><u>2024 Approved  Leading Sites Elevating YouTube Videos' Reach</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-pro-3-analysis-how-ion-is-redefining-the-action-video-landscape/"><u>2024 Approved  Pro 3 Analysis - How ION Is Redefining the Action Video Landscape</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/4-easy-ways-for-your-lava-blaze-2-pro-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>4 Easy Ways for Your Lava Blaze 2 Pro Hard Reset | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-techniques-to-transfer-data-from-vivo-y17s-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Techniques to Transfer Data from Vivo Y17s to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/become-a-pro-with-2023s-free-templates-for-2024/"><u>Become a Pro with 2023'S FREE Templates for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detect-signs-is-it-time-for-windows-clean-slate/"><u>Detect Signs: Is It Time for Windows Clean Slate?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-diagnosing-and-fixing-cc-issues-on-windows-10/"><u>Efficiently Diagnosing and Fixing CC Issues on Windows 10</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/fix-file-not-loaded-completely-error-in-excel-2010-stellar-by-stellar-guide/"><u>Fix File Not Loaded Completely Error in Excel 2010 | Stellar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-scribbling-in-windows-11-effortlessly/"><u>Get Scribbling in Windows 11 Effortlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-manage-your-laptops-energy-efficient-features/"><u>How to Manage Your Laptop's Energy Efficient Features</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-a-working-guide-for-pachirisu-pokemon-go-map-on-poco-f5-5g-drfone-by-drfone-virtual-android/"><u>In 2024, A Working Guide For Pachirisu Pokemon Go Map On Poco F5 5G | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-remove-the-lock-screen-fingerprint-of-your-asus-rog-phone-8-pro-by-drfone-android/"><u>In 2024, Remove the Lock Screen Fingerprint Of Your Asus ROG Phone 8 Pro</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-unique-iphone-photo-style-adding-dynamic-motion-effects/"><u>In 2024, Unique iPhone Photo Style  Adding Dynamic Motion Effects</u></a></li>
<li><a href="https://common-error.techidaily.com/initiating-windows-11-successfully-remedies-for-persistent-freezing-at-startup/"><u>Initiating Windows 11 Successfully: Remedies for Persistent Freezing at Startup</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/inside-the-cut-an-in-depth-look-at-d500-4k-for-2024/"><u>Inside the Cut  An In-Depth Look at D500 4K for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-microsoft-store-repairs-fixing-code-0x80072f30-quickly/"><u>Master Microsoft Store Repairs: Fixing Code 0X80072F30 Quickly</u></a></li>
<li><a href="https://buynow-info.techidaily.com/master-the-skies-with-the-blade-bleb-120s-an-in-depth-review-of-this-favorite-rtf-rc-helicopter/"><u>Master the Skies with the Blade BLeb 120S: An In-Depth Review of This Favorite RTF RC Helicopter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-disabling-windows-updates/"><u>Mastering the Art of Disabling Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-command-prompt-a-guide-to-user-management/"><u>Navigating Command Prompt: A Guide to User Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-startup-hurdles-for-photoshop-on-windows-1011/"><u>Overcoming Startup Hurdles for Photoshop on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proactive-approach-locating-your-devices-mac-address-in-windows-11/"><u>Proactive Approach: Locating Your Device's MAC Address in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-your-pcs-bluetooth-link-with-these-9-essential-tips-for-win-11/"><u>Restore Your PC's Bluetooth Link with These 9 Essential Tips for Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-switching-between-foreign-languages-on-windows-devices/"><u>Speedy Switching Between Foreign Languages on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-tackle-audacitys-sound-fault-windows-11-os/"><u>Strategies to Tackle Audacity's Sound Fault, Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-file-management-overcoming-o365-errors-on-win-11/"><u>Streamlined File Management: Overcoming O365 Errors on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-the-process-of-adjusting-pointer-settings-in-windows-11/"><u>Streamlining the Process of Adjusting Pointer Settings in Windows 11</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/the-ultimate-guide-to-filmora-discounts-4-expert-approved-methods-for-2024/"><u>The Ultimate Guide to Filmora Discounts 4 Expert-Approved Methods for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-reverting-windows-folders-to-full-editability/"><u>Tips for Reverting Windows Folders to Full Editability</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-11-amazing-tricks-and-tasks-achievable-using-siri-on-your-mac/"><u>Top 11 Amazing Tricks and Tasks Achievable Using Siri on Your Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-9-essential-excel-text-manipulation-techniques-using-microsoft-office/"><u>Top 9 Essential Excel Text Manipulation Techniques Using Microsoft Office</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-tips-resolving-latency-in-naraka-bladestorm/"><u>Troubleshooting Tips: Resolving Latency in Naraka Bladestorm</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unifying-ms-office-suite-with-your-zoho-online-platform-a-step-by-step-guide/"><u>Unifying MS Office Suite with Your Zoho Online Platform: A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unlock-the-secrets-of-storytelling-mastery-using-chatgpt-techniques/"><u>Unlock the Secrets of Storytelling Mastery Using ChatGPT Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-efficiency-with-google-sheets-top-14-capabilities-missed-in-microsoft-excel/"><u>Unlocking Efficiency with Google Sheets: Top 14 Capabilities Missed in Microsoft Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-secrets-of-successful-gmaps-integration-in-windows/"><u>Unveiling the Secrets of Successful GMaps Integration in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-context-menu-incorporating-copy-and-move-commands-into-folder-options-win-11/"><u>Upgrade Context Menu: Incorporating Copy & Move Commands Into Folder Options (Win 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/work-on-excel-powerpoint-and-word-online-doc-editing-anywhere/"><u>Work on Excel, PowerPoint & Word Online Doc Editing Anywhere</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>