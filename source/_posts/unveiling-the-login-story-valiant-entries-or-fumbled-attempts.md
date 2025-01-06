---
title: "Unveiling the Login Story: Valiant Entries or Fumbled Attempts"
date: 2024-12-30T06:17:44.160Z
updated: 2025-01-05T22:28:12.717Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unveiling the Login Story: Valiant Entries or Fumbled Attempts"
excerpt: "This Article Describes Unveiling the Login Story: Valiant Entries or Fumbled Attempts"
keywords: Unveiled Login Tales,Entry Attempts Analysis,Valiant Logins Explored,Login Success Stories,Failed Login Recounts,Attempted Entries Review,Valiant Login Journeys
thumbnail: https://thmb.techidaily.com/22dc377b14c8750c75c360ab6d9b7d702e69a18c8a5a08c607e9cd26432f995f.jpg
---

## Unveiling the Login Story: Valiant Entries or Fumbled Attempts

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rxyki8-Y630?si=dHLkIxG59zdlZeN0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/HSFNIAYChbA?si=4TIlsUrYmY5vP2il" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Decipher the Logon Entries in Event Viewer

 While Event ID 4624 is associated with logon events, you will likely find multiple instances of this entry occurring every few minutes in the log. This is due to Event Viewer recording every logon event (whether from the local user account or system services such as Windows Security) with the same event ID**(Event 4624**).

![event viewer security logon event properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-properties.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To identify the source of login, right-click on the event record and select**Properties** . In the**General** tab, scroll down and locate the**Logon information** section. Here, the**Logon Type** field indicates the kind of logon that occurred.

 For example,**Logon Type 5** indicates a service-based login, while**Logon Type 2** indicates user-based login. Know more about the different logon types in the table below.

![event viewer security logon event properties details 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-properties-details-1.jpg)

 Next, scroll down to the**New Logon** section and locate the**Security ID** . This will show the user account that was affected by the logon.

![event viewer security logon event failed attemptjpg](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-failed-attemptjpg.jpg)

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/ITtcSWvS8bo?si=4M4BfMgaabrW6148" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/YfEPmG_O6F8?si=93ZTVtH_zjFRz5eh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-zero.techidaily.com/ealing-with-copyright-infringement-notices-on-youtube/"><u>[New] Dealing with Copyright Infringement Notices on YouTube</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-getting-windows-movie-maker-6-installed-quickly-and-easily/"><u>[New] Getting Windows Movie Maker 6 Installed Quickly & Easily</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-mastering-the-art-of-engaging-facebook-video-ads/"><u>[New] In 2024, Mastering the Art of Engaging Facebook Video Ads</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-streamline-your-life-quick-tips-to-beginning-on-discord-broadcasts-for-2024/"><u>[New] Streamline Your Life Quick Tips to Beginning on Discord Broadcasts for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/decoding-the-puzzle-insights-into-the-nyts-may-17-connection-challenge-hint-set-341/"><u>Decoding the Puzzle: Insights Into The NYT's May 17 Connection Challenge (Hint Set #341)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-fixes-for-repeated-usernamepassword-notifications/"><u>Efficient Fixes for Repeated 'Username/Password' Notifications</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-picks-the-ultimate-selection-of-55-inch-televisions-insights-from-zdnet/"><u>Expert Picks: The Ultimate Selection of 55-Inch Televisions - Insights From ZDNET</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-change-the-date-created-date-modified-and-other-file-attributes-on-windows/"><u>How to Change the Date Created, Date Modified, and Other File Attributes on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/legitimate-methods-vs-chatbots-for-secure-win-11-passwords/"><u>Legitimate Methods Vs. Chatbots for Secure Win 11 Passwords</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-windows-mobility-shutdown/"><u>Master the Art of Windows Mobility Shutdown</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-unable-to-connect-issues-with-malwarebytes-server-link/"><u>Rectifying Unable to Connect Issues with Malwarebytes Server Link</u></a></li>
<li><a href="https://buynow-info.techidaily.com/review-of-amplifi-hd-mesh-networking-solutions-eliminate-your-homes-wi-fi-coverage-gaps/"><u>Review of Amplifi HD Mesh Networking Solutions: Eliminate Your Home's Wi-Fi Coverage Gaps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/self-host-your-local-free-windows-based-chatgpt-clone-using-gpt4all/"><u>Self-Host Your Local, FREE Windows-Based ChatGPT Clone Using GPT4All</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solve-windows-permanent-temp-file-dilemma/"><u>Solve Windows' Permanent Temp File Dilemma</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-task-execution-in-windows-11-with-a-superior-run-setup/"><u>Transform Your Task Execution in Windows 11 with a Superior Run Setup</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/turboinsta-video-boosting-online-and-mobile-fixes-for-2024/"><u>TurboInsta Video Boosting Online & Mobile Fixes for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-full-potential-with-top-4-windows-webp-viewers/"><u>Unlock Full Potential with Top 4 Windows WebP Viewers</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unlocking-new-potentials-for-sites-with-artificial-intelligence-integration-in-search-engines/"><u>Unlocking New Potentials for Sites with Artificial Intelligence Integration in Search Engines</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-oppo-a78-5g-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your Oppo A78 5G Auto Does Not Work | Dr.fone</u></a></li>
</ul></div>

