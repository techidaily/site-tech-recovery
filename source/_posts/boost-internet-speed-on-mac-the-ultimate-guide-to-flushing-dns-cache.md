---
title: "Boost Internet Speed on Mac: The Ultimate Guide to Flushing DNS Cache"
date: 2024-08-19T13:32:19.337Z
updated: 2024-08-20T13:32:19.337Z
categories:
  - BestProducts
description: "This Article Describes Boost Internet Speed on Mac: The Ultimate Guide to Flushing DNS Cache"
excerpt: "This Article Describes Boost Internet Speed on Mac: The Ultimate Guide to Flushing DNS Cache"
thumbnail: https://thmb.techidaily.com/97a064f556a7bb067611e98f7f33b087d4344415697ae32a33a8f3d286a74da8.png
---

## Boost Internet Speed on Mac: The Ultimate Guide to Flushing DNS Cache
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### What to Know

* You can delete the DNS cache through Terminal. Press**Command** +**Space** to search for it.
* Enter this flush DNS command: **sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder**
* El Capitan and older Mac OS X systems use different commands to clear DNS.

 This article explains how to delete the[DNS cache](https://www.lifewire.com/what-is-a-dns-cache-817514) on a Mac.

<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Use the macOS Flush DNS Command

 If you’re experiencing internet connectivity issues, you may be able to fix them by resetting the[DNS](https://www.lifewire.com/what-is-dns-domain-name-system-2625855) cache with a[Terminal command](https://www.lifewire.com/mac-terminal-commands-4774997) . It should only take a few moments.  

1. [Open Terminal](https://www.lifewire.com/macos-terminal-4774149) . One quick way is to press**Command** +**Space** to launch[Spotlight](https://www.lifewire.com/use-spotlight-mac-4586951) . Then, type**Terminal** and select it from the results.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
![Terminal highlighted in Spotlight on a Mac.](https://www.lifewire.com/thmb/QGngs7Naa2bQVtWQWVaRG0K34yc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Terminal-6e4ba7528a4c4220a28542f84f214676.jpg)  
 You can also access Terminal by navigating to**Go** \>**Utilities** \>**Terminal** .
2. Type (or[copy and paste](https://www.lifewire.com/cut-copy-paste-on-mac-4427671) ) this command into Terminal and then press**Enter** :  
 `sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder`  
![Command highlighted in Terminal window](https://www.lifewire.com/thmb/S2U8vSx5U_PgZI2ZZR_uTWdGHcw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Command-e05651de1b2f44e7b99903d8f00910f5.jpg)  
 This command only works in[macOS](https://www.lifewire.com/what-is-macos-4691239) 10.12 Sierra and newer. If you have an older version, check the next section for the correct command.
3. Type your password and then press**return** . The DNS cache will be reset immediately, but there will be no message to that effect. When a new line appears, it indicates the command has been carried out.  
<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Entering a password in Terminal on a Mac.](https://www.lifewire.com/thmb/hvFn07N8xnjZ9XJQvgMitPvCTVQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Password-902f4015f672459598066969c7900b2f.jpg)  
The password will not appear in Terminal as you type it.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
### How to Flush DNS on Mac OS X

 The Mac OS X flush DNS command is different than the one used in modern versions of the operating system. Open Terminal and then enter the command that corresponds with your version:

* **El Capitan** : sudo killall -HUP mDNSResponder
* **Yosemite** : sudo discoveryutil udnsflushcaches
* **Lion, Mountain Lion, and Mavericks** : sudo killall -HUP mDNSResponder
* **Snow Leopard** : sudo dscacheutil -flushcache
* **Leopard** : sudo lookupd -flushcache
* **Tiger** : lookupd -flushcache

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Does Flushing DNS Do?

 Each time you access a website in your web browser, the URL you enter is sent to a[DNS server](https://www.lifewire.com/what-is-a-dns-server-2625854) for translation into an[IP address](https://www.lifewire.com/what-is-an-ip-address-2625920) . This information is stored in a cache on your Mac for easy retrieval in the future, hence the term_DNS cache_ .

 When you try to access a website you’ve been to recently, your Mac uses its DNS cache instead of checking with an actual DNS server. The web browser doesn’t have to go through the extra step of communicating with a remote DNS server, which results in less time between entering a website address and the website loading.

 If the local DNS cache is corrupt or outdated, it’s kind of like trying to use an old phone book that's been vandalized. Your web browser checks the cache to find an IP address for the website you’re trying to visit, and it finds either the wrong address or an unusable one. This can slow the process down or prevent websites or specific web page elements, like videos, from loading.

 When you flush your DNS cache, you instruct your Mac to delete its local DNS records. This in turn forces your web browser to check with a DNS server for fresh information. You should always flush your DNS cache after[changing the DNS servers on your Mac](https://www.lifewire.com/network-preference-pane-change-macs-dns-settings-2260394) . It can also be helpful if you’re having connectivity problems.  

 FAQ

* How do I check the DNS cache on a Mac?  
 Open the built-in Console log-viewer app on your Mac and type**any:mdnsresponder** into the search bar. Then, launch Terminal, type in**sudo killall –INFO mDNSResponder** , and press**Enter** or**Return** . Back in the Console app, you can view a list of cached DNS records.
* How do I clear the DNS cache on Windows 10?  
 To[clear the DNS cache on Windows 10](https://www.lifewire.com/flush-and-clear-windows-dns-cache-5095298) , open the Run dialog box, type in**ipconfig /flushdns** , and click**OK** . You can also use the same command in the Windows command prompt if you want more information on the process.
* What is DNS cache poisoning?  
 DNS cache poisoning, also known as DNS spoofing, is when someone deliberately enters false or incorrect information into a DNS cache. After the false information is input, future DNS queries will return incorrect responses and direct users to the wrong websites.

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
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-perfect-your-technique-recording-the-modern-presentation/"><u>[New] 2024 Approved  Perfect Your Technique  Recording the Modern Presentation</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-5-best-tips-for-enhancing-obs-studio-edits/"><u>[New] 5 Best Tips for Enhancing OBS Studio Edits</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-conquer-joining-on-tiktok-with-confidence-and-flair/"><u>[New] Conquer Joining on TikTok with Confidence and Flair</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-the-ultimate-guide-to-zero-price-virtual-gatherings-for-2024/"><u>[New] The Ultimate Guide to Zero-Price Virtual Gatherings for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-apex-fb-platforms-topping-the-10-list/"><u>[Updated] In 2024, Apex FB Platforms  Topping the 10 List</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-in-2024-premium-sites-summarized-acquiring-personal-preferences-in-ringtone-vids/"><u>[Updated] In 2024, Premium Sites Summarized  Acquiring Personal Preferences in Ringtone Vids</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-syncing-zoom-to-your-calendar-on-iphoneandroiddesktop/"><u>[Updated] In 2024, Syncing Zoom to Your Calendar on iPhone/Android/Desktop</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-the-enigmatic-functionality-of-the-blue-indicator-in-fb-messaging/"><u>[Updated] In 2024, The Enigmatic Functionality of the Blue Indicator in FB Messaging</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-master-image-correction-in-just-5-essential-android-editing-tools/"><u>[Updated] Master Image Correction in Just 5 Essential Android Editing Tools</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-set-up-your-first-google-meet-and-plan-it-for-2024/"><u>[Updated] Set Up Your First Google Meet & Plan It for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-the-ultimate-list-of-5-chrome-addons-to-download-facebook-videos-for-2024/"><u>[Updated] The Ultimate List of 5 Chrome Addons to Download Facebook Videos for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-avoiding-common-pitfalls-in-youtube-sponsorships-according-to-famebit/"><u>2024 Approved  Avoiding Common Pitfalls in YouTube Sponsorships, According to FameBit</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-harmonizing-messages-whatsapps-audio-update/"><u>2024 Approved  Harmonizing Messages  WhatsApp's Audio Update</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-restarting-disrupted-streams-on-fb-fixes-for-todays-broadcasters/"><u>2024 Approved  Restarting Disrupted Streams on FB  Fixes for Today's Broadcasters</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-step-by-step-guide-to-refine-igtv-titles-and-descs/"><u>2024 Approved  Step-by-Step Guide to Refine IGTV Titles & Descs</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-video-annotations-mastery-cutting-with-precision-and-style/"><u>2024 Approved  Video Annotations Mastery  Cutting with Precision & Style</u></a></li>
<li><a href="https://howto.techidaily.com/authentication-error-occurred-on-xiaomi-13t-here-are-10-proven-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Authentication Error Occurred on Xiaomi 13T? Here Are 10 Proven Fixes | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/brighten-your-pc-troubleshooting-steps-for-fixing-windows-11-blackout-issues/"><u>Brighten Your PC: Troubleshooting Steps for Fixing Windows 11 Blackout Issues</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/comprehensive-tips-for-fixing-the-critical-system-error-0x0000007b-blue-screen/"><u>Comprehensive Tips for Fixing the Critical System Error 0X0000007B Blue Screen</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/deciding-between-building-or-purchasing-your-own-computer-find-out-the-best-option/"><u>Deciding Between Building or Purchasing Your Own Computer - Find Out the Best Option!</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/decoding-the-battle-of-giants-how-does-ios-app-store-stack-against-google-play-store/"><u>Decoding the Battle of Giants: How Does iOS App Store Stack Against Google Play Store?</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/discover-the-new-apple-watch-series-8-expected-arrival-features-cost-and-latest-updates/"><u>Discover the New Apple Watch Series 8 - Expected Arrival, Features, Cost, and Latest Updates</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/dive-into-the-past-with-your-camera-roll-and-snapchat-for-2024/"><u>Dive Into the Past with Your Camera Roll and Snapchat for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/download-and-utilize-the-full-power-of-ez-grabber-quickly/"><u>Download and Utilize the Full Power of EZ Grabber Quickly</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/effective-strategies-to-address-boot-up-errors-fixing-issues-with-the-post-process/"><u>Effective Strategies to Address Boot Up Errors: Fixing Issues with the Post Process</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/emojis-explained-fascinating-tidbits-and-unexpected-truths-you-might-not-know/"><u>Emojis Explained: Fascinating Tidbits & Unexpected Truths You Might Not Know</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/enhance-workflow-the-essential-list-of-8-scheduling-apps/"><u>Enhance Workflow  The Essential List of 8 Scheduling Apps</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/fast-track-gaming-understanding-and-applying-the-teleport-functionality-within-minecraft/"><u>Fast Track Gaming: Understanding and Applying the Teleport Functionality Within Minecraft</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/fixing-missing-advrcntr2dll-errors-in-nero-program-easily-and-effectively/"><u>Fixing Missing advrcntr2.dll Errors in Nero Program Easily and Effectively</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/fixing-ssleay32dll-not-detected-a-comprehensive-troubleshooting-guide/"><u>Fixing Ssleay32.dll Not Detected - A Comprehensive Troubleshooting Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/getting-your-xbox-series-xs-headset-working-again-a-comprehensive-fix-guide/"><u>Getting Your Xbox Series X/S Headset Working Again: A Comprehensive Fix Guide</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-iphone-14-pro-without-losing-any-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade iPhone 14 Pro without Losing Any Data? | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-all-encompassing-review-djis-inspire-1-drone/"><u>In 2024, All-Encompassing Review  DJI's Inspire 1 Drone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-unlocking-apple-iphone-6s-plus-lock-screen-3-foolproof-methods-that-actually-work-by-drfone-ios/"><u>In 2024, Unlocking Apple iPhone 6s Plus Lock Screen 3 Foolproof Methods that Actually Work</u></a></li>
<li><a href="https://fox-that.techidaily.com/keep-your-iphone-connected-discover-5-tactics-to-maintain-stable-wi-fi-access/"><u>Keep Your iPhone Connected: Discover 5 Tactics to Maintain Stable Wi-Fi Access</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-the-art-of-spoofing-disguise-your-phones-real-location/"><u>Mastering the Art of Spoofing: Disguise Your Phone's Real Location</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-the-repair-of-nonfunctional-dvd-bd-and-cd-readers/"><u>Mastering the Repair of Nonfunctional DVD, BD & CD Readers</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/maximize-your-instagram-impact-with-these-must-use-hashtag-strategies/"><u>Maximize Your Instagram Impact with These Must-Use Hashtag Strategies</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/navigate-through-photoshop-errors-with-ease-resolving-the-full-scratch-disk-issue/"><u>Navigate Through Photoshop Errors with Ease: Resolving the Full Scratch Disk Issue</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/navigating-a-new-digital-landscape-detailed-steps-for-updating-tiktok-handle/"><u>Navigating a New Digital Landscape  Detailed Steps for Updating TikTok Handle</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/neroadvrctndll-error-solutions-how-to-restore-your-data-management-tools/"><u>nero.advrctn.dll Error Solutions: How to Restore Your Data Management Tools</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-essential-adobe-premiere-pro-extensions-free-and-paid-options/"><u>New 2024 Approved Essential Adobe Premiere Pro Extensions Free & Paid Options</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/oneplus-10-unboxed-a-deep-dive-into-upcoming-tech-rumors-preliminary-price-guess-and-projected-release-date-with-key-specs/"><u>OnePlus 10 Unboxed - A Deep Dive Into Upcoming Tech Rumors, Preliminary Price Guess & Projected Release Date with Key Specs</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/order-matters-how-to-enjoy-every-indy-movie-in-chronological-storyline/"><u>Order Matters - How To Enjoy Every Indy Movie In Chronological Storyline</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/quick-fixes-for-resolving-mfplatdll-not-found-windows-problems/"><u>Quick Fixes for Resolving 'mfplat.dll' Not Found Windows Problems</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/resolving-the-wininetdll-file-couldnt-be-loaded-issue-a-step-by-step-guide/"><u>Resolving the wininet.dll File Couldn't Be Loaded Issue: A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/shutting-off-the-latest-iphones-tips-and-tricks-for-model-15-pro-pro-max-edition/"><u>Shutting Off the Latest iPhones - Tips and Tricks for Model 15 Pro, Pro Max Edition</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/solving-search-is-not-working-in-windows-10-a-step-by-step-approach/"><u>Solving 'Search Is Not Working' In Windows 10 - A Step-by-Step Approach</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/stop-your-macs-auto-sleep-feature-with-these-simple-steps/"><u>Stop Your Mac's Auto-Sleep Feature with These Simple Steps</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-definitive-troubleshooting-guide-to-correcting-missing-msvcr80dll-errors/"><u>The Definitive Troubleshooting Guide to Correcting Missing msvcr80.dll Errors</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ethical-guide-finding-a-persons-email-in-todays-digital-age/"><u>The Ethical Guide: Finding a Person’s Email in Today’s Digital Age</u></a></li>
<li><a href="https://video-capture.techidaily.com/the-nvidia-method-to-perfect-gaming-replays-for-2024/"><u>The NVIDIA Method to Perfect Gaming Replays for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-pixiz-guide-to-blending-photography-and-motion-for-2024/"><u>The Pixiz Guide to Blending Photography and Motion for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-guide-fixing-code-39-error-messages-on/"><u>The Ultimate Guide: Fixing Code 39 Error Messages On</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-how-to-for-sourcing-ev-charging-points-on-google-maps/"><u>The Ultimate How-To for Sourcing EV Charging Points on Google Maps</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-list-of-the-best-and-free-movie-streamingdownloading-sites-selecting-the-top-11/"><u>The Ultimate List of the Best and Free Movie Streaming/Downloading Sites: Selecting the Top 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/troubleshooting-cs2-effective-solutions-to-combat-lag-frame-rate-issues-and-unresponsive-gameplay/"><u>Troubleshooting CS2: Effective Solutions to Combat Lag, Frame Rate Issues & Unresponsive Gameplay</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-missing-or-unseen-coredll-files-effectively/"><u>Troubleshooting Missing or Unseen core.dll Files Effectively</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-steps-correcting-mfc71dll-not-found-or-mismatched-file-error/"><u>Troubleshooting Steps: Correcting 'mfc71.dll Not Found or Mismatched File' Error</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-windows-11-what-to-do-if-your-system-fails-to-shut-down/"><u>Troubleshooting Windows 11: What To Do If Your System Fails to Shut Down</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/understanding-and-repairing-the-critical-process-failure-error-leading-to-bsod-in-win11/"><u>Understanding and Repairing the Critical Process Failure Error Leading to BSoD in Win11</u></a></li>
</ul></div>
