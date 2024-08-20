---
title: Step-by-Step Guide for Resolving Error Code 0X80070570 in Windows Systems
date: 2024-08-19T13:05:28.536Z
updated: 2024-08-20T13:05:28.536Z
categories:
  - BestProducts
description: This Article Describes Step-by-Step Guide for Resolving Error Code 0X80070570 in Windows Systems
excerpt: This Article Describes Step-by-Step Guide for Resolving Error Code 0X80070570 in Windows Systems
thumbnail: https://www.lifewire.com/thmb/fTVqkNhkTrolvSDPKJBYvvpwms0=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/error-0x80070570-featured-d6611f4bacfa477bab911aacf81fb5b9.jpg
---

## Error Code 0X80004005 Resolved? Step-by-Step Strategies to Fix It
 Error 0x80004005 is a type of unspecified Windows error code that usually appears as "Error Code 0x80004005\. Unspecified error." Error 0x80004005 may show up on its own or alongside other error messages. Sometimes, additional text may help you narrow down the source of the problem.

 Instructions in this article apply to[Windows 11](https://www.lifewire.com/windows-11-5188930) ,[Windows 10](https://www.lifewire.com/windows-10-2626217) ,[Windows 8](https://www.lifewire.com/windows-8-2626235) ,[Windows 7](https://www.lifewire.com/windows-7-2626265) ,[Windows Vista](https://www.lifewire.com/windows-vista-2626311) , and[Windows XP](https://www.lifewire.com/windows-xp-2626354) .

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Causes Error Code 0x80004005?

 Error code 0x80004005 typically happens when you access shared folders or drives, use specific programs, or have a problem installing Windows updates. Here are the most common causes of error code 0x80004005:

* Problems with[Windows Update](https://www.lifewire.com/what-is-windows-update-2624597) .
* Moving or renaming files and folders.
* Windows notification issues.
* Problems opening or extracting[compressed files](https://www.lifewire.com/what-is-a-compressed-file-2625829) and folders.

 If you notice the error occurs when you use a specific program, the problem is likely[software](https://www.lifewire.com/what-is-software-4153107) related.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Fix Error Code 0x80004005

 Follow these steps in the order presented to troubleshoot error code 0x80004005:

1. [Run the Windows Update troubleshooter](https://support.microsoft.com/help/4027322/windows-update-troubleshooter) . The error can happen when an automatic Windows Update fails, or when files downloaded by Windows Update are corrupted. On Windows 7 or later, the easiest[way to fix problems with Windows updates](https://www.lifewire.com/how-to-fix-problems-caused-by-windows-updates-2625775) is to run the built-in automatic troubleshooter.
2. Delete everything in the Windows Update download folder. If the automatic troubleshooter does not fix the problem, open Windows[File Explorer](https://www.lifewire.com/what-is-a-file-manager-4589189) and navigate to**C:\\Windows\\SoftwareDistribution** , for Windows 11 or**C:\\Windows\\SoftwareDistribution\\Download** for earlier Windows versions, then delete everything inside the folder.
3. [Run Windows Update](https://www.lifewire.com/how-to-check-for-install-windows-updates-2624596) . If the problem is related to Windows Update, you may have to finish downloading and installing updates. After running the troubleshooter and manually deleting the files in the Windows Update folder, run Windows Update again.
4. [Delete temporary files](https://www.lifewire.com/how-to-delete-temporary-files-in-windows-2624709) . In some cases, a corrupt temporary file can cause error 0x80004005\. Use the Windows Disk Cleanup tool or type**%temp%** in the Windows search bar to find the**Temp** folder and delete everything inside it.
5. [Disable Outlook mail notifications](https://www.lifewire.com/configure-outlook-email-notifications-1173647) . The error code can occur when[Microsoft Outlook](https://www.lifewire.com/microsoft-outlook-4164620) attempts to notify you of new messages. If disabling this feature fixes the problem, then try[starting Outlook in Safe Mode](https://www.lifewire.com/outlook-safe-mode-4164302) . If that works, a simple re-install might fix your problem.
6. [Disable Windows Defender](https://www.lifewire.com/turn-off-windows-defender-4165378) . In some cases,[antivirus](https://www.lifewire.com/what-is-antivirus-software-152947) software can detect a false positive in connection with the Microsoft Outlook app. If you experience error code 0x80004005 when using Microsoft Outlook, and disabling notifications did not help, turning off antivirus software may fix the problem. Also,[disable Norton Antivirus](https://www.lifewire.com/disable-norton-antivirus-4589389) and other third-party antivirus programs you use.  
 Disabling antivirus software leaves the system vulnerable to malware. Try different[free antivirus programs](https://www.lifewire.com/best-free-antivirus-software-4151895) to find one that doesn't conflict with the applications you use.
7. [Use a different unzip program](https://www.lifewire.com/free-unzip-programs-1356643) . If you see the error code when extracting or opening compressed files (like[.zip](https://www.lifewire.com/zip-file-2622675) or[.rar](https://www.lifewire.com/rar-file-2622216) files), use a different extraction tool.
8. Re-register jdscript.dll and vbscript.dll. If you still see error 0x80004005 after trying to unzip files with other extraction tools, then re-registering these two[dynamic link libraries](https://www.lifewire.com/what-is-a-dll-file-2625852) (DLLs) may help.  
[Open the Command Prompt](https://www.lifewire.com/how-to-open-command-prompt-2618089) as an administrator, type**regsvr32 jscript.dll** , then press the**Enter** key. Then, type**regsvr32 vbscript.dll** and press**Enter** .
9. [Add a key to the Windows Registry](https://www.lifewire.com/how-to-add-change-delete-registry-keys-values-2625145) . If you suspect error 0x80004005 in conjunction with copying or moving files,[open the Windows Registry Editor](https://www.lifewire.com/how-to-open-registry-editor-2625150) and go to **HKLM\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** .  
   * On a[32-bit](https://www.lifewire.com/32-bit-64-bit-2624554) system, create a new**DWORD** [registry value](https://www.lifewire.com/what-is-a-registry-value-2626042) called**LocalAccountTokenFilterPolicy** .  
   * On a 64-bit system, create a**QWORD** registry value called**LocalAccountTokenFilterPolicy** .  
 In both cases, set the value to**numeric 1** (on), then select**OK** . After that,[restart the Windows PC](https://www.lifewire.com/how-to-reboot-a-computer-2624568) to see if the problem is fixed.  
<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![A screenshot of Windows Registry with the Numerical Value and OK button highlighted](https://www.lifewire.com/thmb/OqNevLWWV50Z3qSb36MeYz61-8Y=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/001-how-to-fix-error-code-0x80004005-4689559-7b5e14fd0ef942718355465faefbcb77.jpg)  
 Don't delete or change anything in the Windows registry unless you know what you're doing.
10. Contact support. If none of these fixes work, or if you don't want to make changes to the Windows Registry, contact customer support for your Windows PC. The manufacturer may have potential solutions.

[8 Things to Consider Before Buying a Desktop PC](https://www.lifewire.com/best-desktop-pcs-4045927)

 FAQ

* How do I fix error code ws-37398-0?  
 Error code ws-37398-0 is a PS5 error code that occurs during PlayStation network server outages. Because the error stems from PlayStation, there's nothing you can do to fix it. You must wait until the network outage resolves.
* How do I fix error code 4b538e50 2k21?  
 This error occurs in the games_NBA 2K21_ and_NBA 2K22_ . It usually means your game files are outdated, and there's a pending file download or patch. To fix it, check to see if your computer or console still has game files to download, and wait for the downloading process to complete.
* How do I fix a code 10 error in Windows?  
 To[fix code 10 errors](https://www.lifewire.com/how-to-fix-code-10-errors-2623181) , which indicate that Device Manager can't start a hardware device, first try restarting your computer. If you recently installed a device, try uninstalling and reinstalling its drivers, or see if there are driver updates to install. You can also try installing the latest Windows update.

Was this page helpful?

Thanks for letting us know!

 Get the Latest Tech News Delivered Every Day

[Subscribe](https://www.lifewire.com/#)

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
<li><a href="https://article-posts.techidaily.com/new-virtual-realm-highs-the-best-iphoneandroid-apps-for-2024/"><u>[New] Virtual Realm Highs  The Best iPhone/Android Apps for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-navigating-backward-image-hunt-on-the-worlds-largest-social-site/"><u>[Updated] In 2024, Navigating Backward Image Hunt on the World's Largest Social Site</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-navigating-name-change-in-google-meet-laptopmobile/"><u>[Updated] Navigating Name Change in Google Meet (Laptop/Mobile)</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-prime-collection-of-gopro-complements/"><u>[Updated] The Prime Collection of GoPro Complements</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-eyedome-hd-top-quality-chromeos-snapping/"><u>2024 Approved  EyeDome HD  Top Quality ChromeOS Snapping</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-how-to-turn-videos-reverse-wave-style-on-snapchat/"><u>2024 Approved  How to Turn Videos Reverse-Wave Style on Snapchat</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/all-about-sony-2024-announcements-cutting-edge-news-and-inside-scoop-uncovered/"><u>All About Sony 2024: Announcements, Cutting-Edge News & Inside Scoop Uncovered</u></a></li>
<li><a href="https://tech-revival.techidaily.com/boosting-your-freelance-career-top-6-strategies-with-chatgpt/"><u>Boosting Your Freelance Career: Top 6 Strategies with ChatGPT</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/cat5-versus-cat6-cabling-what-sets-them-apart/"><u>Cat5 versus Cat6 Cabling - What Sets Them Apart?</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/customizing-your-pc-a-step-by-step-guide-to-changing-taskbar-colors-on-windows-10/"><u>Customizing Your PC: A Step-by-Step Guide to Changing Taskbar Colors on Windows 10</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/decode-and-defeat-a-comprehensive-guide-to-fixing-kernel-data-faults/"><u>Decode and Defeat: A Comprehensive Guide to Fixing Kernel Data Faults</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/decoding-a-missing-page-error-http-404-and-remedies-for-quick-recovery/"><u>Decoding a Missing Page Error (HTTP 404) & Remedies for Quick Recovery</u></a></li>
<li><a href="https://article-posts.techidaily.com/decoding-the-secrets-to-proficient-cd-ripping-and-burning-with-win-media-for-2024/"><u>Decoding the Secrets to Proficient CD Ripping & Burning with Win, Media for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/desktops-uncluttered-remove-win11s-spotlight-symbol/"><u>Desktops Uncluttered: Remove Win11's Spotlight Symbol</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/effective-methods-to-resolve-haldll-error-messages-on-various-windows-operating-systems/"><u>Effective Methods to Resolve Hal.dll Error Messages on Various Windows Operating Systems</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/exploring-the-hype-around-new-google-pixel-timepiece-price-predictions-launch-windows-and-rumored-innovations/"><u>Exploring The Hype Around New Google Pixel Timepiece - Price Predictions, Launch Windows & Rumored Innovations</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/fixing-a-deactivated-or-disabled-instagram-presence-what-now/"><u>Fixing a Deactivated or Disabled Instagram Presence: What Now?</u></a></li>
<li><a href="https://windows11.techidaily.com/ftdibussys-and-windows-exploring-the-memory-integrity-dilemshift/"><u>Ftdibus.sys and Windows: Exploring the Memory Integrity Dilemshift</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-enjoy-hulu-on-demand-with-your-lg-smart-television-easy-steps/"><u>How to Enjoy Hulu On Demand with Your LG Smart Television - Easy Steps</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-forgotten-pin-of-your-itel-s23-by-drfone-android/"><u>How to Remove Forgotten PIN Of Your Itel S23</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-stream-anything-from-motorola-edge-40-neo-to-apple-tv-drfone-by-drfone-android/"><u>How To Stream Anything From Motorola Edge 40 Neo to Apple TV | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-charming-chic-explore-the-hottest-discothemes-by-curators/"><u>In 2024, Charming Chic  Explore the Hottest DiscoThemes by Curators</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-free-cross-platform-4k-playback-tools-for-win-and-os-x-devices/"><u>In 2024, Free, Cross-Platform 4K Playback Tools for Win & OS X Devices</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-realme-c55-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Realme C55 to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-ultimate-routine-for-large-files-journey-from-iphones-to-macs/"><u>In 2024, The Ultimate Routine for Large Files' Journey From iPhones to Macs</u></a></li>
<li><a href="https://driver-install.techidaily.com/m2-controller-setup-guide/"><u>M.2 Controller Setup Guide</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721471536200-master-the-art-of-perfect-spelling-on-your-iphone-fixing-6-common-autocorrect-faults/"><u>Master the Art of Perfect Spelling on Your iPhone – Fixing 6 Common Autocorrect Faults</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/navigate-the-audio-world-with-these-5-crucial-tips-on-buying-quality-stereo-speakers/"><u>Navigate the Audio World with These 5 Crucial Tips on Buying Quality Stereo Speakers</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-guide-complete-factory-reset-on-your-dell-computer/"><u>Step-by-Step Guide: Complete Factory Reset on Your Dell Computer</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-guide-removing-your-likes-across-all-tracks-in-spotify/"><u>Step-by-Step Guide: Removing Your Likes Across All Tracks in Spotify</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-advantages-of-evs-over-gasoline-vehicles-understanding-their-superior-performance/"><u>The Advantages of EVs Over Gasoline Vehicles: Understanding Their Superior Performance</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/1722730015677-the-apeman-c450-reviewed-budget-dashcam-revealed-for-safety-enthusiasts/"><u>The Apeman C450 Reviewed - Budget Dashcam Revealed for Safety Enthusiasts</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-meaning-behind-your-ps4-controller-light-patterns-unraveling-the-secrets-of-blue-white-red-and-orange-blinks/"><u>The Meaning Behind Your PS4 Controller Light Patterns: Unraveling the Secrets of Blue, White, Red, and Orange Blinks</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-list-of-9-crucial-tech-devices-for-academic-success/"><u>The Ultimate List of 9 Crucial Tech Devices for Academic Success</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/top-9-solutions-for-non-charging-airpods-woes/"><u>Top 9 Solutions for Non-Charging AirPods Woes</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/understanding-the-battle-between-neo-qled-vs-oled-televisions/"><u>Understanding the Battle Between Neo QLED vs OLED Televisions</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unraveling-how-espnpluss-cutting-edge-streaming-platform-enhances-your-sports-viewing-journey/"><u>Unraveling How ESPN+'s Cutting-Edge Streaming Platform Enhances Your Sports Viewing Journey</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722878425073-unveiling-the-secrets-of-metro-by-t-mobiles-extensive-coverage-and-unlimited-options/"><u>Unveiling the Secrets of Metro by T-Mobile's Extensive Coverage and Unlimited Options.</u></a></li>
<li><a href="https://network-issues.techidaily.com/winos-graphics-fault-ui-stops-resolved-quickly/"><u>WinOS Graphics Fault, UI Stops (Resolved Quickly)</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/your-ultimate-checklist-getting-the-fandango-app-running-on-fire-stick/"><u>Your Ultimate Checklist: Getting the Fandango App Running on Fire Stick</u></a></li>
</ul></div>
