---
title: How to Fix Windows 10 Installation Errors Successfully
date: 2025-01-26T18:21:53.132Z
updated: 2025-01-30T16:51:59.263Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes How to Fix Windows 10 Installation Errors Successfully
excerpt: This Article Describes How to Fix Windows 10 Installation Errors Successfully
thumbnail: https://thmb.techidaily.com/db39cf974b891a971b269fa1b5c545ac5598c4412d012bd826ff7f5dff9de440.png
---

## Error Code 80240020 Deciphered: Easy Steps to Successfully Install Windows 10 without a Glitch

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/img_58140207aba43-600x394.jpg)

 Your**Windows Update** panel should come out in a couple of seconds. If it won’t open automatically, you can open this panel from Control Panel manually. Then, you should be able to download your Windows 10 from scratch.

The steps above also work if you are having a**80080080** or **8024600A**  error code. Usually the error is common with Windows 8.1 users, but for those who are using Windows 7, this solution applies as well. If the problem still persists, please be patient, Windows update takes time to download the upgrades in the background. If you still could not get this problem fixed, your Windows update tool might be corrupted so the security settings and background process is now malfunctioned. In this case, it is suggested that you burn the DVD or CD or USB flash drive with Windows 10 ISO files in to do the clean install from scratch. If you want to know how to do it, please refer to[this post here](https://tools.techidaily.com/drivereasy/download/) for more information.

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
<li><a href="https://instagram-videos.techidaily.com/updated-instagram-searching-skills-unlock-additional-free-filters/"><u>[Updated] Instagram Searching Skills – Unlock Additional Free Filters</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-peak-creation-suite-insightful-2023-analysis/"><u>2024 Approved Peak Creation Suite Insightful 2023 Analysis</u></a></li>
<li><a href="https://activate-lock.techidaily.com/a-comprehensive-guide-to-icloud-unlock-on-apple-iphone-6-online-by-drfone-ios/"><u>A Comprehensive Guide to iCloud Unlock On Apple iPhone 6 Online</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/all-you-need-to-know-about-the-new-apple-smartband-pricing-insights-and-forecasted-release-timeline/"><u>All You Need to Know About the New Apple Smartband - Pricing Insights & Forecasted Release Timeline</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/dvd-ripper-for-mac-dvd/"><u>DVD Ripper for Mac: 無料で簡単・安全なDVDコピー - フレックスに作業が可能な最適ソリューションをご提案！</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722899196262-enhance-your-online-presence-blur-your-google-meet-background-today/"><u>Enhance Your Online Presence: Blur Your Google Meet Background Today</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/exploring-the-difference-cat5-versus-cat6-networking-cable-options/"><u>Exploring the Difference: Cat5 Versus Cat6 Networking Cable Options</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-iconic-14-examples-of-animate-texts/"><u>In 2024, Iconic 14 Examples of Animate Texts</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/multi-bluetooth-speaker-sync-a-step-by-step-guide/"><u>Multi-Bluetooth Speaker Sync: A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/solving-iphone-silent-mode-a-step-by-step-guide/"><u>Solving iPhone Silent Mode: A Step-by-Step Guide</u></a></li>
<li><a href="https://some-tips.techidaily.com/top-rated-mp3-audio-devices-expert-reviews/"><u>Top Rated MP3 Audio Devices - Expert Reviews</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

