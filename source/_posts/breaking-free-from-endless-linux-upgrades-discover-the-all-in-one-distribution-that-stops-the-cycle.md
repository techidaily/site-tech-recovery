---
title: Breaking Free From Endless Linux Upgrades? Discover the All-in-One Distribution That Stops the Cycle!
date: 2024-08-27 15:12:24
updated: 2024-08-29 10:54:19
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/laptop-with-the-blendos-screen.jpg
---

## Breaking Free From Endless Linux Upgrades? Discover the All-in-One Distribution That Stops the Cycle!

### Quick Links

* [What’s So Special About blendOS Anyway?](https://ai-topics.techidaily.com/a-detailed-review-of-murfai-ai-text-to-speech-tool-for-2024/)
* [The Installation Was Simple](https://youtube-docs.techidaily.com/rom-novice-to-pro-youtube-shorts-guide-for-2024/)
* [Managing Software and Updates](https://tech-recovery.techidaily.com/ultimate-guide-resolving-d3dx92/)
* [Android App Support Looks Promising](https://fox-info.techidaily.com/new-hp-envy-27-ultra-hd-usb-c-display-analysis-for-2024/)
* [A Recipe for Disaster?](https://youtube-tips.techidaily.com/ed-rewind-and-repeat-mastering-youtube-inversion-for-2024/)
* [blendOS Is for You if…](https://snapchat-videos.techidaily.com/new-from-novice-to-pro-a-tactical-guide-to-snapchat-marketing-for-2024/)

 As a distro-hopper, I'm always on the lookout for new distros to try. With how things work in the Linux world, there's a new shiny distro coming out every once in a while offering new gimmicks.

 blendOS has gained quite some reputation for its all-in-one feature. But is it good enough to make you stop distro-hopping?

##  What’s So Special About blendOS Anyway?

 blendOS is an [immutable Linux distribution](https://bypass-frp.techidaily.com/in-2024-about-vivo-y100-5g-frp-bypass-by-drfone-android/) based on [Arch Linux](https://fox-access.techidaily.com/updated-fiendish-film-pause-techniques-for-2024/) with a rolling release model. It comes from Rudra Saraswat, the person behind many projects, including Ubuntu Unity, Ubuntu Web, and UbuntuEd.

 As of v4 (which I'm covering in this review), blendOS is fully declarative. That means you use a configuration file (system.yaml) for installing custom packages, kernels, drivers, and desktop environments instead of using commands and giving step-by-step instructions. In other words, the system.yaml file lets you define your desired state of the system.

 blendOS allows you to install packages from several Linux distributions including Ubuntu, Fedora, Debian, CentOS Stream, and even Android. Since it's an immutable distro, you can't install packages on the system in the traditional way like on other distros. Instead, it uses Podman containers to install and run applications. That's why you can have multiple Linux distros as containers and gain access to their respective package managers.

 The distro also has its own package manager called bpkg. It allows you to use package managers from different containers you set up in the system. It doesn't come with blendOS by default and requires installation. bpkg is also configurable using a YAML file. You also have out-of-the-box support for [Flatpaks](https://extra-support.techidaily.com/in-2024-marvelous-monitors-top-10-macbooks-with-4k-resolution/), Arch Linux, and [AUR](https://unlock-android.techidaily.com/in-2024-the-ultimate-guide-to-xiaomi-redmi-k70-pro-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/) packages.

 blendOS offers a large pool of desktop environments. You have GNOME, KDE, MATE, XFCE, Cinnamon, and LXQt. However, you can also create your own track to make it support other desktops or window managers. The default installation comes with GNOME.

##  The Installation Was Simple

![blendOS installation screen welcoming the user](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/1-10.png) 

 blendOS is based on Arch Linux. I've never used Arch before, but I'm aware of the dreadful stories regarding [installing Arch Linux](https://bypass-frp.techidaily.com/how-to-bypass-frp-from-infinix-smart-7-hd-by-drfone-android/) on a device. Luckily, many Arch-based distros can be [installed using a GUI installer](https://ai-vdieo-software.techidaily.com/2024-approved-from-minutes-to-seconds-mastering-time-lapse-video-production/).

 blendOS uses the Jade GUI installer. The process was straightforward, like installing other [popular Linux distros](https://sim-unlock.techidaily.com/in-2024-sim-unlock-honor-80-pro-straight-screen-edition-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/). You choose a few settings, such as language, region, and disk partitioning. The installer handles the rest.

![blendOS being installed on a system](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/4-4.png) 

 Before you start installing blendOS, make sure you allocate enough disk space (at least 20GB.) Otherwise, the installation may fail. When you reboot after installing blendOS, remember to boot from the hard disk instead of the USB stick (if you're using one). If you're using virtualization software such as [VirtualBox](https://unlock-android.techidaily.com/in-2024-rootjunky-apk-to-bypass-google-frp-lock-for-infinix-hot-30-5g-by-drfone-android/), change the boot order and put the hard disk at the top.

##  Managing Software and Updates

 blendOS uses containerization technology for managing software. You set up containers for different distributions inside blendOS and then use software from within those containers. You will find a blendOS settings menu from which you can create containers.

![Various Linux containers are listed in blendOS](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/blendos-containers.png) 

 You give a suitable name for a container, choose which distro to use, and press the plus button to create a container. You'll find your containers listed in the same menu. Upon launching the container, you'll see a new terminal window with the name you gave to the container.

![Debian container running in blendOS](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/debian-container-running-in-blendos.png) 

 You may think that to install and update software, you have to open a container for a distro. However, that's not necessary. With a special syntax, you can install and run apps directly from the base blendOS system. All you have to do is put a period (.) sign after the package name and then the name of the distro. Suppose I want to install VLC media player on the Debian container. For that, I'd run:

sudo apt.debian install vlc

![Installing VLC on blendOS via the Debian container](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/installing-vlc-on-blendos.png) 

 To launch the app, I'd run:

vlc.debian

![Launching VLC on blendOS via the Debian container](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/launching-vlc-on-blendos.png) 

 blendOS has a feature called Associations that allows you to connect an app with a particular distribution. Let's say, you always want to use the GIMP installed in the Ubuntu container. You can associate GIMP's package with Ubuntu so that you don't have to add prefixes. You can manage associations from the system settings.

![Associating GIMP with the Ubuntu container in blendOS](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/associating-gimp-with-the-ubuntu-container-in-blendos.png) 

 In my case, to launch GIMP, I only need to run **gimp** on the command line without any prefixes.

![GIMP running on blendOS](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/launching-gimp-on-blendos-using-associations.png) 

 But not everyone likes to remember commands for launching apps. You don't have to. Any app you install on any container will also appear in the apps menu. You can go to the apps menu and launch the app from the GUI.

![Applications from different Linux containers in the same place on blendOS](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/applications-from-different-linux-containers-in-the-same-place-on-blendos.png) 

 If you've downloaded a package from the internet, you can install it on your system directly. All you have to do is double-click on the package and the blendOS package installer will open with the option to choose a container.

![GUI package installer in blendOS](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/gui-package-installer-in-blendos.png) 

 There's also a dedicated GUI software store in blendOS similar to the one you get on Ubuntu. You can search and install software from there as well. The software in the store comes from Flathub.

![An instance of the blendOS software store](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/blendos-software-store.png) 

 For system updates, blendOS offers a utility tool called "akshara." If you'd like to update the system, simply run:

sudo akshara update

![Updating blendOS using the akshara utility](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/updating-blendos.png) 

 You can also find the update option from the system settings if you prefer using the GUI.

![System Settings menu displaying the option to update blendOS](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/update-blendos-from-the-system-settings-menu.png) 

 This update also covers any system changes you included in the system.yaml file. So after updating, you need to reboot the system.

 You can also update individual containers. For that, open a container and run the command to update that distro. For Debian, you run **sudo apt update** and for Fedora, you run **sudo dnf update** in the container's command line.

##  Android App Support Looks Promising

![Android apps initialization in blendOS](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/android-apps-initialization-in-blendos.png) 

 blendOS allows you to install Android apps directly on the system through [Waydroid](https://some-techniques.techidaily.com/ideal-shade-modifier-software-for-2024/). It lets you install F-Droid and Aurora Store for accessing and installing Android apps. You'll first have to initialize Waydroid from the system settings. After the initialization, you can install the app stores.

 You can install and set up Waydroid in other Linux distributions too. However, blendOS removes the installation hassle and makes it a part of the initial setup.

 When using Android apps, you'll feel like you're natively running them on your system thanks to the abstraction. However, as I'm writing this, the Android experience on blendOS was subpar at best. The idea is great and needs better implementation. More on this in a bit.

##  A Recipe for Disaster?

 The very first concern anyone can raise about blendOS is the mixture of different distributions and package managers. Since you're using different package managers from different distributions to install software on the same system, won't that create package conflicts and dependency errors?

 I'll have to say that blendOS has implemented this pretty well. I've used Debian, Ubuntu, Fedora, and Arch containers, and installed software on them. I haven't faced any problems so far.

 Associations is a neat feature that enables you to forget which package is from which container. If we're talking about installing the same package from different containers, I don't see any practical reason for it. So no need to worry about that either.

 So is blendOS fault-proof? Not quite. I faced some challenges when using this distro. This made me think about whether the features I'm getting are worth sacrificing the quality of life features in other distros.

 Since you're using containers for running entire operating systems inside blendOS, it may consume more system resources than traditional distros. The performance also doesn't feel on the same level as using applications natively on a distro. So expect some lags here and there.

 To be fair here, blendOS v4 has been released recently. So you should expect bugs, strange behaviors, and the system breaking more often. For instance, I faced an infinite loop during the installation process. Another problem was that, after booting, the system went onto the same installation screen instead of entering the installed blendOS system.

 Some users reported another problem during installation where the process gets stuck while retrieving packages and keeps repeating. With small tweaks, you can fix these problems though.

 Unlike many other large distributions, you shouldn't expect a "just works" experience from blendOS. I was getting a lot of hangs, unresponsive screens, black screens, and blank windows while testing the distro. There were instances where I had to reboot because the screen got stuck forever. This was more visible when I tried to do multitasking.

 The Android support also felt quite buggy. The initialization was straightforward. But then, I tried to launch both F-Droid and Aurora Store and both showed a white window before finally crashing.

![An instance of blendOS white screen problem](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/blendos-white-screen-problem.png) 

 Initializing Waydroid automatically installs some Android utility apps such as a calculator, file manager, calendar, etc. However, I was unable to open any of them. I'm not sure whether this was a Waydroid or blendOS problem.

 Another issue is when you reboot, you'll need to install F-Droid and Aurora Store again. You won't find them in the applications menu. If you open system settings, you'll see that you're asked to install them instead of giving the option to directly open them.

 The white screen problem isn't limited to Waydroid. When I woke the system up from sleep and logged back in, the windows that were open before going to sleep became white and blank.

##  blendOS Is for You if…

 blendOS is still quite new. The latest version v4 was just released. As with any distro, it will take some time to reach a more stable and usable condition. That being said, it's certainly not a daily driver kind of distro yet.

 Firstly, you'll need good hardware to even run it properly. blendOS recommends a minimum of 4GB of RAM and 25GB of storage space. But you'll have a sluggish experience with that. Running multiple apps from multiple containers will eat up a good amount of RAM.

 Not to mention, the more containers you download, the faster you'll run out of space. I allocated 30GB for blendOS and almost ran out of space after installing 3-4 large apps (LibreOffice, GIMP) from different distros.

 Secondly, it's not as polished as other popular distros. You can do basic tasks without much hassle. But power users and multitaskers will feel disappointed. There's also a learning curve even if you're an experienced Linux user. Not all functionalities work all the time and the best form of support is their Discord server. Other than that, you won't find much help regarding the distro.

 Now, if you love Arch's rolling release, need extra security like blendOS's immutability, or prefer atomic updates for a more stable experience, then blendOS might be a favorable choice. Whether having multiple distros in one is a good idea or not will vary from person to person. I'm all for it as long as it doesn't create extra complexities and dependency issues, which I think blendOS handles really well.

 If that's your thing, go for it. Another big plus for blendOS is its declarative nature. You can customize the system so easily just by editing a YAML file and doing a quick reboot.

---

 Although blendOS is a viable fix for distro-hopping, I'm still on the fence about recommending it to others. It's not everyone's cup of tea. But even putting that aside, there are several areas to improve. For now, we need more robust Android app support. The documentation is okay but needs to be more comprehensive. Support is limited for now, but hopefully, that changes as more people adopt it.

 With all that said, I look forward to daily driving blendOS once it becomes more mature.

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
