---
title: "Troubleshooting Guide: How to Fix SSL/TLS Handshake Errors on Windows"
date: 2025-01-18T22:53:53.940Z
updated: 2025-01-22T16:36:51.559Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Troubleshooting Guide: How to Fix SSL/TLS Handshake Errors on Windows"
excerpt: "This Article Describes Troubleshooting Guide: How to Fix SSL/TLS Handshake Errors on Windows"
thumbnail: https://thmb.techidaily.com/1417e9674a479dcdfdd7fe1ffab0e26b723730f6b6eee67595d026f30ea77ba0.jpg
---

## Error Code 80240020: Comprehensive Troubleshooting Steps for Windows 10 Installation Issues Resolved

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
<li><a href="https://some-techniques.techidaily.com/new-exploring-the-best-ultimate-guide-to-premium-unboxing-youtubers-2024/"><u>[New] Exploring the Best Ultimate Guide to Premium Unboxing YouTubers, 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-file-transportation-hacks-efficient-ways-to-upload-on-pc/"><u>[New] File Transportation Hacks Efficient Ways to Upload on PC</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-in-2024-instantaneous-windows-photo-explorer/"><u>[New] In 2024, Instantaneous Windows Photo Explorer</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-expertise-for-changing-meet-usernames-laptopmobile/"><u>[Updated] 2024 Approved Expertise for Changing Meet Usernames (Laptop/Mobile)</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-picperfect-pro-enhance-your-mobile-images-for-free/"><u>[Updated] In 2024, PicPerfect Pro Enhance Your Mobile Images for Free</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-tactical-co-creation-youtube-and-brand-joint-efforts/"><u>2024 Approved Tactical Co-Creation YouTube and Brand Joint Efforts</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/an-in-depth-look-at-the-operating-principles-of-electric-cycles/"><u>An In-Depth Look at the Operating Principles of Electric Cycles</u></a></li>
<li><a href="https://extra-resources.techidaily.com/audiovisual-harmony-incorporating-audio-into-powerpoint-presentations-for-2024/"><u>Audiovisual Harmony Incorporating Audio Into PowerPoint Presentations for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/enhancing-icloud-email-security-with-dual-stage-verification/"><u>Enhancing iCloud Email Security with Dual-Stage Verification</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/exploring-every-aspect-of-netflixs-online-viewing-experience/"><u>Exploring Every Aspect of Netflix's Online Viewing Experience</u></a></li>
<li><a href="https://youtube-help.techidaily.com/finding-the-perfect-phrases-for-gamers-videos-for-2024/"><u>Finding the Perfect Phrases for Gamers' Videos for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/gamers-favorite-iphones-of-2023-top-picks-for-enthusiastic-players/"><u>Gamers' Favorite iPhones of 2023 – Top Picks for Enthusiastic Players</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-pair-meta-oculus-quest-2-to-a-phone/"><u>How to Pair Meta (Oculus) Quest 2 to a Phone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/insider-info-on-the-upcoming-google-pixel-fold-2-anticipated-cost-and-launch-timeline/"><u>Insider Info on the Upcoming Google Pixel Fold 2 - Anticipated Cost & Launch Timeline</u></a></li>
<li><a href="https://buynow-info.techidaily.com/power-up-your-devices-with-aukeys-sleek-usb-3and-hub-review/"><u>Power Up Your Devices with Aukey's Sleek USB 3.([&] Hub Review)</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-essential-guide-to-choosing-among-our-favorite-gratis-uninstallers-top-15/"><u>The Essential Guide to Choosing Among Our Favorite Gratis Uninstallers (Top 15)</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S0b9szh8vEk?si=NlGzpJ6MN_SJNk5A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

