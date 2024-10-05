---
title: Comprehensive Techniques for Secure Packaging Authentication
date: 2024-10-01T20:29:41.933Z
updated: 2024-10-05T17:13:17.470Z
tags:
  - user-guide
categories:
  - advancedinstaller
description: This Article Describes Comprehensive Techniques for Secure Packaging Authentication
thumbnail: https://thmb.techidaily.com/f7aa9f91ee25ba92e513ec309ccac0797742d37b71585737d9811b8df3523624.jpg
---

## Comprehensive Techniques for Secure Packaging Authentication

Table of Contents

* [Introduction](https://tools.techidaily.com/advancedinstaller/products/)
* [Registration](https://tools.techidaily.com/advancedinstaller/products/)
* [Using Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [GUI](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Working with Projects](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Start Page](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Save As Template Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Project Options Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
         * [External Tools](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Validation](https://tools.techidaily.com/advancedinstaller/products/)  
         * [SCCM Configurations](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Auto Import](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Repository Manager](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Edit Solution Options](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Installer Project](https://tools.techidaily.com/advancedinstaller/products/)  
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

## Package Validation

The validation tool checks your project for compliance with each of the internal consistency evaluators (ICEs). The files containing these ICEs are those installed with the MsiVal2.msi tool (part of the Microsoft Windows Installer Platform SDK) to validate the installation and merge module packages for Windows logo compliance. Advanced Installer will not install those files by default, it will automatically detect them if they are installed. However if the MsiVal2.msi tool is not installed but present on your computer Advanced Installer will automatically prompt you to install it. If this tool is not present on your computer you need to manually browse for the ICE files. The predefined Microsoft ICE evaluation files detected by Advanced Installer are:

* **Full MSI Validation Suite** \- Runs darice.cub, it performs up to 99 checks to ensure that the installation databases are internally consistent.
* **Merge Module Validation Suite** \- Runs mergemod.cub, used to test the internal consistency of merge modules.
* **Windows XP Logo Program Suite** \- Runs XPlogo.cub, which is part of Microsoft Windows XP logo verification program. The tests in XPlogo.cub are a subset of the tests in darice.cub.
* **Windows Vista Logo Program Suite** \- Runs Vstalogo.cub, which is part of Microsoft Windows Vista logo verification program. The tests in Vstalogo.cub are a subset of the tests in darice.cub.

![Tools Dialog](https://cdn.advancedinstaller.com/img/dialog/package-validation.png "Tools Dialog")  

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)To benefit from the newly internal consistency evaluators it is recommended to have installed the newest MsiVal2.msi tool.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134494/18498" target="_top" id="2134494">
  <img src="//a.impactradius-go.com/display-ad/18498-2134494" border="0" alt="https://techidaily.com" width="721" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134494/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Build Settings

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118326/7443" target="_top" id="2118326">
  <img src="//a.impactradius-go.com/display-ad/7443-2118326" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118326/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Enable ICE validation for Msi packages

Run selected ICE evaluation file at the MSI package build time. If no predefined evaluation files are detected use the \[Browse \] button to locate the evaluation file.

### Enable ICE validation for Merge Module packages

Run selected ICE evaluation file at the Merge Module package build time. If no predefined evaluation files are detected use the \[Browse \] button to locate the evaluation file.

### Enable Advanced Installer best practice rules

Run the [Advanced Installer Best Practice](https://tools.techidaily.com/advancedinstaller/products/) evaluators at build time.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886019/19272" target="_top" id="1886019">
  <img src="//a.impactradius-go.com/display-ad/19272-1886019" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886019/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Enable App-V 5 resource compatibility check

By enabling this option you will get an "Issue List" with resources that don't meet the App-V 5 standards. The compatibility check will be performed at build time and it will include [Drivers](https://tools.techidaily.com/advancedinstaller/products/), [Scheduled tasks](https://tools.techidaily.com/advancedinstaller/products/) and [Firewall settings](https://tools.techidaily.com/advancedinstaller/products/).

### Enable UWP resource compatibility check

Verifies that the package resources and settings are attuned to Universal Windows Platform best practices. The check is performed at build time and all detected compatibility issues are shown in the "Issue List" pane.

### Enable UWP manifest validation

Run the UWP manifest validation at build time.

### Enable validation using WACK

Uses appcert.exe from the [Windows App Certification Kit](https://learn.microsoft.com/en-us/windows/uwp/debug-test-perf/windows-app-certification-kit) to validate an MSI or UWP AppX build. If you build your project via command line, you have to be aware that by enabling WACK, the uninstall process will not be silent. The validation will provide an output log as well as a more user-friendly HTML log. 

To run these validation tests requires you to install Windows SDK.

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2141676/17091" target="_top" id="2141676">
  <img src="//a.impactradius-go.com/display-ad/17091-2141676" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettieu.pxf.io/i/5597632/2141676/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Define Rules

### Suppress Warning messages.

No validation warnings will be displayed to the user.

### Suppress specific ICEs.

The ICEs you specify separated by ";" character will not run.

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)The validation result is displayed as information in the build log and will not affect the build result. After the build operation is finished the validation result is displayed in the **Issue Pane** list allowing user to locate the problem in Advanced Installer UI (if possible).

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
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-unlock-content-potential-with-the-right-vimeo-membership-choice/"><u>[Updated] 2024 Approved Unlock Content Potential with the Right Vimeo Membership Choice</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-streamlining-your-approach-to-youtube-community-dialogue/"><u>2024 Approved Streamlining Your Approach to YouTube Community Dialogue</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/begin-your-journey-with-iini-entry-point/"><u>Begin Your Journey with Iini Entry Point</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/boost-user-conversations-strategies-for-adding-dynamic-dialogue-features/"><u>Boost User Conversations: Strategies for Adding Dynamic Dialogue Features</u></a></li>
<li><a href="https://activate-lock.techidaily.com/icloud-unlocker-download-unlock-icloud-lock-for-your-apple-iphone-se-by-drfone-ios/"><u>iCloud Unlocker Download Unlock iCloud Lock for your Apple iPhone SE</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-essential-techniques-for-saving-mobile-gameplay/"><u>In 2024, Essential Techniques for Saving Mobile Gameplay</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/instantaneous-strategies-for-silencing-auditory-ground-hum/"><u>Instantaneous Strategies for Silencing Auditory Ground Hum</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/mastering-screen-captures-a-step-by-step-guide-to-taking-screenshots-in-windows-10/"><u>Mastering Screen Captures: A Step-by-Step Guide to Taking Screenshots in Windows 10</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/merge-several-pdf-documents-on-pc-or-mac-with-simple-methods/"><u>Merge Several PDF Documents on PC or Mac with Simple Methods</u></a></li>
<li><a href="https://extra-skills.techidaily.com/next-gen-thrills-with-intova-x-action-tech-for-2024/"><u>Next-Gen Thrills with Intova X Action Tech for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-contacts-from-blaze-pro-5g-by-fonelab-android-recover-contacts/"><u>Possible solutions to restore deleted contacts from Blaze Pro 5G.</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-8-most-popular-book-apps-to-enhance-your-reading-experience/"><u>The 8 Most Popular Book Apps to Enhance Your Reading Experience</u></a></li>
<li><a href="https://screen-capture.techidaily.com/the-ultimate-macos-experience-with-screenflow-reviewed/"><u>The Ultimate MacOS Experience with ScreenFlow Reviewed</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/top-7-leading-computer-diagnostic-tools-preferred-by-it-professionals/"><u>Top 7 Leading Computer Diagnostic Tools Preferred by IT Professionals</u></a></li>
</ul></div>

