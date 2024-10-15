---
title: Step-by-Step Guide to Restarting File Explorer UI
date: 2024-10-08T21:41:11.937Z
updated: 2024-10-15T12:53:56.209Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Step-by-Step Guide to Restarting File Explorer UI
excerpt: This Article Describes Step-by-Step Guide to Restarting File Explorer UI
keywords: File Explorer Troubleshoot,RESTART Finder Guide,File Explore UI Fix,Revive File Explorer,Restart UI FileExplorer,Windows Explorer Reboot,Refresh File Explorer UI
thumbnail: https://thmb.techidaily.com/9eb4aae367e8d7c80e3c075f7bffa3926b7f3e2ef755ab623092abbe72eca2c0.jpg
---

## Step-by-Step Guide to Restarting File Explorer UI

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

### Quick Links

* [What Is File Explorer in Windows?](#what-is-file-explorer-in-windows)
* [Restart File Explorer Using Task Manager](#restart-file-explorer-using-task-manager)
* [Exit Explorer and Manually Restart It (Windows 10 Only)](#exit-explorer-and-manually-restart-it-windows-10-only)
* [Restart Windows Explorer Manually Using Command Prompt](#restart-windows-explorer-manually-using-command-prompt)
* [Use a Batch File to Restart File Explorer in Windows](#use-a-batch-file-to-restart-file-explorer-in-windows)

 When you're facing issues with the Windows user interface—for example, your taskbar isn't responding or file navigation seems slow—restarting the File Explorer process can often fix the issue. We'll show you how to do it.

## What Is File Explorer in Windows?

 File Explorer is the built-in file manager for Windows devices. You use it to navigate through various directories and browse for files within the operating system. It starts running in the background as soon as your computer boots up.

 If you're someone who switched from a Mac, think of File Explorer as Microsoft's equivalent of Finder in macOS. You can open a new File Explorer window by simply clicking the **folder** icon in the taskbar.

 Besides file management, the process behind this tool also allows you to interact with the Start menu, desktop, and taskbar items. Thus, when you restart File Explorer, you're hitting the reboot button for most of Windows' graphical user interface—without having to shut down or restart your PC.

## 1\. Restart File Explorer Using Task Manager

 Task Manager is a built-in system monitor that lets you start or end a process on your computer. These processes can be active programs, services, and other tasks that run in the background while you use your PC. Many people use Task Manager to [monitor RAM, GPU, and CPU usage on Windows](https://www.makeuseof.com/windows-11-check-ram-gpu-cpu-usage/).

 Since File Explorer is a process that always runs in the background, using Task Manager to restart it is a natural option. Here's what you need to do:

1. Right-click anywhere that's empty on the taskbar and select **Task Manager** from the context menu to get started. Alternatively, you can press **Ctrl + Shift + Esc** on your keyboard.
2. If you don't see the following window and get the simple view instead on Windows 10, click **More details**.
3. Next, scroll through the list of active processes and find **Windows Explorer**. Clicking the **Name** header to sort in ABC order can help here.
4. Select **Windows Explorer** and click **Restart** (or **Restart task** on Windows 11).

![Restarting Windows Explorer in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/restarting-windows-explorer-in-task-manager.png)

 Your desktop will go black, and the taskbar will disappear for a split second, confirming that the Windows Explorer process has rebooted on your system. After the restart, the interface will likely feel more responsive; any slowdowns should be fixed.

## 2\. Exit Explorer and Manually Restart It (Windows 10 Only)

 Do you like to have more control when you restart File Explorer? Maybe you don't want to immediately restart it because you're testing something on your computer and need it to use as few resources as possible.

 If so, Windows 10 lets you exit File Explorer, then you can manually restart it using Task Manager. Follow these steps:

![Exit Explorer option from the Windows Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/exit-explorer-option-from-the-windows-taskbar.png)

1. Press **Ctrl + Shift** on your keyboard and right-click anywhere on the taskbar.
2. Choose **Exit Explorer** from the context menu. Your screen will go black, and the taskbar will disappear indefinitely, but don't panic.
3. Now, press **Ctrl + Shift + Esc** on your keyboard to open the Task Manager.
4. Go to **File > Run new task** from the Task Manager's menu bar.
5. You'll be prompted to enter the name of the process you want to run. Type **explorer.exe** and click **OK**.

![running a new explorer task in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/running-a-new-explorer-task-in-task-manager.png)

 The taskbar and your desktop will reappear on the screen, confirming that File Explorer is once again actively running in the background of your system.

## 3\. Restart Windows Explorer Manually Using Command Prompt

 The [Command Prompt is a tool](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) that most Windows users are familiar with. This built-in command-line interpreter lets you perform various tasks on a Windows computer using specific commands.

 We'll use two separate commands to kill the **Explorer.exe** process and start it back up in this method. This manual method to restart File Explorer can be handy for Windows 11 users, since the above doesn't work on the newer OS.

1. Type **command prompt** in the Start menu search bar and open it. To stop **File Explorer** from running, type the following command and hit **Enter**:  
`taskkill /f /im explorer.exe`
2. When you're ready to re-run it, use this command and press **Enter**:  
`start explorer.exe`  
![Using CMD to restart Windows explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/how-to-restart-explorer-windows-10-7.jpg)

 After entering the first command, your screen will go black. You'll be able to access your desktop again once you enter the second command.

## 4\. Use a Batch File to Restart File Explorer in Windows

 A batch file is simply a plain text file containing a series of commands you can execute with command-line interpreters like Command Prompt or PowerShell. These files use the **.bat** format; you can access them using File Explorer.

 All the [commands stored in a Windows batch file will execute automatically](https://www.makeuseof.com/tag/use-windows-batch-file-commands-automate-repetitive-tasks/) in sequential order once you open it. We'll use the same two commands we used in the Command Prompt method, except you'll store it as a batch file on your desktop for easy access:

1. Use the **Start** menu search bar to find and open **Notepad**. Now, copy/paste or type the following lines:  
`taskkill /f /im explorer.exe  
start explorer.exe  
exit`
2. Click **File > Save As** from Notepad's menu bar.
3. Set the **Save as type** to **All Files** and add **.bat** at the end of the file name. Select a location you can quickly access, like the **Desktop** folder, and click **Save**. This will save the Notepad document as a batch file.

![Saving code to restart explorer as a batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/how-to-restart-explorer-windows-10-10.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135399/19272" target="_top" id="2135399">
  <img src="//a.impactradius-go.com/display-ad/19272-2135399" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135399/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 All you need to do now is double-click the file to run the commands automatically. When File Explorer restarts, your screen will go black for a moment. If you store the batch file on your desktop or [pin the file to your Windows taskbar](https://www.makeuseof.com/windows-11-taskbar-pin-almost-anything/), where it's easily accessible, this becomes the fastest way to restart **Explorer.exe** on your Windows PC.

 Now that you've learned not one, but four, different ways to restart File Explorer, it's time to figure out what works best for you. We have a clear winner if you're looking for the fastest method. But if you don't want to set up a batch file for the job, using Task Manager is generally your best bet.

 When you're facing issues with the Windows user interface—for example, your taskbar isn't responding or file navigation seems slow—restarting the File Explorer process can often fix the issue. We'll show you how to do it.

## What Is File Explorer in Windows?

 File Explorer is the built-in file manager for Windows devices. You use it to navigate through various directories and browse for files within the operating system. It starts running in the background as soon as your computer boots up.

 If you're someone who switched from a Mac, think of File Explorer as Microsoft's equivalent of Finder in macOS. You can open a new File Explorer window by simply clicking the **folder** icon in the taskbar.

 Besides file management, the process behind this tool also allows you to interact with the Start menu, desktop, and taskbar items. Thus, when you restart File Explorer, you're hitting the reboot button for most of Windows' graphical user interface—without having to shut down or restart your PC.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657396/16446" target="_top" id="1657396">
  <img src="//a.impactradius-go.com/display-ad/16446-1657396" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657396/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Restart File Explorer Using Task Manager

 Task Manager is a built-in system monitor that lets you start or end a process on your computer. These processes can be active programs, services, and other tasks that run in the background while you use your PC. Many people use Task Manager to [monitor RAM, GPU, and CPU usage on Windows](https://www.makeuseof.com/windows-11-check-ram-gpu-cpu-usage/).

 Since File Explorer is a process that always runs in the background, using Task Manager to restart it is a natural option. Here's what you need to do:

1. Right-click anywhere that's empty on the taskbar and select **Task Manager** from the context menu to get started. Alternatively, you can press **Ctrl + Shift + Esc** on your keyboard.
2. If you don't see the following window and get the simple view instead on Windows 10, click **More details**.
3. Next, scroll through the list of active processes and find **Windows Explorer**. Clicking the **Name** header to sort in ABC order can help here.
4. Select **Windows Explorer** and click **Restart** (or **Restart task** on Windows 11).

![Restarting Windows Explorer in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/restarting-windows-explorer-in-task-manager.png)

 Your desktop will go black, and the taskbar will disappear for a split second, confirming that the Windows Explorer process has rebooted on your system. After the restart, the interface will likely feel more responsive; any slowdowns should be fixed.

## 2\. Exit Explorer and Manually Restart It (Windows 10 Only)

 Do you like to have more control when you restart File Explorer? Maybe you don't want to immediately restart it because you're testing something on your computer and need it to use as few resources as possible.

 If so, Windows 10 lets you exit File Explorer, then you can manually restart it using Task Manager. Follow these steps:

![Exit Explorer option from the Windows Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/exit-explorer-option-from-the-windows-taskbar.png)

1. Press **Ctrl + Shift** on your keyboard and right-click anywhere on the taskbar.
2. Choose **Exit Explorer** from the context menu. Your screen will go black, and the taskbar will disappear indefinitely, but don't panic.
3. Now, press **Ctrl + Shift + Esc** on your keyboard to open the Task Manager.
4. Go to **File > Run new task** from the Task Manager's menu bar.
5. You'll be prompted to enter the name of the process you want to run. Type **explorer.exe** and click **OK**.

![running a new explorer task in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/running-a-new-explorer-task-in-task-manager.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094421/7443" target="_top" id="2094421">
  <img src="//a.impactradius-go.com/display-ad/7443-2094421" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094421/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The taskbar and your desktop will reappear on the screen, confirming that File Explorer is once again actively running in the background of your system.

## 3\. Restart Windows Explorer Manually Using Command Prompt

 The [Command Prompt is a tool](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) that most Windows users are familiar with. This built-in command-line interpreter lets you perform various tasks on a Windows computer using specific commands.

 We'll use two separate commands to kill the **Explorer.exe** process and start it back up in this method. This manual method to restart File Explorer can be handy for Windows 11 users, since the above doesn't work on the newer OS.

1. Type **command prompt** in the Start menu search bar and open it. To stop **File Explorer** from running, type the following command and hit **Enter**:  
`taskkill /f /im explorer.exe`
2. When you're ready to re-run it, use this command and press **Enter**:  
`start explorer.exe`  
![Using CMD to restart Windows explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/how-to-restart-explorer-windows-10-7.jpg)

 After entering the first command, your screen will go black. You'll be able to access your desktop again once you enter the second command.

## 4\. Use a Batch File to Restart File Explorer in Windows

 A batch file is simply a plain text file containing a series of commands you can execute with command-line interpreters like Command Prompt or PowerShell. These files use the **.bat** format; you can access them using File Explorer.

 All the [commands stored in a Windows batch file will execute automatically](https://www.makeuseof.com/tag/use-windows-batch-file-commands-automate-repetitive-tasks/) in sequential order once you open it. We'll use the same two commands we used in the Command Prompt method, except you'll store it as a batch file on your desktop for easy access:

1. Use the **Start** menu search bar to find and open **Notepad**. Now, copy/paste or type the following lines:  
`taskkill /f /im explorer.exe  
start explorer.exe  
exit`
2. Click **File > Save As** from Notepad's menu bar.
3. Set the **Save as type** to **All Files** and add **.bat** at the end of the file name. Select a location you can quickly access, like the **Desktop** folder, and click **Save**. This will save the Notepad document as a batch file.

![Saving code to restart explorer as a batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/how-to-restart-explorer-windows-10-10.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/977686/11832" target="_top" id="977686">
  <img src="//a.impactradius-go.com/display-ad/11832-977686" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/977686/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 All you need to do now is double-click the file to run the commands automatically. When File Explorer restarts, your screen will go black for a moment. If you store the batch file on your desktop or [pin the file to your Windows taskbar](https://www.makeuseof.com/windows-11-taskbar-pin-almost-anything/), where it's easily accessible, this becomes the fastest way to restart **Explorer.exe** on your Windows PC.

 Now that you've learned not one, but four, different ways to restart File Explorer, it's time to figure out what works best for you. We have a clear winner if you're looking for the fastest method. But if you don't want to set up a batch file for the job, using Task Manager is generally your best bet.

 When you're facing issues with the Windows user interface—for example, your taskbar isn't responding or file navigation seems slow—restarting the File Explorer process can often fix the issue. We'll show you how to do it.

## What Is File Explorer in Windows?

 File Explorer is the built-in file manager for Windows devices. You use it to navigate through various directories and browse for files within the operating system. It starts running in the background as soon as your computer boots up.

 If you're someone who switched from a Mac, think of File Explorer as Microsoft's equivalent of Finder in macOS. You can open a new File Explorer window by simply clicking the **folder** icon in the taskbar.

 Besides file management, the process behind this tool also allows you to interact with the Start menu, desktop, and taskbar items. Thus, when you restart File Explorer, you're hitting the reboot button for most of Windows' graphical user interface—without having to shut down or restart your PC.

## 1\. Restart File Explorer Using Task Manager

 Task Manager is a built-in system monitor that lets you start or end a process on your computer. These processes can be active programs, services, and other tasks that run in the background while you use your PC. Many people use Task Manager to [monitor RAM, GPU, and CPU usage on Windows](https://www.makeuseof.com/windows-11-check-ram-gpu-cpu-usage/).

 Since File Explorer is a process that always runs in the background, using Task Manager to restart it is a natural option. Here's what you need to do:

1. Right-click anywhere that's empty on the taskbar and select **Task Manager** from the context menu to get started. Alternatively, you can press **Ctrl + Shift + Esc** on your keyboard.
2. If you don't see the following window and get the simple view instead on Windows 10, click **More details**.
3. Next, scroll through the list of active processes and find **Windows Explorer**. Clicking the **Name** header to sort in ABC order can help here.
4. Select **Windows Explorer** and click **Restart** (or **Restart task** on Windows 11).

![Restarting Windows Explorer in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/restarting-windows-explorer-in-task-manager.png)

 Your desktop will go black, and the taskbar will disappear for a split second, confirming that the Windows Explorer process has rebooted on your system. After the restart, the interface will likely feel more responsive; any slowdowns should be fixed.

## 2\. Exit Explorer and Manually Restart It (Windows 10 Only)

 Do you like to have more control when you restart File Explorer? Maybe you don't want to immediately restart it because you're testing something on your computer and need it to use as few resources as possible.

 If so, Windows 10 lets you exit File Explorer, then you can manually restart it using Task Manager. Follow these steps:

![Exit Explorer option from the Windows Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/exit-explorer-option-from-the-windows-taskbar.png)

1. Press **Ctrl + Shift** on your keyboard and right-click anywhere on the taskbar.
2. Choose **Exit Explorer** from the context menu. Your screen will go black, and the taskbar will disappear indefinitely, but don't panic.
3. Now, press **Ctrl + Shift + Esc** on your keyboard to open the Task Manager.
4. Go to **File > Run new task** from the Task Manager's menu bar.
5. You'll be prompted to enter the name of the process you want to run. Type **explorer.exe** and click **OK**.

![running a new explorer task in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/running-a-new-explorer-task-in-task-manager.png)

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005184/22899" target="_top" id="2005184">
  <img src="//a.impactradius-go.com/display-ad/22899-2005184" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005184/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The taskbar and your desktop will reappear on the screen, confirming that File Explorer is once again actively running in the background of your system.

## 3\. Restart Windows Explorer Manually Using Command Prompt

 The [Command Prompt is a tool](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) that most Windows users are familiar with. This built-in command-line interpreter lets you perform various tasks on a Windows computer using specific commands.

 We'll use two separate commands to kill the **Explorer.exe** process and start it back up in this method. This manual method to restart File Explorer can be handy for Windows 11 users, since the above doesn't work on the newer OS.

1. Type **command prompt** in the Start menu search bar and open it. To stop **File Explorer** from running, type the following command and hit **Enter**:  
`taskkill /f /im explorer.exe`
2. When you're ready to re-run it, use this command and press **Enter**:  
`start explorer.exe`  
![Using CMD to restart Windows explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/how-to-restart-explorer-windows-10-7.jpg)

 After entering the first command, your screen will go black. You'll be able to access your desktop again once you enter the second command.

## 4\. Use a Batch File to Restart File Explorer in Windows

 A batch file is simply a plain text file containing a series of commands you can execute with command-line interpreters like Command Prompt or PowerShell. These files use the **.bat** format; you can access them using File Explorer.

 All the [commands stored in a Windows batch file will execute automatically](https://www.makeuseof.com/tag/use-windows-batch-file-commands-automate-repetitive-tasks/) in sequential order once you open it. We'll use the same two commands we used in the Command Prompt method, except you'll store it as a batch file on your desktop for easy access:

1. Use the **Start** menu search bar to find and open **Notepad**. Now, copy/paste or type the following lines:  
`taskkill /f /im explorer.exe  
start explorer.exe  
exit`
2. Click **File > Save As** from Notepad's menu bar.
3. Set the **Save as type** to **All Files** and add **.bat** at the end of the file name. Select a location you can quickly access, like the **Desktop** folder, and click **Save**. This will save the Notepad document as a batch file.

![Saving code to restart explorer as a batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/how-to-restart-explorer-windows-10-10.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100538/7443" target="_top" id="2100538">
  <img src="//a.impactradius-go.com/display-ad/7443-2100538" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 All you need to do now is double-click the file to run the commands automatically. When File Explorer restarts, your screen will go black for a moment. If you store the batch file on your desktop or [pin the file to your Windows taskbar](https://www.makeuseof.com/windows-11-taskbar-pin-almost-anything/), where it's easily accessible, this becomes the fastest way to restart **Explorer.exe** on your Windows PC.

 Now that you've learned not one, but four, different ways to restart File Explorer, it's time to figure out what works best for you. We have a clear winner if you're looking for the fastest method. But if you don't want to set up a batch file for the job, using Task Manager is generally your best bet.

 When you're facing issues with the Windows user interface—for example, your taskbar isn't responding or file navigation seems slow—restarting the File Explorer process can often fix the issue. We'll show you how to do it.

## What Is File Explorer in Windows?

 File Explorer is the built-in file manager for Windows devices. You use it to navigate through various directories and browse for files within the operating system. It starts running in the background as soon as your computer boots up.

 If you're someone who switched from a Mac, think of File Explorer as Microsoft's equivalent of Finder in macOS. You can open a new File Explorer window by simply clicking the **folder** icon in the taskbar.

 Besides file management, the process behind this tool also allows you to interact with the Start menu, desktop, and taskbar items. Thus, when you restart File Explorer, you're hitting the reboot button for most of Windows' graphical user interface—without having to shut down or restart your PC.

## 1\. Restart File Explorer Using Task Manager

 Task Manager is a built-in system monitor that lets you start or end a process on your computer. These processes can be active programs, services, and other tasks that run in the background while you use your PC. Many people use Task Manager to [monitor RAM, GPU, and CPU usage on Windows](https://www.makeuseof.com/windows-11-check-ram-gpu-cpu-usage/).

 Since File Explorer is a process that always runs in the background, using Task Manager to restart it is a natural option. Here's what you need to do:

1. Right-click anywhere that's empty on the taskbar and select **Task Manager** from the context menu to get started. Alternatively, you can press **Ctrl + Shift + Esc** on your keyboard.
2. If you don't see the following window and get the simple view instead on Windows 10, click **More details**.
3. Next, scroll through the list of active processes and find **Windows Explorer**. Clicking the **Name** header to sort in ABC order can help here.
4. Select **Windows Explorer** and click **Restart** (or **Restart task** on Windows 11).

![Restarting Windows Explorer in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/restarting-windows-explorer-in-task-manager.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135352/19272" target="_top" id="2135352">
  <img src="//a.impactradius-go.com/display-ad/19272-2135352" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135352/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Your desktop will go black, and the taskbar will disappear for a split second, confirming that the Windows Explorer process has rebooted on your system. After the restart, the interface will likely feel more responsive; any slowdowns should be fixed.

<!-- affiliate ads begin -->
<span id="1938141">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938141.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938141">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938141.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938141%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938141/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Exit Explorer and Manually Restart It (Windows 10 Only)

 Do you like to have more control when you restart File Explorer? Maybe you don't want to immediately restart it because you're testing something on your computer and need it to use as few resources as possible.

 If so, Windows 10 lets you exit File Explorer, then you can manually restart it using Task Manager. Follow these steps:

![Exit Explorer option from the Windows Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/exit-explorer-option-from-the-windows-taskbar.png)

1. Press **Ctrl + Shift** on your keyboard and right-click anywhere on the taskbar.
2. Choose **Exit Explorer** from the context menu. Your screen will go black, and the taskbar will disappear indefinitely, but don't panic.
3. Now, press **Ctrl + Shift + Esc** on your keyboard to open the Task Manager.
4. Go to **File > Run new task** from the Task Manager's menu bar.
5. You'll be prompted to enter the name of the process you want to run. Type **explorer.exe** and click **OK**.

![running a new explorer task in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/running-a-new-explorer-task-in-task-manager.png)

 The taskbar and your desktop will reappear on the screen, confirming that File Explorer is once again actively running in the background of your system.

## 3\. Restart Windows Explorer Manually Using Command Prompt

 The [Command Prompt is a tool](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) that most Windows users are familiar with. This built-in command-line interpreter lets you perform various tasks on a Windows computer using specific commands.

 We'll use two separate commands to kill the **Explorer.exe** process and start it back up in this method. This manual method to restart File Explorer can be handy for Windows 11 users, since the above doesn't work on the newer OS.

1. Type **command prompt** in the Start menu search bar and open it. To stop **File Explorer** from running, type the following command and hit **Enter**:  
`taskkill /f /im explorer.exe`
2. When you're ready to re-run it, use this command and press **Enter**:  
`start explorer.exe`  
![Using CMD to restart Windows explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/how-to-restart-explorer-windows-10-7.jpg)

 After entering the first command, your screen will go black. You'll be able to access your desktop again once you enter the second command.

## 4\. Use a Batch File to Restart File Explorer in Windows

 A batch file is simply a plain text file containing a series of commands you can execute with command-line interpreters like Command Prompt or PowerShell. These files use the **.bat** format; you can access them using File Explorer.

 All the [commands stored in a Windows batch file will execute automatically](https://www.makeuseof.com/tag/use-windows-batch-file-commands-automate-repetitive-tasks/) in sequential order once you open it. We'll use the same two commands we used in the Command Prompt method, except you'll store it as a batch file on your desktop for easy access:

1. Use the **Start** menu search bar to find and open **Notepad**. Now, copy/paste or type the following lines:  
`taskkill /f /im explorer.exe  
start explorer.exe  
exit`
2. Click **File > Save As** from Notepad's menu bar.
3. Set the **Save as type** to **All Files** and add **.bat** at the end of the file name. Select a location you can quickly access, like the **Desktop** folder, and click **Save**. This will save the Notepad document as a batch file.

![Saving code to restart explorer as a batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/how-to-restart-explorer-windows-10-10.jpg)

 All you need to do now is double-click the file to run the commands automatically. When File Explorer restarts, your screen will go black for a moment. If you store the batch file on your desktop or [pin the file to your Windows taskbar](https://www.makeuseof.com/windows-11-taskbar-pin-almost-anything/), where it's easily accessible, this becomes the fastest way to restart **Explorer.exe** on your Windows PC.

 Now that you've learned not one, but four, different ways to restart File Explorer, it's time to figure out what works best for you. We have a clear winner if you're looking for the fastest method. But if you don't want to set up a batch file for the job, using Task Manager is generally your best bet.

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
<li><a href="https://desktop-recording.techidaily.com/updated-precision-leaders-best-7-shooting-adventures/"><u>[Updated] Precision Leaders Best 7 Shooting Adventures</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-tips-for-dimming-windows-and-mac-music-volume/"><u>[Updated] Tips for Dimming Windows & Mac Music Volume</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-the-ultimate-list-of-sandbox-treasures/"><u>2024 Approved The Ultimate List of Sandbox Treasures</u></a></li>
<li><a href="https://blog-min.techidaily.com/8-ways-to-transfer-photos-from-vivo-y100i-to-iphone-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>8 Ways to Transfer Photos from Vivo Y100i to iPhone Easily | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-script-mishaps-a-comprehensive-fix-list-for-windows/"><u>Conquer Script Mishaps: A Comprehensive Fix List for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-edge-techniques-generating-sfx-archives-on-win11/"><u>Cutting Edge Techniques: Generating SFX Archives on Win11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-vivo-y78plus-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Vivo Y78+ to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-maze-of-microsoft-outlook-problems-in-windows/"><u>Navigating the Maze of Microsoft Outlook Problems in Windows</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/protecting-originality-openais-gpt-output-detector/"><u>Protecting Originality: OpenAI's GPT Output Detector</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/staying-longer-and-performing-better-with-the-lg-gram-156-laptop-a-comprehensive-review/"><u>Staying Longer and Performing Better with the LG Gram 15.6 Laptop: A Comprehensive Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-optimize-ram-allocation-in-windows-operating-system/"><u>Tips to Optimize RAM Allocation in Windows Operating System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turning-down-on-typos-reverse-silence-on-your-spacebar/"><u>Turning Down on Typos: Reverse Silence on Your Spacebar</u></a></li>
</ul></div>

