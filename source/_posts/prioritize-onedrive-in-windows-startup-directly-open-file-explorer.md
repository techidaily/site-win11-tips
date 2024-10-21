---
title: "Prioritize OneDrive in Windows Startup: Directly Open File Explorer"
date: 2024-10-20T04:02:43.886Z
updated: 2024-10-20T19:31:47.993Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Prioritize OneDrive in Windows Startup: Directly Open File Explorer"
excerpt: "This Article Describes Prioritize OneDrive in Windows Startup: Directly Open File Explorer"
keywords: OneDrive Quick Access,Startup OneDrive,OneDrive Files Opener,Direct OneDrive Launch,Windows Startup Drives,File Explorer OneDrive,Prioritize Office Storage
thumbnail: https://thmb.techidaily.com/a9309627364580efd732c4c8f6349cf67c0dc25ea886bdb64936441ab4225274.png
---

## Prioritize OneDrive in Windows Startup: Directly Open File Explorer

 When you launch Windows File Explorer, it automatically takes you to the "Quick Access" view. This page displays shortcuts to recently accessed folders and files and lists your favorite folders. It might be convenient for some users but not for others who prefer easy access to their cloud storage.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Use the Folder Options

 If you want to make OneDrive the starting point of your File Explorer, you can do so using folder options. Here's how to do it:

1. Open the Start menu and type **File Explorer** in the search box. When the File Explorer icon appears, click it to launch the app. You can also use **Win + E** to open the program quickly.
2. In the File Explorer window, look for **See more** (three dots) at the top. Clicking on it opens the Folder Options dialog box.  
![Open Folder Options in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-folder-options-in-file-explorer.jpg)
3. On the General tab, click the **Open File Explorer to** drop-down menu and select "Username Personal". Here, "Username" refers to your Windows account name.  
![Open File Explorer to OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-file-explorer-to-onedrive.jpg)
4. Click **Apply** \> **OK** to close the dialog box.

 From now on, opening File Explorer will automatically launch OneDrive rather than Quick Access.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052062/7443" target="_top" id="2052062">
  <img src="//a.impactradius-go.com/display-ad/7443-2052062" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052062/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Using the Registry Editor

 You can also use the Registry Editor to set OneDrive as your default File Explorer view. But be warned: if you make an incorrect change to the system registry, you could damage your computer. We recommend [backing up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 Once backed up, follow these steps to make OneDrive the default view:

1. [Open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the text box and hit **Enter**.
3. If you're prompted for permission, select **Yes** to continue. The Registry Editor window will open.
4. In the Registry Editor window, navigate to this path:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. In the right pane, locate and double-click the **LaunchTo** entry. If the entry isn't present, you'll need to create it. For that, right-click on the **Advanced** folder and select **New > DWORD (32-bit) Value**. Name the value "LaunchTo" and press Enter. Doing so will create a new DWORD in the registry.  
![Set File Explorer to Open OneDrive Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/set-file-explorer-to-open-onedrive-using-registry.jpg)
6. Double-click on this newly created value and set its value to **4**.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398449/3022" target="_top" id="398449">
  <img src="//a.impactradius-go.com/display-ad/3022-398449" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398449/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Click **OK** and close the registry window.

 After that, restart your computer for the changes to take effect. Once your PC restarts, launch File Explorer. With this method, you will launch File Explorer directly to your cloud storage without navigating through Quick Access.

<!-- affiliate ads begin -->
<span id="1834903">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1834903.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1834903">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1834903.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1834903%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1834903/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Using a Reg File

 The third and final method to set OneDrive as the default view involves using a reg file. It contains the necessary instructions that modify the registry on your behalf. So, if you're not comfortable using the registry editor, this is the right way to go.

 To create the reg file, follow these steps:

1. Right-click on your desktop and select **New > Text Document**.
2. Name the file **OneDrive.reg** and hit **Enter**.
3. Now open the file in a text editor such as Notepad.
4. Copy and paste the following code into the text document:  
`<code>Windows Registry Editor Version 5.00  

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced]  
"LaunchTo"=dword:00000004`
5. After pasting the given code, click **File** \> **Save as**.
6. In the Save as dialog box, select **All files** from the Save as type drop-down menu and hit Enter. Make sure the file is saved as a **.reg** file and not as a .txt file.  
![Open File Explorer to OneDrive Using REG File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-file-explorer-to-onedrive-using-reg-file.jpg)
7. Double-click the REG file you just created. If you're prompted for permission to change your computer, click **Yes**.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484945/16446" target="_top" id="1484945">
  <img src="//a.impactradius-go.com/display-ad/16446-1484945" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484945/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. Finally, restart your computer for the changes to take effect.

 After your system restarts, launch File Explorer. You'll see OneDrive as the main view instead of Quick Access.

## Set File Explorer to Open OneDrive Instead of Quick Access

 There you have it; three different methods to make OneDrive your default File Explorer view. If you like, you can also change other folder views, such as Downloads or This PC, using the same techniques we discussed above. I hope this guide helped you get things done quickly and easily.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-access.techidaily.com/new-in-2024-best-focus-effects-iphone-vs-android-photo-solutions/"><u>[New] In 2024, Best Focus Effects IPhone vs Android Photo Solutions</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-2024-approved-how-to-obtain-perfect-photos-without-marks/"><u>[Updated] 2024 Approved How To Obtain Perfect Photos Without Marks</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-techbite-provision-recorder-assessment/"><u>[Updated] In 2024, TechBite ProVision Recorder Assessment</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-ultimate-guide-to-free-and-premium-short-video-clips/"><u>[Updated] In 2024, Ultimate Guide to Free & Premium Short Video Clips</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-quieting-unwanted-sounds-obs-audio-issue-fixed/"><u>[Updated] Quieting Unwanted Sounds OBS Audio Issue Fixed</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-unending-chats-strategies-for-continuous-snapstreaks/"><u>2024 Approved Unending Chats - Strategies for Continuous Snapstreaks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/compre-written-remedy-for-windows-0x0000004e/"><u>Compre Written Remedy for Windows' 0X0000004E</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-guide-to-effective-windows-ping-usage/"><u>Comprehensive Guide to Effective Windows Ping Usage</u></a></li>
<li><a href="https://article-tips.techidaily.com/custom-whatsapp-ringtone-guide-on-ios-devices-for-2024/"><u>Custom WhatsApp Ringtone Guide on iOS Devices for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dxgidll-reemerge-easy-fixes-for-windows-11-users/"><u>Dxgi.dll Reemerge: Easy Fixes for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-the-capabilities-of-microsoft-family-safety/"><u>Exploring the Capabilities of Microsoft Family Safety</u></a></li>
<li><a href="https://win11-tips.techidaily.com/igniting-windows-11s-secret-bar-queries/"><u>Igniting Windows 11'S Secret Bar Queries</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-fix-when-apple-account-locked-from-iphone-12-by-drfone-ios/"><u>In 2024, How to Fix when Apple Account Locked From iPhone 12?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ispoofer-is-not-working-on-realme-narzo-n53-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, iSpoofer is not working On Realme Narzo N53? Fixed | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-family-safety-a-quick-primer/"><u>Microsoft Family Safety: A Quick Primer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefining-tech-trends-artificial-intelligence-and-windows-11/"><u>Redefining Tech Trends: Artificial Intelligence & Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-update-issue-error-code-0xc004f050/"><u>Resolving Windows Update Issue: Error Code 0xC004F050</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-unrelated-edgers-in-tasker/"><u>Understanding Unrelated Edgers in Tasker</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-honor-x50iplus-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On Honor X50i+ | Dr.fone</u></a></li>
</ul></div>

