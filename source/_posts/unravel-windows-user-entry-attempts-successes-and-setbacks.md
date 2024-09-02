---
title: "Unravel Windows User Entry Attempts: Successes and Setbacks"
date: 2024-09-01T05:16:59.348Z
updated: 2024-09-02T05:16:59.348Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unravel Windows User Entry Attempts: Successes and Setbacks"
excerpt: "This Article Describes Unravel Windows User Entry Attempts: Successes and Setbacks"
keywords: Windows Security Logs,Failed Login Windows,WinUserEntrySuccesses,UserLoginFailures,Access Attempt Records,EntryPointWindows,Authentication Windows Issues
thumbnail: https://thmb.techidaily.com/4f39ebc55802b5fd29e1ead6db3dfc5174731a378a897f2615b5059637faad66.png
---

## Unravel Windows User Entry Attempts: Successes and Setbacks

 Windows lets you create multiple user accounts to let multiple users use a single computer. But what if you suspect someone to have accessed your PC or user account without your knowledge?

 While physically monitoring your computer all the time is not feasible for most people, the built-in Windows log utility, Event Viewer, can reveal the recent activities on your computer, including login attempts. Here we show you how to audit failed and successful login attempts in Windows using Event Viewer and other methods.

## How to Enable Logon Auditing via Group Policy Editor

 You need to enable logon auditing in Group Policy Editor to be able to view login audit in Event Viewer. While this feature may be enabled by default on some computers, you can also enable logon auditing manually by following these steps.

 Note that Group Policy Editor is only available on the Pro, Edu, and Enterprise edition of the Windows OS. If you are on the Home edition, follow our guide to[enable gpedit in the Windows home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 Note that if you don't configure your Group Policy for Logon Auditing, you can only view the successful login attempts in Event Viewer.

 Once you have the Group Policy Editor enabled, follow these steps to enable logon auditing:

1. Press**Win + R** to open**Run** .
2. Type**gpedit.msc** and click**OK** to open the**Group Policy Editor.**
3. Next, navigate to the following location:  
`Computer Configuration > Windows Settings > Security Settings > Local Policies > Audit Policy`
4. In the right pane, right-click on**Audit logon events** and select**Properties** .  
![group policy editor audit logon events properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/group-policy-editor-audit-logon-events-properties.jpg)
5. In the**Properties** dialog, select**Success** and**Failure** options under the**Audit these attempts** section.  
![group policy editor audit logon events properties enable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/group-policy-editor-audit-logon-events-properties-enable.jpg)
6. Click**Apply** and**OK** to save the changes.

 Close Group Policy Editor and move to the next set of steps to view login attempts in Event Viewer.

## How to View Failed and Successful Login Attempts in Event Viewer

 The[Event Viewer](https://www.makeuseof.com/windows-event-viewer-guide/) lets you view Windows logs for the application, security, system, and other events. While a useful application to troubleshoot system issues, you can use it to audit login events on your Windows PC.

 Follow these steps to view failed and successful login attempts in Windows:

1. Press the**Win key** and type**event viewer.** Alternatively, click on**Search** in the taskbar and type**event viewer.**
2. Click on**Event Viewer** from the search result to open it.
3. In the left pane, expand the**Windows Logs** section.  
![event viewer security logon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon.jpg)
4. Next, select**Security** .
5. In the right pane, locate the**Event 4624** entry. It is a user logon event ID, and you may find multiple instances of this ID in the event log.
6. To find failed login attempts, locate**Event ID 2625** entries instead.
7. Next, select the**Event 4624** entry you want to view, and Event Viewer will display all the related information in the bottom section. Alternatively, right-click on the event entry and select**Properties** to view detailed information in a new window.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Decipher the Logon Entries in Event Viewer

 While Event ID 4624 is associated with logon events, you will likely find multiple instances of this entry occurring every few minutes in the log. This is due to Event Viewer recording every logon event (whether from the local user account or system services such as Windows Security) with the same event ID**(Event 4624**).

![event viewer security logon event properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-properties.jpg)

<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To identify the source of login, right-click on the event record and select**Properties** . In the**General** tab, scroll down and locate the**Logon information** section. Here, the**Logon Type** field indicates the kind of logon that occurred.

 For example,**Logon Type 5** indicates a service-based login, while**Logon Type 2** indicates user-based login. Know more about the different logon types in the table below.

![event viewer security logon event properties details 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-properties-details-1.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 Next, scroll down to the**New Logon** section and locate the**Security ID** . This will show the user account that was affected by the logon.

![event viewer security logon event failed attemptjpg](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-failed-attemptjpg.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
 Similarly, for failed login attempts, review**Event ID 4625** . In the**Properties** dialog, you can find reasons for the failed login attempt and the affected user account. If you find multiple instances of unsuccessful attempts, consider learning[how to limit the number of failed login attempts to protect your Windows PC](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) .

 Below is the list of all nine**Logon Types** for logon events that you may encounter reviewing login events in Event Viewer:

| **Logon Type** | **Description**                                                                                                                                   |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| Logon Type 2   | A local user logged on to this computer.                                                                                                          |
| Logon Type 3   | A user logged on to this computer from the network.                                                                                               |
| Logon Type 4   | Batch logon type without user intervention – Scheduled Tasks, etc.                                                                                |
| Logon Type 5   | Logon by system service started by Service Control Manager – Most common type                                                                     |
| Logon Type 7   | System unlocked by a local account user                                                                                                           |
| Logon Type 8   | NetworkClearText - Logon attempted over the network where the password was sent as clear text.                                                    |
| Logon Type 9   | NewCredentials – triggered when a user uses the RunAs command with the /netonly option to start a program.                                        |
| Logon Type 10  | RemoteInteractive – Generated when a computer is accessed via a remote access tool such as Remote Desktop Connection.                             |
| Logon Type 11  | CachedInteractive – When the user logged on to the computer via console using the cached credentials when the domain controller is not available. |

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to View the Last Logon History Using Command Prompt

![view specific user last login attempt command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/view-specific-user-last-login-attempt-command-prompt.jpg)

 You can use the Command Prompt to view the last login attempt. It is a handy way to find user-based login attempts without having to go through all the logon events in Event Viewer.

To view the login history of a specific user using Command Prompt:

1. Press**Win + R** to open**Run** .
2. Type**cmd** . While holding the**Ctrl + Shift key** , click**OK** . This will open the**Command Prompt** as administrator.
3. In the Command Prompt window, type the following command and press Enter:  
`net user administrator | findstr /B /C:"Last logon"`
4. In the above command, replace "administrator" with the username to view their login history.
5. The output will show the last login time and date for the specified user.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
## Viewing Failed and Successful Login Attempts in Windows

 If you suspect someone to have logged in to your PC, the Event Viewer will likely catch and record the attempt. For this to work, you must enable the Logon Auditing policy in Group Policy Editor. You can also use Command Prompt to view a specific user's login history.

 That said, anyone who knows their way around Event Viewer can easily clear the logs. So, if anything, beefing up your Windows computer security is the best way to prevent unauthorized access. You can begin by limiting the number of failed login attempts on your Windows PC.

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
<li><a href="https://facebook-record-videos.techidaily.com/new-a-step-by-step-approach-to-professional-video-sharing-for-2024/"><u>[New] A Step-by-Step Approach to Professional Video Sharing for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-arcade-affordability-index/"><u>[New] ARCADE AFFORDABILITY INDEX</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-top-strategies-for-ps4-video-game-preservation/"><u>[New] In 2024, Top Strategies for PS4 Video Game Preservation</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-master-quick-red-eye-correction-with-this-free-ios-tool/"><u>[New] Master Quick Red-Eye Correction with This Free iOS Tool</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-essential-tips-sharing-your-apple-devices-screen-with-youtube/"><u>[Updated] 2024 Approved  Essential Tips  Sharing Your Apple Devices Screen with YouTube</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-sharing-the-vibe-how-to-post-tiktok-videos-to-facebook/"><u>[Updated] In 2024, Sharing the Vibe  How to Post TikTok Videos to Facebook</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-ios-and-ps2-gaming-top-emulators-unveiled-for-2024/"><u>[Updated] IOS and PS2 Gaming  Top Emulators Unveiled for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-essential-skills-editing-blurring-and-background-removal/"><u>2024 Approved  The Essential Skills  Editing, Blurring, and Background Removal</u></a></li>
<li><a href="https://techidaily.com/bypassing-the-chatgpt-limit-strategies-to-avoid-too-many-requests-after-an-hour/"><u>Bypassing the ChatGPT Limit: Strategies to Avoid 'Too Many Requests' After an Hour</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-the-0x0-error-essential-fixes-for-win11-users/"><u>Conquer the 0X0 Error: Essential Fixes for Win11 Users</u></a></li>
<li><a href="https://extra-information.techidaily.com/crafting-impeccable-srt-from-xml-ssa-and-ttml-files/"><u>Crafting Impeccable SRT From XML, SSA & TTML Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-hidden-patterns-in-data-usage-through-windows-diskusage-command/"><u>Discovering Hidden Patterns in Data Usage Through Windows' DiskUsage Command</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/easy-screencasting-techniques-systematic-guidebook-for-2024/"><u>Easy Screencasting Techniques  Systematic Guidebook for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-phone-to-windows-audio-streaming-tips/"><u>Effortless Phone-to-Windows Audio Streaming Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-seamless-live-stream-quality-with-steam/"><u>Ensuring Seamless Live Stream Quality with Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-non-windows-apps-for-modern-computing/"><u>Essential Non-Windows Apps For Modern Computing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-opengl-issue-3-with-nvidia-on-windows-11-os/"><u>Fixing OpenGL Issue #3 with NVIDIA on Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-through-the-maze-of-windows-10-crash-modes/"><u>Guide Through the Maze of Windows 10 Crash Modes</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-remove-google-frp-lock-on-v29-by-drfone-android-unlock-remove-google-frp/"><u>How to remove Google FRP Lock on V29</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-critical-js-error-affecting-discord-on-modern-windows-devices/"><u>How to Resolve Critical JS Error Affecting Discord on Modern Windows Devices</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-disabled-iphone-xsipad-without-computer-drfone-by-drfone-ios/"><u>How to Unlock Disabled iPhone XS/iPad Without Computer | Dr.fone</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/hp-stream-11-review/"><u>HP Stream 11 Review</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-oneplus-ace-3-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On OnePlus Ace 3 | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-fake-snapchat-location-without-jailbreak-on-poco-c51-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fake Snapchat Location without Jailbreak On Poco C51 | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-disabled-apple-iphone-seipad-without-computer-drfone-by-drfone-ios/"><u>In 2024, How to Unlock Disabled Apple iPhone SE/iPad Without Computer | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlocking-made-easy-the-best-10-apps-for-unlocking-your-samsung-device-by-drfone-android/"><u>In 2024, Unlocking Made Easy The Best 10 Apps for Unlocking Your Samsung Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-analysis-executing-powerful-registry-changes-via-terminal/"><u>In-Depth Analysis: Executing Powerful Registry Changes via Terminal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/initiating-quick-assistance-on-windows-11/"><u>Initiating Quick Assistance on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insight-into-vcplusplus-redistributable-needs/"><u>Insight Into VC++ Redistributable Needs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/installing-the-latest-windows-11-arm-via-iso-instructions/"><u>Installing the Latest Windows 11 ARM via ISO Instructions</u></a></li>
<li><a href="https://buynow-info.techidaily.com/introducing-nickwatch-premiering-on-american-soil-during-kcas/"><u>Introducing NickWatch: Premiering on American Soil During KCAs</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/iphone-guide-to-achieving-stunning-hdr-photos/"><u>IPhone Guide to Achieving Stunning HDR Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/judging-the-adequacy-of-windows-11s-visual-extras/"><u>Judging the Adequacy of Windows 11'S Visual Extras</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-honor-x50i-drfone-by-drfone-virtual-android/"><u>Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Honor X50i | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-desktop-art-windows-1011-tutorials/"><u>Mastering Desktop Art: Windows 10/11 Tutorials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-fix-loaded-lol-screens/"><u>Mastering Windows: Fix Loaded LOL Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-samsungs-dex-the-ultimate-users-blueprint/"><u>Navigating Samsung’s DeX: The Ultimate User’s Blueprint</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-common-winx-update-errors/"><u>Overcoming Common WinX Update Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-hurdles-with-windows-1011s-missing-search-output/"><u>Overcoming Hurdles with Windows 10/11'S Missing Search Output</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-windows-inbuilt-pdf-renderer/"><u>Personalizing Windows' Inbuilt PDF Renderer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/protecting-privacy-the-ultimate-windows-encryption-list-152-chars/"><u>Protecting Privacy: The Ultimate Window's Encryption List (152 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-remedy-for-world-of-warcrafts-fatal-error-132-on-win11/"><u>Quick Remedy for World of Warcraft's Fatal Error 132 on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-lost-entry-point-of-mcuicnt-in-windows-os/"><u>Reinstating Lost Entry Point of McUICnt in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-world-of-warcrafts-unresponsive-crash-132/"><u>Remedying World of Warcraft's Unresponsive Crash #132</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sidestep-mobility-center-stay-in-full-screen/"><u>Sidestep Mobility Center, Stay In Full Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slow-down-windows-10-shutdown-during-running-tasks-with-these-tips/"><u>Slow Down Windows 10 Shutdown During Running Tasks with These Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snapping-into-action-activate-snipping-tool-in-windows-11/"><u>Snapping Into Action: Activate Snipping Tool in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-dealing-with-immutable-energy-states-in-windows-11/"><u>Solutions for Dealing with Immutable Energy States in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stealth-meets-practicality-asus-s15-review-analysis/"><u>Stealth Meets Practicality - ASUS S15 Review Analysis</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/step-by-step-guide-to-adding-frames-on-instagram-photos-for-2024/"><u>Step-by-Step Guide to Adding Frames on Instagram Photos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-security-for-browsers-trustable-sites-in-windows-11/"><u>Tailored Security for Browsers: Trustable Sites in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tame-excessive-system-update-notifications-in-windows-11/"><u>Tame Excessive System Update Notifications in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tcp-port-identification-on-windows-devices/"><u>TCP Port Identification on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-resolve-disk-usage-errors-in-windows-11-os/"><u>Techniques to Resolve Disk Usage Errors in Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-pathway-to-efficient-work-implementing-outlook-preview-in-windows-11/"><u>The Pathway to Efficient Work: Implementing Outlook Preview in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-unblock-overloaded-gpt-windows-errors/"><u>Tips to Unblock Overloaded GPT Windows Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-workflow-essential-tips-for-taskbar-users/"><u>Transform Your Workflow: Essential Tips for Taskbar Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-error-0x803f700f-in-windows-activation/"><u>Troubleshooting Error 0X803F700F in Windows Activation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-code-0x80780119-restore-mishap/"><u>Unraveling Windows' Code 0X80780119 Restore Mishap</u></a></li>
<li><a href="https://fake-location.techidaily.com/which-is-the-best-fake-gps-joystick-app-on-itel-p55-5g-drfone-by-drfone-virtual-android/"><u>Which is the Best Fake GPS Joystick App On Itel P55 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-narrative-engagement-startup/"><u>Windows 11 Narrative Engagement Startup</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/youtube-in-the-classroom-best-practices-and-tips-for-educators-for-2024/"><u>YouTube in the Classroom  Best Practices and Tips for Educators for 2024</u></a></li>
</ul></div>
