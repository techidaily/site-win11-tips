---
title: Boost Efficiency with Automatic File Disposal in Windows 11
date: 2024-08-08T10:58:12.280Z
updated: 2024-08-09T10:58:12.280Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Boost Efficiency with Automatic File Disposal in Windows 11
excerpt: This Article Describes Boost Efficiency with Automatic File Disposal in Windows 11
keywords: AutoFileDispose Windows11,BoostEfficiency W11,FileDisposal SaveTime,EfficientW11 Management,Automatic FileCleanup Win,DiskSpace OptimizeWin11,Streamline Files Windows11
thumbnail: https://thmb.techidaily.com/253a511a8eebe03ad95bca3519e71144f55137cbd051ad18a83009076fc1de06.jpg
---

## Boost Efficiency with Automatic File Disposal in Windows 11

 For many, a cluttered desktop and downloads folder is just a way of life—no matter how hard you try, they somehow always ends up disorganized. Need to do a bit of digital spring-cleaning? Fortunately, there are lots of ways you can keep your Windows 10 computer decluttered.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
## 1\. Auto-Delete Old Files or Folders Using Storage Settings

 The Settings menu lets you do and manage a lot of stuff on your Windows computer. From updates to tweaking the Windows appearance—you can do almost everything. It's no surprise then that you can also use it for setting up an auto-deletion setting on your Windows. Here's how:

![storage settings on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-settings-on-windows.jpg)

1. Go to **Settings > System > Storage**.
2. Toggle on the **Storage Sense** feature.
3. Then, click **Configure Storage Sense or run it now**.
4. Under **Temporary Files**, set up your desired time frames fore deleting files in the recycle bin and files in your Downloads folder.  
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
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

 Your files will be removed as quickly as soon as you hit the above commands.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Use Task Scheduler on Windows

 Task Scheduler is a simple Windows tool that lets you easily automate your repetitive Windows tasks. Just set up the task, and the app will handle whatever you have asked it to do. When it comes to auto-deleting your files or folders, the _ForFiles_ command is what you will need to help you delete your older files or folders.

 Here's how you can automate the deletion:

1. Head to the **Start menu** search bar, type in 'task scheduler', and select the best match.
2. Right-click on **Task Scheduler Library** and select **New Folder**.
3. Put in any name and click on **OK**.
4. Right-click on the recently created folder and select the **Create Task** option.  
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/task-scheduler.jpg)
5. In the **Name** box, enter a name for the task.
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

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
![new action setting on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-setting-on-windows.jpg)

 That's it—finalize the changes by clicking **OK** once again, and you will be done in no time. From here forward, your files will be automatically deleted within the specified time. Of course, if you later change your mind you can always reverse this setting by simply deleting the new folder your created in first step (which in our case, will be **New Folder 1**).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-top-5-secure-downloader-apps-for-fb-video-extraction/"><u>[New] 2024 Approved  Top 5 Secure Downloader Apps for FB Video Extraction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-the-annoyance-of-a-never-ending-update-loop/"><u>Avoid the Annoyance of a Never-Ending Update Loop</u></a></li>
<li><a href="https://fake-location.techidaily.com/best-10-mock-location-apps-worth-trying-on-asus-rog-phone-8-drfone-by-drfone-virtual-android/"><u>Best 10 Mock Location Apps Worth Trying On Asus ROG Phone 8 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-retrieve-lost-pictures-from-htc-u23-by-fonelab-android-recover-pictures/"><u>Best Android Data Recovery - Retrieve Lost Pictures from HTC U23.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensively-tackle-the-icloud-install-issue-on-windows/"><u>Comprehensively Tackle the iCloud Install Issue on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explaining-the-red-x-its-role-in-file-system-navigation/"><u>Explaining the Red “X”: Its Role in File System Navigation</u></a></li>
<li><a href="https://article-helps.techidaily.com/from-still-shots-to-dynamic-visuals-using-ai-effects-for-2024/"><u>From Still Shots to Dynamic Visuals Using AI Effects for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-samsung-galaxy-a05s-drfone-by-drfone-virtual-android/"><u>Here are Some Pro Tips for Pokemon Go PvP Battles On Samsung Galaxy A05s | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hidden-potential-utilize-hotkeys-to-control-windows-taskbar/"><u>Hidden Potential: Utilize Hotkeys to Control Windows Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hide-post-display-adjustment-in-windows-power-configuration/"><u>Hide Post-Display Adjustment in Windows Power Configuration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-master-windows-blue-screen-troubleshooting/"><u>How to Master Windows Blue Screen Troubleshooting</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-tecno-pova-6-pro-5g-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Tecno Pova 6 Pro 5G to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-9-best-phone-monitoring-apps-for-apple-iphone-12-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, 9 Best Phone Monitoring Apps for Apple iPhone 12 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-breaking-boundaries-top-6-artists-leading-nft-frontier/"><u>In 2024, Breaking Boundaries  Top 6 Artists Leading NFT Frontier</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-canvas-hidden-power-ups-for-stunning-visuals/"><u>In 2024, Canva's Hidden Power-Ups for Stunning Visuals</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-any-samsung-galaxy-f15-5g-phone-password-using-emergency-call-by-drfone-android/"><u>In 2024, How To Unlock Any Samsung Galaxy F15 5G Phone Password Using Emergency Call</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-learn-to-use-montage-with-these-movies/"><u>In 2024, Learn to Use Montage with These Movies</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-future-of-gaming-at-your-fingertips-top-10-vr-headsets-for-pc/"><u>In 2024, The Future of Gaming at Your Fingertips  Top 10 VR Headsets for PC</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/in-depth-electronics-analysis-and-reviews-by-toms-digital-workshop/"><u>In-Depth Electronics Analysis and Reviews by Tom's Digital Workshop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-windows-apps-into-linux-world/"><u>Integrating Windows Apps Into Linux World</u></a></li>
<li><a href="https://extra-hints.techidaily.com/join-the-metaverse-meme-revolution-quick-tips-for-original-creators/"><u>Join the Metaverse Meme Revolution - Quick Tips for Original Creators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-windows-hello-recognition-work-again/"><u>Making Windows Hello Recognition Work Again</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-malware-discovery-without-software-assistance/"><u>Mastering Malware Discovery without Software Assistance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-your-networks-security-keys-five-steps-towards-error-elimination-in-windows/"><u>Mastering Your Network's Security Keys: Five Steps Towards Error Elimination in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modern-standby-uncovering-its-defects-and-criticisms/"><u>Modern Standby: Uncovering Its Defects and Criticisms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-hidden-dangers-on-a-computer-screen/"><u>Navigating Hidden Dangers on a Computer Screen</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-optimizing-audio-levels-a-guide-to-dynamic-ducking-in-windows-edition-of-adobe-premiere-pro/"><u>New In 2024, Optimizing Audio Levels A Guide to Dynamic Ducking in Windows Edition of Adobe Premiere Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/prodigious-windows-11-tools-the-ultimate-7-productivity-list/"><u>Prodigious Windows 11 Tools: The Ultimate 7 Productivity List</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-and-easy-cures-for-your-computers-messaging-woes/"><u>Quick & Easy Cures for Your Computer's Messaging Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-resetting-graphics-drivers-on-latest-oses/"><u>Quick Guide to Resetting Graphics Drivers on Latest OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-establishing-windows-11-support-features/"><u>Re-Establishing Windows 11 Support Features</u></a></li>
<li><a href="https://howto.techidaily.com/reasons-for-asus-rog-phone-8-pro-stuck-on-startup-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Asus ROG Phone 8 Pro Stuck on Startup Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-old-password-needed-on-windows-11-errors/"><u>Remedy for 'Old Password Needed' On Windows 11 Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-your-windows-11-the-most-impactful-settings-to-modify/"><u>Revolutionize Your Windows 11: The Most Impactful Settings to Modify</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-to-streamline-your-windows-netconnection-access/"><u>Step-By Step to Streamline Your Windows NetConnection Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-guide-to-engaging-windows-11s-calculator/"><u>The Essential Guide to Engaging Windows 11'S Calculator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/time-saving-techniques-for-a-functional-windows-time-service/"><u>Time-Saving Techniques for a Functional Windows Time Service</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/tips-and-tricks-to-tell-if-your-iphone-6-is-unlocked-by-drfone-ios/"><u>Tips And Tricks To Tell if Your iPhone 6 Is Unlocked</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-iis-8-key-steps/"><u>Unlocking IIS: 8 Key Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-mechanism-disabling-dim-display-option/"><u>Unveiling the Mechanism: Disabling 'Dim Display' Option</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windowing-wonderland-personalized-monitor-settings-in-win1011/"><u>Windowing Wonderland: Personalized Monitor Settings in Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-memory-assessment-made-easy/"><u>Windows Memory Assessment Made Easy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-newbies-guide-to-easier-access/"><u>Windows Newbies' Guide to Easier Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-ways-the-best-fixes-to-skip-the-long-wait-in-install-steps/"><u>Winning Ways: The Best Fixes to Skip the Long Wait in Install Steps</u></a></li>
</ul></div>
