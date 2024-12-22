---
title: Workarounds for Blocked by Admin Errors During Windows App Deployment
date: 2024-12-20T06:22:15.498Z
updated: 2024-12-22T05:07:36.950Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Workarounds for Blocked by Admin Errors During Windows App Deployment
excerpt: This Article Describes Workarounds for Blocked by Admin Errors During Windows App Deployment
keywords: Fixing Admin Errors,Prevent Windows Blockage,Workaround Deployment,Bypass Admin Issues,Avoiding Windows Errors,Steps for Deploy Fixes,Circumventing Blockages,Admin Error Solutions,Windows Deployment Avoidance,Quick App Deploy Fixes,Bypass Administrative Blocks,Overcome Windows Issues,Deployment Workaround Steps,Circumvent Admin Errors
thumbnail: https://thmb.techidaily.com/76a953455d282504d07d30484b3d441976cd7c068fdbe75a38577d96433ea41b.jpg
---

## Workarounds for Blocked by Admin Errors During Windows App Deployment

 Installing software is usually a smooth process on Windows 10 and 11 PCs. However, sometimes installation hiccups can arise. For instance, some users have reported this error message appears when they try to install Windows software packages, “The system administrator has set policies to prevent this installation.”

 Users cannot install whatever programs for which that system administrator error arises. The error message suggests this issue is due to some kind of enforced admin settings. You can fix the “system administrator has set policies” error by applying the resolutions below.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run the Software’s Setup File as An Administrator

 First, start with the easiest of potential solutions. They don’t get much simpler than running the affected software’s installation file with administrative rights. Right-click the setup file for the software you can’t install and select **Run as administrator** on its context menu.

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-run-as-administrator-option.jpg)

## 2\. Enable the Built-in Windows Admin Account

 It has been confirmed by some users that activating and logging into the built-in (hidden) Windows admin account can fix the “system administrator has set policies” error. It’s recommended to try that even if your current user account is an administrative one. You can do that by following the instructions for the Command Prompt method in our guide to [enabling the built-in Windows administrator account](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/).

![The net user administrator /active:yes command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/net-user-admin-account-command.jpg)

 When you’ve activated the account, restart your Windows PC. Then sign in to the newly activated admin account and try installing the software you need from there. Disable the built-in administrator account when you’re done with it.

## 3\. Turn Off UAC (User Account Control)

 User Account Control is a security screen that can hinder the installation of programs when set at its highest setting. To ensure UAC isn’t causing any issues with installing software, temporarily turn off User Account Control by selecting its lowest **Never notify** option. You can apply this potential fix by disabling User Account Control with one of the methods in our [guide to turning off UAC](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/).

![The User Account Control Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-uac-settings.jpg)

## 4\. Run or Restart the Windows Installer Service

 Windows Installer is a service that needs to be running for users to install software with MSI packages. So, check that service is enabled and running. Even if it is, restarting that service might also resolve the “system administrator has set policies” error. This is how you can run or restart Windows Installer:

1. To access the file finder tool, right-click **Start** and select the **Search** shortcut.
2. Next, input a **services** search phrase.
3. Click the **Services** app found by the search tool.
4. Double-click **Windows Installer** to see that service’s property settings.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-services-window.jpg)
5. If the service is stopped, click its **Start** button. Or select **Stop** and **Start** to restart Windows Installer.  
![The Windows Installer Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-windows-installer-properties-service-window.jpg)
6. Select **Apply** \> **OK** to save the Windows Installer service settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GyfJUhsz_AY?si=x2HjoLX1B89oEPgZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Change Group Policy Settings

 Lots of users have fixed the “system administrator has set policies” error by setting the Windows Installer policy to never disable Windows Installer. However, you will need to access Local Group Policy Editor, available in the Windows Pro and Enterprise editions, to apply this potential fix. If you can utilize that tool, change the **Turn Off Windows Installer** policy like this:

1. Press **Win + R**, input the **gpedit.msc** command, and click **OK** to [openLocal Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
2. Double-click on **Computer Configuration** and **Administrative Templates** inside Group Policy’s left sidebar.
3. Then go to **Windows Components** \> **Windows Installer** to access policy settings.
4. Double-click the **Turn off Windows Installer** policy setting.  
![The Turn off Windows Installer policy setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-installer-policy-settings.jpg)
5. Select **Enabled** if that option isn’t already set.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wVVp-GggK3U?si=RJb1ClNQV7GjTu_3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Then click **Never** on the **Disable Windows Installer** drop-down menu.  
![The Never option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-never-option.jpg)
7. Select the policy window’s **Apply** and **OK** options.

 On top of that, delete software restriction policies. These are the steps for deleting software restriction policies:

1. Double-click **Windows Settings** \> **Security Settings** in Group Policy’s sidebar.
2. Right-click **Software Restriction Policies** and select **Delete Software Restriction Policies** if that option is available.  
![delete-software-restriction-policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/delete-software-restriction-policies.jpg)
3. Click **Yes** to confirm the deletion of software restriction policies.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SgRVYjqB70s?si=My_2cDvJVdincQRu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Some users also say they went even further and created a new software restriction policy in Group Policy Editor to resolve the “system administrator has set policies” error. You can try doing that after selecting to delete software restriction policies. Create a new software restriction policy like this:

1. Click **Software Restriction Policies** with the right mouse button to select **New Software Restriction Policies**.  
![The New Software Restriction Policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-software-restriction-policies.jpg)
2. Double-click on **Enforcement**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/58KlTPHv8dU?si=7ICagyNgrao7OkVO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![The Software Restriction Policies object types](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enforcement-option.jpg)
3. Select the **All users except local administrators** radio button.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![The Enforcement Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enforcement-properties-window.jpg)
4. Click the Enforcement Properties window’s **Apply** and **OK** options.
5. [Run Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/#:~:text=Press%20the%20Win%20%2B%20R%20on,Command%20Prompt%20with%20administrative%20privileges.) via the search utility.
6. Enter and execute this command for updating the policy:  
`gpupdate /force`
7. Exit the Command Prompt app and restart Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Edit the Installer Registry Key

 Editing an **Installer** registry key is a widely confirmed fix for the “system administrator has set policies” error. This registry tweak involves setting a **DisableMSI** DWORD value. You may also need to create a new **Installer** key from scratch if it’s not already there. These are the steps for applying this registry solution:

1. Click on the taskbar magnifying glass or Search box.
2. Type in a **regedit** search term to locate the Registry Editor app.
3. Select **Registry Editor** to start that app.
4. Input this path inside the Registry Editor address bar:  
`HKEY_LOCAL_MACHINE\Software\Policies\Microsoft\Windows\`
5. If you can’t see an **Installer** subkey, right-click the **Windows** key and select **New** \> **Key**. Users who can select an existing **Installer** subkey within the **Windows** key can skip through to step seven.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-new-key-options.jpg)

1. Enter **Installer** for the new key’s name.
2. Right-click the **Installer** key and select **New** \> **DWORD (32-bit) Value**.
3. Enter **DisableMSI** to be the title of the new DWORD.  
![the-disable-msi-dword](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-disable-msi-dword.jpg)
4. Double-click **DisableMSI** inside the **Installer** key.
5. Make sure the **DisableMSI** value is set to **0**.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-edit-dword-window.jpg)
6. Select **OK** to set the **DisableMSI** value.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fJlICvacgJY?si=jNeijBVj7ia4ammA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Close Registry Editor and restart your PC.

## Get Your Windows Software Installed

 The “system administrator has set policies” error is an old Windows issue many users have fixed with the troubleshooting methods covered in this guide. So, those are tried and tested resolutions that will likely fix the “system administrator has set policies” error on your PC. Then you can get all the Windows 10 and 11 software you need installed.

 Users cannot install whatever programs for which that system administrator error arises. The error message suggests this issue is due to some kind of enforced admin settings. You can fix the “system administrator has set policies” error by applying the resolutions below.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-helps.techidaily.com/new-transform-your-photos-removing-backdrops-with-ease/"><u>[New] Transform Your Photos Removing Backdrops with Ease</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-learn-money-tricks-top-13-beginner-friendly-income-strategies-on-reddit/"><u>[Updated] Learn Money Tricks Top 13 Beginner-Friendly Income Strategies on Reddit</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-natural-beauty-video-suggestions-for-2024/"><u>[Updated] Natural Beauty Video Suggestions for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ing-engagement-with-effective-youtube-banners-and-thumbnails-for-2024/"><u>Boosting Engagement with Effective YouTube Banners & Thumbnails for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/fixing-blurry-youtube-videos-a-step-by-step-guide/"><u>Fixing Blurry YouTube Videos A Step-by-Step Guide</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ispoofer-is-not-working-on-poco-m6-pro-5g-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, iSpoofer is not working On Poco M6 Pro 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keyboard-command-proficiency-a-guide-to-windows-narrator/"><u>Keyboard Command Proficiency: A Guide to Windows Narrator</u></a></li>
<li><a href="https://article-posts.techidaily.com/meta-versus-omni-the-future-of-digital-worlds-for-2024/"><u>Meta versus Omni The Future of Digital Worlds for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/perfecting-zoom-screen-sharpness-users-handbook/"><u>Perfecting Zoom Screen Sharpness User's Handbook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-the-package-registration-hurdle-for-windows-users/"><u>Solving the Package Registration Hurdle for Windows Users</u></a></li>
<li><a href="https://buynow-help.techidaily.com/the-mini-marvel-unpacking-the-full-capabilities-of-amazons-3rd-gen-echo-dot/"><u>The Mini Marvel - Unpacking the Full Capabilities of Amazon's 3Rd Gen Echo Dot.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-invalid-profiles-clearing-windows-1111-errors/"><u>Troubleshooting Invalid Profiles: Clearing Windows 11/11 Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/window-11-taskbar-height-adjustment-tips/"><u>Window 11 Taskbar Height Adjustment Tips</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    