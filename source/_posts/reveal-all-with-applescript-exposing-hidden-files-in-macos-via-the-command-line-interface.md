---
title: "Reveal All with AppleScript: Exposing Hidden Files in macOS via the Command Line Interface"
date: 2024-08-12T03:54:13.738Z
updated: 2024-08-13T03:54:13.738Z
categories:
  - BestProducts
description: "This Article Describes Reveal All with AppleScript: Exposing Hidden Files in macOS via the Command Line Interface"
excerpt: "This Article Describes Reveal All with AppleScript: Exposing Hidden Files in macOS via the Command Line Interface"
thumbnail: https://thmb.techidaily.com/fdc872e52961baec6923b458dbd6d98e67f3ed40f9ab2afdf7e0f1b821a0cc59.jpg
---

## Reveal All with AppleScript: Exposing Hidden Files in macOS via the Command Line Interface
 Your Mac has a few secrets, hidden folders, and files that are invisible to you. You may not even realize how much hidden data there is on your Mac, from basic things, such as preference files for user data and apps, to core system data that your Mac needs to run correctly. Apple hides these files and folders to prevent you from accidentally changing or deleting important data that your Mac needs.

 Apple's reasoning is good, but there are times when you may need to view these out-of-the-way corners of your Mac's file system. You'll find that accessing these hidden corners of your Mac is one of the steps in many Mac troubleshooting guides, as well as guides for backing up important data, such as[mail messages](https://www.lifewire.com/transfer-apple-mail-to-new-mac-2260915) or[Safari bookmarks](https://www.lifewire.com/back-up-or-move-safari-bookmarks-to-new-mac-2260891) . Fortunately, Apple includes ways to access these hidden goodies in[OS X](https://www.lifewire.com/install-mac-os-on-pc-5075590) and the more recent[macOS](https://www.lifewire.com/what-is-macos-4691239) . This guide concentrate on using the Terminal app, which provides a command line-like interface to many of the Mac's core functions.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
![macOS Terminal with hidden files in a Finder window superimposed](https://www.lifewire.com/thmb/0GxCNfM-Nwq84X9L67jj4gSEqP4=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/ScreenShot2019-01-03at3.13.16PM-5c2ea61c46e0fb0001abc508-fb8027cc5efa44e2a3c858234aac1ae3.jpg)

 With Terminal, a simple command is all it takes to get your Mac to spill its secrets.

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Use Terminal

1. Launch**Terminal** , located at**/Applications/Utilities/** .  
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Terminal application in macOS Finder Utilities folder](https://www.lifewire.com/thmb/MlM5SU4iQfZRMK1iLmULOs4OewA=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/001_view-hidden-mac-folders-using-terminal-2260776-5c2ea70b46e0fb000123c164.jpg)
2. Type or copy and paste the commands below into the Terminal window, one at a time, pressing**ENTER** after each one.  
 **defaults write com.apple.finder AppleShowAllFiles TRUE**  
**killall Finder**  
![Terminal window with commands inline](https://www.lifewire.com/thmb/z9u9E5cQZxfSmppiqZSimKAfX_s=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/002_view-hidden-mac-folders-using-terminal-2260776-5c2ea73546e0fb0001415cda.jpg)
3. Entering the two lines above into Terminal allows you to use the[Finder](https://www.lifewire.com/use-mac-finder-2260739) to display all the hidden files on your Mac. The first line tells the Finder to display all files, regardless of how the hidden flag is set. The second line stops and restarts the Finder, so the changes can take effect. You may see your desktop disappear and reappear when you execute these commands; this is normal.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Was Hidden Can Now Be Seen

 Now that the Finder is displaying[hidden files](https://www.lifewire.com/what-is-a-hidden-file-2625898) and folders, just what can you see? The answer depends on the specific folder you're looking at, but in just about every folder, you'll see a file named**.DS\_Store** . The DS\_Store file contains information about the current folder, including the icon to use for the folder, the location its window will open in, and other bits of information the system needs.

 More important than the ubiquitous .DS\_Store file are the hidden folders that allow Mac users to access files such as the[Library folder](https://www.lifewire.com/os-x-is-hiding-your-library-folder-2260833) within your[Home folder](https://www.lifewire.com/move-macs-home-folder-new-location-2260157) . The Library folder contains many files and folders that relate to specific apps and services that you use on your Mac. For example, have you ever wondered where your email messages are stored? If you use Mail, you'll find them in the hidden Library folder. Likewise, the Library folder contains your[Calendar](https://www.lifewire.com/back-up-or-move-ical-or-calendar-data-to-new-mac-2260870) , Notes,[Contacts](https://www.lifewire.com/back-up-or-move-contacts-or-address-book-data-2260801) ,[Saved Application States](https://www.lifewire.com/managing-resume-feature-os-x-2259802) , and much more.

 Go ahead and look around the Library folder, but don't make any changes unless you have a specific problem that you're attempting to fix.

 Now that you can see all the hidden folders and files in the Finder, you'll probably want to hide them again, if only because they tend to clutter up Finder windows with extraneous items.

## Hide the Clutter

1. Launch**Terminal** , located at**/Applications/Utilities/** .
2. Type or copy/paste the commands below into the Terminal window, one at a time, pressing**ENTER** after each one.  
 **defaults write com.apple.finder AppleShowAllFiles FALSE**  
**killall Finder**  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
![Terminal with ShowAllFiles set to FALSE](https://www.lifewire.com/thmb/7JHA9g9EOKMG8xeydvO7Yp3H_24=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/003_view-hidden-mac-folders-using-terminal-2260776-5c2ea75e46e0fb0001a438c8.jpg)
3. Poof! The hidden files are once again hidden. No hidden folder or file was harmed in the making of this Mac tip.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
## More About Terminal

 If the power of the Terminal app intrigues you, you can find out more about what secrets Terminal can uncover in this guide:[Use the Terminal Application to Access Hidden Features](https://www.lifewire.com/mac-terminal-commands-4774997) .

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
<li><a href="https://fox-http.techidaily.com/new-2024-approved-secrets-of-the-trade-boosting-popularity-with-tiktok-unboxings/"><u>[New] 2024 Approved  Secrets of the Trade  Boosting Popularity with TikTok Unboxings</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-mastermakers-ranking-the-top-5-digital-titling-pros/"><u>[New] Mastermakers  Ranking the Top 5 Digital Titling Pros</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-most-liked-and-watched-amazon-prime-video-on-twitter-for-2024/"><u>[New] Most Liked and Watched Amazon Prime Video on Twitter for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-simplified-methods-to-screen-record-instagrams-story-feature-for-2024/"><u>[New] Simplified Methods to Screen Record Instagram's Story Feature for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-enhanced-video-clarity-on-iphone-and-android-platforms-for-2024/"><u>[Updated] Enhanced Video Clarity on iPhone & Android Platforms for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-seamless-screen-saving-on-iphone/"><u>2024 Approved  Seamless Screen Saving on iPhone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/2024s-top-selection-of-smart-key-finders-reviewed/"><u>2024'S Top Selection of Smart Key Finders Reviewed</u></a></li>
<li><a href="https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-vivo-y77t-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Solutions to Fix Error 505 in Google Play Store on Vivo Y77t | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/batch-unfriending-process-for-a-more-manageable-snapchat-network/"><u>Batch Unfriending Process for a More Manageable Snapchat Network</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/best-pokemons-for-pvp-matches-in-pokemon-go-for-zte-axon-40-lite-drfone-by-drfone-virtual-android/"><u>Best Pokemons for PVP Matches in Pokemon Go For ZTE Axon 40 Lite | Dr.fone</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/-cinematic-vision-top-camera-stabilizers-reviewed-for-2024/"><u>Clear Cinematic Vision - Top Camera Stabilizers Reviewed for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/comprehensive-review-of-snappy-driver-installer-version-113-for-automatic-drivers-updates/"><u>Comprehensive Review of Snappy Driver Installer Version 1.13 for Automatic Drivers Updates</u></a></li>
<li><a href="https://fox-http.techidaily.com/customize-with-ease-adding-personalized-audio-to-android-devices/"><u>Customize With Ease  Adding Personalized Audio to Android Devices</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/decoding-the-battle-between-neo-qled-and-oled-displays-key-insights/"><u>Decoding the Battle Between Neo QLED and OLED Displays: Key Insights</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/demystifying-bing-insights-into-microsofts-alternative-to-google/"><u>Demystifying Bing: Insights Into Microsoft’s Alternative to Google</u></a></li>
<li><a href="https://tech-revival.techidaily.com/demystifying-bingchattercrypto-tokens-insights-into-identifying-potential-digital-deception-in-blockchain-ventures/"><u>Demystifying BingChatterCrypto Tokens: Insights Into Identifying Potential Digital Deception in Blockchain Ventures</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/descifrar-cuando-un-primer-tratado-sobre-el-tiempo-en-espanol/"><u>Descifrar Cuándo: Un Primer Tratado Sobre El Tiempo en Espaňol</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/easy-way-to-open-command-prompt-in-specific-directory-paths/"><u>Easy Way to Open Command Prompt in Specific Directory Paths</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/engaging-internet-games-perfect-for-youngsters-a-list-of-7/"><u>Engaging Internet Games Perfect for Youngsters - A List of 7</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/essential-tips-to-correct-the-btballoondll-not-detected-mishap/"><u>Essential Tips to Correct the btballoon.dll Not Detected Mishap</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/expert-tips-on-solving-error-code-43-in-programming/"><u>Expert Tips on Solving Error Code 43 in Programming</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/free-android-16-update-latest-news-on-pricing-and-features-release-info-and-speculations/"><u>Free Android 16 Update: Latest News on Pricing & Features - Release Info & Speculations</u></a></li>
<li><a href="https://extra-information.techidaily.com/full-exploration-new-features-in-videoshow-app-24/"><u>Full Exploration  New Features in VideoShow App '24</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/guide-turning-onoff-windows-11s-on-screen-keyboard/"><u>Guide: Turning On/Off Windows 11'S On-Screen Keyboard</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-google-frp-lock-from-tecno-spark-20-pro-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock from Tecno Spark 20 Pro Devices</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-samsung-galaxy-a05s-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Samsung Galaxy A05s in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-a-damaged-video-file-of-apple-iphone-15-pro-using-video-repair-utility-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair a Damaged video file of Apple iPhone 15 Pro using Video Repair Utility on Mac?</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-stop-that-annoying-boom-overcoming-subwoofer-distortion/"><u>How to Stop That Annoying Boom: Overcoming Subwoofer Distortion</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-balancing-visual-elements-with-ideal-video-ratios/"><u>In 2024, Balancing Visual Elements with Ideal Video Ratios</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-beginning-the-live-journey-on-instagram/"><u>In 2024, Beginning the Live Journey on Instagram</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-beyond-binary-boundaries-metaverse-vs-multiverse/"><u>In 2024, Beyond Binary Boundaries  Metaverse V/S Multiverse</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-check-if-your-asus-rog-phone-8-is-unlocked-by-drfone-android/"><u>In 2024, How To Check if Your Asus ROG Phone 8 Is Unlocked</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-use-pokemon-emerald-master-ball-cheat-on-realme-narzo-60x-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Pokémon Emerald Master Ball Cheat On Realme Narzo 60x 5G | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-skaldic-epic-odins-final-stand/"><u>In 2024, Skaldic Epic  Odin's Final Stand</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-top-5-poco-m6-pro-4g-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>In 2024, Top 5 Poco M6 Pro 4G Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/iphone-users-rejoice-how-to-keep-private-numbers-off-your-phone/"><u>IPhone Users Rejoice: How to Keep Private Numbers Off Your Phone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/master-the-art-of-accessing-your-icloud-gallery-on-multiple-devices/"><u>Master the Art of Accessing Your iCloud Gallery on Multiple Devices</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/mastering-collage-artistry-with-precision-for-2024/"><u>Mastering Collage Artistry with Precision for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-skype-key-strategies-when-facing-connection-problems/"><u>Mastering Skype: Key Strategies When Facing Connection Problems</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-voice-commands-instructions-for-activating-siris-reading-feature/"><u>Mastering Voice Commands: Instructions for Activating Siri's Reading Feature</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/microsoft-word-is-there-a-way-to-use-it-without-spending-money/"><u>Microsoft Word: Is There A Way To Use It Without Spending Money?</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/navigate-your-messages-effortlessly-with-the-best-visual-voice-mail-apps-of/"><u>Navigate Your Messages Effortlessly with the Best Visual Voice Mail Apps Of</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/overcoming-common-game-and-graphics-library-dll-errors-microsoft-directx-and-directinput-explained/"><u>Overcoming Common Game and Graphics Library Dll Errors: Microsoft DirectX and DirectInput Explained</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/pc-integration-with-playstation-vr-detailed-walkthrough/"><u>PC Integration with PlayStation VR: Detailed Walkthrough</u></a></li>
<li><a href="https://techidaily.com/recover-apple-iphone-14-pro-max-data-from-ios-itunes-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover Apple iPhone 14 Pro Max Data From iOS iTunes | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/remedying-not-verified-http-warnings-secure-your-browser-experience/"><u>Remedying 'Not Verified' HTTP Warnings – Secure Your Browser Experience</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/restoring-power-on-your-macbook-pro-a-comprehensive-walkthrough/"><u>Restoring Power on Your MacBook Pro – A Comprehensive Walkthrough</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/roku-tv-mastery-controlling-without-a-physical-remote-techniques-and-tricks/"><u>Roku TV Mastery: Controlling Without a Physical Remote - Techniques and Tricks</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/simple-steps-for-linking-a-ps4-gamepad-to-console/"><u>Simple Steps for Linking a PS4 Gamepad to Console</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/stay-informed-on-playstation-5-slim-release-date-announcements-competitive-pricing-and-detailed-tech-overview/"><u>Stay Informed on PlayStation 5 Slim: Release Date Announcements, Competitive Pricing & Detailed Tech Overview</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-guide-correcting-missing-opengl32dll-error-messages/"><u>Step-by-Step Guide: Correcting Missing OpenGL32.dll Error Messages</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-instructions-for-refreshing-your-residential-sound-systems-speakers/"><u>Step-by-Step Instructions for Refreshing Your Residential Sound System's Speakers</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-repair-tips-overcoming-firestick-remote-connectivity-problems/"><u>Step-by-Step Repair Tips: Overcoming Firestick Remote Connectivity Problems</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/steps-to-activate-your-apple-watch-with-gmail-a-comprehensive-guide/"><u>Steps to Activate Your Apple Watch with Gmail: A Comprehensive Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/steps-to-stream-netflix-content-through-your-nintendo-switch-gaming-system/"><u>Steps To Stream Netflix Content Through Your Nintendo Switch Gaming System</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-samsung-galaxy-z-flip-7-unveiled-anticipated-launch-date-and-pricing-details-revealed/"><u>The Samsung Galaxy Z Flip 7 Unveiled: Anticipated Launch Date & Pricing Details Revealed</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-guide-implementing-windows-11-installation-on-a-clean-slate-hard-disk/"><u>The Ultimate Guide: Implementing Windows 11 Installation on a Clean Slate Hard Disk</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-your-vehicles-malfunctioning-audio-system/"><u>Troubleshooting Your Vehicle's Malfunctioning Audio System</u></a></li>
<li><a href="https://buynow-info.techidaily.com/ultimate-guide-dji-mavic-3-unveiled-revolutionizing-sky-high-photography/"><u>Ultimate Guide: DJI Mavic 3 Unveiled - Revolutionizing Sky-High Photography</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ultimate-list-of-zero-cost-html-editors-for-efficient-coding-in-windows/"><u>Ultimate List of Zero-Cost HTML Editors for Efficient Coding in Windows</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/understanding-and-solving-the-windows-code-19xb4d-malfunction/"><u>Understanding and Solving the Windows Code 19Xb4d Malfunction</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unveiling-the-latest-additions-to-the-macbook-lineup/"><u>Unveiling the Latest Additions to the MacBook Lineup</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/watch-disneys-magic-on-the-big-screen-connecting-disneyplus-with-chromecast-made-easy/"><u>Watch Disney's Magic on the Big Screen: Connecting Disney+ with Chromecast Made Easy</u></a></li>
</ul></div>
