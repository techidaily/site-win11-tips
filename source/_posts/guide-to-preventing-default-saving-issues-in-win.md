---
title: Guide to Preventing Default Saving Issues in Win
date: 2024-08-28T01:15:28.645Z
updated: 2024-08-29T01:15:28.645Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Preventing Default Saving Issues in Win
excerpt: This Article Describes Guide to Preventing Default Saving Issues in Win
keywords: Win Save Fix Guide,Avoid Default Save Errors,Prevent Windows Saves Glitches,Troubleshoot Win Default Save,Solve Win Save Issues,Optimize Win Save Functionality,Stop Win Saving Failures
thumbnail: https://thmb.techidaily.com/19a61f5995d579c8b7ad201fc517afd84cc338957aeb2d8c12a802a23a178f47.jpg
---

## Guide to Preventing Default Saving Issues in Win

 Users have reported error 0x80070005 or 0x80070539 arises when they try to set new apps to save to different external drive locations with Settings. Those error codes have the same message that says, “We couldn’t set your default save location.” This means users can’t change the default save location for apps.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

## 1\. Set Your User Account to Administrator

 If you’re utilizing a standard Windows account, [change your user account type](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) to an administrative one. A standard user account will prevent you from applying any more complicated system changes. Changing the save location for apps is something you might need admin privileges for.

![The Account type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-account-type-window.jpg)

## 2\. Rename the WindowsApps Directory

 This error can arise because the WindowsApps folder where apps save is corrupted. Renaming the WindowsApps folder on the drive or partition you want to save apps can address such an issue. To do so, rename that folder as follows:

1. If you’re trying to set apps to save on an external drive, connect that hard drive to your PC.
2. [Open the File Explorer folder navigator](https://www.makeuseof.com/windows-open-file-explorer/) and click **This PC**.
3. Double-click the drive/partition you want to set as your default save location for apps.
4. Then, right-click on the WindowsApps folder and select its **Rename** context menu option. You should find that directory within the drive’s root directory.  
![The Rename option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-button.jpg)
5. Rename the folder to **WindowsApps.old** and press **Enter**.
6. Thereafter, try changing the default save location for apps again via Settings.

 If that still doesn’t work, then proceed to the next resolution.

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Delete or Rename the WpSystem Folder

 Many users confirm that renaming or deleting the WpSystem folder fixes error 0x80070005\. WpSystem is a folder created to store app data. Try renaming that folder to **WpSystem.old** on the drive you can’t set to be a save location for apps, as outlined for the previous method. The WpSystem will be in the same directory as the WindowsApps folder.

 Alternatively, delete the WpSystem folder. You can [erase a file or folder in Explorer](https://www.makeuseof.com/windows-11-delete-select-files/) by right-clicking it and selecting **Delete**. If you can’t find that folder or this potential solution doesn’t work, try the next resolution.

![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-option.jpg)

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Set Full System Permission for the System Volume Folder

 Setting full permission for the System Volume folder is another confirmed fix for error 0x80070005\. Follow these steps to set full permission for the System Volume directory:

1. Go into File Explorer and click the three-dot **See more** menu > **Options**. In Windows 10, click **Options** on the **View** tab.
2. Select **View** on the Folder Options window.
3. Deselect the **Hide protected operating system files (Recommended)** option.  
![The Hide protected operating system files checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hide-protected-operating-system-files.jpg)
4. Select the **Show hidden files, folders and drives** radio button.
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
5. Click **Apply** to save the new Explorer settings.

1. Select the drive you need to set as the default save location for apps.
2. Right-click the System Volume Information folder and select **Properties**.
3. Click **Security > Advanced** to bring up an Advanced Security Settings window.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/security-tab.jpg)
4. Press the **Continue** button.
5. Next, click **Add** to view a Permission Entry window.

1. Click the **Select a principal** option.
2. Input **SYSTEM** inside the object name box.  
![The Select User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-user-group.jpg)
3. Click on the **OK** button.
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
4. Select the **Full control permission** setting.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-option.jpg)
5. Then select the **OK** options on the Permission Entry and Advanced Security Settings windows.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->

 Close all remaining open windows. Then, restart your PC and try changing the default save location.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
## Set a New Default Save Location in Windows 11/10

 Many users have needed to fix error 0x80070005 and have done so by applying the potential solutions in this guide. The WpSystem folder is often the source of the error, and resolution two is the most widely confirmed method for fixing this issue.

 However, some users have also fixed the issue by applying the less widely cited fourth method.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-bridging-virtuality-business-applications-in-vr/"><u>[New] 2024 Approved  Bridging Virtuality  Business Applications in VR</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-transformative-content-strategies-for-tiktok-success/"><u>[New] 2024 Approved  Transformative Content Strategies for TikTok Success</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-vimeo-vs-youtube-vs-dailymotion-which-platform-is-the-one/"><u>[New] 2024 Approved  Vimeo vs YouTube vs Dailymotion  Which Platform Is the One?</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-the-ultimate-glossary-of-youtube-shorts-terms/"><u>[New] The Ultimate Glossary of YouTube Shorts Terms</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-leading-the-pack-in-multi-media-posting-on-instagram/"><u>[Updated] 2024 Approved  Leading the Pack in Multi-Media Posting on Instagram</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-crucial-6-platforms-enhancing-commercial-relations/"><u>2024 Approved  Crucial 6 Platforms Enhancing Commercial Relations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-folder-size-evaluation-using-powershell-commands/"><u>Demystifying Folder Size Evaluation Using PowerShell Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/designing-individualized-win11-screensavers/"><u>Designing Individualized Win11 Screensavers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-alternatives-to-cortana-in-windows-10/"><u>Exploring Alternatives to Cortana in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-portable-windows-devices/"><u>Five Portable Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-microsoft-store-error-code-0x80073cf3-on-win11/"><u>Fixing Microsoft Store Error Code 0X80073CF3 on Win11</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-life360-on-windows-pc-for-apple-iphone-12-drfone-by-drfone-virtual-ios/"><u>How to Use Life360 on Windows PC For Apple iPhone 12? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-and-fixing-windows-headset-mic-glitches/"><u>Identifying & Fixing Windows Headset Mic Glitches</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-capturing-the-horizon-expert-techniques-in-drone-filmmaking/"><u>In 2024, Capturing the Horizon  Expert Techniques in Drone Filmmaking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-windows-tech-for-premium-macos-experience/"><u>Integrating Windows Tech for Premium macOS Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-device-conflict-multiple-ms-logins/"><u>Mastering Device Conflict: Multiple MS Logins</u></a></li>
<li><a href="https://extra-tips.techidaily.com/navigating-the-intricacies-of-previewing-off-facebook-activities/"><u>Navigating the Intricacies of Previewing Off-Facebook Activities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-low-valorant-download-rate-woes-in-windows/"><u>Overcoming Low Valorant Download Rate Woes in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quieten-the-high-contrast-in-windows-ui/"><u>Quieten the High Contrast in Windows UI</u></a></li>
<li><a href="https://win-dash.techidaily.com/realtek-card-reader-for-windows-11-fast-download-and-easy-installation-guide/"><u>Realtek Card Reader for Windows 11: Fast Download and Easy Installation Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-the-looks-like-youre-stranded-from-xbox-app-windows/"><u>Removing the 'Looks Like You're Stranded' From Xbox App Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-system-5-must-have-pc-tools/"><u>Streamline Your System: 5 Must-Have PC Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-realign-windows-desktop-elements/"><u>Swiftly Realign Windows Desktop Elements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-to-concealreveal-windows-security-zones/"><u>Tactics to Conceal/Reveal Windows Security Zones</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/the-leading-8-linux-programs-for-screenshots-for-2024/"><u>The Leading 8 Linux Programs for Screenshots for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-quick-and-easy-route-to-your-pcs-credential-vault-on-win11/"><u>The Quick and Easy Route to Your PC's Credential Vault on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-workflow-top-7-methods-for-windows-11-excellence/"><u>Transform Your Workflow: Top 7 Methods for Windows 11 Excellence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-for-smooth-captions-essential-tips-on-windows-10/"><u>Troubleshoot for Smooth Captions: Essential Tips on Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-path-related-issues-in-windows-os/"><u>Troubleshooting Path-Related Issues in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/undo-customization-reverting-win11-user-permissions/"><u>Undo Customization: Reverting Win11 User Permissions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-pagefilesys-in-windows-should-you-delete-it/"><u>What Is Pagefile.sys in Windows? Should You Delete It?</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>