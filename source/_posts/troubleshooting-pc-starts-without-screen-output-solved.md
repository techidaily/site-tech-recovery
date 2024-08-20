---
title: "Troubleshooting: PC Starts without Screen Output – Solved"
date: 2024-08-19T12:50:40.631Z
updated: 2024-08-20T12:50:40.631Z
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
<li><a href="https://youtube-web.techidaily.com/0plus-youtube-channel-names-for-vloggers-100-new/"><u>[New] 50+ Youtube Channel Names for Vloggers [100%% New]</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-seamless-mp4-to-fb-video-transfer-technology/"><u>[New] In 2024, Seamless MP4-to-FB Video Transfer Technology</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-2024-approved-5-simple-tricks-for-aspiring-photoshop-editors/"><u>[Updated] 2024 Approved  5 Simple Tricks for Aspiring Photoshop Editors</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-best-instagram-highlights-covers-apps-for-iphone-and-android/"><u>[Updated] 2024 Approved  Best Instagram Highlights Covers Apps for iPhone and Android</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-benefits-of-apples-m1-in-post-production-editing/"><u>[Updated] Benefits of Apple's M1 in Post-Production Editing</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-ultimate-battlescape-chronicles-total-wars-sweepstakes/"><u>[Updated] In 2024, Ultimate Battlescape Chronicles  Total Wars Sweepstakes</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-panasonic-hx-a1-wearable-camera-explored/"><u>[Updated] Panasonic HX-A1 Wearable Camera Explored</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-pro-gamers-manual-learn-xbox-one-screen-recording/"><u>[Updated] Pro Gamer's Manual  Learn Xbox One Screen Recording</u></a></li>
<li><a href="https://android-location.techidaily.com/10-free-location-spoofers-to-fake-gps-location-on-your-infinix-hot-40i-drfone-by-drfone-virtual/"><u>10 Free Location Spoofers to Fake GPS Location on your Infinix Hot 40i | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-free-software-for-sound-changes-amplify-and-elevate-your-vocal-impact/"><u>2024 Approved  Free Software For Sound Changes - Amplify and Elevate Your Vocal Impact</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-pinnacle-of-zooid-creations-guide/"><u>2024 Approved  The Pinnacle of Zooid Creations Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/are-wi-fi-mesh-systems-a-smart-choice/"><u>Are Wi-Fi Mesh Systems a Smart Choice?</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/best-7-kid-friendly-internet-games-to-keep-young-minds-busy/"><u>Best 7 Kid-Friendly Internet Games to Keep Young Minds Busy</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/choosing-and-installing-different-browsers-for-samsung-televisions-an-in-depth-guide/"><u>Choosing And Installing Different Browsers For Samsung Televisions: An In-Depth Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/comprehensive-fixes-for-screen-abnormalities-like-fading-and-blurriness/"><u>Comprehensive Fixes for Screen Abnormalities Like Fading & Blurriness</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/comprehensive-guide-to-ipados-18-release-timeline-zero-price-tag-and-new-functionalities/"><u>Comprehensive Guide to iPadOS 18 - Release Timeline, Zero Price Tag, and New Functionalities</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/comprehensive-tutorial-on-converting-multiple-jpeg-photos-into-one-pdf-document/"><u>Comprehensive Tutorial on Converting Multiple JPEG Photos Into One PDF Document</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/creative-capers-with-ios-amusing-shenanignans-for-iphones-and-ipads/"><u>Creative Capers with iOS: Amusing Shenanignans for iPhones and iPads</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/cutting-ties-with-paramountplus-easy-steps-to-discontinue-your-subscription/"><u>Cutting Ties with Paramount+: Easy Steps to Discontinue Your Subscription</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/easy-tips-and-tricks-timing-photos-perfectly-using-iphone-camera-features/"><u>Easy Tips & Tricks: Timing Photos Perfectly Using iPhone Camera Features</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/editing-your-instagram-captions-a-step-by-step-guide/"><u>Editing Your Instagram Captions: A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/effective-sms-habits-to-prevent-overspending-on-your-plan/"><u>Effective SMS Habits to Prevent Overspending on Your Plan</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/effortless-screenshot-solutions-learn-four-key-windows-11-shortcuts-today/"><u>Effortless Screenshot Solutions – Learn Four Key Windows 11 Shortcuts Today</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/effortless-ways-to-transfer-data-from-your-apple-iphone-7-to-iphone-15-drfone-by-drfone-transfer-from-ios/"><u>Effortless Ways to Transfer Data from Your Apple iPhone 7 to iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/elevate-your-earnings-on-social-media-youtube-mastery-on-the-networking-powerhouse-for-2024/"><u>Elevate Your Earnings on Social Media  YouTube Mastery on the Networking Powerhouse for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/expert-solutions-for-fixing-no-signal-screen-problems-on-android-gadgets/"><u>Expert Solutions for Fixing 'No Signal' Screen Problems on Android Gadgets</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/exploring-how-electric-bikes-operate-a-comprehensive-guide/"><u>Exploring How Electric Bikes Operate: A Comprehensive Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/facebook-image-quest-made-simple-strategies-for-efficient-searches/"><u>Facebook Image Quest Made Simple: Strategies for Efficient Searches</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/fixing-frozen-or-non-responsive-programs-on-mac-computers-quickly-and-easily/"><u>Fixing Frozen or Non-Responsive Programs on Mac Computers Quickly and Easily</u></a></li>
<li><a href="https://win-able.techidaily.com/getting-rid-of-outdated-driver-notifications-in-minecraft-troubleshooting-steps/"><u>Getting Rid of Outdated Driver Notifications in Minecraft: Troubleshooting Steps</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722845975821-guide-advanced-gmail-management-techniques-message-filtering-and-managing-multiple-emails/"><u>Guide: Advanced Gmail Management Techniques - Message Filtering & Managing Multiple Emails</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/guide-making-the-most-out-of-your-ipad-and-printer-connection-issues/"><u>Guide: Making the Most Out of Your iPad and Printer Connection Issues</u></a></li>
<li><a href="https://fox-glue.techidaily.com/how-to-get-royalty-free-clip-art/"><u>How to Get Royalty Free Clip Art?</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-free-videography-starter-pack-openers-and-more/"><u>In 2024, Free Videography Starter Pack  Openers & More</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-from-fast-pace-to-deliberate-motion-making-slow-movies-on-insta/"><u>In 2024, From Fast Pace to Deliberate Motion  Making Slow Movies on Insta</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-latest-guide-how-to-bypass-google-pixel-8-frp-without-computer-by-drfone-android/"><u>In 2024, Latest Guide How To Bypass Google Pixel 8 FRP Without Computer</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-samsung-galaxy-a34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Simple and Effective Ways to Change Your Country on YouTube App Of your Samsung Galaxy A34 5G | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/inside-ussd-how-does-unstructured-supplementary-service-data-work/"><u>Inside USSD: How Does Unstructured Supplementary Service Data Work?</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/leading-smart-goggles-the-ultimate-guide/"><u>Leading Smart Goggles: The Ultimate Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/master-the-art-of-picture-perfection-on-your-samsung-4k-television/"><u>Master the Art of Picture Perfection on Your Samsung 4K Television</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-keyboard-accessibility-turning-off-sticky-keys-on-your-pc/"><u>Mastering Keyboard Accessibility: Turning Off Sticky Keys on Your PC</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-privacy-settings-hiding-spam-and-unknown-callers-on-iphone/"><u>Mastering Privacy Settings: Hiding Spam and Unknown Callers on iPhone</u></a></li>
<li><a href="https://buynow-info.techidaily.com/mastering-the-oculus-quist-2-premium-vr-adventures-for-a-fantastic-deal/"><u>Mastering the Oculus Quist 2: Premium VR Adventures for a Fantastic Deal!</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-adobe-premiere-pro-2023-import-organize-and-export-your-video-projects-like-a-pro/"><u>New In 2024, Adobe Premiere Pro 2023 Import, Organize, and Export Your Video Projects Like a Pro</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-rise-above-the-rest-enhancing-speech-clarity-and-volume-with-filmora-for-2024/"><u>New Rise Above the Rest Enhancing Speech Clarity and Volume with Filmora for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-the-ultimate-fcpx-shortcut-guide-40-time-saving-keys-for-2024/"><u>New The Ultimate FCPX Shortcut Guide 40 Time-Saving Keys for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/precision-editing-harnessing-photoshops-eraser/"><u>Precision Editing  Harnessing Photoshop’s Eraser</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/rcs-explained-transforming-how-we-send-rich-media-messages/"><u>RCS Explained: Transforming How We Send Rich Media Messages</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/restoring-your-iphone-15-a-step-by-step-guide/"><u>Restoring Your iPhone 15: A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/solving-the-kernel-data-parsing-mistake-a-comprehensive-guide/"><u>Solving the Kernel Data Parsing Mistake: A Comprehensive Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-guide-removing-your-smartphones-protective-tempered-glass/"><u>Step-by-Step Guide: Removing Your Smartphone's Protective Tempered Glass</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/steps-to-access-and-edit-pdfs-with-microsoft-word/"><u>Steps to Access and Edit PDFs with Microsoft Word</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/steps-to-hide-subtitle-feature-on-prime-video-platform/"><u>Steps to Hide Subtitle Feature on Prime Video Platform</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-art-of-detecting-phony-friends-on-social-media-platforms/"><u>The Art of Detecting Phony Friends on Social Media Platforms</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-battle-of-durability-are-electric-cars-on-par-with-gasoline-powered-ones/"><u>The Battle of Durability: Are Electric Cars on Par with Gasoline-Powered Ones?</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-beginners-handbook-for-convenient-cashless-transactions-with-apple-pay-on-an-apple-watch/"><u>The Beginner's Handbook for Convenient Cashless Transactions with Apple Pay on an Apple Watch</u></a></li>
<li><a href="https://change-location.techidaily.com/the-best-ispoofer-alternative-to-try-on-samsung-galaxy-xcover-6-pro-tactical-edition-drfone-by-drfone-virtual-android/"><u>The Best iSpoofer Alternative to Try On Samsung Galaxy XCover 6 Pro Tactical Edition | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-next-big-thing-detailed-specs-and-pricing-of-the-forthcoming-apple-ring-revealed/"><u>The Next Big Thing? Detailed Specs and Pricing of the Forthcoming Apple Ring Revealed!</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-how-to-adding-perfect-horizontal-and-vertical-lines-to-microsoft-word/"><u>The Ultimate How-To: Adding Perfect Horizontal and Vertical Lines to Microsoft Word</u></a></li>
<li><a href="https://video-capture.techidaily.com/ultimate-guide-to-non-udemy-online-education-sites-for-2024/"><u>Ultimate Guide to Non-Udemy Online Education Sites for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ultimate-guide-resolving-kernel32dll-issues-on-your-pc/"><u>Ultimate Guide: Resolving Kernel32.dll Issues on Your PC</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/windows-quick-entry-setup-how-to-automate-user-login-processes/"><u>Windows Quick Entry Setup: How to Automate User Login Processes</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->