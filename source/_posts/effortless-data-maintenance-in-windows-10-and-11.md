---
title: Effortless Data Maintenance in Windows 10 & 11
date: 2024-09-29T00:45:46.317Z
updated: 2024-10-03T18:53:09.949Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Effortless Data Maintenance in Windows 10 & 11
excerpt: This Article Describes Effortless Data Maintenance in Windows 10 & 11
keywords: Easy Data Updates,WinMaintenance,Windows Data Cleaning,PC Maintenance Software,Streamlined Sync Tech,Efficient File Management,Automated System Tune-Up
thumbnail: https://thmb.techidaily.com/8467c9e20d909c3a99e5604c440b3f79e42d4e9a9f150048899a6b75835712f0.jpg
---

## Effortless Data Maintenance in Windows 10 & 11

 For many, a cluttered desktop and downloads folder is just a way of life—no matter how hard you try, they somehow always ends up disorganized. Need to do a bit of digital spring-cleaning? Fortunately, there are lots of ways you can keep your Windows 10 computer decluttered.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Auto-Delete Old Files or Folders Using Storage Settings

 The Settings menu lets you do and manage a lot of stuff on your Windows computer. From updates to tweaking the Windows appearance—you can do almost everything. It's no surprise then that you can also use it for setting up an auto-deletion setting on your Windows. Here's how:

![storage settings on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-settings-on-windows.jpg)

1. Go to **Settings > System > Storage**.
2. Toggle on the **Storage Sense** feature.
3. Then, click **Configure Storage Sense or run it now**.
4. Under **Temporary Files**, set up your desired time frames fore deleting files in the recycle bin and files in your Downloads folder.  
![storage sense in windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-sense-in-windows-settings.jpg)

 Not all files in the Downloads folder will be deleted after the set time; just those that haven't been opened. This means if you download a file and want to open it later, it will still be deleted after the set time. If you turn this setting on, you should move anything out of the Downloads folder that you intend to keep.

 If you want, you can always turn off the setting by simply disabling the **Storage Sense** button later on.

## 2\. Deleted Old Files or Folders With the Command Prompt

 Like most things on Windows, you can use the Command Prompt here as well. A replacement for the easy pin-and-point graphical user interface, the Command Prompt works with simple text-based commands to help you perform different admin functions and fix various troubleshooting issues on Windows.

 Here's how you can use it to fix your storage issues via the _ForFiles_ command on Windows:

1. Head to the **Start menu** search bar, type in 'cmd', and run the CMD as an administrator.
2. Now, to delete the files that you haven't modified in 30 days, type in the following command and hit **Enter**:  
`ForFiles /p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 The "C:\\path\\to\\folder" and /d -30 here refer to the folder path from where you want to delete files and the specific time for which you'd like to delete your file. Replace them with the settings that suit you.

![command prompt on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/command-prompt-on-windows.jpg)

<!-- affiliate ads begin -->
<span id="1983545">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983545.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983545">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983545.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983545%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983545/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Your files will be removed as quickly as soon as you hit the above commands.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144285/7443" target="_top" id="2144285">
  <img src="//a.impactradius-go.com/display-ad/7443-2144285" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144285/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Use Task Scheduler on Windows

 Task Scheduler is a simple Windows tool that lets you easily automate your repetitive Windows tasks. Just set up the task, and the app will handle whatever you have asked it to do. When it comes to auto-deleting your files or folders, the _ForFiles_ command is what you will need to help you delete your older files or folders.

 Here's how you can automate the deletion:

1. Head to the **Start menu** search bar, type in 'task scheduler', and select the best match.
2. Right-click on **Task Scheduler Library** and select **New Folder**.
3. Put in any name and click on **OK**.
4. Right-click on the recently created folder and select the **Create Task** option.  
![task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/task-scheduler.jpg)
5. In the **Name** box, enter a name for the task.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087390/7443" target="_top" id="2087390">
  <img src="//a.impactradius-go.com/display-ad/7443-2087390" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087390/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Now, in the **General** tab, under the **Security options** section, select the **Run whether the user is logged on or not** option.
7. Make sure the **Do not store password** checkbox is unselected.
8. Click on the **Triggers** tab and select the **New** button.
9. Select **On a schedule** option using the **Begin the task** setting.  
![new trigger section on task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-trigger-section-on-windows.jpg)
10. Under the **Settings** section, set up the timings of the tasks you'd like to run. Finally, click on **OK**.

 Now, head to the **Actions** tab and click on the **New** button. From the **Actions** drop-down menu, select the **Start a program** option.

 In the Program/script box, type in the following command:

`ForFiles`

![new action tab on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-tab-on-windows.jpg)

 Similarly, in the **Add arguments** box, type in the following command:

`/p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 In the above command, tweak the _"C:\\path\\to\\folder_" to the path of the folder where your files are and replace "_/d -30_" with actual number you'd like pick. So, your command will become something like this:

`/p "%userprofile%\Users\[Your Username]\Downloads" /s /d -30 /c "cmd /c del /q @file"`

 Click on **OK**. Finally, from the **Settings** tab, check the following checkboxes and then click on **OK**:

* Allow task to be run on demand.
* Run the task as soon as possible after a scheduled start is missed.
* If the task fails, restart every.

![new action setting on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-setting-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880940/19272" target="_top" id="1880940">
  <img src="//a.impactradius-go.com/display-ad/19272-1880940" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880940/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 That's it—finalize the changes by clicking **OK** once again, and you will be done in no time. From here forward, your files will be automatically deleted within the specified time. Of course, if you later change your mind you can always reverse this setting by simply deleting the new folder your created in first step (which in our case, will be **New Folder 1**).

## Auto-Deleting Old Files or Folders on a Windows Computer

 Keeping unnecessary files on your computer is seldom useful. They eat up memory space, hamper your PC's performance, and clog the file organization. Setting up auto-delete instructions, with whichever method you prefer, lets you rid your PC of this extra baggage.

 However, we'd add that auto-removing files or folders from your PC is just one part of cleaning up your Windows. There are many other important hacks such as removing unused apps, terminating pointless background processes, and tweaking settings to whatever is most relevant to your situation. So, make sure you follow all the best principles for running your Windows as smoothly as possible.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-avoid-the-quake-optimal-tripod-placement-for-stellar-vlogs/"><u>[Updated] In 2024, Avoid the Quake Optimal Tripod Placement for Stellar Vlogs</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-the-easy-way-to-embed-youtube-into-google-slides-for-2024/"><u>[Updated] The Easy Way to Embed YouTube Into Google Slides for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1-mastering-accessibility-a-step-by-step-guide-to-adding-alt-text-in-ms-excel/"><u>1. Mastering Accessibility: A Step-by-Step Guide to Adding Alt Text in MS Excel</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-turning-your-instagram-movies-inside-out/"><u>2024 Approved Turning Your Instagram Movies Inside Out</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-essential-benefits-of-integrating-microsoft-365-into-daily-operations/"><u>7 Essential Benefits of Integrating Microsoft 365 Into Daily Operations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-showing-and-hiding-excel-sheet-columns-for-better-organization/"><u>A Step-by-Step Guide to Showing and Hiding Excel Sheet Columns for Better Organization</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/beginning-zoom-video-calls-on-android-devices-for-2024/"><u>Beginning Zoom Video Calls on Android Devices for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-microsoft-office-applications-creating-and-managing-spreadsheet-features-inside-microsoft-word/"><u>Bridging Microsoft Office Applications: Creating and Managing Spreadsheet Features Inside Microsoft Word</u></a></li>
<li><a href="https://win11-tips.techidaily.com/building-an-easy-monthly-budget-using-microsoft-excel-tips-and-tricks-for-beginners/"><u>Building an Easy Monthly Budget Using Microsoft Excel – Tips and Tricks for Beginners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comparing-microsoft-office-key-differences-on-windows-vs-macos-platforms/"><u>Comparing Microsoft Office: Key Differences on Windows vs macOS Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-tutorial-renaming-and-disposing-of-kindle-gadgets-via-amazons-online-portal/"><u>Comprehensive Tutorial: Renaming & Disposing of Kindle Gadgets via Amazon's Online Portal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-microsoft-office-spell-checker-to-overlook-web-addresses-effortlessly/"><u>Configuring Microsoft Office Spell Checker to Overlook Web Addresses Effortlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-modernized-interface-of-microsoft-excels-revamped-formula-bar/"><u>Discover the Modernized Interface of Microsoft Excel's Revamped Formula Bar</u></a></li>
<li><a href="https://program-issues.techidaily.com/fixing-pc-instability-when-playing-the-witcher-3-tips-and-solutions-for-gamers/"><u>Fixing PC Instability When Playing The Witcher 3 – Tips & Solutions for Gamers</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-asus-rog-phone-7-ultimate-drfone-by-drfone-virtual-android/"><u>In 2024, Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Asus ROG Phone 7 Ultimate | Dr.fone</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/joint-ventures-in-content-creation-for-youtube-audiences/"><u>Joint Ventures in Content Creation for YouTube Audiences</u></a></li>
<li><a href="https://extra-resources.techidaily.com/perfect-your-pictures-the-ultimate-guide-to-photo-text-editing/"><u>Perfect Your Pictures The Ultimate Guide to Photo Text Editing</u></a></li>
<li><a href="https://blog-min.techidaily.com/step-by-step-tutorial-obtaining-and-setting-up-movie-maker-in-windows-10/"><u>Step-by-Step Tutorial: Obtaining and Setting Up Movie Maker in Windows 10</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-tutorial-setting-up-espn-plus-channel-on-an-lg-smart-tv-screen/"><u>Ultimate Tutorial: Setting Up ESPN Plus Channel on an LG Smart TV Screen</u></a></li>
</ul></div>

