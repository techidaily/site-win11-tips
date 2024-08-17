---
title: "Workflow Enhancer: Integrating Sticky Notes Into Your Windows Morning Ritual"
date: 2024-08-16T02:17:00.057Z
updated: 2024-08-17T02:17:00.057Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Workflow Enhancer: Integrating Sticky Notes Into Your Windows Morning Ritual"
excerpt: "This Article Describes Workflow Enhancer: Integrating Sticky Notes Into Your Windows Morning Ritual"
keywords: Workflow Boost,Notebook Routine,Windows Startup,Productivity Tips,Notepad Integration,Morning Habits,Efficiency Improvement
thumbnail: https://thmb.techidaily.com/88bfebb08e4cbb8d0a68e78c0297b8f1e363343f342702915251fd121c5a13e0.jpg
---

## Workflow Enhancer: Integrating Sticky Notes Into Your Windows Morning Ritual

 Are you tired of opening Sticky Notes every time you turn on your computer? What if it could open automatically each time Windows starts?

 Well, there's good news for you: Sticky Notes can launch at startup in Windows. This article illustrates how to set up and use Sticky Notes at startup.

## 1\. Keep Sticky Notes Open at Shutdown

 When you're done working with Sticky Notes, make sure not to close the window. Instead, leave it open as you shut down your computer. This will ensure that when you turn on your computer, Sticky Notes opens automatically.

 Although the solution is simple, it may not work, or you may find it difficult to remember to keep it open when you turn off your PC. In that case, there are other alternatives; add Sticky Notes to the startup folder or use Task Scheduler.

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
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
<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. In the first step, give your task a name and click **Next**.  
![Startup Sticky Notes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-sticky-notes.jpg)
4. Now select **When I log on** as the trigger and click **Next** at the bottom.  
![Create Basic Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-wizard.jpg)
5. Choose **Start a program** in the Action window and click **Next**.  
![Start a program in Action tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-action-tab.jpg)
6. In the **Program/script** field, type the path below:  
C:\Windows\System32\cmd.exe
7. In the Add arguments (optional) field, copy and paste the following command:  
/c start shell:appsfolder\Microsoft.MicrosoftStickyNotes_8wekyb3d8bbwe!App ![Start a Program in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-task-scheduler.jpg)
<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Click **Next** and review all the settings.
9. Now click **Finish** to save your work.  
![Finish Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/finish-task-wizard.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->

 The Task Scheduler will now run Sticky Notes each time you log in. This way, Sticky Notes launches automatically at startup.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
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
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
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
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-achieving-professional-skype-recordings-in-obs/"><u>[New] 2024 Approved  Achieving Professional Skype Recordings in OBS</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-elevate-your-yt-marketing-essential-tips-for-higher-rankings/"><u>[New] 2024 Approved  Elevate Your YT Marketing  Essential Tips for Higher Rankings</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-smartest-devices-to-modify-your-speech-on-the-go/"><u>[New] 2024 Approved  Smartest Devices to Modify Your Speech on the Go</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-tailored-instagram-filters-a-step-by-step-process/"><u>[New] 2024 Approved  Tailored Instagram Filters  A Step-by-Step Process</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/rafting-content-that-captivates-youtube-keyword-mastery/"><u>[New] Crafting Content that Captivates  YouTube Keyword Mastery</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-gourmet-giants-culinary-stars-you-must-subscribe-to/"><u>[New] In 2024, Gourmet Giants  Culinary Stars You Must Subscribe To</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-jumpstart-connections-winning-tinder-bios-at-a-glance/"><u>[New] In 2024, Jumpstart Connections  Winning Tinder Bios at a Glance</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-streamline-discord-the-ultimate-list-of-10-key-plugins/"><u>[Updated] 2024 Approved  Streamline Discord  The Ultimate List of 10 Key Plugins</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-tech-tutorial-download-youtube-for-your-idevice-securely/"><u>[Updated] 2024 Approved  Tech Tutorial  Download YouTube for Your iDevice Securely</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-exploring-the-world-of-webcam-professional-videotaping-for-2024/"><u>[Updated] Exploring the World of WebCam Professional Videotaping for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-unveiling-top-rated-video-recorders-for-windows/"><u>[Updated] In 2024, Unveiling Top-Rated Video Recorders for Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/2-ways-to-transfer-text-messages-from-realme-c67-4g-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>2 Ways to Transfer Text Messages from Realme C67 4G to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-bites-of-wisdom-youtube-tvs-unique-selling-points/"><u>2024 Approved  Bites of Wisdom  YouTube TV's Unique Selling Points</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-facts-you-need-to-know-about-screen-mirroring-samsung-galaxy-a15-4g-drfone-by-drfone-android/"><u>3 Facts You Need to Know about Screen Mirroring Samsung Galaxy A15 4G | Dr.fone</u></a></li>
<li><a href="https://article-tips.techidaily.com/a-beginner-friendly-approach-to-srt-knowledge/"><u>A Beginner-Friendly Approach to SRT Knowledge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-technical-odyssey-embracing-hdr-in-windows-11-environments/"><u>A Technical Odyssey: Embracing HDR in Windows 11 Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-device-to-windows-microphone-setup/"><u>Android Device to Windows Microphone Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blend-in-with-the-background-hide-taskbars-language-bar-win11/"><u>Blend in with the Background: Hide Taskbar's Language Bar, Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-user-interface-add-psoft-tools-to-windows-11/"><u>Boosting User Interface: Add PSoft Tools to Windows 11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/discover-variety-50-complimentary-youtube-banners-available-in-2024/"><u>Discover Variety – 50 Complimentary YouTube Banners Available, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-subsystem-with-5-crucial-techniques/"><u>Enhancing Windows Subsystem with 5 Crucial Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-to-unlock-disks-in-w10-and-w11/"><u>Essential Steps to Unlock Disks in W10 & W11</u></a></li>
<li><a href="https://technical-tips.techidaily.com/expert-advice-on-handling-there-was-an-issue-resetting-your-pc-a-comprehensive-guide/"><u>Expert Advice on Handling There Was an Issue Resetting Your PC - A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-vivetool-windows-gateway-to-new-and-emerging-tools/"><u>Exploring ViVeTool: Windows' Gateway to New & Emerging Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-app-install-issues-on-microsoft-store/"><u>Fixing App Install Issues on Microsoft Store</u></a></li>
<li><a href="https://apple-account.techidaily.com/guide-on-how-to-remove-apple-id-from-apple-iphone-11-pro-by-drfone-ios/"><u>Guide on How To Remove Apple ID From Apple iPhone 11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-fatal-error-c0000022-in-windows/"><u>How to Fix the Fatal Error C0000022 in Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-oneplus-12-drfone-by-drfone-virtual-android/"><u>How to Get and Use Pokemon Go Promo Codes On OnePlus 12 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-handle-internal-windows-error-during-remote-desktop-use/"><u>How to Handle Internal Windows Error During Remote Desktop Use</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-honor-v-purse-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Honor V Purse to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implementing-edthemes-in-windows-11/"><u>Implementing EdThemes in Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-motorola-moto-g34-5g-to-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Motorola Moto G34 5G To Phone | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-peak-commercial-sky-storage-providers/"><u>In 2024, Peak Commercial Sky-Storage Providers</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-sim-unlock-code-generators-unlock-your-honor-x50i-phone-hassle-free-by-drfone-android/"><u>In 2024, The Best Android SIM Unlock Code Generators Unlock Your Honor X50i Phone Hassle-Free</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-ways-to-find-unlocking-codes-for-poco-c51-phones-by-drfone-android/"><u>In 2024, Ways To Find Unlocking Codes For Poco C51 Phones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lowering-resource-usage-in-windows-modules-installer/"><u>Lowering Resource Usage in Windows Modules Installer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-speech-output-in-windows-environment/"><u>Mastering Speech Output in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-freeing-up-your-c-drive-space/"><u>Mastering the Art of Freeing Up Your C: Drive Space</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-efficiency-guide/"><u>Mastering Windows 11: Efficiency Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-microsoft-pc-manager-bar-tools-on-w11/"><u>Navigating Microsoft PC Manager Bar Tools on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-failure-to-install-win11s-v22h2-update/"><u>Navigating Through Failure to Install Win11's V22H2 Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/nine-must-have-android-apps-for-windows-users/"><u>Nine Must-Have Android Apps for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-internet-unreachability-issue/"><u>Overcoming Internet Unreachability Issue</u></a></li>
<li><a href="https://tech-haven.techidaily.com/prepare-like-a-pro-how-chatgpt-can-enhance-your-job-interview-readiness/"><u>Prepare Like a Pro: How ChatGPT Can Enhance Your Job Interview Readiness</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/profit-prospects-analyzing-youtubes-monetization-mechanisms-for-2024/"><u>Profit Prospects  Analyzing YouTube's Monetization Mechanisms for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-tips-for-modifying-windows-passcode/"><u>Quick Tips for Modifying Windows Passcode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-windows-standard-power-profile/"><u>Restoring Windows' Standard Power Profile</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safeguarding-internal-builds-in-windows-11/"><u>Safeguarding Internal Builds in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secrets-to-turn-off-lurking-apps-in-window-11/"><u>Secrets to Turn Off Lurking Apps in Window 11</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/secure-and-ethical-paths-to-increasing-your-tiktok-following/"><u>Secure & Ethical Paths to Increasing Your TikTok Following</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-guide-for-converting-cr2-images-to-windows-jpeg-files/"><u>Stepwise Guide for Converting CR2 Images to Windows JPEG Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-manage-disks-keyways-into-windows-11s-storage-manager/"><u>Swiftly Manage Disks: Keyways Into Windows 11'S Storage Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackle-windows-camera-problems-with-expert-tips/"><u>Tackle Windows Camera Problems with Expert Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719237818540-trouble-with-compatibility-try-these-straightforward-fixes-now/"><u>Trouble with Compatibility? Try These Straightforward Fixes Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-xbox-apps-voice-issues-in-windows/"><u>Understanding Xbox App's Voice Issues in Windows</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/unlocking-the-full-potential-of-iphone-7-screen-save/"><u>Unlocking the Full Potential of iPhone 7 Screen Save</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unzipping-challenge-managing-multiple-compressed-files-in-a-snap/"><u>Unzipping Challenge: Managing Multiple Compressed Files in a Snap</u></a></li>
<li><a href="https://howto.techidaily.com/want-to-uninstall-google-play-service-from-infinix-hot-30-5g-here-is-how-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Want to Uninstall Google Play Service from Infinix Hot 30 5G? Here is How | Dr.fone</u></a></li>
</ul></div>
