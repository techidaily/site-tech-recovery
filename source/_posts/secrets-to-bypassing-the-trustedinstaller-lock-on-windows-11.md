---
title: Secrets to Bypassing the TrustedInstaller Lock on Windows 11
date: 2024-08-19T13:10:29.512Z
updated: 2024-08-20T13:10:29.512Z
categories:
  - BestProducts
description: This Article Describes Secrets to Bypassing the TrustedInstaller Lock on Windows 11
excerpt: This Article Describes Secrets to Bypassing the TrustedInstaller Lock on Windows 11
thumbnail: https://www.lifewire.com/thmb/bN_F8h8TKTX1N0seGbQ341fq0Y0=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/GettyImages-179036384-b081a08d421b4b6da954cac5b8461946.jpg
---

## Secrets to Bypassing the TrustedInstaller Lock on Windows 11
### What to Know

* Use the**TAKEOWN** and**icacls** Command Prompt commands to take ownership of the file or folder.
* Or, right-click the item and go to**Properties** \>**Security** \>**Advanced** to add yourself to the list.
* TrustedInstaller is a built-in user account that owns lots of important system files.

 This article describes two ways to deal with the message in Windows 10 about needing permission from TrustedInstaller to make changes to a file or folder.

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Fix the TrustedInstaller Error Using Command Prompt

 There are two really simple[Command Prompt commands](https://www.lifewire.com/list-of-command-prompt-commands-4092302) you can use to bypass the TrustedInstaller permissions prompt. Follow these steps to fix the TrustedInstaller "error" by granting your user account permission to make changes to the file or folder:

1. [Open an elevated Command Prompt](https://www.lifewire.com/how-to-open-an-elevated-command-prompt-2618088) . The quickest way there is to search for it from the Start menu, right-click the result, and choose**Run as administrator** .  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Run As Administrator option for the Windows 10 Command Prompt](https://www.lifewire.com/thmb/qK50_I4SdSJ98eEbO9R6yPSN1Vk=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/command-prompt-admin-windows-10-45f7ecab69a442f489eaf6a499a353d4.png)
2. Enter**TAKEOWN /F** and then type the file or folder name. Here's an example:  
 `TAKEOWN /F C:\Windows\System32\fr-FR\fms.dll.mui`
3. Press**Enter** to take control of the file. You'll see a success message if the command executed correctly.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
![The TAKEOWN /F command in Windows 10 Command Prompt](https://www.lifewire.com/thmb/nOnoS4n34cd8C2EJEDT2_rLzdhw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/takeown-command-trustsedinstaller-windows-10-267bfffb4f974a29940a0af233ef4a84.png)
4. Enter the following command (replacing our example file with your own) to immediately give your user account permission to delete or change the file or folder:  
 `icacls C:\Windows\System32\fr-FR\fms.dll.mui /grant Administrators:F /T`  
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![icacls command executed in Windows 10 Command Prompt](https://www.lifewire.com/thmb/clN3CT0-H0V3QdOSRZWprDCigZ4=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/icacls-command-windows-10-7f562cffaf424cd281b4e58c68b19e25.png)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Edit the File's Security Options to Fix the TrustedInstaller Error

 If you don't feel comfortable using Command Prompt to take ownership of the folder or file, there is another way. Here's how to use File Explorer to edit the security settings for the data, which will let you delete or modify it as needed.

Make sure you are logged in as an administrator.

1. Locate the item you need permission to change and then right-click it and choose**Properties** .  
![The context menu for a Windows 10 folder ](https://www.lifewire.com/thmb/CSwAkry59uiW_sJ5GzqkO0QrOuk=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/context-menu-folder-windows-10-0447423a01764cecad790f8dc6303c59.png)
2. Go to**Security** \>**Advanced** , then select**Change** next to**Owner: TrustedInstaller** .  
![The Properties and Advanced Security Settings options for a Windows 10 folder](https://www.lifewire.com/thmb/823H3LgLGW5GbhyNSwSn1HNUZlk=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/advanced-security-settings-windows-10-folder-4eb4fed4cb134eb1ba00993a705f7175.png)
3. Type your username into the text box and then choose**Check Names** \>**OK** .  
![The Windows 10 Check Names box with a user account listed](https://www.lifewire.com/thmb/ESMv2bIcNtWxpryKYLlwZFwmyCA=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/windows-10-select-user-or-group-880cbe35a52348f19d11206db4d7a0b6.png)
4. Check the box next to**Replace owner on subcontainers and objects** .  
![The replace owner on subcontainers and objects checkbox in Windows 10](https://www.lifewire.com/thmb/n8OW45wPPq3HiSTrW4eQIT_Y0EU=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/replace-owner-windows-10-folder-885ef894881e4e21a60b1b09568ea020.png)
5. Select**OK** at the bottom and then**OK** on the Properties window you opened in Step 1.
6. Open**Properties** \>**Security** \>**Advanced** once more. This time, select**Add** .  
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
![The Advanced Security Settings for a Windows 10 folder](https://www.lifewire.com/thmb/fEVYPGbUtSiGdO8kZg1RZd6gtIE=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/add-button-advanced-security-settings-3ffcde5bc8b942278219bbd9b4663921.png)
7. Choose**Select a principal** and then type your username in the box.
8. Press**Check Names** \>**OK** .  
![A user account listed in the Select User or Group box for a Windows 10 folder](https://www.lifewire.com/thmb/a8Ie_eyPviEwOjytgb9HHofaQgc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/select-user-group-windows-10-security-b2ffe7d116f2424e845a612090d4e932.png)
9. Check the box next to**Full control** , then select**OK** .  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Full Control permission selected for a folder in Windows 10](https://www.lifewire.com/thmb/cLa_4Jv8moyuFMZaNvHFNWAcllw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/full-control-folder-permissions-b0f31e6f8d7d418e91990e6c32476c30.png)
10. Check the box next to **Replace all child object permission entries with inheritable permission entries from this object** .  
![The checkbox called Replace all child object permission entries in Windows 10](https://www.lifewire.com/thmb/6T2vTKuuRj3ONEWEpCefVrYtszQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/replace-all-child-object-permission-entries-windows-10-fc09040d1d8b4357b5866ced25b79262.png)
11. Select**OK** on the Advanced Security Settings window and then**Yes** on the confirmation prompts. You should now have full permission to make changes to the file or folder, and you can close any other windows you opened to make these changes.

## Why Do I Need Permission From TrustedInstaller?

 Provided you're the primary user of your home computer, you might be surprised to find out you need anyone’s permission to deal with files on your own PC.

 All Windows 10 PCs have an in-built Microsoft account known as the TrustedInstaller. This account exists to prevent accidental damage to important system files, so it's given ownership over many important operating system files. For you to be able to take control of these files, you need to make yourself the owner as described above.  

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
<li><a href="https://extra-information.techidaily.com/new-ace-voice-changer-apps-for-your-mobile-device/"><u>[New] Ace Voice-Changer Apps for Your Mobile Device</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-full-analysis-powerdirector-app-2024/"><u>[New] Full Analysis  PowerDirector App - 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-instagram-story-perfection-seamless-emoji-integration-techniques/"><u>[New] In 2024, Instagram Story Perfection  Seamless Emoji Integration Techniques</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-twitter-video-reconfiguration-audio-version/"><u>[New] In 2024, Twitter Video Reconfiguration  Audio Version</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-a-sea-of-silence-the-perils-of-pretense-in-profiles/"><u>[Updated] In a Sea of Silence  The Perils of Pretense in Profiles</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-learn-to-prevent-persistent-commercials-in-digital-platforms-for-2024/"><u>[Updated] Learn to Prevent Persistent Commercials in Digital Platforms for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-ultimate-guide-to-travel-blogs-on-youtube/"><u>[Updated] The Ultimate Guide to Travel Blogs on Youtube</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-top-8-best-apps-to-get-likes-on-facebook-android-and-iphone/"><u>[Updated] Top 8 Best Apps to Get Likes on Facebook (Android and iPhone)</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-which-is-superior-obs-or-streamlabs-for-your-livestream-needs-in-2024/"><u>[Updated] Which Is Superior, OBS or Streamlabs for Your Livestream Needs, In 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/a-comprehensive-tutorial-on-turning-on-the-second-layer-of-security-with-gmails-2fa/"><u>A Comprehensive Tutorial on Turning On the Second Layer of Security with Gmail'S 2FA</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/accessing-apple-entertainment-adding-the-apple-tv-application-to-fire-stick/"><u>Accessing Apple Entertainment: Adding the Apple TV Application to Fire Stick</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/all-about-usb-20-insights-into-data-velocity-cord-selection-and-attachment-options/"><u>All About USB 2.0: Insights Into Data Velocity, Cord Selection, and Attachment Options</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/aquatic-adventures-and-iphones-is-the-iphone-13-built-to-withstand-water/"><u>Aquatic Adventures and iPhones: Is the iPhone 13 Built to Withstand Water?</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/avoiding-hassle-simple-steps-to-take-a-device-offline-on-google-home-setup/"><u>Avoiding Hassle: Simple Steps to Take a Device Offline on Google Home Setup</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/before-you-buy-a-checklist-of-5-critical-aspects-for-new-stereo-speakers/"><u>Before You Buy: A Checklist of 5 Critical Aspects for New Stereo Speakers</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/best-calendar-apps-keeping-busy-households-organized-with-time-sharing-tools/"><u>Best Calendar Apps: Keeping Busy Households Organized with Time Sharing Tools</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/comprehensive-solutions-for-fixing-the-unavailable-zlibdll-error/"><u>Comprehensive Solutions for Fixing the Unavailable zlib.dll Error</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/discover-these-10-popular-netflix-substitutes-for-free-viewing/"><u>Discover These 10 Popular Netflix Substitutes for Free Viewing</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/easily-emulate-and-enjoy-android-applications-within-the-windows-11-environment/"><u>Easily Emulate and Enjoy Android Applications Within the Windows 11 Environment</u></a></li>
<li><a href="https://common-error.techidaily.com/error-code-cracked-steps-to-fix-windows-camera-problem-0xa00f4292-explained/"><u>Error Code Cracked: Steps to Fix Windows Camera Problem - 0xA00F4292 Explained</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/excel-integration-essentials-a-step-by-step-guide-to-combining-column-pairs/"><u>Excel Integration Essentials: A Step-by-Step Guide to Combining Column Pairs</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/expert-advice-for-restoring-functionality-in-microsoft-edge-when-it-fails/"><u>Expert Advice for Restoring Functionality in Microsoft Edge When It Fails</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/fixes-for-faded-colors-and-twisted-graphics-on-computer-screens-an-easy-diy-approach/"><u>Fixes for Faded Colors and Twisted Graphics on Computer Screens: An Easy DIY Approach</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/fixing-missing-dll-files-a-focus-on-correcting-d3dx9nul-not-detected-mistakes/"><u>Fixing Missing DLL Files: A Focus on Correcting D3dx9_nul Not Detected Mistakes</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/harmonizing-your-hits-the-definitive-guide-to-merging-spotify-playlists-with-precision/"><u>Harmonizing Your Hits: The Definitive Guide to Merging Spotify Playlists with Precision</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-change-your-apple-iphone-14-plus-apple-id-on-macbook-by-drfone-ios/"><u>How To Change Your Apple iPhone 14 Plus Apple ID on MacBook</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-samsung-galaxy-m34-5g-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Samsung Galaxy M34 5G | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-return-your-lenovo-device-to-factory-conditions-an-easy-to-follow-guide/"><u>How to Return Your Lenovo Device to Factory Conditions - An Easy-to-Follow Guide</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-samsung-galaxy-a25-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Catch or Beat Sleeping Snorlax on Pokemon Go For Samsung Galaxy A25 5G | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-demystifying-data-a-beginners-guide-to-facebook-insights/"><u>In 2024, Demystifying Data  A Beginner's Guide to Facebook Insights</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-secretsunlocked-utilizingyoucamforrecording/"><u>In 2024, SecretsUnlocked  UtilizingYouCamForRecording</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-streaming-into-the-future-a-review/"><u>In 2024, Streaming Into the Future  A Review</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlock-vivo-t2-5g-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>In 2024, Unlock Vivo T2 5G Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/is-it-possible-to-share-a-spotify-stream-simultaneously/"><u>Is It Possible to Share a Spotify Stream Simultaneously?</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/is-your-zoom-experience-compromised-by-user-error-lets-find-out/"><u>Is Your Zoom Experience Compromised by User Error? Let's Find Out!</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/leading-ip68-certified-mobile-case-reviews-2024-edition/"><u>Leading IP68 Certified Mobile Case Reviews - 2024 Edition</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-platformer-fun-top-6-super-mario-bros-titles-on-your-personal-computer/"><u>Mastering Platformer Fun: Top 6 Super Mario Bros Titles on Your Personal Computer</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/navigating-the-future-with-apples-developer-conference-2vews-announcements-news-and-insights-revealed/"><u>Navigating the Future with Apple's Developer Conference 2Vews - Announcements, News, and Insights Revealed</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/samsungs-latest-smartphone-release-unveiling-the-new-era/"><u>Samsung's Latest Smartphone Release: Unveiling the New Era</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/seamless-chatting-on-mac-a-step-by-step-tutorial-for-using-whatsapp/"><u>Seamless Chatting on Mac: A Step-by-Step Tutorial for Using WhatsApp</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/secure-the-latest-great-value-ipad-bargains-immedier/"><u>Secure the Latest Great Value iPad Bargains Immedier</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-directions-for-enabledisable-on-screen-typing-interface-in-microsofts-latest-os/"><u>Step-by-Step Directions for Enable/Disable On-Screen Typing Interface in Microsoft's Latest OS</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-instructions-for-initiating-chats-with-mozilla-thunderbird-users/"><u>Step-by-Step Instructions for Initiating Chats with Mozilla Thunderbird Users</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-instructions-installing-apple-tv-app-on-amazon-fire-stick/"><u>Step-by-Step Instructions: Installing Apple TV App on Amazon Fire Stick</u></a></li>
<li><a href="https://win-amazing.techidaily.com/step-by-step-tutorial-on-downloading-and-upgrading-your-asus-laptop-drivers/"><u>Step-by-Step Tutorial on Downloading and Upgrading Your ASUS Laptop Drivers</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-insiders-blueprint-for-snagging-cheap-dell-computers-as-a-student/"><u>The Insider's Blueprint for Snagging Cheap Dell Computers as a Student</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-selection-of-enjoyable-online-games-tailored-for-children/"><u>The Ultimate Selection of Enjoyable Online Games Tailored for Children</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/the-ultimate-strategy-guide-to-boosting-view-count-on-youtube-shorts/"><u>The Ultimate Strategy Guide to Boosting View Count on YouTube Shorts</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/top-criteria-to-evaluate-before-purchasing-your-next-gaming-desktop-or-laptop/"><u>Top Criteria to Evaluate Before Purchasing Your Next Gaming Desktop or Laptop</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/understanding-t-mobiles-intra-network-wifi-roaming-a-guide/"><u>Understanding T-Mobile's Intra-Network WiFi Roaming: A Guide</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlock-lava-yuva-2-pro-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>Unlock Lava Yuva 2 Pro Phone Password Without Factory Reset Full Guide Here</u></a></li>
</ul></div>
