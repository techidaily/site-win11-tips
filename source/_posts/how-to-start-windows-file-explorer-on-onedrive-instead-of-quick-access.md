---
title: How to Start Windows File Explorer on OneDrive Instead of Quick Access
date: 2024-12-07T21:08:14.932Z
updated: 2024-12-13T00:17:16.282Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Start Windows File Explorer on OneDrive Instead of Quick Access
excerpt: This Article Describes How to Start Windows File Explorer on OneDrive Instead of Quick Access
keywords: Starts Explorer On OneDrive,OneDrive Windows FileExplorer,Bypass QuickAccess,OnDrive Explore Start,OneDrive OpenFolder,QuickAccess Alternative,Launch Explorer Directly
thumbnail: https://thmb.techidaily.com/104450fe8ea4a9516969410598e82c71d2951cffe9ee598f36dc42477a8a3193.jpg
---

## How to Start Windows File Explorer on OneDrive Instead of Quick Access

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyMZxS9479s?si=0T6zZpyN2LBftFTM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Open File Explorer to OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-file-explorer-to-onedrive.jpg)
4. Click **Apply** \> **OK** to close the dialog box.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l-SCWTWpegY?si=oxTsHQkIu1v4-I6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 From now on, opening File Explorer will automatically launch OneDrive rather than Quick Access.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E3yY7lZ-FKA?si=g8VEuExP8GH59B69" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
7. Click **OK** and close the registry window.

 After that, restart your computer for the changes to take effect. Once your PC restarts, launch File Explorer. With this method, you will launch File Explorer directly to your cloud storage without navigating through Quick Access.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nyp7-xVwqHA?si=XCuZbpKLFIdrGQQh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-content.techidaily.com/updated-what-actions-can-i-take-if-my-content-is-swiftly-stripped-by-fb/"><u>[Updated] What Actions Can I Take if My Content Is Swiftly Stripped by FB?</u></a></li>
<li><a href="https://howto.techidaily.com/7-fixes-for-unfortunately-phone-has-stopped-on-xiaomi-redmi-12-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Fixes for Unfortunately, Phone Has Stopped on Xiaomi Redmi 12 5G | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/can-computers-decipher-difficult-equations/"><u>Can Computers Decipher Difficult Equations?</u></a></li>
<li><a href="https://win-tutorials.techidaily.com/complete-fixes-for-the-perpetual-rotation-error-in-windows-10-across-any-situation/"><u>Complete Fixes for the Perpetual Rotation Error in Windows 10 Across Any Situation</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-through-frozen-windows-update-snags-quickly/"><u>Cutting Through Frozen Windows Update Snags Quickly</u></a></li>
<li><a href="https://discover-alternatives.techidaily.com/enhance-your-website-with-the-power-of-cookiebot-technology/"><u>Enhance Your Website with the Power of Cookiebot Technology</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-safely-remove-personal-info-on-login-screen/"><u>How to Safely Remove Personal Info on Login Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-of-controlling-self-opening-searchbar-on-win11/"><u>Mastery of Controlling Self-Opening Searchbar on Win11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/mobile-and-desktop-tips-for-gotomeeting-captures/"><u>Mobile & Desktop Tips for GoToMeeting Captures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalize-your-esc-keys-a-practical-guide-to-immediate-fixes/"><u>Revitalize Your Esc Keys: A Practical Guide to Immediate Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-fixing-faulty-cpu-statistics-in-windows-task-interface/"><u>Solutions for Fixing Faulty CPU Statistics in Windows Task Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-fix-windows-default-device-error-message/"><u>Strategies to Fix Windows Default Device Error Message</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-to-look-for-top-priorities-when-selecting-a-windows-pc/"><u>What to Look For: Top Priorities When Selecting a Windows PC</u></a></li>
</ul></div>

