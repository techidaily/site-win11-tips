---
title: "Become a CMD Guru: Understand These 20 Crucial Commands"
date: 2024-08-16T01:48:30.465Z
updated: 2024-08-17T01:48:30.465Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Become a CMD Guru: Understand These 20 Crucial Commands"
excerpt: "This Article Describes Become a CMD Guru: Understand These 20 Crucial Commands"
keywords: Command Mastery,CMD Essentials,Linux Commands,Shell Expertise,Bash Proficiency,Unix Skills,Terminal Wizardry
thumbnail: https://thmb.techidaily.com/e95b10a90432b136a95f53788d2f6a34587f22e1538a737ba31a5504b6070516.jpg
---

## Become a CMD Guru: Understand These 20 Crucial Commands

 The command prompt is slowly disappearing from the Windows interface and for good reasons: CMD commands are an antiquated and mostly unnecessary tool from an era of text-based input. But many commands remain useful, and Windows 8 and 10 even added new features.

 Here we present the essential commands every Windows user must know.

## How to Access the Windows Command Prompt

 To open the command prompt in Windows 10 and Windows 11, follow these steps:

1. Press **Windows + R** to open the Run command window.
2. Type "cmd" into the box.
3. Hit **Enter** or click **OK**.

 That's it. For additional ways to access the command prompt, how to run it with administrator privileges, and other tips and tricks, refer to our [beginners guide to the Windows command line](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/).

 Curious about the Run command box? We have also compiled a list of [essential Windows Run commands](https://www.makeuseof.com/tag/windows-run-commands-cheat-sheet/) for your convenience.

## Windows Command Prompt Commands

 If you haven't poked around inside Windows' command line, you're missing out. There are lots of handy tools you can use if you know the correct things to type.

### 1\. Assoc
![Screenshot of Windows command prompt with assoccommand.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/assoccmd.png)

 Most files on Windows are associated with a specific program that is assigned to open the file by default. At times, remembering these associations can become confusing. You can remind yourself by entering the command **assoc** to display a full list of filename extensions and program associations.

 You can also extend the command to change file associations. For example, **assoc .txt=** will change the file association for text files to whatever program you enter after the equal sign. The a**ssoc** command itself will reveal both the extension names and program names, which will help you properly use this command.

 In Windows 10, you can view a more user-friendly interface that also lets you change file type associations on the spot. Head to **Settings (Windows + I) > Apps > Default apps > Choose default app by file type**.

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
### 2\. Cipher
![Cipher command in the Windows command prompt.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/ciphercmd.png)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->

 Deleting files on a mechanical hard drive doesn't really delete them at all. Instead, it marks the files as no longer accessible and the space they took up as free. The files remain recoverable until the system overwrites them with new data, which can take some time.

 The cipher command, however, lets you wipe a directory on an NTFS-formatted volume by writing random data to it. To wipe your C drive, for example, you'd use the **cipher /w:d** command, which will wipe free space on the drive. The command does not overwrite undeleted data, so you will not wipe out the files you need by running this command.

 When you run the cipher command by itself, it returns the encryption state of the current directory and the files it contains. Use **cipher /e:<filename>** to encrypt a file, **cipher /c:<filename>** to retrieve information about encrypted files, and **cipher /d:<filename>** to decrypt the selected file. Most of these commands are redundant with the [Windows encryption tool BitLocker](https://www.makeuseof.com/tag/bitlocker-drive-encryption-windows-10/).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 3\. File Compare
![File compare command as seen in Windows command prompt.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/filecomparecmd.png)

 You can use this command to identify differences in text between two files. It's particularly useful for writers and programmers trying to find small changes between two versions of a file. Simply type **fc** and then the directory path and file name of the two files you want to compare.

 You can also extend the command in several ways. Typing **/b** compares only binary output, **/c** disregards the case of text in the comparison, and **/l** only compares ASCII text.

 So, for example, you could use the following:

`fc /l "C:\Program Files (x86)\example1.doc" "C:\Program Files (x86)\example2.doc"`

 The above command compares ASCII text in two Word documents.

### 4\. Ipconfig
![Ipconfig command in Windows command prompt window.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/ipconfigcmd.png)

 This command relays the IP address that your computer is currently using. However, if you're behind a router (like most computers today), you'll instead receive the local network address of the router.

 Still, ipconfig is useful because of its extensions. **ipconfig /release** followed by **ipconfig /renew** can force your Windows PC into asking for a new IP address, which is useful if your computer claims one isn't available. You can also use **ipconfig /flushdns** to refresh your DNS address. These commands are great if the [Windows network troubleshooter](https://www.makeuseof.com/tag/7-simple-steps-diagnose-network-problem/) chokes, which does happen on occasion.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
### 5\. Netstat
![Netstat command run on Windows.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/netstatcmd.png)

 Entering the command **netstat -an** will provide you with a list of currently open ports and related IP addresses. This command will also tell you what state the port is in; listening, established, or closed.

 This is a great command for when you're trying to troubleshoot devices connected to your PC or when you fear a Trojan infected your system and you're trying to locate a malicious connection.

### 6\. Ping
![Ping command prompt window.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/pingcmd.png)

 Sometimes, you need to know whether packets are making it to a specific networked device. That's where ping comes in handy.

 Typing **ping** followed by an IP address or web domain will send a series of test packets to the specified address. If they arrive and are returned, you know the device is capable of communicating with your PC; if it fails, you know that there's something blocking communication between the device and your computer. This can help you decide if the root of the issue is an improper configuration or a failure of network hardware.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
### 7\. PathPing
![Windows command prompt with PathPing command.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/pathpingcmd.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->

 This is a more advanced version of ping that's useful if there are multiple routers between your PC and the device you're testing. Like ping, you use this command by typing **pathping** followed by the IP address, but unlike ping, pathping also relays some information about the route the test packets take.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
### 8\. Tracert
![Screenshot of Tracert command in Windows command prompt.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/tracertcmd.png)

 The **tracert** command is similar to pathping. Once again, type **tracert** followed by the IP address or domain you'd like to trace. You'll receive information about each step in the route between your PC and the target. Unlike pathping, however, tracert also tracks how much time (in milliseconds) each hop between servers or devices takes.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
### 9\. Powercfg
![Powercfg command on Windows 10.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/powercfgacmd.png)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Powercfg is a very powerful command for managing and tracking how your computer uses energy. You can use the command **powercfg hibernate on** and **powercfg hibernate off** to manage hibernation, and you can also use the command **powercfg /a** to view the power-saving states currently available on your PC.

 Another useful command is **powercfg /devicequery s1\_supported**, which displays a list of devices on your computer that support connected standby. When enabled, you can use these devices to bring your computer out of standby, even remotely.

 You can enable this by selecting the device in **Device Manager**, opening its properties, going to the **Power Management** tab, and then checking the **Allow this device to wake the computer** box.

**Powercfg /lastwake** will show you what device last woke your PC from a sleep state. You can use this command to troubleshoot your PC if it seems to wake from sleep at random.

![Powercfg energy command in Administrator command prompt on Windows 10.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/powercfgenergycmd.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->

 You can use the **powercfg /energy** command to build a detailed power consumption report for your PC. The report saves to the directory indicated after the command finishes.

 This report will let you know of any system faults that might increase power consumption, like devices blocking certain sleep modes, or poorly configured to respond to your power management settings.

 Windows 8 added **powercfg /batteryreport**, which provides a detailed analysis of battery use, if applicable. Normally output to your Windows user directory, the report provides details about the time and length of charge and discharge cycles, lifetime average battery life, and estimated battery capacity.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
### 10\. Shutdown
![Shutdown command on Windows 10.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/shutdowncmd.png)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Windows 8 introduced the shutdown command that, you guessed it, [shuts down your computer](https://www.makeuseof.com/tag/how-to-shutdown-or-sleep-windows-10-with-a-keyboard-shortcut/).

 This is, of course, redundant with the already easily accessed shutdown button, but what's not redundant is the **shutdown /r /o** command, which restarts your PC and launches the Advanced Start Options menu, which is where you can access Safe Mode and Windows recovery utilities. This is useful if you want to restart your computer for troubleshooting purposes.

### 11\. System File Checker
![System File Checker sfc command options available on Windows 10.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/sfccmd.png)

 System File Checker is an [automatic scan and repair tool](https://www.makeuseof.com/tag/fix-corrupted-windows-10-installation/) that focuses on Windows system files.

 You will need to run the command prompt with administrator privileges and enter the command **sfc /scannow**. If SFC finds any corrupt or missing files, it will automatically replace them using cached copies kept by Windows for this purpose alone. The command can require a half-hour to run on older notebooks.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 12\. Tasklist
![Tasklist command as shown in Windows command prompt window.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/tasklistcmd.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->

 You can use the **tasklist** command to provide a current list of all tasks running on your PC. Though somewhat redundant with Task Manager, the command may sometimes find tasks hidden from view in that utility.

 There's also a wide range of modifiers. **Tasklist -svc** shows services related to each task, use **tasklist -v** to obtain more detail on each task, and **tasklist -m** will locate DLL files associated with active tasks. These commands are useful for advanced troubleshooting.

 Our reader Eric noted that you can "get the name of the executable associated with the particular process ID you're interested in." The command for that operation is **tasklist | find \[process id\].**

### 13\. Taskkill
![Taskkill command options available on Windows 10.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/taskkillcmd.png)
<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->

 Tasks that appear in the **tasklist** command will have an executable and process ID (a four- or five-digit number) associated with them. You can force stop a program using **taskkill -im** followed by the executable's name, or **taskkill -pid** followed by the process ID. Again, this is a bit redundant with Task Manager, but you can use it to kill otherwise unresponsive or hidden programs.

### 14\. Chkdsk
![Running a chkdsk command to initiate a scan on Windows 10.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2020/11/Windows-chckdsk-command.jpg)

 Windows automatically marks your drive for a diagnostic chkdsk scan when symptoms indicate that a local drive has bad sectors, lost clusters, or other logical or physical errors.

 If you suspect your hard drive is failing, you can manually initiate a scan. The most basic command is **chkdsk c:**, which will immediately scan the C: drive, without a need to restart the computer. If you add parameters like /f, /r, /x, or /b, such as in **chkdsk /f /r /x /b c:**, **chkdsk** will also fix errors, recover data, dismount the drive, or clear the list of bad sectors, respectively. These actions require a reboot, as they can only run with Windows powered down.

 If you see **chkdsk** run at startup, let it do its thing. If it gets stuck, however, refer to our [chkdsk troubleshooting article](https://www.makeuseof.com/tag/stuck-chkdsk-use-fix-right-way/).

### 15\. schtasks
![Scheduling tasks using the Windows schtasks command prompt command.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2020/11/Windows-schtasks-command.jpg)

**Schtasks** is your command prompt access to the Task Scheduler, one of many underrated Windows administrative tools. While you can use the GUI to manage your scheduled tasks, the command prompt lets you copy&paste complex commands to set up multiple similar tasks without having to click through various options. Ultimately, it's much easier to use, once you've committed key parameters to memory.

 For example, you could schedule your computer to reboot at 11pm every Friday:

`schtasks /create /sc weekly /d FRI /tn "auto reboot computer weekly" /st 23:00 /tr "shutdown -r -f -t 10"`

 To complement your weekly reboot, you could schedule tasks to launch specific programs on startup:

`schtasks /create /sc onstart /tn "launch Chrome on startup" /tr "C:\Program Files (x86)\Google\Chrome\Application\Chrome.exe"`

 To duplicate the above command for different programs, just copy, paste, and modify it as needed.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 16\. Format
![Windows Command Prompt showing the format command with various parameters.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/07/Windows-Command-Prompt-Format.jpg)

 When you need to [format a drive](https://www.makeuseof.com/tag/format-usb-drive/), you can either use the Windows File Explorer GUI or you can turn to the command prompt. You'll need Administrator rights to use this command. Be sure you specify the volume you want to format, followed by the desired parameters.

 The command below will quick-format the D drive with the [exFAT file system](https://www.makeuseof.com/tag/exfat-better-different-fat32/), with an allocation unit size of 2048 bytes, and rename the volume to "label" (without the quotes).

`format D: /Q /FS:exFAT /A:2048 /V:label`

 You can also use this command to dismount a volume (/X) or, if it's formatted with NTFS, make file compression the default setting (/R). If you're stuck, use format /? to summon help.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 17\. prompt
![The prompt command in action in the Windows command prompt.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/07/Windows-Command-Prompt-Prompt-Command.jpg)
<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->

 Would you like to customize your command prompt to include instructions or certain information? With the prompt command, you can!

 Try this one:

`prompt Your wish is my command:`

 You can add the current time, date, drive and path, Windows version number, and so much more.

`prompt $t on $d at $p using $v:`

 Type "prompt" to reset your command prompt to default settings or just restart the command prompt. Unfortunately, these settings aren't permanent.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 18\. cls

 Cluttered up your command prompt window trying out all the commands above? There's one last command you need to know to clean it all up again.

`cls`

 That's all. Bet Marie Kondo didn't know that one.

### 19\. Systeminfo
![Systeminfo command as seen on Windows 10.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/systeminfocmd.png)

 This command will give you a detailed configuration overview of your computer. The list covers your operating system and hardware. For example, you can look up the original Windows installation date, the last boot time, your BIOS version, total and available memory, installed hotfixes, network card configurations, and more.

 Use **systeminfo /s** followed by the hostname of a computer on your local network, to remotely grab the information for that system. This may require additional syntax elements for the domain, user name, and password, like this:

`systeminfo /s [host_name] /u [domain]\[user_name] /p [user_password]`

### 20\. Driverquery
![Windows command prompt showing driverquery command.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/driverquerycmd.png)

 Drivers remain among the most important software installed on a PC. Improperly configured, missing, or [old Windows drivers](https://www.makeuseof.com/windows-pc-move-drivers-to-new-pc/) can cause all sorts of trouble, so it's good to have access to a list of drivers on your PC.

 That's exactly what the **driverquery** command does. You can extend it to **driverquery -v** to obtain more information, including the directory in which the driver is installed. Unfortunately, this command isn't relevant post Windows 8 or Windows Server 2012\.

## Windows 8 Only: Recovery Image

 Virtually all Windows 8/8.1 computers ship from the factory with a recovery image, but the image may include bloatware you'd rather not have re-installed. Once you've uninstalled the software you can create a new image using the **recimg** command. Entering this command presents a very detailed explanation of how to use it.

 You must have administrator privileges to use the **recimg** command, and you can only access the custom recovery image you create via the Windows 8 **refresh** feature.

 In [Windows 10, system recovery](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) has changed. Windows 10 systems don't come with a recovery partition, which makes it more important than ever to back up your data.

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Command and Conquer Your Windows PC

 This article can only give you a taste of what's hidden within the Windows command line. When including all variables, there are literally hundreds of commands. Which ones will turn you into a command prompt master?

 The command prompt is slowly disappearing from the Windows interface and for good reasons: CMD commands are an antiquated and mostly unnecessary tool from an era of text-based input. But many commands remain useful, and Windows 8 and 10 even added new features.

 Here we present the essential commands every Windows user must know.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>



