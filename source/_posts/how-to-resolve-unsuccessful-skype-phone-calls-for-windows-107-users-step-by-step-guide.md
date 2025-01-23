---
title: "How to Resolve Unsuccessful Skype Phone Calls for Windows 10/7 Users: Step-by-Step Guide"
date: 2025-01-16T16:25:53.649Z
updated: 2025-01-23T02:54:48.360Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes How to Resolve Unsuccessful Skype Phone Calls for Windows 10/7 Users: Step-by-Step Guide"
excerpt: "This Article Describes How to Resolve Unsuccessful Skype Phone Calls for Windows 10/7 Users: Step-by-Step Guide"
thumbnail: https://thmb.techidaily.com/b40abdafc85906cdf8c505af7da6e2b6de5b2e3882be4cc44ae2eb5b5e3f9c4a.jpg
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
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-crafting-captivating-youtube-thumbnails-on-smartphones/"><u>[New] In 2024, Crafting Captivating YouTube Thumbnails on Smartphones</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-navigating-the-best-online-tools-for-vhs-photo-upgrading/"><u>[New] Navigating the Best Online Tools for VHS Photo Upgrading</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unveiling-the-ultimate-iphone-selfie-sticks-8/"><u>[Updated] Unveiling the Ultimate IPhone Selfie Sticks (#8)</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpt-alert-6-cyber-threats-to-consider/"><u>ChatGPT Alert: 6 Cyber Threats to Consider</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/find-true-companions-these-5-must-have-apps-make-friendship-simple/"><u>Find True Companions: These 5 Must-Have Apps Make Friendship Simple</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-essential-steps-for-adding-videos-to-your-instagram-story/"><u>In 2024, Essential Steps for Adding Videos to Your Instagram Story</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-infinix-note-30-vip-racing-edition-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Infinix Note 30 VIP Racing Edition to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-basics-of-biometric-identification-an-insightful-overview/"><u>The Basics of Biometric Identification: An Insightful Overview</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-fix-for-when-your-system-cant-find-btballoondll/"><u>The Ultimate Fix for When Your System Can’t Find BTBalloon.DLL</u></a></li>
<li><a href="https://win11.techidaily.com/thrilling-new-functionality-awaits-with-w11-update-22h2/"><u>Thrilling New Functionality Awaits with W11 Update #22H2</u></a></li>
<li><a href="https://win-tutorials.techidaily.com/ubersetzen-von-daten-vom-desktop-zu-ihrem-ios-gerat-alternative-strategien-ohne-apple-music/"><u>Übersetzen Von Daten Vom Desktop Zu Ihrem iOS-Gerät - Alternative Strategien Ohne Apple Music</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/x-security-made-simple-changing-your-old-twitter-passcode-effectively/"><u>X Security Made Simple: Changing Your Old Twitter Passcode Effectively</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2Iv3DjT2Fyw?si=pR_z8ZDDVGF2MvKJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

