---
title: Effective Disk Checks and Fixes with the ChkDsk Command on Windows
date: 2024-12-02T01:49:32.385Z
updated: 2024-12-05T03:12:46.214Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/43goO8X0iX0?si=48Cqf6td2q_6T6h3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Chkdsk Command Availability 

 The chkdsk command is available via Command Prompt in Windows 11, Windows 10, Windows 8, Windows 7, Windows Vista, and Windows XP operating systems.

 The chkdsk command is also available in[ Advanced Startup Options](https://www.lifewire.com/advanced-startup-options-2625805) and[ System Recovery Options](https://www.lifewire.com/system-recovery-options-2626021) . It works from within the Recovery Console in Windows 2000 and Windows XP. Chkdsk is a DOS Command, too, available in most versions of MS-DOS.

[  13 Best Free Hard Drive Testing Tools (July 2024) ](https://www.lifewire.com/free-hard-drive-testing-programs-2626183) 

 The availability of certain chkdsk command switches and other chkdsk command[ syntax](https://www.lifewire.com/what-is-syntax-2626014) might differ from operating system to operating system.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## Chkdsk Command Examples 

 Here are some of the different ways you might use the chkdsk command:

### Read-Only Mode 

 `chkdsk`

 Since no drive or additional options were entered in the above example, chkdsk simply runs in read-only mode.

![The CHKDSK command in read-only mode](https://www.lifewire.com/thmb/0p8t7Npad9Bk-vVhkXAlMhm1l-w=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/chkdsk-read-only-mode-45b119cdfaea4c89b2c716c32269497c.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If problems were found when running this simple chkdsk command, you'll want to make sure to use the example from below to correct any issues.

###  Pre-Boot Scan & Fix 

 `chkdsk c: /r`

 In this example, the chkdsk command is used to perform an extensive check of the _C:_ drive to correct errors and locate recovery information from bad sectors. This is best used when running chkdsk from outside of Windows, like from a recovery disc where you need to specify which drive to scan.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ASUEYpqSP5E?si=0KOZxrTVexTuUkRn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Offline Repair 

 ` chkdsk c: /scan /forceofflinefix`

 This chkdsk command runs an _online scan_ on the _C:_ volume so that you don't have to dismount the volume to run the test, but instead of fixing any issues while the volume is active, the problems are sent to a queue that will be resolved in an offline repair.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/May-pLCUkEA?si=PGlcFZAlsp3S3beI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Fast Scan & Fix 

 ` chkdsk c: /r /scan /perf `

 In this example, chkdsk will fix problems on the _C:_ drive while you're using it and will use as many system resources as allowed so that it will run as quickly as possible.

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
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-ride-the-waves-with-top-tier-surf-cameras/"><u>[New] 2024 Approved Ride the Waves with Top-Tier Surf Cameras</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-2024-approved-audio-alchemy-made-accessible-discover-free-transformation-techniques-for-sound/"><u>[Updated] 2024 Approved Audio Alchemy Made Accessible Discover Free Transformation Techniques for Sound</u></a></li>
<li><a href="https://article-files.techidaily.com/bring-order-to-your-digital-memories-ios-album-structure-and-icloud-backup-synergy-for-2024/"><u>Bring Order to Your Digital Memories IOS Album Structure & iCloud Backup Synergy for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722880830271-discover-the-best-apple-iphone-maps-and-navigation-tools-today/"><u>Discover the Best Apple iPhone Maps and Navigation Tools Today</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/easy-instructions-on-how-to-disable-and-delete-windows-11-copilot-feature/"><u>Easy Instructions on How to Disable and Delete Windows 11 Copilot Feature</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/explore-the-best-sites-for-watching-movies-without-paying-a-dime/"><u>Explore the Best Sites for Watching Movies Without Paying a Dime</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-use-special-features-virtual-location-on-poco-f5-pro-5g-drfone-by-drfone-virtual-android/"><u>How To Use Special Features - Virtual Location On Poco F5 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-zte-nubia-z60-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For ZTE Nubia Z60 Ultra | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/macbook-users-secret-prevent-automatic-sleep-mode-with-a-simply-closed-lid/"><u>MacBook Users' Secret: Prevent Automatic Sleep Mode with a Simply Closed Lid</u></a></li>
<li><a href="https://fake-location.techidaily.com/methods-to-change-gps-location-on-poco-m6-pro-5g-drfone-by-drfone-virtual-android/"><u>Methods to Change GPS Location On Poco M6 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-canon-camcorder-video-editing-made-easy-tips-tricks-and-software/"><u>New Canon Camcorder Video Editing Made Easy Tips, Tricks, and Software</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-complete-process-of-chromecast-software-update-explained/"><u>The Complete Process of Chromecast Software Update Explained</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-missing-helperdll-solutions-and-tips/"><u>Troubleshooting Missing Helper.dll: Solutions and Tips</u></a></li>
<li><a href="https://solve-info.techidaily.com/webm-windowsmovwebm/"><u>WEBMへの変換: Windows上でMOV動画をどうやってWEBMに変更するか</u></a></li>
</ul></div>

