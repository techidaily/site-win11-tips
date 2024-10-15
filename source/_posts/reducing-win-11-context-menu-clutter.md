---
title: Reducing Win 11 Context Menu Clutter
date: 2024-10-14T08:28:45.904Z
updated: 2024-10-15T04:55:38.750Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reducing Win 11 Context Menu Clutter
excerpt: This Article Describes Reducing Win 11 Context Menu Clutter
keywords: Minimize Win11 UI,Clean Win11 Menu,Organize Win11 Icons,Simplify Win11 Menu,Declutter Win11 Menu,Streamline Win11 Commands,Tidy Up Win11 Tools
thumbnail: https://thmb.techidaily.com/00e6416ee52e959bd4b417b088ce280ff84f1d381398bcbde7f933c522e87849.jpg
---

## Reducing Win 11 Context Menu Clutter

 Windows 11 comes with a fresh new look and has mainly got a positive response for its new interface. However, there are a couple of features that are not being welcomed by the users. For instance, the addition of the "show more options" entry to the right-click context menu.

 Although it was introduced to simplify things, many users still prefer the old context menu from Windows 10\. Fortunately, you can remove Show more options from the context menu on Windows 11 by following the below methods.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Remove "Show More Options" From the Context Menu With Folder Options

 The[Windows Folder Options](https://www.makeuseof.com/windows-folder-options-guide/) in File Explorer is the go-to place to view and manage File Explorer settings. You can use it to[enable compact view in File Explorer on Windows 11](https://www.makeuseof.com/how-to-enable-compact-view-windows-11-file-explorer/) , manage file thumbnails, remove the "show more options" entry, and much more.

 Here's how to use the folder option to remove the "show more options" entry from the context menu:

1. Press the**Win + E** hotkey to open the**File Explorer.**
2. Click the three horizontal dots at the top bar and choose**Options.**
3. In the**Folder Options,** switch to the**View** tab.
4. Check the**Launch folder** **windows in a separate process** box.  
![Launch folder windows in a separate process box in the Folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/launch-folder-windows-in-a-separate-process-box.jpg)
5. Click**Apply** \>**OK** to save the changes.

Next, restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111982/7443" target="_top" id="2111982">
  <img src="//a.impactradius-go.com/display-ad/7443-2111982" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111982/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Remove Show More Options From the Context Menu Using the Command Prompt

 If you're a power user, you can use Command Prompt to remove the "show more options" entry from the context menu. Here's how:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane.
3. Click**Yes** to the UAC that crops up.
4. In the elevated Command Prompt window, type the following command and press**Enter** :  
`reg add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve`

![Command to Remove Context menu in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/command-to-remove-context-menu.jpg)

 After executing the command, you'll see the "The operation completed successfully" message to confirm that it went through.

 Now, you will have to restart Windows Explorer to see the changes. To do that, open the**Task Manager** (see how to[launch the Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) ), right-click on**Windows Explorer,** and choose**Restart.**

 Check if you can see the changes. If not, then you will have to restart your computer for the changes to take effect.

 In the future, if you want to add the "show more options" entry to the context menu, then open Command Prompt with admin rights and run the following command:

`reg delete "HKEY_CURRENT_USER\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}" /f​`

## 3\. Remove Show More Options From the Context Menu Using the Registry Editor

 Another quick way to remove the "show more options" entry is through the Registry Editor. Here's what you need to do:

 Before making any changes to the registry, ensure you've[created a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) or[back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . This will ensure your system settings and files are secure, and you can quickly access them if something goes wrong.

1. Open the Start Menu, type**Registry Editor** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID`
3. Right-click on the empty space on the right pane, click**New,** and then select**DWORD** **(32-bit) Value** from the context menu.
4. Name the value as**"UndockingDisabled"** and press**Enter** .  
![UndockingDisabled entry in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/undockingdisabled-entry.jpg)
5. Double-click on the UndockingDisabled key, type**1** in the**Value data,** and click**OK** to save the changes.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144297/7443" target="_top" id="2144297">
  <img src="//a.impactradius-go.com/display-ad/7443-2144297" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144297/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Editing UndockingDisabled in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-undockingdisabled.jpg)

## 4\. Remove the "Show More Options" Entry From the Context Menu Using Winaero Tweaker

 There are plenty of third-party tools using which you can customize the look of your Windows 11 computer. For this guide, we will use Winaero Tweaker.

 Here's how to download Winaero Tweaker and use it to remove the "show more options" entry from the context menu:

1. Download the[Winaero Tweaker zip file](https://winaero.com/downloads/winaerotweaker.zip) on your computer.
2. Unzip the file, open the executable, and then follow the on-screen instructions to install it on your computer.
3. Launch Winaero Tweaker and choose the**Classic Full Context Menus** option from the left sidebar.  
![Classic Full Context Menus option of Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/classic-full-context-menus-option.jpg)
4. Check the**Enable classic full context menus** box.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082542/7443" target="_top" id="2082542">
  <img src="//a.impactradius-go.com/display-ad/7443-2082542" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082542/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Enable classic full context menus option in Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-classic-full-context-menus.jpg)
5. Click the**Restart Explorer** button that appears.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136612/26400" target="_top" id="2136612">
  <img src="//a.impactradius-go.com/display-ad/26400-2136612" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136612/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Enjoy an Old School Context Menu on Windows 11

 The desktop context menu lets you quickly access areas like the personalization menu, display settings, and much more. In Windows 11, you get the new "Show more options" entry in the context menu. But if you prefer the old design, you can quickly disable the "Show more options" entry from the context using either of the above methods.

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
<li><a href="https://twitter-videos.techidaily.com/updated-amazon-primes-social-success-stories-likes-and-watches-galore/"><u>[Updated] Amazon Prime’s Social Success Stories Likes & Watches Galore</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-haul-videography-101-preparation-and-editing-for-maximum-impact/"><u>[Updated] Haul Videography 101 Preparation & Editing for Maximum Impact</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-is-picku-the-best-photo-editor-for-android-our-in-depth-review/"><u>[Updated] Is PickU The Best Photo Editor for Android? Our In-Depth Review</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/analyzing-the-lg-k92s-value-a-look-at-its-5g-capabilities/"><u>Analyzing the LG K92's Value: A Look at Its 5G Capabilities</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-vivo-y100i-power-5g-drfone-by-drfone-virtual-android/"><u>Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Vivo Y100i Power 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cut-down-clutter-tackling-large-storage-consumers-in-windows/"><u>Cut Down Clutter: Tackling Large Storage Consumers in Windows</u></a></li>
<li><a href="https://hardware-help.techidaily.com/detailed-description-of-the-chemical-products-offered-by-hahron-spice-including-spices-with-unique-chemical-properties-used-for-industrial-applications/"><u>Detailed Description of the Chemical Products Offered by HAHRON SPICE, Including Spices with Unique Chemical Properties Used for Industrial Applications</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-and-install-the-right-epson-l3110-driver-for-your-windows-version-11-10-or-7/"><u>Download & Install the Right Epson L3110 Driver for Your Windows Version (11, 10 or 7)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-advice-on-resolving-windows-error-code-0xc0000001/"><u>Expert Advice on Resolving Windows Error Code 0XC0000001</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-credential-store-lockups-on-pcs/"><u>Fix Credential Store Lockups on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-steps-to-correct-windows-operating-system-office-errors/"><u>Immediate Steps to Correct Windows Operating System Office Errors</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-tips-for-producing-ai-powered-live-game-streaming-content/"><u>In 2024, Tips for Producing AI-Powered Live Game Streaming Content</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/new-2024-approved-8-best-multi-subtitles-translators-you-shouldnt-miss/"><u>New 2024 Approved 8 Best Multi-Subtitles Translators You Shouldnt Miss</u></a></li>
<li><a href="https://fox-that.techidaily.com/solutions-how-to-locate-missing-events-on-your-iphone-calendar/"><u>Solutions: How to Locate Missing Events on Your iPhone Calendar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedily-seek-synonyms-with-win11-dictionary/"><u>Speedily Seek Synonyms with Win11 Dictionary</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-functionality-of-microsofts-phone-link-an-introduction/"><u>The Functionality of Microsoft's 'Phone Link': An Introduction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-secret-techniques-for-a-transparent-windows-11-title-bar/"><u>The Secret Techniques for a Transparent Windows 11 Title Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-picks-for-trusted-free-software-downloads-on-windows/"><u>Top Picks for Trusted, Free Software Downloads on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-time-with-selective-copymove-features-in-win-11/"><u>Winning Time with Selective Copy/Move Features in Win 11</u></a></li>
</ul></div>

