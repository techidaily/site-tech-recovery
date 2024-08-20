---
title: "Troubleshooting Guide: How to Fix SSL/TLS Handshake Errors on Windows"
date: 2024-08-19T12:49:02.323Z
updated: 2024-08-20T12:49:02.323Z
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
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-vintage-video-upgrade/"><u>[Updated] In 2024, Vintage Video Upgrade</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-reimagining-posts-a-new-perspective-on-ig-for-2024/"><u>[Updated] Reimagining Posts  A New Perspective on IG for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-best-start-up-cameras-from-35mm-to-point-shot/"><u>2024 Approved  Best Start-Up Cameras From 35Mm to Point-Shot</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-in-depth-shots-the-art-of-closing-in-on-movies/"><u>2024 Approved  In-Depth Shots  The Art of Closing in on Movies</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/boost-your-efficiency-with-the-secret-window-to-all-files-on-windows/"><u>Boost Your Efficiency with The Secret Window to All Files on Windows</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/cat-s42-phone-analysis-high-resilience-marred-by-sluggish-response-time/"><u>Cat S42 Phone Analysis: High Resilience Marred by Sluggish Response Time</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/complete-guide-steps-to-swap-out-your-old-ipads-power-source/"><u>Complete Guide: Steps to Swap Out Your Old iPad's Power Source</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/deciphering-rtx-what-you-need-to-know-about-next-gen-graphics-cards/"><u>Deciphering RTX: What You Need to Know About Next-Gen Graphics Cards</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/effective-solutions-for-handling-the-avcodecdll-file-doesnt-exist-issue/"><u>Effective Solutions for Handling the 'Avcodec.dll' File Doesn't Exist Issue</u></a></li>
<li><a href="https://extra-hints.techidaily.com/from-novice-to-expert-navigating-windows-11s-movie-maker-easily/"><u>From Novice to Expert  Navigating Windows 11'S Movie Maker Easily</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-address-the-rpcrt4dll-couldnt-be-located-problem/"><u>How To Address The 'rpcrt4.dll' Couldn't Be Located Problem</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-securely-delete-the-lock-screen-access-code-on-windows-n-operating-system/"><u>How to Securely Delete the Lock Screen Access Code on Windows N Operating System</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/hulu-vs-hulu-plus-whats-the-difference/"><u>Hulu Vs. Hulu Plus: What's the Difference?</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-ultimate-movie-watchlists-for-efficient-screen-time/"><u>In 2024, Ultimate Movie Watchlists for Efficient Screen Time</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/key-information-about-samsung-televisions-and-their-integrated-apps/"><u>Key Information About Samsung Televisions & Their Integrated Apps</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-the-art-of-iphone-voice-messaging-features/"><u>Mastering the Art of iPhone Voice Messaging Features</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-the-resolution-of-kernel-buffer-overflow-issues-expert-tips-and-techniques/"><u>Mastering the Resolution of Kernel Buffer Overflow Issues: Expert Tips & Techniques</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/netflix-struggles-heres-how-to-get-smooth-streaming-again/"><u>Netflix Struggles? Here's How to Get Smooth Streaming Again</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/revolutionary-apple-iphone-release-whats-new-and-exciting/"><u>Revolutionary Apple iPhone Release: What's New and Exciting</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/seamless-setup-integrating-playstation-vr-into-your-pc-gaming-rig/"><u>Seamless Setup: Integrating PlayStation VR Into Your PC Gaming Rig</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/smart-texting-strategies-to-save-on-mobile-data/"><u>Smart Texting Strategies to Save on Mobile Data</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-troubleshooting-resolving-jscriptdll-errors-on-your-pc/"><u>Step-by-Step Troubleshooting: Resolving Jscript.dll Errors on Your PC</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/streaming-iphone-7-display-like-a-pro/"><u>Streaming iPhone 7 Display Like a Pro</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/tackling-the-mystery-of-bsod-stop-code-0x0000007b-strategies-for-a-smooth-fix/"><u>Tackling the Mystery of BSOD STOP Code 0X0000007B: Strategies for a Smooth Fix</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-evolution-of-5g-spotlight-on-verizons-innovations/"><u>The Evolution of 5G: Spotlight on Verizon's Innovations</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-ultimate-guide-to-the-features-and-performance-of-crealitys-k1-c-carbon-edition/"><u>The Ultimate Guide to the Features and Performance of Creality's K1 C Carbon Edition</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-tips-restoring-default-settings-on-your-samsung-soundbar/"><u>Troubleshooting Tips: Restoring Default Settings on Your Samsung Soundbar</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unveiling-the-mystery-understanding-the-blue-screen-of-death-and-its-significance/"><u>Unveiling the Mystery: Understanding the Blue Screen of Death and Its Significance</u></a></li>
<li><a href="https://youtube-web.techidaily.com/-visuals-brush-up-your-youtube-beauty-videos-for-2024/"><u>Vivid Visuals  Brush up Your YouTube Beauty Videos for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/web-superstars-exploring-the-top-1-must-visit-sites-across-the-internet/"><u>Web Superstars: Exploring the Top 1# Must-Visit Sites Across the Internet</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->