---
title: How to Change the Windows Terminal Background Image
date: 2024-10-12T12:11:34.310Z
updated: 2024-10-15T03:32:50.578Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Change the Windows Terminal Background Image
excerpt: This Article Describes How to Change the Windows Terminal Background Image
keywords: Change Terminal Color,WinTerm Setback Pic,Adjust WinTerm Backdrop,Update WinTerm Image,Customize Terminal Theme,Personalize Windows Terminal,Alter Terminal Background
thumbnail: https://thmb.techidaily.com/f755ebc6fd74e541b86783b8f288eb9ebe73ceda235653be011e1c74d43e6c3e.jpg
---

## How to Change the Windows Terminal Background Image

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130528/26400" target="_top" id="2130528">
  <img src="//a.impactradius-go.com/display-ad/26400-2130528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130528/26400" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<span id="2127886">
					<video width="576" height="1024" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2127886.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2127886">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2127886.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2127886%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2127886/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

 Then paste this path into the**backgroundImage** section of settings.json. Remember to include a comma (**,**) after the path, as shown in the image above.

 Once you have pasted the path of your image, save the settings file and close the text editor. To apply this new background image, simply restart your Windows Terminal. The new background image should be displayed on the terminal window.

 You can adjust the image transparency using the same method. Simply input values for the**backgroundImageOpacity** parameters to modify the settings. These additional settings allow you to personalize your Windows Terminal background image even further.

 Restart Windows Terminal for the changes to take effect. In this way, you can easily customize your Windows Terminal background image using the settings.json file.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137227/26400" target="_top" id="2137227">
  <img src="//a.impactradius-go.com/display-ad/26400-2137227" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137227/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://25home.pxf.io/c/5597632/2148638/16836" target="_top" id="2148638">
  <img src="//a.impactradius-go.com/display-ad/16836-2148638" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148638/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Then press**Ctrl + S** on your keyboard to save the changes.
6. Close Notepad, then open Windows Terminal to see your new background image.

 You’re done! Now you know how to customize your Windows Terminal background image using the Run Command tool. You can further explore the settings.json file or use other tools to[customize and personalize your Windows Terminal](https://www.makeuseof.com/windows-terminal-customization/) .

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
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-video-exporting-youtube-content-directed-to-facebook-stream/"><u>[Updated] 2024 Approved Video Exporting YouTube Content Directed to Facebook Stream</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-immersive-experience-creating-rich-skype-recordings-using-obs/"><u>[Updated] In 2024, Immersive Experience Creating Rich Skype Recordings Using OBS</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/3-easy-ways-to-factory-reset-a-locked-iphone-se-2020-without-itunes-by-drfone-ios/"><u>3 Easy Ways to Factory Reset a Locked iPhone SE (2020) Without iTunes</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-unlock-from-apple-iphone-x-how-to-fix-it-by-drfone-ios/"><u>Apple ID Unlock From Apple iPhone X? How to Fix it?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719316562070-boosting-window-light-in-windows-11-top-solutions-explored/"><u>Boosting Window Light in Windows 11: Top Solutions Explored!</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-oppo-reno-11-5g-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Oppo Reno 11 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-you-dont-have-permission-to-view-this-file-error-on-windows/"><u>How to Fix the “You Don’t Have Permission to View This File” Error on Windows</u></a></li>
<li><a href="https://some-guidance.techidaily.com/huge-savings-alert-for-black-friday-buyers-can-get-up-to-70-off-on-macxdvds-premium-3-in-1-media-suite-package/"><u>Huge Savings Alert for Black Friday: Buyers Can Get Up to 70% Off on MacXDVD's Premium 3-in-1 Media Suite Package!</u></a></li>
<li><a href="https://some-guidance.techidaily.com/i-migliori-10-strumenti-gratuiti-ai-per-la-post-produzione-video-su-windows-and-mac-una-guida-completa/"><u>I Migliori 10 Strumenti Gratuiti AI per La Post-Produzione Video Su Windows & Mac: Una Guida Completa</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-6-best-apps-to-remove-objects-from-photo-on-iphone/"><u>In 2024, 6 Best Apps to Remove Objects From Photo on iPhone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/masterfully-adding-premium-quality-srt-subtitles-to-your-mkv-videos-for-an-optimal-viewing-experience/"><u>Masterfully Adding Premium Quality SRT Subtitles to Your MKV Videos for an Optimal Viewing Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/past-keys-to-future-launches-utilizing-windows-7-for-windows-11-bootup/"><u>Past Keys to Future Launches: Utilizing Windows 7 for Windows 11 Bootup</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/recovering-from-a-mistaken-tiktok-reload/"><u>Recovering From a Mistaken TikTok Reload</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-updater-roadblock-0x80073712/"><u>Resolving Updater Roadblock: 0X80073712</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-installation-of-windows-chatgpt/"><u>Step-by-Step Installation of Windows ChatGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-windows-11s-notepad-with-copilot/"><u>Supercharge Windows 11’S Notepad With Copilot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-restoring-accessibility-of-displays-in-nvidia-software/"><u>Tips for Restoring Accessibility of Displays in Nvidia Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-windows-strategy-for-sound-graph-segregation/"><u>Understanding Windows' Strategy for Sound Graph Segregation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winrars-hash-harmony-six-ways-to-ensure-correct-sums/"><u>WinRAR's Hash Harmony: Six Ways to Ensure Correct Sums</u></a></li>
</ul></div>

