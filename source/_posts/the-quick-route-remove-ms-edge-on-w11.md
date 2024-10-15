---
title: "The Quick Route: Remove MS Edge on W11"
date: 2024-10-12T09:13:47.614Z
updated: 2024-10-14T16:25:39.240Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes The Quick Route: Remove MS Edge on W11"
excerpt: "This Article Describes The Quick Route: Remove MS Edge on W11"
keywords: Removing Edge Bloatware,Windows 11 Edge Uninstall,Delete Microsoft Edge,Free Up PC Space,W11 Edge-Less System,Streamline Windows 11,Optimize Browser Choices
thumbnail: https://thmb.techidaily.com/9e9b99a6d9a89547d11f6e0d3b7ad397a8c45980a1b807a51ada942660956a43.jpg
---

## The Quick Route: Remove MS Edge on W11

 Although Microsoft Edge has made significant progress in recent years, it still lags far behind its biggest rival—Google Chrome. If you’re someone who does not like using Microsoft Edge, you may want to get rid of the browser entirely.

 It’s no secret that Microsoft wants users to use its own browser on Windows 11\. To that end, the company has made it difficult to remove the browser from Windows 11\. However, it’s still possible to do so. Here we'll show you three different ways to uninstall Microsoft Edge from your Windows 11 PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Uninstall Microsoft Edge Using the Command Prompt

 You can uninstall Microsoft Edge from your PC by running a few commands in the command prompt. The process requires you to know the version number of Microsoft Edge on your computer. Once you have that, you can get rid of the browser.

Here are the steps you need to follow.

1. Open Microsoft Edge on your PC.
2. Click the**three-dot menu icon** in the top right corner and select**Help and feedback > About Microsoft Edge** .
3. Copy Microsoft Edge's version number from the**About** section.  
![Check Microsoft Edge Version Number](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Microsoft-Edge-Version-Number.jpg)
4. Press**Win + X** and select**Terminal (Admin)** from the menu that appears.
5. Select**Yes** when the User Account Control (UAC) prompt shows up.
6. In the console, run the following commands to navigate to the directory where Microsoft Edge is installed:  
`cd/  
cd %Program Files (x86)%\Microsoft\Edge\Application\EdgeVersion\Installer`  
 Replace**EdgeVersion** in the above command with the actual version number noted earlier.
7. Paste the following command and press**Enter** to uninstall Microsoft Edge.  
`setup --uninstall --force-uninstall --system-level`  
![Uninstall Microsoft Edge Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Command-Prompt.jpg)

 Once you run the above commands, Microsoft Edge will be removed from your PC. If you want to install the browser in the future, you can do so by downloading it from the Microsoft Store.

 If you'd like to get more out of this tool, be sure to check out[the Windows Command Prompt commands you must know](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/) .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087234/19272" target="_top" id="2087234">
  <img src="//a.impactradius-go.com/display-ad/19272-2087234" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087234/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. How to Uninstall Microsoft Edge Using Windows PowerShell

 Like Command Prompt, you can also use Windows PowerShell to uninstall Microsoft Edge from your Windows 11 PC. Unlike the previous method, this one does not require you to know Microsoft Edge's version number. Here's how it works.

1. Press**Win + S** to open the search menu. Type in**Windows PowerShell** and select**Run as administrator** .
2. Select**Yes** when the[User Account Control (UAC)](https://www.makeuseof.com/tag/user-account-control-windows-10/) prompt appears.
3. Paste the following command and press**Enter** .  
`get-appxpackage *edge*`  
![Uninstall Microsoft Edge With Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Windows-PowerShell-1.jpg)
4. Highlight the text next to**PackageFullName** and press**Ctrl + C** to copy it.

5. Run the following command to uninstall Microsoft Edge.  
`Remove-appxpackage <PackageFullName>`  
 Replace**<PackageFullName>** in the above command with the package name copied earlier.

 Once you execute the above command, Microsoft Edge will be uninstalled.

<!-- affiliate ads begin -->
<span id="1982508">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982508.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982508">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982508.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982508%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982508/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. How to Uninstall Microsoft Edge Beta, Dev, or Canary Channel Builds Using the Settings App

 Unlike the stable version, removing a preview build of Microsoft Edge is relatively simple. You can uninstall it just like any other app. Here's how to do it using[Windows 11 Settings app](https://www.makeuseof.com/windows-11-settings-whats-new/) .

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Apps** tab and click on**Installed apps** .
3. Scroll down to locate Microsoft Edge's preview build.
4. Click the**three-dot menu icon** next to it and select**Uninstall** .
5. Select**Uninstall** again when the confirmation pop-up appears.  
![Uninstall Microsoft Edge Beta From Windows 11 Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Beta-From-Windows-11-1.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918703/19272" target="_top" id="1918703">
  <img src="//a.impactradius-go.com/display-ad/19272-1918703" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918703/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Aside from the Settings app, you can uninstall the browser from the Start menu or the Control Panel. See our guide to learn different[ways to uninstall built-in apps on Windows 11](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/) .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043603/7443" target="_top" id="2043603">
  <img src="//a.impactradius-go.com/display-ad/7443-2043603" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043603/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Stop Microsoft Edge From Reinstalling on Windows 11

 Although uninstalling Edge from your computer is easy, it does not prevent newer Windows updates from potentially reinstalling the browser. To get around this, you need to[edit a few registry files](https://www.makeuseof.com/windows-registry-file-guide/) on your PC. For that, use the following steps:

1. Press**Win + R** to open the Run dialog box.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window that appears, navigate to**HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft** key.
5. Right-click on the**Microsoft** key, go to**New** , and select**Key** from the submenu. Rename the key to**EdgeUpdate** .
6. Right-click on the**EdgeUpdate** key and select**New > DWORD (32-bit) Value** . Rename the DWORD to**DoNotUpdateToEdgeWithChromium** .
7. Double-click on the newly created DWORD and change its value data to**1** . Then, hit**OK** .  
![Edit DWORD in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/edit-dword-in-registry-editor.jpg)

 Once you complete the above steps, Windows will not reinstall Microsoft Edge with future updates.

## Get Rid of Microsoft Edge

 With Windows 11, Microsoft tried everything possible to entice users to switch to Microsoft Edge. Unfortunately, it hasn't worked out very well, as many people still prefer to use alternatives like Google Chrome. If you are one of them, you can get rid of Microsoft Edge using the steps outlined above.

 Now that you've uninstalled Microsoft Edge, you might want to make your preferred web browser the default option on Windows 11.

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
<li><a href="https://facebook-video-content.techidaily.com/new-freefb-audio-treasures-collection/"><u>[New] FreeFB Audio Treasures Collection</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-essential-anime-openers-revisited/"><u>2024 Approved Essential Anime Openers Revisited</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-heartfelt-outro-samples-your-budget-our-designs/"><u>2024 Approved Heartfelt Outro Samples Your Budget, Our Designs</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-the-ultimate-app-review-for-crafting-unique-reels/"><u>2024 Approved The Ultimate App Review for Crafting Unique Reels</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-updated-list-of-conversation-catalysts-for-listener-retention/"><u>2024 Approved Updated List of Conversation Catalysts for Listener Retention</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-invalid-temp-path-on-w11-pc/"><u>Correcting Invalid Temp Path on W11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-lock-screen-timeout-errors/"><u>Fixing Windows Lock Screen Timeout Errors</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fake-gps-on-realme-narzo-60-5g-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>How To Fake GPS On Realme Narzo 60 5G For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-4-ways-to-trace-samsung-galaxy-a15-5g-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 4 Ways to Trace Samsung Galaxy A15 5G Location | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-management-of-dxgierror-in-devices/"><u>Mastering Management of DXGI_Error in Devices</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-tech-insights-with-toms-hardware-analyses/"><u>Mastering Tech Insights with Tom's Hardware Analyses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-common-update-failure-code-0xc004f050/"><u>Overcoming Common Update Failure Code 0xC004F050</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sparkle-your-screen-with-7-holiday-windows-tweaks/"><u>Sparkle Your Screen with 7 Holiday Windows Tweaks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/studio-2-spotlight-microsofts-pursuit-of-perfection-in-design/"><u>Studio 2 Spotlight: Microsoft's Pursuit of Perfection in Design</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-outlook-schedule-on-windows-pcs/"><u>Tailoring Your Outlook Schedule on Windows PCs</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-quiet-guide-to-livestreaming-yourself-on-instagram-for-2024/"><u>The Quiet Guide to Livestreaming Yourself on Instagram for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-boosting-virtual-memory-on-windows-11/"><u>The Ultimate Guide to Boosting Virtual Memory on Windows 11</u></a></li>
</ul></div>

