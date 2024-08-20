---
title: Resolving Excessive RAM Consumption in Windows 10 Systems
date: 2024-08-19T12:56:02.323Z
updated: 2024-08-20T12:56:02.323Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes Resolving Excessive RAM Consumption in Windows 10 Systems
excerpt: This Article Describes Resolving Excessive RAM Consumption in Windows 10 Systems
thumbnail: https://thmb.techidaily.com/4e8fed255189bd9ee7a706026d30ffe02100ebaeeb2d7b69ad5a8426d3a0541d.jpg
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
<li><a href="https://youtube-clips.techidaily.com/new-designing-direct-access-to-your-channels-subscribe-page/"><u>[New] Designing Direct Access to Your Channel's Subscribe Page</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-engage-enlighten-and-enthrall-with-immersive-facebook-sharing/"><u>[Updated] 2024 Approved  Engage, Enlighten and Enthrall with Immersive Facebook Sharing</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-recording-skype-calls-with-ease-for-mac-and-pc-users/"><u>[Updated] 2024 Approved  Recording Skype Calls with Ease for Mac and PC Users</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-harness-the-power-of-youtube-shorts-expert-filming-and-editing-techniques-for-2024/"><u>[Updated] Harness the Power of YouTube Shorts  Expert Filming and Editing Techniques for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-from-novice-to-expert-crafting-top-tier-reddit-posts/"><u>2024 Approved  From Novice to Expert  Crafting Top-Tier Reddit Posts</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/breaking-down-the-latest-from-samsung-all-you-need-to-know-about-the-galaxy-z-fold-6s-release-pricing-and-features/"><u>Breaking Down The Latest From Samsung – All You Need to Know About the Galaxy Z Fold 6'S Release, Pricing and Features</u></a></li>
<li><a href="https://fox-helps.techidaily.com/bridging-the-gap-between-human-perception-and-photographic-capture/"><u>Bridging the Gap Between Human Perception and Photographic Capture</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/comprehensive-strategies-to-overcome-ietmodextdll-malfunctions/"><u>Comprehensive Strategies to Overcome ietmodext.dll Malfunctions</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/connect-with-snapchat-representative-for-user-support-needs/"><u>Connect With Snapchat Representative For User Support Needs</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/enhance-account-protection-learn-how-to-modify-your-facebook-password-easily/"><u>Enhance Account Protection: Learn How to Modify Your Facebook Password Easily</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/expert-tips-for-utilizing-androids-swift-settings-shortcut-for-maximum-productivity/"><u>Expert Tips for Utilizing Android's Swift Settings Shortcut for Maximum Productivity</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/explore-a-comprehensive-guide-to-cost-free-and-shared-dns-providers-online/"><u>Explore a Comprehensive Guide to Cost-Free and Shared DNS Providers Online</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/exploring-the-milestones-in-electric-car-history/"><u>Exploring the Milestones in Electric Car History</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/friendly-fun-on-the-go-strategies-for-teaming-up-in-pokemon-go-adventures/"><u>Friendly Fun On-the-Go! Strategies for Teaming Up in Pokémon GO Adventures</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-craft-a-professional-email-signature-on-godaddy-webmail-complete-guide/"><u>How To Craft A Professional Email Signature On GoDaddy Webmail - Complete Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-enable-and-repair-outlook-spell-check-issues-effectively/"><u>How to Enable and Repair Outlook Spell Check Issues Effectively</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-on-nokia-g42-5g-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location on Nokia G42 5G | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-realme-narzo-60-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use GPS Joystick to Fake GPS Location On Realme Narzo 60 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/inside-the-meta-quest-3-comprehensive-guide-to-news-costs-release-calendar-and-features/"><u>Inside the Meta Quest 3 - Comprehensive Guide to News, Costs, Release Calendar & Features</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/list-of-pokemon-go-joysticks-on-infinix-note-30-drfone-by-drfone-virtual-android/"><u>List of Pokémon Go Joysticks On Infinix Note 30 | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/live-broadcast-perfection-comparing-top-screen-recorders-for-2024/"><u>Live Broadcast Perfection  Comparing Top Screen Recorders for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/manage-your-kins-agenda-efficiently-the-ultimate-list-of-7-family-friendly-calendar-applications/"><u>Manage Your Kin's Agenda Efficiently: The Ultimate List of 7 Family-Friendly Calendar Applications</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-the-art-of-choosing-a-stylish-and-secure-smartphone-case/"><u>Mastering the Art of Choosing a Stylish & Secure Smartphone Case</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/overcoming-connectivity-fixing-airpods-that-refuse-to-reset/"><u>Overcoming Connectivity: Fixing AirPods That Refuse to Reset</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/recommended-best-applications-for-mirroring-your-vivo-y100-screen-drfone-by-drfone-android/"><u>Recommended Best Applications for Mirroring Your Vivo Y100 Screen | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/resolving-d3dx926dll-file-missing-issues-a-comprehensive-guide/"><u>Resolving d3dx9_26.dll File Missing Issues: A Comprehensive Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-repair-how-to-recover-missing-or-not-found-mfc42ddll-files-on-windows-systems/"><u>Step-by-Step Repair: How to Recover 'Missing' Or 'Not Found' mfc42d.dll Files on Windows Systems</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/transforming-spotifys-soundtracks-into-downloadable-text-files/"><u>Transforming Spotify's Soundtracks Into Downloadable Text Files</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/troubleshoot-tweets-on-chrome-not-loading/"><u>Troubleshoot  Tweets on Chrome Not Loading</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-and-repairing-qualcomm-atheros-bluetooth-driver-errors-on-windows-11-systems/"><u>Troubleshooting and Repairing Qualcomm Atheros Bluetooth Driver Errors on Windows 11 Systems</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ultimate-list-of-the-15-greatest-dolby-atmos-cinema-hits-for-your-living-room/"><u>Ultimate List of the 15 Greatest Dolby Atmos Cinema Hits for Your Living Room</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unlocking-cross-platform-potential-how-to-operate-android-apps-in-windows-11-environments/"><u>Unlocking Cross-Platform Potential: How to Operate Android Apps in Windows 11 Environments</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/whats-up-with-your-ps4-controller-unraveling-the-meanings-behind-its-blue-white-red-and-orange-blinks/"><u>What's Up with Your PS4 Controller? Unraveling the Meanings Behind Its Blue, White, Red, and Orange Blinks</u></a></li>
<li><a href="https://fox-helps.techidaily.com/your-signature-starts-here-free-modifiable-logos-to-define-brands-for-2024/"><u>Your Signature Starts Here  Free, Modifiable Logos to Define Brands for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->