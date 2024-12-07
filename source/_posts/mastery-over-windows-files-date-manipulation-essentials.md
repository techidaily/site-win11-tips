---
title: "Mastery Over Windows Files: Date Manipulation Essentials"
date: 2024-11-30T20:04:13.778Z
updated: 2024-12-06T17:52:23.309Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastery Over Windows Files: Date Manipulation Essentials"
excerpt: "This Article Describes Mastery Over Windows Files: Date Manipulation Essentials"
keywords: File Dating Skills,Mastering Window OS,Data Edit Window,Windows Files Control,WinDate Management,OS File Alteration,Date Handling Tips
thumbnail: https://thmb.techidaily.com/519c0ecb3a4e958d4703170c89bc9f0f4e206bb0aa2219c94653cd1097dc9a0c.jpg
---

## Mastery Over Windows Files: Date Manipulation Essentials

 Windows keeps a record of when a file was created, who authored it, and when it was last modified. This information is known as file attributes and can be used to sort files by date, author name, and other parameters.

 The problem is that sharing a file with your teacher or supervisor at work entails sharing all of this information, putting your job or grades at risk. To prevent this, you can modify these attributes.

 If you don't want the receiver to know the actual file attributes, here's how to remove or modify them.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change the Date Created, Date Accessed, and Date Modified Attributes Using PowerShell

 File Explorer doesn't allow changing critical attributes, such as the date a document was created, accessed, or modified. With [PowerShell, a command-line interface utility built into Windows](http://www.makeuseof.com/what-is-windows-powershell/), you can modify them.

 However, the process to change the attributes with PowerShell is a bit complex. If you don't have any experience using PowerShell, you can use a third-party app, Attribute Changer, to change the attributes, as explained in the next section.

 If running a few commands in PowerShell isn't a big deal (for instance, you already know the [best PowerShell commands](https://www.makeuseof.com/windows-powershell-commands-cmdlets/)), follow the steps outlined below to change the created, modified, or accessed dates.

 First, type **"PowerShell"** in Windows Search, right-click on **PowerShell,** and select **Run as administrator**. This gives the utility administrative access to make the desired changes without any restriction.

![Run windows powershell as administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-windows-powershell-as-administrator.jpg)

 Then, navigate to the directory where the file or folder you want to change the attributes of is located. Type **cd..** to move back one folder in the given path, and **cd folder\_name** to move to the next folder.

 For example, our desired folder is located at the following location:

`C:\Users\ehtas\Documents\Files`

 However, in PowerShell, we were in the **"System 32"** subfolder of the main folder **"Windows**.**"** Therefore, to return to the main directory **"C**,**"** we've executed **cd..** twice. Then, we used the **cd folder\_name** command three times to get to the directory where we wanted to be.

![changing the directories in PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/changing-directories.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/htnQWyEOCgc?si=fy86hi8_hTtbWAnw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Therefore, use both commands to reach the folder you want to modify attributes for. After landing in your desired directory, type the following command after inserting the file name and your preferred date of creation:

`$(Get-Item File-name).creationtime=$(Get-Date "mm/dd/yyyy")`

 If PowerShell doesn't present any errors and takes you to the same directory again, that confirms that the attributes have been successfully changed.

![successfully changing the creation date of a file in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/creation-date-has-been-changed.jpg)

 Likewise, you can change the date modified and the date accessed by typing the following two commands:

`$(Get-Item File-Name).lastaccesstime=$(Get-Date "mm/dd/yyyy")  
$(Get-Item File-Name).lastwritetime=$(Get-Date "mm/dd/yyyy")`

![Changing the last modified date in Powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/last-modified-date-has-been-changed.jpg)

 Before changing the attributes, here is how a file's created, modified, and accessed dates looked:

![Showing dates of a file we are about to change in the properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dates-of-a-file-we-are-about-to-change.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/grbt-5VvbuI?si=qnoirlmljslpqcQj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After changing them with PowerShell, here are the updated dates:

![Date created and date modified of a file successfully changed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/date-created-and-date-modified-of-a-file-successfully-changed.jpg)

 Windows makes real-time changes to attributes. Therefore, don't modify or access the file after making changes since it will change the modified and accessed dates again.

## How to Modify the Date Created, Date Accessed, and Date Modified Using Attribute Changer

 The Attribute Changer app is one of the [third-party attribute changer apps](https://www.makeuseof.com/apps-change-created-modified-date-windows/) that lets users change file attributes, including when a file was created, modified, or accessed. If changing the file attributes using PowerShell is challenging for you, here are the steps to modify them using this third-party app:

1. Go to the [official PETGES website](https://www.petges.lu/).
2. Download the full setup of Attribute Changer; do not download the portable version, as it may not function properly.
3. Once the software has been downloaded, run the setup file and follow the onscreen instructions to install it.
4. Restart your device if the software asks you to; otherwise, there's no need.
5. Navigate to the folder containing the file whose attributes you wish to modify.

1. Right-click the file and select **Change Attribute** from the context menu to open the software. If you're using Windows 11, you may need to click **Show more options** to reveal this option in the context menu.  
![opening the attribute changer app from context menu of a file in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/opening-the-attribute-changer-app-from-context-menu-of-a-file-in-windows.jpg)
2. Once the application opens, check the box beside **Modify date and time stamps** to make the date field editable.
3. Change the date and time when a file was first created and the last time you accessed or modified it according to your preference.  
![changing the attributes of a file from the atribute changer app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/changing-the-attributes-of-a-file-from-the-atribute-changer-app.jpg)
4. Once you've made your changes, click **Apply** to make them permanent.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hHPljBHrvkA?si=HwdfDM9rlbABSIrx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Click **Yes** in the confirmation pop-up, and the file attributes will be changed successfully.

 In the same way that we changed the attributes of a file, you can also change the attributes of a folder using Attribute Changer.

 Using third-party tools to modify attributes requires you to grant apps permission to access the file. Therefore, if the documents you want to modify the dates for are confidential, don't use third-party apps to change the attributes; instead, use the official methods offered by Windows.

## How to Remove Other File Attributes Using File Explorer

 While File Explorer does not permit modifying critical attributes such as Date Created, Date Modified, and Date Accessed, it does permit users to remove specific attributes such as the author, copyright information, revision number, etc. To remove attributes that are possibly removable using File Explorer, follow the below steps:

1. Navigate to the folder where you want to change the attributes.
2. Right-click on it and select **Properties** from the context menu.
3. Navigate to the **Details** tab at the top of the window.
4. Click the **Remove Properties and Personal Information** link.  
![Opening the Window to Remove the Personal Information of Text Document in the Details Tab of Document Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/1-Removing-the-Personal-Information-of-Text-Document-in-the-Details-Tab-of-Document-Properties.jpg)
5. To remove all possible properties automatically, check the circle beside **Create a copy with all possible properties removed**. This will create a duplicate of the file at the exact location after deleting all possible attributes.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/h5uImbOWmTg?si=z4kP-R0QbXbBAJTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Removing possible file attributes in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/removing-possible-file-attributes-in-file-explorer.jpg)
6. To remove selected properties, check the circle beside **Remove the following properties from this file**, select the attributes you want to remove, and click **OK**.

## Modify Your File's Attributes With Ease

 Modifying file attributes is a great way to hide author information, revision numbers, and other details, such as when a file was created, modified, or accessed. Hopefully, you now better understand the different ways to modify file attributes. Using PowerShell is the easiest and most recommended method to change them.

 If you find it complicated or want more control over how the attributes are changed, you can use the Attribute Changer. If you take this route, be aware of the privacy risks involved.

 The problem is that sharing a file with your teacher or supervisor at work entails sharing all of this information, putting your job or grades at risk. To prevent this, you can modify these attributes.

 If you don't want the receiver to know the actual file attributes, here's how to remove or modify them.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-precise-age-setting-made-simple-tiktoks-guide/"><u>[Updated] 2024 Approved Precise Age Setting Made Simple TikTok's Guide</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-free-subtitle-services-the-ultimate-convertors-guide/"><u>2024 Approved Free Subtitle Services The Ultimate Convertors Guide</u></a></li>
<li><a href="https://howto.techidaily.com/best-methods-for-vivo-x100-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Best Methods for Vivo X100 Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-an-effective-auto-checkup-toolbar-in-the-windows-environment/"><u>Creating an Effective Auto-Checkup Toolbar in the Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-strategies-for-optimizing-w11s-auto-hdr-feature/"><u>Essential Strategies for Optimizing W11's Auto HDR Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-address-missing-mcuicnt-executable-in-microsoft-os/"><u>How To Address Missing McUICnt Executable in Microsoft OS</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-nubia-z50-ultra-location-on-twitter-drfone-by-drfone-virtual-android/"><u>How to Change your Nubia Z50 Ultra Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-5-most-effective-methods-to-unlock-iphone-14-in-lost-mode-by-drfone-ios/"><u>In 2024, 5 Most Effective Methods to Unlock iPhone 14 in Lost Mode</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-pixelperfect-tools-overview-series/"><u>In 2024, PixelPerfect Tools Overview Series</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefine-windows-11-account-hierarchy-update-admin-role/"><u>Redefine Windows 11 Account Hierarchy: Update Admin Role</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-video-file-conversion-from-mkv-to-mp4-on-windows/"><u>Seamless Video File Conversion From MKV to MP4 on Windows</u></a></li>
<li><a href="https://buynow-info.techidaily.com/smarter-spending-on-mobile-devices-a-detailed-evaluation-of-the-oneplus-nord-n100s-features-and-value/"><u>Smarter Spending on Mobile Devices: A Detailed Evaluation of the OnePlus Nord N100's Features and Value</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-overcoming-the-windows-activation-error-0x803f700f/"><u>Strategies for Overcoming the Windows Activation Error 0X803F700f</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-accessing-iis-manager-for-web-servers/"><u>Swiftly Accessing IIS Manager for Web Servers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-for-lengthening-windows-10-shutdown-with-open-applications/"><u>Tactics for Lengthening Windows 10 Shutdown with Open Applications</u></a></li>
<li><a href="https://common-error.techidaily.com/top-5-fixes-to-restore-your-windows-10-touchscreen-functionality-today/"><u>Top 5 Fixes to Restore Your Windows 10 Touchscreen Functionality Today</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-lava-yuva-3-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Lava Yuva 3 Screen | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-selection-of-12-no-cost-typewriting-lessons-suitable-for-all-ages/"><u>Ultimate Selection of 12 No-Cost Typewriting Lessons Suitable for All Ages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unobstructed-memory-management-7-ways-to-restore-in-win11/"><u>Unobstructed Memory Management: 7 Ways to Restore in Win11</u></a></li>
</ul></div>

