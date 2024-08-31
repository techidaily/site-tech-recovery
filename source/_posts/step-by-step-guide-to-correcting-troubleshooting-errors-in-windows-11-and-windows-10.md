---
title: Step-by-Step Guide to Correcting Troubleshooting Errors in Windows 11 and Windows 10
date: 2024-08-30T16:14:01.242Z
updated: 2024-08-31T16:14:01.242Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/08/52781763425_7caa012745_o.jpg
---

## Step-by-Step Guide to Correcting Troubleshooting Errors in Windows 11 and Windows 10

### Key Takeaways

* Try launching the troubleshooter from the Settings app on your Windows 11 or 10 PC.
* Restart the "Background Intelligent Transfer Service" and "Cryptographic Services" services.
* If the issue persists, fix Windows' damaged system files with DSM and SFC, try to use the troubleshooter in safe mode, or reset your Windows PC.

 If you’ve encountered an “An error occurred while troubleshooting” error while launching a troubleshooter, worry not, as fixing this issue is easy in most cases. Here’s how to do that on your Windows 11 or Windows 10 PC.

 After applying each fix, launch your troubleshooter to check if it’s working.

##  Run the Troubleshooter From Settings

 While Windows allows you to [launch the built-in troubleshooters](https://android-transfer.techidaily.com/in-2024-android-to-apple-how-to-transfer-photos-from-honor-play-40c-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/) from the Run dialog box, we recommend opening those tools from Settings, as this is where the tools are hosted.

 To do that, [open the Settings app](https://facebook-video-footage.techidaily.com/updated-2024-approved-5-easy-ways-to-multiply-your-youtube-follower-base/) by pressing Windows+i. On Windows 11, head into System > Troubleshoot > Other Troubleshooters. On Windows 10, go to Update & Security > Troubleshoot > Additional Troubleshooters.

 Find the troubleshooting tool to launch. On Windows 11, next to the troubleshooter, select "Run."

!['Run' highlighted for multiple troubleshooters in Windows 11 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-launch-troubleshooter-windows-11-settings-1.jpg) 

 On Windows 10, click the troubleshooter and choose "Run the Troubleshooter."

!['Run the Troubleshooter' highlighted for a troubleshooter in Windows 10 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-open-troubleshooter-windows-10-settings.jpg) 

 The tool will launch.

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Restart the Required Windows Services

 The built-in troubleshooters rely on various Windows services to function. These services might not be working correctly, causing an error. Give these services a reboot to fix the problem.

 Open the Run dialog box by pressing Windows+R, then type the following in the box and press Enter:

services.msc

 Find the service named "Background Intelligent Transfer Service." Right-click it and select "Restart."

!['Restart' highlighted for the 'Background Intelligent Transfer Service' service.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-restart-bits-service.jpg) 

 Similarly, right-click the "Cryptographic Services" service and select "Restart."

!['Restart' highlighted for the 'Cryptographic Services' service.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-restart-cryptographic-services-service.jpg) 

<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Close the Services window.

##  Fix Broken Troubleshooters

 It’s possible Windows’ system files are corrupted, causing the troubleshooters to malfunction. In this case, you must [repair the damaged core files](https://some-guidance.techidaily.com/twirl-forge-instruments-for-2024/) using the built-in System File Checker (SFC) tool.

 To do that, open the Start Menu, search for **Command Prompt**, and select "Run as Administrator."

!['Run as Administrator' highlighted for Command Prompt in Windows Search.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-open-cmd-as-admin.jpg) 

 In the User Account Control"(UAC) prompt, select "Yes."

 In Command Prompt, type the following command and press Enter. This command will download the files required to fix the broken system files.

DISM.exe /Online /Cleanup-image /Restorehealth

![The DISM command typed in Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6-run-dism-command-in-cmd.jpg) 

 Next up, run the following command to begin finding and repairing the damaged system files:

sfc /scannow

[Restart your Windows 11](https://screen-video-capture.techidaily.com/updated-in-2024-addressing-mute-problems-in-obs-live-recording/) or [Windows 10](https://article-posts.techidaily.com/comparing-the-creme-de-la-creme-gopro-hero5-black-to-hero4-silver-for-2024/) PC once it finishes.

##  Launch the Troubleshooter in Safe Mode

[Safe mode on Windows](https://video-capture.techidaily.com/new-essential-scripting-instant-stopwatch-integration-in-obs-for-2024/) lets you check if third-party apps are preventing you from performing your tasks. In safe mode, Windows only loads the essential files to boot the system, letting you check for interference from any third-party programs or drivers.

 To [start your Windows 11 PC in safe mode](https://buynow-marvelous.techidaily.com/unveiling-the-strong-battery-feature-in-moto-g-power-a-tech-review-insight/), go to Settings > System > Recovery. Next to "Advanced Startup," click "Restart Now."

!['Restart Now' highlighted for 'Advanced Startup' in Windows 11 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-advanced-restart-windows-11.jpg) 

 To [boot your Windows 10 PC in safe mode](https://screen-recording.techidaily.com/updated-leveraging-obs-establishing-an-efficient-countdown-clock/), head into Settings > Update & Security > Recovery. In the "Advanced Startup" section, click "Get Started."

!['Get Started' highlighted for 'Advanced Startup' in Windows 10 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/8-advanced-restart-windows-10.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
 When your PC reboots, navigate to Troubleshoot > Advanced Options > Startup Settings and select "Restart." Then, choose the number for safe mode to boot into that mode. When your PC enters safe mode, launch the troubleshooter you wanted to use.

 If the tool works, a third-party app is likely the culprit. Review the list of your installed apps and remove any suspicious ones. It’s quick and easy to [uninstall apps on Windows 11](https://youtube-docs.techidaily.com/ed-in-2024-strategies-for-using-youtube-to-boost-classroom-engagement/) and [Windows 10](https://tech-recovery.techidaily.com/top-savings-on-apple-watches-in-april/).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
##  Reset Windows

 If nothing else works, you can reset your Windows 11 or Windows 10 PC to the factory defaults. Resetting the system will fix any issues related to settings or corrupted files, but it should only be used as an last resort.

 You’ll lose your installed apps when you reset your PC. You’ll have the option to keep your personal files, though.

 To [reset a Windows 11 PC](https://facebook-video-footage.techidaily.com/new-blueprints-for-breaking-ground-in-edu-video-production-on-youtube-channels-for-2024/), navigate to Settings > System > Recovery. Next to "Reset This PC," click "Reset PC."

!['Reset PC' highlighted in Windows 11 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/9-reset-windows-11-pc.jpg) 

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
 To [reset a Windows 10 PC](https://instagram-videos.techidaily.com/fast-and-free-strategies-for-authenticity-in-insta-circles-for-2024/), go to Settings > Update & Security > Recovery. In the "Reset This PC" section, click "Get Started."

!['Get Started' highlighted in the 'Reset This PC' section of Windows 10 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/10-restart-windows-10-pc.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
 On the open window, select "Keep My Files" so Windows doesn’t delete your personal files. Then, follow the on-screen instructions to finish resetting your computer.

 Your troubleshooting tool should work once your machine is back to the default settings.

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
<li><a href="https://fox-info.techidaily.com/new-in-2024-the-ultimate-guide-to-capturing-stunning-time-lapses-on-galaxys/"><u>[New] In 2024, The Ultimate Guide to Capturing Stunning Time-Lapses on Galaxys</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-streamlined-methods-for-saving-videos-on-desktops-tablets-and-phones/"><u>[New] Streamlined Methods for Saving Videos on Desktops, Tablets & Phones</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/a-detailed-pokemon-go-pvp-tier-list-to-make-you-a-pro-trainer-for-apple-iphone-15-pro-drfone-by-drfone-virtual-ios/"><u>A Detailed Pokemon Go PvP Tier List to Make you a Pro Trainer For Apple iPhone 15 Pro | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/a-how-to-guide-on-bypassing-apple-iphone-14-icloud-activation-lock-by-drfone-ios/"><u>A How-To Guide on Bypassing Apple iPhone 14 iCloud Activation Lock</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/advanced-network-troubleshooting-with-tracert-expert-strategies-for-windows-users/"><u>Advanced Network Troubleshooting with Tracert: Expert Strategies for Windows Users</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/advanced-techniques-to-harness-power-of-telnet-command-line-interface-on-windows/"><u>Advanced Techniques to Harness Power of Telnet Command Line Interface on Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-poco-c51-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your Poco C51 Phone and Remove Locked Screen</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722899110928-anticipate-the-arrival-of-google-tvs-new-contender-price-expectations-release-dates-specs-and-secret-rumors/"><u>Anticipate the Arrival of Google TV's New Contender: Price Expectations, Release Dates, Specs & Secret Rumors</u></a></li>
<li><a href="https://android-location-track.techidaily.com/best-anti-tracker-software-for-nokia-c02-drfone-by-drfone-virtual-android/"><u>Best Anti Tracker Software For Nokia C02 | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/complete-guide-thawing-your-frozen-macbook-air/"><u>Complete Guide: Thawing Your Frozen MacBook Air</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/effective-remedies-for-microsofts-directxdirectinputdll-error-fixes/"><u>Effective Remedies for Microsoft's directx/directinput.dll Error Fixes</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/effective-repair-strategy-implemented-for-failed-igfx-module-now-functional/"><u>Effective Repair Strategy Implemented For Failed iGFX Module - Now Functional</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/essential-factors-to-evaluate-when-purchasing-a-video-recording-equipment/"><u>Essential Factors to Evaluate When Purchasing a Video Recording Equipment</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/expert-picks-leading-ups-battery-solutions-of-ebrary-2024/"><u>Expert Picks: Leading UPS Battery Solutions of Ebrary 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/expert-tips-on-how-to-unlink-gadgets-from-google-home-networks/"><u>Expert Tips on How to Unlink Gadgets From Google Home Networks</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/exploring-how-evs-surpass-gasoline-vehicles-in-performance-and-efficiency/"><u>Exploring How EVs Surpass Gasoline Vehicles in Performance and Efficiency</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/googles-next-smartwatch-leak-specs-expected-release-timeline-and-pricing-rumors/"><u>Google's Next Smartwatch Leak – Specs, Expected Release Timeline, and Pricing Rumors</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/guide-successfully-installing-the-fandango-app-on-your-amazon-fire-tv/"><u>Guide: Successfully Installing the Fandango App on Your Amazon Fire TV</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-recover-when-you-cant-find-the-necessary-python-file-python24dll/"><u>How to Recover When You Can't Find the Necessary Python File: python24.dll</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-zte-blade-a73-5g-phone-without-password-by-drfone-android/"><u>How To Unlock ZTE Blade A73 5G Phone Without Password?</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/max-streaming-service-recommendations-the-shows-you-cant-miss-right-now/"><u>Max Streaming Service Recommendations – The Shows You Can't Miss Right Now!</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/maximizing-visual-impact-how-to-ensure-your-image-fills-the-screen-on-instagram/"><u>Maximizing Visual Impact: How To Ensure Your Image Fills the Screen on Instagram</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/navigating-a-nintendo-switch-online-hiccup-you-or-the-network-at-fault/"><u>Navigating a Nintendo Switch Online Hiccup: You or the Network at Fault?</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/performance-and-features-breakdown-of-the-updated-apple-tv-gen-3-4k/"><u>Performance and Features Breakdown of the Updated Apple TV (Gen 3) 4K</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/playstation-portable-pre-release-guide-insights-into-release-timeline-price-range-tech-details-and-buying-options/"><u>PlayStation Portable Pre-Release Guide: Insights Into Release Timeline, Price Range, Tech Details & Buying Options</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-messages-from-v29-pro-by-fonelab-android-recover-messages/"><u>Possible solutions to restore deleted messages from V29 Pro</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/resolving-login-errors-on-microsoft-teams-is-there-a-widespread-outage-or-local-network-complication/"><u>Resolving Login Errors on Microsoft Teams: Is There a Widespread Outage or Local Network Complication?</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-guide-customizing-your-email-signature-on-godaddys-webmail/"><u>Step-by-Step Guide: Customizing Your Email Signature on Godaddy's Webmail</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-resolution-for-the-notorious-netflix-ui-800-3-error/"><u>Step-by-Step Resolution for the Notorious Netflix UI-800-3 Error</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-tutorial-resolving-phase0exception-stop-error-0x00000078-in-windows-systems/"><u>Step-by-Step Tutorial: Resolving PHASE0_EXCEPTION (Stop Error 0X00000078) in Windows Systems</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-magnificent-art-of-pokemon-go-streaming-on-oppo-reno-10-pro-5g-drfone-by-drfone-virtual-android/"><u>The Magnificent Art of Pokemon Go Streaming On Oppo Reno 10 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-guide-to-7-cost-free-virtual-fax-platforms/"><u>The Ultimate Guide to 7 Cost-Free Virtual Fax Platforms</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-pokemon-go-strategy-tips-and-tricks-for-trainers/"><u>The Ultimate Pokémon Go Strategy: Tips & Tricks for Trainers</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/top-5-non-rooted-android-auto-clicker-applications/"><u>Top 5 Non-Rooted Android Auto-Clicker Applications</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-chatgpt-effective-fixes-for-common-moderation-mishaps/"><u>Troubleshooting ChatGPT – Effective Fixes for Common Moderation Mishaps</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ultimate-guide-effective-steps-for-flat-screen-television-sanitation/"><u>Ultimate Guide: Effective Steps for Flat-Screen Television Sanitation</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/understanding-the-cognitive-features-embedded-in-android-systems/"><u>Understanding the Cognitive Features Embedded in Android Systems</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unveiling-the-secrets-behind-facebook-from-startup-to-global-phenomenon-and-notable-elements/"><u>Unveiling the Secrets Behind Facebook: From Startup to Global Phenomenon & Notable Elements</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-from-footage-to-film-how-to-edit-gopro-videos-with-ease-on-macbook-for-2024/"><u>Updated From Footage to Film How to Edit GoPro Videos with Ease on MacBook for 2024</u></a></li>
</ul></div>
