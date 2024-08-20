---
title: How to Make Your Windows 10 Faster [Work 100%%]
date: 2024-08-19T12:51:56.967Z
updated: 2024-08-20T12:51:56.967Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes How to Make Your Windows 10 Faster [Work 100%%]
excerpt: This Article Describes How to Make Your Windows 10 Faster [Work 100%%]
thumbnail: https://thmb.techidaily.com/8437f38447ce38f499b6100252361ad0a548e9cd2a118e2df20ca665823d885e.jpg
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
<li><a href="https://extra-resources.techidaily.com/new-captivate-your-imagery-with-illustrators-motion-blur-tricks/"><u>[New] Captivate Your Imagery with Illustrator's Motion Blur Tricks</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-insta-editing-secrets-mastering-high-resolution-footage-in-fcpx/"><u>[Updated] Insta-Editing Secrets  Mastering High-Resolution Footage in FCPX</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-make-every-story-stand-out-6-top-rated-apps-for-android-and-iphone-for-2024/"><u>[Updated] Make Every Story Stand Out  6 Top-Rated Apps for Android & iPhone for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-preserving-your-snapshots-mobile-and-desktop-compatible-for-2024/"><u>[Updated] Preserving Your Snapshots  Mobile & Desktop Compatible for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/aol-email-service-outage-identifying-the-root-cause-your-guide/"><u>AOL Email Service Outage: Identifying the Root Cause - Your Guide</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chatgpt-unveiled-for-parents-the-comprehensive-guide-to-generative-ai-explained/"><u>ChatGPT Unveiled for Parents: The Comprehensive Guide to Generative AI Explained</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/discover-the-best-imessage-gaming-trends-the-top-7-picks/"><u>Discover the Best iMessage Gaming Trends : The Top 7 Picks!</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/dual-storage-mastery-how-to-delete-icloud-images-and-keep-them-intact-on-iphone/"><u>Dual-Storage Mastery: How to Delete iCloud Images and Keep Them Intact on iPhone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/eliminating-missing-ksuserdll-errors-with-easy-troubleshooting-tips/"><u>Eliminating Missing ksuser.dll Errors with Easy Troubleshooting Tips</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/explore-the-best-lgbtq-content-available-on-netflix-this-july-2024/"><u>Explore the Best LGBTQ Content Available on Netflix This July 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/find-your-dream-ipad-at-discounted-prices-right-now/"><u>Find Your Dream iPad at Discounted Prices Right Now</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/guide-to-securely-adding-your-email-address-for-priority-delivery/"><u>Guide to Securely Adding Your Email Address for Priority Delivery</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-honor-magic-vs-2withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Honor Magic Vs 2with/without a PC</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-expert-recommended-steadicams-for-professional-dslr-work/"><u>In 2024, Expert-Recommended Steadicams for Professional DSLR Work</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-strategic-steps-for-incorporating-srt-files-into-googleplus-campaigns/"><u>In 2024, Strategic Steps for Incorporating SRT Files Into Google+ Campaigns</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/is-there-a-psn-service-interruption-or-are-you-facing-connectivity-problems/"><u>Is There A PSN Service Interruption, Or Are You Facing Connectivity Problems?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-the-setup-seamless-chatgpt-deployment-on-linux-with-bavarder-software/"><u>Mastering the Setup: Seamless ChatGPT Deployment on Linux with Bavarder Software</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/must-watch-max-documentaries-in-july-2024-our-list/"><u>Must-Watch Max Documentaries in July 2024 - Our List</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/navigate-the-maze-of-car-audio-encryption-learn-how-to-find-your-radio-security-code-easily/"><u>Navigate the Maze of Car Audio Encryption – Learn How to Find Your Radio Security Code Easily!</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/protecting-your-mail-app-on-macos-a-step-by-step-guide-to-creating-safe-senders-lists/"><u>Protecting Your Mail App on macOS: A Step-by-Step Guide to Creating Safe Senders Lists</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ps5-multiplayer-setup-tips-for-effortless-game-sessions-with-loved-ones/"><u>PS5 Multiplayer Setup: Tips for Effortless Game Sessions with Loved Ones</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/seamless-tech-hacks-how-to-perform-screen-reflection-on-an-lg-display/"><u>Seamless Tech Hacks: How to Perform Screen Reflection on an LG Display</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-solution-for-reconnecting-with-your-lost-co-processor-driver-on-windows-10-machine/"><u>Step-by-Step Solution for Reconnecting with Your Lost Co-Processor Driver on Windows #10 Machine</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-altering-file-deletion-alerts-in-win/"><u>Steps for Altering File Deletion Alerts in Win</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/tapping-into-technology-deals-for-students-how-to-access-microsoft-discounted-rates/"><u>Tapping Into Technology Deals for Students: How to Access Microsoft Discounted Rates</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-best-smartwatch-apps-for-android/"><u>The Best Smartwatch Apps for Android</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-tips-for-boosting-indoor-digital-broadcast-quality-with-an-antenna/"><u>The Ultimate Tips for Boosting Indoor Digital Broadcast Quality with an Antenna</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-motorola-moto-g84-5g-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Motorola Moto G84 5G Reset Code | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ultimate-strategies-to-correct-code-43-malfunctions/"><u>Ultimate Strategies to Correct Code 43 Malfunctions</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/understanding-atandts-cellular-data-roaming-rules-and-costs/"><u>Understanding AT&T's Cellular Data Roaming Rules and Costs</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unmasking-hidden-treasures-methods-for-exposing-concealed-iphone-applications/"><u>Unmasking Hidden Treasures: Methods for Exposing Concealed iPhone Applications</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/unraveling-the-purpose-behind-facebooks-blue-icon/"><u>Unraveling the Purpose Behind Facebook's Blue Icon</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->