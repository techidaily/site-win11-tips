---
title: How to Modify Windows Installation Service State
date: 2024-09-27T22:20:02.189Z
updated: 2024-10-03T20:30:07.437Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Modify Windows Installation Service State
excerpt: This Article Describes How to Modify Windows Installation Service State
keywords: Windows Installer Change,Service Install Modification,Windows Update Adjustment,Service Sync Tweak,System Service Alter,Config Service Control,Update Service State Edit
thumbnail: https://thmb.techidaily.com/29d02750ad0cb057d82cf1dca19da27d5429074e0ee73dae3abc4f97673bc3bc.jpg
---

## How to Modify Windows Installation Service State

 Are you looking for a way to disable the Windows Installer Service on your device? This essential component of your operating system performs all necessary installation processes, but can sometimes interfere with other programs.

 Fortunately, there are three ways in which it can be disabled—using the Windows Service tool, Group Policy Editor, or Registry Editor. Check out our guide below to learn how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Use Windows Services

 Windows services are critical programs that typically initiate when you start your computer. It runs silently in the background and provides essential features to run the operating system. If you're looking to enable or disable Windows Installer service using this tool, do the following.

 To begin, press**Win + R** on your keyboard to launch the Run dialog box. In the text box, type**services.msc** , and hit enter. This will open the Services window.

![Disable Windows Installer Service Using Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-services-window.jpg)

 In the window that opens, scroll down until you find**Windows Installer** service then double-click on it for a properties window to open.

 Once you're in the Properties window, click the**Startup type** drop-down menu and select**Automatic** . Now move over towards the**Service status** section and click**Stop** .

![Disable Windows Installer Service Using Windows Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-windows-services.jpg)

 After you've done that, click**Apply** and then**OK** to save the changes. You have now successfully disabled the Windows Installer service on Windows 11.

 If you ever need to re-enable the service, follow the same procedure and click**Start** in the Service status section.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1186802/12108" target="_top" id="1186802">
  <img src="//a.impactradius-go.com/display-ad/12108-1186802" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1186802/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Use Local Group Policy Editor

 You can also use the group policy editor to enable or disable the Windows Installer service on your Windows computer system. However, it is important to note that this tool only works on Windows Pro and Enterprise editions. Therefore, if you are using Windows Home Edition, you must first[activate the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 To disable the service using the group policy editor, do the following:

1. Click on Start and type in**gpedit.msc** , then press**Enter** to[launch the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) .
2. On the left side of the window, navigate to the path:  
`Computer Configuration > Administrative Templates > Windows Components > Windows Installer`
3. Now move to the right and double-click on the policy named**Turn off Windows Installer** .  
![Disable Windows Installer Service Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-group-policy.jpg)
4. In the window that opens, select**Enabled** in the radio box.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134236/18498" target="_top" id="2134236">
  <img src="//a.impactradius-go.com/display-ad/18498-2134236" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134236/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Under Options, click the drop-down menu and select**Always** .
6. Then click**Apply** and**OK** to save changes.

 That's all there is to it. The Windows Installer service will now be disabled on your system. To re-enable it, simply follow the same steps, but set "Turn off Windows Installer" to**Not Configured** .

## 3\. Use the Registry Editor

 Registry Editor is another method you can use to enable or disable the Windows Installer service on any version of Windows, even Home Edition. But make sure to proceed with caution as any incorrect changes can corrupt your system and force you to reinstall Windows. So be mindful and remember to back up your registry before making any modifications.

 To enable or disable this service using Registry Editor, follow these steps:

1. Press**Win + X** , type**regedit** , and press**Enter** to launch the Registry Editor. To learn more, see our guide on how to[open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. If prompted with a UAC warning, click**Yes** to continue.
3. Now once you're in, navigate to the following path:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\msiserver`
4. In the right panel, double-click on**Start** and change its value from**2** to**4** .  
![Disable Windows Installer Service Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-registry-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137204/26400" target="_top" id="2137204">
  <img src="//a.impactradius-go.com/display-ad/26400-2137204" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137204/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you put the Value data, make sure the Base is set to**Hexadecimal** , then click**OK** . Now close the registry editor and restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<span id="1977004">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977004.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977004">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977004.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977004%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977004/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Turning Off the Windows Installer Service Made Easy

 If Windows Installer Service is creating issues or hindering another application, you can easily turn it off with one of the three methods outlined in our guide. See which method works best for you and get back to what matters most.

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
<li><a href="https://youtube-video-recordings.techidaily.com/updated-dominate-search-results-powerful-youtube-seo-techniques-exposed/"><u>[Updated] Dominate Search Results Powerful YouTube SEO Techniques Exposed</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-android-hd-viewing-your-10-app-must-have-guide/"><u>[Updated] In 2024, Android Hd Viewing Your 10-App Must-Have Guide</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-simplified-approach-to-decoding-facebook-statistics/"><u>2024 Approved Simplified Approach to Decoding Facebook Statistics</u></a></li>
<li><a href="https://howto.techidaily.com/app-wont-open-on-your-infinix-smart-7-here-are-all-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>App Wont Open on Your Infinix Smart 7? Here Are All Fixes | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/audio-liberation-the-ultimate-guide-to-pazeras-extraction-tools-for-2024/"><u>Audio Liberation The Ultimate Guide to Pazera's Extraction Tools for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/comprehensive-overview-discover-the-best-macos-based-music-editors-ranked-top-4-for-2024/"><u>Comprehensive Overview Discover the Best macOS-Based Music Editors Ranked Top 4 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-yellow-tint-reviving-true-colors-on-laptops/"><u>Fixing Yellow Tint: Reviving True Colors on Laptops</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-asus-rog-phone-8-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Asus ROG Phone 8 without Losing Data | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-thinking-about-changing-your-netflix-region-without-a-vpn-on-motorola-moto-g13-drfone-by-drfone-virtual-android/"><u>In 2024, Thinking About Changing Your Netflix Region Without a VPN On Motorola Moto G13? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/introducing-efficient-command-execution-via-keys-w11-edition/"><u>Introducing Efficient Command Execution via Keys, W11 Edition</u></a></li>
<li><a href="https://tech-hub.techidaily.com/maximize-your-chatgpt-utility-explore-the-top-7-chrome-extensions-that-transform-ai-communication-in-browsers/"><u>Maximize Your ChatGPT Utility: Explore the Top 7 Chrome Extensions That Transform AI Communication in Browsers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-low-virtual-memory-situations-in-vmware/"><u>Mitigating Low Virtual Memory Situations in VmWare</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-cant-add-your-folder-now-a-quick-guide-to-onedrive/"><u>Navigating Through 'Can't Add Your Folder Now': A Quick Guide to OneDrive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-geforce-x0001-problem-codes-on-w10w11-systems/"><u>Remedying GeForce X0001 Problem Codes on W10/W11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-0x8007045d-error-in-win1011/"><u>Steps to Resolve 0X8007045D Error in Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-blueprint-constructing-personalized-keys-in-w11/"><u>The Essential Blueprint: Constructing Personalized Keys in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-windows-11-printer-issues-and-solutions-quickly/"><u>Unlock Windows 11 Printer Issues & Solutions Quickly</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/unmasking-the-potential-of-recordcast-for-2024/"><u>Unmasking the Potential of RecordCast for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/usb-boot-media-creation-made-simple-tutorial-on-3-win-11-steps/"><u>USB Boot Media Creation Made Simple – Tutorial on 3 Win 11 Steps</u></a></li>
</ul></div>

