---
title: Effortless Ways to Search for Contacts on Facebook – Top 6 Methods
date: 2024-09-09T20:33:59.265Z
updated: 2024-09-16T00:23:38.790Z
categories:
  - BestProducts
description: This Article Describes Effortless Ways to Search for Contacts on Facebook – Top 6 Methods
excerpt: This Article Describes Effortless Ways to Search for Contacts on Facebook – Top 6 Methods
thumbnail: https://www.lifewire.com/thmb/hxWpzKcN-BiBu9bvDiyxKnNO4Us=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/iStock-486099507-59bc12be0d327a0011dbf4b2-5be34b7446e0fb0026758ba5.jpg
---

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Mac Users Rejoice: How to Reset Your DNS Records Effortlessly
### What to Know

* You can delete the DNS cache through Terminal. Press**Command** +**Space** to search for it.
* Enter this flush DNS command: **sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder**
* El Capitan and older Mac OS X systems use different commands to clear DNS.

 This article explains how to delete the[DNS cache](https://www.lifewire.com/what-is-a-dns-cache-817514) on a Mac.

## How to Use the macOS Flush DNS Command

 If you’re experiencing internet connectivity issues, you may be able to fix them by resetting the[DNS](https://www.lifewire.com/what-is-dns-domain-name-system-2625855) cache with a[Terminal command](https://www.lifewire.com/mac-terminal-commands-4774997) . It should only take a few moments.  

1. [Open Terminal](https://www.lifewire.com/macos-terminal-4774149) . One quick way is to press**Command** +**Space** to launch[Spotlight](https://www.lifewire.com/use-spotlight-mac-4586951) . Then, type**Terminal** and select it from the results.  
![Terminal highlighted in Spotlight on a Mac.](https://www.lifewire.com/thmb/QGngs7Naa2bQVtWQWVaRG0K34yc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Terminal-6e4ba7528a4c4220a28542f84f214676.jpg)  
 You can also access Terminal by navigating to**Go** \>**Utilities** \>**Terminal** .
2. Type (or[copy and paste](https://www.lifewire.com/cut-copy-paste-on-mac-4427671) ) this command into Terminal and then press**Enter** :  
 `sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder`  
![Command highlighted in Terminal window](https://www.lifewire.com/thmb/S2U8vSx5U_PgZI2ZZR_uTWdGHcw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Command-e05651de1b2f44e7b99903d8f00910f5.jpg)  
 This command only works in[macOS](https://www.lifewire.com/what-is-macos-4691239) 10.12 Sierra and newer. If you have an older version, check the next section for the correct command.
3. Type your password and then press**return** . The DNS cache will be reset immediately, but there will be no message to that effect. When a new line appears, it indicates the command has been carried out.  
![Entering a password in Terminal on a Mac.](https://www.lifewire.com/thmb/hvFn07N8xnjZ9XJQvgMitPvCTVQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Password-902f4015f672459598066969c7900b2f.jpg)  
The password will not appear in Terminal as you type it.

### How to Flush DNS on Mac OS X

 The Mac OS X flush DNS command is different than the one used in modern versions of the operating system. Open Terminal and then enter the command that corresponds with your version:

* **El Capitan** : sudo killall -HUP mDNSResponder
* **Yosemite** : sudo discoveryutil udnsflushcaches
* **Lion, Mountain Lion, and Mavericks** : sudo killall -HUP mDNSResponder
* **Snow Leopard** : sudo dscacheutil -flushcache
* **Leopard** : sudo lookupd -flushcache
* **Tiger** : lookupd -flushcache

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130889/7443" target="_top" id="2130889">
  <img src="//a.impactradius-go.com/display-ad/7443-2130889" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130889/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-amplifying-your-impact-voice-customization-in-instagram-media/"><u>[New] In 2024, Amplifying Your Impact Voice Customization in Instagram Media</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-innovating-with-structured-content-on-youtube/"><u>[New] Innovating with Structured Content on YouTube</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-unlocking-social-connections-facetime-tutorials-for-android/"><u>[Updated] 2024 Approved Unlocking Social Connections Facetime Tutorials for Android</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-best-youtube-livestreaming-screen-recorders-for-2024/"><u>[Updated] Best YouTube Livestreaming Screen Recorders for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/7-ways-to-unlock-a-locked-xiaomi-redmi-k70-pro-phone-by-drfone-android/"><u>7 Ways to Unlock a Locked Xiaomi Redmi K70 Pro Phone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/complete-guide-requesting-your-game-credit-back-from-steam/"><u>Complete Guide: Requesting Your Game Credit Back From Steam</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/discover-the-finest-in-ceiling-sound-technology/"><u>Discover the Finest In-Ceiling Sound Technology</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/discover-the-ultimate-list-of-online-destinations-with-eng-subtitles-for-popular-k-variety-programs/"><u>Discover the Ultimate List of Online Destinations with Eng Subtitles for Popular K-Variety Programs</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/eight-tips-every-shopper-needs-to-know-before-committing-to-a-new-desktop-pc/"><u>Eight Tips Every Shopper Needs to Know Before Committing to a New Desktop PC</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-ultimate-guide-80s-vhs-tricks-for-dynamic-edits/"><u>In 2024, Ultimate Guide 80'S VHS Tricks for Dynamic Edits</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/navigating-through-client-and-server-vpn-hurdles-demystifying-the-800-error-fixes/"><u>Navigating Through Client and Server VPN Hurdles: Demystifying the 800 Error Fixes</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/online-viewing-tips-for-catching-all-the-action-at-samsungs-next-unveiling/"><u>Online Viewing Tips for Catching All the Action at Samsung's Next Unveiling!</u></a></li>
</ul></div>

