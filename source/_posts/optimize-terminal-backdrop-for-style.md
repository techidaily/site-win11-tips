---
title: Optimize Terminal Backdrop for Style
date: 2024-10-08T09:46:22.940Z
updated: 2024-10-15T12:51:27.361Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Optimize Terminal Backdrop for Style
excerpt: This Article Describes Optimize Terminal Backdrop for Style
keywords: Terminal Design Tips,Stylish Terminal Backgrounds,Custom Terminal Themes,Optimal Terminal Aesthetics,Terminal Skin Enhancement,Elegant Terminal Display,Backdrop Improvement in Terminal
thumbnail: https://thmb.techidaily.com/31fd63ab910fdd0bfef9c588934b4c990590f2025d46dff0a5963e90a62a92d8.jpg
---

## Optimize Terminal Backdrop for Style

 Changing the background image of the Windows Terminal is an easy way to customize your command line experience. This adds a personal touch and makes your experience visually appealing.

 This tutorial will explain three methods to change the Terminal background image in Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Change Windows Terminal Background Image

 You can change the background image of Windows Terminal in three ways: using the**Default** option within the Terminal app or manually editing the settings.json file using**File Explorer** and**Run** dialog box. All three methods achieve the same result and are easy to use.

 Using the default option is the simplest way to change your background image while editing the settings.json file provides more control and customization options. Below, we will guide you through each option.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915810/19272" target="_top" id="1915810">
  <img src="//a.impactradius-go.com/display-ad/19272-1915810" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915810/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Change Windows Terminal Background Image via Its Options

 The easiest way to change the background image of Windows Terminal is by using its option. This can be done by opening Windows Terminal and changing settings within the app. Here's how to do it:

 To get started, open the Windows Terminal application first. For this, click on the Windows icon to open the Start menu. Then type**Terminal** into the search box, and select it from the list.

 Once you open the Terminal application, click on the dropdown menu icon in the top left corner, and select the**Settings** option.

 In the settings window's left column, go to**Defaults** . Now move to the right side of the page and tap**Appearance** to expand it.

![Change Windows Terminal Background Image via Default Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-windows-terminal-background-image-via-default-option.jpg)

 Scroll down to the**Background image** section, then click the**Background image path** option. Next, click the**Browse** option and select an image you want to use as a background.

 Click**Open** to confirm your selection. Now you should be able to see the selected image as the background of the terminal.

 You can also copy and paste the file path of an image directly into the Background image path option. Finally, click the**Save** button and the background image will be set.

 To improve the appearance of your image in the Windows Terminal, you can customize it using several options. You can use**Background image stretch mode** to change how the image is resized to fill the window. Further, you can change the**Background image alignment** to adjust the image position, and**Background image opacity** to make it more or less transparent.

 Once you are satisfied with the changes, click the**Save** button in order to apply them. Your custom background image should now be visible in the Windows Terminal.

 If you want to switch to the default image,[reset the Windows Terminal to its default settings](https://www.makeuseof.com/windows-11-reset-terminal-settings/) . This will automatically restore your background to the default image.

## 2\. Change the Windows Terminal Background Image via Windows File Explorer

 Manually editing settings.json is another great way to customize your Windows Terminal background image. For this, you need to open the settings.json file in any text editor, such as Notepad. Here's how to do it:

1. Open Windows File Explorer (see our guide on[how to open File Explorer on a Windows PC](https://www.makeuseof.com/windows-open-file-explorer/) ).
2. Once you're in File Explorer, navigate to your**C:** drive and select the**Users** folder.
3. Locate your**username** in this folder, then open the**AppData** folder and the**Local** folder.
4. In the Local folder, find and open the**Packages** folder.
5. Look for the**Microsoft.WindowsTerminal\_8wekyb3d8bbwe** folder and open it.
6. Finally, in this folder, double-click on**Settings** to open settings.json in any text editor.

 In the settings.json file, you will find a section called**backgroundImage** . You can use**Ctrl + F** to find it quickly.

 This is where you can enter the path of your own image to set as the Windows Terminal background. To do this, first copy the full file path for the image you want to use, including the file name.

![How to Change Windows Terminal Background Image From Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/how-to-change-windows-terminal-background-image-from-windows-file-explorer.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118305/7443" target="_top" id="2118305">
  <img src="//a.impactradius-go.com/display-ad/7443-2118305" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118305/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then paste this path into the**backgroundImage** section of settings.json. Remember to include a comma (**,**) after the path, as shown in the image above.

 Once you have pasted the path of your image, save the settings file and close the text editor. To apply this new background image, simply restart your Windows Terminal. The new background image should be displayed on the terminal window.

 You can adjust the image transparency using the same method. Simply input values for the**backgroundImageOpacity** parameters to modify the settings. These additional settings allow you to personalize your Windows Terminal background image even further.

 Restart Windows Terminal for the changes to take effect. In this way, you can easily customize your Windows Terminal background image using the settings.json file.

## 3\. Change the Windows Terminal Background Image Using the Run Command

 The Run Command can also help you change your Windows Terminal background image. Instead of searching for the settings.json file in Windows File Explorer, you can directly access and modify it using this tool.

 Follow these instructions to customize your Windows Terminal background image using the Run Command tool:

1. Right-click on Start and select**Run** from the menu list. If you prefer using shortcut keys, press**Win + R** on your keyboard to open the tool directly.
2. In the text box, type the following command and press Enter:  
`%localappdata%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState`
3. This will open the Local State folder containing the settings.json file. Right-click on**Settings** and select**Open with** \>**Notepad** .  
![Change Windows Terminal Background Image From Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-windows-terminal-background-image-from-windows-file-explorer.jpg)
4. Scroll down to the**backgroundImage** section and replace the image path with your own.

<!-- affiliate ads begin -->
<span id="1993645">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993645.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993645">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993645.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993645%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993645/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Then press**Ctrl + S** on your keyboard to save the changes.
6. Close Notepad, then open Windows Terminal to see your new background image.

 You’re done! Now you know how to customize your Windows Terminal background image using the Run Command tool. You can further explore the settings.json file or use other tools to[customize and personalize your Windows Terminal](https://www.makeuseof.com/windows-terminal-customization/) .

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134239/18498" target="_top" id="2134239">
  <img src="//a.impactradius-go.com/display-ad/18498-2134239" border="0" alt="https://techidaily.com" width="721" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134239/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Set a New Background Image for Windows Terminal

 It's easy to customize your Windows Terminal by adding or changing the background image. All you need to do is access the settings.json file, where you can also adjust your image's transparency. Just remember to restart Windows Terminal after making changes. Read this guide to learn how to customize your Windows Terminal background image easily.

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
<li><a href="https://fox-http.techidaily.com/new-2024-approved-the-ultimate-guide-to-iphone-burst-mode-shooting/"><u>[New] 2024 Approved The Ultimate Guide to iPhone Burst Mode Shooting</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-avoid-every-interruption-the-ultimate-guide-to-7-adblocking-tools/"><u>[Updated] Avoid Every Interruption The Ultimate Guide to 7 AdBlocking Tools</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-exploring-the-finest-8-no-cost-open-source-video-communication-apps/"><u>[Updated] Exploring the Finest 8 No-Cost, Open Source Video Communication Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-computer-experience-with-these-6-tools/"><u>Accelerate Your Computer Experience with These 6 Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-visual-fields-in-windows-systems/"><u>Altering Visual Fields in Windows Systems</u></a></li>
<li><a href="https://extra-hints.techidaily.com/crafting-captivating-intros-for-podcasts-for-2024/"><u>Crafting Captivating Intros for Podcasts for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-and-defusing-error-0x80070570-saving-your-damaged-files-in-windows-11/"><u>Deciphering and Defusing Error 0X80070570: Saving Your Damaged Files in Windows 11</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-insights-at-toms-hardware-store-comprehensive-guides/"><u>Expert Insights at Tom’s Hardware Store - Comprehensive Guides</u></a></li>
<li><a href="https://howto.techidaily.com/fixes-for-apps-keep-crashing-on-realme-narzo-n53-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixes for Apps Keep Crashing on Realme Narzo N53 | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-jailbreak-icloud-locked-iphone-14-pro-by-drfone-ios/"><u>How to jailbreak iCloud locked iPhone 14 Pro</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-a-network-locked-oppo-a78-5g-phone-by-drfone-android/"><u>How to Unlock a Network Locked Oppo A78 5G Phone?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correct-device-opens-issue-on-audacity-in-windows/"><u>Steps to Correct Device Opens Issue on Audacity in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-teamsters-downtime-on-windows-11-10/"><u>Troubleshooting Teamsters Downtime on Windows 11, 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-vac-denied-access-in-steam-windows/"><u>Troubleshooting VAC Denied Access in Steam Windows</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unlock-new-possibences-in-private-messaging-utilize-duckduckgos-advanced-ai-chat-features-today/"><u>Unlock New Possibences in Private Messaging – Utilize DuckDuckGo's Advanced AI Chat Features Today</u></a></li>
</ul></div>

