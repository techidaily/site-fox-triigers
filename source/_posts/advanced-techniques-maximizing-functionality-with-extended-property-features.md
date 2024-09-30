---
title: "Advanced Techniques: Maximizing Functionality with Extended Property Features"
date: 2024-09-25T22:01:25.616Z
updated: 2024-09-30T08:06:12.276Z
tags:
  - user-guide
categories:
  - advancedinstaller
description: "This Article Describes Advanced Techniques: Maximizing Functionality with Extended Property Features"
thumbnail: https://thmb.techidaily.com/14598feaeb4d0e61d08a761998cd6976c067dba5c944d538d367654e5b9adad2.jpg
---

## Advanced Techniques: Maximizing Functionality with Extended Property Features

Table of Contents

* [Introduction](https://tools.techidaily.com/advancedinstaller/products/)
* [Registration](https://tools.techidaily.com/advancedinstaller/products/)
* [Using Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [GUI](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Working with Projects](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Installer Project](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Product Information](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Resources](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Files and Folders](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Tiles](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Java Products](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Registry](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [File Associations](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Default Programs](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Context Menu Properties](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [ProgID Properties](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Extension Properties](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Verb Properties](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Assemblies](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Drivers](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Services](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Package Definition](https://tools.techidaily.com/advancedinstaller/products/)  
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

## Extension Properties

## General

### Command

Points the path of the program associated with the extension. You can change the program by using the \[Browse... \] button to select another one from the project. 

### MIME type

Defines the content type of the files with the selected extension. This content type will be used by the browsers to select an application to handle a downloaded file. Leave this field empty if you do not want to register a MIME type for the files with the current extension. 

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)Consult the IANA registry online for a list of assigned MIME Media Types.

![Warning!](https://cdn.advancedinstaller.com/svg/common/IconMessageWarning.svg)During installation of a MIME type Windows Installer registers the MIME type under the Internet Explorer MIME Database too ("HKEY\_CLASSES\_ROOT\\MIME\\Database\\Content Type" registry key). Considering the method how [Internet Explorer handles MIME Types](https://learn.microsoft.com/en-us/previous-versions/windows/internet-explorer/ie-developer/platform-apis/ms775148%28v=vs.85%29?redirectedfrom=MSDN), it is not recommend to register the "application/octet-stream" MIME type with your application extension. This is because after registering the "application/octet-stream" MIME type with your application extension, Internet Explorer could associate all downloaded files of "application/octet-stream" MIME type with your application extension.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105877/7443" target="_top" id="2105877">
  <img src="//a.impactradius-go.com/display-ad/7443-2105877" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105877/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Feature

The feature which controls the extension installation. If this feature is not installed, the file associations is not made.

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)This combo box shows only features which contains the extension component.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886019/19272" target="_top" id="1886019">
  <img src="//a.impactradius-go.com/display-ad/19272-1886019" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886019/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Place extension in a separate feature

When enabling this option a special feature is created for the current extension. Through this feature the extension installation can be controlled.

## Installation Behavior

This group allows you to specify when the extension feature is installed:

* _Installed by default_ \- installs the extension feature by default
* _Not installed by default_ \- the extension feature is not installed by default, but the user can still select it for installation through "SetupTypeDlg" dialog
* _Install based on custom condition_ \- installs the extension feature only if the specified condition is true

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027190/19272" target="_top" id="2027190">
  <img src="//a.impactradius-go.com/display-ad/19272-2027190" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027190/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Show in FileAssociationsDlg dialog

Enabling this option will automatically create for the extension a checkbox on "FileAssociationsDlg" [predefined dialog](https://tools.techidaily.com/advancedinstaller/products/). It will also add the required control events so the checkbox controls the extension feature installation.

![Caution!](https://cdn.advancedinstaller.com/svg/common/IconMessageWarning.svg)Only one extension should be associated with each ProgID.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/2139563/4704" target="_top" id="2139563">
  <img src="//a.impactradius-go.com/display-ad/4704-2139563" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139563/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://article-files.techidaily.com/new-2024-approved-viral-visibility-guiding-you-to-100kplus-views-on-youtube/"><u>[New] 2024 Approved Viral Visibility Guiding You to 100K+ Views on YouTube</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-seamless-manipulation-of-iphone-magnification/"><u>[Updated] Seamless Manipulation of iPhone Magnification</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/download-oracle-e-learning-content-access-video-tutorials-and-online-courses/"><u>Download Oracle E-Learning Content: Access Video Tutorials & Online Courses</u></a></li>
<li><a href="https://win-answers.techidaily.com/easy-fix-outriders-keeps-crashing/"><u>Easy Fix: Outriders Keeps Crashing</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/easy-tutorial-saving-huffpost-videos-as-mp4avi-files-on-windows-and-macos-systems/"><u>Easy Tutorial: Saving HuffPost Videos as MP4/AVI Files on Windows and macOS Systems</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/easy-to-use-3sat-downloader-for-hd-videos-download-in-popular-formats-such-as-flv-mov-avi/"><u>Easy-to-Use 3Sat Downloader for HD Videos: Download in Popular Formats Such as FLV, MOV, AVI</u></a></li>
<li><a href="https://fox-http.techidaily.com/elevating-care-delivery-through-effective-fb-ads/"><u>Elevating Care Delivery Through Effective FB Ads</u></a></li>
<li><a href="https://win-able.techidaily.com/experience-epic-battles-with-god-of-war-first-person-shooter-for-windows-and-pc-gamers/"><u>Experience Epic Battles with God of War First-Person Shooter for Windows and PC Gamers</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/free-abc-iview-streaming-securely-download-tv-shows-and-radios-from-abc-australia-online/"><u>Free ABC iView Streaming: Securely Download TV Shows and Radios From ABC Australia Online</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/free-guide-downloading-daily-motion-movies-without-internet-access/"><u>Free Guide: Downloading Daily Motion Movies Without Internet Access</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/gaana-songs-download-in-multiple-formats-mp3-flac-aac-for-pc-and-mac/"><u>Gaana Songs Download in Multiple Formats (MP3, FLAC, AAC) for PC & Mac</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/guide-converting-and-downloading-oreilly-video-lessons-for-offline-viewing-in-mp4-format/"><u>Guide: Converting and Downloading O'Reilly Video Lessons for Offline Viewing in MP4 Format</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/guide-converting-elephant-drive-educational-content-into-mp4-format-for-pc-and-mac/"><u>Guide: Converting Elephant Drive Educational Content Into MP4 Format for PC & MAC</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-ways-to-track-samsung-galaxy-m54-5g-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Track Samsung Galaxy M54 5G without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://driver-download.techidaily.com/ready-to-go-printer-support-secure-your-epson-perfection-v500-driver-now/"><u>Ready-to-Go Printer Support: Secure Your Epson Perfection V500 Driver Now</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-upgrades-with-windows-11-in-place-protocols/"><u>Streamlining Upgrades with Windows 11 In-Place Protocols</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/the-art-of-audio-in-a-virtual-world-your-ultimate-zoom-recording-tutorial-for-2024/"><u>The Art of Audio in a Virtual World Your Ultimate Zoom Recording Tutorial for 2024</u></a></li>
</ul></div>

