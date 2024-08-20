---
title: "Perfect Start: Key Setup Procedures to Follow with Your Freshly Unboxed Machine"
date: 2024-08-19T13:12:53.975Z
updated: 2024-08-20T13:12:53.975Z
categories:
  - BestProducts
description: "This Article Describes Perfect Start: Key Setup Procedures to Follow with Your Freshly Unboxed Machine"
excerpt: "This Article Describes Perfect Start: Key Setup Procedures to Follow with Your Freshly Unboxed Machine"
thumbnail: https://thmb.techidaily.com/efe03172267db8e41dde950b174798601940a22588399da557fc77a3f3ce0d36.jpeg
---

## Mac Users Rejoice: How to Reset Your DNS Records Effortlessly
<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### What to Know

* You can delete the DNS cache through Terminal. Press**Command** +**Space** to search for it.
* Enter this flush DNS command: **sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder**
* El Capitan and older Mac OS X systems use different commands to clear DNS.

 This article explains how to delete the[DNS cache](https://www.lifewire.com/what-is-a-dns-cache-817514) on a Mac.

## How to Use the macOS Flush DNS Command

 If you’re experiencing internet connectivity issues, you may be able to fix them by resetting the[DNS](https://www.lifewire.com/what-is-dns-domain-name-system-2625855) cache with a[Terminal command](https://www.lifewire.com/mac-terminal-commands-4774997) . It should only take a few moments.  

1. [Open Terminal](https://www.lifewire.com/macos-terminal-4774149) . One quick way is to press**Command** +**Space** to launch[Spotlight](https://www.lifewire.com/use-spotlight-mac-4586951) . Then, type**Terminal** and select it from the results.  
<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
![Terminal highlighted in Spotlight on a Mac.](https://www.lifewire.com/thmb/QGngs7Naa2bQVtWQWVaRG0K34yc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Terminal-6e4ba7528a4c4220a28542f84f214676.jpg)  
 You can also access Terminal by navigating to**Go** \>**Utilities** \>**Terminal** .
2. Type (or[copy and paste](https://www.lifewire.com/cut-copy-paste-on-mac-4427671) ) this command into Terminal and then press**Enter** :  
 `sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder`  
<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Command highlighted in Terminal window](https://www.lifewire.com/thmb/S2U8vSx5U_PgZI2ZZR_uTWdGHcw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Command-e05651de1b2f44e7b99903d8f00910f5.jpg)  
 This command only works in[macOS](https://www.lifewire.com/what-is-macos-4691239) 10.12 Sierra and newer. If you have an older version, check the next section for the correct command.
3. Type your password and then press**return** . The DNS cache will be reset immediately, but there will be no message to that effect. When a new line appears, it indicates the command has been carried out.  
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
![Entering a password in Terminal on a Mac.](https://www.lifewire.com/thmb/hvFn07N8xnjZ9XJQvgMitPvCTVQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Password-902f4015f672459598066969c7900b2f.jpg)  
The password will not appear in Terminal as you type it.

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-essential-tips-for-fbx-based-game-recording/"><u>[New] 2024 Approved  Essential Tips for FBX-Based Game Recording</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-filming-flicks-guide-for-pc-mac-smartphone-recording/"><u>[Updated] 2024 Approved  Filming Flicks  Guide for PC, Mac, Smartphone Recording</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-step-by-step-methods-for-sharing-igtv-in-stories/"><u>[Updated] 2024 Approved  Step-by-Step Methods for Sharing IGTV in Stories</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-mastering-color-changes-11-essential-tips/"><u>[Updated] Mastering Color Changes  11 Essential Tips</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/all-eyes-on-the-future-of-urban-mobility-sonys-afeela-car-revealed-prices-release-dates-and-features-uncovered/"><u>All Eyes on the Future of Urban Mobility: Sony's Afeela Car Revealed – Prices, Release Dates & Features Uncovered</u></a></li>
<li><a href="https://unlock-android.techidaily.com/can-i-bypass-a-forgotten-phone-password-of-xiaomi-14-by-drfone-android/"><u>Can I Bypass a Forgotten Phone Password Of Xiaomi 14?</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/comprehensive-overview-of-what-ray-tracing-entails/"><u>Comprehensive Overview of What Ray Tracing Entails</u></a></li>
<li><a href="https://tech-haven.techidaily.com/creative-crusade-why-artists-like-sarah-silverman-are-challenging-openai-and-meta-in-court-over-their-use-of-ai-technologies/"><u>Creative Crusade: Why Artists Like Sarah Silverman Are Challenging OpenAI and Meta in Court Over Their Use of AI Technologies</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/diagnosing-and-fixing-504-timeout-errors-for-smoother-web-navigation/"><u>Diagnosing and Fixing 504 Timeout Errors for Smoother Web Navigation</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/easy-installation-tips-for-getting-windows-10-running-on-a-new-disk-unit/"><u>Easy Installation Tips for Getting Windows 10 Running on a New Disk Unit</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/easy-solutions-to-correct-the-missing-ieseriesdll-error-in-internet-explorer/"><u>Easy Solutions to Correct the Missing ieseries.dll Error in Internet Explorer</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/essential-tips-to-repair-msvcp100dll-error-not-found-or-unavailable-problem/"><u>Essential Tips to Repair 'msvcp100.dll' Error - Not Found or Unavailable Problem</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/expert-advice-solutions-for-overcoming-facetime-screen-blackouts/"><u>Expert Advice: Solutions for Overcoming FaceTime Screen Blackouts</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/expert-tips-on-fixing-missing-or-not-found-d3dx927dll-issues/"><u>Expert Tips on Fixing Missing or Not Found d3dx9_27.dll Issues</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/exploring-our-picks-the-8-leading-multi-sim-communication-tools/"><u>Exploring Our Picks: The 8 Leading Multi-SIM Communication Tools</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/exploring-the-revolutionary-ai-understanding-chatgpt/"><u>Exploring the Revolutionary AI: Understanding ChatGPT</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-effortlessly-move-your-digital-album-collection-from-google-photos-to-apples-icloud/"><u>How to Effortlessly Move Your Digital Album Collection From Google Photos to Apple's iCloud</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-files-after-iphone-15-plus-factory-reset-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Recover Files after iPhone 15 Plus Factory Reset? | Stellar</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/identifying-inauthentic-connections-the-guide-to-detecting-phony-social-network-invites/"><u>Identifying Inauthentic Connections: The Guide to Detecting Phony Social Network Invites</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-iphone-is-disabled-here-is-the-way-to-unlock-disabled-iphone-se-2022-drfone-by-drfone-ios/"><u>In 2024, iPhone Is Disabled? Here Is The Way To Unlock Disabled iPhone SE (2022) | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-quintessential-10-virtual-brawls/"><u>In 2024, Quintessential 10 Virtual Brawls</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/insightful-methods-for-measuring-personal-internet-traffic-and-data-expenditure/"><u>Insightful Methods for Measuring Personal Internet Traffic and Data Expenditure</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-digital-storefronts-buying-gaming-experiences-with-your-oculus-quest-2/"><u>Mastering Digital Storefronts: Buying Gaming Experiences with Your Oculus Quest 2</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-the-art-of-perfect-selfies-a-comprehensive-guide-to-using-self-lighting-techniques/"><u>Mastering the Art of Perfect Selfies: A Comprehensive Guide to Using Self-Lighting Techniques</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/protect-your-system-with-these-15-free-instant-boot-antivirus-tools/"><u>Protect Your System with These 15 Free, Instant-Boot Antivirus Tools</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/resolving-issues-when-your-instagram-is-not-active-anymore/"><u>Resolving Issues When Your Instagram Is Not Active Anymore</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/seamless-integration-managing-your-google-smart-speaker-through-a-windows-or-mac-computer-interface/"><u>Seamless Integration: Managing Your Google Smart Speaker Through a Windows or Mac Computer Interface</u></a></li>
<li><a href="https://screen-capture.techidaily.com/speedy-cam-and-commentary-recorder-software-for-2024/"><u>Speedy Cam & Commentary Recorder Software for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-fix-for-dysfunctional-closed-captioning-on-amazon-prime-streams/"><u>Step-by-Step Fix for Dysfunctional Closed Captioning on Amazon Prime Streams</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-guide-to-obtaining-your-iphones-user-manuals-online/"><u>Step-by-Step Guide to Obtaining Your iPhones' User Manuals Online</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-definitive-selection-of-the-top-8-tv-streaming-sites-to-watch-in-202/"><u>The Definitive Selection of the Top 8 TV Streaming Sites to Watch in 202</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-tutorial-on-transforming-spotify-listening-playlists-into-text-formats/"><u>The Ultimate Tutorial on Transforming Spotify Listening Playlists Into Text Formats</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/top-12-free-voip-services-you-shouldnt-miss/"><u>Top 12 Free VOIP Services You Shouldn't Miss</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/top-screen-recorders-for-live-broadcasts-on-youtube-for-2024/"><u>Top Screen Recorders for Live Broadcasts on YouTube for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-how-to-recover-or-locate-d3dx928dll-when-lost/"><u>Troubleshooting: How to Recover or Locate d3dx9_28.dll When Lost</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-what-to-do-when-you-encounter-a-dnssddll-error-message/"><u>Troubleshooting: What to Do When You Encounter a 'dnssd.dll' Error Message</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/uber-vs-cab-fares-which-is-the-more-economical-choice-for-your-journey/"><u>Uber Vs. Cab Fares: Which Is the More Economical Choice for Your Journey?</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ultimate-guide-repairing-your-stuck-cd-dvd-and-blu-ray-drives/"><u>Ultimate Guide: Repairing Your Stuck CD, DVD, and Blu-Ray Drives</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ultimate-guide-resolving-coredll-not-found-and-missing-dll-errors-on-your-pc/"><u>Ultimate Guide: Resolving 'Core.dll Not Found' And Missing DLL Errors on Your PC</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ultimate-guide-selecting-the-perfect-phone-case-for-you/"><u>Ultimate Guide: Selecting the Perfect Phone Case for You</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unleashing-the-power-of-artificial-intelligence-with-meta-on-instagram/"><u>Unleashing the Power of Artificial Intelligence with Meta on Instagram</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unlocking-portable-fm-radio-experience-on-your-iphone-or-android-a-comprehensive-guide/"><u>Unlocking Portable FM Radio Experience on Your iPhone or Android: A Comprehensive Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unlocking-your-online-potential-by-enabling-browser-cookies/"><u>Unlocking Your Online Potential by Enabling Browser Cookies</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/video-venue-selection-finding-the-right-platform/"><u>Video Venue Selection  Finding the Right Platform</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/whats-new-in-mozilla-thunderbird-update-discover-version-nkib/"><u>What's New in Mozilla Thunderbird Update - Discover Version Nkib</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/which-is-better-exploring-the-advantages-of-ipad-mini-over-ipad-air/"><u>Which Is Better? Exploring the Advantages of iPad Mini over iPad Air</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/your-essential-guide-to-the-top-8-complimentary-roku-channels-for-2n2024/"><u>Your Essential Guide to the Top 8 Complimentary Roku Channels for 2N2024</u></a></li>
</ul></div>
