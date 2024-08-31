---
title: Effective Disk Checks and Fixes with the ChkDsk Command on Windows
date: 2024-08-30T16:26:39.297Z
updated: 2024-08-31T16:26:39.297Z
categories:
  - BestProducts
description: This Article Describes Effective Disk Checks and Fixes with the ChkDsk Command on Windows
excerpt: This Article Describes Effective Disk Checks and Fixes with the ChkDsk Command on Windows
thumbnail: https://www.lifewire.com/thmb/33AQQZVzam_p173eQdHzdLwctNU=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/chkdsk-help-command-86bf1475305d4df1aeb9ab4846c2c60d.png
---

## Effective Disk Checks and Fixes with the ChkDsk Command on Windows

Close 

 Short for "check disk," the chkdsk command is a Command Prompt command used to check a specified disk and repair or recover data on the drive if necessary.

 Chkdsk also marks any damaged or malfunctioning sectors on the hard drive or disk as "bad" and recovers any information still intact.

##  Chkdsk Command Availability 

 The chkdsk command is available via Command Prompt in Windows 11, Windows 10, Windows 8, Windows 7, Windows Vista, and Windows XP operating systems.

 The chkdsk command is also available in[ Advanced Startup Options](https://www.lifewire.com/advanced-startup-options-2625805) and[ System Recovery Options](https://www.lifewire.com/system-recovery-options-2626021) . It works from within the Recovery Console in Windows 2000 and Windows XP. Chkdsk is a DOS Command, too, available in most versions of MS-DOS.

[  13 Best Free Hard Drive Testing Tools (July 2024) ](https://www.lifewire.com/free-hard-drive-testing-programs-2626183) 

 The availability of certain chkdsk command switches and other chkdsk command[ syntax](https://www.lifewire.com/what-is-syntax-2626014) might differ from operating system to operating system.

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
## Chkdsk Command Examples 

 Here are some of the different ways you might use the chkdsk command:

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Read-Only Mode 


 `chkdsk`

 Since no drive or additional options were entered in the above example, chkdsk simply runs in read-only mode.

![The CHKDSK command in read-only mode](https://www.lifewire.com/thmb/0p8t7Npad9Bk-vVhkXAlMhm1l-w=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/chkdsk-read-only-mode-45b119cdfaea4c89b2c716c32269497c.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If problems were found when running this simple chkdsk command, you'll want to make sure to use the example from below to correct any issues.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
###  Pre-Boot Scan & Fix 


 `chkdsk c: /r`

 In this example, the chkdsk command is used to perform an extensive check of the _C:_ drive to correct errors and locate recovery information from bad sectors. This is best used when running chkdsk from outside of Windows, like from a recovery disc where you need to specify which drive to scan.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Offline Repair 


 ` chkdsk c: /scan /forceofflinefix`

 This chkdsk command runs an _online scan_ on the _C:_ volume so that you don't have to dismount the volume to run the test, but instead of fixing any issues while the volume is active, the problems are sent to a queue that will be resolved in an offline repair.

### Fast Scan & Fix 


 ` chkdsk c: /r /scan /perf `

 In this example, chkdsk will fix problems on the _C:_ drive while you're using it and will use as many system resources as allowed so that it will run as quickly as possible.

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-web.techidaily.com/024-approved-turn-your-youtube-tracks-into-mp3-with-macos/"><u>[New] 2024 Approved  Turn Your YouTube Tracks Into MP3 with MacOS</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-must-try-titles-for-tranquil-touchscreen-time/"><u>[New] In 2024, Must-Try Titles for Tranquil Touchscreen Time</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-prime-screen-snaps-on-apple-devices-max-length-156/"><u>[New] In 2024, Prime Screen Snaps on Apple Devices (Max Length  156)</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-stability-excellence-the-top-10-gimbal-options-for-phones-and-cameras/"><u>[New] Stability Excellence  The Top 10 Gimbal Options for Phones & Cameras</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-transform-your-trip-diary-into-haul-video-hype/"><u>[New] Transform Your Trip Diary Into Haul Video Hype</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2023-insights-how-to-hunt-down-cool-vids-on-fb-for-2024/"><u>[Updated] 2023 Insights  How to Hunt Down Cool Vids on FB for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-step-by-step-mastery-of-video-filters-in-zoom/"><u>[Updated] Step-by-Step Mastery of Video Filters in Zoom</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-tech-triad-analysis-unraveling-the-vr-ar-mr-tapestry-for-2024/"><u>[Updated] Tech Triad Analysis  Unraveling the VR-AR-MR Tapestry for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-video-anonymization-strategies/"><u>[Updated] Video Anonymization Strategies</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-how-to-use-movie-maker-on-windows-8/"><u>2024 Approved  How to Use Movie Maker on Windows 8</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/a-guide-to-boosting-indoor-reception-for-digital-tv-channels/"><u>A Guide to Boosting Indoor Reception for Digital TV Channels</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/comprehensive-fixes-for-when-you-cant-locate-libexec32dll-on-your-pc/"><u>Comprehensive Fixes for When You Can't Locate libexec32.dll on Your PC</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/current-best-binge-worthy-content-on-your-local-max-station/"><u>Current Best Binge-Worthy Content on Your Local MAX Station</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/demystifying-digital-humor-the-essential-breakdown-of-meme-lingo-and-concepts/"><u>Demystifying Digital Humor: The Essential Breakdown of Meme Lingo and Concepts</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/detailed-instructions-casting-windows-workspace-from-pc-to-tv-via-google-chromecast/"><u>Detailed Instructions: Casting Windows Workspace From PC to TV Via Google Chromecast</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/discover-the-creme-de-la-creme-the-8-finest-mobile-games-available/"><u>Discover the Crème De La Crème: The 8 Finest Mobile Games Available</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/discover-the-top-10-mobile-apps-that-will-boost-your-teens-academic-skills/"><u>Discover the Top 10 Mobile Apps That Will Boost Your Teen's Academic Skills</u></a></li>
<li><a href="https://blog-min.techidaily.com/easiest-guide-how-to-clone-samsung-galaxy-f54-5g-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Easiest Guide How to Clone Samsung Galaxy F54 5G Phone? | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/elevate-your-engagement-a-step-by-step-for-commenting-with-gifs-on-instagram/"><u>Elevate Your Engagement: A Step-by-Step for Commenting with GIFs on Instagram</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/essential-tips-for-assessing-before-acquiring-refurbished-computers/"><u>Essential Tips for Assessing Before Acquiring Refurbished Computers</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/essentials-of-output-impedance-explanation-for-enthusiasts/"><u>Essentials of Output Impedance: Explanation for Enthusiasts</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/expert-advice-resolving-technical-hiccups-in-your-tiktok-experience/"><u>Expert Advice: Resolving Technical Hiccups in Your TikTok Experience</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/fixed-top-solutions-for-when-your-apple-watch-cant-access-cellular-networks-anymore/"><u>Fixed! Top Solutions for When Your Apple Watch Can't Access Cellular Networks Anymore</u></a></li>
<li><a href="https://data-wizards.techidaily.com/flashback-finds-restoring-camera-files/"><u>Flashback Finds: Restoring Camera Files</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-realme-narzo-n53-drfone-by-drfone-virtual-android/"><u>How Do I Stop Someone From Tracking My Realme Narzo N53? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-find-ispoofer-pro-activation-key-on-xiaomi-14-pro-drfone-by-drfone-virtual-android/"><u>How to Find iSpoofer Pro Activation Key On Xiaomi 14 Pro? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-driver-power-state-failure-error/"><u>How to Fix DRIVER POWER STATE FAILURE Error</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-vivo-y17s-drfone-by-drfone-virtual-android/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Vivo Y17s | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-how-to-bypass-infinix-hot-30-5g-frp-android-10111213-by-drfone-android/"><u>In 2024, Easy Guide How To Bypass Infinix Hot 30 5G FRP Android 10/11/12/13</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-gratis-global-photo-perfection-suite/"><u>In 2024, Gratis Global Photo Perfection Suite</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-realme-c67-4g-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>In 2024, How to Cast Realme C67 4G to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-circle-everything-you-need-to-know-on-vivo-y78plus-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Circle Everything You Need to Know On Vivo Y78+ | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-mastering-transitions-fading-techniques-in-premiere-pro/"><u>In 2024, Mastering Transitions  Fading Techniques in Premiere Pro</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/inside-scoop-on-nothing-phone-3-anticipated-launch-timeline-cost-estimates-and-specs-revealed/"><u>Inside Scoop on Nothing Phone 3: Anticipated Launch Timeline, Cost Estimates, and Specs Revealed</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/latest-techniques-to-successfully-install-wd-ses-device-driver-in-windows-operating-systems-post-2n11/"><u>Latest Techniques to Successfully Install WD SES Device Driver in Windows Operating Systems Post-2n11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/master-the-basics-of-asl-with-these-16-fantastic-free-learning-sites/"><u>Master the Basics of ASL with These 16 Fantastic Free Learning Sites</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-maps-on-ios-top-5-gps-apps-to-enhance-your-travel-experience/"><u>Mastering Maps on iOS: Top 5 GPS Apps to Enhance Your Travel Experience</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722878762367-mastering-pokemon-unite-the-ultimate-guide-for-pc-gamers/"><u>Mastering Pokémon Unite: The Ultimate Guide for PC Gamers</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-mac-video-editing-app-turn-clips-into-masterpieces/"><u>New 2024 Approved Mac Video Editing App Turn Clips Into Masterpieces</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/perfect-digital-viewing-strategies-to-elevate-in-house-reception-via-antennas/"><u>Perfect Digital Viewing: Strategies to Elevate In-House Reception via Antennas</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-guide-modifying-your-posts-after-sharing-on-instagram/"><u>Step-by-Step Guide: Modifying Your Posts After Sharing on Instagram</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-guide-successful-downloading-and-installation-of-latest-ios-enhancements/"><u>Step-by-Step Guide: Successful Downloading & Installation of Latest iOS Enhancements</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-essentials-of-bing-how-microsofts-search-engine-works-and-compares-to-google/"><u>The Essentials of Bing: How Microsoft's Search Engine Works and Compares to Google</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-wayback-machine-demystified-expert-advice-on-browsing-and-saving-archived-pages/"><u>The Wayback Machine Demystified: Expert Advice on Browsing and Saving Archived Pages</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-the-missing-wlanapidll-effective-solutions-and-tips/"><u>Troubleshooting the Missing 'WLANAPI.DLL': Effective Solutions and Tips</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unlocking-your-gmails-potential-with-easy-alias-creation-techniques/"><u>Unlocking Your Gmail's Potential with Easy Alias Creation Techniques</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unveiling-the-distinctions-between-ipad-mini-and-ipad-air-for-savvy-shoppers/"><u>Unveiling the Distinctions Between iPad Mini and iPad Air for Savvy Shoppers</u></a></li>
<li><a href="https://vp-tips.techidaily.com/unveiling-your-image-picsart-bg-erasure-technique/"><u>Unveiling Your Image  Picsart Bg Erasure Technique</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/verizons-top-pick-exclusive-device-exchange-promotions-for-month/"><u>Verizon's Top Pick: Exclusive Device Exchange Promotions for [Month]</u></a></li>
</ul></div>
