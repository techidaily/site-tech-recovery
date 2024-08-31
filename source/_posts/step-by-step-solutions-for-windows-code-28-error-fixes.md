---
title: Step-by-Step Solutions for Windows 'Code 28' Error Fixes
date: 2024-08-30T16:21:26.741Z
updated: 2024-08-31T16:21:26.741Z
categories:
  - BestProducts
description: This Article Describes Step-by-Step Solutions for Windows 'Code 28' Error Fixes
excerpt: This Article Describes Step-by-Step Solutions for Windows 'Code 28' Error Fixes
thumbnail: https://www.lifewire.com/thmb/by67YPqHc5dBpPbbI5keeWv2aMg=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/code-28-device-manager-error-3d84945a44e0467080dc5a77005500e2.png
---

## Error Code 0X80004005 Resolved? Step-by-Step Strategies to Fix It
 Error 0x80004005 is a type of unspecified Windows error code that usually appears as "Error Code 0x80004005\. Unspecified error." Error 0x80004005 may show up on its own or alongside other error messages. Sometimes, additional text may help you narrow down the source of the problem.

 Instructions in this article apply to[Windows 11](https://www.lifewire.com/windows-11-5188930) ,[Windows 10](https://www.lifewire.com/windows-10-2626217) ,[Windows 8](https://www.lifewire.com/windows-8-2626235) ,[Windows 7](https://www.lifewire.com/windows-7-2626265) ,[Windows Vista](https://www.lifewire.com/windows-vista-2626311) , and[Windows XP](https://www.lifewire.com/windows-xp-2626354) .

## What Causes Error Code 0x80004005?

 Error code 0x80004005 typically happens when you access shared folders or drives, use specific programs, or have a problem installing Windows updates. Here are the most common causes of error code 0x80004005:

* Problems with[Windows Update](https://www.lifewire.com/what-is-windows-update-2624597) .
* Moving or renaming files and folders.
* Windows notification issues.
* Problems opening or extracting[compressed files](https://www.lifewire.com/what-is-a-compressed-file-2625829) and folders.

 If you notice the error occurs when you use a specific program, the problem is likely[software](https://www.lifewire.com/what-is-software-4153107) related.

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
<li><a href="https://youtube-blog.techidaily.com/024-approved-easy-steps-how-to-master-the-best-of-9-free-youtube-logomakers/"><u>[New] 2024 Approved  Easy Steps  How to Master the Best of 9 Free YouTube Logomakers</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-the-hidden-dynamics-of-live-video-images-on-youtube/"><u>[New] 2024 Approved  The Hidden Dynamics of Live Video Images on YouTube</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-inspire-yourself-a-list-of-10-empowering-movie-experiences/"><u>[New] Inspire Yourself  A List of 10 Empowering Movie Experiences</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-elevate-your-videos-impact-with-customizable-youtube-thumbnails/"><u>[Updated] 2024 Approved  Elevate Your Video's Impact with Customizable YouTube Thumbnails</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-best-practices-in-converting-photos-into-movies/"><u>2024 Approved  Best Practices in Converting Photos Into Movies</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722875803460-best-sites-to-watch-your-favourite-music-videos-online-ranked/"><u>Best Sites to Watch Your Favourite Music Videos Online - Ranked!</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/bing-ai-chat-and-android-enhancing-text-input-experience/"><u>Bing AI Chat and Android: Enhancing Text Input Experience</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/boosting-your-photography-skills-master-zoom-on-iphoneipad/"><u>Boosting Your Photography Skills: Master Zoom on iPhone/iPad</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/can-you-unlock-apple-iphone-11-pro-after-forgetting-the-passcode-by-drfone-ios/"><u>Can You Unlock Apple iPhone 11 Pro After Forgetting the Passcode?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/detecting-synthetic-writing-an-in-depth-guide-to-using-gptzero/"><u>Detecting Synthetic Writing: An In-Depth Guide to Using GPTZero</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/digital-entertainment-preservation-online-tv-show-recording-101-for-2024/"><u>Digital Entertainment Preservation  Online TV Show Recording 101 for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/discover-the-seven-key-upgrades-elevating-googles-bard-ai-with-palm-2-technology/"><u>Discover the Seven Key Upgrades Elevating Google's Bard AI with PaLM 2 Technology</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-for-elusive-gpeditmsc-on-your-pc/"><u>Essential Fixes for Elusive 'Gpedit.msc' On Your PC</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/expert-techniques-to-restart-and-fix-airpods-that-are-not-working-properly/"><u>Expert Techniques to Restart and Fix AirPods That Are Not Working Properly</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/expertly-reviewed-visual-communication-tools-of-2024/"><u>Expertly Reviewed Visual Communication Tools of 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/exploring-the-features-of-telegram-messaging-app/"><u>Exploring the Features of Telegram Messaging App</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/harnessing-the-potential-of-artificial-intelligence-for-a-better-tomorrow/"><u>Harnessing the Potential of Artificial Intelligence for a Better Tomorrow</u></a></li>
<li><a href="https://win11.techidaily.com/has-windows-subsystem-for-linux-helped-linux-gain-desktop-market-share/"><u>Has Windows Subsystem for Linux Helped Linux Gain Desktop Market Share?</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-easily-register-and-start-your-x-journey-twitter-reborn-as-x/"><u>How to Easily Register and Start Your X Journey (Twitter Reborn as X)</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-legally-stream-the-movie-spider-man-no-way-home-anywhere-anytime/"><u>How to Legally Stream the Movie ‘Spider Man: No Way Home’ Anywhere, Anytime!</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-best-ways-on-how-to-unlockbypassswiperemove-poco-c51-fingerprint-lock-by-drfone-android/"><u>In 2024, Best Ways on How to Unlock/Bypass/Swipe/Remove Poco C51 Fingerprint Lock</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-can-you-unlock-iphone-12-pro-after-forgetting-the-passcode-by-drfone-ios/"><u>In 2024, Can You Unlock iPhone 12 Pro After Forgetting the Passcode?</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-remove-passcode-from-apple-iphone-12-complete-guide-drfone-by-drfone-ios/"><u>In 2024, How To Remove Passcode From Apple iPhone 12? Complete Guide | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-reducing-background-melodies-windowsmac-guide/"><u>In 2024, Reducing Background Melodies  Windows/Mac Guide</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-step-up-your-slow-mo-game-expert-guide-for-amazing-android-videos/"><u>In 2024, Step Up Your Slow Mo Game  Expert Guide for Amazing Android Videos</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/in-depth-look-at-snappy-driver-installer-software-version-113/"><u>In-Depth Look at Snappy Driver Installer Software, Version 1.13</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/inside-look-the-complete-guide-to-mastery-over-iphones-recovery-mode-entry-and-exit-techniques/"><u>Inside Look: The Complete Guide to Mastery Over iPhone's Recovery Mode Entry & Exit Techniques</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722859081674-iphone-tips-and-tricks-revealing-apps-you-cant-find-anymore/"><u>IPhone Tips & Tricks: Revealing Apps You Can’t Find Anymore!</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/making-sense-of-minecraft-realms-worth-your-time-and-coins/"><u>Making Sense of Minecraft Realms - Worth Your Time and Coins?</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/new-era-increased-customization-on-windows-11/"><u>New Era: Increased Customization on Windows 11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/no-remote-no-problem-guide-to-navigate-roku-by-other-means/"><u>No Remote, No Problem: Guide to Navigate Roku by Other Means</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/oculus-quest-2-elite-strap-with-battery-and-carrying-case-review/"><u>Oculus Quest 2 Elite Strap With Battery and Carrying Case Review</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/outstanding-movies-for-children-to-enjoy-on-netflix/"><u>Outstanding Movies for Children to Enjoy on Netflix</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/pc-command-center-for-google-home-devices-a-comprehensive-walkthrough/"><u>PC Command Center for Google Home Devices: A Comprehensive Walkthrough</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-instructions-to-remove-subtitles-from-your-amazon-video-content/"><u>Step-by-Step Instructions to Remove Subtitles From Your Amazon Video Content</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-solutions-for-correcting-the-infamous-code-28-on-your-pc/"><u>Step-by-Step Solutions for Correcting the Infamous Code 28 on Your PC</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/text-message-recovery-tips-for-iphone-android-and-more-a-complete-guide/"><u>Text Message Recovery Tips for iPhone, Android and More – A Complete Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-future-is-here-anticipating-teslas-self-driving-taxi-service/"><u>The Future Is Here: Anticipating Tesla's Self-Driving Taxi Service</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-solution-to-msvcrtdll-errors-on-your-pc/"><u>The Ultimate Solution to MSVCRT.DLL Errors on Your PC</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/to-own-or-stream-making-the-smart-choice-between-blu-ray-players-and-services/"><u>To Own or Stream: Making the Smart Choice Between Blu-Ray Players and Services</u></a></li>
<li><a href="https://buynow-help.techidaily.com/top-rated-17-inch-laptops-a-comprehensive-guide/"><u>Top Rated 17-Inch Laptops : A Comprehensive Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unstuck-with-your-ipad-password-woes-quick-fix-solutions/"><u>Unstuck with Your iPad Password Woes - Quick Fix Solutions</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->