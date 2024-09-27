---
title: How to Safely Test macOS Sequoia on Your Mac without Compromising Security
date: 2024-08-30T16:13:37.517Z
updated: 2024-08-31T16:13:37.517Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/a-macbook-with-macos-15-coming-out-of-the-screen.jpg
---

## How to Safely Test macOS Sequoia on Your Mac without Compromising Security

### Quick Links

* [Install macOS Sequoia on a Separate Partition](https://mondly-stories.techidaily.com/a-complete-collection-of-top-16-german-gratefulness-statements/)
* [What About Installing macOS 15 Beta in a Virtual Machine?](https://fox-info.techidaily.com/horizon-captured-which-camera-takes-the-lead-in-2024/)

 Wondering what the next version of macOS is like? Try it out for yourself without risking your Mac by either installing it on a separate partition or using a virtual machine. Here’s how you can try both methods.

##  Install macOS Sequoia on a Separate Partition

 If you have the disk space to spare and you’re comfortable [playing around in Disk Utility](https://android-location-track.techidaily.com/in-2024-how-to-intercept-text-messages-on-vivo-y100i-power-5g-drfone-by-drfone-virtual-android/), you can install a pre-release version of macOS on a separate partition. You can retain your stable macOS installation on one partition, then reboot your Mac to try out the beta version.

 Your data won’t be affected, and you won’t even need to “sacrifice” disk space since macOS can take any data it needs from the main drive.

 It’s never a bad idea to [create a Time Machine backup](https://fox-hovers.techidaily.com/updated-2024-approved-navigating-the-path-free-and-safe-vlc-installer-for-macos-users/) before you start playing around with macOS partitions, just in case. Back up your Mac now, before you begin, so that you can restore your data if something goes wrong.

###  Download the macOS Sequoia Installer

 The first thing you’ll need to do is download the installer for the beta version of macOS that you want to download. The easiest way to do this is to use Terminal, which allows you to specify which version of macOS to download and places it ready in your Applications folder.

 You should do this using the same Mac on which you’re installing the beta, since Apple will detect your Mac and show appropriate releases.

 First, head to System Settings > General > Software Update then under “Beta Updates” choose the version of macOS that you want to install. We recommend the public beta, since developer betas can be even more unstable.

![Enable macOS beta updates.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/screenshot-2024-08-16-at-09-18-17.png) 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Now open Terminal and run the following command:

softwareupdate --list-full-installers

 Wait a moment and your Mac will fetch a list of relevant installers.

![Download macOS installers using Terminal.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/screenshot-2024-08-16-at-12-15-13.png) 

 In the screenshot above we can see that 15.0 is the latest version. Now grab that specific installer using the following command:

softwareupdate --fetch-full-installer --full-installer-version 15.0

 Remember to replace the version number with the relevant version. Now wait for the installer to download. It’s around 15GB, so it may take a while.

 If the "list-full-installers" command isn’t working after you enabled the Beta flag in System Settings, restart your Mac and try again. If it's still not working, turn off beta participation and make sure your Mac is updated to the latest stable version of macOS and then switch beta participation back on and try again.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  Create a New Partition for macOS Sequoia

 Now open Disk Utility and with your internal startup volume selected (probably labeled “Macintosh HD”), click the plus “+” icon near Volume. Give your new volume a name you can recognize, make sure “APFS” is selected, and don’t worry about specifying a size.

![Creating a new volume in "Macintosh HD."](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/screenshot-2024-08-16-at-14-50-04.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
 Click “Add” and your volume will be created. You can now close Disk Utility, you’re ready to install the macOS beta.

![Creating a partition for macOS Sequoia installation.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/screenshot-2024-08-16-at-14-55-38.png) 

###  Install macOS Sequoia on Your New Volume

 By now, you should hopefully have a new item in your Applications folder called “Install macOS 15 beta” (if you don’t, check the progress in that Terminal window).

![Running the macOS Sequoia beta installer.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/screenshot-2024-08-16-at-14-51-57.png) 

 All that’s left to do is run this file and start the installation. Click “Continue” and on the next screen you’ll be invited to select an installation location. Click “Show All Disks” and select the volume you created earlier.

![Installing macOS Sequoia on a separate volume.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/screenshot-2024-08-16-at-14-56-49.png) 

 It’s worth double-checking to make sure that your main partition isn’t selected here, or you’ll overwrite your existing stable version of macOS.

 Hit “Continue” and choose whether to copy account settings. Finally, hit “Install” and enter a password if prompted. The macOS beta will be installed on the relevant partition.

![Final step of installing the macOS beta.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/screenshot-2024-08-16-at-14-57-35.png) 

<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 When the installation is finished, your Mac will restart and you’ll be invited to set up the new version of macOS [as if you were using a brand-new Mac](https://tech-recovery.techidaily.com/how-can-you-legally-download-netflix-titles-for-offline-viewing-on-a-laptop/).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
###  Switching Between Stable and Beta macOS Versions

 To pick which version of macOS you want to boot into, turn off your Mac using the Apple > Shut Down option.

 On an Apple Silicon Mac (with an M1 chip or later) press and hold the Power button (Touch ID sensor) to start your Mac, then choose the relevant partition. On an Intel Mac, press and hold Option then press the Power button (Touch ID sensor) and select the relevant partition.

 You’ll need to do this each time you want to swap between beta and stable macOS versions.

###  Deleting the macOS Beta

 To delete the beta, head back to Disk Utility from your stable version of macOS (in this case, macOS 14) and highlight the "macOS Sequoia" partition you created. Click on the minus "–" button next to "Volumes" and confirm by clicking "Delete."

![Deleting a macOS 15 volume.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/screenshot-2024-08-16-at-15-00-57.png) 

<!-- affiliate ads begin -->
<span id="1793213">
					<video width="1080" height="1620" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:1080px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  What About Installing macOS 15 Beta in a Virtual Machine?

 This is supposed to be the part of the guide where I tell you how installing macOS 15 in a virtual machine is the easiest, least risky option. That’s technically true, but getting any of the macOS 15 betas working in a virtual machine isn’t necessarily straightforward.

 It should be a simple case of downloading the relevant IPSW from [Apple’s Developer website](https://developer.apple.com/download/) (which is now free or using a [free IPSW downloader](https://github.com/blacktop/ipsw) to swipe the relevant IPSW file), creating a [virtual machine in free tools like UTM](https://some-approaches.techidaily.com/transformative-approaches-to-engaging-with-online-video-reviews-for-2024/) and Virtual Buddy or a [paid tool like Parallels Desktop](https://screen-mirror.techidaily.com/in-2024-how-to-cast-oneplus-11r-screen-to-pc-using-wifi-drfone-by-drfone-android/), and you’re off to the races.

 After trying for several hours on a fully updated macOS 14 host, I was unable to create a working virtual machine for macOS 15\. This included installing the Xcode 16 beta, extracting and installing mobile support installers from the app directory, and even installing device support packages from Apple Developer.

 In UTM and Virtual Buddy (both of which are based on QEMU), I got a generic “installation failed” message. Parallels Desktop managed to create a virtual machine that terminated during the installation.

![An unhelpful error message in UTM for Mac.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/screenshot-2024-08-16-at-15-00-09.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
 There’s plenty of evidence online of people managing to get these methods working, and others failing miserably (as I did). This highlights the nature of pre-release software, where a few changes on Apple’s side can seemingly break compatibility with even paid virtualization solutions.

 And beta software is fleeting. While it’s likely that the final release of macOS 15 will work just fine in software like UTM and Parallels (just as macOS 14 does), the betas might never work.

 By the time you read this, there could be another beta out that fixes these issues and works fine. If you’re willing to give it a shot, we’ve included instructions below that might help.

###  Install macOS 15 Sequoia With UTM

**Download the Latest macOS and Xcode Beta** 

 To use a virtual machine like UTM, you’ll need to restore an IPSW image. These are provided by Apple with each beta release, and you can download them from [Apple’s Developer website](https://developer.apple.com/download/) (which is now free). Alternatively, you can use a [free IPSW downloader](https://github.com/blacktop/ipsw) to download the relevant IPSW file.

 You’ll also need to install “Device Support for macOS 15 beta” from the Apple Developer website.

**Create a Virtual Machine and Install macOS** 

 Once you’ve grabbed the latest beta version of macOS, it’s time to boot up UTM. Get started by clicking “Create a New Virtual Machine” and then choose “Virtualize” in the window that pops up.

 From here, select “macOS 12+” after which you’ll need to locate the IPSW file you downloaded using the “Browse” button.

 Now it’s time to configure your machine. Apple recommends at least 8GB RAM, but you can get away with 4GB if you’re tight on resources (remember this will be shared with the host machine). Next, specify four CPU cores, and nominate 80GB of disk space.

 Finally, give your machine a name and click “Save.” With your machine selected, click the “Play” button to get started. UTM will ask you if you want to install macOS, click “OK” and wait.

 read more

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  Install macOS 15 Sequoia With Parallels Desktop

**Download the Latest macOS Beta IPSW** 

 To install macOS with Parallels Desktop, you’ll an IPSW image. Grab the latest version from [Apple’s Developer website](https://developer.apple.com/download/) (which is now free) or use a [free IPSW downloader](https://github.com/blacktop/ipsw) to download the relevant IPSW file.

 You’ll also need to install “Device Support for macOS 15 beta” from the Apple Developer website.

**Create a Virtual Machine and Install macOS** 

 Installing macOS in Parallels Desktop is really easy. First, open the app and click the plus “+” icon in Control Center. Choose “Install Windows, Linux, macOS from an image file” then click “Continue.”

 Drag your .IPSW file into the window, or click “select a file…” to locate it on your drive followed by “Continue.”

 Finally, click “Create” and wait for the installation process to complete.

 read more

---

 If you’d rather just find out what’s coming to your Mac without installing anything first, check out [our full roundup of the changes coming in macOS 15](https://youtube-tips.techidaily.com/approved-youtube-editing-essentials-the-ultimate-guide-post-upload-refinements/).

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


