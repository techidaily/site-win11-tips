---
title: Understanding Short-Term Suspension of Windows 11'S Defense
date: 2024-10-01T23:30:11.817Z
updated: 2024-10-03T21:34:21.192Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Understanding Short-Term Suspension of Windows 11'S Defense
excerpt: This Article Describes Understanding Short-Term Suspension of Windows 11'S Defense
keywords: Win11 SysSuspend,Windows Defense Halt,11 Suspend Mechanism,Win11 Defense Pause,Short-Term Windows Suspension,PC Shutdown Safeguard,Temporary OS Lockout
thumbnail: https://thmb.techidaily.com/dda7f892a14e315c0bfa7414c2e13f2432b695f38c3a471ddf15f2d24d24baec.jpg
---

## Understanding Short-Term Suspension of Windows 11'S Defense

 Windows Security is the built-in security app for Windows 11\. You should always keep it enabled as it protects your computer from online and offline threats. However, you may come across situations where you might need to disable it.

 Whether you want to disable it for personal preference or install an app that's facing interference by it, here's how to temporarily disable Windows Security in Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Temporarily Disable Windows Security Using the Settings App

 The Settings app is the central hub of Windows OS, from where you can manage important system settings. You can use it to personalize your computer, change privacy settings, update Windows, and do much more. It's also one of the places to disable Windows Security on your computer. Here's how:

1. Press the**Win + I** hotkeys to open the**Settings** app.
2. Choose**Privacy & security** from the left sidebar.
3. Click the**Open Windows** **Security** button on the right pane.  
![Open Windows Security option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/open-windows-security.jpg)
4. In the Windows Security app, choose the**Virus & threats protection** option from the left sidebar.
5. Click**Manage settings** under the Virus & threats protection section.
6. Disable the toggle under the**Real-time protection** option.  
![Disabling Real-time protection in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/real-time-protection.jpg)

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134501/19576" target="_top" id="2134501">
  <img src="//a.impactradius-go.com/display-ad/19576-2134501" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134501/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. How to Temporarily Disable Windows Security Using the Registry Editor

 Windows Registry is a massive database of important settings and software installed on your computer. You can access and edit that database using a built-in tool called the Registry Editor.

 The Registry Editor can also come in handy in temporarily disabling Windows Security. Here's how to do that:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Windows Security** and press Enter.
3. Select**Virus & threat protection** from the left sidebar.
4. Turn off the toggle under the**Tamper protection** option.  
![Disabling Tamper Protection in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tamper-protection.jpg)
5. Click**Yes** to the UAC that crops up.

 Now it's time to open the Registry Editor. Check out[how to open the Registry Editor on Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/) for steps on how to do this.

1. When the Registry Editor opens, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows Defender`
2. Right-click on**Windows Defender** in the left sidebar and choose**Permissions.**  
![Permissions option in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/permissions.jpg)
3. Click the**Advanced** options.  
![Advanced option in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced.jpg)
4. Click**Change** next to the**Owner** option.
5. In the**Select User or Group window** , click the**Advanced** button.  
![Advanced option in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced-option.jpg)

1. Click the**Find Now** button and then select the admin account.  
![Find Now option in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/find-now.jpg)
2. Click**OK** \>**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130874/7443" target="_top" id="2130874">
  <img src="//a.impactradius-go.com/display-ad/7443-2130874" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130874/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Check the **Replace all child object permission entries with inheritable permission entries from this object** box.  
![Replace all child object permission entries with inheritable permission entries from this object box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/replace-all-child-object-permission-entries-with-inheritable-permission-entries-from-this-object.jpg)
4. Click**Apply** \>**OK.**
5. Next, head towards the**Permission for Windows Defender** window, and check the box next to**Full control.**  
![Full control box in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-control-box.jpg)
6. Click**Apply** \>**OK.**

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880960/19272" target="_top" id="1880960">
  <img src="//a.impactradius-go.com/display-ad/19272-1880960" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880960/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Right-click on the blank space in the right pane, and create three**DWORD (32-bit) Value** with the following names:  
`DisableAntiVirus  

DisableAntiSpyware  

ServiceStartStates`
8. Double-click on each value, type**1** in**Value data,** and click**OK.**

Restart your computer for the changes to take effect.

## 3\. Temporarily Disable Windows Security Using the Local Group Policy Editor

 Another quick way to temporarily turn off Windows Security is through the Local Group Policy Editor. Here's what you need to do:

1. Open the Run dialog box, type**gpedit.msc** , and click**OK.**
2. In the Local Group Policy Editor, navigate to**Computer Configuration** \>**Administrative Templates** \>**Windows Components** \>**Microsoft Defender Antivirus** .
3. Double-click on the**Turn off Microsoft Defender Antivirus** policy.  
![Microsoft Defender Antivirus policy in LGPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/microsoft-defender-antivirus.jpg)
4. Click**Enabled** .  
![Enabled option in LGPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enabled-option.jpg)
5. Click**Apply** \>**OK.**

 Once your work is done, you can enable Windows Security by choosing**Disabled** for the Turn off Microsoft Defender Antivirus policy.

## 4\. Temporarily Disable Windows Security Using Autoruns

 Autoruns is a Windows utility using which you can turn off the service responsible for starting Windows Security at startup. Before you use Autoruns, disable Tamper Protection by following the steps in method 2.

 Follow the below instructions to disable Windows Security using Autoruns:

1. To begin with,[download Autoruns](https://download.sysinternals.com/files/Autoruns.zip) on your computer.
2. Extract the downloaded file on your computer.
3. Next, boot your computer in safe mode (see[how to boot in safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) ) and then open the extracted Autoruns folder.
4. Double-click on the**Autoruns64** file and then choose**Run** from the prompt that crops up.  
![Run option for Autoruns](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/run-option.jpg)
5. Click**Agree** in the**Autoruns Licence Agreement window** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137378/7443" target="_top" id="2137378">
  <img src="//a.impactradius-go.com/display-ad/7443-2137378" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137378/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. In the Autoruns window, click**Options** and uncheck**Hide Windows Entries.**  
![Hide Microsoft Entries option in Autoruns](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/hide-microsoft-enteries.jpg)
7. Click**Services.**

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130890/7443" target="_top" id="2130890">
  <img src="//a.impactradius-go.com/display-ad/7443-2130890" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130890/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. Uncheck the**WinDefend** box and then close the Autoruns window.  
![Disabling WinDefend in Autoruns](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windefend.jpg)

<!-- affiliate ads begin -->
<span id="1424531">
					<video width="864" height="NaN" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424531.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424531">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424531.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424531%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424531/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, to boot in normal mode, open the**System Configuration** window, select**Normal startup,** and then**OK.**

## Stop Windows Security for a Little While on Windows 11

 The new Window Security app ensures you don't have to install a dedicated antivirus program to safeguard your computer. However, the strict policy of Windows Security can sometimes block the installation of third-party apps on your computer. Fortunately, you can disable Windows Security by following the above methods.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-skills.techidaily.com/new-professional-video-finishing-touches-device-based-filters/"><u>[New] Professional Video Finishing Touches Device-Based Filters</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-unveiling-hidden-tiktok-ban-criteria/"><u>[Updated] In 2024, Unveiling Hidden TikTok Ban Criteria</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-5-proven-ways-to-improve-windows-11-search-success/"><u>Discover 5 Proven Ways to Improve Windows 11 Search Success</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ek-direct-die-aio-cooler-delivers-stellar-performance-boost-your-13900ks-with-up-to-20-degrees-of-improved-cooling-efficiency/"><u>EK Direct Die AiO Cooler Delivers Stellar Performance: Boost Your 13900KS with Up to 20 Degrees of Improved Cooling Efficiency</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/how-to-validate-your-youtube-profile-a-simple-guide-for-2024/"><u>How to Validate Your YouTube Profile? A Simple Guide for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-vivo-y27s-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>In 2024, How to Cast Vivo Y27s Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/mp3and/"><u>MP3変換&保存できず、クリップボックスの詳細解明：究極の回避方法</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-ms-store-error-0x80073d26-on-windows-11/"><u>Resolving MS Store Error 0X80073d26 on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-file-format-adaptability-with-windows-expertise/"><u>Securing File Format Adaptability with Windows Expertise</u></a></li>
<li><a href="https://fox-glue.techidaily.com/selecting-premium-steadicams-to-improve-your-dslr-videos/"><u>Selecting Premium Steadicams to Improve Your DSLR Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-mitigate-temp-file-extraction-problem-in-windows/"><u>Strategies to Mitigate 'Temp File Extraction Problem' In Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-happens-when-a-windows-discord-update-fails-fixing-it/"><u>What Happens When a Windows Discord Update Fails? Fixing It</u></a></li>
</ul></div>

