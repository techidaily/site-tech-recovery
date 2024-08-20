---
title: The Ultimate Guide to Understanding and Executing the ChkDsk Utility on Windows PCs
date: 2024-08-19T14:35:38.236Z
updated: 2024-08-20T14:35:38.236Z
categories:
  - BestProducts
description: This Article Describes The Ultimate Guide to Understanding and Executing the ChkDsk Utility on Windows PCs
excerpt: This Article Describes The Ultimate Guide to Understanding and Executing the ChkDsk Utility on Windows PCs
thumbnail: https://www.lifewire.com/thmb/33AQQZVzam_p173eQdHzdLwctNU=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/chkdsk-help-command-86bf1475305d4df1aeb9ab4846c2c60d.png
---

## The Ultimate Guide to Understanding and Executing the ChkDsk Utility on Windows PCs

Close 

 Short for "check disk," the chkdsk command is a Command Prompt command used to check a specified disk and repair or recover data on the drive if necessary.

 Chkdsk also marks any damaged or malfunctioning sectors on the hard drive or disk as "bad" and recovers any information still intact.

##  Chkdsk Command Availability 

 The chkdsk command is available via Command Prompt in Windows 11, Windows 10, Windows 8, Windows 7, Windows Vista, and Windows XP operating systems.

 The chkdsk command is also available in[ Advanced Startup Options](https://www.lifewire.com/advanced-startup-options-2625805) and[ System Recovery Options](https://www.lifewire.com/system-recovery-options-2626021) . It works from within the Recovery Console in Windows 2000 and Windows XP. Chkdsk is a DOS Command, too, available in most versions of MS-DOS.

[  13 Best Free Hard Drive Testing Tools (July 2024) ](https://www.lifewire.com/free-hard-drive-testing-programs-2626183) 

 The availability of certain chkdsk command switches and other chkdsk command[ syntax](https://www.lifewire.com/what-is-syntax-2626014) might differ from operating system to operating system.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
## Chkdsk Command Syntax 

**chkdsk** \[_volume:_ \] \[**/F** \] \[**/V** \] \[**/R** \] \[**/X** \] \[**/I** \] \[**/C** \] \[**/L** :_size_ \] \[**/perf** \] \[**/scan** \] \[**/?** \]

[ How to Read Command Syntax ](https://www.lifewire.com/how-to-read-command-syntax-2618082) 

| Chkdsk Command Options |                                                                                                                                                                                                                                                                                                                                                                             |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Option**             | **Explanation**                                                                                                                                                                                                                                                                                                                                                             |
| _volume:_              | This is the drive letter of the[ partition](https://www.lifewire.com/what-is-a-partition-2625958) for which you want to check for errors.                                                                                                                                                                                                                                   |
| **/F**                 | This chkdsk command option will fix any errors found on the disk.                                                                                                                                                                                                                                                                                                           |
| **/V**                 | Use this chkdsk option on a[ FAT or FAT32](https://www.lifewire.com/what-is-file-allocation-table-fat-2625877) volume to show the full path and name of every file on the disk. If used on an[ NTFS](https://www.lifewire.com/ntfs-file-system-2625948) volume, it will show cleanup messages (if there are any).                                                           |
| **/R**                 | This option tells chkdsk to locate bad sectors and recover any readable information from them. This option implies**/F** when**/scan** is not specified.                                                                                                                                                                                                                    |
| **/X**                 | This command option implies**/F** and will force a dismount of the volume if necessary.                                                                                                                                                                                                                                                                                     |
| **/I**                 | This option will perform a less vigorous chkdsk command by instructing the command to run faster by skipping over certain regular checks.                                                                                                                                                                                                                                   |
| **/C**                 | Same as**/I** but skips over cycles within the folder structure to reduce the amount of time that the chkdsk command runs.                                                                                                                                                                                                                                                  |
| **/L:** _size_         | Use this chkdsk command option to change the size (in KB) of the log file. The default log file size for chkdsk is 65536 KB; you can check the current log file size by executing**/L** without the "size" option.                                                                                                                                                          |
| **/perf**              | This option allows chkdsk to run faster by using more[ system resources](https://www.lifewire.com/what-is-a-system-resource-2626016) . It has to be used with**/scan** .                                                                                                                                                                                                    |
| **/scan**              | This chkdsk option runs an online scan on an NTFS volume but does not try to repair it. Here, "online" means that the volume does not need to be dismounted, but can instead remain online/active. This is true for both internal and[ external hard drives](https://www.lifewire.com/what-is-an-external-drive-2625867) ; you can continue using them throughout the scan. |
| **/spotfix**           | This chkdsk option dismounts the volume only briefly to fix issues that were sent to the log file.                                                                                                                                                                                                                                                                          |
| **/?**                 | Use the[ help switch](https://www.lifewire.com/help-switch-2625896) with the chkdsk command to show detailed help about the commands listed above and other options you can use with chkdsk.                                                                                                                                                                                |

 Other less commonly used chkdsk command switches exist too, like**/B** to re-evaluate bad clusters on the volume,**/forceofflinefix** which runs an online scan (a scan while the volume is active) but then forces the repair to run offline (once the volume has been dismounted),**/offlinescanandfix** which runs an offline chkdsk scan and then fixes any problems that were found, and others that you can read more about through the**/?** switch.

 The**/offlinescanandfix** option is the same as**/F** except that it's only allowed on NTFS volumes.

 If you're using the chkdsk command from the Recovery Console in older versions of Windows, use**/p** in place of**/F** above to instruct chkdsk to perform an extensive check and[ repair errors on the hard drive](https://www.lifewire.com/check-and-fix-hard-drive-errors-3506860) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
## Chkdsk Command Examples 

 Here are some of the different ways you might use the chkdsk command:

### Read-Only Mode 


 `chkdsk`

 Since no drive or additional options were entered in the above example, chkdsk simply runs in read-only mode.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
![The CHKDSK command in read-only mode](https://www.lifewire.com/thmb/0p8t7Npad9Bk-vVhkXAlMhm1l-w=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/chkdsk-read-only-mode-45b119cdfaea4c89b2c716c32269497c.png) 

 If problems were found when running this simple chkdsk command, you'll want to make sure to use the example from below to correct any issues.

###  Pre-Boot Scan & Fix 


 `chkdsk c: /r`

 In this example, the chkdsk command is used to perform an extensive check of the _C:_ drive to correct errors and locate recovery information from bad sectors. This is best used when running chkdsk from outside of Windows, like from a recovery disc where you need to specify which drive to scan.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
### Offline Repair 


 ` chkdsk c: /scan /forceofflinefix`

 This chkdsk command runs an _online scan_ on the _C:_ volume so that you don't have to dismount the volume to run the test, but instead of fixing any issues while the volume is active, the problems are sent to a queue that will be resolved in an offline repair.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
### Fast Scan & Fix 


 ` chkdsk c: /r /scan /perf `

 In this example, chkdsk will fix problems on the _C:_ drive while you're using it and will use as many system resources as allowed so that it will run as quickly as possible.

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Chkdsk Related Commands 

 Chkdsk is often used with many other Command Prompt commands and [ Recovery Console commands](https://www.lifewire.com/recovery-console-2625991) . It's similar to the scandisk command used to check a hard drive or floppy disk for errors in Windows 98 and MS-DOS.

[  The Complete List of Command Prompt (CMD) Commands ](https://www.lifewire.com/list-of-command-prompt-commands-4092302) 

Was this page helpful?

Thanks for letting us know!

 Get the Latest Tech News Delivered Every Day

[ Subscribe ](https://www.lifewire.com/#) 

Tell us why!

 Other  Not enough details  Hard to understand 

 Submit 

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
<li><a href="https://youtube-webster.techidaily.com/hoose-from-the-finest-7-android-browsers-without-ads-for-2024/"><u>[New] Choose From the Finest 7 Android Browsers Without Ads for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-professional-techniques-editing-and-saving-movies-in-win-11/"><u>[New] In 2024, Professional Techniques  Editing and Saving Movies in Win 11</u></a></li>
<li><a href="https://article-files.techidaily.com/new-in-2024-stepping-into-filmmaking-learning-the-basics-of-key-shots/"><u>[New] In 2024, Stepping Into Filmmaking  Learning the Basics of Key Shots</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-mix-like-a-pro-with-20-no-cost-luts-from-dji-devices/"><u>[New] Mix Like a Pro with 20 No-Cost LUTs From DJI Devices</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-complete-windows-11-audio-record-process/"><u>[New] The Complete Windows 11 Audio Record Process</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-blissful-clip-grabber-insight/"><u>[Updated] Blissful Clip Grabber Insight</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-capture-the-moment-live-streams-archive-for-2024/"><u>[Updated] Capture the Moment  Live Streams Archive for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-build-your-personal-brand-on-youtube-for-2024/"><u>[Updated] How to Build Your Personal Brand on YouTube for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-detailed-review-obs-as-a-top-choice-for-screen-recorders/"><u>[Updated] In 2024, Detailed Review  OBS as a Top Choice for Screen Recorders</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-mastering-the-art-of-snapchat-sponsored-content/"><u>[Updated] In 2024, Mastering the Art of Snapchat Sponsored Content</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-lost-opportunities-instant-creative-ban-for-2024/"><u>[Updated] Lost Opportunities  Instant Creative Ban for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-best-picks-essential-websites-for-free-text-enhancements/"><u>2024 Approved  Best Picks  Essential Websites for Free Text Enhancements</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/best-gaming-setups-in-small-packages-a-comprehensive-guide/"><u>Best Gaming Setups in Small Packages: A Comprehensive Guide</u></a></li>
<li><a href="https://activate-lock.techidaily.com/best-ways-to-bypass-icloud-activation-lock-on-iphone-13ipadipod-by-drfone-ios/"><u>Best Ways to Bypass iCloud Activation Lock on iPhone 13/iPad/iPod</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/choosing-your-digital-sidekick-alexa-vs-google-assistant-determining-the-right-fit/"><u>Choosing Your Digital Sidekick: Alexa Vs. Google Assistant - Determining the Right Fit</u></a></li>
<li><a href="https://unlock-android.techidaily.com/complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-honor-90-lite-by-drfone-android/"><u>Complete Review & Guide to Techeligible FRP Bypass and More For Honor 90 Lite</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/comprehensive-d-link-default-passwords-compilation-july-2024-update/"><u>Comprehensive D-Link Default Passwords Compilation - July 2024 Update</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/decoding-bsod-errors-a-comprehensive-guide/"><u>Decoding BSOD Errors - A Comprehensive Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/discover-the-quintessential-5-apple-watch-tools-to-improve-your-rest/"><u>Discover the Quintessential 5 Apple Watch Tools to Improve Your Rest</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/essential-guide-to-choosing-a-motherboard-understanding-the-7-main-points/"><u>Essential Guide to Choosing a Motherboard: Understanding the 7 Main Points</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/expert-advice-for-multi-monitor-setup-with-any-computer/"><u>Expert Advice for Multi-Monitor Setup with Any Computer</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/expertly-curated-list-of-top-10-note-taking-solutions-for-enhanced-efficiency/"><u>Expertly Curated List of Top 10 Note-Taking Solutions for Enhanced Efficiency</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/fixing-your-pc-when-it-reports-a-missing-msvcr1ebf78-file-expert-tips-and-tricks/"><u>Fixing Your PC When It Reports a Missing MSVCR1ebf78 File: Expert Tips and Tricks</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/guide-to-repairing-silent-stereo-systems-and-boosting-audio-output/"><u>Guide to Repairing Silent Stereo Systems and Boosting Audio Output</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-establish-protective-measures-and-controls-on-your-childs-discord-account/"><u>How to Establish Protective Measures and Controls on Your Child’s Discord Account</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-link-up-a-printer-across-different-systems-a-comprehensive-walkthrough/"><u>How to Link Up a Printer Across Different Systems – A Comprehensive Walkthrough</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-make-an-awkward-potion-in-minecraft/"><u>How to Make an Awkward Potion in Minecraft</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-oneplus-ace-2-without-puk-codes-by-drfone-android/"><u>How To Unlock SIM Cards Of OnePlus Ace 2 Without PUK Codes</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-fake-snapchat-location-without-jailbreak-on-realme-gt-3-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fake Snapchat Location without Jailbreak On Realme GT 3 | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/innovative-techniques-for-adjusting-your-taskbars-appearance-in-windows-11/"><u>Innovative Techniques for Adjusting Your Taskbar's Appearance in Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-circle-everything-you-need-to-know-on-vivo-t2-pro-5g-drfone-by-drfone-virtual-android/"><u>Life360 Circle Everything You Need to Know On Vivo T2 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-pokemon-unite-the-ultimate-guide-for-pc-gamers/"><u>Mastering Pokemon Unite: The Ultimate Guide for PC Gamers</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/navigating-the-world-of-lg-channels-important-information-you-cant-miss/"><u>Navigating the World of LG Channels: Important Information You Can't Miss</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/personalizing-the-look-of-windows-11-with-easy-color-modifications-for-the-taskbar/"><u>Personalizing the Look of Windows 11 with Easy Color Modifications for the Taskbar</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/pros-and-cons-of-upgrading-to-ios-17-is-it-worth-it/"><u>Pros and Cons of Upgrading to iOS 17 - Is It Worth It?</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/protect-your-device-with-style-the-most-reliable-waterproof-phones-cases/"><u>Protect Your Device with Style: The Most Reliable Waterproof Phones Cases</u></a></li>
<li><a href="https://driver-install.techidaily.com/protected-logitech-camera-upgrade/"><u>Protected Logitech Camera Upgrade</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/sequential-screening-the-ultimate-guide-to-watching-taylor-swifts-filmography/"><u>Sequential Screening: The Ultimate Guide to Watching Taylor Swift's Filmography</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/sneak-peek-at-the-newly-rumored-features-and-cost-for-the-samsung-galaxy-z-fold-release-date-clues-included/"><u>Sneak Peek at the Newly Rumored Features and Cost for the Samsung Galaxy Z Fold – Release Date Clues Included!</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/solving-the-bootmgr-missing-boot-issue-a-step-by-step-guide/"><u>Solving the BOOTMGR Missing Boot Issue: A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/solving-the-xbox-one-no-video-output-problem-for-smooth-gaming-experience/"><u>Solving the Xbox One 'No Video Output' Problem for Smooth Gaming Experience</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/steps-to-stop-receiving-amber-warnings-on-android-phones/"><u>Steps to Stop Receiving AMBER Warnings on Android Phones</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-comprehensive-resource-on-how-netflix-is-revolutionizing-home-entertainment-services/"><u>The Comprehensive Resource on How Netflix Is Revolutionizing Home Entertainment Services</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-missing-gsdll32dll-errors-in-your-system/"><u>Troubleshooting Missing gsdll32.dll Errors in Your System</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ultimate-guide-mastering-the-art-of-background-blurring-during-a-google-meet/"><u>Ultimate Guide: Mastering the Art of Background Blurring During a Google Meet</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ultimate-troubleshooting-tips-getting-your-chromecasts-speaker-back-on-track/"><u>Ultimate Troubleshooting Tips: Getting Your Chromecast's Speaker Back on Track</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unboxing-the-nintendo-switch-everything-you-get-when-buying-one/"><u>Unboxing The Nintendo Switch – Everything You Get When Buying One</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unmasking-impostors-effective-strategies-for-spotting-fake-friend-invites/"><u>Unmasking Impostors: Effective Strategies for Spotting Fake Friend Invites</u></a></li>
<li><a href="https://extra-resources.techidaily.com/video-storage-assessment-for-128gb-drives/"><u>Video Storage Assessment for 128GB Drives</u></a></li>
</ul></div>
