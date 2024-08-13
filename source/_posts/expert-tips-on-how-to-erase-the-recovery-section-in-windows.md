---
title: Expert Tips on How to Erase the Recovery Section in Windows
date: 2024-08-12T03:57:03.881Z
updated: 2024-08-13T03:57:03.881Z
categories:
  - BestProducts
description: This Article Describes Expert Tips on How to Erase the Recovery Section in Windows
excerpt: This Article Describes Expert Tips on How to Erase the Recovery Section in Windows
thumbnail: https://www.lifewire.com/thmb/ALlLdPlK0nhyrSKTrZhz_J3x2vc=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/hard-drive-56a2cb273df78cf7727a0201.jpg
---

## Expert Tips on How to Erase the Recovery Section in Windows

Close 

###  What to Know

* In PowerShell or Command Prompt:**diskpart** \>**list disk** \>**select disk #** \>**list partition** \>**select partition #** \>**delete partition override** .
* To format partition: right-click**Start** \>**Disk Management** \> right-click**Unallocated** \>**New Simple Volume** \> follow wizard.

 This article explains how to delete a recovery partition in Windows 11, 10, 8, and 7\. It also explains how to format and expand a partition to use the unallocated space.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  How to Delete a Recovery Partition in Windows 

 Because recovery partitions are protected, the steps for removing them differ from deleting a normal partition.

 When you[ create a recovery partition for Windows](https://www.lifewire.com/create-recovery-drive-all-versions-windows-2200650) , it's best to store it on an[ external drive](https://www.lifewire.com/what-is-an-external-drive-2625867) in case something happens to your computer. After saving it somewhere else, you can delete the recovery partition from your PC to free up space.

1. Right-click the Start menu and select**Terminal (Admin)** Windows 11,**Windows PowerShell (Admin)** , or**Command Prompt (Admin)** .  
 If you're using Windows 7 or earlier, you'll have to[ open Command Prompt](https://www.lifewire.com/how-to-open-command-prompt-2618089) another way, like through the Start menu or Run dialog box.
2. Type**diskpart** and press**Enter** , then type**list disk** and press**Enter** .
3. A list of disks displays. Type   **select disk _#_**  (where _#_ is the number of the disk with the recovery partition) and press **Enter** .  
 If you're unsure which one it's on, find out by opening the[ Disk Management tool](https://www.lifewire.com/disk-management-2625863) .  
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
![Select Disk](https://www.lifewire.com/thmb/1Mt2ZXpoT3G6vxjBufv-L3Ax_IM=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/005_delete-windows-recovery-partition-4128723-39d975e00e4342e4ab2690b442c55cc3-5a89be105dd942a0b63ac8b7daf23288.jpg)
4. Type **list partition**  and press **Enter** . A list of partitions displays. Type **select partition #**  (where _#_ is the number of the recovery partition) and press **Enter** .  
![select partition](https://www.lifewire.com/thmb/EWAsDd1kl5UkUHvxcACEQzBdvyw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/007_delete-windows-recovery-partition-4128723-fcdf0b8b44b84e00b08b0da8a89f5052-5befaed89aef4289bc842118b9c4dbfd.jpg)
5. Type **delete partition override** and press**Enter** .

 After you see a confirmation message, you can close the PowerShell/Command Prompt.

![partition override](https://www.lifewire.com/thmb/77odldkkcz9Dr2ifvItweMN-dSg=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/009_delete-windows-recovery-partition-4128723-911baa68a0124e87b42297fc999ad2fa-b7cba53da27543f9a82eb6a6fd047464.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
## How to Format a Partition 

 Deleting a recovery partition will create a section of unallocated space on your drive. To use the unallocated space, you must format the partition:

1. Right-click the **Start** menu and select **Disk Management** .  
 If using Windows 7 or earlier, click the**Start** menu and type **diskmgmt.msc** in the search box to find the Disk Management tool.
2. Beside the disk number for your hard drive, you'll see several partitions, including one named**Unallocated** . Right-click the**Unallocated** partition and select**New Simple Volume** .  
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->
![New volume](https://www.lifewire.com/thmb/vSV9HGlkrIuOGf57tgxOOWkYPSA=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/011_delete-windows-recovery-partition-4128723-bbdbf03a107941c4b897dac28d81c481-12eafd51c56c4e309d480d3341906f0d.jpg)
3. Select**Next** to continue the wizard.
4. Enter how much data the new partition should use out of the unallocated space, then select**Next** .  
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Size volume](https://www.lifewire.com/thmb/hTSzg-d-_iXMiKGEHivv-Y80bhw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/013_delete-windows-recovery-partition-4128723-c3e7a897eaf74a2cbb07e5d3cd346d05-976944267d764fddb1dbc8486b288d8d.jpg)
5. Choose a letter from the drop-down menu to assign to the partition, then select**Next** .  
![drive letter](https://www.lifewire.com/thmb/t7Fd7PU9y95GJmLVpVgmIqFFpS0=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/014_delete-windows-recovery-partition-4128723-bb8b69c95baf427da9438ec7ea8b00e1-2f87c151c02443b5be4f3054f734089e.jpg)
6. Enter a name for the partition in the**Volume label** field, then select**Next** .  
 The default file system is[ NTFS](https://www.lifewire.com/ntfs-file-system-2625948) , but you can change it to[ FAT32](https://www.lifewire.com/what-is-file-allocation-table-fat-2625877) or another file system if you wish.  
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
![volume label](https://www.lifewire.com/thmb/b0FQo4mw5s7_yymf0Yz0bb57juc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/015_delete-windows-recovery-partition-4128723-3cd8c2d36a3046b7b44ee333928b82bb-634a4447146f4f4a874e1c72fd640b13.jpg)
7. Select**Finish** to close the wizard.

##  How to Expand a Partition to Use the Unallocated Space 

 If you want to expand another partition to use the extra space, then the unallocated space must appear to the immediate right of that partition in the Disk Management tool. To extend a partition:

1. Right-click the partition you want to expand and select**Extend Volume** .  
![extend volume](https://www.lifewire.com/thmb/I75j9u4O2PBCkkuxXXdF3ZWYk8U=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/017_delete-windows-recovery-partition-4128723-189b97dc135a4975ab409bfa11c404af-869b027d5b8d4beeac0013e2e75b2fc2.jpg)
2. Select**Next** to continue the wizard.
3. Enter how much of the unallocated space you want to use, then select**Next** .  
![drive size](https://www.lifewire.com/thmb/mXgg3V0zWVClHPqDGqa-nsiA1OA=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/019_delete-windows-recovery-partition-4128723-68d4465915374357af41a11672bc0857-d19bbede5e6346e6a1f1240d4a738789.jpg)
4. Select**Finish** to terminate the wizard. The Windows partition will be resized to include the extra space.

 FAQ

* Is it safe to delete a recovery partition in Windows?  
 Yes. Removing a recovery partition will not affect the Windows operating system.
* How do I restore a deleted Windows recovery partition?  
 To restore deleted recovery partitions,[ rebuild the Windows Boot Configuration Drive](https://www.lifewire.com/how-to-rebuild-the-bcd-in-windows-2624508) , use a third-party tool, or reinstall Windows.
* How do I factory reset Windows without a recovery partition?  
 Use[ Reset This PC](https://www.lifewire.com/reset-this-pc-complete-walkthrough-2624538) to restore your Windows PC to factory settings. In Windows 8, use Refresh Your PC to back up your files first.
* How do I create a recovery drive in Windows?  
 In Windows 11 or 10, search for**Create a recovery drive** and check the box beside**Back up system files to the recovery drive** . Next, connect a USB drive, then select**Next** . You can also[ create a recovery drive in Windows 8](https://www.lifewire.com/how-to-create-a-windows-recovery-drive-2625164) .

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
<li><a href="https://instagram-videos.techidaily.com/new-enhance-your-content-creating-engaging-loop-videos-for-ig-for-2024/"><u>[New] Enhance Your Content  Creating Engaging Loop Videos for IG for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-the-key-to-successful-large-scale-instagram-videos-for-2024/"><u>[New] The Key to Successful Large-Scale Instagram Videos for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-stealthy-content-consumption-top-5-apps/"><u>[Updated] 2024 Approved  Stealthy Content Consumption - Top 5 Apps</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-voice-recording-essentials-the-filmmakers-key-to-excellence/"><u>[Updated] 2024 Approved  Voice Recording Essentials  The Filmmaker's Key to Excellence</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-holistic-evaluation-full-screenflow-for-mac-functionality/"><u>[Updated] In 2024, Holistic Evaluation  Full ScreenFlow for Mac Functionality</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-streaming-showdown-the-duo/"><u>[Updated] In 2024, Streaming Showdown  The Duo</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-the-insiders-guide-to-instagrams-chroma-key-effect/"><u>[Updated] In 2024, The Insider's Guide to Instagram’s Chroma Key Effect</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-unleashing-creative-potential-making-youtube-trailers-in-filmora/"><u>[Updated] Unleashing Creative Potential  Making YouTube Trailers in Filmora</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-smartphone-savvy-capturing-and-storing-twitter-gifs/"><u>2024 Approved  Smartphone Savvy  Capturing & Storing Twitter GIFs</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/a-complete-guide-to-navigating-the-trustedinstaller-gateway-in-windows-11/"><u>A Complete Guide to Navigating the TrustedInstaller Gateway in Windows 11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/a-complete-walkthrough-of-the-how-to-train-your-dragon-movies-watch-them-in-order/"><u>A Complete Walkthrough of the How to Train Your Dragon Movies - Watch Them in Order!</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722879830344-android-phone-no-call-functionality-follow-these-steps-to-fix-it/"><u>Android Phone No Call Functionality? Follow These Steps to Fix It!</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/breaking-into-your-ipad-strategies-for-no-passcode-entry/"><u>Breaking Into Your iPad: Strategies for No-Passcode Entry</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/digital-stream-capturers-2023-edition-for-2024/"><u>Digital Stream Capturers, 2023 Edition for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/effective-solutions-to-correct-zlibdll-errors-on-your-pc/"><u>Effective Solutions to Correct zlib.dll Errors on Your PC</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/efficient-methods-to-turn-off-the-ai-companion-copilot-in-windows-11/"><u>Efficient Methods to Turn Off the AI Companion, Copilot, in Windows 11</u></a></li>
<li><a href="https://data-wizards.techidaily.com/enhancing-screen-quality-on-new-windows-11-interface/"><u>Enhancing Screen Quality on New Windows 11 Interface</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/escaping-gmail-here-are-the-top-8-alternatives-to-consider/"><u>Escaping Gmail? Here Are the Top 8 Alternatives to Consider</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/expert-advice-on-dealing-with-missing-advapi32dll-errors-in-windows/"><u>Expert Advice on Dealing with Missing Advapi32.dll Errors in Windows</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/exploring-the-prospects-of-an-apple-made-domestic-robot-price-and-release-forecast/"><u>Exploring the Prospects of an Apple-Made Domestic Robot – Price & Release Forecast.</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/get-ready-for-ios-18-features-release-timing-and-cost-free-access-today/"><u>Get Ready for IOS 18: Features, Release Timing, and Cost-Free Access Today</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/guide-how-to-deactivate-audio-directions-on-your-samsung-flat-screen-tv/"><u>Guide: How to Deactivate Audio Directions on Your Samsung Flat Screen TV</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/hdcp-glitches-unraveled-diagnosis-and-remedies-for-screen-issues/"><u>HDCP Glitches Unraveled: Diagnosis & Remedies for Screen Issues</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fake-gps-on-oneplus-11-5g-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>How To Fake GPS On OnePlus 11 5G For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-fix-msodll-file-not-detected-errors-on-your-computer/"><u>How to Fix 'mso.dll' File Not Detected Errors on Your Computer</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-creating-a-social-media-impact-the-art-of-using-hashtags-on-fb/"><u>In 2024, Creating a Social Media Impact  The Art of Using Hashtags on FB</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ipados-2023-update-unveiled-find-out-when-it-drops-no-charge-for-users-and-the-latest-upgrades/"><u>IPadOS 2023 Update Unveiled! Find Out When It Drops, No Charge for Users & The Latest Upgrades</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/macbook-air-multitasking-made-easy-the-ultimate-split-screen-setup/"><u>MacBook Air Multitasking Made Easy: The Ultimate Split Screen Setup</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/neo-qled-vs-oled-diving-deep-into-television-display-technologies/"><u>Neo QLED Vs. OLED: Diving Deep Into Television Display Technologies</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/pros-and-cons-making-sense-of-minecraft-realms-benefits/"><u>Pros and Cons: Making Sense of Minecraft Realms' Benefits</u></a></li>
<li><a href="https://review-topics.techidaily.com/realme-c67-5g-tutorial-bypass-lock-screen-security-password-pin-fingerprint-pattern-by-drfone-android-unlock-android-unlock/"><u>Realme C67 5G Tutorial - Bypass Lock Screen,Security Password Pin,Fingerprint,Pattern</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/reducing-dependency-on-large-scale-tech-providers-insights-from-microsoft-service-failures/"><u>Reducing Dependency on Large-Scale Tech Providers: Insights From Microsoft Service Failures</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/rescue-deleted-messages-tips-for-finding-missing-correspondence-in-gmail/"><u>Rescue Deleted Messages: Tips for Finding Missing Correspondence in Gmail</u></a></li>
<li><a href="https://win-able.techidaily.com/resolving-the-error-0x803f8001-issue-on-your-minecraft-launcher-in-windows-operating-systems/"><u>Resolving the 'Error 0X803F8001' Issue on Your Minecraft Launcher in Windows Operating Systems</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/resolving-the-wpcapsdll-file-doesnt-exist-or-cant-be-located-issue/"><u>Resolving the 'Wpcaps.dll' File Doesn't Exist or Can't Be Located Issue</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/secrets-to-featuring-on-youtube-a-comprehensive-walkthrough-for-2024/"><u>Secrets to Featuring on YouTube  A Comprehensive Walkthrough for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/solve-your-zoom-camera-problems-with-these-expert-tips/"><u>Solve Your Zoom Camera Problems with These Expert Tips</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/splurge-smarter-unveiling-top-quality-tech-treasures-at-wallet-friendly-rates/"><u>Splurge Smarter: Unveiling Top Quality Tech Treasures at Wallet-Friendly Rates</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-guide-replacing-your-laptops-missing-keys/"><u>Step-by-Step Guide: Replacing Your Laptop's Missing Keys</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-instructions-for-pairing-apple-airpods-with-the-nintendo-switch/"><u>Step-by-Step Instructions for Pairing Apple AirPods with the Nintendo Switch</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-solutions-getting-your-tiktok-back-on-track/"><u>Step-by-Step Solutions: Getting Your TikTok Back on Track</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-tutorial-on-syncing-oculus-quest-2-with-mobile-devices/"><u>Step-by-Step Tutorial on Syncing Oculus Quest 2 with Mobile Devices</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-tutorial-connecting-devices-to-your-bose-soundlink-speaker/"><u>Step-by-Step Tutorial: Connecting Devices to Your Bose SoundLink Speaker</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/top-7-recommended-alarm-clock-applications/"><u>Top 7 Recommended Alarm Clock Applications</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/transforming-reality-with-ai-unleashing-a-new-era/"><u>Transforming Reality with AI: Unleashing a New Era</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshoot-and-resolve-iphone-glitches-by-rebooting-network-preferences/"><u>Troubleshoot and Resolve iPhone Glitches by Rebooting Network Preferences</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-tips-resolving-call-issues-on-your-android-device/"><u>Troubleshooting Tips: Resolving Call Issues on Your Android Device</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ultimate-tips-for-effective-copilot-integration-within-microsoft-teams/"><u>Ultimate Tips for Effective Copilot Integration Within Microsoft Teams</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/uncover-the-8-leading-mobile-games-dominating-the-market-today/"><u>Uncover the 8 Leading Mobile Games Dominating the Market Today</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/understanding-and-utilizing-the-windows-11-battery-status-feature/"><u>Understanding and Utilizing the Windows 11 Battery Status Feature</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unlock-seamless-pc-management-with-our-favorite-15-free-uninstaller-utilities/"><u>Unlock Seamless PC Management with Our Favorite 15 Free Uninstaller Utilities</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unplugged-digital-life-innovative-ways-to-connect-without-cable-or-traditional-phone-lines/"><u>Unplugged Digital Life: Innovative Ways to Connect without Cable or Traditional Phone Lines</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722884314553-unstuck-from-windows-11-search-issues-here-are-reliable-fixes-to-try/"><u>Unstuck From Windows 11 Search Issues? Here Are Reliable Fixes to Try</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unveiling-the-future-with-google-events-hints-and-official-declarations/"><u>Unveiling the Future with Google: Events, Hints, & Official Declarations</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/wireless-mastery-how-to-pair-airpods-with-your-hewlett-packard-computer-like-a-pro/"><u>Wireless Mastery: How to Pair AirPods with Your Hewlett-Packard Computer Like a Pro</u></a></li>
</ul></div>
