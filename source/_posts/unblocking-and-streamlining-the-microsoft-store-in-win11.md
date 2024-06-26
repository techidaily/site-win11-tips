---
title: Unblocking and Streamlining the Microsoft Store in Win11
date: 2024-06-22 21:26:42
updated: 2024-06-25 11:48:26
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unblocking and Streamlining the Microsoft Store in Win11
excerpt: This Article Describes Unblocking and Streamlining the Microsoft Store in Win11
keywords: MSStoreUpgradeWin11,UnblockMicrosoftStore,StreamlineMSStore,Win11StoreOptimization,MSStoreRemovalGuide,StreamlineWin11Setup,WindowsStoreUnlocking
thumbnail: https://thmb.techidaily.com/92459487433dd8191ecb6f79f9b025b7d93038fc1418a5a54e50bbd98af412de.jpg
---

## Unblocking and Streamlining the Microsoft Store in Win11

 Are you trying to install a new app but running into the “Microsoft Store is blocked” error when launching it? If you’ve already tried the usual fixes such as restarting your computer and closing the app without any luck, give the below fixes a quick try.

## 1\. Run the Windows Store Apps Troubleshooter

 As the name implies, you should run this troubleshooter any time you have a problem with one of the Microsoft Store apps. Including the store itself. So, it might be a useful tool while trying to unblock the Microsoft Store app.

1. Right-click the**Start** button and select**Settings** .
2. Click**System > Troubleshoot** and select**Other troubleshooters** .
3. Find**Windows Store Apps** from the list and click the**Run** button next to it.

![Run the Microsoft Store troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/store-troubleshooter-1-1.jpg)

 Windows will now search for any possible issues with the store apps. Once it finishes the process, it will provide troubleshooting instructions, so make sure to follow them.

## 2\. Switch to a Different Account

 There’s a chance that Microsoft Store restrictions are impacting only the account you’re currently using. If you’re looking for a workaround, you could[switch user accounts](https://www.makeuseof.com/windows-11-switch-user-accounts/) .

 But if this didn’t fix the problem, move on to the next solution.

## 3\. Reset Microsoft Store

 You might be dealing with restricted actions in Microsoft Store due to outdated or corrupted cache files. Fortunately, there are multiple[ways to reset Microsoft Store](https://www.makeuseof.com/windows-10-11-reset-microsoft-store/) and fix the issue.

## 4\. Edit the Group Policy

 You may get the “Microsoft Store is blocked” error if it has been disabled through Group Policy. However, you can enable it by going through the below steps:

1. Press**Windows key + R** to bring up a Run dialog.
2. Type**gpedit.msc** and click**OK** .
3. In the Policy Editor window, head to **Computer Configuration > Administrative Templates > Windows Components > Store** .
4. In the right pane, open**Turn off the Store application** .
5. Select**Not configured** **\> OK** .
6. Restart your computer.

![Disabling or Enabling the Microsoft Store using the LGPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Disabling-or-Enabling-the-Microsoft-Store-using-the-LGPE.jpg)

## 5\. Check Registry Editor

 If you’re using Windows Home, there’s a chance the Group Policy is missing on your computer. However, you can edit the Registry to unblock the Microsoft Store.

 Launch Registry Editor with administrative rights and head to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > WindowsStore** . Then, in the right pane, delete the**RemoveWindowsStore** value.

 Restart your computer and check if the Microsoft Store is now unblocked.

![Clicking the “RemoveWindowsStore” value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Clicking-the-“RemoveWindowsStore”-value-in-the-Registry-Editor.jpg)

## Unblock the Microsoft Store on Windows

 Hopefully, you’ve unblocked the Microsoft Store and can now install new apps on your computer. While it’s usually overlooked, there are a lot of useful apps that you can get for free through the store.


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
