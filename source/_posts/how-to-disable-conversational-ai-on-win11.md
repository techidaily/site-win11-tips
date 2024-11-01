---
title: How to Disable Conversational AI on Win11
date: 2024-10-31T16:25:46.872Z
updated: 2024-11-01T19:30:09.007Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Disable Conversational AI on Win11
excerpt: This Article Describes How to Disable Conversational AI on Win11
keywords: Win11 AI Off Switch,Turn Off ChatBot Windows,Win11 Disable Assistant,Remove Microsoft's Conversational AI,Turn Chatbot OFF in Win11,Silence Win11 Virtual Assistant,Halt Win11 Voice Conversation
thumbnail: https://thmb.techidaily.com/c06aefbb181f576852b2577ec9d3544ebd6635b5e4bff4964dd308c72eeba377.jpg
---

## How to Disable Conversational AI on Win11

 Windows Copilot, Microsoft's new AI assistant, can assist you with a variety of tasks, such as answering questions, changing system settings, and creating AI images. However, if you're not a fan of Copilot or simply don't need it, you can remove its taskbar icon or disable it entirely on your Windows 11 PC. Here, we'll show you how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Remove the Copilot Icon From the Windows 11 Taskbar

 By default, the Copilot icon appears in the Windows 11 taskbar. However, if you prefer not to have it there but still want to use it occasionally, it's easy to hide the Copilot icon. Simply right-click anywhere on an empty spot on your taskbar and select **Taskbar settings**. In the Settings window that appears, turn off the toggle next to **Copilot**.

![Remove Copilot Icon From Windows 11 Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/remove-copilot-icon-from-windows-11-taskbar.jpg)

 This should remove the Copilot icon from the taskbar. You can still access Copilot by pressing the **Win + C** keyboard shortcut in Windows 11\.

<!-- affiliate ads begin -->
<span id="1155462">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1155462.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1155462">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1155462.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1155462%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1155462/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Completely Disable Copilot via Group Policy Settings

 Although hiding the Copilot is quite easy, it does not turn it off completely, and you might inadvertently access it. Fortunately, you can turn off Copilot completely via the Local Group Policy Editor on PCs running the Professional, Education, or Enterprise edition of Windows 11\.

 If you are using Windows 11 Home, skip to the Registry Editor method below or use a [workaround to enable the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Press **Win + S** to access the search menu.
2. Type **gpedit.msc** in the search box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **User Configuration > Administrative Templates > Windows Components > Windows Copilot**.
5. Double-click the **Turn off Windows Copilot** policy on your right.
6. Select the **Enabled** option.
7. Hit **Apply** followed by **OK**.  
![Turn Off Windows Copilot Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-windows-copilot-using-the-group-policy-editor.jpg)

<!-- affiliate ads begin -->
<span id="1484963">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1484963.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1484963">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1484963.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1484963%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1484963/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you complete the above steps, Copilot will be disabled on your Windows 11 PC and you won't be able to access it even with the keyboard shortcut. If you want to re-enable Copilot later, repeat the above steps and set the **Turn off Windows Copilot** policy to **Not configured** or **Disabled**.

## How to Completely Disable Copilot by Modifying Registry Files

 Another way to disable Copilot on Windows 11 involves modifying registry files. However, since editing the registry can be risky, you should follow the steps carefully. Also, be sure to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/). This will allow you to restore the registry files in case something goes wrong.

 Once you’ve done that, here’s what you need to do to disable Copilot via the Registry Editor:

1. Press **Win + R** to open the Run dialog.
2. Type **regedit** in the text box and press **Enter** to open the Registry Editor.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > Software > Policies > Microsoft > Windows**.
5. Right-click the **Windows** key and select **New > Key**. Name it **WindowsCopilot**.
6. Right-click on the **WindowsCopilot** DWORD, go to **New**, and select **DWORD (32-bit) Value** from the submenu. Name the DWORD **TurnOffWindowsCopilot**.
7. Double-click the **TurnOffWindowsCopilot** DWORD, type **1** in the text field, and click **OK**.
8. Restart your PC for the changes to take effect.  
![Turn Off Windows Copilot Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-windows-copilot-using-the-registry-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136536/16384" target="_top" id="2136536">
  <img src="//a.impactradius-go.com/display-ad/16384-2136536" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136536/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 And that’s about it. Windows Copilot will be disabled on your PC. To re-enable it in the future, repeat the above steps and set the **TurnOffWindowsCopilot** DWORD value to 0\. You can also delete the **TurnOffWindowsCopilot** DWORD instead.

<!-- affiliate ads begin -->
<span id="1328683">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1328683.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1328683">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1328683.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1328683%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1328683/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Rid of Copilot on Windows 11

 While Windows Copilot is a powerful tool, not everyone may want to use it. Fortunately, it’s possible to get rid of it. The above steps will help you achieve your goal, whether you want to keep Copilot out of sight or turn it off entirely.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-tricks-to-make-your-profile-video-stand-out/"><u>[New] Tricks to Make Your Profile Video Stand Out</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/outlook/"><u>「オンラインで便利な Outlook メールバックアップのテクニック: 手作業編集から洗練された自動化まで」</u></a></li>
<li><a href="https://video-capture.techidaily.com/1726030040741-musescore/"><u>完璧なサウンド出力: MuseScoreで高解像度オーディオを作成するためのテクニック</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-the-perfect-windows-11-search-experience/"><u>Crafting the Perfect Windows 11 Search Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-insights-making-most-of-windows-canary-channel/"><u>Essential Insights: Making Most of Windows Canary Channel</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/exclusive-insights-viewing-nba-games-remotely/"><u>Exclusive Insights Viewing NBA Games Remotely</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-infinix-smart-8-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on Infinix Smart 8 | Dr.fone</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-proactive-strategies-in-building-an-irresistible-online-identity-on-youtube/"><u>In 2024, Proactive Strategies in Building an Irresistible Online Identity on YouTube</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210693619-9798987183526-isabels-starry-night-the-magical-quest-for-alchemy/"><u>Isabel's Starry Night, The Magical Quest for Alchemy | Free Book</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-live-audio-transcription-with-smart-desktop-tech/"><u>Mastering Live Audio Transcription with Smart Desktop Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/professionals-insight-mastery-of-cmd-based-windows-registry-adjustments/"><u>Professionals' Insight: Mastery of CMD-Based Windows Registry Adjustments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-your-files-with-auto-move-command-on-win-11/"><u>Simplify Your Files with Auto-Move Command on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-a-stuck-downloads-area-on-windows-os/"><u>Solutions for a Stuck Downloads Area on Windows OS</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-strategies-for-mastering-teleport-commands-in-minecraft/"><u>Step-by-Step Strategies for Mastering Teleport Commands in Minecraft</u></a></li>
<li><a href="https://buynow-info.techidaily.com/unlimited-dvr-how-far-does-unlimited-truly-stretch/"><u>Unlimited DVR: How Far Does 'Unlimited' Truly Stretch?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-11-a-new-era-for-backup-and-restore/"><u>Unveiling Windows 11: A New Era for Backup and Restore</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-terminal-customization-aesthetic-choices/"><u>Windows Terminal Customization: Aesthetic Choices</u></a></li>
</ul></div>

