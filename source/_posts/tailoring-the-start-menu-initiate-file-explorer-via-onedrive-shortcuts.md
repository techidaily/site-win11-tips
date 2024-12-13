---
title: "Tailoring the Start Menu: Initiate File Explorer via OneDrive Shortcuts"
date: 2024-12-06T18:03:41.804Z
updated: 2024-12-13T01:04:50.453Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tailoring the Start Menu: Initiate File Explorer via OneDrive Shortcuts"
excerpt: "This Article Describes Tailoring the Start Menu: Initiate File Explorer via OneDrive Shortcuts"
keywords: Start Menu Optimization,OneDrive Quick Access,File Explorer Launching,Windows Custom Menu,Shortcut Integration,OneDrive Navigation,Personalized Start Screen
thumbnail: https://thmb.techidaily.com/606be4e6c5a29affde6b0062eb01d7884930a95dd58e84baf4df0ccd1b6b1a9d.jpg
---

## Tailoring the Start Menu: Initiate File Explorer via OneDrive Shortcuts

 When you launch Windows File Explorer, it automatically takes you to the "Quick Access" view. This page displays shortcuts to recently accessed folders and files and lists your favorite folders. It might be convenient for some users but not for others who prefer easy access to their cloud storage.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Use the Folder Options

 If you want to make OneDrive the starting point of your File Explorer, you can do so using folder options. Here's how to do it:

1. Open the Start menu and type **File Explorer** in the search box. When the File Explorer icon appears, click it to launch the app. You can also use **Win + E** to open the program quickly.
2. In the File Explorer window, look for **See more** (three dots) at the top. Clicking on it opens the Folder Options dialog box.  
![Open Folder Options in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-folder-options-in-file-explorer.jpg)
3. On the General tab, click the **Open File Explorer to** drop-down menu and select "Username Personal". Here, "Username" refers to your Windows account name.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1dR4tF3VgyU?si=AJipgqZsNNxsRsBW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Open File Explorer to OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-file-explorer-to-onedrive.jpg)
4. Click **Apply** \> **OK** to close the dialog box.

 From now on, opening File Explorer will automatically launch OneDrive rather than Quick Access.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/lCpzYpVPIZA?si=hNte-mPRIzjvqpRy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Click **OK** and close the registry window.

 After that, restart your computer for the changes to take effect. Once your PC restarts, launch File Explorer. With this method, you will launch File Explorer directly to your cloud storage without navigating through Quick Access.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mMYEK2gtY5c?si=ytxNz_JHZkTrwb4b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

8. Finally, restart your computer for the changes to take effect.

 After your system restarts, launch File Explorer. You'll see OneDrive as the main view instead of Quick Access.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/dKjioJQaUh8?si=Ls_AeuvGsSyL5ny2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://some-knowledge.techidaily.com/new-eyeem-pro-your-ultimate-guide-to-freepaid-substitutes/"><u>[New] EyeEm Pro Your Ultimate Guide to Free/Paid Substitutes</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-leaving-with-honor-a-disconnect-guide-for-servers-for-2024/"><u>[New] Leaving with Honor A Disconnect Guide for Servers for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-plot-twists-for-success-top-3-channel-building-tactics/"><u>[Updated] 2024 Approved Plot Twists for Success Top 3 Channel-Building Tactics</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-chromatic-creativity-enhancing-your-craft/"><u>[Updated] Chromatic Creativity Enhancing Your Craft</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/7-top-ways-to-resolve-apple-id-not-active-issue-for-apple-iphone-se-2020-by-drfone-ios/"><u>7 Top Ways To Resolve Apple ID Not Active Issue For Apple iPhone SE (2020)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-window-management-hotkey-based-reworking-mastery/"><u>Conquer Window Management: Hotkey-Based Reworking Mastery</u></a></li>
<li><a href="https://android-location.techidaily.com/easy-ways-to-manage-your-nubia-red-magic-9-pro-location-settings-drfone-by-drfone-virtual/"><u>Easy Ways to Manage Your Nubia Red Magic 9 Pro Location Settings | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-resolution-of-error-0x800700e1-in-windows-11-systems/"><u>Mastering the Resolution of Error 0X800700E1 in Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapid-examination-identifying-pcs-graphics-card-makeup/"><u>Rapid Examination: Identifying PC's Graphics Card Makeup</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-realme-10t-5g-stuck-on-startup-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Realme 10T 5G Stuck on Startup Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-chrome-networking-hiccup-in-windows-settings/"><u>Remedy for Chrome Networking Hiccup in Windows Settings</u></a></li>
<li><a href="https://win-tutorials.techidaily.com/resolving-issues-with-undetected-documents-in-scanners-advice-by-yl-software-experts/"><u>Resolving Issues with Undetected Documents in Scanners - Advice by YL Software Experts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-keys-in-crisis-arrows-rescued/"><u>Revive Keys in Crisis: Arrows Rescued</u></a></li>
</ul></div>

