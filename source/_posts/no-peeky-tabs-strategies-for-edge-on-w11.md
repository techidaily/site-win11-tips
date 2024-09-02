---
title: "No Peeky Tabs: Strategies for Edge on W11"
date: 2024-09-01T05:19:57.185Z
updated: 2024-09-02T05:19:57.185Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes No Peeky Tabs: Strategies for Edge on W11"
excerpt: "This Article Describes No Peeky Tabs: Strategies for Edge on W11"
keywords: Edge Tech,W11 SEO,No Tab Abuse,W11 Ranking,Web Performance,Tabs Optimization,Peak Positioning
thumbnail: https://thmb.techidaily.com/895e63c00991de11c3a5bb60d914f7ce63bcb7f1c27750a5c3c9cc5c0ae68538.jpg
---

## No Peeky Tabs: Strategies for Edge on W11

 Microsoft Edge is the default browser in Windows and comes pre-installed on the operating system without any easy way of getting rid of it. The browser uses "tab preloading," which preloads the Start and New Tab page while you sign in to your PC.

 For Edge lovers, it is a boon, but if you don’t use the default browser and prefer something else, it is a waste of resources. Fortunately, you can easily disable Edge's tab preloading in Windows 11\.

## 1\. How to Disable Edge Tab Preloading Using the Group Policy Editor

 Windows Pro, Education, and Enterprise users get the perks of the Group Policy Editor by default. You can use it to configure system policies on your PC and personalize it. If you're on Windows Home, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

 Repeat the following steps to disable Edge tab preloading using the Group Policy Editor:

1. Press **Win + S** to open Windows Search. Type **gpedit.msc** in the text box and press the **Enter** key to open the Group Policy Editor.
2. Click on the **User Configuration** option in the left-hand side pane.
3. Navigate to **Administrative Templates > Windows Components > Microsoft Edge**.
4. Find the “**Allow Microsoft Edge to start and load the Start and New Tab page at Windows startup and each time Microsoft Edge is closed**” policy. Right-click on it and select the **Edit** option from the context menu.  
![Disable Microsoft Edge Tab Preloading Using GPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-gpe.jpg)
5. Click on the **Enabled** radio button.
6. Scroll down and click on the drop-down list next to the **Configure tab preloading** option. Select the **Prevent tab preloading** option.
7. Click on the **Apply** button. Then click on the **OK** button to save the changes.  
![Disable Microsoft Edge Tab Preloading Using GPE 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-gpe-2.jpg)
8. **Exit** the Group Policy Editor window.
9. **Restart** your PC for the policy changes to take effect and disable the tab preloading feature.

## 2\. How to Disable Edge Tab Preloading Using the Registry Editor

 If you use the Home version of Windows 11, it may be easier to take a different approach instead of going through the Group Policy Editor method. If you want, you can tweak the registry manually to disable the Edge tab preloading feature in Windows 11\. Repeat the following steps to do so:

 Before making changes to the Windows Registry, [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) for safety purposes.

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **regedit** in the text box and press the **Enter** key.
2. Go to the address bar at the top and click on it. Paste the following path in the text box and press the **Enter** key:  
HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\Main
3. Go to the right-hand side section and right-click on the empty area. Select **New > DWORD (32-bit) Value**.
4. Click on the newly created DWORD value and name it “**AllowPrelaunch**”.
5. Right-click on the **AllowPrelaunch** value and select the **Modify** option from the context menu.
6. Go to the **Value Data** field and type **0** in it. Set the **Base** to **Hexadecimal** and click on the **OK** button.  
![Disable Microsoft Edge Tab Preloading Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-registry-editor.jpg)

 Now, you need to create a new subkey and add a new DWORD value:

1. Right-click on the Microsoft Edge key and select the **New > Key** option.
2. Name the key “**TabPreloader**” and click on it to select it.
3. Go to the right-hand side section and right-click on it. Select **New > DWORD (32-bit) Value**.
4. Click on the DWORD value and name it “**AllowTabPreloading**”.
5. Right-click on the **AllowTabPreloading** value and select the **Modify** option.
6. Go to the **Value Data** field and type **0** in it. Set the **Base** to **Hexadecimal** and click on the **OK** button.  
![Disable Microsoft Edge Tab Preloading Using Registry Editor 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-registry-editor-2.jpg)
7. **Close** the Registry Editor window.
8. **Restart** your PC to apply the changes made to the registry.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
## 3\. How to Disable Edge Tab Preloading Using CMD or PowerShell

 If you find the Registry Editor method too cumbersome, you can use the Command Prompt or PowerShell to modify the Registry and disable Edge tab preloading. Here’s how to do it:

1. [Open the Command Prompt with administrator privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) on your PC.
2. Execute the following commands to add two new registry entries:  
`reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\Main" /v AllowPrelaunch /t REG_DWORD /d 00000000 /f  
 reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\TabPreloader" /v AllowTabPreloading /t REG_DWORD /d 00000000 /f`
3. **Close** the Command Prompt window and **restart** your PC.  
![Disable Microsoft Edge Tab Preloading Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-cmd.jpg)

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. How to Disable Edge Tab Preloading Using the Ultimate Windows Tweaker App

 You can also use a third-party app like the Ultimate Windows Tweaker to disable Edge tab preloading in Windows 11\. Download the [Ultimate Windows Tweaker](https://www.thewindowsclub.com/ultimate-windows-tweaker-4-windows-10) app and install it on your PC. After that, repeat the following steps:

1. Press **Win + S** to open the Windows Search app. Type **Ultimate Windows Tweaker** and then click on the **Run as administrator** option.
2. Click on the **Search For Tweaks** option. Type “**edge tab**” in the search box and click on the **Go** button.  
![Disable Microsoft Edge Tab Preloading Using Ultimate Windows Tweaker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-ultimate-windows-tweaker.jpg)
3. Click on the **Disable Edge Tab Preloading** checkbox to enable it. Then, click on the **Apply Tweaks** button.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
![Disable Microsoft Edge Tab Preloading Using Ultimate Windows Tweaker 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-ultimate-windows-tweaker-2.jpg)
4. **Close** the Ultimate Windows Tweaker app and **restart** your PC to apply the changes.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Disable Edge Tab Preloading for Good on Windows 11

 Edge tab preloading serves no useful purpose if you use other browsers. You can disable it using the Group Policy Editor or the Registry Editor. Lastly, if you want a GUI app to disable the feature, you can use the Ultimate Windows Tweaker app.

 For Edge lovers, it is a boon, but if you don’t use the default browser and prefer something else, it is a waste of resources. Fortunately, you can easily disable Edge's tab preloading in Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-tips.techidaily.com/ssential-links-for-acquiring-youtube-preview-templates-online/"><u>[New] Essential Links for Acquiring YouTube Preview Templates Online</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unlock-the-power-of-speech-recognition-for-effective-office-documentation-in-microsoft-word/"><u>[New] Unlock the Power of Speech Recognition for Effective Office Documentation in Microsoft Word</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-17-best-lights-and-lighting-equipment-for-youtube-videos/"><u>[Updated] 17 Best Lights and Lighting Equipment for YouTube Videos</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-paving-a-path-to-prominence-instagrams-power-brokers-in-your-sphere/"><u>[Updated] 2024 Approved  Paving a Path to Prominence  Instagram's Power Brokers in Your Sphere</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-2024-approved-the-analytical-approach-to-youtube-content-performance/"><u>[Updated] 2024 Approved  The Analytical Approach to YouTube Content Performance</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-angled-artistry-elevating-youtube-video-editing-skills/"><u>[Updated] Angled Artistry  Elevating YouTube Video Editing Skills</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-get-sweating-to-top-exercromise-anthems-and-rhythms/"><u>[Updated] Get Sweating to Top Exercromise Anthems and Rhythms</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-steps-to-resolve-unusual-self-viewer-mistakes-in-chats/"><u>[Updated] In 2024, Steps to Resolve Unusual Self-Viewer Mistakes in Chats</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-innovative-mac-screen-capture-methods-and-software/"><u>[Updated] Innovative Mac Screen Capture Methods & Software</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-streamline-your-online-presence-using-wirecast-and-facebook-live/"><u>[Updated] Streamline Your Online Presence Using Wirecast and Facebook Live</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-accelerate-creativity-pro-level-lunapic-techniques-unveiled/"><u>2024 Approved  Accelerate Creativity  Pro-Level LunaPic Techniques Unveiled</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-windows-10-game-recording-5-methods/"><u>2024 Approved  Windows 10 Game Recording [5 Methods]</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/a-working-guide-for-pachirisu-pokemon-go-map-on-apple-iphone-7-plus-drfone-by-drfone-virtual-ios/"><u>A Working Guide For Pachirisu Pokemon Go Map On Apple iPhone 7 Plus | Dr.fone</u></a></li>
<li><a href="https://fox-info.techidaily.com/autofocus-plus-next-gen-hdr-image-processing-explained-for-2024/"><u>Autofocus Plus  Next-Gen HDR Image Processing Explained for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-main-panel-of-windows-11-task-manager/"><u>Customizing Main Panel of Windows 11 Task Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-4-paths-to-protect-windows-post-bitlocker/"><u>Discover 4 Paths to Protect Windows Post-BitLocker</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ease-of-access-disabling-security-interrogation-for-windows-11-admin/"><u>Ease of Access: Disabling Security Interrogation for Windows 11 Admin</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-quash-disconnecting-drama-in-discord-on-windows-11-pcs/"><u>How to Quash Disconnecting Drama in Discord on Windows 11 PCs</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-frp-hijacker-by-hagard-download-and-bypass-your-samsung-galaxy-m34-5g-frp-locks-by-drfone-android/"><u>In 2024, FRP Hijacker by Hagard Download and Bypass your Samsung Galaxy M34 5G FRP Locks</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-top-practices-to-personalize-snapchat-video-playback/"><u>In 2024, Top Practices to Personalize Snapchat Video Playback</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/latest-driver-updates-and-downloads-for-your-hp-deskjet-2540-all-in-one-printer/"><u>Latest Driver Updates and Downloads for Your HP Deskjet 2540 All-in-One Printer</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/learn-bengali-online-in-just-10-minutes-a-day/"><u>Learn Bengali Online in Just 10 Minutes a Day</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterclass-creating-multiple-subfolders-with-ease-in-windows/"><u>Masterclass: Creating Multiple Subfolders with Ease in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-window-11s-help-service-disruption/"><u>Mending Window 11'S Help Service Disruption</u></a></li>
<li><a href="https://extra-support.techidaily.com/netizen-chucklers-aid-for-2024/"><u>Netizen Chuckler's Aid for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-error-windows-cant-stop-volume-device/"><u>Overcoming Error: Windows Can’t Stop Volume Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-printmanagement-not-found-issue-quickly/"><u>Overcoming Windows Printmanagement Not Found Issue Quickly</u></a></li>
<li><a href="https://facebook.techidaily.com/peeking-at-potential-renaming-scheme-of-facebook/"><u>Peeking at Potential Renaming Scheme of Facebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/protecting-game-progress-with-epic-saves/"><u>Protecting Game Progress with Epic Saves</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-reactivate-your-preferred-microsoft-store-apps/"><u>Quick Fix: Reactivate Your Preferred Microsoft Store Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-folder-interruption-noise-in-win11/"><u>Reducing Folder Interruption Noise in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-driver-not-supported-errors-in-windows-11/"><u>Solving Driver Not Supported Errors in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-prevalent-anydesk-glitches-in-windows-os/"><u>Solving Prevalent AnyDesk Glitches in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-correct-token-misreference-errors-on-win10win11/"><u>Strategies to Correct Token Misreference Errors on Win10/Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-powershell-workflow-with-script-policy-controls/"><u>Streamline Your PowerShell Workflow with Script Policy Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-to-enhanced-widget-display-interface-in-windows-11/"><u>Transitioning to Enhanced Widget Display Interface in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/triple-threat-tweaks-for-personalized-win11-preferences/"><u>Triple-Threat Tweaks for Personalized Win11 Preferences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-office-solving-windows-activation-issues/"><u>Unlocking Office: Solving Windows Activation Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-taskbars-hidden-features/"><u>Unveiling Windows Taskbar's Hidden Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/xbox-not-launching-regain-control-with-these-tricks/"><u>Xbox Not Launching? Regain Control with These Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/your-pathway-to-elevated-settings-windows-11s-higher-power/"><u>Your Pathway to Elevated Settings: Windows 11'S Higher Power</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>