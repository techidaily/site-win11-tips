---
title: "Streamlined Commence: Quickly Open Windows and Sticky Notes"
date: 2024-12-16T04:16:46.042Z
updated: 2024-12-22T06:32:01.990Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Streamlined Commence: Quickly Open Windows and Sticky Notes"
excerpt: "This Article Describes Streamlined Commence: Quickly Open Windows and Sticky Notes"
keywords: Window Opener App,Fast Note Launcher,Sticky Notes Speedup,Rapid App Accessibility,Efficient Window Management,Quick Sticky Tools,Accelerated Notetaking
thumbnail: https://thmb.techidaily.com/acb788606a304c096daa8263d45d00ea2b9351615c5d83ea5a34a4991c1927bf.jpg
---

## Streamlined Commence: Quickly Open Windows and Sticky Notes

 Are you tired of opening Sticky Notes every time you turn on your computer? What if it could open automatically each time Windows starts?

 Well, there's good news for you: Sticky Notes can launch at startup in Windows. This article illustrates how to set up and use Sticky Notes at startup.

## 1\. Keep Sticky Notes Open at Shutdown

 When you're done working with Sticky Notes, make sure not to close the window. Instead, leave it open as you shut down your computer. This will ensure that when you turn on your computer, Sticky Notes opens automatically.

 Although the solution is simple, it may not work, or you may find it difficult to remember to keep it open when you turn off your PC. In that case, there are other alternatives; add Sticky Notes to the startup folder or use Task Scheduler.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iOVkXoUxLf4?si=QfC18T2cb5OkiaXo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Add Sticky Notes to the Startup Folder

 If you don't want to keep Sticky Notes open at shutdown, you can add it to the startup folder. The Startup folder is a special directory in File Explorer. It stores applications that launch automatically when Windows starts.

 To add Sticky Notes to the Startup folder, follow these steps.

1. Press **Win + R** and type **shell:startup** in the Run dialog.
2. Click **OK** or press Enter. This opens a folder containing all the applications that launch at startup.
3. Press **Windows** to open the Start menu, then click **All apps**. Now scroll down and find **Sticky Notes** in the list.
4. Drag and drop **Sticky Notes** into the Startup folder.

 After performing these steps, close File Explorer and restart your computer. Sticky Notes should now open at startup.

## 3\. Use the Task Scheduler

 Task Scheduler is another way to open Sticky Notes at startup. This Windows feature schedules and automates tasks at specific times or conditions.

 To add Sticky Notes using this tool, follow these steps:

1. [Open Task Scheduler](https://www.makeuseof.com/windows-11-open-task-scheduler/).
2. Click **Create Basic Task** from the **Actions** panel on the right. This opens a wizard that guides you through the setup.  
![Create Basic Task in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-in-task-scheduler.jpg)
3. In the first step, give your task a name and click **Next**.  
![Startup Sticky Notes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-sticky-notes.jpg)
4. Now select **When I log on** as the trigger and click **Next** at the bottom.  
![Create Basic Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-wizard.jpg)
5. Choose **Start a program** in the Action window and click **Next**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LT4sdZgUvRQ?si=SvQD5FouEzu4UHpJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Start a program in Action tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-action-tab.jpg)
6. In the **Program/script** field, type the path below:  
C:\Windows\System32\cmd.exe
7. In the Add arguments (optional) field, copy and paste the following command:  
/c start shell:appsfolder\Microsoft.MicrosoftStickyNotes_8wekyb3d8bbwe!App  
![Start a Program in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-task-scheduler.jpg)
8. Click **Next** and review all the settings.
9. Now click **Finish** to save your work.  
![Finish Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/finish-task-wizard.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sn2STvYRVb8?si=Z-XhJJ1Mc-Em5Kqy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The Task Scheduler will now run Sticky Notes each time you log in. This way, Sticky Notes launches automatically at startup.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Tweak the Registry Editor

 If you're comfortable editing the Windows registry, you can tweak it to open Sticky Notes at startup. This method requires knowledge of how the Registry Editor works and caution when editing it. If done incorrectly, it can cause serious system errors. It's best to [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing anything.

 To open Sticky Notes at startup using the Registry Editor, follow these steps:

1. [Open Windows Search](https://www.makeuseof.com/windows-search-use-guide/).
2. Type **regedit** in the search bar and click on the Registry Editor option.
3. If the UAC dialog appears, click **Yes** to grant access.
4. In the Registry Editor window, navigate to the following path:  
Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\PenWorkspace\Notes
5. Double-click the **LaunchOnNextUserSession** key on the right.  
![Tweak Registry Editor to Open Sticky Notes at Startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tweak-registry-editor-to-open-sticky-notes-at-startup.jpg)
6. Change the Value data from 0 to **1** in the Edit DWORD (32-bit) Value window and click **OK**.  
 If you can't find the **LaunchOnNextUserSession** key, right-click on the **Notes** folder and select **New > DWORD (32-bit) Value**. Name the newly created key “LaunchOnNextUserSession” and assign it the Value data of **1**.
7. Close the Registry Editor and restart your computer to save the changes. Sticky Notes should now open at startup.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HMuxjTCMX2E?si=ylRTMJuUstpjLsZc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Windows Now Starts With Sticky Notes Open

 This article outlines several ways to open Sticky Notes at startup in Windows. If you want an easier solution, leave Sticky Notes open when you shut down your computer; it will launch automatically when Windows starts. If not, add Sticky Notes to the startup folder. If you want more control over when Sticky Notes launches, use Task Scheduler or tweak the Registry Editor.

 Well, there's good news for you: Sticky Notes can launch at startup in Windows. This article illustrates how to set up and use Sticky Notes at startup.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-zero.techidaily.com/op-picks-7-exceptional-android-adblocking-apps/"><u>[New] Top Picks 7 Exceptional Android AdBlocking Apps</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-targeted-success-identifying-youtube-niche-demand/"><u>[Updated] 2024 Approved Targeted Success Identifying YouTube Niche Demand</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-insta-editing-secrets-mastering-high-resolution-footage-in-fcpx-for-2024/"><u>[Updated] Insta-Editing Secrets Mastering High-Resolution Footage in FCPX for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-vr-unveiled-understanding-the-digital-illusion/"><u>[Updated] VR Unveiled Understanding the Digital Illusion</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-video-textualizer/"><u>2024 Approved Video Textualizer</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210500036-9780960075768-ask-the-animals-and-they-shall-teach-thee-harness-the-new-year-with-feng-shui-and-the-chinese-animals/"><u>Ask the Animals and They Shall Teach Thee Harness the New Year with Feng Shui and the Chinese Animals | Free Book</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-9-enhancements-in-windows-modern-outlook/"><u>Discover 9 Enhancements in Windows' Modern Outlook</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-change-credit-card-from-your-iphone-6s-apple-id-and-apple-pay-by-drfone-ios/"><u>How to Change Credit Card from Your iPhone 6s Apple ID and Apple Pay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-overcome-windows-installation-mishap-0xc004f050/"><u>How to Overcome Windows Installation Mishap 0xC004F050</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-management-of-windows-credentials-11/"><u>Mastering the Management of Windows Credentials (11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-potential-unlock-the-most-innovative-windows-powertoy-tips/"><u>Maximize Potential: Unlock the Most Innovative Windows PowerToy Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-win-11s-task-monitor-real-time-updates/"><u>Optimize Win 11'S Task Monitor Real-Time Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-obstacles-reinstate-mspm-in-windows-7/"><u>Overcome Obstacles: Reinstate MSPM in Windows 7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-blocks-from-microsoft-store-usage-in-windows-11/"><u>Removing Blocks From Microsoft Store Usage in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-headset-mic-connectivity-issues/"><u>Resolving Windows Headset Mic Connectivity Issues</u></a></li>
<li><a href="https://hardware-help.techidaily.com/the-rising-demand-why-choose-pure-unmodified-android-experience/"><u>The Rising Demand: Why Choose Pure, Unmodified Android Experience?</u></a></li>
<li><a href="https://some-tips.techidaily.com/transform-your-tiktok-experience-with-new-user-numbers-for-2024/"><u>Transform Your TikTok Experience with New User Numbers for 2024</u></a></li>
</ul></div>

