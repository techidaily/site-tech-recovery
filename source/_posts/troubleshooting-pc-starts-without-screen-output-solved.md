---
title: "Troubleshooting: PC Starts without Screen Output – Solved"
date: 2025-01-23T22:07:38.711Z
updated: 2025-01-30T18:20:35.269Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Troubleshooting: PC Starts without Screen Output – Solved"
excerpt: "This Article Describes Troubleshooting: PC Starts without Screen Output – Solved"
thumbnail: https://thmb.techidaily.com/a3825c53acb734eda563e5e8193fa7e586da129de2b915844ef28bdfbf11f7f0.jpg
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
<li><a href="https://fox-links.techidaily.com/updated-in-2024-direct-connectivity-ios-and-android-file-relay/"><u>[Updated] In 2024, Direct Connectivity IOS & Android File Relay</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-unmatched-visuals-leading-ps5-compatible-hdmi-21-monitors/"><u>[Updated] Unmatched Visuals Leading PS5 Compatible HDMI 2.1 Monitors</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/all-about-the-new-samsung-galaxy-watch-n-find-out-when-it-hits-shelves-and-what-to-expect/"><u>All About the New Samsung Galaxy Watch N - Find Out When It Hits Shelves and What to Expect!</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/comprehensive-guide-recovering-or-locating-missing-launchdll-files-on-your-pc/"><u>Comprehensive Guide: Recovering or Locating Missing Launch.dll Files on Your PC</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722898330498-discover-exceptional-bargains-on-apple-watch-models-aprils-finest-offers-revealed/"><u>Discover Exceptional Bargains on Apple Watch Models - April's Finest Offers Revealed</u></a></li>
<li><a href="https://article-files.techidaily.com/in-2024-top-10-ios-devices-best-video-players-unveiled/"><u>In 2024, Top 10 iOS Devices' Best Video Players Unveiled</u></a></li>
<li><a href="https://android-frp.techidaily.com/reviving-legacy-systems-boost-your-setup-by-mounting-contemporary-gpus-onto-classic-agp-slots-with-top-mod-adapters/"><u>Reviving Legacy Systems: Boost Your Setup by Mounting Contemporary GPUs Onto Classic AGP Slots with Top Mod Adapters</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-fixes-for-persistent-bluetooth-compatibility-challenges-on-windows-10/"><u>Ultimate Fixes for Persistent Bluetooth Compatibility Challenges on Windows 10</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/why-is-my-playstation-4-controller-showing-a-spectrum-of-blue-white-red-or-orange-lights/"><u>Why Is My PlayStation 4 Controller Showing a Spectrum of Blue, White, Red, or Orange Lights?</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-infinix-note-30-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Live Location is Not Updating and How to Fix on your Infinix Note 30 | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

