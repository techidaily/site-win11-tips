---
title: "Editing Windows Files: Removing Read-Only Access"
date: 2024-10-14T21:04:25.858Z
updated: 2024-10-20T20:29:24.403Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Editing Windows Files: Removing Read-Only Access"
excerpt: "This Article Describes Editing Windows Files: Removing Read-Only Access"
keywords: Remove Read-Only Windows,Edit File Permissions,Unlock Windows Files,Disable RW Access,Modify Windows File Rights,Change File Read-Only Status,Delete RW Lock Windows
thumbnail: https://thmb.techidaily.com/6afde60cdf2c4ed08818a0c3bb279e1893a9ceb4675945a4f5d57ab92e9d6ef9.jpg
---

## Editing Windows Files: Removing Read-Only Access

 When a file is marked as read-only on Windows, you can only view it and not change it in any way. This essentially protects important files from unauthorized changes.

 On Windows, you can set or remove the read-only attribute for a file by modifying its properties. Alternatively, you can also run a command in Command Prompt or Windows PowerShell to do the same. In this article, we take a look at all of them.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Change the Read-Only Attribute for Files by Modifying Properties

 The easiest way to set or remove the read-only attribute for a file on Windows is by modifying its properties. Here’s how you can go about it.

1. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the file for which you want to change the read-only attribute.
2. Right-click on your file and select**Properties** .
3. Under the**General** tab, check or uncheck the**Read-only** box.
4. Click**Apply** followed by**OK** .  
![Change Read-Only Attribute by Modifying Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-by-Modifying-Properties.jpg)

 Note that Windows may prevent you from changing the read-only attribute of a file if you don’t have the necessary permissions to modify the folder in which the file is located. In that case, you must take ownership of the folder first. If you need help, check our guide on[how to take ownership of folders on Windows](<http://How> to Take Ownership of Folders in Windows 10 & 11) .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144271/7443" target="_top" id="2144271">
  <img src="//a.impactradius-go.com/display-ad/7443-2144271" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144271/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. How to Change the Read-Only Attribute for Files Using the Command Prompt

 Command Prompt is one of two command-line tools available on Windows. You can use it to run batch files, troubleshoot errors, and perform various other tasks. It also lets you change a file's read-only attribute with a single command. Here are the steps you need to follow.

1. Right-click on the file for which you want to modify the read-only attribute and select**Copy as path** .
2. Press**Win + X** to open the Power User menu.
3. Select**Terminal (Admin)** from the list.
4. Select**Yes** when the User Account Control (UAC) prompt appears.
5. In the console, type the following command and press**Enter** to set your file as read-only.  
`attrib +r "FilePath"`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

![Change Read-Only Attribute With Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-Command-Prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135366/19272" target="_top" id="2135366">
  <img src="//a.impactradius-go.com/display-ad/19272-2135366" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135366/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you run the above command, the file will be set as read-only. Likewise, if you want to remove the read-only attribute for a file, use this command:

`attrib -r "FilePath"`

 Once you remove the read-only attribute for a file, you should be able to edit or modify it.

 Like using Command Prompt? Check our guide to learn[how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2044585/7443" target="_top" id="2044585">
  <img src="//a.impactradius-go.com/display-ad/7443-2044585" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2044585/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. How to Change the Read-Only Attribute for Files Using Windows PowerShell

 You can also run a command in[Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) to change the read-only attribute for a file.

To change the read-only attribute using PowerShell:

1. Right-click on the file for which you want to change the read-only attribute and select**Copy as path** .
2. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
3. Type**Windows PowerShell** and select**Run as Administrator** .
4. Select**Yes** when the User Account Control (UAC) prompt shows up.
5. Paste the following command and press**Enter** to set your file as read-only.  
`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $True`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

![Change Read-Only Attribute With PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-PowerShell.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037359/7443" target="_top" id="2037359">
  <img src="//a.impactradius-go.com/display-ad/7443-2037359" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037359/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Alternatively, if you want to remove the read-only attribute for a file, use this command:

`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $False`

## Modifying the Read-Only Attribute for Files on Windows

 It’s worth noting that most system files on Windows will have the read-only attribute by default. So, make sure you don't modify them by mistake. For your other files, you can pick any of the above methods listed above to set or unset their read-only attribute.

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
<li><a href="https://twitter-clips.techidaily.com/new-in-2024-tailoring-twitter-video-thumbnails-a-step-by-step-guide/"><u>[New] In 2024, Tailoring Twitter Video Thumbnails A Step-by-Step Guide</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-crafting-visibility-on-youtube-the-ultimate-guide-to-featured-channel-placement/"><u>[Updated] In 2024, Crafting Visibility on YouTube The Ultimate Guide to Featured Channel Placement</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/2024-approved-tube-top-ten-twitters-most-watched-video-rankings/"><u>2024 Approved Tube Top Ten Twitter's Most Watched Video Rankings</u></a></li>
<li><a href="https://howto.techidaily.com/8-solutions-to-solve-youtube-app-crashing-on-oppo-a59-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Solutions to Solve YouTube App Crashing on Oppo A59 5G | Dr.fone</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/brain-boosting-techniques-transforming-language-learning-experience/"><u>Brain Boosting Techniques Transforming Language Learning Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/concealing-time-on-win-1011-desktops/"><u>Concealing Time on Win 10/11 Desktops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-unappealing-look-of-greyed-extend-options-in-win/"><u>Eliminate Unappealing Look of Greyed Extend Options in Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-advice-tackling-the-most-common-directdraw-errors-on-windows-11/"><u>Expert Advice: Tackling the Most Common DirectDraw Errors on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-system-bottleneck-explorers/"><u>Innovative System Bottleneck Explorers</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-rated-2024-outdoor-television-sets-professional-picks-and-reviews-zdnet/"><u>Top-Rated 2024 Outdoor Television Sets: Professional Picks and Reviews - ZDNet</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/understanding-twitters-new-video-format-codes-for-2024/"><u>Understanding Twitter's New Video Format Codes for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/ways-to-find-unlocking-codes-for-realme-v30-phones-by-drfone-android/"><u>Ways To Find Unlocking Codes For Realme V30 Phones</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/wyzecams-superior-substitute-discover-why-the-waterproof-blink-mini-amoost-unbeatable-in-home-surveillance/"><u>WyzeCam's Superior Substitute: Discover Why The Waterproof Blink Mini Amoost Unbeatable in Home Surveillance</u></a></li>
</ul></div>

