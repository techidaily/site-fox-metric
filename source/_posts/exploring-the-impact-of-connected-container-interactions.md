---
title: Exploring the Impact of Connected Container Interactions
date: 2024-10-04T17:43:34.486Z
updated: 2024-10-10T18:09:52.705Z
tags:
  - user-guide
categories:
  - advancedinstaller
description: This Article Describes Exploring the Impact of Connected Container Interactions
thumbnail: https://thmb.techidaily.com/c476c76efa4305c4184325fe1ddf82b7177bf5ea101e0b8dd34c17b0c21488b1.jpg
---

## Exploring the Impact of Connected Container Interactions

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
         * [Requirements](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Prerequisites](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Predefined Prerequisites](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Prerequisite Installation Tab](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Prerequisite Files Tab](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Prerequisite Conditions Tab](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Chained Package Behavior](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Edit PseudoFormatted Type Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Windows Features](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Windows Server Roles](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Specify Builds Tab](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Launch Conditions](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Merge Modules](https://tools.techidaily.com/advancedinstaller/products/)  
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

## Chained Package Behavior

A chained package can either be skipped or run as part of the main setup in the following modes:

* install
* uninstall
* maintenance

The chained package conditions are evaluated for install first, then for uninstall. Both conditions are evaluated in this order when the parent setup runs in install, uninstall and maintenance modes.

When these condition fields are left empty, then the chained package will run in the same mode as its parent setup. 

A chained package's run mode depends on three factors:

* parent setup run mode
* install condition
* uninstall condition

The following tables combine these three factors to clarify how the CP (chained package) will behave:

![Tip](https://cdn.advancedinstaller.com/svg/common/IconMessageTip.svg)To read the table start from the top left cell then choose a column and a row based on how the conditions you have set in the [Chained Packages](https://tools.techidaily.com/advancedinstaller/products/) get resolved.

| **When the parent package is installed and** | **CP install condition resolves to TRUE** | **CP install condition resolves to FALSE** | **CP install condition field is EMPTY** |
| -------------------------------------------- | ----------------------------------------- | ------------------------------------------ | --------------------------------------- |
| **CP uninstall condition resolves to TRUE**  | \=> CP will be installed                  | \=> CP will be uninstalled                 | \=> CP will be installed                |
| **CP uninstall condition resolves to FALSE** | \=> CP will be installed                  | \=> CP will be skipped                     | \=> CP will be installed                |
| **CP uninstall condition field is EMPTY**    | \=> CP will be installed                  | \=> CP will be skipped                     | \=> CP will be installed                |

| **When the parent package is uninstalled and** | **CP install condition resolves to TRUE** | **CP install condition resolves to FALSE** | **CP install condition field is EMPTY** |
| ---------------------------------------------- | ----------------------------------------- | ------------------------------------------ | --------------------------------------- |
| **CP uninstall condition resolves to TRUE**    | \=> CP will be installed                  | \=> CP will be uninstalled                 | \=> CP will be uninstalled              |
| **CP uninstall condition resolves to FALSE**   | \=> CP will be installed                  | \=> CP will be skipped                     | \=> CP will be skipped                  |
| **CP uninstall condition field is EMPTY**      | \=> CP will be installed                  | \=> CP will be uninstalled                 | \=> CP will be uninstalled              |

| **When the parent package runs in maintenance mode and** | **CP install condition resolves to TRUE** | **CP install condition resolves to FALSE** | **CP install condition field is EMPTY** |
| -------------------------------------------------------- | ----------------------------------------- | ------------------------------------------ | --------------------------------------- |
| **CP uninstall condition resolves to TRUE**              | \=> CP will be installed                  | \=> CP will be uninstalled                 | \=> CP will be uninstalled              |
| **CP uninstall condition resolves to FALSE**             | \=> CP will be installed                  | \=> CP will run in maintenance mode        | \=> CP will run in maintenance mode     |
| **CP uninstall condition field is EMPTY**                | \=> CP will be installed                  | \=> CP will run in maintenance mode        | \=> CP will run in maintenance mode     |

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
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-essential-tips-for-youtube-thumbnail-design/"><u>[Updated] 2024 Approved Essential Tips for YouTube Thumbnail Design</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-free-video-trimming-tutorial-with-vimeo-features-for-2024/"><u>[Updated] Free Video Trimming Tutorial with Vimeo Features for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-highlight-your-pc-gaming-6-effective-screen-methods/"><u>[Updated] Highlight Your PC Gaming 6 Effective Screen Methods</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-in-2024-premier-script-development-arena/"><u>[Updated] In 2024, Premier Script Development Arena</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/9-essential-iphone-x-hacks-for-every-user-for-2024/"><u>9 Essential iPhone X Hacks for Every User for 2024</u></a></li>
<li><a href="https://fox-metric.techidaily.com/designing-winning-youtube-banners-that-captivate-and-expand-your-audience-base/"><u>Designing Winning YouTube Banners That Captivate and Expand Your Audience Base</u></a></li>
<li><a href="https://fox-metric.techidaily.com/exploring-the-world-of-icom-type-libraries-the-ultimate-resource-optimization-toolkit/"><u>Exploring the World of ICOM Type Libraries: The Ultimate Resource Optimization Toolkit</u></a></li>
<li><a href="https://fox-metric.techidaily.com/how-to-seamlessly-transform-your-pdf-documents-into-tiff-images-expert-strategies-and-tools/"><u>How to Seamlessly Transform Your PDF Documents Into TIFF Images: Expert Strategies and Tools</u></a></li>
<li><a href="https://fox-metric.techidaily.com/mastering-element-query-in-xaml/"><u>Mastering Element Query in XAML</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/unlock-iphone-15-plus-with-forgotten-passcode-different-methods-you-can-try-drfone-by-drfone-ios/"><u>Unlock iPhone 15 Plus With Forgotten Passcode Different Methods You Can Try | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049387/7443" target="_top" id="2049387">
  <img src="//a.impactradius-go.com/display-ad/7443-2049387" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049387/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

