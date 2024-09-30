---
title: Exploring the Impact of Connected Container Interactions
date: 2024-09-26T20:22:48.920Z
updated: 2024-09-30T03:19:13.436Z
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
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-mastering-the-art-of-instagram-metrics-analysis-your-ultimate-ig-guide/"><u>[New] In 2024, Mastering the Art of Instagram Metrics Analysis – Your Ultimate IG Guide</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-2024-approved-top-metaverse-content-creators-and-their-hilarity/"><u>[Updated] 2024 Approved Top Metaverse Content Creators & Their Hilarity</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-breaking-down-8-common-blunders-in-early-stage-youtube-success-for-2024/"><u>[Updated] Breaking Down 8 Common Blunders in Early-Stage YouTube Success for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-investigating-competitors-to-manycam-better-choices-in-2024/"><u>[Updated] Investigating Competitors to ManyCam Better Choices, In 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-perfect-flying-companions-the-top-kids-drones/"><u>[Updated] Perfect Flying Companions The Top Kids' Drones</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/8-free-video-conferencing-software-for-windows-and-mac-for-2024/"><u>8 Free Video Conferencing Software for Windows and Mac for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/essential-guide-to-creating-stunning-timelapses-using-gopro-software/"><u>Essential Guide to Creating Stunning Timelapses Using GoPro Software</u></a></li>
<li><a href="https://fox-metric.techidaily.com/get-started-with-zero-cost-professional-attire-pages-template-collection-for-digital-creatives-on-flipbuilder/"><u>Get Started with Zero Cost: Professional Attire Pages Template Collection for Digital Creatives on FlipBuilder</u></a></li>
<li><a href="https://fox-metric.techidaily.com/how-to-transform-your-office-documents-into-an-interactive-ebook-with-toc-using-flipbuilder/"><u>How to Transform Your Office Documents Into an Interactive eBook with TOC Using FlipBuilder</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-10-best-video-calling-app-for-android-and-iphone/"><u>In 2024, 10 Best Video Calling App for Android and iPhone</u></a></li>
<li><a href="https://fox-metric.techidaily.com/is-it-possible-to-change-help-window-sizes-at-flipbuildercom/"><u>Is It Possible To Change Help Window Sizes at FlipBuilder.com?</u></a></li>
<li><a href="https://fox-metric.techidaily.com/mastering-content-creation-with-flip-writers-expert-knowledge-hub-dive-into-flipbuildercom-resources/"><u>Mastering Content Creation with Flip Writer's Expert Knowledge Hub - Dive Into FlipBuilder.com Resources</u></a></li>
<li><a href="https://fox-metric.techidaily.com/optimize-for-speed-effective-techniques-for-reducing-page-flip-latency-on-flipbuilder/"><u>Optimize for Speed: Effective Techniques for Reducing Page-Flip Latency on FlipBuilder</u></a></li>
<li><a href="https://fox-metric.techidaily.com/preserve-your-design-templates-easily-with-flipcreator-a-comprehensive-tutorial/"><u>Preserve Your Design Templates Easily with FlipCreator: A Comprehensive Tutorial</u></a></li>
<li><a href="https://fox-metric.techidaily.com/professional-free-online-tool-batch-transform-multiple-images-into-high-quality-pdf-documents/"><u>Professional Free Online Tool: Batch Transform Multiple Images Into High-Quality PDF Documents</u></a></li>
<li><a href="https://fox-metric.techidaily.com/requesting-a-purchase-invoice-on-flipbuilder-how-can-i-obtain-it/"><u>Requesting a Purchase Invoice on FlipBuilder - How Can I Obtain It?</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-process-transferring-your-data-and-installing-windows-11-onto-a-new-drive/"><u>Step-by-Step Process: Transferring Your Data and Installing Windows 11 Onto a New Drive</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/top-strategies-for-capturing-lol-matches/"><u>Top Strategies for Capturing LOL Matches</u></a></li>
<li><a href="https://fox-metric.techidaily.com/transforming-word-files-into-interactive-flipbooks-with-flipbuilders-tutorial/"><u>Transforming Word Files Into Interactive Flipbooks with FlipBuilder's Tutorial</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151888/7443" target="_top" id="2151888">
  <img src="//a.impactradius-go.com/display-ad/7443-2151888" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151888/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

