---
title: "DIY: Easy Ways to Tackle Error 0X80004005 on Your Computer System"
date: 2024-08-26T08:26:26.552Z
updated: 2024-08-27T08:26:26.552Z
categories:
  - BestProducts
description: "This Article Describes DIY: Easy Ways to Tackle Error 0X80004005 on Your Computer System"
excerpt: "This Article Describes DIY: Easy Ways to Tackle Error 0X80004005 on Your Computer System"
thumbnail: https://thmb.techidaily.com/174f7545789a7be7b3fd36a0fbdd896064abfcc58024b0d82a0647a125c54df6.jpg
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
<li><a href="https://tech-recovery.techidaily.com/lord-of-the-rings-master-your-journey-through-middle-earth-by-viewing-movies-sequentially/"><u>'Lord of the Rings': Master Your Journey Through Middle Earth by Viewing Movies Sequentially</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/month-exclusive-discounts-on-latest-apple-watch-models-you-cant-miss/"><u>[Month]: Exclusive Discounts on Latest Apple Watch Models You Can't Miss</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-innovative-practices-for-online-learning-archives/"><u>[New] 2024 Approved  Innovative Practices for Online Learning Archives</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-audience-allure-techniques-for-creating-engaging-snap-advertising/"><u>[New] Audience Allure  Techniques for Creating Engaging Snap Advertising</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-skype-or-discord-finding-your-ideal-chat-app-for-2024/"><u>[New] Skype or Discord  Finding Your Ideal Chat App for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-harmonize-your-favorites-creating-custom-youtube-playlists/"><u>[Updated] 2024 Approved  Harmonize Your Favorites  Creating Custom YouTube Playlists</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-breaking-the-silence-crafting-powerful-film-dialogues-for-2024/"><u>[Updated] Breaking the Silence  Crafting Powerful Film Dialogues for 2024</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-in-2024-the-rhythmic-future-tiktoks-most-iconic-rap-songs/"><u>[Updated] In 2024, The Rhythmic Future  TikTok's Most Iconic Rap Songs</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-real-time-vr-hardware-analysis/"><u>[Updated] Real-Time VR Hardware Analysis</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-the-ultimate-guide-to-crypto-conversion-best-generator-list/"><u>2024 Approved  The Ultimate Guide to Crypto Conversion – Best Generator List</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-ultimate-learning-sound-snatchers/"><u>2024 Approved  Ultimate Learning Sound Snatchers</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/2024s-most-popular-combo-deals-cable-modems-meet-wireless-routers/"><u>2024'S Most Popular Combo Deals: Cable Modems Meet Wireless Routers</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-vivo-s18-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On Vivo S18 without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/a-comprehensive-guide-to-duckduckgo-how-secure-is-it-really/"><u>A Comprehensive Guide to DuckDuckGo - How Secure Is It Really?</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/alternate-browsers-for-samsung-televisions-how-to-download-and-set-up/"><u>Alternate Browsers for Samsung Televisions - How To Download and Set Up</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/best-free-iphone-11-imei-checker-by-drfone-ios/"><u>Best Free iPhone 11 IMEI Checker</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/-automated-youtube-content-triggers-for-2024/"><u>Block Automated YouTube Content Triggers for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/1722017626680-chatgpt-desktop-app-on-hold-no-problem-explore-amazing-gratis-alternates-now/"><u>ChatGPT Desktop App on Hold? No Problem - Explore Amazing Gratis Alternates Now!</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/chatgpt-explained-a-look-into-its-corporate-parentage-and-founders/"><u>ChatGPT Explained: A Look Into Its Corporate Parentage and Founders</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/deciphering-snapchat-emojis-the-essential-handbook-for-digital-communication/"><u>Deciphering Snapchat Emojis: The Essential Handbook for Digital Communication</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/decoding-bsods-a-comprehensive-explanation-of-the-notorious-blue-screen-on-computers/"><u>Decoding BSODs: A Comprehensive Explanation of the Notorious Blue Screen on Computers</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/discover-the-ultimate-free-online-platforms-for-watching-sports/"><u>Discover the Ultimate Free Online Platforms for Watching Sports !</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/efficiently-capturing-footage-for-ideal-snaps-via-mac-for-2024/"><u>Efficiently Capturing Footage for Ideal Snaps via Mac for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/eliminate-wininetdll-errors-quick-fixes-and-tips-for-recovery/"><u>Eliminate wininet.dll Errors: Quick Fixes and Tips for Recovery</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722847547368-exclusive-scoop-the-price-release-date-and-tech-specs-of-the-new-apple-household-helper-bot-uncovered/"><u>Exclusive Scoop: The Price, Release Date, and Tech Specs of the New Apple Household Helper Bot Uncovered</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/fix-missing-gsl-errors-a-guide-to-repairing-gdxtools360dll-issues/"><u>Fix Missing GSL Errors: A Guide to Repairing gdxtools360.dll Issues</u></a></li>
<li><a href="https://howto.techidaily.com/full-guide-how-to-fix-connection-is-not-private-on-samsung-galaxy-s24-ultra-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Guide How To Fix Connection Is Not Private on Samsung Galaxy S24 Ultra | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-data-from-broken-iphone-12-pro-max-screen-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Recover Data from Broken iPhone 12 Pro Max Screen | Stellar</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-text-messages-from-oneplus-12r-to-new-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Text Messages from OnePlus 12R to New Phone | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-troubleshoot-and-fix-msstdfmtdll-absence-or-non-discovery-problems/"><u>How to Troubleshoot and Fix Msstdfmt.dll Absence or Non-Discovery Problems</u></a></li>
<li><a href="https://games-able.techidaily.com/ideal-high-refresh-rate-gaming-screens/"><u>Ideal High-Refresh Rate Gaming Screens</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-15-apps-to-hack-wifi-password-on-itel-s23-by-drfone-android/"><u>In 2024, Top 15 Apps To Hack WiFi Password On Itel S23</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/in-ear-apple-gadget-revealed-speculations-on-cost-launch-timeline-and-features/"><u>In-Ear Apple Gadget Revealed: Speculations on Cost, Launch Timeline, and Features</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/inside-scoop-on-teslas-driverless-taxi-prospective-pricing-release-schedule-specifications-and-hearsay-reports/"><u>Inside Scoop on Tesla's Driverless Taxi - Prospective Pricing, Release Schedule, Specifications, and Hearsay Reports</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ipad-showdown-discovering-the-unique-features-of-mini-and-air-variants/"><u>IPad Showdown: Discovering the Unique Features of Mini and Air Variants</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/is-investing-in-a-wi-fi-mesh-network-system-beneficial/"><u>Is Investing in a Wi-Fi Mesh Network System Beneficial?</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/lgs-latest-marvel-the-c9-smart-tv-a-dream-vision-for-tech-addicts-and-cinema-buffs/"><u>LG's Latest Marvel: The C9 Smart TV – A Dream Vision for Tech Addicts and Cinema Buffs</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/navigate-through-2024-a-comprehensive-list-of-top-free-racing-games-for-everyone/"><u>Navigate Through 2024: A Comprehensive List of Top Free Racing Games for Everyone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/networking-made-simple-how-to-link-external-drives-with-mac-os/"><u>Networking Made Simple: How to Link External Drives with Mac OS</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/pairing-multiple-bluetooth-audio-devices-with-a-single-source-a-comprehensive-guide/"><u>Pairing Multiple Bluetooth Audio Devices with a Single Source: A Comprehensive Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/seamless-integration-step-by-step-guide-for-the-new-surface-dock-driver-install/"><u>Seamless Integration: Step-by-Step Guide for the New Surface Dock Driver Install</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-guide-to-restoring-normal-functionality-from-a-blackout-screen-on-android-phones/"><u>Step-by-Step Guide to Restoring Normal Functionality From a Blackout Screen on Android Phones</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-instructions-for-erasing-your-twitch-presence-forever/"><u>Step-by-Step Instructions for Erasing Your Twitch Presence Forever</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-solutions-for-mending-a-nonfunctional-av-receiver/"><u>Step-by-Step Solutions for Mending a Nonfunctional A/V Receiver</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-importance-of-reducing-government-dependence-on-major-tech-companies-lessons-from-microsofts-recent-failures/"><u>The Importance of Reducing Government Dependence on Major Tech Companies: Lessons From Microsoft's Recent Failures</u></a></li>
<li><a href="https://os-tips.techidaily.com/the-ultimate-guide-securely-clearing-your-iphones-data-in-five-essential-steps-before-transfer/"><u>The Ultimate Guide: Securely Clearing Your iPhone's Data in Five Essential Steps Before Transfer</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-tutorial-for-changing-your-profile-icon-on-discord/"><u>The Ultimate Tutorial for Changing Your Profile Icon on Discord</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/thrifty-tech-choices-for-students-securing-discounted-rates-on-lenovo-equipment/"><u>Thrifty Tech Choices for Students: Securing Discounted Rates on Lenovo Equipment</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722876874865-top-10-must-have-note-taking-apps/"><u>Top 10 Must-Have Note-Taking Apps</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-text-message-problems-on-your-android-phone/"><u>Troubleshooting Text Message Problems on Your Android Phone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ultimate-order-of-transformers-movies-for-binge-watching/"><u>Ultimate Order of Transformers Movies for Binge-Watching</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unlock-the-power-of-casting-bridge-your-apple-tvplus-and-chromecast/"><u>Unlock the Power of Casting: Bridge Your Apple TV+ and Chromecast</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unlocking-time-explore-our-picked-4-free-digital-calendars/"><u>Unlocking Time: Explore Our Picked 4 Free Digital Calendars</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-mirror-your-media-how-to-flip-a-clip-in-final-cut-pro-quickly/"><u>Updated In 2024, Mirror Your Media How to Flip a Clip in Final Cut Pro Quickly</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722862532724-usb-tethering-not-working-heres-what-to-do-next/"><u>USB Tethering Not Working? Here's What to Do Next!</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/what-does-a-digital-video-recorder-do-unveiling-the-power-of-dvr-technology/"><u>What Does a Digital Video Recorder Do? Unveiling the Power of DVR Technology</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->