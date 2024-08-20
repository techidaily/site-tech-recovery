---
title: Windows Update 0X80070422 Error on Windows 10 [Solved]
date: 2024-08-19T12:48:10.844Z
updated: 2024-08-20T12:48:10.844Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes Windows Update 0X80070422 Error on Windows 10 [Solved]
excerpt: This Article Describes Windows Update 0X80070422 Error on Windows 10 [Solved]
thumbnail: https://thmb.techidaily.com/71b29e512538a1ca57df111d49f95a750cd58f363eb8989d8b988649bee9d94b.jpg
---

## Resolving Windows 10 Installation Issue - Fix Error Code 80 #

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
<li><a href="https://youtube-lab.techidaily.com/024-approved-perfect-your-strategy-top-rated-techniques-for-video-marketing/"><u>[New] 2024 Approved  Perfect Your Strategy  Top-Rated Techniques for Video Marketing</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-ultimate-screen-recorder-unmatched-pcmacos-quality/"><u>[New] 2024 Approved  Ultimate Screen Recorder - Unmatched PC/macOS Quality</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-how-to-make-a-3d-text-effect-in-photoshop/"><u>[New] How to Make a 3D Text Effect in Photoshop</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-powerdirector-app-2024-in-depth-review-and-step-by-step-guide/"><u>[New] PowerDirector App 2024  In-Depth Review & Step-by-Step Guide</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-investigating-best-fps-for-outstanding-slow-motion-cinematography/"><u>[Updated] 2024 Approved  Investigating Best FPS for Outstanding Slow-Motion Cinematography</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-navigating-the-nuances-of-using-switch-pro-controller-on-steam-for-2024/"><u>[Updated] Navigating the Nuances of Using Switch Pro Controller on Steam for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-peak-performances-in-oly-x-cross-2022/"><u>2024 Approved  Peak Performances in Oly X-Cross 2022</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-screencapture-pro-latest-2023-edition-review/"><u>2024 Approved  ScreenCapture Pro  Latest 2023 Edition Review</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-ultimate-guide-for-amateurs-and-pros-on-windows-11-video-creation/"><u>2024 Approved  The Ultimate Guide for Amateurs & Pros on Windows 11 Video Creation</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/3-ways-for-android-pokemon-go-spoofing-on-lava-agni-2-5g-drfone-by-drfone-virtual-android/"><u>3 Ways for Android Pokemon Go Spoofing On Lava Agni 2 5G | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/a-beginners-roadmap-to-planning-and-publishing-tweets-in-advance/"><u>A Beginner's Roadmap to Planning and Publishing Tweets in Advance</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/a-comprehensive-tutorial-on-how-to-give-steam-digital-presents/"><u>A Comprehensive Tutorial on How to Give Steam Digital Presents</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/a-step-by-step-guide-to-making-your-email-addresses-safe-for-listings-and-search-engines/"><u>A Step-by-Step Guide to Making Your Email Addresses Safe for Listings and Search Engines</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/access-hollywood-for-free-top-11-movie-downloading-portals/"><u>Access Hollywood for Free: Top 11 Movie Downloading Portals</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/android-call-history-recovery-recover-deleted-call-logs-from-honor-x50-gt-by-fonelab-android-recover-call-logs/"><u>Android Call History Recovery - recover deleted call logs from Honor X50 GT</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-t-view-mkv-movies-content-on-samsung-galaxy-m54-5g-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Can’t view MKV movies content on Samsung Galaxy M54 5G</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/comprehensive-tutorial-purging-all-correspondence-from-your-gmail-application/"><u>Comprehensive Tutorial - Purging All Correspondence From Your Gmail Application</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/diagnosing-and-fixing-code-43-mistakes-for-seamless-computer-operations/"><u>Diagnosing and Fixing Code 43 Mistakes for Seamless Computer Operations</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/directly-viewing-facebook-videos-on-your-apple-tv-setup/"><u>Directly Viewing Facebook Videos on Your Apple TV Setup</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/discover-the-most-inspiring-movie-masterpieces-of-all-time-top-11-picks/"><u>Discover the Most Inspiring Movie Masterpieces of All Time (Top 11 Picks)</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/into-high-quality-audio-7-royalty-free-selections-for-2024/"><u>Dive Into High-Quality Audio  7 Royalty-Free Selections for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/dos-and-donts-when-cleaning-your-hdtv-a-comprehensive-walkthrough/"><u>Do's and Don’ts When Cleaning Your HDTV - A Comprehensive Walkthrough</u></a></li>
<li><a href="https://win-solutions.techidaily.com/effective-solutions-for-fixing-the-internet-explorer-has-stopped-working-issue/"><u>Effective Solutions for Fixing the 'Internet Explorer Has Stopped Working' Issue</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/effective-strategies-for-resolving-device-managers-code-41-issues/"><u>Effective Strategies for Resolving Device Manager's Code 41 Issues</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/efficient-solutions-for-the-binkw32dll-file-error-in-your-computer/"><u>Efficient Solutions for the binkw32.dll File Error in Your Computer</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/essential-fixes-for-the-not-found-error-in-msi-dll-file/"><u>Essential Fixes for the Not Found Error in MSI DLL File</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/experience-the-excitement-unveiling-of-the-newest-apple-iphone/"><u>Experience the Excitement: Unveiling of the Newest Apple iPhone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/fix-vcompdll-cannot-be-located-error-a-step-by-step-solution/"><u>Fix Vcomp.dll Cannot Be Located Error: A Step-by-Step Solution</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/fixing-the-error-code-0xc00185-expert-tips-and-solutions/"><u>Fixing the Error Code: 0XC00ˈ185 – Expert Tips & Solutions</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/guide-streaming-your-favorite-apps-from-apple-tv-to-amazon-fire-stick/"><u>Guide: Streaming Your Favorite Apps From Apple TV to Amazon Fire Stick</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-mp4-and-mov-files-of-nubia-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair corrupt MP4 and MOV files of Nubia ?</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-unlink-your-iphone-xr-from-your-apple-id-by-drfone-ios/"><u>How To Unlink Your iPhone XR From Your Apple ID</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-simple-steps-to-embed-youtube-playlists-on-any-website/"><u>In 2024, The Simple Steps to Embed YouTube Playlists on Any Website</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-tracking-apps-to-track-oneplus-ace-2-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Tracking Apps to Track OnePlus Ace 2 without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/insider-insights-on-teslas-robotaxi-unveiling-the-proposed-cost-launch-timeline-and-technical-details/"><u>Insider Insights on Tesla's Robotaxi: Unveiling the Proposed Cost, Launch Timeline & Technical Details</u></a></li>
<li><a href="https://facebook.techidaily.com/introducing-acquaintances-elevate-your-chat-experience-with-messenger/"><u>Introducing Acquaintances: Elevate Your Chat Experience with Messenger</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-nubia-red-magic-9-proplus-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Nubia Red Magic 9 Pro+ | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/luminarx-the-freepaid-lightroom-rival-list/"><u>LuminarX  The Free/Paid Lightroom Rival List</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-the-art-of-better-digital-television-viewing-with-an-indoor-antenna-setup/"><u>Mastering the Art of Better Digital Television Viewing with an Indoor Antenna Setup</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-troubleshooting-a-complete-reference-for-pc-blue-screen-codes/"><u>Mastering Troubleshooting: A Complete Reference for PC Blue Screen Codes</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/recovering-wi-fi-password-on-windows-11-a-comprehensive-tutorial/"><u>Recovering Wi-Fi Password on Windows 11: A Comprehensive Tutorial</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/securing-maximum-exposure-and-traction-for-your-content-on-apple-tv/"><u>Securing Maximum Exposure and Traction for Your Content on Apple TV</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/set-your-files-on-a-path-to-oblivion-with-the-stellar-erase-tool-customized-for-windows/"><u>Set Your Files On A Path To Oblivion With The Stellar Erase Tool, Customized For Windows</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/solving-the-mystery-of-dll-errors-a-step-by-step-guide/"><u>Solving the Mystery of DLL Errors: A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/solving-the-mystery-of-jvmdll-missing-a-step-by-step-guide/"><u>Solving the Mystery of JVM_DLL Missing: A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/solving-the-problem-step-by-step-guide-to-repairing-unresponsive-dvd-bd-and-cd-drives/"><u>Solving the Problem: Step-by-Step Guide to Repairing Unresponsive DVD, BD, and CD Drives</u></a></li>
<li><a href="https://driver-error.techidaily.com/sorted-through-storage-discrepancies/"><u>Sorted Through Storage Discrepancies</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-guide-correcting-msvcr71dll-file-absence-errors/"><u>Step-by-Step Guide: Correcting MSVCR71.DLL File Absence Errors</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-solutions-correcting-kernel32dll-errors-in-windows-systems/"><u>Step-by-Step Solutions: Correcting Kernel32.dll Errors in Windows Systems</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-insiders-guide-to-nvidias-rtx-graphics-cards-what-you-need-to-know/"><u>The Insider’s Guide to Nvidia's RTX Graphics Cards: What You Need to Know</u></a></li>
<li><a href="https://android-unlock.techidaily.com/tips-and-tricks-for-setting-up-your-vivo-v27-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Vivo V27 Phone Pattern Lock</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/transformative-techniques-to-mute-background-noise-for-2024/"><u>Transformative Techniques to Mute Background Noise for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-guide-for-resolving-netflix-connectivity-problems-with-roku/"><u>Troubleshooting Guide for Resolving Netflix Connectivity Problems with Roku</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ultimate-guide-the-6-greatest-playstation-portable-mario-experiennces/"><u>Ultimate Guide: The 6 Greatest PlayStation Portable Mario Experiennces</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-tips-for-pairing-your-xbox-one-controller-when-synching-issues-arise/"><u>Ultimate Tips for Pairing Your Xbox One Controller When Synching Issues Arise</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/uncover-the-secret-to-sending-and-receiving-free-faxes-with-these-7-websites/"><u>Uncover the Secret to Sending and Receiving Free Faxes with These 7 Websites</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlocking-made-easy-the-best-10-apps-for-unlocking-your-xiaomi-redmi-note-12-pro-4g-device-by-drfone-android/"><u>Unlocking Made Easy The Best 10 Apps for Unlocking Your Xiaomi Redmi Note 12 Pro 4G Device</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unlocking-the-secrets-syncing-songs-with-your-insta-videos-like-a-pro/"><u>Unlocking the Secrets: Syncing Songs with Your Insta Videos Like a Pro</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unveiling-the-contrasts-between-ipad-mini-and-ipad-air-for-informed-choices/"><u>Unveiling the Contrasts Between iPad Mini and iPad Air for Informed Choices</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/your-complete-harry-potter-journey-the-right-way-to-experience-the-wizards-tale-on-screen/"><u>Your Complete Harry Potter Journey: The Right Way to Experience the Wizard's Tale on Screen</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->