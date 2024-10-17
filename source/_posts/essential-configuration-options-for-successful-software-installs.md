---
title: Essential Configuration Options for Successful Software Installs
date: 2024-10-12T10:27:17.836Z
updated: 2024-10-17T01:52:03.727Z
tags:
  - user-guide
categories:
  - advancedinstaller
description: This Article Describes Essential Configuration Options for Successful Software Installs
thumbnail: https://thmb.techidaily.com/650d5e59730c35ae2fda836f0e084961424a5a8000cea452bed766d220fa39c3.jpg
---

## Essential Configuration Options for Successful Software Installs

Table of Contents

* [Introduction](https://tools.techidaily.com/advancedinstaller/products/)
* [Registration](https://tools.techidaily.com/advancedinstaller/products/)
* [Using Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [GUI](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Working with Projects](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Installer Project](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Product Information](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Resources](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Package Definition](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Install Parameters](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Execution Level Settings Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Organization](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Builds](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Analytics](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [SCCM](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [ActiveSync](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Requirements](https://tools.techidaily.com/advancedinstaller/products/)  
         * [User Interface](https://tools.techidaily.com/advancedinstaller/products/)  
         * [System Changes](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Server](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Custom Behavior](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Patch Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Merge Module Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Updates Configuration Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Windows Store App Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Modification Package Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Optional Package Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Windows Mobile CAB Projects](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Visual Studio Extension Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Software Installer Wizards - Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Visual Studio integration](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Alternative to AdminStudio/Wise](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Replace Wise](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Migrating from Visual Studio Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Keyboard Shortcuts](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Shell Integration](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Command Line](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Advanced Installer PowerShell Automation Interfaces](https://tools.techidaily.com/advancedinstaller/products/)
* [Features and Functionality](https://tools.techidaily.com/advancedinstaller/products/)
* [Tutorials](https://tools.techidaily.com/advancedinstaller/products/)
* [Samples](https://tools.techidaily.com/advancedinstaller/products/)
* [How-tos](https://tools.techidaily.com/advancedinstaller/products/)
* [FAQs](https://tools.techidaily.com/advancedinstaller/products/)
* [Windows Installer](https://tools.techidaily.com/advancedinstaller/products/)
* [Deployment Technologies](https://tools.techidaily.com/advancedinstaller/products/)
* [IT Pro](https://tools.techidaily.com/advancedinstaller/products/)
* [MSIX](https://tools.techidaily.com/advancedinstaller/products/)
* [Video Tutorials](https://tools.techidaily.com/advancedinstaller/products/)
* [Advanced Installer Blog](https://tools.techidaily.com/advancedinstaller/products/)
* [Table of Contents](https://tools.techidaily.com/advancedinstaller/products/)

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Install Parameters

Windows Installer properties are used during the installation process.

![Install parameters](https://cdn.advancedinstaller.com/img/ui/install-parameters.png "Install parameters")  

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg) You can use the drop-down list in the toolbar to select the current build. Also, all the changes made in this view apply only to the current build. 

## Installation Folders

* **Application Folder** \- in this field, you can specify the default location for the Application Folder (APPDIR). This path is stored in the **APPDIR** property, and it is applicable only to those files and folders which are located under the "Application Folder" directory in the [Files and Folders Page - Installer Project](https://tools.techidaily.com/advancedinstaller/products/). During the installation, the user can modify this path by either using the \[Browse \] button in the "FolderDlg" (Select Installation Folder) dialog or by manually editing the Path Edit control on the same dialog. The default value of this field points to a sub-folder of the [ProgramFilesFolder](https://learn.microsoft.com/en-us/windows/win32/msi/programfilesfolder) for the per--machine installs.
* **Application Shortcut Folder** \- in this field, you can specify the default location for the Application Shortcut Folder (SHORTCUTDIR). This path is stored in the**SHORTCUTDIR** property, and it is applicable only to those files and folders which are located under the "Application Shortcut Folder" directory in the "Files and Folders" page. The default value of this field points to a sub-folder of the [ProgramMenuFolder](https://learn.microsoft.com/en-us/windows/win32/msi/programmenufolder).

These values are directly editable, with a suggested set of defaults available in the drop-down lists. Click the \[Edit... \] button to change them through the [Edit Formatted Type Dialog](https://tools.techidaily.com/advancedinstaller/products/).

## Installation Options

### Package Type

 Select between 32-bit, Arm64, 64-bit for Intel 64 Itanium processors, 64-bit for AMD64 or EM64T processors and mixed 32/64 bit packages.

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)If the package runs on an x64 processor, the "64-bit package for x64 processors(AMD64, EM64T)" must be selected.

You can read more about the difference between those types in the [Package Types](https://tools.techidaily.com/advancedinstaller/products/) page.

### Installation Type

* **Per-user only** \- the application will be available only for the user who installed it.  
   * On Windows Vista or above, with this option set, the logged user will never be elevated to administrative privileges, so if the installation requires such privileges, it will fail.
* **Per-user only (with administrator rights required)** \- on Windows Vista or above, use this option to create a package which will be installed per user but requires administrator privileges (e.g. its application files need to be installed in a privileged location such as "Program Files").  
   * In this case, the user may see anElevation Prompt dialog that will ask for administrator privileges. If the logged user is a member of the "Administrators" user group, he will be asked to allow or deny the installation. Otherwise, he will be prompted to provide credentials for one of the computer administrators.  
   * On other Windows versions, this option behaves like the previous one.
* **Per-machine only (fails if the user is not administrator)** \- the application will be available for all the users of that machine.  
   * On Windows Vista or above the user may see an Elevation Prompt dialog that will ask for administrator privileges when installing the package. If the logged user is a member of the "Administrators" user group, he will be asked to allow or deny the installation. Otherwise, he will be prompted to provide credentials for one of the computer administrators.
* **Per-machine if the user is an administrator, per-user otherwise** \- the application will be installed "Per-machine" if the user has administrative rights and "Per-user" otherwise.  
   * To help with the appropriate install location, [AI\_UserProgramFiles property](https://tools.techidaily.com/advancedinstaller/products/) will be referenced in the application folder path.  
   * On Windows Vista and above this option has the same installation behavior as the previous one.  
   * On Windows 7 or above the installation will be _per-user_ with no UAC prompt only if the resources are installed in [per-user locations](https://tools.techidaily.com/advancedinstaller/products/). Besides this, the installation will also require the [InstallTypeDlg](https://tools.techidaily.com/advancedinstaller/products/) so the user can choose the _per-user_ option. This option will set the [MSIRunningElevated property](https://tools.techidaily.com/advancedinstaller/products/) which can be manually set instead of using the dialog.

![Caution!](https://cdn.advancedinstaller.com/svg/common/IconMessageWarning.svg)The "Per-machine if the user is an administrator, per-user otherwise" option requires "InstallTypeDlg" dialog to be present in [Dialogs page](https://tools.techidaily.com/advancedinstaller/products/)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938721/19272" target="_top" id="1938721">
  <img src="//a.impactradius-go.com/display-ad/19272-1938721" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938721/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Caution!](https://cdn.advancedinstaller.com/svg/common/IconMessageWarning.svg)A per-user installation cannot upgrade a per-machine installation, and a per-machine installation cannot upgrade a per-user installation. However, you can try using a [Preserve Install Type of the old version](https://tools.techidaily.com/advancedinstaller/products/) predefined UI custom action.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918679/19272" target="_top" id="1918679">
  <img src="//a.impactradius-go.com/display-ad/19272-1918679" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918679/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)On Windows Vista or above, it is strongly recommended that you do not alter the value of the ALLUSERS property during install.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144282/7443" target="_top" id="2144282">
  <img src="//a.impactradius-go.com/display-ad/7443-2144282" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144282/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

When performing a Per User installation, the package must respect some rules:

* it creates registry entries only under HKEY\_CURRENT\_USER
* it creates shortcuts only in the user's profile (not in per-machine locations)
* it writes information only in Per User locations (for example a normal user cannot write in the "Windows" or "Program Files" folders)

### Reboot Behavior

 Windows Installer can determine when a system reboot is required and automatically prompt the user at the end of the installation. For instance, if the installer needs to replace any files that are in use during the installation it will automatically prompt for a reboot once the installation is finished.

You can change this default behavior by specifying one of the options below to always prompt for a reboot or to suppress some or all reboot prompts.

* **Prompt for Reboot when required** \- let Windows Installer decide when a system reboot is necessary (for example, when it needs to replace any files that are in use during the installation).
* **Force Reboot after install** \- always prompt for a reboot at the end of the installation, even if a system reboot is not required.
* **Suppress Reboot after install, except for ForceReboot actions** \- Suppress prompts for a reboot at the end of the installation. If the installer encounters the ForceReboot action, it still prompts the user with an option to reboot during the installation.
* **Suppress all Reboots and Reboot prompts** \- all reboots and reboot prompts at the end of the installation and during the installation (initiated by the ForceReboot action) are suppressed.

![Caution!](https://cdn.advancedinstaller.com/svg/common/IconMessageWarning.svg)A reboot request will discontinue a [chained installation](https://tools.techidaily.com/advancedinstaller/products/). If one of the chained packages requires a reboot, you should suppress it by setting the REBOOT property to ReallySuppress. For the main package, you can set the REBOOT property to Force. This way a reboot will be performed when the chained installation is complete.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135351/19272" target="_top" id="2135351">
  <img src="//a.impactradius-go.com/display-ad/19272-2135351" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135351/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Perform the reboot if required without showing any prompts

This option makes the installer perform any required reboots automatically, without prompting the user.

### Limit to a basic user interface (simple progress and error handling)

 This option directs Windows Installer to display only a dialog with a progress bar showing the evolution of the installation and the message boxes that display error messages. It is used especially for unassisted or automated installs (e.g. deployment through Group Policy). 

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)If you select this option, the “Disable Modify” option from “Programs and Features (Control Panel)” will also be selected.

### Enable Verbose Logging

By enabling this option, a log file will be generated each time the install package runs. This option sets the Windows Installer **MsiLogging** property to **vp** value. Windows Installer will automatically set the **MsiLogFileLocation** property to the path where the log file will be generated. By default, the **MsiLogFileLocation** will point to:

* _CurrentUser\\LocalSettings\\Temp\\MSI\*.LOG_ for Windows XP.
* _CurrentUser\\AppData\\Local\\Temp\\MSI\*.LOG_ for Windows Vista or later.

Where \* is a random set of letters and numbers.

![Caution!](https://cdn.advancedinstaller.com/svg/common/IconMessageWarning.svg)The **MsiLogFileLocation** is a **Read-only** property and cannot be changed by the package author or by the user. Its value is automatically set**during** the runtime of the installation package.

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)This option requires Windows Installer 5.0 on Windows Server 2008 R2 or Windows 7\. Windows Installer 4.0 or Windows Installer 4.5 on Windows Server 2008 or Windows Vista, Windows Installer 4.5 on Windows Server 2003 or Windows XP to work properly.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123737/7443" target="_top" id="2123737">
  <img src="//a.impactradius-go.com/display-ad/7443-2123737" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123737/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/977686/11832" target="_top" id="977686">
  <img src="//a.impactradius-go.com/display-ad/11832-977686" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/977686/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Execution Level

**Run as administrator** \- enabling this option automatically sets the execution level to "Require Administrator". Disabling it will set the execution level back to "As Invoker" default.

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)Checking "Run as administrator" doesn't give administrative permissions to the Control Panel instance of the application.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997675/19272" target="_top" id="1997675">
  <img src="//a.impactradius-go.com/display-ad/19272-1997675" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997675/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)Run as administrator does not work for MSI packages launched in maintenance mode.

**Execution level...** \- this link displays the EXE bootstrapper's [Execution Level Settings](https://tools.techidaily.com/advancedinstaller/products/).

## Minimize Installation Time

### Fast Installation

These options enable you to drastically reduce the time it takes your application to install by:

* Moving files on the same volume rather than copy
* Suppressing installation progress estimate

Requirements:

* Installation is using the [Enhanced User Interface](https://tools.techidaily.com/advancedinstaller/products/).
* The install location selected by the user is on the same drive where the files have been extracted.
* Per-machine installation is performing.
* The first time the application is installing.
* No features are being advertised or installed to run from source.
* No isolated components are being installed.

![Caution!](https://cdn.advancedinstaller.com/svg/common/IconMessageWarning.svg)On Windows 7 and above when _Fast Installation_ option is used, the standard users access to installed files will be restricted.

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)The three following options can be used together but are ignored on machines with Windows Installer 4.0 or older. The installation time can be decreased with these options only when **Windows Installer 4.5** or higher is found on the target machine.

### Don't save system restore points for installation

If this option is set, Windows Installer will no longer create system restore points for the install process.

### Perform only file costing and skip checking other costs

If this option is set, Windows Installer will perform only file costing, ignoring the rest of costs.

### Reduce the frequency of progress messages

If this option is set, the installation progress is updated less frequently.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006955/19272" target="_top" id="2006955">
  <img src="//a.impactradius-go.com/display-ad/19272-2006955" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006955/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Topics

* [Execution Level Settings Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
Dialog to set the execution level.

#### Did you find this page useful?

Please give it a rating:

 Thanks!

#### Report a problem on this page

Information is incorrect or missing

Information is unclear or confusing

Something else

#### Can you tell us what’s wrong?

Send message

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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-security-victory-making-your-fb-available-again/"><u>[New] 2024 Approved Security Victory Making Your FB Available Again</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-no-pay-maximum-fun-20-custom-lut-sets-for-dji-miniair-users/"><u>[New] No Pay, Maximum Fun 20 Custom LUT Sets for DJI Mini/Air Users</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/3-ways-to-erase-apple-iphone-se-2022-when-its-locked-within-seconds-drfone-by-drfone-ios/"><u>3 Ways to Erase Apple iPhone SE (2022) When Its Locked Within Seconds | Dr.fone</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/ps4pc/"><u>重建PS4存放的信息技術：解決PC平台如何回復硬碟數據的指南</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/expert-tips-resolving-windows-startup-failures-without-recovery-options-windows-11-8-7/"><u>Expert Tips: Resolving Windows Startup Failures Without Recovery Options (Windows 11, 8, 7)</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-simulate-gps-movement-with-location-spoofer-on-vivo-y56-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How To Simulate GPS Movement With Location Spoofer On Vivo Y56 5G? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-proven-ways-in-how-to-hide-location-on-life360-for-xiaomi-mix-fold-3-drfone-by-drfone-virtual-android/"><u>In 2024, Proven Ways in How To Hide Location on Life360 For Xiaomi Mix Fold 3 | Dr.fone</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/installing-windows-adk-seamlessly-integrated-with-aomei-backupper-your-guide/"><u>Installing Windows ADK Seamlessly Integrated with AOMEI Backupper - Your Guide</u></a></li>
<li><a href="https://review-topics.techidaily.com/mkv-playback-issues-on-xiaomi-redmi-note-12r-by-aiseesoft-video-converter-play-mkv-on-android/"><u>MKV playback issues on Xiaomi Redmi Note 12R</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/professionelle-losungen-fur-die-iphone-datensicherung-auf-windows-und-mac-os/"><u>Professionelle Lösungen Für Die iPhone-Datensicherung Auf Windows Und Mac OS</u></a></li>
<li><a href="https://driver-install.techidaily.com/rejuvenate-your-dell-sound-system-via-realtek-software-update/"><u>Rejuvenate Your Dell Sound System via Realtek Software Update</u></a></li>
<li><a href="https://extra-tips.techidaily.com/soons-review-diverse-perspectives/"><u>Soon's Review Diverse Perspectives</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/usb-usbusb/"><u>USBデバイス間で簡単にファイルを複写する方法 - USBから別のUSBへ</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/vaio-windows-10-pc/"><u>VAIO Windows 10 PC バックアップのための最適な手法</u></a></li>
</ul></div>

