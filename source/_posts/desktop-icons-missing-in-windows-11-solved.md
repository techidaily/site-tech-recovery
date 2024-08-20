---
title: Desktop Icons Missing in Windows 11 [Solved]
date: 2024-08-19T12:48:21.033Z
updated: 2024-08-20T12:48:21.033Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes Desktop Icons Missing in Windows 11 [Solved]
excerpt: This Article Describes Desktop Icons Missing in Windows 11 [Solved]
thumbnail: https://thmb.techidaily.com/c3d35b16437bab1ad5b7b686beca2df570e5510e7d66b97529a73f9cf277751a.jpg
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
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-2023-insights-into-snipping-those-facebook-live-moments/"><u>[New] In 2024, 2023 Insights Into Snipping Those Facebook Live Moments</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-master-your-download-installation-and-usage-of-ez-grabber/"><u>[New] In 2024, Master Your Download  Installation and Usage of EZ Grabber</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-innovative-android-camera-apps-for-2024/"><u>[New] Innovative Android Camera Apps for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-duel-for-dominance-physical-vs-virtual-spectacle-for-2024/"><u>[Updated] Duel for Dominance  Physical vs Virtual Spectacle for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-ensure-your-video-fits-the-instagram-aesthetic-perfectly/"><u>[Updated] Ensure Your Video Fits the Instagram Aesthetic Perfectly</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-how-to-download-youtube-thumbnail-in-3-waysonlinewinmac/"><u>[Updated] How to Download Youtube Thumbnail in 3 Ways[Online/Win/Mac]</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-easy-mp4-from-facebook-videos-quick-guide/"><u>[Updated] In 2024, Easy MP4 From Facebook Videos - Quick Guide</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-leading-music-service-streaming-channels/"><u>[Updated] Leading Music Service Streaming Channels</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-simple-steps-to-modify-screen-capture-on-macos/"><u>[Updated] Simple Steps to Modify Screen Capture on macOS</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-the-social-image-hoarders-manual-a-guide-to-downloading-and-keeping-gif-images/"><u>[Updated] The Social Image Hoarder's Manual  A Guide to Downloading and Keeping GIF Images</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-mastering-view-counts-eluding-mechanized-spectators/"><u>2024 Approved  Mastering View Counts  Eluding Mechanized Spectators</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-secrets-unveiled-seamlessly-download-your-favorite-vimeo-videos-anywhere/"><u>2024 Approved  Secrets Unveiled  Seamlessly Download Your Favorite Vimeo Videos Anywhere</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-superior-visual-experience-ranking-the-best-12-html5-players/"><u>2024 Approved  Superior Visual Experience  Ranking the Best 12 HTML5 Players</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-the-ultimate-guide-to-effective-screen-recorders/"><u>2024 Approved  The Ultimate Guide to Effective Screen Recorders</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/2024s-most-protective-aqua-resistant-mobile-covers-your-perfect-guide/"><u>2024'S Most Protective Aqua-Resistant Mobile Covers - Your Perfect Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/accessibility-guide-for-spider-man-film-no-way-home/"><u>Accessibility Guide for Spider-Man Film - 'No Way Home'</u></a></li>
<li><a href="https://win-amazing.techidaily.com/arbitrators-in-international-disputes-often-have-specialized-knowledge-relevant-to-the-industries-or-issues-involved-adding-expertise-to-the-decision-making49/"><u>Arbitrators in International Disputes Often Have Specialized Knowledge Relevant to the Industries or Issues Involved, Adding Expertise to the Decision-Making Process.</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/1723262423349-asus-unveils-new-nuc-pertplus-model-packing-a-meteor-lake-cpu-core-ultra-5-125h-for-860/"><u>Asus Unveils New NUC Pert+ Model: Packing a Meteor Lake CPU, Core Ultra-5 125H for $860!</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/boosting-computer-speed-the-ultimate-7-tips-you-need/"><u>Boosting Computer Speed: The Ultimate 7 Tips You Need</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/cant-play-mp4-files-on-xiaomi-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Can't play MP4 files on Xiaomi</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/deciphering-rumors-on-apples-latest-innovation-home-robot-unveiling-date-value-and-capabilities/"><u>Deciphering Rumors on Apple’s Latest Innovation – Home Robot Unveiling Date, Value, & Capabilities</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/decoding-the-phenomenon-of-online-memes-explained/"><u>Decoding the Phenomenon of Online Memes Explained</u></a></li>
<li><a href="https://data-wizards.techidaily.com/discover-the-finest-video-recovery-applications-for-your-computer-windowsmac/"><u>Discover the Finest Video Recovery Applications for Your Computer (Windows/Mac)</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/electric-cars-a-journey-through-history/"><u>Electric Cars: A Journey Through History</u></a></li>
<li><a href="https://vp-tips.techidaily.com/elite-4k-reflections-the-best-mirrorless-picks/"><u>Elite 4K Reflections  The Best Mirrorless Picks</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/elite-selection-of-mini-gaming-rigs-high-performance-in-a-tiny-package/"><u>Elite Selection of Mini Gaming Rigs: High Performance in a Tiny Package</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/essential-d-link-login-credentials-july-2024-update/"><u>Essential D-Link Login Credentials - July 2024 Update</u></a></li>
<li><a href="https://facebook.techidaily.com/essential-procedures-for-restoring-deactivated-fb-id/"><u>Essential Procedures for Restoring Deactivated FB ID</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/expand-your-digital-workspace-the-ultimate-how-to-on-attaching-3-displays-to-one-pc/"><u>Expand Your Digital Workspace: The Ultimate How-To on Attaching 3 Displays to One PC</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-samsung-galaxy-a14-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on Samsung Galaxy A14 5G | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/fixing-notfound-wpcapdll-error-in-windows-expert-tips/"><u>Fixing NotFound wpcap.dll Error in Windows - Expert Tips</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/getting-paramountplus-back-on-track-your-ultimate-troubleshooting-manual-for-fire-stick-users/"><u>Getting Paramount+ Back on Track: Your Ultimate Troubleshooting Manual for Fire Stick Users</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-resolve-msodll-file-absent-issues-on-your-computer/"><u>How to Resolve mso.dll File Absent Issues on Your Computer</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-deleted-photos-on-pova-6-pro-5g-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to Retrieve deleted photos on Pova 6 Pro 5G</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-animate-on-the-move-best-3d-animation-apps-for-android-iphone-and-ipad/"><u>In 2024, Animate on the Move Best 3D Animation Apps for Android, iPhone, and iPad</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-cinemagraphy-central-filmo-faqs/"><u>In 2024, Cinemagraphy Central  Filmo FAQs</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-easy-effective-strategy-immediate-clearance-of-unwanted-youtube-comments/"><u>In 2024, Easy, Effective Strategy  Immediate Clearance of Unwanted YouTube Comments</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/in-depth-look-at-oculus-quest-3-unveiling-news-cost-details-upcoming-release-date-and-complete-specs-checklist/"><u>In-Depth Look at Oculus Quest 3: Unveiling News, Cost Details, Upcoming Release Date & Complete Specs Checklist</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/innovative-ways-to-enhance-your-iphone-experience-with-ios-16s-live-activities/"><u>Innovative Ways to Enhance Your iPhone Experience with iOS 16'S Live Activities</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722846604888-insider-insights-on-teslas-robotaxi-unveiling-the-proposed-cost-launch-timeline-and-technical-details/"><u>Insider Insights on Tesla's Robotaxi: Unveiling the Proposed Cost, Launch Timeline & Technical Details</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/master-the-art-of-streaming-with-amazon-fire-tv-cube-a-revolutionary-media-device-evaluation/"><u>Master the Art of Streaming with Amazon Fire TV Cube - A Revolutionary Media Device Evaluation</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-the-concept-of-output-impedance-for-better-circuit-design/"><u>Mastering the Concept of Output Impedance for Better Circuit Design</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/maximize-your-safety-on-the-road-with-the-pruveeo-1080p-full-hd-action-camera-reviews-inside/"><u>Maximize Your Safety on the Road with the Pruveeo 1080P Full HD Action Camera - Reviews Inside</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/our-favourite-selection-of-five-superior-international-voice-apps-at-zero-cost/"><u>Our Favourite Selection of Five Superior International Voice Apps at Zero Cost!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-samsung-cartridge-issues/"><u>Overcoming Samsung Cartridge Issues</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/protect-your-contact-information-an-android-users-manual-to-keeping-numbers-private/"><u>Protect Your Contact Information: An Android User's Manual to Keeping Numbers Private</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/quick-tips-for-resolving-netflix-error-signal-nw-10-1-ensuring-uninterrupted-streaming/"><u>Quick Tips for Resolving Netflix Error Signal NW-10-1: Ensuring Uninterrupted Streaming</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/reclaim-your-night-theme-effective-tips-to-restore-disappeared-dark-mode-on-facebook/"><u>Reclaim Your Night Theme: Effective Tips to Restore Disappeared Dark Mode on Facebook</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/securely-clearing-out-icloud-photos-a-guide-to-preserve-your-iphone-snapshots/"><u>Securely Clearing Out iCloud Photos: A Guide to Preserve Your iPhone Snapshots</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/sequential-spectacle-master-your-movie-marathon-with-the-superman-saga/"><u>Sequential Spectacle: Master Your Movie Marathon with the Superman Saga</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/snapchats-hidden-messages-revealed-the-definitive-guide-to-emoji-meanings/"><u>Snapchat's Hidden Messages Revealed: The Definitive Guide to Emoji Meanings</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/solutions-for-resolving-the-fftd2xxdll-file-doesnt-exist-issue/"><u>Solutions for Resolving the 'fFtd2xx.dll File Doesn't Exist' Issue</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/sonys-next-gen-vr-experience-revealed-get-a-glimpse-of-potential-prices-availability-and-device-specs/"><u>Sony's Next-Gen VR Experience Revealed? Get a Glimpse of Potential Prices, Availability, and Device Specs.</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/speeding-through-the-world-of-snapchat-emojis-a-rapid-reference-guide/"><u>Speeding Through the World of Snapchat Emojis: A Rapid Reference Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-fix-for-missing-pdhdll-files-on-your-pc/"><u>Step-by-Step Fix for Missing pdh.dll Files on Your PC</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-plan-for-binge-watching-all-x-men-movies-correctly/"><u>Step-by-Step Plan for Binge-Watching All X-Men Movies Correctly</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-prospects-of-a-prompt-engineers-job-market/"><u>The Prospects of a Prompt Engineer’s Job Market</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-guide-viewing-conjuring-series-sequentially/"><u>The Ultimate Guide: Viewing 'Conjuring' Series Sequentially</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-steps-for-resolving-hulu-error-rununk13/"><u>Troubleshooting Steps for Resolving Hulu ERROR RUNUNK13</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ultimate-guide-charging-techniques-when-you-dont-have-a-charger/"><u>Ultimate Guide: Charging Techniques When You Don't Have a Charger</u></a></li>
<li><a href="https://tech-revival.techidaily.com/understanding-the-potential-pitfalls-of-using-ai-as-a-mental-wellness-guide/"><u>Understanding the Potential Pitfalls of Using AI as a Mental Wellness Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unleashing-the-potential-of-ai-to-revolutionize-society-and-technology/"><u>Unleashing the Potential of AI to Revolutionize Society and Technology</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/upcoming-samsung-galaxy-s25-unveiled-discover-potential-price-launch-timeline-and-latest-leaks/"><u>Upcoming Samsung Galaxy S25 Unveiled! Discover Potential Price, Launch Timeline & Latest Leaks.</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-in-2024-s-most-popular-free-4k-video-conversion-software/"><u>Updated In 2024, S Most Popular Free 4K Video Conversion Software</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/water-resistance-of-iphone-13-what-are-the-limits/"><u>Water Resistance of iPhone 13: What Are The Limits?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-nokia-c110-drfone-by-drfone-virtual-android/"><u>What is the best Pokemon for pokemon pvp ranking On Nokia C110? | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/windows-users-guide-to-hp-printer-installation/"><u>Windows User's Guide to HP Printer Installation</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->