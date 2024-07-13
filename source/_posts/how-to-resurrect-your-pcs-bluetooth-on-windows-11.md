---
title: How to Resurrect Your PC's Bluetooth on Windows 11
date: 2024-07-12T16:37:33.815Z
updated: 2024-07-13T16:37:33.815Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Resurrect Your PC's Bluetooth on Windows 11
excerpt: This Article Describes How to Resurrect Your PC's Bluetooth on Windows 11
keywords: Revive PC Bluetooth Win11,Reconnect Bluetooth Windows 11,Fix Bluetooth in Win11,Reactivate Bluetooth Win11,Restart PCs' Bluetooth Windows,Windows 11 Bluetooth Reactivation,Boost PC Bluetooth on Windows 11
thumbnail: https://thmb.techidaily.com/0e76410444c7c01d9e8ad4e31c08df5ce8b625bff84337aa8bb982a08609d9e6.jpg
---

## How to Resurrect Your PC's Bluetooth on Windows 11

### Quick Links

* [Run the Appropriate Windows Troubleshooters](#run-the-appropriate-windows-troubleshooters)
* [Perform a Power Cycle](#perform-a-power-cycle)
* [Check the Quick Settings Panel](#check-the-quick-settings-panel)
* [Check Bluetooth Settings](#check-bluetooth-settings)
* [Configure the Bluetooth Support Service](#configure-the-bluetooth-support-service)
* [Update or Reinstall Your Bluetooth Drivers](#update-or-reinstall-your-bluetooth-drivers)
* [Disable and Re-Enable the Problematic USB Driver](#disable-and-re-enable-the-problematic-usb-driver)
* [Run SFC and DISM Scans](#run-sfc-and-dism-scans)
* [Boot into Safe Mode](#boot-into-safe-mode)

 Has the Bluetooth option disappeared on your Windows 11 computer? This can happen for several reasons, including temporary glitches, damaged Bluetooth drivers, and issues with the Windows OS. If you're unsure about what caused the problem, here are some tips that will help.

## 1\. Run the Appropriate Windows Troubleshooters

 Windows troubleshooters are built-in utilities that can help you diagnose and resolve various system-level issues. You can run the Bluetooth troubleshooter and allow Windows to fix any common Bluetooth-related issues. Here’s how:

1. Press **Win + I** to launch the Settings app.
2. In the **System** tab, click **Troubleshoot**.
3. Select **Other troubleshooters**.
4. Click the **Run** button next to **Bluetooth**.  
![Bluetooth Troubleshooter on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Bluetooth-Troubleshooter-on-Windows-11.jpg)

 Windows will scan your computer for any issues and try to fix them. Additionally, you can run the Hardware and Devices troubleshooter to scan your computer for any hardware issues. To do so:

1. Press **Win + R** to open the Run dialog.
2. Type **msdt.exe -id DeviceDiagnostic** in the Open field and press **Enter**.
3. In the Hardware and Devices window, click **Next** and follow the on-screen instructions to run the troubleshooter.  
![Hardware and Devices Troubleshooter on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Hardware-and-Devices-Troubleshooter-on-Windows.jpg)

## 2\. Perform a Power Cycle

 Sometimes, the most effective solution is surprisingly simple. Performing a power cycle can resolve various issues with your Windows PC caused by temporary glitches. To perform a power cycle:

1. Turn off your computer and unplug it from the power source.
2. Press and hold the **power button** for 30 to 60 seconds to drain all the power that’s left on your device.
3. Leave your computer idle for a few minutes.
4. Connect your computer to the power supply, and then turn it back on.

## 3\. Check the Quick Settings Panel

 The [Quick Settings panel in Windows 11](http://www.makeuseof.com/windows-11-customize-quick-settings-menu/) provides access to various commonly used settings, including Bluetooth. If you can’t find the Bluetooth toggle in the Quick Settings panel, you might have removed it by mistake. Here’s how you can retrieve it.

1. Press **Win + A** to open the Quick Settings panel.
2. Click the **pencil icon** to edit the Quick Settings panel.
3. Click on **Add** and select **Bluetooth** from the list to add it to the panel.  
![Add Bluetooth to Quick Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Add-Bluetooth-to-Quick-Settings.jpg)

## 4\. Check Bluetooth Settings

 The Bluetooth icon may not appear on the taskbar or system tray if you have previously removed the icon. Here's how you can [pin the Bluetooth icon to the Windows taskbar](https://www.makeuseof.com/how-pin-bluetooth-icon-windows-10-taskbar/) again.

1. Open the **Start menu** and go to **Settings > Bluetooth & devices**.
2. Go to **Devices** and click on **More Bluetooth Settings**.
3. Tick the box that reads **Show the Bluetooth icon in the notification area**.
4. Hit **Apply,** followed by **OK**.  
![Bluetooth Settings Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Bluetooth-Settings-Window.jpg)

## 5\. Configure the Bluetooth Support Service

 Bluetooth Support Service is a small program that runs in the background to allow Bluetooth to function on Windows. Your Bluetooth issues could be because the service isn't running. Here’s how to fix it.

1. Press **Win + R** to open the Run dialog.
2. Type **services.msc** in the text field and press **Enter**.
3. Double-click on **Bluetooth Support Service** to open its properties.
4. Use the drop-down menu next to **Startup type** to select **Automatic**.
5. Hit **Apply** to save changes.  
![Bluetooth Support Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Bluetooth-Support-Service.jpg)

 Restart your PC one more time and check if the Bluetooth option appears.

## 6\. Update or Reinstall Your Bluetooth Drivers

 Malfunctioning or corrupt Bluetooth drivers on your PC could also be the source of the problem. If that seems to be the case, updating the Bluetooth driver should help.

1. Right-click on the **Start** icon and select **Device Manager** from the list.
2. Expand the **Bluetooth** section, right-click on the **Bluetooth adapter**, and select **Update driver**.
3. Select **Search automatically for drivers** and allow Windows to install the best available drivers.  
![Update Bluetooth Driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Update-Bluetooth-Driver.jpg)

 If the Bluetooth entry is missing from the Device Manager, visit your Bluetooth adapter manufacturer's website to download the driver and install it manually.

 If updating the driver does not help, you’ll have to reinstall the Bluetooth drivers. To do so, open the Device Manager again, right-click on the **Bluetooth driver**, and then select **Uninstall device**.

 Once removed, restart your PC. Windows should install the missing Bluetooth driver during boot, and the Bluetooth option should appear on your PC.

## 7\. Disable and Re-Enable the Problematic USB Driver

 Several users on a [Microsoft Community post](https://answers.microsoft.com/en-us/windows/forum/all/windows-11-bluetooth-disappears-fixes-2023/34f5c8b1-b5a1-4323-a7f6-4513c733d731) reported restoring the missing Bluetooth functionality on their computers by disabling and re-enabling the USB drivers. You can also give it a go.

1. Open Device Manager using the search menu.
2. Expand **Universal Serial Bus controllers**.
3. Look for any entries with a yellow warning triangle. Right-click it and select **Disable device**.
4. Select **Yes** to confirm.
5. Right-click on the USB driver again and select **Enable device**.  
![Enable USB Driver Using Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/enable-usb-driver-using-device-manager.jpg)

## 8\. Run SFC and DISM Scans

 Bluetooth issues can also arise if critical system files are missing from your computer. Windows includes a couple of [tools that can help you replace any missing or damaged system files](http://www.makeuseof.com/windows-built-in-repair-tools/) with their cached version. Here’s how to run them.

1. Press **Win + X** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt shows up.
3. In the console, run the following command:

`sfc /scannow`

 Wait for the scan to complete, and then run the DISM (or Deployment Image Servicing and Management) scan.

`DISM.exe /Online /Cleanup-image /Restorehealth`

![DISM Scan on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/DISM-Scan-on-Windows.jpg)

 After the scan is complete, restart your PC and check if the issue is still there.

## 9\. Boot into Safe Mode

 When you boot Windows into Safe Mode, it runs without any non-essential drivers and programs. This can help you verify if the issue is caused by a third-party driver or program running in the background.

 Windows 11 gives [several options for booting into Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/). You can use any of your preferred methods to enter Safe Mode and see if the Bluetooth option appears. If it does, then a third-party program or service is to blame. In that case, you’ll have to remove any recently installed apps or programs to fix the issue.

 Has the Bluetooth option disappeared on your Windows 11 computer? This can happen for several reasons, including temporary glitches, damaged Bluetooth drivers, and issues with the Windows OS. If you're unsure about what caused the problem, here are some tips that will help.

## 1\. Run the Appropriate Windows Troubleshooters

 Windows troubleshooters are built-in utilities that can help you diagnose and resolve various system-level issues. You can run the Bluetooth troubleshooter and allow Windows to fix any common Bluetooth-related issues. Here’s how:

1. Press **Win + I** to launch the Settings app.
2. In the **System** tab, click **Troubleshoot**.
3. Select **Other troubleshooters**.
4. Click the **Run** button next to **Bluetooth**.  
![Bluetooth Troubleshooter on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Bluetooth-Troubleshooter-on-Windows-11.jpg)

 Windows will scan your computer for any issues and try to fix them. Additionally, you can run the Hardware and Devices troubleshooter to scan your computer for any hardware issues. To do so:

1. Press **Win + R** to open the Run dialog.
2. Type **msdt.exe -id DeviceDiagnostic** in the Open field and press **Enter**.
3. In the Hardware and Devices window, click **Next** and follow the on-screen instructions to run the troubleshooter.  
![Hardware and Devices Troubleshooter on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Hardware-and-Devices-Troubleshooter-on-Windows.jpg)

## 2\. Perform a Power Cycle

 Sometimes, the most effective solution is surprisingly simple. Performing a power cycle can resolve various issues with your Windows PC caused by temporary glitches. To perform a power cycle:

1. Turn off your computer and unplug it from the power source.
2. Press and hold the **power button** for 30 to 60 seconds to drain all the power that’s left on your device.
3. Leave your computer idle for a few minutes.
4. Connect your computer to the power supply, and then turn it back on.

## 3\. Check the Quick Settings Panel

 The [Quick Settings panel in Windows 11](http://www.makeuseof.com/windows-11-customize-quick-settings-menu/) provides access to various commonly used settings, including Bluetooth. If you can’t find the Bluetooth toggle in the Quick Settings panel, you might have removed it by mistake. Here’s how you can retrieve it.

1. Press **Win + A** to open the Quick Settings panel.
2. Click the **pencil icon** to edit the Quick Settings panel.
3. Click on **Add** and select **Bluetooth** from the list to add it to the panel.  
![Add Bluetooth to Quick Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Add-Bluetooth-to-Quick-Settings.jpg)

## 4\. Check Bluetooth Settings

 The Bluetooth icon may not appear on the taskbar or system tray if you have previously removed the icon. Here's how you can [pin the Bluetooth icon to the Windows taskbar](https://www.makeuseof.com/how-pin-bluetooth-icon-windows-10-taskbar/) again.

1. Open the **Start menu** and go to **Settings > Bluetooth & devices**.
2. Go to **Devices** and click on **More Bluetooth Settings**.
3. Tick the box that reads **Show the Bluetooth icon in the notification area**.
4. Hit **Apply,** followed by **OK**.  
![Bluetooth Settings Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Bluetooth-Settings-Window.jpg)

## 5\. Configure the Bluetooth Support Service

 Bluetooth Support Service is a small program that runs in the background to allow Bluetooth to function on Windows. Your Bluetooth issues could be because the service isn't running. Here’s how to fix it.

1. Press **Win + R** to open the Run dialog.
2. Type **services.msc** in the text field and press **Enter**.
3. Double-click on **Bluetooth Support Service** to open its properties.
4. Use the drop-down menu next to **Startup type** to select **Automatic**.
5. Hit **Apply** to save changes.  
![Bluetooth Support Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Bluetooth-Support-Service.jpg)

 Restart your PC one more time and check if the Bluetooth option appears.

## 6\. Update or Reinstall Your Bluetooth Drivers

 Malfunctioning or corrupt Bluetooth drivers on your PC could also be the source of the problem. If that seems to be the case, updating the Bluetooth driver should help.

1. Right-click on the **Start** icon and select **Device Manager** from the list.
2. Expand the **Bluetooth** section, right-click on the **Bluetooth adapter**, and select **Update driver**.
3. Select **Search automatically for drivers** and allow Windows to install the best available drivers.  
![Update Bluetooth Driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Update-Bluetooth-Driver.jpg)

 If the Bluetooth entry is missing from the Device Manager, visit your Bluetooth adapter manufacturer's website to download the driver and install it manually.

 If updating the driver does not help, you’ll have to reinstall the Bluetooth drivers. To do so, open the Device Manager again, right-click on the **Bluetooth driver**, and then select **Uninstall device**.

 Once removed, restart your PC. Windows should install the missing Bluetooth driver during boot, and the Bluetooth option should appear on your PC.

## 7\. Disable and Re-Enable the Problematic USB Driver

 Several users on a [Microsoft Community post](https://answers.microsoft.com/en-us/windows/forum/all/windows-11-bluetooth-disappears-fixes-2023/34f5c8b1-b5a1-4323-a7f6-4513c733d731) reported restoring the missing Bluetooth functionality on their computers by disabling and re-enabling the USB drivers. You can also give it a go.

1. Open Device Manager using the search menu.
2. Expand **Universal Serial Bus controllers**.
3. Look for any entries with a yellow warning triangle. Right-click it and select **Disable device**.
4. Select **Yes** to confirm.
5. Right-click on the USB driver again and select **Enable device**.  
![Enable USB Driver Using Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/enable-usb-driver-using-device-manager.jpg)

## 8\. Run SFC and DISM Scans

 Bluetooth issues can also arise if critical system files are missing from your computer. Windows includes a couple of [tools that can help you replace any missing or damaged system files](http://www.makeuseof.com/windows-built-in-repair-tools/) with their cached version. Here’s how to run them.

1. Press **Win + X** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt shows up.
3. In the console, run the following command:

`sfc /scannow`

 Wait for the scan to complete, and then run the DISM (or Deployment Image Servicing and Management) scan.

`DISM.exe /Online /Cleanup-image /Restorehealth`

![DISM Scan on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/DISM-Scan-on-Windows.jpg)

 After the scan is complete, restart your PC and check if the issue is still there.

## 9\. Boot into Safe Mode

 When you boot Windows into Safe Mode, it runs without any non-essential drivers and programs. This can help you verify if the issue is caused by a third-party driver or program running in the background.

 Windows 11 gives [several options for booting into Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/). You can use any of your preferred methods to enter Safe Mode and see if the Bluetooth option appears. If it does, then a third-party program or service is to blame. In that case, you’ll have to remove any recently installed apps or programs to fix the issue.

 Has the Bluetooth option disappeared on your Windows 11 computer? This can happen for several reasons, including temporary glitches, damaged Bluetooth drivers, and issues with the Windows OS. If you're unsure about what caused the problem, here are some tips that will help.

## 1\. Run the Appropriate Windows Troubleshooters

 Windows troubleshooters are built-in utilities that can help you diagnose and resolve various system-level issues. You can run the Bluetooth troubleshooter and allow Windows to fix any common Bluetooth-related issues. Here’s how:

1. Press **Win + I** to launch the Settings app.
2. In the **System** tab, click **Troubleshoot**.
3. Select **Other troubleshooters**.
4. Click the **Run** button next to **Bluetooth**.  
![Bluetooth Troubleshooter on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Bluetooth-Troubleshooter-on-Windows-11.jpg)

 Windows will scan your computer for any issues and try to fix them. Additionally, you can run the Hardware and Devices troubleshooter to scan your computer for any hardware issues. To do so:

1. Press **Win + R** to open the Run dialog.
2. Type **msdt.exe -id DeviceDiagnostic** in the Open field and press **Enter**.
3. In the Hardware and Devices window, click **Next** and follow the on-screen instructions to run the troubleshooter.  
![Hardware and Devices Troubleshooter on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Hardware-and-Devices-Troubleshooter-on-Windows.jpg)

## 2\. Perform a Power Cycle

 Sometimes, the most effective solution is surprisingly simple. Performing a power cycle can resolve various issues with your Windows PC caused by temporary glitches. To perform a power cycle:

1. Turn off your computer and unplug it from the power source.
2. Press and hold the **power button** for 30 to 60 seconds to drain all the power that’s left on your device.
3. Leave your computer idle for a few minutes.
4. Connect your computer to the power supply, and then turn it back on.

## 3\. Check the Quick Settings Panel

 The [Quick Settings panel in Windows 11](http://www.makeuseof.com/windows-11-customize-quick-settings-menu/) provides access to various commonly used settings, including Bluetooth. If you can’t find the Bluetooth toggle in the Quick Settings panel, you might have removed it by mistake. Here’s how you can retrieve it.

1. Press **Win + A** to open the Quick Settings panel.
2. Click the **pencil icon** to edit the Quick Settings panel.
3. Click on **Add** and select **Bluetooth** from the list to add it to the panel.  
![Add Bluetooth to Quick Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Add-Bluetooth-to-Quick-Settings.jpg)

## 4\. Check Bluetooth Settings

 The Bluetooth icon may not appear on the taskbar or system tray if you have previously removed the icon. Here's how you can [pin the Bluetooth icon to the Windows taskbar](https://www.makeuseof.com/how-pin-bluetooth-icon-windows-10-taskbar/) again.

1. Open the **Start menu** and go to **Settings > Bluetooth & devices**.
2. Go to **Devices** and click on **More Bluetooth Settings**.
3. Tick the box that reads **Show the Bluetooth icon in the notification area**.
4. Hit **Apply,** followed by **OK**.  
![Bluetooth Settings Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Bluetooth-Settings-Window.jpg)

## 5\. Configure the Bluetooth Support Service

 Bluetooth Support Service is a small program that runs in the background to allow Bluetooth to function on Windows. Your Bluetooth issues could be because the service isn't running. Here’s how to fix it.

1. Press **Win + R** to open the Run dialog.
2. Type **services.msc** in the text field and press **Enter**.
3. Double-click on **Bluetooth Support Service** to open its properties.
4. Use the drop-down menu next to **Startup type** to select **Automatic**.
5. Hit **Apply** to save changes.  
![Bluetooth Support Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Bluetooth-Support-Service.jpg)

 Restart your PC one more time and check if the Bluetooth option appears.

## 6\. Update or Reinstall Your Bluetooth Drivers

 Malfunctioning or corrupt Bluetooth drivers on your PC could also be the source of the problem. If that seems to be the case, updating the Bluetooth driver should help.

1. Right-click on the **Start** icon and select **Device Manager** from the list.
2. Expand the **Bluetooth** section, right-click on the **Bluetooth adapter**, and select **Update driver**.
3. Select **Search automatically for drivers** and allow Windows to install the best available drivers.  
![Update Bluetooth Driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Update-Bluetooth-Driver.jpg)

 If the Bluetooth entry is missing from the Device Manager, visit your Bluetooth adapter manufacturer's website to download the driver and install it manually.

 If updating the driver does not help, you’ll have to reinstall the Bluetooth drivers. To do so, open the Device Manager again, right-click on the **Bluetooth driver**, and then select **Uninstall device**.

 Once removed, restart your PC. Windows should install the missing Bluetooth driver during boot, and the Bluetooth option should appear on your PC.

## 7\. Disable and Re-Enable the Problematic USB Driver

 Several users on a [Microsoft Community post](https://answers.microsoft.com/en-us/windows/forum/all/windows-11-bluetooth-disappears-fixes-2023/34f5c8b1-b5a1-4323-a7f6-4513c733d731) reported restoring the missing Bluetooth functionality on their computers by disabling and re-enabling the USB drivers. You can also give it a go.

1. Open Device Manager using the search menu.
2. Expand **Universal Serial Bus controllers**.
3. Look for any entries with a yellow warning triangle. Right-click it and select **Disable device**.
4. Select **Yes** to confirm.
5. Right-click on the USB driver again and select **Enable device**.  
![Enable USB Driver Using Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/enable-usb-driver-using-device-manager.jpg)

## 8\. Run SFC and DISM Scans

 Bluetooth issues can also arise if critical system files are missing from your computer. Windows includes a couple of [tools that can help you replace any missing or damaged system files](http://www.makeuseof.com/windows-built-in-repair-tools/) with their cached version. Here’s how to run them.

1. Press **Win + X** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt shows up.
3. In the console, run the following command:

`sfc /scannow`

 Wait for the scan to complete, and then run the DISM (or Deployment Image Servicing and Management) scan.

`DISM.exe /Online /Cleanup-image /Restorehealth`

![DISM Scan on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/DISM-Scan-on-Windows.jpg)

 After the scan is complete, restart your PC and check if the issue is still there.

## 9\. Boot into Safe Mode

 When you boot Windows into Safe Mode, it runs without any non-essential drivers and programs. This can help you verify if the issue is caused by a third-party driver or program running in the background.

 Windows 11 gives [several options for booting into Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/). You can use any of your preferred methods to enter Safe Mode and see if the Bluetooth option appears. If it does, then a third-party program or service is to blame. In that case, you’ll have to remove any recently installed apps or programs to fix the issue.

 Has the Bluetooth option disappeared on your Windows 11 computer? This can happen for several reasons, including temporary glitches, damaged Bluetooth drivers, and issues with the Windows OS. If you're unsure about what caused the problem, here are some tips that will help.

## 1\. Run the Appropriate Windows Troubleshooters

 Windows troubleshooters are built-in utilities that can help you diagnose and resolve various system-level issues. You can run the Bluetooth troubleshooter and allow Windows to fix any common Bluetooth-related issues. Here’s how:

1. Press **Win + I** to launch the Settings app.
2. In the **System** tab, click **Troubleshoot**.
3. Select **Other troubleshooters**.
4. Click the **Run** button next to **Bluetooth**.  
![Bluetooth Troubleshooter on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Bluetooth-Troubleshooter-on-Windows-11.jpg)

 Windows will scan your computer for any issues and try to fix them. Additionally, you can run the Hardware and Devices troubleshooter to scan your computer for any hardware issues. To do so:

1. Press **Win + R** to open the Run dialog.
2. Type **msdt.exe -id DeviceDiagnostic** in the Open field and press **Enter**.
3. In the Hardware and Devices window, click **Next** and follow the on-screen instructions to run the troubleshooter.  
![Hardware and Devices Troubleshooter on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Hardware-and-Devices-Troubleshooter-on-Windows.jpg)

## 2\. Perform a Power Cycle

 Sometimes, the most effective solution is surprisingly simple. Performing a power cycle can resolve various issues with your Windows PC caused by temporary glitches. To perform a power cycle:

1. Turn off your computer and unplug it from the power source.
2. Press and hold the **power button** for 30 to 60 seconds to drain all the power that’s left on your device.
3. Leave your computer idle for a few minutes.
4. Connect your computer to the power supply, and then turn it back on.

## 3\. Check the Quick Settings Panel

 The [Quick Settings panel in Windows 11](http://www.makeuseof.com/windows-11-customize-quick-settings-menu/) provides access to various commonly used settings, including Bluetooth. If you can’t find the Bluetooth toggle in the Quick Settings panel, you might have removed it by mistake. Here’s how you can retrieve it.

1. Press **Win + A** to open the Quick Settings panel.
2. Click the **pencil icon** to edit the Quick Settings panel.
3. Click on **Add** and select **Bluetooth** from the list to add it to the panel.  
![Add Bluetooth to Quick Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Add-Bluetooth-to-Quick-Settings.jpg)

## 4\. Check Bluetooth Settings

 The Bluetooth icon may not appear on the taskbar or system tray if you have previously removed the icon. Here's how you can [pin the Bluetooth icon to the Windows taskbar](https://www.makeuseof.com/how-pin-bluetooth-icon-windows-10-taskbar/) again.

1. Open the **Start menu** and go to **Settings > Bluetooth & devices**.
2. Go to **Devices** and click on **More Bluetooth Settings**.
3. Tick the box that reads **Show the Bluetooth icon in the notification area**.
4. Hit **Apply,** followed by **OK**.  
![Bluetooth Settings Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Bluetooth-Settings-Window.jpg)

## 5\. Configure the Bluetooth Support Service

 Bluetooth Support Service is a small program that runs in the background to allow Bluetooth to function on Windows. Your Bluetooth issues could be because the service isn't running. Here’s how to fix it.

1. Press **Win + R** to open the Run dialog.
2. Type **services.msc** in the text field and press **Enter**.
3. Double-click on **Bluetooth Support Service** to open its properties.
4. Use the drop-down menu next to **Startup type** to select **Automatic**.
5. Hit **Apply** to save changes.  
![Bluetooth Support Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Bluetooth-Support-Service.jpg)

 Restart your PC one more time and check if the Bluetooth option appears.

## 6\. Update or Reinstall Your Bluetooth Drivers

 Malfunctioning or corrupt Bluetooth drivers on your PC could also be the source of the problem. If that seems to be the case, updating the Bluetooth driver should help.

1. Right-click on the **Start** icon and select **Device Manager** from the list.
2. Expand the **Bluetooth** section, right-click on the **Bluetooth adapter**, and select **Update driver**.
3. Select **Search automatically for drivers** and allow Windows to install the best available drivers.  
![Update Bluetooth Driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Update-Bluetooth-Driver.jpg)

 If the Bluetooth entry is missing from the Device Manager, visit your Bluetooth adapter manufacturer's website to download the driver and install it manually.

 If updating the driver does not help, you’ll have to reinstall the Bluetooth drivers. To do so, open the Device Manager again, right-click on the **Bluetooth driver**, and then select **Uninstall device**.

 Once removed, restart your PC. Windows should install the missing Bluetooth driver during boot, and the Bluetooth option should appear on your PC.

## 7\. Disable and Re-Enable the Problematic USB Driver

 Several users on a [Microsoft Community post](https://answers.microsoft.com/en-us/windows/forum/all/windows-11-bluetooth-disappears-fixes-2023/34f5c8b1-b5a1-4323-a7f6-4513c733d731) reported restoring the missing Bluetooth functionality on their computers by disabling and re-enabling the USB drivers. You can also give it a go.

1. Open Device Manager using the search menu.
2. Expand **Universal Serial Bus controllers**.
3. Look for any entries with a yellow warning triangle. Right-click it and select **Disable device**.
4. Select **Yes** to confirm.
5. Right-click on the USB driver again and select **Enable device**.  
![Enable USB Driver Using Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/enable-usb-driver-using-device-manager.jpg)

## 8\. Run SFC and DISM Scans

 Bluetooth issues can also arise if critical system files are missing from your computer. Windows includes a couple of [tools that can help you replace any missing or damaged system files](http://www.makeuseof.com/windows-built-in-repair-tools/) with their cached version. Here’s how to run them.

1. Press **Win + X** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt shows up.
3. In the console, run the following command:

`sfc /scannow`

 Wait for the scan to complete, and then run the DISM (or Deployment Image Servicing and Management) scan.

`DISM.exe /Online /Cleanup-image /Restorehealth`

![DISM Scan on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/DISM-Scan-on-Windows.jpg)

 After the scan is complete, restart your PC and check if the issue is still there.

## 9\. Boot into Safe Mode

 When you boot Windows into Safe Mode, it runs without any non-essential drivers and programs. This can help you verify if the issue is caused by a third-party driver or program running in the background.

 Windows 11 gives [several options for booting into Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/). You can use any of your preferred methods to enter Safe Mode and see if the Bluetooth option appears. If it does, then a third-party program or service is to blame. In that case, you’ll have to remove any recently installed apps or programs to fix the issue.


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
<li><a href="https://win11-tips.techidaily.com/mastering-map-integration-in-windows/"><u>Mastering Map Integration in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-windows-component-services-interface-quickly/"><u>Accessing Windows' Component Services Interface Quickly</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-rank-of-15-innovative-live-stream-applications-beyond-obs/"><u>[New] In 2024, Rank of 15 Innovative Live-Stream Applications Beyond OBS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-nullified-network-visibility-in-windows/"><u>Navigating Through Nullified Network Visibility in Windows</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-prime-mkv-software-pc-and-android/"><u>[Updated] Prime MKV Software  PC & Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-onedrive-errors-an-easy-guide/"><u>Overcoming Windows OneDrive Errors: An Easy Guide</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/1719574908150-norges-lexicon-leapfrogging-10-minutes-a-day/"><u>Norge's Lexicon Leapfrogging, 10 Minutes A Day!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-tips-for-playing-old-championship-manager-on-pc/"><u>Top Tips for Playing Old Championship Manager on PC</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-androidprocessmedia-has-stopped-on-realme-c55-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android.Process.Media Has Stopped on Realme C55 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719380879608-speedy-outlook-on-windows-heres-how/"><u>Speedy Outlook on Windows? Here's How!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steering-clear-of-low-performance-pitfalls-intel-gpu-resolution/"><u>Steering Clear of Low-Performance Pitfalls: Intel GPU Resolution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-subnet-changes-in-win11/"><u>Navigating Subnet Changes in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-update-failures-strategies-for-error-0x30017/"><u>Overcoming Windows Update Failures: Strategies for Error 0X30017</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-unleash-your-creativity-top-apple-video-editing-tools/"><u>Updated In 2024, Unleash Your Creativity Top Apple Video Editing Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-server-disruptions-and-ms-store-issues-on-windows-11-and-11/"><u>Remedy for Server Disruptions and MS Store Issues on Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/teams-upgrade-fast-memory-conscious-solution/"><u>Teams Upgrade: Fast, Memory-Conscious Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-customize-windows-11s-search-via-settings/"><u>5 Ways to Customize Windows 11'S Search via Settings</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unlock-movie-magic-with-cg-centrals-look-up-tables-luts/"><u>In 2024, Unlock Movie Magic with CG Central's Look-Up Tables (Luts)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-your-digital-experience-with-active-windows-11-notifications/"><u>Maximizing Your Digital Experience with Active Windows 11 Notifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-to-enhancing-performance-in-your-new-windows-11-setup/"><u>A Quick Guide to Enhancing Performance in Your New Windows 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1011-permanent-file-disposal-via-custom-trash-bin-setup/"><u>Windows 10/11: Permanent File Disposal via Custom Trash Bin Setup</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/the-ultimate-guide-to-yoga-focused-fitness-channels/"><u>The Ultimate Guide to Yoga-Focused Fitness Channels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-re-listing-bluetooth-on-windows-pc/"><u>Strategies for Re-Listing Bluetooth on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-recover-faulty-windows-file-organizer/"><u>Methods to Recover Faulty Windows File Organizer</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-boosting-vimeo-streams-tips-and-tricks/"><u>In 2024, Boosting Vimeo Streams  Tips & Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-installation-issues-with-windows-11-troubleshooter/"><u>Solving Installation Issues with Windows 11 Troubleshooter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-for-operational-windows-desktop-context-menus/"><u>Tactics for Operational Windows Desktop Context Menus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-frozen-wastebin-symbol-on-win11/"><u>Reactivating Frozen Wastebin Symbol on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pushing-the-limits-of-solid-state-drives-on-windows-with-ssdfresh/"><u>Pushing the Limits of Solid State Drives on Windows with SSDFresh</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silence-missed-specification-alert-on-windows-11/"><u>Silence Missed Specification Alert on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-eradicate-0x800713f-error-on-windows-11/"><u>Strategies to Eradicate 0X800713F Error on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-discord-install-failure/"><u>Overcoming Windows 11 Discord Install Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/verifying-microphone-function-on-windows/"><u>Verifying Microphone Function on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-print-bridge-trouble-shooting-guide/"><u>Windows Print Bridge: Trouble Shooting Guide</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-oppo-k11x-drfone-by-drfone-virtual-android/"><u>3 Ways to Fake GPS Without Root On Oppo K11x | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strengthening-game-accessibility-winning-over-ea-errors/"><u>Strengthening Game Accessibility: Winning Over EA Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-to-do-restoring-lost-sync-credentials-effectively/"><u>Microsoft To-Do: Restoring Lost Sync Credentials Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-and-resolving-issues-with-registry-editor-missing/"><u>Uncovering and Resolving Issues with 'Registry Editor' Missing</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-the-ultimate-twitter-video-sizing-cheat-sheet-aspect-ratio-included/"><u>New In 2024, The Ultimate Twitter Video Sizing Cheat Sheet Aspect Ratio Included</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tap-out-of-high-contrast-in-windows-environment/"><u>Tap Out of High Contrast in Windows Environment</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-ultimate-guide-to-boosting-android-video-brilliance/"><u>The Ultimate Guide to Boosting Android Video Brilliance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-items-to-windows-11-desktop-menu-hierarchy/"><u>Adding Items to Windows 11 Desktop Menu Hierarchy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correct-invalid-profiles-in-windows-operating-systems/"><u>Steps to Correct Invalid Profiles in Windows Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winfixing-comprehensive-steps-for-repairing-windows-filesystem-issues/"><u>Winfixing: Comprehensive Steps for Repairing Windows Filesystem Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-hacks-for-instantaneous-iis-server-management-entry/"><u>8 Hacks for Instantaneous IIS Server Management Entry</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-explore-iphones-best-value-top-10-budget-friendly-photo-collage-apps/"><u>In 2024, Explore iPhone's Best Value  Top 10 Budget-Friendly Photo Collage Apps</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-vivo-y36i-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your Vivo Y36i</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-solution-for-0x80072af9-issue/"><u>Mastering Solution for 0X80072AF9 Issue</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-how-to-record-lectures-on-mac-for-2024/"><u>[New] How to Record Lectures on Mac for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-instantly-boost-youtube-performance-master-render-and-upload/"><u>[Updated] Instantly Boost YouTube Performance - Master Render and Upload</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-learn-the-ropes-of-tiktok-filming-from-basic-shots-to-cinematic-scenes/"><u>[New] In 2024, Learn the Ropes of TikTok Filming  From Basic Shots to Cinematic Scenes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unresponsive-windows-outlook-conditional-rules/"><u>Overcoming Unresponsive Windows Outlook Conditional Rules</u></a></li>
</ul></div>
