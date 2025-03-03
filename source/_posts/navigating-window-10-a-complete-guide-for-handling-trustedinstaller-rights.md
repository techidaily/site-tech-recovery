---
title: "Navigating Window 10: A Complete Guide for Handling TrustedInstaller Rights"
date: 2025-03-01T02:20:16.964Z
updated: 2025-03-02T18:13:58.670Z
categories:
  - BestProducts
description: "This Article Describes Navigating Window 10: A Complete Guide for Handling TrustedInstaller Rights"
excerpt: "This Article Describes Navigating Window 10: A Complete Guide for Handling TrustedInstaller Rights"
thumbnail: https://thmb.techidaily.com/d8f58ce885808b79b129b3a2207409d6b0df7e72b7b5c93436a642cc91c8c39d.jpg
---

## Navigating Window 10: A Complete Guide for Handling TrustedInstaller Rights
### What to Know

* Use the**TAKEOWN** and**icacls** Command Prompt commands to take ownership of the file or folder.
* Or, right-click the item and go to**Properties** \>**Security** \>**Advanced** to add yourself to the list.
* TrustedInstaller is a built-in user account that owns lots of important system files.

 This article describes two ways to deal with the message in Windows 10 about needing permission from TrustedInstaller to make changes to a file or folder.

## How to Fix the TrustedInstaller Error Using Command Prompt

 There are two really simple[Command Prompt commands](https://www.lifewire.com/list-of-command-prompt-commands-4092302) you can use to bypass the TrustedInstaller permissions prompt. Follow these steps to fix the TrustedInstaller "error" by granting your user account permission to make changes to the file or folder:

1. [Open an elevated Command Prompt](https://www.lifewire.com/how-to-open-an-elevated-command-prompt-2618088) . The quickest way there is to search for it from the Start menu, right-click the result, and choose**Run as administrator** .  
![The Run As Administrator option for the Windows 10 Command Prompt](https://www.lifewire.com/thmb/qK50_I4SdSJ98eEbO9R6yPSN1Vk=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/command-prompt-admin-windows-10-45f7ecab69a442f489eaf6a499a353d4.png)
2. Enter**TAKEOWN /F** and then type the file or folder name. Here's an example:  
 `TAKEOWN /F C:\Windows\System32\fr-FR\fms.dll.mui`
3. Press**Enter** to take control of the file. You'll see a success message if the command executed correctly.  
![The TAKEOWN /F command in Windows 10 Command Prompt](https://www.lifewire.com/thmb/nOnoS4n34cd8C2EJEDT2_rLzdhw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/takeown-command-trustsedinstaller-windows-10-267bfffb4f974a29940a0af233ef4a84.png)
4. Enter the following command (replacing our example file with your own) to immediately give your user account permission to delete or change the file or folder:  
 `icacls C:\Windows\System32\fr-FR\fms.dll.mui /grant Administrators:F /T`  
![icacls command executed in Windows 10 Command Prompt](https://www.lifewire.com/thmb/clN3CT0-H0V3QdOSRZWprDCigZ4=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/icacls-command-windows-10-7f562cffaf424cd281b4e58c68b19e25.png)

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
![The Advanced Security Settings for a Windows 10 folder](https://www.lifewire.com/thmb/fEVYPGbUtSiGdO8kZg1RZd6gtIE=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/add-button-advanced-security-settings-3ffcde5bc8b942278219bbd9b4663921.png)
7. Choose**Select a principal** and then type your username in the box.
8. Press**Check Names** \>**OK** .  
![A user account listed in the Select User or Group box for a Windows 10 folder](https://www.lifewire.com/thmb/a8Ie_eyPviEwOjytgb9HHofaQgc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/select-user-group-windows-10-security-b2ffe7d116f2424e845a612090d4e932.png)
9. Check the box next to**Full control** , then select**OK** .  
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
<li><a href="https://extra-guidance.techidaily.com/new-perfect-synchronization-enhancing-audio-visual-with-subtitles-in-wmp/"><u>[New] Perfect Synchronization Enhancing Audio-Visual with Subtitles in WMP</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-how-to-assemble-a-personalized-youtube-music-list/"><u>[Updated] In 2024, How to Assemble a Personalized YouTube Music List</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-making-online-gaming-more-intimate-via-xbox-zoom/"><u>[Updated] Making Online Gaming More Intimate via Xbox Zoom</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-what-does-it-take-to-promote-a-video-on-youtub-in-2024/"><u>[Updated] What Does It Take to Promote a Video on YouTub, In 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/before-buying-your-next-dash-cam-here-are-the-9-things-you-need-to-know/"><u>Before Buying Your Next Dash Cam - Here Are the 9 Things You Need To Know</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/easily-unlock-your-honor-90-lite-device-sim-by-drfone-android/"><u>Easily Unlock Your Honor 90 Lite Device SIM</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/expert-tips-for-fixing-unwanted-grid-patterns-on-your-flat-screen-tv/"><u>Expert Tips for Fixing Unwanted Grid Patterns on Your Flat Screen TV</u></a></li>
<li><a href="https://solve-lab.techidaily.com/exploring-the-consequences-of-maos-great-leap-forward-on-chinese-society-an-in-depth-analysis-by-yl-computing/"><u>Exploring the Consequences of Mao's Great Leap Forward on Chinese Society: An In-Depth Analysis by YL Computing</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-fix-shell32dll-not-found-or-missing-errors/"><u>How to Fix Shell32.dll Not Found or Missing Errors</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-use-facebook-image-search-to-find-someone/"><u>How to Use Facebook Image Search to Find Someone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-stream-laptop-display-onto-hdtv-with-simple-hdmi-linkup-methods/"><u>How To: Stream Laptop Display Onto HDTV With Simple HDMI Linkup Methods</u></a></li>
<li><a href="https://some-approaches.techidaily.com/i-migliori-tre-player-dvd-free-per-windows-11-scopri-come-masterizza-tutti-i-tuoi-film-in-dvd/"><u>I Migliori Tre Player DVD Free per Windows 11: Scopri Come Masterizza Tutti I Tuoi Film in DVD</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-crack-the-code-of-content-discovery-on-facebook/"><u>In 2024, Crack the Code of Content Discovery on Facebook</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/restore-a-shut-down-or-disabled-instagram-profile-effectively/"><u>Restore a Shut Down or Disabled Instagram Profile Effectively</u></a></li>
<li><a href="https://some-tips.techidaily.com/seamless-virtual-private-network-setup-for-pixel-users-leveraging-the-free-google-one-vpn-feature-detailed-tutorial/"><u>Seamless Virtual Private Network Setup for Pixel Users: Leveraging the Free Google One VPN Feature - Detailed Tutorial</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-repair-restoring-functionality-to-stuck-disc-readers-on-pcs/"><u>Step-by-Step Repair: Restoring Functionality to Stuck Disc Readers on PCs</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-strategies-unlocking-success-in-royal-match/"><u>Step-by-Step Strategies: Unlocking Success in 'Royal Match'</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-tips-for-the-elusive-msvcr7ec-runtime-library/"><u>Troubleshooting Tips for the Elusive MSVCR7e/C Runtime Library</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/oint-visionaries-capturing-the-essence-with-3-viewpoint-strategies-in-reactions/"><u>Viewpoint Visionaries Capturing the Essence with 3 Viewpoint Strategies in Reactions</u></a></li>
</ul></div>

