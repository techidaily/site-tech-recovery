---
title: How to Easily Uninstall Programs From Windows 11 - A Detailed Walkthrough
date: 2025-01-21T02:38:40.794Z
updated: 2025-01-22T22:56:25.437Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes How to Easily Uninstall Programs From Windows 11 - A Detailed Walkthrough
excerpt: This Article Describes How to Easily Uninstall Programs From Windows 11 - A Detailed Walkthrough
thumbnail: https://thmb.techidaily.com/d9d28999ab80c3fe303824be9f1e02b9cc335e9a7ef77a5fdd8ceeee3dcb3523.jpg
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
<li><a href="https://article-helps.techidaily.com/new-maximizing-your-visuals-the-ultrawide-vs-uhd-4k-debate/"><u>[New] Maximizing Your Visuals The UltraWide vs UHD 4K Debate</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-how-to-remove-youtube-videos/"><u>[Updated] How to Remove YouTube Videos</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-bigo-live-intro-video-details-area-px-format-run/"><u>[Updated] In 2024, Bigo Live Intro Video Details Area (Px²), Format, Run</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/best-free-online-tv-and-movies-netflix-substitutes-you-must-check-out/"><u>Best Free Online TV and Movies: Netflix Substitutes You Must Check Out</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-3-things-you-must-know-about-fake-snapchat-location-on-apple-iphone-13-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, 3 Things You Must Know about Fake Snapchat Location On Apple iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-iphone-11-with-imei-code-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 11 with IMEI Code?</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/quietening-mechanical-disturbance-a-guide-to-repairing-a-noisy-desktop-fan/"><u>Quietening Mechanical Disturbance: A Guide to Repairing a Noisy Desktop Fan</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/top-16-zero-cost-guide-to-mastering-sign-language/"><u>Top 16 Zero-Cost Guide to Mastering Sign Language</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/what-to-watch-now-exclusive-selections-from-shows-airing-on-max-right-this-minute/"><u>What to Watch Now? Exclusive Selections From Shows Airing on MAX Right This Minute</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AcAYRX0cwwA?si=DxqWU39vqksZbe1s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

