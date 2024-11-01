---
title: Methods to Mend A Device's Daytime Display Issue
date: 2024-10-26T19:50:01.152Z
updated: 2024-11-01T17:06:06.487Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Methods to Mend A Device's Daytime Display Issue
excerpt: This Article Describes Methods to Mend A Device's Daytime Display Issue
keywords: Fix Screen Brightness,Resolve Display Glitches,Amend Glass Viewer Error,Adjust Daytime Displays,Correct Lighting Issues,Tackle Faulty Shown Content,Improve Visual Display Quality
thumbnail: https://thmb.techidaily.com/80c97e26a42ec85426e926d8a619570205ae66ef3c841d342bad4a1013bf8d86.jpg
---

## Methods to Mend A Device's Daytime Display Issue

 You might often enable dark mode on Windows to reduce eye strain, but it’s quite frustrating when you suddenly can’t switch from dark to normal mode again

 If you’re experiencing this issue, then we’ve got solutions for you. In this article, we’ll explore the five ways to fix your Windows PC when it’s stuck in dark mode.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Configure Settings in the Local Group Policy Editor

 The Local Group Policy Editor (LGPE) is a tool that allows you to configure various settings on your device. Interestingly, you can also use the LGPE to troubleshoot various system issues.

 Now, let’s check out how this tool can help you when your device is stuck in dark mode:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **User Configuration > Administrative Templates > Control Panel > Personalization**.
4. Double-click on the **Prevent changing theme** option on the right-hand side pane.

![Using the Local Group Policy Editor to Prevent Others From Changing the Desktop Theme](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-Local-Group-Policy-Editor-to-Prevent-Others-From-Changing-the-Desktop-Theme.jpg)

 Next, select the **Not Configured** or **Disabled** option on the pop-up screen. From there, click **Apply** and then click **OK** to disable the **Prevent changing theme** option.

 If the issue persists, navigate to the **Personalization** folder as per the previous steps and then disable the following options:

* Prevent changing color and appearance
* Prevent changing desktop background
* Prevent changing screen saver
* Prevent changing color scheme
* Load a specific theme
* Force specific screen saver
* Force a specific visual style file or force Windows Classic

 Finally, restart your device to save these changes.

<!-- affiliate ads begin -->
<span id="1983575">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983575.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983575">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983575.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983575%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983575/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Tweak the Contrast Theme Settings

 You might be stuck in dark mode simply because you’ve enabled the "High contrast" option on Windows. So, let’s check out how you can resolve this problem:

1. Press **Win + I** to open the system settings.
2. Select **Ease of Access** from the options.
3. Click **High contrast** on the left.
4. **Turn off** the button below the **Turn on high contrast** option and check if this resolves the issue.

![Turning off the button below the Turn on high contrast option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/turning-off-the-button-below-the-turn-on-high-contrast-option.jpg)

## 3\. Edit the Relevant Registry Files

 Editing some Registry files could also help you tackle the issue at hand. But to be on the safe side, [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before you proceed. This tool is sensitive and could wreak havoc on your PC if you tweak the wrong keys.

 Now, here’s how to fix the “dark mode” problem using the Registry Editor:

1. Press **Win + R** to open the Run command dialog box.
2. Type **regedit** and press **Enter** to open the Registry Editor. Alternatively, check out [the various ways to access the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Type the following command into the address bar:

HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Themes\Personalize

 Next, double-click on the **AppsUseLightTheme** value on the right-hand side pane.

![Clicking the AppsUseLightTheme value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/clicking-the-appsuselighttheme-value.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2141683/17092" target="_top" id="2141683">
  <img src="//a.impactradius-go.com/display-ad/17092-2141683" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettide.pxf.io/i/5597632/2141683/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Type **0** in the **Value data** box and then click **OK**.

 From there, set the **Value data** as **0** for the **ColorPrevalence**, **EnableTransparency**, and **SystemUsesLightTheme** values. When you finish, restart your device and check if this resolves the problem.

## 4\. Disable Third-Party Apps Like the Auto Dark Mode Tool

 Apps like the [Microsoft Auto Dark Mode](https://apps.microsoft.com/store/detail/auto-dark-mode/XP8JK4HZBVF435) tool switch between dark and light modes at scheduled times. If you’ve configured its settings unknowingly, then it might end up enabling the dark mode feature unexpectedly.

 To resolve the issue, the best solution would be to disable this tool (and any other similar third-party app). Alternatively, you can configure the tool’s settings to your liking. That way, your device will only go into dark mode when you want it to.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043618/7443" target="_top" id="2043618">
  <img src="//a.impactradius-go.com/display-ad/7443-2043618" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043618/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Perform Some Generic Windows-Based Fixes

 Still struggling to resolve the issue? Perhaps the error is caused by corrupted system files. In this case, the best solution is to [repair corrupted Windows files using its built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

 And if all else fails, [update your Windows device](https://www.makeuseof.com/update-windows-manually/) and see if that helps.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137212/26400" target="_top" id="2137212">
  <img src="//a.impactradius-go.com/display-ad/26400-2137212" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137212/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## No More Getting Stuck in Dark Mode

 There’s no denying that the Windows dark mode option is quite convenient. However, being unable to switch from dark to normal mode is quite unpleasant. If your device is stuck in dark mode, try any of the solutions we’ve covered.

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
<li><a href="https://some-approaches.techidaily.com/updated-quick-fixes-utilizing-the-eraser-tool-in-psx/"><u>[Updated] Quick Fixes Utilizing the Eraser Tool in PSX</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/breaking-barriers-gpts-quadruple-boost-to-fame/"><u>Breaking Barriers: GPT's Quadruple Boost to Fame</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decreasing-processor-load-while-engaged-in-virtual-battles/"><u>Decreasing Processor Load While Engaged in Virtual Battles</u></a></li>
<li><a href="https://location-social.techidaily.com/does-find-my-friends-work-on-huawei-nova-y91-drfone-by-drfone-virtual-android/"><u>Does find my friends work on Huawei Nova Y91 | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-samsung-m2070-printer-drivers-fast-and-simple-installation-guide/"><u>Download Samsung M2070 Printer Drivers: Fast and Simple Installation Guide</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-intercept-text-messages-on-itel-a05s-drfone-by-drfone-virtual-android/"><u>How to Intercept Text Messages on Itel A05s | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/lol-gaming-on-air-top-3-recording-methods-for-2024/"><u>LOL Gaming On Air Top 3 Recording Methods for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/loudness-levelers-essential-apps-for-taking-windows-audio-above-100/"><u>Loudness Levelers: Essential Apps for Taking Windows' Audio Above 100%</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-fetching-ip-and-mac-addresses-windows-wise/"><u>Quick Guide: Fetching IP & MAC Addresses, Windows-Wise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-unlocking-telnet-on-wins-os-x/"><u>Step-by-Step Guide: Unlocking Telnet on Wins OS X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-screech-start-scroll-mouse-adjustment-guide/"><u>Stop Screech, Start Scroll: Mouse Adjustment Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-empty-directory-error-code-x80070091/"><u>Troubleshooting Windows' Empty Directory Error Code X80070091</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-data-from-lava-by-fonelab-android-recover-data/"><u>Undelete lost data from Lava</u></a></li>
<li><a href="https://fake-location.techidaily.com/which-is-the-best-fake-gps-joystick-app-on-xiaomi-redmi-note-13-pro-5g-drfone-by-drfone-virtual-android/"><u>Which is the Best Fake GPS Joystick App On Xiaomi Redmi Note 13 Pro 5G? | Dr.fone</u></a></li>
</ul></div>

