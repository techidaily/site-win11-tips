---
title: "Clear Out Windows: A Guide to Auto-Delete Files and Folders"
date: 2024-12-19T22:06:40.581Z
updated: 2024-12-21T16:50:36.191Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Clear Out Windows: A Guide to Auto-Delete Files and Folders"
excerpt: "This Article Describes Clear Out Windows: A Guide to Auto-Delete Files and Folders"
keywords: File Cleanup,Automatic Deletion,Window's Disk Cleanup,Remove Unnecessary Space,Free Up Drive Space,Optimize Windows Files,Streamline File Management
thumbnail: https://thmb.techidaily.com/c2e520b7fa2ea279c78f437762c6d9b1bb9afdd3b83c993e13cda25988d89dcf.png
---

## Clear Out Windows: A Guide to Auto-Delete Files and Folders

 We all know how easy it is to delete files and send them to the Recycle Bin. But wouldn't it be great if Windows automatically emptied the bin for us? Fortunately, you can configure your system to do just that.

 Let's look at the different ways to auto-empty the Recycle Bin on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Automate the Recycle Bin Using the System Settings

 It's easy to configure Windows to empty the recycle bin automatically. All you need to do is open System settings, fiddle with a few things, and you're done.

 However, this feature applies only to the current user account. Other users on the same computer won't have their Recycle Bin emptied automatically until they adjust this setting. In other words, if you're using a shared computer, it won't affect anyone else.

 Here's how to do it:

1. [Open the Settings window](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. From the left panel, select the **System** tab.
3. Scroll down and click on **Storage** on the right-hand side. Here, you will find various computer data storage and management options.  
![Stoage in System Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/stoage-in-system-settings.jpg)
4. Now, you will see a toggle switch under **Storage Sense**. If it's turned off, click to switch it on. This feature enables Windows to delete no longer needed files automatically.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/7JBG_O3Vnh4?si=lUO0fta6YPJ50qjg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Turn on Storage Sense](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/turn-on-storage-sense.jpg)
5. Once Storage Sense is active, click the tiny arrow next to it to expand the options.
6. On the next screen, you'll find an option that says, **Delete files in my recycle bin if they have been there for over**. Click the drop-down menu beside this and select the duration, after which Windows should empty the recycle bin automatically.
7. Select **1 day** if you want Windows to delete these items daily. Or choose another option that suits your needs better.  
![Configure Storage Sense](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/configure-storage-sense.jpg)
8. You can also configure the system to delete downloaded files that haven't been used for several days. To do so, click the **Delete files in my Downloaded folder if they haven't been opened for more than** drop-down menu and select the desired option.

 Once you're done, close the Settings window. Windows will automatically empty your Recycle Bin from now on.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X18Dq7rV-xI?si=twFfXIPD0TFmC5EM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Automate the Recycle Bin Using the Task Scheduler

 If you want more control over the process, you can use Windows Task Scheduler to empty your Recycle Bin. Here's how:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **taskschd.msc** and hit **Enter** or click **OK**. Doing this [opens the Task Scheduler program](https://www.makeuseof.com/windows-11-open-task-scheduler/).
3. On the left-hand side of the window, select **Task Scheduler Library**.
4. Now, click **Create Basic Task** from the right-hand panel. It will open another window where you can configure your task settings.  
![Create Basic Task](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/create-basic-task.jpg)
5. Enter a name for your task (e.g., Empty Recycle Bin) and a brief description if you want. Then, click the **Next** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZblaBc-v2vs?si=CKW1gJwXQT2vZJYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. The following window will ask you to select the frequency when Windows should empty your Recycle Bin. You can choose Daily, Weekly, Monthly, or One time only. Once you've chosen your preferred frequency, click **Next**.  
![Create a Basic Task](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/create-a-basic-task.jpg)
2. After that, set the start date and time for your task. Also, select **Recur every** to specify the total duration of each cleaning session. Then, click **Next**.  

![Start Date and Time in Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/start-date-and-time-in-task-wizard.jpg)
3. You must specify what action Windows should perform when this task runs. Click on the **Start a program** option and click **Next** again.  
![Start a program in Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/start-a-program-in-task-wizard.jpg)
4. In the **Program/script** box, type _**C:\\Windows\\System32\\cmd.exe**_. Then, in the **Add arguments (optional)** field, type the following command:  
/c "echo Y|PowerShell.exe -NoProfile -Command Clear-RecycleBin"  
![Write Program or Script in Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/write-program-or-script-in-task-wizard.jpg)
5. Running this command will delete your Recycle Bin content. Click **Next** to continue.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iPCr_bxZjMQ?si=ubOsoq5umPEXL9xL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Now, you can review your settings and tick **Open the Properties dialog for this task when I click Finish** if you want to make any changes. When done, hit the **Finish** button.  
![Finish Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/finish-task-wizard.jpg)

 Once you're done, close the Task Scheduler window. From now on, Windows will empty your Recycle Bin according to your specified frequency.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aoMiYpYiFZs?si=qvYvGytDD17fvSXO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Automate the Recycling Process on Windows

 To keep your computer running smoothly, you must empty your Recycle Bin regularly. However, the process can be tedious and time-consuming. Fortunately, Windows provides some easy ways to automate this task, either through Windows Settings or Task Scheduler.

 Let's look at the different ways to auto-empty the Recycle Bin on Windows.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-tips.techidaily.com/n-2024-surge-viral-traction-via-youtube-short-content/"><u>[New] In 2024, Surge Viral Traction via YouTube Short Content</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-secretive-approach-to-watching-insta-stories-for-2024/"><u>[Updated] Secretive Approach to Watching Insta-Stories for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/effortless-driver-updates-and-downloads-for-your-microsoft-surface-book/"><u>Effortless Driver Updates & Downloads for Your Microsoft Surface Book</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-15-plus-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 15 Plus without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-embed-google-play-into-your-win11/"><u>How to Embed Google Play Into Your Win11</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/how-to-enable-youtube-videos-to-self-play-on-facebook-for-2024/"><u>How to Enable Youtube Videos to Self-Play on Facebook for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-invalid-user-alerts-in-w11-operating-systems/"><u>How to Rectify Invalid User Alerts in W11 Operating Systems</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-macpc-vmix-bridge-software/"><u>In 2024, MacPC VMix Bridge Software</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-master-the-art-of-live-content-utilizing-wirecast-for-fb/"><u>In 2024, Master the Art of Live Content Utilizing Wirecast for FB</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-control-how-to-fix-your-pc-controller/"><u>Regaining Control: How to Fix Your PC Controller</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shut-off-redundant-windows-alerts-and-recommendations/"><u>Shut Off Redundant Windows Alerts and Recommendations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-network-with-dns-setup-in-windows-11/"><u>Streamline Your Network with DNS Setup in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-challenges-of-xbox-game-pass-error-0x00000001-with-windows-11-pcs/"><u>Tackling the Challenges of Xbox Game Pass Error 0X00000001 with Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-insight-on-wintoys-unlocking-its-full-potential-in-windows/"><u>The Ultimate Insight on WinToys: Unlocking Its Full Potential in Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-6-appsservices-to-trace-any-motorola-razr-40-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>Top 6 Apps/Services to Trace Any Motorola Razr 40 Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-non-responsive-function-keys-in-windows-11-display/"><u>Troubleshooting Non-Responsive Function Keys in Windows 11 Display</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/uniting-digital-and-physical-worlds/"><u>Uniting Digital and Physical Worlds</u></a></li>
</ul></div>

