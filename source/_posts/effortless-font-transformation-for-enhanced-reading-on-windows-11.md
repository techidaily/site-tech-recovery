---
title: Effortless Font Transformation for Enhanced Reading on Windows 11
date: 2024-08-19T14:59:09.250Z
updated: 2024-08-20T14:59:09.250Z
categories:
  - BestProducts
description: This Article Describes Effortless Font Transformation for Enhanced Reading on Windows 11
excerpt: This Article Describes Effortless Font Transformation for Enhanced Reading on Windows 11
thumbnail: https://www.lifewire.com/thmb/-cTvGd46z-nxjaB4BcHIRDdTv0U=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/brett-jordan-M9NVqELEtHU-unsplash-e4b45bd6fa85416fa621be97f9af0ccc.jpg
---

## Effortless Font Transformation for Enhanced Reading on Windows 11
<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
### What to Know

* Go to**Settings** \>**Personalization** \>**Fonts** to find the name of the font you want to use throughout Windows 11.
* Then, create a REG file using that name to replace the current system font. Open the REG file to change the font.
* Not all Windows fonts will change, but some do. It's easy to restore the default font if you change your mind.

 This article teaches you how to change the Windows 11 system font so that various areas of the OS will use the font type you prefer. It also covers how to undo these steps to restore the default font.

## How to Change the System Font in Windows 11

 The quickest way to change the Windows 11 font is through a Windows Registry edit, which we'll do by creating a[REG file](https://www.lifewire.com/how-to-create-edit-and-use-reg-files-2622817) .

1. Open Settings, then select**Personalization** on the left, followed by**Fonts** on the right. Another way to get there is through the Run command:**ms-settings:fonts** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
![The Personalization settings in Windows 11](https://www.lifewire.com/thmb/SJdYi81a1Rm29jJ6p7V24JP49ss=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/personalization-settings-windows-11-83afd8d0867d4d39a1b87dff59dd8fae.png)
2. Scroll down to**Available fonts** , and find and select the font you're interested in using.  
 If you don't see the font you want, you can take this time to download it. Lots of websites have free fonts, but you can also[buy fonts online](https://www.lifewire.com/buy-fonts-for-desktop-publishing-1077714) . Then, return to this area of Settings to see it. Our[How to Install Fonts in Windows 11](https://www.lifewire.com/install-fonts-in-windows-11-5192443) guide can help if you need it.
3. Locate the**Full name** line in the**Metadata** section, and write it down exactly as it's written. In our example, we recorded**Franklin Gothic Medium** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
![Full Name and Franklin Gothic Medium highlighted in Windows 11 font settings](https://www.lifewire.com/thmb/TLWCZLK0sdGg9XBIj1y4Ma1EuAA=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/001_how-to-change-the-font-in-windows-11-6827640-97099a55349a45e392459345af24caf1.jpg)
4. Open Notepad, or a[different text editor](https://www.lifewire.com/best-free-text-editors-4155819) if you prefer, and paste the following:  
 `Windows Registry Editor Version 5.00`  
`[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Fonts]`  
`"Segoe UI (TrueType)"=""`  
`"Segoe UI Bold (TrueType)"=""`  
`"Segoe UI Bold Italic (TrueType)"=""`  
`"Segoe UI Italic (TrueType)"=""`  
`"Segoe UI Light (TrueType)"=""`  
`"Segoe UI Semibold (TrueType)"=""`  
`"Segoe UI Symbol (TrueType)"=""`  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\FontSubstitutes]`  
`"Segoe UI"="Franklin Gothic Medium"`
5. In the last line of the document, replace**Franklin Gothic Medium** with the name of the font you recorded in Step 3 (keep the quotes around the name).  
![Franklin Gothic Medium highlighted in Windows Notepad with REG file contents](https://www.lifewire.com/thmb/5UM6sKcUZ5_xlc9vkHeFpUtlwpk=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/002_how-to-change-the-font-in-windows-11-6827640-babf346069c14d8caa00e4c43d7992b6.jpg)
6. If you're using Notepad, go to**File** \>**Save as** , and type a name in the**File name** box.
7. Choose**All files** from the**Save as type** menu.
8. Type**.reg** at the end of the file name. Our example reads**Franklin Gothic.reg** , but yours can be called whatever you want; just make sure it ends with that file extension.
9. Choose a folder on your computer to save the file (the Desktop folder works), and then select**Save** .  
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
![FranklinGothic.reg and Save highlighted in a Notepad document with REG file extension](https://www.lifewire.com/thmb/4p0dmSoOCDSVSqxK6o9QnPtNX1U=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/003_how-to-change-the-font-in-windows-11-6827640-9563197f19ae4d848482def07b741adc.jpg)
10. Close the text editor, and then double-click or double-tap the REG file from the folder you just saved it to.
11. Press**Yes** on the User Account Control window, then**Yes** again on the Registry Editor prompt (pictured below), and finally**OK** on the success message.  
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Yes highlighted in the Registry Editor prompt in Windows 11](https://www.lifewire.com/thmb/tViUCj2SD1eHRKNxSY2gP3-IusQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/004_how-to-change-the-font-in-windows-11-6827640-acbf618a85854ff58bb4ca6f3a0d7384.jpg)
12. [Reboot your computer](https://www.lifewire.com/how-to-reboot-a-computer-2624568) to see the font changes. The quickest method is to right-click the Start button and go to**Shut down or sign out** \>**Restart** .

## What Does Changing the System Font Do?

 Changing the computer font in Windows 11 will switch up the way text looks throughout the operating system. Desktop icon text and the links in Control Panel are a couple of examples, but it's most obvious in other areas, such as the Run dialog box.

![Windows 11 font type change in Run and Control Panel](https://www.lifewire.com/thmb/eN6m7hD9Mgh_sWhJB-Jl9QOeR2c=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/windows-11-changed-font-type-control-panel-run-desktop-365bc4a2e315498f96aa4115713f7d59.png)

 However, not every part of Windows will change to the new font. All the text within Settings, Start menu, Clock, Quick Settings, and numerous other areas aren't affected.

[Troubleshooting Installed Fonts That Won't Work](https://www.lifewire.com/cant-use-installed-fonts-1074154)

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Restore the Default Font in Windows 11

 The best way to get the original Windows 11 font back is to reverse the registry tweak that changed it in the first place. To do that, repeat the steps from above, but replace the Notepad text with different code.

 You can do this one of two ways. This first method is easiest only if you still have the original REG file:

1. Right-click the REG file from wherever you saved it during Step 9, and select**Edit in Notepad** .
2. Highlight all the text that's in there, and replace it with this:  
 `Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Fonts]`  
`"Segoe UI (TrueType)"="segoeui.ttf"`  
`"Segoe UI Black (TrueType)"="seguibl.ttf"`  
`"Segoe UI Black Italic (TrueType)"="seguibli.ttf"`  
`"Segoe UI Bold (TrueType)"="segoeuib.ttf"`  
`"Segoe UI Bold Italic (TrueType)"="segoeuiz.ttf"`  
`"Segoe UI Emoji (TrueType)"="seguiemj.ttf"`  
`"Segoe UI Historic (TrueType)"="seguihis.ttf"`  
`"Segoe UI Italic (TrueType)"="segoeuii.ttf"`  
`"Segoe UI Light (TrueType)"="segoeuil.ttf"`  
`"Segoe UI Light Italic (TrueType)"="seguili.ttf"`  
`"Segoe UI Semibold (TrueType)"="seguisb.ttf"`  
`"Segoe UI Semibold Italic (TrueType)"="seguisbi.ttf"`  
`"Segoe UI Semilight (TrueType)"="segoeuisl.ttf"`  
`"Segoe UI Semilight Italic (TrueType)"="seguisli.ttf"`  
`"Segoe UI Symbol (TrueType)"="seguisym.ttf"`  
`"Segoe MDL2 Assets (TrueType)"="segmdl2.ttf"`  
`"Segoe Print (TrueType)"="segoepr.ttf"`  
`"Segoe Print Bold (TrueType)"="segoeprb.ttf"`  
`"Segoe Script (TrueType)"="segoesc.ttf"`  
`"Segoe Script Bold (TrueType)"="segoescb.ttf"`  
`[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\WindowsNT\CurrentVersion\FontSubstitutes]`  
`"Segoe UI"=-`
3. Save the file.
4. Exit Notepad, and then open the REG file. Accept all the prompts to edit the registry.
5. If the changes don't take effect immediately (they did for us), reboot your computer.

 If you don't have the original REG file readily available to edit, just repeat the steps at the top of this page. When you get to the part about pasting the code into Notepad, use the modified code from Step 2 above, and don't make any changes to it.

## Changing Other Fonts in Windows 11

 The method outlined in this article isn't how it typically works when you want to use a new font in Windows. The directions explained above are unique for two reasons: Windows doesn't have a built-in way to change the system font, and you're changing the_system_ font, not just the font type for a single app.

 Most programs have their own font settings so you can make changes that apply to just that one program. And doing it is extremely easy because Windows 11_does_ provide a way to easily install a font that can be used by any of your software.

 For example, if you've downloaded a font you'd like to use in Microsoft Word,[install the font to your computer](https://www.lifewire.com/install-fonts-in-windows-11-5192443) , and it'll be available the next time you open Word. That's usually how it works: install the fonts to your computer to give all your programs access to them.

 You can, for instance, change the default font and size in Outlook by choosing an installed font. The same applies when you[pick a new default font for Thunderbird emails](https://www.lifewire.com/change-default-font-thunderbird-1173143) . Online apps need separate instructions since they don't typically access local fonts:[here's how to edit Gmail's default font options](https://www.lifewire.com/change-the-default-compose-font-face-and-color-in-gmail-1171898) in your browser.

 With some programs, there's a special folder in the app's installation directory that's used to load fonts for that one piece of software. This is how you[install fonts just for Photoshop](https://www.lifewire.com/installing-fonts-for-photoshop-only-1702271) .

[How to Manage Your Fonts in Windows](https://www.lifewire.com/too-many-windows-fonts-1077817)

 FAQ

* How do I change the font size on my Windows desktop icons?  
 To change the default text size in Windows 11, go to**Start** \>**Settings** \>**Accessibility** \>**Text size** . Use the slider to adjust the preview text size and select**Apply** .
* What font is used in Windows?  
 The default system font for Windows 11 is called Segoe UI. Pronounced “see-go,” this is the standard font for all Microsoft products.
* How do I change the default font in Microsoft Office?  
 You can[change the default font in Microsoft Office](https://www.lifewire.com/change-default-font-in-microsoft-office-2511891) apps by creating a template. For example, in Microsoft Word, create a new template and go to the**Home** tab, then right-click any style. Select**Modify** , then choose a font under**Formatting** . Make sure**New documents based on this template** is selected, then select**OK** .

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
<li><a href="https://fox-access.techidaily.com/new-savory-cinema-principles-of-culinary-cinematography-for-2024/"><u>[New] Savory Cinema  Principles of Culinary Cinematography for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-insiders-list-google-pixel-tone-sources/"><u>[Updated] Insider's List  Google Pixel Tone Sources</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-reviving-photo-viewer-on-win-11-methods-explained/"><u>[Updated] Reviving Photo Viewer on Win 11 - Methods Explained</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-best-websites-for-downloading-skype-ringtone/"><u>2024 Approved  Best Websites For Downloading Skype Ringtone</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-pioneering-process-open-mac-seamlessly-with-watch/"><u>2024 Approved  Pioneering Process  Open Mac Seamlessly with Watch</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-itel-p55-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Itel P55</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/all-about-dvr-technology-unveiling-digital-video-recorders-secrets/"><u>All About DVR Technology: Unveiling Digital Video Recorders' Secrets</u></a></li>
<li><a href="https://extra-resources.techidaily.com/behind-the-scenes-crafting-a-screenplay-for-2024/"><u>Behind the Scenes  Crafting a Screenplay for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/best-online-tools-and-sites-for-easy-apartment-exploration/"><u>Best Online Tools and Sites for Easy Apartment Exploration</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/can-electric-cars-endure-temperature-extremes-insights-on-ev-functionality-in-harsh-climates/"><u>Can Electric Cars Endure Temperature Extremes? Insights on EV Functionality in Harsh Climates</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/easy-methods-for-embedding-descriptive-titles-into-your-ig-stories/"><u>Easy Methods for Embedding Descriptive Titles Into Your IG Stories</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/fix-guide-how-to-address-and-solve-shell32dll-not-found-problems/"><u>Fix Guide: How to Address and Solve Shell32.dll Not Found Problems</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/from-mobile-to-tv-mastering-the-setup-of-disney-plus-streaming-through-chromecast/"><u>From Mobile to TV: Mastering the Setup of Disney + Streaming Through Chromecast</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-can-i-catch-the-regional-pokemon-without-traveling-on-infinix-hot-30i-drfone-by-drfone-virtual-android/"><u>How Can I Catch the Regional Pokémon without Traveling On Infinix Hot 30i | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-can-you-secure-an-official-verified-emblem-on-instagram/"><u>How Can You Secure an Official Verified Emblem on Instagram?</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-meta-transforms-technology-with-advanced-ai-solutions/"><u>How Meta Transforms Technology with Advanced AI Solutions</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-fix-d3d9dll-is-missing-or-not-found-errors/"><u>How to Fix D3d9.dll Is Missing or Not Found Errors</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-host-a-successful-karaoke-gathering-in-the-comfort-of-your-own-place/"><u>How to Host a Successful Karaoke Gathering in the Comfort of Your Own Place</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-project-apple-tvplus-shows-and-movies-onto-your-google-chromecast-device/"><u>How to Project Apple TV+ Shows and Movies Onto Your Google Chromecast Device</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-vivo-y100-phone-frp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Vivo Y100 Phone FRP Lock</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-looking-for-a-location-changer-on-vivo-y78-5g-look-no-further-drfone-by-drfone-virtual-android/"><u>In 2024, Looking For A Location Changer On Vivo Y78 5G? Look No Further | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-simplifying-image-editing-with-picsarts-background-tool/"><u>In 2024, Simplifying Image Editing with Picsart's Background Tool</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/is-the-entire-xbox-community-experiencing-connectivity-disruptions-or-are-there-user-specific-issues-at-play/"><u>Is the Entire Xbox Community Experiencing Connectivity Disruptions, or Are There User-Specific Issues at Play?</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mac-multi-screen-mastery-a-step-by-step-guide-to-configuring-dual-displays/"><u>Mac Multi-Screen Mastery: A Step-by-Step Guide to Configuring Dual Displays</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mac-users-guide-setting-up-two-displays-seamlessly/"><u>Mac Users Guide: Setting Up Two Displays Seamlessly</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722902703247-multiply-the-whole-number-2-by-the-denominator-3-to-get-6/"><u>Multiply the Whole Number 2 by the Denominator 3 to Get 6.</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-comprehensive-guide-to-nero-waveaudio-editor/"><u>New 2024 Approved Comprehensive Guide to Nero WaveAudio Editor</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/permanent-termination-process-disabling-and-removing-your-yahoo-mail-account/"><u>Permanent Termination Process: Disabling and Removing Your Yahoo Mail Account</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722903549667-rpcrt4dll-not-found-heres-how-you-can-repair-the-issue-easily/"><u>RPCRT4.DLL Not Found? Here's How You Can Repair the Issue Easily!</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-guide-enabling-automatic-user-authentication-on-your-windows-pc/"><u>Step-by-Step Guide: Enabling Automatic User Authentication on Your Windows PC</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/steps-for-successful-downloading-of-latest-ios-update/"><u>Steps for Successful Downloading of Latest iOS Update</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/targeting-beginners-with-the-promise-of-ease-indicates-a-friendly-approach-suitable-for-those-new-to-command-line-interfaces-across-all-windows-devices-enha59/"><u>Targeting Beginners with the Promise of Ease Indicates a Friendly Approach Suitable for Those New to Command-Line Interfaces Across All Windows Devices, Enhancing Its SEO by Targeting Common Search Queries.</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-latest-on-samsung-z-fold-4-specs-revealed-expected-price-points-and-launch-date/"><u>The Latest on Samsung Z Fold 4: Specs Revealed, Expected Price Points, and Launch Date</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-guide-to-using-snappy-driver-installer-version-113/"><u>The Ultimate Guide to Using Snappy Driver Installer Version 1.13</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/top-ranked-visual-voicemail-solutions/"><u>Top-Ranked Visual Voicemail Solutions</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-guide-clearing-up-lines-and-streaks-on-your-tv-screen-at-home/"><u>Troubleshooting Guide: Clearing Up Lines and Streaks on Your TV Screen at Home</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-techniques-for-dll-file-not-found-messages-including-msvcr71dll/"><u>Troubleshooting Techniques for 'DLL File Not Found' Messages, Including MSVCR71.dll</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ultimate-solutions-for-resolving-the-msvcrt10dll-component-missing-problem/"><u>Ultimate Solutions for Resolving the msvcrt10.dll Component Missing Problem</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/upcoming-iphone-model-17-price-predictions-arrival-date-technical-details-and-fresh-gossip-overview/"><u>Upcoming iPhone Model 17: Price Predictions, Arrival Date, Technical Details & Fresh Gossip Overview</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/-gamings-top-10-capture-card-recommendations-for-2024/"><u>Video Gaming's Top 10 Capture Card Recommendations for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-yourphoneexe-necessary-or-not-for-security/"><u>Windows' YourPhone.exe - Necessary or Not for Security?</u></a></li>
</ul></div>
