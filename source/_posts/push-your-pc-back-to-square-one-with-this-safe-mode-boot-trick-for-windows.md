---
title: Push Your PC Back to Square One with This Safe Mode Boot Trick for Windows
date: 2024-08-19T15:00:19.609Z
updated: 2024-08-20T15:00:19.609Z
categories:
  - BestProducts
description: This Article Describes Push Your PC Back to Square One with This Safe Mode Boot Trick for Windows
excerpt: This Article Describes Push Your PC Back to Square One with This Safe Mode Boot Trick for Windows
thumbnail: https://www.lifewire.com/thmb/2PzECV0th8lkw2Wd2G3VSAac2Xk=/540x405/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/how-to-force-windows-to-restart-in-safe-mode-2625163-1105674bea70405ab286d0d61b498bf6.png
---

## Push Your PC Back to Square One with This Safe Mode Boot Trick for Windows
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### What to Know

* To force Windows to restart in Safe Mode, access Advanced Startup Options or System Recovery Options.
* Then, use a**bcdedit** command to open Safe Mode from Command Prompt.

 This article describes how to use the bcdedit command to boot into Safe Mode when[the normal method doesn't work](https://www.lifewire.com/fix-a-computer-that-always-stops-at-startup-settings-or-abo-2624445) .  

## How to Use 'bcdedit' to Start in Safe Mode

 Forcing Windows to restart to this special mode (or making it_stop_ starting in Safe Mode) is moderately difficult and will probably take several minutes, at most. These directions will start Safe Mode from[Command Prompt](https://www.lifewire.com/command-prompt-2625840) :

1. [Open Advanced Startup Options](https://www.lifewire.com/how-to-access-advanced-startup-options-in-windows-10-or-8-2626229) if you're on Windows 11, Windows 10, or Windows 8\. Since you can't start Windows properly, use methods 4, 5, or 6 outlined in that tutorial.  
 With Windows 7 or Vista, start System Recovery Options using your installation media or a system repair disc. Unfortunately, this process doesn't work with Windows XP.  
 If you want to force or stop Safe Mode from starting, and you actually_can_ access Windows properly, you don't need to follow the procedure below. See the much easier[How to Start Windows in Safe Mode Using System Configuration](https://www.lifewire.com/how-to-start-windows-in-safe-mode-using-system-configuration-2626115) process.
2. Open Command Prompt. If you're using Windows 7 or newer, it's located here:**Troubleshoot** \>**Advanced options** \>**Command Prompt** .  
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
![Advanced Startup Options for Windows 10](https://www.lifewire.com/thmb/FvRv0xdSCo8UanPmD9Vp0mBddjE=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/aso-windows-10-5c5c3bde46e0fb000127c6d7.png)
3. Execute the correct bcdedit[command](https://www.lifewire.com/what-is-a-command-2625828) as shown below based on which Safe Mode option you'd like to start:  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
!["bcdedit /set {default} safeboot network" command in Command Prompt](https://www.lifewire.com/thmb/tnUE5VabXIlDNfK2S4UhcOKHG9c=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/002_how-to-force-windows-to-restart-in-safe-mode-2625163-5c77678446e0fb0001d83cb3.jpg)  
 Be sure to type whatever command you choose_exactly_ as shown and then execute it using the**Enter** key. Spaces are very important! The { and } brackets are the ones above the \[ and \] keys on your keyboard. Two separate commands are required to start_Safe Mode with Command Prompt_ , so be sure to execute them both.  
 Safe Mode:  
 `bcdedit /set {default} safeboot minimal`  
 Safe Mode with Networking:  
 `bcdedit /set {default} safeboot network`  
 Safe Mode with Command Prompt:  
 `bcdedit /set {default} safeboot minimal bcdedit /set {default} safebootalternateshell yes`
4. A properly executed bcdedit command should return the message**The operation completed successfully** .  
 If you see one of these messages or something similar, check Step 3 again and make sure you executed the Safe Mode command properly:  
   * **The parameter is incorrect**  
   * **The set command specified is not valid**  
   * **...is not recognized as an internal or external command...**
5. Close the Command Prompt window.
6. In Windows 11, 10, and 8, select**Continue** .  
 In Windows 7 and Vista, select**Restart** .  
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
![ASO menu Windows](https://www.lifewire.com/thmb/s1Q2N-22YKjJTAP7l4M9BJzkNXE=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/003_how-to-force-windows-to-restart-in-safe-mode-2625163-5c7767ddc9e77c0001f57b8c.jpg)
7. Wait while your computer or device restarts.
8. Once Windows starts, log in as you normally do and use Safe Mode however you were planning.

 Windows will continue to start in Safe Mode every time you reboot unless you undo what you did in Step 3\. The easiest way to do that is not by executing more commands but[via System Configuration](https://www.lifewire.com/how-to-start-windows-in-safe-mode-using-system-configuration-2626115) (uncheck**Safe boot** ).

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## How to Stop a Safe Mode Loop

 Try this if Windows is stuck in a sort of Safe Mode loop, preventing you from starting in normal mode again, and you've already tried the instructions in the_Important_ call-out above:

1. Start Command Prompt from_outside_ of Windows, the process outlined in Steps 1 and 2 above.
2. Execute this command once Command Prompt is open:  
 `bcdedit /deletevalue {default} safeboot`  
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
!["bcdedit /deletevalue {default} safeboot" command in Command Prompt on Windows](https://www.lifewire.com/thmb/iw73ubzOfXo2zuWO1YLBafnst2A=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/004_how-to-force-windows-to-restart-in-safe-mode-2625163-5c7768a5c9e77c000136a6ae.jpg)
3. Assuming it was successfully executed (see Step 4 above),[restart your computer](https://www.lifewire.com/how-to-reboot-a-computer-2624568) . Windows should start normally.

[8 Things to Consider Before Buying a Desktop PC](https://www.lifewire.com/desktop-pc-buyers-guide-832343)

 FAQ

* How do I exit Safe Mode in Windows 10?  
 Exiting Windows 10 Safe Mode is typically just a matter of[restarting your PC](https://www.lifewire.com/how-to-reboot-a-computer-2624568) . Another method is to press the**Windows key + R** , then type in "**msconfig** " and select**OK** \>**Boot** and turn off**Safe boot** under Boot Options.
* How do I enter Safe Mode in Windows XP if F8 isn't working?  
 Normally restarting Windows XP in Safe Mode is just a matter of pressing F8 during startup. If the F8 key isn't working, check your keyboard for an F-Lock key that could have turned off your F keys. Otherwise,[open your PC's BIOS menu](https://www.lifewire.com/how-to-enter-bios-2624481) and make sure**Keyboard Support USB** is turned on.

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
<li><a href="https://facebook-video-footage.techidaily.com/updated-exclusive-mcb-logo-designs-and-templates-for-2024/"><u>[Updated] Exclusive MCB Logo Designs and Templates for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-obs-live-broadcasting-on-instagram-for-2024/"><u>[Updated] OBS Live Broadcasting on Instagram for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-retro-to-future-radeon-rebooted-for-2024/"><u>[Updated] Retro to Future  Radeon Rebooted for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/2024s-top-selection-of-smart-key-finders-reviewed/"><u>2024'S Top Selection of Smart Key Finders Reviewed</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-realme-11-5g-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your Realme 11 5G Phone and Remove Locked Screen</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/building-your-dream-4k-video-editing-studio-a-diy-blueprint-for-2024/"><u>Building Your Dream 4K Video Editing Studio  A DIY Blueprint for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/complete-tutorial-access-and-extract-rar-compressed-folders-on-your-mac/"><u>Complete Tutorial: Access and Extract RAR Compressed Folders on Your Mac</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/difficulty-levels-studying-german/"><u>Difficulty Levels: Studying German</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/earn-free-football-fun-learn-to-livestream-legends/"><u>Earn-Free Football Fun  Learn to Livestream Legends</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/expert-tips-on-solving-error-code-43-in-programming/"><u>Expert Tips on Solving Error Code 43 in Programming</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/geforce-rtx-3070-ti-driver-download-support-for-win-11-8-and-7-available-now/"><u>GeForce RTX 3070 Ti Driver Download - Support for Win 11, 8 & 7 Available Now</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/guide-turning-onoff-windows-11s-on-screen-keyboard/"><u>Guide: Turning On/Off Windows 11'S On-Screen Keyboard</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-can-i-fix-an-unresponsive-email-on-my-iphone-device/"><u>How Can I Fix an Unresponsive Email on My iPhone Device?</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-remove-and-reset-face-id-on-iphone-14-by-drfone-ios/"><u>How to Remove and Reset Face ID on iPhone 14</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-stop-that-annoying-boom-overcoming-subwoofer-distortion/"><u>How to Stop That Annoying Boom: Overcoming Subwoofer Distortion</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/ideal-ps2-emulation-software-for-ios-users/"><u>Ideal PS2 Emulation Software for IOS Users</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-2-ways-to-transfer-text-messages-from-itel-p40-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 2 Ways to Transfer Text Messages from Itel P40 to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-many-attempts-to-unlock-apple-iphone-15-pro-drfone-by-drfone-ios/"><u>In 2024, How Many Attempts To Unlock Apple iPhone 15 Pro | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-opening-doors-creating-an-account-on-youtube/"><u>In 2024, Opening Doors  Creating an Account on YouTube</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-syncing-twitter-to-snapchat-video-uploading-techniques/"><u>In 2024, Syncing Twitter to Snapchat  Video Uploading Techniques</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-vimeoifytweets-audiovideo-tweet-tool/"><u>In 2024, VimeoifyTweets  Audio/Video Tweet Tool</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/inside-look-analyzing-user-experience-functionality-and-security-on-the-line-platform/"><u>Inside Look: Analyzing User Experience, Functionality & Security on the Line Platform</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/navigate-your-messages-effortlessly-with-the-best-visual-voice-mail-apps-of/"><u>Navigate Your Messages Effortlessly with the Best Visual Voice Mail Apps Of</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/navigating-microsoft-teams-efficiently-unlocking-the-power-of-the-copilot-tool/"><u>Navigating Microsoft Teams Efficiently: Unlocking the Power of the Copilot Tool</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/order-of-play-a-step-by-step-plan-to-enjoy-all-transformers-films/"><u>Order of Play: A Step-by-Step Plan to Enjoy All Transformers Films</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/overcoming-common-game-and-graphics-library-dll-errors-microsoft-directx-and-directinput-explained/"><u>Overcoming Common Game and Graphics Library Dll Errors: Microsoft DirectX and DirectInput Explained</u></a></li>
<li><a href="https://extra-tips.techidaily.com/pioneering-tools-for-the-future-of-3d-model-and-animation-artistry/"><u>Pioneering Tools for the Future of 3D Model & Animation Artistry</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/planning-to-use-a-pokemon-go-joystick-on-itel-p55plus-drfone-by-drfone-virtual-android/"><u>Planning to Use a Pokemon Go Joystick on Itel P55+? | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/precision-alignment-perfecting-edge-display/"><u>Precision Alignment: Perfecting Edge Display</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/remedying-not-verified-http-warnings-secure-your-browser-experience/"><u>Remedying 'Not Verified' HTTP Warnings – Secure Your Browser Experience</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/resolving-the-phase0exception-error-a-step-by-step-guide-to-overcoming-stop-code-0x00000078/"><u>Resolving the PHASE0_EXCEPTION Error: A Step-by-Step Guide to Overcoming Stop Code 0X00000078</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/roku-tv-mastery-controlling-without-a-physical-remote-techniques-and-tricks/"><u>Roku TV Mastery: Controlling Without a Physical Remote - Techniques and Tricks</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/smartphone-savvy-capturing-and-storing-twitter-gifs-for-2024/"><u>Smartphone Savvy  Capturing & Storing Twitter GIFs for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-guide-correcting-missing-opengl32dll-error-messages/"><u>Step-by-Step Guide: Correcting Missing OpenGL32.dll Error Messages</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-instructions-for-refreshing-your-residential-sound-systems-speakers/"><u>Step-by-Step Instructions for Refreshing Your Residential Sound System's Speakers</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/steps-to-activate-your-apple-watch-with-gmail-a-comprehensive-guide/"><u>Steps to Activate Your Apple Watch with Gmail: A Comprehensive Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/steps-to-stream-netflix-content-through-your-nintendo-switch-gaming-system/"><u>Steps To Stream Netflix Content Through Your Nintendo Switch Gaming System</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-samsung-galaxy-z-flip-7-unveiled-anticipated-launch-date-and-pricing-details-revealed/"><u>The Samsung Galaxy Z Flip 7 Unveiled: Anticipated Launch Date & Pricing Details Revealed</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-ultimate-guide-to-flawless-sound-engineering-in-audacity/"><u>The Ultimate Guide to Flawless Sound Engineering in Audacity</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-guide-implementing-windows-11-installation-on-a-clean-slate-hard-disk/"><u>The Ultimate Guide: Implementing Windows 11 Installation on a Clean Slate Hard Disk</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-your-vehicles-malfunctioning-audio-system/"><u>Troubleshooting Your Vehicle's Malfunctioning Audio System</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ultimate-guide-on-how-to-access-the-playstation-network-portal/"><u>Ultimate Guide on How to Access the PlayStation Network Portal</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ultimate-guide-solving-the-mystery-of-a-missing-avcodecdll-file/"><u>Ultimate Guide: Solving the Mystery of a Missing avcodec.dll File</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ultimate-list-of-zero-cost-html-editors-for-efficient-coding-in-windows/"><u>Ultimate List of Zero-Cost HTML Editors for Efficient Coding in Windows</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/understanding-and-solving-the-windows-code-19xb4d-malfunction/"><u>Understanding and Solving the Windows Code 19Xb4d Malfunction</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/unlocking-iphone-15-pro-passcode-without-a-computer-drfone-by-drfone-ios/"><u>Unlocking iPhone 15 Pro Passcode without a Computer | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unraveling-roku-express-and-stick-distinguishing-key-features/"><u>Unraveling Roku Express and Stick: Distinguishing Key Features</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ling-youtubes-complex-view-count-system-for-2024/"><u>Unveiling YouTube's Complex View Count System for 2024</u></a></li>
</ul></div>
