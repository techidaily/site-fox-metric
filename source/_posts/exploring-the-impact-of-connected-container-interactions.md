---
title: Exploring the Impact of Connected Container Interactions
date: 2024-09-29T17:27:16.399Z
updated: 2024-10-05T16:41:58.406Z
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
<li><a href="https://facebook-video-recording.techidaily.com/new-fix-facebook-videos-not-playing-on-androidiphonechrome/"><u>[New] Fix Facebook Videos Not Playing on Android/iPhone/Chrome</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-audio-alchemy-transforming-instagram-videos-with-sound/"><u>[Updated] In 2024, Audio Alchemy Transforming Instagram Videos with Sound</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-the-rising-riches-of-a-kid-star-ryans-income-insights/"><u>[Updated] In 2024, The Rising Riches of a Kid Star Ryan's Income Insights</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/6-proven-ways-to-unlock-realme-12plus-5g-phone-when-you-forget-the-password-by-drfone-android/"><u>6 Proven Ways to Unlock Realme 12+ 5G Phone When You Forget the Password</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/best-digital-reading-devices-of-2021-ipad-kindle-and-nook-battle/"><u>Best Digital Reading Devices of 2021: IPad, Kindle, and Nook Battle</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/decoding-innovation-understanding-meta-ai-capabilities/"><u>Decoding Innovation: Understanding Meta AI Capabilities</u></a></li>
<li><a href="https://fox-metric.techidaily.com/easy-methods-to-take-screenshots-on-acer-tablets-and-laptops-comprehensive-guide/"><u>Easy Methods to Take Screenshots on Acer Tablets & Laptops - Comprehensive Guide</u></a></li>
<li><a href="https://fox-metric.techidaily.com/effective-use-of-element-attributes-in-xml-tips-and-tricks-for-navigating-the-attribute-settings-tab/"><u>Effective Use of Element Attributes in XML - Tips and Tricks for Navigating the Attribute Settings Tab</u></a></li>
<li><a href="https://fox-metric.techidaily.com/effortless-navigation-tips-navigating-through-the-keyboard-shortcut-window/"><u>Effortless Navigation Tips: Navigating Through the Keyboard Shortcut Window</u></a></li>
<li><a href="https://fox-metric.techidaily.com/enhancing-hyperlink-management-mastering-the-edit-link-dialog/"><u>Enhancing Hyperlink Management: Mastering the Edit Link Dialog</u></a></li>
<li><a href="https://fox-metric.techidaily.com/how-to-navigate-and-utilize-the-registration-tab-effectively/"><u>How to Navigate and Utilize the Registration Tab Effectively</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532">
  <img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

