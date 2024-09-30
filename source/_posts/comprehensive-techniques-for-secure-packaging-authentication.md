---
title: Comprehensive Techniques for Secure Packaging Authentication
date: 2024-09-28T11:35:52.368Z
updated: 2024-09-30T03:50:39.935Z
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

## Build Settings

### Enable ICE validation for Msi packages

Run selected ICE evaluation file at the MSI package build time. If no predefined evaluation files are detected use the \[Browse \] button to locate the evaluation file.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135415/19272" target="_top" id="2135415">
  <img src="//a.impactradius-go.com/display-ad/19272-2135415" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135415/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Enable ICE validation for Merge Module packages

Run selected ICE evaluation file at the Merge Module package build time. If no predefined evaluation files are detected use the \[Browse \] button to locate the evaluation file.

### Enable Advanced Installer best practice rules

Run the [Advanced Installer Best Practice](https://tools.techidaily.com/advancedinstaller/products/) evaluators at build time.

### Enable App-V 5 resource compatibility check

By enabling this option you will get an "Issue List" with resources that don't meet the App-V 5 standards. The compatibility check will be performed at build time and it will include [Drivers](https://tools.techidaily.com/advancedinstaller/products/), [Scheduled tasks](https://tools.techidaily.com/advancedinstaller/products/) and [Firewall settings](https://tools.techidaily.com/advancedinstaller/products/).

### Enable UWP resource compatibility check

Verifies that the package resources and settings are attuned to Universal Windows Platform best practices. The check is performed at build time and all detected compatibility issues are shown in the "Issue List" pane.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137206/26400" target="_top" id="2137206">
  <img src="//a.impactradius-go.com/display-ad/26400-2137206" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137206/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Enable UWP manifest validation

Run the UWP manifest validation at build time.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080328/19272" target="_top" id="2080328">
  <img src="//a.impactradius-go.com/display-ad/19272-2080328" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080328/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Enable validation using WACK

Uses appcert.exe from the [Windows App Certification Kit](https://learn.microsoft.com/en-us/windows/uwp/debug-test-perf/windows-app-certification-kit) to validate an MSI or UWP AppX build. If you build your project via command line, you have to be aware that by enabling WACK, the uninstall process will not be silent. The validation will provide an output log as well as a more user-friendly HTML log. 

To run these validation tests requires you to install Windows SDK.

## Define Rules

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094482/7443" target="_top" id="2094482">
  <img src="//a.impactradius-go.com/display-ad/7443-2094482" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-obs-vs-twitch-studio-which-one-is-better/"><u>[Updated] 2024 Approved OBS Vs Twitch Studio Which One Is Better?</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-spreading-smiles-crafting-visual-jokes-for-fbinstagram-shares/"><u>[Updated] 2024 Approved Spreading Smiles Crafting Visual Jokes for FB/Instagram Shares</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-tracing-treasure-trails-fast-friending-fundamentals/"><u>[Updated] 2024 Approved Tracing Treasure Trails Fast Friending Fundamentals</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-cutting-edge-photo-and-video-enhancement-top-8-editing-apps-for-modern-devices/"><u>[Updated] Cutting-Edge Photo & Video Enhancement Top 8 Editing Apps for Modern Devices</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-orchestrating-a-harmonious-tiktok-finale/"><u>2024 Approved Orchestrating a Harmonious TikTok Finale</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-wirecast-strategies-for-successful-social-media-livestreams/"><u>2024 Approved Wirecast Strategies for Successful Social Media Livestreams</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/argon-power-up-bootstrap-ncreative-tims-free-open-source-dashboard-for-advanced-web-project-management/"><u>Argon: Power Up Bootstrap nCreative Tim's Free Open Source Dashboard for Advanced Web Project Management</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/breaking-news-discover-the-newest-mirillis-announcements-from-their-media-hub/"><u>Breaking News: Discover the Newest Mirillis Announcements From Their Media Hub</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/complimentary-argon-reactnodejs-dashboard-template-integration-with-bootstrap-4-and-reactstrap/"><u>Complimentary Argon React/Node.js Dashboard Template - Integration with Bootstrap 4 & Reactstrap</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/create-your-standout-resume-with-our-complimentary-nextjstailwind-template-from-creativetim/"><u>Create Your Standout Resume with Our Complimentary NextJS/Tailwind Template From CreativeTim</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/creative-tims-impactful-design-system-complimentary-bootstrap-4-integrated-framework/"><u>Creative Tim's Impactful Design System – Complimentary, Bootstrap 4 Integrated Framework</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/discover-mirillis-boutique-shop-online-for-unique-inspired-home-decor/"><u>Discover Mirillis Boutique: Shop Online for Unique, Inspired Home Decor</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/language-differences-in-macau/"><u>Language Differences in Macau</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/mastering-action-sequences-a-comprehensive-guide-to-active-screen-capture-techniques/"><u>Mastering Action Sequences: A Comprehensive Guide to Active Screen Capture Techniques</u></a></li>
<li><a href="https://win-marvelous.techidaily.com/revive-your-aging-pc-with-these-5-time-tested-tricks-for-windows-10-users-many-options-completely-gratis-zdnet-guide/"><u>Revive Your Aging PC with These 5 Time-Tested Tricks for Windows 10 Users - Many Options Completely Gratis! [ZDNet Guide]</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/top-rated-freecorder-clones-get-them-for-free-on-your-pc-or-mac/"><u>Top-Rated Freecorder Clones: Get Them for Free on Your PC or MAC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/xmedia-recode/"><u>XMedia Recodeでビデオアスペクト比を変更するシンプル方法 - チュートリアル</u></a></li>
</ul></div>

