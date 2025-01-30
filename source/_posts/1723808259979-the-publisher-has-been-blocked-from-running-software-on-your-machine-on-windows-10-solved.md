---
title: ‘The Publisher Has Been Blocked From Running Software on Your Machine’ on Windows 10 [Solved]
date: 2025-01-23T19:01:20.893Z
updated: 2025-01-30T16:49:17.275Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes ‘The Publisher Has Been Blocked From Running Software on Your Machine’ on Windows 10 [Solved]
excerpt: This Article Describes ‘The Publisher Has Been Blocked From Running Software on Your Machine’ on Windows 10 [Solved]
thumbnail: https://thmb.techidaily.com/5ab9533fc8b349be19f63e7cbad029dfd19e210f57907497c693bf48b201e0ff.jpg
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
<li><a href="https://vimeo-videos.techidaily.com/updated-master-list-of-vimeo-video-capturers/"><u>[Updated] Master List of Vimeo Video Capturers</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/comprehensive-analysis-of-cleanmymac-x-based-on-the-expert-reviews-at-zdnet/"><u>Comprehensive Analysis of CleanMyMac X Based on the Expert Reviews at ZDNet</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/detailed-look-at-the-meta-quest-anticipated-launch-pricing-strategy-and-cutting-edge-specifications-explained/"><u>Detailed Look at the Meta Quest 지: Anticipated Launch, Pricing Strategy & Cutting-Edge Specifications Explained</u></a></li>
<li><a href="https://network-issues.techidaily.com/enabling-saved-screen-configurations-in-win-107/"><u>Enabling Saved Screen Configurations in Win 10/7</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/getting-your-dark-theme-back-on-facebook-an-essential-troubleshooting-guide/"><u>Getting Your Dark Theme Back on Facebook: An Essential Troubleshooting Guide</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-reset-apple-id-and-apple-password-from-iphone-6s-by-drfone-ios/"><u>How to Reset Apple ID and Apple Password From iPhone 6s</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-vivo-v27-pro-location-by-number-drfone-by-drfone-virtual-android/"><u>How to Track Vivo V27 Pro Location by Number | Dr.fone</u></a></li>
<li><a href="https://some-tips.techidaily.com/mastering-apple-pay-a-comprehensive-guide-for-in-store-and-online-transactions-learn-why-its-beneficial/"><u>Mastering Apple Pay: A Comprehensive Guide for In-Store & Online Transactions - Learn Why It's Beneficial</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/overcoming-common-problems-opening-or-ejecting-cd-dvd-and-blu-ray-drives/"><u>Overcoming Common Problems: Opening or Ejecting CD, DVD & Blu-Ray Drives</u></a></li>
<li><a href="https://fox-sys.techidaily.com/quick-and-simple-methods-transferring-your-contacts-from-vcf-to-iphone-in-just-4-steps/"><u>Quick and Simple Methods: Transferring Your Contacts From VCF to iPhone in Just 4 Steps</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/sneak-peek-at-the-future-anticipated-cost-and-release-dates-for-the-samsung-galaxy-z-fold-7-what-rumors-tell-us-about-its-features/"><u>Sneak Peek at the Future: Anticipated Cost and Release Dates for the Samsung Galaxy Z Fold 7 - What Rumors Tell Us About Its Features</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-technique-for-dueling-on-tiktok-with-friends-and-fans/"><u>The Ultimate Technique for Dueling on TikTok with Friends and Fans</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-techniques-for-syncing-and-sharing-duet-content-on-tiktok/"><u>The Ultimate Techniques for Syncing and Sharing Duet Content on TikTok</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/iewer-count-chronicles-mastering-the-math-of-monetizing-moments-in-youtube-space-for-2024/"><u>The Viewer Count Chronicles Mastering the Math of Monetizing Moments in YouTube Space for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/what-does-page-not-found-mean-quick-fix-strategies-for-a-smooth-site-experience/"><u>What Does 'Page Not Found' Mean? Quick Fix Strategies for a Smooth Site Experience</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/slm2NjVPNtk?si=9ow6g1ucmf0TnT4T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

